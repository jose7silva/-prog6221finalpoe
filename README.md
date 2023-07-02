# -prog6221finalpoe
POE
Recipe App
The Recipe App is a simple application that allows you to create and manage recipes.
With this app, you can easily add ingredients, specify their quantities, units, 
calories, and food groups, and define the steps to prepare your recipes. The app 
provides a user-friendly interface to interact with and visualize your recipes.
Getting Started
To use the Recipe App, follow these steps:
Launch the application.
In the "Recipe Name" field, enter the name of your recipe.
Click on the "Add Ingredient" button to add ingredients to your recipe.
Enter the details of the ingredient, including the ingredient name, quantity, unit, 
calories, and food group.
Click on the "Add Ingredient" button to add the ingredient to the recipe.
Repeat steps 4 and 5 to add more ingredients as needed.
In the "Steps" field, enter the steps required to prepare the recipe.
Click on the "Add Recipe" button to add the recipe to the app.
The added recipe will appear in the "Selected Recipe" section.
To view the details of a recipe, select it from the "Selected Recipe" list.
The recipe's name, ingredients, and steps will be displayed in the respective 
fields.
To clear the form and start afresh, click on the "Cancel" button.
The app also provides a pie chart that displays the number of ingredients in each 
recipe.
System Requirements
The Recipe App requires the following system configuration:
Operating System: Windows
.NET Framework version: 4.7.2 or higher
Dependencies
The Recipe App uses the following dependencies:
LiveCharts.Wpf - A data visualization library for WPF that provides the pie chart 
functionality.
Development
The Recipe App is built using C# and XAML, utilizing the Windows Presentation 
Foundation (WPF) framework for the user interface. The application code is organized
into the following classes:
MainWindow (MainWindow.xaml.cs) - The main window of the application, responsible 
for handling user interactions and managing the recipes.
Recipe - A class representing a recipe, including its name, list of ingredients, and
steps.
Ingredient - A class representing an ingredient, including its name, quantity, unit,
calories, and food group.
The app leverages the ListBox control to display the list of ingredients and 
recipes, and the PieChart control from the LiveCharts library to visualize the 
number of ingredients in each recipe.
Acknowledgments
The Recipe App was developed as a sample application to demonstrate the use of C#, 
XAML, and WPF for building desktop applications. It incorporates the LiveCharts 
library to provide a visually appealing representation of recipe data.
