# GraphTP2

TP de théorie des graphes (licence d'informatique) : **optimisation du coût d'un réseau de fibre optique**.

## Description

Le réseau est modélisé par un graphe non orienté pondéré. Le programme calcule un **arbre couvrant de poids minimal** avec l'algorithme de **Kruskal** (Boost Graph Library), puis exporte le résultat au format Graphviz.

- `rendue.cpp` — construction du graphe, appel à `kruskal_minimum_spanning_tree`, export DOT
- `resultat.dot` / `resultat.png` — l'arbre couvrant obtenu
- `données/` — l'énoncé du TP

## Technologies utilisées

C++ · Boost Graph Library · Graphviz

## Compiler et lancer

```bash
g++ rendue.cpp -o tp2
./tp2
dot -Tpng resultat.dot -o resultat.png
```

## Contact

**Auteur :** resendecode
**GitHub :** [github.com/resendecode](https://github.com/resendecode)
