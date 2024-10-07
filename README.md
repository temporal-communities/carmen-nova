# TEI Edition of »Carmen Nova« (Pseudo Umberto Eco Novella)

## Webversion
- https://temporal-communities.github.io/carmen-nova/
- Erstveröffentlichung: 21. Dezember 2023
- gerendert mit [CETEIcean](https://github.com/TEIC/CETEIcean)

## Kontext
- [»Rätsel um falschen Eco-Roman«](https://www.uni-siegen.de/start/news/forschungsnews/1019454.html) (uni-siegen.de, 29. September 2023)

## Zitierempfehlung
- Frank Fischer, Dîlan Canan Çakir, Viktor J. Illmer, Niels Penke, Mark Schwindt, Lilly Welz: Chasing ›Carmen Nova‹: Encoding and Analysis of a TEI Version of the Crime Novella Allegedly Written by Umberto Eco. In: TEI2024: »Texts, Languages, and Communities«. 7–11 October 2024. Buenos Aires. Book of Abstracts, pp. 100–101. ([doi:10.5281/zenodo.13883242](https://doi.org/10.5281/zenodo.13883242))

## Aktuelles
- am 10. Oktober 2024 präsentieren wir das Projekt auf der TEI2024 in Buenos Aires: [»Chasing ›Carmen Nova‹: Encoding and Analysis of a TEI Version of the Crime Novella Allegedly Written by Umberto Eco«](https://www.conftool.pro/tei2024/sessions.php)

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
- erwähnte Toponyme mit `<placeName>` und Wikidata-ID ausgezeichnet (Moldau, Mallorca, New Yorker Bronx, Italien, Frankreich, England, Abendland, Los Angeles, San Francisco, Liffey); vorerst nicht ausgezeichnet wurden entsprechende Adjektive: italienisch, deutsch, afrikanisch, arabisch, amerikanisch
- Sätze mit `<s>` markiert (insgesamt 531)

## Jupyter Notebook zur Informationsextraktion aus dem TEI-Dokument
<a target="_blank" href="https://colab.research.google.com/github/temporal-communities/carmen-nova/blob/main/analysis/Carmen%20Nova.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Bibliografie der Presseberichterstattung zu »Carmen Nova«
- https://www.zotero.org/groups/5492205/carmen_nova_bibliography/library

## Interessante Textschichten
- Register der erwähnte Personen und Werke (inkl. Häufigkeit der Nennungen)
- Liste der Stellen aus der pseudo-italienischen Vorlage
- viele innovative Komposita (Stimmenarabesken, Schattentrampoline, Ereignisbusse usw.)
- gleichmäßig über den Text verteilte Rechtschreib- und Grammatikfehler, könnten auf die alleinige Autorschaft einer Person hindeuten (und auf fehlendes Lektorat)
- markante konsequente Fehlschreibungen (etwa zweimal *Pandon* statt *Pendant*)
- …

## Quantitative Experimente
- sich wiederholende Wendungen
- längste Wörter
- …

## Vorschläge/Todo
- add cover pic and emblem on page 7 (`<figure>`)

## Carmen-Playlist 😊
- [auf YouTube](https://www.youtube.com/playlist?list=PLwwYoQq959IuCeUaNichLxaGfN1d03Kwz)

## Team
- Miguel Araneda Lavín, Dîlan Canan Çakir, Frank Fischer, Viktor J. Illmer, Jonas Rohe, Mark Schwindt, Bart Soethaert, Lilly Welz, Roya Zendebudie ([RA5](https://www.temporal-communities.de/research/digital-communities/) des Exzellenzclusters EXC2020 »Temporal Communities«, Freie Universität Berlin)

## Dank an
- Niels Penke (Universität Siegen)
- Maria Hermes-Wladarsch (SuUB Bremen)
- Florian Fuchs (Princeton University)
