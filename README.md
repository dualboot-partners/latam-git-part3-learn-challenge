# Git challenge

## Part 3

In this lesson we have seen what Cherry Picking is and when to use it. Now we will do some exercises to test how this function works in a real repository.

Start by cloning this repository on your local machine and pushing it to a new repository on your github account. 

Then follow the instructions given below and once you are done, copy your repository URL into the box provided on the learning platform.

**Please answer all the questions in your project's `README.md` below each one.**

**All code changes must be made to the `index.html` file.**


### Instructions

1.  Create a new branch `feature-a`

    a. Change anything and commit. `(commit 1)`

    b. While you were working on this branch you found a very important bug that needs to be fixed as soon as possible. Create a new commit fixing this bug (just change anything from the `index.html`) `(commit 2)`.

    c. You should merge this solution into `main` as soon as possible to resolve the bug, but you're not ready to merge the entire `feature-a` branch yet, so now you want to merge just `(commit 2)`. Create a cherry pick to do so. What command would you use?
    
    d. If you haven't already, push both branches.

2.  Notice how your `(commit 2)` is now in both `main` and `feature-a`. This is what we explained in the theory part that using Cherry Pick creates duplicate commits.
