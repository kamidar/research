# Devex Research

Welcome to the Devex Research project.
Its main objective is to learn and explore new technologies.

This repository serves various purposes:

- Collect and discuss ideas.
- Record activity and progress on the project.
- Organize work on the project.
- Present obtained results.

## Repository structure

The content of this repository are separated in two folders:

- `share/` contains all the shared stuff. Anything you add here should be part
  of a pull requests against the main repository.
- `local/` is for personal use and should only be pushed to your fork. Use it
  for prototyping, notes or whatever. If it makes sense you can move files over
  to `share/` and open a pull request. Therefore it is recommended to keep a
  folder structure similar to the one under `share/`.

## Proposing ideas

To propose an idea you need to create a document in the folder `share/ideas/`
containing basic info:

- short description of the idea
- simple bullet list of steps to perform
- expected outcomes and possible results
- involved technologies
- possible follow-up or spin-off projects

The file name should consist of the date and a short title, e.g.
`2015-08-18-activity-dashboard.md`. To get started just copy the template
file `share/ideas/TEMPLATE.md`:

```
$ cp ./share/ideas/TEMPLATE.md ./share/ideas/2015-08-18-activity-dashboard.md
```

Then open a pull request to discuss this idea with the team. Once accepted
and merged you should create a GitHub issue with the label `idea`, referencing
the original pull requerst and idea document.

