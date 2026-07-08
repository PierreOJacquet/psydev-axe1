# Site Quarto – Axe 1 PsyDev

Ce dépôt contient une page web Quarto pour l’Axe 1 de l’équipe Psychiatrie du Développement et Trajectoires du CESP.

## Fichiers

- `_quarto.yml` : configuration du site Quarto.
- `index.qmd` : page principale.
- `files/formulaire_demande_financement_axe1.docx` : formulaire de demande de financement.

## Prévisualiser le site

Dans RStudio ou dans un terminal placé dans le dossier du projet :

```bash
quarto preview
```

## Générer le site

```bash
quarto render
```

Le site généré sera placé dans le dossier `docs/`, ce qui permet une publication simple via GitHub Pages.
