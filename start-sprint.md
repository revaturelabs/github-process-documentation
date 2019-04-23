# Starting a Sprint

* On Jira, create a new sprint if the next one has not already been planned (there would be an existing sprit when viewing the backlog)

* Move all stories that the sprint will work on into the new sprint

* Ensure that the stories have been assigned a point value (otherwise the burndown will not show data)

* Select Start Sprint and input the date the sprint will end on

* Ensure branch protections are in place on the repo the batch will be working on

* Create a new team in [revaturelabs](https://github.com/revaturelabs) (naming should be batch-trainer ex. 1901-Java-JoeTheTrainer)

* Add all associates to the team and grant the team write access to the repo they are working on

* Copy over (if not already included) the stories into the issues for the Github repo
  * Tag them with the label Story and with a label for the epic they are apart of if applicable
  * Ensure that the ISSUE KEY: is set to the Jira issue tag ex. `[GH-43]`
    * Putting brackets on the issue key will allow the bot to automatically link the issue key to the Jira story

* Ensure all associates have the repos locally and run the setup.sh script they need to configure their username and name (name should be their actual name)