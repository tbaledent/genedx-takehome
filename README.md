# GeneDx Technical Take-home

## Overview

The goal for this take-home is to create an API-based book inventory tracking system that can handle adding new books to your inventory, selling of books from your existing inventory, and cataloging your current inventory and sales.  Within this repository is a csv file containing data for a baseline book inventory, which should be loaded using whatever technique you desire upon spinning up the application.


## Requirements

The overall purpose of this take-home is to see your methodology and approach to this project, however there are base requirements that should be met.
-	You must expose a web API (RESTful or other) to handle the creation and selling of books in your inventory.  Please *do not* include a frontend for this application, simply a backend will suffice. Note: A sale can only be valid if you have the book in your inventory.
-	Must include endpoints for the following:
    - Creation of books
    - Sale of books
    - Retrieval of book info by author, id, and book title
    - Total dollar amount of sales
    - Average number of pages for books that have been sold
-	This take-home can be written in whatever language/framework you are most comfortable with, although Python is preferred.
-	Provide a README that includes the following:
    - How to run the project
    - Why you chose the approach you did and what you would do differently given more time
    - Document your API endpoints
-	The project should be dockerized and executable with a simple command (shell, GNUMake, etc).

## Optional

The following can be included as optional bonuses:
-	Include an operational database for your application 
-	Include an endpoint for refunds of books that have been sold, with refunded books being added back into your available inventory.

## Models

At a minimum, your project should contain a Books model with at least the following fields, but you are welcome to add any other fields or models as you see fit. 

```
Books
----------
id: number
title: string
authors: string
pages: number
price: number
```


## Submission

To submit this take-home, upload the project to your GitHub account as a private repository and add the GitHub handles provided to you by the recruiter as collaborators.
Note: Please *do not* fork this repo, simply git clone on your local machine.
