# Names of counterparties
## Data
The names of counterparties from the bank statement are given in different spelling formats
## Task
The customer's accounting program requires extracting the names of its counterparties according to a certain principle. The principle is the following:
> **Raw Name**          > | > **Output**      > | **Description**
> ____________________________________________________
> АО "Р-БАНК"       > | > Р-БАНК, АО  > | 
## Libraries
* *re*
* *pandas*
* *numpy*
To extract the name and form of ownership of the organization from the raw line and present them in the following form:
