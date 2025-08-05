# Politique de Confidentialité - Wolves & Whispers

**Dernière mise à jour :** 5 aout 2025

## 1. Introduction

Cette politique de confidentialité décrit comment notre application de jeu **Wolves & Whispers** collecte, utilise et protège vos informations personnelles.

## 2. Informations collectées

### 2.1 Informations que vous nous fournissez
- **Adresse e-mail** : utilisée pour créer et gérer votre compte via Firebase Authentication
- **Pseudo** : utilisé comme nom d'affichage dans les parties (validé par UsernameValidator)
- **Compositions personnalisées** : vos compositions de rôles sauvegardées
- **Historique de parties** : liste des parties auxquelles vous avez participé

### 2.2 Informations collectées automatiquement
- **Données techniques** : type d'appareil, version du système d'exploitation
- **Données d'utilisation** : fréquence d'utilisation, fonctionnalités utilisées
- **Données de performance** : pour améliorer la stabilité de l'application
- **Statut de présence** : connexion/déconnexion en temps réel pendant les parties
- **Actions de jeu** : votes, actions de rôles, participation aux épreuves (anonymisées)

## 3. Utilisation des données

Nous utilisons vos informations pour :
- ✅ **Authentification** : créer et gérer votre compte utilisateur
- ✅ **Gameplay** : permettre la participation aux parties multijoueurs en temps réel
- ✅ **Personnalisation** : sauvegarder vos préférences de jeu et compositions personnalisées
- ✅ **Synchronisation** : maintenir la cohérence des données entre tous les joueurs
- ✅ **Historique** : conserver un historique de vos parties terminées
- ✅ **Performance** : optimiser l'expérience utilisateur via la mise en cache intelligente
- ✅ **Sécurité** : prévenir la triche et les abus via validation serveur
- ✅ **Support technique** : diagnostiquer et résoudre les problèmes techniques

## 4. Partage des données

### 4.1 Avec d'autres joueurs
- Votre **pseudo** est visible par les autres participants de vos parties
- Votre **statut de présence** (en ligne/hors ligne) est visible aux autres joueurs de la même partie
- Vos **actions de jeu** (votes, rôles révélés) sont partagées selon les règles du jeu
- Votre **statut dans la partie** (vivant/mort, rôle si révélé) est visible aux autres joueurs

### 4.2 Avec des tiers
- **Firebase/Google Cloud** : pour l'hébergement, l'authentification et la base de données temps réel
- **Cloud Functions (Node.js)** : pour la logique serveur et la validation des parties
- **Aucune vente** de données personnelles à des tiers
- **Aucun partage** à des fins publicitaires
- **Aucun tracking publicitaire** ou analytics tiers

## 5. Stockage et sécurité

### 5.1 Localisation des données
- **Cloud Firestore** : stockage principal des données de jeu (Europe)
- **Firebase Realtime Database** : données de présence temps réel (Europe)
- **Firebase Authentication** : gestion des comptes utilisateurs (Europe)
- **Cloud Functions** : logique serveur hébergée sur Google Cloud (Europe)

### 5.2 Sécurité
- **Chiffrement** : données chiffrées en transit et au repos
- **Règles de sécurité Firestore** : permissions granulaires par utilisateur et partie
- **Authentification sécurisée** : via Firebase Auth avec protection anti-duplication
- **Validation serveur** : toutes les actions critiques validées côté serveur
- **Isolation des données** : les joueurs ne peuvent accéder qu'aux données de leurs propres parties
- **Nettoyage automatique** : suppression des données temporaires en fin de partie

## 6. Vos droits

Vous avez le droit de :
- **Accéder** à vos données personnelles
- **Modifier** votre pseudo et votre mot de passe
- **Supprimer** votre compte et vos données

Pour exercer ces droits, contactez-nous à : support@wolvesandwhispers.app

## 7. Conservation des données

- **Compte actif** : conservation tant que le compte existe
- **Compte supprimé** : suppression complète sous 30 jours
- **Données de jeu actives** : conservées pendant la durée des parties en cours
- **Historique de parties** : archivé dans la collection `archive_games`
- **Compositions personnalisées** : conservées tant que le compte existe
- **Données de cache** : supprimées automatiquement selon les règles TTL

## 8. Cookies et technologies similaires

L'application utilise :
- **Authentification Firebase** : pour maintenir votre session utilisateur
- **Cache local intelligent** : pour optimiser les performances
- **Stockage local sécurisé** : pour les préférences linguistiques et données temporaires
- **Aucun cookie publicitaire** ou de tracking
- **Aucun analytics tiers** : seules les données Firebase sont utilisées

## 9. Modifications de cette politique

Nous pouvons mettre à jour cette politique. Les modifications importantes vous seront notifiées par e-mail

## 10. Contact

Pour toute question concernant cette politique de confidentialité :

**Email :** support@wolvesandwhispers.app

---

## Annexe technique détaillée

### Services Firebase utilisés
- **Firebase Authentication** : gestion sécurisée des comptes utilisateurs
- **Cloud Firestore** : base de données principale pour les parties et profils
- **Firebase Realtime Database** : système de présence temps réel
- **Cloud Functions (Node.js 22)** : validation serveur et logique de jeu

Pour plus d'informations sur les pratiques de Google/Firebase : [https://policies.google.com/privacy](https://policies.google.com/privacy)
