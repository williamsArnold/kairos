# Guide d'Utilisation du Système Expert M&A

Ce document décrit comment utiliser le système de diagnostic M&A pour l'analyse de l'entreprise FA2C.

## Documents Disponibles pour l'Analyse

| Fichier | Description | Contenu Attendu |
|---------|-------------|-----------------|
| `plaquette_des_comptes_annuels_au_31_12_2022.pdf` | Comptes annuels 2022 | Bilan, Compte de résultat, Annexes |
| `plaquette_des_comptes_annuels_au_31_d_cembre_2023.PDF` | Comptes annuels 2023 | Bilan, Compte de résultat, Annexes |
| `plaquette_des_comptes_annuels_au_31_d_cembre_2024.PDF` | Comptes annuels 2024 | Bilan, Compte de résultat, Annexes |
| `Teaser FA2C.pdf` | Présentation commerciale | Secteur, Activité, Positionnement |
| `FA2C TEMPORIS SITUATION AU 31.10.25.pdf` | Situation récente | Données actualisées |

## Processus d'Analyse Recommandé

### Étape 1 : Collecte des Données Financières

1. Ouvrir les plaquettes des comptes annuels (2022, 2023, 2024)
2. Extraire les données du bilan :
   - Actif immobilisé
   - Actif circulant (stocks, créances, trésorerie)
   - Capitaux propres
   - Dettes financières
3. Extraire les données du compte de résultat :
   - Chiffre d'affaires
   - Achats et charges externes
   - Charges de personnel
   - Résultat d'exploitation
   - Résultat net

### Étape 2 : Calcul des SIG et Indicateurs

```
Marge commerciale = Ventes - Coût d'achat des marchandises vendues
Production = Production vendue + Production stockée + Production immobilisée
Valeur ajoutée = Marge + Production - Consommations intermédiaires
EBE = Valeur ajoutée + Subventions - Impôts & taxes - Charges de personnel
EBIT = EBE - Dotations aux amortissements et provisions
```

### Étape 3 : Retraitements pour EBE Normatif

Vérifier et ajuster :
- [ ] Rémunération du dirigeant (ramener à une valeur de marché)
- [ ] Loyers (si SCI du dirigeant, ramener à valeur marché)
- [ ] Charges exceptionnelles non récurrentes
- [ ] Produits exceptionnels non récurrents
- [ ] Provisions anormales

### Étape 4 : Analyse Extra-Financière

À partir du Teaser et de la Situation :
- [ ] Identifier le secteur d'activité exact
- [ ] Comprendre le positionnement concurrentiel
- [ ] Identifier les clients majeurs
- [ ] Évaluer la dépendance fournisseurs
- [ ] Analyser l'équipe dirigeante

### Étape 5 : Valorisation

#### Méthode des Multiples
1. Calculer l'EBE normatif moyen (moyenne pondérée 3 ans)
2. Identifier le multiple sectoriel approprié :
   - PME services : 4-6x EBE
   - PME industrie : 5-7x EBE
   - PME tech : 8-12x EBE
3. Appliquer décote/surcote selon qualité du dossier

#### Méthode DCF
1. Projeter les cash-flows sur 5 ans
2. Calculer la valeur terminale
3. Actualiser au WACC approprié (généralement 10-15% pour PME)

#### Méthode Patrimoniale
1. Réévaluer l'actif net comptable
2. Ajouter la survaleur (goodwill) si pertinent

### Étape 6 : Synthèse

Compléter le rapport `RAPPORT_DIAGNOSTIC_FA2C.md` avec :
- Toutes les données chiffrées
- L'analyse qualitative
- La fourchette de valorisation justifiée
- La recommandation argumentée

## Checklist de Qualité

Avant de finaliser le rapport, vérifier :

- [ ] Tous les exercices financiers sont analysés
- [ ] Les retraitements sont documentés et justifiés
- [ ] La fourchette de valorisation est cohérente entre les méthodes
- [ ] Les risques sont identifiés et quantifiés si possible
- [ ] Les synergies potentielles sont évaluées
- [ ] La dette nette est correctement calculée
- [ ] Le passage VE → Valeur des titres est explicité
- [ ] Les documents illisibles sont signalés
- [ ] Chaque multiple est justifié par le contexte

## Contact et Support

Pour toute question sur la méthodologie, se référer au README.md qui contient le prompt système complet de l'Expert IA M&A.
