# Ergebnis FF1 -- Schreibplan

Wie können Container-Anwendungen den Prozess des automatisierten "Deployments" unterstützen?

1. Prozess wird generischer
   1. Egal, was der Inhalt des Containers ist
   2. Solange über die Konfigurationsdatei alles beschrieben ist
2. Aufwandskurve ist anders
   1. Container-Deploy: Aufwand am Anfang sehr hoch ... danach kaum Aufwand
   2. Standard-Deploy: Aufwand am Anfang sehr hoch ... und dann pendelt sich der Aufwand auf konstantem Niveau ein
3. Prozess lässt sich leichter kontrollieren, da die verteilten Anwendungen über eine einzige Konfigurationsdatei gesteuert werden
   1. Generierung der Konfigurationsdatei vergleichsweise zur Sammlung aller Quellen bei dem klassischen Deployment total leicht --> Python Skript max.30 Zeilen Code
4. Algorithmus zur Generierung ist ein erster Entwurf
5. Weitere Evaluierung müssen während der ersten Releasezyklen durchgeführt werden
