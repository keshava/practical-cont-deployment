# Continuous Delivery in Practice: a Hands-On DevOps Workshop

This project is a fork of the
[Spring Petclinic](https://github.com/spring-projects/spring-petclinic)
application. It is used as the base application for this Practical Continuous
Delivery work.

## Summary

For many organizations, delivering software into production has become
increasingly more complex with long testing cycles and a division between
development and operations teams. DevOps is a cultural movement that is breaking
down those barriers. Focusing on automation, collaboration, tools, and knowledge
sharing, DevOps is showing that developers and system engineers have much to
learn from each other. Through a series of exercises, this project will
use a sample web application to demonstrate how to automate its build and
deployment pipeline, using infrastructure and pipeline as code techniques. Here we 
will combine tools such as Docker, Terraform, GoCD, and
Kubernetes to create deployment pipelines for your infrastructure, your services,
and applications. But even if your company is not using any of these tools, we
will discuss alternative technologies and highlight the patterns and principles
required to put these ideas into practice. Join in the discussion to help you
improve your development processes and shorten the cycle time from concept to
working software in production.

## Pre-Requisites

This project needs  an environment to be set up first. Follow the
[instructions to setup your laptop](./SETUP.md) **prior to attempting the
steps**.

## Instructions

The process is divided into several steps, which build on top of each other.
Instructions for each exercise can be found under the
[`instructions`](./instructions) folder. We provide sample solutions for each
step that can be used for validation or as the starting point for the next step.
They can be found on separate branches named `step-N`, where `N` corresponds to
step number (e.g. `step-1`, `step-2`, ...) *WARNING: the exercises build on top
of each other, so you might not be able to skip steps ahead without executing
them.*

Fork this project on GitHub before cloning to your machine, to
allow you to make changes, commit them, and push to your own repository.

If you need to update your fork with the latest changes from this repo, you can
run from your local `master` branch:

```shell
$ git remote add upstream https://github.com/keshava/practical-cont-deployment.git
$ git fetch upstream
$ git merge upstream/master
$ git push origin master
```
