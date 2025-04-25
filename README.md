# E-commerce Database Design – Peer Group Assignment

## 📌 Overview  
This project is a **collaborative database design assignment** focused on building a robust relational database for an e-commerce platform. It includes a complete **Entity-Relationship Diagram (ERD)** and an accompanying **SQL implementation**, designed from the ground up by our team.

## 🎯 Objectives
- Design a scalable and normalized e-commerce database schema.
- Visualize the data structure using an ERD.
- Identify and establish relationships, keys, and constraints between entities.
- Implement the database using SQL.
- Collaborate effectively as a team using GitHub.

## 🛠️ What We Did

### 1. **ERD Creation**
We used [draw.io](https://draw.io/) to design our ERD, highlighting:
- Entities and their attributes
- Primary and foreign keys
- One-to-many and many-to-many relationships
- Constraints and data flow

### 2. **Data Flow Planning**
- Mapped data movement between entities
- Defined how products, variants, and attributes relate
- Created normalized tables to avoid redundancy

### 3. **SQL Implementation**
We created the full database schema using MySQL-compatible SQL in `ecommerce.sql`.

---

## 🗃️ Database Tables

| Table Name             | Description |
|------------------------|-------------|
| `brand`                | Stores product brand info |
| `product_category`     | Groups products into categories |
| `product`              | Main table for product information |
| `product_image`        | Stores URLs or references to images |
| `color`                | Defines available product colors |
| `product_item`         | A specific purchasable item (variant) |
| `product_variation`    | Links a product with its variations |
| `size_category`        | Groups sizes by type (e.g. clothing, shoes) |
| `size_option`          | Actual sizes (e.g. S, M, L, 42) |
| `product_attribute`    | Custom properties like material, weight |
| `attribute_category`   | Groups attributes into categories |
| `attribute_type`       | Type of each attribute (text, number, etc.) |
| `group_member`         | Table containing team member information |

---
## ERD Diagram
![ecommerce_erd_diagram](https://github.com/user-attachments/assets/2f4b0eb2-a8be-460e-85ee-672efa0637c8)

---
## 👥 Team Members

| First Name | Last Name  | Email                        |
|------------|------------|------------------------------|
| Brillian   | Chepwogen  | brillianchep@gmail.com       |
| Abdisalam  | Hassan     | abdisalamxhassan@gmail.com   |
| Salifu     | Kamara     | kamarasalifu60@gmail.com     |
| Simon      | Mwangi     | mwangisimone007@gmail.com    |
| Kasisi     | Edwin      | kasisiedwin20@gmail.com      |
| Cynthia    | Moraa      | cynthiamogaka49@gmail.com    |
| Princess   | Linus      | princymmeso37@gmail.com      |
| Abel Ndiritu| Kihara     | abelkihara8@gmail.com        |
| David      | Ngechu     | davidndirangungechu@gmail.com|
| Brian      | Mbaru      | brianmbaruh@gmail.com        |

---

## 📂 Repository Structure

```
📁 ecommerce-database/
├── 📄 README.md
├── 📄 ecommerce.sql
└── 📄 ecommerce_erd_diagram.drawio
└── 📄 ecommerce_erd_diagram.png

```

---

## 🚀 How to Use

1. **Clone the repo**
```bash
git clone https://github.com/senuadev/E-commerce-Database-Design.git
```

2. **Import into MySQL Workbench or CLI**
```sql
SOURCE ecommerce.sql;
```

3. **View the ERD**  
Open the ERD file in your preferred diagram tool or check the included image.
