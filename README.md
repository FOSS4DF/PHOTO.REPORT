<img src="images/icon.png" width="56" alt="">

# Rapport photographique · Photographic Report

**`PHOTO_REPORT.html`** · Hors ligne · Aucune installation · Aucun envoi — *Offline · No install · No upload*

**[Français](#français) · [English](#english)**

---

## Français

### À quoi sert cet outil

Cet outil produit un rapport PDF de pièces photographiques : une photo par page, accompagnée de la date et de l'heure de prise de vue, des coordonnées GPS, de l'appareil utilisé et de l'empreinte SHA-256 du fichier original. Il sert à documenter des constatations (lieux, scènes, scellés) de manière traçable.

### Avant de commencer

- Ouvrez le fichier PHOTO_REPORT.html par double-clic : il s'affiche dans votre navigateur (Chrome, Edge, Firefox ou Safari récents). Aucune installation n'est nécessaire.
- L'outil fonctionne sans connexion Internet. Aucun fichier n'est envoyé : tout le traitement se fait sur votre appareil.
- La langue (FR, EN, SW, LN) se choisit en haut à droite ; le bouton voisin bascule entre thème clair et sombre. Ces choix sont mémorisés.
- Pour obtenir les coordonnées GPS, activez la localisation dans l'application appareil photo avant la prise de vue.

### L'écran en un coup d'œil

![Vue d'ensemble annotée de l'interface](images/overview_fr.png)

1. Langue de l'interface et du rapport
2. Thème clair ou sombre
3. Auteur et numéro de dossier, repris en en-tête de chaque page
4. Prendre ou choisir des photos
5. « Pivoté » : la photo occupe la page en paysage (activé d'office pour les photos horizontales)
6. Flèches haut et bas : changer l'ordre des photos
7. Générer le PDF

#### Sur téléphone (thème sombre)

<img src="images/mobile_fr.png" width="280" alt="Interface sur téléphone en thème sombre">

### Utilisation pas à pas

1. Saisissez l'auteur et le numéro de dossier. Ils sont mémorisés pour la fois suivante.
2. Cliquez sur « Prendre ou choisir des photos ». Sur téléphone, vous pouvez photographier directement ; sur ordinateur, sélectionnez une ou plusieurs images.
3. Contrôlez chaque photo : date et heure, coordonnées, appareil, empreinte SHA-256. La mention « absent de l'EXIF » signale une information que l'appareil n'a pas enregistrée.
4. Réglez l'ordre avec les flèches et l'orientation avec « Pivoté ». « Supprimer » retire une photo, « Tout effacer » vide la liste.
5. Cliquez sur « Générer le PDF ». Le fichier est enregistré sous le nom NuméroDeDossier_AAAA-MM-JJ.pdf.

### Résultat

![Le rapport généré](images/result1_fr.png)

*Le rapport généré : page de garde (dossier, auteur, nombre de photos, date de génération, note de méthode), puis une page par photo avec ses métadonnées. Les photos en mode « Pivoté » sont présentées en paysage.*

### Bonnes pratiques

- N'utilisez que les fichiers originaux. Une photo retouchée, recadrée ou transmise par WhatsApp ou un réseau social perd ses métadonnées et change d'empreinte.
- Conservez les fichiers originaux avec le rapport : l'empreinte SHA-256 imprimée permet de prouver qu'une photo n'a pas été modifiée (vérification avec Forensic Hash Calculator).
- La date et l'heure proviennent de l'horloge de l'appareil : vérifiez qu'elle est juste avant une mission.

### En cas de problème

| Problème | Solution |
|---|---|
| **Coordonnées « absent de l'EXIF »** | La localisation était désactivée, ou l'image a transité par une messagerie. Activez la localisation et utilisez le fichier original. |
| **« Aperçu indisponible » (photo HEIC d'iPhone sur ordinateur)** | Ouvrez l'outil directement sur l'iPhone, ou réglez l'appareil photo sur « Le plus compatible » (JPEG). |
| **Le PDF ne se télécharge pas** | Autorisez les téléchargements dans le navigateur. Sur iPhone, utilisez Safari puis « Enregistrer dans Fichiers ». |

### Confidentialité

L'outil fonctionne entièrement sur votre appareil, sans connexion Internet. Aucune donnée n'est transmise ni conservée en dehors des fichiers que vous téléchargez vous-même.

---

## English

### What this tool is for

This tool produces a PDF report of photographic exhibits: one photo per page, with the capture date and time, GPS coordinates, camera model and the SHA-256 hash of the original file. It is used to document findings (places, scenes, sealed evidence) in a traceable way.

### Before you start

- Double-click PHOTO_REPORT.html: it opens in your browser (recent Chrome, Edge, Firefox or Safari). Nothing to install.
- The tool works without an Internet connection. No file is uploaded: everything is processed on your device.
- Choose the language (FR, EN, SW, LN) at the top right; the button next to it switches between light and dark theme. Both choices are remembered.
- To record GPS coordinates, enable location in the camera app before taking the photos.

### The screen at a glance

![Annotated overview of the interface](images/overview_en.png)

1. Interface and report language
2. Light or dark theme
3. Author and case number, repeated in the header of every page
4. Take or choose photos
5. “Sideways”: the photo fills the page in landscape (on by default for horizontal photos)
6. Up and down arrows: change the order of the photos
7. Generate PDF

#### On a phone (dark theme)

<img src="images/mobile_en.png" width="280" alt="Interface on a phone in dark theme">

### Step by step

1. Enter the author and the case number. They are remembered for next time.
2. Click “Take or choose photos”. On a phone you can shoot directly; on a computer, select one or more images.
3. Check each photo: date and time, coordinates, camera, SHA-256 hash. “not in EXIF” means the device did not record that information.
4. Set the order with the arrows and the orientation with “Sideways”. “Remove” deletes a photo, “Clear all” empties the list.
5. Click “Generate PDF”. The file is saved as CaseNumber_YYYY-MM-DD.pdf.

### Result

![The generated report](images/result1_en.png)

*The generated report: cover page (case, author, number of photos, generation date, method note), then one page per photo with its metadata. “Sideways” photos are laid out in landscape.*

### Good practice

- Only use original files. A photo that was edited, cropped or sent through WhatsApp or social media loses its metadata and its hash changes.
- Keep the original files with the report: the printed SHA-256 hash proves a photo has not been altered (check it with Forensic Hash Calculator).
- Date and time come from the device clock: make sure it is correct before a mission.

### Troubleshooting

| Problem | Solution |
|---|---|
| **Coordinates “not in EXIF”** | Location was off, or the image went through a messaging app. Enable location and use the original file. |
| **“Preview unavailable in this browser” (iPhone HEIC photo on a computer)** | Open the tool directly on the iPhone, or set the camera to “Most Compatible” (JPEG). |
| **The PDF does not download** | Allow downloads in the browser. On iPhone, use Safari, then “Save to Files”. |

### Privacy

The tool runs entirely on your device, without an Internet connection. No data is sent or kept anywhere other than the files you download yourself.
