PROJET ANDROID — LIVRAISON & FACTURE

1. Installez Android Studio.
2. Décompressez ce dossier.
3. Dans Android Studio : Open > sélectionnez le dossier LivraisonFactureAndroid.
4. Attendez la fin de la synchronisation Gradle.
5. Pour tester : Run > Run 'app'.
6. Pour créer un APK :
   Build > Generate App Bundles or APKs > Generate APKs.

APK de test :
   app/build/outputs/apk/debug/app-debug.apk

IMPORTANT POUR PLUSIEURS TÉLÉPHONES
------------------------------------
L'APK de débogage est utilisable pour vos tests, mais pour distribuer des mises
à jour durables, créez une clé de signature permanente :
   Build > Generate Signed App Bundle or APK > APK > Create new...

Gardez précieusement le fichier .jks, l'alias et les mots de passe. Toutes les
futures versions doivent être signées avec la même clé.

Cette application affiche uniquement le domaine :
   https://app-pwa-maquette-162032.onhercules.app/

Les liens externes s'ouvrent dans le navigateur du téléphone.
