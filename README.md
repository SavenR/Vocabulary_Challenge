# Vocabulary_Challenge
A simple two player vocabulary game

v1
  - Two users connect from different clients
  - One player is randomly selected to go first ("Player 1")
  - Completes one round for every word
  - Round:
     - One word is randomly selected from the set and presented to the 
     users along with four unique definitions (1 correct 3 random from
     within the set).
     - The Player 1 is able to interact with the game and guess the
     correct word for 10 points.
       - The other player is able to see what Player 1 selects
     - If Player 1 guesses incorrectly, the other player is allowed to
     guess for 20 points
     - If neither player guesses correctly, the correct answer is
     indicated (highlighted and made bold), and the round ends without
     either player receiving points.
     - The other player is now made the active player
     
  - Preloaded with 10 themed sets of 6 word/definition pairs
  
Technology
  - Backend: Django for managing sets of words, ng-routes for routing, 
  Postgres for DB
  - Frontend: Angular for randomly selecting word, creating an array 
  containing the correct definition and 3 more random definitions from
  the set.
  - Interface: ng-Bootstrap, jQLite (from Angular)
  - Sockets: ???
  
