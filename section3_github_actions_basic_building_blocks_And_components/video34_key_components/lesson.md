1. Workflows
  - Attached to github repositories
  - You can have as many workflows as you want
  - Can contain one or more jobs
  - Triggered upon *events* (e.g: event can be whenever a new commit is pushed)
2. Jobs
  - Can contain one or more steps
  - Define a runner (execution environment)
  - Run in parallel (default) or sequential
  - Can be conditional
3. Steps
  - Execute a shell script or an Action
  - Can use custom or third-party actions
  - Executed in order, no option for parallel run
  - Can be conditional