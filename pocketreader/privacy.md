---
layout: default
---

# Politique de confidentialité

**PocketReader**  
*Dernière mise à jour : 2 mai 2026*

## Aperçu

PocketReader (« l'App ») est une application de lecture différée développée par Sébastien Allamand (« nous »). Nous nous engageons à protéger votre vie privée et à être transparents sur les données que nous collectons.

## Données collectées

### Informations de compte
- **Adresse email** — utilisée pour l'authentification et la récupération de compte via AWS Cognito.
- Aucune autre information personnelle n'est requise.

### Données de contenu
- **URLs et contenu d'articles** — les URLs sauvegardées, le texte extrait, titres et métadonnées sont stockés pour fournir la fonctionnalité de lecture différée.
- **Collections** — les groupements d'articles que vous créez.
- **Notes** — les notes que vous écrivez sur les articles.

### Données d'utilisation
- **Compteurs d'utilisation mensuels** — stockés localement sur votre appareil. Jamais transmis à nos serveurs.
- **Pas d'analytics ni de tracking** — nous n'utilisons aucun SDK d'analytics, identifiant publicitaire ou technologie de suivi.

## Utilisation des données

Vos données sont utilisées uniquement pour fournir les fonctionnalités de l'App :
- Stockage et synchronisation de vos articles
- Génération de résumés IA (via AWS Bedrock)
- Génération d'audio text-to-speech (via Amazon Polly)

## Services tiers

| Service | Finalité | Données partagées |
|---------|----------|-------------------|
| AWS Cognito | Authentification | Email, mot de passe hashé |
| AWS DynamoDB | Stockage | Contenu articles, métadonnées |
| AWS Bedrock (Claude) | Résumés IA | Texte article (traité, non conservé) |
| Amazon Polly | Text-to-speech | Texte article (traité, non conservé) |
| Amazon S3 | Stockage audio temporaire | Fichiers TTS (supprimés après 7 jours) |

Nous ne vendons, partageons ou transférons **aucune** donnée à d'autres tiers.

## Stockage et sécurité

- Toutes les données sont stockées dans la région AWS eu-west-3 (Paris, France).
- Données chiffrées en transit (TLS 1.2+) et au repos (AES-256).
- Tokens d'authentification stockés dans le Keychain iOS.

## Vos droits (RGPD)

En tant qu'utilisateur européen, vous avez le droit de :
- **Accéder** à vos données
- **Supprimer** vos données — supprimez votre compte dans Réglages
- **Portabilité** — demandez une copie en nous contactant
- **Rectification** — mettez à jour vos informations dans l'App

## Conservation des données

- Vos articles et données de compte sont conservés jusqu'à suppression du compte.
- Les fichiers audio TTS sont automatiquement supprimés après 7 jours.
- Après suppression du compte, toutes les données sont définitivement supprimées sous 30 jours.

## Mineurs

L'App n'est pas destinée aux enfants de moins de 13 ans.

## Contact

Pour toute question relative à la confidentialité :
- **Email :** support@pocketreader.dev

---

*Cette politique est effective au 2 mai 2026.*
