# Angular 2 assignment

## Note
This is an assignment to create a very basic Angular 2 app. The template that is used is a derivation of the [angular-cli](https://github.com/angular/angular-cli) start project 

## Prerequisites
The prerequisites are the same as the [angular-cli](https://github.com/angular/angular-cli) project.  

# Description of the assignment

* Start a new angular 2 project (*)

* The data available on following url must be visualized
  [http://www.aarixa.be/assignment_jobs.php](http://www.aarixa.be/assignment_jobs.php)
  
* All the pages must have the aariXa logo

![alt text](http://www.aarixa.be/wp-content/uploads/2016/05/aariXa.png "Logo aariXa")


* Make it possible to filter on the visualized data from the website, you can have a look on our jobpage to see an [example](http://www.aarixa.be/jobs/)
  * It should be possible to filter at least at frontEnd, Java and dotNet
  * Nice to have is search function that is searching on all the JSON content returned form the url

For visualisation it's allowed to use CSS frameworks like [ng-bootstrap](https://github.com/ng-bootstrap/ng-bootstrap) , [angular2-materialize](https://www.npmjs.com/package/angular2-materialize),.. or others that support angular.


## (*) How to get started 
This a possible way to start your project, you can start with this project as a template but you can also use your own angularJS 2 quickstart, include the steps that you followed in the Readme.md in your submission

* Get this project on your local machine using command
``` dos
git clone git://github.com/aariXa/ng-be.git
```

* Go to the retrieved directory and run the the package installer
``` dos
cd ng-be
npm install
```
During the npm install you can see errors or warnings, this is normal and this is the same behaviour in the current young angular-cli beta project.


* When you use visual studio code as IDE for development execute
``` dos
code .
```

* Start your developemt server from command line
``` dos
npm start
```

* You can also use the intergrated terminal window in visual studio code to start your development server ( View -> Integrated Terminal)
* When you want to debug in visual studio code you can check the extention [Debugger for Chrome](https://code.visualstudio.com/blogs/2016/02/23/introducing-chrome-debugger-for-vs-code)

* Open your Chrome Browser and go to following url for opening your start page 
``` dos
http://localhost:4200
```

* To create a deployable version execute following command 
``` dos
ng build
```
This command generates a dist folder that contains the output of your project. This output you can deploy on your webserver.
 
# Submission of the assignment
Follow the instructions on the assignment form for submission of the assignment.

The submission must also contain the steps to start the development and creation of the build for deployment if it's different than the steps mentioned above.

Good Luck

The aariXa Dev Team
