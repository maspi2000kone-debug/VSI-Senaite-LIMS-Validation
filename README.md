# Portfolio VSI — Validation d'un LIMS (Senaite) selon GAMP 5 & 21 CFR Part 11

Bienvenue sur le dépôt de validation du système d'information de laboratoire **Senaite LIMS**. 
Ce projet illustre l'application concrète du cycle en V et des exigences de Data Integrity (ALCOA+) dans un cadre réglementaire GxP / pharmaceutique.

## 🎯 Objectif du Projet
Démontrer la conformité réglementaire d'un logiciel de gestion de laboratoire configuré (GAMP 5 Catégorie 4) déployé via Docker.

## 📁 Structure de la Documentation de Validation
Chaque phase du cycle en V est documentée à la racine du dépôt :

- 📋 **[Plan de Validation (VP)](VP_Senaite_LIMS.md)** : Stratégie globale, périmètre, normes (GAMP 5, 21 CFR Part 11, Annexe 11 BPF) et matrice de responsabilités.
- 📝 **[Spécification des Exigences Utilisateur (URS)](URS_Senaite_LIMS.md)** : Exigences fonctionnelles, sécurité d'accès et intégrité des données (ALCOA+).
- ⚠️ **[Analyse de Risques (AMDEC / FMEA)](RA_Senaite_LIMS.md)** : Évaluation IPR des modes de défaillance sur la donnée et mesures de mitigation.
- 🧪 **[Qualification Opérationnelle (OQ)](OQ_Senaite_LIMS.md)** : Cas de tests fonctionnels exécutés sur l'Audit Trail et le contrôle des accès.

## 🛠️ Stack Technique & Environnement
- **Système cible :** Senaite LIMS
- **Infrastructure :** Conteneurisation Docker / Plone backend
- **Référentiels :** GAMP 5 (2nd Edition), FDA 21 CFR Part 11, BPF Annexe 11
