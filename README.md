# [Github Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#overview)

- CI/CD platform that allows automate build, test, and deployed pipeline.
- create workflows that build and test every pull request to a repository, or deploy merged pull request, or deploy merged PRs to production.



## [Workflows](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#workflows)

- It's a configurable automated process that will run one or more jobs.
- They are defined by a YAML file checked in a repository and will run when triggered by an event in repository, or they can be triggered manually, or at a defined schedule.
- They're defined in `.github/workflows` directory in a repository, and repository can have multiple workflows, each of which can perform a different set of tasks.

## [Events](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#events)

- It's a specific activity in a repository that triggers a workflow run.


## [Jobs](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#jobs)

- It's a set of steps in a workflow that is executed on the same runner. 
- Each steps is either a shell script that wull be executed, or an *action* that will be run.
- They are executed in order and are dependent to each other. 
- Share data from one step to another.


## [Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#actions)
- It's a custom application for the Github Action platform that performs a complex but frequently repeated task.
- Help in reduce the amount of repetitive code that is written in workflows file.


## [Runners](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#runners)
- It's a server that runs workflows when they're triggered
- Each runner can run a single job at a time. 

