This project is built using JavaScript and DOM manipulation. Here's how the game works:

1. The user selects **Rock**, **Paper**, or **Scissor** by clicking one of the buttons.
2. An event listener detects the click and captures the user's choice.
3. The computer randomly selects one of the three options using `Math.random()`.
4. The program compares the user's choice with the computer's choice.
5. If both choices are the same, the game ends in a draw.
6. Otherwise, the game determines the winner based on the standard Rock-Paper-Scissors rules.
7. The winner's score is updated dynamically on the webpage.
8. A result message is displayed with different colors:
   - 🟢 Green for a user win
   - 🔴 Red for a computer win
   - ⚪ Gray for a draw
9. The game continues, allowing the user to play multiple rounds without refreshing the page.
