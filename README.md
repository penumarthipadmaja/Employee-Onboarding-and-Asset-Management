# Employee Onboarding and Asset Management

## 1. Project Overview
This project is developed using ServiceNow to automate employee onboarding, onboarding task tracking, asset assignment, and asset return processes.

## 2. Objectives
- Automate onboarding record creation.
- Track employee onboarding tasks.
- Automate asset assignment.
- Update onboarding status when all required tasks are completed.
- Manage asset return status.

## 3. Technologies Used
- ServiceNow Studio
- Flow Designer
- Business Rules
- JavaScript
- GlideRecord API
- GitHub

## 4. Tables Created
1. Employee
2. Asset
3. Onboarding
4. Onboarding Task

## 5. Onboarding Tasks
The project tracks four onboarding tasks:
- HR Verification
- IT Setup
- Asset Assignment
- Employee Orientation

## 6. Automation
### Employee Onboarding Automation
Creates the related onboarding record when a new employee record is created.

### Asset Automation
Creates and assigns an asset through the configured automation.

### Onboarding Task Automation
Creates and tracks onboarding tasks for the employee.

### Task Completion Business Rule
Updates a task's status when its Work Completed checkbox is selected.

### Onboarding Completion Business Rule
When all four related tasks are completed, updates the HR Verification, IT Setup, Asset Assignment, and overall Status fields in the Onboarding table.

### Asset Return Automation
Updates the asset status to Returned when the return process is completed.

## 7. Testing
The following scenarios have been tested:
- Employee record creation
- Automatic onboarding record creation
- Asset record creation and assignment
- Creation of all four onboarding tasks
- Automatic onboarding field and status updates
- Asset return status update

## 8. Project Screenshots
Screenshots demonstrating the tables, automation, and successful test results will be added here.

## 9. Project Status
Core project development and automation testing are complete. Final screenshots, documentation, and demo preparation are in progress.

## 10. Conclusion
This project demonstrates how ServiceNow Flow Designer, Business Rules, and GlideRecord can be used to automate employee onboarding and asset management workflows.

