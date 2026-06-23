# 🍎 PomPom

Une application de liste de course minimaliste pour iPhone, au design tout en pomme.

PomPom est une web-app installable sur l'écran d'accueil qui fonctionne **hors-ligne** et garde ta liste en mémoire sur ton téléphone. Pas de compte, pas de pub, pas de connexion requise — juste ta liste, et une pomme qui sourit.

## ✨ Fonctionnalités

- **Ajouter un article** en un geste depuis la barre du bas
- **Cocher** les articles attrapés en magasin (ils descendent automatiquement en bas de liste)
- **Supprimer** un article d'un appui
- **Vider** d'un coup tous les articles cochés
- **Hors-ligne** : tout est stocké localement sur ton iPhone
- **Installable** comme une vraie app, en plein écran, sans barre Safari

## 📱 Installation sur iPhone

1. Ouvre l'application dans **Safari** : [roro-lab33.github.io/PomPom](https://roro-lab33.github.io/PomPom/)
2. Appuie sur le bouton **Partager** (le carré avec la flèche)
3. Choisis **« Sur l'écran d'accueil »**
4. Valide — l'icône pomme apparaît sur ton écran d'accueil

## 🛠️ Technique

Construite en HTML, CSS et JavaScript purs, sans aucune dépendance externe ni bibliothèque à télécharger. Tout tient dans un seul fichier, ce qui rend l'app rapide à charger et fiable hors-ligne.

- Données sauvegardées via le stockage local du navigateur (`localStorage`)
- Hébergée gratuitement sur **GitHub Pages**
- Conçue comme une **PWA** (Progressive Web App) pour l'installation sur écran d'accueil

## 📂 Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | L'application complète (structure, style et logique) |
| `apple-touch-icon.png` | L'icône pomme affichée sur l'écran d'accueil |

## 🔄 Modifier l'application

Pour faire évoluer PomPom, il suffit de modifier `index.html` sur GitHub. L'adresse en ligne se met à jour automatiquement après une à deux minutes. Ta liste de course, elle, reste sur ton téléphone et n'est pas effacée par les mises à jour.

---

*Premier projet — fait avec 🍎.*
