📋 Description

This C library offers a collection of fundamental string manipulation functions implemented from scratch. It demonstrates low-level string handling, memory management, and common operations without relying on the standard string library.
✨ Features

    String Length Calculation: Safe character counting

    String Copy: Manual string duplication with allocation

    Character Replacement: Multi-character substitution functionality

    String Concatenation: Safe string joining with proper memory allocation

    Memory Management: Manual allocation and deallocation control
    
📚 API Reference

str_count(char *word)

Calculates the length of a string. Returns 0 for NULL or empty strings.
str_cpy(char *word)

Creates a duplicate of the input string. Returns NULL if input is invalid.
str_replace(char *word, char *lettersToReplace, char substitute)

Replaces all occurrences of specified characters with a substitute character.
str_conc(char *firstWord, char *secondWord)

Concatenates two strings into a new allocated string.
🛠️ Compilation
bash

gcc -Wall -Wextra -std=c99 -o string_demo main.c string_lib.c

💡 Key Features

    Null Safety: Proper handling of null pointers and empty strings

    Memory Safety: Manual memory management with malloc/free

    No External Dependencies: Pure C implementation

    Educational Value: Demonstrates low-level string manipulation

⚠️ Important Notes

    Remember to free all memory allocated by functions

    All functions return NULL on error conditions

    Input strings must be null-terminated

    Replacement function replaces all occurrences of any character in the replacement set

📋 Requirements

    C99 compatible compiler

    Standard C library
