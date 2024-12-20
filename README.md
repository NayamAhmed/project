# 
This project is a web-based application designed to manage reservations, activities, and user interactions for a campground. The system includes PHP scripts for backend functionality, a CSS stylesheet for styling, and integrated logic for handling user interactions.

Project Features
User Features:

View available activities and details.
Book and manage reservations.
Leave and manage comments.
Admin Features:

Respond to user reservations and comments.
View and manage campground data.
Styling:

Consistent design with a CSS stylesheet for navigation, layout, and footers.
File Descriptions
PHP Files
activities.php

Displays available campground activities.
Handles logic related to activity listings.
comm-resp.php

Manages admin responses to user comments.
comments.php

Handles user comments, including posting and retrieving reviews.
index.php

The homepage of the application.
Provides navigation to other sections.
reservation.php

Manages user reservations for campground stays or activities.
resv-resp.php

Admin-side functionality for handling reservation requests and responses.
yurts.php

Focused on managing yurt reservations or details.
CSS Files
style.css
Defines the visual design of the application.
Highlights:
.bg-green: Green background elements.
.nav-link: Styled navigation links.
footer: Consistent footer design.
.navbar-collapse: Center-aligned navigation bar.
Installation
Requirements
Server: Apache or Nginx with PHP support.
Database: MySQL or equivalent for storing activity, comment, and reservation data.
Browser: Any modern web browser (Chrome, Firefox, Edge).
Setup Instructions
Copy the project files to the server's root directory (e.g., htdocs or www).
Configure the database connection in the respective PHP files.
Import the required database schema and data.
Access index.php through the browser to use the application.
Usage
Users:
Navigate through activities and make reservations.
Leave comments or feedback.
Admins:
Respond to user queries and reservations.
Manage campground details and operations.
