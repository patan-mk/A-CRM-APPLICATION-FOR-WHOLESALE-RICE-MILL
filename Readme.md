# Rice Mill CRM Application

## Overview

The **Rice Mill CRM** is designed to streamline and automate daily rice production and sales reporting for a wholesale rice mill. This application helps in optimizing customer interactions, improving operational efficiency, and enhancing productivity.

## Features

- **Reports and Dashboards**: Generate detailed reports on rice sales, daily revenue, and customer purchasing trends.
- **Roll-Up Summary Fields**: Aggregation of data from related records (COUNT, SUM, MIN, MAX).
- **Cross-Object Formulas**: Seamless calculations, such as total payment based on rice quantity and price.
- **Validation Rules**: Ensures data integrity by preventing submission of incomplete or invalid data.
- **Permission Sets**: Provides role-based access control for owners, employers, and workers.

## Technical Architecture

The system integrates data from production and sales records to generate real-time reports. It uses Salesforce as the primary platform, utilizing standard CRM features such as objects, fields, profiles, roles, and dashboards to manage rice mill operations.

## Key Components

- **Custom Objects**: Supplier, Rice Mill, Consumer, Rice Details.
- **Tabs**: User interface components for managing records.
- **Lightning App**: "MY RICE" Lightning app that organizes and provides navigation for the system.

## Prerequisites

- **Salesforce Developer Account**
- **Basic Salesforce Admin Knowledge**
- **Machine with Two Web Browsers**
- **Stable Internet Connectivity**

## Milestones and Activities

1. **Salesforce Introduction**: Set up a Salesforce Developer account.
2. **Objects Creation**: Create custom objects for Supplier, Rice Mill, Consumer, and Rice Details.
3. **Tabs**: Create tabs for each custom object.
4. **Lightning App**: Build the "MY RICE" Lightning app.
5. **Fields**: Define custom fields like `Rice Distributed` and junction objects.
6. **Page Layouts**: Design page layouts for data entry optimization.
7. **Profiles**: Create profiles for different user roles (Owner, Employer, Worker).
8. **Roles & Role Hierarchy**: Define visibility and access control using roles.
9. **Users**: Create user accounts with specific roles and permissions.
10. **Permission Sets**: Extend access control with custom permission sets.
11. **Reports**: Create reports on sales, rice price per kilogram, and total sales.
12. **Dashboards**: Build dashboards with components like bar and donut charts for visual insights.

## Learning Outcomes

- Understanding of Salesforce object relationships.
- Experience with real-time Salesforce projects.
- Knowledge of formula fields, validation rules, and page layouts.
- Proficiency in creating reports, dashboards, and implementing role-based permissions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

