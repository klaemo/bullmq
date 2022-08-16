<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [QueueBaseOptions](./bullmq.queuebaseoptions.md)

## QueueBaseOptions interface

Base Queue options

<b>Signature:</b>

```typescript
export interface QueueBaseOptions 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [blockingConnection?](./bullmq.queuebaseoptions.blockingconnection.md) | boolean | <i>(Optional)</i> Denotes commands should retry indefinitely. |
|  [connection?](./bullmq.queuebaseoptions.connection.md) | [ConnectionOptions](./bullmq.connectionoptions.md) | <i>(Optional)</i> Options for connecting to a Redis instance. |
|  [prefix?](./bullmq.queuebaseoptions.prefix.md) | string | <i>(Optional)</i> Prefix for all queue keys. |
|  [sharedConnection?](./bullmq.queuebaseoptions.sharedconnection.md) | boolean | <i>(Optional)</i> Specify if the connection is shared. |
