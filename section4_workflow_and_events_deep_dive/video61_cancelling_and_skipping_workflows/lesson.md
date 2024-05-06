1. Cancelling 
  - by default workflows get canceled automatically if a job fails
  - by default a job fails if at least one step fails
  - you can cancel workflow manually

2. Skipping
  - if you add `skip ci` or `skip actions` or anything from [here](https://docs.github.com/en/actions/managing-workflow-runs/skipping-workflow-runs), workflow will not start, even that would otherwise be triggered.