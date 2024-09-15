
# Atomation testing of Amazon website 

Automation testing is a critical component in maintaining the robustness and reliability of the Amazon 
website, essential in the competitive e-commerce sector. This process leverages automated scripts to 
systematically verify the functionality, performance, and security of the platform across a wide array 
of devices and browsers. By integrating continuous integration and deployment practices, automation 
testing significantly accelerates the development lifecycle, reduces human error, and ensures 
consistency in testing. This approach enables the swift identification and resolution of issues, thereby 
minimizing downtime and enhancing customer satisfaction through a stable and responsive user 
experience. 



## Overview
The automation testing project for the Amazon website aims to ensure key functionalities, such as user 
registration, login, product search, product details, cart management, checkout, and user profile, work 
seamlessly. By leveraging tools like Selenium, Cypress, and Playwright, the project will automate test 
cases and integrate them into a CI/CD pipeline using Jenkins or GitHub Actions. The testing scope 
includes functional, performance, security, and usability testing, addressing challenges like dynamic 
content and cross-browser compatibility through dynamic locators and tools like BrowserStack. Detailed 
test reports, dashboards, and alerts will be used for monitoring, with the team consisting of test automation 
engineers, QA analysts, DevOps engineers, and a project manager ensuring timely and efficient testing. 
## Objectives
1. Functional Testing: Validate all features to ensure they meet specified requirements and operate 
flawlessly under various scenarios. 

2. Compatibility Testing: Verify compatibility across major web browsers (including Chrome, 
Firefox, Safari, and Edge) and across different devices (desktops, laptops, tablets, and mobile 
phones). 

3. Performance Testing: Evaluate response times, loading speeds, and overall system performance 
to ensure optimal user experience under normal and peak traffic conditions. 

4. Security Testing: Identify potential vulnerabilities, conduct penetration testing, and ensure robust 
security measures are implemented to protect user data and maintain the integrity of the platform. 

5. Usability Testing: Assess the overall usability of the interface, evaluate navigation flow, and 
ensure intuitive interaction design to enhance user satisfaction and engagement. 

## Approaches
 Phase 1: Planning and Test Strategy Development Define testing objectives, establish testing 
environments, and outline test execution timelines. 

 Phase 2: Test Case Creation and Documentation Develop detailed test cases based on 
functional requirements and user scenarios 

 Phase 3: Test Execution and Bug Reporting Execute tests systematically, record results, and 
prioritize bug reporting based on severity. 

 Phase 4: Analysis and Reporting Analyse test findings, generate comprehensive reports, and 
present findings to stakeholders for review and decision-making. 


## Test Cases
Test Case : Login 
Objective: Verify that users can successfully login into Amazon Website. 

Preconditions:
1. Access to the Amazon Website. 
2. All the fields should be filled in order to login a user successfully.

Test Steps:
1. Open the login page of Amazon website. 
2. Inspect the login webpage by right clicking on it. 
3. Check the attributes in the console section. 
4. Executing the test case by copying the respective attributes and sending it the tool for automation 

testing. 
Expected Results:
 The user is successfully logged into Amazon Website. 

Post-conditions:
 The page should redirect after login to home page. 
 Options such as home, search, sidebar on the left side of the redirected page. 

Test Case : Product Search 
Objective: Verify the product is searched by the respective details. 

Preconditions:
1. Access to the Amazon Website. 
2. Logged into a valid user account. 

Test Steps:
1. In the home page clicking on the search option 
2. Entering of product name or details. 
3. Entering it to find a set of products based on searched name or item.

Expected Results:
 The page is redirected to the search page and successfully enters data, and after data is entered it 
successfully searches product. 

Test Case : Product Details
Objective: Verify the product information is accuracy. 

Preconditions: 
1. Access to the Amazon Website. 
2. Logged into a valid user account. 

Test Steps: 
1. After entering the product name wait for the page to redirect to the product page. 
2. When it reaches to the product page it navigates to the product description or details section. 

Expected Results:
 The page is redirected to product page after searching successful and then it validates the 
product details and reviews.

Test Case : Cart Management 
Objective: Verify that product is added to cart successfully. 

Preconditions:
1. Access to the Amazon Website. 
2. Logged into a valid user account successfully. 

Test Steps:
1. After verifying the product details wait for the page to redirect to the adding the product 
into cart. 
2. Validate the process from cart to payment completion. 
3. Test different payment methods (credit card, PayPal, etc.). 

Expected Results:
 After the product is added to cart and selecting the payment mode and address the product 
is ordered for the user. 

Test Case : User Profile 

Objective: Verify the User profile information. 

Preconditions:
1. Access to the Amazon Website. 
2. Logged into a valid user account successfully. 

Test Steps:
1. After the order is completed and redirecting to the user profile page. 
2. View and edit user profile information. 
3. Verify order history and tracking. 

Expected Results:
1. The page is redirected to user profile page and verifying the user details and order details.
