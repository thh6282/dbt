# Set up dbt environment

Step 1: create folder dbt workspace (Desktop or othor you want). Acess the folder just created.

Step 2: Set up Python environment in the folder.
   ```
   python -m venv dbt venv
   .\dbt_venv\Scripts\Activate.ps1
   pip install dbt-postgres # can change dbt-snowflake,...
   ```


Step 3: Create .dbt folder in Users


Step 4: Create connect to database
  ```
  dbt init
  ```


Step 5: Check connect to database
  ```
  dbt debug
  ```
