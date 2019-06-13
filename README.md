## Repository Information

This repository contains the source code used during Red Hat Summit 2019 Discovery Zone session for the demo aorund "How Volkswagen used microservices and automation to develop self-service solutions" presentation.

[Presentation Slides](https://www.slideshare.net/makimak1/how-volkswagen-used-microservices-and-automation-to-develop-self-service-solutions)

## Configuration and demo case

Ansible Tower will be configured with 4 Projects, corresponding to the projects under [projects](projects/) directory

Ansible Tower will be configured with 4 Job Templates using the Playbook from each previous configured Project

Ansible Tower will be configured with a Workflow Template using the previuos 4 Job Templates, this way the whole workflow will be executed on the user onboard.

## Demo video

[Container Manifest e2e Demo](media/demo.webm)

## High Level Architecture

![System Diagram](media/high_level_arch.png "System Diagram")