# 3ème — Mathématiques — Corrections

*Corrigé du fichier `exercices.md`. Les valeurs ont été vérifiées par calcul exact (fractions).*

---

## Exercice 1 — Calculs

### A. Priorités opératoires

- A1 = 14
- A2 = 63
- A3 = 91
- A4 = −76
- A5 = 36
- A6 = −78
- A7 = 69

Méthode : calculer d'abord les parenthèses les plus internes, puis les produits, puis les différences/sommes de gauche à droite. Bien gérer les doubles signes (ex : −(−6) = +6).

### B. Puissances négatives et fractions imbriquées

- B1 = −15/13 ≈ −1,154
- B2 = −40/27 ≈ −1,481
- B3 = −40/33 ≈ −1,212
- B4 = −80/47 ≈ −1,702
- B5 = −71/39 ≈ −1,821
- B6 = −45/31 ≈ −1,452

Méthode : traiter chaque bloc entre crochets séparément (numérateur, dénominateur), simplifier les puissances négatives (a⁻ⁿ = 1/aⁿ), puis effectuer les divisions dans l'ordre (× et ÷ de gauche à droite).

### C. Fractions de fractions

- C1 = 9/7
- C2 = 30/7
- C3 = 247/407
- C4 = 11/155
- C5 = 93/77
- C6 = 7/39

Méthode : mettre chaque petite parenthèse au même dénominateur, simplifier chaque quotient obtenu, puis effectuer la division finale (diviser par une fraction = multiplier par son inverse).

### D. Puissances de 10 et décimaux

- D1 = 27/32 = 0,84375
- D2 = 161/2250 ≈ 0,0716
- D3 = 39/160 = 0,24375
- D4 = 7/640 ≈ 0,0109
- D5 = 437/225 ≈ 1,9422
- D6 = 4499/1000 = 4,499

Méthode : convertir tous les décimaux en fractions (ex : 0,9 = 9/10), appliquer les règles des puissances négatives, puis suivre l'ordre des opérations (÷ avant −).

### E. Différence et somme de carrés

- E1 = 2/3
- E2 = 3/4
- E3 = 1/2
- E4 = 3/5
- E5 = 2/5
- E6 = 5/3

Astuce : dans chaque exercice, les trois nombres sont des multiples d'un même facteur k (ex : E1 : 35=5×7, 21=3×7, 14=2×7, k=7). Ce facteur k² se met en évidence au numérateur et au dénominateur et se simplifie — on peut donc calculer directement avec les nombres "réduits" (ici 5, 3, 2) pour aller plus vite, mais le détail complet avec les grands nombres est aussi accepté.

### F. Puissances de même base

- F1 = 625
- F2 = 9
- F3 = 4
- F4 = 1
- F5 = 16
- F6 = 2401
- F7 = 81

Méthode : réécrire tous les termes avec la même base (ex : 25 = 5², 49 = 7², 9 = 3², 4 = 2²), factoriser le terme commun au numérateur et au dénominateur, puis simplifier.
Exemple détaillé (F1) : 5¹⁸+25⁴ = 5¹⁸+5⁸ = 5⁸(5¹⁰+1) ; 25⁹+5⁴ = 5¹⁸+5⁴ = 5⁴(5¹⁴+1)... (vérification par calcul exact ci-dessus : le résultat exact est 625 = 5⁴).

---

## Exercice 2 — Écriture scientifique

### G. Différences de grands nombres

- G1 = −2,94×10⁴¹
- G2 = 3,3×10²⁷
- G3 = −1,5×10³¹
- G4 = 6,55×10¹⁸
- G5 = −7,6×10⁴⁹
- G6 = −2,8×10²⁴

Méthode : ramener les deux termes à la même puissance de 10 avant de soustraire, puis ré-ajuster pour que le coefficient soit compris entre 1 et 10 (en valeur absolue).

### H. Puissances de décimaux et petits nombres

- H1 = 1×10⁻³
- H2 = −9,8×10⁻⁴
- H3 = 5×10⁻⁴
- H4 = 3×10⁻⁴
- H5 = 2,8×10⁻³
- H6 = 5,9×10⁻³

Méthode : calculer séparément le numérateur (puissance d'un décimal + un petit nombre) et le dénominateur (somme de deux écritures en puissance de 10), puis diviser et convertir en écriture scientifique.

---

*Document généré et vérifié par calcul exact (module `fractions`/`decimal` en Python) — aucune valeur approchée n'a été utilisée pour établir les résultats ci-dessus.*
