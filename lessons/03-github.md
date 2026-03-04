# 🗂️ SECTION 2 — GitHub Sans la Peur

GitHub fait peur à beaucoup de débutants. Ça ne devrait pas. C'est juste un endroit pour sauvegarder ton code et voir ce qui a changé.

**La bonne nouvelle :** Firebase Studio crée ton dépôt GitHub pour toi automatiquement. Tu n'as pas besoin de le configurer manuellement.

Cette section supprime la peur et te montre comment GitHub fonctionne (et comment Firebase Studio le rend facile).

---

## Leçon 2.1 — GitHub Expliqué Comme si Tu Avais 5 Ans

### Ce qu'Est Vraiment GitHub

**GitHub, c'est comme Google Drive pour le code.**

- Tu y sauvegardes ton projet
- Tu peux y accéder de n'importe où
- Tu peux voir ce qui a changé
- Tu peux revenir aux anciennes versions

C'est tout. Pas de magie. Pas de complexité. Juste un endroit pour sauvegarder ton code.

### Dépôts = Dossiers de Projet

Un **dépôt** (repo) est juste un dossier pour ton projet.

Pense-y comme :
- Un dossier sur ton ordinateur = Un dépôt sur GitHub
- Tes fichiers de projet = Tes fichiers de code
- Ton README = Tes notes de projet

**Créer un dépôt, c'est comme créer un nouveau dossier. C'est tout.**

### Commits = Points de Sauvegarde

Un **commit** est comme sauvegarder ta partie.

- Tu fais des changements dans ton code
- Tu les « commit » (sauvegardes)
- GitHub se souvient de ce qui a changé
- Tu peux revenir à n'importe quel point de sauvegarde

**C'est le contrôle de version, mais pense-y comme des « points de sauvegarde » et ça prend tout son sens.**

### Pourquoi GitHub est Important Même si Tu N'es Pas Développeur

Tu pourrais penser : « Je ne suis pas développeur, pourquoi ai-je besoin de GitHub ? »

**Voici pourquoi :**

1. **Ton code est en sécurité** — Si ton ordinateur tombe en panne, ton code est toujours sur GitHub
2. **Tu peux voir ta progression** — Regarde ce que tu as construit et quand
3. **Tu peux travailler de n'importe où** — Accède à ton projet depuis n'importe quel ordinateur
4. **C'est la mémoire de ton projet** — Vois ce qui a changé et pourquoi
5. **C'est professionnel** — Même si tu es débutant, utiliser GitHub montre que tu es sérieux

**Tu n'as pas besoin d'être développeur pour profiter de GitHub. Tu as juste besoin de construire des choses.**

### Le Modèle Mental

Pense à GitHub comme ça :

```
Ton Ordinateur          GitHub
─────────────         ────────
Dossier Projet   →    Dépôt
Sauvegarder      →    Commit
Voir Changements →    Voir l'Historique
```

**Mêmes concepts, noms différents. Ne laisse pas la terminologie t'effrayer.**

---

## Leçon 2.2 — Comment Firebase Studio Crée ton Dépôt (La Façon Facile)

### Firebase Studio le Fait Pour Toi

**Voici la magie :** Tu ne crées pas manuellement un dépôt GitHub. Firebase Studio le fait pour toi.

**Quand tu publies/synchronises ton code depuis Firebase Studio :**

1. Firebase Studio te demandera de te connecter à GitHub
2. Il te demandera de créer un nom de dépôt (comme `my-note-app`)
3. Firebase Studio crée automatiquement le dépôt sur GitHub
4. Ton code est synchronisé vers ce dépôt automatiquement

**C'est tout. Pas de configuration manuelle. Pas de confusion. Firebase Studio gère ça.**

**Note :** Tu peux toujours créer d'abord un dépôt GitHub manuellement si tu préfères. Mais pour le vibe coding, on utilise l'approche automatique de Firebase Studio parce qu'elle supprime les frictions et te permet de construire plus vite. C'est la façon vibe coding.

### Ce que Tu dois Faire

**Avant que Firebase Studio puisse créer ton dépôt :**

1. **Créer un compte GitHub** (si tu n'en as pas un)
   - Va sur [GitHub.com](https://github.com)
   - Inscris-toi (c'est gratuit)
   - C'est tout

2. **Connecter GitHub à Firebase Studio**
   - Quand Firebase Studio te demande de se connecter, autorise-le
   - Cela permet à Firebase Studio de créer des dépôts pour toi

**C'est toute la configuration dont tu as besoin. Firebase Studio fait le reste.**

### Nommer ton Dépôt

Quand Firebase Studio te demande un nom de dépôt, utilise quelque chose de descriptif :

**Bons noms :**
- `my-note-app`
- `habit-tracker`
- `idea-saver`
- `resource-bookmarker`

**Mauvais noms :**
- `project`
- `test`
- `new-thing`
- `asdfghjkl`

**Règle :** Nomme-le par ce qu'il fait, pas par ce qu'il est.

### Garde tes Dépôts Privés (Important !)

**Quand Firebase Studio crée ton dépôt, rends-le privé.**

**Pourquoi ?**
- Ton code t'appartient (tu ne voudras peut-être pas le rendre public)
- Tu pourrais avoir des clés API ou des infos sensibles (on abordera .gitignore plus tard)
- Les dépôts privés sont gratuits sur GitHub

**Comment le rendre privé :**
- Quand Firebase Studio te le demande, sélectionne « Dépôt privé »
- Ou change-le plus tard dans les paramètres GitHub

**Ne commit pas de clés secrètes ou d'informations sensibles.** On apprendra .gitignore plus tard pour gérer ça correctement.

### Ce qui se Passe Après que Firebase Studio Crée ton Dépôt

**Une fois que Firebase Studio a créé ton dépôt :**

1. Ton code est sur GitHub (en sécurité et sauvegardé)
2. Tu peux le cloner sur ton ordinateur
3. Tu peux l'ouvrir dans Cursor
4. Tu peux travailler dessus localement
5. Tu peux committer les changements et les repousser

**Firebase Studio a rendu ça facile. Maintenant tu peux utiliser GitHub comme un pro.**

### Utiliser GitHub comme une Carte de Projet

GitHub ne sert pas qu'à sauvegarder du code. C'est pour suivre ton projet.

**Tes commits racontent une histoire :**
- « Ajout de l'authentification utilisateur »
- « Création de la fonctionnalité de sauvegarde de notes »
- « Correction du bug de connexion »
- « Ajout de la fonctionnalité de suppression »

**Chaque commit est une étape. Ensemble, ils constituent l'historique de ton projet.**

---

## 🎯 Exercice Pratique

**Avant de construire ta première application :**

1. **Créer un compte GitHub** (si tu n'en as pas un)
   - Va sur [GitHub.com](https://github.com)
   - Inscris-toi (c'est gratuit)
   - Vérifie ton e-mail

2. **C'est tout !** Firebase Studio s'occupera du reste quand tu publieras ta première application.

**Tu n'as pas besoin de créer un dépôt manuellement. Firebase Studio le fera pour toi quand tu synchroniseras ton code.**

**C'est la façon vibe coding :** Supprime les frictions. Laisse les outils faire la configuration. Concentre-toi sur la construction, pas la configuration.

**Suivant :** [SECTION 3 — Cursor : Ton Co-Développeur IA](./04-cursor.md)

