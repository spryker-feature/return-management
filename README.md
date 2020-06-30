# Spryker Feature: Return Management

Return Management enables not only to manage the reverse product flow efficiently but to identify opportunities to reduce unwanted returns.
Return Management allows Customers and Back-office users to select items that should be returned, create returns itself and add return reasons for these items. 
Return Management also includes a Global return policy that defines Return days during what purchased product can be returned.

## Installation

```
composer require spryker-feature/return-management
```

## Recommended feature dependencies
- [spryker-feature/order-management](https://github.com/spryker-feature/order-management)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [SalesReturnGuiExtension ^1.0.0](https://github.com/spryker/sales-return-gui-extension) (Extension)
- [Shop.SalesReturnPageExtension ^1.0.0](https://github.com/spryker-shop/sales-return-page-extension) (Extension)
- [SalesReturnsRestApi ^1.0.0](https://github.com/spryker/sales-returns-rest-api) (Glue)
