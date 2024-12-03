# Team ***** Mist 4610 Group Project 2

## Team Name: 


## Team Members:

1. Hazel Lee [@MIST4610](https://www.github.com/MIST4610)
2. Kevin Reilly [@kmr95597](https://www.github.com/@kmr95597)
3. Alexandre Tran
4. Samantha nguyen

## Problem Description:

The task is to model and build a relational database for a T-shirt manufacturing and retail company. This company operates across multiple domains, including managing suppliers, tracking inventory, processing customer orders, overseeing production, and maintaining employee records. The goal is to accurately model these relationships, generate sample data, populate the entities and their attributes, and run functional queries on this data to derive valuable business insights.

## Data Model

<img width="616" alt="image" src="https://github.com/user-attachments/assets/a3c53f65-ce69-420e-a7ab-5a94815d05c8">



Explanation of data model: 

Our model is based on the structure of a T-shirt manufacturing and retail company. At the core of this business are suppliers, products, inventory, customer orders, production, and employees, all of which are interconnected to streamline operations.

The supplier entity represents the external vendors that provide raw materials or finished T-shirts. Each supplier can provide multiple products, and this relationship is reflected in the one-to-many link between the supplier and T-shirt entities. This setup allows the company to track which supplier is responsible for which products, ensuring smooth procurement processes.

At the heart of the operation is the T-shirt entity, which represents the various products sold or manufactured by the company. These products are tightly linked to the inventory entity, which keeps track of their availability in the warehouse. The inventory entity includes critical details such as stock levels, restocking dates, and storage locations, ensuring the company can manage supply effectively to meet demand.

Customer orders are handled through the orders entity, which is connected to the customer entity. This structure enables the company to manage who is purchasing products and what items they are buying. The order details entity provides a breakdown of each order, capturing information about the specific products, quantities, and pricing. Returns are also incorporated into this model, allowing the company to track products returned by customers and the reasons behind those returns.

On the production side, the company must manage the manufacturing process, which is represented by the production entity. This entity links employees, equipment, and products to capture details about when production starts and ends, which equipment is used, and which employees are involved. Equipment and employees are organized within their respective entities, with equipment tracking workload capacity and employees capturing roles, performance ratings, and supervisors. These connections allow for efficient resource allocation and oversight.

Overall, this data model provides a comprehensive framework for managing the company’s operations, from sourcing materials and manufacturing T-shirts to processing customer orders and monitoring inventory levels. The interconnected relationships ensure that all aspects of the business work together seamlessly, enabling the company to maintain high efficiency and deliver quality products to its customers.

## Data Dictionary:








## Queries:

1. How do different inventory statuses impact order delays?

<img width="629" alt="image" src="https://github.com/user-attachments/assets/85aefdc6-af9c-4b4e-8838-8cf4123f1557">

Managers need to understand the relationship between inventory levels and delays in fulfilling customer orders. This insight helps optimize inventory management, avoid stockouts, and improve customer satisfaction.

2. Which suppliers contribute the most to overall revenue, and how significant is their contribution to the company's total sales? 

<img width="641" alt="image" src="https://github.com/user-attachments/assets/337d3d60-78f4-4e5b-ad9d-a0d46c580b16">

Managers can use this information to identify top-performing suppliers, prioritize critical partnerships, optimize revenue by increasing orders from high-performing suppliers or improving underperforming ones, and ensure supply chain balance by avoiding over-reliance on a single supplier.

3. This query evaluates which suppliers contribute the most to products categorized as "critical" based on certain thresholds (e.g., low inventory levels).

<img width="586" alt="image" src="https://github.com/user-attachments/assets/fe78111b-2b0c-4915-aa04-aa57582a53f0">



4. This query finds the top suppliers by their total inventory
   
 <img width="488" alt="image" src="https://github.com/user-attachments/assets/f578148c-7e6d-445d-968b-9f9d7f541c29">


5.This query shows the top 10 products that produce the highest revenue

<img width="597" alt="image" src="https://github.com/user-attachments/assets/ac716aaf-3b91-4816-bae6-97ae05bc819b">




## Tableau Visualizations 

1. Workload percent to Equipment name, Only Primary Equipment

<img width="617" alt="image" src="https://github.com/user-attachments/assets/8d0b4f57-e0e6-4fa5-bc64-b5cf61d927e9">

The graph highlights equipment with high workload percentages, such as the Laser Cutter and Sewing Machines. These machines may be nearing or exceeding their optimal operating capacity, which can lead to wear and tear or potential downtime if not managed proactively. Identifying overutilized equipment allows for strategic planning, such as redistributing workload or scheduling maintenance to avoid disruptions

2. employees and creates a heat map

<img width="619" alt="image" src="https://github.com/user-attachments/assets/70f17f94-7328-47f6-96cf-8aa2885d792c">

The graph ranks employees based on their performance ratings, allowing managers to quickly identify high performers (e.g., Paul Harris, Charlie Davis) and those whose performance is at the lower end (e.g., Alice Johnson, Kathy Scott). This can guide discussions around recognition, rewards, or areas of improvement.

3. Displays the amount in inventory in depending on the color and the material

<img width="630" alt="image" src="https://github.com/user-attachments/assets/15588e53-972c-42ef-8169-73676c7af5fc">






