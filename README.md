# Note à note

Petit jeu pour apprendre à lire les notes en clé de sol au piano.

La page affiche une portée avec une note. L'enfant la joue au piano, l'appli l'écoute (micro ou câble MIDI) et valide quand la bonne note est jouée. Après 5 manches réussies sans erreur, les notes arrivent par deux, puis trois, quatre et cinq.

Après le niveau 5, le mode « Morceaux » propose de vraies partitions qui se dévoilent au fur et à mesure qu'on les joue, avec toujours cinq notes visibles d'avance. Le répertoire est tiré d'airs du domaine public (Beethoven, Dvořák, Mozart, comptines traditionnelles), arrangés pour une main, en noires et blanches, sans altérations. Les morceaux sont décrits dans la constante `PIECES` d'`index.html` : une note par mot (`E4`, `G4:2` pour une blanche), une barre `|` par mesure.

## Utilisation

- Ouvrir la page dans Safari ou Chrome et accepter l'accès au micro.
- Sur iPad : Partager, puis « Sur l'écran d'accueil » pour l'ouvrir en plein écran comme une appli.
- Les réglages (prénom, notes utilisées, sensibilité du micro, niveau) sont dans le bouton « Réglages ». La progression est gardée sur l'appareil.

## Fichiers

- `index.html` : toute l'application (HTML, CSS et JavaScript dans un seul fichier)
- `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` : nom et icône pour l'écran d'accueil

La clé de sol, les têtes de note et les chiffres de mesure sont dessinés avec les contours de la police Bravura (Steinberg, licence SIL Open Font).
