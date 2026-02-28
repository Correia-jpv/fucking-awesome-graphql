# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/chentsulin/awesome-graphql/awesome_bot.yml?logo=githubactions&label=Awesome%20Bot)

> Awesome list of GraphQL

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [awesome-graphql  ](#awesome-graphql--)
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
        - [Databases \& ORMs](#databases--orms)
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
      - [.NET Examples](#net-examples)
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
    - [Ballerina](#ballerina)
      - [Ballerina Samples](#ballerina-samples)
  - [Tools](#tools)
    - [Tools - Editors \& IDEs \& Explorers](#tools---editors--ides--explorers)
    - [Tools - Testing, Prototyping \& Mocking](#tools---testing-prototyping--mocking)
    - [Tools - Security](#tools---security)
    - [Tools - Browser Extensions](#tools---browser-extensions)
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
  - [Tutorials](#tutorials)
  - [License](#license)

<!-- /MarkdownTOC -->

<a name="spec" />

## Specifications

- <b><code>&nbsp;14754⭐</code></b> <b><code>&nbsp;&nbsp;1152🍴</code></b> [GraphQL](https://github.com/graphql/graphql-spec)) - Working draft of the specification for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [GraphQL over HTTP](https://github.com/graphql/graphql-over-http)) - Working draft of "GraphQL over HTTP" specification.
- 🌎 [GraphQL Relay](relay.dev/docs/guides/graphql-server-specification/) - Relay-compliant GraphQL server specification.
- <b><code>&nbsp;&nbsp;&nbsp;388⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [OpenCRUD](https://github.com/opencrud/opencrud)) - OpenCRUD is a GraphQL CRUD API specification for databases.
- 🌎 [Apollo Federation](www.apollographql.com/docs/federation/federation-spec/) - Apollo Federation specification
- 🌎 [GraphQXL](gabotechs.github.io/graphqxl/) - GraphQXL is an extension of the GraphQL language with some additional features that help creating big and scalable server-side schemas.
- 🌎 [GraphQL Scalars](www.graphql-scalars.com/) - hosts community defined custom Scalar specifications for use with @specifiedBy.

<a name="foundation" />

## Foundations

- 🌎 [GraphQL Foundation](graphql.org/foundation/) - GraphQL Foundation under the Linux Foundation

<a name="community" />

## Communities

- 🌎 [Discord - GraphQL](discord.graphql.org/) - Official GraphQL.org discord channel.
- 🌎 [GraphQL Weekly](www.graphqlweekly.com/) - A weekly newsletter highlighting resources and news from the GraphQL community.
- 🌎 [Apollo GraphQL Community](community.apollographql.com/) - Connect with other developers and share knowledge about every part of the Apollo GraphQL platform.
- [Discord - Reactiflux](http://join.reactiflux.com/) - Join `#help-graphql` on the Reactiflux Discord server.
- 🌎 [Facebook](www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing.
- 🌎 [X](x.com/search?q=%23GraphQL) - Use the hashtag `#graphql`.
- 🌎 [StackOverflow](stackoverflow.com/questions/tagged/graphql) - Questions and answers. Use the tag `graphql`.
- <b><code>&nbsp;&nbsp;4646⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;344🍴</code></b> [GraphQL APIs](https://github.com/APIs-guru/graphql-apis)) - A collective list of public GraphQL APIs.
- 🌎 [/r/GraphQL](www.reddit.com/r/graphql/) - A Subreddit for interesting and informative GraphQL content and discussions.

<a name="meetup" />

## Meetups

- 🌎 [Relay Meetup](relaymeetup.com/) - A global, online meetup on Relay, the GraphQL client.
- 🌎 [Amsterdam](www.meetup.com/Amsterdam-GraphQL-Meetup/)
- 🌎 [Bangalore](www.meetup.com/graphql-bangalore/)
- 🌎 [Berlin](www.meetup.com/graphql-berlin/)
- 🌎 [Buenos Aires](www.meetup.com/es-ES/GraphQL-BA/)
- 🌎 [Copenhagen](www.meetup.com/Copenhagen-GraphQL-Meetup-Group/)
- 🌎 [Dallas-Fort Worth](www.meetup.com/DFW-GraphQL-Meetup/)
- 🌎 [Hamburg](www.meetup.com/GraphQL-Hamburg/)
- 🌎 [London](www.meetup.com/GraphQL-London/)
- 🌎 [Melbourne](www.meetup.com/GraphQL-Melbourne/)
- 🌎 [Munich](www.meetup.com/GraphQL-Munich/)
- 🌎 [New York City](www.meetup.com/GraphQL-NYC/)
- 🌎 [San Francisco](www.meetup.com/GraphQL-SF/)
- 🌎 [Seattle](www.meetup.com/Seattle-GraphQL/)
- 🌎 [Sydney](www.meetup.com/GraphQL-Sydney/)
- 🌎 [Tel Aviv](www.meetup.com/GraphQL-TLV/)
- 🌎 [Wrocław](www.meetup.com/GraphQL-Wroclaw/)
- 🌎 [Singapore](www.meetup.com/GraphQL-SG/)
- 🌎 [Zurich](www.meetup.com/GraphQL-Zurich/)

<a name="impl" />

## Implementations

<a name="js" />

### JavaScript/TypeScript

- <b><code>&nbsp;20330⭐</code></b> <b><code>&nbsp;&nbsp;2056🍴</code></b> [graphql-js](https://github.com/graphql/graphql-js)) - A reference implementation of GraphQL for JavaScript.
- <b><code>&nbsp;&nbsp;1082⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [graphql-jit](https://github.com/zalando-incubator/graphql-jit)) - GraphQL execution using a JIT compiler.
- 🌎 [Gra*fast*](grafast.org) - a cutting edge planning and execution engine for GraphQL.

#### Clients

- <b><code>&nbsp;19725⭐</code></b> <b><code>&nbsp;&nbsp;2707🍴</code></b> [apollo-client](https://github.com/apollographql/apollo-client)) - A fully-featured, production ready caching GraphQL client for every UI framework and GraphQL server.
- <b><code>&nbsp;&nbsp;6116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [graphql-request](https://github.com/prisma-labs/graphql-request)) - A minimal GraphQL client for Node and browsers.
- 🌎 [typescript-graphql-request](graphql-code-generator.com/docs/plugins/typescript-graphql-request) - Use GraphQL Request as a fully typed SDK.
- <b><code>&nbsp;&nbsp;1974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [graphql-zeus](https://github.com/graphql-editor/graphql-zeus)) - GraphQL Zeus creates autocomplete client library for `JavaScript` or `TypeScript` which provides autocompletion for strongly typed queries.
- <b><code>&nbsp;&nbsp;3375⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [graphqurl](https://github.com/hasura/graphqurl)) - curl for GraphQL with autocomplete, subscriptions and GraphiQL. Also a dead-simple universal javascript GraphQL client.
- <b><code>&nbsp;&nbsp;9593⭐</code></b> <b><code>&nbsp;&nbsp;2169🍴</code></b> [aws-amplify](https://github.com/aws-amplify/amplify-js)) - A client library developed by Amazon for caching, analytics and more that includes a way to fetch GraphQL queries.
- <b><code>&nbsp;&nbsp;1031⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [gqty](https://github.com/gqty-dev/gqty)) - A No GraphQL client for TypeScript
- <b><code>&nbsp;&nbsp;&nbsp;965⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [genql](https://github.com/remorses/genql)) - Type safe TypeScript client for any GraphQL API.

##### Frontend Framework Integrations

- <b><code>&nbsp;&nbsp;6056⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;521🍴</code></b> [vue-apollo](https://github.com/vuejs/vue-apollo)) - Apollo/GraphQL integration for VueJS.
- <b><code>&nbsp;&nbsp;1514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;311🍴</code></b> [apollo-angular](https://github.com/kamilkisiela/apollo-angular)) - A fully-featured, production ready caching GraphQL client for Angular and every GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;950⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [svelte-apollo](https://github.com/timhall/svelte-apollo)) - Svelte integration for Apollo GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;280⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [ember-apollo-client](https://github.com/ember-graphql/ember-apollo-client)) - An ember-cli addon for Apollo Client and GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [apollo-elements](https://github.com/apollo-elements/apollo-elements)) - GraphQL web components that work in any frontend framework.
- <b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [sveltekit-kitql](https://github.com/jycouet/kitql)) - A set of tools, helping you building efficient apps in a fast way with SvelteKit and GraphQL.

###### React

- 🌎 [react-apollo](www.apollographql.com/docs/react/) - The core @apollo/client library provides built-in integration with React.
- <b><code>&nbsp;18936⭐</code></b> <b><code>&nbsp;&nbsp;1879🍴</code></b> [relay](https://github.com/facebook/relay)) - Relay is a JavaScript framework for building data-driven React applications.
- <b><code>&nbsp;&nbsp;8938⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;473🍴</code></b> [urql](https://github.com/FormidableLabs/urql)) - A simple caching GraphQL client for React.
- <b><code>&nbsp;&nbsp;1887⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [graphql-hooks](https://github.com/nearform/graphql-hooks)) - Minimal hooks-first GraphQL client with caching and server-side rendering support.
- <b><code>&nbsp;&nbsp;&nbsp;688⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [mst-gql](https://github.com/mobxjs/mst-gql)) - Bindings for mobx-state-tree and GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;531⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [micro-graphql-react](https://github.com/arackaf/micro-graphql-react)) - A lightweight utility for adding GraphQL to React. components. Includes simple caching and uses GET requests that could additionally be cached through a service-worker.
- <b><code>&nbsp;&nbsp;1031⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [@gqty/react](https://github.com/gqty-dev/gqty)) - A No GraphQL client for TypeScript

#### Servers

- <b><code>&nbsp;13947⭐</code></b> <b><code>&nbsp;&nbsp;2018🍴</code></b> [apollo-server](https://github.com/apollographql/apollo-server)) - Spec-compliant and production ready JavaScript GraphQL server that lets you develop in a schema-first way. Built for Express, Connect, Hapi, Koa, and more.
- <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql)) - Create a GraphQL HTTP server with Hapi.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [hapi-plugin-graphiql](https://github.com/rse/hapi-plugin-graphiql)) - HAPI plugin for GraphiQL integration.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [graphql-api-koa](https://github.com/jaydenseric/graphql-api-koa)) - GraphQL Koa middleware that implements GraphQL.js from scratch and supports native ESM.
- <b><code>&nbsp;&nbsp;&nbsp;841⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [koa-graphql](https://github.com/chentsulin/koa-graphql)) - GraphQL Koa Middleware.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [graphql-koa-scripts](https://github.com/ryanhs/graphql-koa-scripts)) - GraphQL Koa 1 file simplified. usefull for quick test
- <b><code>&nbsp;&nbsp;&nbsp;202⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [gql](https://github.com/deno-libs/gql)) - Universal GraphQL HTTP middleware for Deno.
- <b><code>&nbsp;&nbsp;2473⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [mercurius](https://github.com/mercurius-js/mercurius)) - GraphQL plugin for Fastify.
- <b><code>&nbsp;&nbsp;8487⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;590🍴</code></b> [graphql-yoga](https://github.com/prisma-labs/graphql-yoga)) - Fully-featured GraphQL Server with focus on easy setup, performance and great developer experience.
- <b><code>&nbsp;&nbsp;&nbsp;121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [graphitejs](https://github.com/graphitejs/server)) - Framework NodeJS for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [graphql-helix](https://github.com/contrawork/graphql-helix)) - A highly evolved GraphQL HTTP Server.
- <b><code>&nbsp;&nbsp;&nbsp;364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [pylon](https://github.com/getcronit/pylon)) - Write full-feature APIs with just functions. No more boilerplate code, no more setup. Just write functions and deploy.
- <b><code>&nbsp;&nbsp;&nbsp;415⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [modus](https://github.com/hypermodeinc/modus)) - Serverless runtime based on WebAssembly that delivers auto-generated GraphQL APIs.

##### Databases & ORMs

- <b><code>&nbsp;&nbsp;1892⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize)) - Sequelize helpers for GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf)) - Some help defining GraphQL schema around BookshelfJS models.
- <b><code>&nbsp;&nbsp;2698⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [join-monster](https://github.com/acarl005/join-monster)) - A GraphQL-to-SQL query execution layer for batch data fetching.

##### PubSub

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [graphql-ably-pubsub](https://github.com/ably-labs/graphql-ably-pubsub)) - Ably PubSub implementation for GraphQL to publish mutation updates and subscribe to the result through a subscription query.

#### Custom Scalars

- <b><code>&nbsp;&nbsp;1935⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [graphql-scalars](https://github.com/Urigo/graphql-scalars)) - A library of custom GraphQL Scalars for creating precise type-safe GraphQL schemas.

#### Type

- <b><code>&nbsp;&nbsp;8092⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;672🍴</code></b> [type-graphql](https://github.com/19majkel94/type-graphql)) - Create GraphQL schema and resolvers with TypeScript, using classes and decorators!
- <b><code>&nbsp;&nbsp;3422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [graphql-nexus](https://github.com/graphql-nexus/nexus)) - Code-First, Type-Safe, GraphQL Schema Construction.
- <b><code>&nbsp;11218⭐</code></b> <b><code>&nbsp;&nbsp;1390🍴</code></b> [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator)): GraphQL code generator with flexible support for custom plugins and templates like TypeScript (frontend and backend), React Hooks, resolvers signatures and more.
- <b><code>&nbsp;&nbsp;2579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [pothos](https://github.com/hayes/pothos)) - Pothos is a plugin based GraphQL schema builder for typescript. It makes building graphql schemas in typescript easy, fast and enjoyable.
- <b><code>&nbsp;&nbsp;1319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [garph](https://github.com/stepci/garph)) - Garph is full-stack framework for building type-safe GraphQL APIs in TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [gqloom](https://github.com/modevol-com/gqloom)) - GQLoom is a GraphQL weaver for TypeScript/JavaScript that weaves GraphQL schema and resolvers using <b><code>&nbsp;&nbsp;8458⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;307🍴</code></b> [Valibot](https://github.com/fabian-hiller/valibot)), <b><code>&nbsp;41985⭐</code></b> <b><code>&nbsp;&nbsp;1827🍴</code></b> [Zod](https://github.com/colinhacks/zod)), or <b><code>&nbsp;23689⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;942🍴</code></b> [Yup](https://github.com/jquense/yup)).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [fast-graphql](https://github.com/idurar/fast-graphql)) - Graphql Tools to Structure, Combine Resolvers and Merge Schema Definitions for Node.js, Next.Js and Graphql Apollo server
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-to-type](https://github.com/lkster/graphql-to-type)) - GraphQL query parser written entirely in TypeScript's type system for creating interfaces based on provided query
- <b><code>&nbsp;&nbsp;2914⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [gql.tada](https://github.com/0no-co/gql.tada)) - GraphQL document authoring library, inferring the result and variables types of GraphQL queries and fragments in the TypeScript type system.

#### Miscellaneous

- <b><code>&nbsp;&nbsp;5420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;832🍴</code></b> [graphql-tools](https://github.com/apollographql/graphql-tools)) - Tool library for building and maintaining GraphQL-JS servers.
- <b><code>&nbsp;&nbsp;2338⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;180🍴</code></b> [graphql-tag](https://github.com/apollographql/graphql-tag)) - A JavaScript template literal tag that parses GraphQL queries.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [load-gql](https://github.com/KunalSin9h/load-gql)) - A tiny, zero dependency GraphQL schema loader from files and folders.
- <b><code>&nbsp;&nbsp;1210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [graphql-compose](https://github.com/graphql-compose/graphql-compose)) - Tool which allows you to construct flexible graphql schema from different data sources via plugins.
- <b><code>&nbsp;&nbsp;1328⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [graphql-modules](https://github.com/Urigo/graphql-modules)) - Separate GraphQL server into smaller, reusable parts by modules or features.
- <b><code>&nbsp;&nbsp;3575⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [graphql-shield](https://github.com/maticzav/graphql-shield)) - A library that helps creating a permission layer for a graphql api.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [graphql-shield-generator](https://github.com/omar-dulaimi/graphql-shield-generator)) - Emits a GraphQL Shield from your GraphQL schema.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [graphqlgate](https://github.com/oslabs-beta/GraphQL-Gate)) - A GraphQL rate-limiting library with query complexity analysis for Node.js
- <b><code>&nbsp;&nbsp;&nbsp;453⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [graphql-let](https://github.com/piglovesyou/graphql-let)) - A webpack loader to import type-protected codegen results directly from GraphQL documents
- <b><code>&nbsp;&nbsp;1199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [graphql-config](https://github.com/kamilkisiela/graphql-config)) - One configuration for all your GraphQL tools (supported by most tools, editors & IDEs).
- <b><code>&nbsp;&nbsp;2019⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [graphql-cli](https://github.com/urigo/graphql-cli)) - A command line tool for common GraphQL development workflows.
- <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [graphql-toolkit](https://github.com/ardatan/graphql-toolkit)) - A set of utils for faster development of GraphQL tools (Schema and documents loading, Schema merging and more).
- <b><code>&nbsp;&nbsp;3488⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;358🍴</code></b> [graphql-mesh](https://github.com/urigo/graphql-mesh)) - use GraphQL query language to access data in remote APIs that don't run GraphQL (and also ones that do run GraphQL).
- <b><code>&nbsp;&nbsp;1115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [sofa](https://github.com/Urigo/sofa)) - Generate REST API from your GraphQL API.
- <b><code>&nbsp;&nbsp;&nbsp;408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [graphback](https://github.com/aerogear/graphback)) - Framework and CLI to add a GraphQLCRUD API layer to a GraphQL server using data models.
- <b><code>&nbsp;&nbsp;1149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [graphql-middleware](https://github.com/maticzav/graphql-middleware)) - Split up your GraphQL resolvers in middleware functions.
- <b><code>&nbsp;&nbsp;1546⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [graphql-relay-js](https://github.com/graphql/graphql-relay-js)) - A library to help construct a graphql-js server supporting react-relay.
- <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [graphql-normalizr](https://github.com/monojack/graphql-normalizr)) - Normalize GraphQL responses for persisting in the client cache/state.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql)) - Babel plugin that compile GraphQL tagged template strings.
- <b><code>&nbsp;&nbsp;1216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql)) - An ESLint plugin that checks your GraphQL strings against a schema.
- <b><code>&nbsp;&nbsp;1858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [graphql-ws](https://github.com/enisdenjo/graphql-ws)) - Coherent, zero-dependency, lazy, simple, GraphQL over WebSocket Protocol compliant server and client.
- <b><code>&nbsp;&nbsp;&nbsp;441⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [graphql-live-query](https://github.com/n1ru4l/graphql-live-query)) - Realtime GraphQL Live Queries with JavaScript.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [GraphVinci](https://github.com/Comcast/graphvinci)) - An interactive schema visualizer for GraphQL APIs.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [supertest-graphql](https://github.com/alexstrat/supertest-graphql)) - Extends <b><code>&nbsp;14324⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;782🍴</code></b> [supertest](https://github.com/visionmedia/supertest)) to easily test a GraphQL endpoint
- <b><code>&nbsp;&nbsp;3071⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [schemathesis](https://github.com/schemathesis/schemathesis)) - Runs arbitrary queries matching a GraphQL schema to find server errors.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [microfiber](https://github.com/anvilco/graphql-introspection-tools)) - Query and manipulate GraphQL introspection query results in useful ways.
- <b><code>&nbsp;&nbsp;&nbsp;573⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [graphql-armor](https://github.com/Escape-Technologies/graphql-armor)) - An instant security layer for production GraphQL Endpoints.
- <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [goctopus](https://github.com/Escape-Technologies/goctopus)) - an incredibly fast GraphQL discovery & fingerprinting toolbox.
- <b><code>&nbsp;&nbsp;&nbsp;577⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [GraphQL Constraint Directive](https://github.com/confuser/graphql-constraint-directive)) - Allows using @constraint as a directive to validate input data. Inspired by Constraints Directives RFC and OpenAPI
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Validator.js Wrapper Directive](https://github.com/ktutnik/graphql-directive/tree/master/packages/validator)) - A comprehensive list of validator directive wraps Validator.js functionalities
- <b><code>&nbsp;&nbsp;1169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [WunderGraph Cosmo](https://github.com/wundergraph/cosmo)) - The Open-Source GraphQL Federation Solution with Full Lifecycle API Management for (Federated) GraphQL. Schema Registry, composition checks, analytics, metrics, tracing and routing.
- <b><code>&nbsp;&nbsp;&nbsp;815⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [graphql-go-tools](https://github.com/wundergraph/graphql-go-tools)) - A graphQL Router / API Gateway framework written in Golang, focussing on correctness, extensibility, and high-performance. Supports Federation v1 & v2, Subscriptions & more.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-sunset](https://github.com/sophiabits/graphql-sunset)) - Quickly and easily add support for the `Sunset` header to your GraphQL server, to better communicate upcoming breaking changes.

<a name="js-example" />

#### JavaScript Examples

- <b><code>&nbsp;23511⭐</code></b> <b><code>&nbsp;&nbsp;4228🍴</code></b> [React Starter Kit](https://github.com/kriasoft/react-starter-kit)) - front-end starter kit using React, Relay, GraphQL, and JAM stack architecture.
- <b><code>&nbsp;&nbsp;1065⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;274🍴</code></b> [SWAPI GraphQL Wrapper](https://github.com/graphql/swapi-graphql)) - A GraphQL schema and server wrapping SWAPI.
- <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Relay TodoMVC](https://github.com/taion/relay-todomvc)) - Relay TodoMVC with routing.
- 🌎 [Apollo Client documentation](www.apollographql.com/docs/react) - Documentation and example for building GraphQL apps using apollo client.
- 🌎 [Apollo Server tools documentation](www.apollographql.com/docs/apollo-server/) - Documentation, tutorial and examples for building GraphQL server and connecting to SQL, MongoDB and REST endpoints.
- <b><code>&nbsp;13933⭐</code></b> <b><code>&nbsp;&nbsp;2491🍴</code></b> [F8 App 2017](https://github.com/fbsamples/f8app)) - Source code of the official F8 app of 2016, powered by React Native and other Facebook open source projects.
- <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Apollo React example for Github GraphQL API](https://github.com/katopz/react-apollo-graphql-github-example)) - Usage Examples Apollo React for Github GraphQL API with create-react-app.
- <b><code>138035⭐</code></b> <b><code>&nbsp;30518🍴</code></b> [Next.js TypeScript and GraphQL Example](https://github.com/zeit/next.js/tree/canary/examples/with-typescript-graphql)) - A type-protected GraphQL example on Next.js running 🌎 [graphql-codegen](graphql-code-generator.com/) under the hood
- 🌎 [GraphQL StackBlitz Starter](stackblitz.com/fork/graphql) – A live, editable demo spinning up in about 2 seconds and running in a browser.
- <b><code>&nbsp;&nbsp;1337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [NAPERG](https://github.com/alan345/naperg)) - Fullstack Boilerplate GraphQL. Made with React & Prisma + authentication & roles.
- [VulcanJS](http://vulcanjs.org) - The full-stack React+GraphQL framework
- <b><code>&nbsp;&nbsp;2208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [RAN Toolkit](https://github.com/sly777/ran)) - Production-ready toolkit/boilerplate with support for GraphQL, SSR, Hot-reload, CSS-in-JS, caching, and more.

<a name="ts-example" />

#### TypeScript Examples

- <b><code>&nbsp;&nbsp;3976⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;559🍴</code></b> [Node.js API Starter](https://github.com/kriasoft/nodejs-api-starter)) - Yarn v2 based monorepo template (code-first GraphQL API, PostgreSQL, PnP, Zero-install, serverless).
- <b><code>&nbsp;&nbsp;&nbsp;274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Next.js Apollo TypeScript Starter](https://github.com/borisowsky/nextjs-apollo-ts-starter)) - Next.js starter project focused on developer experience.
- <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [GraphQL Starter](https://github.com/cerino-ligutom/GraphQL-Starter)) - A boilerplate for TypeScript + Node Express + Apollo GraphQL APIs.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Mocked Managed Federation - Apollo Server 3](https://github.com/setchy/apollo-server-3-mocked-federation)) - An example of how to mock a managed federation Supgraph using Apollo Server 3.x
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Mocked Managed Federation - Apollo Server 4](https://github.com/setchy/apollo-server-4-mocked-federation)) - An example of how to mock a managed federation Supgraph using Apollo Server 4.x
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Next.js Advanced Graphql Crud MongoDB Starter](https://github.com/idurar/starter-advanced-graphql-crud-next-js-mongodb)) - Starter Generic CRUD with Advanced Apollo Graphql server with Next.js and Mongodb (TypeScript)

<a name="rb" />

### Ruby

- <b><code>&nbsp;&nbsp;5431⭐</code></b> <b><code>&nbsp;&nbsp;1420🍴</code></b> [graphql-ruby](https://github.com/rmosolgo/graphql-ruby)) - Ruby implementation of Facebook's GraphQL.
- <b><code>&nbsp;&nbsp;1437⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [graphql-batch](https://github.com/Shopify/graphql-batch)) - A query batching executor for the graphql gem.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [graphql-auth](https://github.com/o2web/graphql-auth)) - A JWT auth wrapper working with devise.
- <b><code>&nbsp;&nbsp;&nbsp;925⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [agoo](https://github.com/ohler55/agoo)) - Ruby web server that implements Facebook's GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;209⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [GQLi](https://github.com/contentful-labs/gqli.rb)) - A GraphQL client and DSL. Allowing to write queries in native Ruby.

<a name="rb-example" />

#### Ruby Examples

- <b><code>&nbsp;&nbsp;&nbsp;216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo)) - Use graphql-ruby to expose a Rails app.
- <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [github-graphql-rails-example](https://github.com/github/github-graphql-rails-example)) - Example Rails app using GitHub's GraphQL API.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [relay-on-rails](https://github.com/nethsix/relay-on-rails)) - Barebones starter kit for Relay application with Rails GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [relay-rails-blog](https://github.com/gauravtiwari/relay-rails-blog)) - A graphql, relay and standard rails application powered demo weblog.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [to_eat_app](https://github.com/jcdavison/to_eat_app)) - A sample graphql/rails/relay application with a related 3-part article series.
- <b><code>&nbsp;&nbsp;&nbsp;925⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [agoo-demo](https://github.com/ohler55/agoo/tree/develop/example/graphql)) - Use of the Agoo server to demonstrate a simple GraphQL application.
- <b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [rails-devise-graphql](https://github.com/zauberware/rails-devise-graphql)) - A rails 6 boilerplate with devise, graphql & JWT auth.

<a name="php" />

### PHP

- <b><code>&nbsp;&nbsp;4710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;572🍴</code></b> [graphql-php](https://github.com/webonyx/graphql-php)) - A PHP port of GraphQL reference implementation.
- <b><code>&nbsp;&nbsp;&nbsp;271⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [graphql-relay-php](https://github.com/ivome/graphql-relay-php)) - Relay helpers for webonyx/graphql-php implementation of GraphQL.
- <b><code>&nbsp;&nbsp;3480⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;466🍴</code></b> [lighthouse](https://github.com/nuwave/lighthouse)) - A PHP package that allows to serve a GraphQL endpoint from your Laravel application.
- <b><code>&nbsp;&nbsp;2212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;270🍴</code></b> [graphql-laravel](https://github.com/rebing/graphql-laravel)) - Laravel wrapper for Facebook's GraphQL.
- <b><code>&nbsp;&nbsp;&nbsp;796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [overblog/graphql-bundle](https://github.com/overblog/GraphQLBundle)) - This bundle provides tools to build a complete GraphQL server in your Symfony App. Supports react-relay.
- <b><code>&nbsp;&nbsp;3768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;468🍴</code></b> [wp-graphql](https://github.com/wp-graphql/wp-graphql)) - GraphQL API for WordPress.
- <b><code>&nbsp;&nbsp;&nbsp;572⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [graphqlite](https://github.com/thecodingmachine/graphqlite)) - Framework agnostic library that allows you to write GraphQL server by annotating your PHP classes.
- <b><code>&nbsp;&nbsp;1110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [siler](https://github.com/leocavalcante/siler)) - Plain-old functions providing a declarative API for GraphQL servers with Subscriptions support.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-request-builder](https://github.com/dpauli/php-graphql-request-builder)) - Builds request payload in GraphQL structure.
- 🌎 [drupal/graphql](www.drupal.org/project/graphql) - Craft and expose a GraphQL schema for Drupal 9 and 10.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [jerowork/graphql-schema-builder](https://github.com/jerowork/graphql-attribute-schema)) - Easily build your GraphQL schema for webonyx/graphql-php using PHP attributes instead of large configuration arrays.

<a name="php-example" />

#### PHP Examples

- <b><code>&nbsp;&nbsp;1110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [siler-graphgl](https://github.com/leocavalcante/siler/tree/main/examples/graphql)) - An example GraphQL server written with Siler.

<a name="py" />

### Python

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [graphql-parser](https://github.com/tryolabs/graphql-parser)) - GraphQL parser for Python.
- <b><code>&nbsp;&nbsp;&nbsp;531⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [graphql-core](https://github.com/graphql-python/graphql-core)) - GraphQL implementation for Python based on GraphQL.js v16.3.0 reference implementation
- <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py)) - A library to help construct a graphql-py server supporting react-relay.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python)) - A python wrapper around libgraphqlparser.
- <b><code>&nbsp;&nbsp;8250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;822🍴</code></b> [graphene](https://github.com/graphql-python/graphene)) - A package for creating GraphQL schemas/types in a Pythonic easy way.
- <b><code>&nbsp;&nbsp;&nbsp;117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [graphene-gae](https://github.com/graphql-python/graphene-gae)) - Adds GraphQL support to Google AppEngine (GAE).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [django-graphiql](https://github.com/GraphQL-python-archive/django-graphiql)) - Integrate GraphiQL easily into your Django project.
- <b><code>&nbsp;&nbsp;1339⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [flask-graphql](https://github.com/graphql-python/flask-graphql)) - Adds GraphQL support to your Flask application.
- <b><code>&nbsp;&nbsp;&nbsp;156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [python-graphql-client](https://github.com/prisma/python-graphql-client)) - Simple GraphQL client for Python 2.7+
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [python-graphjoiner](https://github.com/healx/python-graphjoiner)) - Create GraphQL APIs using joins, SQL or otherwise.
- <b><code>&nbsp;&nbsp;4386⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;766🍴</code></b> [graphene-django](https://github.com/graphql-python/graphene-django)) - A Django integration for Graphene.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Flask-GraphQL-Auth](https://github.com/callsign-viper/Flask-GraphQL-Auth)) - An authentication library for Flask inspired from flask-jwt-extended.
- <b><code>&nbsp;&nbsp;&nbsp;855⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [tartiflette](https://github.com/dailymotion/tartiflette)) - GraphQL Implementation, SDL First, for python 3.6+ / asyncio.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [tartiflette-aiohttp](https://github.com/dailymotion/tartiflette-aiohttp)) - Wrapper of Tartiflette to expose GraphQL API over HTTP based on aiohttp / 3.6+ / asyncio, 🌎 [official tutorial available on tartiflette.io](tartiflette.io/docs/tutorial/getting-started).
- <b><code>&nbsp;&nbsp;2318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;189🍴</code></b> [Ariadne](https://github.com/mirumee/ariadne)) - library for implementing GraphQL servers using schema-first approach. Asynchronous query execution, batteries included for ASGI, WSGI and popular webframeworks, 🌎 [fully documented](ariadnegraphql.org).
- <b><code>&nbsp;&nbsp;&nbsp;331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [django-graphql-auth](https://github.com/PedroBern/django-graphql-auth)) - Django registration and authentication with GraphQL.
- <b><code>&nbsp;&nbsp;4616⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;613🍴</code></b> [strawberry](https://github.com/strawberry-graphql/strawberry)) - A new GraphQL library for Python.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [turms](https://github.com/jhnnsrs/turms)) - A pythonic graphql codegenerator built around graphql-core and pydantic
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [rath](https://github.com/jhnnsrs/rath)) - An apollo like graphql client with async and sync interface
- <b><code>&nbsp;&nbsp;&nbsp;549⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [sgqlc](https://github.com/profusion/sgqlc)) - Simple GraphQL Client makes working with GraphQL API responses easier in Python.

<a name="py-example" />

#### Python Examples

- <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [swapi-graphene](https://github.com/graphql-python/swapi-graphene)) - A GraphQL schema and server using 🌎 [Graphene](graphene-python.org).
- 🌎 [Python Backend Tutorial](hasura.io/learn/graphql/backend-stack/languages/python/) - A tutorial on creating a GraphQL server with 🌎 [Strawberry](strawberry.rocks/) and a client with 🌎 [Qlient](qlient-org.github.io/python-qlient/site/).

<a name="java" />

### Java

- <b><code>&nbsp;&nbsp;6233⭐</code></b> <b><code>&nbsp;&nbsp;1149🍴</code></b> [graphql-java](https://github.com/graphql-java/graphql-java)) - GraphQL Java implementation.
- <b><code>&nbsp;&nbsp;3305⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;333🍴</code></b> [DGS Framework](https://github.com/Netflix/dgs-framework)) - A GraphQL server framework for Spring Boot, developed by Netflix.
- [graphql-java-generator](https://github.com/graphql-java-generator) - A <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Maven plugin](https://github.com/graphql-java-generator/graphql-maven-plugin-project)) and a <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Gradle plugin](https://github.com/graphql-java-generator/graphql-gradle-plugin-project)) that can generate both the **Client** and the **Server** (POJOs and utility classes). The server part is based on graphql-java, and hides all its boilerplate codes.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [gaphql-java-type-generator](https://github.com/graphql-java/graphql-java-type-generator)) - Auto-generates types for use with GraphQL Java
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [schemagen-graphql](https://github.com/bpatters/schemagen-graphql)) - Schema generation and execution package that turns POJO's into a GraphQL Java queryable set of objects. Enables exposing any service as a GraphQL service using Annotations.
- <b><code>&nbsp;&nbsp;&nbsp;391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [graphql-java-annotations](https://github.com/Enigmatis/graphql-java-annotations)) - Provides annotations-based syntax for schema definition with GraphQL Java.
- <b><code>&nbsp;&nbsp;&nbsp;822⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;173🍴</code></b> [graphql-java-tools](https://github.com/graphql-java-kickstart/graphql-java-tools)) - Schema-first graphql-java convenience library that makes it easy to bring your own implementations as data resolvers. Inspired by <b><code>&nbsp;&nbsp;5420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;832🍴</code></b> [graphql-tools](https://github.com/apollographql/graphql-tools)) for JS.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [graphql-java-codegen-maven-plugin](https://github.com/kobylynskyi/graphql-java-codegen-maven-plugin)) - Schema-first maven plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools. Inspired by <b><code>&nbsp;17709⭐</code></b> <b><code>&nbsp;&nbsp;6027🍴</code></b> [swagger-codegen-maven-plugin](https://github.com/swagger-api/swagger-codegen/tree/master/modules/swagger-codegen-maven-plugin)).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [graphql-java-codegen-gradle-plugin](https://github.com/kobylynskyi/graphql-java-codegen-gradle-plugin)) - Schema-first gradle plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools. Inspired by <b><code>&nbsp;&nbsp;&nbsp;309⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [gradle-swagger-generator-plugin](https://github.com/int128/gradle-swagger-generator-plugin)).
- <b><code>&nbsp;&nbsp;&nbsp;226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [graphql-java-servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet)) - A framework-agnostic java servlet for exposing graphql-java query endpoints with GET, POST, and multipart uploads.
- <b><code>&nbsp;&nbsp;2714⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql)) - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Java example](#example-java) below.
- <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [spring-graphql-common](https://github.com/oembedler/spring-graphql-common)) - Spring Framework GraphQL Library.
- <b><code>&nbsp;&nbsp;1512⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;324🍴</code></b> [graphql-spring-boot](https://github.com/graphql-java-kickstart/graphql-spring-boot)) - GraphQL and GraphiQL Spring Framework Boot Starters.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [vertx-graphql-service-discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery)) - Asynchronous GraphQL service discovery and querying for your microservices.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [vertx-dataloader](https://github.com/engagingspaces/vertx-dataloader)) - Port of Facebook DataLoader for efficient, asynchronous batching and caching in clustered GraphQL environments.
- <b><code>&nbsp;&nbsp;1105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [graphql-spqr](https://github.com/leangen/GraphQL-SPQR)) - Java 8+ API for rapid development of GraphQL services.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Light Java GraphQL](https://github.com/networknt/light-graphql-4j)): A lightweight, fast microservices framework with all cross-cutting concerns addressed and ready to plug in GraphQL schema.
- 🌎 [Elide](elide.io): A Java library that can expose a JPA annotated data model as a GraphQL service over any relational database.
- <b><code>&nbsp;&nbsp;&nbsp;272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [federation-jvm](https://github.com/apollographql/federation-jvm)) - Apollo Federation on the JVM.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [graphql-orchestrator-java](https://github.com/graph-quilt/graphql-orchestrator-java)) GraphQL Orchestrator/Gateway library that supports Schema Stitching and Apollo Federation directives to combine schema from multiple GraphQL microservices into a single unified schema.
- <b><code>&nbsp;&nbsp;&nbsp;137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [graphql-java-extended-validation](https://github.com/graphql-java/graphql-java-extended-validation)) - Provides extended validation of fields and field arguments for graphql-java.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [dgs-extended-formatters](https://github.com/setchy/dgs-extended-formatters)) - An experimental set of DGS Directives for common formatting use-cases.

#### Custom Scalars

- <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [graphql-java-datetime](https://github.com/donbeave/graphql-java-datetime)) - GraphQL ISO Date is a set of RFC 3339 compliant date/time scalar types to be used with graphql-java.
- <b><code>&nbsp;&nbsp;&nbsp;281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [graphql-java-extended-scalars](https://github.com/graphql-java/graphql-java-extended-scalars)) - Extended scalars for graphql-java.

<a name="java-example" />

#### Java Examples

- <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [light-java-graphql examples](https://github.com/networknt/light-example-4j/tree/master/graphql)) - Examples of Light Java GraphQL and tutorials.
- <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [graphql-spqr-samples](https://github.com/leangen/graphql-spqr-samples)) - An example GraphQL server written with Spring MVC and GraphQL-SPQR.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-graphql-app)) - A simple application, both client and server, demonstrating the Manifold GraphQL library.
- <b><code>&nbsp;&nbsp;&nbsp;120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [graphql-java-kickstart_samples](https://github.com/graphql-java-kickstart/samples)) - Samples for using the GraphQL Java Kickstart projects.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [graphql-java-kickstart-federation-example](https://github.com/setchy/graphql-java-kickstart-federation-example)) - A GraphQL Java Kickstart federation example.
- <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [dgs-federation-example](https://github.com/Netflix/dgs-federation-example)) - A Netflix DGS federation example.
- 🌎 [Spring Boot backend tutorial](hasura.io/learn/graphql/backend-stack/languages/java/) - A tutorial creating a GraphQL server and client using Spring Boot and Netflix DGS.

<a name="kotlin" />

### Kotlin

- <b><code>&nbsp;&nbsp;1797⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;375🍴</code></b> [graphql-kotlin](https://github.com/ExpediaGroup/graphql-kotlin)) - GraphQL Kotlin implementation.
- <b><code>&nbsp;&nbsp;2714⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql)) - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Kotlin example](#example-kotlin) below.
- <b><code>&nbsp;&nbsp;&nbsp;307⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [KGraphQL](https://github.com/aPureBase/KGraphQL)): Pure Kotlin implementation to setup a GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Kobby](https://github.com/ermadmi78/kobby)) - Codegen plugin of 🌎 [Kotlin DSL Client](blog.kotlin-academy.com/how-to-generate-kotlin-dsl-client-by-graphql-schema-707fd0c55284) by GraphQL schema. The generated DSL supports execution of complex GraphQL queries, mutation and subscriptions in Kotlin with syntax similar to native GraphQL syntax.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Graphkt](https://github.com/cufyorg/graphkt)) - A DSL based graphql server library for kotlin, backed by graphql-java.

<a name="kotlin-example" />

#### Kotlin Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-kotlin-app)) - A simple GraphQL application, both client and server, demonstrating the Manifold GraphQL library with Kotlin.

<a name="c" />

### C/C++

- <b><code>&nbsp;&nbsp;1104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [libgraphqlparser](https://github.com/graphql/libgraphqlparser)) - A GraphQL query parser in C++ with C and C++ APIs.
- <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [agoo-c](https://github.com/ohler55/agoo-c)) - A high performance GraphQL server written in C. <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [benchmarks](https://github.com/the-benchmarker/graphql-benchmarks))
- <b><code>&nbsp;&nbsp;&nbsp;346⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [cppgraphqlgen](https://github.com/Microsoft/cppgraphqlgen)) - C++ GraphQL schema service generator.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [CaffQL](https://github.com/caffeinetv/CaffQL)) - Generates C++ client types and request/response serialization from a GraphQL introspection query.

<a name="go" />

### Go

- <b><code>&nbsp;10153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;842🍴</code></b> [graphql](https://github.com/graphql-go/graphql)) - An implementation of GraphQL for Go follows graphql-js
- <b><code>&nbsp;&nbsp;4747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;491🍴</code></b> [graphql-go](https://github.com/graph-gophers/graphql-go)) - GraphQL server with a focus on ease of use.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [gql](https://github.com/kadirpekel/gql)) - Code first graphql (graphql-go/graphql) schema builder.
- <b><code>&nbsp;10674⭐</code></b> <b><code>&nbsp;&nbsp;1245🍴</code></b> [gqlgen](https://github.com/99designs/gqlgen)) - Go generate based graphql server library.
- <b><code>&nbsp;&nbsp;&nbsp;425⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [graphql-relay-go](https://github.com/graphql-go/relay)) - A Go/Golang library to help construct a server supporting react-relay.
- <b><code>&nbsp;&nbsp;3021⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [graphjin](https://github.com/dosco/graphjin)): Build APIs in 5 minutes with GraphQL. An instant GraphQL to SQL compiler.
- <b><code>&nbsp;&nbsp;&nbsp;815⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [graphql-go-tools](https://github.com/wundergraph/graphql-go-tools)) - A graphQL Router / API Gateway framework written in Golang, focussing on correctness, extensibility, and high-performance. Supports Federation v1 & v2, Subscriptions & more.
- <b><code>&nbsp;&nbsp;&nbsp;119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Thunder](https://github.com/Raezil/Thunder)) - A scalable microservices framework powered by Go, gRPC-Gateway, Prisma, and Kubernetes. It exposes REST, gRPC and Graphql
- <b><code>&nbsp;&nbsp;&nbsp;424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [grpc-graphql-gateway](https://github.com/ysugimoto/grpc-graphql-gateway)) - A protoc plugin that generates graphql execution code from Protocol Buffers. 
<a name="go-example" />

#### Go Examples

- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit)) - Barebones starting point for a Relay application with Golang GraphQL server.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go)) - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [go-graphql-subscription-example](https://github.com/ccamel/go-graphql-subscription-example)) - A GraphQL schema and server that demonstrates GraphQL <b><code>&nbsp;&nbsp;1511⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;331🍴</code></b> [subscriptions](https://github.com/apollographql/subscriptions-transport-ws/blob/v0.9.4/PROTOCOL.md)) (over Websocket) to consume 🌎 [Apache Kafka](kafka.apache.org/) messages.
- 🌎 [Go Backend Tutorial](hasura.io/learn/graphql/backend-stack/languages/go/) - A tutorial showing how to make a Go GraphQL server and client using code generation.

<a name="scala" />

### Scala

- <b><code>&nbsp;&nbsp;1963⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;221🍴</code></b> [sangria](https://github.com/sangria-graphql/sangria)) - Scala GraphQL server implementation.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [sangria-relay](https://github.com/sangria-graphql/sangria-relay)) - Sangria Relay Support.
- <b><code>&nbsp;&nbsp;&nbsp;985⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;263🍴</code></b> [caliban](https://github.com/ghostdogpr/caliban)) - Caliban is a purely functional library for creating GraphQL backends in Scala.

<a name="scala-example" />

#### Scala Examples

- <b><code>&nbsp;&nbsp;&nbsp;241⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example)) - An example GraphQL server written with akka-http and 🌎 [sangria](sangria-graphql.github.io/)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [sangria-playground](https://github.com/sangria-graphql/sangria-playground)) - An example of GraphQL server written with Play and sangria.

<a name="dotnet" />

### .NET

- <b><code>&nbsp;&nbsp;5981⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;933🍴</code></b> [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)) - GraphQL for .NET.
- <b><code>&nbsp;&nbsp;&nbsp;888⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [graphql-net](https://github.com/ckimes89/graphql-net)) - GraphQL to IQueryable for .NET.
- <b><code>&nbsp;&nbsp;5672⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;804🍴</code></b> [Hot Chocolate](https://github.com/ChilliCream/hotchocolate)) - GraphQL server for .Net Core and .NET Framework.
- <b><code>&nbsp;&nbsp;&nbsp;160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Snowflaqe](https://github.com/Zaid-Ajaj/Snowflaqe)) - Type-safe GraphQL code generator for F# and <b><code>&nbsp;&nbsp;3060⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;321🍴</code></b> [Fable](https://github.com/fable-compiler/Fable))
- <b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [EntityGraphQL](https://github.com/EntityGraphQL/EntityGraphQL)) - library to build a GraphQL API on top of data model with the extensibility to bring multiple data sources together in the single GraphQL schema.
- <b><code>&nbsp;&nbsp;&nbsp;317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [ZeroQL](https://github.com/byme8/ZeroQL)) - type-safe GraphQL client with Linq-like interface for C#

<a name="net-example" />

#### .NET Examples

- 🌎 [.NET backend tutorial](hasura.io/learn/graphql/backend-stack/languages/dotnet/) - A tutorial creating a GraphQL server and client with .NET.

<a name="elixir" />

### Elixir

- <b><code>&nbsp;&nbsp;4393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;547🍴</code></b> [absinthe-graphql](https://github.com/absinthe-graphql/absinthe)) - Fully Featured Elixir GraphQL Library.
- <b><code>&nbsp;&nbsp;&nbsp;857⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [graphql-elixir](https://github.com/graphql-elixir/graphql)) - GraphQL Elixir. (No longer maintained)
- <b><code>&nbsp;&nbsp;&nbsp;126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [plug_graphql](https://github.com/graphql-elixir/plug_graphql)) - Plug integration for GraphQL Elixir.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [graphql_relay](https://github.com/graphql-elixir/graphql_relay)) - Relay helpers for GraphQL Elixir.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [graphql_parser](https://github.com/graphql-elixir/graphql_parser)) - Elixir bindings for <b><code>&nbsp;&nbsp;1104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [libgraphqlparser](https://github.com/graphql/libgraphqlparser))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql](https://github.com/asonge/graphql)) - Elixir GraphQL parser.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [plot](https://github.com/peburrows/plot)) - GraphQL parser and resolver for Elixir.

<a name="elixir-example" />

#### Elixir Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [hello_graphql_phoenix](https://github.com/graphql-elixir/hello_graphql_phoenix)) - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix

<a name="haskell" />

### Haskell

- <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [graphql-haskell](https://github.com/jdnavarro/graphql-haskell)) - GraphQL AST and parser for Haskell.
- <b><code>&nbsp;&nbsp;&nbsp;416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [morpheus-graphql](https://github.com/morpheusgraphql/morpheus-graphql)) - Haskell GraphQL Api, Client and Tools.

<a name="sql" />

### SQL

- <b><code>&nbsp;&nbsp;1089⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL)) - GraphQL for Postgres.
- <b><code>&nbsp;&nbsp;&nbsp;591⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [sql-to-graphql](https://github.com/rexxars/sql-to-graphql)) - Generate a GraphQL API based on your SQL database structure.
- <b><code>&nbsp;12907⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;612🍴</code></b> [PostGraphile](https://github.com/graphile/postgraphile)) - Lightning-fast GraphQL APIs for PostgreSQL: highly customisable; extensible via plugins; realtime.
- <b><code>&nbsp;31908⭐</code></b> <b><code>&nbsp;&nbsp;2853🍴</code></b> [Hasura](https://github.com/hasura/graphql-engine)) - Hasura gives Instant Realtime GraphQL APIs over PostgreSQL. Works with an existing database too.
- 🌎 [subZero](subzero.cloud/) - GraphQL & REST API for your database

<a name="lua" />

### Lua

- <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [graphql-lua](https://github.com/bjornbytes/graphql-lua)) - GraphQL for Lua.

<a name="elm" />

### Elm

- <b><code>&nbsp;&nbsp;&nbsp;786⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [elm-graphql](https://github.com/dillonkearns/elm-graphql)) - GraphQL for Elm.

<a name="clojure" />

### Clojure

- <b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [graphql-clj](https://github.com/tendant/graphql-clj)) - A Clojure library designed to provide GraphQL implementation.
- <b><code>&nbsp;&nbsp;1849⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [Lacinia](https://github.com/walmartlabs/lacinia)) - GraphQL implementation in pure Clojure.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [graphql-query](https://github.com/district0x/graphql-query)) - Clojure(Script) GraphQL query generation.

<a name="clojure-example" />

#### Clojure Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Clojure Game Geek](https://github.com/walmartlabs/clojure-game-geek)) - Example code for the Lacinia GraphQL framework tutorial.

<a name="swift" />

### Swift

- <b><code>&nbsp;&nbsp;&nbsp;962⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [GraphQL](https://github.com/GraphQLSwift/GraphQL)) - The Swift implementation for GraphQL.

<a name="ocaml" />

### OCaml

- <b><code>&nbsp;&nbsp;&nbsp;621⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [ocaml-graphql-server](https://github.com/andreas/ocaml-graphql-server)) - GraphQL servers in OCaml.

<a name="android" />

### Android

- <b><code>&nbsp;&nbsp;3947⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;696🍴</code></b> [apollo-android](https://github.com/apollographql/apollo-android)) - 📟 A strongly-typed, caching GraphQL client for Android, written in Java.
- <b><code>&nbsp;&nbsp;2714⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql)) - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Java example](#example-java) below.

<a name="android-example" />

#### Android Examples

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [apollo-frontpage-android-app](https://github.com/rnitame/apollo-frontpage-android-app)) - 📄 Apollo "hello world" app, for Android.

<a name="ios" />

### iOS

- <b><code>&nbsp;&nbsp;4033⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;750🍴</code></b> [apollo-ios](https://github.com/apollographql/apollo-ios)) - 📱 A strongly-typed, caching GraphQL client for iOS, written in Swift.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [ApolloDeveloperKit](https://github.com/manicmaniac/ApolloDeveloperKit)) - Apollo Client Devtools bridge for [Apollo iOS].
- <b><code>&nbsp;&nbsp;&nbsp;499⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Graphaello](https://github.com/nerdsupremacist/Graphaello)) - Type Safe GraphQL directly from SwiftUI.

<a name="ios-example" />

#### iOS Examples

- <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [frontpage-ios-app](https://github.com/apollographql/frontpage-ios-app)) - 📄 Apollo "hello world" app, for iOS.

<a name="clojurescript" />

### ClojureScript

- <b><code>&nbsp;&nbsp;&nbsp;463⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [re-graph](https://github.com/oliyh/re-graph)) - A GraphQL client for ClojureScript with bindings for re-frame applications.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [graphql-query](https://github.com/district0x/graphql-query)) - Clojure(Script) GraphQL query generation.

<a name="reasonml" />

### ReasonML

- <b><code>&nbsp;&nbsp;&nbsp;547⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [reason-apollo](https://github.com/apollographql/reason-apollo)) - ReasonML binding for Apollo Client.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [ReasonQL](https://github.com/sainthkh/reasonql)) - Type-safe and simple GraphQL Client for ReasonML developers.
- <b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [reason-urql](https://github.com/FormidableLabs/reason-urql)) - ReasonML binding for urql Client.

<a name="dart" />

### Dart

- <b><code>&nbsp;&nbsp;3273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;643🍴</code></b> [graphql-flutter](https://github.com/zino-app/graphql-flutter)) - A GraphQL client for Flutter.
- <b><code>&nbsp;&nbsp;&nbsp;492⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Artemis](https://github.com/comigor/artemis)) - A GraphQL type and query generator for Dart/Flutter.

<a name="rust" />

### Rust

- <b><code>&nbsp;&nbsp;3629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;524🍴</code></b> [async-graphql](https://github.com/async-graphql/async-graphql)) - High-performance server-side library that supports all GraphQL specifications.
- <b><code>&nbsp;&nbsp;5943⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;439🍴</code></b> [juniper](https://github.com/graphql-rust/juniper)) - GraphQL server library for Rust.
- <b><code>&nbsp;&nbsp;1247⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [graphql-client](https://github.com/tomhoule/graphql-client)) - GraphQL client library for Rust with WebAssembly (wasm) support.
- <b><code>&nbsp;&nbsp;&nbsp;372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [graphql-parser](https://github.com/graphql-rust/graphql-parser)) - A parser, formatter and AST for the GraphQL query and schema definition language for Rust.
- <b><code>&nbsp;&nbsp;1431⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [tailcall](https://github.com/tailcallhq/tailcall)) - A platform for building high-performance GraphQL backends.

<a name="rust-example" />

#### Rust Examples

- 🌎 [Warp GraphQL Juniper](graphql-rust.github.io/)
- 🌎 [Tailcall](tailcall.run/docs/)

<a name="d" />

### D (dlang)

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [graphqld](https://github.com/burner/graphqld)) - GraphQL server library for D.

<a name="r" />

### R (Rstat)

- <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [ghql](https://github.com/ropensci/ghql)) - General purpose GraphQL R client.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [graphql](https://github.com/ropensci/graphql)) - Bindings to the 'libgraphqlparser' C++ library. Parses GraphQL syntax and exports the AST in JSON format.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [gqlr](https://github.com/schloerke/gqlr)) - R GraphQL Implementation.

<a name="julia" />

### Julia

- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Diana.jl](https://github.com/codeneomatrix/Diana.jl)) - A Julia GraphQL client/server implementation.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [GraphQLClient.jl](https://github.com/DeloitteDigitalAPAC/GraphQLClient.jl)) - A Julia GraphQL client for seamless integration with a server.

<a name="crystal" />

### Crystal

- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [graphql](https://github.com/graphql-crystal/graphql)) - GraphQL server library.
- <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [graphql-crystal](https://github.com/ziprandom/graphql-crystal)) - library inspired by <b><code>&nbsp;&nbsp;5431⭐</code></b> <b><code>&nbsp;&nbsp;1420🍴</code></b> [graphql-ruby](https://github.com/rmosolgo/graphql-ruby)) & <b><code>&nbsp;&nbsp;&nbsp;246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [go-graphql](https://github.com/playlyfe/go-graphql)) & <b><code>&nbsp;&nbsp;&nbsp;220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [graphql-parser](https://github.com/graphql-dotnet/parser)).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [crystal-gql](https://github.com/itsezc/crystal-gql)) - GraphQL client shard inspired by Apollo client.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [graphql.cr](https://github.com/garymardell/graphql.cr)) - GraphQL shard.

### Ballerina

- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [graphql](https://github.com/ballerina-platform/module-ballerina-graphql)) - Ballerina standard library for GraphQL. This library provides a GraphQL client and server implementations including builtin support for GraphQL subscriptions.
- <b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [graphql CLI](https://github.com/ballerina-platform/graphql-tools)) - A CLI tool to generate Ballerina code from GraphQL schema and GraphQL schema from Ballerina code. It also provides functionality to generate usage-specific GraphQL clients using GraphQL schemas and documents.

#### Ballerina Samples

- <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Ballerina GraphQL Examples](https://github.com/ballerina-platform/module-ballerina-graphql/tree/master/examples))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Convert Weather REST API to GraphQL API](https://github.com/ThisaruGuruge/weather-rest-api-to-graphql))

<a name="tools" />

## Tools

### Tools - Editors & IDEs & Explorers

- <b><code>&nbsp;16792⭐</code></b> <b><code>&nbsp;&nbsp;1822🍴</code></b> [GraphiQL](https://github.com/graphql/graphiql)) - An in-browser IDE for exploring GraphQL.
- <b><code>&nbsp;&nbsp;6073⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;287🍴</code></b> [GraphQL Editor](https://github.com/graphql-editor/graphql-editor)) - Visual Editor & GraphQL IDE.
- <b><code>&nbsp;&nbsp;8090⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;549🍴</code></b> [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager)) - Represent any GraphQL API as an interactive graph.
- <b><code>&nbsp;&nbsp;5393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;385🍴</code></b> [Altair GraphQL Client](https://github.com/altair-graphql/altair)) - A beautiful feature-rich GraphQL Client for all platforms.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Brangr](https://github.com/networkimprov/brangr)) - A unique, user-friendly data browser/viewer for any GraphQL service, with attractive result layouts.
- 🌎 [Insomnia](insomnia.rest/) - A full-featured API client with first-party GraphQL query editor.
- 🌎 [Postman](learning.postman.com/docs/sending-requests/supported-api-frameworks/graphql/) - An HTTP Client that supports editing GraphQL queries.
- <b><code>&nbsp;41176⭐</code></b> <b><code>&nbsp;&nbsp;2149🍴</code></b> [Bruno](https://github.com/usebruno/bruno)) - Fast, open source API client, which stores collections offline-only in a Git-friendly plain text markup language.
- <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Escape GraphMan](https://github.com/Escape-Technologies/graphman)) - Generate a complete Postman collection from a GraphQL endpoint.
- 🌎 [Apollo Sandbox](sandbox.apollo.dev/) - The quickest way to navigate and test your GraphQL endpoints.
- <b><code>&nbsp;&nbsp;&nbsp;702⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [GraphQL Birdseye](https://github.com/Novvum/graphql-birdseye)) – View any GraphQL schema as a dynamic and interactive graph.
- 🌎 [AST Explorer](astexplorer.net/) - Select "GraphQL" at the top, explore the GraphQL AST and highlight different parts by clicking in the query.
- 🌎 [Firecamp - GraphQL Playground](firecamp.io/graphql) - The fastest collaborative GraphQL playground.
- <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [CraftQL](https://github.com/yamafaktory/craftql)) - A CLI tool to visualize GraphQL schemas and to output a graph data structure as a graphviz .dot format.
- <b><code>&nbsp;&nbsp;&nbsp;467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [gqt](https://github.com/eerimoq/gqt)) - Build and execute GraphQL queries in the terminal.
- 🌎 [Hackolade](studio.hackolade.com/) - Visual GraphQL schema editor to generate Schema Definition Language files without any knowledge of the GraphQL syntax. Also visualize and document existing endpoints with introspection.  Additional info and instructions 🌎 [here](hackolade.com/help/GraphQL.html)


<a name="tool-testing" />

### Tools - Testing, Prototyping & Mocking

- 🌎 [Beeceptor](beeceptor.com/graphql-mock-server/) - A no-code platform for creating AI-powered **GraphQL Mock Servers** from your schema (SDL) with rules, stateful mocking, mutation/subscription, to speed up development and integration testing.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [graphql-to-karate](https://github.com/wbaldoumas/graphql-to-karate)) - **Generate Karate API tests** from your GraphQL schemas
- <b><code>&nbsp;&nbsp;2712⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [GraphQL Faker](https://github.com/APIs-guru/graphql-faker)) - 🎲 Mock or extend your GraphQL API with faked data. No coding required.
- 🌎 [GraphQL Inspector](the-guild.dev/graphql/inspector) - A tool to **validate schemas**, compare schema changes, find breaking changes, and check document coverage against a schema.
- 🌎 [Microcks](microcks.io/) - The open source  🌎 [CNCF](www.cncf.io/projects/microcks/) project), cloud native tool for **API Mocking** and Testing with 🌎 [GraphQL support](microcks.io/blog/graphql-features-what-to-expect/) 🎥 🌎 [GraphQL conf 2023](youtu.be/UjDnrrTp7uI?si=M6S4l_Bukp9CEYl4)
- 🌎 [Keploy](keploy.io/) - Open-source AI Powered API testing tool that generates test cases and **data mocks automatically by recording real API traffic**. Supports GraphQL, REST, and gRPC.
- 🌎 [Step CI](stepci.com) - Open-Source API **Testing and Monitoring** with GraphQL support

<a name="tool-security" />

### Tools - Security

- <b><code>&nbsp;&nbsp;&nbsp;333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [GraphCrawler - The all-in-one GraphQL Security toolkit](https://github.com/gsmith257-cyber/GraphCrawler)) - The all-in-one automated penetration tester toolkit for GraphQL, written in Python
- 🌎 [Escape - The GraphQL Security Scanner](graphql.security/) - One-click security scan of your GraphQL endpoints. Free, no login required.
- <b><code>&nbsp;&nbsp;&nbsp;227⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Escape Graphinder - GraphQL Subdomain Enumeration](https://github.com/Escape-Technologies/graphinder)) – Blazing fast GraphQL endpoints finder using subdomain enumeration, scripts analysis and bruteforce.
- 🌎 [StackHawk - GraphQL Vulnerability Scanner](www.stackhawk.com/blog/automated-graphql-security-testing) - 🌎 [StackHawk](www.stackhawk.com)
- <b><code>&nbsp;&nbsp;1738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [InQL Scanner](https://github.com/doyensec/inql)) - A Burp Extension for GraphQL Security Testing
- 🌎 [GraphQL Raider](portswigger.net/bappstore/4841f0d78a554ca381c65b26d48207e6) 🌎 [BurpSuite](portswigger.net/burp)
- 🌎 [WAF for graphQL](lab.wallarm.com/api-security-solution/) - Web Application Firewall for graphQL APIs
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [GraphQL Intruder](https://github.com/davinerd/gql_intruder)) - Plugin based python script to perform GraphQL vulnerability assessment.
- <b><code>&nbsp;&nbsp;&nbsp;604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [GraphQL Cop](https://github.com/dolevf/graphql-cop)) - Security Audit Utility for GraphQL
- <b><code>&nbsp;&nbsp;&nbsp;157⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [GraphQLer](https://github.com/omar2535/GraphQLer)) - Dependency-aware dynamic GraphQL testing tool
- 🌎 [Vulert](vulert.com) - Vulert secures software by detecting vulnerabilities in open-source dependencies—without accessing your code. It supports Js, PHP, Java, Python, and more

### Tools - Browser Extensions

- <b><code>&nbsp;&nbsp;1523⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [Apollo Client Developer Tools](https://github.com/apollographql/apollo-client-devtools)) - GraphQL debugging tools for Apollo Client in the Chrome developer console
- 🌎 [GraphQL Network Inspector](chrome.google.com/webstore/detail/graphql-network-inspector/ndlbedplllcgconngcnfmkadhokfaaln) - A simple and clean chrome dev-tools extension for GraphQL network inspection.

### Tools - Docs

- <b><code>&nbsp;&nbsp;1567⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;131🍴</code></b> [graphdoc](https://github.com/2fd/graphdoc)) - Static page generator for documenting GraphQL Schema.
- <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [gqldoc](https://github.com/Code-Hex/gqldoc)) - The easiest way to make API documents for GraphQL.
- <b><code>&nbsp;&nbsp;1223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [spectaql](https://github.com/anvilco/spectaql)) - Autogenerate static GraphQL API documentation.
- 🌎 [graphql-markdown](graphql-markdown.github.io/) - Flexible documentation for GraphQL powered with Docusaurus.
- 🌎 [xyd](xyd.dev) - Generate GraphQL API docs.

### Tools - Editor Plugins

- 🌎 [Apollo GraphQL VSCode Extension](marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) - Rich editor support for GraphQL client and server development that seamlessly integrates with the Apollo platform
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/)) - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;509⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [vim-graphql](https://github.com/jparise/vim-graphql)) - A Vim plugin that provides GraphQL file detection and syntax highlighting.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [graphql-autocomplete](https://github.com/orionsoft/atom-graphql-autocomplete)) - Autocomplete and lint from a GraphQL endpoint in Atom.

### Tools - Miscellaneous

- <b><code>&nbsp;11218⭐</code></b> <b><code>&nbsp;&nbsp;1390🍴</code></b> [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator)) - GraphQL code generator based on schema and documents.
- <b><code>&nbsp;&nbsp;&nbsp;925⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [swagger-to-graphql](https://github.com/yarax/swagger-to-graphql)) - GraphQL types builder based on REST API described in Swagger. Allows to migrate to GraphQL from REST for 5 minutes
- <b><code>&nbsp;&nbsp;&nbsp;759⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin)) - A language service plugin complete and validate GraphQL query in TypeScript template strings.
- <b><code>&nbsp;&nbsp;&nbsp;478⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [apollo-tracing](https://github.com/apollographql/apollo-tracing)) - GraphQL extension that enables you to easily get resolver-level performance information as part of a GraphQL response.
- <b><code>&nbsp;&nbsp;1954⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [json-graphql-server](https://github.com/marmelab/json-graphql-server)) - Get a full fake GraphQL API with zero coding in less than 30 seconds, based on a JSON data file.
- <b><code>&nbsp;45411⭐</code></b> <b><code>&nbsp;&nbsp;2083🍴</code></b> [Prisma](https://github.com/prisma/prisma)) - Turn your database into a GraphQL API. Prisma lets you design your data model and have a production ready GraphQL API online in minutes.
- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Typetta](https://github.com/twinlogix/typetta)) - Node.js ORM written in TypeScript for type lovers. Typetta is the perfect ORM for the GraphQL + NodeJS + Typescript stack.
- <b><code>&nbsp;&nbsp;1070⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [tuql](https://github.com/bradleyboy/tuql)) - Automatically create a GraphQL server from any sqlite database.
- <b><code>&nbsp;18354⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;947🍴</code></b> [Bit](https://github.com/teambit/bit)) - Organize GraphQL API as components to be consumed with NPM or modified from any project, 🌎 [example-explanation](hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)).
- <b><code>&nbsp;&nbsp;1644⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [openapi-to-graphql](https://github.com/ibm/openapi-to-graphql)) - Take any OpenAPI Specification (OAS) or swagger and create a GraphQL interface - Two minute video and resources 🌎 [here](developer.ibm.com/open/projects/openapi-to-graphql/)
- 🌎 [Retool](retool.com/) – Internal tools builder on top of your GraphQL APIs + GraphQL IDE with a schema explorer.
- <b><code>&nbsp;&nbsp;&nbsp;114⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [dataloader-codegen](https://github.com/Yelp/dataloader-codegen)) - An opinionated JavaScript library for automatically generating predictable, type safe DataLoaders over a set of resources (e.g. HTTP endpoints).
- <b><code>&nbsp;&nbsp;1737⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [raphql-inspector](https://github.com/kamilkisiela/graphql-inspector)): alidate schema, get schema change notifications, validate operations, find breaking changes, look for similar types, schema coverage.
- <b><code>&nbsp;16005⭐</code></b> <b><code>&nbsp;&nbsp;1552🍴</code></b> [amplication](https://github.com/amplication/amplication)): Amplication is an open‑source low code development tool. It builds database applications with REST API and GraphQL for CRUD with relations, sorting, filtering, pagination.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Blendbase](https://github.com/blendbase/blendbase)): Single open-source GraphQL API to connect CRMs to your SaaS. Query any customer CRM system (Salesforce, Hubspot and more) with a single API query from your SaaS app.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [microfiber](https://github.com/anvilco/graphql-introspection-tools)) - Query and manipulate GraphQL introspection query results in useful ways.
- 🌎 [DronaHQ](www.dronahq.com/) - Build internal tools, dashboards, admin panel on top of GraphQL data in minutes
- 🌎 [Dynaboard](dynaboard.com) - Generate low-code web apps from any GraphQL API using AI.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [gqlhash](https://github.com/romshark/gqlhash)) - Lightning fast query hasher that ignores formatting diffs and comments and supports multiple hashing functions.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Apollo APQ Debugger](https://github.com/rookieInTraining/apq-debugger)) - Reveal full GraphQL queries behind Apollo APQ hashes. Inspect fallback flow and debug Automatic Persisted Queries in DevTools.
  <a name="databases" />

## Databases

- 🌎 [Cube](cube.dev) - 🌎 [Headless BI](cube.dev/blog/headless-bi) for building data applications with SQL, REST, and 🌎 [GraphQL API](cube.dev/docs/backend/graphql). Connect any database or data warehouse and instantly get a GraphQL API with sub-second latency on top of it. - <b><code>&nbsp;19558⭐</code></b> <b><code>&nbsp;&nbsp;1965🍴</code></b> [Source Code](https://github.com/cube-js/cube.js))
- 🌎 [Dgraph](dgraph.io/) - Scalable, distributed, low latency, high throughput Graph database with GraphQL as the query language
- 🌎 [EdgeDB](edgedb.com/) - The next generation object-relational database with native GraphQL support.
- 🌎 [ArangoDB](arangodb.com/) - Native multi-model database with 🌎 [GraphQL integration](www.arangodb.com/docs/3.4/foxx-reference-modules-graph-ql.html) via the built-in 🌎 [Foxx Microservices Framework](www.arangodb.com/docs/stable/foxx.html).
- <b><code>&nbsp;15692⭐</code></b> <b><code>&nbsp;&nbsp;1193🍴</code></b> [Weaviate](https://github.com/semi-technologies/weaviate)) - Weaviate is a cloud-native, modular, real-time vector search engine with a 🌎 [GraphQL interface](weaviate.io/developers/weaviate/api/graphql) built to scale your machine learning models.

<a name="services" />

## Services

- 🌎 [AWS AppSync](aws.amazon.com/appsync/) - Scalable managed GraphQL service with subscriptions for building real-time and offline-first apps
- 🌎 [FakeQL](fakeql.com/) - GraphQL API mocking as a service ... because GraphQL API mocking should be easy!
- 🌎 [Moesif API Analytics](www.moesif.com/features/graphql-analytics) - A GraphQL analaytics and monitoring service to find functional and performance issues.
- 🌎 [Booster framework](booster.cloud/) - An open-source framework that makes you _completely_ forget about infrastructure and allows you to focus exclusively on your business logic. It autogenerates a GraphQL API for your models, supporting mutations, queries, and subscriptions.
- 🌎 [Nhost](nhost.io/) - Open source Firebase alternative with GraphQL
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Saleor](https://github.com/mirumee/saleor/)) - GraphQL-first headless e-commerce platform.
- 🌎 [Stargate](stargate.io/docs/latest/quickstart/qs-graphql-cql-first.html) - Open source data gateway currently supporting Apache Cassandra&reg; and DataStax Enterprise.
- 🌎 [Vedika](vedika.io) - Vedic astrology AI API with GraphQL support for horoscopes, birth charts, kundali matching, and 108+ endpoints.
- 🌎 [Grafbase](grafbase.com) - Instant GraphQL APIs for any data source.

### CDN

- 🌎 [GraphCDN](graphcdn.io/) - GraphQL CDN for caching GraphQL APIs.

### CMS

- 🌎 [DatoCMS](www.datocms.com/) - CDN-based GraphQL based Headless Content Management System.
- 🌎 [Apito](apito.io/) - A Cloud Based Headless CMS with CDN, Webhooks, Team Collaborations, Content Revision, Cloud Functions.
- 🌎 [Hygraph](hygraph.com/) - Build Scalable Content Experiences.
- 🌎 [Cosmic](www.cosmicjs.com/) - GraphQL-powered Headless CMS and API toolkit.
- 🌎 [Graphweaver](graphweaver.com/) - Turn multiple datasources into a single GraphQL API.

<a name="book" />

## Books

- 🌎 [The GraphQL Guide](graphql.guide) by John Resig and Loren Sands-Ramshaw
- 🌎 [Craft GraphQL APIs in Elixir with Absinthe](pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) by Bruce Williams and Ben Wilson
- 🌎 [The Road to GraphQL](www.roadtographql.com/)
- 🌎 [Practical GraphQL](leanpub.com/book-graphql) by Daniel Schmitz
- 🌎 [Production Ready GraphQL](book.productionreadygraphql.com) by Marc-André Giroux
- 🌎 [Full Stack GraphQL Applications](www.manning.com/books/fullstack-graphql-applications) by William Lyon

<a name="video" />

## Videos

- 🌎 [GraphQL: The Documentary](www.youtube.com/watch?v=783ccP__No8)
- 🌎 [Zero to GraphQL in 30 Minutes](www.youtube.com/embed/UBGzsb2UkeY)
- 🌎 [Data fetching for React applications at Facebook](www.youtube.com/watch?v=9sc8Pyc51uU)
- 🌎 [React Native & Relay: Bringing Modern Web Techniques to Mobile](www.youtube.com/watch?v=X6YbAKiLCLU)
- 🌎 [Exploring GraphQL](www.youtube.com/watch?v=WQLzZf34FJ8)
- 🌎 [Creating a GraphQL Server](www.youtube.com/watch?v=gY48GW87Feo)
- 🌎 [GraphQL at The Financial Times](www.youtube.com/watch?v=S0s935RKKB4)
- 🌎 [Relay: An Application Framework For React](www.youtube.com/watch?v=IrgHurBjQbg)
- 🌎 [Building and Deploying Relay with Facebook](www.youtube.com/watch?t=643&v=Pxdgu2XIAAg)
- 🌎 [Introduction to GraphQL](vimeo.com/144817545)
- 🌎 [Exploring GraphQL@Scale](www.youtube.com/watch?v=_9RgHXqH8J0)
- 🌎 [What's Next for Phoenix by Chris McCord](www.youtube.com/watch?v=IMUpYOc9z3c&feature=youtu.be)
- 🌎 [GraphQL with Nick Schrock](www.youtube.com/watch?v=Ed6oJXKt3-M)
- 🌎 [Build a GraphQL server for Node.js using PostgreSQL/MySQL](www.youtube.com/watch?v=DNPVqK_woRQ)
- 🌎 [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](www.youtube.com/watch?v=PHabPhgRUuU)
- 🌎 [JavaScript Air Episode 023: Transitioning from REST to GraphQL](www.youtube.com/watch?v=ENqDNIp1Nd8)
- 🌎 [GraphQL Future at react-europe 2016](www.youtube.com/watch?v=ViXL0YQnioU)
- 🌎 [GraphQL at Facebook at react-europe 2016](www.youtube.com/watch?v=etax3aEe2dA)
- 🌎 [Building native mobile apps with GraphQL at react-europe 2016](www.youtube.com/watch?v=z5rz3saDPJ8)
- 🌎 [Build a GraphQL Server](www.youtube.com/watch?v=PEcJxkylcRM&list=PLillGF-RfqbYZty73_PHBqKRDnv7ikh68)
- 🌎 [GraphQL Tutorial](www.youtube.com/watch?v=Y0lDGjwRYKw&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f)
- 🌎 [Five years of GraphQL](www.youtube.com/watch?v=s8meG38iZAM)
- 🌎 [GraphQL is for Everyone by Moon Highway](moonhighway.teachable.com/p/graphql-is-for-everyone)

<a name="podcast" />

## Podcasts

- 🌎 [GraphQL.FM](podcasts.google.com/feed/aHR0cHM6Ly9hbmNob3IuZm0vcy8zNjE5NmViMC9wb2RjYXN0L3Jzcw==) by Marc-Andre Giroux and Tony Ghita.

<a name="style-guide" />

## Style Guides

- <b><code>&nbsp;&nbsp;2460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;190🍴</code></b> [Shopify GraphQL Design Tutorial](https://github.com/Shopify/graphql-design-tutorial)) - This tutorial was originally created by Shopify for internal purposes. It's based on lessons learned from creating and evolving production schemas at Shopify over almost 3 years.
- 🌎 [GitLab GraphQL API Style Guide](docs.gitlab.com/ee/development/api_graphql_styleguide.html) - This document outlines the style guide for the GitLab GraphQL API.
- 🌎 [Yelp GraphQL Guidelines](yelp.github.io/graphql-guidelines/) - This repo contains documentation and guidelines for a standardized and mostly reasonable approach to GraphQL (at Yelp).
- 🌎 [Principled GraphQL](principledgraphql.com/) - Apollo's 10 GraphQL Principles, broken out into three categories, in a format inspired by the Twelve Factor App.

<a name="blogs" />

## Blogs

- 🌎 [Official GraphQL blog](graphql.org/blog/)
- 🌎 [Building Apollo](blog.apollographql.com/)
- 🌎 [The Guild blog](medium.com/the-guild)
- 🌎 [Production Ready GraphQL blog](productionreadygraphql.com)

<a name="security-blog" />

### Blogs - Security

- 🌎 [Escape - The GraphQL Security Blog](escape.tech/blog) - Learn about GraphQL security, performance, testing and building production-ready APIs with the latest tools and best practices of the GraphQL ecosystem.
- 🌎 [9 GraphQL Security Best Practices](escape.tech/blog/9-graphql-security-best-practices/)
- 🌎 [Discovering GraphQL Endpoints and SQLi Vulnerabilities](medium.com/@localh0t/discovering-graphql-endpoints-and-sqli-vulnerabilities-5d39f26cea2e)
- 🌎 [Securing GraphQL API](lab.wallarm.com/securing-graphql-api/)
- 🌎 [Security Points to Consider Before Implementing GraphQL](nordicapis.com/security-points-to-consider-before-implementing-graphql/)
- 🌎 [Authorization Patterns in GraphQL](www.osohq.com/post/graphql-authorization)

<a name="post" />

## Posts

- 🌎 [GraphQL federation example with Apollo Federation and Apollo GraphOS](cube.dev/blog/graphql-federation-example-with-apollo-federation-and-apollo-graphos)
- 🌎 [GraphQL federation with Hasura GraphQL Engine and Cube](cube.dev/blog/graphql-federation-with-hasura-graphql-engine)
- 🌎 [Using DataLoader to batch GraphQL requests](medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433)
- 🌎 [Introducing Relay and GraphQL](reactjs.org/blog/2015/02/20/introducing-relay-and-graphql.html)
- 🌎 [GraphQL Introduction](reactjs.org/blog/2015/05/01/graphql-introduction.html)
- 🌎 [Unofficial Relay FAQ](gist.github.com/wincent/598fa75e22bdfa44cf47)
- 🌎 [Your First GraphQL Server](medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2)
- 🌎 [GraphQL Overview - Getting Started with GraphQL and Node.js](blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
- 🌎 [4 Reasons you should try out GraphQL](medium.freecodecamp.org/introduction-to-graphql-1d8011b80159)
- 🌎 [Moving from REST to GraphQL](medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
- [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
- 🌎 [Building a GraphQL Server with Node.js and SQL](www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
- 🌎 [GraphQL at The Financial Times](www.slideshare.net/LondonReact/graph-ql)
- 🌎 [Implementing GraphQL RBAC Authorization: A Practical Guide](www.permit.io/blog/implementing-graphql-authorization)
- 🌎 [From REST to GraphQL](jacobwgillespie.com/2015-10-09-from-rest-to-graphql)
- 🌎 [GraphQL: A data query language](graphql.org/blog/graphql-a-query-language/)
- 🌎 [Subscriptions in GraphQL and Relay](graphql.org/blog/subscriptions-in-graphql-and-relay/)
- 🌎 [Relay 101: Building A Hacker News Client](medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6)
- 🌎 [GraphQL Shorthand Notation Cheatsheet](wehavefaces.net/graphql-shorthand-notation-cheatsheet-17cd715861b6)
- 🌎 [The GitHub GraphQL API](githubengineering.com/the-github-graphql-api/)
- 🌎 [Github GraphQL API React Example](medium.com/@katopz/github-graphql-api-react-example-eace824d7b61)
- 🌎 [Testing a GraphQL Server using Jest](medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e)
- 🌎 [How to implement viewerCanSee in GraphQL](medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464)
- 🌎 [Preventing traversal attacks on your GraphQL API](blog.morethancode.dev/preventing-traversal-attacks-in-your-graphql-api/)
- 🌎 [Mock your GraphQL server realistically with faker.js](dev.to/yvonnickfrin/mock-your-graphql-server-realistically-with-faker-js-25oo)
- 🌎 [Create an infinite loading list with React and GraphQL](dev.to/yvonnickfrin/create-an-infinite-loading-list-with-react-and-graphql-19hh)
- 🌎 [REST vs GraphQL](www.moesif.com/blog/technical/graphql/REST-vs-GraphQL-APIs-the-good-the-bad-the-ugly/)
- 🌎 [Authentication and Authorization for GraphQL APIs](www.moesif.com/blog/technical/api-design/Steps-to-Building-Authentication-and-Authorization-For-GraphQL-APIs/)
- 🌎 [Build a GraphQL API with Siler on top of Swoole](www.swoole.co.uk/article/Build-a-GraphQL-API-on-top-of-Swoole)
- 🌎 [Fluent GraphQL clients: how to write queries like a boss](hasura.io/blog/fluent-graphql-clients-how-to-write-queries-like-a-boss/)
- 🌎 [Level up your serverless game with a GraphQL data-as-a-service layer](hasura.io/blog/level-up-your-serverless-game-with-a-graphql-data-as-a-service-layer/)
- 🌎 [A deep-dive into Relay, the friendly & opinionated GraphQL client](hasura.io/blog/deep-dive-into-relay-graphql-client/)
- 🌎 [make your graphql api easier to adopt through components](hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)
- 🌎 [Undocumented: keeping parts of your GraphQL schema hidden from introspection](www.useanvil.com/blog/engineering/undocumented-directive/)
- 🌎 [GraphQL Subscriptions with Apache Kafka in Ballerina](medium.com/ballerina-techblog/graphql-subscriptions-with-apache-kafka-in-ballerina-b3c296d333cd)
- 🌎 [How to Test your GraphQL Endpoints](escape.tech/blog/8-most-common-graphql-vulnerabilities/)
- 🌎 [Why Automatic Persisted Queries Don't Scale](blog.tailcall.run/the-truth-about-scaling-automatic-persisted-queries/)

<a name="tutorials" />

## Tutorials

- 🌎 [How to GraphQL](www.howtographql.com) - Fullstack Tutorial Website with Tracks for all Major Frameworks & Languages including React, Apollo, Relay, JavaScript, Ruby, Java, Elixir and many more.
- 🌎 [Apollo Odyssey](odyssey.apollographql.com/) - Apollo's free interactive learning platform.
- <b><code>&nbsp;&nbsp;&nbsp;937⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [learning-graphql](https://github.com/mugli/learning-graphql)) - An attempt to learn GraphQL.
- 🌎 [GraphQL Roadmap](roadmap.sh/graphql) - Step by step guide to learn GraphQL.
- 🌎 [GraphQL Security Academy](escape.tech/academy/) - a free and interactive platform to learn GraphQL security: how to find, exploit and fix GraphQL vulnerabilities.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Chen-Tsu Lin](https://github.com/chentsulin) has waived all copyright and related or neighboring rights to this work.

## Source
<b><code>&nbsp;14983⭐</code></b> <b><code>&nbsp;&nbsp;1240🍴</code></b> [chentsulin/awesome-graphql](https://github.com/chentsulin/awesome-graphql))