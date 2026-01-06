---
description: Authentification avec double facteurs à votre compte RealT
---

# Accès en 2FA à votre compte

L’activation du 2FA est obligatoire pour les nouveaux utilisateurs et sera progressivement imposée aux anciens (cf [CC 16/10/2025](https://t.me/RtCCR/380) et message suivant qui va apparaitre)

<figure><img src="../.gitbook/assets/image (2) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

## Le 2FA et le TOTP : c'est quoi ?

L’authentification à deux facteurs (2FA) est une méthode de sécurité qui exige que l’utilisateur fournisse une seconde preuve d’identité (en complément de l'identifiant / mot de passe), afin d’accéder à un compte ou un service (ici l'application RealT.co).\
\
La seconde preuve d'identité est un code à usage unique basé sur le temps (Time-based One-Time Password, TOTP), ce code change toutes les 30 à 60 secondes.\
Soit ce code vous est envoyé par email à chaque connexion (ce qui devient vite fastidieux), soit il est généré par une application (solution préférable). Il en existe de [multiples applications TOTP](https://www.clubic.com/guide-achat-538328-authentification-2fa-les-meilleures-applications-en-2024.html), installables sur PC ou mobile.

Avec une application TOTP, l'initialisation se fait avec une clé secrète générée par le site (ici RealT.co). Par la suite, cette clé secrète est utilisée par le site et votre application TOTP pour générer un code suivant l'heure. Si ces deux codes correspondent, votre second authentification est réussit.&#x20;

## Mise en place initiale

Dans le document ci-après sont détaillées les différentes étapes d'installation et explications correspondantes.

{% file src="../.gitbook/assets/Initialisation 2FA.pdf" %}

