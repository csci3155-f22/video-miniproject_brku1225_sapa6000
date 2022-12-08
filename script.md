STEP 1: Give Demonstration of the app
	
	Show how we can access it locally
	
	Show the user interface for each of the pages

	Show the functionallity of the pages

		Adding things

		Marking things as done

STEP 2: Go through the code base

	Package.json

		How to run the app locally

		dependencies/npm packages

	Index.html

		Show basic structure, Not much here

	date.js

		Exporting two modules to get the date and the day of the week

		This allows us to call these functions in our app to display this information

	app.js
		Setting up express, parser and date variables using require (npm modules and exports)

		Setting up app to use for routing by calling our express function which is a variable

		Telling our app to use body parser for parsing http data

		telling our app to use the public directory for css

		setting up pre-determined lists to see

		setting up the http get route for our home list route

			Gets the day by using our date function and then renders the day and the pre-determined list using ejs syntax

		setting up the http post route for our home page
		
			getting the item that the user entered and storing it in a variable
			
			checking what the list name is and adding the item to the appropriate list and then redirecting to that route

		setting up the http get route for our work list route
			
			gets the list title and then displays the to-do for that specific list

		setting up a listening server with a port so we can access the app

	views
	
		Directory for all our .ejs files

		Needs to be in views directory to work with Express.Js

		.ejs files are used so the content of the html can be updated dynamically

		use footer, header and list ejs files for modularity

			we can use these files anywhere so we dont have to keep writing code for different pages

	public
		
		directory for css

		needs to be called public for Express.Js to work

		contains the css for the app

STEP 3: Relationship to Class

	Functions as Values

	Call Back/Higher Order Functions
