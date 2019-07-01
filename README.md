# VMware CodeHouse 2019

This document will serve as guidance for attendees and mentors of VMware CodeHouse 2019.

The goal of the hackathon will be to create an application that furthers STEM eduction and/or Diversity & Inclusion.

This application will run on Kubernetes together with other needed services (databases etc), can connect to third-party APIs to extract/modify/store data, and should be well documented so it can be shared as an example application after the hackathon.

We will be using [kind](https://github.com/kubernetes-sigs/kind) as the tool to run Kubernetes on the attendees' laptops.

## Required reading

To make sure you are comfortable with the environment we will be using, please read through the following documents well in advance:

- Get Started with Docker [part 1](https://docs.docker.com/get-started/) and [part 2](https://docs.docker.com/get-started/part2/)
- [What is Kubernetes](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/)
- [What is kind](https://kind.sigs.k8s.io)
- [Kind Quickstart](https://kind.sigs.k8s.io/docs/user/quick-start/)
- Go through at least one of the examples in [Kubernetes Examples](https://github.com/kubernetes/examples)

## Completion of pre-req tasks

Once you have completed these tasks, make a pull request to this repository with a Markdown file in this format:

`firstname-lastname.md`
```
I've finished reading through the pre-req docs and ran at least one example K8s app on kind on my laptop!
```