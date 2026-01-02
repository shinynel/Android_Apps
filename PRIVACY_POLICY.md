---
 Renard Distingué
---

# **Politique de Confidentialité**
**Dernière mise à jour : 2 janvier 2026**

Bienvenue dans **Renard Distingué**, une application Android développée par **Maxime** (Nelwy's Apps).
En tant que développeur et utilisateur soucieux de la vie privée, je m'engage à ce que cette application **ne collecte ni ne partage aucune donnée personnelle identifiable** sans votre consentement explicite.

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

- **Jeton de notification (FCM Token)** :
  - Un identifiant unique généré par Firebase Cloud Messaging.
  - Anonyme : Non lié à votre identité réelle.
  - Usage : Envoyer les notifications de nouveaux événements à votre appareil.
  - Stockage : Hébergé sur les serveurs Firebase (Google), conformes au RGPD.
  - Révocable : En désactivant les notifications dans les paramètres de l'app.

- **Préférences locales** :
  Les paramètres (ex : activation des notifications) sont stockés **uniquement sur votre appareil** et supprimés lors de la désinstallation.

### 📅 **Ajout d'événements au calendrier**
- L'application peut ajouter des événements à **votre calendrier local**
- Aucune donnée n'est envoyée en ligne
- Stockage uniquement sur votre appareil (via add_2_calendar)

### 🖼️ **Sauvegarde d'images dans la galerie**
- L'application peut sauvegarder des images d'articles dans **votre galerie locale**
- **Aucune lecture de vos photos** : L'application ne peut pas accéder à vos photos existantes
- Les images sont créées et sauvegardées localement sur votre appareil
- Sur Android 10+, aucune permission n'est requise grâce au "scoped storage"

### 📊 **Analytics et Statistiques d'Usage (Firebase Analytics)**

L'application utilise **Firebase Analytics** pour améliorer l'expérience utilisateur et comprendre comment l'application est utilisée.

**Données collectées (anonymes)** :
- Navigation dans l'application (onglets visités, temps passé)
- Interactions avec les fonctionnalités :
  - Recherches dans les ressources (termes de recherche)
  - Lectures d'articles (titre, catégorie, durée)
  - Événements ajoutés au calendrier
  - Clics sur les liens partenaires
  - Utilisation de la galerie photo
  - Interactions avec l'onboarding
- Informations techniques : modèle d'appareil, version Android, langue

**Durée de conservation** :
- Données Analytics : 2 mois (Google Firebase)
- FCM Tokens : Jusqu'à révocation des notifications
- Préférences locales : Jusqu'à désinstallation

**Ce qui N'EST PAS collecté** :
- ❌ Aucune donnée personnelle identifiable
- ❌ Pas de contenu saisi par l'utilisateur (hors termes de recherche)
- ❌ Pas de données de localisation précise
- ❌ Pas d'accès à vos photos ou médias existants

**Pourquoi ?**
- Identifier les fonctionnalités les plus/moins utilisées
- Détecter les bugs et améliorer la stabilité
- Optimiser l'expérience utilisateur

**Contrôle** :
- Les données sont **anonymisées** automatiquement par Firebase
- Conformes au **RGPD** (serveurs Google Europe)
- Vous pouvez demander la suppression de vos données via : nelwy.dev@proton.me

### 🔗 **Services tiers**
L'application utilise et contient des liens vers :
- **Firebase (Google)** : Hébergement de données et analytics
  - [Politique de confidentialité Firebase](https://firebase.google.com/support/privacy)
- **HelloAsso** (dons) : Soumis à leur propre politique de confidentialité
- **Réseaux sociaux** (Instagram, FetLife, Telegram, Discord)
- **Google Maps** : Affichage de l'itinéraire vers les événements

### 🌍 **Transferts internationaux de données**
Les données peuvent être transférées vers les **États-Unis** 
dans le cadre de l'utilisation de Firebase (Google LLC).

**Garanties** :
- Google adhère au **EU-US Data Privacy Framework** (2023)
- Clauses contractuelles types de la Commission Européenne
- Plus d'infos : https://firebase.google.com/support/privacy

---

## 🔍 **Explication des permissions**

Les permissions demandées sont **minimales** et nécessaires au fonctionnement de l'application :

| Permission                          | Pourquoi ?                                                                                     | Type               |
|-------------------------------------|-----------------------------------------------------------------------------------------------|--------------------|
| `INTERNET`                          | Télécharger les nouveaux événements et leurs bannières depuis Firebase.                       | Automatique        |
| `POST_NOTIFICATIONS`                | Vous alerter lors de nouveaux événements (doit être **activée manuellement**).                | Manuel (révocable) |
| `VIBRATE`                           | Faire vibrer l'appareil pour les notifications.                                               | Automatique        |
| `WRITE_EXTERNAL_STORAGE`            | Sauvegarder les images d'articles dans votre galerie (**Android 9 et moins uniquement**).     | Automatique        |

> ⚠️ **Transparence** :
> - Aucune permission n'est utilisée pour collecter des données.
> - Les permissions "Automatiques" sont gérées par Android et **ne peuvent pas être désactivées**.
> - Sur Android 10+, la sauvegarde d'images utilise le "scoped storage" et ne nécessite aucune permission.
> - **L'application ne peut PAS lire vos photos existantes.**

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

**Base légale (Art. 6 RGPD)** :
- En téléchargeant et utilisant l'application, vous **acceptez** 
  la collecte de données anonymes via Firebase Analytics.
- Si vous refusez, veuillez désinstaller l'application.

---

## 📬 **Contact & Signaler une vulnérabilité**

Pour toute question ou signalement de faille de sécurité :
- **Email** : [nelwy.dev@proton.me](mailto:nelwy.dev@proton.me)

> 💡 Je m'engage à répondre rapidement à toute préoccupation liée à la vie privée.

---

## 📝 **Modifications de cette politique**

Cette politique de confidentialité peut être mise à jour de temps à autre. Toute modification sera publiée sur cette page. Nous vous encourageons à consulter régulièrement cette politique pour rester informé de la manière dont nous protégeons vos informations.

---
*© 2026 Nelwy's Apps. Tous droits réservés.*
*Dernière révision : 02/01/2026*
Privacy Policy inspirée par https://github.com/WrichikBasu
