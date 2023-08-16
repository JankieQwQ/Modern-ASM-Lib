# NEASM 2
*Coding standards for modern assembly.*

# Indent
Four Spaces are recommended for each indent. For line continuations, either align the content vertically, or use "hanging alignment", that is, use an extra indent on the additional line, and do not put arguments on the first line.

# Long
It is recommended that the length of each line be limited to a maximum of 79 characters.
For those that are not strictly structured (such as strings and comments), it is recommended to limit each line to a maximum of 72 characters.

# Code
Modern assembly should use ASCII encoding, and non-ASCII characters should not appear in the source file.

# Comments
Modern assembly uses' '; "As a comment, the comment content should be separated by a space from the comment symbol.

# Other Suggestions
- Using ASMP to import a modern assembled lib can greatly simplify your operation.
- Try to use comments to comment on magic numbers.
- Place two blank lines in the area of global declaration and function implementation.
- When using ASMP, you **must** set the first line of a modern assembly source file to blank.
