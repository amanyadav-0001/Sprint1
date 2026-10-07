# Adactin Hotel App – Manual Testing Test Artifacts

## Overview

This repository contains a manual testing workbook for the **Adactin Hotel App**.  
The workbook is organized to support the complete testing workflow from test planning and scenario creation through test execution, defect reporting, summary reporting, and requirements traceability.

**Test Plan ID:** `Adactin_Hotel_App_01`

## File

- `aman_manual.xlsx` — Main Excel workbook containing all manual testing artifacts.

## Workbook Structure

| Sheet | Purpose |
|---|---|
| `TestPlan` | Defines the overall test plan, scope, objectives, and planning information. |
| `TestScenario` | Contains functional test scenarios organized by module. |
| `TestCase` | Contains detailed test cases, steps, test data, expected/actual results, status, and bug IDs. |
| `DefectReport` | Records defects found during testing, including priority, severity, expected result, and actual result. |
| `SummaryReport` | Provides an overall summary of testing results and execution status. |
| `RTM` | Requirements Traceability Matrix used to map requirements to test coverage. |

## Testing Workflow

The workbook can be used in the following sequence:

1. Review the **TestPlan** to understand the testing scope and objectives.
2. Review or update **TestScenario** for the functional areas being tested.
3. Execute the detailed **TestCase** entries.
4. Record actual results and update the test status.
5. When a test fails, create or update the corresponding entry in **DefectReport**.
6. Use **SummaryReport** to review overall test execution and defect status.
7. Use **RTM** to verify that requirements have adequate test coverage.

## Test Case Execution

For each test case:

- Follow the listed **Test Steps**.
- Use the specified **Test Data**.
- Compare the application behavior with the **Expected Result**.
- Enter the observed behavior under **Actual Result**.
- Update **Status** (for example, Pass/Fail).
- Add the related **Bug ID** when a defect is identified.

## Defect Reporting

For failed test cases, the `DefectReport` sheet captures key defect information such as:

- Bug ID
- Test Case ID
- Module
- Priority
- Severity
- Expected Result
- Actual Result

This helps maintain traceability between failed test cases and reported defects.

## Requirements Traceability

The `RTM` sheet provides traceability between requirements and test coverage.  
It can be used to identify requirements that are covered, partially covered, or not covered by test cases.

## Reporting

The `SummaryReport` sheet is intended to provide a consolidated view of testing progress and results, making it easier to communicate the overall test status.

## Tools

- Microsoft Excel or another compatible spreadsheet application
- Manual testing of the Adactin Hotel App
- Test data and application environment as defined by the project

## Project Information

**Application:** Adactin Hotel App  
**Testing Type:** Manual Testing  
**Artifact Type:** Test Plan, Test Scenarios, Test Cases, Defect Report, Summary Report, and RTM

## Notes

Keep the workbook updated during test execution so that test results, defects, and traceability remain synchronized
