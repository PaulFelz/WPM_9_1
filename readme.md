# Datenintensive und datenfokussierte Aktivitäten in der Stadtbibliothek Gelsenkirchen

## Einleitung

Die Digitalisierung ermöglicht in der heutigen Zeit einen äußerst effizienten Informationsaustausch. Diese Entwicklung ist im so genannten Informationszeitalter unverzichtbar und Institutionen wie Stadtbibliotheken 
machen sich die Möglichkeiten Informationen über Netzwerke, zwischen Datenbanken oder einfach zwischen zwei Computern zu senden zunutze, um diese Informationen innerhalb der eigenen Strukturen auszutauschen, oder 
sogar von anderen Betrieben zu beziehen. Dadurch können Synergien geschaffen werden, die effizienteres Arbeiten und natürlich Aktualisierungen von Informationen sehr viel schneller zu erhalten, ermöglicht. Zudem 
können bestimmte Arbeitsschritte dahingehend automatisiert werden.   
Die Stadtbibliothek Gelsenkirchen bezieht Daten über bestimmte Schnittstellen von externen Institutionen und Firmen, um diese innerhalb der eigenen Organisation weiterzuverwenden und für eigene Zwecke 
aufzubereiten. Des Weiteren nutzt die Stadtbibliothek die digitale Infrastruktur der Stadt, um Informationen zwischen dem Bibliothekspersonal auszutauschen. Diese Datenhaltungen und Datenflüsse sollen im folgenden 
beschrieben werden, um im Anschluss ein Beispiel herauszustellen, das zur Verbesserung noch genauer beleuchtet wird. 

## 1. Datenströme und -vorhaltungen in der Stadtbibliothek Gelsenkirchen

Die Stadtbibliothek Gelsenkirchen bezieht von der DNB, dem hbz, der DiviBib und der ekz bestimmte Daten, um diese für eigene Zwecke weiterzuverwenden. Des Weiteren werden über einige Netzlaufwerke Daten zwischen dem 
Bibliothekspersonal, über andere aber auch zwischen Bibliotheksnutzern ausgetauscht. Das Content Management System (CMS) Sharepoint dient als so genanntes Wiki, wodurch ebenfalls Informationen bereitgestellt und 
zur Recherche direkt vom Personal hinterlegt werden können. Die Stadtbibliothek Gelsenkirchen sammelt, katalogisiert und verwaltet ihren Bestand mit dem 
Bibliothekssystem [BIBDIA](https://www.axiell.de/bibdia/) von der Firma AXIELL. 

  ### 1.1 Import von Metadaten aus der Deutschen Nationalbibliothek und dem Hochschulbibliothekszentrum NRW in den OPAC der Stadtbibliothek Gelsenkirchen

Um die Katalogisierung der neu eingegangenen Medien der Stadtbibliothek effizient zu gestalten, werden die Titel- und Normdaten aus der Deutschen Nationalbibliothek (DNB) 
heruntergeladen. Anstatt sämtliche Normdaten aus dem vorliegenden Medium zu autopsieren, wird der [Datenshop](https://www.dnb.de/DE/Header/Hilfe/datenshop.html) der DNB genutzt um die Metadaten direkt ins 
Bibliothekssystem zu laden. Hierfür wird das maschinenlesbare Austauschformat [MARC21](https://www.dnb.de/DE/Standardisierung/Formate/MARC21/marc21_node.html) verwendet. 
Des Weiteren sei erwähnt, das zur Kataloganreicherung, auch [Catalogue Enrichment](https://www.hbz-nrw.de/produkte/digitalisierung/catalogue-enrichment) genannt, zum größten Teil das Angebot des 
[Hochschulbibliothekszentrum NRW](https://www.hbz-nrw.de/ueber-uns) (hbz) genutzt wird. Auch hier werden mit MARC21 bspw. Inhaltsverzeichnisse oder Buchcover geladen. Nach kurzer Korrespondenz mit der 
Projektkoordination Catalogue Enrichment* gibt es jedoch keine sonderlich hohe Priorität zur Digitalisierung der Buchcover. Dies führt zu einem Mangel an Bildern und es musste eine andere Lösung gefunden werden, damit 
für möglichst jedes Medium auch ein Buchcover angeboten werden kann. Aufgrund dessen hat die Stadt Gelsenkirchen einen Vertrag mit Amazon geschlossen. Dies ermöglicht der Stadtbibliothek eine Verlinkung auf ihre 
Buchcover. Wenn der [OPAC](https://katalog.stadtbibliothek-ge.de/opax/de/qsim.html.S) aufgerufen wird und eine beliebige Suche durchgeführt wird, kann davon ausgegangen werden, das ein Großteil der bereitgestellten 
Coverbilder von Amazon ist. Ein Klick auf ein Cover führt dann zu dem Titel auf der Website von Amazon. Dies wird in der Bibliothekslandschaft [kontrovers diskutiert](https://www.kribiblio.de/?p=681), aber auch von Nutzer*innen unter Umständen als [kritisch 
wahrgenommen](https://www.bib-info.de/verband/publikationen/aktuell.html?tx_ttnews%5Btt_news%5D=4524&cHash=d764971a32) 

*E-Mailkorrespondenz hat Sperrvermerk - wird auf Anfrage gern zugesendet
 
  ### 1.2 Import von Fremddaten der Digitale Virtuelle Bibliotheken der ekz Gruppe in den Katalog der Stadtbibliothek Gelsenkirchen 

Einen anderen Bezugsweg für Metadaten im Bibliothekskatalog haben die digitalen Medien. Titel- und Normdaten für die im OPAC ausgewiesenen eBooks, ePapers, eAudios u.a. werden über 
die [Onleihe](http://www.onleihe.net/) bezogen. Die Onleihe gehört zur [Digitale Virtuelle Bibliotheken](http://www.onleihe.net/unternehmen.html) (divibib), welche zur so genannten [ekz 
Gruppe](http://www.onleihe.net/unternehmen/die-ekz-gruppe.html) gehört. Für die Titel der Onleihe werden sämtliche Metadaten im MAB/MARC Format von der divibib bereitgestellt. Die Stadtbibliothek bezieht auch hier für 
sämtliche lizensierten Titel die Titeldaten im MARC21 Format, um sie im eigenen OPAC zu präsentieren. Jedoch werden bspw. keine Buchcover mit bezogen, sondern auf der Ergebnisseite ein Hinweis "Downloadtitel" 
angezeigt. Ein Link auf derselben Seite mit der Bezeichnung "Titel nur digital verfügbar; zur Ausleihe bitte hier klicken!" fürht dann auf die [externe 
Seite](https://ebib.onleihe.de/gelsenkirchen/frontend/welcome,51-0-0-100-0-0-1-0-0-0-0.html) der Onleihe. Diese Website wird nicht von Gelsenkirchen selbst gehostet, sondern die Divibib präsentiert hier die 
lizenzierten Titel der Stadtbibliothek Gelsenkirchen. Dort finden sich dann auch viele Kataloganreicherungen, die Nutzer*innen ausführlichere Informationen bieten, als die vom OPAC.

  ### 1.3 Datenaustausch über Netzlaufwerke innerhalb der internen Abteilungen der Stadtbibliothek und dem Computerraum

Um Daten innerhalb der Abteilungen der Stadtbibliothek auszutauschen gibt es einen Netzwerkordner. Dieser Netzwerkordner hat eine Speicherkapazität von ca. 1,5TB und muss sämtliche Dokumente, Bilder, 
Filmmaterialien, Logos etc. vorhalten. Die Stadtbibliothek bietet so an jedem ihrer Arbeitsplätze denselben Zugriff auf die vorgehaltenen Daten an. Im Netzwerkordner können sämtliche Daten vom gesamten Personal 
der Stadtbibliothek eingesehen und verändert werden. Ein [RAID](https://www.elektronik-kompendium.de/sites/com/1001011.htm) unterstützt die Datensicherheit und kann bei einem kritischen Ausfall der Hardware einen 
Verlust verhindern. Das Netzlaufwerk steht für das gesamte Referat 40 Bildung zur Verfügung. Jedoch sind die jeweiligen Partitionen für die Abteilungen Schul-IT, Schulverwaltung, Schulwesen, Stadtbibliothek und 
Volkshochschule nur von den Abteilungen einzusehen. Ein Mitarbeiter der Stadtbibliothek hat bspw. keinen Zugriff auf die anderen vier Partitionen des Netzlaufwerks.
Des Weiteren gibt es ein Netzlaufwerk für den Computerraum namens [log in](https://stadtbibliothek.gelsenkirchen.de/Homepage/Bibliotheken/Medienzentrum/login.asp). Hier kommt das so genannte [Sneaker 
Net](https://www.bet.de/lexikon/sneakernet/) zum Einsatz. Eine externe Festplatte wird wöchentlich an den Server des log ins angeschlossen und sämtliche Daten aus dem Netzlaufwerk werden darauf gesichert. Dies ist 
aufgrund der eingeschränkten Funktionen des Windows Explorers mühselig und die Problemstellung soll im zweiten Punkt genauer behandelt werden.

  ### 1.4 Bereitstellung von Informationen über das Content Management System Sharepoint zu internen Zwecken
 
Das [Content Management System](https://wirtschaftslexikon.gabler.de/definition/content-management-system-cms-31303) CMS [Sharepoint](https://products.office.com/de-de/sharepoint/collaboration) dient als 
[Enterprise Wiki](https://it-service.network/blog/2017/07/20/enterprise-wiki-chancen-und-risiken/). Hier wird bibliotheksinternes Wissen vorgehalten, gepflegt und aktualisiert. In Wikipedia Form kann das Personal 
spezielles Wissen für die Allgemeinheit innerhalb der Stadtbibliothek aufbereiten. Von Anleitungen zu Mahnfällen bis zum Umgang mit dem 3D-Drucker ist hier Spezialwissen des Bibliothekspersonals vorgehalten und 
durchsuchbar gemacht.  


## 2. Implementierung eines Backupprogramms für den Netzwerkordner des Computerraums

Chancen, Nutzen, Herausforderungen, Ablauf, Routinebetrieb


## Reflexion


