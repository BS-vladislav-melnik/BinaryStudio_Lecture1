  The first preview of ASP.NET Core 2 has been released, joining the release of .NET Core 2 Preview.  Developers can now take their first look at the code that will make up this major release that will adhere to .NET Standard 2.0.

  Among the new features found in 2.0 are meta-packages, a new default Web Host Configuration, simplified logging, and an improved ASP.NET Core Identity system which makes it easy to change authentication providers.  The addition of meta-packages provides an alternative way for projects to be setup:  simply add the Microsoft.AspNetCore.All package to get started.  Unused subcomponents will be trimmed automatically when the application is built.  These changes are on top of the many performance improvements which according to Microsoft produce web apps that start and execute quicker as well as use less disk space as compared to ASP.NET 1.X.

  At Build 2017, Microsoft’s Daniel Roth and Scott Hanselman were on hand to demonstrate firsthand what ASP.NET Core 2 offers developers.  The development team had four primary goals in mind when producing this release:

  Developer delights – Remove the papercuts (frustrating behavior) experienced when writing for ASP.NET Core
  
* Extending App Model

* Performance

* Increased Azure Integration

  Razor Pages have been added to ASP.NET Core 2 to provide a way for developers to start building web applications without requiring the infrastructure of a full MVC app.  One of the benefits to this approach is that since Razor pages are built on top of MVC, it is easy to later transform a growing application into a proper MCV solution.  Razor pages utilize the @page directive to handle requests directly without needing a corresponding controller.

  To use ASP.NET Core 2 Preview with Visual Studio 2017, you will need to install the latest build (15.3 Preview).  Visual Studio is not required and working from the Windows command line, Mac or Linux is also an option.  Installation binaries are available for all three platforms today.

  Remember that this can be installed side-by-side with your current production copy of VS2017 15.2.  Full release notes are available on GitHub. It should also be noted that ASP.NET Core 2 applications will be able to run on Mono, .NET Core, and .NET Framework.


## Very deep thought should be here:D
