# 🎉 Jura Events

Application web statique d'inscription à des événements — hébergée gratuitement sur GitHub Pages.

## ✨ Fonctionnalités

- **Créer des événements** avec titre, description, lieu et plusieurs dates
- **S'inscrire** (prénom, nom, email optionnel, choix de date(s))
- **Voir les inscrits** par date avec barre de progression si max défini
- **Export calendrier** — Google Calendar + fichier .ics (iPhone/Outlook)
- **Mode admin** protégé par mot de passe pour gérer les événements

## 🔑 Mot de passe admin par défaut

```
jura2026
```

> Modifiable dans `index.html` à la ligne `const ADMIN_PW = 'jura2026';`

## 🚀 Utilisation

1. Ouvrir **https://jura39bot.github.io/jura-events/**
2. Cliquer sur **⚙️ Admin** → entrer le mot de passe
3. Créer un événement avec **+ Nouvel événement**
4. Partager le lien aux participants
5. Les gens cliquent **✋ S'inscrire** et choisissent leur(s) date(s)

## 💾 Stockage

Les données sont stockées dans `localStorage` du navigateur — simple et sans serveur.
> ⚠️ Les données ne sont **pas partagées** entre navigateurs. Pour un usage collectif, une évolution vers Supabase ou Firebase est recommandée.

## 📅 Export calendrier

Chaque date propose :
- **Google Calendar** — ouvre directement dans Google Cal
- **.ics** — fichier téléchargeable pour iPhone/Outlook/Thunderbird
