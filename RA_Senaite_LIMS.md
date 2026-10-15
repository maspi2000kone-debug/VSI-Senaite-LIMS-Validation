# Analyse de Risques (AMDEC / FMEA) — Data Integrity
**Projet :** Système LIMS
**Référence :** RA-LIMS-2026-001

---

## Échelle d'Évaluation
* **S (Sévérité) :** 1 (Faible) à 5 (Critique pour la santé/conformité BPF)
* **P (Probabilité) :** 1 (Rare) à 5 (Fréquent)
* **D (Détectabilité) :** 1 (Détection automatique) à 5 (Indétectable)
* **IPR (Indice de Priorité du Risque) = S x P x D**

---

## Matrice des Risques

| ID | Mode de Défaillance | Cause Possible | S | P | D | IPR | Mesure de Mitigation (Contrôle) |
|---|---|---|---|---|---|---|---|
| **R-01** | Modification manuelle non traçable d'un résultat d'analyse | Audit Trail désactivé ou contourné | 5 | 2 | 4 | **40** | Activer le verrouillage natif de l'Audit Trail. Qualification OQ obligatoire. |
| **R-02** | Saisie de résultats par du personnel non autorisé | Partage de compte utilisateur ou session restée ouverte | 4 | 3 | 3 | **36** | Activer la déconnexion automatique à 15 min et l'authentification individuelle. |
| **R-03** | Perte de données lors d'un crash système | Absence de sauvegarde périodique automatisée | 5 | 2 | 3 | **30** | Mise en place de sauvegardes automatiques quotidiennes testées en IQ. |
| **R-04** | Falsification de la date/heure de saisie | Horloge système du serveur modifiée manuellement | 5 | 1 | 3 | **15** | Restriction des droits administrateur sur le serveur d'horloge. |
