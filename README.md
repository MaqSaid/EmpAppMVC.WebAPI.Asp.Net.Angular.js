# EmpApp using technologies MVC WebAPI in Asp.Net and Angular.js
CRUD Operations on Emp App using Web API Asp.Net and Anguar.js
Hero360 Employee Management App

1) Application Scope and Objective:
CRUD Operations:Showing List of Employees Previously Entered in Database Using Add Option. Option to Add New Employee to Database and Option to Edit/Delete Exisitng Employee and Save to Database.

2) Approach and Technologies Used
This is a SPA : Single Page to perform CRUD Operations on Employee Management App, Developed using ASP.NET WEB API, MVC and Angular.js.
I created SQL database company.mdf and EmployeeInfo table. Further I created a Model using DATABASE FIRST Approach.
Further in Controller using Entity Framework selected my Model and Context Class to generate methods performing GET,POST,PUT and DELETE operations.
Created controller and added my methods to ListAdd, Edit and Delete Employee.
The Advantages of using this method and technologies is we avoid post back using AngularJS and CRUD operations can be performed using REST API in MVC .NET Framework

3) ****** What is Remaining to be Developed? *****
Creation of Department Master and Designation Master, so that they can be related by Foreign key to EmployeeInfo table to minimise Client Validations
*** In Employee Edit, rendering of Date using Anugular.js 1.2 is not occuring in yyyy-mm-dd format, I have to work to solve this issue.
**** You will find Home,About, Contact, Register and Login, but they are OUT OF SCOPE OF CURRENT SPECIFICATION PROVIDED.
**** OUT OF SCOPE: Client Side Validations are Yet to be Done and Proper Message Alerts.
**** OUT OF SCOPE: The App has not been tested for Mobile Mode and More Styling CSS has to be done for both Desktop and Mobile Devices
*** OUT OF SCOPE :Authentication, registeration and sign in

4) Steps to Deploy/Run the Application
Download and UnZip the File and Open the Solution in Hero360Proj\Hero360EmpMgmtProj\EmployeeManagementApp.sln in Microsft Visual Studio Community 2017 15.4.1.
Within the Opened Solution Open the Folder Hero360EmpMgmtProj\Employee.Web.UI\App_Data\Company.mdf.
Check your Connection String Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename="Employee.Web.UI\App_Data\Company.mdf"; Integrated Security=True;Connect Timeout=30.
Test your Database Connection.Change the Connection String in your Web.Config File.Edit your connectionString in Web.Config.
Build the Solution and Run in Non-Debug Mode Ctrl+F5.Note: Index.cshtml is our Index page.If the solution gets builds without any errors, then run http://localhost:11360/EmployeeInfo/Index.
Test if you can Perform CRUD operations on Employee using Show List, Add Employee, Edit Employee and Delete Employee.
