 Highly distributed, how to prevent a problem in a single service from cascading up and out to the consumers of the service.
 
 * Client-side load balancing 
   
   How to cache the location of your service instances on the service client so that calls to multiple instances of a 
   microservice are load balanced to all the health instances of that microservice
   
 * Circuit breakers pattern
   
   how to prevent a client from continuing to call a service that's failing or suffering performance problems
   
 * Fallback pattern
 
   when a service call failes, how do you provide a "plud-in" mechanism that will allow the service client to try to carry out its
   work through alternative means other than the microservice being called
 
 * Bulkhead pattern
   
   use multiple distributed resources to carry out their work. compartmentalize calls so that the misbehavior of one service 
   call doesn't negatively impact the rest of the application?
   
   
 
 
