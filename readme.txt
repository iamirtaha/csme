# Number-to-Letter Converter in Python 
#### Video Demo:  https://youtu.be/z7_R_gbVrnU
#### Description:
Number-to-Letter Converter

This program defines a function convert_to_letters that takes a number as input and returns the corresponding letter based on a predefined mapping. The main function takes user input, converts it using the convert_to_letters function, and then displays the result. The program uses a simple dictionary for the number-to-letter mapping, and you can extend it by adding more mappings as needed.




Function: convert_to_letters

This function takes a single argument, number, representing the numerical input. Inside the function:

There's a dictionary named letter_mapping that associates numbers with their corresponding letters.
The function checks if the provided number exists in the dictionary. If it does, it returns the corresponding letter; otherwise, it returns a message indicating that the number is not mapped to a letter.
Function: main

The main function serves as the entry point of the program. Here's what it does:

Attempts to get a numerical input from the user using input.
Converts the input to an integer using int.
If the input is not a valid number, a ValueError is caught, and an error message is displayed.
Calls the convert_to_letters function with the input number.
Displays the result, combining the original number and its corresponding letter.
if __name__ == "__main__":

This line ensures that the main function is executed only if the script is run directly, not if it is imported as a module into another script. This is a common Python idiom that allows the script to be both reusable and executable.

User Interaction

The program prompts the user to enter a number. If the user provides a non-numeric input, an error message is displayed. Otherwise, the program converts the number to a letter using the convert_to_letters function and prints the result.

Extensibility

You can easily extend the program by adding more mappings to the letter_mapping dictionary. For example, you can add mappings for numbers 11 onwards. The program will gracefully handle cases where the input number is not in the current mapping.

Feel free to modify and expand the program based on your specific requirements. You can add more complex logic, error handling, or additional features to make it more robust or tailored to your needs.
