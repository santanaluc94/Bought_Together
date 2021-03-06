# Frequently Bought Together

## Installation

To download the module by composer, execute this code bellow.

```sh
  composer require magezil/module-bought-together
```

### System Requirements

> **Requires at least:** 2.O
>
> **Tested up to:** 2.3
> 
> **Requires PHP:** 7.0
> 
> **Stable tag**: 1.0
> 
> **Licenses:** OSL-3.0/AFL-3.0

---

## Magento Admin

This module adds a block in product page, which insert all products that were bought together with the product on the page. It is possible to edit the title and how many products will display in this block. To enable this module, follow these steps:
  - **Step 1:** Magento admin -> Stores -> Settings -> Configurations
  - **Setp 2:** Tab _Magezil_ -> Section _Frequently Bought Together_ -> Group _General Configuration_
  - **Setp 3:** Enable Module = Yes

![ScreenShot](https://github.com/santanaluc94/CustomModules_BoughtTogether/blob/master/Readme/magezil-module.jpg)

### General settings

This module provides some settings in admin:
  - Show block only when the user is logged in;
  - Edit title block;
  - Quantity of products to display on frontend (to do not apply this filter, just leave it empty).

![ScreenShot](https://github.com/santanaluc94/Magezil_BoughtTogether/blob/master/Readme/general-settings.jpg)

### Cards settings

This module provides some settings to cards in this block to:
  - Show button add to wishlist in list products;
  - Show button add to compare in list products;
  - Show quantity products to add to cart in list products.

![ScreenShot](https://github.com/santanaluc94/Magezil_BoughtTogether/blob/master/Readme/cards-settings.jpg)

---

## Store Frontend

The results of the product page follows below with all settings enabled.

Listing product:
![ScreenShot](https://github.com/santanaluc94/Magezil_BoughtTogether/blob/master/Readme/block-frontend.jpg)

Card product:
![ScreenShot](https://github.com/santanaluc94/Magezil_BoughtTogether/blob/master/Readme/listing-product.jpg)

