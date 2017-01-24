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
-   The data structure you plan to use.
-   How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code modular.
-   What creative spin will you add to your project?
-   How will you use version control to backup / track your project?
-   Do you plan to attempt any of the bonuses?

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur]
(http://imgur.com/).

Wireframe:
http://imgur.com/a/XyZtJ

Data Structure:
For this project I plan on using the JSON data structure to save different types of data
including user credentials, game history for each user, and

Markup:
To be honest I am really not sure what this question is refering to which may be
a bad omen for how I'm going to do on this project but I am hoping that I will be able to represent the board in JavaScript using an array for each game played filled with empty strings or other values. When player_x or player_o select a square the index corresponding to the selected square is altered to signify that an x or o now occupies that space. When the array is filled with a enough x's and o's in certain way it will trigger a response. The three responses are: player_x wins!; player_o wins!; and Draw!.

Approach:
First, I am going to attempt to outline all of the aspect of the game that I think I will need. These include but are not limited to HTML layout, potential methods needed for execution of UX, jQuery methods to communicate with the server, and user credential modules. Next I am going to want to visualize how the user willm interact with the app, from creating a user name all the way to starting a new game. Once I have all that mapped out I will probably update my wireframe to see if anything needs to be changed. I am sure I am missing several things that I will need to plan out once the ball get rolling with this project.

User Stories:
As a user I want to be able to create account so I can track my stats.
As a user I want to be able to start a new game after I finish one.
As a user I want to be able to play cooperatively with a friend.
As a user I want to be able to change my password.
As a user I want to be abe to see the winner of a game.

Modular Code:
In order to create modular code I plan on organizing my code in seperate files and by code utility. For instance, I plan on keeping all of my helper functions in one file and all of my functions that interact with the API in another. This will make it less likely for the variables in each file to interact with each other.

Creative Spin:
Hopefully I can add some musical aspect to my project. Not sure what it will be quite yet; creativity for me comes spontaneously.

Version control:
I plan to commit early and often creating useful comments in my commit messages.

Bonuses:
As of now I do not plan on attempting any of the bonuses. My focus now is to just complete the essentials of the project and if I have any remaining time before the due date then I will attemp the bonus.
