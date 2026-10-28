# Exercice 05 — Probabilités — Corrigé

**Matière** : Mathématiques — 4ème
**Notions** : Tableau incomplet, tirage successif, équation, simulation, raisonnement
**Date** : 2026-05-26

---

## Correction

### Situation 1 — Tableau incomplet

#### Question 1

- Réussi français et échoué maths : 18 − 11 = **7**
- Échoué français total : 30 − 18 = **12**
- Échoué français et réussi maths : 12 − 4 = **8**
- Total réussi maths : 11 + 8 = **19** | Total échoué maths : 11

|  | Réussi maths | Échoué maths | Total |
|---|---|---|---|
| Réussi français | 11 | 7 | 18 |
| Échoué français | 8 | 4 | 12 |
| **Total** | 19 | 11 | 30 |

#### Question 2

P(réussi les deux) = 11/30 **≈ 0,37**

P(échoué au moins à l'un) = 1 − 11/30 = 19/30 **≈ 0,63**

---

### Situation 2 — Tirage successif sans remise

Boules : R1, R2, R3, B1, B2 → 5 boules. Sans remise : 5 × 4 = **20 paires ordonnées**.

#### Question 3

Paires où la 1re boule est bleue : (B1;R1), (B1;R2), (B1;R3), (B1;B2), (B2;R1), (B2;R2), (B2;R3), (B2;B1) → **8 paires**

#### Question 4

P(1re bleue) = 8/20 = **2/5 = 0,4**

*Méthode directe : 2 boules bleues sur 5 au départ → P = 2/5.*

Deux couleurs différentes : (rouge puis bleue) ou (bleue puis rouge) = (3 × 2) + (2 × 3) = 6 + 6 = 12 cas.

P(couleurs différentes) = 12/20 = **3/5 = 0,6**

---

### Situation 3 — Proportion constante

#### Question 5

Total = n + 2n = 3n. P(rouge) = n / 3n = **1/3**

Le résultat **ne dépend pas de n** : la probabilité est entièrement fixée par la proportion rouge/bleue (1 pour 2).

#### Question 6

Si P(rouge) = 1/4, alors rouge représente 1 part et bleue 3 parts.

Rapport rouge/bleue = 1/3, mais l'énoncé impose bleue = 2 × rouge, soit rapport rouge/bleue = 1/2.

**Il y a contradiction** : si le nombre de bleues est le double des rouges, P(rouge) vaut toujours 1/3, pas 1/4.

---

### Situation 4 — Simulation

#### Question 7

48 + 52 + 49 + 51 + 53 + 47 = **300** ✓

f(3) = 49/300 ≈ **0,163**. Probabilité théorique : 1/6 ≈ 0,167. Proche mais pas identique — normal sur 300 lancers.

#### Question 8

Fréquence faces paires : 52 + 51 + 47 = 150. f(pair) = 150/300 = **0,5**

Probabilité théorique : 3/6 = 0,5. Coïncidence exacte ici — pas une règle générale.

---

### Situation 5 — Tirage successif et raisonnement

Sac : R1, R2, B1, B2 → 4 boules. Sans remise : 4 × 3 = **12 paires ordonnées**.

#### Question 9

P(rouge puis rouge) : 2 × 1 = 2 cas → P = 2/12 = **1/6 ≈ 0,17**

#### Question 10

**FAUX.**

Même couleur : (rouge, rouge) = 2 cas + (bleue, bleue) = 2 cas → **4 cas**. P = 4/12 = 1/3 ≈ 0,33

Couleurs différentes : 12 − 4 = **8 cas**. P = 8/12 = 2/3 ≈ 0,67

La probabilité d'obtenir deux couleurs différentes (2/3) est supérieure à celle d'obtenir deux couleurs identiques (1/3).
