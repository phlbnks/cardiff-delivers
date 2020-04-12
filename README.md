# Support My Local

This project is a fork of [Cardiff Delivers](https://github.com/matpassmore/cardiff-delivers) by [Matthew Passmore](https://matthewpassmore.co.uk/)

## Getting Started

* Clone
* `npm install`
* `ELEVENTY_ENV=prod npx @11ty/eleventy --serve`

## Customising

### Creating a new data source

 * Create a spreadsheet in Google Docs with the columns `name, tags, description, village, collection, delivery, contact, address, latitude, longitude`
 * 'Publish to the web' the spreadsheet as 'Entire Document' in format 'Web page'.
 * Take the document ID from the **spreadsheet** URL (where you go to edit it, not the published doc URL) - it's the long string that comes after `https://docs.google.com/spreadsheets/d/`
 * Insert the document ID into the `sheetID` variable in `/src/_data/prod/sheet.js`

### Templates / content

Currently there isn't seperation between key variables like destination URL and the templates. Most importantly you need to edit `src/_includes/layouts/base.njk`.

## Plans / todo / pipe dreams

* [ ] Delivery filter
* [ ] Distance from me / point filtering
