# SME-Assignment - Shivansh

## Part2: Setting up your Project 
I downloaded sfml-32-bit at first and did the whole part2 but was stuck with the set up due to wrong version of sfml.
Then I downloaded the correct one sfml-64-bit and completed the setup
I made the following changes:-
Copy and pasted the include and lib in the `smfl` folder.
Copy and pasted the include and lib in the `smfl` folder.
Copy and pasted necessary bin files in the `debug` folder which was created after first run.

## Part3: Bug Fixing
There were sevaral warnings and 3 errors , all in the PlayerController header file.
So I fixed the delibrate bug in the code and ignored the warnings to start the game.

The bug was that in the PlayerController header file 'Space-Invaders/header/Player/PlayerView.h' header was included and 
in the PlayerView header file 'Space-Invaders/header/Player/PlayerController.h' was used which resulted in 
circular dependency between PlayerController.h and PlayerView.h.

To resolve this, i used forward declarations in PlayerController.h and PlayerView.h instead of including each other's headers directly. 
As was used in the EnemyController.h and EnemyView.h header files.

## Time taken

Part 2 took me 35 mins as I had to redo it.
Part 3 took me 30 mins as I went through the code and resolved the error.
Part 1 took the most amout of time - 3.5 hours as it was something new for me and I had to be thorough with it
but I really enjoyed the content writing part of game development.
