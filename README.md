# Awesome GraphQL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A query language and runtime for APIs that prioritizes precise data fetching and strongly typed schemas.

## Contents

- [Specifications](#specifications)
- [Federation & Schema Composition](#federation--schema-composition)
- [Foundations](#foundations)
- [Communities](#communities)
- [Meetups](#meetups)
- [Implementations](#implementations)
- [Tools](#tools)
- [Databases & Data Platforms](#databases--data-platforms)
- [Services](#services)
- [Tutorials](#tutorials)
- [Books](#books)
- [Videos](#videos)
- [Podcasts](#podcasts)
- [Style Guides](#style-guides)
- [Blogs](#blogs)
- [Posts](#posts)

<a name="spec" />

## Specifications

- <b><code>&nbsp;14596⭐</code></b> <b><code>&nbsp;&nbsp;1155🍴</code></b> [GraphQL](https://github.com/graphql/graphql-spec)) - Working draft of the specification for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [GraphQL over HTTP](https://github.com/graphql/graphql-over-http)) - Working draft of "GraphQL over HTTP" specification.
- 🌎 [GraphQL Relay](relay.dev/docs/guides/graphql-server-specification/) - Relay-compliant GraphQL server specification.
- <b><code>&nbsp;&nbsp;&nbsp;390⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [OpenCRUD](https://github.com/opencrud/opencrud)) - CRUD API specification for GraphQL databases.
- 🌎 [GraphQXL](gabotechs.github.io/graphqxl/) - Extension of the GraphQL language for creating large, scalable server-side schemas.
- 🌎 [GraphQL Scalars](www.graphql-scalars.com/) - Hosts community-defined custom scalar specifications for use with `@specifiedBy`.
- 🌎 [Apollo Technical Specifications](specs.apollo.dev/) - Registry of Apollo's versioned GraphQL schema and protocol specifications.
- 🌎 [Apollo Link](specs.apollo.dev/link/v1.0/) - Draft specification for linking a GraphQL schema to external schemas and importing their definitions.
- 🌎 [Apollo Incremental Delivery](specs.apollo.dev/incremental/v0.2/) - Specification for the response format and client behavior used with `@defer` and `@stream`.

## Federation & Schema Composition

### Specification

- 🌎 [GraphQL Federation](graphql.github.io/graphql-federation-spec/) - Prerelease working draft for composing independently developed GraphQL schemas into a unified graph.
- 🌎 [Apollo Federation](specs.apollo.dev/federation/v2.9/) - Apollo's specification for composing subgraphs into a federated supergraph.
- 🌎 [Apollo Join](specs.apollo.dev/join/v0.3/) - Specification for describing subgraphs and field resolution in a supergraph schema.

### Implementations & Platforms

- <b><code>&nbsp;&nbsp;&nbsp;272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [federation-jvm](https://github.com/apollographql/federation-jvm)) - Apollo Federation on the JVM.
- <b><code>&nbsp;&nbsp;1268⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [WunderGraph Cosmo](https://github.com/wundergraph/cosmo)) - Open source GraphQL federation solution with schema registry, composition checks, analytics, metrics, tracing, and routing.
- <b><code>&nbsp;&nbsp;3511⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;363🍴</code></b> [graphql-mesh](https://github.com/ardatan/graphql-mesh)) - A GraphQL federation framework for unifying GraphQL, REST, OpenAPI, SOAP, gRPC, and other API services.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [graphql-orchestrator-java](https://github.com/graph-quilt/graphql-orchestrator-java)) - Orchestrator and gateway library that combines schemas from multiple GraphQL microservices using schema stitching and Apollo Federation directives.

### Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Mocked Managed Federation - Apollo Server 3](https://github.com/setchy/apollo-server-3-mocked-federation)) - Example of mocking a managed federation subgraph using Apollo Server 3.x.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Mocked Managed Federation - Apollo Server 4](https://github.com/setchy/apollo-server-4-mocked-federation)) - Example of mocking a managed federation subgraph using Apollo Server 4.x.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [graphql-java-kickstart-federation-example](https://github.com/setchy/graphql-java-kickstart-federation-example)) - A GraphQL Java Kickstart federation example.
- <b><code>&nbsp;&nbsp;&nbsp;114⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [dgs-federation-example](https://github.com/Netflix/dgs-federation-example)) - A Netflix DGS federation example.

### Posts

- 🌎 [GraphQL federation example with Apollo Federation and Apollo GraphOS](cube.dev/blog/graphql-federation-example-with-apollo-federation-and-apollo-graphos) - Tutorial for federating services with Apollo Federation, GraphOS, and Cube.
- 🌎 [GraphQL federation with Hasura GraphQL Engine and Cube](cube.dev/blog/graphql-federation-with-hasura-graphql-engine) - Tutorial for federating Hasura and Cube GraphQL APIs.

<a name="foundation" />

## Foundations

- 🌎 [GraphQL Foundation](graphql.org/foundation/) - Organization supporting GraphQL under the Linux Foundation.

<a name="community" />

## Communities

- 🌎 [Discord - GraphQL](discord.graphql.org/) - Official GraphQL.org Discord channel.
- 🌎 [GraphQL Weekly](www.graphqlweekly.com/) - A weekly newsletter highlighting resources and news from the GraphQL community.
- 🌎 [Apollo GraphQL Community](community.apollographql.com/) - Connect with other developers and share knowledge about every part of the Apollo GraphQL platform.
- [Discord - Reactiflux](http://join.reactiflux.com/) - Join `#help-graphql` on the Reactiflux Discord server.
- 🌎 [Facebook](www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing.
- 🌎 [X](x.com/search?q=%23GraphQL) - Use the hashtag `#graphql`.
- 🌎 [Stack Overflow](stackoverflow.com/questions/tagged/graphql) - Questions and answers using the tag `graphql`.
- <b><code>&nbsp;&nbsp;4694⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;352🍴</code></b> [GraphQL APIs](https://github.com/APIs-guru/graphql-apis)) - A collective list of public GraphQL APIs.
- 🌎 [/r/GraphQL](www.reddit.com/r/graphql/) - A subreddit for GraphQL news, resources, and discussions.

<a name="meetup" />

## Meetups

- 🌎 [Relay Meetup](relaymeetup.com/) - A global, online meetup on Relay, the GraphQL client.
- 🌎 [Amsterdam](www.meetup.com/Amsterdam-GraphQL-Meetup/) - Local GraphQL meetup community.
- 🌎 [Bangalore](www.meetup.com/graphql-bangalore/) - Local GraphQL meetup community.
- 🌎 [Berlin](www.meetup.com/graphql-berlin/) - Local GraphQL meetup community.
- 🌎 [Buenos Aires](www.meetup.com/es-ES/GraphQL-BA/) - Local GraphQL meetup community.
- 🌎 [Copenhagen](www.meetup.com/Copenhagen-GraphQL-Meetup-Group/) - Local GraphQL meetup community.
- 🌎 [Dallas-Fort Worth](www.meetup.com/DFW-GraphQL-Meetup/) - Local GraphQL meetup community.
- 🌎 [Hamburg](www.meetup.com/GraphQL-Hamburg/) - Local GraphQL meetup community.
- 🌎 [London](www.meetup.com/GraphQL-London/) - Local GraphQL meetup community.
- 🌎 [Melbourne](www.meetup.com/GraphQL-Melbourne/) - Local GraphQL meetup community.
- 🌎 [Munich](www.meetup.com/GraphQL-Munich/) - Local GraphQL meetup community.
- 🌎 [New York City](www.meetup.com/GraphQL-NYC/) - Local GraphQL meetup community.
- 🌎 [San Francisco](www.meetup.com/GraphQL-SF/) - Local GraphQL meetup community.
- 🌎 [Seattle](www.meetup.com/Seattle-GraphQL/) - Local GraphQL meetup community.
- 🌎 [Sydney](www.meetup.com/GraphQL-Sydney/) - Local GraphQL meetup community.
- 🌎 [Tel Aviv](www.meetup.com/GraphQL-TLV/) - Local GraphQL meetup community.
- 🌎 [Wrocław](www.meetup.com/GraphQL-Wroclaw/) - Local GraphQL meetup community.
- 🌎 [Singapore](www.meetup.com/GraphQL-SG/) - Local GraphQL meetup community.
- 🌎 [Zurich](www.meetup.com/GraphQL-Zurich/) - Local GraphQL meetup community.

<a name="impl" />

## Implementations

<a name="js" />

### JavaScript/TypeScript

- <b><code>&nbsp;20346⭐</code></b> <b><code>&nbsp;&nbsp;2114🍴</code></b> [graphql-js](https://github.com/graphql/graphql-js)) - A reference implementation of GraphQL for JavaScript.
- <b><code>&nbsp;&nbsp;1084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [graphql-jit](https://github.com/zalando-incubator/graphql-jit)) - GraphQL execution using a JIT compiler.
- 🌎 [Gra**fast**](grafast.org) - A cutting edge planning and execution engine for GraphQL.

#### Clients

- <b><code>&nbsp;19803⭐</code></b> <b><code>&nbsp;&nbsp;2868🍴</code></b> [apollo-client](https://github.com/apollographql/apollo-client)) - A production-ready GraphQL client for TypeScript and JavaScript with caching, framework integrations, and developer tools.
- <b><code>&nbsp;&nbsp;6119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [Graffle](https://github.com/graffle-js/graffle)) - A minimal, extensible, type-safe GraphQL client for JavaScript and TypeScript runtimes.
- 🌎 [typescript-graphql-request](graphql-code-generator.com/docs/plugins/typescript-graphql-request) - Use GraphQL Request as a fully typed SDK.
- <b><code>&nbsp;&nbsp;1977⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [graphql-zeus](https://github.com/graphql-editor/graphql-zeus)) - Generates type-safe JavaScript and TypeScript GraphQL clients with autocomplete.
- <b><code>&nbsp;&nbsp;3378⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [graphqurl](https://github.com/hasura/graphqurl)) - Curl for GraphQL with autocomplete, subscriptions, and GraphiQL, plus a universal JavaScript GraphQL client.
- <b><code>&nbsp;&nbsp;9557⭐</code></b> <b><code>&nbsp;&nbsp;2176🍴</code></b> [aws-amplify](https://github.com/aws-amplify/amplify-js)) - A JavaScript library for building applications with AWS cloud services, including GraphQL APIs through AWS AppSync.
- <b><code>&nbsp;&nbsp;1040⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [gqty](https://github.com/gqty-dev/gqty)) - No-query-language GraphQL client for TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;980⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [genql](https://github.com/remorses/genql)) - Type safe TypeScript client for any GraphQL API.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [zodql](https://github.com/mattiasahlsen/zodql)) - Type-safe GraphQL client that uses Zod schemas as the single source of truth to build queries, infer response types, and validate responses at runtime.

##### Frontend Framework Integrations

- <b><code>&nbsp;&nbsp;6029⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;516🍴</code></b> [vue-apollo](https://github.com/vuejs/apollo)) - Apollo Client integration for Vue.js.
- <b><code>&nbsp;&nbsp;1514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [apollo-angular](https://github.com/the-guild-org/apollo-angular)) - Apollo Client integration for Angular with declarative data fetching and caching.
- <b><code>&nbsp;&nbsp;&nbsp;945⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [svelte-apollo](https://github.com/timhall/svelte-apollo)) - Svelte integration for Apollo GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;280⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [ember-apollo-client](https://github.com/ember-graphql/ember-apollo-client)) - An ember-cli addon for Apollo Client and GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [apollo-elements](https://github.com/apollo-elements/apollo-elements)) - GraphQL web components that work in any frontend framework.
- <b><code>&nbsp;&nbsp;&nbsp;455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [sveltekit-kitql](https://github.com/jycouet/kitql)) - A collection of tools for building SvelteKit applications with GraphQL.

###### React

- 🌎 [react-apollo](www.apollographql.com/docs/react/) - The core @apollo/client library provides built-in integration with React.
- <b><code>&nbsp;18964⭐</code></b> <b><code>&nbsp;&nbsp;1893🍴</code></b> [relay](https://github.com/facebook/relay)) - JavaScript framework for building data-driven React applications.
- <b><code>&nbsp;&nbsp;8978⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;480🍴</code></b> [urql](https://github.com/urql-graphql/urql)) - A customizable GraphQL client with framework bindings and extensible caching.
- <b><code>&nbsp;&nbsp;1887⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [graphql-hooks](https://github.com/nearform/graphql-hooks)) - Minimal hooks-first GraphQL client with caching and server-side rendering support.
- <b><code>&nbsp;&nbsp;&nbsp;691⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [mst-gql](https://github.com/mobxjs/mst-gql)) - Bindings for mobx-state-tree and GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;525⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [micro-graphql-react](https://github.com/arackaf/micro-graphql-react)) - A lightweight React GraphQL client with simple caching and support for service-worker caching through GET requests.

#### Servers

- <b><code>&nbsp;13954⭐</code></b> <b><code>&nbsp;&nbsp;2004🍴</code></b> [apollo-server](https://github.com/apollographql/apollo-server)) - A spec-compliant, production-ready JavaScript GraphQL server for schema-first development with standalone and web framework integrations.
- <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql)) - Create a GraphQL HTTP server with Hapi.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [hapi-plugin-graphiql](https://github.com/rse/hapi-plugin-graphiql)) - HAPI plugin for GraphiQL integration.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [graphql-api-koa](https://github.com/jaydenseric/graphql-api-koa)) - GraphQL Koa middleware that implements GraphQL.js from scratch and supports native ESM.
- <b><code>&nbsp;&nbsp;&nbsp;840⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [koa-graphql](https://github.com/chentsulin/koa-graphql)) - GraphQL Koa Middleware.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [graphql-koa-scripts](https://github.com/ryanhs/graphql-koa-scripts)) - GraphQL Koa 1 file simplified. Useful for quick test.
- <b><code>&nbsp;&nbsp;&nbsp;204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [gql](https://github.com/deno-libs/gql)) - Universal GraphQL HTTP middleware for Deno.
- <b><code>&nbsp;&nbsp;2490⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;253🍴</code></b> [mercurius](https://github.com/mercurius-js/mercurius)) - GraphQL plugin for Fastify.
- <b><code>&nbsp;&nbsp;8529⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;598🍴</code></b> [graphql-yoga](https://github.com/graphql-hive/graphql-yoga)) - A fully featured GraphQL server built on the WHATWG Fetch API for deployment in any JavaScript environment.
- <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [graphitejs](https://github.com/graphitejs/server)) - Node.js framework for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;826⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [graphql-helix](https://github.com/contrawork/graphql-helix)) - A highly evolved GraphQL HTTP Server.
- <b><code>&nbsp;&nbsp;&nbsp;374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [pylon](https://github.com/getcronit/pylon)) - Write full-feature APIs with just functions. No more boilerplate code, no more setup. Just write functions and deploy.
- 🌎 [Booster framework](booster.cloud/) - Open-source serverless framework that generates GraphQL queries, mutations, and subscriptions from application models.

##### Databases & ORMs

- <b><code>&nbsp;&nbsp;1883⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize)) - Sequelize helpers for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf)) - Some help defining GraphQL schema around BookshelfJS models.
- <b><code>&nbsp;&nbsp;2699⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;226🍴</code></b> [join-monster](https://github.com/acarl005/join-monster)) - A GraphQL-to-SQL query execution layer for batch data fetching.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Simfinity.js](https://github.com/simtlix/simfinity.js)) - Generates GraphQL queries, mutations, relationships, and MongoDB or PostgreSQL storage from GraphQL object types.

##### PubSub

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [graphql-ably-pubsub](https://github.com/ably-labs/graphql-ably-pubsub)) - Ably PubSub implementation for GraphQL to publish mutation updates and subscribe to the result through a subscription query.

#### Custom Scalars

- <b><code>&nbsp;&nbsp;1932⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [graphql-scalars](https://github.com/Urigo/graphql-scalars)) - A library of custom GraphQL Scalars for creating precise type-safe GraphQL schemas.

#### Schema Builders

- <b><code>&nbsp;&nbsp;8090⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;670🍴</code></b> [type-graphql](https://github.com/MichalLytek/type-graphql)) - Creates GraphQL schemas and resolvers with TypeScript classes and decorators.
- <b><code>&nbsp;&nbsp;3430⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;272🍴</code></b> [graphql-nexus](https://github.com/graphql-nexus/nexus)) - Code-First, Type-Safe, GraphQL Schema Construction.
- <b><code>&nbsp;&nbsp;2618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [pothos](https://github.com/hayes/pothos)) - Plugin-based GraphQL schema builder for TypeScript.
- <b><code>&nbsp;&nbsp;1312⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [garph](https://github.com/stepci/garph)) - Full-stack framework for building type-safe GraphQL APIs in TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [gqloom](https://github.com/modevol-com/gqloom)) - GraphQL weaver for TypeScript/JavaScript that weaves GraphQL schema and resolvers using Valibot, Zod, or Yup.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [fast-graphql](https://github.com/idurar/fast-graphql)) - GraphQL tools to structure and combine resolvers and merge schema definitions for Node.js, Next.js, and Apollo Server.

#### Code Generation & Typed Documents

- <b><code>&nbsp;11263⭐</code></b> <b><code>&nbsp;&nbsp;1401🍴</code></b> [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator)) - GraphQL code generator with flexible support for custom plugins and templates such as TypeScript, React Hooks, and resolver signatures.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-to-type](https://github.com/lkster/graphql-to-type)) - GraphQL query parser written entirely in TypeScript's type system for creating interfaces from a provided query.
- <b><code>&nbsp;&nbsp;2973⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [gql.tada](https://github.com/0no-co/gql.tada)) - GraphQL document authoring library, inferring the result and variables types of GraphQL queries and fragments in the TypeScript type system.

#### Miscellaneous

- <b><code>&nbsp;&nbsp;5431⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;829🍴</code></b> [graphql-tools](https://github.com/ardatan/graphql-tools)) - Utilities for building, mocking, and stitching GraphQL schemas.
- <b><code>&nbsp;&nbsp;2330⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [graphql-tag](https://github.com/apollographql/graphql-tag)) - A JavaScript template literal tag that parses GraphQL queries.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [load-gql](https://github.com/KunalSin9h/load-gql)) - A tiny, zero dependency GraphQL schema loader from files and folders.
- <b><code>&nbsp;&nbsp;1210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [graphql-compose](https://github.com/graphql-compose/graphql-compose)) - Tool for constructing flexible GraphQL schemas from different data sources via plugins.
- <b><code>&nbsp;&nbsp;1327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [graphql-modules](https://github.com/graphql-hive/graphql-modules)) - Modularizes GraphQL schemas and resolvers into reusable, testable feature units.
- <b><code>&nbsp;&nbsp;3576⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [graphql-shield](https://github.com/maticzav/graphql-shield)) - Library for creating a permission layer for a GraphQL API.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [graphql-shield-generator](https://github.com/omar-dulaimi/graphql-shield-generator)) - Emits a GraphQL Shield from your GraphQL schema.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [graphqlgate](https://github.com/oslabs-beta/GraphQL-Gate)) - GraphQL rate-limiting library with query complexity analysis for Node.js.
- <b><code>&nbsp;&nbsp;&nbsp;452⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [graphql-let](https://github.com/piglovesyou/graphql-let)) - Webpack loader for importing type-protected code generation results directly from GraphQL documents.
- <b><code>&nbsp;&nbsp;1199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [graphql-config](https://github.com/graphql-hive/graphql-config)) - Provides shared configuration for GraphQL tools, editors, and IDEs.
- <b><code>&nbsp;&nbsp;2018⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [graphql-cli](https://github.com/urigo/graphql-cli)) - A command line tool for common GraphQL development workflows.
- <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [graphql-toolkit](https://github.com/ardatan/graphql-toolkit)) - A set of utils for faster development of GraphQL tools (Schema and documents loading, Schema merging and more).
- <b><code>&nbsp;&nbsp;1119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [sofa](https://github.com/graphql-hive/SOFA)) - Generates RESTful APIs from a GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;407⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [graphback](https://github.com/aerogear/graphback)) - Framework and CLI to add a GraphQLCRUD API layer to a GraphQL server using data models.
- <b><code>&nbsp;&nbsp;1146⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [graphql-middleware](https://github.com/maticzav/graphql-middleware)) - Split up your GraphQL resolvers in middleware functions.
- <b><code>&nbsp;&nbsp;1542⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [graphql-relay-js](https://github.com/graphql/graphql-relay-js)) - A library to help construct a graphql-js server supporting react-relay.
- <b><code>&nbsp;&nbsp;&nbsp;196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [graphql-normalizr](https://github.com/monojack/graphql-normalizr)) - Normalize GraphQL responses for persisting in the client cache/state.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql)) - Babel plugin that compiles GraphQL tagged template strings.
- <b><code>&nbsp;&nbsp;1215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql)) - An ESLint plugin that checks your GraphQL strings against a schema.
- <b><code>&nbsp;&nbsp;1872⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [graphql-ws](https://github.com/enisdenjo/graphql-ws)) - Coherent, zero-dependency, lazy, simple, GraphQL over WebSocket Protocol compliant server and client.
- <b><code>&nbsp;&nbsp;&nbsp;442⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [graphql-live-query](https://github.com/n1ru4l/graphql-live-query)) - Realtime GraphQL Live Queries with JavaScript.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [microfiber](https://github.com/anvilco/graphql-introspection-tools)) - Query and manipulate GraphQL introspection query results in useful ways.
- <b><code>&nbsp;&nbsp;&nbsp;577⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [GraphQL Constraint Directive](https://github.com/confuser/graphql-constraint-directive)) - Allows `@constraint` directives to validate input data, inspired by the Constraints Directives RFC and OpenAPI.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Validator.js Wrapper Directive](https://github.com/ktutnik/graphql-directive/tree/master/packages/validator)) - Wraps Validator.js functionality in validation directives.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-sunset](https://github.com/sophiabits/graphql-sunset)) - Quickly and easily add support for the `Sunset` header to your GraphQL server, to better communicate upcoming breaking changes.

<a name="js-example" />

#### JavaScript Examples

- <b><code>&nbsp;23687⭐</code></b> <b><code>&nbsp;&nbsp;4201🍴</code></b> [React Starter Kit](https://github.com/kriasoft/react-starter-kit)) - Frontend starter kit using React, Relay, GraphQL, and JAMstack architecture.
- <b><code>&nbsp;&nbsp;1063⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;268🍴</code></b> [SWAPI GraphQL Wrapper](https://github.com/graphql/swapi-graphql)) - A GraphQL schema and server wrapping SWAPI.
- <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Relay TodoMVC](https://github.com/taion/relay-todomvc)) - TodoMVC example with Relay and routing.
- 🌎 [Apollo Server tools documentation](www.apollographql.com/docs/apollo-server/) - Documentation, tutorial and examples for building GraphQL server and connecting to SQL, MongoDB and REST endpoints.
- <b><code>&nbsp;13879⭐</code></b> <b><code>&nbsp;&nbsp;2458🍴</code></b> [F8 App 2017](https://github.com/fbsamples/f8app)) - Source code for the official 2017 F8 app, built with React Native, Relay, and GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Apollo React example for GitHub GraphQL API](https://github.com/katopz/react-apollo-graphql-github-example)) - Example using Apollo React with the GitHub GraphQL API and Create React App.
- <b><code>142491⭐</code></b> <b><code>&nbsp;33080🍴</code></b> [Next.js TypeScript and GraphQL Example](https://github.com/zeit/next.js/tree/canary/examples/with-typescript-graphql)) - Type-protected GraphQL example on Next.js running graphql-codegen under the hood.
- 🌎 [GraphQL StackBlitz Starter](stackblitz.com/fork/graphql) - Live, editable demo that starts in a browser in about two seconds.
- [VulcanJS](http://vulcanjs.org) - Full-stack React and GraphQL framework.
- <b><code>&nbsp;&nbsp;2204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [RAN Toolkit](https://github.com/sly777/ran)) - Production-ready toolkit/boilerplate with support for GraphQL, SSR, Hot-reload, CSS-in-JS, caching, and more.

<a name="ts-example" />

#### TypeScript Examples

- <b><code>&nbsp;&nbsp;3970⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;551🍴</code></b> [Node.js API Starter](https://github.com/kriasoft/graphql-starter-kit)) - Monorepo starter with a code-first GraphQL API, PostgreSQL, React, and Joy UI.
- <b><code>&nbsp;&nbsp;&nbsp;274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Next.js Apollo TypeScript Starter](https://github.com/borisowsky/nextjs-apollo-ts-starter)) - Next.js starter project focused on developer experience.
- <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [GraphQL Starter](https://github.com/cerino-ligutom/GraphQL-Starter)) - A boilerplate for TypeScript + Node Express + Apollo GraphQL APIs.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Next.js Advanced GraphQL CRUD MongoDB Starter](https://github.com/idurar/starter-advanced-graphql-crud-next-js-mongodb)) - Generic CRUD starter with an advanced Apollo GraphQL server, Next.js, MongoDB, and TypeScript.

<a name="rb" />

### Ruby

- <b><code>&nbsp;&nbsp;5443⭐</code></b> <b><code>&nbsp;&nbsp;1418🍴</code></b> [graphql-ruby](https://github.com/rmosolgo/graphql-ruby)) - Ruby implementation of GraphQL with tools for defining schemas, executing queries, and serving subscriptions.
- <b><code>&nbsp;&nbsp;1443⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [graphql-batch](https://github.com/Shopify/graphql-batch)) - Query batching executor for the GraphQL Ruby gem.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [graphql-auth](https://github.com/o2web/graphql-auth)) - A JWT auth wrapper working with devise.
- <b><code>&nbsp;&nbsp;&nbsp;934⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [agoo](https://github.com/ohler55/agoo)) - High-performance Ruby web server with GraphQL support.
- <b><code>&nbsp;&nbsp;&nbsp;210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [GQLi](https://github.com/contentful-labs/gqli.rb)) - A GraphQL client and DSL for writing queries in native Ruby.

<a name="rb-example" />

#### Ruby Examples

- <b><code>&nbsp;&nbsp;&nbsp;215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo)) - Use graphql-ruby to expose a Rails app.
- <b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [github-graphql-rails-example](https://github.com/github/github-graphql-rails-example)) - Example Rails app using GitHub's GraphQL API.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [relay-on-rails](https://github.com/nethsix/relay-on-rails)) - Barebones starter kit for Relay application with Rails GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [relay-rails-blog](https://github.com/gauravtiwari/relay-rails-blog)) - Demo weblog powered by GraphQL, Relay, and a standard Rails application.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [to_eat_app](https://github.com/jcdavison/to_eat_app)) - Sample GraphQL, Rails, and Relay application with a related three-part article series.
- <b><code>&nbsp;&nbsp;&nbsp;934⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [agoo-demo](https://github.com/ohler55/agoo/tree/develop/example/graphql)) - Use of the Agoo server to demonstrate a simple GraphQL application.
- <b><code>&nbsp;&nbsp;&nbsp;284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [rails-devise-graphql](https://github.com/zauberware/rails-devise-graphql)) - Rails 6 boilerplate with Devise, GraphQL, and JWT authentication.

<a name="php" />

### PHP

- <b><code>&nbsp;&nbsp;4714⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;577🍴</code></b> [graphql-php](https://github.com/webonyx/graphql-php)) - A PHP port of GraphQL reference implementation.
- <b><code>&nbsp;&nbsp;&nbsp;271⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [graphql-relay-php](https://github.com/ivome/graphql-relay-php)) - Relay helpers for webonyx/graphql-php implementation of GraphQL.
- <b><code>&nbsp;&nbsp;3497⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;468🍴</code></b> [lighthouse](https://github.com/nuwave/lighthouse)) - A PHP package that allows to serve a GraphQL endpoint from your Laravel application.
- <b><code>&nbsp;&nbsp;2222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;271🍴</code></b> [graphql-laravel](https://github.com/rebing/graphql-laravel)) - Laravel package for building GraphQL APIs with webonyx/graphql-php.
- <b><code>&nbsp;&nbsp;&nbsp;796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [overblog/graphql-bundle](https://github.com/overblog/GraphQLBundle)) - This bundle provides tools to build a complete GraphQL server in your Symfony App. Supports react-relay.
- <b><code>&nbsp;&nbsp;3791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;472🍴</code></b> [wp-graphql](https://github.com/wp-graphql/wp-graphql)) - GraphQL API for WordPress.
- <b><code>&nbsp;&nbsp;&nbsp;577⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [graphqlite](https://github.com/thecodingmachine/graphqlite)) - Framework agnostic library that allows you to write GraphQL server by annotating your PHP classes.
- <b><code>&nbsp;&nbsp;1110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [siler](https://github.com/leocavalcante/siler)) - Plain-old functions providing a declarative API for GraphQL servers with Subscriptions support.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-request-builder](https://github.com/dpauli/php-graphql-request-builder)) - Builds request payload in GraphQL structure.
- 🌎 [Drupal GraphQL](www.drupal.org/project/graphql) - Drupal module for crafting and exposing GraphQL schemas.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [jerowork/graphql-schema-builder](https://github.com/jerowork/graphql-attribute-schema)) - Easily build your GraphQL schema for webonyx/graphql-php using PHP attributes instead of large configuration arrays.

<a name="php-example" />

#### PHP Examples

- <b><code>&nbsp;&nbsp;1110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [siler-graphql](https://github.com/leocavalcante/siler/tree/main/examples/graphql)) - An example GraphQL server written with Siler.

<a name="py" />

### Python

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [graphql-parser](https://github.com/tryolabs/graphql-parser)) - GraphQL parser for Python.
- <b><code>&nbsp;&nbsp;&nbsp;532⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [graphql-core](https://github.com/graphql-python/graphql-core)) - Python port of the GraphQL.js reference implementation.
- <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py)) - A library for building GraphQL servers that support the Relay server specification.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python)) - A python wrapper around libgraphqlparser.
- <b><code>&nbsp;&nbsp;8238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;819🍴</code></b> [graphene](https://github.com/graphql-python/graphene)) - A package for creating GraphQL schemas/types in a Pythonic easy way.
- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [graphene-gae](https://github.com/graphql-python/graphene-gae)) - Adds GraphQL support to Google AppEngine (GAE).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [django-graphiql](https://github.com/GraphQL-python-archive/django-graphiql)) - Integrate GraphiQL easily into your Django project.
- <b><code>&nbsp;&nbsp;1340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;139🍴</code></b> [flask-graphql](https://github.com/graphql-python/flask-graphql)) - Adds GraphQL support to your Flask application.
- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [python-graphql-client](https://github.com/prisma/python-graphql-client)) - Simple GraphQL client for Python 2.7+.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [python-graphjoiner](https://github.com/healx/python-graphjoiner)) - Create GraphQL APIs using joins, SQL or otherwise.
- <b><code>&nbsp;&nbsp;4393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;762🍴</code></b> [graphene-django](https://github.com/graphql-python/graphene-django)) - A Django integration for Graphene.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Flask-GraphQL-Auth](https://github.com/callsign-viper/Flask-GraphQL-Auth)) - An authentication library for Flask inspired from flask-jwt-extended.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [tartiflette](https://github.com/dailymotion/tartiflette)) - Schema-first asynchronous GraphQL engine for Python.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [tartiflette-aiohttp](https://github.com/tartiflette/tartiflette-aiohttp)) - Wrapper for exposing Tartiflette GraphQL APIs over HTTP with aiohttp.
- <b><code>&nbsp;&nbsp;2345⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [Ariadne](https://github.com/mirumee/ariadne)) - Library for implementing GraphQL servers using a schema-first approach. Asynchronous query execution, batteries included for ASGI, WSGI and popular web frameworks with comprehensive documentation.
- <b><code>&nbsp;&nbsp;&nbsp;332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [django-graphql-auth](https://github.com/PedroBern/django-graphql-auth)) - Django registration and authentication with GraphQL.
- <b><code>&nbsp;&nbsp;4721⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;663🍴</code></b> [strawberry](https://github.com/strawberry-graphql/strawberry)) - Python GraphQL library that uses type annotations to define schemas.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [turms](https://github.com/jhnnsrs/turms)) - Pythonic GraphQL code generator built around graphql-core and Pydantic.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [rath](https://github.com/jhnnsrs/rath)) - Apollo-like GraphQL client with asynchronous and synchronous interfaces.
- <b><code>&nbsp;&nbsp;&nbsp;555⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [sgqlc](https://github.com/profusion/sgqlc)) - Simple GraphQL Client makes working with GraphQL API responses easier in Python.

<a name="py-example" />

#### Python Examples

- <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [swapi-graphene](https://github.com/graphql-python/swapi-graphene)) - GraphQL schema and server using Graphene.
- 🌎 [Python Backend Tutorial](hasura.io/learn/graphql/backend-stack/languages/python/) - Tutorial on creating a GraphQL server with Strawberry and a client with Qlient.

<a name="java" />

### Java

- <b><code>&nbsp;&nbsp;6220⭐</code></b> <b><code>&nbsp;&nbsp;1143🍴</code></b> [graphql-java](https://github.com/graphql-java/graphql-java)) - GraphQL Java implementation.
- <b><code>&nbsp;&nbsp;&nbsp;525⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [java-dataloader](https://github.com/graphql-java/java-dataloader)) - DataLoader implementation that provides batching and caching to avoid N+1 data-fetching problems.
- <b><code>&nbsp;&nbsp;3396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;344🍴</code></b> [DGS Framework](https://github.com/Netflix/dgs-framework)) - A GraphQL server framework for Spring Boot, developed by Netflix.
- 🌎 [Spring for GraphQL](spring.io/projects/spring-graphql) - Official Spring integration for applications built on GraphQL Java.
- <b><code>&nbsp;&nbsp;&nbsp;102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [MicroProfile GraphQL](https://github.com/microprofile/microprofile-graphql)) - Specification for developing portable, code-first GraphQL services with Enterprise Java.
- <b><code>&nbsp;&nbsp;&nbsp;177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [SmallRye GraphQL](https://github.com/smallrye/smallrye-graphql)) - Implementation of MicroProfile GraphQL with server, client, and tooling support.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Micronaut GraphQL](https://github.com/micronaut-projects/micronaut-graphql)) - Official Micronaut integration for building GraphQL Java servers.
- 🌎 [Vert.x Web GraphQL](vertx.io/docs/vertx-web-graphql/java/) - Official GraphQL Java integration for Vert.x Web.
- [graphql-java-generator](https://github.com/graphql-java-generator) - Maven and Gradle plugins that generate both the **client** and the **server** (POJOs and utility classes). The server part is based on graphql-java and hides its boilerplate code.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [gaphql-java-type-generator](https://github.com/graphql-java/graphql-java-type-generator)) - Automatically generates types for use with GraphQL Java.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [schemagen-graphql](https://github.com/bpatters/schemagen-graphql)) - Schema generation and execution package that turns POJO's into a GraphQL Java queryable set of objects. Enables exposing any service as a GraphQL service using Annotations.
- <b><code>&nbsp;&nbsp;&nbsp;393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [graphql-java-annotations](https://github.com/Enigmatis/graphql-java-annotations)) - Provides annotations-based syntax for schema definition with GraphQL Java.
- <b><code>&nbsp;&nbsp;&nbsp;824⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [graphql-java-tools](https://github.com/graphql-java-kickstart/graphql-java-tools)) - Schema-first graphql-java convenience library that makes it easy to bring your own implementations as data resolvers, inspired by graphql-tools for JS.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [graphql-java-codegen-maven-plugin](https://github.com/kobylynskyi/graphql-java-codegen-maven-plugin)) - Schema-first Maven plugin for generating Java types and resolver interfaces. Works with graphql-java-tools and was inspired by swagger-codegen-maven-plugin.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [graphql-java-codegen-gradle-plugin](https://github.com/kobylynskyi/graphql-java-codegen-gradle-plugin)) - Schema-first Gradle plugin for generating Java types and resolver interfaces. Works with graphql-java-tools and was inspired by gradle-swagger-generator-plugin.
- <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [graphql-java-servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet)) - A framework-agnostic java servlet for exposing graphql-java query endpoints with GET, POST, and multipart uploads.
- <b><code>&nbsp;&nbsp;2760⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql)) - Comprehensive schema-first GraphQL client with type-safe types, queries, and results, no code generators, no POJOs, and no annotations. Includes IDE support for IntelliJ IDEA and Android Studio. See the [Java example](#java-examples) below.
- <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [spring-graphql-common](https://github.com/oembedler/spring-graphql-common)) - Spring Framework GraphQL Library.
- <b><code>&nbsp;&nbsp;1502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;319🍴</code></b> [graphql-spring-boot](https://github.com/graphql-java-kickstart/graphql-spring-boot)) - GraphQL and GraphiQL Spring Framework Boot Starters.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [vertx-graphql-service-discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery)) - Asynchronous GraphQL service discovery and querying for your microservices.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [vertx-dataloader](https://github.com/engagingspaces/vertx-dataloader)) - Port of Facebook DataLoader for efficient, asynchronous batching and caching in clustered GraphQL environments.
- <b><code>&nbsp;&nbsp;1103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;182🍴</code></b> [graphql-spqr](https://github.com/leangen/GraphQL-SPQR)) - Java 8+ API for rapid development of GraphQL services.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Light Java GraphQL](https://github.com/networknt/light-graphql-4j)) - Lightweight, fast microservices framework with cross-cutting concerns addressed and support for GraphQL schemas.
- 🌎 [Elide](elide.io) - Java library that exposes a JPA-annotated data model as a GraphQL service over a relational database.
- <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [GraphQL JPA Query](https://github.com/introproventures/graphql-jpa-query)) - Generates GraphQL query APIs from JPA entity models.
- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [graphql-java-extended-validation](https://github.com/graphql-java/graphql-java-extended-validation)) - Provides extended validation of fields and field arguments for graphql-java.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [dgs-extended-formatters](https://github.com/setchy/dgs-extended-formatters)) - An experimental set of DGS Directives for common formatting use-cases.

#### Custom Scalars

- <b><code>&nbsp;&nbsp;&nbsp;153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [graphql-java-datetime](https://github.com/donbeave/graphql-java-datetime)) - GraphQL ISO Date is a set of RFC 3339 compliant date/time scalar types to be used with graphql-java.
- <b><code>&nbsp;&nbsp;&nbsp;290⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [graphql-java-extended-scalars](https://github.com/graphql-java/graphql-java-extended-scalars)) - Extended scalars for graphql-java.

<a name="java-example" />

#### Java Examples

- <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [light-java-graphql examples](https://github.com/networknt/light-example-4j/tree/master/graphql)) - Examples of Light Java GraphQL and tutorials.
- <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [graphql-spqr-samples](https://github.com/leangen/graphql-spqr-samples)) - An example GraphQL server written with Spring MVC and GraphQL-SPQR.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-graphql-app)) - A simple application, both client and server, demonstrating the Manifold GraphQL library.
- <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [graphql-java-kickstart_samples](https://github.com/graphql-java-kickstart/samples)) - Samples for using the GraphQL Java Kickstart projects.
- 🌎 [Spring for GraphQL reference](docs.spring.io/spring-graphql/reference/) - Official reference documentation for building GraphQL services with Spring.
- 🌎 [Spring Boot backend tutorial](hasura.io/learn/graphql/backend-stack/languages/java/) - A tutorial creating a GraphQL server and client using Spring Boot and Netflix DGS.

<a name="kotlin" />

### Kotlin

- <b><code>&nbsp;&nbsp;1804⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;381🍴</code></b> [graphql-kotlin](https://github.com/ExpediaGroup/graphql-kotlin)) - GraphQL Kotlin implementation.
- <b><code>&nbsp;&nbsp;&nbsp;307⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [KGraphQL](https://github.com/aPureBase/KGraphQL)) - Pure Kotlin implementation for setting up a GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Kobby](https://github.com/ermadmi78/kobby)) - Codegen plugin of Kotlin DSL Client by GraphQL schema. The generated DSL supports execution of complex GraphQL queries, mutation and subscriptions in Kotlin with syntax similar to native GraphQL syntax.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Graphkt](https://github.com/cufyorg/graphkt)) - DSL-based GraphQL server library for Kotlin, backed by graphql-java.

<a name="kotlin-example" />

#### Kotlin Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-kotlin-app)) - A simple GraphQL application, both client and server, demonstrating the Manifold GraphQL library with Kotlin.

<a name="c" />

### C/C++

- <b><code>&nbsp;&nbsp;1105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [libgraphqlparser](https://github.com/graphql/libgraphqlparser)) - A GraphQL query parser in C++ with C and C++ APIs.
- <b><code>&nbsp;&nbsp;&nbsp;153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [agoo-c](https://github.com/ohler55/agoo-c)) - High-performance GraphQL server written in C with published benchmarks.
- <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [cppgraphqlgen](https://github.com/Microsoft/cppgraphqlgen)) - C++ GraphQL schema service generator.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [CaffQL](https://github.com/caffeinetv/CaffQL)) - Generates C++ client types and request/response serialization from a GraphQL introspection query.

<a name="go" />

### Go

- <b><code>&nbsp;10145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;846🍴</code></b> [GraphQL](https://github.com/graphql-go/graphql)) - Implementation of GraphQL for Go that follows graphql-js.
- <b><code>&nbsp;&nbsp;4759⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;497🍴</code></b> [graphql-go](https://github.com/graph-gophers/graphql-go)) - GraphQL server with a focus on ease of use.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [gql](https://github.com/kadirpekel/gql)) - Code-first schema builder based on the reference Go implementation.
- <b><code>&nbsp;10764⭐</code></b> <b><code>&nbsp;&nbsp;1255🍴</code></b> [gqlgen](https://github.com/99designs/gqlgen)) - Go generate-based GraphQL server library.
- <b><code>&nbsp;&nbsp;&nbsp;423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [graphql-relay-go](https://github.com/graphql-go/relay)) - A Go/Golang library to help construct a server supporting react-relay.
- <b><code>&nbsp;&nbsp;3172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [graphjin](https://github.com/dosco/graphjin)) - Instant GraphQL-to-SQL compiler for building APIs quickly.
- <b><code>&nbsp;&nbsp;&nbsp;835⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [graphql-go-tools](https://github.com/wundergraph/graphql-go-tools)) - GraphQL router and API gateway framework written in Go, focused on correctness, extensibility, and performance.
- <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Thunder](https://github.com/Raezil/Thunder)) - Scalable microservices framework powered by Go, gRPC-Gateway, Prisma, and Kubernetes that exposes REST, gRPC, and GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;425⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [grpc-graphql-gateway](https://github.com/ysugimoto/grpc-graphql-gateway)) - Protoc plugin that generates GraphQL execution code from Protocol Buffers.
<a name="go-example" />

#### Go Examples

- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit)) - Barebones starting point for a Relay application with Golang GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go)) - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [go-graphql-subscription-example](https://github.com/ccamel/go-graphql-subscription-example)) - A GraphQL schema and server that demonstrates GraphQL <b><code>&nbsp;&nbsp;1504⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;327🍴</code></b> [subscriptions](https://github.com/apollographql/subscriptions-transport-ws/blob/v0.9.4/PROTOCOL.md)) over WebSocket to consume 🌎 [Apache Kafka](kafka.apache.org/) messages.
- 🌎 [Go Backend Tutorial](hasura.io/learn/graphql/backend-stack/languages/go/) - A tutorial showing how to make a Go GraphQL server and client using code generation.

<a name="scala" />

### Scala

- <b><code>&nbsp;&nbsp;1961⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;219🍴</code></b> [sangria](https://github.com/sangria-graphql/sangria)) - Scala GraphQL server implementation.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [sangria-relay](https://github.com/sangria-graphql/sangria-relay)) - Sangria Relay Support.
- <b><code>&nbsp;&nbsp;&nbsp;995⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;261🍴</code></b> [caliban](https://github.com/ghostdogpr/caliban)) - Purely functional library for creating GraphQL backends in Scala.

<a name="scala-example" />

#### Scala Examples

- <b><code>&nbsp;&nbsp;&nbsp;241⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example)) - An example GraphQL server written with akka-http and 🌎 [sangria](sangria-graphql.github.io/).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [sangria-playground](https://github.com/sangria-graphql/sangria-playground)) - An example of GraphQL server written with Play and sangria.

<a name="dotnet" />

### .NET

- <b><code>&nbsp;&nbsp;5991⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;947🍴</code></b> [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)) - GraphQL for .NET.
- <b><code>&nbsp;&nbsp;&nbsp;882⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [graphql-net](https://github.com/ckimes89/graphql-net)) - GraphQL to IQueryable for .NET.
- <b><code>&nbsp;&nbsp;5759⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;811🍴</code></b> [Hot Chocolate](https://github.com/ChilliCream/graphql-platform)) - .NET GraphQL platform containing the Hot Chocolate server, Strawberry Shake client, and Nitro IDE.
- <b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Snowflaqe](https://github.com/Zaid-Ajaj/Snowflaqe)) - Type-safe GraphQL code generator for F# and Fable.
- <b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [EntityGraphQL](https://github.com/EntityGraphQL/EntityGraphQL)) - Library for building a GraphQL API on top of a data model with support for multiple data sources.
- <b><code>&nbsp;&nbsp;&nbsp;323⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [ZeroQL](https://github.com/byme8/ZeroQL)) - Type-safe GraphQL client with a LINQ-like interface for C#.

<a name="net-example" />

#### .NET Examples

- 🌎 [.NET backend tutorial](hasura.io/learn/graphql/backend-stack/languages/dotnet/) - A tutorial creating a GraphQL server and client with .NET.

<a name="elixir" />

### Elixir

- <b><code>&nbsp;&nbsp;4402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;561🍴</code></b> [absinthe-graphql](https://github.com/absinthe-graphql/absinthe)) - Fully Featured Elixir GraphQL Library.
- <b><code>&nbsp;&nbsp;&nbsp;856⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [graphql-elixir](https://github.com/graphql-elixir/graphql)) - GraphQL Elixir. (No longer maintained)
- <b><code>&nbsp;&nbsp;&nbsp;126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [plug_graphql](https://github.com/graphql-elixir/plug_graphql)) - Plug integration for GraphQL Elixir.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [graphql_relay](https://github.com/graphql-elixir/graphql_relay)) - Relay helpers for GraphQL Elixir.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [graphql_parser](https://github.com/graphql-elixir/graphql_parser)) - Elixir bindings for libgraphqlparser.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [GraphQL](https://github.com/asonge/graphql)) - Elixir GraphQL parser.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [plot](https://github.com/peburrows/plot)) - GraphQL parser and resolver for Elixir.

<a name="elixir-example" />

#### Elixir Examples

- <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [hello_graphql_phoenix](https://github.com/graphql-elixir/hello_graphql_phoenix)) - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix.

<a name="haskell" />

### Haskell

- <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [graphql-haskell](https://github.com/jdnavarro/graphql-haskell)) - GraphQL AST and parser for Haskell.
- <b><code>&nbsp;&nbsp;&nbsp;414⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [morpheus-graphql](https://github.com/morpheusgraphql/morpheus-graphql)) - Haskell GraphQL Api, Client and Tools.

<a name="sql" />

### SQL

- <b><code>&nbsp;&nbsp;1086⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL)) - GraphQL for Postgres.
- <b><code>&nbsp;&nbsp;&nbsp;590⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [sql-to-graphql](https://github.com/rexxars/sql-to-graphql)) - Generate a GraphQL API based on your SQL database structure.
- <b><code>&nbsp;12936⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;627🍴</code></b> [PostGraphile](https://github.com/graphile/crystal)) - Extensible, plugin-based tooling for building high-performance GraphQL APIs from PostgreSQL schemas.
- <b><code>&nbsp;32121⭐</code></b> <b><code>&nbsp;&nbsp;3034🍴</code></b> [Hasura](https://github.com/hasura/graphql-engine)) - Provides instant real-time GraphQL APIs over new or existing PostgreSQL databases.

<a name="lua" />

### Lua

- <b><code>&nbsp;&nbsp;&nbsp;191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [graphql-lua](https://github.com/bjornbytes/graphql-lua)) - GraphQL for Lua.

<a name="elm" />

### Elm

- <b><code>&nbsp;&nbsp;&nbsp;787⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [elm-graphql](https://github.com/dillonkearns/elm-graphql)) - GraphQL for Elm.

<a name="clojure" />

### Clojure

- <b><code>&nbsp;&nbsp;&nbsp;287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [graphql-clj](https://github.com/tendant/graphql-clj)) - A Clojure library designed to provide GraphQL implementation.
- <b><code>&nbsp;&nbsp;1863⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [Lacinia](https://github.com/walmartlabs/lacinia)) - GraphQL implementation in pure Clojure.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [graphql-query](https://github.com/district0x/graphql-query)) - Clojure(Script) GraphQL query generation.

<a name="clojure-example" />

#### Clojure Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Clojure Game Geek](https://github.com/walmartlabs/clojure-game-geek)) - Example code for the Lacinia GraphQL framework tutorial.

<a name="swift" />

### Swift

- <b><code>&nbsp;&nbsp;&nbsp;959⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [GraphQL](https://github.com/GraphQLSwift/GraphQL)) - The Swift implementation for GraphQL.

<a name="ocaml" />

### OCaml

- <b><code>&nbsp;&nbsp;&nbsp;618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [ocaml-graphql-server](https://github.com/andreas/ocaml-graphql-server)) - GraphQL servers in OCaml.

<a name="android" />

### Android

- <b><code>&nbsp;&nbsp;3974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;697🍴</code></b> [apollo-kotlin](https://github.com/apollographql/apollo-kotlin)) - A strongly typed, caching GraphQL client for the JVM, Android, and Kotlin Multiplatform.

<a name="android-example" />

#### Android Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [apollo-frontpage-android-app](https://github.com/rnitame/apollo-frontpage-android-app)) - 📄 Apollo "hello world" app, for Android.

<a name="ios" />

### iOS

- <b><code>&nbsp;&nbsp;4036⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;761🍴</code></b> [apollo-ios](https://github.com/apollographql/apollo-ios)) - 📱 A strongly-typed, caching GraphQL client for iOS, written in Swift.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [ApolloDeveloperKit](https://github.com/manicmaniac/ApolloDeveloperKit)) - Apollo Client developer tools bridge for Apollo iOS.
- <b><code>&nbsp;&nbsp;&nbsp;498⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Graphaello](https://github.com/nerdsupremacist/Graphaello)) - Type Safe GraphQL directly from SwiftUI.

<a name="ios-example" />

#### iOS Examples

- <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [frontpage-ios-app](https://github.com/apollographql/frontpage-ios-app)) - 📄 Apollo "hello world" app, for iOS.

<a name="clojurescript" />

### ClojureScript

- <b><code>&nbsp;&nbsp;&nbsp;467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [re-graph](https://github.com/oliyh/re-graph)) - A GraphQL client for ClojureScript with bindings for re-frame applications.

<a name="reasonml" />

### ReasonML

- <b><code>&nbsp;&nbsp;&nbsp;545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [reason-apollo](https://github.com/apollographql/reason-apollo)) - ReasonML binding for Apollo Client.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [ReasonQL](https://github.com/sainthkh/reasonql)) - Type-safe and simple GraphQL Client for ReasonML developers.
- <b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [reason-urql](https://github.com/FormidableLabs/reason-urql)) - ReasonML binding for urql Client.

<a name="dart" />

### Dart

- <b><code>&nbsp;&nbsp;3268⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;643🍴</code></b> [graphql-flutter](https://github.com/zino-app/graphql-flutter)) - A GraphQL client for Flutter.
- <b><code>&nbsp;&nbsp;&nbsp;491⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [Artemis](https://github.com/comigor/artemis)) - A GraphQL type and query generator for Dart/Flutter.

<a name="rust" />

### Rust

- <b><code>&nbsp;&nbsp;3683⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;535🍴</code></b> [async-graphql](https://github.com/async-graphql/async-graphql)) - High-performance server-side library that supports all GraphQL specifications.
- <b><code>&nbsp;&nbsp;5969⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;442🍴</code></b> [juniper](https://github.com/graphql-rust/juniper)) - GraphQL server library for Rust.
- <b><code>&nbsp;&nbsp;1266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [graphql-client](https://github.com/tomhoule/graphql-client)) - GraphQL client library for Rust with WebAssembly support.
- <b><code>&nbsp;&nbsp;&nbsp;372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [graphql-parser](https://github.com/graphql-rust/graphql-parser)) - A parser, formatter and AST for the GraphQL query and schema definition language for Rust.

<a name="rust-example" />

#### Rust Examples

- 🌎 [Warp GraphQL Juniper](graphql-rust.github.io/) - Warp web framework integration example with a Juniper GraphQL server.

<a name="d" />

### D (dlang)

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [graphqld](https://github.com/burner/graphqld)) - GraphQL server library for D.

<a name="r" />

### R (Rstat)

- <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [ghql](https://github.com/ropensci/ghql)) - General purpose GraphQL R client.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [GraphQL](https://github.com/ropensci/graphql)) - Bindings to the 'libgraphqlparser' C++ library. Parses GraphQL syntax and exports the AST in JSON format.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [gqlr](https://github.com/schloerke/gqlr)) - R GraphQL Implementation.

<a name="julia" />

### Julia

- <b><code>&nbsp;&nbsp;&nbsp;114⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Diana.jl](https://github.com/codeneomatrix/Diana.jl)) - A Julia GraphQL client/server implementation.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [GraphQLClient.jl](https://github.com/DeloitteDigitalAPAC/GraphQLClient.jl)) - A Julia GraphQL client for seamless integration with a server.

<a name="crystal" />

### Crystal

- <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [GraphQL](https://github.com/graphql-crystal/graphql)) - Server library for Crystal.
- <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [graphql-crystal](https://github.com/ziprandom/graphql-crystal)) - Library inspired by graphql-ruby, go-graphql, and graphql-parser.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [crystal-gql](https://github.com/itsezc/crystal-gql)) - GraphQL client shard inspired by Apollo client.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql.cr](https://github.com/garymardell/graphql.cr)) - GraphQL shard.

### Ballerina

- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [GraphQL](https://github.com/ballerina-platform/module-ballerina-graphql)) - Standard Ballerina library providing GraphQL client and server implementations with built-in subscription support.
- <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [GraphQL CLI](https://github.com/ballerina-platform/graphql-tools)) - A CLI tool to generate Ballerina code from GraphQL schema and GraphQL schema from Ballerina code. It also provides functionality to generate usage-specific GraphQL clients using GraphQL schemas and documents.

#### Ballerina Samples

- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [Ballerina GraphQL Examples](https://github.com/ballerina-platform/module-ballerina-graphql/tree/master/examples)) - Sample implementations of GraphQL services in Ballerina.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Convert Weather REST API to GraphQL API](https://github.com/ThisaruGuruge/weather-rest-api-to-graphql)) - Example demonstrating REST API conversion to GraphQL.

<a name="tools" />

## Tools

### Tools - IDEs & Schema Explorers

- <b><code>&nbsp;16911⭐</code></b> <b><code>&nbsp;&nbsp;1856🍴</code></b> [GraphiQL](https://github.com/graphql/graphiql)) - Reference ecosystem for building browser and IDE tools around GraphQL and the GraphQL language server.
- <b><code>&nbsp;&nbsp;6069⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [GraphQL Editor](https://github.com/graphql-editor/graphql-editor)) - Visual Editor & GraphQL IDE.
- <b><code>&nbsp;&nbsp;8169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;554🍴</code></b> [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager)) - Represent any GraphQL API as an interactive graph.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Brangr](https://github.com/networkimprov/brangr)) - A unique, user-friendly data browser/viewer for any GraphQL service, with attractive result layouts.
- <b><code>&nbsp;&nbsp;&nbsp;700⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [GraphQL Birdseye](https://github.com/Novvum/graphql-birdseye)) - View any GraphQL schema as a dynamic and interactive graph.
- 🌎 [AST Explorer](astexplorer.net/) - Select "GraphQL" at the top, explore the GraphQL AST and highlight different parts by clicking in the query.
- <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [CraftQL](https://github.com/yamafaktory/craftql)) - A CLI tool to visualize GraphQL schemas and to output a graph data structure as a graphviz .dot format.
- 🌎 [Hackolade](studio.hackolade.com/) - Visual GraphQL schema editor that generates Schema Definition Language files and documents existing endpoints with introspection.
- 🌎 [Smart Formatter - GraphQL Query Formatter](smartformatter.com/tools/graphql-query-formatter) - A client-side, browser-only tool to format, beautify, and validate GraphQL queries and schemas instantly.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [GraphVinci](https://github.com/Comcast/graphvinci)) - An interactive schema visualizer for GraphQL APIs.

### Tools - API Clients & Workbenches

- <b><code>&nbsp;&nbsp;5433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;403🍴</code></b> [Altair GraphQL Client](https://github.com/altair-graphql/altair)) - A beautiful feature-rich GraphQL Client for all platforms.
- 🌎 [Insomnia](insomnia.rest/) - A full-featured API client with first-party GraphQL query editor.
- 🌎 [Postman](learning.postman.com/docs/sending-requests/supported-api-frameworks/graphql/) - An HTTP Client that supports editing GraphQL queries.
- <b><code>&nbsp;47211⭐</code></b> <b><code>&nbsp;&nbsp;2922🍴</code></b> [Bruno](https://github.com/usebruno/bruno)) - Fast, open source API client, which stores collections offline-only in a Git-friendly plain text markup language.
- <b><code>&nbsp;&nbsp;&nbsp;253⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Escape GraphMan](https://github.com/Escape-Technologies/graphman)) - Generate a complete Postman collection from a GraphQL endpoint.
- 🌎 [Apollo Sandbox](sandbox.apollo.dev/) - The quickest way to navigate and test your GraphQL endpoints.
- 🌎 [Firecamp - GraphQL Playground](firecamp.io/graphql) - The fastest collaborative GraphQL playground.
- <b><code>&nbsp;&nbsp;&nbsp;468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [gqt](https://github.com/eerimoq/gqt)) - Build and execute GraphQL queries in the terminal.
- 🌎 [Mongrel](www.visorcraft.com/) - Desktop workbench with a GraphQL client, plus HTTP, WebSocket, and gRPC, inside a multi-database GUI.
- 🌎 [GalleonQL](galleonql.com/) - A desktop API client built specifically for GraphQL (macOS, Windows, Linux), pairing an introspected schema browser with an incremental query builder and switchable endpoint profiles.


<a name="tool-testing" />

### Tools - Testing, Prototyping & Mocking

- 🌎 [Beeceptor](beeceptor.com/graphql-mock-server/) - A no-code platform for creating AI-powered **GraphQL Mock Servers** from your schema (SDL) with rules, stateful mocking, mutation/subscription, to speed up development and integration testing.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [graphql-to-karate](https://github.com/wbaldoumas/graphql-to-karate)) - **Generate Karate API tests** from your GraphQL schemas.
- <b><code>&nbsp;&nbsp;2712⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [GraphQL Faker](https://github.com/APIs-guru/graphql-faker)) - 🎲 Mock or extend your GraphQL API with faked data. No coding required.
- 🌎 [GraphQL Inspector](the-guild.dev/graphql/inspector) - A tool to **validate schemas**, compare schema changes, find breaking changes, and check document coverage against a schema.
- 🌎 [Microcks](microcks.io/) - Open source, cloud native tool for API mocking and testing with GraphQL support.
- <b><code>&nbsp;&nbsp;&nbsp;146⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [mockd](https://github.com/getmockd/mockd)) - Multi-protocol mock server with GraphQL schema mocking, resolver configuration, and query validation. Also supports HTTP, gRPC, WebSocket, MQTT, and SOAP.
- 🌎 [Keploy](keploy.io/) - Open-source AI Powered API testing tool that generates test cases and **data mocks automatically by recording real API traffic**. Supports GraphQL, REST, and gRPC.
- 🌎 [Step CI](stepci.com) - Open source API **testing and monitoring** with GraphQL support.
- 🌎 [MockBase](mockbase.org) - Hosted mock server for REST, GraphQL, and SOAP with fault injection, stateful mocks, and OpenAPI import.
- <b><code>&nbsp;&nbsp;1949⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [json-graphql-server](https://github.com/marmelab/json-graphql-server)) - Get a full fake GraphQL API with zero coding in less than 30 seconds, based on a JSON data file.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [supertest-graphql](https://github.com/alexstrat/supertest-graphql)) - Extends supertest to easily test a GraphQL endpoint.
- <b><code>&nbsp;&nbsp;3629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [schemathesis](https://github.com/schemathesis/schemathesis)) - Runs arbitrary queries matching a GraphQL schema to find server errors.

<a name="tool-security" />

### Tools - Security

- <b><code>&nbsp;&nbsp;&nbsp;334⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [GraphCrawler - The all-in-one GraphQL Security toolkit](https://github.com/gsmith257-cyber/GraphCrawler)) - Automated penetration testing toolkit for GraphQL, written in Python.
- 🌎 [Escape - The GraphQL Security Scanner](graphql.security/) - One-click security scan of your GraphQL endpoints. Free, no login required.
- <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Escape Graphinder - GraphQL Subdomain Enumeration](https://github.com/Escape-Technologies/graphinder)) - Blazing fast GraphQL endpoint finder using subdomain enumeration, script analysis, and brute force.
- 🌎 [StackHawk - GraphQL Vulnerability Scanner](www.stackhawk.com/blog/automated-graphql-security-testing) - Automated GraphQL security scanning and vulnerability detection.
- <b><code>&nbsp;&nbsp;1811⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [InQL Scanner](https://github.com/doyensec/inql)) - Burp extension for GraphQL security testing.
- 🌎 [GraphQL Raider](portswigger.net/bappstore/4841f0d78a554ca381c65b26d48207e6) - Burp Suite extension for GraphQL security testing.
- 🌎 [WAF for GraphQL](lab.wallarm.com/api-security-solution/) - Web application firewall for GraphQL APIs.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [GraphQL Intruder](https://github.com/davinerd/gql_intruder)) - Plugin-based Python script for performing GraphQL vulnerability assessments.
- <b><code>&nbsp;&nbsp;&nbsp;693⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [GraphQL Cop](https://github.com/dolevf/graphql-cop)) - Security audit utility for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [GraphQLer](https://github.com/omar2535/GraphQLer)) - Dependency-aware dynamic GraphQL testing tool.
- 🌎 [Vulert](vulert.com) - Detects vulnerabilities in open source dependencies without accessing code, with support for JavaScript, PHP, Java, Python, and more.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [hasura-security](https://github.com/Perufitlife/hasura-security)) - Active-probe security auditor for self-hosted Hasura GraphQL Engine that detects open introspection, public-role data leaks, and unauthenticated endpoints.
- <b><code>&nbsp;&nbsp;&nbsp;588⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [graphql-armor](https://github.com/Escape-Technologies/graphql-armor)) - An instant security layer for production GraphQL Endpoints.
- <b><code>&nbsp;&nbsp;&nbsp;135⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [goctopus](https://github.com/Escape-Technologies/goctopus)) - Fast GraphQL discovery and fingerprinting toolbox.

### Tools - Developer Extensions

- <b><code>&nbsp;&nbsp;1527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;173🍴</code></b> [Apollo Client Developer Tools](https://github.com/apollographql/apollo-client-devtools)) - GraphQL debugging tools for Apollo Client in the Chrome developer console.
- 🌎 [GraphQL Network Inspector](chrome.google.com/webstore/detail/graphql-network-inspector/ndlbedplllcgconngcnfmkadhokfaaln) - A simple and clean chrome dev-tools extension for GraphQL network inspection.
- 🌎 [Apollo GraphQL VSCode Extension](marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) - Rich editor support for GraphQL client and server development that integrates with the Apollo platform.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/)) - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [vim-graphql](https://github.com/jparise/vim-graphql)) - A Vim plugin that provides GraphQL file detection and syntax highlighting.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [graphql-autocomplete](https://github.com/orionsoft/atom-graphql-autocomplete)) - Autocomplete and lint from a GraphQL endpoint in Atom.
- <b><code>&nbsp;&nbsp;&nbsp;758⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin)) - A language service plugin complete and validate GraphQL query in TypeScript template strings.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Apollo APQ Debugger](https://github.com/rookieInTraining/apq-debugger)) - Reveal full GraphQL queries behind Apollo APQ hashes. Inspect fallback flow and debug Automatic Persisted Queries in DevTools.

### Tools - Docs

- <b><code>&nbsp;&nbsp;1563⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [graphdoc](https://github.com/2fd/graphdoc)) - Static page generator for documenting GraphQL Schema.
- <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [gqldoc](https://github.com/Code-Hex/gqldoc)) - The easiest way to make API documents for GraphQL.
- <b><code>&nbsp;&nbsp;1232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [spectaql](https://github.com/anvilco/spectaql)) - Autogenerate static GraphQL API documentation.
- 🌎 [graphql-markdown](graphql-markdown.github.io/) - Flexible documentation for GraphQL powered with Docusaurus.
- 🌎 [xyd](xyd.dev) - Generate GraphQL API docs.
- <b><code>&nbsp;&nbsp;3222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [Cortex](https://github.com/cortex-docs/cortex)) - Generates interactive API documentation and typed SDKs from GraphQL schemas.

### Tools - API Integration & Transformation

- <b><code>&nbsp;&nbsp;&nbsp;921⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [swagger-to-graphql](https://github.com/yarax/swagger-to-graphql)) - GraphQL types builder based on a REST API described in Swagger that supports migrating from REST to GraphQL in five minutes.
- <b><code>&nbsp;&nbsp;1645⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [openapi-to-graphql](https://github.com/ibm/openapi-to-graphql)) - Convert OpenAPI Specification or Swagger definitions to GraphQL interfaces.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Blendbase](https://github.com/blendbase/blendbase)) - Single open source GraphQL API for connecting CRMs to SaaS applications.
- 🌎 [Schemato](www.schemato.top/graphql-to-typescript) - Browser-only GraphQL SDL converter for generating TypeScript, Zod, Pydantic, Go, Rust, and other typed models.

### Tools - Data Access & ORMs

- <b><code>&nbsp;47673⭐</code></b> <b><code>&nbsp;&nbsp;2544🍴</code></b> [Prisma](https://github.com/prisma/orm)) - Type-safe ORM for Node.js and TypeScript that can serve as the data layer for GraphQL APIs.
- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Typetta](https://github.com/twinlogix/typetta)) - Node.js ORM written in TypeScript for type lovers and the GraphQL, Node.js, and TypeScript stack.
- <b><code>&nbsp;&nbsp;1073⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [tuql](https://github.com/bradleyboy/tuql)) - Automatically create a GraphQL server from any SQLite database.
- <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [dataloader-codegen](https://github.com/Yelp/dataloader-codegen)) - An opinionated JavaScript library for automatically generating predictable, type safe DataLoaders over a set of resources (e.g. HTTP endpoints).

### Tools - Low-Code & App Builders

- 🌎 [Retool](retool.com/) - Internal tools builder on top of GraphQL APIs with a GraphQL IDE and schema explorer.
- <b><code>&nbsp;16016⭐</code></b> <b><code>&nbsp;&nbsp;1541🍴</code></b> [amplication](https://github.com/amplication/amplication)) - Platform for defining golden paths and generating standardized backend services, including GraphQL APIs through plugins.
- 🌎 [DronaHQ](www.dronahq.com/) - Build internal tools, dashboards, and admin panels on top of GraphQL data in minutes.
- 🌎 [Dynaboard](dynaboard.com) - Generate low-code web apps from any GraphQL API using AI.

### Tools - Performance & Query Utilities

- <b><code>&nbsp;&nbsp;&nbsp;477⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [apollo-tracing](https://github.com/apollographql/apollo-tracing)) - GraphQL extension that enables you to easily get resolver-level performance information as part of a GraphQL response.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [gqlhash](https://github.com/romshark/gqlhash)) - Lightning fast query hasher that ignores formatting diffs and comments and supports multiple hashing functions.
  <a name="databases--data-platforms" />


## Databases & Data Platforms

- <b><code>&nbsp;20906⭐</code></b> <b><code>&nbsp;&nbsp;2143🍴</code></b> [Cube](https://github.com/cube-js/cube)) - Open-source semantic layer for AI, BI, and embedded analytics with GraphQL, SQL, and REST APIs.
- 🌎 [Dgraph](dgraph.io/) - Scalable, distributed, low-latency, high-throughput graph database with GraphQL as the query language.
- 🌎 [ArangoDB](arangodb.com/) - Native multi-model database with GraphQL support through Foxx microservices.
- <b><code>&nbsp;16850⭐</code></b> <b><code>&nbsp;&nbsp;1409🍴</code></b> [Weaviate](https://github.com/weaviate/weaviate)) - Open-source vector database combining vector search, structured filtering, and a GraphQL interface.

<a name="services" />

## Services

### GraphQL Platforms & Backends

- 🌎 [AWS AppSync](aws.amazon.com/appsync/) - Scalable managed GraphQL service with subscriptions for building real-time and offline-first apps.
- 🌎 [Nhost](nhost.io/) - Open source backend with a GraphQL API over PostgreSQL, plus auth, storage and functions.
- 🌎 [Grafbase](grafbase.com) - Instant GraphQL APIs for any data source.
- 🌎 [Graphweaver](graphweaver.com/) - Turn multiple datasources into a single GraphQL API.

### API Management, Delivery & Observability

- 🌎 [Moesif API Analytics](www.moesif.com/features/graphql-analytics) - GraphQL analytics and monitoring service for identifying functional and performance issues.
- 🌎 [Stellate](stellate.co/) - GraphQL edge platform for caching, observability, and API security, formerly known as GraphCDN.

### Data APIs & Gateways

- 🌎 [Stargate](stargate.io/docs/latest/quickstart/qs-graphql-cql-first.html) - Open-source data gateway that generates GraphQL APIs for Apache Cassandra and DataStax Enterprise tables.
- 🌎 [Vedika](vedika.io) - Vedic astrology AI API with GraphQL support for horoscopes, birth charts, kundali matching, and 108+ endpoints.
- 🌎 [Codex](www.codex.io) - GraphQL API for real-time and historical on-chain data, including token prices, charts, and holders across 90+ networks.

### Commerce

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Saleor](https://github.com/saleor/saleor/)) - High-performance, composable headless commerce API built with GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Unchained Engine](https://github.com/unchainedshop/unchained)) - GraphQL-first open-source headless e-commerce framework for Node.js.

### CMS

- 🌎 [DatoCMS](www.datocms.com/) - Headless content management system with a CDN-backed GraphQL Content Delivery API.
- 🌎 [Apito](apito.io/) - Cloud-based headless CMS with GraphQL APIs, a CDN, webhooks, collaboration, revisions, and cloud functions.
- 🌎 [Hygraph](hygraph.com/) - Federated content platform for composing and delivering content through GraphQL APIs.
- 🌎 [Cosmic](www.cosmicjs.com/) - GraphQL-powered Headless CMS and API toolkit.

<a name="tutorials" />

## Tutorials

- 🌎 [How to GraphQL](www.howtographql.com) - Fullstack Tutorial Website with Tracks for all Major Frameworks & Languages including React, Apollo, Relay, JavaScript, Ruby, Java, Elixir and many more.
- 🌎 [Apollo Odyssey](odyssey.apollographql.com/) - Apollo's free interactive learning platform.
- <b><code>&nbsp;&nbsp;&nbsp;934⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [learning-graphql](https://github.com/mugli/learning-graphql)) - An attempt to learn GraphQL.
- 🌎 [GraphQL Roadmap](roadmap.sh/graphql) - Step by step guide to learn GraphQL.
- 🌎 [OWASP GraphQL Security Cheat Sheet](cheatsheetseries.owasp.org/cheatsheets/GraphQL_Cheat_Sheet.html) - Comprehensive guide for securing GraphQL endpoints and preventing vulnerabilities.

<a name="book" />

## Books

- 🌎 [The GraphQL Guide](graphql.guide) - Comprehensive GraphQL learning guide.
- 🌎 [Craft GraphQL APIs in Elixir with Absinthe](pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) - Guide to building GraphQL APIs in Elixir.
- 🌎 [The Road to GraphQL](www.roadtographql.com/) - Full-stack GraphQL tutorial and learning resource.
- 🌎 [Practical GraphQL](leanpub.com/book-graphql) - Practical guide to implementing GraphQL applications.
- 🌎 [Production Ready GraphQL](book.productionreadygraphql.com) - Best practices for production GraphQL systems.
- 🌎 [Full Stack GraphQL Applications](www.manning.com/books/fullstack-graphql-applications) - Complete guide to full-stack GraphQL development.

<a name="video" />

## Videos

- 🌎 [GraphQL: The Documentary](www.youtube.com/watch?v=783ccP__No8) - Documentary on the history and development of GraphQL.
- 🌎 [Zero to GraphQL in 30 Minutes](www.youtube.com/embed/UBGzsb2UkeY) - Quick introduction to GraphQL fundamentals.
- 🌎 [Data fetching for React applications at Facebook](www.youtube.com/watch?v=9sc8Pyc51uU) - Talk on data fetching patterns for React.
- 🌎 [React Native & Relay: Bringing Modern Web Techniques to Mobile](www.youtube.com/watch?v=X6YbAKiLCLU) - Presentation on React Native and Relay integration.
- 🌎 [Exploring GraphQL](www.youtube.com/watch?v=WQLzZf34FJ8) - Overview of GraphQL concepts and capabilities.
- 🌎 [Creating a GraphQL Server](www.youtube.com/watch?v=gY48GW87Feo) - Tutorial on building a GraphQL server.
- 🌎 [GraphQL at The Financial Times](www.youtube.com/watch?v=S0s935RKKB4) - Case study of GraphQL adoption at the Financial Times.
- 🌎 [Relay: An Application Framework For React](www.youtube.com/watch?v=IrgHurBjQbg) - Introduction to the Relay framework for React applications.
- 🌎 [Building and Deploying Relay with Facebook](www.youtube.com/watch?t=643&v=Pxdgu2XIAAg) - Guide to building and deploying Relay applications.
- 🌎 [Introduction to GraphQL](vimeo.com/144817545) - Introductory talk on GraphQL.
- 🌎 [Exploring GraphQL@Scale](www.youtube.com/watch?v=_9RgHXqH8J0) - Strategies for scaling GraphQL APIs.
- 🌎 [What's Next for Phoenix by Chris McCord](www.youtube.com/watch?v=IMUpYOc9z3c&feature=youtu.be) - Future directions of the Phoenix web framework.
- 🌎 [GraphQL with Nick Schrock](www.youtube.com/watch?v=Ed6oJXKt3-M) - Discussion about GraphQL development.
- 🌎 [Build a GraphQL server for Node.js using PostgreSQL/MySQL](www.youtube.com/watch?v=DNPVqK_woRQ) - Tutorial on building GraphQL servers with Node.js.
- 🌎 [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](www.youtube.com/watch?v=PHabPhgRUuU) - Comprehensive GraphQL server tutorial.
- 🌎 [JavaScript Air Episode 023: Transitioning from REST to GraphQL](www.youtube.com/watch?v=ENqDNIp1Nd8) - Podcast episode on REST to GraphQL migration.
- 🌎 [GraphQL Future at react-europe 2016](www.youtube.com/watch?v=ViXL0YQnioU) - Conference talk on the future of GraphQL.
- 🌎 [GraphQL at Facebook at react-europe 2016](www.youtube.com/watch?v=etax3aEe2dA) - Facebook's perspective on GraphQL usage.
- 🌎 [Building native mobile apps with GraphQL at react-europe 2016](www.youtube.com/watch?v=z5rz3saDPJ8) - Mobile development with GraphQL.
- 🌎 [Build a GraphQL Server](www.youtube.com/watch?v=PEcJxkylcRM&list=PLillGF-RfqbYZty73_PHBqKRDnv7ikh68) - Video series on GraphQL server development.
- 🌎 [GraphQL Tutorial](www.youtube.com/watch?v=Y0lDGjwRYKw&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f) - Complete GraphQL tutorial series.
- 🌎 [Five years of GraphQL](www.youtube.com/watch?v=s8meG38iZAM) - Retrospective on five years of GraphQL.
- 🌎 [GraphQL is for Everyone by Moon Highway](moonhighway.teachable.com/p/graphql-is-for-everyone) - Beginner-friendly GraphQL course.

<a name="podcast" />

## Podcasts

- 🌎 [GraphQL.FM](podcasts.google.com/feed/aHR0cHM6Ly9hbmNob3IuZm0vcy8zNjE5NmViMC9wb2RjYXN0L3Jzcw==) - Podcast series on GraphQL development and best practices.

<a name="style-guide" />

## Style Guides

- <b><code>&nbsp;&nbsp;2458⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [Shopify GraphQL Design Tutorial](https://github.com/Shopify/graphql-design-tutorial)) - This tutorial was originally created by Shopify for internal purposes. It's based on lessons learned from creating and evolving production schemas at Shopify over almost 3 years.
- 🌎 [GitLab GraphQL API Style Guide](docs.gitlab.com/ee/development/api_graphql_styleguide.html) - This document outlines the style guide for the GitLab GraphQL API.
- 🌎 [Yelp GraphQL Guidelines](yelp.github.io/graphql-guidelines/) - This repo contains documentation and guidelines for a standardized and mostly reasonable approach to GraphQL (at Yelp).
- 🌎 [Principled GraphQL](principledgraphql.com/) - Apollo's 10 GraphQL Principles, broken out into three categories, in a format inspired by the Twelve Factor App.

<a name="blogs" />

## Blogs

- 🌎 [Official GraphQL blog](graphql.org/blog/) - News and technical articles from the GraphQL project.
- 🌎 [Building Apollo](blog.apollographql.com/) - Product updates and engineering articles from Apollo GraphQL.
- 🌎 [The Guild blog](medium.com/the-guild) - Articles from The Guild about GraphQL tools and practices.
- 🌎 [Production Ready GraphQL blog](productionreadygraphql.com) - Guidance for designing and operating production GraphQL systems.

<a name="security-blog" />

### Blogs - Security

- 🌎 [Escape - The GraphQL Security Blog](escape.tech/blog) - Learn about GraphQL security, performance, testing and building production-ready APIs with the latest tools and best practices of the GraphQL ecosystem.

<a name="post" />

## Posts

### Posts - General

- 🌎 [Using DataLoader to batch GraphQL requests](medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433) - Guide to batching and caching data access with DataLoader.
- 🌎 [Introducing Relay and GraphQL](reactjs.org/blog/2015/02/20/introducing-relay-and-graphql.html) - Original announcement introducing Relay and GraphQL.
- 🌎 [GraphQL Introduction](reactjs.org/blog/2015/05/01/graphql-introduction.html) - Early overview of GraphQL's design and query model.
- 🌎 [Unofficial Relay FAQ](gist.github.com/wincent/598fa75e22bdfa44cf47) - Community answers to common questions about Relay.
- 🌎 [Your First GraphQL Server](medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2) - Tutorial for creating a basic GraphQL server.
- 🌎 [GraphQL Overview - Getting Started with GraphQL and Node.js](blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/) - Introduction to building GraphQL APIs with Node.js.
- 🌎 [4 Reasons you should try out GraphQL](medium.freecodecamp.org/introduction-to-graphql-1d8011b80159) - Introduction to GraphQL and its benefits over REST APIs.
- 🌎 [Moving from REST to GraphQL](medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247) - Account of migrating an API from REST to GraphQL.
- [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/) - Tutorial for implementing a basic GraphQL API.
- 🌎 [Building a GraphQL Server with Node.js and SQL](www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/) - Tutorial for connecting a Node.js GraphQL server to SQL.
- 🌎 [GraphQL at The Financial Times](www.slideshare.net/LondonReact/graph-ql) - Presentation about GraphQL adoption at the Financial Times.
- 🌎 [From REST to GraphQL](jacobwgillespie.com/2015-10-09-from-rest-to-graphql) - Comparison of GraphQL's data model with REST APIs.
- 🌎 [GraphQL: A data query language](graphql.org/blog/graphql-a-query-language/) - Original announcement explaining GraphQL's purpose and design.
- 🌎 [Subscriptions in GraphQL and Relay](graphql.org/blog/subscriptions-in-graphql-and-relay/) - Introduction to real-time GraphQL subscriptions with Relay.
- 🌎 [Relay 101: Building A Hacker News Client](medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6) - Tutorial for building a Hacker News client with Relay.
- 🌎 [GraphQL Schema Reference](graphql.org/learn/schema/) - Official documentation explaining GraphQL schema definition language and shorthand notation.
- 🌎 [The GitHub GraphQL API](githubengineering.com/the-github-graphql-api/) - Introduction to the design of GitHub's GraphQL API.
- 🌎 [GitHub GraphQL API React Example](medium.com/@katopz/github-graphql-api-react-example-eace824d7b61) - Tutorial for consuming GitHub's GraphQL API from React.
- 🌎 [Testing a GraphQL Server using Jest](medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e) - Guide to testing GraphQL queries and mutations with Jest.
- 🌎 [Mock your GraphQL server realistically with faker.js](dev.to/yvonnickfrin/mock-your-graphql-server-realistically-with-faker-js-25oo) - Tutorial for generating realistic mock GraphQL data with Faker.
- 🌎 [Create an infinite loading list with React and GraphQL](dev.to/yvonnickfrin/create-an-infinite-loading-list-with-react-and-graphql-19hh) - Tutorial for cursor-based pagination with React and GraphQL.
- 🌎 [REST vs GraphQL](www.moesif.com/blog/technical/graphql/REST-vs-GraphQL-APIs-the-good-the-bad-the-ugly/) - Comparison of REST and GraphQL API tradeoffs.
- 🌎 [Build a GraphQL API with Siler on top of Swoole](www.swoole.co.uk/article/Build-a-GraphQL-API-on-top-of-Swoole) - Tutorial for building a PHP GraphQL API with Siler and Swoole.
- 🌎 [Fluent GraphQL clients: how to write queries like a boss](hasura.io/blog/fluent-graphql-clients-how-to-write-queries-like-a-boss/) - Survey of fluent GraphQL client libraries across several languages.
- 🌎 [Level up your serverless game with a GraphQL data-as-a-service layer](hasura.io/blog/level-up-your-serverless-game-with-a-graphql-data-as-a-service-layer/) - Guide to using GraphQL as a data layer for serverless applications.
- 🌎 [A deep-dive into Relay, the friendly & opinionated GraphQL client](hasura.io/blog/deep-dive-into-relay-graphql-client/) - Detailed introduction to Relay's architecture and data-fetching model.
- 🌎 [Make Your GraphQL API Easier to Adopt Through Components](hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1) - Guide to packaging GraphQL schemas and resolvers as reusable components.
- 🌎 [GraphQL Subscriptions with Apache Kafka in Ballerina](medium.com/ballerina-techblog/graphql-subscriptions-with-apache-kafka-in-ballerina-b3c296d333cd) - Tutorial for streaming Kafka messages through Ballerina GraphQL subscriptions.

### Posts - Security

- 🌎 [9 GraphQL Security Best Practices](escape.tech/blog/9-graphql-security-best-practices/) - Practical measures for protecting GraphQL APIs from common attacks.
- 🌎 [Discovering GraphQL Endpoints and SQLi Vulnerabilities](medium.com/@localh0t/discovering-graphql-endpoints-and-sqli-vulnerabilities-5d39f26cea2e) - Walkthrough of GraphQL endpoint discovery and SQL injection testing.
- 🌎 [Securing GraphQL API](lab.wallarm.com/securing-graphql-api/) - Overview of common GraphQL security risks and mitigations.
- 🌎 [Security Points to Consider Before Implementing GraphQL](nordicapis.com/security-points-to-consider-before-implementing-graphql/) - Security considerations for teams adopting GraphQL.
- 🌎 [Authorization Patterns in GraphQL](www.osohq.com/post/graphql-authorization) - Comparison of authorization patterns for GraphQL APIs.
- 🌎 [Implementing GraphQL RBAC Authorization: A Practical Guide](www.permit.io/blog/implementing-graphql-authorization) - Guide to implementing role-based access control in GraphQL APIs.
- 🌎 [How to implement viewerCanSee in GraphQL](medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464) - Guide to exposing field visibility through a GraphQL schema.
- 🌎 [Preventing traversal attacks on your GraphQL API](blog.morethancode.dev/preventing-traversal-attacks-in-your-graphql-api/) - Techniques for limiting maliciously deep GraphQL queries.
- 🌎 [Authentication and Authorization for GraphQL APIs](www.moesif.com/blog/technical/api-design/Steps-to-Building-Authentication-and-Authorization-For-GraphQL-APIs/) - Guide to authentication and authorization patterns for GraphQL APIs.
- 🌎 [Undocumented: keeping parts of your GraphQL schema hidden from introspection](www.useanvil.com/blog/engineering/undocumented-directive/) - Guide to hiding selected schema elements from GraphQL introspection.
- 🌎 [How to Test your GraphQL Endpoints](escape.tech/blog/8-most-common-graphql-vulnerabilities/) - Overview of common GraphQL vulnerabilities and how to test for them.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

## Source
<b><code>&nbsp;15124⭐</code></b> <b><code>&nbsp;&nbsp;1247🍴</code></b> [chentsulin/awesome-graphql](https://github.com/chentsulin/awesome-graphql))