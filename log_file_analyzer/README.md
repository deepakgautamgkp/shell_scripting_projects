Parse .log file

We check if the file exists.

Show first 10 lines using head (basic parsing).

Count errors/warnings

grep -i "error" → finds all lines with “error” (case-insensitive).

wc -l → counts how many times it appears.

Same for “warning”.

Extract logs from a specific date

User enters a date like 2025-09-07.

grep "$logdate" logfile.log prints all matching lines.
