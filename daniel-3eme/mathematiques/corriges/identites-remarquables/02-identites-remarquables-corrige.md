# Corrigé — Identités remarquables (Feuille 2 — approfondissement)

**Matière** : Mathématiques — 3ème
**Chapitre** : Calcul littéral — identités remarquables
**Date** : 2026-10-04

**Rappel** (pour tous nombres a et b) : (a + b)² = a² + 2ab + b² ; (a − b)² = a² − 2ab + b² ; (a + b)(a − b) = a² − b².

> Sur cette feuille, le développement « bourrin » marche parfois, mais il est long et source d'erreurs. Le but est de **repérer la structure** avant de calculer.

---

## Correction

### A. Développer astucieusement

**1.** A = (3a − 2b)² − (3a + 2b)² + (a − 4b)(a + 4b)

- (3a − 2b)² = 9a² − 12ab + 4b² (identité (u − v)², u = 3a, v = 2b)
- (3a + 2b)² = 9a² + 12ab + 4b² (identité (u + v)²)
- Leur différence : (9a² − 12ab + 4b²) − (9a² + 12ab + 4b²) = −24ab
- (a − 4b)(a + 4b) = a² − (4b)² = a² − 16b²

**A = a² − 24ab − 16b²**

*Raccourci* : (u − v)² − (u + v)² = −4uv, donc les deux carrés donnent −4 × 3a × 2b = −24ab.
*Vérification* (a = 1, b = 1) : (1)² − 5² + (−3)(5) = 1 − 25 − 15 = −39 et 1 − 24 − 16 = −39 ✓

---

**2.** a) On regroupe les facteurs dans le bon ordre :

- (3 − x)(3 + x) = 9 − x² (identité (a − b)(a + b), a = 3, b = x)
- (9 − x²)(9 + x²) = 81 − x⁴ (même identité, a = 9, b = x²)
- (x² − 9)² = x⁴ − 18x² + 81 (identité (a − b)², a = x², b = 9)
- B = 81 − x⁴ − (x⁴ − 18x² + 81) = 81 − x⁴ − x⁴ + 18x² − 81

**B = −2x⁴ + 18x²**

b) Facteur commun 2x², puis identité a² − b² :
B = 2x²(9 − x²) = **2x²(3 − x)(3 + x)**

*Vérification* (x = 1) : 2 × 4 × 10 − 64 = 16 ; −2 + 18 = 16 ; 2 × 1 × 2 × 4 = 16 ✓

---

**3.** C = (x + y − 3)(x − y + 3)

- Astuce : on regroupe. x − y + 3 = x − (y − 3). Donc C = [x + (y − 3)] × [x − (y − 3)].
- Identité (a + b)(a − b) avec a = x, b = y − 3 : C = x² − (y − 3)²
- (y − 3)² = y² − 6y + 9, donc C = x² − (y² − 6y + 9)

**C = x² − y² + 6y − 9**

*Vérification* (x = 1, y = 0) : (1 − 3)(1 + 3) = −8 et 1 − 0 + 0 − 9 = −8 ✓

---

### B. Factoriser complètement

**4.** D = (2x − 3)² − 4(x + 1)²

- Piège : 4(x + 1)² est aussi un carré, car 4(x + 1)² = [2(x + 1)]² = (2x + 2)².
- D = (2x − 3)² − (2x + 2)², forme a² − b² avec a = 2x − 3, b = 2x + 2.
- a − b = (2x − 3) − (2x + 2) = −5
- a + b = (2x − 3) + (2x + 2) = 4x − 1
- D = −5(4x − 1)

**D = 5(1 − 4x)**

*Vérification* (x = 0) : 9 − 4 = 5 et 5 × 1 = 5 ✓ ; (x = 1) : 1 − 16 = −15 et 5 × (−3) = −15 ✓

> Un des facteurs « disparaît » (il vaut la constante −5) : ce n'est pas une erreur, c'est le résultat.

---

**5.** E = x³ − 6x² + 9x − x(x² − 9)

- Facteur commun x partout : E = x[(x² − 6x + 9) − (x² − 9)]
- On reconnaît x² − 6x + 9 = (x − 3)² et x² − 9 = (x − 3)(x + 3).
- E = x[(x − 3)² − (x − 3)(x + 3)] → nouveau facteur commun (x − 3)
- E = x(x − 3)[(x − 3) − (x + 3)] = x(x − 3)(−6)

**E = −6x(x − 3)**

*Vérification* (x = 1) : 1 − 6 + 9 − 1 × (−8) = 12 et −6 × 1 × (−2) = 12 ✓

> Autre méthode, plus rapide ici : développer d'abord. E = x³ − 6x² + 9x − x³ + 9x = −6x² + 18x = −6x(x − 3). Les deux méthodes concordent ✓

---

**6.** F = x² − 4y² + x − 2y

- Pas de facteur commun à tous les termes : on **regroupe** par deux.
- x² − 4y² = (x − 2y)(x + 2y) (identité a² − b², a = x, b = 2y)
- x − 2y = (x − 2y) × 1
- F = (x − 2y)(x + 2y) + (x − 2y) × 1 = (x − 2y)(x + 2y + 1)

**F = (x − 2y)(x + 2y + 1)**

*Vérification* (x = 3, y = 1) : 9 − 4 + 3 − 2 = 6 et 1 × 6 = 6 ✓

---

### C. Calcul sans développer

**7.** On sait que a − b = 3 et ab = 4.

a) (a − b)² = a² − 2ab + b², donc a² + b² = (a − b)² + 2ab = 9 + 8.
**a² + b² = 17**

b) (a + b)² = a² + b² + 2ab = 17 + 8.
**(a + b)² = 25**
Un nombre dont le carré vaut 25 est 5 ou −5 : **a + b = 5 ou a + b = −5**.

c) (a² + b²)² = a⁴ + 2a²b² + b⁴, donc a⁴ + b⁴ = (a² + b²)² − 2(ab)² = 17² − 2 × 4² = 289 − 32.
**a⁴ + b⁴ = 257**

*Vérification* : les couples (a ; b) = (4 ; 1) et (−1 ; −4) vérifient a − b = 3 et ab = 4.
Pour (4 ; 1) : a² + b² = 17, a + b = 5, a⁴ + b⁴ = 256 + 1 = 257 ✓. Pour (−1 ; −4) : a + b = −5 ✓ — les deux signes existent bien.

---

**8.**

a) On pose n = 12 345. Alors 12 344 × 12 346 = (n − 1)(n + 1) = n² − 1.
12 345² − 12 344 × 12 346 = n² − (n² − 1) = **1**

b) 99 999 999 = 10⁸ − 1 = (10⁴)² − 1² = (10⁴ − 1)(10⁴ + 1) = 9 999 × 10 001
Puis 9 999 = 10⁴ − 1 = (10²)² − 1² = (10² − 1)(10² + 1) = 99 × 101.
**99 999 999 = 99 × 101 × 10 001** (une écriture possible : d'autres décompositions existent, par exemple 9 × 11 × 1 010 101, et sont acceptées si elles sont justifiées)

*Vérification* : 99 × 101 = 9 999 ; 9 999 × 10 001 = 99 990 000 + 9 999 = 99 999 999 ✓

c) 1,01² − 0,99² = (1,01 − 0,99)(1,01 + 0,99) = 0,02 × 2 = **0,04**

*Vérification* : 1,0201 − 0,9801 = 0,04 ✓

---

### D. Équations

**9.** a) (3x − 1)² = (x + 5)²

- (3x − 1)² − (x + 5)² = 0, puis identité a² − b² :
  (3x − 1 − x − 5)(3x − 1 + x + 5) = 0, soit (2x − 6)(4x + 4) = 0
- Produit nul : 2x − 6 = 0 ⟺ x = 3 ; 4x + 4 = 0 ⟺ x = −1

**Solutions : x = 3 et x = −1**
*Vérification* : x = 3 → 8² = 8² ✓ ; x = −1 → (−4)² = 4² ✓

b) x³ = 4x

- x³ − 4x = 0 ⟺ x(x² − 4) = 0 ⟺ x(x − 2)(x + 2) = 0
- Produit nul : x = 0, x = 2 ou x = −2

**Solutions : x = −2, x = 0 et x = 2**
*Vérification* : (−2)³ = −8 = 4 × (−2) ✓ ; 0 = 0 ✓ ; 8 = 8 ✓

> Piège : diviser par x pour obtenir x² = 4. On perd la solution x = 0.

c) 4x² + 9 = 12x

- 4x² − 12x + 9 = 0. On reconnaît (2x)² − 2 × 2x × 3 + 3² = (2x − 3)².
- (2x − 3)² = 0 ⟺ 2x − 3 = 0 ⟺ x = 3/2

**Solution unique : x = 3/2**
*Vérification* : 4 × 9/4 + 9 = 18 et 12 × 3/2 = 18 ✓

---

### E. Démonstration

**10.** a) n(n + 3) = n² + 3n et (n + 1)(n + 2) = n² + 2n + n + 2 = n² + 3n + 2.

b) On regroupe : N = [n(n + 3)] × [(n + 1)(n + 2)] + 1 = (n² + 3n)(n² + 3n + 2) + 1.
Avec u = n² + 3n : N = u(u + 2) + 1 = u² + 2u + 1 = (u + 1)² (identité (a + b)², a = u, b = 1).

Donc **N = (n² + 3n + 1)²**. Comme n est entier, n² + 3n + 1 est entier : N est le carré d'un entier.

c) Pour n = 10 : 10 × 11 × 12 × 13 + 1 = (10² + 3 × 10 + 1)² = (100 + 30 + 1)²

**10 × 11 × 12 × 13 + 1 = 131² = 17 161**

*Vérification* : 10 × 11 × 12 × 13 = 110 × 156 = 17 160, puis + 1 = 17 161 ; et 131² = 130² + 2 × 130 + 1 = 16 900 + 260 + 1 = 17 161 ✓

> La clé : multiplier les facteurs **extrêmes** ensemble et les facteurs **du milieu** ensemble, pour faire apparaître la même expression n² + 3n.
