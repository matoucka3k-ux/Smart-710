# Smart 710 🎓

Site de messagerie anonyme pour la classe 710.  
Fait par **Mathis Bobo** — Meilleur délégué 🏆

## Fonctionnalités

- 🏠 **Landing page** style SaaS
- 👤 **Inscription / Connexion** pour les élèves
- 🎭 **Anonymat** — chaque message peut être envoyé anonymement ou avec son nom
- 📬 **Dashboard élève** — écrire et voir ses messages envoyés
- 🔐 **Panel admin** (Mathis) — voir tous les messages, filtrer, supprimer, voir les élèves inscrits

## Connexion Admin

| Email | Mot de passe |
|-------|-------------|
| `admin@smart710.fr` | `mathis710` |

## Déploiement sur GitHub Pages

1. Crée un repo GitHub (ex: `smart710`)
2. Upload le fichier `index.html`
3. Va dans **Settings → Pages → Deploy from branch → main**
4. Ton site sera en ligne à : `https://TON_PSEUDO.github.io/smart710`

## Données

Les données (comptes + messages) sont stockées dans le `localStorage` du navigateur.  
➡️ Chaque élève voit les données **de son propre navigateur uniquement**.  
➡️ Le panel admin stocke les messages envoyés localement.

> Pour une vraie base de données partagée, il faudrait un backend (ex: Supabase, Firebase).

## Stack

- HTML / CSS / JavaScript vanilla
- Aucune dépendance externe
- Un seul fichier `index.html`
