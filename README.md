# SnapRecap-API-UI-Tests
This repository contains the comprehensive test suite for the SnapRecap application, covering both UI test cases and API testing.
UI Test Cases

The `SnapRecap_Test_Cases.xls` file contains structured test cases for the SnapRecap application, including:

* **Test Case ID:** Unique identifier for each test case.
* **Title/Description:** Brief summary of the test's objective.
* **Prerequisites:** Conditions that must be met before executing the test.
* **Steps:** Detailed steps to reproduce the test scenario.
* **Expected Result:** The anticipated outcome of the test.
* **Pass/Fail:** Record of whether the test passed or failed.
* **Comments:** Any additional notes or observations.

** How to Use:**

1. Open the `.xls` file using Microsoft Excel, Google Sheets, or any compatible spreadsheet software.
2. Review the existing test cases to understand the application's functionality.
3. Use the spreadsheet to track test execution and record results.

*** API Testing with Postman

The `SnapRecap.postman_collection.json` file includes API test cases for the following endpoints:

* **User Authentication (`/api/User/Authentication`):** Tests user login and token generation.
* **Create Recap (`/api/Recap/Create`):** Tests the creation of new recaps.
* **Get All Recaps (`/api/Recap/All`):** Tests retrieval of all recaps for a user.
* **Edit Recap (`/api/Recap/Edit`):** Tests updating existing recaps.
* **Delete Recap (`/api/Recap/Delete`):** Tests deleting recaps.

** How to Use the Postman Collection:**

1. **Import the Collection:**
   * Open Postman.
   * Click `File > Import` and select `SnapRecap.postman_collection.json`.

2. **Set Up Environment Variables:**
   * Create a Postman environment (e.g., "Development," "Testing").
   * Define environment variables for the base URL (`baseUrl`) and the authentication token (`token`).  The `baseUrl` should be your application's URL (e.g., `http://snaprecap-env.eba-cafzhs9x.eu-north-1.elasticbeanstalk.com`). The `token` will be obtained after successful authentication.

3. **Run API Tests:**
   * Select the appropriate environment.
   * Use the Postman Collection Runner to execute the entire collection or individual requests.
   * View responses and debug issues as needed.

*** Bug Reports ***

Bug reports identified during testing are documented in the `SnapRecap_Bug_Report.xls` file (or whatever your file name is). This file includes details such as:

* **Bug ID:** Unique identifier for each bug.
* **Test Case ID:** The associated test case that revealed the bug.
* **Priority:** The urgency of fixing the bug.
* **Severity:** The impact of the bug on the application.
* **Title:** A concise description of the bug.
* **Steps to Reproduce:** Detailed steps to replicate the bug.
* **Expected Result:** The correct behavior.
* **Actual Result:** The observed incorrect behavior.
