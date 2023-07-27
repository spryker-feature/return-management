# Spryker Feature: Return Management

Return Management enables not only to manage the reverse product flow efficiently but to identify opportunities to reduce unwanted returns.
Return Management allows Customers and Back-office users to select items that should be returned, create returns itself and add return reasons for these items. 
Return Management also includes a Global return policy that defines Return days during what purchased product can be returned.

[Learn more](https://docs.spryker.com/docs/pbc/all/return-management/202307.0/base-shop/return-management-feature-overview.html)

## Installation

```
composer require spryker-feature/return-management
```

## Recommended feature dependencies
- [spryker-feature/order-management](https://github.com/spryker-feature/order-management)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [SalesReturnExtension ^1.2.0](https://github.com/spryker/sales-return-extension) (Extension)
- [SalesReturnGuiExtension ^1.2.0](https://github.com/spryker/sales-return-gui-extension) (Extension)
- [Shop.SalesReturnPageExtension ^1.0.0](https://github.com/spryker-shop/sales-return-page-extension) (Extension)
- [SalesReturnsRestApi ^1.1.0](https://github.com/spryker/sales-returns-rest-api) (Legacy Glue)
