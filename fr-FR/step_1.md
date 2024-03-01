La fonction `list()` **renvoie** une liste que tu peux utiliser dans ton code.

**Renvoyer une liste vide**

Si tu utilises la fonction `list()` sans **paramètre** dans les parenthèses, elle **renverra** une liste vide.

Voici un exemple de la fonction `list()` utilisée **sans paramètre**.

```python
print(list())
```

Le résultat de ce code sera :

```
[]
```

En effet, la fonction `list()` a **renvoyé** une liste vide.

**Convertir une chaîne en liste**

Tu peux utiliser la fonction `list()` pour convertir une chaîne en liste.

Par exemple, tu pourrais avoir une **variable** qui contient les voyelles de l'alphabet anglais. Pour la convertir en liste, tu dois **transmettre** la variable `voyelles` via les **paramètres** (parenthèses) et la fonction la renvoie sous forme de liste.

Tu peux voir cela se produire à la **ligne 2** dans l'exemple de code ci-dessous :

--- code ---
---
language: python filename: main.py line_numbers: true line_number_start: 1
line_highlights: 2
---
vowels = 'AEIOU' # The variable holds a string of vowels vowel_list = list(vowels) # Create a list that holds each vowel as a separate item print(vowel_list) # Display the list of vowels --- /code ---

Le résultat de ce code sera :

```
['A', 'E', 'I', 'O', 'U']
```





