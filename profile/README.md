# Tomshley

**World-class technical and commercial leadership for independent businesses.**

We're a founder-led firm: fractional CTO leadership, software engineering and commercialization in one place. Tomshley Labs is where we publish the open-source building blocks that run [tomshley.com](https://tomshley.com) and our clients' systems.

---

## The outer layers are already built

Every business runs on the same things around its core: the front doors customers and partners use, the orders, requests and data moving through, the rules that keep change safe, and the infrastructure underneath. We built them once, to a standard, and they're open source.

**Core** is what makes you different. **Edge** is how customers and other systems reach it. **Rules** keep the layers apart in the build. **Outside** is where it runs, in your name.

| Layer | Repository | What it does | Latest |
|---|---|---|---|
| Edge · Surface | [PasteStack](https://github.com/PasteStack) | Server-built pages, interface components and asset bundles, in their own organization. | |
| Edge · Runtime | [boilerplate-jvm](https://github.com/tomshley/boilerplate-jvm) | Hexagonal building blocks for JVM services, including reqreply and the kafka and twilio adapters. | ![latest](https://img.shields.io/github/v/tag/tomshley/boilerplate-jvm?sort=semver&label=&color=1e1e47) |
| Rules · Build | [magicroot-sbt](https://github.com/tomshley/magicroot-sbt) | Build plugins that keep the core apart from the outer layers. | ![latest](https://img.shields.io/github/v/tag/tomshley/magicroot-sbt?sort=semver&label=&color=1e1e47) |
| Outside · Ship & run | [cicd-pipelines](https://github.com/tomshley/cicd-pipelines) | CI templates, runner images and release checks for GitLab and Bitbucket. | ![latest](https://img.shields.io/github/v/tag/tomshley/cicd-pipelines?sort=semver&label=&color=1e1e47) |
| Outside · Ship & run | [base-containers](https://github.com/tomshley/base-containers) | Small, layered Alpine images for pipelines and services. | ![latest](https://img.shields.io/github/v/tag/tomshley/base-containers?sort=semver&label=&color=1e1e47) |
| Outside · Ship & run | [workload-templates-k8s](https://github.com/tomshley/workload-templates-k8s) | Kubernetes templates for services and workers. | ![latest](https://img.shields.io/github/v/tag/tomshley/workload-templates-k8s?sort=semver&label=&color=1e1e47) |
| Outside · Ship & run | [root-modules-tf](https://github.com/tomshley/root-modules-tf) | Terraform and OpenTofu modules for the edge, clusters, networks and data. | ![latest](https://img.shields.io/github/v/tag/tomshley/root-modules-tf?sort=semver&label=&color=1e1e47) |

What's left to build is your core: the products, rules and ways of serving customers that make your business different. [See how the layers fit together →](https://tomshley.com/labs)

## How we build

Every system we build has the same shape, from a website to a platform with many services and data pipelines, and it lives in your accounts:

- **The map comes first.** An architecture repository holds the north star, the agreed constraints, the principles behind each choice and every decision on record.
- **Typed contracts** every service agrees on, versioned so a change never breaks what reads it.
- **Plain-language tests** for every service, written before the code and run before each deploy.
- **Infrastructure as reviewed code**, for each environment.
- **Core services**, each with one clear job, built on the outer layers.

## Yours to keep

- **Mainstream underneath.** Pekko, Kafka, PostgreSQL, Kubernetes, Terraform and OpenTofu, on Google Cloud or AWS, through GitLab or Bitbucket.
- **Thin and replaceable.** Each layer is a library or a template. Lift one out and replace it, and your core doesn't change.
- **Open source.** Apache License 2.0, with no license fee.

## Contributing

Opinionated, and open to good changes. Each repository says what it's for and what's out of scope. Bug fixes, security, accessibility and documentation improvements are especially welcome.

1. Open an issue that describes the change.
2. Fork the repository.
3. Send a focused pull request with clean, scoped commits.
4. Found a vulnerability? Report it privately, as the repository's `SECURITY.md` describes, never in a public issue.

## Work with us

- **Start a conversation:** [tomshley.com/contact](https://tomshley.com/contact) or [office@tomshley.com](mailto:office@tomshley.com)
- **We're hiring:** Senior Software Engineer, Scala, and Business Development Lead. Contract or full-time, remote in the US. [tomshley.com/careers](https://tomshley.com/careers)
- **Follow us:** [LinkedIn](https://www.linkedin.com/company/tomshley)

---

Maintained by Tomshley LLC. Unless otherwise noted, everything here is licensed under the Apache License 2.0.
