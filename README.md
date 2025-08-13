
<img width="582" height="313" alt="image" src="https://github.com/user-attachments/assets/b58dc9b3-eeb1-4b63-a99b-2398edaf65ba" />


# Rick and Morty GraphQL Character Query

## How to Fetch Character Details

You can use the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql) to fetch details about characters by their ID.

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
