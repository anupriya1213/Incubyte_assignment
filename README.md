# Gmail Compose Functionality - QA Assessment
## Project Overview
This repository contains the manual test documentation for the Gmail Compose functionality. The objective of this assessment is to verify that a user can successfully draft and send an email with specific data requirements, while also handling potential user errors.

Test Data Requirements:
Subject: Incubyte
Body: QA test for Incubyte

## Deliverables
The assessment is structured into three main components:

1. Traditional Test Cases: A detailed set of step-by-step instructions, including preconditions and expected results.

2. BDD (Behavior Driven Development): Gherkin-style scenarios (Given, When, Then) to bridge the gap between business requirements and technical testing.

3. Excel Documentation: A formatted spreadsheet containing both positive and negative test scenarios.

## Repository Structure
```text
.
├── README.md # Project documentation
├── test-cases/
│   └── Gmail_Compose_Test_Cases.xlsx # Main Excel deliverable
└── features/
    └── gmail_compose.feature # BDD Gherkin scenarios
```

## Scenarios Covered
1. Positive Testing<br>
a. Successful Dispatch: Verifying the email reaches the "Sent" folder when all fields are valid.<br>
b. Draft Persistence: Ensuring the "Incubyte" test data is saved automatically if the window is closed.<br>

2. Negative Testing<br>
a. Empty Recipient: Ensuring the system prevents sending when the "To" field is blank.<br>
b. Invalid Recipient Format: Testing the system's resilience against improperly formatted email addresses.<br>

## How to Review
1. Excel Sheet: Navigate to the /test-cases/ folder and download Gmail_Compose_Test_Cases.xlsx. This contains the full traceability matrix.
2. BDD Scenarios: Open /features/gmail_compose.feature to see how the requirements translate into behavioral scenarios suitable for automation.

## Author
Name: Annupriya Singh<br>
Role: QA Engineering Candidate<br>
Submission Date: June 15, 2026<br>

Prepared for the Incubyte QA Assessment.
