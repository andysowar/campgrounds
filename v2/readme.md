#YelpCamp v1

* Add Landing Page
* Add Campgrounds Page that lists all campgrounds

Each campground has:
* Name
* Image

#Layout and basic styling
* Create header and footer paritals
* Add Bootstrap

#Creating New Campgrounds
* Setup new campground POST route
* Add body-parser
* Setup route to show form 
* Add basic unstyled form

#Add Mongoose
* Install and configure Mongoose
* Setup campground model
* Use campground model inside of our routes

#Show Page
* Review the RESTful routes we've seen so far
* Add description to our campground model
* Show db.collection.drop()
* Add a show route/template

RESTful routes
* index | /campgrounds | GET | Displays list of campgrounds
* new   | /campgrounds/new | GET | Displays form to make a new campground
* create| /campgrounds | POST| Add a new campground to the db
* show  | /campgrounds/:id | GET | Shows more info about a campground    