[dummy-typescript-api](../../index.md) / [products](../index.md) / ProductReviewService

# ProductReviewService

Service for managing product reviews.

## Constructors

### new ProductReviewService()

```ts
new ProductReviewService(): ProductReviewService
```

#### Returns

[`ProductReviewService`](ProductReviewService.md)

## Methods

### addProductReview()

```ts
addProductReview(review): ProductReview
```

Add a new product review.

#### Parameters

• **review**: [`ProductReview`](../interfaces/ProductReview.md)

The product review to be added.

#### Returns

[`ProductReview`](../interfaces/ProductReview.md)

The added product review.

***

### getAverageRating()

```ts
getAverageRating(productId): number
```

Get the average rating for a specific product.

#### Parameters

• **productId**: `string`

The ID of the product.

#### Returns

`number`

The average rating for the specified product.

***

### getProductReviews()

```ts
getProductReviews(productId): ProductReview[]
```

Get all product reviews for a specific product.

#### Parameters

• **productId**: `string`

The ID of the product.

#### Returns

[`ProductReview`](../interfaces/ProductReview.md)[]

An array of product reviews for the specified product.
