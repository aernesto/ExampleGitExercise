# Three Big Reasons to Use Git 
Version-Control Systems like Git and their associated online platforms such as GitHub are essential because:
1. It is easy to get Open Source code written by others
2. It is easy to share code (open source or not) with others
3. It is **great** to keep track of the history of your project

# This Repo
This repo shows how git and GitHub can address a specific minimalist use case. The goal is to simulate a minimal project development setup, in which sharing with 2 independent parties is needed.

**Note:** _I use MATLAB here, but the whole exercise is doable in any language. I encourage you to do it in your favorite programing language._

# Code development exercise
Try to perform the sequence of steps below: 

1. create a function `myfunc` that takes no argument and displays the number 38 to the screen (or at the console).
2. create a script called `myscript` that calls `myfunc` once.
3. share the script and the function with collaborator 1.
4. Enhance both `myfunc` and `myscript` so that:  
  - `myfunc` now takes a single integer as argument and displays it to the screen
  - `myscript` calls `myfunc` 5 consecutive times with successive arguments 1, 2, 3, 4, 5.
5. you share the enhanced `myfunc` and `myscript` with collaborator 2.
6. collaborator 1 gets back to you and tells you that `myfunc` should really take 1 integer as argument (just as the enhancement made) but `myscript` should call `myfunc` twice with successive args 33, 34. You bring the modifications and share the appropriate function and script with collaborator 1.
7. collaborator 2 gets back to you and tells you that things look okay, except for the fact that `myfunc` really should subtract 2 from its argument before displaying the result to the screen. You implement the changes and share with them the latest files.
8. At some big conference, you present a poster for which you used a slightly different version of the code, compared to what you last shared with collaborator 1. Namely, the script calls `myfunc` three times with arguments 66, 67, 87. You want to remember the exact version of the code used for this poster in case someone asks detailed questions about it.
9. etc.

## Solution
The present repo solves the problem above by:
- assigning a specific branch to each collaboration
- assigning annotated tags (release versions) to every important commit (e.g. when sharing or for presentations)

# Resources
- [High-Level Intro to GitHub](https://youtu.be/w3jLJU7DT5E)
- [Configure git on your computer](https://help.github.com/en/github/getting-started-with-github/set-up-git)
- Use a Graphical User Interface (GUI) for Git if you wish. One possibility is [GitHub Desktop](https://help.github.com/en/desktop), but there are [many more](https://www.thewindowsclub.com/git-gui-clients-for-windows).
- A good (some people might say better) alternative to GitHub is [GitLab](https://about.gitlab.com/). It works in a very similar manner.
- This [Student Developer Pack](https://education.github.com/pack) is invaluable. 
- I find the [MATLAB resources on git](https://www.mathworks.com/help/matlab/matlab_prog/set-up-git-source-control.html) appalling, but there is still some important info there for MATLAB users.


# Advice
__**Use Git from day 1 on all your coding projects!!!!**__
