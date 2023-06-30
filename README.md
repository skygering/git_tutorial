# Git/GitHub Tutorial

This repository contains the materials for two Git tutorials, one for working independently and one for working collaboratively. They are meant to be run in a sequence, with the second tutorial building on the skills from the first. 

While this tutorial is meant to be used in Julia, it would be simple to make the changes necessary to do these activities in an alternative language.

**If you want to use these materials, please make a fork of this repository for your tutorial sessions and give credit to Skylar Gering and Julia Sloan.**

## Tutorial 1

The first turorial covers the following Git commands: `clone`, `add`, `commit`, `push`, `pull`, `status`, and `log`.  These commands are taught through a madlibs activity. Each student will clone the repostory, make a personal copy of the `sample_inputs.txt` file, and rename it. They will then replace the example madlib words with words of their own choosing. They will then push these files and choices to the repository, and all students will retrieve the new files by pulling from the repository. Students can then run `generate_madlibs.jl` to generate a madlibs using words submitted from the group.

[Git_Tutorial_1 Slides](https://github.com/skygering/git_tutorial/files/11923634/GitHub_Tutorial_Part1.pdf)


## Tutorial 2

The second tutorial reviews all of the commands from Tutorial 1 and teaches the following new commands: `branch`, `switch`, and `rebase`. It also purposely creates a merge conflict so that students can practice resolving a merge conflict. In this activity, students work in groups of two. They will be creating a landscape drawing using emojis. One student will draw the top of the image (the atmosphere) and the other will draw the bottom (the land, ocean, city, etc.). Each pair of students will have their own file, a copy of `sample_drawings.jl`. Then, each student will make a branch and add their emojis to their file, filling the three available lines, making several commits along the way. Both students will push to the remote so they can see how the file differs on each branch on GitHub. All students will then squash their commits down to one commit. One member of each pair will merge their branch to main, followed by the other student, causing a merge conflict. The pairs will resolve the merge conflict, complete their picture, and push their finished image to the remote repository. 


[Git_Tutorial_2 Slides](https://github.com/skygering/git_tutorial/files/11923635/GitHub_Tutorial_Part2.pdf)
