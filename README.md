# <img src="https://cloud.githubusercontent.com/assets/7833470/10423298/ea833a68-7079-11e5-84f8-0a925ab96893.png" width="60"> Project 0 - Browser Game


Over the next 3 days, we would like you to build a simple game in your browser using your newfound powers as a stylish, jQuery-slinging, frontend developer. 

Please Fork & Clone this repo and use it as your starting point.

## Guidelines

* **Assigned:** Friday, March 25th
* **Due:** Monday, March 28th @ 9:17am

**You will be working individually for this project**, but we encourage you to get help from your peers and even pair program on each other's projects when bugs arise.

**You must push your project to Github**, and we encourage you to also host it either using <a href="https://pages.github.com" target="_blank">Github Pages</a> or <a href="https://www.bitballoon.com" target="_blank">BitBalloon</a>.

**You will receive written instructor feedback** on this project. See the [feedback doc](feedback.md) for details.


### File Structure
* You'll need an `index.html`, `css/style.css`, and `js/app.js`. 
* Make sure your stylesheet and JavaScript files are linked in `index.html` (sanity check them!), and also include the CDNs you'll be using (e.g. Bootstrap, jQuery).


## Requirements

You'll have a choice of games and select one to develop for this project.  Each game will have the following core requirements.

### Core Requirements

**A user should be able to...**

* See a beautiful **game board** on the page
* **Reset the game** / start a new round
* See when the game is finished or won

**Technically, your game should include...***

* jQuery for listening to events and/or modifying the DOM

### Game Options

 Pick one of the following games to develop: 
 
 * [racing game](#racing-game)
 
 * [connect 4](#connect-4)
 
 * [battleship](#battleship)
 
 * [memory](#memory)

### Bonus Features

Please also attempt at least one bonus feature (or come up with your own!). You must complete all **core** requirements above, and all core requirements of the game you choose, before moving on to bonuses.

Some bonus ideas for any game are:

* Integrate **Object Oriented Programming** design patterns.
* Keep track of **multiple game rounds** with a win counter / leader board.
* Allow **player customization** (e.g. pick a name/symbol/color/avatar).
* Use <a href="https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage" target="_blank">localStorage</a> to **keep track of game state**, even if the user refreshes the page.
* Get creative with **inventive styling** (e.g. use css animations/transforms and hover effects, get creative with backgrounds).
* Timing: display a **countdown timer** ("3, 2, 1, Go!"), the winning time, or the best time.
* Integrate with a **3rd party API**: flickr, youtube, spotify, giphy, etc.



## Best Practices
* Take very small steps, and test things in your console as you go!
* **Wireframe** your page layout, and **whiteboard** the different components of your app (data, view/presentation logic, control logic, styles)
* Write **clean, well-indented code**! Follow this javascript [style guide](https://github.com/airbnb/javascript/tree/master/es5). Make sure you remove unused/commented code!
* Minimize the use of global variables.
* Abide by the **separation of concerns** principle with separate HTML, CSS, and JavaScript files.
* Use **class-based css** rules, and leverage CSS styling.
* Stick with the **KISS** (Keep It Simple Stupid) and **DRY** (Don’t Repeat Yourself) principles.
* **Commit early, and commit often**. Write commit messages that describe what you changed in each commit.
* Don't be afraid to **break your code**. Play in your console. Experiment.
* Write a helpful **`README.md`** that you or other developers can reference later. See [example-readme](example-readme.md) as a guide, and use this <a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet" target="_blank">markdown cheatsheet</a> to help with formatting.

## Racing Game

<img src="https://media.giphy.com/media/mHChlbqGMndYY/giphy.gif" width=400>

#### Minimum Viable Product

**In addition to the core requirements above, a user should be able to...**

* See at least **two players** on the board
* Press a key on their keyboard to **move their player** one square 
* See the name of the **winner** of the round

#### Bonus Ideas

* Race against **a bot**.
* **Instant replay**: record yourself and then race against yourself, in real-time.


## Connect 4

<img src="http://www.hamleys.com/images/_lib/connect-4-grid-10222-0-1417083604000.jpg" width=300>

#### Minimum Viable Product

**In addition to the core requirements above, a user should be able to...**

* Select a column to drop their piece down, and see the color change where it lands
* Alternate turns between two players

#### Bonus Ideas

* Play against **a bot**


## Battleship

<img src="http://blogs-images.forbes.com/erikkain/files/2012/02/battleship-board-game.jpg" width=300>

#### Minimum Viable Product

**In addition to the core requirements above, a user should be able to...**

* Select placement of their "ships" at the start of the game
* Alternate turns between two players
* Receive a message when they "hit" or "miss" the other player's ship
* Decide which square of the other player's board to target
* See their own ships with indicators of where the other player's guesses have hit and missed
* See where their guesses have hit and missed

#### Bonus Ideas

* Display a timer between turns so two players don't see each other's ships
* Play against **a bot**


#### Hints
* Start with just one size of ship
* Start by building a one-dimensional battleship game that takes place on a single row instead of a square grid




## Memory

<img src="https://img1.etsystatic.com/003/0/7146482/il_570xN.470573231_6gxw.jpg" width=400>

#### Minimum Viable Product

**In addition to the core requirements above, a user should be able to...**

* See a series of card "backs"
* Select two cards at once. If the cards match, both should stay revealed. Otherwise, both should be hidden again. 
* Win by matching all cards with their duplicates

#### Bonus Ideas

* Allow the user to do a search on giphy to get the card "fronts" for a round


