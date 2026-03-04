# 🧱 SECTION 1 — La Stack Vibe Coding (Simple + Gratuit)

Tu n'as pas besoin de 300 €/mois en outils pour publier ta première application. Tu as besoin de trois choses, et elles sont toutes gratuites pour commencer.

Cette section couvre la stack exacte qui fonctionne, pourquoi elle fonctionne, et comment la configurer.

---

## Leçon 1.1 — Les Seuls Outils Dont Tu as Besoin pour Commencer (Gratuit)

### Pourquoi les Débutants Dépensent Trop en Outils

La plupart des débutants pensent avoir besoin de :
- Hébergement premium (20 €/mois)
- Services de base de données (15 €/mois)
- Services d'authentification (10 €/mois)
- Éditeurs de code (10 €/mois)
- Outils de gestion de projet (15 €/mois)

**Total : 70 €+/mois avant même d'avoir construit quoi que ce soit.**

**Réalité :** Tu n'as besoin d'aucun de ça pour commencer.

### La Stack Gratuite qui Fonctionne Vraiment

Voici ce dont tu as réellement besoin :

#### 1. **Firebase Studio** (Gratuit)
- Infrastructure backend
- Authentification
- Base de données
- Hébergement
- **Coût :** Le forfait gratuit couvre la plupart des projets débutants

#### 2. **GitHub** (Gratuit)
- Source de vérité pour ton code
- Contrôle de version
- Historique du projet
- **Coût :** Gratuit pour les dépôts publics et privés

#### 3. **Cursor** (Forfait gratuit disponible)
- Éditeur de code propulsé par l'IA
- Comprend l'intégralité de ta base de code
- T'aide à construire plus vite
- **Coût :** Forfait gratuit disponible, les plans payants commencent à 20 €/mois (mais tu peux démarrer gratuitement)

**Total pour commencer : 0 €/mois**

### Pourquoi Cette Stack Fonctionne

**Firebase Studio** supprime les frictions :
- Pas de configuration de serveur
- Pas de configuration de base de données
- Pas de maux de tête au déploiement
- Tout en un seul endroit

**GitHub** te garde organisé :
- Ton code est en sécurité
- Tu peux voir ce qui a changé
- Tu peux travailler de n'importe où
- C'est la mémoire de ton projet

**Cursor** accélère la construction :
- L'IA comprend ton projet
- Tu décris ce que tu veux
- Elle écrit le code
- Tu te concentres sur la construction, pas la syntaxe

### Le Point Clé

**Tu n'as pas besoin de 300 €/mois en outils pour publier ta première application.**

Tu as besoin de :
1. Un endroit pour construire (Firebase Studio)
2. Un endroit pour sauvegarder ton travail (GitHub)
3. Un moyen de construire rapidement (Cursor)

C'est tout.

---

## Leçon 1.2 — Pourquoi Firebase Studio est Parfait pour les Débutants

### Ce que Firebase Studio te Donne Directement

Quand tu crées un projet dans Firebase Studio, tu obtiens :

#### Authentification
- Inscription et connexion des utilisateurs
- Réinitialisation du mot de passe
- Vérification par e-mail
- Connexions sociales (Google, etc.)
- **Tu ne codes pas ça. Ça fonctionne juste.**

#### Base de données
- Base de données en temps réel (Firestore)
- Aucune connaissance SQL nécessaire
- Stocke et récupère des données facilement
- **Tu ne configures pas de serveurs. C'est déjà là.**

#### Hébergement
- Déploie ton application en un clic
- Obtiens une URL en direct instantanément
- Certificats SSL automatiques
- **Tu ne configures rien. Ça se déploie.**

### Pourquoi Ça Supprime les Frictions

**La voie traditionnelle :**
1. Configurer un serveur (des heures de configuration)
2. Configurer une base de données (encore plus de configuration)
3. Configurer l'authentification (encore plus de configuration)
4. Configurer l'hébergement (maux de tête au déploiement)
5. Finalement commencer à construire

**La voie Firebase Studio :**
1. Créer un projet
2. Commencer à construire
3. Déployer quand c'est prêt

**Les tâches ennuyeuses mais importantes sont gérées pour toi.**

### Pourquoi C'est Mieux que « l'Enfer de la Configuration Locale »

La plupart des tutoriels commencent par :
- « Installe Node.js »
- « Installe les packages npm »
- « Configure ton environnement local »
- « Configure ta base de données »
- « Configure l'authentification »

**Résultat :** Tu passes 3 heures à configurer et 30 minutes à construire.

Firebase Studio renverse tout ça :
- Créer un compte (2 minutes)
- Créer un projet (1 minute)
- Commencer à construire (immédiatement)

**Tu passes 3 minutes à configurer et des heures à construire.**

### Le Workflow Réel (C'est la Clé)

Voici le workflow exact que j'utilise (et que tu utiliseras aussi) :

**Étape 1 : Construire les Ossatures du Projet dans Firebase Studio**
- Crée ton projet dans Firebase Studio
- Utilise des invites pour construire les « ossatures du projet » — la structure de base et le squelette
- Lance quelques invites pour le mettre en mouvement
- C'est là que tu établis la fondation avant de plonger en profondeur

**Étape 2 : Publier depuis Firebase Studio**
- Publie ton projet depuis Firebase Studio
- Cela crée le dossier du projet dans Firebase Console
- **Cette étape est cruciale** — elle configure ton projet dans l'écosystème Firebase

**Étape 3 : Activer les Services dans Firebase Console**
- Va dans Firebase Console (le projet que tu viens de publier)
- Active l'Authentification (Email/Mot de passe)
- Active la Base de données Firestore
- Active l'Hébergement
- Configure tous les autres services dont tu as besoin
- **Ça simplifie beaucoup ta vie plus tard** — tous les services sont prêts à l'emploi

**Étape 4 : Synchroniser avec GitHub (Automatique !)**
- Quand tu synchronises depuis Firebase Studio, il te demandera de créer un dépôt GitHub
- Tu entres juste un nom de dépôt (comme `my-note-app`)
- Firebase Studio crée automatiquement le dépôt et synchronise ton code dessus
- **Tu ne crées pas le dépôt manuellement. Firebase Studio le fait pour toi.**
- **Important :** Garde tes dépôts privés (ne commit pas de clés secrètes ou d'infos sensibles)

**Étape 5 : Cloner dans Cursor**
- Clone le dépôt GitHub sur ton ordinateur
- Ouvre le dossier du projet dans Cursor
- Tu peux maintenant construire rapidement avec l'IA
- Tous tes services Firebase sont déjà configurés, donc Cursor peut travailler avec eux immédiatement

**Étape 6 : Construire et Itérer**
- Utilise Cursor pour construire des fonctionnalités, refactoriser et améliorer
- Commit les changements dans GitHub
- Synchronise de nouveau avec Firebase Studio quand tu es prêt
- Déploie depuis Firebase Studio (déploiement en un clic)

**Cette boucle est tout le jeu : Construire les ossatures → Publier → Activer les services → Synchroniser avec GitHub → Construire dans Cursor → Déployer. Répéter.**

**Pourquoi ce workflow fonctionne :**
- Firebase Studio supprime les frictions de configuration (commencer à construire immédiatement)
- Publier d'abord assure que tous les services sont correctement configurés
- Activer les services tôt facilite tout plus tard
- Firebase Studio supprime les frictions de configuration GitHub (crée le dépôt pour toi automatiquement)
- Cursor supprime les frictions de construction (l'IA t'aide à construire vite avec tout déjà configuré)

**Tu ne combats pas les outils. Tu utilises chaque outil pour ce qu'il fait de mieux.**

### Configurer Firebase Studio

**Exercice : Créer ton Compte Firebase Studio**

1. Va sur [Firebase Studio](https://studio.firebase.google.com/)
2. Inscris-toi avec ton compte Google (ou crées-en un)
3. Crée ton premier projet
4. Nomme-le quelque chose de simple : `my-first-vibe-app`

**C'est tout. Tu es prêt à construire.**

**Note :** Ne t'inquiète pas de configurer quoi que ce soit pour l'instant. On abordera la construction des ossatures du projet et l'activation des services dans la Section 4 quand on construira quelque chose de réel.

---

## 🎯 Exercice Pratique

**Crée ton compte Firebase Studio maintenant.**

N'attends pas. Ne t'en fais pas trop. Crée juste le compte.

Mets un ✅ quand c'est fait (même si c'est juste dans ta tête).

**Suivant :** [SECTION 2 — GitHub Sans la Peur](./03-github.md)

