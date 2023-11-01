Previous requirements:

THE .NET 6 FRAMEWORK MUST BE INSTALLED.
BROWSER BY DEFAULT, GOOGLE CHROME.
Visual Studio 2019 or above.
Visual Studio Code 2022.
SQL Server 2014 or higher.
SQL Management Studio v17.8.1.
NodeJS for windows 10.
ReactJS 18.
POSTMAN for Windows 10.



--------------------------------------------------

WHAT'S THIS APPLICATION ABOUT?

This a demo of a Company monolithic intranet web application which implements ASP.NET Web Api as backend and ReactJS 18 as frontend. You can perform CRUD operations over both Company's Departments and Company's employees.

--------------------------------------------------

How to run this application locally?

1- OPEN AND RESTORE THE DATABASE "CompanyDemoDB"..\REACT JS\DB\COMPDB.bak, ON THE SELECTED LOCAL SQL SERVER.

2- OPEN THE FILE 
   \\REACT JS\API\WebApplication1\WebApplication1\appsettings.json
    
    AND MODIFY THE CONNECTION STRING:

    "Data Source=WIN-IJCBKM5MI60\\SQKK17;Initial Catalog=CompanyDemoDB; Integrated Security=true"

    SO THE DATASOURCE CAN POINT TO YOUR LOCAL SQL SERVER.

3- OPEN THE VISUAL STUDIO 2019 SOLUTION 
   \\REACT JS\API\WebApplication1\WebApplication1.sln

4- OPEN A NEW WINDOWS EXPLORER WINDOW AT THE LOCATION 
    \\REACT JS\REACT CRUD\ui\my-app

5- SELECT THE ADDRESS BAR OF THE OPENED WINDOW OF THE PREVIOUS STEP.

6- WRITE THE COMMAND "CMD" IN THE ADDRESS BAR, OVERWRITING THE CURRENT PATH, THEN 
   PRESS ENTER.

7- IN THE COMMAND LINE WINDOW THAT WAS JUST OPENED, WRITE "code ." AND THEN PRESS
   THE ENTER. IT'S IMPORTANT TO LEAVE A SPACE AFTER "code".

8- RUN THE SOLUTION ..\\REACT JS\API\WebApplication1\WebApplication1.sln AND WAIT
   FOR IT TO OPEN A NEW BROWSER WINDOW.

9- COPY THE URL SHOWN IN THE PREVIOUS STEP INTO A NOTEPAD.

10- MODIFY THE FILE \\REACT CRUD\ui\my-app\src\Variables.js, SO THAT THE API_URL  
    AND URLs PHOTO_URL POINT TO THE PORT NUMBER OF THE URL THAT WAS COPIED TO THE NOTEPAD FROM THE PREVIOUS STEP.

11- IN THE OPENED COMMAND LINE WINDOW, TYPE "npm start" AND THEN PRESS ENTER.

12- WAIT FOR THE BROWSER TO OPEN A NEW WINDOW SHOWING THE MAIN PAGE
    OF THE APPLICATION THAT CONTAINS THE "Home", "Department" and "Employee" BUTTONS.

13- IN THE EVENT THAT THE WINDOWS FIREWALL REQUESTS PERMISSION TO RUN THIS APP,
CLICK ON "ACCEPT".

14- For functionality purposes it's important that you click on the button "Home", before clicking any other button.

15- When you create a new Employee, you can select a profile picture from 

    \\REACTJS_ ADONET\EXTERNAL PICS
    
--------------------------------------------------

HIGHLIGHTS:

    - This application implements ADO.NET for the Data Access layer.

    - This Reactjs application implements the classic "JavaScript" approach, instead of
      the modern "TypeScript" approach which I took to create the othee version with Entity Framework Core. Still, this "JavaScript" version has a lot of stability.
    
    - This "JavaScript" approach version of the application doesn't prevent full 
      re-rendering of the components, since they're defined as "functions".

    - Although I know the heavy differences in performance comparing this version against
      the other version with TypeScript, I've considered important to show my skills regarding flexibility to work with Reactjs in both cases. 