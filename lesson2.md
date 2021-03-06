# Reflections: Lesson 2

## Initializing a Repository

In most software systems there is an initialization that needs to occur. This sets up the .git directory with the necessary information about your repository. And it also tells Git to start tracking changes.

## Staging Area

Staging area is a temporary holding area for files that you are working on. It gives you a place to put files you want to change before you can commit all those files at once. This also gives you an opportunity to review changes before committing them.

## Commit Size

You can review the staging area before you commit to ensure the commit you will make only has one logical change.


## When to Use Branches

Creating branches for working on new features or experiments is a good idea. That way the master only contains a working clean version of your repository at all times.

## Visualizing with Diagrams

It is much easy to understand branches and how they are connected by using diagrams.

## Merging Two Branches

The result of merging two branches together is the resulting branch has all of the commits in both branches. This is a good way to work on new features independently, until they are ready to be merged into the Master branch.

## Automatic vs. Manual Merging

It is nice that sometimes Git can automatically merge conflicts. However, I think it is better that it falls back to having the developer, who really knows the code, manually merge conflicts that occur on the same lines.
