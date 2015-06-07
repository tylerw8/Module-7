# Module-7
This is the repository for the final project for the University of Washington's Javascript Certificate course Spring Quarter, that was taught by James Donaldson.  It is an app that is meant to let the user search a set of food trucks on a variety of characteristics such as type of food they serve and what their schedule is.

For this assignment, I set up a class project repository at:

Tyler Waite's Module 7 repository:
https://github.com/tylerw8/Module-7

Then I forked the repository at:
https://github.com/JSCRIPT300-Spring2015/Module_7

I updated the README.md with a link to my project repository (see above), then I initiated a pull request. I also updated the README.md file to explaining what my project is and any necessary documentation for the repository. 

I organized the files according to recommended structure: [project_structure](https://github.com/JSCRIPT300-Spring2015/project_structure) 

I added a LICENSE file for the project using the MIT license that has been used for all of the class assignments.

I added and updated the package.json - this should have both a dependencies section for application dependencies

I set up my project repository (as a separate repository - not the fork of this assignment repository). 

I added to it the following:
In the root of your project I provided the following files:
- .gitignore file the prevents any node modules from being part of your github repository

- Gruntfile.js that defines a jshint task and makes it the default task. When it runs, it lints all of the .js files in your entire project, including the Gruntfile itself.

--an Express server that serves up the following endpoints:

__GET__ /trucks

__GET__ /trucks/:id

and a devDependencies section for grunt, grunt-contrib-jshint, and any additional plugins you wish to use later (we will briefly cover using minification and concatenation for the production versions of your js and css assets.)

In an app directory I provided the following files:

- app.js - this is the main application file that instantiates the application, connects to mongodb, requires and uses any necessary middleware. I leveraged the work I already did in previous assignments for this.

Inside the app directory there is a models directory and a routes directory. Inside of each, respectively, include the following files:

- truckModel.js - this defines the same foodTruckSchema as the Module_5 assignment, and exports the Truck model. 

- truckRoutes.js - this defines the __GET__ /trucks and __GET__ /trucks/:id routes. 

Inside the public directory, provide the following file:

index.html - this is the main file served up for visits to your root url. This file should include jquery.js, underscore.js, backbone.js, and your main.js - the main entry-point for your client-side application. This file doesn't need any implementation inside it yet, but it should be present inside the js directory.

Your index.html file can either link to CDN versions of the 3rd party libraries mentioned, or you can put copies of them inside the js/libs directory and point your script elements at those versions instead.

Inside the public directory there is a js directory, a css directory, an img directory, and a libs directory. 

Inside the js directory there is a models directory, a collections directory, a views directory, a templates directory, and a routers directory.


This assignment is due by Saturday, May 30th by 7pm. Once grading has been completed, a :+1: comment will be added to the pull request and the pull request will be closed.