# Born2beroot - 42 School Project

## 📋 Description
Born2beroot est un projet système du tronc commun à 42 qui consiste à configurer et sécuriser un serveur Debian ou CentOS suivant des règles strictes. Ce projet introduit les concepts d'administration système, de virtualisation et de sécurité informatique.

## 🎯 Objectifs
- Maîtriser l'installation et configuration d'un système d'exploitation
- Comprendre les principes fondamentaux de la sécurité système
- Apprendre la gestion des utilisateurs et des permissions
- Implémenter des politiques de sécurité avancées

## 🛠️ Technologies Utilisées

### 🔧 Virtualisation
- **VMware** ou **VirtualBox** - Environnement de virtualisation
- **Debian** ou **CentOS** - Système d'exploitation serveur

### 🛡️ Sécurité Système
- **SSH** - Accès distant sécurisé
- **UFW** (Uncomplicated Firewall) - Pare-feu
- **Sudo** - Gestion des privilèges
- **AppArmor** ou **SELinux** - Sécurité obligatoire d'accès

### 📊 Monitoring
- **SSH Service** - Configuration sécurisée
- **Sudo Configuration** - Politiques personnalisées
- **Password Policy** - Règles de mots de passe stricts
- **Monitoring Script** - Script de surveillance système

## 🚀 Installation et Configuration

### 📋 Prérequis
- Machine virtuelle avec Debian ou CentOS
- Partitionnement LVM obligatoire
- Configuration réseau adaptée

### ⚙️ Configuration Principale
```bash
# Installation des paquets essentiels
sudo apt update && sudo apt upgrade
sudo apt install ssh ufw sudo apparmor
```

📊 Fonctionnalités Implémentées
🔐 Sécurité
Politique de mots de passe forte

Configuration sécurisée de SSH (port personnalisé, désactivation de la connexion root)

Pare-feu UFW avec règles restrictives

Sudo sécurisé avec configuration personnalisée

🖥️ Système
Partitionnement LVM avec schéma spécifique

Gestion des utilisateurs avec groupes dédiés

Script de monitoring affichant les informations système

Configuration hostname selon la norme 42

📝 Services
Service personnalisé pour le monitoring

Cron task pour l'exécution périodique du script

Message du jour (motd) personnalisé

💡 Compétences Développées
Administration système Linux

Gestion de la virtualisation

Configuration de la sécurité serveur

Scripting Bash avancé

Gestion des partitions LVM

Configuration des services système

Mise en place de politiques de sécurité

Résolution de problèmes système

🎯 Validation
Le projet doit respecter des contraintes techniques strictes :

Connexion SSH uniquement avec clé ou mot de passe fort

Port SSH personnalisé (non 22)

Désactivation de la connexion root via SSH

Politique de mot de passe exigeante

Partitionnement LVM obligatoire

Script de monitoring fonctionnel

Ce projet fournit une base solide en administration système et sécurité, essentielle pour tout développeur travaillant dans un environnement professionnel.
