# Freiheitsgrade bei Baum

Im Expertenmodus lassen sich die Freiheitsgrade des Extruderkopfes über mehrere Optionen beschreiben.
Folgende Parameter stehen zur Verfügung:

```
extruder_clearance_x_pos
extruder_clearance_x_neg
extruder_clearance_y_pos
extruder_clearance_y_neg
extruder_clearance_height
```
Die Werte geben den maximalen Ausladungsabstand des Extruders vom Düsenmittelpunkt in den jeweiligen Achsrichtungen an.

Beispiel für Prusa Mini+:

```
extruder_clearance_x_pos = 85
extruder_clearance_x_neg = 32
extruder_clearance_y_pos = 37
extruder_clearance_y_neg = 13
extruder_clearance_height = 25
```

Diese Information kann genutzt werden, um spezielle Druckstrategien für Bauteile mit versetzten Säulen umzusetzen.
