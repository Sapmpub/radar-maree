# Radar-Marée · horaires et coefficients de marée en France

Radar-Marée est un projet de génération de site web statique dédié aux marées françaises.  
Objectif : proposer, pour chaque code postal, commune, port et lieu dit du littoral, des **horaires de marée précis**, **horaires de marée local**, les **coefficients de marée**, les **hauteurs d’eau** et un texte de contexte local optimisé pour le référencement.

🔗 Site en production : [https://radar-maree.fr](https://radar-maree.fr)

---

## À propos de Radar-Marée

Radar-Marée est un atlas numérique des marées en France.  
Le projet couvre progressivement :

- les côtes de la **Manche**,
- la façade **Atlantique**,
- la **Méditerranée** et les zones estuariennes.

Pour chaque zone, Radar-Marée cherche à fournir :

- les **horaires de marée haute et marée basse**,
- les **coefficients de marée**,
- les **hauteurs d’eau**,
- une **description locale** (baie, estuaire, plage, port, embouchure, etc.),
- une page dédiée par **code postal**, **commune** ou **lieu précis** pour le SEO.

Le site vise une expérience simple : trouver rapidement la marée du jour ou des prochains jours pour un lieu donné, avec un contenu clair et adapté aux recherches type  
> “marée [ville]”, “heure marée [plage]”, “coefficient marée [port]”.

---

## Objectifs du projet

- Proposer une **alternative moderne** aux sites de marées existants.
- Offrir un **maillage très fin** du littoral français : CP, communes, ports, lieux dits.
- Générer des pages **SEO friendly** à grande échelle à partir d’un inventaire structuré.
- Rester **rapide** et **facilement hébergeable** (site statique, cache, CDN).

---

## Périmètre technique

Le projet repose principalement sur :

- **Python** pour :
  - la construction de l’inventaire du littoral (CP, communes, ports, lieux dits),
  - le traitement des données de marée,
  - la génération des descriptions locales (blocs de texte hydrodynamiques),
  - la génération des pages HTML finales à partir d’un CSV central.
- Des fichiers **CSV** pour décrire les lieux, les liens entre CP et communes, les ports, etc.
- Des **templates HTML** pour produire un site statique optimisé SEO :
  - balises `<title>` propres,
  - meta description,
  - balisage JSON-LD,
  - maillage interne entre pages voisines.

L’architecture cible est compatible avec un déploiement sur un hébergement statique classique ou via un CDN type **Cloudflare Pages**.

---

## Ce que contient ce dépôt

Ce dépôt GitHub sert de vitrine technique du projet Radar-Marée et peut contenir, selon les versions :

- des scripts Python de génération (inventaire, descriptions, HTML),
- des exemples de fichiers CSV d’inventaire du littoral,
- des extraits de templates HTML utilisés pour produire les pages finales.

Le cœur complet de la génération peut évoluer et n’est pas forcément entièrement public au départ.

---

## Cas d’usage

Radar-Marée s’adresse notamment à :

- toute personne qui cherche les **horaires de marée** pour une plage ou un port précis,
- les habitants du littoral qui veulent un site **simple et rapide** pour consulter les marées,
- les professionnels qui ont besoin d’un accès clair aux **coefficients** et **hauteurs d’eau**,
- les projets de sites ou d’applications qui souhaitent s’inspirer d’une approche **données + SEO** sur le thème des marées.

---

## Statut du projet

Radar-Marée est un projet en évolution continue :

- amélioration de la couverture géographique,
- enrichissement des textes locaux (hydrodynamique, configuration du lieu, type de côte),
- optimisation du SEO et des performances de génération.

---

## Contact

Pour toute question autour du projet Radar-Marée, des marées en France ou de l’architecture de génération statique, vous pouvez passer par le site :

👉 [https://radar-maree.fr](https://radar-maree.fr)
