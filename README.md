# PacExternal

[Télécharger la dernière version](https://github.com/Natt0001/PacExternal/releases/latest).

Extraire entièrement le ZIP Windows x64, puis ouvrir **PacExternal.exe**. Conserver **PacExternal.Updater.exe** et les dossiers fournis. Aucun SDK ni .NET installé n’est requis.

Depuis la 4.2.0, choisir français ou anglais au premier lancement. La langue système est présélectionnée, avec repli anglais. Le choix est modifiable dans Configurations et s’applique au redémarrage. Un raccourci est créé sur le Bureau lors d’un lancement normal.

L’updater vérifie les nouvelles releases stables, leur signature et les empreintes avant installation. Les réglages sont conservés. Le nouvel affichage de progression est disponible dans l’updater 4.2.0 ; le premier passage depuis la 4.1.1 garde l’ancien écran pendant le téléchargement.

Les fichiers `PacExternal.update.json` et `PacExternal.update.sig` sont destinés à l’updater. Il n’est pas nécessaire de les télécharger manuellement. La signature de mise à jour est distincte d’Authenticode Windows.

Ce dépôt publie les paquets client. Les sources développeur et les clés privées restent locales.
