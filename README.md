# CMPG323-Project2-27191532-Azure-.NETcore3.1
Azure and .NET Core 3.1 API

## How to use the API
1. 

## Project Progress
1. Currently I have a local dB running ```SQL SERVER 19``` managed with ```SSMS```, linked with a ```.NET 3.1``` API.
2. I will make use of ```swagger``` to test and document the API return codes and functionality.
3. Next, I will try to link the cloud dB with the API, to test and populate the database with a ```add-migration``` ```.NET``` command.
4. Managed to link the local visual studio code with a azure dB.
5. Fixed issue with the authentication.
6. Login requests now receive a JWT token.


## Branching Strategy 
1. The main branch was used to deploy the initial API with swagger.
2. The developer branch is used to introduce Authentication within the API requests.\
3. The developer branch was used to further expand the API.

## References
1. <a href="https://www.tutorialsteacher.com/sqlserver/install-sql-server">Tutorials Teacher</a>
2. <a href="https://docs.microsoft.com/en-us/ef/core/cli/dotnet">Entity Framework Core tools reference</a>
3. <a href="https://www.c-sharpcorner.com/blogs/implement-swagger-in-asp-net-core-31-web-api">C# Corner</a>
4. <a href="https://jwt.io/introduction/">JSON Web Token</a>
5. <a href="https://docs.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-6.0&tabs=visual-studio">MS DOCS Create minimal web with ASP.net Core</a>
6. <a href="https://www.youtube.com/watch?v=elMpS1Js7rc">Awesome Youtube video by TechWithPat</a>