# ExampleGitExercise
This repo shows how git and GitHub can address a specific minimalist use case. The goal is to simulate a minimal project development setup,
in which sharing with 2 independent parties is needed.

# MATLAB code development exercise
Try to perform the sequence of steps below without a version control system if you feel brave. 

1. create a function myfunc that takes no argument and displays the number 38 to the screen.
2. create a script called myscript.m that calls myfunc once.
3. share the script and the function with collaborator 1.
4. Enhance both myfunc and myscript so that:  
  - myfunc now takes a single integer as argument and displays it to the screen
  - myscript calls myfunc 5 consecutive times with successive arguments 1, 2, 3, 4, 5.
5. you share the enhanced myfunc and myscript with collaborator 2.
6. collaborator 1 gets back to you and tells you that myfunc should really take 1 integer as argument (just as the enhancement made) but myscript should call myfunc twice with successive args 33, 44. You bring the modifications and share the appropriate function and script with collaborator 1.
7. collaborator 2 gets back to you and tells you that things look okay, except for the fact that myfunc really should subtract 2 from its argument before displaying the result to the screen. You implement the changes and share with them the latest files.
8. etc.

The present repo solves the problem above by:
- assigning a specific branch to each collaboration
- assigning annotated tags (release versions) to every commit that was shared
