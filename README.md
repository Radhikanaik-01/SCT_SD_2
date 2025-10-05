This C++ program is a simple **Number Guessing Game** that allows the user to guess a randomly generated number between **1 and 100**. It uses the `rand()` function from the C++ standard library to generate a random number and the `srand(time(0))` function to ensure that each program run produces a different random number by seeding it with the current system time.

When the program starts, it prompts the user with a message: *“Guess the number between 1 and 100:”*. The user then enters a number, and the program compares the user’s guess with the randomly generated number. If the guess is higher than the actual number, it displays *“Too high! Try again:”*. If the guess is lower, it shows *“Too low! Try again:”*. This process continues in a loop until the user correctly guesses the number, upon which the program displays *“Congratulations! You guessed the number.”*

The logic of the program is implemented using a `do-while` loop, which ensures that the guessing process repeats until the correct number is guessed. The program demonstrates key C++ concepts such as random number generation, conditional statements (`if-else`), loops, and user input/output handling using `cin` and `cout`.

To run this program, you can compile it using a C++ compiler. In a terminal, type:
`g++ number_guessing_game.cpp -o number_guessing_game`
and then execute it with:
`./number_guessing_game`

Each time you run the program, it generates a new random number, making the game fun and unpredictable. This project is ideal for beginners who want to understand loops, conditions, and basic game logic in C++.
