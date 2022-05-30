# Inheritance and Polymorphism**Exercise statement:**
Write a program to read the data of `N` taxpayers (`N` provided by the user), which can be `individuals` or `legal entities`, and then show the tax amount paid by each one and the total tax collected.

The individual data are `name, annual income, and health expenses`. Legal entity data are `name, annual income, and the number of employees`. The rules for tax calculation are as follows:

Individuals: people whose income was below `20000.00` pay `15%` tax. People with income from `20000.00` onwards pay `25%` tax. If the person had health expenses, `50%` of these expenses are deducted from the tax. Example: a person whose income was `50000.00` and had `2000.00` in healthcare expenses, the tax is: `(50000 * 25%) - (2000 * 50%) = 11500.00`

Legal entity: legal entities pay `16%` tax. However, if the company has more than `10` employees, it pays `14%` tax. Example: a company whose income was `400000.00` and has `25` employees, the tax is: `400000 * 14% = 56000.00`### Exemplo

```
Enter the number of tax payers: 3
Tax payer #1 data:
Individual or company (i/c)? i
Name: Alex
Anual income: 50000.00
Health expenditures: 2000.00
Tax payer #2 data:
Individual or company (i/c)? c
Name: SoftTech
Anual income: 400000.00
Number of employees: 25
Tax payer #3 data:
Individual or company (i/c)? i
Name: Bob
Anual income: 120000.00
Health expenditures: 1000.00

TAXES PAID:
Alex: $ 11500.00
SoftTech: $ 56000.00
Bob: $ 29500.00

TOTAL TAXES: $ 97000.00
```

### Diagrama

![myImage](https://github.com/devsuperior/aulao007/raw/master/domain-model.png)