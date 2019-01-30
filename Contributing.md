# Notes for authors of the proposal

## To compile document

### install latex class (only required once)

    git submodule init; git submodule update

### to compile document

    make draft

produces ``draft.pdf`` if all goes well.

## writing

Most writing should occur by creating a task in `tasks/` based on
`tasks/template.tex`. Then the task should be added to a workpackage
file in the task list.

## Building of the proposal by Continuous Integration

[![CI builds](https://circleci.com/gh/bossee-project/proposal/tree/master.svg?style=svg)](https://circleci.com/gh/bossee-project/proposal/tree/master)

The draft is built automatically [on CircleCI](https://circleci.com/gh/bossee-project/proposal/tree/master).
The URL of the PDF produced by the latest build can be found on
[this page](https://circleci.com/api/v1.1/project/github/bossee-project/proposal/latest/artifacts?branch=master&filter=successful).

Alternatively, click on a successful build and then the 'Artifacts' tab, where there will be a link to the resulting PDF:

![circle-screenshot](circle-screenshot.png)

