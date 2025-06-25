# Task 2 — Get Specific Episode by ID

**Objective:**  
Write a GraphQL query to retrieve the details of a specific episode using its ID.

**GraphQL Endpoint Used:**  
[https://rickandmortyapi.com/graphql](https://rickandmortyapi.com/graphql)

---

## 📘 Description

In this task, we wrote a GraphQL query to fetch data about a specific episode using the `episode(id: ID!)` field.

We included the following fields in the query:

- `id`
- `name`
- `air_date`
- `episode`

The result was stored in a corresponding `.json` file.

---

## 🗂️ Files Structure

| File Name                  | Description                             |
| -------------------------- | --------------------------------------- |
| episode-page-1.graphql     | Query to get the episode with ID = 1    |
| episode-page-1-output.json | Output for episode ID 1 (Pilot episode) |

---

## ✅ Sample Query Format

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
```
