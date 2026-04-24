# DAX Measures

```DAX
Total Customers = DISTINCTCOUNT(CreditData[customer_id])
```

```DAX
Total Applications = COUNTROWS(CreditData)
```

```DAX
Approved Applications = CALCULATE(COUNTROWS(CreditData), CreditData[approved] = 1)
```

```DAX
Approval Rate = DIVIDE([Approved Applications], [Total Applications], 0)
```

```DAX
Defaulted Customers = CALCULATE(COUNTROWS(CreditData), CreditData[default] = 1)
```

```DAX
Default Rate = DIVIDE([Defaulted Customers], [Total Applications], 0)
```

```DAX
Average Score = AVERAGE(CreditData[score])
```

```DAX
Total Revenue = SUM(CreditData[revenue])
```

```DAX
Total Cost = SUM(CreditData[cost])
```

```DAX
Estimated Profit = [Total Revenue] - [Total Cost]
```

```DAX
Profit Margin = DIVIDE([Estimated Profit], [Total Revenue], 0)
```

```DAX
Average Credit Amount = AVERAGE(CreditData[credit_amount])
```

```DAX
Average DTI = AVERAGE(CreditData[debt_to_income_ratio])
```
