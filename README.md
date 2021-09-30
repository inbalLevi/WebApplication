# WebApplication1

Part I
* Create a new project in Visual Studio 19
* In the Create a new project window, choose C# from the Language list.
* Choose the ASP.NET Core Web App template, and then choose Next.
* In the Additional information window, verify that .NET 5 appears in the top drop-down menu.
* Right-click on your project and choose Manage NuGet Packages.
* Search for Newtonsoft.Json and install it for your project.
* ![image](https://user-images.githubusercontent.com/71599740/135452789-2a2e462a-fe76-4c74-bf71-c1bd0ec9737a.png)
* Check your .csproj file (Newtonsoft.Json package has been added).
* Right-click on your solution and choose Restore Nuget Packages.
* Rebuild your solution.
* ![image](https://user-images.githubusercontent.com/71599740/135453061-7b7f0a5f-b6e3-466b-88e7-dea3e69db6e3.png)

* Right-click on your project and choose Publish.
* In publish window choose Folder.
* ![image](https://user-images.githubusercontent.com/71599740/135453960-aead6599-30c6-4b3c-afb3-913af3bd21a1.png)
* In Location choose the folder location and then choose Finish.
* In publish window press the Publish button.
* Some publishing files were created at [Your project]/bin/Release/net5.0/publish.
* ![image](https://user-images.githubusercontent.com/71599740/135454037-75d99f91-1520-45bf-81db-bf5a0cec4222.png)
* Check your project is running.
* ![image](https://user-images.githubusercontent.com/71599740/135454232-3c58b0df-4fbb-4a08-86af-2fbd2e3fdbb8.png)




Part II
* Enter to RDP in your computer 
* Add IIS Manager to your Windows server.
* Create new application pool by right-clicking Application Pools.
* For .NET 5 choose No Managed and Integrated.
* Create new website by right-clicking Sites.
* Give your site a name, press SELECT and choose the application pool that you created.
* ![image](https://user-images.githubusercontent.com/71599740/135454499-41154ac6-16de-4856-81eb-eb778468e485.png)
* On physical path insert: C:/inetpub/wwwroot.
* In wwwroot directory press Make New Folder and create a folder for your website.
* In Binding insert the port for your website (for example: 5100) and press OK.
* Right-click on your website and press Explore.
* Copy your publish folder (PART I) to the folder you created.
* ![image](https://user-images.githubusercontent.com/71599740/135454738-c76c7812-f8db-45f4-bcc8-cc9fd6ea833e.png)
* Your website has been created so refresh it and browse on http://localhost:[your port].
* There is an ERROR (500.29).
* Download ASP.NET Core Hosting Bundle and install it on your windows server machine (https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-aspnetcore-5.0.10-windows-* hosting-bundle-installer).
* ![image](https://user-images.githubusercontent.com/71599740/135454585-ff713bfa-b775-423f-ae9a-4686f7a522c6.png)
* Refresh your website and press Browse*:[your port](http).
* ![image](https://user-images.githubusercontent.com/71599740/135454670-65acfc83-1027-4605-aa24-7a7a274294fb.png)

