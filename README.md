# ICP-Radar GROB Antriebstechnik

Bewertete Zielmarktlisten für das Produkt **Hochpräzisions-Kugelgewindetriebe**, erzeugt aus zwei
Idealkundenprofilen der Buyer-Enablement-Plattform.

**Dashboard:** https://es-dev-1.github.io/icp-accounts-grob/

## Inhalt

| ICP | Firmen | Starker Fit | Guter Fit | Bedingter Fit | Schlechter Fit |
|---|---|---|---|---|---|
| Druckmaschinenhersteller (Präzision) | 87 | 3 | 8 | 38 | 38 |
| Spritzgussmaschinenbau | 48 | 2 | 10 | 19 | 17 |

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
| 85 bis 100 | Starker Fit |
| 70 bis 84 | Guter Fit |
| 51 bis 69 | Bedingter Fit |
| 0 bis 50 | Schlechter Fit |

Für einen starken Fit müssen zusätzlich die Branche passen, die Mitarbeiterzahl belegt und im Zielband liegen und
mindestens 70 Prozent der gewichteten Kriterien belegt sein. Fehlt eine dieser Bedingungen, steht die Firma trotz
hoher Punktzahl eine Stufe tiefer.

Je Kriterium gibt es eine Note: A erfüllt, B überwiegend, C teilweise oder nur schwach belegt, D nicht erfüllt,
N ohne Datenbasis. Bei Anti-Kriterien heißt A, dass das Ausschlussmerkmal nicht zutrifft. Ein C ist ein
Prüfauftrag, keine Absage.

Die Kriteriengruppen sind **F** Firmografie (Branche, Region, Mitarbeiterzahl, Jahresumsatz) und **B**
Bedarfsindikatoren, die aus Herausforderungen, Zielen und Kaufentscheidungsprozess des Idealkundenprofils
abgeleitet und auf den Firmenwebsites geprüft wurden.

Die Spalte Datenqualität nennt, wie viel Prozent der gewichteten Kriterien belegt sind. Unter 70 Prozent wird die
Punktzahl zur Mitte gedämpft und die Note A nicht vergeben, damit eine Firma mit wenigen belegten Kriterien nicht
die Liste anführt.

## Grenzen

- Die Region beider Profile ist eng gefasst (Heidelberg, Österreich). Firmen im selben Land, aber außerhalb der
  Region, erhalten deshalb nur ein B.
- Das Mitarbeiterband 1001 bis 10000 beschreibt die Spitze beider Branchen. Der überwiegende Teil des Marktes ist
  Mittelstand mit 50 bis 500 Mitarbeitern.
- Websites, die ihre Inhalte erst im Browser aufbauen, liefern wenig prüfbaren Text. Wo die Firmografie durchweg A
  ist und die Bedarfsindikatoren auffällig schwach sind, lohnt der Blick auf die Firma statt auf die Punktzahl.

Stand: 1. September 2026 (Einstufungsskala angepasst)
