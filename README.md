# TPGA UI (Angular) Assignment

## TOTAL DURATION: 4 Hours


**BEFORE YOU BEGIN, READ THIS**
- Create an Angular Project using NPM and Angular CLI.
- You may use any open source libraries via NPM that aid quicker development.
- Ensure that your code is written in TypeScript instead of JavaScript.
- Once completed, ensure that you run the build to generate the Javascript code.



> SECTION 1 - **Duration 40 Minutes**
Create a Login page. This should be the default view. Feel free to design it the way you like it and apply your own theme. Add Form validations to the Login screen.

> SECTION 2 - **Duration 1 Hour**
Create a Home page. On valid Login submit, the user should be redirected to this page. This page should have a navigation bar with two tabs; "Home" and "Graph".
The "Home" tab should contain a DataGrid that loads data via a HTTP call. You can use any public API (example: https://www.govtrack.us/api/v2/role?current=true&role_type=representative&limit=438) or visit this page (https://github.com/jdorfman/awesome-json-datasets#government) for other sample APIs. If time permits, feel free to add features like column sorting, search, pagination, etc.
Note: You do not need to show all the data in separate columns. It is up to you to decide which columns should be displayed.

> SECTION 3 - **Duration 1 Hour**
In the grid, each of the rows should have an edit button. On click, a dialog popup should open that lists all the grid columns in a Form in edit mode along with a "Ok" button. You can decide to choose the input form elements based on the type of data the column has. On clicking "Ok", the changes made should be reflected in the grid row. 

> SECTION 4 - **Duration 1 Hour, 20 Minutes**
In the "Graph" tab, use the same grid data or any data in the link provided above to create a dashboard of multiple chart widgets. This is where you take the liberty to make your own layout and decide what charts should be depicted. You can decide any open source chart library / libraries you wish to use. Ensure there are at least 3 chart widgets. This (https://coderthemes.com/minton/boxed-hori/index.html), is an example of what we are looking for. 
