## Birthday Day Name Calculator

This Python script allows users to input their birthdate and a specified number of years into the future to calculate the day of the week on which their birthday falls for each of those years. The script utilizes the `datetime` module to handle date-related operations.

### How to Use:

1. Run the script.
2. Enter the day, month, and year of your birthday when prompted.
3. Enter the number of years into the future for which you want to calculate the day of the week for your birthday.
4. The script will then display the day of the week for your birthday for each year in the specified range.

### Example Output:

```plaintext
Enter the day of your birthday (e.g. 21): 17
Enter the month of your birthday (e.g. 4): 4
Enter the year of your birthday (e.g. 2000): 2023
Enter the number of years in the future to calculate the birthday day name for: 20

4/17/2023 falls on a Monday.
4/17/2024 falls on a Wednesday.
4/17/2025 falls on a Thursday.
4/17/2026 falls on a Friday.
4/17/2027 falls on a Saturday.
4/17/2028 falls on a Monday.
4/17/2029 falls on a Tuesday.
4/17/2030 falls on a Wednesday.
4/17/2031 falls on a Thursday.
4/17/2032 falls on a Saturday.
4/17/2033 falls on a Sunday.
4/17/2034 falls on a Monday.
4/17/2035 falls on a Tuesday.
4/17/2036 falls on a Thursday.
4/17/2037 falls on a Friday.
4/17/2038 falls on a Saturday.
4/17/2039 falls on a Sunday.
4/17/2040 falls on a Tuesday.
4/17/2041 falls on a Wednesday.
4/17/2042 falls on a Thursday.
```

### Note:

- The script uses the `strftime` method to format the day of the week (e.g., "Monday").
- It calculates the day of the week for each year in the range specified by the user.
- The current year is obtained using `datetime.datetime.now().year`.
