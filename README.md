# Reverse-Hangman-Game
A game I call "Reverse Hangman" programmed in Eek! and NOO! [(Download Eek! and NOO!)](https://github.com/ZeroPlayerRodent/Eek-Esolang)

Or use an in-browser interpreter! [(Eek!)](https://vilgotanl.github.io/Esolang-implementations/js/eek/index.html#RWVlZWVlZUVlZUVlZUVlZUVlZUVlZUVlZUVlZUVlZUVlZUVlZUVlRWVFZUVlRWVlZUVlZWVlZWVlZWVrIQ==)
[(NOO!)](https://zeroplayerrodent.github.io/NOO-Browser-Interpreter/#Tk9PT09PT05PT05PT05PT05PT05PT05PT05PT05PTk9OT09PTk9PT09PT09PTyEKTk9PT09PT05PT05PT05PT05PT05PT05PT05PT05PT05PT05PT05PTk9PT05PT09PT09PT08hCk5PT09PT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT05PTk9OT05PTk9OT05PTk9PT05PT09PT09PT08hCk5PT09PT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT05PTk9OT05PTk9OT05PTk9PT05PT09PT09PT08hCk5PT09PT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT05PT09OT09PT09PT09PIQpOT09PT09PTk9PTk9PTk9PTk9PTk9OT05PTk9OT09PTk9PT09PT09PTyEKTk9PT09PT05PT05PT05PT05PTk9OT09PTk9PT09PT09PTyEKTk9PT09PT05PT05PT05PT05PT05PT05PT05PT05PT05PT05PT05PT05PTk9OT05PTk9OT05PTk9OT05PT09OT09PT09PT09PIQpOT09PT09PTk9PTk9PTk9PTk9PTk9PTk9PTk9PTk9PTk9PTk9PTk9PTk9OT09PTk9PT09PT09PTyEKTk9PT09PT05PT05PT05PT05PT05PT05PT05PT05PT05PT05PT05PT05PTk9OT05PTk9PT05PT09PT09PT08hCk5PT09PT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT05PTk9OT05PTk9OT05PTk9PT05PT09PT09PT08hCk5PT09PT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT09OT09PTk9PT09PT09PTyEKTk9PT09PT05PT05PT05PT05PTk9OT05PT09OT09PT09PT09PIQpOT09PT09PT09PT09PT09PT09PT09PIQ==)

Instead of guessing letters to find a secret word like in normal hangman, this game has you guessing words to find a secret letter!

Type a word in all lowercase, and the program will output "!" if the secret letter was in the word you typed. It will output "!" as many times as the letter appeared in the word. For example, if the secret letter was "o" the word "cool" would result in the program outputting "!!".

You have a limit of 60 letters you can use in all your guesses. For example, if you guessed "cool" as your first guess, your letter count would go down to 55. (The newline at the end of a guess counts as a letter!) If the letter count reaches 0, you lose. After each guess the game will tell you how many letters you have left. When you lose, it will tell you what the secret letter was. (Currently only available in NOO! version)

