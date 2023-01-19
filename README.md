# muxinc/.github
Shared templates and workflows for Mux repos on github

## Cloning this Repository
Remember, this repo has a dot in front of its name. You should call it something else on your machine
```
git clone git@github.com:muxinc/.github.git mux-dot-github
```

## Starter Workflows

This repo contains starter Github Actions workflows for doing common tasks like CI/CD and release automation. These are template files you can install in your repo using the GitHub website. They aren't usually ready-to-go outside the box, but comments in the workflow file can help you fill in the missing details.

The starter workflows can be found under [/workflow-templates](/workflow-templates). For more information on creating starter workflows, see the [Create Starter Workflows for Your Organization](https://docs.github.com/en/enterprise-cloud@latest/actions/using-workflows/creating-starter-workflows-for-your-organization). 

### Using a Starter Workflow

For a guide on using starter workflows, please see (Using starter workflows)[https://docs.github.com/en/enterprise-cloud@latest/actions/using-workflows/using-starter-workflows] in the GitHub Actions docs.

### Workflow List 

| Workflow name           | Requires Config | Description                                                                                                                       |
| ----------------------- | --------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| `categorized-changelog` | No              | A workflow that generates a sorted, formatted, categorized changelog on a Release PR that preserves attribution for the devs who contributed |

