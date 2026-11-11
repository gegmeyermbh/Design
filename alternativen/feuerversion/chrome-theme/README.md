# Chrome-Theme: Anthrazit Orange – Feuerversion

Version 1.3.0. Das Theme überträgt die Feuerlinie und die glänzenden anthrazitfarbenen Glasflächen auf Chrome. Fensterrahmen, Tabs und Symbolleiste verwenden dunkle Feuerreflexe; ein neuer Tab zeigt das größere Motiv unterhalb der ruhigen Suchfläche.

[ZIP herunterladen](../downloads/Anthrazit-Orange-Chrome-Feuerversion-1.3.0.zip) · [Installation](INSTALLATION.txt) · [Manifest](manifest.json)

![Vorschau der tatsächlichen Theme-Bilddateien; keine Aufnahme aus Chrome](../chrome-theme-vorschau.png)

## Installation

Das ZIP vollständig in einen dauerhaften Ordner entpacken. In Chrome unter chrome://extensions den Entwicklermodus einschalten, „Entpackte Erweiterung laden“ wählen und den Ordner mit manifest.json auswählen. Den Ordner während der Nutzung behalten. Details und Hinweise zum Aktualisieren bzw. Zurücksetzen stehen in INSTALLATION.txt.

Das Paket ist ein lokales Theme. Es enthält ausschließlich das Manifest und PNG-Bilder sowie die Installationshinweise; keine Skripte, Berechtigungen oder Netzwerkzugriffe.

## Prüfung

- Chromes eigene Paketprüfung über --pack-extension war mit Chrome 157.0.8103.40 erfolgreich.
- Manifest, sämtliche lokalen Bildverweise, PNG-Abmessungen und ZIP-Inhalt wurden geprüft.
- Text- und Symbolfarben wurden konservativ gegen die jeweils hellsten Pixel der betroffenen Texturen geprüft.
- Die Vorschau zeigt die tatsächlichen Bildtexturen. Das Theme wurde nicht in einem persönlichen Chrome-Profil installiert; die Darstellung innerhalb Chrome wurde nicht visuell getestet.

| Datei | Pixel |
|---|---|
| Rahmen | 3840 × 256 |
| Inaktive Tabs | 3840 × 41 |
| Symbolleiste | 3840 × 160 |
| Neuer Tab | 3840 × 2160 |
| Theme-Symbol | 128 × 128 |

Glanz und Transparenz sind visuelle Materialeffekte in deckenden Bildern. Die Browserfenster werden dadurch nicht tatsächlich zum Desktop durchsichtig. Chrome bestimmt Schrift, Form der Bedienelemente und den sichtbaren Ausschnitt der Texturen. Eigene Hintergrundbilder für neue Tabs können den Theme-Hintergrund verdecken.

Dokumentation: [Chrome-Themes](https://developer.chrome.com/docs/extensions/develop/ui/themes), [lokales Laden](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked).
