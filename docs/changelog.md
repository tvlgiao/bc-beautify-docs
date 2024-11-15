# Release Notes

## 1.5.4 (11-15-2024)
- Update Stencil using Node 20.17
- bump bigcommerce/stencil-utils to 6.18.0
- fix scss warning theme-mobile.scss

## 1.5.3 (11-08-2024)
- Fix browser crash when editing options in Bulk Order layout with products that have an empty file
- Fix undefined 'input-font-color' in add payment methods account page

## 1.5.2 (07-26-2024)
- Fix qty input syntax error on cart/content.html
- Update Supermarket 7.0.6:
  - [CORNERSTONE] Extended initialization interface of the storefront-account-payments lib, added theme styles [#2335][https://github.com/bigcommerce/cornerstone/pull/2335]

## 1.5.1 (06-28-2024)
- Fix currency dropdown not visible in Grocery style.
- Remove dropdown background color and border color of navUser.

## 1.5.0 (06-21-2024)
- Update deprecated emitOnErrors
- fix jstree color
- Fix brands grid, widget layout beautify-grid6 not center
- Update [Supermarket 7.0.5](https://papathemes.com/blog/bigcommerce-supermarket-theme-release-notes/).

## 1.4.2 (09-22-2023)
- Fix cart quantity input change not working
- Fix to prevent mega menu from overflowing right edge of page
- Update Webpack 5 + Node 18

## 1.4.1 (06-29-2023)
- Fix issue with deleting cart item in version 1.4.0

## 1.4.0 (06-22-2023)
- Fix edit cart item display incorrect message when product is unavailable / out of stock
- Fixed unavailable options' strikeout display during cart edit
- Fix SCSS compiler in fonts-icons.scss for Node 16
- Increase warning of asset size limit to 500KB

## 1.3.4 (05-12-2023)
- Display final price after non sale price in price range on PDP

## 1.3.3 (04-20-2023)
- Fix SCSS Compiler

## 1.3.2 (03-09-2023)
- Style PayPal GPay Venmo additional checkout buttons
- Update stencil-utils 6.15.0

## 1.3.1 (12-13-2022)
- Rename setting variables: fontSize-*, button-radius, carousel-bgColor-opacity, input-radius, container-border-radius, to change the variable types.

  ## 1.3.0 (12-09-2022)
- Add alert colors to theme settings
- Update to [Supermarket 6.2.0](https://papathemes.com/blog/bigcommerce-supermarket-theme-release-notes/).

## 1.2.7 (10-13-2022)
- Fix in-category search not working when multiple search boxes are present
- Fix invalid condition in merchant listing schema

## 1.2.6 (09-23-2022)
- Fix duplicated product_below_related region
- Fix SCSS error on NodeJS 14
- Fix duplicated top banner on category page

## 1.2.5 (05-30-2022)
- Fix custom badges not appears on PDP

## 1.2.4 (05-14-2022)
- Add theme option "Show product description below product details"
- Update translation

## 1.2.3 (04-30-2022)
- Update additional checkout buttons' style on the preview cart popup.
- Fix Scroll to Top button was hidden behind the newsletter box.
- Only display Sold Out label if product purchasibility is not "cannot be purchased"
- Fix price currency format in Frequently Bought Together


## 1.2.2 (03-04-2022)
- Remove header logo css on checkout page
- Added new region on the cart page [#1901](https://github.com/bigcommerce/cornerstone/pull/1901)
- Added custom event for product price change on PDP page. [#1948](https://github.com/bigcommerce/cornerstone/pull/1948)
- PAYPAL-886 added container setting for spb container. [#2041](https://github.com/bigcommerce/cornerstone/pull/2041)
- Fix PayPal Pay Later Message on Cart page

## 1.2.1 (02-04-2022)
- Fix wishlist items pagination next button not working

## 1.2.0 (12-10-2021)
- Fix search box width not equal navUser when the site logo is center.
- Fix Frequently Bought Together display money decimal incorrect
- Tweak Google checkout button
- Fix newsletter heading on cart page
- Fix product card overlap on mobile
- Change Hotline to Call us
- Remove development code
- Improve navUser labels display
- Update from Supermarket theme:
- Fix Google Structured Data schema for product reviews - Invalid object type for field "author".
- Fix Recently Viewed Products dropdown position wrong when 'row' class exists (Foundation bug)
- Revert SCSS for NodeJS 10 compatibility.
- Fix auto fit 1 line menu not display standard menu + check right edge more accurately.
- Fix HTML encoding in Address List + Edit Account pages
- Fix SCSS compile error in NodeJS v12
- [New Feature] Display Recently Viewed Products for everyone
- Remove recently viewed products limit
- [CORNERSTONE] HTML Entity displayed as is via system/error message on a Storefront. [#1888](https://github.com/bigcommerce/cornerstone/pull/1888)
- Fix nav user icon padding on medium screen

## 1.1.1 (09-09-2021)
- End discount program.
- 
## 1.1.0 (08-26-2021)
- Fix vertical product image thumbnail display incorrect
- Discount 25%

## 1.0.6 (07-15-2021)
- Fix syntax error when the home carousel has no text

## 1.0.5 (06-16-2021)
- Update theme description.

## 1.0.4 (06-04-2021)
- Update theme description.
## 1.0.3 (05-17-2021)
- Move phrases and static strings to en.json for improving translation customizing. [#1850](https://github.com/bigcommerce/cornerstone/pull/1850)

## 1.0.2 (04-22-2021)
- Fix spacing.
- Tweak Furniture style.

## 1.0.1 (04-22-2021)
- Initial release.
- Based on Supermarket 4.8.4
## 1.0.0
- Initial release.

