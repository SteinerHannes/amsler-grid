# Interaktives Amsler-Gitter


## Struktur/Aufbau:
Das Amsler-Gitter besteht aus horizontalen und vertikalen Linien, die an ihren Überkreuzungen mit einander verbunden sind.
Jede horizontale und vertikale Linie besteht aus vielen in Reihe verbundene [Bézierkurven](https://de.m.wikipedia.org/wiki/Bézierkurve). 
Jede dieser (quadratischen) Bézierkurve besteht aus einem Start- und einem Endpunkt, sowie einem Mittelpunkt. Mit Hilfe dieser Punkte lässt sich die Krümmung der Kurve verändern. 
An einer Kreuzung befindet sich ein Knoten, mit dem die Position der Kreuzung verändert werden kann. Ein weiterer Knoten befindet sich auf dem Mittelpunkt jeder Bézierkurve, womit sich diese noch feiner justieren lassen. 

![Amsler-Grid](grid.png)

## Besonderheit:
* Größe der Canvas kann beliebig sein    
```html 
    <canvas id="grid" width="720" height="450"></canvas>
```
* Anzahl der horizontalen und vertikalen Linien kann beliebig sein
```javascript
    let amountOfHorizontalLines = 9;
    let amountOfVerticalLines = 16;
```
* Horizontale und vertikale Linien können separat unsichtbar gemacht werden

## Weitere Entwicklung:
- [ ] Amsler-Gitter aus gespeicherten Daten wiederherstellen
- [ ] Kästchen in Amsler-Gitter markieren