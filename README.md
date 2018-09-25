# ShopifyCheckoutCustomizationTricks

Shopify checkout page (checkout.liquid) available to Shopify Plus merchants only. If your store isn't on Shopify Plus / Shopify Gold, then you can customize your checkout pages in the theme editor.

Basically, Shopify checkout page(checkout.liquid) hold 4 phase of checkout of your shopify store. These are
1. Customer Information.
2. Shipping Methods.
3. Payment Methods.
4. Order Thank You / Order Status.

In default case of Shopify checkout page(checkout.liquid), there are many objects called by shopify but there are two major objects required to execute Shopify checkout page(checkout.liquid). Give below are required and optional objects needs to call on Shopify checkout page(checkout.liquid) file.

Required objects
1. {{ content_for_header }} variable  must be placed between the opening and closing <head> tag
2. {{ content_for_layout }} variable must be placed between the opening and closing <body> tag. It dynamically outputs the form fields and content for each step of the checkout process.
  
Optional objects
1. {{ checkout_html_classes }}

2 .{{ checkout_stylesheets }}
3. {{ checkout_scripts }}
4. {{ checkout }}
5. {{ content_for_logo }}
6. {{ order_summary_toggle }}
7. {{ content_for_order_summary }}
8. {{ breadcrumb }}
9. {{ alternative_payment_methods }}
10.{{ content_for_footer }}
11.{{ tracking_code }}

You can find more descriptive details from shopify.com
