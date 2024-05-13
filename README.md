# What is dbt?


dbt is a transformation workflow that helps you get more work done while producing higher quality results. You can use dbt to modularize and centralize your analytics code, while also providing your data team with guardrails typically found in software engineering workflows. Collaborate on data models, version them, and test and document your queries before safely deploying them to production, with monitoring and visibility.


dbt compiles and runs your analytics code against your data platform, enabling you and your team to collaborate on a single source of truth for metrics, insights, and business definitions. This single source of truth, combined with the ability to define tests for your data, reduces errors when logic changes, and alerts you when issues arise.


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
