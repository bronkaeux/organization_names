# Names of counterparties
## Data
The names of counterparties from the bank statement are given in different spelling formats
## Task
The customer's accounting program requires extracting the names of its counterparties according to a certain principle. The principle is the following:\

**Raw Name**|**Output**|**Description**
_____________________________________________________________________________
АО "Р-БАНК"|Р-БАНК, АО| Main organization's name, Form of ownership (abbreviated)

Индивидуальный ПРЕДПРИНИМАТЕЛЬ|  |         
Логинов Андрей Николаевич|Логинов А., ИП| Surname Name (1st letter), Form of ownership (abbreviated)
## Libraries
* *re*
* *pandas*
* *numpy*
To extract the name and form of ownership of the organization from the raw line and present them in the following form:
