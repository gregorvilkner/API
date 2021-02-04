# CESMII Smart Manufacturing Innovation Platform
CESMII's Smart Manufacturing Innovation Platform™ (or SMIP™, for short) is a collection of technologies for simplifying access to manufacturing data by normalizing across protocols, enforcing a re-usable object model, and guaranteeing an interface contract for application development. These goals are implemented through the related [Smart Manufacturing Profile™](https://github.com/cesmii/SMProfiles) (SM Profile™) project, a cooperation between OPC UA and CESMII Members, to create re-distributable and extensible Information Model that includes protocol bindings. 

Once applied by an adopting platform (such as the SMIP, or other commercial offerings) the developer interface to the object model is exposed through GraphQL. These documents describe this interface, and how to build raw payloads. Efforts to develop SDKs that provide a simplified adoption path fromspecific programming languages or environments are also discussed.

## GraphQL API
* [Intro to GraphQL](https://github.com/cesmii/API/wiki/Intro-to-GraphQL)
* [GraphQL applied to Smart Manufacturing](https://github.com/cesmii/API/wiki/GraphQL-applied-to-Smart-Manufacturing)
* [SMIP GraphQL Endpoint](https://github.com/cesmii/API/wiki/SMIP-GraphQL-Endpoint)
* [SMIP GraphQL SDKs](https://github.com/cesmii/API/wiki/SMIP-GraphQL-SDKs)

### Security and Authentication
* Acquiring a JSON Web Token (JWT)
* Handling Token Expiry

### Queries
* [Type (SM Profile) list](https://github.com/cesmii/API/wiki/GraphQL-Queries#query-types)
* [Equipment list](https://github.com/cesmii/API/wiki/GraphQL-Queries#query-equipment)
* [Location list](https://github.com/cesmii/API/wiki/GraphQL-Queries#query-locations)
* [Attribute list](https://github.com/cesmii/API/wiki/GraphQL-Queries#query-attributes)
* [Time Series Values](https://github.com/cesmii/API/wiki/GraphQL-Queries#query-timeseries)

### Mutations
* [Inserting or updating time series samples](https://github.com/cesmii/API/wiki/Inserting-or-Updating-Time-Series-Samples)