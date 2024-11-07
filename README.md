# CountryForMomentJs

CountryForMoment.js allows you to get the country code of your current location.

## Detailed description

We took the project  [Moment.js](https://momentjs.com) (with an open MIT license) as a basis. 
We copy all the code from [moment-timezone.js](https://momentjs.com/downloads/moment-timezone.js) - it allows you to get the current timezone "only".
We asked ChatGPT to generate a list of all existing timezones and country codes to which they belong. And added it to the previous code
Then we added the function of getting the country code according to the current timezone.

## How does this work ?

(Make sure the CountryForMoment.js file is "downloaded" before you run the following next code)

Code to get timezone: `var timeZone = Intl.DateTimeFormat().resolvedOptions().timeZone`

Code to get country code: `var countryCode = getCountryCodeByCurrentTimezone()`