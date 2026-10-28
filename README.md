# Exercices de Daniel — organisation du dépôt

## Arborescence

```
daniel-<classe>/                      classe : 3eme (en cours), 4eme (archive)
├── index.md                          catalogue : thème, contenu, durée estimée, liens
└── <matiere>/                        mathematiques | physique
    ├── enonces/<theme>/              ce que Daniel reçoit
    │   ├── NN-<theme>.md (+ .pdf)
    │   └── figures/NN-figK.svg       figures des énoncés
    ├── corriges/<theme>/             ce que Daniel ne voit qu'après coup
    │   └── NN-<theme>-corrige.md (+ .pdf)
    └── sources/                      documents fournis (scans de DST, fiches du prof)
        └── AAAA-MM-JJ-<description>.pdf
```

## Nomenclature

| Élément | Règle | Exemple |
|---|---|---|
| Thème (dossier) | minuscules, sans accent, mots séparés par `-` | `identites-remarquables` |
| Énoncé | `NN-<theme>.md` — NN sur deux chiffres | `09-thales.md` |
| Corrigé | même nom + `-corrige`, rangé côté `corriges/` | `09-thales-corrige.md` |
| PDF | même nom que le `.md` dont il est issu | `09-thales.pdf` |
| Figure | `NN-figK.svg` dans `enonces/<theme>/figures/` | `09-fig3.svg` |
| Série hors format | `serie-K-<theme>.md` | `serie-2-entrainement-dst.md` |
| Source externe | `AAAA-MM-JJ-<description>.pdf` dans `sources/` | `2026-10-16-fiche-arithmetique-prof-scan.pdf` |

- **3ème** : NN est un compteur unique par matière (une feuille = un numéro, tous thèmes confondus) — le numéro suffit à désigner une feuille (« la 09 »).
- **4ème** (archive) : NN est propre à chaque thème.
- Le thème figure dans le nom du fichier : un PDF isolé (imprimé, envoyé) reste identifiable.
- Le suffixe `-corrige` est conservé malgré le dossier : impossible de confondre un corrigé égaré avec un énoncé.

## Index

- [daniel-3eme/index.md](daniel-3eme/index.md)
- [daniel-4eme/index.md](daniel-4eme/index.md)
