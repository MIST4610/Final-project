# Team 9 Mist 4610 Group Project 2

## Team Name: Team KASH


## Team Members:

1. Hazel Lee [@MIST4610](https://www.github.com/MIST4610)
2. Kevin Reilly [@kmr95597](https://www.github.com/@kmr95597)
3. Alexandre Tran
4. Samantha nguyen

## Problem Description:

The task is to model and build a relational database for a T-shirt manufacturing and retail company. This company operates across multiple domains, including managing suppliers, tracking inventory, processing customer orders, overseeing production, and maintaining employee records. The goal is to accurately model these relationships, generate sample data, populate the entities and their attributes, and run functional queries on this data to derive valuable business insights.

## Data Model

<img width="638" alt="image" src="https://github.com/user-attachments/assets/b79ecc0e-b2f9-4082-9ae4-e5728b2bedff">




Explanation of data model: 

Our model is based on the structure of a T-shirt manufacturing and retail company. At the core of this business are suppliers, products, inventory, customer orders, production, and employees, all of which are interconnected to streamline operations.

The supplier entity represents the external vendors that provide raw materials or finished T-shirts. Each supplier can provide multiple products, and this relationship is reflected in the one-to-many link between the supplier and T-shirt entities. This setup allows the company to track which supplier is responsible for which products, ensuring smooth procurement processes.

At the heart of the operation is the T-shirt entity, which represents the various products sold or manufactured by the company. These products are tightly linked to the inventory entity, which keeps track of their availability in the warehouse. The inventory entity includes critical details such as stock levels, restocking dates, and storage locations, ensuring the company can manage supply effectively to meet demand.

Customer orders are handled through the orders entity, which is connected to the customer entity. This structure enables the company to manage who is purchasing products and what items they are buying. The order details entity provides a breakdown of each order, capturing information about the specific products, quantities, and pricing. Returns are also incorporated into this model, allowing the company to track products returned by customers and the reasons behind those returns.

On the production side, the company must manage the manufacturing process, which is represented by the production entity. This entity links employees, equipment, and products to capture details about when production starts and ends, which equipment is used, and which employees are involved. Equipment and employees are organized within their respective entities, with equipment tracking workload capacity and employees capturing roles, performance ratings, and supervisors. These connections allow for efficient resource allocation and oversight.

Overall, this data model provides a comprehensive framework for managing the company’s operations, from sourcing materials and manufacturing T-shirts to processing customer orders and monitoring inventory levels. The interconnected relationships ensure that all aspects of the business work together seamlessly, enabling the company to maintain high efficiency and deliver quality products to its customers.

## Data Dictionary:

<img width="689" alt="image" src="https://github.com/user-attachments/assets/d554cdaa-94b3-404f-b0d1-5adb830f6c28">


<img width="664" alt="image" src="https://github.com/user-attachments/assets/65bb8f82-332f-4eaa-82ba-36edd6a23d36">


<img width="699" alt="image" src="https://github.com/user-attachments/assets/b62e9510-9c7f-44b7-9201-f98fe595e319">


<img width="686" alt="image" src="https://github.com/user-attachments/assets/536a672c-5061-4685-ac4f-bb0aa7c21964">


<img width="659" alt="image" src="https://github.com/user-attachments/assets/224684cf-057e-4eb2-9b05-88497539b1e4">


<img width="656" alt="image" src="https://github.com/user-attachments/assets/5349dd52-a40e-4d8a-a760-190928bc41ec">


<img width="659" alt="image" src="https://github.com/user-attachments/assets/7ae19c6c-2241-49db-9a9f-da7c9ebc807d">


<img width="646" alt="image" src="https://github.com/user-attachments/assets/94d92dab-5f5e-44f4-ada9-059000500b64">


<img width="670" alt="image" src="https://github.com/user-attachments/assets/351d96a8-bd9c-4f2c-af88-c4c73891d334">


<img width="650" alt="image" src="https://github.com/user-attachments/assets/a64cd94a-1434-45bc-81b0-1b79481cc15e">
















## Queries:

1. How do different inventory statuses impact order delays

<img width="629" alt="image" src="https://github.com/user-attachments/assets/85aefdc6-af9c-4b4e-8838-8cf4123f1557">

Managers need to understand the relationship between inventory levels and delays in fulfilling customer orders. This insight helps optimize inventory management, avoid stockouts, and improve customer satisfaction.

2. Which suppliers contribute the most to overall revenue, and how significant is their contribution to the company's total sales

<img width="641" alt="image" src="https://github.com/user-attachments/assets/337d3d60-78f4-4e5b-ad9d-a0d46c580b16">

Managers can use this information to identify top-performing suppliers, prioritize critical partnerships, optimize revenue by increasing orders from high-performing suppliers or improving underperforming ones, and ensure supply chain balance by avoiding over-reliance on a single supplier.

3. Which suppliers contribute the most to products categorized as "critical" based on certain thresholds (e.g., low inventory levels).

<img width="586" alt="image" src="https://github.com/user-attachments/assets/fe78111b-2b0c-4915-aa04-aa57582a53f0">



4. What is the top suppliers by their total inventory
   
 <img width="488" alt="image" src="https://github.com/user-attachments/assets/f578148c-7e6d-445d-968b-9f9d7f541c29">


5. This query shows the top 10 products that produce the highest revenue

<img width="597" alt="image" src="https://github.com/user-attachments/assets/ac716aaf-3b91-4816-bae6-97ae05bc819b">

This query identifies the top 10 t-shirt products by total revenue. It calculates total revenue by multiplying the quantity ordered by the price for each product. The query uses joins to combine data from the tshirt, orderDetails, and orders tables, ensuring accurate product and sales information. It groups results by product ID and description, then sorts them in descending order of total revenue. This is useful for analyzing top-performing products, optimizing inventory, and planning marketing strategies.



## Tableau Visualizations 

1. Workload percent to Equipment name, Only Primary Equipment

<img width="617" alt="image" src="https://github.com/user-attachments/assets/8d0b4f57-e0e6-4fa5-bc64-b5cf61d927e9">

The graph highlights equipment with high workload percentages, such as the Laser Cutter and Sewing Machines. These machines may be nearing or exceeding their optimal operating capacity, which can lead to wear and tear or potential downtime if not managed proactively. Identifying overutilized equipment allows for strategic planning, such as redistributing workload or scheduling maintenance to avoid disruptions

2. Employee Performance Ratings

<img width="619" alt="image" src="https://github.com/user-attachments/assets/70f17f94-7328-47f6-96cf-8aa2885d792c">

This graph displays a list of employees with their performance ratings ranked from lowest to highest. It allows managers to identify employees who may need additional support or improvement. By focusing on lower-rated employees, targeted interventions or meetings can be scheduled to address specific challenges and improve overall performance.

3. Inventory distribution based on color and material type

<img width="630" alt="image" src="https://github.com/user-attachments/assets/15588e53-972c-42ef-8169-73676c7af5fc">

This graph provides a clear view of inventory distribution by color and material type, helping businesses identify overstocked or understocked combinations. It supports better inventory management, ensuring the right products are available to meet customer demand. Additionally, it aids in supply chain decisions, production planning, and sales strategies by highlighting which combinations are most or least popular. Overall, it simplifies decision-making for optimizing stock and improving business efficiency.






