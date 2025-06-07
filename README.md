# delta-clientes-sql

This repository provides an SQL script that exports detailed information about clients from the CEMAR database. The query brings installation data, personal details and contact information and also counts open invoices for each account.

## Running the script

1. Connect to the Oracle database using `sqlplus`, `SQLcl` or another compatible client.
2. Execute the script:
   ```
   @delta_clientes.sql
   ```
3. Redirect the output if you want to save the results. For example:
   ```
   sqlplus user/password@database @delta_clientes.sql > clientes.csv
   ```
