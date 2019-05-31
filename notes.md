


// One to One relationship //

- Like Customer Table and Profile Table and their link would be a one to one
- Not common
- Primary key would be the primary/main entity
- Foreign key would be the second entity and has to be unique


// One to Many Relationship //

- Primary table linked to many entries in seconday table. Ex customer
- Secondary table be linked to one entry in primary. Will have column called customer_id will be foreign key that links back to customer to the id column
- Customer can have many orders
- User can have followers
- Used alot
- In secondary table can have many things to relate back to first entity


// Many to Many Relationship //

- Fairly common
- You need a third table
- An order can have many products and the same product will appear in many orders. A third column will have 3 foreign keys to link first two tables.
- A book can have more than one author and an author can write more than one book.
- Create a third table(say we have order and product table) that will hold these relationships