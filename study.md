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
    http://i.imgur.com/Ml7FeJx.jpg

    The data structure you plan to use.
    
    const currentGame = {
  'game': {
    'id': 1,
    'cells': ['', '', '', '', '', '', '', '', ''],
    'over': true,
    'player_x': {
      'id': 1,
      'email': 'and@and.com'
    },
    'player_o': {
      'id': 3,
      'email': 'dna@dna.com'
    }
  }
}
-   How you will take the markup of the game board and represent it in JS

    Using the above I will store the updates as they happen.

-   How you plan to approach this project.

    Using the user stories build out the features starting with Authentication

-   4-8 user stories for your game project.

Story: As a User, I want to Play in a desktop browser, So that I can play on my computer
Story: As a User, I want to know my current games won, So that I can try harder
Story: As a User, I want to change my password, So that I feel secure.
Story: As a User, I want to logout, So that no one can play under my account.
Story: As a User, I want to know when it is my turn, So that I can play my turn.
Story: As a User, I want to my mark to be X, So I can go first.
Story: As a User, I want to Sign Up, so that I can play in the future.
Story: As a User, I want to know who won, So that I can celebrate

-   How you plan to keep your code modular.

    Use the DRY prinicples when building out the code.

-   What creative spin will you add to your project?

    Use images other then X and O

-   How will you use version control to backup / track your project?

    Commit often and push changes to github

-   Do you plan to attempt any of the bonuses?

    Only if time permits

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
