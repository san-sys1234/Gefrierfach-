# Frostfach – Gefrierschrank-App

Eine iPhone-freundliche PWA für GitHub Pages. Produkte samt Menge, Einheit, Einfrierdatum, Kategorie, Lagerort und Notizen erfassen. Über **„Menge verwenden“** kannst du Teilmengen oder die gesamte Restmenge verbuchen. Bei Teilverbrauch wird die verfügbare Menge automatisch reduziert; erst bei vollständigem Verbrauch wandert der Eintrag in **„Aufgebraucht“**. Verwendungsdatum und Notiz werden im Verlauf gespeichert. Einträge können bearbeitet, zurückgelegt oder gelöscht werden.

## Auf GitHub veröffentlichen
1. Erstelle auf GitHub ein neues Repository, z. B. `frostfach`.
2. Lade **alle Dateien dieses Ordners** in das Repository hoch (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md`).
3. Öffne im Repository **Settings → Pages**.
4. Bei **Build and deployment** `Deploy from a branch` auswählen, Branch `main`, Ordner `/(root)`, dann **Save**.
5. Nach der Veröffentlichung öffne die angezeigte GitHub-Pages-Adresse in Safari am iPhone.
6. Tippe auf **Teilen → Zum Home-Bildschirm**.

## Daten & Sicherung
- Die Daten bleiben im Browser-Speicher dieses Geräts und werden nicht automatisch mit GitHub oder anderen Geräten synchronisiert.
- Nutze **Daten exportieren**, um eine JSON-Sicherung herunterzuladen.
- **Daten importieren** ersetzt den aktuellen Bestand durch die gewählte Sicherung.
- Browserdaten nicht löschen, ohne vorher eine Sicherung zu exportieren.

## Hinweis
Über **Menge verwenden** trägst du die tatsächlich verbrauchte Menge ein. Beispiel: Aus 500 g werden 200 g verwendet – der Bestand sinkt automatisch auf 300 g. Erst wenn die verbleibende Menge vollständig verbraucht wird, wandert der Eintrag ins Register „Aufgebraucht“.

## Designupdate
Warme Creme- und Terrakottatöne, minimalistische einspaltige Listen, Kategorienfilter und Anzeige der Restmenge. Bestehende lokal gespeicherte Daten werden beibehalten.

## Design 2 + 4
Warm-minimales Design in Creme, Terrakotta und Salbeigrün, kompakte Listenansicht, Kategorie-Filter, automatische Restmengen und Verbrauchsverlauf. Bei Teilverbrauch bleibt das Produkt aktiv; erst bei vollständigem Verbrauch wird es nach „Aufgebraucht“ verschoben.
