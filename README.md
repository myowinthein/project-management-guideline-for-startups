# Acronym Explained
| Abbr | Meaning |
| ---- | ------- |
| CTO | Chief Technical Officer |
| PD | Project Director |
| PM | Project Manager |
| BD | Business Development |
| BA | Business Analyst |
| Dev | Developer |
| SA | System Administrator |
| UI | User Interface Developer |
| UX | User Experience Designer |
| QA | Quality Assurance |
| PMS | Project Management Software |

# 1st Stage - Submit Proposal to Potential Client

| Step | Responsibility | Action | Output |
| ---- | -------------- | ------ | ------ |
| 1 | BA | Collect project requirements and features from client | Overall features of each platform (e.g. web, mobile) |
| 2 | BA | Prepare use case diagrams, AC sheets, BRS, etc. | A bunch of documents to understand the business flow |
| 3 | CTO, PD, PM, BA | 1. Read the documents from BA <br/> 2. Plan resource allocation <br/> 3. Choose the lead developer <br/> 4. Discuss tech stacks | 1. Understanding of the project scope <br/> 2. A development team |
| 4 | UI, UX, Dev | 1. Timeline estimation <br/> 2. Submit timeline to BA & PM <br/> 3. Add buffer to timeline by PM | Overall estimated timeline of each platform |
| 5 | BD, PD, PM, BA | Calculate the estimated project cost based on timeline | Overall estimated cost |
| 6 | PM | 1. Submit documents from BA, CV of tech team members, project development procedure, tech stacks, estimated timeline and cost to client <br/> 2. Let the client know these are the initial estimations. The actual timeline and cost can be different based on upcoming changes | Wait for client decision |

# 2nd Stage - Client Agree the Proposal & Start Planning

| Step | Responsibility | Action | Output |
| ---- | -------------- | ------ | ------ |
| 1 | PM, BA | 1. Split the project by sprints <br/> 2. Add features by sprint in PMS (e.g. clickup, forcast) <br/> 3. Invite client to PMS | Wait for client decision |
| 2 | PM, BA, UI, UX, Dev, QA | 1. Disuss technical & business flow of each feature in PMS by sprints <br/> 2. BA to note down the questions to clarify with client <br/> 3. Set the version releases inside the sprint for client to test | 1. Understanding of each feature <br/> 2. List of questions to clarify with client <br/> 3. Version Releases |
| 3 | BA | 1. Send the questions & version releases to client <br/> 2. Once received the feedback, explained to tech team <br/> 3. Loop the process until there are no more questions left | Wait for client feedback |
| 4 | BA, PM | 1. Make changes to existing documents, diagrams & PMS based on client feedback <br/> 2. Send all to client | Update documents, diagrams & PMS |

> If there are out of scope features in feedbacks, check 4th stage

# 3rd Stage - UI/UX Kick Off

| Step | Responsibility | Action | Output |
| ---- | -------------- | ------ | ------ |
| 1 | UX | 1. Draw prototypes of each platform <br/> 2. Submit completed pages to PM and Dev to confirm techincal feasibility & make sure everything are in project scope | Link of hosted prototype (e.g. sketch, invision) |
| 2 | PM, Dev | 1. Check & remark on the screens provided by UX <br/> 2. Request meeting with UX if needed <br/> 3. Once done, submit all the feedbacks to UX | Feedback about prototype from technical & business perspective |
| 3 | UX | 1. Once received the feedback, make changes to prototype <br/> 2. Request meeting with PM & Dev if needed <br/> 3. Loop the process until there are no more feedbacks left | Link of updated prototype |
| 4 | PM | 1. Send prototype hosted link to client <br/> 2. Once received the feedback, discuss with UX for changes <br/> 3. Loop the process until the final prototype is released | Wait for client feedback |
| 5 | UI | 1. Generate web design template based on prototype <br/> 2. Submit completed pages to PM and Dev | Frontend codes in repository (e.g. gitlab) |

> If there are out of scope features in feedbacks, check 4th stage

# 4th Stage - Proposal for Additional Timeline & Cost

| Step | Responsibility | Action | Output |
| ---- | -------------- | ------ | ------ |
| 1| BA, PM | 1. Analyse all the changes & new features made by client <br/> 2. Prepare to request additional timeline & cost | Overview of the impact of feature changes |
| 2 | Dev, UX | 1. Timeline estimation <br/> 2. Submit timeline to BA & PM <br/> 3. Add buffer to timeline by PM | Estimated timeline of additional changes |
| 3 | BD, PD, PM, BA | Calculate the additional project cost based on timeline | Estimated cost for additional changes |
| 4 | PM, BA | Send the additional timeline & cost to client | Wait for client decision |

# 5th Stage - SA Kick Off

| Step | Responsibility | Action | Output |
| ---- | -------------- | ------ | ------ |
| 1 | CTO, PM, Dev, SA | 1. Discuss server architecture, hosting, domains, CI/CD, dockers, task automations, etc. <br/> 2. PM to assign SA about the tasks <br/> 3. SA to give credentials to tech team once done | 1. Staging & production servers <br/> 2. Domains with HTTPS <br/> 3. Servers (e.g. web, database, mail) <br/> 4. GitLab repository |
| 2 | Dev | 1. Dev to create an initial project in local & push code to hosting <br/> 2. Check everything SA did are working well `(some services can't be tested at that time)` <br/> 3. Once done, submit all the feedbacks to SA | A test result |
| 3 | SA | 1. Once received the feedback, make changes to servers <br/> 2. Loop the process until there are no more feedbacks left | A complete server setup |

# 6th Stage - Dev Kick Off


| Step | Responsibility | Action | Output |
| ---- | -------------- | ------ | ------ |
| 1 | Dev | 1. If project include API integration, arrange meeting to list all possible API <br/> 2. Discuss & take notes | 1. API listing with request, response & headers <br/> 2. API security plan |
| 2 | Dev | 1. Draw ER diagram <br/> 2. Set technical rules for tech team (e.g. git flow, code merge, code review plan) <br/> 3. Create API documentation (e.g. postman, swagger) <br/> 4. List third-party services to purchase <br/> 5. List things to research | A project development plan |
| 3 | QA | 1. Write test cases of each feature <br/> 2. Give that test case to Dev once done | A test scenario |
| 4 | PM, QA, Dev | 1. Explain the project management procedure <br/> 2. Explain the planned timeline <br/> 3. Explain the testing procedure <br/> 4. Start assigning & managing of the tasks | Understanding of the project management plan |
| 5 | Dev | 1. Once a version release is completed, upload to staging server <br/> 2. Submit the web domains & apps with login credentials to QA & PM | A staging server for internal testing |
| 6 | PM, QA | 1. Perform testing & note bugs, improvements, feature requests, etc. <br/> 2. Once done, submit all the feedbacks to Dev | A test result |
| 7 | Dev | 1. Once received the feedback, make changes to code <br/> 2. Loop the process until there are no more feedbacks left <br/> 3. Deploy changes to staging server | A staging server for external testing |
| 8 | PM | 1. Submit the web domains & apps with login credentials to client <br/> 2. Once received the feedback, discuss with Dev for changes <br/> 3. Loop the process until no more feedbacks left | Wait for client feedback |
| 9 | PM | If new features or changes requested during the development, follow these steps <br/> - Move all new features to end of the final sprint <br/> - Integrate changes of old features <br/> - Check 4th stage | A plan to manage the changes |

# 7th Stage - Project Completion

| Step | Responsibility | Action | Output |
| ---- | -------------- | ------ | ------ |
| 1 | All | 1. Give feedback on performance of each team members <br/> 2. List down the mistakes <br/> 3. Create plans to improve in coming projects | Lessons to learn |
| 2 | All | Nightout together or arrange team dinner | Improved team building |
