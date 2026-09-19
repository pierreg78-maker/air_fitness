# Air Fitness

**Souffle et Bien-être**

Application web de respiration consciente. Gratuite, sans compte, 100 % privée.

Respire mieux, quelques minutes à la fois. Le souffle d’abord — le corps et l’alimentation viendront ensuite.

- Présentation : [index.html](https://pierreg78-maker.github.io/air_fitness/)
- Application : [app.html](https://pierreg78-maker.github.io/air_fitness/app.html)
- Mentions légales : [mentions-legales.html](https://pierreg78-maker.github.io/air_fitness/mentions-legales.html)
- Code : [github.com/pierreg78-maker/air_fitness](https://github.com/pierreg78-maker/air_fitness)

---

## À quoi ça sert

Tu respires environ 20 000 fois par jour sans y penser. En guidant ce souffle, tu parles directement au système nerveux : calmer un pic de stress, préparer le sommeil, retrouver un peu de clarté, ou simplement revenir dans le corps.

Air Fitness propose des exercices variés, filtrables par besoin du moment (`#Sommeil`, `#Stress`, `#Craving`, `#Débutant`…) et par intention (Calme, Énergie, Focus, plus une intention selon l’heure).

Ce n’est pas un cabinet, ni un dispositif médical. C’est un outil pratique, à utiliser dès que tu as deux minutes.

---

## Ce que fait l’app aujourd’hui

- Catalogue d’exercices de respiration (consignes, bienfaits, tags)
- Filtres par hashtags et intentions
- Guidage phase par phase (inspire / pause / expire)
- Métronome réglable (bpm), sonorités et vibrations
- Journal de sessions et suivi de série, stockés **sur l’appareil uniquement**
- Installation sur l’écran d’accueil (PWA), hors store
- Aucun compte, aucune pub, rien n’est envoyé à un serveur d’Air Fitness

---

## Utilisation

1. Ouvre la [présentation](https://pierreg78-maker.github.io/air_fitness/) ou directement l’[application](https://pierreg78-maker.github.io/air_fitness/app.html).
2. Choisis un exercice selon ce dont tu as besoin maintenant.
3. Règle le tempo si tu veux, puis lance le guidage.
4. Pour l’avoir sous la main : Safari (iPhone) → Partager → Sur l’écran d’accueil ; Chrome (Android / ordinateur) → Installer l’application.

Fonctionne dans un navigateur moderne. Une connexion sert à charger la page ; ensuite le souffle n’a besoin de personne.

---

## Technique

Prototype web statique, prêt PWA :

| Fichier | Rôle |
|---|---|
| `index.html` | Page d’accueil / présentation |
| `app.html` | Application |
| `app.js`, `app-1.js` … `app-5.js` | Logique de l’app |
| `app.css` | Styles |
| `exercises.json` (+ `exercises-a.json`, `exercises-b.json`) | Catalogue |
| `site.webmanifest` + favicons | Icônes et installation |
| `mentions-legales.html` | Mentions légales et confidentialité |

Hébergement : GitHub Pages, dépôt `pierreg78-maker/air_fitness`, branche `main`.

---

## Vie privée, en une phrase

Air Fitness ne crée pas de compte et n’envoie pas ton journal quelque part. Les réglages et l’historique restent dans le navigateur (stockage local). L’hébergeur (GitHub Pages) peut journaliser des données techniques de visite, hors de notre contrôle — détails dans les [mentions légales](mentions-legales.html).

---

## Santé

Les exercices de respiration présentés ici s’adressent à un public général, en bonne santé. Ils ne remplacent pas un avis médical.

En cas de trouble respiratoire, cardiaque, psychologique, de grossesse à risque, ou de doute : demande l’avis d’un professionnel de santé avant de pratiquer, surtout les exercices soutenus ou de rétention.

Arrête si tu ressens un malaise, des vertiges ou une douleur.

---

## Contribution & licence

Projet personnel, mené à titre non professionnel. Licence [MIT](LICENSE) — Copyright (c) 2026 pierre.

Les textes, la structure des exercices et l’identité visuelle Air Fitness restent attachés à ce projet. Tu peux t’en inspirer ; merci de ne pas republier l’app telle quelle sous un autre nom.

---

*Le souffle est déjà là. L’app sert juste à s’en souvenir.*
