# DevOps: Section 1 - Introduction

## What is DevOps

### Software Development Lifecycle (SDLC)
Requirement Gathering -> Planning -> Designing -> Development -> Testing -> Deployment

There are different models of SDLC:
- Agile
- Waterfall
- Spiral
- Big Bang
- ...

### Agile - main focus
2-4 weeks per each lifecycle

Regular code changes need to be deployed fast to the servers so that code testers may access it.

### Dev vs Ops
Devs - agile; regular and quick changes
Ops - ITIL driven, provides stable env for the product

Big wall of confusion between the two & delays and errors.

### Enter DevOps
Fixes delivery issue.

Automate - Code Build, Code Testing, Software Testing, Infra Changes, Deployments

Everyone works together.

### Entire Lifecycle

**Code** - Devs commit code

**Code Build** - deployable artifact

**Code Test** - Unit & Integration Tests

**Code Analysis** - Vulnerability, best practices

**Delivery** - Deploy changes to staging

**DB/Sec Changes** - Every other ops changes

**Software Testing** - QA/Functional, load performance tests

**Deploy to prod**

**Go live** - user traffic diverted to new changes

**User feedback**

**Keep monitoring**

## What is CI
**Key goal**: Catch defects as early as possible so they don't multiply. This requires a toolchain where IDEs, version control, build tools, artifact repositories, and CI tools are all integrated together.

## What is CD
Every step in deployment should be automated, using tools suited to the job: system automation tools like Ansible, Puppet, and Chef; cloud infrastructure automation tools like Terraform; and CI/CD automation tools like Jenkins or Octopus Deploy (there are many others depending on need). Software testing needs the same treatment — functional, load, performance, database, network, security, and any other test types should be automated too.

Ops writes automation code for deployment, testers write automation code for testing, and both are synced with the developers' source code. This stitches together deployment automation and automated testing with the development process, integrating all three teams end to end — that combined, fully automated pipeline is continuous delivery.