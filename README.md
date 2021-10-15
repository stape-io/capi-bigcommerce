# Facebook Conversion API for Bigcommerce

We've created Google Tag Manager web and server container templates for BigCommerce that you can use to set up Facebook conversion API. 
These containers work for the Stencil theme and optimized one-page checkout.

To make these containers work you should add scripts to the BigCommerce that will send product and user data to the data layer. 
Facebook browser tracking should be set up using the Google Tag Manager web container, not the BigCommerce app for FB.

### Getting started

1. Create and set up a Google Tag Manager web container.
2. Add web GTM script to BigCommerce.
3. Add [scripts](https://github.com/stape-io/capi-bigcommerce/blob/main/dataLayer_script_manager.html) that send user and products data to the data layer for the BigCommerce site.
3. Create and set up a Google Tag Manager server container.
4. Import [Web](https://github.com/stape-io/capi-bigcommerce/blob/main/bigcommerce_no_container_id_web.json) and [Server Google Tag Manager](https://github.com/stape-io/capi-bigcommerce/blob/main/bigcommerce_no_container_id_server.json) containers.
5. Update variables with your values.

More detailed description of [how to set up Facebook conversion API for BigCommerce](https://stape.io/facebook-conversion-api-for-bigcommerce/) can be found by this link.

### Supported events:

- PageView
- ViewContent
- AddToCart
- CustomizeProduct
- AddPaymentInfo
- CompleteRegistration
- InitiateCheckout
- Purchase

## Open Source

Developed and maintained by [Stape Team](https://stape.io/) under the MIT license.
