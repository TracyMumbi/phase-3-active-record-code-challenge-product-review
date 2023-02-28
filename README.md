
# Product Review(e-commerce domain)
 This is an e-commerce domain. We'll be focusing on the product reviews.
## Domain Model
We have three models: User, Review, and Product.
For our purposes, a Product has many Users, a User has many Products’ s, and a Review belongs to a User and to a Product.
Product - User is a many-to-many relationship.
<br>
The application allows creating, updating, and deleting(CRUD) objects of the three models, and performing various object relationship methods and aggregate methods.
## Entity Relationship Diagram
Here's what our Entity Relationship Diagram looks like:
<img src= "img/Screenshot from 2023-02-27 13-19-17.png">
## Topics
* Active Record Migrations
* Active Record Associations
* Class and Instance Methods
* Active Record Querying
## Built With
* Ruby Active Record
## Installation
To use this repo on your machine,follow the steps below;
### Step One
- Open a terminal / command line interface on your computer
- Clone the repo by using the following:
        git clone [https://github.com/TracyMumbi/phase-3-active-record-code-challenge-product-review]
- This will create a copy on your local machine for you.
- Change directory to the repo folder:
        cd phase-3-product_review
- Open it in ``Visual Studio Code`` OR any other code editor of your choice
        code .
### Step Two
- On the top right corner of this page there is a button labelled ``Fork``.
- Click on that button to fork the repo to your own account.
- Then follow  ``Step One`` above.
- Remember to replace your username when cloning.
        git clone https://github.com/your-username-here/phase-3-product_review.git
# Running the application
Use the following steps to run the app.
- Install required dependencies using bundle
      bundle install
- Run the application on the terminal
-  Run the application on the terminal
      ruby `file_name.rb`
- For our app, we run the following command;
      ruby run/console.rb
# Authors
This project was contributed to by:
- [Tracy Mumbi](https://github.com/TracyMumbi)


