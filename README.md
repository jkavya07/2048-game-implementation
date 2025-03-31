# 2048-game-implementation
2048 Game
This repository contains a web-based implementation of the popular 2048 game.

Features

Classic 2048 gameplay
Responsive design for desktop and mobile
Smooth animations
Undo feature (if implemented)
Score tracking
AI-powered gameplay using the Expectimax algorithm

How to Play

Use the arrow keys (or swipe on mobile) to move the tiles.
Tiles with the same number merge when they touch.
Reach 2048 to win the game!

AI Algorithm

This implementation includes an AI using the Expectimax algorithm, which is commonly used in decision-making problems involving uncertainty. Unlike Minimax, Expectimax does not assume an optimal opponent but instead considers the probability of different outcomes. The AI evaluates possible moves by:
Simulating all possible moves.
Estimating the expected value of each move by considering the probability of new tile placements.
Choosing the move with the highest expected value.
This approach allows the AI to perform well in uncertain environments like 2048.
Installation & Usage

Clone the repository:

git clone https://github.com/jkavya07/2048-game-implementation.git

Save & Open 2048.html in a web browser to start playing.

Acknowledgments

Inspired by the original 2048 game
Built using HTML, CSS, and JavaScript.
