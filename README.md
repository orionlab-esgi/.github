# Groupe Coucou (cours AIOps)

Bienvenue sur l’organisation GitHub du groupe Coucou pour le cours AIOps & observabilité.
Ce groupe travaille sur Orion, un laboratoire de pratiques autour :
- de l’observabilité (métriques, logs, traces),
- de l’exploitation de services,
- d’un assistant documentaire interne (RAG) pour les équipes `support`, `rh` et `dev`.

## Dépôt principal du groupe

Le dépôt de référence est :
➡️ https://github.com/orionlab-esgi/orion-lab-src3-coucou

## Ce que contient le projet Orion

Le projet couvre notamment :
- une stack locale Docker pour les labs ;
- un démarrage guidé avec `make` (`pull`, `check`, `up`, `down`, `maj`) ;
- des parcours de labs (`start-lab1a` à `start-lab4b`) ;
- des checkpoints avec jetons de validation ;
- un rendu final via tag Git `rendu-projet`.

## Pré-requis essentiels (résumé)

- machine avec ressources suffisantes (8 Go minimum, 16 Go recommandé selon le lab) ;
- `git`, `make`, `python3`, Docker + Compose v2 ;
- Ollama `0.40.9` pour les scénarios non `LOW_MEM=1`.

## Bonnes pratiques du groupe

- travailler via commits clairs et fréquents ;
- synchroniser régulièrement avec les mises à jour du cours (`make maj`) ;
- documenter les décisions et résultats dans le dépôt ;
- conserver les remises et preuves de checkpoints dans les emplacements attendus.

## Documentation détaillée

Pour l’installation complète, les commandes exactes, la configuration par OS et les modalités de rendu, consulter le README détaillé du dépôt principal :
➡️ https://github.com/orionlab-esgi/orion-lab-src3-coucou/blob/main/README.md
