# Un savoir par jour

Une web app de culture générale : chaque jour, un nouveau savoir en trois niveaux de lecture
(L'essentiel 1 min, Le détail 3 min, L'analyse 5 min), avec ses sources.

- `index.html` : l'application (HTML, CSS et JavaScript, sans framework)
- `savoirs.json` : les savoirs, ajoutés chaque matin par une tâche planifiée Claude
- `manifest.webmanifest`, `sw.js`, `icons/` : ce qui en fait une app installable (PWA), lisible hors ligne
- `fonts/` : police OpenDyslexic (licence SIL OFL, voir `fonts/OFL.txt`) pour le mode lecture dys

Installation sur iPhone : ouvrir le site dans Safari, Partager, puis « Sur l'écran d'accueil ».
