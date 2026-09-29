# Import Data Using Transform Maps – ServiceNow

## 📌 Overview

This project demonstrates how to import external data such as CSV/Excel files into ServiceNow using **Import Sets and Transform Maps**.

## 🔄 Workflow

```text
CSV / Excel
    ↓
Import Set
    ↓
Import Set Table
    ↓
Transform Map
    ↓
Field Mapping
    ↓
Target Table
```

## 🛠️ Technologies

* ServiceNow
* Import Sets
* Transform Maps
* CSV / Excel

## 🚀 Steps

1. Prepare the CSV/Excel data.
2. Go to **System Import Sets → Load Data**.
3. Upload the file.
4. Create an **Import Set Table**.
5. Create a **Transform Map**.
6. Select the source and target tables.
7. Map source fields to target fields.
8. Configure **Coalesce** if required.
9. Run the Transform.
10. Verify the records in the target table.

## 🔑 Coalesce

Coalesce helps ServiceNow identify existing records.

* **Match found** → Update existing record.
* **No match** → Create a new record.

## 🎯 Learning Outcome

This project helps understand how to import, transform, map, and manage external data in ServiceNow.

## 👨‍💻 Platform

**ServiceNow**

## 📄 Purpose

Educational and academic project.
