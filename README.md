# Objekte bewegen – fliegende Kugeln

## Umsetzung
Vier Kugeln bewegen sich auf Kreisbahnen durch einen Torus. Die Kugeln sind um 90 Grad phasenverschoben und berühren sich nicht. Eine Gitterebene hilft bei der räumlichen Orientierung.

Der Torus rotiert synchron um X- und Y-Achse.

## Steuerung
- K: ein Animationsschritt bei pausierter Animation
- Leertaste: automatische Animation starten/stoppen
- R: zurücksetzen
- Buttons auf der Webseite: dieselben Funktionen

## Formel
x = R · cos(alpha + i · pi/2)
y = H · sin(alpha + i · pi/2)
z = R · sin(alpha + i · pi/2)

## Quelle
WebGL Fundamentals:
https://webglfundamentals.org/webgl/lessons/webgl-2d-rotation.html

## Test
Chrome unter macOS. K, Leertaste, R, Buttons und Browser-Konsole testen.
