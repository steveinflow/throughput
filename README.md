PR Throughput Simulator

[Live Demo](https://steveinflow.github.io/projects/throughput/)

Interactive visualization showing how PRs flow through a software team.
Producers write code, PRs queue up for review, and reviewers process them.

Adjust producer productivity and reviewer speed to see how bottlenecks form.
When producers outpace reviewers, the blocked queue grows and throughput
turns red. When reviewers can keep up, throughput is green.

Open index.html in a browser to run. No dependencies or build tools needed.

## Original Prompt

> We're going to make a web app that models PR throughput at a software company. It will show the pipeline from engineers generating pull requests, to a different set of engineers reviewing those pull requests, then finally merging to master. at first we'll just show code flowing through at a regular rate. we should be able to adjust code review latency to see how it causes things to get backed up
