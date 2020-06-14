# Project-Technician ☺️👌🏻

### In Progress - Any time, I finish 🛠⚙️ if it compiles it can get an error

_____________________________________________________________________

**Update**

Add data annotation

_____________________________________________________________________

**.gitignore**

- [x] mydb.db
- [x] Migrations


**Framework Web:**

- [ ] Blazor
- [x] Asp.net Core
- [ ] Asp.net

**Framework, tools and libraries**

- [x] .Net core
- [ ] .Net 

**Licence:** 
  
- [x] MIT
          
**Languages:**
   
- [x] JAVASCRIPT
- [x] C#
- [x] CSS/HTML
   
**Techniques:**

- [x] MVC
- [x] MVVM
- [ ] MVT

**SCAFFOLDING**
- [x] Controllers
- [x] Views
- [x] Models
- [x] ViewsModels

- mvc+vm scheme:          


                                                                   ORM
                                                    ___________________________________
                                                    |                                 |
                            |-----------------------|------|                          |
                            |                       |      |                          |
                           🔽                       |     🔼                          |
                          Views ⬅️--- Controllers --|--➡️ ViewModels ------➡️ Models--|---➡️ Database
                            |             |         |      |               |          | 
                            |             |         |      |               |          |
                            🔽           🔽         |     🔽              🔽         |
                         Response    Client Side    |   VistasDB           DB         |       
                                                    |                                 | 
                                                    |_________________________________|
                                                    
**Micro ORM or ORM:**

- [ ] Dapper
- [x] Entity Framework core
- [ ] Entity Framework

**Methods ORM**

- [x] Code first
- [ ] Database first
- [ ] Model first
              
                          Class ----➡️ EF CORE ----➡️ DATABASE
              
**Data annotations: Library**
              
**DataBase:**
      
- [x] SQlite
- [x] SQL server

  
**Platforms:**

- [x] Azure
   
**Development environments and tools:**

- [x] Visual studio code
- [x] Visual studio
- [x] DB browser for SQlite
- [x] SQlite Studio
- [x] SQL Server Management Studio

**Operating systems:**

- [x] Windows
- [x] Mac OS
- [ ] Linux

**Collaboration tools:**

- [x] Github
- [x] Notion
- [x] Azure
- [x] Discord
- [x] IIS
  
**Libraries integrate - no integrate the project online:**
  
          dataannotations: EF CORE
          
          side - client:
          boostrap twitter

              "library": "twitter-bootstrap@4.5.0",
              "destination": "wwwroot/twitter-bootstrap/"

          nugets:
          
                    
          Update: in the commit version 3.1.* for up

              <PackageReference Include="Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore" Version="3.1.5" />
              <PackageReference Include="Microsoft.AspNetCore.Identity.EntityFrameworkCore" Version="3.1.5" />
              <PackageReference Include="Microsoft.AspNetCore.Identity.UI" Version="3.1.5" />
              <PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="3.1.5" />
              <PackageReference Include="Microsoft.EntityFrameworkCore.Tools" Version="3.1.5" />
              <PackageReference Include="Microsoft.Extensions.Logging.Debug" Version="3.1.5" />
              <PackageReference Include="Microsoft.VisualStudio.Web.CodeGeneration.Design" Version="3.1.3" />
              <PackageReference Include="Microsoft.EntityFrameworkCore.Sqlite" Version="3.1.5" />
              
          Install nugets vscode:
              
                               dotnet add package Microsoft.EntityFrameworkCore.SqlServer

          jquery:
              
              jQuery JavaScript Library v3.3.1
 
 **Extras:**
 
          css:
          
              <link rel="stylesheet" href="~/lib/bootstrap/dist/css/bootstrap.min.css" />
              <link rel="stylesheet" href="~/css/site.css" />
          
          MDBoostrap:
          
              <!-- Google Fonts -->
              <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap">
              <!-- Bootstrap core CSS -->
              <link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.0/css/bootstrap.min.css" rel="stylesheet">
              <!-- Material Design Bootstrap -->
              <link href="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.19.0/css/mdb.min.css" rel="stylesheet">
              <link href="//netdna.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
              
          Font-awesome:
          
              <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">
              
 **Execute:**
 
 
 
 **VSCODE:**
         
         RUN:
         
         
         dotnet ef migrations add [migration name]
         dotnet ef database update
         cd Project_technician
         dotnet run
         
         
         
**VISUAL STUDIO:**
         
         RUN:
         
         add-migration [migration name]
         update-database
         boton run
         
              
              
              

**POSSIBLE ERROR SOLUTION**

                DOTNET TOOL INSTALL --GLOBAL DOTNET-EF
                DOTNET HELP
                DELETE FOLDER MIGRATIONS
                DELETE AND DROP DATABASE Mydb.db
                DELETE OBJ & EXECUTE DOTNET RESTORE
                REMOVE-MIGRATION INITIAL1
                DROP-DATABASE

              
**Errors Report**

                FIX
                Rename folders Project_Tecnician
                "Project_Technician", "Project_Technician\Project_Technician.csproj"

               
☠️ Create by SLTECHNOLOGY ☠️

   


