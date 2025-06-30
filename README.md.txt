# 📘 Cockpit interactif Cessna 172

Bienvenue ! Ce petit projet HTML vous permet de cliquer sur les instruments du tableau de bord de votre C172 pour afficher leur nom et une brève description.

---

## 📂 Contenu du dossier :

- `cockpit_interactif.html` → Page principale à ouvrir dans un navigateur
- `style.css` → Feuille de style modifiable
- `tableau_bord.jpg` → ⚠️ votre propre photo du tableau de bord (nommée ainsi)
- `README.md` → Ce fichier d’instructions

---

## 🔧 Comment modifier les zones interactives

1. Ouvrez `cockpit_interactif.html` dans un éditeur (Notepad++, Visual Studio Code…)
2. Dans la section `<map name="cockpit">`, chaque élément ressemble à ceci :

```html
<area shape="circle" coords="140,220,50" alt="Anémomètre" title="Anémomètre" onclick="showInfo('Anémomètre', 'Indique la vitesse en nœuds via pression dynamique.')">
