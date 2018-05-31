# **VA Micropurchases**
This is the GitHub repository for VA's micropurchases primarily supporting VA's API platform.  In this repo we will seek feedback on draft microconsulting work statements and solicit microconsulting RFQs.

## Workflow 

Awarding a new microconsulting engagement:

- To release a new work statement, VA will create an issue in this repository. The solicitation period opens when the issue is created. 
- When the solicitation period closes, VA will comment on the issue saying that the solicitation period has closed.  The issue will be left open until the award is made. 
- When the award is made, VA will comment on the issue saying that the award has been made and which company it has been awarded to.  
- At this time a directory will be created in the repository named `yyyy-mm-dd_NAME_OF_WORK_STATEMENT`, where `yyyy-mm-dd` is the date that the award was made (so that they will be shown in order) and `NAME_OF_WORK_STATEMENT` is the name of the work statement so that it's easy to understand what is in each directory. 
- Inside this directory, a `README.md` file will have the final work statement for reference, including who won the award and how much it was for. An empty directory called `deliverables` will also be created. 
- In a comment in the issue, VA will link to this `README.md` file for future reference then close the issue and the award is complete. 


For a vendor to submit a deliverable and VA to accept the deliverable:

- To submit their final deliverables, vendors should fork the `department-of-veterans-affairs/VA-Micropurchase-Repo` repository then create a pull request back to the master branch of the `department-of-veterans-affairs/VA-Micropurchase-Repo` repository with the deliverables added in `yyyy-mm-dd_NAME_OF_WORK_STATEMENT/deliverables`.
- VA will then review the deliverables, and if they approve them, they will merge them.  
- This merge is the trigger that VA has accepted the final deliverables and payment should be issued to the vendor. 
- All deliverables following this process will be open source. Any deliverable not intended to be viewed publicly will be specified in the solicitation and will follow a different process. 

