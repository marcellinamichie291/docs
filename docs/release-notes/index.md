# {{custom.company_name}} Changelog

## Release Notes

[{{custom.company_name}}]({{custom.website_url}}) follows [Semantic Versioning](https://semver.org/) and regularly updates the platform and its APIs. You can periodically check this page to keep abreast of new or updated features, bug fixes, known issues, and deprecated functionality.

This changelog lists releases by date and version number along with associated changes.

### [October 12, 2021 (versions 1.112, 1.111, 1.110, 1.109, 1.108, 1.107, 1.106, 1.105, 1.104, & 1.103)](v1.103-1.112/)

* [Provider accounts update](#provider-accounts-update): added possibility to check account credentials from the Dashboard
* [Commerce updates](#commerce-updates): added the *Auto-approve* option for transactions  within an organisation, added the *Resolution message* attribute for payment invoices
* [Card gate HPP update](#card-gate-hpp-update): added the theme option for customer redirection only after final statuses
* Performance improvements

### [September 9, 2021 (versions 1.103, 1.102, 1.101, 1.100, 1.99, 1.98, 1.97, 1.96, 1.95, & 1.94)](v1.94-1.103/)

* [Commerce updates](#commerce-updates): made invoice reference ID optional so now generate UUID randomly
* Updated [addon creating](#addon-updates)
* [New Analytics tables and columns](#new-analytics-tables)
* Updated [Telegram bot](#telegram-bot) functionality
* And other performance improvements

### [August 10, 2021 (versions 1.93, 1.92, 1.91, 1.90, 1.89, 1.88, 1.87, 1.86, 1.85, 1.84, & 1.83)](v1.83-1.93/)

* [Routing updates](v1.83-1.93/#routing-updates): added option for service auto-enabling
* [Processing updates](v1.83-1.93/#processing-updates): added `processed` timestamp to all final statuses of payment and payout invoices, added a `queued` status for items in batch payouts
* [Card Gateway updates](v1.83-1.93/#card-gateway-updates): added the turnover limit for merchant accounts, new routing and modifier scheme attributes, new resolution for cascading, `cash` payment and payout methods for manual transactions, changed handling asynchronous failures process
* [Analytics update](v1.83-1.93/#analytics-update): new attributes for data source
* [Addons updates](v1.83-1.93/#addons-updates): added IP filter to restrict API requests for the addons with external usage, NBU registration data tabs for payment and payout entries
* And various [performance improvements](v1.83-1.93/#performance-improvements)

### [July 8, 2021 (versions 1.82, 1.81, 1.80, 1.79, 1.78, 1.77, & 1.76)](v1.76-1.82/)

* [Commerce updates](v1.76-1.82/#commerce-updates): added the `company_phone` and `country_code` parameters to the `merchant_profile` object
* [Platform API updates](v1.76-1.82/#api-updates): added endpoints for handling transactions that affect the Commerce balances
* [Card Gate updates](v1.76-1.82/#card-gate-updates): started supporting OTP flow for card payments, moved the 'Allow to use saved cards' to the Card Gateway Options
* [Routing updates](v1.76-1.82/#routing-updates): extended the list of attributes for payout scheme conditions
* [Addons updates](v1.76-1.82/#addons-management): expanded possibilities to manage addons, updated the NBU transaction registration addon, revised approaches to providing access to addons within organisations
* Performance improvements and bug fixes.

### [June 9, 2021 (versions 1.75, 1.74, 1.73, 1.72, 1.71, 1.70, 1.69, 1.68, 1.67, & 1.66)](v1.66-1.75/)

* [Commerce update](v1.66-1.75/#commerce-update): implemented two-step transactions within an organisation
* [Gateways updates](v1.66-1.75/#gateways-updates): detailed charged back amounts and fees, added an option for the card validation field on the default HPP, and new metrics for card payment routing
* [Customers section's updates](v1.66-1.75/#customers-sections-updates): added options to control payments and payouts availability in the customer entry and two extra columns in the transactional report tables for the customers' data and metadata
* Added an extra table for [Analytics queries](v1.66-1.75/#analytics-update)
* [Minor dashboard layout update](v1.66-1.75/#dashboard-layout-update)
* Performance improvements and bug fixes.

### [May 13, 2021 (versions 1.65, 1.64, 1.63, 1.62, 1.61, 1.60, 1.59, 1.58, 1.57, 1.56, 1.55, & 1.54)](v1.54-1.65/)

* [Commerce updates](v1.54-1.65/#commerce-updates): expanded access settings for commerce accounts and operations, added `merchant_profile` object to the Commerce settings and request creation and options to control Saved cards access scope
* [Connectors Hub update](v1.54-1.65/#connectors-hub-update): updated the Callback handler, added `payouts` array to Callback for payouts processing, added the Deposit account option for preventing finalising payout transactions with failure resolutions
* [Card Gateway update](v1.54-1.65/#card-gate-update): added modifier by card status to Payment schemes
* [Reports optimising](v1.54-1.65/#reports-optimising)
* [Receipt Addon update](v1.54-1.65/#addons-update): receipts generating for Payout invoices

### [April 2, 2021 (versions 1.53, 1.52, 1.51, 1.50, 1.49, 1.48, 1.47, 1.46, & 1.45)](v1.45-1.53/)

* [Processing supplements](v1.45-1.53/#processing-supplements): added partial statuses for payments' refunds and chargebacks, and an option to skip the verify stage on payouts
* [Card Gate](v1.45-1.53/#card-gate-update): added possibility to update features for connected merchant accounts in the Dashboard
* [Merchant Portal](v1.45-1.53/#merchant-portal-updates): configuration and exports updates
* [Performance improvements](v1.45-1.53/#performance-improvements)

### [March 3, 2021 (versions 1.44, 1.43, 1.42, 1.41, 1.40, 1.39, 1.38, & 1.37)](v1.37-1.44/)

* [Payout Gateway update](v1.37-1.44/#payout-gateway-update): added possibility to resolve statement conflict from the Dashboard
* [Extend Export Data Files](v1.37-1.44/#extended-export-data-files) and add new fields
* Update [Addons](v1.37-1.44/#addons-editing): add editing option
* [Performance Improvements](v1.37-1.44/#performance-improvements)

### [February 6, 2021 (versions 1.36, 1.35, 1.34, 1.33, 1.32, 1.31, 1.30, & 1.29)](v1.36-1.29/)

* [Payment Gateway updates](v1.36-1.29/#payment-gateway-updates): added fee set for chargebacks to Commerce payment services' options and Provider Reference ID parameter to payment flow
* [Card Gateway update](v1.36-1.29/#card-gateway-updates): security updates, increased HPP theme options limit, updated `browser_ip` regular expression to support IPv4 and IPv6 addresses
* And other platform performance improvements

### [January 5, 2021 (v1.28)](v1.28/)

* [Payout Schemes optimisation](v1.28/#payout-schemes-update): at payout splitting, the system examines routes' limits and remaining amounts for each following parts
* [Manual card transaction handling](v1.28/#card-gate-update)
* [Other fixes and improvements](v1.28/#fixes-and-improvements)

## Other resources

To view release notes for versions prior to 2021, see the [2020](archive/2020) and [2019](archive/2019) archive pages.

You also can follow us for the latest news and updates on [:fontawesome-brands-twitter: @insidecorefy](https://twitter.com/insidecorefy).

<!--

## Documentation Changelog

We are improving our documentation day by day, so add to the list only significant changes, news, articles, and sections (starting with version 1.30).

-->

!!! question
    We are always here to hear your thoughts, questions, and feedback!

    Send us your questions and suggestions at <!--email_off-->[{{custom.support_email}}](mailto:{{custom.support_email}})<!--/email_off-->.
