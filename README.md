# Hi there

Backend developer interested in how things work below the framework level.

I build small tools when existing ones are either too much or not quite right. I like CLI applications, Linux, automation, and digging into the details of dependencies, build systems and runtime behavior.

## Selected projects

### [bartender](https://github.com/decatile/bartender)

Python CLI for recovering dependency versions from a project's Git history.

Given a `requirements.txt` or `pyproject.toml`, it uses the last modification of the dependency file as a point in time, queries PyPI for releases available at that moment, and produces pinned dependencies.

Things I worked with here:

* Git history and `git blame` from inside Python
* PyPI API
* async I/O with `httpx`
* CLI design
* dependency file parsing
* separating repository, parsing and PyPI concerns
* dry-run and backup behavior

The interesting part is less the CLI itself and more the problem: making an old Python project reproducible when its dependencies were never properly pinned.

### [colored-goodies](https://github.com/decatile/colored-goodies)

Rust library for expressive terminal formatting.

It adds macros for colored output with compile-time, runtime and no-color modes, including named colors, hex colors and styles.

This is a smaller project, but it gets into parts of Rust that are easy to avoid in ordinary application code:

* procedural macros
* compile-time expansion
* feature flags
* runtime color detection
* API design around formatting syntax
* integration with the `colored` crate

### [ansible-playbooks](https://github.com/decatile/ansible-playbooks)

Ansible automation for configuring systems.

One of the playbooks turns a fresh Alpine Linux VM into a network gateway/router: key-only SSH access, firewall configuration, routing between interfaces, passwordless sudo and configuration required for running containers as an unprivileged user.

This is mostly about infrastructure rather than application development, but it is part of the same interest in understanding and automating the system underneath the application.

## What I work with

**Languages**

Python · Java · JavaScript · Rust · Bash

**Systems**

Linux · automation (Ansible) · networking (firewalls) · containers (docker, k8s)

**Interested in**

Backend engineering · developer tooling · infrastructure · systems programming

## Contact

Telegram: [@decatile](https://t.me/decatile)

GitHub: [github.com/decatile](https://github.com/decatile)
