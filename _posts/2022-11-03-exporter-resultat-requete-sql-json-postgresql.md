---
layout: post
title: Exporter le résultat d’une requête SQL en JSON avec PostgreSQL
description: Comment, en utilisant que PostgreSQL, exporter le résultat d’une requête SQL en JSON.
category: notes
seo:
  date_modified: 2022-11-15
---

Avant que je n’oublie à nouveau, voici comment exporter le résultat d’une requête SQL en JSON avec PostgreSQL.

Supposons qu’on ait la table suivante :

```sql
SELECT * FROM user;

--  id | first_name | last_name | age
-- ----+-------------+-----------------
--   1 | Alice      | Hamilton  | 101
--   2 | Bob        | Bemer     |  84
-- (2 rows)

```

Il suffit alors d’utiliser [les fonctions](https://www.postgresql.org/docs/current/functions-json.html) `row_to_json`
pour convertir chaque ligne en un document JSON et `json_agg` pour convertir le tout en un tableau de documents JSON :

```sql
COPY (
    SELECT json_agg(row_to_json(user))
    FROM (
        SELECT id, first_name as firstname, last_name as lastname
        FROM user
        ORDER BY age ASC
    ) AS user
) TO '/tmp/users.json';
```

Et alors :

```shell
cat '/tmp/users.json'
[{"id":2,"firstname":"Bob","lastname":"Bemer"},{"id":1,"firstname":"Alice","lastname":"Hamilton"}]
```

Voilà !

<!-- prettier-ignore-start -->
*[JSON]: JavaScript Object Notation
*[SQL]: Structured Query Language
<!-- prettier-ignore-end -->
