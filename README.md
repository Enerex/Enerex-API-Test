# Enerex-API-Test

The goal of this project if for the developer to create an API that will provide access to the students data provided in the txt file. <br>

# Implementation

1. Data from the provided file should be loaded into database and consulted using EF Core. <br>
2. Implement CRUD with all necessary endpoints to: <br>
   2.1 Get complete students list <br>
   2.2 Add new student <br>
   2.3 Update existing student <br>
   2.4 Remove existing student <br>
3. Implement additional endpoint to retrieve specific information given a particular request: <br>

## Sample Input
Given gender and/or age and/or education and/or academic year
F,25,Construction Engineering,4

## Sample Output
Return a list with all students that matches the filters
Case #5: Ellie Brown Reed,Laura Stewart Foster,Nicole Peterson Torres

# Project structure: 
## SQL Server or My SQL database: 
A simple database using Microsoft SQL Server (2018) or MySQL. The express SQL Server instance within Visual Studio also may be used or inMemory collection can be used
## Data access layer / service layer: 
It must be implemented through a web API using any of the following versions: .NET Core 3.1 or .NET 6.0 framework or higher. 
## Test suite: 
For testing purposes, it is required the use of Swagger or Postman. 

# Additional information

Complete the application design taking into consideration SOLID principles.

# Once completed

After completion please contact your recruiter and share a link to the github or docker with the solution.
