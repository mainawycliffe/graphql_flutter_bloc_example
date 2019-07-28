# A Flutter GraphQL example using "graphql" with "flutter_bloc"

This example uses [`flutter_bloc`](https://pub.dev/packages/flutter_bloc) package for state management and [`graphql`](https://pub.dev/packages/graphql) package to connect to Githubs GraphQL API to fetch and star/unstar your repositories.

## About `graphql` flutter package

`graphql` package is the core of `graphql_flutter`, which manages caching, http and websocket clients, query management among others. This allows you to use it with any state management tool of your choice. In fact, `graphql_flutter` package also uses this package under the hood, but just exposes a number of Widgets such `GraphQLProvider`,`CacheProvider`, `Query`, `Mutation` etc for you to use.

I will add complete documentation for this example soon.

This repo, after completion shall be merged as one of the examples inside the `graphql_flutter`.
