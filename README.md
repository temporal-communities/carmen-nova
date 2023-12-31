# TEI Edition of »Carmen Nova« (Pseudo Umberto Eco Novella)

## Webversion
- https://temporal-communities.github.io/carmen-nova/
- Erstveröffentlichung: 21. Dezember 2023
- gerendert mit [CETEIcean](https://github.com/TEIC/CETEIcean)

## Kontext
- [»Rätsel um falschen Eco-Roman«](https://www.uni-siegen.de/start/news/forschungsnews/1019454.html) (uni-siegen.de, 29. September 2023)

## Scan
- Staats- und Universitätsbibliothek Bremen (SuUB) ([urn:nbn:de:gbv:46:1-162417](https://nbn-resolving.org/urn:nbn:de:gbv:46:1-162417))
- Erstellung der TEI-Version in Absprache mit der SuUB
- Lizenz: Nutzungsrechte eingeschränkt – Freier Zugriff – Nicht kommerziell

## Annotationsstrategie und Auffälligkeiten
- Ziel: TEI-Edition des Buchs als digitales Abbild mit semantischen Anreicherungen
- Auszeichnung von erwähnten historischen und fiktionalen Personen sowie literarischen Werken und Identifizierung via Wikidata-IDs (```<persName ref="http://www.wikidata.org/entity/Q160333">```, ```<rs type="work" ref="http://www.wikidata.org/entity/Q674832">```)
- keine Korrektur der orthografischen und grammatischen Fehler, aber Kennzeichnung mit `<sic>`
- die Anführungszeichen wechseln zwischen »« und „“ und wurden jeweils so belassen wie vorgefunden
- einfache Absätze ohne Leerzeile vs. Absätze mit vorstehender Leerzeile (`<p type="parskip">`)
- angebliche Zitate aus der italienischen Pseudo-Vorlage wurden in `<foreign xml:lang="it">` gefasst

## Jupyter Notebook zur Informationsextraktion aus dem TEI-Dokument
- (folgt)

## Bibliografie der Presseberichterstattung zu »Carmen Nova«
- (folgt, Zotero)

## Interessante Textschichten
- Register der erwähnte Personen und Werke (inkl. Häufigkeit der Nennungen)
- Liste der Stellen aus der pseudo-italienischen Vorlage
- …

## Quantitative Experimente
- sich wiederholende Wendungen
- längste Wörter
- …

## Vorschläge/Todo
- erwähnte Orte auszeichnen mit `<placeName>` (z. B. Italien, Moldau, New Yorker Bronx, Frankreich, Amerika, Los Angeles, San Francisco, Liffey)
- add cover pic and emblem on page 7 (`<figure>`)
- Sätze kennzeichnen mit `<s>`

## Carmen-Playlist 😊
- [auf YouTube](https://www.youtube.com/playlist?list=PLwwYoQq959IuCeUaNichLxaGfN1d03Kwz)

## Team
- Miguel Araneda Lavín, Dîlan Canan Çakir, Frank Fischer, Viktor J. Illmer, Jonas Rohe, Mark Schwindt, Bart Soethaert, Lilly Welz, Roya Zendebudie ([RA5](https://www.temporal-communities.de/research/digital-communities/) des Exzellenzclusters EXC2020 »Temporal Communities«, Freie Universität Berlin)

## Dank an
- Niels Penke (Universität Siegen)
- Maria Hermes-Wladarsch (SuUB Bremen)
- Florian Fuchs (Freie Universität Berlin)
