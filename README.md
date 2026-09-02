# ICP-Radar GROB Antriebstechnik

Bewertete Zielmarktlisten für das Produkt **Hochpräzisions-Kugelgewindetriebe**, erzeugt aus zwei
Idealkundenprofilen der Buyer-Enablement-Plattform.

**Dashboard:** https://es-dev-1.github.io/icp-accounts-grob/

## Inhalt

| ICP | Firmen | Starker Fit | Guter Fit | Bedingter Fit | Schlechter Fit |
|---|---|---|---|---|---|
| Druckmaschinenhersteller (Präzision) | 87 | 4 | 27 | 45 | 11 |
| Spritzgussmaschinenbau | 48 | 5 | 16 | 21 | 6 |

Das Dashboard hat oben einen Reiter je Idealkundenprofil. Jede Firma lässt sich aufklappen und zeigt dann Sitz,
Größe, Umsatz, Konzernzugehörigkeit und die Note je Kriterium mit Begründung und Quelle.

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | Dashboard, beide Listen, offline lauffähig |
| `2026-09-01-icp-bewertung-druckmaschinen.csv` | 87 Firmen, alle Kriterien mit Begründung |
| `2026-09-01-icp-bewertung-druckmaschinen-a-liste.csv` | nur Gesamtnote A |
| `2026-09-01-icp-bewertung-spritzgussmaschinen.csv` | 48 Firmen, alle Kriterien mit Begründung |
| `2026-09-01-icp-bewertung-spritzgussmaschinen-a-liste.csv` | nur Gesamtnote A |

## Bewertung lesen

Die Gesamtpunkte je Firma reichen von 0 bis 100 und ergeben die Einstufung:

| Punkte | Einstufung |
|---|---|
| 80 bis 100 | Starker Fit |
| 60 bis 79 | Guter Fit |
| 40 bis 59 | Bedingter Fit |
| 0 bis 39 | Schlechter Fit |

Die Einstufung folgt allein der Punktzahl, es gibt keine Zusatzbedingungen.

Je Kriterium gibt es eine Note: A erfüllt, B überwiegend, C teilweise oder nur schwach belegt, D nicht erfüllt,
N ohne Datenbasis. Bei Anti-Kriterien heißt A, dass das Ausschlussmerkmal nicht zutrifft. Ein C ist ein
Prüfauftrag, keine Absage.

Die Kriteriengruppen sind **F** Firmografie (Branche, Region, Mitarbeiterzahl, Jahresumsatz) und **B**
Bedarfsindikatoren, die aus Herausforderungen, Zielen und Kaufentscheidungsprozess des Idealkundenprofils
abgeleitet und auf den Firmenwebsites geprüft wurden.

Die Spalte Datenqualität nennt, wie viel Prozent der gewichteten Kriterien belegt sind. Unter 70 Prozent wird die
Punktzahl zur Mitte gedämpft, damit eine Firma mit wenigen belegten Kriterien nicht die Liste anführt. Die Dämpfung
wirkt über die Punkte, die Einstufung selbst kennt keine Ausnahmen.

## Grenzen

- Die Region beider Profile ist eng gefasst (Heidelberg, Österreich). Firmen im selben Land, aber außerhalb der
  Region, erhalten deshalb nur ein B.
- Das Mitarbeiterband 1001 bis 10000 beschreibt die Spitze beider Branchen. Der überwiegende Teil des Marktes ist
  Mittelstand mit 50 bis 500 Mitarbeitern.
- Websites, die ihre Inhalte erst im Browser aufbauen, liefern wenig prüfbaren Text. Wo die Firmografie durchweg A
  ist und die Bedarfsindikatoren auffällig schwach sind, lohnt der Blick auf die Firma statt auf die Punktzahl.

Stand: 2. September 2026
