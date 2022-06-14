GeneDx Technical Take-home

Overview

The goal for this take-home is to create an API-based book inventory tracking system that can handle adding new books to your inventory, selling of books from your existing inventory, and cataloging your current inventory and sales.  Within this repository is a csv file containing data for a baseline book inventory, which should be loaded using whatever technique you desire upon spinning up the application.

Requirements

The overall purpose of this take-home is to see your methodology and approach to this project, however there are base requirements that should be met.
-	You must expose a web API (RESTful or other) to handle the creation and selling of books in your inventory. Note: A sale can only be valid if you have the book in your inventory.
-	Must include endpoints for the following:
o	Creation of books
o	Sale of books
o	Retrieval of book info by author, id, and book title
o	Total dollar amount of sales
o	Average number of pages for books that have been sold

Optional

The following can be included as optional bonuses:
-	Include an operational database for your application 
-	Include an endpoint for refunds of books that have been sold, with refunded books being added back into your available inventory.








Models

At a minimum, your project should contain a Books model with at least the following fields, but you are welcome to add any other fields or models as you see fit. 

Books
----------
id: number
title: string
authors: string
pages: number
price: number

Additional Requirements

-	This take-home can be written in whatever language/framework you are most comfortable with, although Python is preferred.
-	Provide a README that includes the following:
o	How to run the project
o	Why you chose the approach you did and what you would do differently given more time
o	Document your API endpoints
-	The project should be dockerized and executable with a simple command (shell, GNUMake, etc).

Submission

To submit this take-home, upload the project to your GitHub account as a public repository and provide a link to the repository when complete.
