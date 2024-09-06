[dummy-typescript-api](../../index.md) / [products](../index.md) / ProductInventory

# ProductInventory

Class representing a product inventory.

## Constructors

### new ProductInventory()

```ts
new ProductInventory(): ProductInventory
```

#### Returns

[`ProductInventory`](ProductInventory.md)

## Methods

### addProduct()

```ts
addProduct(product): ProductDetails
```

Add a new product to the inventory.

#### Parameters

• **product**: [`ProductDetails`](../interfaces/ProductDetails.md)

The product to be added.

#### Returns

[`ProductDetails`](../interfaces/ProductDetails.md)

The added product details.

***

### getAllProducts()

```ts
getAllProducts(): ProductDetails[]
```

Get all products in the inventory.

#### Returns

[`ProductDetails`](../interfaces/ProductDetails.md)[]

An array of all product details.

***

### getProductById()

```ts
getProductById(productId): ProductDetails
```

Get product details by ID.

#### Parameters

• **productId**: `string`

The ID of the product.

#### Returns

[`ProductDetails`](../interfaces/ProductDetails.md)

The product details with the specified ID.

***

### getProductsByCategory()

```ts
getProductsByCategory(category): ProductDetails[]
```

Get products by category.

#### Parameters

• **category**: [`ProductCategory`](../enumerations/ProductCategory.md)

The product category.

#### Returns

[`ProductDetails`](../interfaces/ProductDetails.md)[]

An array of product details in the specified category.

***

### removeProduct()

```ts
removeProduct(productId): ProductDetails
```

Remove a product from the inventory.

#### Parameters

• **productId**: `string`

The ID of the product to be removed.

#### Returns

[`ProductDetails`](../interfaces/ProductDetails.md)

The removed product details.

***

### updateProductDetails()

```ts
updateProductDetails(productId, updatedDetails): ProductDetails
```

Update product details.

#### Parameters

• **productId**: `string`

The ID of the product to be updated.

• **updatedDetails**: [`ProductDetails`](../interfaces/ProductDetails.md)

The updated product details.

#### Returns

[`ProductDetails`](../interfaces/ProductDetails.md)

The updated product details.
