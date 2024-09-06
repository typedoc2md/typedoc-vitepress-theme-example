[dummy-typescript-api](../../index.md) / [billing](../index.md) / TransactionStatus

# TransactionStatus

Enum representing different transaction statuses.
These statuses indicate the current state of a billing transaction in the process pipeline.

## Enumeration Members

### Completed

```ts
Completed: "Completed";
```

Transaction has been successfully processed.

***

### Failed

```ts
Failed: "Failed";
```

Transaction failed due to an error or rejection.

***

### Pending

```ts
Pending: "Pending";
```

Transaction has been initiated but not yet processed.
