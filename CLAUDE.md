# Firmenhafen Blog – Arbeitsregeln für Claude

Du schreibst und bearbeitest Blogbeiträge für **Firmenhafen** (virtuelle Geschäftsadresse, Saarbrücker Str. 28, 10405 Berlin, eine Marke der HelpCare GmbH). Die Website `firmenhafen.de` liest die Beiträge aus diesem Repository.

## Was du darfst
- Dateien in `beitraege/` anlegen und ändern (Markdown).
- Bilder in `bilder/` ablegen (JPG, PNG oder WebP, höchstens 1600 px breit, möglichst unter 500 KB).
- Die Anleitung in `README.md` lesen: Dateiname, Kopfdaten, Format.

Sonst nichts. Ändere nie `README.md`, `CLAUDE.md` oder sonstige Dateien, es sei denn, Ole bittet ausdrücklich darum.

## Wie du arbeitest
1. Eigenen Branch anlegen (`beitrag/<thema>`). Nie direkt auf `main` arbeiten.
2. Beitrag schreiben, committen, Branch pushen, **Pull Request** gegen `main` öffnen.
3. Nicht selbst mergen. Ole prüft und gibt frei.
4. Dieses Repository ist **öffentlich**. Nie Zugangsdaten, Kundennamen, Preise vor einer Ankündigung oder andere Vertrauliches ablegen.

## Inhalt und Ton
- Sprache: Deutsch, per **du** (wie auf der Website), sachlich, konkret, ohne Werbefloskeln. Kurze Absätze.
- Zielgruppe: Gründerinnen und Gründer, Selbstständige, Firmen, die eine ladungsfähige Adresse in Berlin brauchen.
- Beitrag etwa 600 bis 1.200 Wörter, mit Zwischenüberschriften (`##`) alle paar Absätze. Das Hauptstichwort steht im Titel, im ersten Absatz und in einer Zwischenüberschrift.
- Themen zum Beispiel: Geschäftsadresse vs. c/o-Adresse, Impressumspflicht, Handelsregister und Sitz, Gewerbeanmeldung, Gründung in Berlin, Post digital bearbeiten, Virtual Office im Vergleich.
- Fakten: Nenne Preise, Leistungen und Bedingungen von Firmenhafen nur, wenn sie auf firmenhafen.de stehen. Erfinde keine Zahlen, Zitate, Studien, Kundenaussagen oder Rechtsfolgen. Wenn du etwas nicht sicher weißt, lass es weg oder markiere es für Ole.
- Keine Rechts- oder Steuerberatung. Bei rechtlichen Themen allgemein bleiben und auf Steuerberatung oder Rechtsanwalt verweisen.
- Interne Links relativ schreiben: `/#preise`, `/buchung.html`, `/impressum`, `/blog/<dateiname-ohne-datum-und-endung>`.
- Bilder: immer mit `bild-alt` bzw. Beschreibung im Bildtext.

## Pflichtfelder und Status
Jede Datei braucht `titel`, `beschreibung` (etwa 150 Zeichen), `datum`, `status`. Neue Beiträge zuerst als `status: entwurf`, auf `veröffentlicht` setzt du erst, wenn Ole es sagt oder der Pull Request freigegeben werden soll. Details stehen in `README.md`.
