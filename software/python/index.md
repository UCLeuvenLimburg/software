---
layout: default
---
# Python

Installeer de recentste versie van [Python](https://www.python.org/downloads/) (64 bit indien je de keuze krijgt).

TODO: `$ python -v` moet correcte versie tonen
TODO: hello world scriptje laten runnen vanop command line
TODO: check dat pip install werkt (vermoedelijk liefst op de challenges package die ontwikkeld wordt, die gaan ze nodig hebben)

Potentiële moeilijkheden:

* Installatie is zeer OS-gevoelig. Op Windows best werken met `py` om Python op te roepen, op MacOS roept `python` Python2 op en moet er gewerkt worden met `python3`. Linux is weer wat anders.
* Vanaf Win10 is er een `python` stub die als die opgeroepen wordt de gebruiker leidt naar de Windows Store. Typisch laat ik ze hun `PATH` variabele aanpassen zodat die stub niet meer opgeroepen wordt, want die zorgt voor heel wat miserie (ze gaan 2 Pythons staan hebben en de pip installeert dingen op de ene versie terwijl python oproepen de andere versie oproept, etc.)
