# Application Triple saut · LeoPhysio (APK)

## Obtenir l'APK (10 minutes, gratuit, sans Android Studio)
1. Créez un compte sur github.com, puis un nouveau dépôt (bouton « New »), nommé par exemple `leophysio-triple-saut`.
2. Dans le dépôt : « Add file » > « Upload files ». Glissez TOUT le contenu de ce dossier
   (y compris le dossier `.github`, `www`, `assets`), puis « Commit changes ».
   Astuce : si `.github` n'apparaît pas, envoyez le dossier depuis un ordinateur ou utilisez GitHub Desktop.
3. Onglet « Actions » : la compilation « Build APK » démarre toute seule (3 à 6 minutes).
   Sinon : « Build APK » > « Run workflow ».
4. Quand la pastille est verte, ouvrez l'exécution et téléchargez « LeoPhysio-Triple-saut-APK » (un zip contenant `app-debug.apk`).
5. Copiez l'APK sur le téléphone Android, ouvrez-le et autorisez l'installation depuis cette source.

## Mettre à jour la fiche
Remplacez `www/index.html` dans le dépôt : l'APK est recompilé automatiquement.

## Notes
- L'APK est signé avec une clé de test : parfait pour une installation directe, pas pour le Play Store.
- L'icône et l'écran de démarrage sont générés à partir du logo (`assets/`).

## Version 2 (FR / EN + export PDF)
Pour mettre à jour le dépôt GitHub, remplacez uniquement 2 fichiers :
1. `index.html` (la fiche, à la racine du dépôt ou dans `www/`)
2. `package.json` (ajoute les modules de partage de fichiers pour Android)
Puis attendez la compilation dans l'onglet « Actions ».

## Version 4 (journal quotidien, analyse par critère, manquements)
Pour mettre à jour le dépôt GitHub, remplacez uniquement 2 fichiers :
1. `www/index.html` (la fiche)
2. `package.json` (numéro de version)
Puis attendez la compilation dans l'onglet « Actions » et installez le nouvel APK par-dessus l'ancien (vos données restent).

Nouveautés :
- **Journal** : saisie de la journée en une minute (forme, sommeil, séance avec durée et effort perçu, performances du jour). « Nouvelle journée » remet à zéro les champs du jour, « Enregistrer la journée » ajoute un point au suivi.
- **Charge d'entraînement** : charge de séance (effort perçu × durée) et ratio charge aiguë / chronique (ACWR, zone cible 0,8 à 1,3, disponible après 10 jours de données).
- **Analyse** : score par critère de performance (vitesse, puissance horizontale, détente, force, technique, santé musculo-tendineuse, composition corporelle, biologie, récupération), radar, évolution, axes prioritaires et manquements cliquables avec écart chiffré et tendance.
- **Suivi** : les scores par critère sont ajoutés aux courbes.
- **Exports Word et PDF** : nouveau tableau « Analyse par critère de performance ».
- Batterie de tests élite (vitesse, sauts sans élan, force, santé musculo-tendineuse) déjà intégrée à l'onglet « Tests élite ».
