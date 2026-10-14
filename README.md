# SmartCommerce — E-commerce Order & Inventory Automation

An automated e-commerce order processing and inventory management system built using **n8n Cloud, JavaScript, Google Sheets, and Gmail**.

## Project Overview

SmartCommerce automates repetitive e-commerce operations, including customer order collection, product validation, inventory updates, order tracking, and email notifications.

The project demonstrates workflow automation, conditional logic, JavaScript data processing, and integration with third-party services.

## Key Features

- Customer order submission through an n8n form
- Automatic product lookup and price calculation
- Stock availability validation
- Automatic inventory updates in Google Sheets
- Order records for successful and rejected requests
- Customer confirmation and rejection emails
- Low-stock notifications for store owners

## Technologies Used

| Technology | Purpose |
|---|---|
| n8n Cloud | Workflow orchestration |
| JavaScript | Order processing and validation |
| Google Sheets | Inventory and order records |
| Gmail | Automated email notifications |
| n8n Form Trigger | Customer order collection |

## How It Works

1. A customer submits an order through the SmartCommerce form.
2. n8n retrieves product details from Google Sheets.
3. JavaScript calculates the order total and validates stock.
4. Valid orders update inventory and are recorded in the Orders sheet.
5. Invalid orders are rejected without changing inventory.
6. Customers receive automated email notifications.
7. Low-stock products trigger an alert to the store owner.

## Screenshots

### Automation Workflow

![Workflow Overview](screenshots/workflow-overview.png)

### Customer Order Form

![Customer Form](screenshots/customer-order-form.png)

### Inventory Management

![Inventory](screenshots/inventory-management.png)

### Order Records

![Orders](screenshots/order-records.png)

### Email Notifications

![Email Notifications](screenshots/email-notifications.png)

## Testing

The workflow was tested using sample orders to verify successful order processing, stock validation, rejection handling, inventory updates, and email notifications.

## Limitations

SmartCommerce is a portfolio prototype rather than a production-ready online store. It does not process payments and requires additional duplicate-order protection, concurrency safeguards, and security controls before real-world deployment.

## Author

Nour Ben Fekih Ahmed

Software Engineering Student | Automation & Web Development

GitHub: https://github.com/benfekihnourrr
