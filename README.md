## This repository contains two pages that interact with the [SpoonerInv Database](https://github.com/jaredlyon/SpoonerInv):

### Barista Page
There are 2 barista pages one for placeing orders and another for editing their information.

1 - edit information page. This page has the barista enter their id which then allows them to see the infomation of the other employees at work in the store in the table. As well this entry allow them to change their own information via the form. There is no place for an barista to change their employee ID or store ID as thos permissions would be reserved for the manager. The refresh button allows the employee to see the changes that they have made to their information in the table. 

2 - drink orders page. This page is ment to simular a point of sale system where a barista can enter new orders and new drinks. The workflow starts with the barista entering their ID. This both allows them to submit orders and updates the list of ingridents that they have acess to by what their store has acess to. They then take the customer's ID and add a new order. When the order is posted the new order ID is place into add drink, drinks table, and edit order automatically. The barista can than add drinks to the order using the add drink form, which will then appear in the drinks table when the table is refreshed. If there needs to be any edits to the drinks they can use the table to edit as well as delete drinks. When a drink's price is updated it will edit the derived field of formalated price. This can be checked in the edit order modal. The edit order modal both allows the employee to check what customer ordered the drink and its price, as well as edit those fields. Finally a whole order can be deleted using the delete order button. 

### Manager Page
TODO: write useme here


![](https://raw.githubusercontent.com/appsmithorg/appsmith/release/static/appsmith_logo_primary.png)

This app is built using Appsmith. Turn any datasource into an internal app in minutes. Appsmith lets you drag-and-drop components to build dashboards, write logic with JavaScript objects and connect to any API, database or GraphQL source.

![](https://raw.githubusercontent.com/appsmithorg/appsmith/release/static/images/integrations.png)

### [Github](https://github.com/appsmithorg/appsmith) • [Docs](https://docs.appsmith.com/?utm_source=github&utm_medium=social&utm_content=appsmith_docs&utm_campaign=null&utm_term=appsmith_docs) • [Community](https://community.appsmith.com/) • [Tutorials](https://github.com/appsmithorg/appsmith/tree/update/readme#tutorials) • [Youtube](https://www.youtube.com/appsmith) • [Discord](https://discord.gg/rBTTVJp)

##### You can visit the application using the below link

###### [![](https://assets.appsmith.com/git-sync/Buttons.svg) ](http://localhost:8080/applications/642d92bfea2f36397c4913a9/pages/642d92bfea2f36397c4913ac) [![](https://assets.appsmith.com/git-sync/Buttons2.svg)](http://localhost:8080/applications/642d92bfea2f36397c4913a9/pages/642d92bfea2f36397c4913ac/edit)
