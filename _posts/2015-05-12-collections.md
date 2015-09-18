# Collection

Due to restrictions with Shopify Collections, in order to customise the look and feel for each Collection we match a Product to the Collection (what we refer to as a Collection Product) and use the Collection Product attributes to customise the look and feel of the Collection.

A Collection can have multiple Collection Products.

### Creating a new Collection and Collection Product
1. Create a Collection
2. Save the Collection
3. Create a Product
4. Set the template of the Product to `product.collection`
5. Add the Product to the Collection
6. Go to Online Store/Navigation/Collections
7. In the Links section, click Add another link
8. Enter the collection name, select Links to... Collection, and select the corresponding collection
9. Hit Save!

## Collection Listing

Each Collection Product is shown on the [Collection Listing](https://ampal.myshopify.com/collections) page.

### Ordering collections
1. Go to Online Store/Navigation/Collections
2. Under ‘Links,’ drag collections into the desired order

### Ordering Collection Products
1. Go to the Collection
2. Under Products changed sort to `Manually`
3. Drag Products to re-order

### Collection title

The title can be set by updating the Collection title.

### Collection Product location

The location can be set by updating the Collection Product title.

### Collection Videos

You can embed a Vimeo video by creating a Collection Product with the template
`product.collection_video` and setting the product SKU for the first variant as the Vimeo video ID.
 
e.g. How to add this video: https://vimeo.com/103752297 to S-S 2013
 
1. Create a new Product
2. Type the title `Ampal Creative x Venice Originals`
3. Under Collections select `S—S 2013`
4. Under Inventory type the Vimeo ID into the SKU field, `103752297`
5. Under Variants click `Add Variant`
6. Under option values type `S` (This value doesn't matter, we just need a variant)
7. Click `Save Product`
 
The video will now appear on the Collections page under the S-S 2013.

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

You can find the exact product name by going to *Search engine listing preview* on a product page and clicking *Edit website SEO*. The end of the URL is the exact product name.

## Image caption

You can add a caption to an image by updating the `alt` tag for the image.
 
If the image has a product reference, you need to separate the caption and the product reference with an `*`.  
e.g. `product:dottie-bucket*The image caption will follow.`
