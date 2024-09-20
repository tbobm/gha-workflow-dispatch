# Github Actions Workflow Dispatch

Demo of the workflow dispatch event type.

[Events that trigger workflows#workflow_dispatch](https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows#workflow_dispatch)

## Concept

This can be used to have a **manual** and structured automated way to
deploy a specific version of a Service.

In simple terms, a CICD process can:
- automatically deploy artifact images to a non production environment
- allow to run tests, validation and review on a live environment
- generate a tagged artifact that can then be deployed in production safely

![image](https://github.com/tbobm/gha-workflow-dispatch/assets/16706490/040436fc-edd4-4443-80f6-fd029d639489)
