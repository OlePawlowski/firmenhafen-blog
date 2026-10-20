# Firmenhafen Blog

Die Blogbeiträge von [firmenhafen.de](https://firmenhafen.de). Dieses Repository enthält nur Texte und Bilder, keinen Code. Die Website liest die Beiträge alle paar Minuten von hier und zeigt sie unter [firmenhafen.de/blog](https://firmenhafen.de/blog).

## So kommt ein Beitrag auf die Seite

1. Neuen Branch anlegen, zum Beispiel `beitrag/virtual-office-kosten`.
2. Datei in `beitraege/` anlegen, Dateiname `JJJJ-MM-TT-kurzer-titel.md` (nur Kleinbuchstaben, Zahlen, Bindestriche).
3. Bilder (falls nötig) in `bilder/` ablegen.
4. Pull Request gegen `main` öffnen. Ole prüft und gibt frei.
5. Nach dem Merge steht der Beitrag innerhalb von etwa zehn Minuten auf der Seite.

## Aufbau einer Beitragsdatei

```markdown
---
titel: Was kostet eine Geschäftsadresse in Berlin?
beschreibung: Von 29 € bis 199 € im Monat: Was eine ladungsfähige Adresse kostet und worauf Sie beim Vergleich achten.
datum: 2026-10-20
stichwort: Geschäftsadresse Berlin
status: veröffentlicht
bild: bilder/geschaeftsadresse-kosten.jpg
bild-alt: Briefkasten an einem Berliner Altbau
---

Erster Absatz mit dem Hauptstichwort.

## Zwischenüberschrift

Text, **fett**, *kursiv*, [Link auf die Preise](/#preise) und Listen:

- Punkt eins
- Punkt zwei
```

| Feld | Pflicht | Bedeutung |
|---|---|---|
| `titel` | ja | Überschrift und Seitentitel, möglichst mit dem Hauptstichwort |
| `beschreibung` | ja | Kurzfassung für Google und die Übersicht, etwa 150 Zeichen |
| `datum` | ja | `JJJJ-MM-TT`. Liegt es in der Zukunft, erscheint der Beitrag erst an diesem Tag |
| `stichwort` | nein | Hauptstichwort, für die Suchmaschine |
| `status` | ja | `veröffentlicht` oder `entwurf`. Entwürfe erscheinen nicht auf der Seite |
| `bild` | nein | Pfad zum Titelbild in `bilder/` |
| `bild-alt` | bei Bild | Beschreibung des Bildes für Sehbehinderte und Google |

Unterstützt sind Überschriften (`##`, `###`), Absätze, Listen, **fett**, *kursiv*, Links, Bilder (`![Beschreibung](bilder/datei.jpg)`), Zitate (`>`) und Trennlinien (`---`). Rohes HTML wird nicht angezeigt.

**Dieses Repository ist öffentlich.** Alles, was hier liegt, kann jeder lesen, auch Entwürfe. Keine Kundennamen, keine Zugangsdaten, nichts Vertrauliches.
