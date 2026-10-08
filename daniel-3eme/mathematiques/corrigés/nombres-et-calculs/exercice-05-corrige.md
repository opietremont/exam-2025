# Corrigé — Nombres et calculs (Feuille 5)

**Matière** : Mathématiques — 3ème
**Chapitre** : Nombres et calculs — fractions, puissances, arithmétique, ensembles de nombres, calcul littéral, équations
**Date** : 2026-10-08

**Outils de la feuille**
- Priorités : parenthèses, puis puissances, puis × et ÷ (de gauche à droite), puis + et −.
- Puissances (a ≠ 0) : aⁿ × aᵐ = aⁿ⁺ᵐ ; aⁿ / aᵐ = aⁿ⁻ᵐ ; (aⁿ)ᵐ = aⁿˣᵐ ; a⁻ⁿ = 1/aⁿ. Écriture scientifique : a × 10ⁿ avec 1 ≤ a < 10.
- Identités : (a + b)² = a² + 2ab + b² ; (a − b)² = a² − 2ab + b² ; (a + b)(a − b) = a² − b².

---

## Correction

**1.** a) Priorité au produit dans la première parenthèse.

- 3/4 × 2/9 = 6/36 = 1/6
- 5/6 − 1/6 = 4/6 = 2/3
- (1 − 2/3)² = (1/3)² = 1/9
- A = 2/3 ÷ 1/9 = 2/3 × 9 = 18/3

**A = 6**

*Vérification décimale* : (0,8333 − 0,1667) ÷ 0,1111 = 0,6667 ÷ 0,1111 ≈ 6 ✓

> Piège : calculer 5/6 − 3/4 en premier. La multiplication est prioritaire.

b) On commence par l'étage le plus bas du dénominateur.

- 1 − 1/3 = 2/3, donc 1 / (2/3) = 3/2
- 1/2 + 3/2 = 2
- 2/5 − 1 = −3/5
- B = −3/5 ÷ 2 = −3/10

**B = −3/10**

*Vérification décimale* : (0,4 − 1) / (0,5 + 1,5) = −0,6 / 2 = −0,3 ✓

---

**2.** a) Pour n entier naturel non nul, on réduit au même dénominateur n(n + 1) :

1/n − 1/(n + 1) = (n + 1)/(n(n + 1)) − n/(n(n + 1)) = (n + 1 − n)/(n(n + 1)) = 1/(n(n + 1)).

b) D'après a), il faut que n(n + 1) = 56. Les produits de deux entiers consécutifs valent 6 × 7 = 42, puis 7 × 8 = 56, puis 8 × 9 = 72 : ils augmentent avec n.

**n = 7** (et c'est la seule solution parmi les entiers naturels).

*Vérification* : 1/7 − 1/8 = 8/56 − 7/56 = 1/56 ✓

c) D'après a), chaque terme se découpe en une différence :

S = (1/1 − 1/2) + (1/2 − 1/3) + (1/3 − 1/4) + … + (1/9 − 1/10)

Les termes intermédiaires s'annulent deux à deux (−1/2 + 1/2, −1/3 + 1/3, etc.). Il reste S = 1 − 1/10.

**S = 9/10**

*Vérification* (sur les trois premiers termes) : 1/2 + 1/6 + 1/12 = 6/12 + 2/12 + 1/12 = 9/12 = 3/4 = 1 − 1/4 ✓

> Cette technique s'appelle une **somme télescopique** : comme une longue-vue qu'on replie, presque tout disparaît.

---

**3.** a) On écrit tout en puissances de 2 : 4 = 2², 8 = 2³, 16 = 2⁴.

- 4³ × 8⁻² = 2⁶ × 2⁻⁶ = 2⁰ = 1
- 16⁻¹ × 2⁵ = 2⁻⁴ × 2⁵ = 2¹
- E = 2⁰ / 2¹

**E = 2⁻¹** (soit 1/2)

*Vérification* : 64 / 64 = 1 et (1/16) × 32 = 2, donc E = 1/2 ✓

b) 3²⁰²⁶ + 3²⁰²⁶ + 3²⁰²⁶ = 3 × 3²⁰²⁶ = 3¹ × 3²⁰²⁶ = **3²⁰²⁷**

> Piège : écrire 3⁶⁰⁷⁸ ou 9²⁰²⁶. Additionner des puissances n'additionne pas les exposants.

c) On factorise par la plus petite puissance, 2¹⁰ :

2¹⁰ + 2¹⁰ + 2¹¹ + 2¹² = 2¹⁰ × (1 + 1 + 2 + 2²) = 2¹⁰ × 8 = 2¹⁰ × 2³ = **2¹³**

*Vérification* : 1 024 + 1 024 + 2 048 + 4 096 = 8 192 = 2¹³ ✓

d) 0,000 32 = 3,2 × 10⁻⁴, donc :

G = (3,2 × 10⁻⁴ × 10⁷) / (8 × 10⁻²) = (3,2 / 8) × 10⁻⁴⁺⁷⁻⁽⁻²⁾ = 0,4 × 10⁵

Or 0,4 n'est pas compris entre 1 et 10 : 0,4 × 10⁵ = 4 × 10⁻¹ × 10⁵.

**G = 4 × 10⁴**

*Vérification* : 0,000 32 × 10⁷ = 3 200 et 8 × 10⁻² = 0,08 ; 3 200 / 0,08 = 40 000 ✓

---

**4.** a) **12 = 2² × 3** ; **18 = 2 × 3²** ; **30 = 2 × 3 × 5**

b) Les trois lignes repartent ensemble au bout d'un nombre de minutes multiple de 12, de 18 et de 30. La première fois, c'est le PPCM.

PPCM = produit de tous les facteurs premiers présents, chacun avec son plus grand exposant = 2² × 3² × 5 = 180.

180 minutes = 3 heures. **Prochain départ commun : 10 h 00.**

*Vérification* : 180 = 12 × 15 = 18 × 10 = 30 × 6 ✓ ; et aucun multiple commun plus petit : aucun des multiples de 30 inférieurs à 180 n'est divisible à la fois par 12 et par 18 (60 et 120 ne sont pas divisibles par 18 ; 90 n'est pas divisible par 12 ; 30 et 150 ne sont divisibles ni par 12 ni par 18) ✓

c) Les départs communs ont lieu toutes les 3 heures à partir de 7 h 00 : 7 h, 10 h, 13 h, 16 h, 19 h. Le suivant, 22 h, est après la fin du service.

**5 départs communs.**

---

**5.** a) **Vrai.** Soient a/10ⁿ et b/10ᵐ deux décimaux, avec par exemple n ≤ m.
a/10ⁿ = (a × 10ᵐ⁻ⁿ)/10ᵐ, donc a/10ⁿ + b/10ᵐ = (a × 10ᵐ⁻ⁿ + b)/10ᵐ. Le numérateur est un entier relatif : la somme est décimale.

b) **Faux.** Contre-exemple : 1 et 3 sont décimaux, mais 1 ÷ 3 = 1/3 n'est pas décimal. En effet, si 1/3 = a/10ⁿ, alors 3 diviserait 10ⁿ = 2ⁿ × 5ⁿ, ce qui est impossible.

c) **Faux.** Contre-exemple : √2 est irrationnel, mais √2 × √2 = 2 est un entier, donc rationnel.

d) **Vrai.** Tout entier relatif k s'écrit k = k/1, quotient d'un entier relatif par un entier naturel non nul.

e) **Faux.** Si 2/7 = a/10ⁿ, alors 2 × 10ⁿ = 7a, donc 7 diviserait 2 × 10ⁿ = 2ⁿ⁺¹ × 5ⁿ. Or 7 n'apparaît pas dans cette décomposition en facteurs premiers : c'est impossible. 2/7 n'est pas décimal (2/7 ≈ 0,285714 285714…, l'écriture ne s'arrête jamais).

---

**6.** a) F = (4x² − 1)(x + 3) − (2x + 1)²(x − 1)

- 4x² − 1 = (2x − 1)(2x + 1) (identité a² − b², a = 2x, b = 1)
- F = (2x + 1)(2x − 1)(x + 3) − (2x + 1)(2x + 1)(x − 1) → facteur commun (2x + 1)
- F = (2x + 1)[(2x − 1)(x + 3) − (2x + 1)(x − 1)]
- (2x − 1)(x + 3) = 2x² + 6x − x − 3 = 2x² + 5x − 3
- (2x + 1)(x − 1) = 2x² − 2x + x − 1 = 2x² − x − 1
- Crochet : 2x² + 5x − 3 − 2x² + x + 1 = 6x − 2 = 2(3x − 1)

**F = 2(2x + 1)(3x − 1)**

*Vérification* (x = 0) : (−1)(3) − (1)(−1) = −3 + 1 = −2 et 2 × 1 × (−1) = −2 ✓ ; (x = 1) : 3 × 4 − 9 × 0 = 12 et 2 × 3 × 2 = 12 ✓

b) F = 0 ⟺ 2(2x + 1)(3x − 1) = 0. Comme 2 ≠ 0 : 2x + 1 = 0 ou 3x − 1 = 0.

**Solutions : x = −1/2 et x = 1/3**

---

**7.** On sait que x − y = 5 et x² + y² = 37.

a) (x − y)² = x² + y² − 2xy, donc 25 = 37 − 2xy, soit 2xy = 12.
**xy = 6**

b) (x + y)² = x² + y² + 2xy = 37 + 12.
**(x + y)² = 49**, donc **x + y = 7 ou x + y = −7**.

c) Cas 1 : x + y = 7 et x − y = 5. En additionnant : 2x = 12, x = 6, puis y = 1.
Cas 2 : x + y = −7 et x − y = 5. En additionnant : 2x = −2, x = −1, puis y = −6.
**(x ; y) = (6 ; 1) ou (−1 ; −6)**

d) x/y + y/x = x²/(xy) + y²/(xy) = (x² + y²)/(xy) = **37/6**

*Vérification* : (6 ; 1) → 6 − 1 = 5 ✓, 36 + 1 = 37 ✓, 6 + 1/6 = 37/6 ✓ ; (−1 ; −6) → −1 + 6 = 5 ✓, 1 + 36 = 37 ✓

---

**8.** a) 501² − 499² = (501 − 499)(501 + 499) = 2 × 1 000 = **2 000**

*Vérification* : 501² = 251 001 et 499² = 249 001 ; 251 001 − 249 001 = 2 000 ✓

b) 4 095 = 2¹² − 1 = (2⁶)² − 1² = (2⁶ − 1)(2⁶ + 1) = 63 × 65

- 63 = 9 × 7 = 3² × 7
- 65 = 5 × 13

**4 095 = 3² × 5 × 7 × 13**

*Vérification* : 9 × 5 = 45 ; 45 × 7 = 315 ; 315 × 13 = 4 095 ✓

c) (7/3)² − (4/3)² = (7/3 − 4/3)(7/3 + 4/3) = 1 × 11/3 = **11/3**

*Vérification* : 49/9 − 16/9 = 33/9 = 11/3 ✓

---

**9.** a) (4x − 3)² − (2x + 1)² = 0 ⟺ (4x − 3 − 2x − 1)(4x − 3 + 2x + 1) = 0 ⟺ (2x − 4)(6x − 2) = 0

**Solutions : x = 2 et x = 1/3**
*Vérification* : x = 2 → 5² = 5² ✓ ; x = 1/3 → (4/3 − 3)² = 25/9 et (2/3 + 1)² = 25/9 ✓

b) x³ − 2x² = 9x − 18 ⟺ x³ − 2x² − 9x + 18 = 0

- Regroupement : x²(x − 2) − 9(x − 2) = 0 ⟺ (x − 2)(x² − 9) = 0 ⟺ (x − 2)(x − 3)(x + 3) = 0

**Solutions : x = −3, x = 2 et x = 3**
*Vérification* : x = 3 → 27 − 18 = 9 et 27 − 18 = 9 ✓ ; x = −3 → −27 − 18 = −45 et −27 − 18 = −45 ✓ ; x = 2 → 0 = 0 ✓

> L'astuce : 9x − 18 = 9(x − 2) fait apparaître le même facteur (x − 2) que x³ − 2x² = x²(x − 2).

c) x² + 1/4 = x ⟺ x² − x + 1/4 = 0 ⟺ x² − 2 × x × 1/2 + (1/2)² = 0 ⟺ (x − 1/2)² = 0

**Solution unique : x = 1/2**
*Vérification* : 1/4 + 1/4 = 1/2 ✓

---

**10.** a) (n − 1)(n + 2) = n² + 2n − n − 2 = n² + n − 2 et n(n + 1) = n² + n.

b) P = [(n − 1)(n + 2)] × [n(n + 1)] + 1 = (n² + n − 2)(n² + n) + 1.
Avec u = n² + n : P = (u − 2)u + 1 = u² − 2u + 1 = (u − 1)² (identité (a − b)², a = u, b = 1).

Donc **P = (n² + n − 1)²**. Comme n est entier, n² + n − 1 est entier : P est le carré d'un entier.

c) 19 × 20 × 21 × 22 correspond à n = 20 (n − 1 = 19, n + 1 = 21, n + 2 = 22).
n² + n − 1 = 400 + 20 − 1 = 419.

**19 × 20 × 21 × 22 + 1 = 419² = 175 561**

*Vérification* : 19 × 22 = 418 et 20 × 21 = 420 ; 418 × 420 = 175 560 ; + 1 = 175 561. Et 419² = (420 − 1)² = 176 400 − 840 + 1 = 175 561 ✓
