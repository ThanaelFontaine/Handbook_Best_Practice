# Automated Testing

## Introduction

Automated testing is the third topic we have chosen to cover in this handbook. We have identified 5 quality resources related to this topic and identified common themes among them. The following guidelines summarize the best practices for automated testing:

---
### Write tests early and often to ensure coverage and catch issues early in the development process.
Writing tests is a key feature in IT development, as a matter of fact there is a development methodology that is called TDD (Test Driven Development) that advocates creating tests before even coding so you are sure that your code is going to fulfill its purpose. But for some projects it is not possible to use TDD so instead of creating tests before coding we recommend creating them at the earliest stage possible to ensure that there is no useless function or any issues in any functions. 

### Use a variety of testing types, including unit, integration, and end-to-end testing, to ensure comprehensive coverage.
As you probably know there are a lot of different kinds of tests that have a purpose for example unit tests are good for single functions to tests that the output is the one expected etc. We recommend that you use different kinds of tests to ensure that your code has good coverage and also that every issue is covered because you might see issues with unit coverage that you won’t detect with end to end testing or the other way around. We also recommend that you make scenarios that simulate the action of a person using your applications if it is one. With scenarios you might be able to see a different behavior in your code that can help you find bugs before you push. 

### Use tools and frameworks to support testing, such as Selenium for web applications or Appium for mobile applications.
Software development must include testing, and automating repetitious testing chores and increasing efficiency can both be accomplished with the aid of tools and frameworks. Selenium is one of the most well-known and often used tools for web application testing. Programming languages supported by the open-source Selenium testing framework include Python, Java, C#, and Ruby. It is portable and compatible with a wide range of web browsers and operating systems, including Windows, Linux, macOS, Android, Firefox, and Solaris. Testers can construct automation tests utilizing Selenium's record and replay capability without having to learn programming languages.

Appium is a popular option for mobile application testing among developers and testers. It is an open-source framework that enables testing in a number of different programming languages, including Java, Python, Ruby, JavaScript, and C#, for the Android and iOS platforms. Appium is a flexible tool for mobile testing since it can automate testing for native, hybrid, and mobile web applications. Additionally, it includes cross-platform testing features that let testers create tests once and run them across several platforms and gadgets.

### Continuously monitor and evaluate test results to identify potential issues and areas for improvement.
For automated tests to be successful, it is essential to continuously monitor and evaluate test results in order to spot potential problems and areas for development. The Plan-Do-Check-Act (PDCA) cycle, which entails identifying possibilities for change, implementing the change on a small scale, using data to assess the effects of the change, and determining whether it made a difference, is one widely used approach for continuous improvement. Contrarily, continuous monitoring is a strategy in which a company continuously examines its IT infrastructure and networks in order to automatically identify security risks, performance concerns, or non-compliance issues. Organizations can find chances to increase productivity and effectiveness and continuously enhance current programs by utilizing program assessments. Hence, just like any other process that needs continual improvement, it is crucial to create continuous monitoring and assessment methods to find possible problems and opportunities for improvement in automated tests.


### Integrate testing into the development process as a standard practice, rather than as an afterthought.
For the development of high-quality software, it is essential to incorporate testing as a normal procedure. According to, when incorporating testing into the development process, the following three steps must be followed:

- Call internal meetings to discuss and review user histories.
- Provide the development team all of the current sprint's developed user history test cases.
- Before beginning any work, review the user history acceptance criteria.

In order to make sure that the various parts or units of a software project function as intended as a whole, integration testing is a crucial component of the testing process. This entails confirming that the software components, created by various programmers, function as expected when put together. Both a standard-based technique, where all components are in the same architectural domain, and a negative approach, which looks for instances where the standard is not being followed, can be used to approach integration testing. Making testing a crucial component of the development process allows software teams to spot problems early on, making the process more efficient and resulting in the delivery of high-quality software to users.

---
For further reading, we recommend the following resources:
1. "The Benefits of Automated Testing" by SmartBear
2. "Automated Testing: Types, Benefits, Tools and Frameworks" by Guru99
3. "The Importance of Automated Testing in Software Development" by Testim
4. "13 Best Test Automation Frameworks: The 2021 List" by Harish Rajora
---
Write by Quentin NICOLAS, José RODRIGUES and Maxime THIONG-KAY

Review by Thanael FONTAINE