[dummy-typescript-api](../../index.md) / [customer](../index.md) / CustomerService

# CustomerService

Service for managing customers.

## Constructors

### new CustomerService()

```ts
new CustomerService(): CustomerService
```

#### Returns

[`CustomerService`](CustomerService.md)

## Methods

### addCustomer()

```ts
addCustomer(
   customer, 
   contactInfo, 
   billingInfo): CustomerAccount
```

Add a new customer.

#### Parameters

• **customer**: [`Customer`](../interfaces/Customer.md)

The customer to be added.

• **contactInfo**: [`CustomerContact`](../interfaces/CustomerContact.md)

The contact information for the customer.

• **billingInfo**: [`CustomerBilling`](../interfaces/CustomerBilling.md)

The billing information for the customer.

#### Returns

[`CustomerAccount`](CustomerAccount.md)

The added customer account.

***

### getAllCustomers()

```ts
getAllCustomers(): CustomerAccount[]
```

Get all customer accounts.

#### Returns

[`CustomerAccount`](CustomerAccount.md)[]

An array of all customer accounts.

***

### getCustomerById()

```ts
getCustomerById(customerId): CustomerAccount
```

Get a customer account by ID.

#### Parameters

• **customerId**: `string`

The ID of the customer.

#### Returns

[`CustomerAccount`](CustomerAccount.md)

The customer account with the specified ID.
