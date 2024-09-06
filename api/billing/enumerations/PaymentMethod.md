[dummy-typescript-api](../../index.md) / [billing](../index.md) / PaymentMethod

# PaymentMethod

Enum representing different types of payment methods.
These are used to specify the payment mechanism chosen by a customer.

## Enumeration Members

### BankTransfer

```ts
BankTransfer: "Bank Transfer";
```

Payment via direct bank transfer. Used typically for larger transactions or where credit cards and PayPal are not viable.

***

### CreditCard

```ts
CreditCard: "Credit Card";
```

Payment through credit card.

***

### PayPal

```ts
PayPal: "PayPal";
```

Payment through PayPal. Ideal for users who prefer not to directly use their credit card details.
