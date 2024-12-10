# SolutionsProgrammingAssignments
# Solutions Programming Assignments

This repository contains solutions to various programming assignments that demonstrate my problem-solving and coding skills. Each folder represents a specific assignment, including the code and documentation.

## Assignments
- [Assignment 1: Palindrome Checker](./Assignment1_PalindromeChecker/): A Python solution to check whether a string is a palindrome.

## Contact
For any questions or additional details, feel free to reach out: [shafieabdulkadir441@gmmail.com](mailto:your-email@example.com)
# Assignment 1: Palindrome Checker

## Problem Statement
Write a Python program that checks whether a given string is a palindrome. A palindrome is a word, phrase, or sequence that reads the same backward as forward.

## How to Run
1. Navigate to the `Assignment1_PalindromeChecker` folder.
2. Run the script using the following command:
def is_palindrome(string):
    """
    Determines if a given string is a palindrome.
    :param string: Input string
    :return: True if palindrome, False otherwise
    """
    return string == string[::-1]

if __name__ == "__main__":
    user_input = input("Enter a string: ")
    if is_palindrome(user_input):
        print("The string is a palindrome!")
    else:
        print("The string is not a palindrome.")
