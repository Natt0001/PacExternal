# PacExternal

Téléchargements officiels : [dernière release stable](https://github.com/Natt0001/PacExternal/releases/latest).

## Installer

Télécharger le ZIP Windows x64, l’extraire entièrement dans un dossier accessible en écriture puis ouvrir `PacExternal.exe`. Conserver `PacExternal.Updater.exe`, les licences et le dossier Offsets à côté. Aucun SDK ni .NET installé n’est requis.

La première installation de la **4.1.0** se fait manuellement depuis une version antérieure. À partir de la 4.1.0, l’updater vérifie les nouvelles releases stables au démarrage, authentifie leur manifeste et installe les fichiers avant de lancer l’application. Les réglages restent dans AppData. Une panne réseau laisse la version locale utilisable.

Les fichiers `PacExternal.update.json` et `PacExternal.update.sig` servent à l’updater ; il n’est pas nécessaire de les télécharger manuellement. Cette signature de mise à jour ne remplace pas une signature Authenticode Windows des EXE.

Ce dépôt distribue les paquets client et les informations de version. Les sources développeur et les clés privées ne sont pas publiées ici.
