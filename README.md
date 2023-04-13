# ETL mysql to postgres
## Instruction
Step 1: Run the [psql-dwh.sql](/psql-dwh.sql) \
Step 4: Run the python notebook [etl-with-helper](/etl-with-helper.ipynb)  in your Postgresql database \
Step 2: create virtual env and install python packages:  
```
pip install pandas psycopg2 numpy mysql-connector-python datetime
```
Step 3: Run the python script [initialize_reference_table](/initialize_reference_table.py) \
Step 4: Run the python notebook [etl-with-helper](/etl-with-helper.ipynb) 

## Rerun the etl
Step 1: Run the psql-dwh.sql in your Postgresql database \
Step 2: Run the python notebook [etl-with-helper](/etl-with-helper.ipynb) 
