# point-getter

Design a game in which players can click house sigils to rack up points, with a specific point goal.

### MVP
The game should have four house sigils displayed as buttons on the page. ✅

The player should have a random number assigned as their `House Point Goal` at the beginning of the game. ✅

When a player clicks on a house sigil, it should add a specific amount of points to the `House Point Total`. ✅

This specific amount of points for each sigil is randomized at the beginning of every game. ✅

Your game should hide the amount of points assigned to each sigil until the player clicks that sigil. ✅

When the player clicks a sigil, update the player’s `House Point Total` count. ✅

The player wins if their `House Point Total` matches the `House Point Goal`. ✅

The player loses if their score goes above the `House Point Goal`. ✅

The game should restart whenever the player wins or loses. ✅

When the game begins again, the player should see a new `House Point Goal`, the sigils should have four new hidden values and `The House Point Total` should be reset to zero. ✅

Notes:
The `House Point Goal` shown at the start of the game should be between 19 - 250.
Each sigil should have a random hidden value between 1 - 21.

## Deployment

Launched with GitHub Pages. Can be viewed at https://reduncan.github.io/point-getter/

## Author

* **Robert Duncan** - Sole Developer
  * created base HTML and CSS 
  * implemented random number generator for goal and house buttons
  * created success and failure messages for points

## Acknowledgments

* Hannah Patellis for the Graphics

