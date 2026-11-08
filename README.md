# LOC-NANDO — démarrage technique 0.1

Ce dossier contient une première base d'interface web responsive construite avec React et Vite.

## Ce qui fonctionne déjà dans cette maquette
- Navigation entre les sections Accueil, Apprendre, Documents, Révisions, Objectifs et Paramètres.
- Sélection du niveau d'étude et du domaine.
- Sélection locale de fichiers PDF et images (aucun envoi au serveur à ce stade).
- Bascule visuelle du thème clair/sombre.
- Mise en page adaptée aux écrans mobiles.

## Ce qui n'est PAS encore connecté
- Création de compte et authentification.
- Base de données et stockage sécurisé.
- Traitement réel des PDF et images.
- Fonctions d'intelligence artificielle.
- Génération effective de quiz, corrections, podcasts et cartes mémoire.
- Synchronisation et fonctionnement hors connexion complet.
- Tests de sécurité et déploiement de production.

Ne jamais placer une clé secrète d'API dans le code du navigateur. Les secrets devront rester côté serveur.

## Lancer le projet (ordinateur)
1. Installer Node.js (version LTS).
2. Ouvrir un terminal dans ce dossier.
3. Exécuter `npm install`.
4. Exécuter `npm run dev`.
5. Pour vérifier la version de production : `npm run build`.

## Étapes suivantes
1. Ajouter une authentification et une base de données (par exemple Supabase).
2. Créer une API serveur sécurisée.
3. Ajouter le stockage des documents et le traitement PDF/OCR.
4. Connecter les fonctions IA via le serveur.
5. Ajouter une stratégie hors connexion et la synchronisation.
6. Tester chaque parcours avant publication.

Cette base est un point de départ, pas une application complète prête à publier.
