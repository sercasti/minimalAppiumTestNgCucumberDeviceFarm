## AWS Device Farm Appium Cucumber Tests For Sample App

Sample Appium Cucumber tests for Android sample app that can be used on AWS Device Farm.

Instructions to package and run this test can be found [here.](https://aws.amazon.com/blogs/mobile/testing-mobile-apps-with-cucumber-and-appium-through-testng-on-aws-device-farm/)

This is a fork with some bug fixes and clean up from the original https://github.com/aws-samples/aws-device-farm-appium-cucumber-tests-for-sample-app/

To run this locally, remember to uncomment lines 85-89 on TestBase.java

To run this on DeviceFarm, just use mvn clean package -DskipTests and upload target/zip-with-dependencies.zip

## License

This library is licensed under the Apache 2.0 License. 