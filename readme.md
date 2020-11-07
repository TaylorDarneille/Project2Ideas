# Project 2 Planning

* Fork & Clone this repo.

Review the [Project 2 requirements](https://tmdarneille.gitbook.io/seirfx/11-projects/project-2#project-feedback-evaluation) and check out some [examples](https://tmdarneille.gitbook.io/seirfx/11-projects/past-projects/project2).

## Idea: 
User is able to search hikes in WA state based on season, that info will come from different altitudes of hikes. (For fall specifically, I wanted to try and determine hikes by region where certain trees grow so trees that have a tendency to change color can be placed in the fall section). User will have their own page with full CRUD functionality to save hikes and add comments/photos. (Would like to implement an editable map that marks a place they've been).
* Models: user, hikes, seasons, comments 


In the space below:
* either embed or link a completed ERD for your P2 idea
* include [user stories](https://revelry.co/user-stories-that-dont-suck/)
* either embed or link wireframes for every page of your app
* include links to any APIs or other 3rd party tech you plan to use

----------------------------------------------------------
### ERD
![ERD full] (images/ERD1.png)
![ERD for models] (images/ERD2.png)
----------------------------------------------------------
### User Stories
I moved to WA state beginning in September for the sole purpose of escaping the East Coast cold and being close to top tier nature. Now that I'm here, I realized that it is really cold, even snowy, on a lot of these hikes I go on, which was unexpected to me, it's October. 
I'm creating this app for people like me who might not be in touch with weather when it comes to mountains. I want this app to direct users to chosing hikes depending on which is the best season to visit; which is directly correlated to the altitude of a given hike. The app should allow users to bookmark hikes they'd like to do and also let them post comments/stories/hopefully images too, that is related to a hike. 
----------------------------------------------------------
### Wireframes

----------------------------------------------------------
### APIs and other outside tech

* Data scrape from: 
    * https://www.wta.org/go-outside/hikes
    * https://www.gardenguides.com/12428538-dawn-redwood-lumber-uses.html
* APIs: 
    * https://rapidapi.com/trailapi/api/trailapi?endpoint=53aa3bd0e4b008bb2ef85a53
    * https://docs.trefle.io/

----------------------------------------------------------

Make a PR when you're done and title it with your pod person's name and yours (eg. "Edward<-->Taylor")!


# Project 2 Requirements: 
* sign up/login functionality 
* at least 2 models 
    * user model and then 2 more 
* one third-party API
* CRUD/RESTful routing
    * get, post, put, delete 
* use ORM 
    * sequelize/postgres data tables
* readme file
    * explain how to use your app 
        * API keys/ environment variables 

