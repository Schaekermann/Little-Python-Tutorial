# Python Tutorial
erstellt mit http://stackit.io/app
## Vergleich zu Java und C
- C-Quelltext wird zu einem Executable compiliert
- Java-Quelltexte werden zu class-Dateien compiliert, die von der virtuellen Maschine ausgeführt werden.
- Python ist eine Skriptsprache. Quelltexte werden vom Python-Interpreter ausgeführt.

## Arbeitsumgebung
- Es reicht eine Python-Installation mit IDLE zum Editieren und Ausführen
- Eine portable Entwicklungsumgebung ist Thonny
- Auch für VS Code gibt es Python-Erweiterungen

## Python Quelltexte
- definieren **Variablen ohne Angabe des Datentyp** und haben **kein Semikolon** am Ende einer Anweisung
```
zaehler=0
```
- haben **keine geschweiften Klammern** aber **verbindliche Einrückungen** im Quelltext für Anweisungsblöcke
```
zaehler=0
while zaehler <10:
	print(zaehler)
	zaehler+=1
print("Das waren die Ziffern von 0 bis 9.")	
```
- können über **import-Anweisungen** mit vielen Funktionen aus nachinstallierten Pakteten erweitert werden.

https://pypi.org/project/face-recognition/
```
import face_recognition
image = face_recognition.load_image_file("your_file.jpg")
face_locations = face_recognition.face_locations(image)
```

