Testing Project for Magento Demo Store
The scope of the final project for the ITF Manual Testing Course is to use all the gained knowledge throughout the course and apply it in practice, using a live application.
Application under test: Magento Demo Store
Tools used: Jira, Zephyr Squad
________________________________________
Functional Specifications
The below story describes the functional specifications of the "User Registration and Shopping" module, for which the final project is performed upon.
________________________________________
Testing Process
The test process was performed based on the standard test process as described below.
1.1 Test Planning
The Test Plan is designed to describe all details of testing for all the modules from the Magento Demo Store application.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.
1.1.1 Roles Assigned to the Project and Persons Allocated
•	Project Manager: Alin Suceveanu
•	Product Owner: Mircea Alecu
•	Software Developer: Mihnea Ion
•	QA Engineer: Tudor Itu
1.1.2 Entry Criteria Defined
•	Access to the Magento Demo Store website
•	User stories and acceptance criteria finalized
•	Test environment set up and configured
•	Required tools and access to Jira and Zephyr Squad
•	All dependencies (third-party APIs, databases) available and stable
1.1.3 Exit Criteria Defined
•	All planned test cases executed
•	All critical and major bugs resolved
•	No open blockers or critical bugs
•	Successful regression testing completed
•	Test coverage meets the defined threshold
1.1.4 Test Scope
Tests in Scope:
•	Functional Testing: User Registration, Login, Product Search, Add to Cart, Checkout, Payment Processing
•	UI Testing: Verification of UI elements' alignment, responsiveness, and consistency
•	Cross-Browser Testing: Testing on Chrome, Firefox, Safari, and Edge
•	Mobile Testing: Testing on iOS and Android devices
•	Security Testing: Basic security checks for user data protection
Tests Not in Scope:
•	Performance Testing: Not covered due to lack of suitable environment and tools
•	Accessibility Testing: Not specifically tested due to time constraints
•	Load Testing: Out of scope for this phase
1.1.5 Risks Detected
Project Risks:
•	Delays in test environment setup
•	Limited access to mobile devices for testing
Product Risks:
•	Potential security vulnerabilities due to lack of comprehensive security testing
•	Inconsistent UI behavior across different browsers
1.1.6 Evaluating Entry Criteria
The entry criteria defined in the Test Planning phase have been achieved, and the test process can continue.
________________________________________
1.2 Test Monitoring and Control
The monitoring and control process was implemented to ensure the test progress and quality were aligned with the plan. The test status report from Zephyr Squad reflects the activity and progress of testing, updated daily.
 
1.3 Test Analysis
The testing process was executed based on the application requirements. The requirements analysis was done in order to implement the early testing test principle.
The following test conditions were found:
•	User Registration
•	Login and Logout
•	Product Search and Filter
•	Adding Products to Cart
•	Checkout Process
•	Payment Processing
•	Order History and Details
1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications.
1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:
•	Test environment setup and configuration
•	Test data preparation
•	Accessibility to required tools and applications
•	Test case review and finalization
1.6 Test Execution
Test cases are executed in the created test Cycle summary: Cycle 1 - User Registration and Shopping Flow
Bugs have been created based on the failed tests. The complete bug reports can be found here.
Summary of Bugs Found:
•	Bug 001: Registration form not accepting valid email format (Priority: High, Severity: Critical)
•	Bug 002: Product images not loading on Firefox (Priority: Medium, Severity: Major)
•	Bug 003: Checkout button not responsive on mobile view (Priority: High, Severity: Major)
Full regression testing is needed on the impacted areas after the bugs are fixed, and retesting will be done for every functionality that was previously failed.
1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.
Test Execution Chart:
