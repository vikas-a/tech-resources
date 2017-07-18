

### How to Model services
   - Good service
        Loose coupling
        High Cohesion
   - Bounded context
        Domain driven design
        Shared and hidden models
        Modules and services
    Business capabilities
        When thinking about the bounded contexts, we should not be thinking about the data that is being shrared, but the capabilities that those context provide to the rest of the domain.

    The technical boundary
    
Integration
    Microservices should retain their autonomy allowing them to change independenly and be deployed
Ideal Integration technology : Guiding principles
Avoid breaking changes : Every change should try to be backward compatible
Keep the APIs technology agnostic
Make the services simple for customers to use
Hide internal implementation details : Expose as little data as needed for the business. Not more, not less
         2.   

Scaling
    Splitting workloads
    Single microservice per host using Kubernetes
Service discovery
    Kubernetes service discovery mechanism

Configuration
    Distributed configuration
    Secrets
