# SQL-Project - Personal Nutrition and Fitness Management System
Business Objective:

With more people pivoting towards a healthier lifestyle, we see that fitness centers diversify their services and venture into nutritional services, as well as find unique ways to retain and motivate their customer base. Our management system provides a one stop solution for the fitness centers to manage schedules, inventories, events etc.
Customer:

Fitness centers and chains

Pain points the customer is facing:

· Streamlined customer scheduling and employee scheduling of a fitness and nutrition center

· Unique ideas to provide exceptional value to their customers and retain/improve their customer base

Solutioning:

Enable a fitness center to have streamlined and seamless features such as

- Customer management

- Employee management

- Attendance and booking management

- Billing and invoicing management

- Product inventory management

We also enable fitness centers to create and track customized challenges and have reward programs. In addition to the above, we provide functionalities that help in making dietary decisions based on allergies, general health, and fitness level of the customer.
Relational Data Model

Assumptions/Notes About Data Entities and Relationships:

Based on business requirements, we have created 19 entities which can be grouped into the following modules

1) Customer module

2) Employee module

3) Challenges and Rewards module

4) Inventory module

5) Invoice and Billing module

6) Booking and Attendance module

1) Customer module:

- For a given customer, we focus on two key areas, namely training and nutrition. In the training module, we associate a customer with the trainer based on the workout types. A customer can be associated with multiple trainers for various workout types.

- In the nutrition module, we take note of customers height and weight periodically. Also, we track the allergies of the customer which impacts the nutritional and workout recommendations.

2) Employee module:

- In the employee module, we track the employee's attendance and their future schedule. Also, the system maps every employee with the particular workout type that they are specialized in.

- An employee will be organizing challenges and competitions to retain and improve their customer base.

3) Challenges and Rewards module:

- Being the Unique Selling Proposition (USP) of our project, this module is to specifically encourage the customers to lead a healthier lifestyle in terms of physical activities. Every challenge belongs to a particular workout type and tracks with start/end date.

- The top three performers will be recognized and awarded a credit on their next invoice.

- Each Challenge is associated with one employee who is the organizer.

4) Inventory module:

- Our inventory table tracks all usable products under various categories such as gym equipment, nutrition products and miscellaneous products.

- All gym equipment will have an upcoming maintenance record and all nutritional products will have an expiration date. On a periodic basis, we remove all unsold and expired nutritional products from our inventory.
- - The inventory master table contains a list of all the products ever purchased and this can be linked to their corresponding invoices.

5) Invoice and Billing module:

- Here we have two areas namely customer billing and supplier invoicing. In customer billing, the system tracks any credit discounts that the customer is awarded. We also track top customers based on their patronage and defaulters to follow up on payments.

- Supplier invoicing tracks the vendor, invoice amount, payment amount and credit details. It also tracks the due date and payment date if the invoice is already paid.

- On a periodic basis, we track and address any overdue invoices.

6) Booking and attendance module:

- People who are interested in booking trial classes can do so via email, phone, or in-person. The system will record the name, email address and phone number. They will be provided with trial classes and this offer comes with an expiration date.

- Entry for the visitors will be based on the following status: Existing customer with valid customer ID, Customers with non-expired booking ID, Customers stopping by for general enquiries or purchasing.

- If a visitor does not satisfy the entry conditions, an entry will be logged with timestamp and the administrator will be notified immediately.
Screen shot of Physical Database objects




![Screenshot (93)](https://user-images.githubusercontent.com/110411394/186741484-a1e08cbd-ff95-4c00-ba95-2e5d5524fede.png)

ER Diagram:

![ER diagram](https://user-images.githubusercontent.com/110411394/186791506-59b5faef-4256-4859-9265-8c1ca0c77e9c.png)






