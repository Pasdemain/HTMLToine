# HTMLToine — Cyber Castle Defense

Tower Defense jouable sur telephone, theme medieval/futuriste, en HTML pur (un seul fichier, sans dependances).

## Demarrer

Ouvrez simplement `index.html` dans un navigateur (mobile ou desktop). Aucun build, aucune installation.

Pour tester sur telephone via le PC :
```
python3 -m http.server 8000
```
Puis sur le telephone (meme reseau) : `http://<ip-du-pc>:8000/`.

## Comment jouer

- **Vie** : nombre d'ennemis qui peuvent atteindre le donjon avant la defaite.
- **Or** : monnaie pour acheter et ameliorer des tours.
- **Vague** : touchez `VAGUE SUIVANTE` quand vous etes pret.
- **Placer une tour** : choisissez un type dans la barre du bas, puis touchez une case libre (hors chemin).
- **Vendre** : touchez une de vos tours puis `VENDRE` (recupere 60% du cout total).

## Tours

| Tour     | Cout | Specialite                       |
|----------|------|----------------------------------|
| Archer   | 30   | Medievale, basique               |
| Laser    | 55   | Tir continu rapide               |
| Plasma   | 90   | Degats de zone                   |
| Tesla    | 140  | Eclair en chaine                 |

## Ennemis

Goblins, Drones, Chevaliers, Ogres, et un Boss final reparti sur 10 vagues.

## Structure

```
HTMLToine/
├── README.md
├── CLAUDE.md
└── index.html   # le jeu complet
```

## Licence

A definir.
