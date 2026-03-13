Git Workflow Homework

## About This Project
This project was created to practice Git history management skills. Throughout the work, I focused on several key aspects of Git including history cleanup, recovering lost commits, and branch management.

## What Was Done?

Initially, the repository was created and project.txt was added with several ordinary commits like "update", "stuff", and "final changes". Afterwards, the history was cleaned up by squashing some of the commits together to create a cleaner and more meaningful history.

To simulate a mistake, a new commit was added and then "lost" using reset. This commit was later recovered using reflog, and a new branch (recovered-branch) was created directly from that commit.

To make history viewing easier, an alias was created that shows the history in a graphical format. The cleaned-up version of the project was tagged as v1.0.

Finally, everything was pushed to GitHub including both branches and the tag.

## Structure

**Main branch** contains the final cleaned-up version:
- Version 1 of project
- Version 2 of project
- Added some changes
- Final Version

**Recovered-branch** contains the same code but with an additional line that was recovered:
- Version 1 of project
- Version 2 of project
- Added some changes
- Final Version
- Temporary change that will be lost


## Additional Information
- Author: Erion Zabeli
- Date: March 13, 2026
