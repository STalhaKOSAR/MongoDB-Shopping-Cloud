## E-Bay Clone

E-Bay Clone is a basic CRUD webpages using MongoDB for database and Backend As A Service(BaaS).

## Installation

Make sure that you have active internet connection first and use Google Chrome(preferable). Then

```bash
open index.html
```
or go to url:
```bash
https://stitch-statichosting-prod.s3.amazonaws.com/5cb79b5982b2fb94b56d7477/index.html
```

## Usage

On index.html, you can Add User, Delete User or Login as a User. You can Search any product. And you can see the list of users registered.  
On login.html, you can Deposit or Withdraw Money, Search any product and Add a product to your Store(On Sale or Drop). You can also see your account data and product list.  
On product.html, you can Buy products and Rate the Seller.

## Design Choices
-Project is using Backend as a Service in MongoDB. In data bases some objects consist arrays but displaying numbers(e.g Seller's rates given by Buyers stored in arrays but shown in login.html as integer).  
-There are 3 html file and redirections(login or search) are done by URL.  
-Any empty search will result in all products.  
-When a user try to add a product with same name, it just updates with new photo, status, quantity and price.(i.e product names are unique in user's store)
-To add url of image just copy url and paste it to input box.  
-All Usernames are unique, so when you try to add non-unique username, there will be alerts(same apply for all unique fields).  
-Rating are done after clicking Buy button, the prompt will be opened and you Rate Seller between 0 and 5.  
-You can use Go to buttons to swap between pages.
-All input fields must not contain white space  
-And some cool css stuffs added to beautify.

## License
[&copy; Copyright 2019 Sinan Talha KOSAR](https://www.linkedin.com/in/STalhaKosar/)
