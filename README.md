📌 Overview

This project automates data import in ServiceNow using Import Sets and Transform Maps, while establishing relationships between tables using Dot Walking.

🚀 Key Features

Import data from CSV/Excel using Import Sets
Transform and map data with Transform Maps
Avoid duplicates using coalesce fields
Automatically create relationships using dot walking
⚙️ How It Works

Load data via a Data Source
Store it in an Import Set Table
Use a Transform Map to map fields
Apply dot walking to link reference fields
Insert/update records in target tables
🔗 Example

target.department.name = source.department_name;
Maps and links a user to a department automatically.

✅ Benefits

Reduces manual effort
Ensures data consistency
Scalable and reusable
⚠️ Prerequisites

ServiceNow instance access
Basic knowledge of Import Sets & Transform Maps
