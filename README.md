# [Speedia Control](https://speedia.net/control/) &middot; [![Roadmap](https://img.shields.io/badge/roadmap-014737)](https://github.com/orgs/speedianet/projects/2) [![Demo](https://img.shields.io/badge/read--only_demo-233876)](https://control.demo.speedia.net:3141/_/) [![Community](https://img.shields.io/badge/community-751A3D)](https://github.com/orgs/speedianet/discussions) [![Deploy](https://img.shields.io/badge/deploy_now-a16207)]([https://github.com/orgs/speedianet/discussions](https://speedia.net/blog/docs/speedia-control/getting-started/installation/))

Speedia Control is a self-hosted PaaS platform written in Go. It's incredibly lightweight, relying solely on the standard dependencies that come with openSUSE MicroOS (such as Podman). The operating system, with Control running, should comfortably fit within 512MB of RAM.

A read-only demo of the dashboard is available at [https://control.demo.speedia.net:3141/\_/](https://control.demo.speedia.net:3141/_/). The default credentials are `demo` and `abc123`.

Speedia Control is a single binary and comes with a user-friendly dashboard, REST API, and CLI for seamless container fleet management. **It does not rely on Kubernetes** and is designed to be extremely easy to use, requiring little to no technical knowledge despite utilizing top-tier technologies.

With Speedia Control, you can create multiple users with their own resource quotas. Each user can deploy their containers with their own scope (rootless), and everything technical, such as reverse proxy, autoscaling, rate limiting, SSL certificates, backups etc, is handled automatically.

It integrates perfectly with [Speedia OS](https://github.com/speedianet/os), an open-source container operating system designed to eliminate the need for writing Dockerfiles. By combining Speedia Control and Speedia OS, you can **have a fully functional PaaS platform without needing any knowledge of infrastructure or containers**.

In this repository, you'll find the roadmap and all issues related to Speedia Control. Although Speedia Control is closed source, it is free for personal use. Read more about it on the [website](https://speedia.net/control/).
