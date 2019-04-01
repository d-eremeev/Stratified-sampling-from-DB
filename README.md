# Stratified sampling from DB [continuous responce]
The aim of this script is to perform stratified sampling on dataset with continuous response variable.

In this script one could:

    1. Connect to PostgreSQL DB table (with continuous responce variable) using pyodbc.
    2. Bin responce variable into bins with at least <threshold> elements.
    3. Use stratified sampling to get subsets with distribution similar to initial one.
    4. Add column with flags for corresponding subsets to DB table.
