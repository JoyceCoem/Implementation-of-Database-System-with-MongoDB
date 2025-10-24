## 🍃 Implementation of Database System with MongoDB

This section presents the **NoSQL implementation** of the Cultural Facility Management Database using **MongoDB**.  
It mirrors the Oracle DBMS structure with collections and documents instead of relational tables.

### 📄 Overview
The MongoDB implementation demonstrates:
- Creation of collections for **provinces**, **municipalities**, **facilities**, **rooms**, **activities**, and **uses**  
- Insertion of sample records as **JSON documents**  
- Use of **aggregation pipelines** (`$lookup`, `$match`, `$project`) to query related data across collections  

### ⚙️ Key Features
- Simplifies complex relationships through document-based modeling  
- Enables flexible data structures without strict schemas  
- Supports queries for:
  - Facilities and their rooms  
  - Municipalities with population filters  
  - Activity schedules with linked province and facility details  

### 🧩 Tools Used
- **MongoDB Community Server / Atlas**  
- **MongoDB Compass** or **VS Code MongoDB Extension**  

### 🎓 Learning Outcomes
Through this implementation, learners gain experience in:
- Transitioning from relational to document-based database design  
- Using aggregation pipelines for multi-collection queries  
- Managing hierarchical data in a flexible, schema-less environment  
