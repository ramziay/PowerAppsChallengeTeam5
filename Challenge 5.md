# Challenge 5: Add Automation to your app (Optional)

## Background

If you made it this far, Congrats! You're a **hero**🐱‍🏍

 Now that your request has been submitted, who will be receiving it?
 In this challenge, you'll set up a Power Automate approval flow for HR to review and accept these submissions.The flow will take the newly submitted request and send an email with the information to the HR and wait for the approval. Once Approved, an email will be sent to the Developer so they can add it in the app

## Challenge

For this last challenge, you'll be using the same environment working with Power Automate. Inside your solution in Power Apps studio, Add a new automated cloud flow, or alternatively you can head to the [Power Automate website](https://make.powerautomate.com/) and log in. Once you're in, make a new cloud automated flow and give it a name like 'HR Request Approval'. This flow should be able to send a message and wait for approval. Depending on that answer, decide what happens next; if HR approves, a message should automatically go to a developer telling them to add the requested type. After you've set everything up, test it out

🚨 **Important Note:** Select your username for the HR role and the Dev role so you will receive the emails in your inbox from power automate so you can approve or reject. This is to indicate for the attendees to type in the flow the email they are using to create the flow so they will receive the emails and they can test the flow correctly; typing any other email will result in an error in the flow and it will not function.


#### Hints

- Flow should be automatically trigerred when row is added in Dataverse
- You should use dynamic content to showcase the input of the user
- In the condition, use the dynamic content 'Outcome' from the approval step.
- If Approval outcome is not approved, terminate the flow
- Upon saving the flow, ignore the warning for 'Power Automate Approvals has not been installed for this environment...' and proceed to Test the flow
- When Testing, You can check the Approvals in the Approvals tab or in Outlook (Refresh the page if you do not see the approval request)

## Success Criteria

- The flow should send an email to the HR with the employee's request information
- If request is approved, an automated email will be sent to the developer with the required information to add the request to the problemType choices. If not approved, flow should terminate
- When testing the flow, it will take a while for the approval to start, make sure you are in the correct environment in power automate and keep refreshing your browser, or alternatively check your email  
- Present the Power Automate flow to your coach



## Prerequisties

#### - Complete Challenge 4 


## References
- [Cloud flows](https://learn.microsoft.com/en-us/power-platform/release-plan/2023wave1/power-automate/cloud-flows)
- [Create and test an approval workflow with Power Automate](https://learn.microsoft.com/en-us/power-automate/modern-approvals)
