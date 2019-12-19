 # microservice-based architectures 
 
  * constrained :
  have a single set of responsibilities and are narrow is scope.
 
  * loosely couple: 
  a collection of small services that only interact with one another through a non-implementation specific interface 
 using a non-proprietary invocation protocol. 
 
  * abstracted :
  microservices completely own their data structures and data sources. Data owned by a microservice can only be modified
  by that service.
 
  * independent : 
  each microservice in a microservice application can be compiled and deployed independently of the other services used in 
 the application.
 
 # Cloud-based application
 
 * large and diverse user base
 
 * Extremly high upstream requirements

 * Uneven volume requirements


architect: an application can be decomposed into individual microservices and how the microservices will interact to deliver a solution
software developer: writes the code and understands in detail how the language and developement frameworks for the language will be used to
deliver a microservice.
DevOp engineer: how the services are deployed and managed throughout no only production, but also all the nonproduction environments.
__consistency__ __repeatability__

# Guideline for identify and decomposing a business problem into microservice candidate:

 1 Describe the business problem, and listen to the nounss you're using to describe the problem
 
 2 Pay attention to the verbs
 
 3 Look for data cohesion : microservices should completely own their data
 
 



 
