# Git challenge

## Part 3

In this lesson we have seen what Cherry Picking is and when to use it. Now we will do some exercises to test how this function works in a real repository.

**Please answer all the questions in the `README.md` of your project below each of them.**

1.  Fork this [repository](https://github.com/djabif/git-challenge-part3)

2.  Create a new branch `feature-a`

    a. Change anything and commit. `(commit 1)`

    b. While you were working on this branch you found a very important bug that needs to be fixed as soon as possible. Create a new commit fixing this bug (just change anything from the `index.html`) `(commit 2)`.

    c. You should merge this solution into `main` as soon as possible to resolve the bug, but you're not ready to merge the entire `feature-a` branch yet, so now you want to merge just `(commit 2)`. Create a cherry pick to do so. What command would you use?
    
    d. If you haven't already, push both branches.

3.  Notice how your `(commit 2)` is now in both `main` and `feature-a`. This is what we explained in the theory part that using Cherry Pick creates duplicate commits.
