# Calmora — Prototype 3D interactif

**FR** · [English below](#english)

Prototype interactif d'une montre connectée de bien-être (détection du stress, de la fatigue et de la sédentarité) avec son application mobile. Tout tourne dans un seul fichier HTML, sans installation ni serveur.

**Démo en ligne :** `https://<votre-utilisateur>.github.io/<nom-du-depot>/`

## Contenu

- Modèle 3D de la montre (faces, dos, vue éclatée) avec écran tactile simulé
- Simulation de 6 scénarios : stress aigu, effort physique, pic soudain, tension légère, fatigue, sédentarité
- Détection expliquée : seuil, durée de confirmation, filtre de mouvement, personnalisation sur plusieurs jours
- Application mobile simulée : respiration, relaxation, mini-jeux, assistant IA, psychologue partenaire, récompenses
- Interface en français, anglais et arabe (RTL)
- Export CSV de la séance

> Toutes les données sont **simulées**. Ce prototype n'est pas un dispositif médical.

## Lancer en local

Ouvrez simplement `index.html` dans un navigateur récent (connexion internet requise pour charger three.js depuis un CDN).

## Publier avec GitHub Pages

1. Poussez ce dossier sur un dépôt GitHub.
2. Dans le dépôt : **Settings → Pages**.
3. Source : **Deploy from a branch**, branche `main`, dossier `/ (root)`.
4. Après une minute, le site est disponible à l'adresse de démo ci-dessus.

## Assistant IA

L'assistant fonctionne en local avec des réponses simulées. Pour brancher un vrai modèle, renseignez `AI_ENDPOINT` dans `index.html` (POST JSON `{messages, lang, context}` → `{reply}`).

## Licence

MIT, voir [LICENSE](LICENSE).

---

## English

Interactive prototype of a wellbeing smartwatch (stress, fatigue and inactivity detection) with its companion mobile app. Everything runs from a single HTML file, with no install and no server.

**Live demo:** `https://<your-username>.github.io/<repo-name>/`

### Features

- 3D watch model (front, back, exploded view) with a simulated touchscreen
- 6 simulated scenarios: acute stress, physical effort, sudden spike, mild tension, fatigue, sedentary
- Explained detection: threshold, confirmation time, motion filter, multi-day personalization
- Simulated mobile app: breathing, relaxation, mini-games, AI assistant, partner psychologist, rewards
- French, English and Arabic (RTL) interface
- CSV export of the session

> All data is **simulated**. This prototype is not a medical device.

### Run locally

Open `index.html` in a modern browser (internet access needed to load three.js from a CDN).

### Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repo: **Settings → Pages**.
3. Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. After about a minute, the site is live at the demo address above.

### License

MIT, see [LICENSE](LICENSE).
