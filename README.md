# WebApplication1

Part I
Create a new project in Visual Studio 19
In the Create a new project window, choose C# from the Language list.
Choose the ASP.NET Core Web App template, and then choose Next.
In the Additional information window, verify that .NET 5 appears in the top drop-down menu.
Right-click on your project and choose Manage NuGet Packages.
Search for Newtonsoft.Json and install it for your project.
Check your .csproj file (Newtonsoft.Json package has been added).
Right-click on your solution and choose Restore Nuget Packages.
Rebuild your solution.
Right-click on your project and choose Publish.
In publish window choose Folder.
In Location choose the folder location and then choose Finish.
In publish window press the Publish button.
Some publishing files were created at [Your project]/bin/Release/net5.0/publish.
Check your project is running.



Part II
Enter to RDP in your computer 
Add IIS Manager to your Windows server.
Create new application pool by right-clicking Application Pools.
For .NET 5 choose No Managed and Integrated.
Create new website by right-clicking Sites.
Give your site a name, press SELECT and choose the application pool that you created.
On physical path insert: C:/inetpub/wwwroot.
In wwwroot directory press Make New Folder and create a folder for your website.
In Binding insert the port for your website (for example: 5100) and press OK.
Right-click on your website and press Explore.
Copy your publish folder (PART I) to the folder you created.
Your website has been created so refresh it and browse on http://localhost:[your port].
There is an ERROR (500.29).
Download ASP.NET Core Hosting Bundle and install it on your windows server machine (https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-aspnetcore-5.0.10-windows-hosting-bundle-installer).
Refresh your website and press Browse*:[your port](http).
