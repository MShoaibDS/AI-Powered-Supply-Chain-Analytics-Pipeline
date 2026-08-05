
# **🚀 AI-Powered Supply Chain Analytics Automation Pipeline**

AI-powered end-to-end Supply Chain Analytics Pipeline using n8n, PostgreSQL (Supabase), Gmail Automation, and Quadratic AI to automate ETL, KPI generation, and real-time business reporting.


### **End-to-End ETL Pipeline using n8n • PostgreSQL (Supabase) • Gmail API • Quadratic AI**

# **📌 Project Overview**

This project demonstrates an **AI-powered, enterprise-grade Supply Chain Analytics Pipeline** that automates the complete ETL process—from receiving supplier CSV reports via Gmail to generating business-ready insights using PostgreSQL and Quadratic AI.

Instead of manually downloading email attachments, cleaning data in Excel, and preparing reports, this solution automates the entire workflow, enabling faster reporting, improved data quality, and scalable analytics.

# **🎯 Business Problem**

Supply chain teams often receive operational reports as CSV attachments through email.

Traditional reporting involves:

- Downloading files manually
- Cleaning data in spreadsheets
- Importing into databases
- Combining multiple datasets
- Calculating KPIs manually
- Preparing management reports

This manual process is time-consuming, error-prone, and difficult to scale.

# **💡 Solution**

Designed and implemented a fully automated ETL pipeline that:

- 📩 Monitors Gmail inbox automatically
- 📂 Downloads CSV attachments
- 🔄 Extracts structured data
- 🗄 Loads data into PostgreSQL (Supabase)
- 🤖 Uses Quadratic AI for data transformation
- 📊 Calculates Supply Chain KPIs
- 📈 Produces business-ready analytics tables

# **🏗 Solution Architecture**

Supplier Email
        │
        ▼
 Gmail Trigger (n8n)
        │
        ▼
Download CSV Attachments
        │
        ▼
CSV Extraction
        │
        ▼
Data Validation & Transformation
        │
        ▼
 PostgreSQL (Supabase)
        │
        ▼
 Quadratic AI
        │
        ▼
 KPI Generation
        │
        ▼
 Business Analytics

## **📊 Interactive Quadratic AI Dashboard**

🔗 **View the live analytics workbook here:**

### 👉 **[Open Quadratic Sheet](https://app.quadratichq.com/file/182db7d6-d89d-4226-ad14-144b22a791a5)**

This live workbook showcases:

- ✅ AI-powered data transformation
- ✅ PostgreSQL (Supabase) integration
- ✅ Automated KPI calculations
- ✅ Supply Chain Analytics
- ✅ SQL queries and business insights


# **⚙️ Technology Stack**

| Technology | Purpose |
|------------|---------|
| **n8n** | Workflow Automation |
| **Gmail API** | Email Integration |
| **Google OAuth 2.0** | Authentication |
| **PostgreSQL** | Relational Database |
| **Supabase** | Cloud Database Hosting |
| **SQL** | Data Querying |
| **Quadratic AI** | AI-powered Analytics |
| **CSV** | Source Data |
| **ETL** | Data Engineering |

# **🔄 End-to-End Workflow**

## **📩 Step 1 — Gmail Automation**

- Connected Gmail using OAuth 2.0
- Automatically monitors incoming emails
- Filters supplier reports
- Downloads CSV attachments

## **📂 Step 2 — Data Extraction**

CSV attachments are automatically processed using n8n.

The workflow:

- Reads CSV files
- Extracts structured records
- Converts raw data into JSON
- Validates incoming data

## **🗄 Step 3 — Database Loading**

The extracted data is automatically inserted into PostgreSQL hosted on Supabase.

Tables are populated without any manual intervention.

## **🤖 Step 4 — AI-Powered Analytics**

Quadratic AI connects directly to PostgreSQL to:

- Clean data
- Merge datasets
- Generate exchange rate tables
- Build date tables
- Calculate business KPIs
- Produce analytics-ready datasets

# **📊 Supply Chain KPIs**

The solution automatically calculates:

- Total Orders
- Total Order Lines
- Line Fill Rate
- Volume Fill Rate
- On-Time Delivery %
- In-Full Delivery %
- OTIF (On-Time In-Full)
- Exchange Rate Conversion
- Order Performance Metrics

# **📈 Business Outcomes**

This project delivers significant operational improvements by:

- ✅ Automated end-to-end ETL workflows
- ✅ Eliminated repetitive manual reporting
- ✅ Standardized data ingestion
- ✅ Improved reporting accuracy
- ✅ Accelerated business insights
- ✅ Enabled scalable analytics architecture
- ✅ Supported AI-driven decision-making
- ✅ Created reusable enterprise automation workflows


# **🚀 Key Features**

- End-to-End ETL Pipeline
- Gmail Workflow Automation
- Automated CSV Processing
- PostgreSQL Data Warehouse
- Cloud Database Integration
- AI-assisted Data Transformation
- Automated KPI Generation
- Supply Chain Analytics
- Business Intelligence Automation
- Scalable Data Engineering Solution

# **🎯 Skills Demonstrated**

- Data Engineering
- ETL Development
- Workflow Automation
- PostgreSQL
- SQL
- Cloud Databases
- Business Intelligence
- AI-assisted Analytics
- Process Automation
- Data Transformation
- Supply Chain Analytics

