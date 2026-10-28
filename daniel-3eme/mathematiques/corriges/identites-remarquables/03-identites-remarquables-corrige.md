# Corrigé — Identités remarquables (Feuille 3 — expert)

**Matière** : Mathématiques — 3ème
**Chapitre** : Calcul littéral — identités remarquables
**Date** : 2026-10-04

**Rappel** (pour tous nombres a et b) : (a + b)² = a² + 2ab + b² ; (a − b)² = a² − 2ab + b² ; (a + b)(a − b) = a² − b².

**Outil dérivé, très utile ici** : (u + v)² − (u − v)² = 4uv (les deux identités se soustraient : a² et b² s'annulent, il reste 2 × 2uv).

---

## Correction

### A. Développer sans s'épuiser

**1.** On regroupe les termes deux par deux en isolant c.

- (a + b + c)² − (a + b − c)² : forme (u + v)² − (u − v)² avec u = a + b, v = c → 4c(a + b)
- (a − b − c)² − (a − b + c)² : forme (u − v)² − (u + v)² avec u = a − b, v = c → −4c(a − b)
- A = 4c(a + b) − 4c(a − b) = 4ac + 4bc − 4ac + 4bc

**A = 8bc**

*Vérification* (a = 1, b = 2, c = 1) : 4² − 2² − 0² + (−2)² = 16 − 4 − 0 + 4 = 16 et 8 × 2 × 1 = 16 ✓

> Développer les quatre carrés à trois termes fonctionne aussi, mais cela fait 24 termes à gérer. C'est le piège de l'exercice.

---

**2.** a) On regroupe x² + 2 : (x² + 2x + 2)(x² − 2x + 2) = [(x² + 2) + 2x] × [(x² + 2) − 2x]

Identité (a + b)(a − b) avec a = x² + 2, b = 2x :
= (x² + 2)² − (2x)² = x⁴ + 4x² + 4 − 4x²

**(x² + 2x + 2)(x² − 2x + 2) = x⁴ + 4**

b) 629 = 625 + 4 = 5⁴ + 4. Avec x = 5 :
629 = (25 + 10 + 2)(25 − 10 + 2) = **37 × 17**

*Vérification* : 37 × 17 = 370 + 259 = 629 ✓

c) Soit n un entier, n ≥ 2. D'après a), n⁴ + 4 = (n² + 2n + 2)(n² − 2n + 2).

- Ces deux facteurs sont des entiers.
- n² − 2n + 2 = (n² − 2n + 1) + 1 = (n − 1)² + 1. Comme n ≥ 2, (n − 1)² ≥ 1, donc n² − 2n + 2 ≥ 2.
- n² + 2n + 2 est encore plus grand (il vaut n² − 2n + 2 + 4n), donc lui aussi ≥ 2.

n⁴ + 4 est donc le produit de deux entiers supérieurs ou égaux à 2 : **il a un diviseur autre que 1 et lui-même, il n'est pas premier.**

> Point de rigueur : il ne suffit pas de factoriser. Il faut montrer qu'aucun facteur ne vaut 1, sinon la factorisation ne prouve rien (pour n = 1 : 5 = 5 × 1, et 5 est premier).

---

### B. Factoriser complètement

**3.** B = (x² + 4)² − 16x² = (x² + 4)² − (4x)²

- Identité a² − b² avec a = x² + 4, b = 4x : B = (x² + 4 − 4x)(x² + 4 + 4x)
- On n'a pas fini : x² − 4x + 4 = (x − 2)² et x² + 4x + 4 = (x + 2)².

**B = (x − 2)²(x + 2)²** (ou encore [(x − 2)(x + 2)]² = (x² − 4)²)

*Vérification* (x = 0) : 16 − 0 = 16 et 4 × 4 = 16 ✓ ; (x = 1) : 25 − 16 = 9 et 1 × 9 = 9 ✓

---

**4.** C = x² − y² − 6x + 9

- Il faut trouver le bon regroupement : les termes en x et le 9 forment un carré. C = (x² − 6x + 9) − y²
- x² − 6x + 9 = (x − 3)² (identité (a − b)², a = x, b = 3)
- C = (x − 3)² − y², identité a² − b² avec a = x − 3, b = y

**C = (x − 3 − y)(x − 3 + y)**

*Vérification* (x = 0, y = 0) : 9 et (−3)(−3) = 9 ✓ ; (x = 4, y = 1) : 16 − 1 − 24 + 9 = 0 et 0 × 2 = 0 ✓

> Le regroupement naturel (x² − y²) + (9 − 6x) ne mène nulle part : il faut tester plusieurs groupements.

---

**5.** D = 4a²b² − (a² + b² − c²)² = (2ab)² − (a² + b² − c²)²

- Attention, les lettres a et b sont déjà prises par l'énoncé : on écrit l'identité avec d'autres lettres, u² − v² = (u − v)(u + v), avec u = 2ab et v = a² + b² − c².
- D = [2ab − (a² + b² − c²)] × [2ab + (a² + b² − c²)]
- Premier crochet : 2ab − a² − b² + c² = c² − (a² − 2ab + b²) = c² − (a − b)² = (c − a + b)(c + a − b)
- Second crochet : a² + 2ab + b² − c² = (a + b)² − c² = (a + b − c)(a + b + c)

**D = (c − a + b)(c + a − b)(a + b − c)(a + b + c)**

*Vérification* (a = 1, b = 1, c = 1) : 4 − 1 = 3 et 1 × 1 × 1 × 3 = 3 ✓ ; (a = 2, b = 1, c = 0) : 16 − 25 = −9 et (−1)(1)(3)(3) = −9 ✓

> Culture : cette expression sert à calculer l'aire d'un triangle à partir de ses trois côtés (formule de Héron, vue au lycée).

---

### C. Nombres et raisonnement

**6.** a) (x + y)² = x² + y² + 2xy, donc 2xy = (x + y)² − (x² + y²) = 25 − 13 = 12.
**xy = 6**

b) (x − y)² = x² + y² − 2xy = 13 − 12.
**(x − y)² = 1**, donc **x − y = 1 ou x − y = −1** (deux nombres ont pour carré 1).

c) Cas 1 : x + y = 5 et x − y = 1. En additionnant : 2x = 6, x = 3, puis y = 2.
Cas 2 : x + y = 5 et x − y = −1. En additionnant : 2x = 4, x = 2, puis y = 3.
**(x ; y) = (3 ; 2) ou (2 ; 3)**

d) Comme xy = 6 ≠ 0, ni x ni y n'est nul : 1/x et 1/y existent. 1/x + 1/y = y/(xy) + x/(xy) = (x + y)/(xy) = 5/6.
**1/x + 1/y = 5/6**

*Vérification* : (3 ; 2) → 3 + 2 = 5, 9 + 4 = 13, 1/3 + 1/2 = 2/6 + 3/6 = 5/6 ✓

---

**7.** a) On regroupe les termes deux par deux et on applique a² − b² à chaque paire :

- 100² − 99² = (100 − 99)(100 + 99) = 100 + 99
- 98² − 97² = (98 − 97)(98 + 97) = 98 + 97
- … et ainsi de suite jusqu'à 2² − 1² = 2 + 1.

Donc S = 100 + 99 + 98 + 97 + … + 2 + 1 = **5 050**

*Vérification* (même méthode sur un cas court) : 4² − 3² + 2² − 1² = 16 − 9 + 4 − 1 = 10 = 4 + 3 + 2 + 1 ✓

b) x² − y² = 15 ⟺ (x − y)(x + y) = 15.

- x + y est un entier naturel, et il n'est pas nul (sinon x = y = 0 et x² − y² = 0 ≠ 15) : x + y > 0.
- Comme (x − y)(x + y) = 15 > 0 et x + y > 0, on a x − y > 0 : x − y est aussi un entier naturel.
- De plus x − y ≤ x + y (car y ≥ 0) : le plus petit facteur est x − y.
- Les décompositions de 15 en produit de deux entiers naturels, le plus petit en premier, sont 1 × 15 et 3 × 5.
  - x − y = 1 et x + y = 15 → 2x = 16, x = 8, y = 7
  - x − y = 3 et x + y = 5 → 2x = 8, x = 4, y = 1

**Couples solutions : (8 ; 7) et (4 ; 1)**

*Vérification* : 64 − 49 = 15 ✓ ; 16 − 1 = 15 ✓

---

### D. Équations

**8.** a) (x² − 1)² = (x + 1)² ⟺ (x² − 1)² − (x + 1)² = 0

- Identité a² − b² : (x² − 1 − x − 1)(x² − 1 + x + 1) = 0, soit (x² − x − 2)(x² + x) = 0
- x² + x = x(x + 1)
- x² − x − 2 = (x² − 1) − (x + 1) = (x − 1)(x + 1) − (x + 1) = (x + 1)(x − 2)
- L'équation devient : x(x + 1)²(x − 2) = 0
- Produit nul : x = 0, x + 1 = 0 ou x − 2 = 0

**Solutions : x = −1, x = 0 et x = 2**

*Vérification* : x = −1 → 0 = 0 ✓ ; x = 0 → 1 = 1 ✓ ; x = 2 → 3² = 3² ✓

> Point délicat : x² − x − 2 ne ressemble à aucune identité. L'astuce est d'écrire −2 = −1 − 1 pour faire apparaître x² − 1.

b) x² + 6x = 16

- On reconnaît le début de (x + 3)² = x² + 6x + 9. On ajoute 9 des deux côtés : x² + 6x + 9 = 25, soit (x + 3)² = 25.
- (x + 3)² − 5² = 0 ⟺ (x + 3 − 5)(x + 3 + 5) = 0 ⟺ (x − 2)(x + 8) = 0

**Solutions : x = 2 et x = −8**

*Vérification* : 4 + 12 = 16 ✓ ; 64 − 48 = 16 ✓

---

### E. Démonstrations

**9.** a) Pour n ≥ 1, le plus grand côté est 2n² + 2n + 1 (il dépasse 2n² + 2n de 1, et 2n² + 2n + 1 − (2n + 1) = 2n² > 0).

On compare le carré du plus grand côté à la somme des carrés des deux autres :

(2n² + 2n + 1)² − (2n² + 2n)² = [(2n² + 2n + 1) − (2n² + 2n)] × [(2n² + 2n + 1) + (2n² + 2n)]
= 1 × (4n² + 4n + 1) = (2n + 1)²

Donc (2n² + 2n + 1)² = (2n² + 2n)² + (2n + 1)².

D'après la **réciproque du théorème de Pythagore**, **le triangle est rectangle**, et son hypoténuse est le côté de longueur 2n² + 2n + 1.

> 4n² + 4n + 1 = (2n + 1)² : c'est l'identité (a + b)² avec a = 2n, b = 1.

b) n = 3 : 2 × 3 + 1 = 7 ; 2 × 9 + 6 = 24 ; 2 × 9 + 6 + 1 = 25.
**Côtés : 7, 24 et 25.** *Vérification* : 49 + 576 = 625 = 25² ✓

---

**10.** a) (a + b)² − 4ab = a² + 2ab + b² − 4ab = a² − 2ab + b² = (a − b)².
**(a + b)² − 4ab = (a − b)²**

b) Un carré est toujours positif ou nul : (a − b)² ≥ 0. Donc (a + b)² − 4ab ≥ 0.
**4ab ≤ (a + b)²**

c) On note a et b la longueur et la largeur du rectangle (en cm). Périmètre : 2(a + b) = 20, donc a + b = 10.

- D'après b) : 4ab ≤ (a + b)² = 100, donc ab ≤ 25.
- L'aire ab est donc **inférieure ou égale à 25 cm²**.
- Égalité : ab = 25 ⟺ 4ab = (a + b)² ⟺ (a − b)² = 0 ⟺ a = b. Avec a + b = 10 : a = b = 5.

**L'aire vaut exactement 25 cm² lorsque le rectangle est un carré de 5 cm de côté.**

*Vérification* : rectangle 6 × 4 → aire 24 < 25 ; rectangle 9 × 1 → aire 9 < 25 ; carré 5 × 5 → aire 25 ✓

> Conclusion à retenir : à périmètre fixé, c'est le carré qui a la plus grande aire. La démonstration tient en une ligne grâce à une identité remarquable.
