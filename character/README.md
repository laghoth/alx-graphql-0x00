# Task 0 — Get Specific Characters by ID

**Endpoint used:** `https://rickandmortyapi.com/graphql`

## Queries & Outputs

| File                       | Description                           |
| -------------------------- | ------------------------------------- |
| character-id-1.graphql     | Query for character with `id: 1`      |
| character-id-1-output.json | Result for character 1 (Rick Sanchez) |
| character-id-2.graphql     | Query for character with `id: 2`      |
| character-id-2-output.json | Result for character 2 (Morty Smith)  |
| character-id-3.graphql     | Query for character with `id: 3`      |
| character-id-3-output.json | Result for character 3 (Summer Smith) |
| character-id-4.graphql     | Query for character with `id: 4`      |
| character-id-4-output.json | Result for character 4 (Beth Smith)   |

## Usage

Execute each query in GraphQL playground

# Task 1 — Get List of Characters by Page

**Objective:**  
Write GraphQL queries to retrieve a paginated list of all characters using the `characters(page: Int)` field.

**GraphQL Endpoint Used:**  
[https://rickandmortyapi.com/graphql](https://rickandmortyapi.com/graphql)

---

## 📘 Description

In this task, we wrote 4 GraphQL queries to fetch a list of characters from page 1 to page 4.  
Each query selects the following fields:

- `id`
- `name`
- `status`
- `image`

The result of each query is stored in its corresponding `.json` output file.

---

## 🗂️ Files Structure

| File Name                     | Description                             |
| ----------------------------- | --------------------------------------- |
| characters-page-1.graphql     | GraphQL query for characters on page 1  |
| characters-page-1-output.json | Output result of characters from page 1 |
| characters-page-2.graphql     | GraphQL query for characters on page 2  |
| characters-page-2-output.json | Output result of characters from page 2 |
| characters-page-3.graphql     | GraphQL query for characters on page 3  |
| characters-page-3-output.json | Output result of characters from page 3 |
| characters-page-4.graphql     | GraphQL query for characters on page 4  |
| characters-page-4-output.json | Output result of characters from page 4 |

---

## ✅ Sample Query Format

```graphql
query {
  characters(page: X) {
    results {
      id
      name
      status
      image
    }
  }
}
```
