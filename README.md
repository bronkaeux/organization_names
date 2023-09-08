# Names of counterparties
## Data
The names of counterparties from the bank statement are given in different spelling formats
## Task
The customer's accounting program requires extracting the names of its counterparties according to a certain principle. The principle is the following:  
| Raw name | Output | Description |
| ---------|--------|-------------|
| АО "Р-БАНК" | Р-БАНК, АО | Main organization's name, Form of ownership (abbreviated) |
| Индивидуальный Предприниматель Логинов Андрей Николаевич | Логинов А., ИП | Surname Name (1st letter), Form of ownership (abbreviated) |
| текст // ИЗМАЙЛОВ ВАЛЕРИЙ МИХАЙЛОВИЧ // текст | Измайлов В. | Surname Name (1st letter) |
| ООО "КОМПАНИЯ "УЗОР" | УЗОР, КОМПАНИЯ, ООО | Main organization's name, Middle name, Form of ownership (abbreviated) |
| ЗАКРЫТОЕ АКЦИОНЕРНОЕ ОБЩЕСТВО "Трио" | Трио, ЗАО | Main organization's name, Form of ownership (abbreviated) |
| МИ ФНС РОССИИ ПО УПРАВЛЕНИЮ ДОЛГОМ | ФНС | raw name contains "FNS" |
## Libraries
* *re*
* *pandas*
* *numpy*
