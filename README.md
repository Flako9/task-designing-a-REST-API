# REST API Design: Library Catalogue System 📚

This repository contains the solution for the RESTful API design exercise. The goal was to design a comprehensive API for a Library Management System.

📄 **Full Documentation:** [Library_API_Design.pdf](./Designing_a_REST_API.pdf)

## 📋 Project Overview

The design follows industry best practices and meets the **Richardson Maturity Model Level 3** (Hypermedia Controls).

### Key Features Designed:
* **Entities:** `Book`, `Author`.
* **HATEOAS:** Full implementation of hypermedia links (`_links`) for resource navigation.
* **Caching:** Client-side caching strategy using `Cache-Control` and `ETag` validation.
* **Security:** Role-based access control using **Bearer Token (JWT)**.
* **Performance:** Pagination and Filtering standards for collection resources.

## 🛠 Contents of the PDF
1.  **Requirements:** Functional & Non-functional.
2.  **Data Model:** Entity definitions.
3.  **Operations:** Detailed endpoints description (GET, POST, PUT, DELETE).
4.  **Status Codes:** Mapping of HTTP codes to business logic.
5.  **Caching & Pagination:** Detailed technical strategy.

---
*Created as part of the University Course Task.*
