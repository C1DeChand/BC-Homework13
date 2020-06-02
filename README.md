# What-a-Burger express handlebars demo
## By: C1DeChand - ![GitHub followers](https://img.shields.io/github/followers/C1DeChand?label=Follow&style=social)


# Table of Contents:
## [Description](#description)
## [Links](#links)
## [Installation](#installation)
## [Usage](#usage)
## [License](#license)
## [Tests](#tests)
## [FAQs](#faqs)
## [Contact](#contact)

## Description: 
An annoyingly complex demo of express handlebars functionality. It was made with nodeJS, MySQL, Express, and Express Handlebars. It has been hosted on Heroku and the repository is available on GitHub (links included below). The application allows you to take input and create database entries which are then dynamically added to the applications lists. It creates entries, updates entries, and selects all entries from the database table being used.

## Links:
https://github.com/C1DeChand/BC-Homework13
https://shrouded-caverns-38372.herokuapp.com/

## Installation:

For local install:
You must download the application from the above GitHub link. Once downloaded, you must open the file directory where the server.js file resides and open a CLI window. Run "npm i" in the CLI window to install the dependencies. You will also need to have MySQL Workbench installed in order to create the database you will need for the application. Once Workbench is installed, use the copy and paste the schema.sql code into your localhost and run it.

Finally, you will need to update the ".env.sample" file with your MySQL password and change the file name to ".env".

After all dependencies have been installed, simply run "node server.js" to use the application.

## Usage:

To use the demo, either use it with the deployed Heroku application link, or use your newly installed local version.

For Local version, you may wish to use the seeds.sql file to add starter entries into the database.

To begin using the demo. Type in the name of any burger you enjoy and hit the add button. This will add your new entry to the database and it will appear in the list of burgers you haven't devoured. To devour the burger, hit the "Devour it!" button. This will update the entry and move it to the devoured list. You may also wish to throw it up and transfer it back to the yet to be devoured list. Beyond this, there's not really anything else to do. Demo complete!

## License:
N/A

## Tests:
N/A

## FAQs:
Q. Will you update this if something breaks?
A. Uhhh....No.

## Contact:
N/A