
## Qu'est-ce qu'un problème supervisé ?

Un **problème supervisé** est une situation où **on connaît déjà la réponse attendue** et **on entraîne une machine à la retrouver**.

> **Image simple** :  
> C’est comme **entraîner un élève avec des exercices corrigés** : il apprend à associer une question à la bonne réponse.

**Exemples** :

- Prédire si un client va acheter ou non (réponse = Oui/Non).
    
- Estimer le prix d'une maison selon sa surface (réponse = montant en €).
    

**À retenir** :  
**On connaît la réponse** → **On apprend à la retrouver**.

Dans les données d'entrainement, nous avons la cible ou nous pouvons la construire. La cible est une variable que nous devons prédire. ex nous voulons prédire la consommation d'un batiment. À partir des caractéristiques du batiment (surface, etage etc), nous pouvons prédire sa consommation en kWh.

## Qu'est-ce qu'un problème non-supervisé ?

Un **problème non-supervisé** est une situation où **on n'a pas de réponse connue** et **on demande à la machine de trouver des structures cachées par elle-même**.

> **Image simple** :  
> C’est comme **laisser un explorateur découvrir seul les différents paysages sans carte**.

**Exemples** :

- Regrouper automatiquement des clients ayant des comportements similaires (segmentation).
    
- Détecter des comportements anormaux sans savoir à l’avance ce qu’est une anomalie.
    

**À retenir** :  
**Pas de réponse connue** → **On découvre des patterns cachés**.

## Pour résumer
| Critère            | Supervisé                              | Non-Supervisé                                          |
| ------------------ | -------------------------------------- | ------------------------------------------------------ |
| **Réponse connue** | Oui (labels, exemples).                | Non (exploration libre).                               |
| **Objectif**       | Prédire une valeur ou une catégorie.   | Regrouper, explorer, détecter des schémas.             |
| **Exemples**       | Prédire un achat, un risque, un prix.  | Segmenter des clients, détecter des fraudes inconnues. |
| **Image**          | L'élève qui apprend avec des corrigés. | L'explorateur sans carte.                              |
- **Supervisé** → projet où **le client veut prédire un résultat connu** (ex : score de risque, churn client, prix).
    
- **Non-supervisé** → projet où **le client veut explorer ou découvrir des regroupements ou anomalies** (ex : segmentation client, détection de fraudes).

Supervisé = apprendre avec la réponse.  
Non-supervisé = découvrir sans réponse.