# Cotilleo Convo for OpenCode

A planned standalone OpenCode plugin for agent delegation, conversations and collaboration.

**Pre-development: not implemented.** This repository contains documentation only. There is no installable plugin, published release or verified compatibility matrix.

[Contribute](CONTRIBUTING.md) · [Issues](https://github.com/Yivas/cotilleo-convo-opencode/issues) · [Security](SECURITY.md)

## Planned capabilities

The goal is to support a coordinator that can both delegate and execute, child agents, independent peers and mixed teams. Direct, group, team and global conversations should have selective context rather than broadcasting every message to every model.

Users should be able to choose a coordinator or specialist as their conversation partner without transferring authority. An authorized view of active and historical sessions should include never-contacted sessions and show when discovery coverage is unknown.

Task delivery, acceptance, execution and verification need distinct states. Peers must be able to decline work; messages must not grant permissions. Recovery must reconcile uncertain operations instead of assuming a timeout cancelled them. These are planned requirements, not implemented behavior or security guarantees.

## Scope and status

The OpenCode plugin is intended to work independently of the Pi plugin. Its own host APIs, configuration reuse, process lifecycle, UI capabilities and permission boundaries still require research and testing. No supported host versions or installation commands are offered yet, and Pi behavior is not an OpenCode compatibility claim.

There is no sandbox, remote-control service or application in this repository. Hiding a conversation and stopping owned work will need separate controls; independent sessions must not be treated as owned children.

## Participation and license

This is a collaborative open-source project maintained by Yivas. Documentation corrections, proposals, issues and pull requests are accepted through [CONTRIBUTING](CONTRIBUTING.md). No delivery or response time is guaranteed. Security reports use the private channel in [SECURITY](SECURITY.md), not public issues.

Copyright (c) 2026 Yivas. Licensed under the [MIT License](LICENSE).
