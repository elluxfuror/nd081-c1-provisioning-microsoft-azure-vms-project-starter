# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I chose App Service to host my app to address the following:
    - Cost
        In general it is cheaper to use App Service over VMS
    - Scalability
        Both App Service and VMs can scale quickly and efficiently
    - Availability
        For this app, I knew I wouldn't have to worry about availability for either VM or App Service
    - Workflow
        Workflow was a large reason I chose App Service over VM. I wanted to utilize git commands for managing version control as well as deployment. Git made this workflow manageable and enjoyable.