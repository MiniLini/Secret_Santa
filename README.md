# Secret Santa Program

This Java-based Secret Santa program assigns each participant a unique moniker and pairs them with another participant as their gift recipient. The program ensures anonymity and prevents self-assignment.

## Features

- Assigns unique monikers to participants for added fun and anonymity.
- Ensures participants do not get themselves as their Secret Santa.
- Randomized pairing of participants.
- Cross-platform console screen clearing for privacy during entry.

## Prerequisites

1. **Java Development Kit (JDK)**: Ensure JDK 8 or higher is installed.

   - Download from [Oracle's Java SE Downloads](https://www.oracle.com/java/technologies/javase-downloads.html) or use OpenJDK.

2. **IDE or Text Editor**:

   - Use an IDE like IntelliJ IDEA, Eclipse, or a text editor like VS Code to run the program.

## Files

- **`SecretSanta.java`**: The main program file.
- **Executable ************`.exe`************ (Optional)**: To be added for easier use without compiling.

## How to Run

### Using the Source Code

1. Clone the repository or download the `SecretSanta.java` file.
2. Open a terminal/command prompt and navigate to the folder containing `SecretSanta.java`.
3. Compile the program:
   ```
   javac SecretSanta.java
   ```
4. Run the program:
   ```
   java SecretSanta
   ```

### Using the Executable

(If available)

1. Download the `.exe` file from the repository.
2. Double-click the file to execute.

## Program Flow

1. **Input Participants:**

   - Participants enter their names one by one.
   - Each participant is assigned a unique moniker from a predefined list.

2. **Anonymity and Privacy:**

   - The console screen clears after each participant's input to maintain privacy.

3. **Pairing Secret Santas:**

   - Randomized pairing ensures that each Santa is assigned a recipient.
   - Self-assignment is avoided by reshuffling if necessary.

4. **Display Results:**

   - The program outputs moniker-based assignments.

## Example Output

```
Santa #1, what is your name? (type done when there are no more Santas left)
> John
Your unique moniker is: Rudolph the Red-Nosed Reindeer
Press Enter to clear the screen for the next person.

...

Secret Santa Assignments:
"Rudolph the Red-Nosed Reindeer" gives a gift to "Jane"
"Frosty the Snowman" gives a gift to "John"
```

## Moniker List

Participants are randomly assigned one of the following fun monikers:

- Rudolph the Red-Nosed Reindeer
- Frosty the Snowman
- Olaf
- Cindy Lou Who
- Charlie Brown
- The Nutcracker
- Jack Skellington
- Dasher, Dancer, Prancer, Vixen, Comet, Cupid, Donner, Blitzen

## Technical Notes

### Platform Compatibility

- The program clears the console screen using platform-specific commands:
  - **Windows**: Uses `cls`
  - **Linux/macOS**: Uses `clear`

### Error Handling

- If an error occurs during screen clearing, the program displays an error message and continues execution.

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**. See the `LICENSE` file for details.

## Contribution

Contributions are welcome! Feel free to fork the repository, make your changes, and submit a pull request.

## Contact

For questions or suggestions, please open an issue in the repository.

---

Happy Gifting!

i also need to separate these files as i will have different versions of this program, a java file and a android sdk

