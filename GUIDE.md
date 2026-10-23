# Reader's Guide — awesome-go

## What this project is

**Awesome Go** is the curated catalogue of **Go frameworks, libraries and
software** — the go-to list when you need a package for a job in Go and want
the community-vetted options, plus a resources section covering tooling,
benchmarks, conferences, books and communities.

## How the content is organised

- [`README.md`](README.md) — the list (this guide was written from its
  section outline and the repository tree; the README runs to 88 sections).
  After **Contents**, entries are grouped by job:
  - **Build with it:** Web Frameworks, Database and Database Drivers, ORM,
    Authentication and Authorization, Messaging, Networking, Distributed
    Systems, Stream Processing, Configuration, Logging, Error Handling,
    Testing, and dozens more — Actor Model, Artificial Intelligence,
    Blockchain, Command Line, Data Structures and Algorithms, Email, File
    Handling, Financial, Game Development, Goroutines, GUI, Images, IoT,
    JSON, Machine Learning, Natural Language Processing, Security,
    Serialization, Template Engines, Text Processing, Third-party APIs,
    Utilities, UUID, Validation, Video, WebAssembly, XML and Zero Trust.
  - **Learn & community:** Code Analysis, Editor Plugins, Go Generate Tools,
    Go Tools, Software Packages, Benchmarks, Conferences, E-Books, Gophers,
    Meetups, Style Guides, Social Media and Websites.
- The repo also carries the machinery that keeps the list honest: `main.go`
  with its test files (`main_test.go`, `maturity_test.go`,
  `stale_repositories_test.go`), `pkg/` and `tmpl/`, plus `COVERAGE.md`,
  `CONTRIBUTING.md` (the inclusion rules) and `MAINTAINERS`.

## How to use it

1. Find your job in the README **Contents** and jump to that section.
2. Compare the listed packages — each entry is a link with a one-line
   description.
3. Proposing a package? `CONTRIBUTING.md` sets the quality bar; entries are
   checked by the repo's own tooling.

## About this standalone edition

This repository is a standalone edition of
[avelino/awesome-go](https://github.com/avelino/awesome-go), converted from a
fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to the upstream
contributors; licence MIT (see `LICENSE`).
