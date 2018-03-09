# ssd4tsd
Das Modell SSD4TSD ist das Ergebnis meiner Masterarbeit. Es ist in der Lage, 78 deutsche Verkehrszeichen auf eine Entfernung von 15-5 Metern zu erkennen.
# Prerequirements
- Tensorflow >= 1.3
- OpenCV
- Object Detection API

# Devolepment Scripts
- Zur Generierung der Trainingsdaten wird das Skript.. verwendet. Anstelle von Verkehrszeichen köennen beliebige andere Objekt antrainiert werden.

# Application
- Das fertige Modell mit 78 Verkehrszeichen findet Ihr hier: http://eugen-lange.de/download/ssd-4-traffic-sign-detection-frozen_inpherence_graph-pb/ 

Demonstration: https://www.youtube.com/watch?v=hcZYYu8u57A

# ROS Integration
- Das ROS_Package, das die Modelle, zur Verkkehrszeichenerkennung nutzt ist her zu finden.
