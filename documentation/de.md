<!-- ELUCENIA technical documentation · fleischner-2017 · de · no clinical/professional/rights approval -->

# Fleischner 2017 (solider Lungenknoten)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/fleischner-2017)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Mittlerer Knotendurchmesser (bei mehreren: des verdächtigsten Knotens)

`tamanho`

mm · Bereich: 1–30

### Anzahl der Knoten

`num`

- `u` — Einzeln
- `m` — Mehrere

### Lungenkrebsrisiko

`risco`

- `b` — Niedrig
- `a` — Hoch (Rauchen, Alter, Exposition, Familienanamnese, Emphysem, Oberlappen)

## Fassung der Methode

Fleischner Society 2017: zufällige solide Knoten, gerundeter mittlerer Durchmesser; Ausschlüsse erhalten

## Dokumentierte Formel

Mittlerer Durchmesser = (längste Achse + kürzeste Achse) ÷ 2, auf den nächsten Millimeter gerundet. Bereiche: \< 6 mm (\< 100 mm³), 6 bis 8 mm (100 bis 250 mm³), \> 8 mm (\> 250 mm³).

## Grenzen und Population

Variante für zufällig entdeckte solide Lungenknoten bei Erwachsenen ab 35 Jahren. Die Fleischner 2017-Empfehlungen gelten nicht für das Lungenkrebs-Screening, immungeschwächte Personen oder Patienten mit einer bekannten primären Krebserkrankung. Subsolide oder teilsolide Knoten erfordern einen anderen Algorithmus. Bei mehreren Knoten sollte der verdächtigste Knoten die Beurteilung bestimmen; er ist nicht zwangsläufig der größte. Risikoeinstufung und Entscheidung zur Verlaufskontrolle hängen von der klinischen und radiologischen Beurteilung ab.

## Referenzen

- [MacMahon H et al. Guidelines for management of incidental pulmonary nodules detected on CT images: from the Fleischner Society 2017. Radiology, 2017.](https://doi.org/10.1148/radiol.2017161659)

- [MacMahon et al. Radiology2017, DOI10.1148/radiol.2017161659](https://pubs.rsna.org/doi/full/10.1148/radiol.2017161659)

- [Original sixteen-page RSNA article, institutional copy at University of Wisconsin](https://wiki.radiology.wisc.edu/images/b/b9/Flesichner_Guidelines_2017.pdf)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
