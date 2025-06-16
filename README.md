# Hike Plan

You've just been on the worst hike of your life, but you've learned a lot about
how to make the next one better and it's time to start planning. Build a commit
containing the items you want to bring with you.

## Instructions

1. Clone this repository to your computer and navigate to it using your terminal
2. Run `./new-game` in your terminal to begin the game.
3. Using files from the `shelter`, `food`, and `clothing` branches, build a
   single commit containing:
   - 1 shelter option
   - 2 food options
   - 3 clothing options, 1 of which must be hiking books
4. Run `./next` in your terminal to check your work!

If you make a mistake, run `./new-game` to start over.

## Tips

### Exploring Commits

- See which branches are available with `git branch -a`
- Switch branches with `git switch <branch_name_here>`, such as `git switch food`.
- Navigate back to your previous branch with `git switch -`

### Getting Files From Other Branches

To copy a file or folder from another branch:

1. Switch to the **destination** branch
2. Use one of the following options:
   - **Traditional**: Run
     `git checkout <branch_name_here> -- <file_or_folder_to_copy>`. For example,
     `git checkout food -- food/trail-mix` copies the file `food/trail-mix` from
     the `food` branch into your current branch.
   - **Modern**: Run
     `git restore --source=<branch_name_here> <file_or_folder_to_copy>`. For
     example, `git restore --source=food food/trail-mix` copies the file
     `food/trail-mix` from the `food` branch into your current branch.

Use tab completion to help with spelling!

## Why This Matters

Checking out files from other branches is useful in situations like:

- Using parts of abandoned experiments
- Recovering files from old commits that were deleted or changed
- Using scripts, setup files, or seeds temporarily

Game 4: [Hike Packing](https://github.com/sikaeducation/hike-packing)
