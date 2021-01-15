# Bewegungsmelder
Aufgabe: Ein Piezo-Lautsprecher soll piepen, sobald eine Bewegung registriert wird.

Material: Arduino / Bewegungsmelder HC-SR501 / Breadboard / Kabel / Piezo-Lautsprecher

Lerninhalt: Spannung eines Bewegungsmelder (HC-SR501) auslesen und für eine Ausgabe verwenden.

Erklärung zum Bewegungsmelder
Der Bewegungsmelder HC-SR501, auch PIR Sensor genannt, ist sehr einfach konstruiert. Sobald er eine Bewegung detektiert, gibt er auf einem Pin eine Spannung von 5 Volt aus. Diese muss nur ausgelesen und vom Mikrocontroller verarbeitet werden.
Die Dauer des Ausgangssignals (linker Regler) und die Sensibilität (rechter Regler) kann über Drehregler eingestellt werden. (Weitere Infos unter: https://funduino.de/nr-8-bewegungsmelder#Erklaerung_zum_Bewegungsmelder)


1) Jumper ist wie auf dem Bild ganz außen: Das Ausgangssignal wird nachdem eine Bewegung detektiert wurde für eine gewisse Zeit aufrecht erhalten und danach auf jeden Fall wieder deaktiviert, auch wenn im Aktionsbereich des Bewegungsmelders noch eine Bewegung detektiert werden könnte. Nach einer gewissen Zeit wird das Ausgangssignal erneut erzeugt.

2) Der Jumper ist leicht nach innen versetzt. Das Ausgangssignal bleibt pausenlos aktiv, so lange vom Bewegungsmelder eine Bewegung detektiert wird.

Die Kunststofflinse ist nur leicht gesteckt. Wenn man sie abhebt kann man den Infrarotdetektor erkennen und man sieht anhand der Beschriftung unter der Linse, wie der Sensor verkabelt werden muss: GND ( – ), OUT (Ausgang des Signals), VCC ( + ).

Hinweis: Die neuste Version des Bewegungsmelder verzichtet auf die Jumperbrücke. Der Sensor kann über die Potentiometer direkt kalibriert werden.


Weitere Infos unter: https://funduino.de/
