## Selenium-Java Test Automation Framework

----
## Setup
1. Download [SeleniumJavaAutomation](https://github.com/irfanalinoor/SeleniumJavaAutomation) Project from GitHub
2. Install latest [Java SDK](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
3. Install latest [IntelliJ IDEA](https://www.jetbrains.com/idea/)
4. Open Project = SeleniumJavaAutomation
5. Open Maven Project Tab on IntelliJ IDEA and click on LifeCycle > Package. This will install project dependencies.
6. Run Tests.


----
## Concepts Used
1. Maven-Java
2. Selenium (WebDriver)
3. JUnit
4. PageObject 

----
## Sample Tests: 

    Scenario: A trip request can be executed and results returned
    Given:  User is planning a trip
    When: He executes a trip plan from "North Sydney Station" to "Town Hall Station"
    Then: A list of trips should be provided



