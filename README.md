h1. SassRoku

This is a simple sinatra template for hosting static sites on heroku. 

Use SASS + HAML, and serve everything from heroku's cache for free!
  
  
h3. Features
* Catch-all html routes, just put your haml files inside 'views/pages/'
* Anyhting put in 'public' is served as a static file
* Cache-control headers for 24 hours caching

h3. Installation
Clone this repository and make your own changes.
'bundle install'
'rackup'

Though I recommended installing the 'shotgun' gem and runnning that instead of rackup.

Run locally with 'rackup'


