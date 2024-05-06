You should be aware of one thing when you are accepting pull requests from people that forked your Repository.

By default, pull requests based on forks do NOT trigger a workflow!
The reason for that is that 
- everyone can fork your public Repositories
- everyone can create pull requests targeting your Repository

And because of that, people could, of course, start Workflow runs in a malicious way.

Solution:
- first-time contributors must be approved manually

People who have not opened pull requests before and had those pull requests approved by you before,
whenever people open a pull request with your Repository for the first time, you as the owner have to approve
that pull request first before the Workflow runs.

- This is not the case, if you are a contributor.