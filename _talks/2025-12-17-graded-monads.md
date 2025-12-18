---
title: "Monades et monades gradées : comment typer les effets des programmes fonctionnels"
collection: talks
type: "Seminar"
permalink: /talks/2025-12-17-graded-monads
excerpt : 'Talk given at the student seminar at DIENS about the general ideas of graded monads'
venue: "Ecole Normale Supérieure - PSL"
date: 2025-12-17
location: "Paris, France"

---

Les langages fonctionnels sont par essence purs : l'évaluation des termes ne produit pas d'effets. Cependant, programmer peut nécessiter des opérations plus riches, comme l'introduction d'effets de bord, qui agissent sur la mémoire de la machine. Une manière d'encapsuler les aspects impurs des programmes est la notion de monade, que l'on présentera sous son jour informatique, et qui est au centre d'un langage comme Haskell.
Cette sémantique peut être raffinée pour obtenir dans le système de types l'information de l'effet produit par le programme, grâce à la notion de monade gradée, où l'on verra que le mot effet peut avoir un sens bien plus large que les simples effets de bord. Enfin, on discutera de l'influence de la stratégie d'évaluation des arguments sur la production d'effets, et on présentera l'idée générale du système Call-by-Push-Value. 