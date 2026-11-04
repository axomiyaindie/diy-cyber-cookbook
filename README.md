# DIY Cyber Cookbook

**Hands-on, build-it-yourself cybersecurity recipes.** Each recipe is a step-by-step
how-to: what you'll build or practice, the tools you need, the steps, and how to
verify it worked.

This is a cookbook, not a link dump - every recipe is something you do yourself.

---

## Table of Contents

- [What this is](#what-this-is)
- [Who it's for](#who-its-for)
- [Recipe format](#recipe-format)
- [The recipes](#the-recipes)
- [Getting started](#getting-started)
- [Project structure](#project-structure)
- [Safety and ethics](#safety-and-ethics)
- [Contributing](#contributing)
- [License](#license)

---

## What this is

A collection of practical cybersecurity recipes for learners and tinkerers who want
to practice, not just read. Every recipe is written to be followed on your own
machine, in your own isolated lab, using legal and safe targets.

The goal is simple: **you build and practice every recipe yourself.** No passive
reading, no copy-paste without understanding.

---

## Who it's for

- Beginners who want a structured path into hands-on security
- Students preparing for labs, CTFs, or certifications
- Developers who want to understand how attacks work so they can defend better
- Anyone who prefers learning by doing

You do not need to be an expert. Each recipe assumes basic comfort with a computer
and a willingness to install tools and break things in a safe environment.

---

## Recipe format

Every recipe follows the same structure so you always know what to expect:

| Section | What it covers |
|---------|----------------|
| **Goal** | What you'll build or practice, and why it matters |
| **Tools** | What you need installed, with official links |
| **Setup** | How to prepare the environment safely |
| **Steps** | Numbered, reproducible instructions |
| **Verify** | How to confirm it worked |
| **Extend** | Ideas to go further on your own |

---

## The recipes

| # | Recipe | What you do | Difficulty |
|---|--------|-------------|------------|
| 01 | [Home Lab](./01-home-lab/) | Build an isolated lab with virtual machines | Beginner |
| 02 | [Recon Basics](./02-recon-basics/) | Gather information on a target you own | Beginner |
| 03 | [Network Scanning](./03-network-scanning/) | Scan your own lab network | Beginner |
| 04 | [Web Testing Basics](./04-web-testing-basics/) | Test a deliberately vulnerable web app | Intermediate |
| 05 | [Password Cracking](./05-password-cracking/) | Crack hashes in a controlled exercise | Intermediate |
| 06 | [Forensics Basics](./06-forensics-basics/) | Analyze a disk image | Intermediate |
| 07 | [Report Writing](./07-report-writing/) | Turn findings into a clear report | Beginner |

> Start with **01 Home Lab** - every other recipe assumes you have a safe place to practice.

---

## Getting started

1. Pick a recipe from the table above.
2. Open its folder and read the `README.md`.
3. Follow the **Tools** and **Setup** sections first.
4. Work through the **Steps** in your own lab.
5. Confirm with **Verify**, then try the **Extend** ideas.

Each recipe is self-contained - you don't need to do them in order, though the home
lab recipe is recommended first.

---

## Project structure

```
diy-cyber-cookbook/
├── README.md                  <- you are here
├── 01-home-lab/
│   └── README.md              <- goal, tools, setup, steps, verify, extend
├── 02-recon-basics/
│   └── README.md
├── 03-network-scanning/
│   └── README.md
├── 04-web-testing-basics/
│   └── README.md
├── 05-password-cracking/
│   └── README.md
├── 06-forensics-basics/
│   └── README.md
└── 07-report-writing/
    └── README.md
```

---

## Safety and ethics

- Only test systems **you own** or have **explicit written permission** to test.
- Use isolated virtual machines and legal practice targets.
- Never use these recipes against public systems, networks, or people.
- Follow the law in your country and your organization's policies.

Cybersecurity skills are powerful. Use them to defend, learn, and protect - not to harm.

---

## Contributing

Contributions are welcome. To keep the cookbook consistent:

- One recipe per folder, with a `README.md`.
- Follow the standard format: Goal / Tools / Setup / Steps / Verify / Extend.
- Keep every recipe **buildable** - if it's just a list of links, it doesn't belong here.
- Test your steps before submitting.
- No illegal, harmful, or unauthorized content.

Open a pull request with a short description of what you added or fixed.

---

## License

MIT - use, fork, and share freely.

---

## Acknowledgements

Built for learners who prefer doing over reading. If this helped you, share it
with someone starting out.
```