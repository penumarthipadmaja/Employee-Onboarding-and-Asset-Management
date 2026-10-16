# Employee Onboarding and Asset Management


## Project Overview
This project is a ServiceNow application developed to automate employee onboarding activities and IT asset management. It helps manage employee records, onboarding tasks, asset assignments, and asset returns using automation.

## Objectives
- Automate employee onboarding record creation.
- Manage onboarding tasks and their completion status.
- Track IT asset assignments and returns.
- Automatically update onboarding status when all required tasks are completed.

## Technologies Used
- ServiceNow Studio
- Flow Designer
- Business Rules
- JavaScript
- GlideRecord

## Tables Created
1. **Employee** – Stores employee details and onboarding status.
2. **Asset** – Stores asset information, assignment details, and return status.
3. **Onboarding** – Tracks onboarding progress and overall status.
4. **Onboarding Task** – Manages individual onboarding tasks and their completion.

## Key Features
- Automatically creates onboarding and asset records through Flow Designer.
- Creates and manages onboarding tasks.
- Updates task status when the Work Completed checkbox is selected.
- Automatically updates onboarding status to Completed when all four onboarding tasks are completed.
- Updates asset status when an asset is assigned or returned.

## Onboarding Tasks
The application manages the following four tasks:
1. HR Verification
2. IT Setup
3. Asset Assignment
4. Employee Orientation

## Testing
The application was tested by creating employee records, verifying automatic onboarding and asset record creation, completing all four onboarding tasks, and checking the resulting onboarding and asset statuses.



## Conclusion
The Employee Onboarding and Asset Management project demonstrates how ServiceNow can be used to simplify and automate employee onboarding processes and IT asset management. By implementing Flow Designer and Business Rules, the application automates record creation, manages onboarding tasks, updates onboarding status when all required tasks are completed, and tracks asset assignments and returns. This project provided practical experience in ServiceNow application development, workflow automation, table relationships, and server-side scripting.

