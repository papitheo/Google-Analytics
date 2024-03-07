# Google Analytics Tutorial Series

## Features

- Events
- Conversions
- Audiences
- Consent Mode
- Binding

## Creating a google analytics project/account

`Account Creation`

- On the homePage of the analytics dashboard, locate admin at the down left corner of the screen and click on it.
- click on create.
- Select account.
- Give your project/account a name
- Under account Data Sharing Settings, review the settings and select accordingly.
- Click next.

`Property creation`

- Create a property. (A property is used to report on an individual website but can be used to collect data on multiple websites and apps into a single property so evevrything is combine or synced into one set of report). Good to name is so it reflect either one or the combination of application you will be reporting on.
- Select time zone accordingly
- Select Currency accordingly
- click next

`Business Details`

- Select Industry Category
- Select size of business

`Business Objective`

- The selection you make here would determine which configured report would be added to your property. Recommendered to select the `Get baseline report` as it includes evevrything that is available in the other four options.
- Click create and agree to the terms to creat your google analytics account

## Setting up a Data Stream (Data Collection)

`A data stream is used to collect data from your application to be processed into your google analytics reports or property. In google analytic 4, you can create one or multiple data streams: web,  android application, and iOS application`

**To Create a web data Stream**

- Select web fom the options available (Web, Android app, iOS app)
- Enter the URL for your website and enter a stream name.
- You can choose to modify the enhance modified settings. The Enhance measurement settings allows you to keep track of important activities on your application automatically, without having to modify your implementation.
- Click create stream when your okay with the settings.

## Key things to note on the Google Analytics demo account canvas for their GA4 - Google Merch Shop data report

- `Home:` Displayed the high level report of the data you are reporting on. Here, you are shown the report you have recently viewed along with other automated insights.

---

- `Reports:` Lets you view preconfigured reports. Shows you how people find your website/app, pages they have viewed, if they have converted from just viewers to becoming account holders or subscribers, demographics and data about the decices they are using.
  - `Real time:` Gives you a report of the people who are currently on your website, and where people are viewing your website from.
  ***
  - `Life Cycle:`
    - `Acquisition:` The aquisition report deals with how people are finding the website.
      - `Overview:` Displays the total number of users and new users. It also displays the realitime card displaying conversion in the last couple of minutes per country. Displays how new users are finding the website (through: direct, cross-network, organic search,...). Here you can choose diferent date ranges and compare metrics.
      - `User Aquisition:` This shows the metric/ break-down for the first ways users find your website.
      - `Traffic Aquisitions:` This shows how users found your website to start each of their sessions. Here, each channel group (Direct, Organic search) has a metric representing how long users are staying on the page and interacting with it based on their mode on landing on the wesite. People coming through direct channel may have a higher session that users coming by referrals.
      ***
    - `Engagement:` Reports on what people are doing on your website. Here you can report on what people are doing, events that automatically collected using the enhance measurement feature and any other events you are sending to google analytics.
      - `Overview:` Reports on the top level summery with the overview report.
      - `Events:` Shhows a top level report on all the events that has been collected.
      - `Conversion:` Shows the total number of conversions based on the date range for events that have been marked for conversion.
      - `Pages and Screens:` Reports on the pages people are viewing on the website.
      - `Landing Page:`
      ***
    - `Monetization:`
      - `Overview:` Gives a high level report on ecommerce reviews, purchases and revenue (total and ad revenue).
      - `Ecommerce Purchases:` Provides more indepth report on the items people are purchasing.
      - `Purchase journey:`
      - `CheckOut Journey:`
      - `In-App purchases:`
      - `Publisher Ads:`
      - `Promotions:`
    - `Retention:`
  - `Search Console:`
  - `User:` This report shows you a top level summary of people viewing your website. It reports on the demographics of the people using your wesite: the cities they live in, their interest age, prefered language, and many more depending on the settings on their phone. To report on details like the age of your users, you would need to enable google signals.
    - `User Attributes:`
      - `Overview:`
      - `Demographic Details:` This reports on the users geograpic location by country. You can choose to display the metric by city, region ...
      - `Audiences:`
- `Tech:`
  - `Overview:` The card titled platform shows the type of data stream you are using to collect the data (Wesite, app) into your report.This reports on the systerms peple are using to access your wesite. Here you can find the operating systerms people are using to acces your application. The types of devices they using, the browsers, etc. Device categories: Desktop, laptops and mobile, and even the size of their screens. -`Tech Details:` Show the browsers people are using by default. You can select other options to view it's metric.


__If you have admin access to the account, you would see library. There you can customers the report and menu__

---
- `Explore:`
