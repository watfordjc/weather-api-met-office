# weather-api-met-office
## Test Code
This repository is for test code to use the Met Office Global spot data APIs, and show some sample data* returned from the API (Met Office doesn't provide examples).

I felt the only logical response to DarkSky taking Apple's money to kill off their API and Android app was to use a partially taxpayer funded meteorological organisation's planet Earth weather data API that will likely be better than an API that only supports the UK and USA.

As I used DarkSky to, literally, find out if the sky is so darkened by clouds that the hallway light should be turned on automatically to minimise the risk of trips/falls on the staircase, I am hoping the Met Office's API provides equivalent data for cloud cover and precipitation.

## API Keys
The process for getting API keys is detailed at the Met Office's [Getting Started](https://metoffice.apiconnect.ibmcloud.com/metoffice/production/start) page.

1. [Explore the APIs](https://metoffice.apiconnect.ibmcloud.com/metoffice/production/api) to find the one that suits your needs.
2. Create an account - click the button on the Getting Started page.
3. After registering and logging in, go to the Apps section and click Create new App.
    * After filling in the Register Application form, you will be given the **client ID** (unique app ID) and **client secret** (API key) for your application.
4. Subscribe to the API you chose in step 1.

## Licensing
This repository contains examples of API responses* as well as code examples for accessing the API.
* The example code is licensed per the license applicable to the repository.
* The example API responses* are separately licensed, and per Term 1.11 of the 30th April 2019 version of the Met Office Weather DataHub Terms and Conditions the following dislaimer is required:
  * **Powered by Met Office Data**

## Sample API Responses
All sample responses* for England will be obtained using the generic location of the Royal Greenwich Observatory (51.4778 degrees North, 0.0014 degrees West) and the time the Greenwich Time Ball drops daily (13:00 Europe/London).

\* The plan for including some sample API responses is dependent on such usage of the data being consistent with the API Terms.
