# Episode queries

This directory contains files and resources related to querying episode data from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).

## Sample GraphQL Query to Fetch Episodes

To fetch episode details, you can use the following query:

```graphql
query {
  episodes(page: 1) {
    results {
      id
      name
      air_date
      episode
    }
  }
}
```

You can change the `page` parameter to fetch more episodes.

## Fields

- `id`: Episode ID
- `name`: Episode name
- `air_date`: Air date of the episode
- `episode`: Episode code (e.g., S01E01)

## Usage

Save your queries in `.graphql` files in this directory and use them with the Rick and Morty GraphQL endpoint.
