# worktracker
This is a simple Excel sheet that allows tracking units of work performed over a longer period of time
The original usage was to track pages translated from a document, but the units could be anything from dollars, pieces, meters, weight, whatever...

Suggested usage:
1. Do not change anything in row 1, except the value of total units, target date or password.
Notes:
- Target date is best specified, by setting an absolute reference to a cell in column A (not row 1). E.g. in this table I use =$A$104. Following the recommendation can go a long way to prevent syntax errors.
- The password is something you set yourself in the ribbon menu using Review > Protect Sheet. It's value in the current sheet is "UnlockMe" (without quotes), but after unlocking you may set it to anything you'd like. Since it's meant only to prevent entering data that would destroy formatting/formulas, it's just a safety net, not meant to keep anything secret.
2. Do not change anything in row 2, except for A2.
3. Do not change anything in row 3, except for A3.
4. Next, change the starting date for your project and enter it into A2. Make sure you use a valid date format.
5. While A2 is selected, pull it down by dragging the handle in the right bottom corner of the cell down, until you've filled all your dates that you need (it will destroy the formatting for the weekends, but that's OK for now)
6. Adjust T1 to point to the correct date from column A using absolute cell reference (e.g. =$A$104)
7. Add additional lines from the last one that is filled, by copying formulas from the column range B to N.
8. After you're all done, make sure to re-protect the sheet with a password to prevent incidental damage to the table structure.
