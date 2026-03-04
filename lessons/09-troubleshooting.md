# 🔧 Dépannage : Quand Les Choses se Cassent

Les choses vont se casser. C'est normal. Cette section t'aide à corriger les problèmes les plus courants sans paniquer.

---

## Le Mindset

**Quand quelque chose se casse :**
1. Ne panique pas
2. Lis le message d'erreur
3. Demande à Cursor de le corriger
4. Si ça ne fonctionne pas, demande à la communauté

**La plupart des erreurs sont des corrections simples. Tu as juste besoin de savoir où chercher.**

---

## Problèmes Courants Firebase

### « Firebase is not defined »

**Ce que ça signifie :** Ton SDK Firebase n'est pas chargé ou configuré correctement.

**Comment corriger :**
1. Assure-toi que tu as inclus le SDK Firebase dans ton HTML
2. Vérifie que ta configuration Firebase est correcte
3. Demande à Cursor : « J'ai une erreur 'Firebase is not defined'. Vérifie ma configuration Firebase et assure-toi qu'elle est correctement configurée. »

### « Permission denied » dans Firestore

**Ce que ça signifie :** Tes règles de sécurité bloquent l'opération.

**Comment corriger :**
1. Va dans Firebase Console → Base de données Firestore → Règles
2. Pour le développement, tu peux temporairement utiliser :
   ```
   rules_version = '2';
   service cloud.firestore {
     match /databases/{database}/documents {
       match /{document=**} {
         allow read, write: if request.auth != null;
       }
     }
   }
   ```
3. **Avertissement :** Cela permet à tout utilisateur connecté de lire/écrire tout. Bien pour l'apprentissage, pas pour la production.

**Demande à Cursor :** « J'ai des erreurs de permission refusée. Aide-moi à configurer des règles de sécurité Firestore de base pour le développement. »

### L'authentification ne fonctionne pas

**Ce que ça signifie :** L'auth n'est peut-être pas activée ou configurée correctement.

**Comment corriger :**
1. Va dans Firebase Console → Authentification → Méthode de connexion
2. Active « Email/Mot de passe »
3. Assure-toi que ton code auth correspond à ta configuration Firebase
4. Vérifie la console du navigateur pour des messages d'erreur spécifiques

**Demande à Cursor :** « Mon authentification Firebase ne fonctionne pas. Vérifie mon code auth et aide-moi à le déboguer. »

---

## Problèmes Courants Cursor

### Cursor génère du code qui ne fonctionne pas

**Ce que ça signifie :** L'invite n'était pas assez spécifique, ou Cursor a fait une hypothèse.

**Comment corriger :**
1. Sois plus spécifique dans ton invite
2. Montre à Cursor le message d'erreur
3. Demande : « Ce code ne fonctionne pas. Voici l'erreur : [erreur]. Corrige-le. »
4. Fournis du contexte sur ce que tu essaies de faire

**Exemple :**
❌ « Corrige ça »
✅ « Ce code d'auth Firebase ne fonctionne pas. L'erreur dit 'auth/operation-not-allowed'. J'essaie de laisser les utilisateurs s'inscrire avec un email et un mot de passe. Corrige-le. »

### Cursor ne comprend pas mon projet

**Ce que ça signifie :** Cursor a besoin de plus de contexte sur ta base de code.

**Comment corriger :**
1. Assure-toi que tu as ouvert tout le dossier du projet dans Cursor
2. Référence des fichiers spécifiques dans tes invites
3. Montre à Cursor le code associé : « Voici mon code auth [code]. Maintenant je veux ajouter un bouton de déconnexion. Fais-le fonctionner avec ce code existant. »

---

## Problèmes Courants GitHub

### « Repository not found »

**Ce que ça signifie :** GitHub ne peut pas trouver ton dépôt, ou tu n'es pas authentifié.

**Comment corriger :**
1. Assure-toi d'être connecté à GitHub
2. Vérifie que le nom du dépôt est correct
3. Vérifie que tu as accès au dépôt
4. Essaie de le cloner à nouveau : `git clone [repo-url]`

### « Les changements n'apparaissent pas »

**Ce que ça signifie :** Tu n'as pas commité et poussé tes changements.

**Comment corriger :**
1. Commit tes changements : `git add .` puis `git commit -m "Ton message"`
2. Pousse vers GitHub : `git push`
3. Rafraîchis GitHub dans ton navigateur

**Demande à Cursor :** « Aide-moi à commiter et pousser mes changements vers GitHub. Explique-moi les commandes git. »

---

## Problèmes Courants de Déploiement

### Erreurs de build au déploiement

**Ce que ça signifie :** Ton code a des erreurs, ou le processus de build échoue.

**Comment corriger :**
1. Teste ton application localement d'abord
2. Vérifie les logs de déploiement Firebase pour des erreurs spécifiques
3. Corrige les erreurs localement
4. Essaie de déployer à nouveau

**Demande à Cursor :** « J'ai des erreurs de build au déploiement vers Firebase. Voici l'erreur : [erreur]. Aide-moi à la corriger. »

### L'application fonctionne localement mais pas une fois déployée

**Ce que ça signifie :** Les variables d'environnement ou les chemins pourraient être incorrects.

**Comment corriger :**
1. Vérifie que ta configuration Firebase est correcte
2. Assure-toi que tous les chemins de fichiers sont relatifs (pas absolus)
3. Vérifie la console du navigateur sur le site déployé pour des erreurs
4. Vérifie que les paramètres de ton projet Firebase correspondent à ton code

**Demande à Cursor :** « Mon application fonctionne localement mais se casse une fois déployée. Aide-moi à déboguer les différences entre les environnements local et déployé. »

---

## Le Problème « Rien ne Fonctionne »

**Quand rien ne semble fonctionner :**

1. **Fais une pause** — Parfois s'éloigner aide
2. **Simplifie** — Réduis-le aux bases absolues
3. **Recommence à zéro** — Parfois repartir de zéro est plus rapide que déboguer
4. **Demande de l'aide** — Dans la [communauté Skool](https://www.skool.com/vibe-coding-with-chris-7196)

**Rappelle-toi :** Chaque développeur passe par là. C'est normal. Tu n'es pas cassé. C'est le code qui l'est.

---

## Comment Demander de l'Aide

**Quand tu demandes de l'aide (dans la communauté ou à Cursor), inclus :**

1. **Ce que tu essaies de faire** — L'objectif
2. **Ce que tu attendais** — Le comportement attendu
3. **Ce qui s'est vraiment passé** — Le comportement réel
4. **Le message d'erreur** — Copie/colle l'erreur exacte
5. **Ce que tu as essayé** — Les étapes que tu as déjà suivies

**Exemple :**
« J'essaie de laisser les utilisateurs sauvegarder des notes dans Firestore. J'attendais que la note soit sauvegardée quand ils cliquent sur soumettre. À la place, j'obtiens une erreur : 'Permission denied'. J'ai vérifié que l'auth est activée et que l'utilisateur est connecté. Qu'est-ce qui me manque ? »

**Les bonnes questions obtiennent de bonnes réponses. Sois spécifique.**

---

## Le Mindset de Débogage

**Quand quelque chose se casse :**

1. **Lis l'erreur** — Elle te dit généralement ce qui ne va pas
2. **Vérifie la console** — Les outils de développement du navigateur montrent les erreurs
3. **Simplifie** — Supprime les fonctionnalités jusqu'à ce que ça fonctionne, puis ajoute-les de nouveau
4. **Utilise Cursor** — Demande-lui de déboguer : « Déboguez ce code. Voici l'erreur : [erreur] »
5. **Demande à la communauté** — Quelqu'un est probablement déjà passé par là

**La plupart des bugs sont simples. Tu as juste besoin de les trouver.**

---

## 🎯 Référence Rapide : Corrections Courantes

| Problème | Correction Rapide |
|---------|-----------|
| Firebase non défini | Vérifie que le SDK Firebase est chargé |
| Permission refusée | Mets à jour les règles de sécurité Firestore |
| Auth ne fonctionne pas | Active Email/Mot de passe dans Firebase Console |
| Le code Cursor ne fonctionne pas | Sois plus spécifique dans ton invite |
| Dépôt GitHub introuvable | Vérifie que tu es connecté et que le dépôt existe |
| Erreurs de build | Teste localement d'abord, corrige les erreurs, puis déploie |
| Fonctionne localement, se casse une fois déployé | Vérifie les variables d'environnement et les chemins |

---

**Rappelle-toi :** Casser des choses, c'est comme ça qu'on apprend. Chaque erreur est une leçon.

**Suivant :** Continue à construire. Continue à casser. Continue à corriger. C'est le vibe coding.

---

*Bloqué ? Rejoins la [communauté Skool Vibe Coding avec Chris](https://www.skool.com/vibe-coding-with-chris-7196) pour de l'aide et du soutien.*


