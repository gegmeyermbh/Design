# Chrome-Theme: Feuerstrom

Version 1.4.0 verbindet organische Feuerströme im Browserrahmen mit einem passenden Neuer-Tab-Hintergrund. Die Flammen verzweigen sich, wechseln ungleichmäßig ihre Höhe und Stärke und gehen stellenweise in Rauch über. Lange ruhigere Abschnitte wechseln sich mit einzelnen stärkeren Flammenbüscheln ab.

Der Neuer-Tab-Hintergrund übernimmt die anthrazitfarbene Grundstimmung und die beiden asymmetrischen Randbereiche des ursprünglichen Kupferlicht-Themes. Dort stehen lebendige Feuerfilamente und Rauch; die Mitte bleibt ruhig für Suche und Verknüpfungen. Die UI-Texturen verwenden dasselbe Feuermaterial mit einer eigenen unregelmäßigen Linienführung. Die bisherigen wiederholten Sinuskurven entfallen.

Die Theme-Farben, Bildverweise, Ausrichtungseinstellungen und das Paketsymbol stammen weiterhin aus Kupferlicht 1.2.0.

[ZIP herunterladen](../downloads/Anthrazit-Orange-Chrome-Feuerstrom-1.4.0.zip) · [Installation](INSTALLATION.txt) · [Manifest](manifest.json)

Zum vollständigen Wiederherstellen ist auch das [unveränderte Original Kupferlicht 1.2.0](../downloads/Anthrazit-Orange-Chrome-Kupferlicht-Original-1.2.0.zip) verfügbar.

![Texturvorschau von Feuerstrom](../chrome-theme-vorschau.png)

[Bildauftrag für den passenden Hintergrund](../BILDAUFTRAG-CHROME140.txt)

## Installation

Das ZIP vollständig in einen dauerhaften Ordner entpacken. In Chrome unter chrome://extensions den Entwicklermodus einschalten, „Entpackte Erweiterung laden“ wählen und den Ordner mit manifest.json auswählen. Den Ordner während der Nutzung behalten. Details und Hinweise zum Aktualisieren bzw. Zurücksetzen stehen in INSTALLATION.txt.

Das Paket ist ein lokales Theme. Es enthält ausschließlich das Manifest und PNG-Bilder sowie die Installationshinweise; keine Skripte, Berechtigungen oder Netzwerkzugriffe.

## Prüfung

- Chromes eigene Paketprüfung über --pack-extension war mit Chrome 157.0.8103.40 erfolgreich.
- Manifest, sämtliche lokalen Bildverweise, PNG-Abmessungen und ZIP-Inhalt wurden geprüft.
- Symbol sowie alle Theme-Farben und Eigenschaften stimmen mit Kupferlicht 1.2.0 überein.
- Chrome 157 hat das Theme über die offizielle Erweiterungsschnittstelle in einem separaten Testprofil erfolgreich geladen. Die abschließende Kontrolle der Browserdarstellung konnte nicht durchgeführt werden, weil die Computersteuerung die aktuelle Browser-URL nicht zuverlässig bestimmen konnte.
- Die Vorschau zeigt die tatsächlichen Theme-Bilddateien als Kontaktbogen. Sie ist keine Browseraufnahme. Das persönliche Chrome-Profil wurde nicht verändert.

| Datei | Pixel |
|---|---|
| Rahmen | 3840 × 256 |
| Inaktive Tabs | 3840 × 41 |
| Symbolleiste | 3840 × 160 |
| Neuer Tab, Feuerstrom | 3840 × 2160 |
| Theme-Symbol, Original | 128 × 128 |

Glanz und Transparenz sind visuelle Materialeffekte in deckenden Bildern. Die Browserfenster werden dadurch nicht tatsächlich zum Desktop durchsichtig. Chrome bestimmt Schrift, Form der Bedienelemente und den sichtbaren Ausschnitt der Texturen. Eigene Hintergrundbilder für neue Tabs können den Theme-Hintergrund verdecken.

Dokumentation: [Chrome-Themes](https://developer.chrome.com/docs/extensions/develop/ui/themes), [lokales Laden](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked).
