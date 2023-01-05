Python-GUI zur Berechnung der Form von Vertikalsegmenten für EQ-Plattformen

Für Windows-Benutzer ist unter Releases eine ZIP-Datei mit kompiliertem Programm verfügbar. Zum Starten nach Herunterladen und Entzippen "VNS_Plattform_GUI.exe" ausführen.

![grafik](https://user-images.githubusercontent.com/98178269/210774645-85dcd5cc-68c8-4dda-9c1a-00cfeb49049e.png)

Viele Spiegelteleskope sind zu groß, um sie äquatorial auf einem Stativ zu montieren. Stattdessen werden sie azimuthal montiert und heißen dann "Dobson" Teleskope. Um bei hohen Vergrößerungen dennoch die Sternbewegung motorisiert nachverfolgen zu können, kann die Azimut-Montierung aber auf eine sogenannte Äquatorial-Plattform (EQ-Plattform) gestellt werden. Die EQ-Plattform kippt das Teleskop wie eine "echte" äquatoriale Montierung auf einem Kegel um eine Parallele zur Erdachse und muss nur regelmäßig zurückgesetzt werden.

Bei der Konstruktion von EQ-Plattformen besteht das Südlager häufig aus einem Achsen- oder Zapfenlager, während Segmente auf zwei Nordlagern die Bewegung der Plattform definieren. Die Segmente können schräg an die Plattform montierte Kreissegmente oder senkrecht montierte elliptische Segmente sein. Bei letzteren ist vor allem bei höheren Breitengraden die Kraftübertragung auf die Lager besser, sie sind jedoch aufwändiger zu konstruieren und vollziehen durch Verkippen und Veränderung des Lagerpunktes eine komplexere Bewegung. Entscheidet man sich beim Bau einer EQ-Plattform für Vertikalsegmente (engl. VNS = vertical north segments) werden üblicherweise Ellipsensegmente als (meist sehr gute) Näherung verwendet. Die Ellipsensegmente müssen jedoch gemeinsam mit der Plattform konstruiert werden und sind deshalb für bereits bestehende Plattformen schwierig nachzuberechnen. Außerdem ist der Auflagepunkt auf das Lager nicht genau definiert: Die horizontale Mitte der Segmente zu nehmen ist nicht ganz korrekt, da dann die Lauflänge in Richtung der Spitzen aufgrund der größeren Steigung länger ist als in Richtung der Innenkanten.

Mit diesem Programm kann man die Vertikalsegmente ohne Näherung auf die Ellipsenform auch für bestehende Plattformen berechnen und als PDF in Originalgröße druckbar abspeichern. Mit abgespeichert werden außerdem die Entwicklungen der Ablauf-Geschwindigkeit und der Position der Segmente auf den Lagern.

3D-Ansicht der Plattform mit berechneten Segmenten:

![611d04_fb9863da12954d2ea040b54abf5b4810~mv2](https://user-images.githubusercontent.com/98178269/210785812-c19b3f93-cd64-4d1b-8ea3-df56e2a87cb7.gif)

PDF der Segmente in Originalgröße:

![grafik](https://user-images.githubusercontent.com/98178269/210576156-a3bcfdf3-93e8-4956-ad13-232114d9f376.png)

Änderung der Segmente mit den Parametern:

![Segmente_klein](https://user-images.githubusercontent.com/98178269/210732111-be4c0c6b-e834-4fec-8e6b-9260b7e00e0b.png)
