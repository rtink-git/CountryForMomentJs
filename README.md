# CountryForMomentJs

CountryForMoment.js allows you to get the country code of your current location based on your device system data





## How does this work ?

(Make sure the CountryForMoment.js file is "downloaded" before you run the following next code)

Code to get timezone: `const timeZone = Intl.DateTimeFormat().resolvedOptions().timeZone;`

Code to get country code: `const countryCode = new TimeZoneToCountry().GetCountryCode();`





### Upates

- Used a Map instead of an array: Lookup time is O(1) with Map compared to O(n) with array.find(). More efficient for frequent lookups
- Removed duplicate entries:
- The code became cleaner and smaller