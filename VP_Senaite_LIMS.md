# Plan de Validation (Validation Plan - VP)
**Projet :** Déploiement & Validation de Senaite LIMS
**Référence :** VP-LIMS-2026-001
**Normes appliquées :** GAMP 5 (2nd Edition), FDA 21 CFR Part 11, Annexe 11 BPF

---

## 1. Objectif & Périmètre
Ce document définit la stratégie de validation pour le système d'information de laboratoire (Senaite LIMS).
L'objectif est de garantir la conformité aux exigences réglementaires relatives à l'intégrité des données (ALCOA+) et à la traçabilité des analyses.

## 2. Classification GAMP 5 du système
- **Type de système :** Catégorie 4 — Logiciel configuré (Senaite LIMS sur infrastructure conteneurisée Docker).

## 3. Matrice des Responsabilités
- **Responsable Validation (VSI) :** Rédaction du VP, approbation des URS et du rapport final.
- **Administrateur Système :** Déploiement de l'environnement Docker et gestion des accès.
- **Utilisateur Clé (Laboratoire) :** Définition des besoins métier et exécution des tests OQ/PQ.

## 4. Stratégie du Cycle en V
1. **Spécification des Exigences Utilisateur (URS) :** Définition des besoins métier et réglementaires.
2. **Analyse de Risques (AMDEC / FMEA) :** Évaluation des risques critiques sur la donnée.
3. **Qualification d'Installation (IQ) :** Vérification de l'environnement Docker et de la base de données.
4. **Qualification Opérationnelle (OQ) :** Tests fonctionnels (Audit Trail, gestion des rôles, signatures).
5. **Matrice de Traçabilité (TM) :** Lien 1:1 entre exigences et cas de tests.
6. **Rapport de Validation (VR) :** Bilan final concluant à la mise en production.
