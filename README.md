## Reproduction for Prisma generate bug

With a fairly basic many to many relation, prisma will produce conflicting types:

```
npm install
npm run generate
npm run type
```

## version info:

```
prisma                  : 4.8.0
@prisma/client          : 4.8.0
Current platform        : darwin-arm64
Query Engine (Node-API) : libquery-engine d6e67a83f971b175a593ccc12e15c4a757f93ffe (at node_modules/.pnpm/@prisma+engines@4.8.0/node_modules/@prisma/engines/libquery_engine-darwin-arm64.dylib.node)
Migration Engine        : migration-engine-cli d6e67a83f971b175a593ccc12e15c4a757f93ffe (at node_modules/.pnpm/@prisma+engines@4.8.0/node_modules/@prisma/engines/migration-engine-darwin-arm64)
Introspection Engine    : introspection-core d6e67a83f971b175a593ccc12e15c4a757f93ffe (at node_modules/.pnpm/@prisma+engines@4.8.0/node_modules/@prisma/engines/introspection-engine-darwin-arm64)
Format Binary           : prisma-fmt d6e67a83f971b175a593ccc12e15c4a757f93ffe (at node_modules/.pnpm/@prisma+engines@4.8.0/node_modules/@prisma/engines/prisma-fmt-darwin-arm64)
Format Wasm             : @prisma/prisma-fmt-wasm 4.8.0-61.d6e67a83f971b175a593ccc12e15c4a757f93ffe
Default Engines Hash    : d6e67a83f971b175a593ccc12e15c4a757f93ffe
Studio                  : 0.479.0
```
