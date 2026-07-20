# WooCommerce Automation Suite

A powerful n8n automation system for managing a complete WooCommerce store workflow.

##  Main Features

### Order Processing
- Triggers on new order placement
- Generates beautiful PDF invoices
- Sends professional invoice emails to customers

### Stock Management
- Automatically updates stock quantity after each order
- Marks products as "Out of Stock" when needed

### Product Synchronization
- Syncs product data from Google Sheets to WooCommerce
- Creates new products
- Updates existing products (price, description, images)
- Deletes unavailable products

### Daily Reporting
- Generates daily sales reports
- Includes total orders, sales, tax, refunds, best-selling products
- Sends formatted HTML report to admin

### AI Invoice Processing
- Reads sent invoices from Gmail
- Uses AI (OpenAI/Gemini) to extract and summarize data
- Maintains records in Google Sheets

##  Technologies Used

- **n8n** Workflow Automation
- **WooCommerce API**
- **Google Sheets**
- **Gmail**
- **PDF Generator API**
- **OpenAI + Google Gemini**

## How to Use

1. Download `woocommerce-automation.json`
2. Import into n8n
3. Configure credentials:
   - WooCommerce API
   - Google Sheets OAuth
   - Gmail OAuth
   - PDF Generator API
4. Activate required workflows
