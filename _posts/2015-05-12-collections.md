# Collection

Due to restrictions with Shopify Collections, in order to customise the look and feel for each Collection we match a Product to the Collection (what we refer to as a Collection Product) and use the Collection Product attributes to customise the look and feel of the Collection.

A Collection can have multiple Collection Products.

### Creating a new Collection and Collection Product
1. Create a Collection
2. Take note of the handle e.g. `ss2015`
3. Save the Collection
4. Create a Product
5. Set the template of the Product to `product.collection`
6. Add the Product to the Collection

## Collection Listing

Each Collection Product is shown on the [Collection Listing](https://ampal.myshopify.com/collections) page.

### Collection title

The title can be set by updating the Collection title.

### Collection Product location

The location can be set by updating the Collection Product title.

## Collection Detail

## Location title

The location title can be set by updating the `location.title` metafield for the Collection Product.

## Location description

The location description can be set by updating the Collection Product description.  

## Location meta

The location meta can be set by updating the `location.meta` metafield for the Collection Product.  
e.g. `Shot on location in Malibu by Heather Gildroy`

## Image product

You can reference an image to a product by adding the product handle to the alt tag prefixed by `product:`.  
e.g. `product:dottie-bucket`

## Image caption

You can add a caption to an image by updating the `alt` tag for the image.
 
If the image has a product reference, you need to separate the caption and the product reference with an `*`.  
e.g. `product:dottie-bucket*The image caption will follow.`