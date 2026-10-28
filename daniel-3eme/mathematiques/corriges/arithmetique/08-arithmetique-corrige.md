# Corrigé — Nombres et calculs (Feuille 8 — arithmétique)

**Matière** : Mathématiques — 3ème
**Chapitre** : Nombres et calculs — arithmétique : PGCD, PPCM, division euclidienne, divisibilité
**Date** : 2026-10-16

**Outils de la feuille**
- PGCD : facteurs premiers **communs**, chacun avec le **plus petit** exposant.
- PPCM : **tous** les facteurs premiers présents, chacun avec le **plus grand** exposant.
- PGCD(a ; b) × PPCM(a ; b) = a × b.
- Puissances : aⁿ × aᵐ = aⁿ⁺ᵐ ; (aⁿ)ᵐ = a^(n × m) ; (ab)ⁿ = aⁿbⁿ.

---

## Correction

**1.** a) 2 520 = 2³ × 315 = 2³ × 3² × 35 → **2 520 = 2³ × 3² × 5 × 7**
3 300 = 2² × 825 = 2² × 3 × 275 → **3 300 = 2² × 3 × 5² × 11**

b) PGCD = 2² × 3 × 5 = **60** ; PPCM = 2³ × 3² × 5² × 7 × 11 = **138 600**.

*Vérification* : 60 × 138 600 = 8 316 000 et 2 520 × 3 300 = 8 316 000 ✓

c) 2 520/3 300 = (60 × 42)/(60 × 55) = **42/55**
*Vérification* : 42 = 2 × 3 × 7 et 55 = 5 × 11 n'ont aucun facteur commun ✓

d) 138 600 = 2 520 × 55 = 3 300 × 42, donc :
1/2 520 − 1/3 300 = 55/138 600 − 42/138 600 = **13/138 600**
13 est premier et n'apparaît pas dans la décomposition de 138 600 : la fraction est irréductible.

*Vérification décimale* : 1/2 520 − 1/3 300 ≈ 0,00039683 − 0,00030303 = 0,00009380 et 13/138 600 ≈ 0,00009380 ✓

---

**2.** a) Le point rouge de A revient au contact toutes les 42 dents, celui de B toutes les 60 dents. Ils se retrouvent ensemble au bout d'un nombre de dents multiple de 42 et de 60 ; la première fois, c'est le PPCM.

42 = 2 × 3 × 7 ; 60 = 2² × 3 × 5 → PPCM = 2² × 3 × 5 × 7 = 420.

**420 dents.**

b) Roue A : 420 ÷ 42 = **10 tours** ; roue B : 420 ÷ 60 = **7 tours**.

*Vérification* : 10 × 42 = 7 × 60 = 420 ✓ ; 10 et 7 sont premiers entre eux, donc il n'y a pas de rencontre plus tôt ✓

---

**3.** a) Toutes les briques sont dans le même sens : le côté du carré est un multiple de 18 (dans un sens) et de 30 (dans l'autre). Le plus petit carré a pour côté le PPCM.

18 = 2 × 3² ; 30 = 2 × 3 × 5 → PPCM = 2 × 3² × 5 = 90.

**Côté 90 cm**, avec 90 ÷ 18 = 5 briques dans un sens et 90 ÷ 30 = 3 dans l'autre, soit **15 briques**.

*Vérification par les aires* : 90² = 8 100 cm² et 15 × 18 × 30 = 8 100 cm² ✓

b) Le côté doit être un multiple de 90 cm compris entre 150 cm et 300 cm : 180 cm et 270 cm (90 est trop petit, 360 trop grand).

- **Côté 180 cm** : (180 ÷ 18) × (180 ÷ 30) = 10 × 6 = **60 briques**
- **Côté 270 cm** : (270 ÷ 18) × (270 ÷ 30) = 15 × 9 = **135 briques**

*Vérification* : 180² = 32 400 = 60 × 540 ✓ ; 270² = 72 900 = 135 × 540 ✓ (une brique a une aire de 540 cm²)

---

**4.** n a pour reste 7 dans les deux divisions, donc n − 7 est un multiple de 24 et de 40, c'est-à-dire un multiple de leur PPCM.

24 = 2³ × 3 ; 40 = 2³ × 5 → PPCM = 2³ × 3 × 5 = 120.

n = 7 + 120k, avec k entier naturel. On veut 1 000 ≤ 7 + 120k ≤ 1 500, soit 993 ≤ 120k ≤ 1 493, donc 8,275 ≤ k ≤ 12,44…, c'est-à-dire k ∈ {9 ; 10 ; 11 ; 12}.

**n ∈ {1 087 ; 1 207 ; 1 327 ; 1 447}**

*Vérification* : 1 087 = 24 × 45 + 7 = 40 × 27 + 7 ✓ ; 1 447 = 24 × 60 + 7 = 40 × 36 + 7 ✓

---

**5.** 4 620 = 2² × 3 × 5 × 7 × 11 et 35 = 5 × 7, donc 4 620 = 35 × 132, avec 132 = 2² × 3 × 11.

- PGCD(4 620 ; y) = 35, donc y = 35k avec k premier avec 132, c'est-à-dire k divisible ni par 2, ni par 3, ni par 11.
- 200 ≤ 35k ≤ 300 ⟺ 5,71… ≤ k ≤ 8,57…, donc k ∈ {6 ; 7 ; 8}.
- k = 6 est divisible par 2 (et par 3) et k = 8 par 2 : on les écarte. Seul **k = 7** convient.

**y = 245**, et c'est la seule valeur possible.

*Vérification* : 245 = 5 × 7² ; facteurs communs avec 4 620 : 5 et 7 (chacun avec l'exposant 1), donc PGCD = 35 ✓ ; contre-exemple écarté : 210 = 35 × 6 donne PGCD(4 620 ; 210) = 210 ≠ 35 ✓

---

**6.** 168 = 2³ × 3 × 7 = 56 × 3.

- PGCD(x ; 168) = 56, donc x = 56k avec k premier avec 3, c'est-à-dire k non multiple de 3.
- x ≤ 400 ⟺ 56k ≤ 400 ⟺ k ≤ 7,14…, donc k ≤ 7.
- On écarte k = 0 (x = 0 est nul ; et comme tout entier divise 0, on aurait PGCD(0 ; 168) = 168), ainsi que k = 3 et k = 6, multiples de 3. Il reste k ∈ {1 ; 2 ; 4 ; 5 ; 7}.

**x ∈ {56 ; 112 ; 224 ; 280 ; 392}**

*Vérification* : 112 = 2⁴ × 7 et 168 = 2³ × 3 × 7, donc PGCD = 2³ × 7 = 56 ✓ ; contre-exemple écarté : 168 = 56 × 3 donne PGCD(168 ; 168) = 168 ✓

> Piège : croire que k doit être premier, ou impair. Seule compte la divisibilité par 3, le seul facteur premier de 168/56 = 3.

---

**7.** PGCD(a ; b) = 6, donc a = 6a' et b = 6b', avec a' et b' premiers entre eux et a' < b'.

- D'après le rappel : 6 × 180 = a × b = 36a'b', donc a'b' = 1 080 ÷ 36 = 30.
- Décompositions 30 = a' × b' avec a' < b' : 1 × 30 ; 2 × 15 ; 3 × 10 ; 5 × 6. Dans chacune, a' et b' sont premiers entre eux, car 30 = 2 × 3 × 5 et chaque facteur premier n'apparaît qu'une fois.
- Réciproquement, pour chacun de ces couples, PGCD(a ; b) = 6 d'après le rappel, puis PPCM(a ; b) = a × b ÷ 6 = 36 × 30 ÷ 6 = 180 ✓

**(a ; b) ∈ {(6 ; 180) ; (12 ; 90) ; (18 ; 60) ; (30 ; 36)}**

*Vérification* : (18 ; 60) → 18 = 2 × 3², 60 = 2² × 3 × 5 ; PGCD = 2 × 3 = 6 et PPCM = 2² × 3² × 5 = 180 ✓ ; (30 ; 36) → PGCD = 6 et PPCM = 180 ✓

---

**8.** a) A = 4ⁿ + 4ⁿ⁺¹ = 4ⁿ × (1 + 4) = 5 × 4ⁿ = 5 × (2²)ⁿ = **5 × 2²ⁿ**
B = 6ⁿ⁺¹ − 6ⁿ = 6ⁿ × (6 − 1) = 5 × 6ⁿ = **5 × 2ⁿ × 3ⁿ**

b) Décompositions : A = 2²ⁿ × 5 et B = 2ⁿ × 3ⁿ × 5.

- Facteurs premiers communs : 2 et 5 (3 n'apparaît pas dans A).
- Exposant de 2 : 2n dans A, n dans B. Comme n ≥ 1, le plus petit est n.
- Exposant de 5 : 1 dans les deux.

**PGCD(A ; B) = 5 × 2ⁿ**

c) n = 2 : A = 16 + 64 = 80 = 2⁴ × 5 et B = 216 − 36 = 180 = 2² × 3² × 5.
PGCD(80 ; 180) = 2² × 5 = 20, et 5 × 2² = 20 ✓

---

**9.** a) abcabc = abc × 1 000 + abc (on décale abc de trois rangs, puis on ajoute abc) = abc × (1 000 + 1) = **1 001 × abc**.

b) 1 001 = 7 × 143 = 7 × 11 × 13 → **1 001 = 7 × 11 × 13**.
abcabc = 7 × 11 × 13 × abc : ce nombre est un multiple de 7, de 11 et de 13.

*Vérification* sur un exemple : 123 123 = 1 001 × 123, et 123 123 = 7 × 17 589 = 11 × 11 193 = 13 × 9 471 ✓

c) Même idée avec quatre chiffres : 20 262 026 = 2 026 × 10 000 + 2 026 = 2 026 × 10 001 = 2 026 × 73 × 137.

**20 262 026 est donc divisible par 73** (le quotient est 2 026 × 137 = 277 562).

*Vérification* : 73 × 277 562 = 20 262 026 ✓

---

**10.** a) (2k + 1)² − 1 = 4k² + 4k + 1 − 1 = 4k² + 4k = **4k(k + 1)**
(identité (a + b)², a = 2k, b = 1 ; ou identité a² − b² : (2k + 1 − 1)(2k + 1 + 1) = 2k(2k + 2) = 4k(k + 1))

b) Si n est impair, il s'écrit n = 2k + 1 avec k entier. D'après a), n² − 1 = 4k(k + 1).
k et k + 1 sont deux entiers consécutifs : l'un d'eux est pair, donc k(k + 1) = 2m avec m entier.
Ainsi n² − 1 = 4 × 2m = 8m.

**n² − 1 est divisible par 8.**

c) n⁴ − 1 = (n² − 1)(n² + 1) (identité a² − b², a = n², b = 1).

- D'après b), n² − 1 = 8m.
- n est impair, donc n² est impair (produit de deux impairs) et n² + 1 est pair : n² + 1 = 2p.
- n⁴ − 1 = 8m × 2p = 16mp.

**n⁴ − 1 est divisible par 16.**

*Vérification* : n = 3 → 9 − 1 = 8 ✓ et 81 − 1 = 80 = 16 × 5 ✓ ; n = 5 → 24 = 8 × 3 ✓ et 624 = 16 × 39 ✓ ; n = 2 025 → 2 025² − 1 = 2 024 × 2 026 et 2 024 = 8 × 253, donc divisible par 8 ✓
