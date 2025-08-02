# 🎧 Discord Voice Manager Bot

Un bot Discord intelligent qui gère dynamiquement les salons vocaux : création automatique, options de contrôle (ouverture, fermeture, whitelist, blacklist...) via boutons, et logs des actions. Idéal pour les serveurs communautaires.

---

## ⚙️ Fonctions principales

- 🏗️ Création auto de salons vocaux personnalisés
- 🔘 Panel de gestion avec boutons :
  - 🔓 Ouvrir à tous
  - 🔒 Fermer (whitelist seulement)
  - 🔐 Privé (whitelist/staff uniquement)
  - ➕ Ajouter à la whitelist
  - ➖ Retirer de la whitelist
  - ⛔ Ajouter à la blacklist
  - 🚫 Retirer de la blacklist
  - 🚪 Purger les membres non-whitelist
- ❌ Auto-suppression des salons vides
- 🧾 Système de logs personnalisable
- 📁 Données persistantes dans `vocal_data.json`

---

## 🛠️ Installation

### 🔗 Dépendances

<pre>pip install discord.py aiofiles<pre>
