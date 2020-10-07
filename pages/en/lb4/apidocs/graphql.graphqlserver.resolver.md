---
lang: en
title: 'API docs: graphql.graphqlserver.resolver'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/extensions/graphql
permalink: /doc/en/lb4/apidocs.graphql.graphqlserver.resolver.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/graphql](./graphql.md) &gt; [GraphQLServer](./graphql.graphqlserver.md) &gt; [resolver](./graphql.graphqlserver.resolver.md)

## GraphQLServer.resolver() method

Register a GraphQL resolver class

<b>Signature:</b>

```typescript
resolver(resolverClass: Constructor<ResolverInterface<object>>, nameOrOptions?: string | BindingFromClassOptions): Binding<any>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  resolverClass | [Constructor](./context.constructor.md)<!-- -->&lt;ResolverInterface&lt;object&gt;&gt; | GraphQL resolver class |
|  nameOrOptions | string \| [BindingFromClassOptions](./context.bindingfromclassoptions.md) | Resolver name or binding options |

<b>Returns:</b>

[Binding](./context.binding.md)<!-- -->&lt;any&gt;

