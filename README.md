# water bottling company database
 
First off, the company that this database is built for has a main headquarters (HQ) branch that it is based out off. This was the first branch to be founded and holds importance in the company’s history. Throughout the years, multiple other branches have been opened all throughout the country, and the company now operates out of multiple locations. Each branch includes multiple departments which it oversees its function and work, with each department serving its own use as with any other company of such magnitude. Each branch also oversees its respective factory(s). Each branch is managed by one employee of the company (or in this case manager). When an employee works for a department or factory he/she by default works for Branch.
All departments have more than one phone number as to reach the different personnel in charge of that department.
Factories on the other hand are identified by its factory number. It is assumed that all factories use machinery. All machinery that is registered in the database is used only by the factories. Furthermore, each machine is identified by its serial number. The factory’s main function is to produce product and consume supplies, hence it is connected to both entities respectively.
The main base the company’s function revolves around is the signing of contracts.it is assumed in this database that each type of item is supplied or sold through the signing of a contract by a supplier or customer respectively. Hence the contract entity includes the Quantity attribute because one contract is designed to deal with one type of item no matter the quantity. Every contract is identified by its unique contract ID that is generated when the contract is made.
As soon as a supplier engages in dealings with the company, he is given a unique ID to represent the supplying company in the database. Only one contact person deals with the communication between the supplying company and our company.
The same goes for the customer, but in this case, we also included an attribute called loyalty points. As a gesture of appreciation, the company likes to reward its customers who stick with it throughout time. These loyalty points stack up with each purchase and result in gifts or discounts on products when an invoice is issued in the contract entity (represented as the rewards attribute in contract). If, however a specific customer is deleted from the database and then rejoins, his loyalty points are zeroed and start again.
In the case a customer does not purchase products from the company itself, he/she can buy the company’s products from local shops that belong to the company. These shops sell all the company products that can be bought from the company itself, however a customer is not contracted nor is he/she included in the database when such a purchase is made, hence it can be considered an “over the counter” purchase. Each shop is also managed by one employee of the company. These shops not only sell products made by the company, but also offer services such as refilling water or delivering water gallons to home.
