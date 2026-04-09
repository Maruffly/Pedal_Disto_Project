# Big Muff Pi - Guitar Fuzz Replica

Ce dépôt contient la liste des composants et les informations nécessaires pour fabriquer une réplique de la célèbre pédale de fuzz **Big Muff Pi**, basée sur l'analyse technique d'ElectroSmash.

---

## BOM

### Semi-conducteurs
* **4x** Transistors NPN **2N3904** (Q1, Q2, Q3, Q4)
* **4x** Diodes Silicium **1N4148** (D1, D2, D3, D4)

### Résistances
* **5x** 10K : R11, R12, R13, R18, R19
* **3x** 100K : R3, R16, R20
* **3x** 470K : R9, R15, R17
* **2x** 39K : R2, R8
* **2x** 150Ω : R10, R21
* **1x** 15K : R6
* **1x** 47K : R14
* **1x** 100Ω : R22
* **1x** 3.3K : R4
* **1x** 1K : R23
* **1x** 22K : R5

### Condensateurs
* **4x** 1µF : C1, C4, C6, C7
* **4x** 100nF : C2, C3, C5, C13
* **3x** 470pF : C10, C11, C12
* **1x** 10nF : C8
* **1x** 4nF : C9

### Potentiomètres
* **Sustain** : 100K Linéaire
* **Tone** : 100K Linéaire
* **Volume** : 100K Linéaire

---

## Spécifications Techniques
Le circuit est composé de quatre étages :
1.  **Input Booster** : Amplification d'entrée.
2.  **Clipping Stage 1** : Première saturation par diodes.
3.  **Clipping Stage 2** : Deuxième saturation et compression.
4.  **Tone & Recovery** : Contrôle de tonalité et amplification de sortie.

## Ref
Analyse du schéma et fonctionnement détaillé disponibles sur :
[ElectroSmash - Big Muff Pi Analysis](https://www.electrosmash.com/big-muff-pi-analysis)