I've filled in all the date function formulas for the exercise. Here's a summary of what each formula does:

| Cell | Description | Formula |
|------|-------------|---------|
| G73 | Today's date | `=TODAY()` |
| G74 | Current date & time | `=NOW()` |
| G75 | Year from Project Start | `=YEAR(B73)` → 2024 |
| G76 | Month from Project Start | `=MONTH(B73)` → 1 |
| G77 | Day from Project Start | `=DAY(B73)` → 15 |
| G78 | Create date (2024, 12, 25) | `=DATE(2024,12,25)` |
| G79 | Day of week (1=Sun) | `=WEEKDAY(B73,1)` → 2 (Monday) |
| G80 | End of Project Start month | `=EOMONTH(B73,0)` → Jan 31, 2024 |
| G81 | Working days (Start to End) | `=NETWORKDAYS(B73,B74)` → 120 days |
| G82 | Years employed | `=DATEDIF(B75,TODAY(),"Y")` → 6 years |
| G83 | Age from Birthday | `=DATEDIF(B76,TODAY(),"Y")` → 35 years |
| G84 | 3 months after Start | `=EDATE(B73,3)` → Apr 15, 2024 |

The cells will display as dates/numbers based on Excel's formatting. You may want to format the date cells appropriately to see the results clearly.
