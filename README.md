# exo-afrix-html-devops
Projet d'initiation au devops 

### À LIRE AVANT DE COMMENCER LE DÉVELOPPEMENT 


# 📘 Guide de Contribution – Projet HTML + Tailwind (Débutants Bienvenus)

Bienvenue dans ce projet ! 🎉

Ce guide explique **pas à pas**, de façon **ULTRA simple**, comment contribuer correctement au projet. Même si tu es débutant, tu vas pouvoir participer sans stress.

---

# 🚀 1. Prérequis

Pour contribuer, tu as besoin de :

* **Git** installé sur ton ordinateur
* **Node.js** installé (version LTS recommandée)
* Un éditeur comme **VS Code**

Si ce n’est pas encore fait :

* Git → [https://git-scm.com](https://git-scm.com)
* Node.js → [https://nodejs.org](https://nodejs.org)

---

# 🌱 2. Récupérer le projet (Cloner le dépôt)

Ouvre un terminal puis tape :

```bash
git clone https://github.com/TON_REPO.git
cd TON_REPO
```

> ⚠️ Ne jamais travailler directement sur la branche **main**.

---

# 📦 3. Installer les dépendances

Dans le dossier du projet, exécute :

```bash
npm install
```

Cela installe Tailwind, les outils de qualité, etc.

---

# 🌿 4. Créer ta propre branche (OBLIGATOIRE)

Chaque nouvelle fonctionnalité doit être faite dans une branche séparée.

Nom de branche recommandé :

* `feature/nom-fonctionnalite`
* `fix/nom-du-bug`
* `docs/amelioration-doc`

👉 Exemple :

```bash
git checkout -b feature/ajout-header
```

---

# 🛠️ 5. Lancer le projet en mode développement

```bash
npm run dev
```

Puis ouvre `index.html` dans ton navigateur.

Dès que tu modifies un fichier, le CSS Tailwind se met automatiquement à jour.

---

# 🧹 6. Vérifier la qualité du code (Lint)

Avant de proposer tes changements, vérifie que ton code est propre :

```bash
npm run lint
```

Si tout va bien → aucun message d’erreur.
Si tu vois des erreurs → corrige-les avant de continuer.

---

# 🧪 7. S’assurer que tout fonctionne (Build)

```bash
npm run build
```

S’il n’y a pas d’erreurs, tu peux passer à l’étape suivante.

---

# 🔄 8. Ajouter, commit et push tes changements

Quand tout est prêt :

### 🔹 Ajouter les fichiers

```bash
git add .
```

### 🔹 Écrire un message de commit clair

```bash
git commit -m "Ajout du header responsive"
```

### 🔹 Envoyer ta branche sur GitHub

```bash
git push origin feature/ajout-header
```

---

# 🔃 9. Créer une Pull Request (PR)

1. Va sur GitHub → ton dépôt

2. GitHub te propose : **"Compare & Pull Request"**

3. Indique :

   * un bon titre (ex : *Ajout header responsive*)
   * une description simple de ce que tu as fait

4. Soumets la PR.

> 🛑 Ta PR sera automatiquement testée (lint + build).
> Si un test échoue → corrige et renvoie les modifications.

---

# 👨‍💼 10. Validation du Team Leader

Seul le **Team Leader** peut :

* approuver la PR
* merger dans `main`

Si tout est bon → ta contribution est intégrée ! 🎉

---

# 🎯 Résumé rapide

| Étape                 | Commande                    |
| --------------------- | --------------------------- |
| Créer ta branche      | `git checkout -b feature/x` |
| Installer dépendances | `npm install`               |
| Lancer projet         | `npm run dev`               |
| Lint du projet        | `npm run lint`              |
| Build final           | `npm run build`             |
| Commit                | `git commit -m "message"`   |
| Push                  | `git push origin feature/x` |
| Pull Request          | Via GitHub                  |

---

# 💬 Besoin d’aide ?

Tu peux poser toutes tes questions dans la section "Issues" du repo.

Bonne contribution et merci de faire avancer le projet 💙🚀
