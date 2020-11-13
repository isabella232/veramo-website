---
id: daf-core.idatastore.datastoresaveverifiablecredential
title: IDataStore.dataStoreSaveVerifiableCredential() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Packages](./index.md) &gt; [daf-core](./daf-core.md) &gt; [IDataStore](./daf-core.idatastore.md) &gt; [dataStoreSaveVerifiableCredential](./daf-core.idatastore.datastoresaveverifiablecredential.md)

## IDataStore.dataStoreSaveVerifiableCredential() method

Saves verifiable credential to the data store

<b>Signature:</b>

```typescript
dataStoreSaveVerifiableCredential(args: IDataStoreSaveVerifiableCredentialArgs): Promise<string>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  args | [IDataStoreSaveVerifiableCredentialArgs](./daf-core.idatastoresaveverifiablecredentialargs.md) | verifiable credential |

<b>Returns:</b>

Promise&lt;string&gt;

a promise that resolves to the hash of the VerifiableCredential