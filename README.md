# Project 1 CRUD application

This document outlines my CRUD application. Highlighting the technologies used, my approach to the task and the full stack development process.

## Call of Duty loadout

My app is based on the call of duty franchise and the weapons loadout systems. Please find below the contents for the document.


## Contents

Resource
Brief
Technologies
Kanban Board
Database structure
Data Stack
Testing
Frontend

## Resources

Jira Board
Github
Presentation

## Brief
To create a CRUD application with the utilisation of supporting tools, methodologies and technologies that encapsulate all core modules covered during training.

I approached this project with a simple idea of recreating my own version of the call of duty loadout system. This would mean that it uses a single table database to store only the equipment a player would need. The app would allow users to;

Create an entry into the database using a drop down list allowing the users to pick from a list of guns.
Read all the entries in the table in an easy to read table.
Update an existing entry in the list of loadouts.
Delete any entry in the database.

I drew inspiration for the style of the app from the call of duty franchise, with slick dark colours in mind and a minimalist approach.

## Technologies

Full stack applications require many different technologies. Find below the technologies i used; 

Project management
Jira
Github 
Database
SQL
Backend
Java
Spring
Front end
Html
Css
Javascript
Testing
Mockito
mockMVC
selenium	

## Project Management

I used both jira and github to manage my project. I used jira and created a kanban board to help me manage my time. I used an agile approach so I created user stories and epics to help plan out the application.

I used a feature branch modal in my github to help organise and keep my new entries away from the main code until the project is complete.

## Database

I used an h2 database to test the application as it can run on my local machine. Then i used an sql database for the live application so that it can run and not reset once it is closed.

## Backend

Java i used java in conjunction with spring to create the back end of this application with spring being a java framework that makes it easier to communicate to the database.

## Frontend

I used a combination of html, css and javascript to build my front end and using bootstrap to help with the styling.

## Testing

I used mockito and mock MVC to test my back end. Mocktio tested whether or not that the back end would do CRUD functionality for example that it would create an entry to the database. Mock MVC would test that it would communicate the a http request to the database and create the correct entry.

Selenium would test the front end. This simulated a users experience and would test the functionality of the site.

## Kanban Board 

I used a kanban board in jira to manage my project. I used an agile scrum method.

I used user stories to outline the tasks I needed to complete and put story points to each task to ensure that I spent the correct amount of time on each task.

## Database structure

Below is a Enhanced entity-relationship diagram (EER) of my table in the database. My id is a primary key which uses an auto increment so that it will addaept with what ever the user puts in.

## Data stack

## Database

I use an sql database to hold all my data. Because its a persistent database meaning that it will retain the information after the app is closed.

## Back end

I used java to power my back end and also used spring frame work. Meaning it could easily communicate with the front end and a the database.

## Front end

It uses html, css and javascript to ensure that the site is easy to use and can communicate with the back end to give the user a easy experience. 

## Testing

I ran three kinds of tests a mockito, mockMVC and a selenium test. The image below shows my mockito test. This creates a h2 database to test if the back end can put the info into the database.

















## Front end

Below is a screen shot of my front end as you can see its a single table with a fixed navbar with create button in. I used bootstrap to help in the styling.





















I used modals to help the user experience to ensure it was an easy to use experinance


##Future improvements

If i was to improve this project i would widen the functionality meaning the user could pick attachments for their weapons. This would need a second table in the database.

I would also create more pages for the user to learn about what is the best loadout for them.

