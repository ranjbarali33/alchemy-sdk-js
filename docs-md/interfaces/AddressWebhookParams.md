[alchemy-sdk](../README.md) / [Exports](../modules.md) / AddressWebhookParams

# Interface: AddressWebhookParams

Params to pass in when calling [NotifyNamespace.createWebhook](../classes/NotifyNamespace.md#createwebhook) in order
to create a [AddressActivityWebhook](AddressActivityWebhook.md).

## Table of contents

### Properties

- [addresses](AddressWebhookParams.md#addresses)
- [network](AddressWebhookParams.md#network)

## Properties

### addresses

• **addresses**: `string`[]

Array of addresses the webhook should activity for.

#### Defined in

[src/types/types.ts:2337](https://github.com/alchemyplatform/alchemy-sdk-js/blob/46e9716/src/types/types.ts#L2337)

___

### network

• `Optional` **network**: [`Network`](../enums/Network.md)

Optional network to create the webhook on. If omitted, the webhook will be
created on network of the app provided in the api key config.

#### Defined in

[src/types/types.ts:2342](https://github.com/alchemyplatform/alchemy-sdk-js/blob/46e9716/src/types/types.ts#L2342)
