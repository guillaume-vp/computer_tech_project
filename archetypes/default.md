---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
begin:
end:
---


# Niveau de titre H1

Ceci est un paragraphe

Ceci est un autre paragraphe avec de l'*italique* et du **gras**.

## Niveau de titre H2
### Niveau de titre H3

[Ceci est un lien](http://www.google.com/)

Voici un exemple de liste :

- Yaourts
+ Crème fraiche
* Saucisson

On peut également créer des listes ordonnées :

1. Bière
2. Whisky
  - Single Malt

Et on peut aussi créer des tableaux (c'est magique le markdown)

| Colonne 1 | Colonne 2 | Colonne 3 |
| -------- | -------- | -------- |
| J'        | aime     | Les tableaux   |
| C'est     | du       | contenu  |