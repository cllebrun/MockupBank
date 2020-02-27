# IBM Mockup Bank developer toolkit

All you need to know about the fictious **Banking Data Model &amp; APIs** for the Hackathon.

This page will provide high level documentation, the basics and links to get to the **APIs** and more detailed documentation.
+ Detailed documentation of the **IBM API Connect APIs** is [here](mockupbank-api-doc.md)
+ Access to a Node-RED application as an example on how to consume the APIs [here]() (You only have access as a viewer to get inspiration and build your own Node-RED application.)
+ Detailed documentation of the Data Model is [here](datamodel/DataModel.md)

---
### The API Swagger  

The **API swagger** for the Mockbank is available here: https://mockupbank-da.bnk-kno.nca.ihost.com/api/explorer/#/


> **Note:** the above URL is the swagger which will allow you to test the APIs and the domain for all the APIs for the *MockupBank application*.

This lets developers explore the APIs that are available, the required and optional parameters, and schema for responses.

![](assets/swagger-mockup.png)


---
### The Node-RED application  
Node-RED is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.

It provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes in the palette that can be deployed to its runtime in a single-click.

Everything you need to know about how to develop applications with Node-RED is available at: https://nodered.org/
You can find, open source Node-RED flows, nodes libraries, documentation...

As an example of usage of the APIs, a sample Web Application has been built for you to consume the URLs as an example of rapidly prototyping an app.
This application UI is available at the following URL:

![](assets/markdown-img-paste-20191001123544158.png)

---
### The Data model  

The **Data Model** is a simplistic one based on Customers, Accounts and Transactions.

The provided data is based on the following schema which is an extract of a larger data model.
![](assets/datamodel-20.png)

More details about the data model and its entities is available [here](datamodel/DataModel.md)

---
### The Data Dynamic Dashboard  

A dynamic dashboard is available as a mean of descriptive analytic [here](https://eu-gb.dataplatform.cloud.ibm.com/dashboards/c30b0802-4968-4b88-a71f-d2f1b60e86ae/view/7c35c90104a018965ff6c0e4079f24527f36715db1bb8a0380877b4959632497a96d1691c87a490c89120264fbed445a9b)


The dashboard is composed of three tabs:
- Customers
- Accounts
- Transactions

It displays **counts** and **charts** which can be filtered by various means.

![](assets/data-dashboard.png)

All the widgets on the dashboard are connected which means that selection on one widget will filter content of other widgets.

Please note that this dashboard **DOES NOT** consume the exposed APIs but queries directly against the database.
