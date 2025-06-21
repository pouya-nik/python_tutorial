# Python für Java-Entwickler

In diesem Dokument bekommst du eine kurze Einführung in Python mit Fokus auf Gemeinsamkeiten und Unterschiede zu Java. Anschließend findest du einige Aufgaben, um das Gelernte zu üben.

## 1. Unterschiede und Gemeinsamkeiten

- **Syntax**: Python setzt stark auf Einrückungen, um Blöcke zu definieren, während Java geschweifte Klammern verwendet.
- **Variablentypen**: Python ist dynamisch typisiert. Du musst den Datentyp bei der Variablendeklaration nicht angeben.
- **Klassen und Objekte**: Auch in Python kannst du Klassen definieren und Objekte erzeugen. Die Syntax ist schlanker, aber das Konzept ist dem in Java ähnlich.
- **Fehlerbehandlung**: Python nutzt `try`/`except`-Blöcke anstelle von `try`/`catch`.

## 2. Beispiel: Eine einfache Klasse

```python
class Hund:
    def __init__(self, name):
        self.name = name

    def bellen(self):
        print(f"{self.name} bellt")

rex = Hund("Rex")
rex.bellen()
```

## 3. Aufgaben zum Üben

1. Installiere Python (falls noch nicht geschehen) und führe das obige Beispiel aus.
2. Erstelle eine Klasse `Auto` mit einem Attribut `marke` und einer Methode `fahren()`.
3. Schreibe eine Funktion `fibonacci(n)`, die die ersten `n` Zahlen der Fibonacci-Folge als Liste zurückgibt.
4. Lese eine Textdatei ein und zähle, wie oft jedes Wort vorkommt (Tipp: Verwende ein Dictionary).

Viel Erfolg beim Lernen!
