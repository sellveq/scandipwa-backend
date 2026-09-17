# selveq/scandipwa-backend

The metapackage that installs the Selveq-maintained ScandiPWA backend modules for Magento 2.4.9.

## Install

```sh
composer require selveq/scandipwa-backend
bin/magento setup:upgrade
```

## Includes

- `selveq/installer`
- `selveq/module-core`
- `selveq/service-worker`
- `selveq/cache`
- `selveq/persisted-query`
- `selveq/slider-graphql`
- `selveq/cms-graphql`
- `selveq/catalog-graphql`
- `selveq/route717`
- `selveq/performance`
- `selveq/customer-graphql`
- `selveq/quote-graphql`
- `selveq/wishlist-graphql`
- `selveq/urlrewrite-graphql`
- `selveq/store-graphql`
- `selveq/customization`
- `selveq/locale`
- `selveq/contact-graphql`
- `selveq/compare-graphql`
- `selveq/customer-downloadable-graphql`
- `selveq/directory-graphql`
- `selveq/product-alerts-graphql`
- `selveq/sales-graphql`
- `selveq/catalog-customer-graphql`
- `selveq/review-graphql`

`selveq/menu-organizer` and `selveq/slider` are installed separately because a store may not want either, though `selveq/slider-graphql` requires `selveq/slider` and so brings it in anyway.

## License

[MIT](LICENSE).
