# airtrafictest
Test aplication regarding airtrafic

App is showing all the airplanes that are flying over current location of user. 

As user opens app, he is asked about usage of geolocation. After he accepts, it shows up the listing
from ADS-B Exchange API (https://www.adsbexchange.com/data/). 

Each listing contain:
• Altitude
• Flight code number

When listing item is clicked, page is shown with following details:
• Airplane Manufacturer and model
• Destination and Flight Origin airport

ADS-B Exchange has CORS security which is taken care of in app.

If the user didn’t allow usage of geolocation, there is an error alert that it is necessary to allow it to use the app.
