# Tekton <3 GitOps

Experiments of integrating Tekton into GitOps tool


## What expects to see

- [ ] Automatically sync Tekton Task, Pipeline when submitting it to Git repository.
- [ ] Integrating with GitHub
  - [ ] When pull request was created. It should use Task, Pipeline that defined on that branch.
  - [ ] When push any code to Git repository, PipelineRun should be create.
