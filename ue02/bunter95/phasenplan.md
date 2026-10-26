# Phasenplan — Terminplaner für die THM

Kürzel: bunter95

## Studie

**Ergebnis der Phase:** …

- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten
- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Aufwand schätzen und einen Meilensteinplan vorschlagen

## Systemspezifikation

**Ergebnis der Phase:** …

- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde

## Systemkonstruktion

**Ergebnis der Phase:** …

- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen
- Datenbank, Programmiersprache und Web-Framework auswählen
- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen

## Implementierung

**Ergebnis der Phase:** …

- Die Komponente „Benachrichtigung“ programmieren
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt

## Integration & Einführung

**Ergebnis der Phase:** …

- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen
- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt
- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt

## Wartung

**Ergebnis der Phase:** …

- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Aufwand schätzen und einen Meilensteinplan vorschlagen** (Studie): unsicher ob eher zur studie oder bereits systemkonstruktion
- **Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen** (Studie): zwischen systemspezifikation oder studie eventuell noch

<!-- zuordnung ue02-phasenplan: k01=implementierung k02=studie k03=integration k04=spezifikation k05=wartung k22=spezifikation k06=konstruktion k07=studie k08=integration k09=konstruktion k10=spezifikation k11=wartung k12=implementierung k23=konstruktion k13=studie k14=studie k15=studie k16=integration k17=wartung k18=konstruktion k19=spezifikation k24=integration k20=integration k21=spezifikation | unsicher: k13 k14 -->
