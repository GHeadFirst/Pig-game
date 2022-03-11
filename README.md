# Pig-game
Pig game is a simple JS game, where you roll dice between two players. First player to reach 100 wins. Each time you roll a 1 your current score resets, unless you hold your score. At which point the current score goes to your total score, and you end your turn, allowing the second player to roll the dice. 

if you want to change the winning score in the game, go to script.js and change the following:


if (scores[activePlayer] >= 100) {
      document.querySelector(`.player--${activePlayer}`).classList.add('player--winner')
      document.querySelector(`.player--${activePlayer}`).classList.remove('player--active')
      playing = false;
    }


Only change the number 100 to the number you want.
