# [Story](http://avijeet.me/)

This is a simple static page is using Ruby on Rails to display three titles and minimal contact information on the bottom of the page.

Three categories:
	
	What I Do
	What I've Done
	What I Want To Do

This page uses [Sinatra](http://sinatrarb.com/), [Heroku](http://heroku.com), and [Compass](http://compass-style.org) for rails, hosting and stylesheets. 

##Installation

Have every gem to run this program by following commands, followed by running the server:

	sudo rake gems:install
	rake server

If you have a problem running the server, make sure you have the latest version of ruby:

	brew install ruby

To push to heroku, make sure git has been initialized in your repository, and make sure you make a heroku site"

	heroku create
	git push heroku master

That should put your site online! Enjoy.
