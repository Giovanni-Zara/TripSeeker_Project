# TripSeeker_Project

# Overview
This project is a comprehensive web application built for a university course on web languages and technologies. The application leverages HTML, Bootstrap, PHP, JavaScript, jQuery, CSS, and AJAX to create an interactive platform for users to manage and participate in trips.

# Technologies Used
HTML
Bootstrap
PHP
JavaScript
jQuery
CSS
AJAX

# Project Structure and Description
Root Files
database.sql: Contains the code for creating the database tables.
index.html: The homepage for users who are not logged in. Includes a carousel, search bar, owl carousel, site purpose information, and footer.
index.php: The main page accessible only to logged-in users. It includes the same elements as index.html, plus a popup for creating trips (using jQuery and AJAX) and a button to access the profile.
login.php: Contains the code for user login.
logout.php: Contains the code for user logout.
# Folders and Their Contents
* CONTACT US
contact.html: Includes a form for submitting questions and a function to check the length of form fields.
contact.js: JavaScript and AJAX for asynchronous form submission.
send-email.php: Saves the question's content to the database.

* CREA_VIAGGIO
nuovo_viaggio.php: Inserts a new trip into the database.

* FAQ
faq.php: Contains frequently asked questions.
faq.js: JavaScript for toggling FAQ sections.
faq.css: Styles for the FAQ page, question boxes, and popups.

* FOTO PROFILO
Contains user profile photos (useless without the database).

* I_TUOI_VIAGGI
dismiss.php: Removes a user's participation in a trip from the database.
tuoi_viaggi.css: Styles for the "Your Trips" page and trip divs.
user_trip.php: Displays the trips organized by the user and those they are participating in.

* IMG
Contains site images (carousels, logos, backgrounds, etc.).

* LISTA_VIAGGI
dismiss.php: Deletes a trip from the database for a specific user.
index.php: The main page showing all available trips, with filtering, participation, renouncement, and contact buttons.
join.php: Manages user participation in trips, updating the participation table.
lista_viaggi.css: Styles for the trip list page and trip divs.
login_from_lista_viaggi.php: Handles login from the trip list page using a modal popup.
trending_trip.php: Manages the trending trips feature, incrementing a counter based on user clicks and allowing trips to be sorted by this value.

* PHPMAILER
PHPMAILER library: Manages email server for sending reset tokens.
password_dimenticata.php: Form for entering an email to receive the reset token.
crea_token.php: Creates and sends the reset token to the provided email.
inserimento_token.php: Form for entering the received token.
cambio_password.php: Form for entering a new password, with token validation.
salva_password_db.php: Saves the new password to the database if validation is successful.
template_pagine.php: Contains the template for the pages in this folder.

* Other_User
Altro_Utente.php: Displays another user's profile page, including profile photo, personal information/interests, the last two trips with TripSeeker, and received reviews (using jQuery and AJAX).
Altro_Utente.css: Styles for the Altro_Utente.php page.
recensioni.php: Code for submitting a review to the database.
login_from_altro_utente.php: Allows login so a user can leave reviews on the Altro_Utente.php page.

* Sign up
index.php: Registration form for the site.
signup.css: Styles for the registration page.
signup.js: JavaScript/jQuery code to validate form fields.
registrazione.php: Handles inserting user information into the database.

* Termini e Condizioni
termini_condizioni.php: Contains the site's terms and conditions.
termini_condizioni.css: Styles for the terms and conditions page.

* User
delete_interessi.php: Allows deletion of user interests from the database.
index.php: The main user page, containing the page template and code for submitting personal information and profile picture.
insert_interessi.php: Allows insertion of user interests into the database.
remove_pro_pic.php: Connects to the database to remove the profile picture.
index.css: Styles for the user's main page.



This detailed structure provides a clear overview of the project's files and their functionalities, making it easier for contributors and users to navigate and understand the codebase.
