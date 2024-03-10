
1)Relationship between "Product" and "Product_Category":-
Th relationship between them is many-to-one relationship , meaning that many products can belong to one category.As we can see the "Product" entity has a foreign key column category_id that establishes a relationship with the "Product_Category" entity.
Each product in the "Product" table is assigned a category from the "Product_Category" table. 

2)To ensure each product has a valid category, set up a foreign key for the "category_id" in the "Product" table, referencing the "id" in the "Product_Category" table. 
Add constraints to enforce non-null values and validate against existing "Product_Category" table IDs, ensuring referential integrity.
