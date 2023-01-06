# RumbleOnSFApi MicroService
RumbleOnSFApi microservice provides api methods to create/update Account, Contact or Leads in Salesforce.

## Quick Setup (New Windows Development Environment)
Follow these steps to get your environment set up as quickly as possible:

- Download and install [Visual Studio 2019 Community](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=16)

## Requirements
API development and building requires the following:

- .NET Core 2.2 SDK
- Microsoft Sql Server Management Studio

### Git Setup
- Install [Git](https://git-scm.com/downloads)
- git config --global user.name "{FULL_NAME}"
- git config --global user.email {EMAIL}
- git config --global core.autocrlf input.
- Refer to Advanced Git Configuration for additional information.

### Github Flow/SourceTree/GitHub Desktop
- Create the branch
- Add commits
- Open a Pull Request
- Review & Collaborate changes
- Deploy and Test
- Merge

## Build Instructions for .NET Project
Once the above requirements are in place, open the solution file (*.sln) in Visual Studio:

Once that has been done, you can build the solution again in Visual Studio by selecting **Build**->**Build Solution**. The application can just as easily be debugged from within Visual Studio by selecting **Debug**->**Start Debugging**.

Debugging the application will start up a new instance of the API and open a browser, which is where the backend runs from. 

You will likely want to debug the API directly by using an application like [Postman](https://www.getpostman.com/apps). To do so, simply run the Debug from Visual Studio and then run your API calls from Postman after the application is running. To facilitate this process, you may want to disable the "Stop debugging when browser window is closed" option in Visual Studio (`Ctrl+Q` to search for that option by default).
