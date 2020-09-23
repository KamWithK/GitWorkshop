# Git Workshop Exercise
In this exercise your team will create a mini-website (with simple markdown pages) documenting your project.
There are several tasks to complete (listed as `GitLab Issues`), but take these with a pinch of salt.
The questions should get you thinking about positive open-source documentation, but the priority here is to **practice conflict resolution with Git**.

To complete the exercises you'll just need to edit markdown files (end with a `.md`) with any text-editor.
The `#`'s are for headings (more `#` means smaller).
Wrap text in `*` for italics or `**` for bold and `\`` for code-blocks (`\`\`\`` for multi-line code blocks).

Think very carefully about your actions (creating files, editing files, where you create a branch from...) and discuss any doubts/questions with your teammates.
If you stay conscious of what you're doing, you'll quickly become a Git lean mean machine!
Please **work on merging and fixing conflicts together** where possible.
Note that it may be useful to use a visual UI to show what changes have been made (VScode is a great choice).

# Setup and Workflow
Sart by forking and cloning this repository (`git clone YOUR_REPO_LINK`).
There will be a fork button near the top right hand side of the screen (left of the blue clone button).
**Only one person per-team should do this** (you can share screen with everyone else so they know how too though)!
Once you've got your own GitLab repository clone it (hitting the clone button and then HTTPS will give you the URL) to use in `git clone REPO_LINK`.

Once everyone knows what task they'll start with create a feature branch to work in (`git checkout -b some-feature-branch`, but use a meaningful name which doesn't include the words feature branch).
Although it won't be immidiately useful, do recall that you by default branch from your current (**not `master`**) branch.

> Remember, each task should be completed in a new branch!

You should gradually commit (`git commit -m "ADDED COOL THING/CHANGED BLAH BLAH BLAH"`) your changes.
Once you've completed a task make sure to push (`git push`) everything and create a pull request (through the website).

Before creating a pull request remember to get the latest changes (`git pull`).
This is one place where conflicts may occur (hint - this is when rebases are useful).

## Project timeline:
# Completed targets:
1. Converting .dicom files to .npy files and filtering and thresholding CT scans to produce data on skull location.
2. Implementation of new metrics to improve the training of the model.
# Future targets:
1. Nov 2020 - Complete preprocess pipeline for cleaning of .npy files (removal of unecessary data, image cropping).
2. Nov 2020 - Research pre-trained weights for model implementation and acheive functional stability.
3. Dec 2021 - Implement Weights & Biases to allow hyperparameter tuning and model optimisation.
4. Mar 2021 - Submit conference paper for Miccai (March 2021 submission for August 2021 Conference). Current goal is to submit two distinct papers for both the 2D depth map and 3D volumetric deep learning methods.
5. Jan 2022 - Use it to "solve code" by 2022.