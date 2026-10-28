# Corrigé — Nombres et calculs (Feuille 7 — arithmétique)

**Matière** : Mathématiques — 3ème
**Chapitre** : Nombres et calculs — arithmétique : PGCD, PPCM, division euclidienne, divisibilité
**Date** : 2026-10-16

**Outils de la feuille**
- PGCD : facteurs premiers **communs**, chacun avec le **plus petit** exposant.
- PPCM : **tous** les facteurs premiers présents, chacun avec le **plus grand** exposant.
- Une fraction a/b est irréductible quand on a divisé a et b par leur PGCD.
- Problème du type « reste r dans plusieurs divisions » : x − r est un multiple commun des diviseurs, donc un multiple de leur PPCM.

---

## Correction

**1.** a) 588 = 2 × 294 = 2² × 147 = 2² × 3 × 49 → **588 = 2² × 3 × 7²**
840 = 2 × 420 = 2² × 210 = 2³ × 105 = 2³ × 3 × 5 × 7 → **840 = 2³ × 3 × 5 × 7**

b) PGCD = 2² × 3 × 7 = **84** ; PPCM = 2³ × 3 × 5 × 7² = **5 880**.

*Vérification* : 84 × 5 880 = 493 920 et 588 × 840 = 493 920 ✓

c) 588/840 = (84 × 7)/(84 × 10) = **7/10**

d) 5 880 = 588 × 10 = 840 × 7, donc 1/588 + 1/840 = 10/5 880 + 7/5 880 = **17/5 880**.
17 est premier et n'apparaît pas dans 5 880 = 2³ × 3 × 5 × 7² : la fraction est irréductible.

*Vérification décimale* : 1/588 + 1/840 ≈ 0,0017007 + 0,0011905 = 0,0028912 et 17/5 880 ≈ 0,0028912 ✓

---

**2.** a) Les guirlandes s'allument ensemble après un nombre de secondes multiple de 8, de 12 et de 20. La première fois, c'est le PPCM.

8 = 2³ ; 12 = 2² × 3 ; 20 = 2² × 5 → PPCM = 2³ × 3 × 5 = 120 s = 2 min.

**Prochain allumage commun : 18 h 02 min 00 s.**

*Vérification* : 120 = 8 × 15 = 12 × 10 = 20 × 6 ✓ ; les multiples de 20 plus petits (20, 40, 60, 80, 100) ne sont pas multiples de 8 et de 12 à la fois : 40 et 80 ne sont pas multiples de 12, 60 n'est pas multiple de 8, et 20 et 100 ne sont multiples ni de 8 ni de 12 ✓

b) En 120 s, la première guirlande s'allume toutes les 8 s : 120 ÷ 8 = **15 fois**.

c) Les allumages communs ont lieu toutes les 2 minutes : à 18 h 00, 18 h 02, …, 18 h 58, 19 h 00. Cela correspond aux minutes 0, 2, 4, …, 60, soit 60 ÷ 2 + 1 = **31 allumages communs**.

> Piège : répondre 30. Il y a un allumage de plus que d'intervalles, comme les poteaux d'une clôture.

---

**3.** a) Le nombre de boîtes doit diviser 1 260 et 924 : le maximum est le PGCD.

- 1 260 = 2² × 3² × 5 × 7
- 924 = 2² × 3 × 7 × 11
- PGCD = 2² × 3 × 7 = 84

**84 boîtes au maximum**, chacune contenant 1 260 ÷ 84 = **15 truffes** et 924 ÷ 84 = **11 pralines**.

*Vérification* : 84 × 15 = 1 260 ✓ ; 84 × 11 = 924 ✓ ; 15 et 11 sont premiers entre eux, donc on ne peut pas faire plus de boîtes ✓

b) 15 × 0,45 + 11 × 0,30 = 6,75 + 3,30 = **10,05 €** par boîte.

c) Bénéfice par boîte : 12 − 10,05 = 1,95 €. Bénéfice total : 84 × 1,95 = **163,80 €**.

*Vérification* : recette 84 × 12 = 1 008 € ; coût total 1 260 × 0,45 + 924 × 0,30 = 567 + 277,20 = 844,20 € ; 1 008 − 844,20 = 163,80 € ✓

---

**4.** Soit N le nombre de billes. Il reste 5 billes dans les trois rangements, donc N − 5 est un multiple de 12, de 18 et de 21, c'est-à-dire un multiple de leur PPCM.

- 12 = 2² × 3 ; 18 = 2 × 3² ; 21 = 3 × 7
- PPCM = 2² × 3² × 7 = 252

N − 5 ∈ {0 ; 252 ; 504 ; 756 ; …}, donc N ∈ {5 ; 257 ; 509 ; 761 ; …}.
Le seul de ces nombres compris entre 400 et 600 est 509 : le précédent, 257, est trop petit, et le suivant, 761, trop grand.

**Il y a 509 billes.**

*Vérification* : 509 = 12 × 42 + 5 = 18 × 28 + 5 = 21 × 24 + 5 (et 5 est bien plus petit que 12, 18 et 21) ✓

---

**5.** On cherche x tel que PGCD(x ; 180) = 15.

- 15 divise x, donc x = 15k avec k entier naturel ; et 180 = 15 × 12.
- D'après le rappel, PGCD(15k ; 15 × 12) = 15 si et seulement si k et 12 sont premiers entre eux, c'est-à-dire si k n'est divisible **ni par 2 ni par 3** (car 12 = 2² × 3).
- x < 150 ⟺ 15k < 150 ⟺ k < 10.
- Parmi 1, 2, …, 9, les entiers qui ne sont ni pairs ni multiples de 3 sont 1, 5 et 7. (k = 0 est exclu : le PGCD n'est défini ici que pour des entiers non nuls ; et comme tout entier divise 0, on aurait de toute façon PGCD(0 ; 180) = 180.)

**x ∈ {15 ; 75 ; 105}**

*Vérification* : 15 divise 180 donc PGCD(15 ; 180) = 15 ✓ ; 75 = 3 × 5² et 180 = 2² × 3² × 5, donc PGCD = 3 × 5 = 15 ✓ ; 105 = 3 × 5 × 7, donc PGCD = 15 ✓ ; contre-exemple écarté : 45 = 3² × 5 donne PGCD(45 ; 180) = 45 ≠ 15 ✓

---

**6.** PGCD(a ; b) = 12, donc a = 12a' et b = 12b' avec a' et b' premiers entre eux.

- a + b = 96 ⟺ 12(a' + b') = 96 ⟺ a' + b' = 8, avec a' ≤ b'.
- Couples possibles : (0 ; 8), (1 ; 7), (2 ; 6), (3 ; 5), (4 ; 4).
- On garde ceux qui sont premiers entre eux : (1 ; 7) et (3 ; 5). On écarte (0 ; 8), qui donnerait a = 0, entier nul pour lequel le PGCD n'est pas défini ici (et tout entier divisant 0, on aurait PGCD(0 ; 96) = 96) ; (2 ; 6), car 2 les divise ; et (4 ; 4), car 4 les divise.

**(a ; b) = (12 ; 84) ou (36 ; 60)**

*Vérification* : 12 + 84 = 96 et PGCD(12 ; 84) = 12 (84 = 12 × 7) ✓ ; 36 + 60 = 96 et PGCD(36 ; 60) = 12 (36 = 2² × 3², 60 = 2² × 3 × 5) ✓

---

**7.** a) A = 2ⁿ⁺² + 2ⁿ = 2ⁿ × 2² + 2ⁿ = 2ⁿ × (4 + 1) = **5 × 2ⁿ**
B = 3ⁿ⁺² − 3ⁿ = 3ⁿ × 3² − 3ⁿ = 3ⁿ × (9 − 1) = **8 × 3ⁿ** = 2³ × 3ⁿ

b) n = 2 : A = 5 × 4 = 20 = 2² × 5 et B = 8 × 9 = 72 = 2³ × 3².
**PGCD(20 ; 72) = 2² = 4**

c) Décompositions : A = 2ⁿ × 5 et B = 2³ × 3ⁿ.

- Le seul facteur premier commun est 2 : 5 n'apparaît pas dans B, et 3 n'apparaît pas dans A.
- L'exposant de 2 vaut n dans A et 3 dans B. Pour n ≥ 3, le plus petit des deux est 3.

**Pour tout n ≥ 3 : PGCD(A ; B) = 2³ = 8.**

*Vérification* (n = 3) : A = 40 et B = 216 ; 40 = 2³ × 5 et 216 = 2³ × 3³, donc PGCD = 8 ✓

> Remarque : pour n = 0, 1, 2, le PGCD vaut 2ⁿ (soit 1, 2, 4). La réponse dépend de n tant que n < 3.

---

**8.** a) ab = 10a + b et ba = 10b + a.

- ab − ba = 10a + b − 10b − a = 9a − 9b = **9(a − b)**, un multiple de 9 (éventuellement nul ou négatif, si a ≤ b : 0 et −9 sont aussi des multiples de 9).
- ab + ba = 10a + b + 10b + a = 11a + 11b = **11(a + b)**, un multiple de 11.

b) abc − cba = (100a + 10b + c) − (100c + 10b + a) = 99a − 99c = **99(a − c)**, un multiple de 99.

c) ab + ba = 11(a + b) = 121 ⟺ a + b = 11, avec a et b chiffres de 1 à 9.
Couples possibles : (2 ; 9), (3 ; 8), (4 ; 7), (5 ; 6), (6 ; 5), (7 ; 4), (8 ; 3), (9 ; 2). Le couple (1 ; 10) est exclu, car 10 n'est pas un chiffre.

**Les nombres sont 29, 38, 47, 56, 65, 74, 83 et 92.**

*Vérification* : 29 + 92 = 121 ✓ ; 56 + 65 = 121 ✓

---

**9.** a) 36 = 2² × 3² ; 48 = 2⁴ × 3 ; 60 = 2² × 3 × 5 → PPCM = 2⁴ × 3² × 5 = **720**.

- 7/36 = (7 × 20)/720 = 140/720
- 5/48 = (5 × 15)/720 = 75/720
- 11/60 = (11 × 12)/720 = 132/720
- C = (140 + 75 − 132)/720 = 83/720

83 est premier et ne divise pas 720 : **C = 83/720** (irréductible).

*Vérification décimale* : 0,19444 + 0,10417 − 0,18333 = 0,11528 et 83/720 ≈ 0,11528 ✓

b) 3 150 = 2 × 3² × 5² × 7 ; 4 620 = 2² × 3 × 5 × 7 × 11.
PGCD = 2 × 3 × 5 × 7 = 210, donc 3 150/4 620 = (210 × 15)/(210 × 22) = **15/22**.

*Vérification* : 210 × 15 = 3 150 ✓ ; 210 × 22 = 4 620 ✓ ; 15 = 3 × 5 et 22 = 2 × 11 n'ont pas de facteur commun ✓

---

**10.** a) n³ − n = n(n² − 1) = n(n − 1)(n + 1) (identité a² − b², a = n, b = 1).
**n³ − n = (n − 1)n(n + 1)**

b) Si n = 1, n³ − n = 0 = 6 × 0 est divisible par 6. Soit maintenant n ≥ 2 : P = (n − 1)n(n + 1) est un produit de trois entiers naturels consécutifs non nuls.

- Parmi deux entiers consécutifs, l'un est pair : P est divisible par 2, donc P = 2m avec m entier.
- Parmi trois entiers consécutifs, l'un est un multiple de 3 : P = 2m est divisible par 3.
- 3 est premier et ne divise pas 2, donc 3 divise m : m = 3q, et P = 2 × 3q = 6q.

**Donc n³ − n est divisible par 6 pour tout n ≥ 1.**

c) n³ + 5n = (n³ − n) + 6n. Le premier terme est divisible par 6 d'après b), le second aussi (6n = 6 × n). La somme de deux multiples de 6 est un multiple de 6.

**n³ + 5n est divisible par 6.**

*Vérification* : n = 4 → 64 − 4 = 60 = 6 × 10 ✓ et 64 + 20 = 84 = 6 × 14 ✓ ; n = 7 → 343 − 7 = 336 = 6 × 56 ✓ et 343 + 35 = 378 = 6 × 63 ✓
