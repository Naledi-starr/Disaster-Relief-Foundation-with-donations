An ASP.NET Core Web Application using Azure SQL Server.
1. Users must log in securely to the web application to be able to edit information.
2. The web application must allow authorised users to capture new monetary donations. The 
date and amount are mandatory, but the donor may decide to remain anonymous.
3. The web application must allow authorised users to capture new goods donations. The 
date, number of items, category, and description of each item are mandatory. But the 
donor may decide to remain anonymous.
4. The web application must be pre-configured with the following categories of goods:
  a. Clothes
  b. Non-perishable foods
5. The web application must allow authorised users to define new categories of goods.
6. The web application must allow authorised users to capture a new disaster. The data for a 
disaster includes the start date and end date, the location, and a description. It must also 
be possible to specify the required aid types, for example, water provision, clothing, food, 
etc.
7. The web application must allow authorised users to view the following lists:
  a. All incoming monetary donations.
  b. All incoming goods donations.
  c. All disasters.
8. The web application must allow authorised users to allocate money or goods to active disaster.
9. The web application must allow authorised users to capture the purchase of goods using 
available money. This means that the available money decreases, and the goods are added 
to the inventory of available goods and allocated to a specific disaster.
10. The web application must have a publicly accessible page that shows the following 
information (PoE only):
  a. Total monetary donations received
  b. Total number of goods received
  c. Currently active disasters, with the money and goods allocated to the disaster
11. Add unit tests to any logic in the code.
12. As you build the various features, update the work items in Azure Boards to reflect your progress.
13. Publish the web app to the Azure Cloud.
