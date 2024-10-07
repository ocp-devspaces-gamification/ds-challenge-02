## Challenge-02

### Scenario
* 
* 


### Set Up + verification
* Open a terminal. Run the quarkus application in live coding mode with the command : "./mvnw quarkus:dev"
* Select your option "y/n" to the question (if asked) : Do you agree to contribute anonymous build time data to the Quarkus community? 
* Open another terminal and invoke "curl localhost:8080/api/greet/bengaluru". You will see empty result
* Openthe "src/main/java/org/acme/GreetingResource.java". You will observe the method "greetUser" needs to be fixed.

### Success Criteria
* Method "greetUser" is updated to accept a string as a parameter and returns a concatenated string of "Hello " and the passed name
* Invoking "curl localhost:8080/api/greet/bengaluru" will return "Hello bengaluru"
* Invoking "curl localhost:8080/api/greet/delta" will return "Hello delta"

### Resources
* https://quarkus.io/
* 

