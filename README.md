## $\textcolor{blue}{\text{Joule Transactional Test Scripts}}$

![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/fa19742d-eb00-4471-bd89-2adfedd09b3b)



## **Joule Transactional Test Scripts**

## Guidance on Navigating the Use Cases

Now that you have completed the setup of Joule Co Pilot on your SuccessFactors Instance, it is now time for you to ensure all the Joule Use Cases are functioning properly in your environment. 

To facilitate through the testing, we have consolidated the Transactional Use Cases of Joule, each with a detailed description of the specific scenarios. As we continue to develop and deliver the new use cases, you can visit the Help Page for Transactional Use Cases of Joule for an exhaustive list of the delivered functionalities.

https://help.sap.com/docs/joule/capabilities-guide/transactional-use-cases 
 
Please note that for the use cases to function as intended, the following prerequisites must be met:
1.	The required product /module in SuccessFactors to be live, with data available. 
2.	The Employee Central Quick Actions to be configured for the specific scenario requested.
3.	The necessary Permissions for the User to be in place to access the data being requested.
4.	The Joule activation has been completed based on the Getting Started Guide 

https://d.dam.sap.com/a/rVgJwgV/Getting%20Started%20with%20Joule%20for%20SuccessFactors_ONB%20Deck.pdf

You can utilize this guide to review various scenarios and test them in your Test Instance before deploying Joule to the production instance. These test cases are instrumental in verifying the functionality and performance of Joule. You may click on the Table of Contents to directly visit the scenario you want to test. 

Furthermore, please don't hesitate to reach out to us at SAP_SuccessFactors_Joule_Activation@sap.com with your feedback and the copy of the filled in test script. Your input will aid us in understanding and addressing any issues that may arise, thereby contributing to the enhancement of the product. 

# Contents

1. [Approve spot award](#approve-spot-award)
2. [Create spot award](#create-spot-award)
3. [Approve and reject time-off requests](#approve-and-reject-time-off-requests)
4. [Approve Employee Central workflow requests](#approve-employee-central-workflow-requests)
5. [Change cost center](#change-cost-center)
6. [Change chosen name](#change-chosen-name)
7. [Change job](#change-job)
8. [Change legal name](#change-legal-name)
9. [Change location](#change-location)
10. [Change pronouns](#change-pronouns)
11. [Change working time](#change-working-time)
12. [Promotion](#promotion)
13. [Transfer](#transfer)
14. [View cost center](#view-cost-center)
15. [View job](#view-job)
16. [View legal name](#view-legal-name)
17. [View location](#view-location)
18. [View marital status](#view-marital-status)
19. [View birthday](#view-birthday)
20. [View department](#view-department)
21. [View division](#view-division)
22. [View direct manager](#view-direct-manager)
23. [View display name](#view-display-name)
24. [View direct reports](#view-direct-reports)
25. [View email](#view-email)
26. [View hire date](#view-hire-date)
27. [View job code](#view-job-code)
28. [View peers](#view-peers)
29. [Pronouns](#pronouns)
30. [View phone number](#view-phone-number)
31. [View team's hire dates](#view-teams-hire-dates)
32. [View title](#view-title)
33. [View timezone](#view-timezone)
34. [View worker](#view-worker)
35. [Clock in clock out](#clock-in-clock-out)

## Approve spot award

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "Approve spot award" into the query bar labeled "How can I assist you?"      |The following message is displayed alongside the most recent request. "I can only get you MDF workflow-related requests, which might include the spot award requests you're looking for. Let's start with the latest one." with options to Approve, Approve with Comments and Skip.| ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/9eeb2a41-273b-432f-b691-648690cdb598)|

# Create spot award

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "Create spot award" into the query bar labeled "How can I assist you?" | The prompt "Who do you want to Nominate" appears.|![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/8c6b4331-aa73-404b-a9c1-8e9ae87dcde1)
|Type in Employee Name) | Confirm the employee details. | ![image]![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/ec91c200-9e1d-4fa9-8578-c63ee938081e)|
|     |List of Awards is shown along with the message "Select one award program." |![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/efee181c-7f30-45f0-af71-61fc5dc9e342)|
| Select an award program. | The prompt "Leave a message for the award recipient." appears | ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/3ccb77ff-96ab-4585-abfa-6f015f6a4ad6)

| Type in a message. | The given spot award information is displayed with the options "Yes, send in" and "No." | ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/aa1c1145-d3ff-41da-8fef-d6ba4e8a09bd)|

# Approve and reject time-off requests

| Step| Expected Result | Screenshot |
|-----|-----------------|------------|
| Upon launching Joule, input "Approve and reject time-off requests" into the query bar labeled "How can I assist you?". | The pending requests for approval are listed alongside the options to either approve or decline them. |![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/371fa79c-8d6c-425f-b260-bc8ee2631ea3)|

# Approve Employee Central workflow requests.

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "Approve Employee central workflow" into the query bar labeled "How can I assist you?". | The message "No requests need your approval right now. Let's try something else" is displayed since there are no pending requests for approval.|![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/adfed341-e622-4f7c-9f12-8f358616b856)


# Change cost center

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "Change cost center" into the query bar labeled "How can I assist you?. | The prompt "Whose information do you want to change?" appears.| ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/3c3d0c25-cb75-4680-987b-a2c60f851f53)

| Type in Employee Name | Employee information is displayed. Press the "Select" button, triggering the message "When do you want the change to take effect". |![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/b1672f1c-c70b-4d44-be8b-ff497cb56d75)

| Choose between "Pick a date" or "Today" options. Date format should be yyyy-MM-dd, then proceed to Submit. |The current cost center value is displayed as: "Jada Baker's current Cost Center value is Product Management (US10_PROD). What is the updated value?" A list of new values is also provided alongside this information. |![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/0b96904b-98ee-4e18-b3a8-dadc00861a23)

| Choose one of the values, for instance, BestRun Comp and Benefits (US10_M7). | The chosen details are displayed once more, accompanied by two options: "Yes, please" and "No, discard changes". | ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/62fe75ee-274c-4602-a34d-079640602c2c)
 |

# Change chosen name

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "Change chosen name" into the query bar labelled "How can I assist you?". | The prompt "Whose information do you want to change?" appears. ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/d55ee7ee-b209-4ea7-b77f-18b248cc49c0)

| Type in Employee Name/Type in “mine” if you want to change your own data. | Employee information is displayed. Press the "Select" button, triggering the message "When do you want the change to take effect". | ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/51c5eb95-48e8-4b86-997a-2f5f8a59d64a)

| Choose between "Pick a date" or "Today" options. Date format should be yyyy-MM-dd, then proceed to Submit. | The Current details are displayed as "Ben Shervin 's current Preferred Name value is Ben. What's the new value? accompanied by 2 options "Leave it blank" and "Skip this step". |![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/c730d0f8-2ad3-49f0-9817-1eb2d27c6932)

| Type in the new value or choose between the options. |The updated details, along with the prompt "Would you like to submit your request?", are presented. Select between the options "Yes, please" and "No, discard changes" to finalize the process. |![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/7f95c4aa-4333-410b-9975-1b7e040b161a)


# Change job

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "Change job" into the query bar labeled "How can I assist you?". | The prompt "Whose information do you want to change?" appears.|![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/3f708660-6c12-4e89-b9e2-89e7581ddf94)

| Type in Employee Name / Type in “mine” if you want to change your own data.| Employee information is displayed. Press the "Select" button, triggering the message "When do you want the change to take effect". | ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/b5ee5891-c7c8-4124-98ed-3471e84de1d0)

| Choose between "Pick a date" or "Today" options. Date format should be yyyy-MM-dd, then proceed to Submit. | The current Job classification value is displayed as: "Ben Shervin 's current Job Classification value is Management & Planning (50070999). What's the new value?" A list of new values is also provided alongside this information. | ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/0cf68fbb-c55f-476e-8867-afd725535f46)

| Choose one of the values, for instance, Craft Workers (50071001). | A subsequent message appears requesting the "New Job Title Value," with the alternative option to "Skip this step. |![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/9871df56-e06a-4f3a-853c-88769e3ac623)

| Type the New job title value or skip the step. | By selecting "Skip this step," the revised details are once again displayed for confirmation. Choose either to proceed with "Yes, please" or to discard the changes with "No, discard changes. |![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/514caa70-5734-473a-a1c0-94e70013f65a)


# Change legal name

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "Change legal name" into the query bar labeled "How can I assist you?". | The prompt "Whose information do you want to change?" appears.|![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/8fca2bcb-4d94-48b3-bfc3-0e0cf485366f)

| Type in Employee Name Type in “mine” if you want to change your own data. | Employee information is displayed. Press the "Select" button, triggering the message "When do you want the change to take effect". | ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/3777c3d4-fefe-4f86-abd6-db18fd6eab12)

| Choose between "Pick a date" or "Today" options. Date format should be yyyy-MM-dd, then proceed to Submit. | A prompt is displayed requesting the new First Name value, stating "Jada Baker's current First Name value is Jada. What is the new value?" If no changes are necessary, an option to skip this step is provided.|![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/41409696-2a9c-4b5f-bc70-d23dbf0a7500)

|Type in the value or skip the step. | Right after, a prompt appears asking for the new middle name value, accompanied by an option to skip this step. | ![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/ba58237b-2ab3-48c0-8b94-b2c2ce499b59)

| Type in the value or skip the step. | A prompt is displayed requesting for the **new Last name value**, If no changes are necessary, an option to skip this step is provided.|![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/8888e281-536f-49ba-802a-10289ca0ddf3)
|The updated details starting from the provided effective date are displayed, along with the options to either proceed with the changes or discard them.| 

# Change location

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "Change location" into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to change?" appears.|![image](https://github.com/vishnu746206/Joule-AI/assets/166359300/4cc25991-f4c1-4bd5-bb7f-2028c0476ea5)

| Type in Employee Name/ Type in “mine” if you want to change your own data. |Employee information is displayed. Press the "Select" button, triggering the message "When do you want the change to take effect". | ![image](https://github.wdf.sap.corp/storage/user/139934/files/9a31d897-5478-42b5-9e9e-18607e51ca93)|
| Choose between "Pick a date" or "Today" options. Date format should be yyyy-mm-dd, then proceed to Submit.|A prompt is displayed requesting the new current location value, stating "Ben Shervin 's current Location value is Philadelphia (1710-2018). What's the new value?" A list of new values is also provided alongside this information.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/b7751547-f9fc-401b-806b-a4b1677bade4)|
| Choose one of the values, For Instance, Boston (1710-2017) | A prompt is displayed requesting the new Time zone value, stating "Ben Shervin 's current Timezone value is US/Eastern (GMT-04:00). What's the new value?" A list of new values is also provided alongside this information.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/3301143a-b080-485b-8734-a42f2277cdff)|
| Choose the right Timezone value.| The updated details starting from the provided effective date are displayed, along with the options to either proceed with the changes or discard them.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/9639c2cc-d960-42a7-939b-e503eab61b24) |

# Change pronouns

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "Change pronouns" into the query bar labeled "How can I assist you?" .|The Prompt "Your current Pronouns value is He/Him/His. What's your new value?" appears along with a list of new values.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/a7e3891f-6cf6-4868-a94a-5455240d438b)|
| Choose the new value | The chosen details are displayed, prompting whether to proceed and submit the request or discard the changes. | ![image](https://github.wdf.sap.corp/storage/user/139934/files/fbc4fd40-b404-4309-b496-d5bd3653f72d) |

# Change working time

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "Change working time" into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to change?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/552b163e-5316-4c89-a35f-7da5c0c3821a)|
|Type in Employee Name/ Type in “mine” if you want to change your own data.| Employee information is displayed. Press the "Select" button, triggering the message "When do you want the change to take effect". | ![image](https://github.wdf.sap.corp/storage/user/139934/files/69d9981d-bb47-4f91-96f5-0c859ad050ca)|
| Choose between "Pick a date" or "Today" options. Date format should be yyyy-MM-dd, then proceed to Submit.| A prompt is displayed requesting the new value stating "Jada Baker 's current Standard Weekly Hours value is 40. What's the new value?" along with the options to either "Leave it blank" or "Skip this step".|![image](https://github.wdf.sap.corp/storage/user/139934/files/9292a7fa-54ad-4805-a844-1b2e4e742ec9)|
| Type the value.  | The updated details starting from the provided effective date are displayed, along with the options to either proceed with the changes or discard them.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/d1f87f18-103a-4197-b61d-927713e4d710)|

# Promotion

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "Promotion" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to change?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/408a898f-6276-47e0-a5d1-8ea204f8aabe)|
| Choose between "Pick a date" or "Today" options. Date format should be yyyy-MM-dd, then proceed to Submit.|A prompt is displayed requesting the new value stating" Jada Baker 's current Job Classification value is Management & Planning (50070999). What's the new value?" A list of new values is also provided alongside this information.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/181672c9-4438-487e-9231-2e32cac8ecbf)|
| Choose one of the values, For Instance, Digital Expert (7000012).| The chosen details are displayed once more, accompanied by two options: "Yes, please" and "No, discard changes."|![image](https://github.wdf.sap.corp/storage/user/139934/files/327070f2-e0f5-49c6-a553-7334576606cd)|

# Transfer

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "Transfer" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to change?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/cf67ad59-a917-4da5-9652-2cc3be11f0aa)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.| Employee information is displayed. Press the "Select" button, triggering the message "When do you want the change to take effect".| ![image](https://github.wdf.sap.corp/storage/user/139934/files/b8d4d3a8-904c-49f1-a8d2-babdf7242126) |
| Choose between "Pick a date" or "Today" options. Date format should be yyyy-MM-dd, then proceed to Submit.|A prompt is displayed requesting the new value stating "Ben Shervin 's current Position value is Engineering Manager (50014349). What's the new value?" A list of newvalue?" A list of new values is also provided alongside this information.|![image](https://github.wdf.sap.corp/storage/user/139934/files/65d33174-9b90-4ca5-ad32-958e886baa9f) | 
|Choose one of the values, For Instance, Analyst (51710004). | The chosen details are displayed once more, accompanied by two options: "Yes, please" and "No, discard changes".| ![image](https://github.wdf.sap.corp/storage/user/139934/files/406c11b5-d33e-4512-bbf6-62a3c19115cb)|

# View cost center

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "View cost center" into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/5bdb12d8-b667-4964-9c7d-77ca9aa367bf)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.| The employee information is shown. Click the "Select" button to access the requested details.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/f7cfd295-a89f-44b0-9fc3-105bab5103b4)|

# View job

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "View job" into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/50c1b425-12d3-49f6-b174-21598a400c99) |
| Type in Employee Name/ Type in “mine” if you want to change your own data.| The employee information is shown. Click the "Select" button to access the requested details.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/f92a4648-237f-4baf-958d-3d291cbf1fee)|

# View legal name

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "View legal name into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/9bac35ea-ec29-4c32-8c1f-8b5e4d8e8439)|
|Type in Employee Name/ Type in “mine” if you want to change your own data.|The employee information is shown. Click the "Select" button to access the requested details.|![image](https://github.wdf.sap.corp/storage/user/139934/files/46f6d650-7326-4cf4-a931-3552bc6a6654)|

# View location

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "View location" into the query bar labelled "How can I assist you?".| The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/a410b824-d4dc-4889-9be0-9509b327903e)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.|The employee information is shown. Click the "Select" button to access the requested details.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/0e0615a8-8c77-4c16-84b3-a5aa8ee4fdcc)|

# View marital status

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View marital status" into the query bar labelled "How can I assist you?".|The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/369f7d90-1466-43d6-8684-cc5f1648bbda)|
|Type inEmployee Name/ Type in “mine” if you want to change your own data.| The employee information is shown. Click the "Select" button to access the requested details.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/6cfa0f61-3d87-4594-aa5c-2a945f427fbf)

# View birthday

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View birthday" into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/3c2c3816-98d1-407c-a8b0-202f1a3b6b15)| 
|Type in Employee Name/ Type in “mine” if you want to change your own data.| The requested information is displayed.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/5d8a774a-0c01-4ca4-8243-f5aed5ea67ed)|

# View department

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View department" into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/9146c807-679b-4323-9490-283482d5e9a5)| 
|Type in Employee Name/ Type in “mine” if you want to change your own data.|The requested information is displayed.|![image](https://github.wdf.sap.corp/storage/user/139934/files/337fd601-583c-481c-94d6-74cd2c0af2f4)|

# View division

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View division" into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/bef471db-5f7e-473c-aaca-f200ee380cbe)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.| The requested information is displayed.|![image](https://github.wdf.sap.corp/storage/user/139934/files/71783ddb-3d74-41f7-ae87-d27f2ceead0f)|

# View direct manager

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View direct manager" into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to view?" appears.|![image](https://github.wdf.sap.corp/storage/user/139934/files/87e04140-2d3f-4c51-9cb3-5af119262926)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.| The requested information is displayed.|![image](https://github.wdf.sap.corp/storage/user/139934/files/18eb8f0c-c7ec-4962-a770-6849139b75f4)|

# View display name

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View display name" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to view?" appears.|![image](https://github.wdf.sap.corp/storage/user/139934/files/6f55af6d-6794-4f69-afcc-2a61fe33c1f6)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.| The requested information is displayed.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/2dbed153-f7b3-421c-b909-3a9886ad0163)|

# View direct reports.

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
| Upon launching Joule, input "View direct reports" into the query bar labeled "How can I assist you?". |The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/623e2eb2-447c-4a36-b99f-ce22c311317c)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.| The list includes direct reports up to three individuals, accompanied by a "View more" option. Additionally, there's a notification stating, "To view more direct reports beyond 20, you can go to Org Chart page".| ![image](https://github.wdf.sap.corp/storage/user/139934/files/744190d1-bac3-4c8a-8455-47a9188b8da0)|

# View email

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View email" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/4cb495fa-6445-4cb1-9d2b-370bb71cef76)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.|The employee information is shown. Click the "Select" button to access the requested details.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/137a3159-c371-4aa3-b32e-6de0679b33c6)|

# View hire date

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View hire data" into the query bar labeled "How can I assist you?".| The prompt "Whose information do you want to view?" appears.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/69b958b8-a490-4fce-82c8-4a32acef9271)|
|Type in Employee Name/ Type in “mine” if you want to change your own data.|The requested information is displayed.|![image](https://github.wdf.sap.corp/storage/user/139934/files/fbe6c41a-0c50-4407-96e0-01898ac01a0c)|

# View job code

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View job code" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to view?" appears.|  ![image](https://github.wdf.sap.corp/storage/user/139934/files/b03cfc79-8d9d-407c-9f7a-80d4f1083903)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.|The employee information is shown. Click the "Select" button to access the requested details.|![image](https://github.wdf.sap.corp/storage/user/139934/files/b5f8fc5a-c17f-4577-aba7-8de7b01f99c6)|

# View peers

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View peers" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to view?" appears.|![image](https://github.wdf.sap.corp/storage/user/139934/files/de5d575d-537e-4fbe-ab26-108eac50e489)|
| Type in Employee Name/ Type in “mine” if you want to change your own data. | The list of peers is shown upto 3 individuals accompanied by a "View more" option.|![image](https://github.wdf.sap.corp/storage/user/139934/files/7bde6e74-21ee-41e0-a8b1-648ad7c083b1)|

# Pronouns

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View pronouns" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to view?" appears.|![image](https://github.wdf.sap.corp/storage/user/139934/files/7aa7331d-ef2f-4f6b-845b-18fe4b016bf1)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.|The requested information is displayed.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/32fa8429-99bd-4027-9dbb-285c354a81ac)|

# View phone number

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View phone number" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to view?" appears.| !|[image](https://github.wdf.sap.corp/storage/user/139934/files/d8a9802d-1311-4fa8-ae07-0f2cdfb5e7a5)|
|Type in Employee Name/ Type in “mine” if you want to change your own data.|The employee information is shown. Click the "Select" button to access the requested details.|![image](https://github.wdf.sap.corp/storage/user/139934/files/47fb890a-ccf0-4b2e-a465-a1f0678c3070)|

# View team’s hire dates

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View team's hire dates" into the query bar labeled "How can I assist you?".|The requested information is displayed for 3 individuals accompanied by "view more" option| ![image](https://github.wdf.sap.corp/storage/user/139934/files/e87c8768-b22e-4cda-a3c9-1678e63b0d73)|

# View title

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View title" into the query bar labeled "How can I assist you?.|The prompt "Whose information do you want to view?" appears.|![image](https://github.wdf.sap.corp/storage/user/139934/files/60cad375-8f4d-4b81-a910-8cadff3aa7fe)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.|The employee information is shown. Click the "Select" button to access the requested details.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/276af12a-f434-43fe-82ca-1aa0ed199281)|

# View timezone

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View timezone" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to view?" appears.|![image](https://github.wdf.sap.corp/storage/user/139934/files/6e69f1b8-49fd-45fb-9b24-f4d66ff1c7a5)|
|Type in Employee Name/ Type in “mine” if you want to change your own data.|The employee information is shown. Click the "Select" button to access the requested details.|![image](https://github.wdf.sap.corp/storage/user/139934/files/a879bb16-7a05-45e9-8831-ab23fc219423)|

# View worker

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "View worker" into the query bar labeled "How can I assist you?".|The prompt "Whose information do you want to view?" appears.|![image](https://github.wdf.sap.corp/storage/user/139934/files/0aba2907-9563-4f0f-9a01-e560761d5623)|
| Type in Employee Name/ Type in “mine” if you want to change your own data.| The requested information is shown.| ![image](https://github.wdf.sap.corp/storage/user/139934/files/5e6aea19-b1d2-46d1-8ee2-fd9c1a358d1c)|

# Clock in clock out

| Step                                                                                                     | Expected Result | Screenshot |
|----------------------------------------------------------------------------------------------------------|-----------------|--------|
|Upon launching Joule, input "Clock in clock out" into the query bar labeled "How can I assist you?".|The prompt "Which time event would you like to record?" appears.|![image](https://github.wdf.sap.corp/storage/user/139934/files/a14d9a74-3f3b-4646-ad53-55fdadb52600)|
| Select the option.|The event time is recorded.[And the same applies to Clock out as well]| ![image](https://github.wdf.sap.corp/storage/user/139934/files/f50c03a1-0f28-4cbb-98b3-e9b4af6e4ea3)|













