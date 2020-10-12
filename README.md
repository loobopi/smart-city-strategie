# Smart City Strategie der Stadt Ulm
Hier macht sich die Stadt Ulm auf den Weg, eine Smart City Strategie zu entwickeln. Wir sind dankbar für Anregungen, Kritik und Input

## Ein paar Worte vorneweg...
Das hier ist der Versuch, eine Strategie zu schreiben und den Entwicklungsprozess für alle Interessierten via GitHub zu öffnen. Wir probieren das zum ersten Mal, wir sind ein kleines Team - aber wir haben Lust auf die Diskussion hier. Also seht uns bitte nach, wenn etwas nicht perfekt funktioniert! Manöverkritik und Vorschläge zum Handling gerne ins Issue Manöverkritik.

## Über die Verwendung von GitHub

Das [GitHub-Verzeichnis zur "Smart City Strategie der Stadt Ulm"](https://github.com/stadtulm/smart-city-strategie) kann auch unter der folgenden Webadresse als gut les- und navigierbare Webseite abgerufen werden: 

[https://smartcitystrategie.ulm.dev/](https://smartcitystrategie.ulm.dev/)

Zur Generierung dieser Webseite verwenden wir [Sphinx](https://pypi.org/project/Sphinx/), [Sphinx-Book-Theme](https://github.com/executablebooks/sphinx-book-theme) und [MyST Parser](https://myst-parser.readthedocs.io/en/latest/#), die sich mit folgendem Befehl installieren lassen: 

```
pip install -r requirements.txt
```

Falls noch sowohl Python 2 als auch Python 3 installiert sind, kann es nötig sein, hier `pip3` anstelle von `pip` zu verwenden.

Die Webseite kann dann mit dem Befehl `sphinx-build -a -E -b html . ../smart-city-strategie_html/` (unter Windows Backslashes statt Slashes verwenden) bzw. mit den mitgelieferten Makefiles erstellt werden: `make html` unter GNU/Linux oder `make.bat html` unter Windows. 

Wenn du einen Beitrag zum Smart City Strategie Projekt erstellen willst, würden wir uns freuen, wenn du wie folgt vorgehst: 

•	Du hast einen konkreten Textvorschlag zu einem der Textbausteine der Strategie: Bringe deine Änderungen über einen Pull Request ein. Du kannst deinen Vorschlag in der Commit Message begründen.
•	Du hast KEINEN konkreten Textvorschlag, aber eine Idee, eine Frage oder würdest gerne diskutieren: Bitte bezieh dich wenn möglich auf eine bestimmte Stelle im Strategietext und mach ein Issue auf bzw. schließe dich einem bestehenden Issue an.
•	Du hast eine inhaltliche Nachfrage: Mache ein Issue auf oder kontaktiere uns per Mail über zukunftsstadt@ulm.de



## Über Sinn und Zweck einer Smart City Strategie 
Das Bundesministerium des Innern, für Bau und Heimat fördert in Zusammenarbeit mit der KfW Kommunen dabei, eine integrierte Smart City Strategie zu entwickeln, die bestehende Ansätze zur Digitalisierung bündelt, eine gemeinsames Verständnis und eine gemeinsame Zielrichtung der Akteure einer Stadtverwaltung schafft und aufzeigt, wo es in Zukunft hingehen soll. Durch die enge Verbindung von Digitalisierung und Stadtplanung/Städtebau sollen wichtige Zukunftsaufgaben bewältigt werden wie beispielsweise Nachhaltigkeit und Klimaschutz, Herausforderungen einer wachsenden Stadt und des sozialen Zusammenhalts. 
* Also planen statt einfach machen? - Kommunen sind große Tanker, die etwas länger brauchen zum manövrieren. Corona hat uns gezeigt, dass wir diese Zeit aber nicht immer haben. Eine Strategie kan klarer machen, wohin es gehen soll, Entscheidungswege verkürzen und vor allem: Eine Stadt widerstandsfähiger gegen Krisen machen. 
* Silos aufbrechen und mehr zusammenarbeiten ist ein weiterer Vorteil einer gemeinsamen, stadtweiten Strategie 
* Und last but not least: BürgerInnen, ExpertInnen, Politik, Verwaltung, Wissenschaft und viele andere Akteure können über einen städtischen Strategieprozess mitbestimmen, wohin es in Zukunft gehen soll 

## Woher kommt der Input?
Der Input für die Strategie ist möglichst breit gefächert. Unter anderem sind folgende Personen/ Institutionen eingebunden:
* Die Ulmer BürgerInnen und lokale Akteure wie Vereine und Initiativen werden online und offline in verschiedenen Beteiligungsformaten einbezogen
* Wir binden die Politik, beispielsweise unsere GemeinderätInnen, mit ein, die letzten Endes über die Verabschiedung der Strategie entscheiden
* Wissenschaftliche Begleitforschung: Wir werden von drei Instituten begleitet, die uns mit Rat fachlicher Expertise zur Seite stehen und jeweils einen anderen Fokus einbringen. Das sind: Urban Catalyst für städtebauliche Fragen, das Wuppertal Institut für das Thema Nachhaltigkeit, und Fraunhofer IESE für Stadt/Land, Wissenstransfer und KPIs. 
* Fachbeirat: ExpertInnen aus ganz Deutschland geben über den Fachbeirat Input für unseren Strategieprozess 
* Lenkungsgruppe und Koordinierungsgruppe sind mit Schlüsselpersonen aus den unterschiedlichen Bereichen der Stadtverwaltung besetzt und treffen zum Teil die kurzfristigen Entscheidungen im Projekt. Über verschiedene andere Kanäle und Formate sind auch VerwaltungsmitarbeiterInnen unterhalb der Leitungsebene eingebunden und können Input geben. 
* Die anderen Modellprojekte: Momentan gibt es in der aktuellen Förderstaffel 13 Modellprojekte in ganz Deutschland. Mit den KollegInnen der anderen Städte stehen wir im regelmäßigen Austausch und teilen Best und Worst Practice. 
* ... last but not least: Die Textentwürfe werden von der Digitalen Agenda und unseren Projektpartnern von City&Bits verfasst

## Wer entscheidet? 
Wir hoffen, die Strategie in einem kooperativen Prozess mit den verschiedenen beteiligten Akteuren verfassen zu können. Je mehr Menschen mitdenken und ihre Sicht einbringen, desto besser wird dieses Dokument am Ende werden. Aber: Beim Schreiben einer Strategie mit einer realistischen Chance auf Umsetzung gibt es Sachzwänge, Ressourcenmangel und die Notwendigkeit von guter Zusammenarbeit. Wenn ein Vorschlag den Förderbedingungen unseres Fördermitelgebers entgegen steht, werden wir ihn nicht aufnehmen können. Wenn die Mitarbeitenden einer Abteilung oder die BürgermeisterInnen des Bereichs, die für die Umsetzung verantwortlich sein wird, einen Vorschlag nicht mittragen können, werden wir ihn nicht aufnehmen können. Wenn die vorhandenen Mittel nicht ausreichen, um Vorschläge umzusetzen, werden wir sie nicht aufnehmen können. In letzter Instanz entscheidet der Gemeinderat der Stadt Ulm über die Verabschiedung der Strategie. 

## Wie sieht die Timeline aus? 
Vorläufig ist folgendes Vorgehen geplant (Work in Progress):  

### 2020
* April-Juli: Erste Konsultation der Fachabteilungen; Vorstellung des Projekts; Abholen von Input
* Juli-August: Erster Entwurf der Strategiekapitel 1&2
* August-September: Feedback Strategiekapitel 1&2 über GitHub und zukunftsstadt-ulm.de 
* August-September: Erster Entwurf der Handlungsfelder
* Anfang Oktober: Fachabteilungen bekommen Handlungsfelder zum Gegenlesen
* Mitte Oktober: Fachbeirat spricht über Strategiekapitel 1&2 und Handlungsfelder
* Ende Oktober: Feedback Handlungsfelder über GitHub und zukunftsstadt-ulm.de 
* tbd: Beteiligungsveranstaltung zu Handlungsfeldern 
* Dezember: Lenkungsgruppe mit allen Bürgermeistern berät über bisherigen Entwurf   

### 2021
* Umsetzungskonzept wird entwickelt
* tbd: Weitere Beteiligungsmöglichkeiten für BürgerInnen und Fachabteilungen 
* Oktober: Entscheidung des Gemeinderates über die Strategie 