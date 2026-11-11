# Übergabe: App-Design

Stand: 11.11.2026. Ausgangsstand des ursprünglichen Designs: `cc0c3ea`; Ergänzung der Feuerversion auf Basis von `b51761e`.

Die Referenz besteht aus [dem freigegebenen Mockup](app-design-manrope.png) und [der Farbspezifikation](design-beschreibung.txt). Schwarz (#000000) bildet den Grund, Anthrazit (#181A1E) die Karten, Orange (#FF7A1A) die primären Aktionen. Schwarze Schrift auf der orangen Grundfarbe hat ein Kontrastverhältnis von 8,05:1. Konturen trennen die dunklen Ebenen.

Geprüft: PNG dekodiert (1536 × 1024). Alle drei Screens, die neue Unterzeile, die Glasflächen und die orangefarbenen Aktionen sind sichtbar. SHA-256 des freigegebenen Bildes: `84c6177aeaa5610ffe9e8ca477ab09db69622e85f32a1e6b77e9eaf71fcdf1d1`.

Für die Übernahme in Apps: Grund, Karten und Aktionsflächen getrennt behandeln; die Lichtwellen bleiben Dekoration.

## Bildbearbeitung

Integrierte Bildbearbeitung mit der vorherigen Version von `app-design-manrope.png` als Referenz. Bildauftrag:

> Bearbeite nur die Farbgebung der mitgelieferten originalen Designvorlage (Edit target). Gleiche Komposition im Querformat 3:2, alle drei vollständigen Geräte, dieselben Screens, Inhalte, deutschen Texte, Zahlen, Manrope-artige Typografie, Abstände und Navigation beibehalten. Ergänze echtes Schwarz #000000 als klar erkennbare tiefste Ebene: die ruhigen Freiflächen hinter Karten, die vertiefte Mitte des Fokustimers und die Zwischenräume. Die darüberliegenden Glasflächen, Karten und Navigationsleisten bleiben erkennbar Anthrazit #181A1E mit feinen hellen Kanten. Orange #FF7A1A bleibt für primäre Aktionen, Auswahl und Fokus-Ring; die vorhandenen organischen Lichtwellen sparsam beibehalten. Helle Schrift wie im Original, auf hellorangefarbenen Aktionsflächen schwarze Beschriftung. Oben Titel »APP DESIGN« erhalten, Unterzeile exakt »Anthrazit × Orange × Schwarz« gut lesbar setzen, das Wort Schwarz nicht schwarz auf schwarz. Keine neuen Bedienelemente, keine weiteren Labels, kein Umgestalten der App.

## Alternative Feuerversion – 11.11.2026

Die neue Alternative liegt vollständig unter `alternativen/feuerversion/`. Sie ergänzt die bisherigen Lichtwellen um feine Feuerlinien und verstärkt Transparenz, Glanzkanten und warme Reflexe der anthrazitfarbenen Glasflächen. Enthalten sind eine eigene App-Referenz, die Materialreferenz, das abgestimmte QHD-Wallpaper-Paar mit sichtbarem Rauch und das Chrome-Theme „Anthrazit Orange - Feuerstrom“ 1.4.2 mit offenen Dateien und ZIP-Download.

Das App-Mockup wurde mit dem integrierten Imagegen-Werkzeug aus der bestehenden Vorlage und der Feuerlinien-Materialreferenz bearbeitet. Geprüft: PNG 1536 × 1024; alle drei Geräte vollständig, bisherige deutsche Inhalte und Bedienelemente lesbar. Bildaufträge und Gestaltungsspezifikation liegen bei der Alternative.

Die Wallpaper haben 1440 × 2560 Pixel (links, Hochformat) und 2560 × 1440 Pixel (rechts). Aus der Feuerlinie steigen durchscheinende anthrazit- und aschgraue Rauchwirbel auf. Die Ausschnitte berücksichtigen den Grundversatz von 95 mm beziehungsweise rund 349 Pixeln sowie die Feinkorrektur von 35 Pixeln nach unten am linken Motiv. Das generierte Ausgangsmotiv wurde für den exakten Export hochwertig skaliert.

Das Chrome-Theme übernimmt Farben und Symbol aus Kupferlicht 1.2.0. Das gemeinsame Gesamtmotiv mit 2560 × 1440 Pixeln und die Kopfzone bleiben unverändert. Fensterrahmen, inaktiver Rahmen, Tabs und Symbolleiste referenzieren dieselbe header.png. Die bereitgestellte Browseraufnahme wurde lokal numerisch registriert: UI-Bildmaßstab 1,0 mit Y-Versatz −16, NTP-Bildmaßstab 1,25 mit Y-Versatz −48,75 gegenüber dem Master. Der neue NTP-Export gleicht diesen Unterschied aus: 2048 × 1042 Pixel, bilineare Master-Abtastung bei (1,25 × x, 137,25 + 1,25 × y), weiterhin links oben ausgerichtet. Die Offline-Vorwärtsdarstellung ergibt danach dieselbe geometrische Zuordnung wie die Kopfzone. Browser-Einstellungen wurden nicht geändert. Der Bildauftrag des Feuermaterials steht in `BILDAUFTRAG-CHROME140.txt`.

Die ursprüngliche Datei `app-design-manrope.png` behält die oben dokumentierte SHA-256-Prüfsumme. Beim Chrome-Theme sind die numerische Bildregistrierung, die explizite NTP-Abtastung, der unveränderte Header, Manifest, Bildgrößen, ZIP-Inhalt, ursprüngliche Farbwerte und Symbol geprüft; dazu kommt Chromes native Paketprüfung. Eine neue visuelle Kontrolle der Browserdarstellung ist durch die URL-Erkennung der Computersteuerung blockiert. Die private Aufnahme wurde nicht veröffentlicht und das persönliche Chrome-Profil nicht verändert. Theme-Prüfung und Installationshinweise stehen im Unterordner `chrome-theme/` der Alternative.
