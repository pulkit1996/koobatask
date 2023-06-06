Kooba Backend Challenge 2022
Introduction
In this document, I will walk through the steps to complete the Kooba Backend Challenge 2022. The challenge involves integrating a static HTML page into a Content Management System (CMS) and implementing additional functionalities. I will estimate the time required, choose Craft CMS and MySQL as the technology stack, outline the steps involved, and provide a detailed execution plan.

Estimation
Based on the given time limit of 3-4 hours, I estimated the time required for each task and prioritized the critical elements. This helped me ensure that I deliver a functional solution within the given timeframe.

Estimation:

CMS Integration: 1 hours
Card Listing: 1 hour
CRUD Functionality: 2 hours
Bonus Functionalities:
Remind Me: 1 hour
Total estimated time: 5 hours

Technology Stack
For this challenge, I chose Craft CMS as the Content Management System and MySQL as the database.

Reasons for choosing Craft CMS:
Craft CMS is a flexible and robust CMS that allows for easy content management and customization.
It provides a user-friendly interface for editors to create, update, and delete shows and their data.
Craft CMS has a strong community and extensive documentation, which will aid in the development process.
Reasons for choosing MySQL:
MySQL is a widely used and reliable open-source relational database management system.
It integrates seamlessly with Craft CMS and provides efficient data storage and retrieval capabilities.
MySQL is well-documented and supported, making it suitable for this project.
Steps in Craft CMS Integration

Installation and Setup:
Installed Craft CMS.
Configured the MySQL database connection.
Set up the necessary directory structure and permissions.
Create Sections and Entry Types
Defined the necessary sections.
Created entry types to define the fields and structure for each section.
Create Fields
Identified the required data fields for each show, based on the HTML build.
Created fields in Craft CMS to store the show data, such as title, date, description, image, etc.
Integrated the static HTML code into the Craft CMS template, replacing the relevant sections with dynamic content.
Limited the number of cards to a maximum of 6 per section.
Displayed the data in the template, following the responsive design of the HTML build.
Set up the necessary permissions and user roles for editors.
Implement the Create, Update, and Delete functionality for shows and their data.
Bonus Functionalities: 
Remind Me: Implement the functionality to generate an ICS file on clicking the "Remind Me" button.
