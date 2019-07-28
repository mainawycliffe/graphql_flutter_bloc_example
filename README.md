# A Flutter GraphQL example using "graphql" with "flutter_bloc"

This example uses [`flutter_bloc`](https://pub.dev/packages/flutter_bloc) package for state management and [`graphql`](https://pub.dev/packages/graphql) package to connect to Githubs GraphQL API to fetch and star/unstar your repositories.

## About `graphql` flutter package

`graphql` package is the core of `graphql_flutter`, which manages caching, http and websocket clients, query management among others. This allows you to use it with any state management tool of your choice. In fact, `graphql_flutter` package also uses this package under the hood, but just exposes a number of Widgets such `GraphQLProvider`,`CacheProvider`, `Query`, `Mutation` etc for you to use.

## Running this example

Before running this example, make sure to create a `local.dart` file inside the `lib` directory, and add your Github token, as shown below:

```dart
const String YOUR_PERSONAL_ACCESS_TOKEN =
   '<YOUR_PERSONAL_ACCESS_TOKEN>';
```

I will add complete documentation for this example soon.

This repo, after completion shall be merged as one of the examples inside the `graphql_flutter`.
