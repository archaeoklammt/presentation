# Datenkuration

|  |  |
|---|---|
| date | 25-01-2022 |
| author | Anne Klammt |
| license | cc by-s.a 4.0 |

---

## Kurze Vorstellungsrunde

pad 

---

## Inhalte

----

### Modulbeschreibung

• Kunst- und Kulturobjekte als Daten erfassen („Datendenken“ ) 

• Normdaten (welche Normdaten? Wie können sie eingesetzt werden?

• Standards zur Aufbereitung von Daten (CIDOC-CRM, LIDO,…) (welche Standards gibt es? Warum sinnvoll? Wie unterscheiden sich diese Standards?)

• Überblick zu französischen Initiativen und Entwicklungen

----

### Lernziele

1. Ich verstehe, wie Kunst- und Kulturobjekte mittels beschreibenden Daten und digitalen Surrogaten erfasst werden können.

\# *Digitalisierung* \# *Metadaten*  \# *digitale surrogate* 

----

2. Ich kenne den Unterschied zwischen Ontologien und kontrolliertem Vokabular. 

Ich kann Daten anreichern, die geographische Orte, Personen, Materialien, Stile und Epochen sowie ikonographische Motive betreffen.

\# *geonames* \# *Getty AAT* \# *GND* \# *VIAF* \# *Iconclass* \# *iDAI.chronotology* \# *CIDOC-CRM*

----

3. Ich kenne zwei Austauschformate für Metadaten und kann wichtige Ansprüche an sie und Anwendungen beschreiben.  

\# *LIDO XML* \# *Linked Art data model*

----

4. Über den Vergleich mit Frankreich kann ich eine kritische Distanz gegenüber den in meiner Domäne vorherrschenden Lösungen entwickeln.

\# *Joconde* \# *pop* \# *Thesaurus iconographique* \#*Rameau* 

---

## Organisation

|  | Thema | 
|:---|:---|
| vormittags | Onboarding |
| | das Objekt beschreiben |
| | das Objekt vernetzen |
| mittags | Pause 
| nachmittags | die Objektbeschreibung standardisieren |
| | die Maschine liest mit |
| | Wrap Up |

---

## Wo und wie ?

* Olat für die Literaturablage
* Zoom als Seminarraum
* Pads zum gemeinsamen Schreiben

<hr>

* Mischung aus Input, Hands-On und Austausch

---

# *Digitalisierung* und *digitales Surrogat* 

----

> Spricht nun ein/e MuseumsmitarbeiterIn von einem digitalen Objekt, dann hat er/ sie wahrscheinlich das Wort »digital« aus fremden Zusammenhängen genommen und
ihn mit seinem Begriff von Objekt gepaart.

>Rohde-Ensslin 2020, 26

----

> ***Digital object***: Any type of electronic file. Within the context of digital repositories, most often used to describe audio, video, images, or text-based documents. 

>Abby Clobridge 2010

----

>Vielleicht wäre in diesem Fall das digitali­sierte Museumsobjekt die genauere Bezeichnung. Aber auch hier sind die Begriffe nicht geklärt : 
>Ab wann ist ein Museumsobjekt digitalisiert (oder digital)?

>Rohde-Ensslin 2020, 26

----

Schema: Evolution der Digitalisierung von Kunst- und Kulturgut 

| | |
|---|:---|
| * | Digitale Bestandserfassung | 
| ** | Digitale Verwaltung aller Informationen zum Objekt |
| *** | Digitales Surrogate des Objekts mit Beschreibungen des  Objekts und des Surrogats |
| ***\* | Gemeinsame Verwaltung von Daten zum Objekt und dem digitalen Surrogaten |
| ***** | Gemeinsame Verwaltung + Präsentation der Surrogate und Informationen |

----

> ***Digital surrogate***: A digital version of an object, one that is intended to serve as a stand-in for the object itself. Most often used when referring to works of art. Example: a .JPG image of the Mona Lisa.

Abby Clobridge 2010

----

> How many times have you said, or heard someone else say, “I saw the manuscript online” or “I consulted it online” or “I used it online”? Not pictures of the manuscript or the digitized manuscript but the manuscript? 

Dot Porter 2018

----

![Mona Lisa 2017. Foto: Artnews 2017](https://www.artnews.com/wp-content/uploads/2017/11/Crowd_looking_at_the_Mona_Lisa_at_the_Louvre.jpg)

ArtNews 29.11.2017

----

Nach Dot Porter (2018) können digitale Surrogate das Original und die Erfahrung des Originals nicht ersetzen. 
(s. a. W. Benjamin "Aura" des Kunstwerks)

**Aber !**

----

> ... this gives us something practical to aim for. ...let’s do more with 3D, RTI, and MSI to show us parts of the manuscript we can’t see under regular institutional photography, **let’s do more work using data about the manuscript to organize our flat images in new and interesting ways**, all with a mind towards informing us about that unreproducible ghost.

Dot Porter 2018

----

![PixPlot](https://yale-smithsonian.yale.edu/sites/default/files/images/pixplot-mk-sm.jpg)

---
## Metadaten 

***oder : ***

***... let’s do more work using data about the manuscript to organize our flat images in new and interesting ways...*** 

---

## Sparkling Metadata

1. Beispiel: Facettierung der Bildsuche über Iconclass in der digitalen Sammlung des Städel Museum [Link: Adam und Eva vor dem Sündenfall](https://sammlung.staedelmuseum.de/de/suche?scope=all&q=term(8849:iconclass))

2. Beispiel: Metadaten zum Trainieren von Bilderkennung und -clustering. Yale DH-Lab [Link: Meserve-Kunhardt Collection](https://yale-smithsonian.yale.edu/projects/exploring-meserve-kunhardt-collection)

----

## Metadaten ?

----

> *Imagine data as information in any form sitting on shelves, in drawers, or boxes (objects, numbers, files). Metadata provides the labels for those entities and the organizational system in which they are stored*.

Johanna Drucker 2021,52

----

Kurz gesagt: Metadaten sind Daten über Daten

----

> *For digital ressources, two levels of metadata may be required - information about the original source ( e.g painting or film) and the digital file (who made it, when, in what format, and so on)*.

Johanna Drucker 2021,52

----

Metadaten beschreiben also einerseits das digitale Surrogat und andererseits das wiedergegebene Objekt.

----

| Thema | Surrogat | Objekt |
| ------ | ------ | ------ |
| Technik    | Rasterimage, Dateiformat TIFF,..    | Öl auf Leinwand, gebrannter Ton... |
| Urheber | Photodienst Museum XY | Michelangelo |
| Größe | 45 MB | 80 x 120 m ; 320 Seiten |
| usw.... | |

Reiche Metadaten beschreiben also das digitale Surrogat und das wiedergegebene Objekt.

----

> Ohne Metadaten zur Struktur sind die Seitenabbildungen oder die Textdateien, aus denen es besteht, so gut wie wertlos. Und ohne technische Metadaten über den Digitalisierungsprozess können Leser nicht sicher sein, wie genau die digitale Version die ursprüngliche Vorlage wiedergibt.

[Deutsches METS Tutorial](https://www.loc.gov/standards/mets/METSOverview.v2_de.html), Version 2, Abruf 2021

----

### Metadaten sind domänenspezifisch

Bücher, Zeitschriften, Manuskripte etc.

* Dublin Core TM [Website https://dublincore.org/](https://dublincore.org/)
* Resource Description and Access (RDA), [RDA Registry https://www.rdaregistry.info/](https://www.rdaregistry.info/)

----

Digitale Bücher, Manuskripte etc. 

* Metadata Encoding & Transmission Standard (METS) [METS - Einführung auf Deutsch](https://www.loc.gov/standards/mets/METSOverview.v2_de.html)

----

### Metadaten beschreiben Inhalte, Strukturen, Rechte

* Deskriptive Metadaten : *Titel, Abstract, Motive, Materialien ...*
* Operationale Metadaten : *Farbprofile, Gliederung der Bestandteile, Namespace ...*
* Administrative Metadaten : *Lizensierung, Urheber ...*

---

## Hands On 

Öffnen Sie: Drottningholm, Schloss, nordwestlicher Flügelbau, Bauaufnahme, Teilaufriss, Kopie nach Carl Hårleman
[https://www.graphikportal.org/document/gpo00319478](https://www.graphikportal.org/document/gpo00319478)

----

#### Fragen

* Wo wird die Druckgrafik aufbewahrt ?
* Wer stellt das digitale Surrogat zur Verfügung ?
* Aus wievielen Teilen besteht das analoge Objekt, aus wievielen das digitale Surrogat?
* Welche Rechte liegen vor ?
* Von welchen Informationseinheiten führen Informationen zu weiteren Informationen ? Nennen Sie einige Beispiele

---

## Normdaten, um Informationen zu vernetzen

----

![Die Damstädter Madonna](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Darmstadtmadonna.jpg/139px-Darmstadtmadonna.jpg)

Gemälde: "Die Darmstädter Madonna von **Hans Holbein dem Jüngeren**" (Öl auf Holz). Renaissance. Sammlung Würth, Schwäbisch-Hall

**Person** : Hans Holbein d. J., deutscher Maler  1497/1498-1543 =  [Getty ULAN 500005259](http://vocab.getty.edu/page/ulan/500005259), [GND 118552953](https://d-nb.info/gnd/118552953), [BnF ID 12030224](https://data.bnf.fr/fr/12030224/hans_holbein/), [VIAF ID 4945401](https://viaf.org/viaf/4945401/)

----

#### Getty ULAN - Union List of Artists names

* Künstler:innen, Sammler:innen, Kurator:innen ...
* Teil der digitalen Forschungsinfrastruktur des Getty Research Institute

mehr Informationen: [http://www.getty.edu/research/tools/vocabularies/ulan/about.html](http://www.getty.edu/research/tools/vocabularies/ulan/about.html)

----

#### GND - Gemeinsame Normdatei

* Gemeinsame Normdatei der Deutschen Nationalbibliothek
* War Sammlung von Personen, Körperschaften, Werke und Themen, um Publikationen zu katalogisieren. Wird zum zentralen Knoten für Normdaten im deutschsprachigen Raum ausgebaut (-> GND4C)
* Nutzung z.B. durch Kunsthistorisches Museum Wien [Beispiel](https://www.khm.at/de/object/fe73f687e5/)

mehr: Barbara K. Fischer 2021 in den AKMB-News 

----

#### VIAF - Virtual International Authority File

* Internationale Normdatei von Bibliotheken Im Verbund des [OCLC](https://www.oclc.org) (Online Computer Library Center)

----

Gemälde: "Die **Darmstädter Madonna** von Hans Holbein dem Jüngeren" (Öl auf Holz). Renaissance. Sammlung Würth, Schwäbisch-Hall

**Werk**: GND [4331511-2](https://portal.dnb.de/opac.htm?method=simpleSearch&cqlMode=true&query=nid%3D4331511-2), VIAF [207937698/](https://viaf.org/viaf/207937698/)

Wikidata [Q455319](https://www.wikidata.org/wiki/Q455319) (*hier auch der Beleg für das gezeigte digitale Surrogat*)

----

#### Wikidata 

* Kein kontrolliertes Vokabular, sondern eine kollaborative Datensammlung.
* Wird von Google zur Verbesserung der Suche genutzt (*kleiner Kasten rechts*)
* Zentraler Datenknoten im *'Semantic-Web'*

----

![Die Damstädter Madonna](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Darmstadtmadonna.jpg/139px-Darmstadtmadonna.jpg)

Gemälde: "Die Darmstädter **Madonna** von Hans Holbein dem Jüngeren" (Öl auf Holz). Renaissance. Sammlung Würth, Schwäbisch-Hall

**Motiv**: Mutter Gottes stehend mit Christus auf dem Arm nahe an ihrer Brust

Iconclass [11F411(+5)](https://test.iconclass.org/11F41(%2B5))

----

#### Iconclass 

* Vokabular ab 1947 von Hans ... zur Beschreibung von Bildmotiven entwickelt
* Wird inzwischen als *Linked Open Data* angeboten und vom niederländischen RKD gepflegt
* u. a. vom Bildarchiv Foto Marburg verwendet

mehr: Alina Kühnl 2020

----

**Gemälde**: "Die Darmstädter Madonna von Hans Holbein dem Jüngeren" **(Öl auf Holz)**. Renaissance. Sammlung Würth, Schwäbisch-Hall

**Gemälde** : Getty AAT [300033618](http://vocab.getty.edu/page/aat/300033618), PATCOLS [12471](https://pactols.frantiq.fr/opentheso/?idc=12471&idt=TH_1) 

----

#### Getty AAT

* gehört wie ULAN zu den Werkzeugen des Getty Research Institutes
* wird seit den 1970ern entwickelt und wird Mitte der 1990er Jahren als Online-Ressource angeboten
* mittlerweile inhaltlich betreut durch ein internationales Konsortium zur Pflege und Entstehung verschiedener Übersetzungen (darunter deutsch und chinesisch)
* ca. 55.000 beschrieben Begriffe (Konzepte)

----

#### PATCOLS

* Französisches Normvokabular zur Beschreibung von Begriffen der Archäologie )
* gegliedert in 6 Bereiche: (*Peuples, Anthroponymes, Chronologie, Toponymes, Oeuvres, Lieux, Sujets*)
*  ca. 50.000 beschriebene Begriffe (Konzepte)

Webseite: [PACTOLS](https://www.frantiq.fr/pactols/le-thesaurus/)

----

Gemälde: "Die Darmstädter Madonna von Hans Holbein dem Jüngeren" (Öl auf Holz). 1526 n. Chr. **Renaissance**. Sammlung Würth, Schwäbisch-Hall

**Datierung **: Getty AAT [300021140](300021140), BnF Rameau [13318531w](https://catalogue.bnf.fr/ark:/12148/cb13318531w)

----

#### Rameau

* Vokabular zur Sacherschließung (Verschlagwortung) der Bibliotheque national de la France (BnF) und universitärer Bibliotheken
* Beschriebene Begriffe (Konzepte)

Webseite: [BnF Rameau](https://rameau.bnf.fr/)

----

![Sammlung Würth, Wikidata](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Schw%C3%A4bisch_Hall-Kunsthalle_W%C3%BCrth-_Niki_de_Saint_Phalle-04.jpg/110px-Schw%C3%A4bisch_Hall-Kunsthalle_W%C3%BCrth-_Niki_de_Saint_Phalle-04.jpg)

Gemälde: "Die Darmstädter Madonna von Hans Holbein dem Jüngeren" (Öl auf Holz). 1526 n. Chr. Renaissance. Sammlung Würth, **Schwäbisch-Hall**

* Getty TGN [7012708](http://vocab.getty.edu/page/tgn/7012708), geonames [28354581](https://www.geonames.org/2835481/schwaebisch-hall.html), GND [4053684-1](https://d-nb.info/gnd/4053684-1)

----

#### Getty TGN - Thesaurus of geographic Names Online

* Gazetteer (Verzeichnis von Toponymen und ggfs. weiteren geographischen Einheiten) des Getty Research Institute (Entwicklung und Pflege ähnlich ULAN und AAT)
* Als Linked Open Data angeboten

Webseite: [https://www.getty.edu/research/tools/vocabularies/tgn/](https://www.getty.edu/research/tools/vocabularies/tgn/)

----

#### geonames

* Gazetteer, das aus offiziellen US-amerikanischen Gazetteer hervorgegangen ist und inzwischen von einer offenen Community (wie Wiikipedia) weiter betrieben wird. 
* Sehr umfangreiche Informationen, Ortsnamen und geographische Bezeichnungen in vielen Sprachen. Keine systematische Kontrolle.
* Als Linked Open Data angeboten

Webseite: [https://www.geonames.org](https://www.geonames.org)

----

### Praxis: Daten anreichern ? (A)

* [Openrefine](https://openrefine.org) für **strukturierte Daten insbesondere Tabellen** mit Personennamen, Ortsnamen, Gattungsbegriffen etc., "einfache" Nutzung mit Wikidata, GND, Getty ULAN und AAT

Links : [Einstieg](https://openrefine.org/documentation.html) und [Reconcilation](https://docs.openrefine.org/manual/reconciling), GND mit [lobid-gnd](https://blog.lobid.org/2018/08/27/openrefine.html), Video Openrefine und [Wikidata](https://youtu.be/q8ffvdeyuNQ), Openrefine und [Getty Vocabulars](https://www.getty.edu/research/tools/vocabularies/obtain/openrefine.html)

----

### Praxis: Daten anreichern ? (B)

* [Recogito](https://recogito.pelagios.org/) um unstrukturierte Daten aus Texten (z. B. Katalogtexte) und Bildern (z.B. historische Karten, Fotografien) zu gewinnen.

Link: [10 Minuten Tutorial](https://recogito.pelagios.org/help/tutorial)

----

### Take away

* Normdaten sind festgelegte Label/Bezeichner für Entitäten (Personen, Orte, Ereignisse, Werke, ...) und Konzepte (Stil, Material, Technik, Objekttyp, Gattung, ...)
* Normdaten können maschinenlesbar sein und mit einer URI hinterlegt sein (-> Semantic Web)
* Normdaten werden oft von Bibliotheken (DNB, BnF), Museen/Sammlungen (Iconclass), Denkmalbehörden (PACTOLS) und Forschungseinrichtungen (Getty ULAN, AAT) entwickelt und betreut

---

## Ontologien, um Objekte zu beschreiben

----

> Ist der Ortsname, den Sie exportieren möchten, ein Name für den Herstellungsort oder den Standort in Ihrer Sammlung? Handelt es sich beim Personennamen um einen Künstler oder ehemaligen Besitzer des Kunstwerks?

arthistoricum.net: Graphik vernetzt zum LIDO Handbuch 

---

***Hast Du mein Schloß gesehen?***
***Sie ist rechts.***

Warum sind diese Sätze nicht eindeutig?

---

gemeinsames Vokabular : *Thesaurus*, *Namespaces*

---

*B fragt: **Hast Du mein Schloß gesehen?***

Disambiguierung durch gemeinsames Vokabular "Schloß" entspricht:
* ähnlich zu [http://vocab.getty.edu/page/aat/300005738](http://vocab.getty.edu/page/aat/300005738)
* genau wie [Wikidata Element Q16823155](https://www.wikidata.org/wiki/Q16823155)

---

*A sagt: **Ich bin rechts.***

Kontextwissen: Es geht um Fußball (*sie spielt rechts*)  oder um Politik (*sie wählt die AfD*) oder die Anordnung auf einem Foto (*sie steht rechts von der Mitte*).

Der allgemeine Begriff wird erst durch den Kontext und die darin möglichen Eigenschaften eindeutig : *Ontologie*

---

> A computational ontology is a system for organizing knowledge that describes and defines relationships among things within a domain.

Jana Millar Usiskin, Christine Walde, Caroline Winter 2020

---

Ontologien bestehen aus Klassen und Subklassen, die in definierten Beziehungen zueinander stehen und darüber Eigenschaften teilen.

---

* Fiktive Ontologie: Picasso ist eine Instanz von der Klasse *Künstler:in*, *Künstler:in* sind eine Subklasse von *Mensch*. Die Klasse Mensch hat die Eigenschaft *sterben*, also hat auch Picasso ein Todesdatum. Künstler ist keine Subklasse von HumanMadeThings und deswegen kann Picasso kein Herstellungsdatum haben.

* Fiktive Ontologie: Francois I. "korrespondiert" mit Leonardo Da Vinci. -> Leonardo Da Vinci "kennt" Francois. (Eigenschaften "korrespondiert" und "kennt" sind invers zueinander)

---








Belege:
ArtNews 2017: ArtNews, The Louvre was the ‘Most Instagrammed Museum’ in 2017. published 29.11.2017 https://www.artnews.com/art-news/news/louvre-instagrammed-museum-2017-9392/

https://www.arthistoricum.net/netzwerke/graphik-vernetzt/lido-handbuch-graphik
