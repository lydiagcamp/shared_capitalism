# Shared Capitalism in the United States (1999-2024)

## Description

This dataset represents the first comprehensive panel of Employee Stock Ownership Plans (ESOPs) in the United States that tracks the same plans over time (1999 to 2024). The panel was constructed using raw Form 5500 filings from the [U.S. Department of Labor (EBSA)](https://www.dol.gov/agencies/ebsa/researchers/data). All organizations that offer any kind of employee benefit plans covered by ERISA (Employee Retirement Income Security Act) must fill out this form annually. Since there is no universal unique identifier, plan names were matched across years using a combination of manual coding, fuzzy string matching, and AI-assisted standardization via OpenAI’s GPT-4o-mini model. This dataset aims to make research in shared capitalism more accessible by providing clean, comprehensive data on companies offering these plans from 1999 to 2024.



## Variables

| Variable | Description |
|----------|-------------|
| `id` | Unique identifier |
| `plan_name` | Unique name of the plan |
| `first_rec_year` | Year the plan was first recorded by the EBSA |
| `last_rec_year` | Year the plan was last recorded by the EBSA |
| `start_year` | Year the plan was started |
| `sponsor_name` | Name of the sponsoring company |
| `street` | Street address of the sponsoring company |
| `city` | City of the sponsoring company |
| `state` | State of the sponsoring company |
| `zipcode` | Zip code of the sponsoring company |
| `phone_number` | Phone number of the sponsoring company |
| `collective_bargain` | Indicates if the plan is collectively bargained (0 = No, 1 = Yes) |
