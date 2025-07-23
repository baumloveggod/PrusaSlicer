# Freiheitsgrade bei Baum

Das optionale Feld `baum_head_freedom` beschreibt im Expertenmodus die Geometrie des Druckkopfes. Werte werden in positiver und negativer Richtung der Achsen angegeben.

Beispiel für Prusa Mini+:

```
baum_head_freedom = "y+=37,y-=13,x+=85,x-=32,z+=25,rot=12"
```

Diese Information kann genutzt werden, um spezielle Druckstrategien für Bauteile mit versetzten Säulen umzusetzen.
