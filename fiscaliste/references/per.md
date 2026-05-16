# PER (Plan d'Épargne Retraite) individuel

Voir `data/per-plafonds.json` pour les plafonds et paramètres.

## Mécanisme de déduction

Le versement PER **réduit le RNI** de l'année de versement.

```
RNI avant PER
  − versement PER (dans la limite du plafond)
= RNI après PER
  ÷ nombre de parts
= Quotient → barème → impôt brut réduit
```

**Économie d'impôt immédiate** = versement × TMI.

Exemple : versement 5 000 €, TMI 30% → économie IR = 1 500 €.

## Plafond de déduction

### Formule

**Plafond = 10% des revenus professionnels nets** de l'année N-1 (salaires après abattement 10%, BNC, BIC — pas les revenus du capital).

### Bornes (revenus 2025)

| Borne | Valeur | Base |
|-------|--------|------|
| Plancher | 4 710 € | 10% × PASS 2025 |
| Plafond absolu | 37 680 € | 10% × 8 × PASS 2025 |

**Plancher garanti** même sans revenus professionnels → toujours au moins 4 710 € déductibles.

### Report des plafonds non utilisés

Les plafonds non utilisés des années précédentes sont mobilisables. Ordre d'imputation : plafond de l'année en cours d'abord, puis plafonds reportés **en commençant par le plus ancien** (N-3, N-2, N-1).

**Durée du report :**
- Jusqu'au 31/12/2025 : report sur les **3 années suivantes**
- À compter du 01/01/2026 : report sur les **5 années suivantes** (loi de finances 2026)

**Exemple (revenus 2025, déclaration 2026) :**
- Plafond N : 5 000 €, utilisé 3 000 € → reste 2 000 € reportables
- Si inutilisé, ce reliquat est disponible jusqu'en 2031 (5 ans)
- Au-delà, le plafond non utilisé est **perdu**

**Ordre FIFO obligatoire :** on consomme N-3 avant N-2 avant N-1 pour que les droits les plus anciens ne périment pas.

### Mutualisation couple

Les époux/pacsés soumis à imposition commune peuvent **mutualiser leurs plafonds** (case à cocher sur 2042). Un conjoint sans revenu pro peut bénéficier du plafond inemployé de l'autre.

## Arbitrage : le PER est-il vraiment utile ?

**Le PER est un REPORT d'imposition, pas une exonération.**

À la sortie, les versements sont imposés comme revenu (barème). Les gains sont imposés au PFU.

### Gagnant / perdant

| Situation | Résultat |
|-----------|----------|
| TMI entrée > TMI sortie | **Gain net** — économie à l'entrée > imposition sortie |
| TMI entrée = TMI sortie | **Neutre fiscalement** — seul l'effet capitalisation sur l'économie initiale joue |
| TMI entrée < TMI sortie | **Perte nette** — rare mais possible (carrière ascendante, sortie capital massif) |

### Cas typiques favorables

- **Actif TMI 30-41% avec retraite estimée TMI 11-30%** : gain net substantiel
- **Année de revenus exceptionnels** : versement pour écraser l'IR de l'année, sortie étalée plus tard
- **Quotient pour revenus exceptionnels + PER** : combinaison puissante pour un vesting RSU important

### Cas défavorables ou neutres

- **TMI 11% stable** : intérêt marginal — seul l'effet capitalisation compte
- **TMI 45% stable (hauts revenus à la retraite)** : pas d'avantage, imposition identique entrée/sortie
- **Horizon court (< 10 ans avant retraite)** : peu d'effet de capitalisation

## Sortie du PER

### Sortie à la retraite

**Deux options au choix** :

1. **Sortie en rente viagère**
   - Imposition comme pension (barème + abattement 10% plafonné)
   - Prélèvements sociaux 9,1%
   - Protection en cas de longévité

2. **Sortie en capital**
   - **Versements déduits à l'entrée** : imposés au barème progressif (part capital)
   - **Gains** : imposés séparément au PFU 30%
   - Possibilité de fractionner la sortie sur plusieurs années (à demander à l'assureur)

**Piège sortie capital** : ne pas confondre le régime du capital (barème, écrase la tranche) et celui des gains (PFU fixe). Bien distinguer.

### Versements non déduits (cas rare)

Si l'on a choisi de ne pas déduire les versements (case à cocher à la souscription) :
- Sortie partiellement exonérée
- Seuls les gains sont imposés (PFU)
- Utile si on anticipe un TMI sortie > TMI entrée — rare

### Sortie anticipée autorisée

Cas de déblocage avant la retraite (sans pénalité fiscale sur le capital) :
- Achat de la résidence principale
- Décès du conjoint / partenaire PACS
- Invalidité
- Surendettement
- Fin des droits au chômage
- Cessation d'activité non salariée après jugement de liquidation

Hors ces cas : déblocage impossible (capital bloqué jusqu'à la retraite).

## Priorité absolue : abondement employeur avant PER individuel

**Avant tout versement PER individuel, vérifier que l'abondement PEE / PERCO de l'employeur est saturé.**

L'abondement est un complément versé par l'entreprise pour chaque euro versé par le salarié sur son PEE ou son PERCO — typiquement 50 à 300 % du versement salarié, dans une limite annuelle (8 % du PASS pour le PEE, 16 % du PASS pour le PERCO).

| Dispositif | Avantage |
|------------|----------|
| **PEE + abondement** | Prime gratuite de l'employeur + exonération IR sur l'abondement + PFU 17,2 % à la sortie (pas 30 %) |
| **PERCO + abondement** | Idem + blocage jusqu'à la retraite |
| **PER individuel** | Uniquement économie d'impôt immédiate × TMI, pas de match employeur |

**Règle** : un abondement employeur de 100 % représente un rendement immédiat de 100 %. Aucune défiscalisation PER n'égale ce rendement. Toujours saturer PEE/PERCO en premier si l'option existe.

## Mécanique pratique

### Déclaration

- Versements : case 6NS (déclarant 1) / 6NT (déclarant 2) sur la 2042
- Plafond calculé automatiquement par la DGFIP (figure sur l'avis d'imposition N-1, rubrique "Plafond pour l'épargne retraite")

## PER TNS (ex-Madelin) : spécificités du travailleur non salarié

Le PER individuel (art. 163 quatervicies CGI) est accessible à tous, mais les TNS (gérant majoritaire SARL, gérant EURL, EI) disposent en plus du **PER TNS issu du contrat Madelin** (art. 154 bis CGI), avec un plafond de déduction spécifique.

### Plafond de déduction PER TNS (art. 154 bis CGI)

Plafond = **10% du bénéfice imposable** (dans la limite de 8 PASS) **+ 15% de la fraction du bénéfice comprise entre 1 PASS et 8 PASS**.

| Composante | Calcul | Plafond 2025 |
|------------|--------|--------------|
| Fraction 10% | 10% × bénéfice (max 8 PASS) | Max 37 094 € |
| Fraction 15% | 15% × (bénéfice − 46 368 €) si bénéfice > PASS | Variable |
| Plancher | Même plancher que PER individuel | 4 710 € |

Le plafond TNS est donc potentiellement **supérieur** au plafond du PER individuel (37 680 €) pour les bénéfices élevés. Consulter l'avis d'imposition pour le plafond exact calculé par la DGFIP.

### Double avantage TNS

Les cotisations versées sur un PER TNS sont :
1. Déductibles du revenu professionnel (réduction IR)
2. Déductibles de l'assiette des cotisations sociales TNS (réduction cotisations URSSAF)

Ce double avantage est plus puissant que le PER individuel (qui ne joue que sur l'IR). Le taux effectif d'économie peut atteindre TMI + taux marginal de cotisations TNS.

### Arbitrage PER TNS vs PEE/PERECO pour le dirigeant TNS

Pour un dirigeant TNS qui peut mettre en place un PEE/PERECO dans sa société (voir `equity-salarial.md` → section dédiée TNS) :

**Ordre de priorité recommandé :**
1. Saturer l'abondement PEE + PERECO (11 127 € pour 2025) — double exonération IS + cotisations, liquidité PEE après 5 ans
2. PER TNS (art. 154 bis) pour les montants supplémentaires — plafond plus élevé, double avantage IR + cotisations
3. PER individuel (art. 163 quatervicies) en complément si plafond Madelin atteint

**Pourquoi PEE/PERECO d'abord ?**
- L'abondement société est exonéré de cotisations TNS côté dirigeant ET de charges patronales côté société
- La sortie PEE est en PFU sur les gains (pas au barème) — avantage si TMI retraite = TMI actuel
- Liquidité supérieure : PEE débloquable après 5 ans (nombreux cas anticipés)

## Différence PER individuel vs PERCO / PERO

- **PER individuel** (présent doc) : versements volontaires, déductibles dans la limite du plafond, sortie imposée au barème.
- **PERCO / PEE** (plans d'épargne entreprise) : alimenté par intéressement, participation, abondement employeur. Voir la section Equity salarial listée depuis SKILL.md pour le détail.

**Règle d'or** : toujours saturer l'abondement employeur (PEE + PERCO) AVANT d'abonder un PER individuel. L'abondement est de l'argent gratuit — aucun rendement PER individuel n'égale un match à 50-300%.

### Plafond partagé : ce qui consomme le plafond 163 quatervicies

Le plafond de déduction (art. 163 quatervicies) est commun à toutes les enveloppes retraite déductibles. Plusieurs flux le consomment ou le réduisent :

| Flux | Case déclaration | Consomme le plafond ? |
|------|-----------------|----------------------|
| Versements volontaires PER individuel | 6NS / 6NT | **Oui** |
| Versements volontaires PERECO (compartiment 1) | 6NS / 6NT | **Oui** |
| Abondement employeur PERECO / PERCO | **6QS** | **Oui** — réduit le plafond disponible pour les versements volontaires |
| Intéressement / participation placés en PERECO | — (non déclarés) | **Non** — exonération séparée, hors plafond |
| Cotisations obligatoires PERO (compartiment 3) | 6QS | Oui (dans la limite exonérée) |

**Conséquence pratique** : si l'employeur abonde 7 418 € sur le PERECO, ce montant est déclaré en 6QS et réduit d'autant le plafond restant pour les versements volontaires PER individuel. Un salarié qui reçoit le plafond maximum d'abondement PERECO peut se retrouver avec un plafond résiduel nul pour son PER individuel si son plafond global est modeste.

**Pour les TNS** : l'abondement que la société verse sur le PERECO du dirigeant réduit de la même façon le plafond disponible pour un PER individuel — à intégrer dans l'arbitrage (voir `equity-salarial.md` → section TNS).

## Pièges fréquents

1. **Oublier le plafond** : versement > plafond → fraction non déductible (mais remboursable sans frais ou reportable selon le contrat)
2. **Sortie en capital sur un TMI 45%** : imposition quasi équivalente à un revenu normal — intérêt limité
3. **Mutualisation couple oubliée** : conjoint sans revenu laisse 4 710 € de plafond inemployé
4. **Assurer le plafond N-1 sur l'avis** : ne pas se fier aux calculs manuels, utiliser le plafond officiel DGFIP
5. **PER individuel avant PEE/PERCO** : manque l'abondement employeur

## Références CGI / BOFiP

- PER individuel : art. 163 quatervicies CGI
- Plafond de déduction : art. 163 quatervicies-I-2 CGI
- Sortie en capital : art. 158-5-b bis CGI
- Mutualisation couple : art. 163 quatervicies-I-2° CGI
- BOFiP : BOI-IR-BASE-20-50-20
