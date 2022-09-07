# CMPG323-Project2-27191532-Azure-.NETcore3.1
Azure and .NET Core 3.1 API

## How to use the API
1. Head to the API website for a visual representation of all the commands. ```LINK```: <a href="https://project2-api-v2.azurewebsites.net/swagger/index.html">PROJECT2_API_V2</a> 	
2. Access is very limited if a user is not logged in.
3. You will have to create an account first under ```Authentication``` and then ```register```.
4. Create your ```Username``` and ```Password```.
5. You may now navigate to the ```login``` command.
6. Enter your details and the server should respond with a ```JWT Token```, which you need to access all the other requests.
7. Copy the ```JWT Token``` string, navigate to the top of the webpage.
8. Top-right, click ```Authorize``` and enter "Bearer token_here".

## Project Progress
1. Currently I have a local dB running ```SQL SERVER 19``` managed with ```SSMS```, linked with a ```.NET 3.1``` API.
2. I will make use of ```swagger``` to test and document the API return codes and functionality.
3. Next, I will try to link the cloud dB with the API, to test and populate the database with a ```add-migration``` ```.NET``` command.
4. Managed to link the local visual studio code with an ```Azure dB```.
5. Added Controllers for , Zone, Device and Category.
5. Fixed issue with the authentication.
6. Login requests now receive a ```JWT token```.
7. Currently working on having the ```API``` hosted on ```Azure```.
8. ```API``` is now hosted on ```Azure```.


## Branching Strategy 
1. The main branch was used to deploy the initial API with swagger.
2. The developer branch is used to introduce Authentication within the API requests.
3. The developer branch was used to further expand the API.
3. The developer branch was used to implement code from version 1.

## References
1. <a href="https://www.tutorialsteacher.com/sqlserver/install-sql-server">Tutorials Teacher</a>
2. <a href="https://docs.microsoft.com/en-us/ef/core/cli/dotnet">Entity Framework Core tools reference</a>
3. <a href="https://www.c-sharpcorner.com/blogs/implement-swagger-in-asp-net-core-31-web-api">C# Corner</a>
4. <a href="https://jwt.io/introduction/">JSON Web Token</a>
5. <a href="https://docs.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-6.0&tabs=visual-studio">MS DOCS Create minimal web with ASP.net Core</a>
6. <a href="https://www.youtube.com/watch?v=elMpS1Js7rc">Awesome Youtube video by TechWithPat</a>