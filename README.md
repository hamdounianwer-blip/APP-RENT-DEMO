# 🚗 CityRent — Démo publique

Démonstration du système de gestion de location de voitures **CityRent**.

> ⚠️ Ceci est une **version démo** : toutes les données (véhicules, clients,
> contrats, paiements...) sont **100% fictives**. Il n'y a **aucun serveur** —
> tout fonctionne directement dans ton navigateur, et tout ce que tu modifies
> est sauvegardé **uniquement en local, dans ce navigateur** (localStorage).
> Rien n'est envoyé ni partagé nulle part.

## 🔑 Connexion

- **Utilisateur :** `demo`
- **Mot de passe :** `0000`

Le même mot de passe (`0000`) sert aussi à débloquer les champs verrouillés
et confirmer les suppressions dans l'appli (unlock KM, unlock prix, supprimer
un véhicule/contrat/paiement, etc.).

## 🗑️ Réinitialiser les données

Un bouton **"🗑️ Réinitialiser démo"** est visible en bas à droite de l'écran.
Il efface toutes les données stockées dans ce navigateur et recharge des
données de démonstration fraîches. Tu peux aussi le faire manuellement via
la console du navigateur :

```js
localStorage.clear(); location.reload();
```

## 🧩 Ce qui fonctionne dans la démo

- Dashboard, Flotte, Locations (Daily Rentals), Paiements, Clients
- Service & KM, Mouvements internes, GPS Tracking (liens factices)
- Statistiques de revenus, Activity Log, gestion des violations (مخالفات)
- Verrouillage/déverrouillage de champs par mot de passe (`0000`)

## ⚠️ Ce qui ne fonctionne pas dans cette version statique

Ces fonctionnalités nécessitent normalement un serveur (stockage de fichiers) :
- Upload de scans clients (pièce d'identité / permis)
- Upload de reçus PDF pour les paiements
- Upload de modèles Word pour les violations
- Vidéos de contrat

Elles échouent silencieusement avec un message d'erreur — le reste de
l'application n'est pas affecté.

## 🏗️ Architecture

Application 100% statique (HTML/CSS/JS), aucune dépendance serveur,
stockage exclusivement via `localStorage` du navigateur.
