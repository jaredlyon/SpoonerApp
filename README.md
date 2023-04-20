## This repository contains two pages that interact with the [SpoonerInv Database](https://github.com/jaredlyon/SpoonerInv):

### Barista Page
There are 2 barista pages one for placing orders and another for editing their information.

1 - Edit Information Page
This page has the barista enter their ID, which then allows them to see the information of the other employees at work in the store in the table. This page also allows them to change their own information via the form. There is no place for a barista to change their employee ID or store ID, since those permissions would be reserved for the manager. The refresh button allows the employee to see the changes that they have made to their information in the table. 

2 - Drink Order Page
This page is meant to simulate a point of sale system where a barista can enter new orders and new drinks. The workflow starts with the barista entering their ID. This allows them to both submit orders as well as update the list of ingredients that they have access to (determined by what store they work at). They then take the customer's ID and add a new order. When the order is posted the new order ID is placed into the add drink, drinks table, and edit order widgets automatically using routes. The barista can than add drinks to the order using the add drink form, which will then appear in the drinks table when the table is refreshed. If there needs to be any edits to the drinks they can use the table to edit as well as delete drinks. When a drink's price is updated it will edit the derived field of formulated price. This can be checked in the edit order modal. The edit order modal both allows the employee to check what customer ordered the drink and its price, as well as edit those fields. Finally a whole order can be deleted using the delete order button. 

### Manager Page
There are three manager pages: one for viewing and updating employee information for a specified store, one for viewing and updating stock information for a specified store, and viewing store information for a specified region.

1 - Employee Page
This page has the manager enter their store ID, which allows them to view personal and contact information for all the employees that work for their store. The form on the left allows the manager to hire a new employee and add them to the store database by entering their first and last name, phone number, email address, and the ID of the store that they are going to work in and clicking the submit button. The form on the right allows the manager to edit and fire employees, subsquently removing them from the store database. To edit an employee's information, they need to click on the table row of that employee, change the neccessary field(s), and click the save button to the right of the row. Clicking the discard button will revert any changes made to that row. To fire an employee, they need click on the table row of that employee and then click on the delete button.

2 - Stock Page
This page has the manager enter their store ID, which allows them to view information about all the stock itmes available in their store. They can edit the information of a stock item by clicking on the table row of that item, changing the necessary field(s), and clicking on the save button to the right of the row. Clicking the discard button will revert any changes made to that row. The manager can also delete a stock item by clicking on the table row of the item that needs to be deleted and then clicking on the delete buttom at the bottom.

3 - Store Page
This page has the manager enter their region ID, which allows them to view information about all the stores located within that region.

![](https://raw.githubusercontent.com/appsmithorg/appsmith/release/static/appsmith_logo_primary.png)

This app is built using Appsmith. Turn any datasource into an internal app in minutes. Appsmith lets you drag-and-drop components to build dashboards, write logic with JavaScript objects and connect to any API, database or GraphQL source.

![](https://raw.githubusercontent.com/appsmithorg/appsmith/release/static/images/integrations.png)

### [Github](https://github.com/appsmithorg/appsmith) • [Docs](https://docs.appsmith.com/?utm_source=github&utm_medium=social&utm_content=appsmith_docs&utm_campaign=null&utm_term=appsmith_docs) • [Community](https://community.appsmith.com/) • [Tutorials](https://github.com/appsmithorg/appsmith/tree/update/readme#tutorials) • [Youtube](https://www.youtube.com/appsmith) • [Discord](https://discord.gg/rBTTVJp)

##### You can visit the application using the below link

###### [![](https://assets.appsmith.com/git-sync/Buttons.svg) ](http://localhost:8080/applications/642d92bfea2f36397c4913a9/pages/642d92bfea2f36397c4913ac) [![](https://assets.appsmith.com/git-sync/Buttons2.svg)](http://localhost:8080/applications/642d92bfea2f36397c4913a9/pages/642d92bfea2f36397c4913ac/edit)
