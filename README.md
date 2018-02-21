# Projects

 

## Auth API

### Handles OAuth2 authentication



## API

### Handle requests/responses of the API with the correspondent Http codes.

- Call bus (mediator) to handle Request/Response informations

- Receives and reponds DTOs (Data Transfer Objects) to clients

- Using OWIN as interface between API and IIS

- Using Swagger library for documentation of the API (UI accessible through http://localhost:53070/swagger/)




## Domain

### Contain all domain/business logic.

- Contain Models.

- Contains Commands, Queries and their Handlers (Using MediatR library).

- Call Data layer to retrieve/persist informations.



## Data

### Handle Database objects and manipulate data. e.g. Mappings / Repositories / Context.

- Using Entity Framework as ORM for data access.

- Using Code First approach.

- Automatically creates Database and seed data in the first execution.

- Using AsNoTracking for better performance on retrieving data.



## CrossCutting.IoC

### Project that handles Dependency Injection of the application.




## IntegrationTest

### Project that handles integration tests of the API.




## UnitTest

### Project that handles unit tests of the application.



## Overall Arquiteture and Patterns used

- Domain Driven Design: Layers and Domain Model patterns applied.

- CQRS (Command Query Responsability Segregation) through MediatR library.

- Repository Pattern: Data layer.

- Dependendy Injection Pattern.



## Main libraries used

- AutoMapper: Handle mappings.

- EntityFramework: Microsoft ORM.

- MediatR: In-process messaging.

- OWIN: Decouple web server and web application.

- Swashbuckle: Swagger implementation for .NET, documentation for API.

- IdentityServer4: Handles OAuth2 authentication