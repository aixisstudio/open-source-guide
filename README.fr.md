# Open Source Guide

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

Ta première contribution open source, pas à pas

Votre première contribution open-source, étape par étape

1. Trouver un projet convivial pour les débutants

- https://goodfirstissue.dev — `good first issue` curés pour tous les projets
- Recherche de sujet GitHub: [`good-first-issue`](https://github.com/topics/good-first-issue)
- Docs & traductions sont les points d'entrée les plus faciles — chaque projet les veut

2. Comprendre le flux de travail

```
fork → clone → branch → edit → commit → push → pull request → review → merge
```

- **Fork** = votre propre copie côté serveur
- **Branche** = ne fonctionne pas sur `main`, jamais
- **PR** = votre proposition + la discussion autour

3. Les PR qui sont acceptées

- Lisez d'abord le `CONTRIBUTING.md` — toujours
- Un changement par PR — petits battements
- Expliquer **pourquoi**, pas seulement quoi — les responsables fusionnent le contexte, pas le code
- Soyez réceptif à l'examen — un PR que vous abandonnez meurt

4. Pratiquez en toute sécurité d'abord

Chauffer sur des bacs à sable spécialement conçus (pas de jugement, les robots fusionnent instantanément):

- [première demande] (https://github.com/aixisstudio/first-pull-request) — votre première communication
- [ajouter votre nom] (https://github.com/aixisstudio/add-your-name) - rejoindre le mur des contributeurs

Niveau 5.

- Numéros → reproductions → correctifs : l'échelle de confiance
- Discussions sur les réponses — les responsables se souviennent des aides
- Les battements de cohérence éclatent : un petit PR/semaine construit un profil réel

Comment lire une base de code inconnue

1. `README.md` + `CONTRIBUTING.md` — l'intention
2. `git log --oneline -50` — Ce qui change activement
3. Tests — ils documentent mieux le comportement que les docs
4. Trouvez le point d'entrée, suivez une demande de bout en bout
5. `rg "TODO|FIXME|HACK"` — où les responsables savent que ça fait mal

Votre premier PR — l'étiquette

- **Small is respected**: typo fix > semi-broken feature
- **Lire les 10 derniers PR fusionnés** : ils enseignent le style de révision du projet
- **Ne demandez pas "pourrais-je travailler là-dessus"**: il suffit d'ouvrir le PR ou de commenter une fois, brièvement
- **Sorties conventionnelles**: `feat:`, `fix:`, `docs:` — vérifier le journal d'abord
- **CI rouge = inmergable** : effectuer les vérifications localement d'abord

Programmes à connaître

Programme pour Prix
|---|---|---|
Hacktoberfest: tout le monde: récompenses numériques:
Google Été du Code des étudiants
MLH Bourse d'études d'étudiants distants
Un stage de 7 000 $ sous-représenté
Fonds souverain de technologie

License décision rapide

Vous voulez
|---|---|
"Utilisez-le"
Crédit + protection par brevet
Part-aimable
Docs/contenu
Domaine public

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
