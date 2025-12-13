# Shared Capitalism Project

## Description

Shared capitalism is an umbrella term encompassing plans that give workers a financial stake in their employers' success. Typically, shared capitalism refers to (1) employee stock ownership plans (ESOPs), (2) profit-sharing plans, and (3) stock bonuses. Data on shared capitalism is generally limited, and there is no official database that tracks its changes over time. This dataset seeks to address this gap by offering a comprehensive coverage of companies that provide these three plans from 1999 to 2024.

## Data Sources
The data are drawn from the Form 5500 filings from the [U.S. Department of Labor (EBSA)](https://www.dol.gov/agencies/ebsa/researchers/data). All organizations that offer any kind of employee benefit plans covered by ERISA (Employee Retirement Income Security Act) must fill out this form annually. I filter to only include firms that offer shared-capitalistic plans, which I 

## Variables

| Variable | Description |
|----------|-------------|
| `id` | Unique identifier |
| `plan_name` | Unique name of the plan |
| `start_year` | Year the plan was started |
| `sponsor_name` | Name of the sponsoring company |
| `street` | Street address of the sponsoring company |
| `city` | City of the sponsoring company |
| `state` | State of the sponsoring company |
| `zipcode` | Zip code of the sponsoring company |
| `phone_number` | Phone number of the sponsoring company |
| `collective_bargain` | Indicates if the plan is collectively bargained (0 = No, 1 = Yes) |
| `active_participants` | Number of active participants |
| `esop` | Employee stock ownership plan (0 = No, 1 = Yes) |
| `profit_sharing` | Profit sharing plan (0 = No, 1 = Yes) |
| `stock_bonus` | Stock bonus (0 = No, 1 = Yes) |
