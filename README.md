# 🦉 NightOwl — Enregistreur de Sommeil

Une PWA simple qui enregistre automatiquement les bruits que tu fais pendant ton sommeil.

## Comment ça marche

1. **Ouvre l'app** dans ton navigateur (Chrome recommandé)
2. **Règle la sensibilité** avec le slider — le marqueur vert sur la barre indique le seuil
3. **Appuie sur Play** et pose ton téléphone à côté de toi (branché sur secteur)
4. **Dors** — l'app n'enregistre que quand un bruit dépasse le seuil
5. **Le matin**, réécoute tes clips et télécharge les plus drôles

## Fonctionnalités

- 🎙️ Détection de bruit par seuil d'amplitude (pas d'enregistrement continu)
- 📊 Indicateur de niveau sonore en temps réel
- 🎚️ Sensibilité réglable
- ⏱️ Chaque clip est horodaté avec sa durée
- 💾 Téléchargement individuel ou groupé des clips
- 🔒 Wake Lock pour garder l'écran actif toute la nuit
- 📱 PWA installable sur l'écran d'accueil

## Limitations

- L'onglet doit rester ouvert toute la nuit (ne pas fermer le navigateur)
- Les clips sont en mémoire dans la session (pas de persistance entre les nuits)
- Format audio : WebM/Opus (compatible avec la plupart des lecteurs)

## Déploiement GitHub Pages

1. Crée un repo sur GitHub
2. Push ces fichiers
3. Va dans Settings > Pages > Source: `main` branch
4. L'app sera dispo sur `https://ton-pseudo.github.io/nightowl/`

## Tech

HTML/CSS/JS vanilla — zéro dépendance. Utilise les APIs Web Audio et MediaRecorder.

## Licence

MIT
