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
