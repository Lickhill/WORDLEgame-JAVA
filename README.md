# Wordle Game in Java

## Overview
This project is a simple Java-based implementation of the popular word-guessing game Wordle. Players have five attempts to guess a randomly chosen 5-letter word. Feedback is provided for each guess:

- Letters in the correct position are enclosed in `|`.
- Correct letters in the wrong position are enclosed in `*`.
- Incorrect letters are displayed without symbols.

## Prerequisites

### Hardware Requirements
- **RAM**: At least 128 MB
- **Disk Space**: 124 MB for JRE, 2 MB for Java Update
- **Processor**: Minimum Pentium 2 266 MHz processor.

### Software Requirements
- **Java Development Kit (JDK)**: Ensure JDK is installed on your system. Recommended version: JDK 11 or higher.
- **Text Editor**: Use any text editor like Notepad++, TextPad, or IDEs like IntelliJ IDEA or Eclipse.
- **Terminal**: Command Prompt (Windows) or Shell (Linux/Mac) to compile and run the program.

## Installation

### Step 1: Install Java
Download the JDK from the Oracle website or OpenJDK.

Follow installation instructions based on your operating system:

- **Windows**: Run the .exe file and set environment variables (JAVA_HOME).
- **Mac/Linux**: Use .dmg files for Mac or package managers like `apt` for Linux.

### Step 2: Set Up Environment
Verify Java installation:

```bash
java -version
```

Install a text editor or IDE of your choice.

### Step 3: Compile and Run the Program
Save the provided code as `Wordle.java`.

Compile the program:

```bash
javac Wordle.java
```

Run the program:

```bash
java Wordle
```

## Working Commands
Below are essential commands used in this project:

- **Compile Java Code**:

```bash
javac Wordle.java
```

- **Run Java Code**:

```bash
java Wordle
```

- **Check Installed Java Version**:

```bash
java -version
```

## Algorithm
### Step-by-Step Process:
1. Initialize Variables:
   - Randomly select a word from a predefined list.
   - Set up counters and feedback mechanisms.
   
2. Input Validation:
   - Ensure user input is exactly 5 letters.
   
3. Feedback Generation:
   - Compare each letter of the input with the target word.
   - Provide feedback using symbols (`|`, `*`, or plain text).
   
4. Win/Loss Condition:
   - If the user guesses correctly within five attempts, display success message.
   - Otherwise, reveal the correct word after five failed attempts.

### Pseudocode:

## START
-Generate random word from predefined list.
-Prompt user to guess a word.
-Validate input length (must be 5 characters).
-Compare guessed word with target word:
-Use "|" for correct letter and position.
-Use "" for correct letter but incorrect position.
-Display incorrect letters without symbols.
-If guessed correctly, display success message and exit.
-Repeat steps until all attempts are exhausted.
-Display failure message and reveal correct word.
END


## Example Usage
When you run the program, it will look like this:


-WELCOME TO THIS GAME OF WORDLE
-YOU WILL BE GIVEN 5 CHANCES TO GUESS A 5 LETTER WORD
-Enter your guesses below:
-Guess #1: hello
-Output: h e l l o
-Irrelevant Letters: /h/ /l/ /o/
-Guess #2: world
-Output: w |o| r l d
-Irrelevant Letters: /r/ /l/ /d/


## Troubleshooting
- Ensure Java is installed and properly configured (`java -version`).
- Check that `Wordle.java` is saved in the correct directory before compiling.
- Verify that input words are exactly five characters long.

## License
This project is distributed under the MIT License.

## Contact Information
For questions or support, contact:

- **Name**: Likhil N Maiya
- **Email**: likhilnm17103@gmail.com
- **GitHub**: https://github.com/lickhill
  
