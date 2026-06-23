# Portfolio — Badreddine Zouaoui

Portfolio personnel monopage (HTML + CSS + JavaScript, sans dépendance), responsive, avec mode sombre/clair, animations au scroll et téléchargement du CV.

## 📁 Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | Le site complet (tout est dans ce seul fichier) |
| `cv-badreddine-zouaoui.pdf` | CV téléchargeable depuis le bouton **CV** |
| `README.md` | Ce fichier |

> ⚠️ Le bouton de téléchargement pointe vers `cv-badreddine-zouaoui.pdf`. Garde donc **les deux fichiers dans le même dossier** lors de la mise en ligne.

## 🚀 Publier sur GitHub Pages

1. Crée un dépôt GitHub (par ex. `portfolio` ou, mieux, `ton-pseudo.github.io` pour avoir l'URL la plus propre).
2. Pousse `index.html`, `cv-badreddine-zouaoui.pdf` et `README.md` à la racine du dépôt :
   ```bash
   git init
   git add .
   git commit -m "Portfolio Badreddine Zouaoui"
   git branch -M main
   git remote add origin https://github.com/TON-PSEUDO/portfolio.git
   git push -u origin main
   ```
3. Sur GitHub : **Settings → Pages → Build and deployment → Source : Deploy from a branch**, choisis la branche `main` et le dossier `/ (root)`, puis **Save**.
4. Patiente ~1 min : le site est en ligne sur `https://TON-PSEUDO.github.io/portfolio/`.

## ✏️ À personnaliser avant publication

- Dans `index.html`, remplace **`ton-pseudo`** par ton vrai identifiant GitHub (2 occurrences, le lien de l'icône GitHub). Recherche `ton-pseudo` dans le fichier.
- (Optionnel) Ajuste les couleurs via les variables CSS en haut du `<style>` (`--accent`, `--bg`, etc.).

## 🛠️ Aperçu en local

Ouvre simplement `index.html` dans ton navigateur, ou lance un petit serveur :
```bash
python3 -m http.server 8000
# puis ouvre http://localhost:8000
```
