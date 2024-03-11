De `list()` functie **maakt** een lijst die je kunt gebruiken in je code.

**Het teruggeven van een lege lijst**

Als je `list()` gebruikt zonder **parameters** tussen de gebogen haakjes, zal dit een lege lijst **opleveren**.

Hier is een voorbeeld van `list()` die wordt gebruikt **zonder parameters**.

```python
print(list())
```

De uitvoer van deze code zou zijn:

```
[]
```

Dit komt omdat de `list()` functie een lege lijst heeft **teruggegeven**.

**Een string omzetten in een lijst**

Je kunt de functie `list()` gebruiken om een string in een lijst om te zetten.

Je hebt bijvoorbeeld een **variabele** die de klinkers van het Engelse alfabet bevat. Om dit in een lijst om te zetten, moet je de `klinkers` variabele **doorgeven** via de **parameters** (ronde haakjes) en de functie zal het als een lijst retourneren.

Je kunt dit zien in **regel 2** in het onderstaande code voorbeeld:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 2
---
klinkers = 'AEIOU' # De variabele bevat een reeks klinkers
klinker_lijst = list(klinkers) # Maak een lijst waarin elke klinker als afzonderlijk item wordt vermeld
print(klinker_lijst) # Geef de lijst met klinkers weer
--- /code ---

De uitvoer van deze code zou zijn:

```
['A', 'E', 'I', 'O', 'U']
```





