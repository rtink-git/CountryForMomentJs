# CountryForMomentJs

CountryForMoment.js allows you to get the country code of your current location.

## How does this work ?

We use [Moment.js](https://momentjs.com) project (with an open MIT license) as a basis. 
We take file [moment-timezone.js](https://momentjs.com/downloads/moment-timezone.js) - it allows you to get the current timezone only.

Code to get timezone: `var timeZone = Intl.DateTimeFormat().resolvedOptions().timeZone`

We asked ChatGPT to generate a list of all existing timezones and country codes to which they belong
And add code to get country code by current tiezone:

Code to get country code: `var countryCode = getCountryCodeByCurrentTimezone()`