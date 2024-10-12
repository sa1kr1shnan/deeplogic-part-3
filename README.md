Part 3: Debugging and Improving Extraction Logic
Approach:

Developed a robust function to extract invoice amounts.
Implemented multiple strategies to handle different formats.
Created comprehensive test cases to verify functionality.

Challenges:

Handling various formats of amount representation (numeric, currency symbol, words).
Dealing with potential missing or malformed data.

Solution:

Used regex for flexible matching of numeric amounts.
Implemented word-to-number conversion for amounts in words.
Added fallback to "N/A" for missing data.

Key Code Section:
python
