# Site romantique

## Installation
1. Installe Node.js.
2. Ouvre un terminal dans ce dossier.
3. Lance `npm install`.
4. Définis un vrai mot de passe admin :
   - Windows PowerShell : `$env:ADMIN_PASSWORD="ton-mot-de-passe"`
   - macOS/Linux : `export ADMIN_PASSWORD="ton-mot-de-passe"`
5. Lance `npm start`.
6. Ouvre http://localhost:3000
7. Ton espace privé est sur http://localhost:3000/admin

## Mise en ligne
Pour que d'autres personnes puissent visiter le site, il faut déployer le projet sur un hébergeur qui accepte Node.js.
Ne mets jamais ton vrai mot de passe dans le code.

## Vie privée
Le site enregistre uniquement des statistiques techniques minimales (date, type d'appareil et un identifiant technique haché utilisé pour estimer les navigateurs uniques). Il n'affiche pas de liste de personnes ni leur identité.
