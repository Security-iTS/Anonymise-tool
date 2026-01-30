# Data Anonymization and Pseudonymization Project

**English :**

## Context and Challenges

In a world where personal data is ubiquitous, anonymization has become a major challenge for both organizations and individuals. Data breaches, misuse, and digital surveillance reinforce the need to protect sensitive information.

Regulations such as GDPR, CNIL guidelines, and ISO standards now impose strict data processing practices. Beyond legal compliance, anonymization is a key driver of trust, security, and digital responsibility.

This project addresses these challenges by providing a concrete, operational, and secure tool designed for real-world professional environments.

## Project Objectives
* Protect personal and sensitive data
* Reduce legal and technical risks related to data breaches
* Enable data processing, analysis, and sharing without exposing real identities
* Provide an accessible and user-friendly solution, usable by non-technical profiles

## Key Features
* Intuitive graphical user interface (GUI): easy to use, no command line required
* Multi-column pseudonymization: bulk processing of datasets
* Automatic data type detection:
    * Email addresses
    * Phone numbers
    * IBANs
    * First and last names
    * Alphanumeric identifiers
* Format-preserving pseudonymization: data remains consistent and usable
* Encrypted mapping (AES / Fernet): strong protection of the link between original and pseudonymized data
* Option to remove the identity link (enhanced anonymization)
* Timestamped audit log: action traceability without exposing sensitive data
* CSV and JSON support for both input and output
* Generation of reusable pseudonym datasets

## Why Anonymization Is Essential Today

### In organizations
* Protection of customer, HR, medical, or financial databases
* Securing testing and development environments
* Safe data sharing with partners
* Regulatory compliance and reduced risk of penalties

### On a personal level
* Protection of privacy
* Reduced digital exposure
* Awareness of cybersecurity best practices

Anonymization is no longer a technical luxury — it is a strategic necessity.

## Security and Best Practices
* No storage of sensitive data in plain text
* Strong encryption with separate key management
* Audit logs without personal data leakage
* Simple, readable, and maintainable architecture
* Well-documented and structured code for professional use

## Vision and Future Enhancements

This project was designed as a solid foundation, extensible toward:
* K-anonymity and differential privacy
* Salted irreversible hashing
* Excel support and batch processing
* Automated audit reports
* Integration into enterprise workflows

## About the Project

This project demonstrates:
* A concrete understanding of modern data challenges
* A security-, compliance-, and UX-oriented approach
* The ability to design tools usable in real-world conditions

It targets both technical teams and business roles, including DPOs, analysts, and decision-makers.

\
\
\
\
      
**Français :**

# Projet d’Anonymisation et de Pseudonymisation des Données

## Contexte et enjeux

Dans un monde où les données personnelles sont omniprésentes, l’anonymisation est devenue un enjeu majeur, aussi bien pour les entreprises que pour les particuliers. Les violations de données, les usages abusifs et la surveillance numérique renforcent la nécessité de protéger les informations sensibles.

Les réglementations comme le RGPD, la CNIL, ou encore les normes ISO imposent aujourd’hui des pratiques strictes en matière de traitement des données. Mais au-delà de l’aspect légal, l’anonymisation est un levier de confiance, de sécurité et de responsabilité numérique.

Ce projet répond à ces enjeux en proposant un outil concret, opérationnel et sécurisé, pensé pour un usage réel en environnement professionnel.

## Objectifs du projet
* Protéger les données personnelles et sensibles
* Réduire les risques juridiques et techniques liés aux fuites de données
* Permettre le traitement, l’analyse et le partage de données sans exposer les identités réelles
* Proposer une solution accessible, compréhensible et utilisable par des profils non techniques

## Fonctionnalités principales
* Interface graphique intuitive (GUI) : utilisation simple, sans ligne de commande
* Pseudonymisation multi-colonnes : traitement en masse de jeux de données
* Reconnaissance automatique du type de données :
    * Emails
    * Numéros de téléphone
    * IBAN
    * Noms / prénoms
    * Identifiants alphanumériques
* Pseudonymisation respectant le format : les données restent cohérentes et exploitables
* Mapping chiffré (AES / Fernet) : protection forte du lien entre données originales et pseudonymisées
* Option de suppression du lien d’identité (anonymisation renforcée)
* Journal d’audit horodaté : traçabilité des actions sans exposer les données sensibles
* Support CSV et JSON en entrée et en sortie
* Génération de jeux de pseudonymes réutilisables

## Pourquoi l’anonymisation est essentielle aujourd’hui
### En entreprise
* Protection des bases clients, RH, médicales ou financières
* Sécurisation des environnements de test et de développement
* Partage de données avec des partenaires sans risque
* Conformité réglementaire et réduction des sanctions

### À titre personnel
* Protection de la vie privée
* Réduction de l’exposition numérique
* Sensibilisation aux bonnes pratiques de cybersécurité

L’anonymisation n’est plus un luxe technique : c’est une nécessité stratégique.

## Sécurité et bonnes pratiques
* Aucun stockage en clair des données sensibles
* Chiffrement fort et clé séparée
* Journal d’audit sans fuite d’information personnelle
* Architecture simple, lisible et maintenable
* Code commenté et structuré pour un usage professionnel

## Vision et évolutions possibles

Ce projet a été conçu comme une base solide, extensible vers :
* K-anonymity et privacy différentielle
* Hash irréversible salé
* Support Excel et traitements batch
* Rapports d’audit automatisés
* Intégration dans des workflows d’entreprise

## À propos du projet

Ce projet démontre :
* Une compréhension concrète des enjeux actuels de la donnée
* Une approche orientée sécurité, conformité et UX
* Une capacité à concevoir des outils utilisables en conditions réelles

Il s’adresse autant à des équipes techniques, qu’à des métiers, DPO, analystes ou décideurs.
