# Name Card application 


1. node version: 14.15.4
2. npm version 6.14.10
3. install packages: `npm install`
4. run application: `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

# Requirements 
The application should have the following functionalities:
* The input (card list) should initially be empty.
* Before all values (First Name, Last Name, Phone, Address) are entered, clicking
on "Add Card" button should not do anything.
* After entering all values, clicking on "Add Card" button should add the input to
the name card list.
* After adding the input to the list, automatically clear the input values for the
next card input.
* While typing the phone number, validate the format is xxx-xxx-xxxx (x is digit).
Until the format is correct, highlight the phone input box with red outline.
* The search bar is used to search the entered card by name (both first and last
names). Fuzzy search should be applied while typing in the search bar.
* "Sort By" is a dropdown menu that allows to sort the entered cards by either
first name, last name, phone, or address. Initially, no value is selected (no
sorting is applied) and the cards should show up in the order as entered.

  
# Implementation Details
1. The card list is empty initially.
2. If any fields missed, the 'Add Card' button is disabled. ( All fields are required)
3. If any field entered and cleared, 'Required' error message pops up and input box red bordered.
4. If phone number isn't valid when entering in xxx-xxx-xxxx format, error messages pops and input box red bordered.
5. After entering the card, card will show up at the end of the list.
6. Search box key word are applied to firstName and lastName.
7. "Sort By" is a dropdown to select sorting key. Default filter is based on 'createdAt'.


# Improvements 
1. add typescript 
2. add validation for form item field: for example: if vakueKey is mssing, error pops and form will not be rendered.
3. add remove card function.
4. add edit card function.
5. More to dos 
