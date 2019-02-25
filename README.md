# Azure Databricks workshop

Please refer to README.docx to get started with the workshop

Tools for setting up your own Databricks Workspace are available in the DBXWOrkspaceSetup folder - including DBC files (Databricks Archive Files) and Powershell Scripts. ___THESE TOOLS ARE ALPHA RELEASE.___

Sample Agenda for the day:
-	8am-9am registration, get customer set up on the lab as they come in.
-	9am-10am – Azure Databricks Overview – PPT provided on the Team Site – “Azure Databricks – Overview.”
-	10am-10:30am – Azure Databricks Demo 
-	10:30-10:45am – Break 
-	10:45am-Noon – Lab – Use the “Azure Databricks HOL Technical Trainer walk through” video to train your partner team.  
-	Noon-1pm - Lunch 
-	1pm-3:30pm – Lab 
-	3:30pm – End of day wrap up 

- Lab Set Up – Your team will be responsible for setting up your own Azure Databricks lab environment.  We have posted the lab to GitHub.  Below are instruction on lab set up.  

- The Github repository for the workshops (be sure to use the README file): https://github.com/jakeatmsft/adb-fsi-workshop

Requirements:
-	An Azure tenant where you can create demo users:
   -	Typically, we will want to conduct these in the Client tenant, which will require sufficient rights to setup the resources and administer the users.  Please coordinate with client Azure Administrator for this step.  
   - Alternatively, you can register a domain name and associate that with the tenant (to make the username easier, eg. Azureworkshops.net instead of azureworkshops.onmicrosoft.com).
-	An Azure subscription in that tenant where costs can be sent.
-	Databricks Premium Workspace created in that tenant.

Instructions:
-	To create new users within your tenant, you can use the NewDBXAccountSetup.ps1 script – which will create them.
-	To set up clusters and groups within Azure Databricks, you can import Administration.dbc into your workspace and manually create a 0 worker node cluster to run the notebooks.

Thank you and please let us know if you are able to leverage these assets!
