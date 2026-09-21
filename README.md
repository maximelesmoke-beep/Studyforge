# StudyForge v3 FINAL
Cette archive contient la PWA, le moteur pédagogique local, un catalogue de départ et un backend prêt à connecter à une IA.

## Ce qui est déjà construit
- PWA Android installable
- profil/niveau/objectif/temps
- cours, exercices, quiz XP, secrets
- progression par compétence
- modes Araphax
- focus 25 min
- catalogue multi-disciplines
- backend Node/Express + adaptateur OpenAI côté serveur

## Ce qui doit encore être fait pour une vraie publication
1. Héberger `app/` en HTTPS.
2. Déployer `server/` en HTTPS et mettre la clé IA dans `.env`, jamais dans le frontend.
3. Relier l'URL du backend dans le frontend.
4. Tester sur Android.
5. Transformer la PWA en Android App Bundle (.aab) pour Google Play.
6. Créer le compte Play Console, remplir fiche, confidentialité, Data safety et contenu.
7. Faire le test requis par Google si le compte personnel y est soumis.
8. Publier en production après validation.

## Important
Le catalogue fourni est un socle de départ, pas l'intégralité de tous les programmes scolaires du monde. L'architecture est prévue pour ajouter des chapitres, compétences et exercices sans refaire l'application.

## Sécurité
La clé IA doit rester côté serveur. Ne jamais la placer dans `app/app.js`.
