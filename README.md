# Hi there 👋 — I'm DC0SK

I build **open-source Rust systems** at the intersection of **amateur radio, computational electromagnetics, and practical HF data communication**. My work turns real engineering requirements into reliable, verifiable tools — from antenna-length planning and NEC-compatible modeling to plugin-based digital modem architecture and rig remote control.

🌐 **[View my project page →](https://dc0sk.github.io/)**

## Abstract

My approach is strongly rooted in **requirements engineering**. I define clear problem boundaries, keep interfaces explicit, validate assumptions with testable designs, and evolve systems in modular steps that stay maintainable over time. The goal is not only to make things work, but to make them **understandable, verifiable, and reusable** by others.

I am deeply dedicated to **Free and Open Source Software (FOSS)**: building in public, choosing copyleft licenses for shared progress, and contributing software that helps the radio and engineering communities learn, experiment, and collaborate.

## Projects

| Project | What it does | Language |
| --- | --- | --- |
| [**rusty-wire**](https://github.com/dc0sk/rusty-wire) | Wire-antenna planning across ham-radio and shortwave bands | Rust |
| [**fnec-rust**](https://github.com/dc0sk/fnec-rust) | A free and modern NEC client for antenna modeling | Rust |
| [**OpenPulseHF**](https://dc0sk.github.io/OpenPulseHF/) | Transmit data via HF — plugin-based digital modem | Rust |
| [**landline**](https://github.com/dc0sk/landline) | Open-source ham-radio rig remote control | Rust |
| [**K4remote**](https://dc0sk.github.io/K4remote/) | An open-source remote panel for the Elecraft K4 | Rust |

→ Browse everything at **[github.com/dc0sk?tab=repositories](https://github.com/dc0sk?tab=repositories)**

## How I Engineer

I work **from requirements to reproducible results**, and I hold project stewardship to the same standard as code quality: clear scope, transparent progress, practical outcomes.

- **Traceable execution** — every capability traces from a stated requirement through design and implementation to the tests that prove it. In `rusty-wire`, antenna calculations are clear models with documented assumptions, so users can verify *why* a result was produced.
- **Challenging existing solutions** — in `fnec-rust` I'm not just reusing classic NEC ideas but rethinking solver structure and modularity for portability, maintainability, and long-term evolution.
- **Layered validation** — from parser/model consistency checks to numerical sanity checks and benchmark comparisons, so changes are measurable and regressions surface early.
- **Quality gates before every push** — format, lint (warnings as errors), the full test suite, and a security/dependency audit run automatically; coverage is a gate before a release, not an afterthought.
- **Small, well-labeled changes** — one logical change per branch, docs updated alongside the code, and disciplined semver releases with changelogs and release notes.
- **Stable interfaces** — public plugin and API surfaces are versioned semantically, so extensions survive framework upgrades and every break ships with a migration path.

## Why Sponsor My Work

Your sponsorship helps me dedicate sustained time to high-value FOSS engineering for radio and computational electromagnetics.

With sponsorship, I can:

- deliver better-documented releases and onboarding material,
- expand automated testing and reproducibility infrastructure,
- prioritize community issues and requested features,
- keep core tooling open, modular, and accessible.

If you value rigorous requirements engineering, open collaboration, and durable technical work, sponsoring is the most direct way to help this ecosystem grow.

**What sponsors can expect:** regular public progress updates, transparent priorities and scope decisions, responsible maintenance of released code, and respectful, constructive community collaboration.

## Support

If my work is useful to you, a donation directly funds more open tooling for the radio and engineering communities.

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/donate/?hosted_button_id=WY9U4MQ3ZAQWC)

<!--
**dc0sk/dc0sk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
