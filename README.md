API Test Automation - Postman Collection
This repository contains a professional Postman collection for the Automation Exercise API suite. The project covers the complete user account lifecycle and product/brand exploration, ensuring robust API reliability through automated test scripts.

🚀 Project Overview
The goal of this project was to automate 14+ API endpoints, focusing on both Positive and Negative testing scenarios. It includes automated assertions for status codes, response messages, and data integrity.

Key Features:
End-to-End User Flow: Automated registration, login, profile update, and data retrieval.

Dynamic Data Handling: Used Postman's built-in variables (e.g., {{$randomInt}}) to generate unique test data and avoid duplication errors.

Comprehensive Assertions: Custom JavaScript snippets to validate JSON response structures and business logic.

Negative Testing: Verified system behavior against missing parameters, invalid methods (405), and non-existent resources.

🛠️ Tech Stack
Tool: Postman

Scripting: JavaScript (Postman Sandbox)

Environment: Automation Exercise API

Runner: Postman Collection Runner / Newman

📋 API Endpoints Automated
Products: GET all products, POST to search products.

Brands: GET all brands, PUT to update (Negative).

User Account: * POST Create Account (with dynamic email handling)

PUT Update Account Details

GET Fetch User Details by Email

DELETE Account scenarios (Negative/Positive)

🚦 How to Run the Collection
To review and execute these tests locally:

Download/Clone this repository.

Open Postman.

Click on the Import button and select the Postman_Collection.json file.

Once imported, click on the Collection in the sidebar.

Click Run to open the Collection Runner.

Press Run Automation Exercise - Full Suite to see all tests passing.

📊 Test Results
All 14 APIs have been tested and verified.

Total Tests: 30+ Assertions

Success Rate: 100% Passed

💡 Author
Shahzar Ahmad Software Quality Assurance (SQA) | Frontend Developer
