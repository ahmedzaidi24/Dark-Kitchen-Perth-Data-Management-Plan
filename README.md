# Dark Kitchen Perth - Data Management Plan

This repository contains a **data management plan** for setting up and operating a multi-brand dark kitchen in Perth, Australia. The project focuses on leveraging data to optimize operations, improve customer satisfaction, and drive business insights.

---

## Overview
A **dark kitchen** (also known as a ghost kitchen) is a delivery-only food service that operates multiple fast-food brands under one roof. This project involves managing data related to:
- Customer orders
- Supply chain and inventory
- Operational efficiency
- Marketing and customer feedback

The data is collected from various sources, including POS systems (e.g., Deliverect), delivery platforms (e.g., UberEats, Menulog), and social media. It is then processed, analyzed, and visualized to support decision-making.

---

## Data Management Plan
The data management plan includes the following key components:

### 1. **Data Sources**
- **POS Systems**: Deliverect's MyOrderBox for order tracking.
- **Delivery Platforms**: UberEats, Menulog, and DoorDash for order data.
- **Social Media**: Customer feedback and marketing data from platforms like Instagram and Facebook.

### 2. **Data Lifecycle**
- **Generation**: Data is generated from orders, customer interactions, and operational activities.
- **Collection**: Data is collected through integrated POS systems and delivery platforms.
- **Processing**: Data is validated, cleaned, and stored in cloud storage (e.g., Microsoft OneDrive).
- **Analysis**: Data is analyzed using statistical methods and visualized using tools like PowerBI and Python.
- **Archival**: Historical data is archived for future reference and compliance.

### 3. **Data Governance**
- **Data Owners**: The owner of the mother brand and managers of individual fast-food brands.
- **Data Stewards**: Data analysts and administrators responsible for data quality and integrity.
- **Data Users**: Managers, chefs, and marketers who use data for decision-making.

### 4. **Data Security and Privacy**
- Compliance with Australian data protection laws.
- Access control mechanisms to restrict data access based on user roles.
- Use of firewalls, encryption, and intrusion detection systems to protect data.

---

## Setup Instructions
To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/dark-kitchen-perth-data-management-plan.git
