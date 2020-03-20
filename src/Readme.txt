Understanding how the game actually works.

-------------
*COMPONENTS:
-------------

1- App : this components just render a Game component.
2- Game : 
    # this the biggest component and only statefull component.
    # Game has three main state :
        - dice : which contain the random roll of the five dices.
        - locked : which contain by default a false value for each dice and will change to  true if we want to locked it up (freeze).
        - scores : which contain all the scores possible for the game and its value.
    # Game has two main methods : 
        - toggleLocked : 