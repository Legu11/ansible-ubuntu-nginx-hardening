# Déploiement & Sécurisation Automatisée d'un Serveur Web (IaC)

> Réalisation d'un projet d'infrastructure et de cybersécurité visant à automatiser le déploiement et la sécurisation d'un serveur Web sous **Linux Ubuntu Server**, en adoptant une démarche **Infrastructure as Code (IaC)**.

---

## Objectifs & Réalisations

* **Virtualisation & Administration :** Instanciation d'une machine virtuelle **Linux Ubuntu Server** (mode `Headless`) sur **VMware** et configuration d'un accès à distance sécurisé via `SSH`.
* **Automatisation (IaC) :** Rédaction et exécution d'un Playbook **Ansible** pour orchestrer l'installation des services et la mise à jour du système sans intervention manuelle.
* **Sécurisation / Hardening :** Déploiement du serveur Web **Nginx** et configuration d'un pare-feu **UFW** appliquant une politique stricte de rejet par défaut (`Default Deny`) avec ouverture sélective des ports `22` (`SSH`) et `80` (`HTTP`).
* **Recette & Validation :** Réalisation des tests d'accès `HTTP` et contrôle du statut des règles de filtrage réseau.

---

## Environnement technique

`Linux Ubuntu Server` • `Ansible (YAML)` • `Nginx` • `UFW` • `SSH` • `VMware Workstation`

---

📄 **[Consulter le rapport complet du projet (PDF)](./rapport_projet_deploiement_renforcement_auto_srv.pdf)**
