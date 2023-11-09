# pcce_event_2023
Workshop - Introduction to Umbraco CMS

## PREREQUISITES
### Windows PC with internet access

### IIS

### Visual Studio 2022 (community edition)
https://visualstudio.microsoft.com/downloads/

### .NET 7 SDK
https://dotnet.microsoft.com/en-us/download/visual-studio-sdks

### Git
https://git-scm.com/download/win

### Git client - Tortoise
https://tortoisegit.org/download/

## IMPORTANT LINKS
1. Create a free umbraco cloud account
https://umbraco.com/products/umbraco-cloud/

2. More info on Umbraco Cloud | Video on creating a trial umbraco coud project
https://docs.umbraco.com/umbraco-cloud/

3. Video on cloning a project from cloud
https://docs.umbraco.com/umbraco-cloud/set-up/working-locally

4. Working with umbraco cloud
https://www.youtube.com/watch?v=uvBpiY9TkV0


## DEVELOPMENT PLAN


### Create a project on Cloud
1.	Introduction about Umbraco Cloud
2.	Create a free Umbraco cloud trial project.
https://umbraco.com/products/umbraco-cloud/
3.	Enter the details and verify it.
4.	This will create a free workspace for you in the cloud. While it spins a new project talk about the other links
5.	Go to the backoffice and give a quick tour about it
6.	Show the empty frontend
7.	Show https://www.s1.umbraco.io/

### Clone the project locally
1.	Click on the clone project option from the dropdown menu and copy the clone url
2.	Create a folder in your file system – MyUmbracoSite
3.	Open it in terminal and type the following command
git clone https://scm.umbraco.io/euwest01/debasishs-fearless-otter.git
4.	It will probably prompt you for the username and password
5.	This will create a project for you locally
6.	Open the UmbracoProject.csproj in the Visual Studio IDE
7.	Check target framework if .net 7
8.	Manage Nuget Packages for Solution
9.	Install Clean v3.1.4 by Paul Seal
10.	 Run the project
11.	 Double click on the project and change the package reference from Clean to Clean.Core
12.	 Run the project
13.	 Make some content changes and show
14.	 Push the schema to cloud using tortoise git
15.	Queue for transfer the content and media
16.	 Browse the cloud site
17.	 Make some changes on Live and show


