1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.

Ans. The "Product" and "Product_Category" entities have one-to-many relationship. One product_category can have multiple products but one product can belong to only one product_category.
     This relationship is represented by foreign key in "product" table which references primary key of "product_category" table.



2. How could you ensure that each product in the "Product" table has a valid category assigned to it?

Ans. To ensure that each product in the "Product" table has a valid category assigned to it, we have to create a foreign key constraint in "Product" table that references the primary key of "Product_Category" table.
     Foreign key prevents insertion of any rows into "Product" table where category does not exist in "Product_Category" table.
