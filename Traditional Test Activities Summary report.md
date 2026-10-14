# Test Activities Summary \- BRQ100 WM Loan App Enhancement \[Sample\]

## Test Progress Report

This monitoring report is to show the progress of the on-going test activities, whether the Unit Testing and SIT execution is on-track or lag-behind.

| **Test Cycle** | Unit Testing, SIT |
| --- | --- |
| **Test Execute Date** | 22-Sep-2026 to 26-Sep-2026 |
| **Test Cases** | **11 issues ** |
| **Status** | HEALTHY |


This is a simple matrix for test cases (**“Key“**) mapping to corresponding requirements / stories (**“Linked Issues“**).


| **Key** | **Summary** | **Type** | **Linked Issues** |
| --- | --- | --- | --- |
| TestCase-001 | \[WM-2026Q3\] WM\_LoanApp\_Unit\_Test\_Cases | Test | Task-123, Task-124 |
| TestCase-002 | \[WM-2026Q3\] WM\_LoanApp\_BRQ100\_SecureLoan\_DataValidation | Test | Task-123, Task-124 |
| TestCase-003 | \[WM-2026Q3\] WM\_LoanApp\_BRQ100\_LoanTypes\_DataValidation | Test | Task-123, Task-124 |
| … | … | Test | … |
| TestCase-011 | \[WM-2026Q3\] WM\_LoanApp\_BRQ100\_LoanForm\_Visualisation | Test | Task-123 |


**Timeline chart **- to show the trends of actual no. of test case execution and the planned number of test case execution per day in test cycle
<img width="871" height="438" alt="image" src="https://github.com/user-attachments/assets/72a0293b-41c7-4886-918e-4939f34c27ab" />

| **Test Cycle** | **Test Execution Date** | **TCs to complete per day (plan)** | **Accumulated no. of TCs (plan)** | **TCs to complete per day (actual)** | **Accumulated no. of TCs (actual)** |
| --- | --- | --- | --- | --- | --- |
| UAT Testing | 22/09/26 | 2 | 2 | 1 | 1 |
|  | 23/09/2026 | 2 | 4 | 2 | 3 |
|  | 24/09/2026 | 2 | 6 | 1 | 4 |
|  | 25/09/2026 | 2 | 8 | 3 | 7 |
|  | 26/09/2026 | 3 | 11 |  |  |

Remarks: Timeline chart shows the accumulated figures in the table columns - 'Accumulated no. of TCs (plan)' and 'Accumulated no. of TCs (actual)', which are manually updated during test cycles.


**Test execution burndown chart** - to show the estimated end date to complete all outstanding test cases
<img width="432" height="489" alt="image" src="https://github.com/user-attachments/assets/c5b5d47f-370e-4e0c-b554-e4a073e6917e" />

Remark: The burndown chart is the JIRA built-in chart, and refers to the test executions under the test cycles. 


## Test Execution Log
Highlights: 
- The UAT Testing plans to start on 22-Sep-2026

| **Log Date** | **Description** | **Info / Issue** | **Logged By** | **Resolutions (if any)** | **Log Status** |
| --- | --- | --- | --- | --- | --- |
| 22-Sep | IT team provided xxx as test evidence, …. | Info | Donald\_QA | Nil | Closed |
| 23-Sep | With the secured loan process documents, …. | Issue | Donald\_QA | Pending re-test | Open |
| … | …. | Info | Bob\_BU | Nil | Closed |
| 25-Sep | The test case has been executed. No defect found, … - **\[WM-2026Q3\] WM\_MergedKPI\_BRQ100\_LoanForm\_Visualisation** | Info | Donald\_QA | Nil | Closed |
| 26-Sep |  |  |  |  |  |

- This is to show the up-to-dated status of each test case execution in Test Cycles. Execution “defect“/”query” will be tagged also in each Test Execution in the list.

| **Cycle Name** | **Test Summary** | **Priority** | **Version** | **Execution Status** | **Executed By** | **Execution On** | **Execution Defect(s)** | **Issue Key** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Unit Testing | \[WM-2026Q3\] WM\_LoanApp\_Unit\_Test\_Cases | Medium | Version V26.3 | PASS | Charlie\_Dev | 18-Sep |  | TestCase-001 |
| SIT Execution | \[WM-2026Q3\] WM\_LoanApp\_BRQ100\_SecureLoan\_DataValidation | Medium | Version V26.3 | PASS | Donald\_QA | 22-Sep |  | TestCase-002 |
| SIT Execution | \[WM-2026Q3\] WM\_LoanApp\_BRQ100\_LoanTypes\_DataValidation | High | Version V26.3 | PASS | Donald\_QA | 22-Sep |  | TestCase-003 |
| SIT Execution | … | … | Version V26.3 | … | … | … | … | … |
| SIT Execution | \[WM-2026Q3\] WM\_LoanApp\_BRQ100\_LoanForm\_Visualisation | Medium | Version V26.3 | UNEXECUTED | Donald\_QA |  |  | TestCase-011 |


- Upon SIT completion,  a SIT test execution detail with the test results (*{to attach SIT Test Execution result and evidence.xlsx}*, in MS Excel format) is attached for reference.

Remarks : The detail of the “Defect” or “Query” in Test Execution is showing in “Defect / Query Log” section below. This section may not be shown in the pdf export file.

## Defect / Query Log
| **Defect ID** | **Summary** | **Status** | **Tests Affected** |
| --- | --- | --- | --- |
| Defect-032 | \[WM-2026Q3\] Change reason code in Loan application in wrong configuration | Open | 1 |

The traceability report of Defect/Query to corresponding requirements/improvements is capture on \<SIT completion date\> upon the  completion of SIT cycle.

- *{to attach defect-to-requirement-traceability-report.xlsx}*


## Overall Release Activities 
Summary of project activities for the business requirement - BRQ100 WM Loan App enhancement in Test Cycles

| **Key** | **Summary** | **Due** | **Assignee** | **Priority** | **Status** | **Resolution** | **Sprint** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Task-100 | Requirement Deck Preparation |  | Bob\_BU | High | **Closed** | Done | WM 2026Q3 Sprint 1 |
| Task-101 | SIT Activity Planning |  | Donald\_QA | High | **Closed** | Done | WM 2026Q3 Sprint 2 |
| Task-102 | TC / TM Preparation |  | Donald\_QA | High | **Closed** | Done | WM 2026Q3 Sprint 2 |
| Task-103 | Loan App development |  | Charlie\_Dev | High | **Closed** | Done | WM 2026Q3 Sprint 2 |
| … | … | … |  | … | … | … | … |
| Task-123 | SIT Testing | Sep 22 2026 | Donald\_QA | High | **Open** | - | WM 2026Q3 Sprint 3 |
| Task-124 | SIT Test Result Playback (Demonstration) | Sep 27 2026 | Donald\_QA | High | **Open** | - | WM 2026Q3 Sprint 4 |
| … | … | … | … | … | … | … | … |
