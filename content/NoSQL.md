## Qu'est-ce que NoSQL ?

**NoSQL** signifie **"Not Only SQL"**.  
Ce sont **des bases de données alternatives** aux bases traditionnelles **relationnelles** (SQL), conçues pour **gérer de grandes quantités de données, très diverses et changeantes**.

> **Image simple** :  
> **SQL** est **une bibliothèque très ordonnée**, chaque livre à sa place précise.  
> **NoSQL** est **un grand entrepôt flexible**, où on peut stocker des livres, des photos, des vidéos, des objets… sans suivre des règles strictes.

---

## Pourquoi existe-t-il des bases NoSQL ?

- **Besoin de flexibilité** : tout n’est pas un tableau bien structuré (ex : réseaux sociaux, applications mobiles, IoT...).
    
- **Volume massif de données** : applications modernes doivent gérer **des millions** voire **des milliards d'éléments** (ex : Amazon, Facebook).
    
- **Vitesse et scalabilité** : NoSQL est conçu pour **grossir rapidement** sans casser la structure de base.
    

---

## Différence entre SQL et NoSQL

| Critère               | SQL (relationnel)                                                       | NoSQL (non relationnel)                                                                 |
| --------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| **Structure**         | Données organisées en tables (colonnes, lignes).                        | Données flexibles : documents, graphes, colonnes, clés-valeurs.                         |
| **Règles**            | Forte structure, schéma fixe (ex : toujours le même format).            | Schéma libre ou souple (chaque enregistrement peut être différent).                     |
| **Cohérence**         | Priorité à la cohérence forte (données toujours fiables immédiatement). | Souvent priorité à la rapidité et à la disponibilité (parfois avec cohérence retardée). |
| **Exemples d'usage**  | ERP, CRM, finance, applications métiers classiques.                     | Réseaux sociaux, e-commerce géant, applications mobiles, Big Data.                      |
| **Exemples d'outils** | MySQL, PostgreSQL, Oracle, SQL Server.                                  | MongoDB, Cassandra, Redis, Neo4j.                                                       |

## Pour résumer
- **SQL** : projet classique, structuré, besoin d'ordre et de rigueur.

- **NoSQL** : projet moderne, agile, besoin de stocker de grandes quantités de données diverses, évolutives.


- Si un client parle de CRM, ERP, reporting structuré → probablement **SQL**.  
- Si un client parle de Big Data, réseaux sociaux, objets connectés, scalabilité → probablement **NoSQL**.

SQL = Organisation stricte, stabilité.  
NoSQL = Flexibilité, rapidité, volume.

[[ELK]],