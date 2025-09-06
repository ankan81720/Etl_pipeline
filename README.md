# ETL Pipeline Project

##  Overview
This project simulates a simple ETL (Extract → Transform → Load) pipeline:
- **Extract**: Reads sales data from a CSV file.
- **Transform**: Cleans data and calculates new features like `revenue`.
- **Load**: Loads transformed data into a MySQL database.

Additionally:
- Added **logging** to track pipeline execution.
- Added **scheduling** (Python `schedule`) to run automatically.

##  Features
- Extract sales data from CSV
- Transform with Pandas (cleaning + new columns)
- Load into MySQL with SQLAlchemy
- Logging (`etl_pipeline.log`) for monitoring
- Scheduler (`etl_scheduler.py`) → demo mode (every 10 sec) & daily mode (09:00 AM)

## 🛠 Setup
1. Clone repo:
   ```bash
   git clone https://github.com/yourusername/etl-pipeline-project.git
   cd etl-pipeline-project
