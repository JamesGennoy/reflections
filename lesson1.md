# Reflections: Lesson 1

## Using diff to Find Bugs

Because the file was so huge it would have been extremely difficult to go line by line to find the bug in the new version. By comparing just the difference between the old and new files it was easy to spot the error as there were only 4 lines to compare instead of 1000.

## Using History for Efficiency

Easier than having to manually save off old versions of files. You always have a reference to old versions of a file. This will help to track down bugs. And also may help by seeing how a file has changed over time and making decisions on where new changes should go.

## Manual Commits

The positive is you have complete control over how big or small a commit can be. Which can be help since you as the programmer know what makes most logical sense to be committed together.

The negative would be that sometimes we make mistakes and can forget to commit, make a commit too small, or even make a commit too big.

However, I think the positives out weigh the negatives in this case and it is nice to have full control of when to commit.

## Multi-file Commits

Multi-file commits are helpful because making changes (bug fixes, new features) often involve change more than one file. So tracking those changes together can be very helpful when looking back at the history

## Using Git to View History

You can view the history of the repository using `git log` to look for commits with messages that point you to when the changes took place. And you can use `git diff` to view the actual changes in the files.

Maybe you don't know the commit where the change took place, how do you look at the history of a file?

## Confidence from Version Control

Having the ability to completely revert to an older version of the repository, I have a lot more confidence in making new changes because I can revert back to the old changes so easily if something gets messed up.

## How Do You Want to Use Git?

I want to use it for all personal projects and I am happy to see that we are going to be using Git for the new projects at work as well.
