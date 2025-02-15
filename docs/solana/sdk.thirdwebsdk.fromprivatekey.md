---
slug: /sdk.thirdwebsdk.fromprivatekey
title: ThirdwebSDK.fromPrivateKey() method
hide_title: true
displayed_sidebar: solana
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# ThirdwebSDK.fromPrivateKey() method

Create a new SDK instance connected with the given private key

**Signature:**

```typescript
static fromPrivateKey(network: Network, privateKey: string, storage?: ThirdwebStorage): ThirdwebSDK;
```

## Parameters

| Parameter  | Type                        | Description                                                 |
| ---------- | --------------------------- | ----------------------------------------------------------- |
| network    | [Network](./sdk.network.md) | The network to connect to                                   |
| privateKey | string                      | The private key to use                                      |
| storage    | ThirdwebStorage             | _(Optional)_ The storage provider to use or IPFS by default |

**Returns:**

[ThirdwebSDK](./sdk.thirdwebsdk.md)

an SDK instance
