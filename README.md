# env
Example for using the `env` field at workflow, job, and step level.

## Documentation

* [`env`](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions#env): a `map` of environment variables that are available to all jobs and steps in the workflow
* [`jobs.<job_id>.env`](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions#jobsjob_idenv): a `map` of environment variables that are available to all steps in the job
* [`jobs.<job_id>.steps.env`](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions#jobsjob_idstepsenv): a `map` of environment variables for steps to use in the runner environment
