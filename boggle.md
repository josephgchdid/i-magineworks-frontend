

# I-magine works frontend assessment 

The purpose of this assesment is to test the following skills in an applicant : 

<ul>

  <li> Logical thinking  </li>

  <li> Ability to write clean code  </li>

  
</ul>


In this assesment you are required to create a word based board game called 
Boggle in react 

The game begins with an NxN board where N >= 4, each square on the board is a random 
letter, the player has to construct as much words as he can from the board that fit the 
following criteria before a timer runs out: 
<ul>

   <li> Words must be at least three letters in length.  </li>
   <li> Each letter must be a horizontal, vertical, or diagonal neighbor of the one before it. </li>
   <li>
      No individual letter square may be used more than once in a word.
   </li>
   <li>No capitalized words or hyphenated words are allowed.</li>
</ul>

For more information about the game, refer to this [Wikipedia](https://en.wikipedia.org/wiki/Boggle)

To save time there is no need to make it a 2 player game and instead just make it 
where you play against yourself 

When the player is done constructing the word , they will press a submit button 
that will validate their word 

To validate if the word is correct or not , you will use a dictionary Api found 
[here](https://dictionaryapi.dev/)

When the timer is done , the player is prompted with the total correct words guessed  and 
the total incorrect tries and asked if they would like to try again. 

the initial page just has an input and a button, the player chooses the desired duration 

for the timer ( minimum is 1 minute ) and when they press the button they are redirected to 
the game page where the timer is initialized to their chosen time

## Project requirements 

1 - The project must be in React 

2 - No other Node packages can be used ( Except styling libraries mentioned in the next point)

3 - You can use Bootstrap/Tailwind or any other styling libraries that you prefer 

4 - You must use MVC architecture 

## Extra points

1 - Implement the project in Typescript instead of Javascript 

2 - Stunning and well designed UI

3 - Optimal and efficient solution is used for the logic
