# spriteCloudTest

How to Run the Tests Locally

Web: 
  - Install Selenium AddOn for whichever Browser you use.
  - Download SpriteCloudTest.side from this repository and Import it into the Add On. 
  - Run the tests

API: 
  - Download Postman
  - Download Petstore Test Automation.postman_collection from this repository
  - Import the Collection Into Postman and Run Collection



Run Tests in CI/CD Pipeline
(Ran out of time for this) 
  - Would use either GitLab or Jenkings (I would need to use Newman with Postman in order to automate the collection) 
  - Not sure how I would go about adding the Capture and Playback to a Jenkings Pipeline, would need to go research that one. 



Link to Calliope.pro


Scenario Selection:

[Risk based Approach - each software I asked a few questions to help me determine risk, I had to make a few assumptions but was happy with the selection]


![image](https://user-images.githubusercontent.com/36734593/148464070-33768ac5-dc8a-40c8-8890-72f1f74750e0.png)

![image](https://user-images.githubusercontent.com/36734593/148464151-5545bd40-9916-4fd5-8b48-946ebe58b64b.png)


Next Steps:

1. Get the CI/CD process setup. Needs to be easy to run and use. Would use Jenkins as I am more familiar.  
2. Expand the testing coverage to include all high risk scenarios including different status codes for Endpoints. 
3. Expand the test coverage to include common scenarios not just high risk. 
4. Transition to a more robust Java / Selenium Combination for the Web Automation. 
