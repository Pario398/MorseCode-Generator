# MorseCode-Generator

This is a Java program that converts a given phrase into Morse Code. The program uses a HashMap to store the mapping of characters to their corresponding Morse Code representations. It reads user input, converts the input phrase to uppercase, and then looks up the Morse Code for each character. The resulting Morse Code is displayed as the output.

# Table of Contents

- [How to use](#how-to-use)
- [Code Explaination](#code-explaination)
- [Example](#examples)


## How to use
1. Save the Java code in a file named `morsecode.java`
2. Ensure you have Java installed on your system.
3. Open a terminal or command prompt and navigate to the directory containing the `morsecode.java` file.
4. Compile the Java program using the Javac command:
   ```bash
   javac morsecode.java
   ```
5. Run the program using the Java command:
   ```bash
   java morsecode
   ```
6. The program will prompt you to enter a phrase to convert into Morse Code.
7. Enter the desired phrase and press Enter.
8. The program will display the corresponding Morse Code representation of the input phrase.

## Code Explanation:

* `morseCodeMap`: A static HashMap used to store the mapping of characters to their corresponding Morse Code representations. The static initializer block is used to populate this map with the necessary mappings.

* `main` method: The entry point of the program. It prompts the user to enter a phrase and then calls the `toMorseCode` method to convert the phrase into Morse Code. The resulting Morse Code is then displayed on the screen.

* `toMorseCode` method: This method takes a string input and converts it into Morse Code. It converts the input string to uppercase and iterates through each character. If the character exists in the `morseCodeMap`, it appends the corresponding Morse Code to the result string.

## Examples:
```bash
javac morsecode.java
java morsecode
Enter a phrase to convert into MorseCode : Hello World
Morse Code: .... . .-.. .-.. ---   .-- --- .-. .-.. -..
```
