[![Status](https://github.com/cloud-bulldozer/kube-burner/actions/workflows/pullrequest.yml/badge.svg?branch=master&event=push)](https://github.com/cloud-bulldozer/kube-burner/actions/workflows/pullrequest.yml)
[![Go Report Card](https://goreportcard.com/badge/github.com/cloud-bulldozer/kube-burner)](https://goreportcard.com/report/github.com/cloud-bulldozer/kube-burner)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# What is Kube-burner

Kube-burner is a Kubernetes performance and scale test orchestration toolset. It provides multi-faceted functionality, the most important of which are summarized below.

- Create, delete, and patch Kubernetes resources at scale.
- Prometheus metric collection and indexing.
- Measurements.
- Alerting.

Kube-burner is a binary application written in Golang that makes extensive usage of the official k8s client library, [client-go](https://github.com/kubernetes/client-go).

![Demo](media/demo.gif)

# Quick starting with kube-burner

To start tinkering with kube-burner now:

- Find binaries for different CPU architectures and operating systems in the [releases section of the repository](https://github.com/cloud-bulldozer/kube-burner/releases).
- Use the container image repository available at [quay](https://quay.io/repository/cloud-bulldozer/kube-burner?tab=tags).
- Referemce valid examples of configuration files, metrics profiles, and Grafana dashboards in the [examples directory](https://github.com/cloud-bulldozer/kube-burner/tree/master/examples) of the repository.
