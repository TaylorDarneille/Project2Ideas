# Project 2 Planning

Fork & Clone this repo.

## Part 1

Review the [Project 2 requirements](https://tmdarneille.gitbook.io/seirfx/11-projects/project-2#project-feedback-evaluation) and check out some [examples](https://tmdarneille.gitbook.io/seirfx/11-projects/past-projects/project2).

--------------------------------------------------------
Project 2 Idea
##### Air Pollution App:
###### Users enter their location and are given air quality data. They can make an account to store data and write journal entires about their health. They can click on specific pollutants to learn more about them and receive recommendations for ways to lessen their environmental impact.
---------------------------------------------------------

Make a PR when you're done!

---

## Part 2

In the space below:
* either embed or link a completed ERD for your approved P2 idea
* if there are any changes/additions to your user stories, place your full set of revised user stories here
* either embed or link wireframes for every page of your app

----------------------------------------------------------
### ERD
![Image of ERD](https://i.imgur.com/weTjxR4.png)

----------------------------------------------------------
### User Stories
* When I navigate to the home page, I want to see a description of the application so I know what I am signing up for.
* When I navigate to the home page, I want to see a location to log-in or sign-up for the application using my name, e-mail, and password.
* When I log-in to my account, I want to be directed to the home page that has a location for me to enter a zip code. 
* When I enter a zip code, I want to be redirected to the display page for my entered location. I want to see basic air quality information about my location along with what the air quality parameters mean in simple terms.
* On the display page for each location, I want to be able to learn more about the air quality parameters by clicking on a link for each air quality parameter (like nitrous oxide, ozone, carbon dioxide, etc).
* On the “learn more” display page, I want to view the meaning of the air quality parameter and helpful graphs that better explain the air quality parameter as well as recommendations on how to lessen the impact of those pollutants in my community.
* On this “lean more” page, I want the ability to go back to the display page for my location.
* On the display page, I want to be able to save the location to my favorite locations so that I can access it later without having to type in the zip code again.
* On all pages, I want the header to give me the ability to click on “my favorites” page and take me to my list of favorite locations.
* In the “favorite locations” page, I want to be able to create, update, read, or delete journal entries about my personal health symptoms due to air quality in that location.


----------------------------------------------------------
### Wireframes
#### Homepage
![HomePageImage](https://i.imgur.com/eYg8BNp.png)
#### Create Account
![CreateAccount](https://i.imgur.com/uadezgl.png)
#### Log-In
![Login](https://i.imgur.com/yGoVAgc.png)
#### Search Location
![Search](https://i.imgur.com/AviyFBY.png)
#### Air Quality Display
![ShowAirQuality](https://i.imgur.com/dcwjuE6.png)
#### Pollutant-Specific Display
![ShowPollutant](https://i.imgur.com/0vMs4Gg.png)
#### My Locations
![myLocations](https://i.imgur.com/26hh50v.png)
#### My Journal Entries
![JournalEntries](https://i.imgur.com/NyeAGXI.png)

----------------------------------------------------------

### APIs
#### [Air Quality API](https://docs.breezometer.com/api-documentation/air-quality-api/v2/#current-conditions)
#### [Zip Code API](https://developers.google.com/maps/documentation/geocoding/start?utm_source=google&utm_medium=cpc&utm_campaign=FY18-Q2-global-demandgen-paidsearchonnetworkhouseads-cs-maps_contactsal_saf&utm_content=text-ad-none-none-DEV_c-CRE_315916117661-ADGP_Hybrid%20%7C%20AW%20SEM%20%7C%20SKWS%20~%20Geocoding%20API-KWID_43700039136946174-aud-599437144768%3Akwd-301485311002-userloc_9028770&utm_term=KW_geocoding%20api-ST_geocoding%20api&gclid=CjwKCAiAv4n9BRA9EiwA30WND1y_zOpCskXWSEXTAr9jKZWaHEiaEexxkygVpA-_5O7MCCYFSg4A7BoC-RAQAvD_BwE)
