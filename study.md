# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
-   How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code modular.
-   What creative spin will you add to your project.
-   How you will use version control to backup / track your project.
-   Do you plan to attempt any of the bonuses.

_   Photo of wireframe is included in this repository.

_   I will use multiple variables (gameID = game id value, playerX = user id
    value, etc.) to store DOM info that will then be transmitted to the server
    through AJAX requests, particularly to place values into the array
    representing the game board. These same variables will again be used to
    store the information retreived from the server.

_   I want to use id's on ui divs and assigned data values to retrieve that
    div's value after a click, using $.val() and $.data(). This value will then
    be assigned to the corresponding game array for a given player.

_   I initially wanted to work out the game logic to begin, but on further
    reflection I decided to work from the outside in; settling the AJAX
    requests (using curl to interpret what I get back from the server) server
    side, and figuring out the basic HTML and CSS for the ui in order to set a
    template for how user input is handle. From there I will work inward,
    figuring out event handlers, game logic functions, etc.

_   1.) As a user, I want to be able to sign in and be able to track the games
    I am involved in.
    2.) As a user, I want to be able to click on a section of the game and make
    a play.
    3.) As a user, I want a visual display of how many games I've won, drew or
    lost.
    4.) As a user, I want to be able to sign out whenever I want.

_   I plan to keep all code of related intent contained in separate files that
    are then exported when needed (for example, functions determining game
    logic should be contained in their own file).

_   If I have the time, I want to use CSS to style the game to be visually
    appealing, possibly using animations or researching svg.

_   Git. Commit. All the time. Create new branches for different aspects
    (ui, api) of the project.

_   If I have the time, I want to include multiplayer using separate devices.
