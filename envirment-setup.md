# Environment Setup

Each repo should have a README.md that has a `Setup` section to explain how to setup the environment for the application to function.

Trainers should also have the envirment setup on their local computers so that they can check the progress of the project throughout the sprint as well as be able to test the PRs that will come into dev branch at the end

> If there are any problems with the documentation about setting up the environment follow the steps at [Update Setup](#Update-Setup)

Environment setup should not take more than one day if it does then please notify [Quintin Donnelly](mailto:quintin.donnelly@revature.com) so that envirment setup for that project can be improved upon as to save training time in these tasks.

### Update Setup

1. Clone the repo locally `git clone <git repo>`

2. Move into the repository `cd <repo name>`

3. Go to the dev branch and create a new branch for doc changes `git checkout -b <descriptive branch names>`

4. Make the changes to the documentation

5. Commit the changes

    ```sh
    git add <changed files>
    git commit
    ```

    Type commit message explain the problem with the old docs

    ```sh
    git push origin <branch name>
    ```

6. Open a PR to the dev branch from the branch you created in bullet 2