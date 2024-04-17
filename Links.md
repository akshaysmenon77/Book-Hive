## GET
localhost:1622/bookhive/books
localhost:1622/bookhive/books/bookname/harry potter
localhost:1622/bookhive/books/bookid/1

## Post
localhost:1622/bookhive/books

## Delete
localhost:1622/bookhive/books/removebook/3

## Updated
localhost:1622/bookhive/books/updatebooks/1

{
    "bookid": 2,
    "bookname": "Harry Potter1",
    "bookauthor": "J R Rowling",
    "bookprice": 300.0
}

## ============================ Order ============================

## GET
localhost:1622/bookhive/orders
localhost:1622/bookhive/orders/orderbyid/3
localhost:1622/bookhive/orders/ordername/akshay

## POST
localhost:1622/bookhive/orders/placeorder/1

{
    "orderby": "Akshy",
    "productQnt":30
}

## DELET
localhost:1622/bookhive/orders/deleteorder/5



## ============================ Authentication ============================

## Add new user 

localhost:1622/auth/addNewUser

For Admin: 

{
  "name": "Akshay1",
  "password": "password1",
  "email":  "akshay@mail.com",
  "roles":  "ROLE_ADMIN"
}

For User

{
  "name": "Akshay",
  "password": "password",
  "email":  "akshay@mail.com",
  "roles":  "ROLE_USER"
}

## Generate Token

localhost:1622/auth/generateToken
{
  "username": "Akshay1",
  "password": "password1"
}

