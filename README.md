Printf Project 

Printf Function Project
Description

In this project we have remade the printf function in C from scratch. The printf function in C is a powerful tool for formatting and printing various types of data. By creating our version of printf, we have gained a deep understanding of C programming, string formatting, and handling variadic arguments.

Getting Started

#Install gcc or clang compiler

#Clone our repo

#Features
-> Supports basic format specifiers: '%d', '%s', '%c', '%f', etc.
-> Handles variadic arguments for different format specifiers.
-> Supports flags for string formatting, such as left-justification and width.

#How It Works

1. The custom_printf function takes a format string and variable arguments, just like the standard printf function.

2. It parses the format string to identify format specifiers (e.g., 
'%d', '%s', '%c') and processes them one by one.

3. For each format specifier, the function extracts the corresponding arguments from the variadic argument list and converts them to the appropriate data types.

4. It formats the data according to the specified flags (if any) for correct alignment and precision.

5. Finally, the formatted data is printed to the standard output.
