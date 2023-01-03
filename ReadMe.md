### Vorlage für das Romseminar (Stand 2022/12/30)

#### Für den »Master«

Für die finale Version ist `Rom-Master` zuständig. Die Vorlage ist auf dem Stand von TeXLive 2022, d.h. die verwendeten Pakete sind aktuell. Vom System her habe ich es so wie bei der Volrlage `AGFA-Master`:

* Es gibt ein Hauptdokument, `Rom-Buch.tex`, welches im Hauptverzeichnis steht.
* In den Unterverzeichnissen `preamble`,  `content` und `bib` finden sich dann die entsprechenden Dateien der Beiträge, für das Format und für die Literatur.
* Meine Empfhelung: pro Beitrag ein separates Unterverzeicnis in `content` anlegen, was die Pflege vereinfacht.

#### Für die »Teilnehmer«

Die Teilnehmer nutzen für Ihren Beitrag die Vorlage `Rom-Teilnehmer` die identisch zur Vorlage für den Master ist (bis auf Titelseite, TOC etc.). Dabei sollten die entsprechenden Dateien umbenannt werden (etwa `Rom-Name`). Alles weitere findet sich in der Datei `My-Artikel.tex`

#### Wie bekomme ich die Vorlagen:

Für die Teilnehmer: Einfach auf das zip-File gehen (anklicken) und dann herunterladen oder auf `Code`gehen und das zip-File herunterladen. Dann werden die beiden Vorlagen heruntergeladen. Man kann dann diese entsprechend umbenennen bzw. löschen und etwa auf seinen PC entpacken. Wer `Overleaf`nutzt: Dieses dann als zip-File und als neues Projekt hochladen. 

#### Korrekturen

* 2022/12/30: 
  - `bibliography = leveldown` damit es kein eigens Kapitel wird.
  - DOI wird hinter dem Titel der zitierten Zeitschrift verrsteckt und diese blau unterlegt. Daher kann man im PDF direkt darauf zugreifen. 
  - URL weiterhin separat aber bitte URL-Date nicht vergessen in der bib-Datei mit einzutragen.
  - Mit `
  - URL weiterhin separat aber bitte URL-Date nicht vergessen in der bib-Datei mit einzutragen.
  - Mit `subsubsection{Text}` bekommt man eine Nummerierung hin aber mit anschließenden Fließtext. Will man keine Nummer haben, dann einfach die * Variante nutzen.
  - Kleine Überarbeitung der Vorlage für die Teilnehmer.
  
* 2023/01/02:
	- Aktuelle Version, d.h. Korrekturen bei den `include` Files und dem `bib` File
	- Update bei den `Rom-Teilnehmer`-Vorlage
	- Ergänzungen folgen  

#### Bei Rückfragen: 

Ulrich Groh <br>


Mail: <ulgr@math.uni-tuebingen.de>
