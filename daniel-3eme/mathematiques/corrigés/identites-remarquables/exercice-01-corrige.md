# Corrigé — Identités remarquables (Feuille 1)

**Matière** : Mathématiques — 3ème
**Chapitre** : Calcul littéral — identités remarquables
**Date** : 2026-10-04

**Rappel des trois identités** (pour tous nombres a et b) :
- (a + b)² = a² + 2ab + b²
- (a − b)² = a² − 2ab + b²
- (a + b)(a − b) = a² − b²

> Méthode générale : **toujours écrire qui est a et qui est b** avant d'appliquer l'identité. C'est là que se cachent 90 % des erreurs.

---

## Correction

### A. Développer et réduire

**1.** A = (3x − 5)² − (2x + 1)(2x − 1)

- (3x − 5)² : identité (a − b)² avec a = 3x, b = 5.
  (3x − 5)² = (3x)² − 2 × 3x × 5 + 5² = 9x² − 30x + 25
- (2x + 1)(2x − 1) : identité (a + b)(a − b) avec a = 2x, b = 1.
  (2x + 1)(2x − 1) = (2x)² − 1² = 4x² − 1
- Attention au signe « − » devant le produit : on met le résultat **entre parenthèses** avant de supprimer celles-ci.
  A = 9x² − 30x + 25 − (4x² − 1) = 9x² − 30x + 25 − 4x² + 1

**A = 5x² − 30x + 26**

*Vérification* (x = 1) : (3 − 5)² − 3 × 1 = 4 − 3 = 1 et 5 − 30 + 26 = 1 ✓

---

**2.** B = (½x + 3)² − (½x − 3)²

- (½x + 3)² : a = ½x, b = 3 → (½x)² + 2 × ½x × 3 + 3² = ¼x² + 3x + 9
- (½x − 3)² : a = ½x, b = 3 → (½x)² − 2 × ½x × 3 + 3² = ¼x² − 3x + 9
- B = (¼x² + 3x + 9) − (¼x² − 3x + 9) = ¼x² + 3x + 9 − ¼x² + 3x − 9

**B = 6x**

*Autre méthode* : B est de la forme a² − b² avec a = ½x + 3 et b = ½x − 3.
B = (a − b)(a + b) = [(½x + 3) − (½x − 3)] × [(½x + 3) + (½x − 3)] = 6 × x = 6x ✓

*Vérification* (x = 2) : (1 + 3)² − (1 − 3)² = 16 − 4 = 12 = 6 × 2 ✓

---

### B. Factoriser

**3.** C = 49x² − 84x + 36

- Trois termes, deux carrés : 49x² = (7x)² et 36 = 6². On teste la forme a² − 2ab + b² avec a = 7x, b = 6.
- Double produit : 2 × 7x × 6 = 84x ✓ — et le signe est « − ».

**C = (7x − 6)²**

*Vérification* (x = 1) : 49 − 84 + 36 = 1 et (7 − 6)² = 1 ✓

---

**4.** D = (2x + 1)² − (x − 3)²

- Forme a² − b² avec a = 2x + 1 et b = x − 3. Donc D = (a − b)(a + b).
- a − b = (2x + 1) − (x − 3) = 2x + 1 − x + 3 = x + 4 (attention : le « − » change le signe de −3)
- a + b = (2x + 1) + (x − 3) = 3x − 2

**D = (x + 4)(3x − 2)**

*Vérification* (x = 0) : 1² − (−3)² = 1 − 9 = −8 et 4 × (−2) = −8 ✓

---

**5.** E = 9x² − 25 + (3x + 5)(x − 2)

- Pas de facteur commun visible : il faut d'abord **factoriser 9x² − 25**.
  9x² − 25 = (3x)² − 5² = (3x − 5)(3x + 5) (a = 3x, b = 5)
- E = (3x + 5)(3x − 5) + (3x + 5)(x − 2) → facteur commun **(3x + 5)**
- E = (3x + 5)[(3x − 5) + (x − 2)] = (3x + 5)(4x − 7)

**E = (3x + 5)(4x − 7)**

*Vérification* (x = 1) : 9 − 25 + 8 × (−1) = −24 et 8 × (−3) = −24 ✓

---

### C. Calcul astucieux

**6.**

a) 102² = (100 + 2)² = 100² + 2 × 100 × 2 + 2² = 10 000 + 400 + 4 = **10 404**
   *(identité (a + b)², a = 100, b = 2)*

b) 998² = (1 000 − 2)² = 1 000² − 2 × 1 000 × 2 + 2² = 1 000 000 − 4 000 + 4 = **996 004**
   *(identité (a − b)², a = 1 000, b = 2)*

c) 497 × 503 = (500 − 3)(500 + 3) = 500² − 3² = 250 000 − 9 = **249 991**
   *(identité (a − b)(a + b), a = 500, b = 3)*

d) 2026² − 2025² = (2026 − 2025)(2026 + 2025) = 1 × 4051 = **4 051**
   *(identité a² − b², a = 2026, b = 2025)*

*Vérifications* : 998 × 998 = 998 000 − 1 996 = 996 004 ✓ ; 497 × 503 = 248 500 + 1 491 = 249 991 ✓

---

### D. Équations

**7.** (2x − 1)² = 16

- On ramène tout à gauche : (2x − 1)² − 16 = 0, soit (2x − 1)² − 4² = 0.
- Identité a² − b² avec a = 2x − 1, b = 4 : (2x − 1 − 4)(2x − 1 + 4) = 0, soit (2x − 5)(2x + 3) = 0.
- Équation produit nul : un produit est nul si et seulement si l'un de ses facteurs est nul.
  - 2x − 5 = 0 ⟺ x = 5/2
  - 2x + 3 = 0 ⟺ x = −3/2

**Solutions : x = 5/2 et x = −3/2**

*Vérification* : x = 5/2 → (5 − 1)² = 16 ✓ ; x = −3/2 → (−3 − 1)² = 16 ✓

> Piège classique : écrire seulement 2x − 1 = 4. Un carré égal à 16 vient de 4 **ou de −4**.

---

**8.** 9x² − 1 = (3x + 1)(x + 5)

- On ramène tout à gauche : 9x² − 1 − (3x + 1)(x + 5) = 0.
- 9x² − 1 = (3x)² − 1² = (3x − 1)(3x + 1)
- (3x + 1)(3x − 1) − (3x + 1)(x + 5) = 0 → facteur commun (3x + 1)
- (3x + 1)[(3x − 1) − (x + 5)] = 0, soit (3x + 1)(2x − 6) = 0.
- Produit nul :
  - 3x + 1 = 0 ⟺ x = −1/3
  - 2x − 6 = 0 ⟺ x = 3

**Solutions : x = −1/3 et x = 3**

*Vérification* : x = 3 → 81 − 1 = 80 et 10 × 8 = 80 ✓ ; x = −1/3 → 1 − 1 = 0 et 0 × (14/3) = 0 ✓

> Piège classique : « simplifier » par (3x + 1) des deux côtés. Interdit — on perd la solution x = −1/3 (on diviserait par 0).

---

### E. Démonstration et problème

**9.** a) Soit n un nombre entier.

- (2n − 1)(2n + 1) est de la forme (a − b)(a + b) avec a = 2n, b = 1.
- (2n − 1)(2n + 1) = (2n)² − 1² = 4n² − 1
- Donc (2n − 1)(2n + 1) + 1 = 4n² − 1 + 1 = 4n² = (2n)².

Comme n est entier, 2n est entier : **(2n − 1)(2n + 1) + 1 est le carré de l'entier 2n.**

b) 2025 = 2n − 1 et 2027 = 2n + 1 avec n = 1013, donc 2n = 2026.

2025 × 2027 + 1 = 2026² = (2000 + 26)² = 2000² + 2 × 2000 × 26 + 26² = 4 000 000 + 104 000 + 676

**2025 × 2027 + 1 = 4 104 676**

*Vérification* : 2025 × 2027 = 2025 × 2000 + 2025 × 27 = 4 050 000 + 54 675 = 4 104 675, puis + 1 = 4 104 676 ✓

---

**10.** a) Aire engazonnée = aire du jardin − aire de l'abri.

- Aire du jardin : (x + 3)² ; aire de l'abri : 3² = 9.
- Aire engazonnée = (x + 3)² − 9 = (x + 3)² − 3²
- Identité a² − b² avec a = x + 3, b = 3 : (x + 3 − 3)(x + 3 + 3)

**Aire engazonnée = x(x + 6) m²** (forme développée : x² + 6x)

b) On cherche x > 0 tel que (x + 3)² − 9 = 40, soit (x + 3)² = 49.

- (x + 3)² − 7² = 0 ⟺ (x + 3 − 7)(x + 3 + 7) = 0 ⟺ (x − 4)(x + 10) = 0
- x = 4 ou x = −10. Or x > 0 (c'est une longueur), donc on rejette x = −10.

**x = 4 m** (le jardin mesure alors 7 m de côté).

*Vérification* : 7² − 9 = 49 − 9 = 40 m² ✓ ; et x(x + 6) = 4 × 10 = 40 ✓
