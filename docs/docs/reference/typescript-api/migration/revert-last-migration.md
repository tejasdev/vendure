---
title: "RevertLastMigration"
weight: 10
date: 2023-07-20T13:56:15.769Z
showtoc: true
generated: true
---
<!-- This file was generated from the Vendure source. Do not modify. Instead, re-run the "docs:build" script -->
import MemberInfo from '@site/src/components/MemberInfo';
import GenerationInfo from '@site/src/components/GenerationInfo';
import MemberDescription from '@site/src/components/MemberDescription';


## revertLastMigration

<GenerationInfo sourceFile="packages/core/src/migrate.ts" sourceLine="82" packageName="@vendure/core" />

Reverts the last applied database migration. See [TypeORM migration docs](https://typeorm.io/#/migrations)
for more information about the underlying migration mechanism.

```ts title="Signature"
function revertLastMigration(userConfig: Partial<VendureConfig>): void
```
Parameters

### userConfig

<MemberInfo kind="parameter" type="Partial&#60;<a href='/typescript-api/configuration/vendure-config#vendureconfig'>VendureConfig</a>&#62;" />
