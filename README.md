# ruhepuls – Demo-Website

Demo für den Pitch: Professionals, Executives und Personaler:innen bieten kostenlose Interview-Prep an. Bewerber:innen suchen nach ihrem Zielbereich, wählen eine Mentor:in und buchen direkt einen freien Slot im Kalender.

## Lokal ansehen

Variante 1: `index.html` doppelklicken (öffnet im Browser).

Variante 2 (lokaler Server):

```bash
cd Social-Entrepreneurship-Lab
python3 -m http.server 8000
```

Dann im Browser: http://localhost:8000

## Was die Demo kann

- Suche nach Job/Bereich mit Filtern (Interviewformat, Karrierestufe, Sprache, Verfügbarkeit)
- 16 fiktive Mentor:innen-Profile mit freien Slots für die nächsten 14 Tage
- Buchung mit Tages- und Uhrzeitwahl, Bestätigung und „In Google Kalender eintragen“
- „Meine Termine“ inkl. Stornieren (gespeichert nur im Browser, localStorage)
- Ruhe-Check: 60-Sekunden Box-Breathing-Übung
- Formular „Mentor:in werden“ (Demo, sendet nichts)
- Hell-/Dunkelmodus automatisch, mobil optimiert

Alles steckt in einer einzigen Datei (`index.html`), ohne Build-Schritt.
