**Stone-Paper-Scissors Game in C**

**Description:**

This is a simple Stone-Paper-Scissors game implemented in C. The user plays against the computer, which randomly selects its choice. The game follows the standard rules:

Stone (s) beats Scissors (z)

Scissors (z) beats Paper (p)

Paper (p) beats Stone (s)

If both the user and computer choose the same option, it's a draw.

**How It Works:**

The program initializes a random seed using srand(time(NULL)) to ensure different results in each execution.

The computer randomly selects 's' (Stone), 'p' (Paper), or 'z' (Scissors).

The user is prompted to enter their choice ('s', 'p', or 'z').

The game() function determines the winner based on predefined rules.

The result is displayed, showing whether the user won, lost, or if the game was a draw.

**About srand() and rand():**

**srand(unsigned int seed):**

Initializes the random number generator.

Using srand(time(NULL)) ensures that each execution generates different random numbers.

**rand():**

Returns a pseudo-random integer.

The program uses rand() % 100 to generate a number between 0 and 99, which determines the computer's choice.

Sample Output

**Enter s for STONE, p for PAPER and z for SCISSOR
s
Wow! You have won the game!
You choose: s and Computer choose: z**

Issues and Improvements
**License:**

This project is open-source and can be modified or distributed freely.

**Author**

PARVATHALA GAYATHRI
