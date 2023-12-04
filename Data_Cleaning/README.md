# Text Cleaning using remove_backslash Function

This script demonstrates a simple text cleaning process using the `remove_backslash` function. The function is designed to remove specific patterns and retain certain characters from text data.

## Function Overview

The `remove_backslash` function performs the following operations:

### Patterns Removed:

- `\x97`: Removes occurrences of the hexadecimal escape sequence '\x97'.
- `\ufeff` and `\x92`: Removes specific patterns identified by hexadecimal escape sequences.

### Characters Retained:

- Alphabets: All alphabetical characters (both uppercase and lowercase) are retained.
- `<`, `>`, `/`, `[`, `]`, `,`, `'`, `"`, `?`, `-`: Retains these specific characters.
- Whitespace: Spaces and tabs are retained.

### Removed Characters:

Characters other than those specified above are removed from the text.

## Usage

1. **File Paths**: Specify the input CSV file path (`file_path`) and the desired output CSV file path (`output_file_path`).

2. **Read CSV**: Read the CSV file into a pandas DataFrame using `pd.read_csv()`.

3. **Text Cleaning**: Apply the `remove_backslash` function to the 'causal_text_w_pairs' column to clean the text.

4. **Print Original and Modified DataFrames**: Display the original and modified DataFrames, showing the 'causal_text_w_pairs' and 'cleaned_text' columns.

5. **Save to CSV**: Save the modified DataFrame to a new CSV file.
