# Depot Manager
A tool to manage depots and product within them

# Overview
This tool has been created to manage up to 4 depots and 5 product within them.
It has different functions which are: 
- Add a depot
- Remove a depot
- Add a product to a depot
- Remove one item from a depot
- Query a list of depots
- Query a list of items in a depot
- Query about a product presence in a depot
- Query a cumulative value of all products

This program is written in Java.

It uses console as an input and output.

It also can use txt files as an input and output, but it has to follow this template:

"DepotName" - to only create a depot without a product

"DepotName" "ProductName" "Price" "Weight" "Quantity" - to create a depot with a product inside
Program handles cases where for example if given depot with a name already exists it will add a product to it, 
or when a product exists in a depot it will just add quantity.

# What I learnt
- Basics of java developement
- Working with multiple Classes
- Arrays
- Basic optimisation
- Writing output to the text file
- Reading input from a text file
