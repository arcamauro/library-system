# BookHaven

Library Management System, where you can borrow books, add them to your wishlist and leave reviews, all of this through an API.
The librarian can also do book returns.

To run the project you need to run both the backend and the frontend, so you have to open two terminals.

To run the backend use Python 3.11.5 and install the requirements:  
- pip install -r requirements.txt  
- Inside library_management/ run: py manage.py runserver 'port' 

We recommend to use port 8000 or 8080 (by default django uses 8000)  

To run the frontend first you have to install node.js if you don't have it:
- https://nodejs.org/en/download/

Then you have to install the dependencies:
- npm install

And then inside library_management/library_frontend/ run:
- npm start

Use localhost:3000(which is the default port) to access the frontend.

> Made by Davide Scaccia, Danilo Spera, Giovanni Romano, Arcangelo Mauro
> This specific application is made by Arcangelo Mauro
