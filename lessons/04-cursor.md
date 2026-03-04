# 🤖 SECTION 3 — Cursor : Ton Co-Développeur IA

Cursor, c'est là où la magie opère. Ce n'est pas juste un éditeur de code. C'est un co-développeur IA qui comprend l'intégralité de ton projet et t'aide à construire plus vite.

Cette section te montre comment utiliser Cursor comme un pro (même si tu es débutant).

---

## Leçon 3.1 — Ce que Cursor Fait Différemment

### Pourquoi Cursor Surpasse le Copier/Coller avec ChatGPT

**L'ancienne façon (ChatGPT) :**
1. Copier ton code
2. Le coller dans ChatGPT
3. Poser une question
4. Copier la réponse
5. La recoller
6. Espérer que ça fonctionne
7. Recommencer

**La façon Cursor :**
1. Poser une question dans ton éditeur
2. Cursor comprend toute ta base de code
3. Il modifie les fichiers directement
4. Tu vois les changements immédiatement
5. Tu continues à construire

**Cursor est l'IA à l'intérieur de ta base de code, pas l'IA dans une fenêtre séparée.**

### L'IA à l'Intérieur de ta Base de Code

Voici ce qui rend Cursor différent :

**Conscience du contexte :**
- Cursor voit tous tes fichiers
- Il comprend la structure de ton projet
- Il sait sur quoi tu travailles
- Il propose des changements qui correspondent à ta base de code

**Édition directe :**
- Cursor édite les fichiers directement
- Pas de copier/coller
- Pas de changement de contexte
- Tu restes dans le flux

**Compréhension du projet :**
- Cursor connaît tes dépendances
- Il comprend ta structure de fichiers
- Il suggère des améliorations basées sur ton code
- C'est comme avoir un développeur senior qui connaît tout ton projet

### Éditer des Fichiers avec Contexte

**Exemple :**

Tu construis une application de prise de notes. Tu demandes à Cursor :

« Je veux que les utilisateurs puissent modifier leurs notes. »

**Cursor :**
- Regarde ton code existant
- Voit comment tu sauvegardes les notes
- Comprend ta structure de données
- Ajoute une fonction d'édition qui correspond à ton style
- Met à jour l'interface pour inclure des boutons d'édition
- Fait tout ça en contexte

**Tu n'expliques pas ton projet entier. Cursor le connaît déjà.**

### Le Modèle Mental

Pense à Cursor comme ça :

```
Toi (le penseur)          Cursor (le constructeur)
────────────────         ────────────────────────
« Je veux X »       →    « Voici le code pour X »
« Change Y »        →    « Y mis à jour dans 3 fichiers »
« Corrige Z »       →    « Z corrigé, voici ce qui a changé »
```

**Tu décris le comportement. Cursor écrit le code.**

---

## Leçon 3.2 — Comment Parler à l'IA comme un Développeur

### Mauvaises Invites vs. Bonnes Invites

**Mauvaise invite :**
« Écris du code pour l'authentification »

**Pourquoi c'est mauvais :**
- Trop vague
- Pas de contexte
- Cursor ne sait pas ce que tu veux
- Tu auras du code générique qui ne correspond pas

**Bonne invite :**
« Je veux que les utilisateurs puissent s'inscrire et se connecter. Ils doivent pouvoir réinitialiser leur mot de passe s'ils l'oublient. Utilise l'authentification Firebase. »

**Pourquoi c'est bon :**
- Comportement spécifique
- Exigences claires
- Mentionne ta stack
- Cursor sait exactement quoi construire

### Décrire le Comportement, Pas le Code

**Ne dis pas :**
- « Écris une fonction qui... »
- « Crée un composant qui... »
- « Ajoute une requête de base de données... »

**Dis :**
- « Je veux que les utilisateurs puissent... »
- « Quand un utilisateur clique sur X, Y devrait se passer... »
- « Les utilisateurs devraient voir Z quand... »

**Décris ce qui doit se passer, pas comment le coder.**

### Exemples d'Invites qui Fonctionnent

**Pour construire une application de notes :**

✅ « Je veux que les utilisateurs puissent créer des notes. Chaque note doit avoir un titre et un contenu. Les notes doivent être sauvegardées dans Firebase Firestore. »

✅ « Quand un utilisateur clique sur 'Nouvelle Note', montre-lui un formulaire où il peut entrer un titre et un contenu. Quand il soumet, sauvegarde dans Firebase Firestore et affiche dans sa liste de notes. »

✅ « Je veux que les utilisateurs puissent supprimer des notes. Ajoute un bouton de suppression à chaque note. Quand cliqué, retire de Firebase Firestore et met à jour la liste. »

✅ « Je veux que les utilisateurs puissent modifier leurs notes existantes. Ajoute un bouton d'édition qui leur permet de changer le titre et le contenu, puis sauvegarder les changements dans Firebase. »

**Remarque :** Toutes ces invites décrivent le comportement, pas le code.

### Plus d'Exemples du Monde Réel

**Pour un tracker d'habitudes :**

✅ « Je veux que les utilisateurs puissent créer une liste d'habitudes quotidiennes. Chaque habitude doit avoir un nom et une case à cocher. Quand ils la cochent, sauvegarde qu'ils l'ont complétée aujourd'hui dans Firebase. »

✅ « Montre aux utilisateurs une liste de leurs habitudes. Affiche combien de jours d'affilée ils ont complété chaque habitude. Récupère ces données depuis Firebase Firestore. »

**Pour un bookmarker de ressources :**

✅ « Je veux que les utilisateurs puissent sauvegarder des liens. Ils entrent une URL et un titre. Sauvegarde dans Firebase. Affiche tous leurs liens sauvegardés dans une liste. »

✅ « Quand un utilisateur clique sur un lien sauvegardé, ouvre-le dans un nouvel onglet. Suis aussi combien de fois chaque lien a été cliqué et affiche ce nombre. »

**Le modèle :** Décris ce qui doit se passer, mentionne Firebase/Firestore, et sois précis sur l'expérience utilisateur.

### Construction Itérative

**Tu ne construis pas tout en même temps. Tu construis de manière itérative.**

**Étape 1 :** « Je veux une application simple où les utilisateurs peuvent se connecter. »

**Étape 2 :** « Maintenant je veux que les utilisateurs puissent sauvegarder des notes après s'être connectés. »

**Étape 3 :** « Maintenant je veux que les utilisateurs puissent modifier leurs notes. »

**Étape 4 :** « Maintenant je veux que les utilisateurs puissent supprimer des notes. »

**Chaque étape s'appuie sur la précédente. Tu n'essaies pas de tout construire en même temps.**

### La Formule d'Invite

**Les bonnes invites suivent cette formule :**

1. **Qui :** « Les utilisateurs » ou « Je veux »
2. **Quoi :** L'action ou le comportement
3. **Comment :** La stack ou la méthode (optionnel, mais utile)
4. **Contexte :** Ce avec quoi ça doit fonctionner (optionnel)

**Exemple :**
« Je veux que les utilisateurs puissent sauvegarder des notes dans Firebase après s'être connectés. »

- Qui : Les utilisateurs
- Quoi : Sauvegarder des notes
- Comment : Firebase
- Contexte : Après s'être connectés

**C'est une invite parfaite.**

### Erreurs Courantes à Éviter

**Erreur 1 : Être trop vague**
❌ « Améliore ça »
✅ « Je veux que le formulaire de connexion affiche un message d'erreur si le mot de passe est incorrect »

**Erreur 2 : Demander tout en même temps**
❌ « Construis une application de prise de notes complète avec authentification, opérations CRUD et une belle interface »
✅ « Je veux que les utilisateurs puissent se connecter » (puis construire à partir de là)

**Erreur 3 : Ne pas fournir de contexte**
❌ « Ajoute un bouton »
✅ « Ajoute un bouton de suppression à chaque note qui la retire de Firebase quand cliqué »

**Erreur 4 : Demander du code, pas du comportement**
❌ « Écris une fonction qui interroge la base de données »
✅ « Je veux afficher toutes les notes de l'utilisateur quand il se connecte »

---

## 🎯 Exercice Pratique

**Entraîne-toi à écrire des invites :**

Pense à ton idée de projet de la Section 0. Écris 3 invites qui décrivent ce que tu veux construire :

1. Une invite pour la fonctionnalité principale
2. Une invite pour une fonctionnalité secondaire
3. Une invite pour améliorer l'expérience utilisateur

**Exemple (pour une application de notes) :**
1. « Je veux que les utilisateurs puissent créer et sauvegarder des notes dans Firebase »
2. « Je veux que les utilisateurs puissent voir toutes leurs notes dans une liste »
3. « Je veux que la liste de notes se mette à jour automatiquement quand une nouvelle note est créée »

**Ce sont les invites que tu utiliseras quand tu commenceras à construire dans la Section 4.**

---

## 🎯 Configurer Cursor

### Installe l'Application Bureau (Pas la Version Navigateur !)

**Important :** Installe Cursor sur ton ordinateur. **N'utilise PAS la version navigateur.** La version navigateur est horrible et ne fonctionne pas bien pour le vibe coding.

**Voici comment installer Cursor correctement :**

#### Étape 1 : Télécharger Cursor

1. **Va sur [Cursor.sh](https://cursor.sh/)**
2. **Clique sur « Download »** (généralement un grand bouton sur la page d'accueil)
3. **Choisis ton système d'exploitation :**
   - **Windows :** Télécharge le fichier `.exe`
   - **Mac :** Télécharge le fichier `.dmg`
   - **Linux :** Télécharge le package approprié pour ta distribution

**C'est gratuit pour commencer.** Tu peux utiliser le forfait gratuit, et les plans payants commencent à 20 €/mois si tu veux plus de fonctionnalités plus tard.

#### Étape 2 : Installer Cursor

**Pour Windows :**
1. Trouve le fichier `.exe` téléchargé (généralement dans ton dossier Téléchargements)
2. Double-clique pour lancer l'installateur
3. Suis l'assistant d'installation (clique sur « Suivant » à travers les invites)
4. Choisis où l'installer (l'emplacement par défaut est bien)
5. Clique sur « Installer »
6. Attends que l'installation se termine
7. Clique sur « Terminer »

**Pour Mac :**
1. Trouve le fichier `.dmg` téléchargé (généralement dans ton dossier Téléchargements)
2. Double-clique pour ouvrir
3. Fais glisser l'icône Cursor vers ton dossier Applications
4. Ouvre Applications et double-clique sur Cursor pour le lancer
5. Si tu obtiens un avertissement de sécurité, va dans Préférences Système → Sécurité et confidentialité → Clique sur « Ouvrir quand même »

**Pour Linux :**
1. Extrais ou installe le package téléchargé selon ta distribution
2. Suis le processus d'installation standard de ta distribution

#### Étape 3 : Ouvrir Cursor

1. **Lance Cursor** depuis tes applications ou le menu démarrer
2. **Connecte-toi ou crée un compte** (si on te le demande)
3. **Tu es prêt à aller !**

### Pourquoi Pas la Version Navigateur ?

**La version navigateur de Cursor :**
- ❌ N'a pas un accès complet à ton système de fichiers
- ❌ Ne peut pas comprendre correctement toute ta base de code
- ❌ Capacités IA limitées
- ❌ Plus lente et moins fiable
- ❌ Fonctionnalités clés manquantes dont tu as besoin pour le vibe coding

**L'application bureau :**
- ✅ Accès complet à tes fichiers
- ✅ Comprend tout ton projet
- ✅ Meilleure assistance IA
- ✅ Plus rapide et plus fiable
- ✅ Toutes les fonctionnalités dont tu as besoin

**En résumé :** Installe l'application bureau. N'utilise pas la version navigateur. Ça vaut les 2 minutes d'installation.

### Comment Cursor Fonctionne avec ton Projet

**Cursor fonctionne mieux quand tu ouvres un dossier (ton projet) :**

1. **Ouvre Cursor**
2. **Clique sur « Fichier » → « Ouvrir un Dossier »** (ou utilise le raccourci clavier)
3. **Sélectionne le dossier de ton projet** (celui avec ton code)
4. **Cursor comprend maintenant tout ton projet**

**On fera ça dans la Section 4 quand on commencera à construire.** Pour l'instant, assure-toi juste que Cursor est installé sur ton ordinateur.

### Configuration Initiale

**Quand tu ouvres Cursor pour la première fois :**

1. Il pourrait te demander de te connecter ou de créer un compte
2. Il pourrait te montrer un écran de bienvenue ou un tutoriel
3. Tu peux passer le tutoriel si tu veux (on va apprendre en construisant)
4. Tu es prêt à commencer à construire !

**C'est tout. Cursor est installé et prêt.**

---

## 🎯 Exercice Pratique

**Installe Cursor sur ton ordinateur maintenant :**

1. Va sur [Cursor.sh](https://cursor.sh/)
2. Télécharge l'application bureau (pas la version navigateur !)
3. Installe-la
4. Ouvre-la
5. Assure-toi qu'elle fonctionne

**N'attends pas. N'utilise pas la version navigateur. Installe l'application bureau.**

**Suivant :** [SECTION 4 — Ta Première Vraie Construction (Petite mais Réelle)](./05-first-build.md)

---

**Suivant :** [SECTION 4 — Ta Première Vraie Construction (Petite mais Réelle)](./05-first-build.md)

