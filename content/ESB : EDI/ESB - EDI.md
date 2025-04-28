## Qu'est-ce qu'un ESB (Enterprise Service Bus) ?

Un **ESB** est une **plateforme d'échange interne** qui **connecte toutes les applications** d'une entreprise entre elles.

> **Image simple** : imaginez une **gare centrale** où chaque application est un train.  
> L'**ESB** organise les circulations : il reçoit les informations d'une application, les transforme si besoin, et les achemine proprement à une autre application.

**Objectif** :

- **Faire communiquer** les applications internes (CRM, ERP, RH, etc.) **de manière fluide**.
    
- **Standardiser** les échanges (format, sécurité, traçabilité).
    
- **Simplifier** l'architecture du système d'information.
    

---

## Qu'est-ce que l'EDI (Échange de Données Informatisé) ?

L'**EDI** est **un système d'échange automatisé de documents** **entre plusieurs entreprises**.

> **Image simple** : c'est **un service postal ultra-rapide et sécurisé** qui permet d’envoyer automatiquement des factures, des bons de commande, des contrats, etc., sans intervention humaine.

**Objectif** :

- **Échanger des documents standardisés** (commandes, factures, avis d’expédition) **entre partenaires commerciaux**.
    
- **Gagner du temps** et **réduire les erreurs** par rapport à un traitement manuel.
    
- **Renforcer la traçabilité** des transactions inter-entreprises.
    

---

## Différences entre ESB et EDI

| Critère            | ESB                                                         | EDI                                                                    |
| ------------------ | ----------------------------------------------------------- | ---------------------------------------------------------------------- |
| **Objectif**       | Connecter les applications internes d'une même entreprise.  | Échanger automatiquement des documents entre entreprises différentes.  |
| **Périmètre**      | Interne à l'entreprise (CRM, ERP, RH, etc.).                | Externe, entre partenaires commerciaux (clients, fournisseurs).        |
| **Type d'échange** | Événements, services, flux d'informations complexes.        | Documents commerciaux normalisés (commandes, factures, etc.).          |
| **Technologie**    | Architecture orientée services (SOA), messages instantanés. | Standards EDI (EDIFACT, ANSI X12), souvent sur protocoles spécifiques. |
| **Exemples**       | Une commande client entre CRM et ERP internes.              | Une commande client envoyée automatiquement au fournisseur.            |
- **ESB** = **connecter l’intérieur** de l'entreprise.
    
- **EDI** = **connecter l’entreprise avec ses partenaires extérieurs**.

- ESB = Gare intérieure pour les applications.  
- EDI = Autoroute rapide pour échanger des documents entre entreprises.

- Un projet **ESB** est souvent lié à une **modernisation du système d'information interne**.  
- Un projet **EDI** est souvent lié à **l'optimisation des échanges commerciaux**.
### Quelque outils
| Outil           | Type                                                                                        | Particularité                                                                                                                      | Typologie de client cible                                                                                    |
| --------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **Talend ESB**  | ESB (Enterprise Service Bus)                                                                | Solution  robuste pour l'intégration d'applications et de services. Fortement orienté Data et Cloud.                               | Grandes entreprises, ETI en transformation numérique, clients cherchant flexibilité et coûts maîtrisés.      |
| **Blueway ESB** | ESB français + EAI (Enterprise Application Integration) + BPM (Business Process Management) | Plateforme souveraine, forte intégration entre flux de données, processus métiers et gouvernance. Solution "tout-en-un" française. | Secteur public, collectivités, industries réglementées, entreprises sensibles à la souveraineté des données. |


[[Blueway]],[[TALEND]],