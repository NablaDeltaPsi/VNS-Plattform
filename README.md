
## VNS-Plattform <img src="VNS_Plattform.ico" width=30 align="right">

Python-GUI zur Berechnung der Form von Vertikalsegmenten für EQ-Plattformen

<img src="readme_images/GUI.png">

### Start

**Mit Python**  
Für alle im Header von **VNS_Plattform.py** aufgeführten, benötigten Pakete, Prüfen ob sie in der Python Distribution installiert sind (`python -m pip show <package>`) und Installieren wenn nicht (`python -m pip install <package>`). Wenn alle Voraussetzungen erfüllt sind, mit `python VNS_Plattform.py` ausführen.

**Executable für Windows-Benutzer**  
Für Windows-Benutzer ist unter Releases eine ZIP-Datei mit kompiliertem Programm verfügbar. Herunterladen, Entzippen und **VNS_Plattform.exe** ausführen.

### Hintergrund
Viele Spiegelteleskope sind zu groß, um sie äquatorial auf einem Stativ zu montieren. Stattdessen werden sie azimuthal montiert und heißen dann "Dobson" Teleskope. Um bei hohen Vergrößerungen dennoch die Sternbewegung motorisiert nachverfolgen zu können, kann die Azimut-Montierung aber auf eine sogenannte Äquatorial-Plattform (EQ-Plattform) gestellt werden. Die EQ-Plattform kippt das Teleskop wie eine "echte" äquatoriale Montierung auf einem Kegel um eine Parallele zur Erdachse und muss nur regelmäßig zurückgesetzt werden.

<img src="readme_images/Segmente_schnell.gif">

Bei der Konstruktion von EQ-Plattformen besteht das Südlager häufig aus einem Achsen- oder Zapfenlager, während Segmente auf zwei Nordlagern die Bewegung der Plattform definieren. Die Segmente können schräg an die Plattform montierte Kreissegmente oder senkrecht montierte elliptische Segmente sein. Bei letzteren ist vor allem bei höheren Breitengraden die Kraftübertragung auf die Lager besser, sie sind jedoch aufwändiger zu konstruieren und vollziehen durch Verkippen und Veränderung des Lagerpunktes eine komplexere Bewegung. Entscheidet man sich beim Bau einer EQ-Plattform für Vertikalsegmente (engl. VNS = vertical north segments) werden üblicherweise Ellipsensegmente als (meist sehr gute) Näherung verwendet. Die Ellipsensegmente müssen jedoch gemeinsam mit der Plattform konstruiert werden und sind deshalb für bereits bestehende Plattformen schwierig nachzuberechnen. Außerdem ist der Auflagepunkt auf das Lager nicht genau definiert: Die horizontale Mitte der Segmente zu nehmen ist nicht ganz korrekt, da dann die Lauflänge in Richtung der Spitzen aufgrund der größeren Steigung länger ist als in Richtung der Innenkanten.

### Verwendung
Mit diesem Programm kann man die Vertikalsegmente ohne Näherung auf die Ellipsenform auch für bestehende Plattformen berechnen und als PDF in Originalgröße druckbar abspeichern. Die Bedienung ist einfach: Die Maße der Plattform entsprechend der nebenstehenden Abbildung eintragen, bis alle rechten Felder grün sind. Es gibt mehr ausfüllbare Felder als freie Parameter, bspw. kann man entweder die Plattformbreite oder den Segmentwinkel eingeben. Beide Felder auszufüllen funktioniert nicht.

Sind schließlich alle Felder grün, kann man unter "Anzeigen" die Plattform in 3D aus verschiedenen Richtungen betrachten, sowie unter "GIF" die obenstehende Animation erzeugen. Unter PDF & DATA werden PDFs (DIN A3, A4 und A5) der Segmente erzeugt. Die vertikale Linie bzw. x=0 definiert dabei den Punkt an dem die Senkrechte vom Südlager das Segment schneiden sollte, und somit die Position der Segmente an der Plattform. Man beachte dass x=0 nicht in der horizontalen Mitte des Segments liegt, sondern etwas in Richtung Segmentspitzen verschoben! Mit abgespeichert werden außerdem Textdateien mit Daten zu den Entwicklungen der Nachführ-Geschwindigkeit und der Position der Segmente auf den Lagern sowie die Form der Segmente als Datentabelle.

<img src="readme_images/Output_files.png">

<img src="readme_images/Output_pdf.png">

### Vergleich
Nun kann man nicht nur Segmente für die eigene Plattform berechnen, sondern auch mit den Parametern experimentieren und ihren Einfluss auf die Segmentform bzw. das Verhalten der Plattform analysieren:

<img src="readme_images/Comparison.png">
