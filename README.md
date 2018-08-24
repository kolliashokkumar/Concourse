# Concourse

Concourse is an open-source continuous thing-doer. Built on the simple mechanics of resources, tasks, and jobs, Concourse presents a general approach to automation that makes it great for CI/CD.
Read more: https://concourse.ci

This reporsitory contains Concourse Pipelines to build a JAVA web app and deploy it to PWS continuously on each GIT commit in Source.

## Usage

jobs.yml is the main pipeline file which needs to be triggered using Cocourse.

Dependencies:

```
Pivotal Web Services Account
```

Get a Pivotal Free account and store the credentials in a file "creds.yml" in LOCAL Linux VM.
