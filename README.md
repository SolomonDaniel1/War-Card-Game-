War Card Game (iOS)
This is a digital version of the classic "War" card game, built for iOS using Swift and SwiftUI. In this version, a player competes against CPU to win cards based on card values. The player and the machine each draw a card, and the highest card wins both. If the cards are tied, a "war" occurs, where additional cards are drawn until a winner is determined. The game ends when the player or the machine collects all the cards.
Features:
Player vs Machine: The game pits the player against a machine opponent.
Card Deck: A full deck of 52 cards (no jokers) is used.
Game Flow: The game continues until either the player or the machine wins all cards.
Smooth Animations: Cards flip and animate with smooth transitions for a better visual experience.

Technologies Used:
Swift: The primary programming language used for game logic, including card comparison, shuffling, and managing the game state.
SwiftUI: The UI framework used for building the user interface in a declarative manner.
UIKit: Used alongside SwiftUI to handle animations and card flip transitions for a seamless experience.

Game Flow:
Start the Game: When the app launches, the player starts a new game against the machine.
Draw Cards: Each round, both the player and the machine draw one card. The card values are compared, and the higher card wins the round. Tied cards result in a "war" scenario.
War Scenario: In case of a tie, both the player and machine draw three additional cards each, and the winner of the subsequent round takes all six cards.
End of Game: The game continues until one player (either the human or the machine) wins all the cards.

