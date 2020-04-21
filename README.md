# Overview
Infrastructure for the [VEO-IBD Genie](https://github.com/veo-ibd/Genie) application.

It uses a Docker image based on a `Dockerfile` from [Sage-Bionetworks/veoibd-validation-docker](https://github.com/Sage-Bionetworks/veoibd-validation-docker).

# Purpose
This repository contains CloudFormation infrastructure templates for the GENIE batch jobs.

* validation
* input to database

## Continuous Integration
We have configured Travis to deploy CF template updates.  Travis deploys using
[sceptre](https://sceptre.cloudreach.com/latest/about.html)

