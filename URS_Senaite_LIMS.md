# Spécification des Exigences Utilisateur (URS)
**Projet :** Système de Gestion d'Information de Laboratoire (LIMS)
**Référence :** URS-LIMS-2026-001
**Version :** 1.0

---

## 1. Exigences de Sécurité & Accès (21 CFR Part 11)
- **URS-SEC-01 :** Authentification unique requise pour chaque utilisateur avec mot de passe complexe (longueur minimale de 8 caractères).
- **URS-SEC-02 :** Déconnexion automatique après 15 minutes d'inactivité.
- **URS-SEC-03 :** Gestion des rôles basée sur le principe du moindre privilège (Opérateur, Biologiste, Administrateur).

## 2. Intégrité des Données & Audit Trail (ALCOA+)
- **URS-DAT-01 (Audit Trail) :** Toute création, modification ou suppression de résultat doit être enregistrée automatiquement dans un Audit Trail non modifiable.
- **URS-DAT-02 :** L'Audit Trail doit horodater l'action, identifier l'auteur, afficher l'ancienne valeur, la nouvelle valeur et le motif du changement.
- **URS-DAT-03 :** Horodatage verrouillé sur l'heure système du serveur (non modifiable par les utilisateurs).

## 3. Gestion des Échantillons & Analyses
- **URS-FNC-01 :** Génération automatique d'un identifiant unique (Code-barres / ID) lors de la réception de l'échantillon.
- **URS-FNC-02 :** Saisie des résultats d'analyse avec contrôle des limites de tolérance réglementaires.
- **URS-FNC-03 :** Processus de validation à double niveau (Saisie par Technicien -> Approbation par Biologiste/Responsable Qualité).
