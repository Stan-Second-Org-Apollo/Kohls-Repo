# Product Added to Cart

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Product Added to Cart",
    "product": [
        {
            "fulfillment": {
                "isBopusCartAdd": "<isBopusCartAdd>"
            },
            "productInfo": {
                "collection": "<collection>",
                "productID": "<productID>",
                "sephoraBirthdayOffer": "<sephoraBirthdayOffer>"
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|collection|string|The product collection at the time of cart add and product view.||||||||
|isBopusCartAdd|integer|Count of times the user added a product to the cart with a BOSS shipping method selected.||||||||
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||
|sephoraBirthdayOffer|boolean|Customer adds a Sephora Birthday Gift Offer to their cart.||||||||
