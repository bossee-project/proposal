# Building Open Science Services on European E-Infrastructure (BOSSEE)

A proposal for [INFRAEOSC-02-2019](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/topic-details/infraeosc-02-2019)
started by participants in OpenDreamKit.

brainstorm docs: https://hackmd.io/fNJQFqgYQaCDGx-BFgz4XQ

[![CI builds](https://circleci.com/gh/bossee-project/proposal/tree/master.svg?style=svg)](https://circleci.com/gh/bossee-project/proposal/tree/master)

The draft is built automatically [on CircleCI](https://circleci.com/gh/bossee-project/proposal/tree/master).
To see a rendered draft, click on a successful build and then the 'Artifacts' tab, where there will be a link to the resulting PDF:

![circle-screenshot](circle-screenshot.png)


## To compile document

### install latex class (only required once)

    git submodule init; git submodule update

### to compile document

    make draft

produces ``draft.pdf`` if all goes well.


