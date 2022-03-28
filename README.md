# GoHighLevel Assignment

The Automation scripts in this project are developed using the Cucumber (v 6.x.x) BDD framework with Java as programming language. 
It generates Extent Spark Report and PDF Report.


## Installation (pre-requisites)
1. JDK 1.8+ (make sure Java class path is set)
2. Maven (make sure .m2 class path is set)
3. Eclipse
4. Eclipse Plugins for
   * Maven
   * Cucumber
5. Browser driver (make sure you have your desired browser drivers in  `` driver ``  folder under project directory).
   Currently this repository has below drivers:
  
   * Chrome driver version - [98.0.4147.30](https://chromedriver.storage.googleapis.com/index.html?path=98.0.4758.102/), compatible with Chrome version 98.x.x



## Setup

* Install dependencies  `` mvn install ``

# Test data 
* Go to project 
* Open project.properties
* Add `` username  `` , `` password `` 

## Running your tests
* To run the test on open terminal 
* Go to project directory path 
* Enter command as : ``  mvn -Dtest=GoHighLevel_UI_Runner test  ``

## Reporters

### Spark Extent Report:
Generates HTML report at project directory path:  `` test-output/SparkReport ``
