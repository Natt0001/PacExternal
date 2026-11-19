# PacExternal

**[Télécharger l’installateur — PacExternal-Setup.exe](https://github.com/Natt0001/PacExternal/releases/download/setup-1.0.0/PacExternal-Setup.exe)**

Le fichier à partager reste cet installateur unique. Il télécharge la dernière version stable compatible, installe l’application pour le compte courant et crée le raccourci Bureau. Lancer normalement, sans droits administrateur. Aucun SDK ni runtime .NET à installer chez le destinataire.

Après une installation réussie, l’updater attend la fermeture du setup et peut supprimer sa copie locale reconnue. En cas d’échec, le setup reste disponible pour réessayer. Les réglages existants sont conservés.

**Application déjà installée :** fermer complètement PacExternal puis le relancer pour rechercher la mise à jour. Une fenêtre simplement masquée ou réduite reste ouverte ; utiliser Quitter si nécessaire.

[Installation manuelle : dernière version de l’application](https://github.com/Natt0001/PacExternal/releases/latest). Extraire entièrement le ZIP Windows x64 et conserver PacExternal.exe, PacExternal.Updater.exe et les dossiers fournis.

Au premier lancement, choisir français ou anglais. Le choix est modifiable dans Configurations et s’applique au redémarrage. Les réglages restent dans AppData.

L’installateur possède sa propre release, séparée des releases stables de l’application. Son lien reste identique quand l’application est mise à jour. Les fichiers PacExternal.update.json et PacExternal.update.sig sont utilisés automatiquement par l’updater ; aucun téléchargement manuel de ces deux fichiers n’est nécessaire.

Les EXE n’ont pas de signature éditeur Authenticode. Les mises à jour sont vérifiées par signature et empreintes avant installation. Les sources développeur et les clés privées restent locales et ne sont pas publiées dans ce dépôt.