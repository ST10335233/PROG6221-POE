This is how the software works

Open Visual Studio: Launch Visual Studio on your computer.
Open Project: Navigate to File > Open > Project/Solution... and select the solution file (.sln) of the Recipe Filter Application.
Restore Packages: If prompted, click Restore to ensure all required NuGet packages are installed.
Set Startup Project: In the Solution Explorer, right-click on the project representing the Recipe Filter Application and choose Set as Startup Project.
Build Solution: Go to Build > Build Solution or press Ctrl + Shift + B to compile the application.
Start Debugging: Press F5 to run the application in debug mode or Ctrl + F5 to run without debugging.
Use the Application: Follow the instructions in the user manual to interact with the Recipe Filter Application.

These are the changes that ive made.

UI Organization: The layout was restructured using StackPanel for better alignment and grouping of controls, improving visual clarity and user experience.
Input Controls: Added TextBoxes and ComboBox (FoodGroupComboBox) for recipe details such as name, ingredients, food group, ingredient calories, max calories, and scale factor. This enhances input handling and user interaction.
Button Functionality: Each button was linked to specific event handlers (Click events), enabling functionality like entering recipe details, displaying all or specific recipes, scaling recipes, resetting quantities, clearing recipes, filtering based on criteria, creating menus, and exiting the application.
ListBox Display: The ListBox (RecipeListBox) was configured with an ItemTemplate to display recipe names, ensuring recipes are visually represented in a clear and organized manner.
