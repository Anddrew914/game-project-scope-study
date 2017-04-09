# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
- [Imgur](http://imgur.com/a/WXDHt)
-
-   The data structure you plan to use.
- I'm planning on using an array to represent the board similar to the boggle
- challenge. I'm also going to use a series of arrays to represent winning
- combinations and compare the board to those winning combinations at each turn.
- Player data will be stored as objects with User, number of games v current player
- , number of wins v current player and possibly number of wins and games total.
- User password and login info will be stored via the API rails server.
-
-   How you will take the markup of the game board and represent it in JS
- Orininally I was going to use an image of a tic tac toe board as my background
- image on the website and I was going to super impose an invisible div grid
- over that image. I think in the project guidlines however I was told I have to
- render the board. I'm not sure if that means a specific thing and if this precludes
- that option. Either way, divs will be gotten via jquery, pushed to a players
- "in play" array and compared to the "winning" array at every move.
-
-   How you plan to approach this project.
- I'm going to follow the recommended benchmarks! I also plan on looking at many
- examples online for solutions to the game engine. I've thought of my own solutions
- as well (outlined roughly above)but I don't think there's a good reason not to
- see how other people havedone it.
-
-   4-8 user stories for your game project.
- As a user, I can visit Andrews website and play tic tac toe.
- As a user, I can create a user name and log in to Andrews website.
- As a user, I can change my password on Andrews website.
- As a user, I can compete against another person on the same machine.
- As a user, I can (hopefully) compete aganst another person online.
- As a user, I can track my wins and losses against a single player, and
  - against all players.

-
-   How you plan to keep your code modular.
- By following the given JS template I can separate my codes functions into different
- files. Within files I'll use function variables and callbacks to allow my code
- to be used in each scenario for each player.
-
-   What creative spin will you add to your project?
- I have several stretch goals. I'd like to add a blitz clock that declares a winner
- in case of a tie (Cause no one wants a tie) and I'd like to add icons for each player.
- I'd like to animate the board with a drawing effect for the x's and o's and I'd like to
- add sounds to the animations. I'd also like my website in general to look modern and high
- quality.
-
-   How will you use version control to backup / track your project?
- Commit early commit often! Branch for new features!
-
-   Do you plan to attempt any of the bonuses?
- If I can, certainly!

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
