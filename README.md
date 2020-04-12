# Deeelish

Deeelish is a web application, designed by me, Carly Clark, to satisfy the requirements of the "Data Centric Development" milestone project on the Code Institute Full-Stack Software Development course.

It is intended to be an online community resource primarily for searching and sharing recipes, though users can also view cooking tips and techniques. 


## Demo
A live demo can be found [here](https://deeelish.herokuapp.com/).


## UX

### User stories

As the cook of the household, I am looking for recipe inspiration for our next family dinner and would like to be able to quickly search a collection of recipes and view the recipe details. 

As a cooking novice, I would like access to recipes with step by step preparation guidance, as well as some handy tips and techniques to improve my skills. 

As someone with food intolerances, I would like to be able to filter my recipe search by specifc dietry requirements as well as my preference for the type of meal course and cuisine.

As someone with a passion for homecooking, I would like to be able to add my tried and tested recipes to the collection so they can be shared with a community of like-minded people. I would also like to be able to edit and delete my recipes if I spot an error or its no longer suitable. 


### Strategy
My goal in the design was to make it as easy as possible to access information, whether this be recipes, catergories, tips or techniques, while striving to display the information in a minimalist and user-friendly format.

### Scope
I wanted users to feel welcome, to understand the purpose of the site and to be provided with some inspiration to get them cooking. I would like users to be able to view, edit and delete the categories and recipes in the collection as well as add their own categories and recipes. Additionally I would like users to be able to access our handy tips and techniques to improve their cooking skills. 

### Structure
My hope was to present information to the users in a logical format that provides easy access to the information they require. With this in mind, users are welcomed to the site landing page with a brief overview of the purpose and some featured 'seasonal' recipe imagery to inspire them. From there, users can easily navigate 5 other areas of the site; Discover Recipes, Add Recipe, Browse Categories, Add Category and Tips & Techniques. On the Discover Recipe and Browse Categories pages, users can choose to expend a particular result to view more detail or access options including view, edit and delete. Hiding these options until required is is intended to promote a minimalist design. 

### Skeleton
The basic wireframes for this site can be found [here](https://github.com/Carly07/deeelish/static/wireframes/)


### Surface
The greyscale and yellow color scheme was chosen to create a bright, modern feel. Colourful images of fresh produce, cooked meals and home bakes are used to appeal to the users senses.


## Features

### Existing Features

#### Navbar
A fixed Navbar with dropdown menus has been implemented on larger devices whilst a side nav is enabled for mobile use. It was felt that this would enhance user experience by ensuring quick and easy navigation whilst still promoting a minimalist design. 

#### Seasonal Recipes Section
The featured 'Seasonal' recipe imagery is displayed using a touch enabled carousel offering the users recipe inspiration. Users can click on the image to be redirected to the relevant recipe. 

#### Filter Function
A form at the top of the Discover Recipes page offers users three dropdown menus displaying categories to select from in order to filter their recipe results. The Meals & Courses Category and the Cuisines Category have been populated dynamically so they remain consistant with any changes that have been made. 

#### Discover Recipe and Browse Category Pages
The Discover Recipe and Browse Category results are presented in an accordion displaying only basic details and hiding additional information that's not immediately relevant. Where users are interested in a particular recipe or category, they can expand the result to reveal more information and or other options available to them such as View, Edit and Delete. 

#### Adding and Editing a Recipe or Category
Materialzie Forms incoroparting input fields, text-areas, select menus and switches, have been used to receive user inputted data when adding or editing a recipe or category. The forms have sensible defaults for fields which are required or optional. 

#### Flash Messages
Flash messages have been implemented to provide feedback to the user when adding, editing or deleting from the database. Users will recive confirmation of their action or else be notified that either the category already exists when trying to add a new entry or that they cannot delete a category that is currently in use. 

#### Tips Section
Cards with a hoverable class are used to navigate users to three handy tips. If users are interested in a particular tip, they can click on the card title to open a modal displaying the information to the user. 

#### Footer
Materialize Footer has been used to provide the user with social medial links and copyright information. 


### Features Left to Implement
In the future, I would like to add user registration and authentication to the site. 


## Technologies
All the languages, frameworks, libraries, and tools used to construct this project are listed below. I have also provided a link to each official site and a brief overview of its usage.

### Languages

•	<a target="_blank" href="https://en.wikipedia.org/wiki/HTML5">HTML5</a> – Markup language used to write customised frontend content for the application.

•	<a target="_blank" href="https://en.wikipedia.org/wiki/Cascading_Style_Sheets">CSS3</a> – Used to customise the style of the web application. 

•	<a target="_blank" href="https://www.python.org/">Python</a> High-level programming language used to build back-end functionality.


### Framework

•	<a target="_blank" href="http://archives.materializecss.com/0.100.2/">Materialize CSS v.0.100.2</a> - A framework used to create the responsive grid system and various components within the site including the navbar, select menus, accordion, cards, modals and carousels. 

•	<a target="_blank" href="https://en.wikipedia.org/wiki/Flask_(web_framework)">Flask</a> - A python microframework used to construct and render pages within the application quickly and easily.


### Libraries

•	<a target="_blank" href="https://jquery.com/">jQuery</a> - A JavaScript library used here to simplify DOM manipulation when initializing specific Materialize components within the application e.g. carousel, modal, accordion etc.

•	<a target="_blank" href="https://fonts.google.com/">Google Fonts</a> – The font used throughout this website was obtained from Google Fonts.

•	<a target="_blank" href="https://fontawesome.com/">Font Awesome</a> - The Social Media icons used within the footer were sourced from Font Awesome.

•	<a target="_blank" href="https://material.io/resources/icons/?style=baseline">Material Icons</a> - All other icons used within the web application were sourced from Material Icons.

•	<a target="_blank" href="https://jinja.palletsprojects.com/en/2.11.x/">Jinja</a> - A templating language used to simplify the displaying of back-end data in a HTML markup format that is returned to the user via an HTTP response.

•	<a target="_blank" href="https://api.mongodb.com/python/current/api/pymongo/index.html#module-pymongo">PyMongo</a> - A driver used to access the MongoDB database from Python and make communication between the two possible.


### Tools 

•	<a target="_blank" href="https://www.gitpod.io/">GitPod</a> – This is the online Integrated Development Environment (IDE) used for the development of this project.

•	<a target="_blank" href="https://account.mongodb.com/">MongoDB</a> - A NoSQL database used for storing the user data in JSON-like documents.

•   <a target="_blank" href="https://www.google.co.uk/chrome/">Google Chrome</a> - This browser and its' developer tools were used throughout the development of the app. 

•   <a target="_blank" href="https://www.google.co.uk/chrome/">Responsinator</a> - Website used throughout the development to test responsiveness functionality on different devices. 

•	<a target="_blank" href="https://github.com/">Git</a> – A command-line tool, used for version control

•	<a target="_blank" href="https://github.com/">GitHub</a> – GitHub was used for hosting my repository

•	<a target="_blank" href="https://github.com/">Heroku</a> – A cloud platform used for deployment

•	<a target="_blank" href="https://validator.w3.org/">W3C Markup Validation Service</a> - The HTML and CSS code for this project was checked and validated by the W3C Markup Validation Service


## Information Architecture

This project utilizes the NoSQL database [MongoDB](https://account.mongodb.com/account/login).

### Data Storage Types

The types of data stored in MongoDB for this project are:

ObjectId
String
Boolean

### Collections Data Structure

The deeelish project relies on three collections:

•	[recipes](https://github.com/Carly07/deeelish/static/images/mongodb/recipescollection.png)

•	[meals_courses](https://github.com/Carly07/deeelish/static/images/mongodb/meals_coursescollection.png)

•	[cuisines](https://github.com/Carly07/deeelish/static/images/mongodb/cuisinescollection.png)

The ObjectId from the selected meals_courses and cuisines category collection are retrieved and stored as the meal_course_type and cuisine values within the recipe document in the recipes collection. This creates a relationship between the collections which means that if a particular category within either the meals_courses or cuisine collections is updated it will reflect the change in all the recipe documents associated with that category.

## Testing
### Developer tools

GitPod's live preview, google chrome developer tools and responsinator were utilised throughout the development of the project to identify and successfully address any bugs, errors or style issues affecting UX on various screen resolutions. W3C Markup and CSS Validation Services were also used to check the validity of my HTML and CSS code. NB. the W3c validator throws many errors in the HTML files to do with the Jinja templating syntax. 

### User scenarios

The newly engaged couple achieved their desired outcome of being presented with inspiration and guidance to assist them in planning their wedding. They arrive at the site and are immediately greeted to a beautiful image capturing a bride and groom as they embrace. The image does not reveal the couples faces allowing users to imagine themselves as the bride and groom. They can then read a brief overview about Tie the Knot before scrolling down to the planning and inspiration sections, where they are presented with advice, guidance and wedding theme ideas to inspire and assist. From there the engaged couple can navigate to the supplier and featured sections to find wedding suppliers who will bring their ideas to life. Finally, if the couple have any specific questions not answered within the site, they can request advice by submitting the contact form located at the bottom of the site. All the links and buttons contained within the site were manually tested on various devices to ensure functionality. 

Members of the wedding industry can achieve their goal of promoting their business / services by getting in touch using the Contact form. This sends an email with their details and enquiry to Tie the Knot. Their business / service can then be advertised within the featured section of the site. Additionally, wedding suppliers contact details and websites are displayed within an info window that opens when a user completes a google map search within the Suppliers section and clicks on a marker. 

On the Contact form all users are required to enter their name, email, subject and question. If users try to submit the form with any of the fields blank, they are presented with a message requesting they enter the required details. Similarly, if they enter an invalid email address, they receive an error message. Once the form is complete, users can click on the send button which sends an email with their enquiry and opens a model, thanking the user for their enquiry.

### Multiple browsers and devices

After the site was deployed, I tested it across four browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple devices (Samsung Galaxy J3, iPhone 7 Plus, 8, iPad 6, iPad Air, MacBook Air, HP laptop and iMac) as well as on Responsinator to ensure compatibility and responsiveness. Whilst testing, I noticed that the flip cards were not rotating correctly on Safari. Having researched the problem, I found that adding a prefix in webkit and other browsers fixed the issue. I also found that the alert modal was firing when the contact form was submit without all fields complete. The issue was fixed by manually calling the modal with javascript on submit. 


## Deployment
This application was deployed to Heroku for hosting. 

In order to achieve this, a `requirements.txt` and `Procfile` were created using the following two commands in the terminal:
`pip freeze > requirements.txt`
`echo web: python app.py > Procfile` 

A new app was created on the Heroku website by clicking the "New" button on dashboard. The app was named deeelish and the region set to Europe. Then from the deeelish app dashboard, the "Deployment method" was set to GitHub.

All code was then committed to a local Git repository using the `git add` and `git commit -m 'message'` commands. The code was then pushed to a remote [GitHub repository](https://github.com/Carly07/deeelish) using `git push -u origin master` before being deployed to Heroku using `git push heroku master`.

During development my environment variables (SECRET_KEYs, or MONGDB_URIs) were stored in a seperate file (env.py) that was not pushed to my git repository so to prevent anyone (or any bot) from accessing and misusing the sensitive information. However, as heroku uses the GitHub repository code to build the app, it wouldn't have access to the environment variables and this would likely throw errors. So, for deployment, I gave heroku a copy of the environment variables; storing them in Key Value pairs under Reveal Config Vars in the Settings tab on my app dashboard. The variables are then accessed through the os.environ.get() method. Similarly, during development, the debug attribute was set to true whilst for deployment it has been changed to false. 

To run the project locally in your own IDE, you must have Git, PIP and Python installed on your machine. You will also need to set up a MongoDB account [here](https://account.mongodb.com/account/login) and create a database called deeelish with three collections named recipes, meals_courses and cuisines. You will find example json structures for these collections in the mongodb folder. 

Once this is done, you can then simply clone my repository by pasting `git clone https://github.com/Carly07/deeelish` directly into your terminal. Next install all the required modules with the command `pip -r requirements.txt.`, create a file called `env.py` and inside this add a SECRET_KEY variable and a MONGO_URI to link to your own database. 

You should then be able to run the application with the command `python app.py`


## Credits

### Content
•	All the recipes used within this site were sourced from [BBC Good Food](https://www.bbcgoodfood.com/). 

•	The text within the Tips section was taken from [BBC Good Food](https://www.bbcgoodfood.com/).

### Media
•	The photographs used throughout this site were found on [Google Images](https://www.google.com/imghp?hl=en).

•	The videos contained within the Techniques Section were obtained from [YouTube](https://www.youtube.com/).

### Acknowledgements

Special thanks to my mentor, Antonio Rodriguez, and the tutors at Code Institute for their help and advice with this project.

**This is for educational use.** 