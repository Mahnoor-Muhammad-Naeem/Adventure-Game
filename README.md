# Adventure-Game
This project is named "Adventure Game", a simple text-based game created using Python. It allows users to make choices and navigate through different scenarios, leading to various outcomes based on their decisions. Below is the breakdown of the functionality and flow of the game:

Welcome Message:

The game starts by asking the player to input their name using input() and greets them with a personalized message.
Example: If the player types "Alex," it prints:
"Hello Alex welcome to my game!"
Playing Decision:

The game asks the player if they want to play by entering either "yes" or "no."
If the player types "yes" (or "y"), the game proceeds. Otherwise, it ends with the message:
"We are NOT playing..."
First Choice - Direction:

If the player chooses to play, they are asked to decide whether to go "left" or "right."
If 'left':
The player falls off a cliff, and the game ends with the message:
"You went left and fell off a cliff, game over, try again."
If 'right':
The player moves forward to the next scenario.
Second Choice - Bridge:

After choosing "right," the player encounters a bridge and must decide:
Swim under it:
They are eaten by an alligator, ending the game with:
"You got eaten by an alligator, you die, the end!"
Cross the bridge:
They find the gold and win the game with:
"You found the gold and won!"
Invalid Inputs:

If the player enters anything other than "left" or "right" for the direction choice, they are informed with the message:
"Sorry not a valid reply, you die!"
Game Ending:

The game provides multiple endings based on the player's choices, creating an interactive experience.
Key Features:
User interaction through input().
Decision-making with conditional statements (if, elif, else).
A personalized experience by including the player's name.
Simple and engaging gameplay with branching scenarios.
This game demonstrates basic Python programming concepts like input handling, string manipulation, and conditional logic, making it a great beginner-level project!
