# Data Science Challenge

## Business Setting

A client is an owner of a fleet of machinery and is looking for a solution to optimize the expenses related to the equipment breakdown. If breakdown happens, the production stops. Each stop costs 10.000 EUR. The client collected historical data from the equipment, where each equipment unit was operated until breakdown and asks for a small proof of concept (PoC) that should give insight into the accuracy of predictions if a certain unit going to break down within next 20 cycles.

The client provides us with a historical dataset and its description:

column_1 - equipment unit id,  
column_2 - unit operating cycle,

rest of the columns are sensor values.

Additionally, the client gives us a snapshot dataset of currently running working machinery and asks us to identify if each unique equipment unit is going to break down within next 20 cycles.

## Tasks

- Create a solution for the client using best data science and coding practices, where predictions for the snapshot dataset could be given for each unique unit as 1 (for yes, it will fail during next 20 cycles) or 0 (for no). Use table format with 2 columns (unit, prediction).
