# _Pierre's Sweet and Savory Treats_

#### By _**Trevor Hunter**_

#### _An application where customers can view Treats, and the Flavors that are associated with them, and vice versa._

## Technologies Used

* _C#_
* _.NET 5_
* _Entity_
* _MySQL_
* _ASP.NET Core MVC
* _HTML_
* _JavaScript_
* _CSS_

## Description

_This application lets the user look at the different treats and flavors that Pierre has, and see which treats and flavors are connected._

_On this application, the user can create a new account, and from there will be able to Create, Edit, and Delete Flavors and Treats within the website._

_All CRUD Methods exist for both Treats and Flavors. This application also features full Identity usage and Authorization. Many of the pages are restricted for users that are not signed into an account._

## Setup/Installation Requirements

* _Clone project from repo: https://github.com/TrevorH08/Pierres-Treats ._
* _Make sure you have Entity Framework Core installed at a Global level. To Ensure, paste the following into your terminal_
** _$ dotnet tool install --global dotnet-ef --version 5.0.1_
* _Create a file in the main project folder /Factory called appsettings.json_
* _Enter this code into the file: 
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=factory;uid=[ENTER YOUR USERNAME];pwd=[ENTER YOUR PASSWORD];"
  }
}_
* _From there run the following commands in the terminal:_
* _$ dotnet restore_
* _$ dotnet build_
* _$ dotnet ef migrations add Initial_
* _$ dotnet ef database update_
* _$ dotnet run_

## Known Bugs

* _No Known Bugs_

## License

MIT

If you have any questions or issues, head over to this projects GitHub Repository, and navigate to the "Issues" tab to leave feedback! If you have any suggestions or would like to contribute to this project, reach out and let me know!

Copyright (c) 10/30/22 Trevor Hunter

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
