# Open-Source-Workflow
Contribution workflow guide for Open Source

## Contributing to code

Code contributions—bug fixes, new development, test improvement—all follow a GitHub-centered workflow. To participate in OSS development, set up a GitHub account. Then:

1. Fork the repo you plan to work on. Go to the project repo page and use the Fork button. This will create a copy of the repo, under your username. (For more details on how to fork a repository see this [guide](https://docs.github.com/en/get-started/quickstart/fork-a-repo).)

2. Clone down the repo to your local system.

`$ git clone git@github.com:your-user-name/project-name.git`

3. Create a new branch to hold your work.

`$ git checkout -b new-branch-name`

4. Work on your new code. Write and run tests.

5. Commit your changes.

`$ git add -A`

`$ git commit -m "commit message here"`

6. Push your changes to your GitHub repo.

`$ git push origin branch-name`

7. Open a Pull Request (PR). Go to the original project repo on GitHub. There will be a message about your recently pushed branch, asking if you would like to open a pull request. Follow the prompts, compare across repositories, and submit the PR. This will send an email to the committers. You may want to consider sending an email to the mailing list for more visibility. (For more details, see the GitHub guide on PRs.

8. Maintainers and other contributors will review your PR. Please participate in the conversation, and try to make any requested changes. Once the PR is approved, the code will be merged.

*Before working on your next contribution, make sure your local repository is up to date.*

1. Set the upstream remote. (You only have to do this once per project, not every time.)

`$ git remote add upstream git@github.com:organization/project-repo-name`

2. Switch to the local master branch.

`$ git checkout master`

3. Pull down the changes from upstream.

`$ git pull upstream master`

4. Push the changes to your GitHub account. (Optional, but a good practice.)

`$ git push origin master`

5. Create a new branch if you are starting new work.

`$ git checkout -b branch-name`

***Additional resources:***
- [Git documentation](https://git-scm.com/documentation)
