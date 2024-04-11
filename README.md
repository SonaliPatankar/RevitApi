# RevitApi

# Revit API: Hello World

This Revit API project contains a simple external command that displays a "Hello World" message using a TaskDialog.

## Usage

To use this project, follow these steps:

1. Open the solution in Visual Studio.
2. Build the solution to compile the code.
3. If necessary, adjust the project settings such as target Revit version, build configurations, etc.
4. Run Revit.
5. Load the add-in into Revit:
   - Copy the compiled .dll file to the Revit Add-ins folder. By default, it's located at:
     - **For Revit 2021**: C:\ProgramData\Autodesk\Revit\Addins\2021
     - **For Revit 2022**: C:\ProgramData\Autodesk\Revit\Addins\2022
     - **For Revit 2023**: C:\ProgramData\Autodesk\Revit\Addins\2023
     - **For Revit 2024**: C:\ProgramData\Autodesk\Revit\Addins\2024
6. Launch or reload Revit.
7. In Revit, navigate to the "Add-ins" tab.
8. You should see the "Hello World" command listed.
9. Click on the command.
10. A TaskDialog will appear displaying the message "Hello World".
    
# Revit Add-in: Hello World Panel

This Revit add-in creates a custom ribbon panel with a button that triggers a command to display a "Hello World" message using a TaskDialog.

## Usage

1. Open Revit.
2. Navigate to the Add-ins tab.
3. You should see a panel named "NewRibbonPanel".
4. Click on the "Hello World" button.
5. A TaskDialog will appear displaying the message "Hello Entire World".

   
