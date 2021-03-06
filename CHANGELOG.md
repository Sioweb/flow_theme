# Change Log for OXID eSales Flow Theme

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [3.2.0] - unreleased

### Added
- New blocks:
  - `page/search/search.tpl`
    - search_bottom_listlocator [PR-141](https://github.com/OXID-eSales/flow_theme/pull/141)
  - `page/checkout/inc/basketcontents.tpl`
    - checkout_basketcontents_summary_table_inner [PR-148](https://github.com/OXID-eSales/flow_theme/pull/148)

### Fixed
- Several CSS improvements:
  - Remove the unsupported font-smooth property [PR-144](https://github.com/OXID-eSales/flow_theme/pull/144)
  - Remove empty CSS rules [PR-145](https://github.com/OXID-eSales/flow_theme/pull/145)
  - Merge duplicate CSS selector [PR-146](https://github.com/OXID-eSales/flow_theme/pull/146)
- [0006958](https://bugs.oxid-esales.com/view.php?id=6958) Remove unnecessary closing "strong" tags [PR-147](https://github.com/OXID-eSales/flow_theme/pull/147)
  
### Changed
- Remove scheme from href of product external url [PR-142](https://github.com/OXID-eSales/flow_theme/pull/142)
- Wrap product count in minibasket in "badge" div [PR-138](https://github.com/OXID-eSales/flow_theme/pull/138)

## [3.1.0] - 2019-01-18

### Added
- Add active class to cms content pages in mainnavbar [PR-126](https://github.com/OXID-eSales/flow_theme/pull/126)
- Add active class to cms content pages in submenus [PR-133](https://github.com/OXID-eSales/flow_theme/pull/133)
- Introduce new feature - reset category filter [0002046](https://bugs.oxid-esales.com/view.php?id=2046)
- New blocks:
  - `email/html/header.tpl`
    - email_html_header [PR-140](https://github.com/OXID-eSales/flow_theme/pull/140)
  - `page/checkout/inc/basketcontents_table.tpl`
    - checkout_basketcontents_basketitem_title [PR-134](https://github.com/OXID-eSales/flow_theme/pull/134)
    - checkout_basketcontents_basketitem_artnum [PR-134](https://github.com/OXID-eSales/flow_theme/pull/134)
    - checkout_basketcontents_basketitem_attributes [PR-134](https://github.com/OXID-eSales/flow_theme/pull/134)
    - checkout_basketcontents_basketitem_selectlists
    - checkout_basketcontents_basketitem_persparams [PR-134](https://github.com/OXID-eSales/flow_theme/pull/134)
  - `page/checkout/inc/basketcontents_list.tpl`
    - checkout_basketcontents_basketitem_title [PR-135](https://github.com/OXID-eSales/flow_theme/pull/135)
    - checkout_basketcontents_basketitem_artnum [PR-135](https://github.com/OXID-eSales/flow_theme/pull/135)
    - checkout_basketcontents_basketitem_attributes [PR-135](https://github.com/OXID-eSales/flow_theme/pull/135)
    - checkout_basketcontents_basketitem_selectlists
    - checkout_basketcontents_basketitem_persparams [PR-135](https://github.com/OXID-eSales/flow_theme/pull/135)

### Fixed
- Fix mouseover on cart in lists flickering [PR-127](https://github.com/OXID-eSales/flow_theme/pull/127)
- Table structure health fix in basketcontents_table.tpl [PR-129](https://github.com/OXID-eSales/flow_theme/pull/129)
- Fix fullwidth theme option incompatabilities [PR-131](https://github.com/OXID-eSales/flow_theme/pull/131)
  - New item in basket message width
  - Start page container alignments
  - Details page blocks alignments
  - Border bottom was changes to customizable HR tag
  - Allow textarea to be resized only vertically
- Fix errors in translations [PR-132](https://github.com/OXID-eSales/flow_theme/pull/132) [0006909](https://bugs.oxid-esales.com/view.php?id=6909)
- Fix the Icon on the account dashboard button [PR-139](https://github.com/OXID-eSales/flow_theme/pull/139)

### Changed
- Alert and offset class removed from default payment description template [PR-128](https://github.com/OXID-eSales/flow_theme/pull/128)
- Specify "container" for tooltip plugin [PR-130](https://github.com/OXID-eSales/flow_theme/pull/130)
- Use oxprice for formatting the currency in basket and details page [PR-129](https://github.com/OXID-eSales/flow_theme/pull/129)
- PHP 7.2 support: count(): Parameter must be an array or an object that implements Countable
- Exclude non-essential files from dist package [PR-136](https://github.com/OXID-eSales/flow_theme/pull/136)
- Filter non-essential files during theme installation [PR-137](https://github.com/OXID-eSales/flow_theme/pull/137)

## [3.0.2] - 2018-07-06

### Added
- Add ids to form fields in `form/contact.tpl`
- Add "for" attribute to labels in `form/contact.tpl`
- Add empty select option in `form/fieldset/salutation.tpl`
- Commented out inclusion of non-existing file in `page/info/contact.tpl`

### Fixed

## [3.0.1] - 2018-07-03

### Added
- Block:
    - `widget_minibasket_modal_header` in widget/minibasket/minibasket.tpl
    - `widget_minibasket_modal_content` in widget/minibasket/minibasket.tpl
    - `widget_minibasket_modal_footer` in widget/minibasket/minibasket.tpl
    
### Fixed
- Fix alignment for payment desciption [PR-95](https://github.com/OXID-eSales/flow_theme/pull/95)
- Show deliverytime wrapper only if deliverytime is available [PR-102](https://github.com/OXID-eSales/flow_theme/pull/102)
- Add missing twbs col wrapper for grid alignment [PR-105](https://github.com/OXID-eSales/flow_theme/pull/105)
- Remove not working swipe code for mobile device [PR-81](https://github.com/OXID-eSales/flow_theme/pull/81)
- Init swipe on mobile device [PR-82](https://github.com/OXID-eSales/flow_theme/pull/82)
- Show private sales login error messages [PR-79](https://github.com/OXID-eSales/flow_theme/pull/79)
- Showing error messages with destination 'popup' [PR-54](https://github.com/OXID-eSales/flow_theme/pull/54)
- Shipping address form overlaps footer area [PR-125](https://github.com/OXID-eSales/flow_theme/pull/125)
- Add missing li end-tag [PR-122](https://github.com/OXID-eSales/flow_theme/pull/122)
- Don't show empty <li> tag on product detail actions [PR-103](https://github.com/OXID-eSales/flow_theme/pull/103)
- Add missing template err_accessdenied.tpl [PR-101](https://github.com/OXID-eSales/flow_theme/pull/101)
- Add possibility for not logged in user to change email in checkout second step (OXDEV-29).
- Remove unused code from inputvalidation.tpl [PR-124](https://github.com/OXID-eSales/flow_theme/pull/124)

## [3.0.0] - 27-03-2018

### Added
- Template:
    - `page/account/delete_my_account_confirmation.tpl`
    - `page/account/reviews.tpl` 
    - `page/account/delete_review_confirmation.tpl`
    - `form/fieldset/delete_shipping_address_modal.tpl`
      
- Block:
    - `page_list_upperlocator` in page/list/list.tpl
    - `page_list_bottomlocator` in page/list/list.tpl
    - `page_list_productlist` in page/list/list.tpl
    - `details_relatedproducts_also_bought` in page/details/inc/related_products.tpl
    - `account_order_history_cart_items` in page/account/order.tpl
    - `account_dashboard_delete_my_account` in page/account/dashboard.tpl
    - `account_delete_my_account_confirmation` in page/account/delete_my_account_confirmation.tpl
    - `account_delete_my_account_confirmation_header_message` in page/account/delete_my_account_confirmation.tpl
    - `account_delete_my_account_confirmation_warning_message` in page/account/delete_my_account_confirmation.tpl
    - `account_delete_my_account_confirmation_form` in page/account/delete_my_account_confirmation.tpl
    - `account_delete_my_account_confirmation_form_button_set` in page/account/delete_my_account_confirmation.tpl
    - `account_reviewlist_header` in page/account/reviews.tpl
    - `account_reviewlist_locator` in page/account/reviews.tpl
    - `account_reviewlist_list` in page/account/reviews.tpl
    - `account_reviewlist_item` in page/account/reviews.tpl
    - `account_reviewlist_item_action` in page/account/reviews.tpl
    - `account_reviewlist_no_reviews_available` in page/account/reviews.tpl    
    - `delete_review_confirmation_modal` in page/account/delete_review_confirmation.tpl
    - `delete_review_confirmation_modal_header` in page/account/delete_review_confirmation.tpl
    - `delete_review_confirmation_modal_body` in page/account/delete_review_confirmation.tpl
    - `delete_review_confirmation_modal_form` in page/account/delete_review_confirmation.tpl
    - `delete_review_confirmation_modal_buttons_set` in page/account/delete_review_confirmation.tpl
    - `details_productmain_price` in page/details/inc/priceinfo.tpl
    - `contact_form_fields` in form/contact.tpl
    - `contact_form_buttons` in form/contact.tpl
    - `widget_reviews_form_rating` in widget/reviews/reviews.tpl
    - `widget_reviews_form_fields` in widget/reviews/reviews.tpl
    - `widget_reviews_form_buttons` in widget/reviews/reviews.tpl
    
- Multilang string: 
    - `DD_DELETE_REVIEW_AND_RATING`
    - `DD_DELETE_REVIEW_CONFIRMATION_QUESTION`
    - `DD_REVIEWS_NOT_AVAILABLE`
    - `DELETE`   
    - `DELETE_SHIPPING_ADDRESS`  
    - `DD_DELETE`   
    - `DD_DELETE_SHIPPING_ADDRESS`

- Feature: a user has the possibility to delete a shipping address
- Feature: a user has the possibility to disable product recommendations
- Feature: a user has the possibility to delete own reviews and ratings, if this option is enabled in the shop
- Feature: show unit price near the product full price [PR-116](https://github.com/OXID-eSales/flow_theme/pull/116)
- Additional information added to Google Tracking id hint
    - The shop owner is responsible for the legal use of this function. An adaptation of the privacy policy is mandatory.

### Fixed
- Cover unit price with rights to see check [0006687](https://bugs.oxid-esales.com/view.php?id=6687)
- Fix zoom picture if allow_url_fopen disabled [PR-111](https://github.com/OXID-eSales/flow_theme/pull/111)
- Email Templates contains some untranslated Idents [0006437](https://bugs.oxid-esales.com/view.php?id=6437)
- Updated deprecated price functions in basketcontents [PR-89](https://github.com/OXID-eSales/flow_theme/pull/89)
- Single quote was impossible in form validation translations [PR-119](https://github.com/OXID-eSales/flow_theme/pull/119)
- Fix translations COOKIE_NOTE_CLOSE and ADD_RECOMM_ADDRECOMMLINK2 [PR-117](https://github.com/OXID-eSales/flow_theme/pull/117)
- Fix double evaluation of Javascript on details page [PR-118](https://github.com/OXID-eSales/flow_theme/pull/118)
- Fix not working selection lists in checkout (cart) [PR-121](https://github.com/OXID-eSales/flow_theme/pull/121)
- Fix variant switching in preview mode [PR-120](https://github.com/OXID-eSales/flow_theme/pull/120)
- Fix missing blDebugTemplateBlocks option related script [PR-100](https://github.com/OXID-eSales/flow_theme/pull/100)
- Fix recursive blDebugTemplateBlocks option related script initialization [PR-106](https://github.com/OXID-eSales/flow_theme/pull/106)

## [2.3.3] - 30-11-2017

### Fixed
- [Guestbook option remains in footer settings of the Flow theme](https://bugs.oxid-esales.com/view.php?id=6696)

[3.1.1]: https://github.com/OXID-eSales/flow_theme/compare/v3.1.0...HEAD
[3.1.0]: https://github.com/OXID-eSales/flow_theme/compare/v3.0.2...v3.1.0
[3.0.2]: https://github.com/OXID-eSales/flow_theme/compare/v3.0.1...v3.0.2
[3.0.1]: https://github.com/OXID-eSales/flow_theme/compare/v3.0.0...v3.0.1
[3.0.0]: https://github.com/OXID-eSales/flow_theme/compare/v2.3.3...v3.0.0
[2.3.3]: https://github.com/OXID-eSales/flow_theme/compare/v2.3.2...v2.3.3
