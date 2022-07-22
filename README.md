# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome list of GraphQL

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [awesome-graphql ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-graphql-)
  - [Table of Contents](#table-of-contents)
  - [Specifications](#specifications)
  - [Foundations](#foundations)
  - [Communities](#communities)
  - [Meetups](#meetups)
  - [Implementations](#implementations)
    - [JavaScript/TypeScript](#javascripttypescript)
      - [Clients](#clients)
        - [Frontend Framework Integrations](#frontend-framework-integrations)
          - [React](#react)
      - [Servers](#servers)
        - [Databases & ORMs](#databases--orms)
        - [PubSub](#pubsub)
      - [Custom Scalars](#custom-scalars)
      - [Type](#type)
      - [Miscellaneous](#miscellaneous)
      - [JavaScript Examples](#javascript-examples)
      - [TypeScript Examples](#typescript-examples)
    - [Ruby](#ruby)
      - [Ruby Examples](#ruby-examples)
    - [PHP](#php)
      - [PHP Examples](#php-examples)
    - [Python](#python)
      - [Python Examples](#python-examples)
    - [Java](#java)
      - [Custom Scalars](#custom-scalars-1)
      - [Java Examples](#java-examples)
    - [Kotlin](#kotlin)
      - [Kotlin Examples](#kotlin-examples)
    - [C/C++](#cc)
    - [Go](#go)
      - [Go Examples](#go-examples)
    - [Scala](#scala)
      - [Scala Examples](#scala-examples)
    - [.NET](#net)
    - [Elixir](#elixir)
      - [Elixir Examples](#elixir-examples)
    - [Haskell](#haskell)
    - [SQL](#sql)
    - [Lua](#lua)
    - [Elm](#elm)
    - [Clojure](#clojure)
      - [Clojure Examples](#clojure-examples)
    - [Swift](#swift)
    - [OCaml](#ocaml)
    - [Android](#android)
      - [Android Examples](#android-examples)
    - [iOS](#ios)
      - [iOS Examples](#ios-examples)
    - [ClojureScript](#clojurescript)
    - [ReasonML](#reasonml)
    - [Dart](#dart)
    - [Rust](#rust)
      - [Rust Examples](#rust-examples)
    - [D (dlang)](#d-dlang)
    - [R (Rstat)](#r-rstat)
    - [Julia](#julia)
    - [Crystal](#crystal)
  - [Tools](#tools)
    - [Tools - Editors & IDEs & Explorers](#tools---editors--ides--explorers)
    - [Tools - Security](#tools---security)
    - [Tools - Browser Extensions](#tools---browser-extensions)
    - [Tools - Prototyping](#tools---prototyping)
    - [Tools - Docs](#tools---docs)
    - [Tools - Editor Plugins](#tools---editor-plugins)
    - [Tools - Miscellaneous](#tools---miscellaneous)
  - [Databases](#databases)
  - [Services](#services)
    - [CDN](#cdn)
    - [CMS](#cms)
  - [Books](#books)
  - [Videos](#videos)
  - [Podcasts](#podcasts)
  - [Style Guides](#style-guides)
  - [Blogs](#blogs)
    - [Blogs - Security](#blogs---security)
  - [Posts](#posts)
  - [Workshoppers](#workshoppers)
  - [License](#license)

<!-- /MarkdownTOC -->

<a name="spec" />

## Specifications

- <b><code>&nbsp;13817⭐</code></b> <b><code>&nbsp;&nbsp;1141🍴</code></b> [GraphQL](https://github.com/graphql/graphql-spec) - Working draft of the specification for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [GraphQL over HTTP](https://github.com/graphql/graphql-over-http) - Working draft of "GraphQL over HTTP" specification.
- 🌎 [GraphQL Relay](https://relay.dev/docs/guides/graphql-server-specification/) - Relay-compliant GraphQL server specification.
- <b><code>&nbsp;&nbsp;&nbsp;385⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [OpenCRUD](https://github.com/opencrud/opencrud) - OpenCRUD is a GraphQL CRUD API specification for databases.
- 🌎 [Apollo Federation](https://www.apollographql.com/docs/federation/federation-spec/) - Apollo Federation specification

<a name="foundation" />

## Foundations

- 🌎 [GraphQL Foundation](https://graphql.org/foundation/) - GraphQL Foundation under the Linux Foundation

<a name="community" />

## Communities

- 🌎 [Slack](https://graphql.slack.com/messages/general/) - Share and help people on the chat. Get your invite 🌎 [here](https://graphql-slack.herokuapp.com/).
- 🌎 [Discord](http://join.reactiflux.com/) - Join `#help-graphql` on the Reactiflux Discord server.
- 🌎 [Facebook](https://www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing.
- 🌎 [Twitter](https://twitter.com/search?q=%23GraphQL) - Use the hashtag `#graphql`.
- 🌎 [StackOverflow](https://stackoverflow.com/questions/tagged/graphql) - Questions and answers. Use the tag `graphql`.
- <b><code>&nbsp;&nbsp;3935⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;299🍴</code></b> [GraphQL APIs](https://github.com/APIs-guru/graphql-apis) - A collective list of public GraphQL APIs.
- 🌎 [/r/GraphQL](https://old.reddit.com/r/graphql/) - A Subreddit for interesting and informative GraphQL content and discussions.
- 🌎 [GraphQL Jobs](https://graphql.jobs) - A list of GraphQL-based jobs in startups all over the world.
- 🌎 [Codever](https://www.codever.land/search?q=graphql) - Dev bookmarks. Use the tag 🌎 [graphql](https://www.codever.land/bookmarks/t/graphql).
- 🌎 [Everything GraphQL - Curated by The Guild](https://discord.gg/xud7bH9) - A Discord server dedicated to GraphQL.
- 🌎 [GraphQL Weekly](https://www.graphqlweekly.com/) - A weekly newsletter highlighting resources and news from the GraphQL community.
- 🌎 [GraphQL Custom Scalars](https://www.graphqlscalars.com/) - Search graphql custom scalars across Javascript, Java, PHP, Go, Scala, etc....
- 🌎 [Escape - The GraphQL Security Blog](https://blog.escape.tech) - Learn about GraphQL security, performance, testing and building production-ready APIs with the latest tools and best practices of the GraphQL ecosystem.

<a name="meetup" />

## Meetups

- 🌎 [Relay Meetup](https://relaymeetup.com/) - A global, online meetup on Relay, the GraphQL client.
- 🌎 [Amsterdam](https://www.meetup.com/Amsterdam-GraphQL-Meetup/)
- 🌎 [Bangalore](https://www.meetup.com/graphql-bangalore/)
- 🌎 [Berlin](https://www.meetup.com/graphql-berlin/)
- 🌎 [Buenos Aires](https://www.meetup.com/es-ES/GraphQL-BA/)
- 🌎 [Copenhagen](https://www.meetup.com/Copenhagen-GraphQL-Meetup-Group/)
- 🌎 [Dallas-Fort Worth](https://www.meetup.com/DFW-GraphQL-Meetup/)
- 🌎 [Hamburg](https://www.meetup.com/GraphQL-Hamburg/)
- 🌎 [London](https://www.meetup.com/GraphQL-London/)
- 🌎 [Melbourne](https://www.meetup.com/GraphQL-Melbourne/)
- 🌎 [Montreal](https://www.meetup.com/GraphQL-Montreal/)
- 🌎 [Munich](https://www.meetup.com/GraphQL-Munich/)
- 🌎 [New York City](https://www.meetup.com/GraphQL-NYC/)
- 🌎 [Portland](https://www.meetup.com/GraphQLPDX/)
- 🌎 [San Francisco](https://www.meetup.com/GraphQL-SF/)
- 🌎 [Seattle](https://www.meetup.com/Seattle-GraphQL/)
- 🌎 [Sydney](https://www.meetup.com/GraphQL-Sydney/)
- 🌎 [Tel Aviv](https://www.meetup.com/GraphQL-TLV/)
- 🌎 [Wrocław](https://www.meetup.com/GraphQL-Wroclaw/)
- 🌎 [Singapore](https://www.meetup.com/GraphQL-SG/)
- 🌎 [Zurich](https://www.meetup.com/GraphQL-Zurich/)

<a name="impl" />

## Implementations

<a name="js" />

### JavaScript/TypeScript

- <b><code>&nbsp;18912⭐</code></b> <b><code>&nbsp;&nbsp;2018🍴</code></b> [graphql-js](https://github.com/graphql/graphql-js) - A reference implementation of GraphQL for JavaScript.
- <b><code>&nbsp;&nbsp;&nbsp;861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [graphql-jit](https://github.com/zalando-incubator/graphql-jit) - GraphQL execution using a JIT compiler.

#### Clients

- <b><code>&nbsp;17915⭐</code></b> <b><code>&nbsp;&nbsp;2429🍴</code></b> [apollo-client](https://github.com/apollographql/apollo-client) - A fully-featured, production ready caching GraphQL client for every UI framework and GraphQL server.
- <b><code>&nbsp;&nbsp;4692⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;247🍴</code></b> [graphql-request](https://github.com/prisma-labs/graphql-request) - A minimal GraphQL client for Node and browsers.
- 🌎 [typescript-graphql-request](https://graphql-code-generator.com/docs/plugins/typescript-graphql-request) - Use GraphQL Request as a fully typed SDK.
- <b><code>&nbsp;&nbsp;1626⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [graphql-zeus](https://github.com/graphql-editor/graphql-zeus) - GraphQL Zeus creates autocomplete client library for `JavaScript` or `TypeScript` which provides autocompletion for strongly typed queries.
- <b><code>&nbsp;&nbsp;3124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [graphqurl](https://github.com/hasura/graphqurl) - curl for GraphQL with autocomplete, subscriptions and GraphiQL. Also a dead-simple universal javascript GraphQL client.
- <b><code>&nbsp;&nbsp;8810⭐</code></b> <b><code>&nbsp;&nbsp;1927🍴</code></b> [aws-amplify](https://github.com/aws-amplify/amplify-js) - A client library developed by Amazon for caching, analytics and more that includes a way to fetch GraphQL queries.

##### Frontend Framework Integrations

- <b><code>&nbsp;&nbsp;5693⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;479🍴</code></b> [vue-apollo](https://github.com/vuejs/vue-apollo) - Apollo/GraphQL integration for VueJS.
- <b><code>&nbsp;&nbsp;1372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;288🍴</code></b> [apollo-angular](https://github.com/kamilkisiela/apollo-angular) - A fully-featured, production ready caching GraphQL client for Angular and every GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;837⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [svelte-apollo](https://github.com/timhall/svelte-apollo) - Svelte integration for Apollo GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;279⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [ember-apollo-client](https://github.com/ember-graphql/ember-apollo-client) - An ember-cli addon for Apollo Client and GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [apollo-elements](https://github.com/apollo-elements/apollo-elements) - GraphQL web components that work in any frontend framework.
- <b><code>&nbsp;&nbsp;&nbsp;205⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [sveltekit-kitql](https://github.com/jycouet/kitql) - A set of tools, helping you building efficient apps in a fast way with SvelteKit and GraphQL.

###### React

- 🌎 [react-apollo](https://www.apollographql.com/docs/react/) - The core @apollo/client library provides built-in integration with React.
- <b><code>&nbsp;17147⭐</code></b> <b><code>&nbsp;&nbsp;1721🍴</code></b> [relay](https://github.com/facebook/relay) - Relay is a JavaScript framework for building data-driven React applications.
- <b><code>&nbsp;&nbsp;7331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;333🍴</code></b> [urql](https://github.com/FormidableLabs/urql) - A simple caching GraphQL client for React.
- <b><code>&nbsp;&nbsp;1710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [graphql-hooks](https://github.com/nearform/graphql-hooks) - Minimal hooks-first GraphQL client with caching and server-side rendering support.
- <b><code>&nbsp;&nbsp;3614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [gqless](https://github.com/samdenty/gqless) - A GraphQL client without queries ✨
- <b><code>&nbsp;&nbsp;&nbsp;649⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [mst-gql](https://github.com/mobxjs/mst-gql) - Bindings for mobx-state-tree and GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [micro-graphql-react](https://github.com/arackaf/micro-graphql-react) - A lightweight utility for adding GraphQL to React. components. Includes simple caching and uses GET requests that could additionally be cached through a service-worker.

#### Servers

- <b><code>&nbsp;12771⭐</code></b> <b><code>&nbsp;&nbsp;1964🍴</code></b> [apollo-server](https://github.com/apollographql/apollo-server) - Spec-compliant and production ready JavaScript GraphQL server that lets you develop in a schema-first way. Built for Express, Connect, Hapi, Koa, and more.
- <b><code>&nbsp;&nbsp;6328⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;591🍴</code></b> [express-graphql](https://github.com/graphql/express-graphql) - GraphQL Express Middleware.
- <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql) - Create a GraphQL HTTP server with Hapi.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [hapi-plugin-graphiql](https://github.com/rse/hapi-plugin-graphiql) - HAPI plugin for GraphiQL integration.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [graphql-api-koa](https://github.com/jaydenseric/graphql-api-koa) - GraphQL Koa middleware that implements GraphQL.js from scratch and supports native ESM.
- <b><code>&nbsp;&nbsp;&nbsp;823⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [koa-graphql](https://github.com/chentsulin/koa-graphql) - GraphQL Koa Middleware.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-koa-scripts](https://github.com/ryanhs/graphql-koa-scripts) - GraphQL Koa 1 file simplified. usefull for quick test
- <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [gql](https://github.com/deno-libs/gql) - Universal GraphQL HTTP middleware for Deno.
- <b><code>&nbsp;&nbsp;1781⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [mercurius](https://github.com/mercurius-js/mercurius) - GraphQL plugin for Fastify.
- <b><code>&nbsp;&nbsp;7057⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;446🍴</code></b> [graphql-yoga](https://github.com/prisma-labs/graphql-yoga) - Fully-featured GraphQL Server with focus on easy setup, performance and great developer experience.
- <b><code>&nbsp;&nbsp;&nbsp;119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [graphitejs](https://github.com/graphitejs/server) - Framework NodeJS for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;744⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [graphql-helix](https://github.com/contrawork/graphql-helix) - A highly evolved GraphQL HTTP Server.

##### Databases & ORMs

- <b><code>&nbsp;&nbsp;1883⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) - Sequelize helpers for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) - Some help defining GraphQL schema around BookshelfJS models.
- <b><code>&nbsp;&nbsp;2495⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [join-monster](https://github.com/acarl005/join-monster) - A GraphQL-to-SQL query execution layer for batch data fetching.

##### PubSub

- 🌎 [graphql-ably-pubsub](https://www.npmjs.com/package/graphql-ably-pubsub) - Ably PubSub implementation for GraphQL to publish mutation updates and subscribe to the result through a subscription query.

#### Custom Scalars

- <b><code>&nbsp;&nbsp;1526⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [graphql-scalars](https://github.com/Urigo/graphql-scalars) - A library of custom GraphQL Scalars for creating precise type-safe GraphQL schemas.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [graphql-tools-types](https://github.com/rse/graphql-tools-types) - Custom GraphQL types for use with GraphQL-Tools (Void, Int, Float, String, Date, UUID, JSON).

#### Type

- <b><code>&nbsp;&nbsp;7323⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;621🍴</code></b> [type-graphql](https://github.com/19majkel94/type-graphql) - Create GraphQL schema and resolvers with TypeScript, using classes and decorators!
- <b><code>&nbsp;&nbsp;3036⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;269🍴</code></b> [graphql-nexus](https://github.com/graphql-nexus/nexus) - Code-First, Type-Safe, GraphQL Schema Construction.
- <b><code>&nbsp;&nbsp;8986⭐</code></b> <b><code>&nbsp;&nbsp;1034🍴</code></b> [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator): GraphQL code generator with flexible support for custom plugins and templates like TypeScript (frontend and backend), React Hooks, resolvers signatures and more.
- <b><code>&nbsp;&nbsp;&nbsp;875⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [pothos](https://github.com/hayes/pothos) - Pothos is a plugin based GraphQL schema builder for typescript. It makes building graphql schemas in typescript easy, fast and enjoyable.

#### Miscellaneous

- <b><code>&nbsp;&nbsp;4869⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;733🍴</code></b> [graphql-tools](https://github.com/apollographql/graphql-tools) - Tool library for building and maintaining GraphQL-JS servers.
- <b><code>&nbsp;&nbsp;2138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [graphql-tag](https://github.com/apollographql/graphql-tag) - A JavaScript template literal tag that parses GraphQL queries.
- <b><code>&nbsp;&nbsp;1139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [graphql-compose](https://github.com/graphql-compose/graphql-compose) - Tool which allows you to construct flexible graphql schema from different data sources via plugins.
- <b><code>&nbsp;&nbsp;1182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [graphql-modules](https://github.com/Urigo/graphql-modules) - Separate GraphQL server into smaller, reusable parts by modules or features.
- <b><code>&nbsp;&nbsp;3299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [graphql-shield](https://github.com/maticzav/graphql-shield) - A library that helps creating a permission layer for a graphql api.
- <b><code>&nbsp;&nbsp;&nbsp;433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [graphql-let](https://github.com/piglovesyou/graphql-let) - A webpack loader to import type-protected codegen results directly from GraphQL documents
- <b><code>&nbsp;&nbsp;1037⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [graphql-config](https://github.com/kamilkisiela/graphql-config) - One configuration for all your GraphQL tools (supported by most tools, editors & IDEs).
- <b><code>&nbsp;&nbsp;1878⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [graphql-cli](https://github.com/urigo/graphql-cli) - A command line tool for common GraphQL development workflows.
- <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [graphql-toolkit](https://github.com/ardatan/graphql-toolkit) - A set of utils for faster development of GraphQL tools (Schema and documents loading, Schema merging and more).
- <b><code>&nbsp;&nbsp;2502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [graphql-mesh](https://github.com/urigo/graphql-mesh) - use GraphQL query language to access data in remote APIs that don't run GraphQL (and also ones that do run GraphQL).
- <b><code>&nbsp;&nbsp;&nbsp;892⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [sofa](https://github.com/Urigo/sofa) - Generate REST API from your GraphQL API.
- <b><code>&nbsp;&nbsp;&nbsp;387⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [graphback](https://github.com/aerogear/graphback) - Framework and CLI to add a GraphQLCRUD API layer to a GraphQL server using data models.
- <b><code>&nbsp;&nbsp;1035⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [graphql-middleware](https://github.com/maticzav/graphql-middleware) - Split up your GraphQL resolvers in middleware functions.
- <b><code>&nbsp;&nbsp;1475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [graphql-relay-js](https://github.com/graphql/graphql-relay-js) - A library to help construct a graphql-js server supporting react-relay.
- <b><code>&nbsp;&nbsp;&nbsp;189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [graphql-normalizr](https://github.com/monojack/graphql-normalizr) - Normalize GraphQL responses for persisting in the client cache/state.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) - Babel plugin that compile GraphQL tagged template strings.
- <b><code>&nbsp;&nbsp;1165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) - An ESLint plugin that checks your GraphQL strings against a schema.
- <b><code>&nbsp;&nbsp;1177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [graphql-ws](https://github.com/enisdenjo/graphql-ws) - Coherent, zero-dependency, lazy, simple, GraphQL over WebSocket Protocol compliant server and client.
- <b><code>&nbsp;&nbsp;&nbsp;340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [graphql-live-query](https://github.com/n1ru4l/graphql-live-query) - Realtime GraphQL Live Queries with JavaScript.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [GraphVinci](https://github.com/Comcast/graphvinci) - An interactive schema visualizer for GraphQL APIs.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [supertest-graphql](https://github.com/alexstrat/supertest-graphql) - Extends <b><code>&nbsp;12235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;753🍴</code></b> [supertest](https://github.com/visionmedia/supertest) to easily test a GraphQL endpoint
- <b><code>&nbsp;&nbsp;1333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [schemathesis](https://github.com/schemathesis/schemathesis) - Runs arbitrary queries matching a GraphQL schema to find server errors.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [microfiber](https://github.com/anvilco/graphql-introspection-tools) - Query and manipulate GraphQL introspection query results in useful ways.

<a name="js-example" />

#### JavaScript Examples

- <b><code>&nbsp;21290⭐</code></b> <b><code>&nbsp;&nbsp;4116🍴</code></b> [React Starter Kit](https://github.com/kriasoft/react-starter-kit) - front-end starter kit using React, Relay, GraphQL, and JAM stack architecture.
- <b><code>&nbsp;&nbsp;&nbsp;987⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;264🍴</code></b> [SWAPI GraphQL Wrapper](https://github.com/graphql/swapi-graphql) - A GraphQL schema and server wrapping SWAPI.
- <b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Relay TodoMVC](https://github.com/taion/relay-todomvc) - Relay TodoMVC with routing.
- 🌎 [Apollo Client documentation](https://www.apollographql.com/react/) - Documentation and example for building GraphQL apps using apollo client.
- 🌎 [Apollo Server tools documentation](https://www.apollographql.com/docs/apollo-server/) - Documentation, tutorial and examples for building GraphQL server and connecting to SQL, MongoDB and REST endpoints.
- <b><code>&nbsp;14028⭐</code></b> <b><code>&nbsp;&nbsp;2642🍴</code></b> [F8 App 2017](https://github.com/fbsamples/f8app) - Source code of the official F8 app of 2016, powered by React Native and other Facebook open source projects.
- <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Apollo React example for Github GraphQL API](https://github.com/katopz/react-apollo-graphql-github-example) - Usage Examples Apollo React for Github GraphQL API with create-react-app.
- <b><code>&nbsp;89964⭐</code></b> <b><code>&nbsp;19368🍴</code></b> [Next.js TypeScript and GraphQL Example](https://github.com/zeit/next.js/tree/canary/examples/with-typescript-graphql) - A type-protected GraphQL example on Next.js running 🌎 [graphql-codegen](https://graphql-code-generator.com/) under the hood
- 🌎 [GraphQL StackBlitz Starter](https://stackblitz.com/fork/graphql) – A live, editable demo spinning up in about 2 seconds and running in a browser.
- <b><code>&nbsp;&nbsp;&nbsp;726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [NAPERG](https://github.com/alan345/naperg) - Fullstack Boilerplate GraphQL. Made with React & Prisma + authentication & roles.
- 🌎 [VulcanJS](http://vulcanjs.org) - The full-stack React+GraphQL framework
- <b><code>&nbsp;&nbsp;2159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [RAN Toolkit](https://github.com/sly777/ran) - Production-ready toolkit/boilerplate with support for GraphQL, SSR, Hot-reload, CSS-in-JS, caching, and more.

<a name="ts-example" />

#### TypeScript Examples

- <b><code>&nbsp;&nbsp;3567⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;554🍴</code></b> [Node.js API Starter](https://github.com/kriasoft/nodejs-api-starter) - Yarn v2 based monorepo template (code-first GraphQL API, PostgreSQL, PnP, Zero-install, serverless).
- <b><code>&nbsp;&nbsp;&nbsp;210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Next.js Apollo TypeScript Starter](https://github.com/borisowsky/nextjs-apollo-ts-starter) - Next.js starter project focused on developer experience.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [GraphQL Starter](https://github.com/cerino-ligutom/GraphQL-Starter) - A boilerplate for TypeScript + Node Express + Apollo GraphQL APIs.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Mocked Managed Federation](https://github.com/setchy/apollo-server-3-mocked-federation) - A mocked managed federation supgraph using Apollo Server 3.x

<a name="rb" />

### Ruby

- <b><code>&nbsp;&nbsp;5094⭐</code></b> <b><code>&nbsp;&nbsp;1240🍴</code></b> [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of Facebook's GraphQL.
- <b><code>&nbsp;&nbsp;1083⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [graphql-client](https://github.com/github/graphql-client) - A Ruby library for declaring, composing and executing GraphQL queries.
- <b><code>&nbsp;&nbsp;1304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [graphql-batch](https://github.com/Shopify/graphql-batch) - A query batching executor for the graphql gem.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [graphql-auth](https://github.com/o2web/graphql-auth) - A JWT auth wrapper working with devise.
- <b><code>&nbsp;&nbsp;&nbsp;790⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [agoo](https://github.com/ohler55/agoo) - Ruby web server that implements Facebook's GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [GQLi](https://github.com/contentful-labs/gqli.rb) - A GraphQL client and DSL. Allowing to write queries in native Ruby.

<a name="rb-example" />

#### Ruby Examples

- <b><code>&nbsp;&nbsp;&nbsp;222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo) - Use graphql-ruby to expose a Rails app.
- <b><code>&nbsp;&nbsp;&nbsp;274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [github-graphql-rails-example](https://github.com/github/github-graphql-rails-example) - Example Rails app using GitHub's GraphQL API.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [relay-on-rails](https://github.com/nethsix/relay-on-rails) - Barebones starter kit for Relay application with Rails GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [relay-rails-blog](https://github.com/gauravtiwari/relay-rails-blog) - A graphql, relay and standard rails application powered demo weblog.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [to_eat_app](https://github.com/jcdavison/to_eat_app) - A sample graphql/rails/relay application with a related 3-part article series.
- <b><code>&nbsp;&nbsp;&nbsp;790⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [agoo-demo](https://github.com/ohler55/agoo/tree/develop/example/graphql) - Use of the Agoo server to demonstrate a simple GraphQL application.
- <b><code>&nbsp;&nbsp;&nbsp;269⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [rails-devise-graphql](https://github.com/zauberware/rails-devise-graphql) - A rails 6 boilerplate with devise, graphql & JWT auth.

<a name="php" />

### PHP

- <b><code>&nbsp;&nbsp;4344⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;527🍴</code></b> [graphql-php](https://github.com/webonyx/graphql-php) - A PHP port of GraphQL reference implementation.
- <b><code>&nbsp;&nbsp;&nbsp;269⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [graphql-relay-php](https://github.com/ivome/graphql-relay-php) - Relay helpers for webonyx/graphql-php implementation of GraphQL.
- <b><code>&nbsp;&nbsp;2931⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;377🍴</code></b> [lighthouse](https://github.com/nuwave/lighthouse) - A PHP package that allows to serve a GraphQL endpoint from your Laravel application.
- <b><code>&nbsp;&nbsp;1858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [graphql-laravel](https://github.com/rebing/graphql-laravel) - Laravel wrapper for Facebook's GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;703⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [overblog/graphql-bundle](https://github.com/overblog/GraphQLBundle) - This bundle provides tools to build a complete GraphQL server in your Symfony App. Supports react-relay.
- <b><code>&nbsp;&nbsp;3263⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;412🍴</code></b> [wp-graphql](https://github.com/wp-graphql/wp-graphql) - GraphQL API for WordPress.
- <b><code>&nbsp;&nbsp;&nbsp;497⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [graphqlite](https://github.com/thecodingmachine/graphqlite) - Framework agnostic library that allows you to write GraphQL server by annotating your PHP classes.
- <b><code>&nbsp;&nbsp;1124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [siler](https://github.com/leocavalcante/siler) - Plain-old functions providing a declarative API for GraphQL servers with Subscriptions support.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-request-builder](https://github.com/dpauli/php-graphql-request-builder) - Builds request payload in GraphQL structure.

<a name="php-example" />

#### PHP Examples

- <b><code>&nbsp;&nbsp;1124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [siler-graphgl](https://github.com/leocavalcante/siler/tree/main/examples/graphql) - An example GraphQL server written with Siler.

<a name="py" />

### Python

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [graphql-parser](https://github.com/tryolabs/graphql-parser) - GraphQL parser for Python.
- <b><code>&nbsp;&nbsp;&nbsp;436⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [graphql-core](https://github.com/graphql-python/graphql-core) - GraphQL implementation for Python based on GraphQL.js v0.6.0 reference implementation
- <b><code>&nbsp;&nbsp;&nbsp;436⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [graphql-core-next](https://github.com/graphql-python/graphql-core-next) - Latest GraphQL implementation based on GraphQL.js v14.5.6 reference implementation
- <b><code>&nbsp;&nbsp;&nbsp;141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py) - A library to help construct a graphql-py server supporting react-relay.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python) - A python wrapper around libgraphqlparser.
- <b><code>&nbsp;&nbsp;7309⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;787🍴</code></b> [graphene](https://github.com/graphql-python/graphene) - A package for creating GraphQL schemas/types in a Pythonic easy way.
- <b><code>&nbsp;&nbsp;&nbsp;119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [graphene-gae](https://github.com/graphql-python/graphene-gae) - Adds GraphQL support to Google AppEngine (GAE).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [django-graphiql](https://github.com/GraphQL-python-archive/django-graphiql) - Integrate GraphiQL easily into your Django project.
- <b><code>&nbsp;&nbsp;1282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [flask-graphql](https://github.com/graphql-python/flask-graphql) - Adds GraphQL support to your Flask application.
- <b><code>&nbsp;&nbsp;&nbsp;147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [python-graphql-client](https://github.com/prisma/python-graphql-client) - Simple GraphQL client for Python 2.7+
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [python-graphjoiner](https://github.com/healx/python-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise.
- <b><code>&nbsp;&nbsp;3898⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;689🍴</code></b> [graphene-django](https://github.com/graphql-python/graphene-django) - A Django integration for Graphene.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Flask-GraphQL-Auth](https://github.com/callsign-viper/Flask-GraphQL-Auth) - An authentication library for Flask inspired from flask-jwt-extended.
- <b><code>&nbsp;&nbsp;&nbsp;824⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [tartiflette](https://github.com/dailymotion/tartiflette) - GraphQL Implementation, SDL First, for python 3.6+ / asyncio.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [tartiflette-aiohttp](https://github.com/dailymotion/tartiflette-aiohttp) - Wrapper of Tartiflette to expose GraphQL API over HTTP based on aiohttp / 3.6+ / asyncio, 🌎 [official tutorial available on tartiflette.io](https://tartiflette.io/docs/tutorial/getting-started).
- <b><code>&nbsp;&nbsp;1795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [Ariadne](https://github.com/mirumee/ariadne) - library for implementing GraphQL servers using schema-first approach. Asynchronous query execution, batteries included for ASGI, WSGI and popular webframeworks, 🌎 [fully documented](https://ariadnegraphql.org).
- <b><code>&nbsp;&nbsp;&nbsp;287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [django-graphql-auth](https://github.com/PedroBern/django-graphql-auth) - Django registration and authentication with GraphQL.
- <b><code>&nbsp;&nbsp;2433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;285🍴</code></b> [strawberry](https://github.com/strawberry-graphql/strawberry) - A new GraphQL library for Python.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [turms](https://github.com/jhnnsrs/turms) - A pythonic graphql codegenerator built around graphql-core and pydantic
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [rath](https://github.com/jhnnsrs/rath) - An apollo like graphql client with async and sync interface

<a name="py-example" />

#### Python Examples

- <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [swapi-graphene](https://github.com/graphql-python/swapi-graphene) - A GraphQL schema and server using 🌎 [Graphene](https://graphene-python.org).

<a name="java" />

### Java

- <b><code>&nbsp;&nbsp;5548⭐</code></b> <b><code>&nbsp;&nbsp;1029🍴</code></b> [graphql-java](https://github.com/graphql-java/graphql-java) - GraphQL Java implementation.
- <b><code>&nbsp;&nbsp;2367⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [DGS Framework](https://github.com/Netflix/dgs-framework) - A GraphQL server framework for Spring Boot, developed by Netflix.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [graphql-java-generator](https://github.com/graphql-java-generator) - A <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Maven plugin](https://github.com/graphql-java-generator/graphql-maven-plugin-project) and a <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Gradle plugin](https://github.com/graphql-java-generator/graphql-gradle-plugin-project) that can generate both the **Client** and the **Server** (POJOs and utility classes). The server part is based on graphql-java, and hides all its boilerplate codes.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [gaphql-java-type-generator](https://github.com/graphql-java/graphql-java-type-generator) - Auto-generates types for use with GraphQL Java
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [schemagen-graphql](https://github.com/bpatters/schemagen-graphql) - Schema generation and execution package that turns POJO's into a GraphQL Java queryable set of objects. Enables exposing any service as a GraphQL service using Annotations.
- <b><code>&nbsp;&nbsp;&nbsp;364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [graphql-java-annotations](https://github.com/Enigmatis/graphql-java-annotations) - Provides annotations-based syntax for schema definition with GraphQL Java.
- <b><code>&nbsp;&nbsp;&nbsp;770⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [graphql-java-tools](https://github.com/graphql-java-kickstart/graphql-java-tools) - Schema-first graphql-java convenience library that makes it easy to bring your own implementations as data resolvers. Inspired by <b><code>&nbsp;&nbsp;4869⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;733🍴</code></b> [graphql-tools](https://github.com/apollographql/graphql-tools) for JS.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [graphql-java-codegen-maven-plugin](https://github.com/kobylynskyi/graphql-java-codegen-maven-plugin) - Schema-first maven plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools. Inspired by <b><code>&nbsp;14627⭐</code></b> <b><code>&nbsp;&nbsp;5832🍴</code></b> [swagger-codegen-maven-plugin](https://github.com/swagger-api/swagger-codegen/tree/master/modules/swagger-codegen-maven-plugin).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [graphql-java-codegen-gradle-plugin](https://github.com/kobylynskyi/graphql-java-codegen-gradle-plugin) - Schema-first gradle plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools. Inspired by <b><code>&nbsp;&nbsp;&nbsp;252⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [gradle-swagger-generator-plugin](https://github.com/int128/gradle-swagger-generator-plugin).
- <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [graphql-java-servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet) - A framework-agnostic java servlet for exposing graphql-java query endpoints with GET, POST, and multipart uploads.
- <b><code>&nbsp;&nbsp;1291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent 🌎 [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Java example](#example-java) below.
- <b><code>&nbsp;&nbsp;&nbsp;131⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [spring-graphql-common](https://github.com/oembedler/spring-graphql-common) - Spring Framework GraphQL Library.
- <b><code>&nbsp;&nbsp;1392⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [graphql-spring-boot](https://github.com/graphql-java-kickstart/graphql-spring-boot) - GraphQL and GraphiQL Spring Framework Boot Starters.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [vertx-graphql-service-discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - Asynchronous GraphQL service discovery and querying for your microservices.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [vertx-dataloader](https://github.com/engagingspaces/vertx-dataloader) - Port of Facebook DataLoader for efficient, asynchronous batching and caching in clustered GraphQL environments.
- <b><code>&nbsp;&nbsp;&nbsp;979⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [graphql-spqr](https://github.com/leangen/GraphQL-SPQR) - Java 8+ API for rapid development of GraphQL services.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Light Java GraphQL](https://github.com/networknt/light-graphql-4j): A lightweight, fast microservices framework with all cross-cutting concerns addressed and ready to plug in GraphQL schema.
- 🌎 [Elide](https://elide.io): A Java library that can expose a JPA annotated data model as a GraphQL service over any relational database.
- <b><code>&nbsp;&nbsp;&nbsp;186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [federation-jvm](https://github.com/apollographql/federation-jvm) - Apollo Federation on the JVM.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [graphql-java-extended-validation](https://github.com/graphql-java/graphql-java-extended-validation) - Provides extended validation of fields and field arguments for graphql-java.

#### Custom Scalars

- <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [graphql-java-datetime](https://github.com/donbeave/graphql-java-datetime) - GraphQL ISO Date is a set of RFC 3339 compliant date/time scalar types to be used with graphql-java.
- <b><code>&nbsp;&nbsp;&nbsp;160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [graphql-java-extended-scalars](https://github.com/graphql-java/graphql-java-extended-scalars) - Extended scalars for graphql-java.

<a name="java-example" />

#### Java Examples

- <b><code>&nbsp;&nbsp;&nbsp;141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [light-java-graphql examples](https://github.com/networknt/light-example-4j/tree/master/graphql) - Examples of Light Java GraphQL and tutorials.
- <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [graphql-spqr-samples](https://github.com/leangen/graphql-spqr-samples) - An example GraphQL server written with Spring MVC and GraphQL-SPQR.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-graphql-app) - A simple application, both client and server, demonstrating the Manifold GraphQL library.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [graphql-java-kickstart_samples](https://github.com/graphql-java-kickstart/samples) - Samples for using the GraphQL Java Kickstart projects.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [graphql-java-kickstart-federation-example](https://github.com/setchy/graphql-java-kickstart-federation-example) - A GraphQL Java Kickstart federation example.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [dgs-federation-example](https://github.com/Netflix/dgs-federation-example) - A Netflix DGS federation example.

<a name="kotlin" />

### Kotlin

- <b><code>&nbsp;&nbsp;1461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;290🍴</code></b> [graphql-kotlin](https://github.com/ExpediaGroup/graphql-kotlin) - GraphQL Kotlin implementation.
- <b><code>&nbsp;&nbsp;1291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent 🌎 [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Kotlin example](#example-kotlin) below.
- <b><code>&nbsp;&nbsp;&nbsp;239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [KGraphQL](https://github.com/aPureBase/KGraphQL): Pure Kotlin implementation to setup a GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Kobby](https://github.com/ermadmi78/kobby) - Codegen plugin of 🌎 [Kotlin DSL Client](https://blog.kotlin-academy.com/how-to-generate-kotlin-dsl-client-by-graphql-schema-707fd0c55284) by GraphQL schema. The generated DSL supports execution of complex GraphQL queries, mutation and subscriptions in Kotlin with syntax similar to native GraphQL syntax.

<a name="kotlin-example" />

#### Kotlin Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-kotlin-app) - A simple GraphQL application, both client and server, demonstrating the Manifold GraphQL library with Kotlin.

<a name="c" />

### C/C++

- <b><code>&nbsp;&nbsp;&nbsp;986⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [libgraphqlparser](https://github.com/graphql/libgraphqlparser) - A GraphQL query parser in C++ with C and C++ APIs.
- <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [agoo-c](https://github.com/ohler55/agoo-c) - A high performance GraphQL server written in C. <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [benchmarks](https://github.com/the-benchmarker/graphql-benchmarks)
- <b><code>&nbsp;&nbsp;&nbsp;258⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [cppgraphqlgen](https://github.com/Microsoft/cppgraphqlgen) - C++ GraphQL schema service generator.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [CaffQL](https://github.com/caffeinetv/CaffQL) - Generates C++ client types and request/response serialization from a GraphQL introspection query.

<a name="go" />

### Go

- <b><code>&nbsp;&nbsp;8660⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;769🍴</code></b> [graphql](https://github.com/graphql-go/graphql) - An implementation of GraphQL for Go follows graphql-js
- <b><code>&nbsp;&nbsp;4179⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;471🍴</code></b> [graphql-go](https://github.com/graph-gophers/graphql-go) - GraphQL server with a focus on ease of use.
- <b><code>&nbsp;&nbsp;7786⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;891🍴</code></b> [gqlgen](https://github.com/99designs/gqlgen) - Go generate based graphql server library.
- <b><code>&nbsp;&nbsp;&nbsp;394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [graphql-relay-go](https://github.com/graphql-go/relay) - A Go/Golang library to help construct a server supporting react-relay.
- <b><code>&nbsp;&nbsp;2273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [graphjin](https://github.com/dosco/graphjin): Build APIs in 5 minutes with GraphQL. An instant GraphQL to SQL compiler.

<a name="go-example" />

#### Go Examples

- <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit) - Barebones starting point for a Relay application with Golang GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go) - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [go-graphql-subscription-example](https://github.com/ccamel/go-graphql-subscription-example) - A GraphQL schema and server that demonstrates GraphQL <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [subscriptions](https://github.com/apollographql/subscriptions-transport-ws/blob/v0.9.4/PROTOCOL.md) (over Websocket) to consume 🌎 [Apache Kafka](https://kafka.apache.org/) messages.

<a name="scala" />

### Scala

- <b><code>&nbsp;&nbsp;1897⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [sangria](https://github.com/sangria-graphql/sangria) - Scala GraphQL server implementation.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [sangria-relay](https://github.com/sangria-graphql/sangria-relay) - Sangria Relay Support.
- <b><code>&nbsp;&nbsp;&nbsp;793⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [caliban](https://github.com/ghostdogpr/caliban) - Caliban is a purely functional library for creating GraphQL backends in Scala.

<a name="scala-example" />

#### Scala Examples

- <b><code>&nbsp;&nbsp;&nbsp;244⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) - An example GraphQL server written with akka-http and 🌎 [sangria](https://sangria-graphql.github.io/)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [sangria-playground](https://github.com/sangria-graphql/sangria-playground) - An example of GraphQL server written with Play and sangria.

<a name="dotnet" />

### .NET

- <b><code>&nbsp;&nbsp;5267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;866🍴</code></b> [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET.
- <b><code>&nbsp;&nbsp;&nbsp;882⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [graphql-net](https://github.com/ckimes89/graphql-net) - GraphQL to IQueryable for .NET.
- <b><code>&nbsp;&nbsp;3635⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;524🍴</code></b> [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) - GraphQL server for .Net Core and .NET Framework.
- <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Snowflaqe](https://github.com/Zaid-Ajaj/Snowflaqe) - Type-safe GraphQL code generator for F# and <b><code>&nbsp;&nbsp;2437⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;267🍴</code></b> [Fable](https://github.com/fable-compiler/Fable)

<a name="elixir" />

### Elixir

- <b><code>&nbsp;&nbsp;3974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;473🍴</code></b> [absinthe-graphql](https://github.com/absinthe-graphql/absinthe) - Fully Featured Elixir GraphQL Library.
- <b><code>&nbsp;&nbsp;&nbsp;856⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [graphql-elixir](https://github.com/graphql-elixir/graphql) - GraphQL Elixir. (No longer maintained)
- <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [plug_graphql](https://github.com/graphql-elixir/plug_graphql) - Plug integration for GraphQL Elixir.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [graphql_relay](https://github.com/graphql-elixir/graphql_relay) - Relay helpers for GraphQL Elixir.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - Elixir bindings for <b><code>&nbsp;&nbsp;&nbsp;986⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [libgraphqlparser](https://github.com/graphql/libgraphqlparser)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql](https://github.com/asonge/graphql) - Elixir GraphQL parser.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [plot](https://github.com/peburrows/plot) - GraphQL parser and resolver for Elixir.

<a name="elixir-example" />

#### Elixir Examples

- <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [hello_graphql_phoenix](https://github.com/graphql-elixir/hello_graphql_phoenix) - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix

<a name="haskell" />

### Haskell

- <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [graphql-haskell](https://github.com/jdnavarro/graphql-haskell) - GraphQL AST and parser for Haskell.

<a name="sql" />

### SQL

- <b><code>&nbsp;&nbsp;1084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL) - GraphQL for Postgres.
- <b><code>&nbsp;&nbsp;&nbsp;581⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [sql-to-graphql](https://github.com/rexxars/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure.
- <b><code>&nbsp;11428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;534🍴</code></b> [PostGraphile](https://github.com/graphile/postgraphile) - Lightning-fast GraphQL APIs for PostgreSQL: highly customisable; extensible via plugins; realtime.
- <b><code>&nbsp;27475⭐</code></b> <b><code>&nbsp;&nbsp;2354🍴</code></b> [Hasura](https://github.com/hasura/graphql-engine) - Hasura gives Instant Realtime GraphQL APIs over PostgreSQL. Works with an existing database too.
- 🌎 [subZero](https://subzero.cloud/) - GraphQL & REST API for your database

<a name="lua" />

### Lua

- <b><code>&nbsp;&nbsp;&nbsp;170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [graphql-lua](https://github.com/bjornbytes/graphql-lua) - GraphQL for Lua.

<a name="elm" />

### Elm

- <b><code>&nbsp;&nbsp;&nbsp;733⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [elm-graphql](https://github.com/dillonkearns/elm-graphql) - GraphQL for Elm.

<a name="clojure" />

### Clojure

- <b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [graphql-clj](https://github.com/tendant/graphql-clj) - A Clojure library designed to provide GraphQL implementation.
- <b><code>&nbsp;&nbsp;1699⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [Lacinia](https://github.com/walmartlabs/lacinia) - GraphQL implementation in pure Clojure.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [graphql-query](https://github.com/district0x/graphql-query) - Clojure(Script) GraphQL query generation.

<a name="clojure-example" />

#### Clojure Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Clojure Game Geek](https://github.com/walmartlabs/clojure-game-geek) - Example code for the Lacinia GraphQL framework tutorial.

<a name="swift" />

### Swift

- <b><code>&nbsp;&nbsp;&nbsp;865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [GraphQL](https://github.com/GraphQLSwift/GraphQL) - The Swift implementation for GraphQL.

<a name="ocaml" />

### OCaml

- <b><code>&nbsp;&nbsp;&nbsp;611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [ocaml-graphql-server](https://github.com/andreas/ocaml-graphql-server) - GraphQL servers in OCaml.

<a name="android" />

### Android

- <b><code>&nbsp;&nbsp;3196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;592🍴</code></b> [apollo-android](https://github.com/apollographql/apollo-android) - 📟 A strongly-typed, caching GraphQL client for Android, written in Java.
- <b><code>&nbsp;&nbsp;1291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent 🌎 [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Java example](#example-java) below.

<a name="android-example" />

#### Android Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [apollo-frontpage-android-app](https://github.com/rnitame/apollo-frontpage-android-app) - 📄 Apollo "hello world" app, for Android.

<a name="ios" />

### iOS

- <b><code>&nbsp;&nbsp;3390⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;612🍴</code></b> [apollo-ios](https://github.com/apollographql/apollo-ios) - 📱 A strongly-typed, caching GraphQL client for iOS, written in Swift.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [ApolloDeveloperKit](https://github.com/manicmaniac/ApolloDeveloperKit) - Apollo Client Devtools bridge for [Apollo iOS].
- <b><code>&nbsp;&nbsp;&nbsp;457⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Graphaello](https://github.com/nerdsupremacist/Graphaello) - Type Safe GraphQL directly from SwiftUI.
- 🌎 [GQLite iOS SDK](https://graphqlite.com/sdk-ios) - GQLite iOS SDK is a toolkit to work with GraphQL servers easily.

<a name="ios-example" />

#### iOS Examples

- <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [frontpage-ios-app](https://github.com/apollographql/frontpage-ios-app) - 📄 Apollo "hello world" app, for iOS.

<a name="clojurescript" />

### ClojureScript

- <b><code>&nbsp;&nbsp;&nbsp;422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [re-graph](https://github.com/oliyh/re-graph) - A GraphQL client for ClojureScript with bindings for re-frame applications.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [graphql-query](https://github.com/district0x/graphql-query) - Clojure(Script) GraphQL query generation.

<a name="reasonml" />

### ReasonML

- <b><code>&nbsp;&nbsp;&nbsp;557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [reason-apollo](https://github.com/apollographql/reason-apollo) - ReasonML binding for Apollo Client.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [ReasonQL](https://github.com/sainthkh/reasonql) - Type-safe and simple GraphQL Client for ReasonML developers.
- <b><code>&nbsp;&nbsp;&nbsp;231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [reason-urql](https://github.com/FormidableLabs/reason-urql) - ReasonML binding for urql Client.

<a name="dart" />

### Dart

- <b><code>&nbsp;&nbsp;2981⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;519🍴</code></b> [graphql-flutter](https://github.com/zino-app/graphql-flutter) - A GraphQL client for Flutter.
- <b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [Artemis](https://github.com/comigor/artemis) - A GraphQL type and query generator for Dart/Flutter.

<a name="rust" />

### Rust

- <b><code>&nbsp;&nbsp;2331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;293🍴</code></b> [async-graphql](https://github.com/async-graphql/async-graphql) - High-performance server-side library that supports all GraphQL specifications.
- <b><code>&nbsp;&nbsp;4623⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;382🍴</code></b> [juniper](https://github.com/graphql-rust/juniper) - GraphQL server library for Rust.
- <b><code>&nbsp;&nbsp;&nbsp;843⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [graphql-client](https://github.com/tomhoule/graphql-client) - GraphQL client library for Rust with WebAssembly (wasm) support.
- <b><code>&nbsp;&nbsp;&nbsp;271⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [graphql-parser](https://github.com/graphql-rust/graphql-parser) - A parser, formatter and AST for the GraphQL query and schema definition language for Rust.

<a name="rust-example" />

#### Rust Examples

- <b><code>&nbsp;&nbsp;4623⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;382🍴</code></b> [Warp GraphQL Juniper Demo](https://github.com/graphql-rust/juniper/tree/master/examples/warp_async)

<a name="d" />

### D (dlang)

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [graphqld](https://github.com/burner/graphqld) - GraphQL server library for D.

<a name="r" />

### R (Rstat)

- <b><code>&nbsp;&nbsp;&nbsp;128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [ghql](https://github.com/ropensci/ghql) - General purpose GraphQL R client.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [graphql](https://github.com/ropensci/graphql) - Bindings to the 'libgraphqlparser' C++ library. Parses GraphQL syntax and exports the AST in JSON format.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [gqlr](https://github.com/schloerke/gqlr) - R GraphQL Implementation.

<a name="julia" />

### Julia

- <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Diana.jl](https://github.com/codeneomatrix/Diana.jl) - A Julia GraphQL client/server implementation.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [GraphQLClient.jl](https://github.com/DeloitteDigitalAPAC/GraphQLClient.jl) - A Julia GraphQL client for seamless integration with a server.

<a name="crystal" />

### Crystal

- <b><code>&nbsp;&nbsp;&nbsp;104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [graphql](https://github.com/graphql-crystal/graphql) - GraphQL server library.
- <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - library inspired by <b><code>&nbsp;&nbsp;5094⭐</code></b> <b><code>&nbsp;&nbsp;1240🍴</code></b> [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) & <b><code>&nbsp;&nbsp;&nbsp;249⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [go-graphql](https://github.com/playlyfe/go-graphql) & <b><code>&nbsp;&nbsp;&nbsp;189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [graphql-parser](https://github.com/graphql-dotnet/parser).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [crystal-gql](https://github.com/itsezc/crystal-gql) - GraphQL client shard inspired by Apollo client.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql.cr](https://github.com/garymardell/graphql.cr) - GraphQL shard.

<a name="tools" />

## Tools

### Tools - Editors & IDEs & Explorers

- <b><code>&nbsp;13805⭐</code></b> <b><code>&nbsp;&nbsp;1507🍴</code></b> [GraphiQL](https://github.com/graphql/graphiql) - An in-browser IDE for exploring GraphQL.
- <b><code>&nbsp;&nbsp;5648⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [GraphQL Editor](https://github.com/graphql-editor/graphql-editor) - Visual Editor & GraphQL IDE.
- <b><code>&nbsp;&nbsp;6829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;448🍴</code></b> [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager) - Represent any GraphQL API as an interactive graph.
- <b><code>&nbsp;&nbsp;4315⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [Altair GraphQL Client](https://github.com/altair-graphql/altair) - A beautiful feature-rich GraphQL Client for all platforms.
- 🌎 [Insomnia](https://insomnia.rest/) - A full-featured API client with first-party GraphQL query editor.
- 🌎 [Postman](https://learning.postman.com/docs/sending-requests/supported-api-frameworks/graphql/) - An HTTP Client that supports editing GraphQL queries.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Escape GraphMan](https://github.com/Escape-Technologies/graphman) - Generate a complete Postman collection from a GraphQL endpoint.
- 🌎 [Apollo Sandbox](https://sandbox.apollo.dev/) - The quickest way to navigate and test your GraphQL endpoints.
- <b><code>&nbsp;&nbsp;&nbsp;685⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [GraphQL Birdseye](https://github.com/Novvum/graphql-birdseye) – View any GraphQL schema as a dynamic and interactive graph.
- 🌎 [AST Explorer](https://astexplorer.net/) - Select "GraphQL" at the top, explore the GraphQL AST and highlight different parts by clicking in the query.
- 🌎 [Firecamp - GraphQL Playground](https://firecamp.io/graphql) - The fastest collaborative GraphQL playground.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [CraftQL](https://github.com/yamafaktory/craftql) - A CLI tool to visualize GraphQL schemas and to output a graph data structure as a graphviz .dot format.
- <b><code>&nbsp;&nbsp;&nbsp;422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [gqt](https://github.com/eerimoq/gqt) - Build and execute GraphQL queries in the terminal.

<a name="tool-security" />

### Tools - Security

- 🌎 [Escape - The GraphQL Security Scanner](https://graphql.security/) - One-click security scan of your GraphQL endpoints. Free, no login required.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Escape Graphinder - GraphQL Subdomain Enumeration](https://github.com/Escape-Technologies/graphinder) – Blazing fast GraphQL endpoints finder using subdomain enumeration, scripts analysis and bruteforce.
- 🌎 [StackHawk - GraphQL Vulnerability Scanner](https://www.stackhawk.com/blog/automated-graphql-security-testing) - 🌎 [StackHawk](https://www.stackhawk.com)
- 🌎 [Tinfoil Security - GraphQL Security Scanner](https://www.tinfoilsecurity.com/blog/graphql-security-scanning) - 🌎 [Tinfoil Security](https://www.tinfoilsecurity.com/solutions/api-scanner)
- <b><code>&nbsp;&nbsp;&nbsp;994⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [InQL Scanner](https://github.com/doyensec/inql) - A Burp Extension for GraphQL Security Testing
- 🌎 [GraphQL Raider](https://portswigger.net/bappstore/4841f0d78a554ca381c65b26d48207e6) 🌎 [BurpSuite](https://portswigger.net/burp)
- 🌎 [WAF for graphQL](https://lab.wallarm.com/api-security-solution/) - Web Application Firewall for graphQL APIs
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [GraphQL Intruder](https://github.com/davinerd/gql_intruder) - Plugin based python script to perform GraphQL vulnerability assessment.

### Tools - Browser Extensions

- <b><code>&nbsp;&nbsp;1376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [Apollo Client Developer Tools](https://github.com/apollographql/apollo-client-devtools) - GraphQL debugging tools for Apollo Client in the Chrome developer console
- <b><code>&nbsp;&nbsp;&nbsp;318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [GraphQL Network](https://github.com/Ghirro/graphql-network) - A chrome dev-tools extension for debugging GraphQL network requests.

### Tools - Prototyping

- <b><code>&nbsp;&nbsp;2490⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [GraphQL Faker](https://github.com/APIs-guru/graphql-faker) - 🎲 Mock or extend your GraphQL API with faked data. No coding required.
- 🌎 [GraphQL Designer](http://graphqldesigner.com/) - A developer's web-app tool to rapidly prototype a full stack CRUD implementation of GraphQL with React.

### Tools - Docs

- <b><code>&nbsp;&nbsp;1443⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [graphdoc](https://github.com/2fd/graphdoc) - Static page generator for documenting GraphQL Schema.
- <b><code>&nbsp;&nbsp;&nbsp;156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [gqldoc](https://github.com/Code-Hex/gqldoc) - The easiest way to make API documents for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;656⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [spectaql](https://github.com/anvilco/spectaql) - Autogenerate static GraphQL API documentation

### Tools - Editor Plugins

- 🌎 [Apollo GraphQL VSCode Extension](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) - Rich editor support for GraphQL client and server development that seamlessly integrates with the Apollo platform
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/) - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;442⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [vim-graphql](https://github.com/jparise/vim-graphql) - A Vim plugin that provides GraphQL file detection and syntax highlighting.
- 🌎 [Apollo Workbench](https://marketplace.visualstudio.com/items?itemName=apollographql.apollo-workbench) - Tooling to help you develop and mock federated schemas using Apollo Federation.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [graphql-autocomplete](https://github.com/orionsoft/atom-graphql-autocomplete) - Autocomplete and lint from a GraphQL endpoint in Atom.

### Tools - Miscellaneous

- <b><code>&nbsp;&nbsp;8986⭐</code></b> <b><code>&nbsp;&nbsp;1034🍴</code></b> [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator) - GraphQL code generator based on schema and documents.
- <b><code>&nbsp;&nbsp;&nbsp;885⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [swagger-to-graphql](https://github.com/yarax/swagger-to-graphql) - GraphQL types builder based on REST API described in Swagger. Allows to migrate to GraphQL from REST for 5 minutes
- <b><code>&nbsp;&nbsp;&nbsp;608⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) - A language service plugin complete and validate GraphQL query in TypeScript template strings.
- <b><code>&nbsp;&nbsp;&nbsp;467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [apollo-tracing](https://github.com/apollographql/apollo-tracing) - GraphQL extension that enables you to easily get resolver-level performance information as part of a GraphQL response.
- <b><code>&nbsp;&nbsp;1748⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [json-graphql-server](https://github.com/marmelab/json-graphql-server) - Get a full fake GraphQL API with zero coding in less than 30 seconds, based on a JSON data file.
- <b><code>&nbsp;24340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;859🍴</code></b> [Prisma](https://github.com/prisma/prisma) - Turn your database into a GraphQL API. Prisma lets you design your data model and have a production ready GraphQL API online in minutes.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Typetta](https://github.com/twinlogix/typetta) - Node.js ORM written in TypeScript for type lovers. Typetta is the perfect ORM for the GraphQL + NodeJS + Typescript stack.
- <b><code>&nbsp;&nbsp;&nbsp;660⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [tuql](https://github.com/bradleyboy/tuql) - Automatically create a GraphQL server from any sqlite database.
- <b><code>&nbsp;15487⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;858🍴</code></b> [Bit](https://github.com/teambit/bit) - Organize GraphQL API as components to be consumed with NPM or modified from any project, 🌎 [example-explanation](https://hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)).
- <b><code>&nbsp;&nbsp;1327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [openapi-to-graphql](https://github.com/ibm/openapi-to-graphql) - Take any OpenAPI Specification (OAS) or swagger and create a GraphQL interface - Two minute video and resources 🌎 [here](https://developer.ibm.com/open/projects/openapi-to-graphql/)
- 🌎 [Retool](https://retool.com/) – Internal tools builder on top of your GraphQL APIs + GraphQL IDE with a schema explorer.
- <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [dataloader-codegen](https://github.com/Yelp/dataloader-codegen) - An opinionated JavaScript library for automatically generating predictable, type safe DataLoaders over a set of resources (e.g. HTTP endpoints).
- <b><code>&nbsp;&nbsp;1367⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [raphql-inspector](https://github.com/kamilkisiela/graphql-inspector): alidate schema, get schema change notifications, validate operations, find breaking changes, look for similar types, schema coverage.
- <b><code>&nbsp;&nbsp;7733⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;476🍴</code></b> [amplication](https://github.com/amplication/amplication): Amplication is an open‑source low code development tool. It builds database applications with REST API and GraphQL for CRUD with relations, sorting, filtering, pagination.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Blendbase](https://github.com/blendbase/blendbase): Single open-source GraphQL API to connect CRMs to your SaaS. Query any customer CRM system (Salesforce, Hubspot and more) with a single API query from your SaaS app.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [microfiber](https://github.com/anvilco/graphql-introspection-tools) - Query and manipulate GraphQL introspection query results in useful ways.

<a name="databases" />

## Databases

- 🌎 [Dgraph](https://dgraph.io/) - Scalable, distributed, low latency, high throughput Graph database with GraphQL as the query language
- 🌎 [EdgeDB](https://edgedb.com/) - The next generation object-relational database with native GraphQL support.
- 🌎 [FaunaDB](https://fauna.com) - Relational NoSQL database with 🌎 [GraphQL schema import.](https://fauna.com/blog/getting-started-with-graphql-part-1-importing-and-querying-your-schema) Supports joins, indexes, and multi-region ACID transactions with serverless pay-per-use pricing.
- 🌎 [ArangoDB](https://arangodb.com/) - Native multi-model database with 🌎 [GraphQL integration](https://www.arangodb.com/docs/3.4/foxx-reference-modules-graph-ql.html) via the built-in 🌎 [Foxx Microservices Framework](https://www.arangodb.com/docs/stable/foxx.html).
- <b><code>&nbsp;&nbsp;2573⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Weaviate](https://github.com/semi-technologies/weaviate) - Weaviate is a cloud-native, modular, real-time vector search engine with a 🌎 [GraphQL interface](https://www.semi.technology/developers/weaviate/current/graphql-references/) built to scale your machine learning models.
- 🌎 [Back4App](https://www.back4app.com/graphql-database) - Build a Scalable Database with GraphQL API in minutes.
- 🌎 [LunaSec](https://www.lunasec.io/) - Key-Value Database for encrypting/tokenizing sensitive data with 🌎 [GraphQL support](https://www.lunasec.io/docs/pages/getting-started/dedicated-tokenizer/graphql/) to authorize requests. - <b><code>&nbsp;&nbsp;1105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Source Code](https://github.com/lunasec-io/lunasec)

<a name="services" />

## Services

- 🌎 [AWS AppSync](https://aws.amazon.com/appsync/) - Scalable managed GraphQL service with subscriptions for building real-time and offline-first apps
- 🌎 [FakeQL](https://fakeql.com/) - GraphQL API mocking as a service ... because GraphQL API mocking should be easy!
- 🌎 [Moesif API Analytics](https://www.moesif.com/features/graphql-analytics) - A GraphQL analaytics and monitoring service to find functional and performance issues.
- 🌎 [Booster framework](https://booster.cloud/) - An open-source framework that makes you _completely_ forget about infrastructure and allows you to focus exclusively on your business logic. It autogenerates a GraphQL API for your models, supporting mutations, queries, and subscriptions.
- 🌎 [Hypi](https://hypi.io/) - Low-code, scalable, serverless backend as a service. Your GraphQL & REST over GraphQL backend in minutes.
- 🌎 [Nhost](https://nhost.io/) - Open source Firebase alternative with GraphQL
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Saleor](https://github.com/mirumee/saleor/) - GraphQL-first headless e-commerce platform.
- 🌎 [Stargate](https://stargate.io/docs/stargate/1.0/quickstart/quick_start-graphql.html) - Open source data gateway currently supporting Apache Cassandra&reg; and DataStax Enterprise.

### CDN

- 🌎 [GraphCDN](https://graphcdn.io/) - GraphQL CDN for caching GraphQL APIs.

### CMS

- 🌎 [DatoCMS](https://www.datocms.com/) - CDN-based GraphQL based Headless Content Management System.
- 🌎 [GraphCMS](https://graphcms.com/) - GraphQL based Headless Content Management System.
- 🌎 [Cosmic](https://www.cosmicjs.com/) - GraphQL-powered Headless CMS and API toolkit.

<a name="book" />

## Books

- 🌎 [The GraphQL Guide](https://graphql.guide) by John Resig and Loren Sands-Ramshaw
- 🌎 [Learning GraphQL](https://www.amazon.com/dp/1492030716) by Eve Porcello and Alex Banks
- 🌎 [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) by Bruce Williams and Ben Wilson
- 🌎 [The Road to GraphQL](https://www.roadtographql.com/)
- 🌎 [Fullstack GraphQL](https://www.graphql.college/fullstack-graphql) by Julian Mayorga
- 🌎 [Learning GraphQL and Relay](https://www.packtpub.com/web-development/learning-graphql-and-relay) by Samer Buna
- 🌎 [Practical GraphQL](https://leanpub.com/book-graphql) by Daniel Schmitz
- 🌎 [Production Ready GraphQL](https://book.productionreadygraphql.com) by Marc-André Giroux
- 🌎 [Full Stack GraphQL Applications](https://www.manning.com/books/fullstack-graphql-applications) by William Lyon

<a name="video" />

## Videos

- 🌎 [GraphQL: The Documentary](https://www.youtube.com/watch?v=783ccP__No8)
- 🌎 [Zero to GraphQL in 30 Minutes](https://www.youtube.com/embed/UBGzsb2UkeY)
- 🌎 [Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)
- 🌎 [React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU)
- 🌎 [Exploring GraphQL](https://www.youtube.com/watch?v=WQLzZf34FJ8)
- 🌎 [Creating a GraphQL Server](https://www.youtube.com/watch?v=gY48GW87Feo)
- 🌎 [GraphQL at The Financial Times](https://www.youtube.com/watch?v=S0s935RKKB4)
- 🌎 [Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg)
- 🌎 [Building and Deploying Relay with Facebook](https://www.youtube.com/watch?t=643&v=Pxdgu2XIAAg)
- 🌎 [Introduction to GraphQL](https://vimeo.com/144817545)
- 🌎 [Exploring GraphQL@Scale](https://www.youtube.com/watch?v=_9RgHXqH8J0)
- 🌎 [What's Next for Phoenix by Chris McCord](https://www.youtube.com/watch?v=IMUpYOc9z3c&feature=youtu.be)
- 🌎 [GraphQL with Nick Schrock](https://www.youtube.com/watch?v=Ed6oJXKt3-M)
- 🌎 [Build a GraphQL server for Node.js using PostgreSQL/MySQL](https://www.youtube.com/watch?v=DNPVqK_woRQ)
- 🌎 [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](https://www.youtube.com/watch?v=PHabPhgRUuU)
- 🌎 [JavaScript Air Episode 023: Transitioning from REST to GraphQL](https://www.youtube.com/watch?v=ENqDNIp1Nd8)
- 🌎 [GraphQL Future at react-europe 2016](https://www.youtube.com/watch?v=ViXL0YQnioU)
- 🌎 [GraphQL at Facebook at react-europe 2016](https://www.youtube.com/watch?v=etax3aEe2dA)
- 🌎 [Building native mobile apps with GraphQL at react-europe 2016](https://www.youtube.com/watch?v=z5rz3saDPJ8)
- 🌎 [Build a GraphQL Server](https://www.youtube.com/watch?v=PEcJxkylcRM&list=PLillGF-RfqbYZty73_PHBqKRDnv7ikh68)
- 🌎 [GraphQL Tutorial](https://www.youtube.com/watch?v=Y0lDGjwRYKw&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f)
- 🌎 [Five years of GraphQL](https://www.youtube.com/watch?v=s8meG38iZAM)

<a name="podcast" />

## Podcasts

- 🌎 [GraphQL.FM](https://podcasts.google.com/feed/aHR0cHM6Ly9hbmNob3IuZm0vcy8zNjE5NmViMC9wb2RjYXN0L3Jzcw==) by Marc-Andre Giroux and Tony Ghita.

<a name="style-guide" />

## Style Guides

- <b><code>&nbsp;&nbsp;2124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;173🍴</code></b> [Shopify GraphQL Design Tutorial](https://github.com/Shopify/graphql-design-tutorial) - This tutorial was originally created by Shopify for internal purposes. It's based on lessons learned from creating and evolving production schemas at Shopify over almost 3 years.
- 🌎 [GitLab GraphQL API Style Guide](https://docs.gitlab.com/ee/development/api_graphql_styleguide.html) - This document outlines the style guide for the GitLab GraphQL API.
- 🌎 [Yelp GraphQL Guidelines](https://yelp.github.io/graphql-guidelines/) - This repo contains documentation and guidelines for a standardized and mostly reasonable approach to GraphQL (at Yelp).
- 🌎 [Principled GraphQL](https://principledgraphql.com/) - Apollo's 10 GraphQL Principles, broken out into three categories, in a format inspired by the Twelve Factor App.

<a name="blogs" />

## Blogs

- 🌎 [Official GraphQL blog](https://graphql.org/blog/)
- 🌎 [Building Apollo](https://blog.apollographql.com/)
- 🌎 [The Guild blog](https://medium.com/the-guild)
- 🌎 [Production Ready GraphQL blog](https://productionreadygraphql.com)

<a name="security-blog" />

### Blogs - Security

- 🌎 [9 GraphQL Security Best Practices](https://blog.escape.tech/9-graphql-security-best-practices/)
- 🌎 [Discovering GraphQL Endpoints and SQLi Vulnerabilities](https://medium.com/@localh0t/discovering-graphql-endpoints-and-sqli-vulnerabilities-5d39f26cea2e)
- 🌎 [Securing GraphQL API](https://lab.wallarm.com/securing-graphql-api/)
- 🌎 [How to secure a GraphQL API (The Complete Vulnerability Checklist)](https://leapgraph.com/graphql-api-security)
- 🌎 [Security Points to Consider Before Implementing GraphQL](https://nordicapis.com/security-points-to-consider-before-implementing-graphql/)

<a name="post" />

## Posts

- 🌎 [Using DataLoader to batch GraphQL requests](https://medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433)
- 🌎 [Introducing Relay and GraphQL](https://reactjs.org/blog/2015/02/20/introducing-relay-and-graphql.html)
- 🌎 [GraphQL Introduction](https://reactjs.org/blog/2015/05/01/graphql-introduction.html)
- 🌎 [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)
- 🌎 [Your First GraphQL Server](https://medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2)
- 🌎 [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
- 🌎 [4 Reasons you should try out GraphQL](https://medium.freecodecamp.org/introduction-to-graphql-1d8011b80159)
- 🌎 [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
- 🌎 [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
- 🌎 [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
- 🌎 [GraphQL at The Financial Times](https://www.slideshare.net/LondonReact/graph-ql)
- 🌎 [From REST to GraphQL](https://jacobwgillespie.com/2015-10-09-from-rest-to-graphql)
- 🌎 [GraphQL: A data query language](https://graphql.org/blog/graphql-a-query-language/)
- 🌎 [Subscriptions in GraphQL and Relay](https://graphql.org/blog/subscriptions-in-graphql-and-relay/)
- 🌎 [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6)
- 🌎 [GraphQL Shorthand Notation Cheatsheet](https://wehavefaces.net/graphql-shorthand-notation-cheatsheet-17cd715861b6)
- 🌎 [The GitHub GraphQL API](https://githubengineering.com/the-github-graphql-api/)
- 🌎 [Github GraphQL API React Example](https://medium.com/@katopz/github-graphql-api-react-example-eace824d7b61)
- 🌎 [Testing a GraphQL Server using Jest](https://medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e)
- 🌎 [How to implement viewerCanSee in GraphQL](https://medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464)
- 🌎 [Preventing traversal attacks on your GraphQL API](https://blog.morethancode.dev/preventing-traversal-attacks-in-your-graphql-api/)
- 🌎 [Mock your GraphQL server realistically with faker.js](https://dev.to/yvonnickfrin/mock-your-graphql-server-realistically-with-faker-js-25oo)
- 🌎 [Create an infinite loading list with React and GraphQL](https://dev.to/yvonnickfrin/create-an-infinite-loading-list-with-react-and-graphql-19hh)
- 🌎 [REST vs GraphQL](https://www.moesif.com/blog/technical/graphql/REST-vs-GraphQL-APIs-the-good-the-bad-the-ugly/)
- 🌎 [Authentication and Authorization for GraphQL APIs](https://www.moesif.com/blog/technical/api-design/Steps-to-Building-Authentication-and-Authorization-For-GraphQL-APIs/)
- 🌎 [Build a GraphQL API with Siler on top of Swoole](https://www.swoole.co.uk/article/Build-a-GraphQL-API-on-top-of-Swoole)
- 🌎 [Fluent GraphQL clients: how to write queries like a boss](https://hasura.io/blog/fluent-graphql-clients-how-to-write-queries-like-a-boss/)
- 🌎 [Level up your serverless game with a GraphQL data-as-a-service layer](https://hasura.io/blog/level-up-your-serverless-game-with-a-graphql-data-as-a-service-layer/)
- 🌎 [A deep-dive into Relay, the friendly & opinionated GraphQL client](https://hasura.io/blog/deep-dive-into-relay-graphql-client/)
- 🌎 [make your graphql api easier to adopt through components](https://hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)
- 🌎 [Undocumented: keeping parts of your GraphQL schema hidden from introspection](https://www.useanvil.com/blog/engineering/undocumented-directive/)

<a name="workshopper" />

## Workshoppers

- 🌎 [How to GraphQL](https://www.howtographql.com) - Fullstack Tutorial Website with Tracks for all Major Frameworks & Languages including React, Apollo, Relay, JavaScript, Ruby, Java, Elixir and many more.
- 🌎 [Apollo Odyssey](https://odyssey.apollographql.com/) - Apollo's free interactive learning platform.
- <b><code>&nbsp;&nbsp;&nbsp;920⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [learning-graphql](https://github.com/mugli/learning-graphql) - An attempt to learn GraphQL.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Chen-Tsu Lin](https://github.com/chentsulin) has waived all copyright and related or neighboring rights to this work.
