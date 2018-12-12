# SPA-With-Blazor
- Single Page Application using Razor pages in Blazor
- Entity Framework Core database first approach
- Application performed with CRUD operations on it
- .Net Core app developed on MacOS
- Database firt approach
- Scafolding via command line:
Scaffold-DbContext "Your connection string here" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -Tables Employee

- Link to working app hosted on aws:
http://ooproject-dev.us-west-2.elasticbeanstalk.com/

- MAC Visual Studio 2017 Community 

Deployment 
- AWS Elastic Beanstalk
- AWS MSSQL RDS instance



- Final application.

![Alt Text](https://i2.wp.com/ankitsharmablogs.com/wp-content/uploads/2018/05/BlazorWithRazor.gif)


This was a an interesting project to get my hands wet with Blazor development. Blazor allows for the use of C# server and client side. No need to use javascript to make this a spa. C# gets complied via webasembly. Though .Net Core has been around for some time I felt that the creation of even the most simple appliactions are not well documented nor intuitive for development or deployment on MacOS. Granted MacOS is not a native environment for C#.

Future work:
- Create full documentation and a guided tutorial for steps needed to recreate this Blazor SPA App which includes:
  - Errors that I ran into even when creating a project based of a template.
  - Running your application on a Mac.
  - Scafolding your DB with Blazor Hosted app (This was a big time consumer) but might have been an issue with the template       itself. I have to confirm.
  - Deployment to AWS (on Windows this can be done via integrated AWS tools in VS Studio. Not the case for VS. Mac).
  - How to migrate and run your applications (if locally) on a Windows machine (Mac -> Windows). 
  - How to deploy your app on Windows
  - How to set up AWS instances for your deployment.
  
- Grow out the application, add more "useful" features
