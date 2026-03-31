# Setup Instructions

## 1. Import Workflow
- Download the workflow JSON file
- Import it into your n8n instance

## 2. Configure Credentials
Add your own credentials:
- OpenAI / DeepSeek API Key
- MySQL Database Credentials
- Google Drive (if used)

## 3. Database Setup
- Create table: `sales_data`
- Columns:
  product_id, product_name, category, cost_per_unit, selling_price, units_sold, month, revenue, profit, margin, product_id_month

## 4. Run the Workflow
- Start workflow
- Try queries like:
  - best product
  - top 3 products
  - most sold product

## ⚠️ Note
Credentials are not included for security reasons.
