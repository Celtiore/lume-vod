# LumeVOD

**Films à la demande (Xtream) pour Android TV** — simple, rapide, pensé pour la télécommande.
Compagnon de [LumeTV](https://github.com/Celtiore/lume-tv) (le direct) : même compte Xtream,
même clé de signature, deux apps côte à côte sur le launcher.

> ⚠️ **LumeVOD ne contient aucun film ni aucun contenu.** C'est uniquement un lecteur :
> tu dois renseigner ta propre source Xtream (à laquelle tu as légalement accès).

---

## 📥 Téléchargement

➡️ **[Dernière version (Releases)](../../releases/latest)** — télécharge le fichier `LumeVOD-x.y.z.apk`.

Version actuelle : **1.0.4**.

## ✨ Fonctionnalités (v1.0.1)

- 🔑 **Connexion Xtream** (saisie guidée au premier lancement — import depuis LumeTV à venir)
- 🗂️ **Catalogue à deux colonnes** : catégories à gauche, affiches de la catégorie à droite,
  recherche dans les catégories et dans les films affichés
- 🎬 **Fiche film** : synopsis, durée, note, genre, réalisation, casting
- ▶️ **Lecture plein écran** à la télécommande (OK = pause, ±10 s, ±60 s)
- 🔌 **Connexion unique respectée** : passer en arrière-plan coupe le flux, LumeTV peut
  reprendre le direct (et inversement)
- 🔄 **Mises à jour intégrées** (depuis les Releases GitHub)
- Import des identifiants depuis LumeTV en un OK (1.0.3), comptes multiples et Réglages (Comptes, À propos, vérification manuelle des mises à jour).
- ⏯️ **Reprise de lecture** (1.0.4) : « Reprendre à … » et « Lire depuis le début » sur la fiche, badge « Vu », reprise après Home ou redémarrage, catégorie « ▶ En cours », « Effacer l'historique de lecture » dans Réglages › Lecture.
- 🚪 **Confirmation de sortie** (1.0.4) : Retour depuis le catalogue demande « Quitter LumeVOD ? ».

## 🗺️ Prochainement

- Affiches et synopsis enrichis (TMDB)
- Les séries ont leur app : [**LumeSeries**](https://github.com/Celtiore/lume-series)

## 🔧 Installation

1. Sur la box : autoriser l'installation d'applications inconnues pour ton navigateur ou
   ton gestionnaire de fichiers.
2. Télécharger `LumeVOD-x.y.z.apk` depuis les Releases et l'ouvrir.
3. Au premier lancement : host, utilisateur, mot de passe Xtream (Entrée passe au champ
   suivant).

Les mises à jour suivantes sont proposées **dans l'app** au démarrage.

## 🔐 Vie privée

Aucune télémétrie. Les identifiants Xtream sont stockés chiffrés sur l'appareil, exclus des
sauvegardes cloud. Le code source vit dans le dépôt `Iptv` (monorepo LumeTV / LumeVOD).
