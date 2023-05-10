# Practicum Data Science Project
## Prepaid Package Analysis

Telecommunications operator Megaline offers its customers two prepaid packages, Surf and Ultimate. The advertising department wants to know which prepaid package generates more revenue in order to adjust the advertising budget.

As an analyst, you will conduct an initial analysis for these prepaid packages based on a relatively small sample of Megaline customers. You will have 500 data points of Megaline customers: who they are, where they are from, what package they use, as well as the number of calls and messages they sent in 2018. Your task is to analyze customer behavior and determine which prepaid package brings in more revenue.

**Prepaid Package Description**<br>
Note: Megaline rounds seconds to minutes and megabits to gigabits. For calls, each individual call is rounded up: even if the call lasts only one second, it will be counted as one minute. For web traffic, each web session is not rounded up. However, the total for the month is rounded up. If a user consumes 1025 megabits this month, they will be charged for 2 gigabits.

**Surf:**
1. Monthly cost: \$20
2. 500 minutes of call duration per month, 50 SMS, and 15 GB data
3. After exceeding the package limits, the following charges apply:
 * 1 minute: 3 cents
 * 1 SMS: 3 cents
 * 1 GB data: $10

**Ultimate:**
1. Monthly cost: \$70
2. 3000 minutes of call duration per month, 1000 SMS, and 30 GB data
3. After exceeding the package limits, the following charges apply:
 * 1 minute: 1 cent
 * 1 SMS: 1 cent
 * 1 GB data: $7
