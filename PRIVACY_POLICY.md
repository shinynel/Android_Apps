---
title: "Renard Distingué – Politique de Confidentialité"
---

# **Politique de Confidentialité**
**Dernière mise à jour : 06 novembre 2025**

Bienvenue dans **Renard Distingué**, une application Android développée par **Maxime** (Nelwy's Apps).
En tant que développeur et utilisateur soucieux de la vie privée, je m'engage à ce que cette application **ne collecte ni ne partage aucune donnée personnelle** sans votre consentement explicite.

---

## 📜 **Données collectées (ou leur absence)**

### ❌ **Aucune donnée personnelle**
Cette application **ne collecte aucun** :
- Nom, prénom, adresse email ou numéro de téléphone.
- Données de localisation (GPS, adresse IP, etc.).
- Historique d'utilisation ou comportement dans l'application.
- Identifiants publics (comme les comptes Google/Facebook).

### 🔑 **Données techniques anonymes**
- **UID Firebase** :
  Un identifiant unique est généré **localement** par Firebase pour synchroniser les événements.
  - **Anonyme** : Non lié à votre identité réelle.
  - **Usage** : Uniquement pour distinguer les appareils dans la base de données.
  - **Stockage** : Hébergé sur les serveurs **Firebase (Google)**, conformes au RGPD.

- **Préférences locales** :
  Les paramètres (ex : activation des notifications) sont stockés **uniquement sur votre appareil** et supprimés lors de la désinstallation.

### 📊 **Pas de tracking ni d'analytics**
Aucun outil de suivi (Google Analytics, Crashlytics, etc.) n'est intégré.

---

## 🔍 **Explication des permissions**

Les permissions demandées sont **minimales** et nécessaires au fonctionnement de l'application :

| Permission                          | Pourquoi ?                                                                                     | Type               |
|-------------------------------------|-----------------------------------------------------------------------------------------------|--------------------|
| `INTERNET`                          | Télécharger les nouveaux événements et leurs bannières depuis Firebase.                       | Automatique        |
| `POST_NOTIFICATIONS`                | Vous alerter lors de nouveaux événements (doit être **activée manuellement**).                | Manuel (révocable) |
| `VIBRATE`                           | Faire vibrer l'appareil pour les notifications.                                               | Automatique        |

> ⚠️ **Transparence** :
> - Aucune permission n'est utilisée pour collecter des données.
> - Les permissions "Automatiques" sont gérées par Android et **ne peuvent pas être désactivées**.

---

## 🇪🇺 **Conformité RGPD**

### ✅ **Vos droits**
En tant qu'utilisateur européen, vous bénéficiez des droits suivants :
1. **Accès** : Savoir quelles données (ici, aucune personnelle) sont traitées.
2. **Rectification** : Corriger des données (non applicable ici).
3. **Effacement** : Supprimer vos données locales en :
   - Réinitialisant l'application (`Paramètres > Apps > Renard Distingué > Stockage > Effacer les données`).
   - Désinstallant l'application.
4. **Opposition** : Désactiver les notifications à tout moment.

### 🔒 **Sécurité des données**
- **Firebase** : Les UID anonymes sont protégés par les [mesures de sécurité de Google](https://firebase.google.com/support/privacy).
- **Chiffrement** : Les communications avec Firebase utilisent **HTTPS (TLS)**.

---

## 📬 **Contact & Signaler une vulnérabilité**

Pour toute question ou signalement de faille de sécurité :
- **Email** : [nelwy.dev@proton.me](mailto:nelwy.dev@proton.me)

> 💡 Je m'engage à répondre rapidement à toute préoccupation liée à la vie privée.

---

## 📝 **Modifications de cette politique**

Cette politique de confidentialité peut être mise à jour de temps à autre. Toute modification sera publiée sur cette page. Nous vous encourageons à consulter régulièrement cette politique pour rester informé de la manière dont nous protégeons vos informations.

---
*© 2025 Nelwy's Apps. Tous droits réservés.*
*Dernière révision : 06/11/2025*
Privacy Policy inspirée par https://github.com/WrichikBasu
