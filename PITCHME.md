---
marp: true
title: Records and Relationships
description: This lesson practices domain modeling by discussing when to use a one-to-many or a many-to-many relationship.
# theme: uncover
transition: fade
paginate: true
_paginate: false
html: true
---

# Records and Relationships

---
# <!--fit--> What are the associations?
- Cities and Neighborhoods
- Courses and Students
- Photographers and Photos
- Bands and Venues
- Contractors and Clients
- States and Senators
- Groups and Members

---
# One-to-Many or Many-to-Many?
When you're deciding, ask yourself:
- Can one x have many y?
- Can one y have many x?

The answer:
- **It depends on what you're building**
- Justify it

### If **One-to-Many**, which table gets the **foreign key** column?
### If **Many-to-Many**, what’s a good name for the **join table**?

---

Poll

https://pollev.com/ianheraty201


<!-- 
1. Cities and Neighborhoods

If we model Cities and Neighborhoods as a one-to-many, which table would you add a foreign key to?

What would you call the foreign key column?

2. Courses and Students

If we model it as a many-to-many, can you think of a good name for the join table between courses and students?

3. Photographers and photos

If we model Photos and Photographers as a one-to-many, which table would you add a foreign key to?

4. Bands and Venues

If we model it as a many-to-many, can you think of a good name for the join table between bands and venues?

5. Contractors and Clients

If we model it as a many-to-many, can you think of a good name for the join table between contractors and clients?

6. States and Senators

7. Groups and members

If we model it as a many-to-many, can you think of a good name for the join table between groups and members?

8. Can you think of any more relationships that we could model?

 -->