# Zur [interaktiven Kurzfassung](https://smartcitystrategie.ulm.de/)

# Smart City Strategie der Stadt Ulm
Zwischen 2020 und 2021 hat Ulm im Rahmen des Förderprojektes Ulm4CleverCity eine Smart City Strategie für die Stadt entwickelt. Die Inhalte der Strategie gibt es als interaktive Kurzfassung unter [https://smartcitystrategie.ulm.de/](https://smartcitystrategie.ulm.de/) und hier auf GitHub als ausführliche Langfassung. 

## Über die Verwendung von GitHub

Das [GitHub-Verzeichnis zur "Smart City Strategie der Stadt Ulm"](https://github.com/stadtulm/smart-city-strategie) kann auch unter der folgenden Webadresse als gut les- und navigierbare Webseite abgerufen werden: 

[https://stadtulm.github.io/smart-city-strategie/](https://stadtulm.github.io/smart-city-strategie/)

Zur Generierung dieser Webseite verwenden wir [Sphinx](https://pypi.org/project/Sphinx/), [Sphinx-Book-Theme](https://github.com/executablebooks/sphinx-book-theme) und [MyST Parser](https://myst-parser.readthedocs.io/en/latest/#), die sich mit folgendem Befehl installieren lassen: 

```
pip install -r requirements.txt
```

Falls noch sowohl Python 2 als auch Python 3 installiert sind, kann es nötig sein, hier `pip3` anstelle von `pip` zu verwenden.

Die Webseite kann dann mit dem Befehl `sphinx-build -a -E -b html . ../smart-city-strategie_html/` (unter Windows Backslashes statt Slashes verwenden) bzw. mit den mitgelieferten Makefiles erstellt werden: `make html` unter GNU/Linux oder `make.bat html` unter Windows. 

## So kannst du beitragen:

Nach der Beschlussfassung durch den Gemeinderat wird die Strategie ab 2022 überarbeitet und angepasst. Wir freuen uns über Input und Anregungen. Allerdings gleich vorab: Wir werden das Dokument nicht laufend überarbeiten (da wir in den kommenden Jahren eher mit der Umsetzung beschäftigt sein werden), daher kann es eine Weile dauern, bis eine überarbeitet Fassung entsteht. 

## Über Sinn und Zweck einer Smart City Strategie 
Das Bundesministerium des Innern, für Bau und Heimat fördert in Zusammenarbeit mit der KfW Kommunen dabei, eine integrierte Smart City Strategie zu entwickeln, die bestehende Ansätze zur Digitalisierung bündelt, eine gemeinsames Verständnis und eine gemeinsame Zielrichtung der Akteure einer Stadtverwaltung schafft und aufzeigt, wo es in Zukunft hingehen soll. Durch die enge Verbindung von Digitalisierung und Stadtplanung/Städtebau sollen wichtige Zukunftsaufgaben bewältigt werden wie beispielsweise Nachhaltigkeit und Klimaschutz, Herausforderungen einer wachsenden Stadt und des sozialen Zusammenhalts. 


