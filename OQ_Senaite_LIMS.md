# Protocole & Rapport de Qualification Opérationnelle (OQ)
**Projet :** Senaite LIMS
**Référence :** OQ-LIMS-2026-001

---

## Cas de Test 1 : Vérification de la Sécurité & Mots de Passe
* **Exigences associées :** URS-SEC-01, URS-SEC-03
* **Procédure :** 
  1. Tenter de créer un utilisateur avec un mot de passe simple (`12345`).
  2. Tenter de se connecter avec un rôle "Opérateur" et accéder aux paramètres d'administration.
* **Résultat Attendu :** Rejet du mot de passe faible. Accès refusé aux menus administrateur.
* **Statut :** CONFORME (PASS)

---

## Cas de Test 2 : Vérification de l'Audit Trail (21 CFR Part 11)
* **Exigences associées :** URS-DAT-01, URS-DAT-02
* **Procédure :**
  1. Saisir la valeur d'une analyse d'échantillon (`pH = 7.2`).
  2. Modifier la valeur pour la passer à `pH = 7.5`.
  3. Consulter l'historique de l'Audit Trail.
* **Résultat Attendu :** L'historique affiche la date, l'heure, l'auteur, l'ancienne valeur (7.2), la nouvelle valeur (7.5) et demande la raison de la modification. Aucune option de suppression n'est présente.
* **Statut :** CONFORME (PASS)
