# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Added

- Added support to export accounts
- Added suport to import accounts

### Changed

- Improved the styling in the admin control panel

## 1.232.0 - 2023-02-05

### Changed

- Improved the language localization for German (`de`)
- Migrated the style of `ActivitiesPageModule` to `@angular/material` `15` (mdc)
- Migrated the style of `GfCreateOrUpdateActivityDialogModule` to `@angular/material` `15` (mdc)
- Migrated the style of `GfMarketDataDetailDialogModule` to `@angular/material` `15` (mdc)
- Upgraded `ng-extract-i18n-merge` from version `2.1.2` to `2.5.0`
- Upgraded `ngx-markdown` from version `14.0.1` to `15.1.0`

### Fixed

- Fixed the `Upgrade Plan` button of the interstitial for the subscription

## 1.231.0 - 2023-02-04

### Added

- Added the dividend and fees to the position detail dialog
- Added support to link a (wealth) item to an account

### Changed

- Relaxed the validation rule of the _Redis_ host environment variable (`REDIS_HOST`)
- Improved the language localization for German (`de`)
- Eliminated `angular-material-css-vars`
- Upgraded `angular` from version `14.2.0` to `15.1.2`
- Upgraded `Nx` from version `15.0.13` to `15.6.3`

## 1.230.0 - 2023-01-29

### Added

- Added an interstitial for the subscription
- Added _SourceForge_ to the _As seen in_ section on the landing page
- Added a quote to the blog post _Ghostfolio auf Sackgeld.com vorgestellt_

### Changed

- Improved the unit format (`%`) in the global heat map component of the public page
- Improved the pricing page
- Upgraded `Node.js` from version `16` to `18` (`Dockerfile`)
- Upgraded `prisma` from version `4.8.0` to `4.9.0`

### Fixed

- Fixed the click of unknown accounts in the portfolio proportion chart component
- Fixed an issue with `value` in the value redaction interceptor for the impersonation mode

## 1.229.0 - 2023-01-21

### Added

- Added a blog post: _Ghostfolio auf Sackgeld.com vorgestellt_
- Added _Sackgeld.com_ to the _As seen in_ section on the landing page

### Changed

- Removed the toggle _Original Shares_ vs. _Current Shares_ on the allocations page
- Hid error messages related to no current investment in the client
- Refactored the value redaction interceptor for the impersonation mode

### Fixed

- Fixed the value of the active (emergency fund) filter in percentage on the allocations page

## 1.228.1 - 2023-01-18

### Added

- Extended the hints in user settings

### Changed

- Improved the date formatting in the tooltip of the dividend timeline grouped by month / year
- Improved the date formatting in the tooltip of the investment timeline grouped by month / year
- Reduced the execution interval of the data gathering to every 4 hours
- Removed emergency fund as an asset class

## 1.227.1 - 2023-01-14

### Changed

- Improved the language localization for German (`de`)

### Fixed

- Fixed the create or edit activity dialog

## 1.227.0 - 2023-01-14

### Added

- Added support for assets other than cash in emergency fund (affecting buying power)
- Added support for translated tags

### Changed

- Improved the logo alignment

### Fixed

- Fixed the grouping by month / year of the dividend and investment timeline

## 1.226.0 - 2023-01-11

### Added

- Added the language localization for Français (`fr`)
- Extended the landing page by a global heat map of subscribers
- Added support for the thousand separator in the global heat map component

### Changed

- Improved the form of the import dividends dialog (disable while loading)
- Removed the deprecated `~` in _Sass_ imports

### Fixed

- Fixed an exception in the _X-ray_ section

## 1.225.0 - 2023-01-07

### Added

- Added support for importing dividends from a data provider

### Changed

- Extended the Frequently Asked Questions (FAQ) page

## 1.224.0 - 2023-01-04

### Added

- Added support for the dividend timeline grouped by year
- Added support for the investment timeline grouped by year
- Set up the language localization for Français (`fr`)
- Set up the language localization for Português (`pt`)

### Changed

- Improved the language localization for Dutch (`nl`)

## 1.223.0 - 2023-01-01

### Added

- Added a student discount to the pricing page
- Added a prefix to the codes of the coupon system

### Changed

- Optimized the page titles in the header for mobile
- Extended the asset profile details dialog in the admin control panel

## 1.222.0 - 2022-12-29

### Added

- Added support for filtering on the analysis page
- Added the price to the `Subscription` database schema

### Changed

- Changed the execution time of the asset profile data gathering to every Sunday at lunch time
- Improved the activities import by providing asset profile details
- Upgraded `@codewithdan/observable-store` from version `2.2.11` to `2.2.15`
- Upgraded `bull` from version `4.8.5` to `4.10.2`
- Upgraded `countup.js` from version `2.0.7` to `2.3.2`
- Upgraded the _Internet Identity_ dependencies from version `0.12.1` to `0.15.1`
- Upgraded `prisma` from version `4.7.1` to `4.8.0`

### Fixed

- Fixed the language localization of the account type

## 1.221.0 - 2022-12-26

### Added

- Added support to manage the tags in the create or edit activity dialog
- Added the tags to the admin control panel
- Added a blog post: _The importance of tracking your personal finances_
- Resolved the title of the blog post

### Changed

- Improved the activities import by a preview step
- Improved the labels based on the type in the create or edit activity dialog
- Refreshed the cryptocurrencies list
- Removed the data source type `RAKUTEN`

### Fixed

- Fixed the date conversion for years with only two digits

## 1.220.0 - 2022-12-23

### Added

- Added the position detail dialog to the _Top 3_ and _Bottom 3_ performers of the analysis page
- Added the `dryRun` option to the import activities endpoint

### Changed

- Increased the historical data chart of the _Fear & Greed Index_ (market mood) to 365 days
- Upgraded `color` from version `4.0.1` to `4.2.3`
- Upgraded `prettier` from version `2.7.1` to `2.8.1`

### Fixed

- Fixed the rounding of the y-axis ticks in the benchmark comparator

## 1.219.0 - 2022-12-17

### Added

- Added support to disable user sign up in the admin control panel
- Extended the glossary of the resources page by _Deflation_, _Inflation_ and _Stagflation_

### Changed

- Added the name to the symbol column in the activities table
- Combined the name and symbol column in the holdings table (former positions table)

## 1.218.0 - 2022-12-12

### Added

- Added the date of the first activity to the positions table
- Added an endpoint to fetch the logo of an asset or a platform

### Changed

- Improved the asset profile details dialog in the admin control panel
- Upgraded `chart.js` from version `3.8.0` to `4.0.1`

## 1.217.0 - 2022-12-10

### Added

- Added the dividend timeline grouped by month

### Changed

- Improved the value redaction interceptor (including `comment`)
- Improved the language localization for Español (`es`)
- Upgraded `cheerio` from version `1.0.0-rc.6` to `1.0.0-rc.12`
- Upgraded `prisma` from version `4.6.1` to `4.7.1`

### Fixed

- Fixed the activities sorting in the account detail dialog

## 1.216.0 - 2022-12-03

### Added

- Supported a note for asset profiles
- Supported a manual currency for the activity fee
- Extended the support for column sorting in the accounts table (name, platform, transactions)
- Extended the support for column sorting in the activities table (name, symbol)
- Extended the support for column sorting in the positions table (performance)

### Changed

- Upgraded `big.js` from version `6.1.1` to `6.2.1`
- Upgraded `date-fns` from version `2.28.0` to `2.29.3`
- Upgraded `replace-in-file` from version `6.2.0` to `6.3.5`

### Fixed

- Fixed the filter by asset sub class for the asset profiles in the admin control

## 1.215.0 - 2022-11-27

### Changed

- Improved the language selector on the account page
- Improved the wording in the _X-ray_ section (net worth instead of investment)
- Extended the asset profile details dialog in the admin control panel
- Updated the browserslist database
- Upgraded `ionicons` from version `5.5.1` to `6.0.4`
- Upgraded `uuid` from version `8.3.2` to `9.0.0`

## 1.214.0 - 19.11.2022

### Added

- Added support for sorting in the accounts table

### Changed

- Improved the support for the `MANUAL` data source
- Improved the _Activities_ tab icon
- Improved the _Activities_ icons for `BUY`, `DIVIDEND` and `SELL`
- Upgraded `prisma` from version `4.4.0` to `4.6.1`
- Upgraded `yahoo-finance2` from version `2.3.6` to `2.3.10`

### Fixed

- Fixed the activities sorting in the position detail dialog
- Fixed the dynamic number of decimal places for cryptocurrencies in the position detail dialog
- Fixed a division by zero error in the cash positions calculation

## 1.213.0 - 14.11.2022

### Added

- Added an indicator for excluded accounts in the accounts table
- Added a blog post: _Black Friday 2022_

### Fixed

- Fixed an issue with the currency inconsistency in the _Yahoo Finance_ service (convert from `ZAc` to `ZAR`)

## 1.212.0 - 11.11.2022

### Changed

- Changed the view mode selector to a slide toggle
- Upgraded `Nx` from version `15.0.0` to `15.0.13`

## 1.211.0 - 11.11.2022

### Changed

- Converted the client into a _Progressive Web App_ (PWA) with `@angular/pwa`
- Removed the bottom margin from the body element
- Improved the pricing page

## 1.210.0 - 08.11.2022

### Added

- Added tabs to the portfolio page

### Changed

- Merged the _FIRE_ calculator and the _X-ray_ section to a single page
- Tightened the validation rule of the base currency environment variable (`BASE_CURRENCY`)

### Fixed

- Fixed an issue in the cash positions calculation

## 1.209.0 - 05.11.2022

### Added

- Added the _Buy me a coffee_ button to the about page

### Changed

- Improved the usability of the activities import
- Improved the usage of the premium indicator component
- Removed the intro image in dark mode
- Refactored the `TransactionsPageComponent` to `ActivitiesPageComponent`

## 1.208.0 - 03.11.2022

### Added

- Added pagination to the activities table

### Changed

- Restructured the actions in the admin control panel

### Fixed

- Fixed the calculation in the portfolio evolution chart

## 1.207.0 - 31.10.2022

### Added

- Added support for translated labels of asset and asset sub class
- Added support for dates in _ISO 8601_ date format (`YYYY-MM-DD`) in the activities import

### Changed

- Darkened the background color of the dark mode

### Fixed

- Fixed the public page
- Improved the loading indicator of the portfolio evolution chart

## 1.206.2 - 20.10.2022

### Changed

- Fixed the `rxjs` version to `7.5.6` (resolutions)
- Migrated the `angular.json` to `project.json` files in the `Nx` workspace
- Upgraded `nestjs` from version `9.0.7` to `9.1.4`
- Upgraded `Nx` from version `14.6.4` to `15.0.0`

### Fixed

- Fixed the performance calculation including `SELL` activities with a significant performance gain

## 1.205.2 - 16.10.2022

### Changed

- Persisted the language on url change
- Improved the portfolio evolution chart
- Refactored the appearance (dark mode) in user settings (from `appearance` to `colorScheme`)
- Improved the wording on the landing page

## 1.204.1 - 15.10.2022

### Added

- Added support to change the appearance (dark mode) in user settings
- Added the total amount chart to the investment timeline
- Setup the `prettier` plugin `prettier-plugin-organize-attributes`

### Changed

- Respected the current date in the _FIRE_ calculator
- Simplified the settings management in the admin control panel
- Renamed the data source type `RAKUTEN` to `RAPID_API`

### Fixed

- Fixed some links in the blog posts
- Fixed the alignment of the value component on the allocations page

### Todo

- Rename the environment variable from `RAKUTEN_RAPID_API_KEY` to `RAPID_API_API_KEY`

## 1.203.0 - 08.10.2022

### Added

- Supported a progressive line animation in the line chart component

### Changed

- Moved the benchmark comparator from experimental to general availability
- Improved the user interface of the benchmark comparator

### Fixed

- Fixed an issue in the performance and chart calculation of today
- Fixed the alignment of the value component in the admin control panel

## 1.202.0 - 07.10.2022

### Added

- Added support for a translated 4% rule in the _FIRE_ section

### Changed

- Improved the caching of the benchmarks in the markets overview (only cache if fetching was successful)
- Improved the wording in the twitter bot service

### Fixed

- Fixed the support for cryptocurrencies having a symbol with less than 3 characters (e.g. `SC-USD`)
- Fixed the text truncation in the value component

## 1.201.0 - 01.10.2022

### Added

- Added a blog post: _Hacktoberfest 2022_

### Changed

- Improved the usage of the value component in the admin control panel
- Improved the language localization for Español (`es`)

### Fixed

- Fixed the usage of the value component on the allocations page

## 1.200.0 - 01.10.2022

### Added

- Added a mini statistics section to the landing page including pulls on _Docker Hub_
- Added an _As seen in_ section to the landing page
- Added support for an icon in the value component

### Changed

- Upgraded `prisma` from version `4.1.1` to `4.4.0`

## 1.199.1 - 27.09.2022

### Added

- Set up the language localization for Español (`es`)
- Added support for sectors in mutual funds

## 1.198.0 - 25.09.2022

### Added

- Added support to exclude an account from analysis
- Set up the language localization for Nederlands (`nl`)

## 1.197.0 - 24.09.2022

### Added

- Added the value of the active filter in percentage on the allocations page
- Extended the feature overview page by multi-language support (English, German, Italian)

### Changed

- Combined the performance and chart calculation
- Improved the style of various selectors (density)

## 1.196.0 - 22.09.2022

### Added

- Set up the language localization for Italiano (`it`)
- Extended the landing page

## 1.195.0 - 20.09.2022

### Changed

- Improved the algorithm of the performance chart calculation

### Fixed

- Improved the chart tooltip of the benchmark comparator

## 1.194.0 - 17.09.2022

### Added

- Added `NODE_ENV: production` to the `docker-compose` files (`docker-compose.yml` and `docker-compose.build.yml`)
- Visualized the percentage of the active filter on the allocations page

### Changed

- Improved the language localization for German (`de`)

### Fixed

- Respected the end date in the performance chart calculation

### Todo

- Set `NODE_ENV: production` as in [docker-compose.yml](https://github.com/ghostfolio/ghostfolio/blob/main/docker/docker-compose.yml)

## 1.193.0 - 14.09.2022

### Changed

- Sorted the benchmarks by name
- Extended the pricing page

### Fixed

- Fixed the calculations of the exchange rate service by changing `USD` to the base currency
- Fixed the missing assets during the local development

## 1.192.0 - 11.09.2022

### Changed

- Simplified the configuration of the benchmarks: `symbolProfileId` instead of `dataSource` and `symbol`
- Upgraded `yahoo-finance2` from version `2.3.3` to `2.3.6`

### Fixed

- Improved the loading indicator of the benchmark comparator
- Improved the error handling in the benchmark calculation

## 1.191.0 - 10.09.2022

### Changed

- Removed the `currency` and `viewMode` from the `User` database schema

### Fixed

- Allowed the date range change for the demo user

## 1.190.0 - 10.09.2022

### Added

- Added the date range component to the benchmark comparator

### Changed

- Improved the mobile layout of the benchmark comparator
- Migrated the date range setting from the locale storage to the user settings
- Refactored the `currency` and `view mode` in the user settings

## 1.189.0 - 08.09.2022

### Changed

- Distinguished between currency and unit in the chart tooltip

### Fixed

- Fixed the benchmark chart in the benchmark comparator (experimental)

## 1.188.0 - 06.09.2022

### Added

- Added a benchmark comparator (experimental)

### Fixed

- Improved the asset profile details dialog for assets without a (first) activity in the admin control panel

## 1.187.0 - 03.09.2022

### Added

- Supported units in the line chart component
- Added a new chart calculation engine (experimental)

## 1.186.2 - 03.09.2022

### Changed

- Decreased the rate limiter duration of queue jobs from 5 to 4 seconds
- Removed the alias from the `User` database schema
- Upgraded `angular` from version `14.1.0` to `14.2.0`
- Upgraded `Nx` from version `14.5.1` to `14.6.4`

### Fixed

- Fixed the environment variables `REDIS_HOST`, `REDIS_PASSWORD` and `REDIS_PORT` in the Redis configuration
- Handled errors in the portfolio calculation if there is no internet connection
- Fixed the _GitHub_ contributors count on the about page

## 1.185.0 - 30.08.2022

### Added

- Added a skeleton loader to the market mood component in the markets overview

### Changed

- Moved the build pipeline from _Travis_ to _GitHub Actions_
- Increased the caching of the benchmarks

### Fixed

- Disabled the language selector for the demo user

## 1.184.2 - 28.08.2022

### Added

- Added the alias to the `Access` database schema
- Added support for translated time distances
- Added a _GitHub Action_ to create an `arm64` docker image

### Changed

- Improved the language localization for German (`de`)

### Fixed

- Fixed the missing assets during the local development

## 1.183.0 - 24.08.2022

### Added

- Added a filter by asset sub class for the asset profiles in the admin control

### Changed

- Improved the language localization for German (`de`)

## 1.182.0 - 23.08.2022

### Changed

- Improved the language localization for German (`de`)
- Extended and made the columns of the asset profiles sortable in the admin control
- Moved the asset profile details in the admin control panel to a dialog

## 1.181.2 - 21.08.2022

### Added

- Added a language selector to the account page
- Added support for translated labels in the value component

### Changed

- Integrated the commands `database:setup` and `database:migrate` into the container start

### Fixed

- Fixed a division by zero error in the benchmarks calculation

### Todo

- Apply manual data migration (`yarn database:migrate`) is not needed anymore

## 1.180.1 - 18.08.2022

### Added

- Set up `ng-extract-i18n-merge` to improve the i18n extraction and merge workflow
- Set up the language localization for German (`de`)
- Resolved the feature graphic of the blog post

### Changed

- Tagged template literal strings in components for localization with `$localize`

### Fixed

- Fixed the license component in the about page
- Fixed the links to the blog posts

## 1.179.5 - 15.08.2022

### Added

- Set up i18n support
- Added a blog post: _500 Stars on GitHub_

### Changed

- Reduced the maximum width of the performance chart on the home page

## 1.178.0 - 09.08.2022

### Added

- Added `url` to the symbol profile overrides model for manual adjustments
- Added default values for `countries` and `sectors` of the symbol profile overrides model

### Changed

- Simplified the initialization of the exchange rate service
- Improved the orders query for `assetClass` with symbol profile overrides
- Improved the styling of the benchmarks in the markets overview

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.177.0 - 04.08.2022

### Added

- Added `GHOSTFOLIO` as a default to `DATA_SOURCES`
- Added the `AGPLv3` logo to the landing page

### Changed

- Refactored the initialization of the exchange rate service
- Upgraded `angular` from version `14.0.2` to `14.1.0`
- Upgraded `nestjs` from version `8.4.7` to `9.0.7`
- Upgraded `Nx` from version `14.3.5` to `14.5.1`
- Upgraded `prisma` from version `3.15.2` to `4.1.1`

### Fixed

- Handled database connection errors (do not exit process)

## 1.176.2 - 31.07.2022

### Added

- Added page titles

### Changed

- Improved the performance of data provider requests by introducing a maximum number of symbols per request (chunk size)
- Changed the log level settings
- Refactored the access of the environment variables in the bootstrap function (api)
- Upgraded `Node.js` from version `14` to `16` (`Dockerfile`)

### Todo

- Upgrade to `Node.js` 16+

## 1.175.0 - 29.07.2022

### Added

- Set up a Frequently Asked Questions (FAQ) page
- Added the savings rate to the investment timeline grouped by month

### Fixed

- Added the symbols to the activities in the account detail dialog

## 1.174.0 - 27.07.2022

### Added

- Supported a note for activities

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.173.0 - 23.07.2022

### Fixed

- Fixed an issue with the currency inconsistency in the _Yahoo Finance_ service (convert from `USX` to `USD`)

## 1.172.0 - 23.07.2022

### Added

- Added a blog post: _Ghostfolio meets Internet Identity_

## 1.171.0 - 22.07.2022

### Added

- Added _Internet Identity_ as a new social login provider

### Changed

- Improved the empty state of the
  - _Analysis_ section
  - _Holdings_ section
  - performance chart on the home page

### Fixed

- Fixed the distorted tooltip in the performance chart on the home page
- Fixed a calculation issue of the current month in the investment timeline grouped by month

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.170.0 - 19.07.2022

### Added

- Added support for the tags in the create or edit transaction dialog
- Added support for the cryptocurrency _TerraUSD_ (`UST-USD`)

### Changed

- Removed the alias from the user interface as a preparation to remove it from the `User` database schema
- Removed the activities import limit for users with a subscription

### Todo

- Rename the environment variable from `MAX_ORDERS_TO_IMPORT` to `MAX_ACTIVITIES_TO_IMPORT`

## 1.169.0 - 14.07.2022

### Added

- Added support for the cryptocurrency _Songbird_ (`SGB1-USD`)
- Added support for the cryptocurrency _Terra 2.0_ (`LUNA2-USD`)
- Added a blog post

### Changed

- Refreshed the cryptocurrencies list to support more coins by default
- Upgraded `date-fns` from version `2.22.1` to `2.28.0`

## 1.168.0 - 10.07.2022

### Added

- Extended the investment timeline grouped by month

### Changed

- Handled an occasional currency pair inconsistency in the _Yahoo Finance_ service (`GBP=X` instead of `USDGBP=X`)

### Fixed

- Fixed the content height of the account detail dialog

## 1.167.0 - 07.07.2022

### Added

- Added _Markets_ to the public pages

### Changed

- Improved the _Create Account_ link in the _Live Demo_
- Upgraded `ngx-markdown` from version `13.0.0` to `14.0.1`

### Fixed

- Fixed an issue in the _Holdings_ section for users without a subscription

## 1.166.0 - 30.06.2022

### Added

- Added an account detail dialog

### Changed

- Improved the label of the (symbol) search
- Refactored the demo account as a route (`/demo`)
- Upgraded `nestjs` from version `8.2.3` to `8.4.7`
- Upgraded `prisma` from version `3.14.0` to `3.15.2`
- Upgraded `yahoo-finance2` from version `2.3.2` to `2.3.3`
- Upgraded `zone.js` from version `0.11.4` to `0.11.6`

## 1.165.0 - 25.06.2022

### Added

- Added an icon and name column to the positions table
- Added a reusable premium indicator component

### Changed

- Moved the positions table to a dedicated section (_Holdings_)
- Changed the data gathering by symbol endpoint to delete data first

## 1.164.0 - 23.06.2022

### Added

- Added the positions table including performance to the public page

## 1.163.0 - 22.06.2022

### Changed

- Improved the onboarding for iOS

## 1.162.0 - 18.06.2022

### Added

- Added a _Privacy Policy_ page

### Changed

- Simplified the header

### Fixed

- Fixed an issue with the currency inconsistency in the _Yahoo Finance_ service (convert from `ILA` to `ILS`)

## 1.161.1 - 16.06.2022

### Added

- Added the vertical hover line to inspect data points in the performance chart on the home page

### Changed

- Improved the landing page
- Upgraded `angular` from version `13.3.6` to `14.0.2`
- Upgraded `Nx` from version `14.1.4` to `14.3.5`
- Upgraded `storybook` from version `6.4.22` to `6.5.9`

### Fixed

- Improved the error handling of missing market prices

## 1.160.0 - 15.06.2022

### Fixed

- Fixed the `No data provider has been found` error in the search (regression after `envalid` upgrade to `7.3.1` in Ghostfolio `1.157.0`)

## 1.159.0 - 15.06.2022

### Changed

- Changed the default `HOST` to `0.0.0.0`
- Refactored the endpoint of the public page (filter by equity)

## 1.158.1 - 12.06.2022

### Added

- Extended the queue jobs view in the admin control panel by a data dialog

### Changed

- Exposed the environment variable `HOST`
- Decreased the number of attempts of queue jobs from `20` to `10` (fail earlier)
- Improved the message for data provider errors in the client
- Changed the label from _Balance_ to _Cash Balance_ in the account dialog
- Restructured the documentation for self-hosting

## 1.157.0 - 11.06.2022

### Added

- Extended the queue jobs view in the admin control panel by the number of attempts and the status

### Changed

- Migrated the historical market data gathering to the queue design pattern
- Refreshed the cryptocurrencies list to support more coins by default
- Increased the historical data chart of the _Fear & Greed Index_ (market mood) to 180 days
- Upgraded `chart.js` from version `3.7.0` to `3.8.0`
- Upgraded `envalid` from version `7.2.1` to `7.3.1`

### Fixed

- Reloaded the accounts of a user after creating, editing or deleting one
- Excluded empty items in the activities filter

## 1.156.0 - 05.06.2022

### Added

- Added the user id to the account page
- Added a new view with jobs of the queue to the admin control panel

### Changed

- Simplified the features page
- Restructured the _FIRE_ section
- Upgraded `@simplewebauthn/browser` and `@simplewebauthn/server` from version `4.1.0` to `5.2.1`

### Fixed

- Fixed the `docker-compose` files to resolve variables correctly

## 1.155.0 - 29.05.2022

### Added

- Added `EOD_HISTORICAL_DATA` as a new data source type

### Changed

- Exposed the environment variable `REDIS_PASSWORD`

### Fixed

- Fixed the empty state of the portfolio proportion chart component (with 2 levels)

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.154.0 - 28.05.2022

### Added

- Added a vertical hover line to inspect data points in the line chart component

### Changed

- Improved the tooltips of the chart components (content and style)
- Simplified the pricing page
- Improved the rounding numbers in the twitter bot service
- Removed the dependency `round-to`

## 1.153.0 - 27.05.2022

### Added

- Extended the benchmarks of the markets overview by the current market condition (bear and bull market)
- Extended the twitter bot service by benchmarks
- Added value redaction for the impersonation mode in the API response as an interceptor

### Changed

- Changed the twitter bot service to rest on the weekend
- Upgraded `prisma` from version `3.12.0` to `3.14.0`

### Fixed

- Fixed a styling issue in the benchmark component on mobile

## 1.152.0 - 26.05.2022

### Added

- Added the _Ghostfolio_ trailer to the landing page
- Extended the markets overview by benchmarks (current change to the all time high)

## 1.151.0 - 24.05.2022

### Added

- Added support to set the base currency as an environment variable (`BASE_CURRENCY`)

### Fixed

- Fixed an issue with the missing conversion of countries in the symbol profile overrides

## 1.150.0 - 21.05.2022

### Changed

- Skipped data enhancer (_Trackinsight_) if data is inaccurate

### Fixed

- Fixed an issue with the currency conversion in the account calculations
- Fixed an issue with countries in the symbol profile overrides

## 1.149.0 - 16.05.2022

### Added

- Added groups to the activities filter component
- Added support for filtering by asset class on the allocations page

## 1.148.0 - 14.05.2022

### Added

- Supported enter key press to submit the form of the create or edit transaction dialog
- Added a _Report Data Glitch_ button to the position detail dialog

### Fixed

- Fixed the date format of the date picker and support manual changes
- Fixed the state of the account delete button (disable if account contains activities)
- Fixed an issue in the activities filter component (typing a search term)

## 1.147.0 - 10.05.2022

### Changed

- Improved the allocations page with no filtering (include cash positions)

## 1.146.3 - 08.05.2022

### Added

- Set up a queue for the data gathering jobs
- Set up _Nx Cloud_

### Changed

- Migrated the asset profile data gathering to the queue design pattern
- Improved the allocations page with no filtering
- Harmonized the _No data available_ label in the portfolio proportion chart component
- Improved the _FIRE_ calculator for the _Live Demo_
- Simplified the about page
- Upgraded `angular` from version `13.2.2` to `13.3.6`
- Upgraded `Nx` from version `13.8.5` to `14.1.4`
- Upgraded `storybook` from version `6.4.18` to `6.4.22`

### Fixed

- Eliminated the circular dependencies in the `@ghostfolio/common` library

## 1.145.0 - 07.05.2022

### Added

- Added support for filtering by accounts on the allocations page
- Added support for private equity
- Extended the form to set the asset and asset sub class for (wealth) items

### Changed

- Refactored the filtering (activities table and allocations page)

### Fixed

- Fixed the tooltip update in the portfolio proportion chart component

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.144.0 - 30.04.2022

### Added

- Added support for commodities (via futures)
- Added support for real estate

### Changed

- Improved the layout of the position detail dialog
- Upgraded `yahoo-finance2` from version `2.3.1` to `2.3.2`

### Fixed

- Fixed the import validation for numbers equal 0
- Fixed the color of the spinner in the activities filter component (dark mode)

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.143.0 - 26.04.2022

### Changed

- Improved the filtering by tags

## 1.142.0 - 25.04.2022

### Added

- Added the tags to the create or edit transaction dialog
- Added the tags to the position detail dialog

### Changed

- Changed the date to UTC in the data gathering service
- Reused the value component in the users table of the admin control panel

## 1.141.1 - 24.04.2022

### Added

- Added the database migration

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.141.0 - 24.04.2022

### Added

- Added a tagging system for activities

### Changed

- Extracted the activities table filter to a dedicated component
- Changed the url of the _Get Started_ link to `https://ghostfol.io` on the public page
- Simplified `@@id` using multiple fields with `@id` in the database schema of (`Access`, `Order`, `Subscription`)
- Upgraded `prisma` from version `3.11.1` to `3.12.0`

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.140.2 - 22.04.2022

### Added

- Added support for sub-labels in the value component
- Added a symbol profile overrides model for manual adjustments

### Changed

- Reused the value component in the _Ghostfolio in Numbers_ section of the about page
- Persisted the savings rate in the _FIRE_ calculator
- Upgraded `yahoo-finance2` from version `2.3.0` to `2.3.1`

### Fixed

- Fixed the calculation of the total value for sell and dividend activities in the create or edit transaction dialog

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.139.0 - 18.04.2022

### Added

- Added the total amount to the tooltip in the chart of the _FIRE_ calculator

### Changed

- Beautified the ETF names in the symbol profile

### Fixed

- Fixed an issue with changing the investment horizon in the chart of the _FIRE_ calculator
- Fixed an issue with the end dates in the `.ics` file of the future activities (drafts) export
- Fixed the data source of the _Fear & Greed Index_ (market mood)

## 1.138.0 - 16.04.2022

### Added

- Added support to export a single future activity (draft) as an `.ics` file
- Added the _Boringly Getting Rich_ guide to the resources section

### Changed

- Separated the deposit and savings in the chart of the _FIRE_ calculator

## 1.137.0 - 15.04.2022

### Added

- Added support to export future activities (drafts) as an `.ics` file

### Changed

- Migrated the search functionality to `yahoo-finance2`

### Fixed

- Fixed an issue in the average price / investment calculation for sell activities

## 1.136.0 - 13.04.2022

### Changed

- Changed the _Total_ label to _Total Assets_ in the portfolio summary tab on the home page

### Fixed

- Fixed an issue with the calculation of the projected total amount in the _FIRE_ calculator
- Fixed an issue with the loading state of the _FIRE_ calculator

## 1.135.0 - 10.04.2022

### Added

- Added a calculator to the _FIRE_ section
- Added support for the cryptocurrency _Terra_ (`LUNA1-USD`)
- Added support for the cryptocurrency _THORChain_ (`RUNE-USD`)

## 1.134.0 - 09.04.2022

### Changed

- Switched to the new calculation engine
- Improved the 4% rule in the _FIRE_ section
- Changed the background of the header to a solid color

## 1.133.0 - 07.04.2022

### Changed

- Improved the empty state of the portfolio proportion chart component

### Fixed

- Fixed an issue with dates in the value component

## 1.132.1 - 06.04.2022

### Fixed

- Fixed an issue with percentages in the value component

## 1.132.0 - 06.04.2022

### Added

- Added support for localization (date and number format) in user settings

### Changed

- Improved the label of the average price from _Ø Buy Price_ to _Average Unit Price_

## 1.131.1 - 04.04.2022

### Fixed

- Fixed the missing API version in the _Stripe_ success callback url

## 1.131.0 - 02.04.2022

### Added

- Added API versioning
- Added more durations in the coupon system

### Changed

- Displayed the value in base currency in the accounts table on mobile
- Displayed the value in base currency in the activities table on mobile
- Renamed `orders` to `activities` in import and export functionality
- Harmonized the algebraic sign of `currentGrossPerformancePercent` and `currentNetPerformancePercent` with `currentGrossPerformance` and `currentNetPerformance`
- Improved the pricing page
- Upgraded `prisma` from version `3.10.0` to `3.11.1`
- Upgraded `yahoo-finance2` from version `2.2.0` to `2.3.0`

## 1.130.0 - 30.03.2022

### Added

- Added a _FIRE_ (Financial Independence, Retire Early) section including the 4% rule
- Added more durations in the coupon system

### Fixed

- Fixed an issue with the currency conversion (duplicate) in the account calculations

## 1.129.0 - 26.03.2022

### Added

- Added the calculation for developed vs. emerging markets to the allocations page
- Added a hover effect to the page tabs
- Extended the feature overview page by _Bonds_ and _Emergency Fund_

## 1.128.0 - 19.03.2022

### Added

- Added the attribute `defaultMarketPrice` to the scraper configuration to improve the support for bonds
- Added a hover effect to the table style

### Fixed

- Fixed an issue with the user currency of the public page
- Fixed an issue of the performance calculation with recent activities in the new calculation engine

## 1.127.0 - 16.03.2022

### Changed

- Improved the error handling in the scraper configuration

### Fixed

- Fixed the support for multiple symbols of the data source `GHOSTFOLIO`

## 1.126.0 - 14.03.2022

### Added

- Added support for bonds

### Changed

- Restructured the portfolio summary tab on the home page
- Improved the tooltips in the portfolio proportion chart component by introducing multilines

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.125.0 - 12.03.2022

### Added

- Added support for an emergency fund
- Added the contexts to the logger commands

### Changed

- Upgraded `Nx` from version `13.8.1` to `13.8.5`

## 1.124.0 - 06.03.2022

### Added

- Added support for setting a duration in the coupon system

### Changed

- Upgraded `ngx-skeleton-loader` from version `2.9.1` to `5.0.0`
- Upgraded `prisma` from version `3.9.1` to `3.10.0`
- Upgraded `yahoo-finance2` from version `2.1.9` to `2.2.0`

## 1.123.0 - 05.03.2022

### Added

- Included data provider errors in the API response

### Changed

- Removed the redundant attributes (`currency`, `dataSource`, `symbol`) of the activity model
- Removed the prefix for symbols with the data source `GHOSTFOLIO`

### Fixed

- Improved the account calculations

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.122.0 - 01.03.2022

### Added

- Added support for click in the portfolio proportion chart component

### Fixed

- Fixed an issue with undefined currencies after creating an activity

## 1.121.0 - 27.02.2022

### Added

- Added support for mutual funds
- Added the url to the symbol profile model

### Changed

- Migrated from `yahoo-finance` to `yahoo-finance2`

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.120.0 - 25.02.2022

### Changed

- Distinguished the labels _Other_ and _Unknown_ in the portfolio proportion chart component
- Improved the portfolio entry page

### Fixed

- Fixed the _Zen Mode_

## 1.119.0 - 21.02.2022

### Added

- Added a trial for the subscription

## 1.118.0 - 20.02.2022

### Changed

- Improved the calculation of the overall performance percentage in the new calculation engine
- Displayed features in features overview page based on permissions
- Extended the data points of historical data in the admin control panel

## 1.117.0 - 19.02.2022

### Changed

- Moved the countries and sectors charts in the position detail dialog
- Distinguished today's data point of historical data in the admin control panel
- Restructured the server modules

### Fixed

- Fixed the allocations by account for non-unique account names
- Added a fallback to the default account if the `accountId` is invalid in the import functionality for activities

## 1.116.0 - 16.02.2022

### Added

- Added a service to tweet the current _Fear & Greed Index_ (market mood)

### Changed

- Improved the mobile layout of the position detail dialog (countries and sectors charts)

### Fixed

- Fixed the `maxItems` attribute of the portfolio proportion chart component
- Fixed the time in market display of the portfolio summary tab on the home page

## 1.115.0 - 13.02.2022

### Added

- Added a feature overview page
- Added the asset and asset sub class to the position detail dialog
- Added the countries and sectors to the position detail dialog

### Changed

- Upgraded `angular` from version `13.1.2` to `13.2.2`
- Upgraded `Nx` from version `13.4.1` to `13.8.1`
- Upgraded `storybook` from version `6.4.9` to `6.4.18`

## 1.114.1 - 10.02.2022

### Fixed

- Fixed the creation of (wealth) items

## 1.114.0 - 10.02.2022

### Added

- Added support for (wealth) items

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.113.0 - 09.02.2022

### Changed

- Improved the position of the currency column in the accounts table
- Improved the position of the currency column in the activities table

### Fixed

- Fixed an issue with the performance calculation in connection with fees in the new calculation engine

## 1.112.1 - 06.02.2022

### Fixed

- Fixed the creation of the user account (missing access token)

## 1.112.0 - 06.02.2022

### Added

- Added the export functionality to the position detail dialog

### Changed

- Improved the export functionality for activities (respect filtering)
- Removed the _Admin_ user from the database seeding
- Assigned the role `ADMIN` on sign up (only if there is no admin yet)
- Upgraded `prisma` from version `3.8.1` to `3.9.1`

### Fixed

- Fixed an issue with the performance calculation in connection with a sell activity in the new calculation engine
- Fixed the horizontal overflow in the accounts table
- Fixed the horizontal overflow in the activities table
- Fixed the total value of the activities table in the position detail dialog (absolute value)

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.111.0 - 03.02.2022

### Added

- Added support for deleting symbol profile data in the admin control panel

### Changed

- Used `dataSource` and `symbol` from `SymbolProfile` instead of the `order` object (in `ExportService` and `PortfolioService`)

### Fixed

- Fixed the symbol selection of the 7d data gathering

## 1.110.0 - 02.02.2022

### Fixed

- Fixed the data source of the _Fear & Greed Index_ (market mood)

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.109.0 - 01.02.2022

### Added

- Added support for the (optional) `accountId` in the import functionality for activities
- Added support for the (optional) `dataSource` in the import functionality for activities
- Added support for the data source transformation
- Added support for the cryptocurrency _Mina Protocol_ (`MINA-USD`)

### Changed

- Improved the usability of the form in the create or edit transaction dialog
- Improved the consistent use of `symbol` in combination with `dataSource`
- Removed the primary data source from the client

### Removed

- Removed the unused endpoint `GET api/order/:id`

## 1.108.0 - 27.01.2022

### Changed

- Improved the annualized performance in the new calculation engine
- Increased the historical data chart of the _Fear & Greed Index_ (market mood) to 90 days

## 1.107.0 - 24.01.2022

### Added

- Added a new calculation engine (experimental)

### Fixed

- Fixed the styling in the footer row of the activities table

## 1.106.0 - 23.01.2022

### Added

- Added the footer row with total fees and total value to the activities table

### Changed

- Extended the historical data view in the admin control panel
- Upgraded _Stripe_ dependencies
- Upgraded `prisma` from version `3.7.0` to `3.8.1`

### Fixed

- Improved the redirection on logout

## 1.105.0 - 20.01.2022

### Added

- Added support for fetching multiple symbols in the `GOOGLE_SHEETS` data provider

### Changed

- Improved the data provider with grouping by data source and thereby reducing the number of requests

### Fixed

- Fixed the unresolved account names in the _X-ray_ section
- Fixed the date conversion in the `GOOGLE_SHEETS` data provider

## 1.104.0 - 16.01.2022

### Fixed

- Fixed the fallback to load currencies directly from the data provider
- Fixed the missing symbol profile data connection in the import functionality for activities

## 1.103.0 - 13.01.2022

### Changed

- Added links to the statistics section on the about page

### Fixed

- Fixed the currency of the value in the position detail dialog

## 1.102.0 - 11.01.2022

### Changed

- Start eliminating `dataSource` from activity

### Fixed

- Fixed the support for multiple accounts with the same name
- Fixed the preselected default account of the create activity dialog

## 1.101.0 - 08.01.2022

### Added

- Added `GOOGLE_SHEETS` as a new data source type

### Changed

- Excluded the url pattern of shared portfolios in the `robots.txt` file

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.100.0 - 05.01.2022

### Added

- Added the _Top 3_ and _Bottom 3_ performers to the analysis page
- Added a blog post

### Fixed

- Fixed the routing of the create activity dialog
- Fixed the link color in the blog posts

## 1.99.0 - 01.01.2022

### Added

- Exposed the profile data gathering by symbol as an endpoint

### Changed

- Improved the portfolio analysis page: show the y-axis and extend the chart in relation to the days in market
- Restructured the about page
- Start refactoring _transactions_ to _activities_
- Refactored the demo user id
- Upgraded `angular` from version `13.0.2` to `13.1.1`
- Upgraded `chart.js` from version `3.5.0` to `3.7.0`
- Upgraded `Nx` from version `13.3.0` to `13.4.1`

### Fixed

- Hid the data provider warning while loading
- Fixed an exception with the market state caused by a failed data provider request
- Fixed an exception in the portfolio position endpoint
- Fixed the reload of the position detail dialog (with query parameters)
- Fixed the missing mapping for Russia in the data enhancer for symbol profile data via _Trackinsight_

## 1.98.0 - 29.12.2021

### Added

- Added the date range component to the holdings tab

### Changed

- Extended the statistics section on the about page (users in Slack community)

### Fixed

- Fixed the creation of historical data in the admin control panel (upsert instead of update)
- Fixed the scrolling issue in the position detail dialog on mobile

## 1.97.0 - 28.12.2021

### Added

- Added the transactions to the position detail dialog
- Added support for dividend

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.96.0 - 27.12.2021

### Changed

- Made the data provider warning more discreet
- Upgraded `http-status-codes` from version `2.1.4` to `2.2.0`
- Upgraded `ngx-device-detector` from version `2.1.1` to `3.0.0`
- Upgraded `ngx-markdown` from version `12.0.1` to `13.0.0`
- Upgraded `ngx-stripe` from version `12.0.2` to `13.0.0`
- Upgraded `prisma` from version `3.6.0` to `3.7.0`

### Fixed

- Fixed the file type detection in the import functionality for transactions

## 1.95.0 - 26.12.2021

### Added

- Added a warning to the log if the data gathering fails

### Fixed

- Filtered potential `null` currencies
- Improved the 7d data gathering optimization for currencies

## 1.94.0 - 25.12.2021

### Added

- Added support for cryptocurrencies _Cosmos_ (`ATOM-USD`) and _Polkadot_ (`DOT-USD`)

### Changed

- Increased the historical data chart of the _Fear & Greed Index_ (market mood) to 30 days
- Made the import functionality for transactions by `csv` files more flexible
- Optimized the 7d data gathering (only consider symbols with incomplete market data)
- Upgraded `prettier` from version `2.3.2` to `2.5.1`

## 1.93.0 - 21.12.2021

### Added

- Added support for the cryptocurrency _Solana_ (`SOL-USD`)
- Extended the documentation for self-hosting with the [official Ghostfolio Docker image](https://hub.docker.com/r/ghostfolio/ghostfolio)

### Fixed

- Converted errors to warnings in portfolio calculator

## 1.92.0 - 19.12.2021

### Added

- Added a line chart to the historical data view in the admin control panel
- Supported the update of historical data in the admin control panel

### Fixed

- Improved the redirection on logout
- Fixed the permission for the system status page

## 1.91.0 - 18.12.2021

### Changed

- Removed the redundant all time high and all time low from the performance endpoint

### Fixed

- Fixed the symbol conversion from _Yahoo Finance_ including a hyphen
- Fixed hidden values (`0`) in the statistics section on the about page

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.90.0 - 14.12.2021

### Added

- Extended the validation in the import functionality for transactions by checking the currency of the data provider service
- Added support for cryptocurrency _Uniswap_
- Set up pipeline for docker build

### Changed

- Removed the default transactions import limit
- Improved the landing page in dark mode

### Fixed

- Fixed `/bin/sh: prisma: not found` in docker build
- Added `apk` in `Dockerfile` (`python3 g++ make openssl`)

## 1.89.0 - 11.12.2021

### Added

- Extended the data gathering by symbol endpoint with an optional date

### Changed

- Upgraded `Nx` from version `13.2.2` to `13.3.0`
- Upgraded `storybook` from version `6.4.0-rc.3` to `6.4.9`

## 1.88.0 - 09.12.2021

### Added

- Added a coupon system

## 1.87.0 - 07.12.2021

### Added

- Supported the management of additional currencies in the admin control panel
- Introduced the system message
- Introduced the read only mode

### Changed

- Increased the historical data chart of the _Fear & Greed Index_ (market mood) to 10 days
- Upgraded `prisma` from version `2.30.2` to `3.6.0`

## 1.86.0 - 04.12.2021

### Added

- Added the historical data chart of the _Fear & Greed Index_ (market mood)

### Changed

- Improved the historical data view in the admin control panel (hide invalid and future dates)
- Enabled the import functionality for transactions by default
- Converted the symbols to uppercase to avoid case-sensitive duplicates in the symbol profile model

### Fixed

- Improved the allocations by currency in combination with cash balances

## 1.85.0 - 01.12.2021

### Fixed

- Fixed the data gathering of the _Fear & Greed Index_ (market mood)

## 1.84.0 - 30.11.2021

### Added

- Exposed the data gathering by symbol as an endpoint

## 1.83.0 - 29.11.2021

### Changed

- Removed the experimental API

### Fixed

- Eliminated the redundant storage of historical exchange rates

## 1.82.0 - 28.11.2021

### Added

- Added tabs with routing to the admin control panel
- Added a new tab to manage historical data to the admin control panel

### Changed

- Introduced tabs with routing to the home page

## 1.81.0 - 27.11.2021

### Added

- Added the value to the position detail dialog

### Changed

- Upgraded `angular` from version `12.2.4` to `13.0.2`
- Upgraded `angular-material-css-vars` from version `2.1.2` to `3.0.0`
- Upgraded `nestjs` from version `7.6.18` to `8.2.3`
- Upgraded `Nx` from version `12.8.0` to `13.2.2`
- Upgraded `rxjs` from version `6.6.7` to `7.4.0`
- Upgraded `storybook` from version `6.3.8` to `6.4.0-rc.3`

### Fixed

- Fixed the broken line charts showing value labels if openend from the allocations page
- Fixed the click event for drafts in the transactions table

## 1.80.0 - 23.11.2021

### Added

- Accentuated the all time high and the all time low

## 1.79.0 - 21.11.2021

### Added

- Added the value column to the positions table
- Added support for cryptocurrency _Algorand_

### Changed

- Locked the symbol input in the edit transaction dialog
- Filtered the account selector by account type (`SECURITIES`) in the create or edit transaction dialog

### Fixed

- Fixed the search functionality for cryptocurrency symbols (do not show unsupported symbols)

## 1.78.0 - 20.11.2021

### Added

- Added a testimonial section to the landing page

### Fixed

- Fixed the footer row border of the accounts table in dark mode

## 1.77.0 - 16.11.2021

### Changed

- Hid the _Get Started_ button on the registration page

### Fixed

- Fixed the footer row of the accounts table on mobile
- Fixed the transactions count calculation in the accounts table (exclude drafts)

## 1.76.0 - 14.11.2021

### Added

- Added the footer row with buying power and net worth to the accounts table

## 1.75.0 - 13.11.2021

### Added

- Added a logo to the log on the server start
- Added the data gathering progress to the log and the admin control panel
- Added the value column to the accounts table

## 1.74.0 - 11.11.2021

### Changed

- Adapted the decimal places for cryptocurrencies in the position detail dialog
- Moved the _Fear & Greed Index_ (market mood) to a new tab on the home page

## 1.73.0 - 10.11.2021

### Changed

- Improved the info messages to add the first transaction

### Fixed

- Fixed the skeleton loader of the portfolio holdings

## 1.72.0 - 08.11.2021

### Changed

- Cached the statistics section on the about page

## 1.71.0 - 07.11.2021

### Changed

- Changed the logger from `console.log()` to `Logger.log()`

### Fixed

- Fixed an exception in the scraper configuration

## 1.70.0 - 07.11.2021

### Changed

- Improved the validation of `json` files in the import functionality for transactions
- Moved the scraper configuration to the symbol profile model

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.69.0 - 07.11.2021

### Added

- Added the symbol mapping attribute to the symbol profile model

### Changed

- Improved the registration page

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.68.0 - 01.11.2021

### Changed

- Prettified the generic scraper symbols in the portfolio proportion chart component
- Extended the statistics section on the about page by the active users count (7d)
- Extended the statistics section on the about page by the new users count

## 1.67.0 - 31.10.2021

### Added

- Added more details to the public page (currencies, sectors, continents and regions)
- Added a `Dockerfile` and documentation to build a _Docker_ image

## 1.66.0 - 30.10.2021

### Changed

- Improved the landing page
- Ordered the granted accesses by type

## 1.65.0 - 25.10.2021

### Added

- Added the user interface for granting and revoking public access to share the portfolio

### Changed

- Moved the data enhancer calls from the data provider (`get()`) to the data gathering service to reduce traffic to 3rd party data providers
- Changed the profile data gathering from every 12 hours to once every weekend

## 1.64.0 - 21.10.2021

### Added

- Added support for more cryptocurrency symbols like _Avalanche_, _Polygon_, _Shiba Inu_ etc.

### Changed

- Changed the data provider service to handle a dynamic list of services

## 1.63.0 - 19.10.2021

### Added

- Added a public page to share the portfolio

### Changed

- Improved the skeleton loader size of the portfolio proportion chart component

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.62.0 - 17.10.2021

### Added

- Extended the validation message of the import functionality for transactions

## 1.61.0 - 15.10.2021

### Added

- Extended the import functionality for transactions by `csv` files
- Introduced the primary data source

### Changed

- Restricted the file selector of the import functionality for transactions to `csv` and `json`

## 1.60.0 - 13.10.2021

### Added

- Extended the validation of the import functionality for transactions
  - Valid data types
  - Maximum number of orders
  - No duplicate orders
  - Data provider service returns data for the `dataSource` / `symbol` pair

### Changed

- Harmonized the page layouts

### Fixed

- Fixed the broken line charts showing value labels

## 1.59.0 - 11.10.2021

### Added

- Added a data enhancer for symbol profile data (countries and sectors) via _Trackinsight_

### Changed

- Changed the values of the global heat map to fixed-point notation

### Fixed

- Fixed the links of cryptocurrency assets in the positions table
- Fixed various values in the impersonation mode which have not been nullified

## 1.58.1 - 03.10.2021

### Fixed

- Fixed an issue in the symbol conversion for _Yahoo Finance_ (for a cryptocurrency with the same code as a currency)

## 1.58.0 - 02.10.2021

### Changed

- Improved the symbol conversion for _Yahoo Finance_: Support for _Solana USD_ (`SOL1-USD`)
- Improved the tooltips of the allocations page
- Upgraded `envalid` from version `7.1.0` to `7.2.1`

## 1.57.0 - 29.09.2021

### Added

- Added a protection for endpoints (subscriptions)

### Changed

- Reformatted the exchange rates table in the admin control panel

## 1.56.0 - 25.09.2021

### Added

- Added a story for the line chart component
- Added a story for the portfolio proportion chart component

### Changed

- Changed the navigation to always show the portfolio page
- Migrated the data type of currencies from `enum` to `string` in the database
- Supported unlimited currencies (instead of `CHF`, `EUR`, `GBP` and `USD`)
- Respected the accounts' currencies in the exchange rate service

### Fixed

- Hid the actions from the accounts table in the _Presenter View_
- Hid the actions from the transactions table in the _Presenter View_
- Fixed the data gathering of the initial project setup (database seeding)

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.55.0 - 20.09.2021

### Changed

- Removed the default value of the data source attribute
- Upgraded `@storybook` dependencies

### Fixed

- Fixed an issue in the create or edit transaction dialog

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.54.0 - 18.09.2021

### Added

- Added the data source attribute to the symbol profile model

### Changed

- Respected the data source attribute in the data provider service
- Respected the data source attribute in the symbol data endpoint
- Improved the search functionality of the data management (multiple data sources)

### Fixed

- Hid the net performance in the _Presenter View_ (portfolio holdings and summary tab on the home page)
- Hid the sign if the performance is zero in the value component

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.53.0 - 13.09.2021

### Changed

- Optimized the annualized performance calculation
- Changed the data gathering selection from distinct orders to symbol profiles

## 1.52.0 - 11.09.2021

### Added

- Added the annualized performance to the portfolio summary tab on the home page
- Added the Ghostfolio Slack channel to the about page

### Changed

- Upgraded `@simplewebauthn/browser` and `@simplewebauthn/server` from version `3.0.0` to `4.1.0`

### Fixed

- Fixed the sign in with fingerprint for some android devices

## 1.51.0 - 11.09.2021

### Changed

- Provided the name in the portfolio position endpoint

## 1.50.0 - 11.09.2021

### Fixed

- Fixed the _Fear & Greed Index_ (market mood)
- Fixed the overlap of the home button with tabs on iOS (_Add to Home Screen_)

## 1.49.0 - 08.09.2021

### Added

- Added labels to the allocation chart by symbol on desktop

## 1.48.0 - 07.09.2021

### Added

- Added the attribute `precision` in the value component

### Fixed

- Hid the performance in the _Presenter View_

## 1.47.1 - 06.09.2021

### Fixed

- Fixed the search functionality for cryptocurrency symbols

## 1.46.0 - 05.09.2021

### Added

- Extended the statistics section on the about page by the _GitHub_ contributors count
- Set up _Storybook_
  - Added a story for the logo component
  - Added a story for the no transactions info component
  - Added a story for the trend indicator component
  - Added a story for the value component

### Changed

- Switched from gross to net performance
- Restructured the portfolio summary tab on the home page (fees and net performance)

## 1.45.0 - 04.09.2021

### Added

- Added a link below the holdings to manage the transactions
- Added the allocation chart by symbol

### Changed

- Restructured the allocations page
- Upgraded `angular` from version `12.0.4` to `12.2.4`
- Upgraded `@angular/cdk` and `@angular/material` from version `12.0.6` to `12.2.4`
- Upgraded `Nx` from version `12.5.4` to `12.8.0`
- Upgraded `prisma` from version `2.24.1` to `2.30.2`

### Fixed

- Fixed the value formatting for integers (transactions count)

## 1.44.0 - 30.08.2021

### Changed

- Extended the sub classification of assets by cash
- Upgraded `svgmap` from version `2.1.1` to `2.6.0`

### Fixed

- Filtered out positions without any quantity in the positions table
- Improved the symbol lookup: allow saving with valid symbol in create or edit transaction dialog

## 1.43.0 - 24.08.2021

### Added

- Extended the data management of symbol profile data by countries (automated for stocks)
- Added a fallback for initially loading currencies if historical data is not yet available

## 1.42.0 - 22.08.2021

### Added

- Added the subscription type to the users table of the admin control panel
- Introduced the sub classification of assets

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.41.0 - 21.08.2021

### Added

- Added a link to the system status page

### Changed

- Improved the wording for the _Restricted View_: _Presenter View_
- Improved the styling of the tables
- Ignored cash assets in the allocation chart by sector, continent and country

### Fixed

- Fixed an issue in the allocation chart by account (wrong calculation)
- Fixed an issue in the allocation chart by account (missing cash accounts)

## 1.40.0 - 19.08.2021

### Changed

- Improved the fault tolerance of the portfolio details endpoint

### Fixed

- Fixed the node engine version mismatch in `package.json`
- Fixed an issue on the buy date in the position detail dialog
- Fixed an issue with the currency inconsistency in the _Yahoo Finance_ service (convert from `GBp` to `GBP`)

## 1.39.0 - 16.08.2021

### Added

- Added an option to hide absolute values like performances and quantities (_Restricted View_)

### Changed

- Restructured the allocations page

### Fixed

- Fixed an issue with the performance in the portfolio summary tab on the home page (impersonation mode)
- Fixed various values in the impersonation mode which have not been nullified

### Removed

- Removed the current net performance
- Removed the read foreign portfolio permission

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.38.0 - 14.08.2021

### Added

- Added the overview menu item on mobile

### Changed

- Refactored the exchange rate service
- Improved the users table in the admin control panel

## 1.37.0 - 13.08.2021

### Added

- Added the calculated net worth to the portfolio summary tab on the home page
- Added the calculated time in market to the portfolio summary tab on the home page

### Changed

- Improved the usability of the tabs on the home page
- Restructured the portfolio summary tab on the home page
- Upgraded `angular-material-css-vars` from version `2.1.0` to `2.1.2`

### Fixed

- Fixed the position detail chart if there are missing historical data around the first buy date
- Fixed the snack bar background color in dark mode
- Fixed the search functionality for symbols (filter for supported currencies)

## 1.36.0 - 09.08.2021

### Changed

- Improved the data gathering handling on server restart
- Respected the cash balance on the allocations page
- Eliminated the name from the scraper configuration

### Fixed

- Fixed hidden cryptocurrency holdings

## 1.35.0 - 08.08.2021

### Changed

- Hid the pagination of tabs
- Improved the classification of assets
- Improved the support for future transactions (drafts)
- Optimized the accounts table for mobile
- Upgraded `chart.js` from version `3.3.2` to `3.5.0`

### Fixed

- Added a fallback if the exchange rate service has not been initialized correctly

### Todo

- Apply data migration (`yarn database:migrate`)

## 1.34.0 - 07.08.2021

### Changed

- Restructured the page hierarchy

### Fixed

- Fixed an issue with the currency conversion of the market price in the position detail dialog
- Fixed the chart and missing data of positions from the past in the position detail dialog

## 1.33.0 - 05.08.2021

### Fixed

- Fixed an issue of a division by zero in the portfolio calculations
- Fixed an issue with the currency conversion in the position detail dialog

## 1.32.0 - 04.08.2021

### Added

- Added the name to the position detail dialog when opened from the transactions table
- Added a screenshot to the blog posts

### Fixed

- Fixed the missing market state in the positions tab
- Fixed the chart of positions with differing currency from user

## 1.31.1 - 01.08.2021

### Fixed

- Fixed an issue with the currency conversion in the portfolio calculations

## 1.31.0 - 01.08.2021

### Added

- Added more data points to the chart

### Changed

- Rewritten the core engine for the portfolio calculations
  - Switched to [Time-Weighted Rate of Return](https://www.investopedia.com/terms/t/time-weightedror.asp) (TWR) for the performance calculation
  - Improved the performance of the portfolio calculations

## 1.30.0 - 31.07.2021

### Added

- Added the date range component to the positions tab
- Added a blog

## 1.29.0 - 26.07.2021

### Changed

- Introduced tabs on the home page
- Changed the menu icon if the menu is open on mobile

## 1.28.0 - 24.07.2021

### Added

- Extended the data management by symbol profile data
- Added a currency attribute to the symbol profile model
- Added a positions button on the home page which scrolls into the view

### Changed

- Improved the style of the active page in the navigation on desktop
- Removed the footer for users
- Extended the _Zen Mode_ by positions
- Improved the _Create Account_ message in the _Live Demo_

## 1.27.0 - 18.07.2021

### Changed

- Improved the onboarding
  - Flow of creating a new account
  - Info message to add the first transaction

### Fixed

- Fixed the chart on the landing page
- Fixed the url to the _Fear & Greed Index_ on the resources page

## 1.26.0 - 17.07.2021

### Added

- Added the import functionality for transactions
- Added the `robots.txt` file

### Changed

- Improved the styling of the current pricing plan
- Improved the styling of the transaction type badge
- Set the public _Stripe_ key dynamically
- Upgraded `angular-material-css-vars` from version `2.0.0` to `2.1.0`

### Fixed

- Fixed the warn color (button) of the theme

## 1.25.0 - 11.07.2021

### Added

- Added the export functionality for transactions

### Changed

- Respected the cash balance on the analysis page
- Improved the settings selectors on the account page
- Harmonized the slogan to "Open Source Wealth Management Software"

### Fixed

- Fixed rendering of currency and platform in dialogs (account and transaction)
- Fixed an issue in the calculation of the average buy prices in the position detail chart

## 1.24.0 - 07.07.2021

### Added

- Added the total value in the create or edit transaction dialog
- Added a balance attribute to the account model
- Calculated the total balance (cash)

### Changed

- Upgraded `@angular/cdk` and `@angular/material` from version `11.0.4` to `12.0.6`
- Upgraded `@nestjs` dependencies
- Upgraded `angular-material-css-vars` from version `1.2.0` to `2.0.0`
- Upgraded `Nx` from version `12.3.6` to `12.5.4`

## 1.23.1 - 03.07.2021

### Fixed

- Fixed the investment chart (drafts)

## 1.23.0 - 03.07.2021

### Added

- Added support for future transactions (drafts)

## 1.22.0 - 25.06.2021

### Added

- Set the user id in the _Stripe_ callback

## 1.21.0 - 22.06.2021

### Changed

- Changed _Stripe_ mode from `subscription` to `payment`

### Fixed

- Fixed the base currency on the pricing page

## 1.20.0 - 21.06.2021

### Added

- Set up _Stripe_ for subscriptions

### Changed

- Improved the style of the _Ghostfolio in Numbers_ section

## 1.19.0 - 17.06.2021

### Added

- Added a _Ghostfolio in Numbers_ section to the about page

## 1.18.0 - 16.06.2021

### Changed

- Improved the pie chart: Investments by sector
- Improved the onboarding for TWA by redirecting to the account registration page

## 1.17.0 - 15.06.2021

### Changed

- Improved the error page of the sign in with fingerprint
- Disable the sign in with fingerprint selector for the demo user
- Upgraded `angular` from version `11.2.4` to `12.0.4`
- Upgraded `angular-material-css-vars` from version `1.1.2` to `1.2.0`
- Upgraded `chart.js` from version `3.2.1` to `3.3.2`
- Upgraded `date-fns` from version `2.19.0` to `2.22.1`
- Upgraded `eslint` and `prettier` dependencies
- Upgraded `ngx-device-detector` from version `2.0.6` to `2.1.1`
- Upgraded `ngx-markdown` from version `11.1.2` to `12.0.1`

## 1.16.0 - 14.06.2021

### Changed

- Improved the sign in with fingerprint

## 1.15.0 - 14.06.2021

### Added

- Added a counter column to the transactions table
- Added a label to indicate the default account in the accounts table
- Added an option to limit the items in pie charts
- Added sign in with fingerprint

### Changed

- Cleaned up the analysis page with an unused chart module
- Improved the cell alignment in the users table of the admin control panel

### Fixed

- Fixed the last activity column of users in the admin control panel

## 1.14.0 - 09.06.2021

### Added

- Added a connect or create symbol profile model logic on creating a new transaction

### Changed

- Improved the global heat map to visualize investments by country

## 1.13.0 - 08.06.2021

### Added

- Added a global heat map to visualize investments by country

## 1.12.0 - 06.06.2021

### Added

- Added a symbol profile model with additional data
- Added new pie charts: Investments by continent and country

## 1.11.0 - 05.06.2021

### Added

- Added a dedicated page for the account registration
- Rendered the average buy prices in the position detail chart (useful for recurring transactions)
- Introduced the initial prisma migration

### Changed

- Changed the buttons to links (`<a>`) on the tools page
- Upgraded `prisma` from version `2.20.1` to `2.24.1`

## 1.10.1 - 02.06.2021

### Fixed

- Fixed an optional type in the user interface

## 1.10.0 - 02.06.2021

### Changed

- Moved the tools to a sub path (`/tools`)
- Extended the pricing page and aligned with the subscription model

## 1.9.0 - 01.06.2021

### Added

- Added the year labels to the investment chart on the x-axis

### Changed

- Respected the data source attribute of the transactions model in the data management for historical data
- Prettified the generic scraper symbols in the transaction filtering component
- Changed to the strict mode of distance formatting between two given dates

### Fixed

- Fixed the sorting in various tables
- Made the order of the rules in the _X-ray_ section consistent

## 1.8.0 - 24.05.2021

### Added

- Added a section for _Analysis_, _X-ray_ and upcoming tools

### Changed

- Introduced a user service implemented as an observable store (single source of truth for state)

### Fixed

- Fixed the performance chart by considering the investment
- Fixed missing header of public pages (_About_, _Pricing_, _Resources_)

## 1.7.0 - 22.05.2021

### Changed

- Hid footer on mobile (except on landing page)

### Fixed

- Fixed the internal navigation of the _Zen Mode_ in combination with a query parameter

## 1.6.0 - 22.05.2021

### Added

- Added an index in the users table of the admin control panel

### Changed

- Improved the alignment in the users table of the admin control panel

## 1.5.0 - 22.05.2021

### Added

- Added _Zen Mode_: the distraction-free view

## 1.4.0 - 20.05.2021

### Added

- Added filtering by year in the transaction filtering component

### Changed

- Renamed _Ghostfolio Account_ to _My Ghostfolio_
- Hid unknown exchange in the position overview
- Disable the base currency selector for the demo user
- Refactored the portfolio unit tests to work without database
- Refactored the search functionality of the data management (aligned with data source)
- Renamed shared helper to `@ghostfolio/common/helper`
- Moved shared interfaces to `@ghostfolio/common/interfaces`
- Moved shared types to `@ghostfolio/common/types`

## 1.3.0 - 15.05.2021

### Changed

- Refactored the active menu item state by parsing the current url
- Used a desaturated background color for unknown types in pie charts
- Renamed the columns _Initial Share_ and _Current Share_ to _Initial Allocation_ and _Current Allocation_ in the positions table

### Fixed

- Fixed the link to the pricing page

## 1.2.1 - 14.05.2021

### Changed

- Updated the sitemap

## 1.2.0 - 14.05.2021

### Changed

- Harmonized the style of various tables
- Keep the color per type when switching between _Initial_ and _Current_ in pie charts
- Upgraded `chart.js` from version `3.0.2` to `3.2.1`
- Moved the pricing section to a dedicated page
- Improved the style of the transaction filtering component

### Fixed

- Fixed the tooltips when switching between _Initial_ and _Current_ in pie charts

## 1.1.0 - 11.05.2021

### Added

- Added a button to fetch the current market price in the create or edit transaction dialog

### Changed

- Improved the transaction filtering with multi filter support

### Fixed

- Fixed the filtering by account name in the transactions table
- Fixed the active menu item state when a modal has opened

## 1.0.0 - 05.05.2021

### Added

- Added the functionality to clone a transaction
- Added a _Google Play_ badge on the landing page

### Changed

- Changed to maskable icons

## 0.99.0 - 03.05.2021

### Added

- Added support for deleting users in the admin control panel

### Changed

- Eliminated the platform attribute from the transaction model

## 0.98.0 - 02.05.2021

### Added

- Added the logic to create and update accounts

## 0.97.0 - 01.05.2021

### Added

- Added an account page as a preparation for the multi accounts support

## 0.96.0 - 30.04.2021

### Added

- Added the absolute change to the position detail dialog
- Added the number of transactions to the position detail dialog

### Changed

- Harmonized the slogan to "Open Source Portfolio Tracker"

## 0.95.0 - 28.04.2021

### Added

- Added a data source attribute to the transactions model

## 0.94.0 - 27.04.2021

### Added

- Added the generic scraper symbols to the symbol lookup results

## 0.93.0 - 26.04.2021

### Changed

- Improved the users table styling of the admin control panel
- Improved the background colors in the dark mode

## 0.92.0 - 25.04.2021

### Added

- Prepared further for multi accounts support: store account for new transactions
- Added a horizontal scrollbar to the users table of the admin control panel

### Fixed

- Fixed an issue in the header with outdated data
- Fixed an issue on the about page with outdated data

## 0.91.0 - 25.04.2021

### Added

- Extended the support for feature flags to simplify the initial project setup
- Prepared for multi accounts support

### Changed

- Improved the styling of the rules in the _X-ray_ section

## 0.90.0 - 22.04.2021

### Added

- Added the symbol logo to the position detail dialog
- Introduced a third option for the market state: `delayed` (besides `open` and `closed`)

### Changed

- Improved the users table of the admin control panel

## 0.89.0 - 21.04.2021

### Added

- Added a prettifier (pipe) for generic scraper symbols

### Fixed

- Fixed the text truncation in buttons of the admin control panel

## 0.88.0 - 20.04.2021

### Changed

- Reverted the restoring of the scroll position when opening a new page

### Fixed

- Fixed the frozen screen if the token has expired
- Fixed some issues in the generic scraper

## 0.87.0 - 19.04.2021

### Added

- Added a generic scraper

### Fixed

- Fixed an issue in the users table of the admin control panel with missing data

## 0.86.1 - 18.04.2021

### Added

- Added the license to the about page
- Added a validation for environment variables
- Added support for feature flags to simplify the initial project setup

### Changed

- Changed the about page for the new license
- Optimized the data management for historical data
- Optimized the exchange rate service
- Improved the users table of the admin control panel

### Fixed

- Restored the scroll position when opening a new page

## 0.85.0 - 16.04.2021

### Changed

- Refactored many frontend components
- Changed the routing to `routerLink` for an improved navigation experience
- Simplified the initial project setup

## 0.84.0 - 11.04.2021

### Fixed

- Fixed static portfolio analysis rules (_Currency Cluster Risk_) if no positions in base currency
  - Initial Investment: Base Currency
  - Current Investment: Base Currency

## 0.83.0 - 11.04.2021

### Added

- Added a new static portfolio analysis rule: Fees in relation to the initial investment

### Changed

- Reset the cache on the server start

### Fixed

- Fixed an issue in the portfolio update on deleting a transaction
- Fixed an issue in the _X-ray_ section (missing redirection on logout)

## 0.82.0 - 10.04.2021

### Added

- Added a gradient to the line charts
- Added a selector to set the base currency on the account page

## 0.81.0 - 06.04.2021

### Added

- Added support for assets in `GBP`
- Added an error handling with messages in the client

### Changed

- Changed the _Ghostfolio_ SaaS (cloud) from a `nano` to a `micro` instance for a better performance

## 0.80.0 - 05.04.2021

### Changed

- Improved the spacing in the header
- Upgraded `chart.js` from version `2.9.4` to `3.0.2`

## 0.79.0 - 04.04.2021

### Changed

- Refactored the data management services
- Upgraded `bootstrap` from version `4.5.3` to `4.6.0`
- Upgraded `date-fns` from version `2.16.1` to `2.19.0`
- Upgraded `ionicons` from version `5.4.0` to `5.5.1`
- Upgraded `lodash` from version `4.17.20` to `4.17.21`
- Upgraded `ngx-markdown` from version `11.1.0` to `11.1.2`
- Upgraded `ngx-skeleton-loader` from version `2.6.2` to `2.9.1`
- Upgraded `prisma` from version `2.18.0` to `2.20.1`

## 0.78.0 - 04.04.2021

### Added

- Added a spinner to the create or edit transaction dialog
- Added support for the back button in
  - portfolio performance chart dialog
  - position detail dialog
  - create transaction dialog
  - edit transaction dialog

### Changed

- Improved the single platform rule by adding the number of platforms

## 0.77.1 - 03.04.2021

### Changed

- Minor improvements

## 0.77.0 - 03.04.2021

### Added

- Added support for base currency in user settings
- Added an investment risk disclaimer to the footer
- Added two more static portfolio analysis rules:
  - _Currency Cluster Risk_ (current investment)
  - _Platform Cluster Risk_ (current investment)

### Changed

- Grouped the _X-ray_ section visually in _Currency Cluster Risk_ and _Platform Cluster Risk_

## 0.76.0 - 02.04.2021

### Added

- Added two more static portfolio analysis rules:
  - _Currency Cluster Risk_ (base currency)
  - _Platform Cluster Risk_ (single platform)

### Fixed

- Fixed an issue in the _X-ray_ section (empty portfolio)

## 0.75.0 - 01.04.2021

### Fixed

- Fixed an issue in the exchange rate service occurring on the first day of the month

## 0.74.0 - 01.04.2021

### Added

- Added a _Create Account_ message in the _Live Demo_
- Added skeleton loaders to the _X-ray_ section

### Changed

- Improved the alignment of the _Why Ghostfolio?_ section
- Improved the styling of the _Fear & Greed Index_ (market mood)

## 0.73.0 - 31.03.2021

### Added

- Added the _Fear & Greed Index_ (market mood) to the portfolio performance chart dialog
- Added a link to the info box on the analysis page

### Changed

- Improved the intro text in the _X-ray_ section

### Fixed

- Fixed the flickering of the _Sign in_ button in the header

## 0.72.1 - 30.03.2021

### Fixed

- Fixed an issue with updating or resetting the platform of a transaction

## 0.72.0 - 30.03.2021

### Added

- Added an intro text to the _X-ray_ section

### Changed

- Improved the editing of transactions
- Harmonized the page titles

### Fixed

- Fixed an issue with wrong transaction dates

## 0.71.0 - 28.03.2021

### Added

- Added the second static portfolio analysis rule: _Platform Cluster Risk_

### Changed

- Improved the styling in the _X-ray_ section

## 0.70.0 - 27.03.2021

### Added

- Added the current _Fear & Greed Index_ as text
- Extended the landing page text: _Ghostfolio_ empowers busy folks...
- Added the first static portfolio analysis rule in the brand new _X-ray_ section

### Changed

- Improved the spacing in the footer

## 0.69.0 - 27.03.2021

### Added

- Added the current _Fear & Greed Index_ to the resources page

## 0.68.0 - 26.03.2021

### Changed

- Improved the performance of the position detail dialog

### Fixed

- Fixed a scroll issue in dialogs

## 0.67.0 - 26.03.2021

### Added

- Added an experimental API to get historical data for benchmarks

## 0.66.0 - 25.03.2021

### Added

- Added a chevron to the position
- Added an experimental API to get benchmark data

## 0.65.0 - 24.03.2021

### Added

- Added a legend to the portfolio performance chart
- Added a placeholder to the filter of the transactions table

### Changed

- Changed the regular data management check to a smarter approach

## 0.64.0 - 23.03.2021

### Added

- Added an index to the market data database table

### Changed

- Optimized the other dialogs for mobile (full screen and close button)

## 0.63.0 - 22.03.2021

### Changed

- Improved the transactions table
- Optimized the position detail dialog for mobile (full screen and close button)

## 0.62.0 - 21.03.2021

### Fixed

- Fixed an issue while loading data concurrently via the date range component

## 0.61.0 - 21.03.2021

### Fixed

- Fixed an issue in the performance calculation if there are only transactions from today

## 0.60.0 - 20.03.2021

### Added

- Added a button to create the first transaction on the analysis page

### Fixed

- Fixed an issue on the analysis page if there are only transactions from today

## 0.59.0 - 20.03.2021

### Added

- Extended the landing page text: Why _Ghostfolio_?
- Extended the glossary of the resources page

## 0.58.0 - 20.03.2021

### Added

- Added meta data for _Open Graph_ and _Twitter Cards_
- Added meta data: `description` and `keywords`

### Changed

- Improved the icon

### Fixed

- Fixed the `sitemap.xml` file

## 0.57.0 - 19.03.2021

### Added

- Added the `sitemap.xml` file
- Added a resources page
- Added a chart to the landing page

### Changed

- Improved the performance chart
- Improved the average buy price in the position detail chart
- Improved the style of the active page in the navigation on mobile

## 0.56.0 - 18.03.2021

### Added

- Added the quantity and investment in the position detail dialog

### Changed

- Improved the performance chart
- Improved the performance calculation
- Improved the average buy price in the position detail chart

## 0.55.0 - 16.03.2021

### Changed

- Improved the performance calculation

## 0.54.0 - 15.03.2021

### Added

- Added another _Create Account_ button at the end of the landing page

### Fixed

- Fixed an issue in the position detail chart if the position has been bought today (no historical data)
- Fixed an issue in the transaction service with unordered items

## 0.53.0 - 14.03.2021

### Added

- Set up database backup

### Changed

- Improved `site.webmanifest`

## 0.52.0 - 14.03.2021

### Changed

- Added the membership status to the account page

### Fixed

- Fixed an issue in the chart (empty portfolio)

## 0.51.0 - 14.03.2021

### Changed

- Changed the default number of rows from 10 to 7 in the positions table

## 0.50.1 - 13.03.2021

### Fixed

- Fixed the button to expand rows in the positions table

## 0.50.0 - 13.03.2021

### Added

- Added filters to switch between _Original Shares_ vs. _Current Shares_ in pie charts
- Added a button to expand rows in the positions table

### Changed

- Ordered platforms by name in edit transaction dialog
- Modularized the date range component

### Fixed

- Fixed the error handling for the data management (errors in nested data)

## 0.49.0 - 13.03.2021

### Added

- Added additional portfolio filters for `1Y` and `5Y`
- Added an error handling for the data management

### Changed

- Improved the pricing section

## 0.48.1 - 11.03.2021

### Fixed

- Fixed the about page for unauthorized users

## 0.48.0 - 11.03.2021

### Added

- Added a pricing section

### Changed

- Improved the positions and transactions table
  - Harmonized alignment
  - Enabled position detail dialog

## 0.47.0 - 10.03.2021

### Added

- Added a positions table with information about _Original Shares_ vs. _Current Shares_
- Added data management to control panel

## 0.46.0 - 09.03.2021

### Added

- Added permission based access-control
- Added an admin control panel

## 0.45.0 - 08.03.2021

### Changed

- Changed the data management of benchmarks with extended persistency
- Changed the data management of currencies with extended persistency

## 0.44.0 - 07.03.2021

### Changed

- Changed the data management with extended persistency
- Upgraded `prisma` from version `2.16.1` to `2.18.0`
- Upgraded `angular` from version `11.0.9` to `11.2.4`

## 0.43.0 - 04.03.2021

### Fixed

- Fixed missing columns (_Quantity_, _Unit Price_ and _Fee_) in transactions table
- Fixed displaying edit transaction dialog in impersonation mode
- Fixed `/.well-known/assetlinks.json` for TWA

## 0.42.0 - 03.03.2021

### Changed

- Improved the skeleton loader (minor)

### Fixed

- Fixed the portfolio unit tests

## 0.41.0 - 02.03.2021

### Added

- Added the possibility to create or edit a transaction with a platform

### Changed

- Increased the token expiration duration

### Fixed

- Only show relevant data in the position detail dialog
- Improved the performance chart styling in Safari

## 0.40.0 - 01.03.2021

### Fixed

- Fixed the calculation issues occurring on the first day of each month
- Harmonized the percent value formatting

## 0.39.0 - 28.02.2021

### Changed

- Improved the buy price in the position detail dialog

### Fixed

- Fixed the (hidden) header issue

## 0.38.0 - 26.02.2021

### Added

- Added `/.well-known/assetlinks.json` for TWA

## 0.37.0 - 25.02.2021

### Added

- Added a benchmark (_S&P 500_) to the portfolio performance chart

## 0.36.1 - 24.02.2021

### Changed

- Minor improvements in the transactions table

## 0.36.0 - 24.02.2021

### Added

- Added the possibility to edit a transaction

## 0.35.0 - 23.02.2021

### Changed

- Added transparent background to header
- Harmonized currency value formatting

### Fixed

- Fixed header issue with (not) signed in

## 0.34.0 - 21.02.2021

### Changed

- Improved skeleton loader of position
- Simplified sign in / sign up flow

## 0.33.0 - 21.02.2021

### Added

- Added favicon and `site.webmanifest`

### Changed

- Set font style of numbers to tabular
- Rename _Orders_ to _Transactions_

### Security

- Additionally hash the _Security Token_ (no more stored in plain text)

## 0.32.0 - 20.02.2021

### Added

- Added a landing page text: How does _Ghostfolio_ work?
- Added the _Independent & Bootstrapped_ badge to the about page

## 0.31.0 - 20.02.2021

### Added

- Added a changelog to the about page
- Added a twitter account to the about page
- Added the version to the about page

## 0.30.0 - 19.02.2021

### Added

- Added an about page

## 0.29.0 - 19.02.2021

### Added

- Added a landing page text: Why _Ghostfolio_?

## 0.28.2 - 17.02.2021

### Added

- Added caching for the portfolio (Redis)