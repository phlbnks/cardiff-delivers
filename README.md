# Support My Local

This project is a fork of [Cardiff Delivers](https://github.com/matpassmore/cardiff-delivers) by [Matthew Passmore](https://matthewpassmore.co.uk/)

## Getting Started

* Clone
* `npm install`
* `ELEVENTY_ENV=prod npx @11ty/eleventy --serve`

## Customising

### Updating business list

 * Listing is rendered from JSON in `src/_data/prod/data.json`

### Templates / content

Currently there isn't seperation between key variables like destination URL and the templates. Most importantly you need to edit `src/_includes/layouts/base.njk`.

## Plans / todo / pipe dreams

* [ ] Delivery filter
* [ ] Distance from me / point filtering
