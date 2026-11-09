# GroupOps

Existing GroupOps offline-first single-browser application migrated from the saved HTML app. Import your GroupOps JSON export using the app's Import button. Group data stays in localStorage on each device. GitHub Pages does not provide multi-user login, shared database, or automatic social posting. Keep your original exports private.

## Live website

https://xbren56.github.io/GroupOps/

## Publishing

GitHub Settings → Pages → Deploy from branch → main → / (root).

## Data safety

Data is stored in the current browser, not synced across devices. Export backups regularly. Do not commit private exports or sensitive organization records to this public repository. Offline caching is installed after an initial successful online visit.

## Future Wix migration

The project uses plain HTML, CSS and JavaScript to keep migration straightforward. Cloud accounts and shared data would require a backend and an appropriate access-control plan.
