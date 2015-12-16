---
layout: post
title: Affiche du Club-Méta
source: club-meta
files: [meta.md, meta08122015.tex, pandoc.tex]
---

Cette affiche, qui n'est autre qu'une slide Beamer, n'a pas été facile à obtenir. Je voulais conserver un code Markdown simple `meta.md` et faire une mise en abyme tout en passant de portrait à paysage.

C'est pourquoi il y a deux fichiers LaTeX :

- `pandoc.tex` permet d'afficher le code au-dessus de l'affiche, en 2 pages paysage par feuille via `pgfpages` ;
- `meta08122015.tex` permet d'obtenir l'affiche en Arial Black à partir du fragment de slide Beamer généré par pandoc 1.16.

… En fait, les `{height=130%}`, ce n'est généré en pandoc que [depuis le 19 novembre 2015](https://github.com/jgm/pandoc/issues/261), dans la version 1.16. C'est donc plutôt récent (ça faisait 4 ans que cette poule équestre attendait d'être fermée).
