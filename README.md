# Test Cases

## Overview

This repository contains test cases designed to verify that the application works as expected. The test cases cover different scenarios,
including valid inputs, invalid inputs, edge cases, and expected system behavior.

## Objectives

* Verify that each feature works according to its requirements.
* Identify defects and unexpected behavior.
* Validate both positive and negative scenarios.
* Ensure edge cases are handled correctly.
* Provide a clear and repeatable testing process.

## Test Case Structure

Each test case should include:

| Field               | Description                               |
| ------------------- | ----------------------------------------- |
| **Test Case ID**    | Unique identifier for the test case       |
| **Test Case Name**  | Short description of what is being tested |
| **Preconditions**   | Requirements before executing the test    |
| **Test Steps**      | Actions required to perform the test      |
| **Test Data**       | Input values used during testing          |
| **Expected Result** | Result that should occur                  |
| **Actual Result**   | Result observed during execution          |
| **Status**          | Pass, Fail, or Blocked                    |

## Test Case Categories

### 1. Positive Test Cases

Verify that the system behaves correctly when valid inputs are provided.

### 2. Negative Test Cases

Verify that the system properly handles invalid or unexpected inputs.

### 3. Boundary Test Cases

Test minimum, maximum, and boundary values to identify edge-case issues.

### 4. Functional Test Cases

Verify that individual features perform their intended functions.

### 5. Regression Test Cases

Ensure that previously working functionality continues to work after changes.

## Example

**Test Case ID:** TC-001
**Test Case Name:** Verify valid user login

**Preconditions:**

* A registered user account exists.
* The login page is accessible.

**Steps:**

1. Open the login page.
2. Enter a valid username.
3. Enter the correct password.
4. Click **Login**.

**Expected Result:**
The user should be successfully authenticated and redirected to the appropriate page.

**Status:** Pass

## Test Execution

Before marking a test case as complete:

1. Verify the required preconditions.
2. Execute all defined test steps.
3. Compare the actual result with the expected result.
4. Record the test result and status.
5. Report any failures with relevant details.

## Status Definitions

* **Pass** — Expected behavior was observed.
* **Fail** — Actual behavior differs from the expected result.
* **Blocked** — Testing cannot continue because of a dependency or issue.
* **Not Run** — The test case has not yet been executed.
