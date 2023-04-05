# Online parking blog

# The objective of the project.

The intention of this project is to make an online parking web page.

# ****Audience of the project.****

This project is for people who wants to use online parking system.

# ****Data Collection****

Data of this project are collected from the user.

# ****Structure**** of the project.

What this web page does is that it collect information of a car when it Enters a parking space the information it takes are  (Owner , Plate . Model . Color . Check in time)  can take more if needed.

It has a validation to enter every filed or else it wont proceed it will show as error.

After taking those it will display them on a table and adds extra column that has a leave button in it. This leave button will remove the car from the table.

How this work is that after the user gives all the info in a given input they will be stored in a variable and  we have a table with headers we will create a row and  we append this row to the table we have after that we create cells and assign the values of the variables to the cells and append all cells to the row and also the remove button will be created be the createElement method in js and will also be appended to the row.

After that the function of the leave button comes when that button is clicked we will get the id of the row that button is and delete the that row by using element.remove() methode.