# SBSAutomationTests
1.	Mocha tests are under test->specs->sbsTests.js file
2.	Tests are run with command 'npx wdio run wdio.conf.js'. Both test cases are run in parallel in Chrome. Run config can be changed via wdio.conf.js 
3.	Pages (.js files) of front-end application are created in test->frontendPageObjects folder. Pages of ‘Get API’ are created in test->apiPages folder. Pages have class which contains getter fields (elements) and methods. Methods and fields of pages are called from tests via creating objects of page classes
4.	Install all the packages present in package.json file (Installing node.js is pre-requisite)
5.	Test data for front-end tests is in class that resides in test->TestData->frontendTestData.js file. Test data for API tests is in class that resides in test->TestData->apiTestData.js file. Test data is called from tests via creating objects of test data classes
6.	Front end Audio test not only validates what is there in the PDF but also validates progression of audio at various intervals
7.	I have reported results in default ‘Spec’ reporter although reporters such as HTML Reporter can also be used in the framework to create HTML reports. Screenshot of results after running both tests are attached in the email



 
 
 
