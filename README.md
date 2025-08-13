# Rick and Morty GraphQL Character Query

## How to Fetch Character Details

You can use the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql) to fetch details about characters by their ID.

### Sample GraphQL Query

```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
  character2: character(id: 2) {
    id
    name
    status
    species
    type
    gender
  }
  character3: character(id: 3) {
    id
    name
    status
    species
    type
    gender
  }
  character4: character(id: 4) {
    id
    name
    status
    species
    type
    gender
  }
}
```

### Example Output for Character ID 4

```json
{
  "data": {
    "character": {
      "id": "4",
      "name": "Beth Smith",
      "status": "Alive",
      "species": "Human",
      "type": "",
      "gender": "Female"
    }
  }
}
```

Replace the `id` in the query to fetch details for other characters.
