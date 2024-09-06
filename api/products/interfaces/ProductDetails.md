[dummy-typescript-api](../../index.md) / [products](../index.md) / ProductDetails

# ProductDetails

Interface representing product details.
Extends the basic Product interface to include more comprehensive attributes for detailed product management.

## Extends

- [`Product`](Product.md)

## Properties

### category

```ts
category: ProductCategory;
```

Category of the product as defined by the ProductCategory enum. This categorization helps in organizing products
into sections or departments, facilitating easier product discovery and management.

***

### description

```ts
description: string;
```

Detailed textual description of the product. This provides potential buyers with more information about the
product's features, usage, and benefits.

***

### name

```ts
name: string;
```

Name of the product.

#### Inherited from

[`Product`](Product.md).[`name`](Product.md#name)

***

### price

```ts
price: number;
```

Price of the product in the system's set currency.

#### Inherited from

[`Product`](Product.md).[`price`](Product.md#price)

***

### productId

```ts
productId: string;
```

Unique identifier for the product.

#### Inherited from

[`Product`](Product.md).[`productId`](Product.md#productid)
