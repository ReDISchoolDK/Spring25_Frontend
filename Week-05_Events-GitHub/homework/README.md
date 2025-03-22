# Homework Week 5

Going forward you will submit your exercise by creating a Pull Request.

## Watch

[Video for using Github in VsCode](https://www.youtube.com/watch?v=i_23KUAEtUM)

## Do

Your homework is to open your very first Pull Request. The goal is to change a file called [my_first_pr.txt](./my_first_pr.txt), which lives in the same directory as this README file.

To create your PR follow these steps:

1. Clone the Repository

    The very first step is to make a copy of the repository on your computer - also called cloning.
    
    On the repository page, click the green Code button.
    Copy the HTTPS or SSH link.
    Open your terminal (Command Prompt, Git Bash, etc.) and run:

    git clone <REPO_URL>

    Replace <REPO_URL> with the link you copied. This will download all the files onto your computer.

2. Open the folder in VSCode

    Now open your new folder in VSCode. You can do so by going to `File > Open Folder` in the upper left corner.

3. Create a New Branch

    Now you should create a new branch.
    - VSCode:
        1. Click on the button in the lower left corner that says `main`
        2. A menu should open in the middle on top. Click `Create new branch`
        3. Name your branch: `feature/week-5/<your-name>`. For example, if your name is Daisy Duck, then your branch would be `feature/week-5/daisy-duck`.
    - Alternative: Terminal
        1. To create a branch via terminal simply run `git checkout -b feature/week-5/<your-name>` 

4. Open and Edit the File my_first_pr.txt

    Open the my_first_pr.txt file. Change it to anything you want - just know that your classmates and teachers can see what you write here, so be respectful and positive.

5. Stage and Commit Your Changes

    Stage your changes by clicking the Source Control button in the left bar.

    There should be a littl tab that says `Changes` - if you hover over it there is a small plus button that says `Stage all changes`. Press it to stage the changes.

    Then write a message above the big blue button that says `Commit`. A good commit message usually communicates what changes you make. For example: `updated my first pr message`. Press the `Commit` button when you are ready.

6. Push Your Changes to GitHub

    Now we need to get your commit to the repository. The blue Button should say `Publish branch`.
    Press that button to push your branch to Github.
    
7. Open a Pull Request

    Go to the repository’s page on GitHub.
    You’ll see a prompt: "Compare & pull request" (or a button labeled New pull request). Click it.
    Make sure the base is set to the repository’s main branch (often called main or master) and the compare is set to your new branch (`feature/week-5/<your-name>`).
    Add a title and description for your PR (e.g., "My first PR – added personal greetings").
    Click Create pull request.


> **Need Help?**
>
> If you run into any issues or have questions, please post in the Slack channel. We're here to help!

Create your Pull Request by Sunday 18:00 and send the link to your assigned teacher via Slack. We will send out the assignments.
