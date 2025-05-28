# Developed_scripts

Two Postgresql DB dynamic comparision using python

Features / Workflow
-------------------
1)Load Configuration:
Read DB credentials from a config.yaml file.

2)Establish Connections:
Connect to both source and target PostgreSQL databases using psycopg2.

3)Compare Components:
Common schemas
Tables and Views
Columns: names, types, sizes
Constraints (PKs, FKs, Unique)
Triggers: name, event, and definition
Functions and Procedures
Sequences: start, increment, max
Data types compatibility
Export Results:
All results are consolidated into a pandas DataFrame and exported to an Excel file:
