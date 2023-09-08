# Names of counterparties
## Data
The names of counterparties from the bank statement are given in different spelling formats
## Task
The customer's accounting program requires extracting the names of its counterparties according to a certain principle. The principle is the following:  
| Raw name | Output | Description |
| ---------|--------|-------------|
| АО "Р-БАНК" | Р-БАНК, АО | Main organization's name, Form of ownership (abbreviated) |
| Индивидуальный Предприниматель Логинов Андрей Николаевич | Логинов А., ИП | Surname Name (1st letter), Form of ownership (abbreviated) |
|//ИЗМАЙЛОВ ВАЛЕРИЙ МИХАЙЛОВИЧ// | Измайлов В. | Surname Name (1st letter) |
## Libraries
* *re*
* *pandas*
* *numpy*
To extract the name and form of ownership of the organization from the raw line and present them in the following form:
