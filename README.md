# A Responsive E-commerce E-mail Template

Build as a starter-template for your ecommerce campaign layouts.  
Feel free to edit or use the template as is.

## Features

* Responsive E-mail Template
* MailChimp compatible template with drag & drop functionality
* Flexible table structure (delete/copy/replace).
* Valid XHTML 1.0 Transitional! Markup (Via https://validator.w3.org/check)
* ShopOrama Product Feed - template for MailChimp

## Getting started

### The MailChimp Template

* Open up `email-template-plain.html` and copy the HTML into your MailChimp Template
* The template has all required MailChimp markup for you to edit the template in design-mode.
* Use the template as is. They'll put the CSS inline for you when you send your campaign.

### The HTML Template

To use the HTML-template with your CMS you need to put the CSS inline. You can use [Premailer](http://premailer.dialect.ca/) to do this automatically.

* Copy all of `email-template-mailchimp.html`
* Paste the HTML as the source into Premailer
* Copy the HTML results and use them in your email view/template
* Note that some services may allow you to opt into CSS inlining, such as Mandrill.

### The ShopOrama Product Feed

This template can be used with a ShopOrama product feed. Here's how to make that work in MailChimp:

1. Open ShopOrama and create a new landingpage. 
2. Name it `mailchimp product feed` and set it to `no-index, follow`
3. Set the settings of your landingpage to your liking. All products in this feed will be shown in your e-mail.
4. Download the `mailchimp-product-feed.xml` from this repository and upload it to your sFTP.
5. In the "XML" widget of your landingpage, put in `mailchimp-product-feed.xml` and save.
6. Open up `http://shop.shoporama.dk/mailchimp-product-feed.xml` ("shop" should be your shopname)
7. Inspect the source of the page. Copy all HTML.
8. Open MailChimp. Create a Campaign. Choose to use this template.
9. Add the section called `module_product_html_feed` to your campaign. 
10. Edit the contents of this section, and click the "HTML"-icon. Delete everything, and paste in your HTML.
11. There you have it. Products are now automatically inserted into your e-mail.


## Demo

![Design Template](https://mikkeltschentscher.dk/hosting/shoporama/screenshot-v3.png "Design Template")


## Compatibility

The template has been tested throughly with Litmus Email Testing and Email Marketing Analytics.  
[Inspect the final test from Litmus here](https://litmus.com/checklist/public/71477d5 "Inspect the e-mail template")


### E-mail Clients with full compatibility

Apple Mail 8, Apple Mail 9, Outlook 2000, Outlook 2002, Outlook 2003, Outlook 2007, Outlook 2010, Outlook 2011, Outlook 2013, Outlook 2016, Thunderbird 38, Android 4.4, Gmail App (Android), iPhone 5s (iOS 7), iPhone 5s (iOS 8), iPhone 6, iPhone 6 Plus, iPhone 6s, iPhone 6s Plus, iPad (Retina), iPad Mini, AOL Mail, Gmail, Inbox by Gmail, GMX.de, Google Apps,Office 365, Outlook.com,Web.de, Yahoo! Mail

*E-mail with full compatibility will match the original design as seen above*


### E-mail Clients with partial compatibility

Lotus Notes 8, IBM Notes 9, Outlook 2013 120 DPI

*E-mail with partial compatibility will show the content in the right layout, but paddings, line-heights and similar is a bid off.*


### E-mail Clients with no compatibility

Lotus Notes 7, Lotus Notes 8.5

*E-mail with no compatibility will not be viewable what-so-ever.*


## Author & Credits

Mikkel Tschentscher, +45 22 51 31 79, based in Copenhagen, Denmark.  
[https://mikkeltschentscher.dk](https://mikkeltschentscher.dk)


## Support

If you have any questions feel free to email me at [hello@mikkeltschentscher](mailto:hello@mikkeltschentscher.dk).


## License

The code is available under the [MIT license](https://github.com/mikkel-tschentscher/responsive-ecommerce-email-template/blob/master/LICENSE.txt).
