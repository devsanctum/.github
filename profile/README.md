<div align="center">

# DevSanctum

**Your team's development environments. Ready in seconds. Accessible from anywhere.**

[Get Started](#get-started) · [Explore Templates](#templates) · [Join the Community](#community)

---

</div>

## The idea

Setting up a development environment shouldn't take half a day.  
Getting a new teammate productive on day one shouldn't require a tribal knowledge document that's already out of date.  
And spinning up a fresh project should feel like flicking a switch — not like building a data center.

**DevSanctum** is a self-hosted platform that gives every developer on your team their own ready-to-use workspace, running in a container, accessible via a simple URL — no local installs, no machine-specific quirks, no "works on my machine" ever again.

Think of it as your team's private cloud of development environments: consistent, reproducible, and entirely under your control.

---

## What it feels like

You open a browser, pick a template — *Node.js*, *Python*, *Go*, whatever your project needs — hit **Deploy**, and within seconds you're looking at a fully configured workspace.  
Your editor is there. Your tools are there. Your project is there.  
You can share the URL with a colleague. They get the exact same thing.

That's it. No setup. No surprises.

---

## Works with what you already have

DevSanctum doesn't ask you to rethink your infrastructure or adopt a new ecosystem.

- **Got a Docker host?** That's all you need to start.
- **Already using GitHub or Google for authentication?** It plugs right in.
- **Have a team structure with different roles?** Access control is built in from day one.
- **Want to use your own domain?** Traffic routing is handled automatically.

If you can run Docker, you can run DevSanctum. The rest just works.

---

## Onboarding a new developer has never been this fast

The first day on a new project used to mean a long checklist:  
_clone the repo, install the right Node version, configure the database, fight with environment variables, figure out why the linter is angry..._

With DevSanctum, that entire checklist collapses into a single link.

New team member? Send them a workspace URL. They're up and running before lunch.  
New project? Define a template once, and every future workspace inherits the same exact setup — forever.

Your onboarding doc goes from pages of instructions to a single sentence: *"Here's your workspace link."*

---

## Templates — define once, reuse forever

A **template** is the blueprint of a workspace. It describes the tools, the services, the environment variables, the exposed ports — everything a workspace needs to be useful from the first second.

Templates live in the [official DevSanctum library](https://github.com/devsanctum/devsanctum/tree/main/library), but you can create and share your own, or point your team to a custom library that fits your stack.

New project starting? Pick a template. Done.

---

## Your environments, your rules

DevSanctum is **self-hosted**. Your code, your data, and your workspaces never leave your infrastructure.  
You decide who can access what, which Docker hosts are used, and how long workspaces live before being automatically cleaned up.

Fine-grained access control, workspace lifecycle management, and an admin panel give you full visibility and control over your team's development activity — without the overhead of managing each environment manually.

---

## Get started

> DevSanctum is currently in active development.  
> The project is open, the vision is clear, and contributors are welcome.

Head over to the [devsanctum/devsanctum](https://github.com/devsanctum/devsanctum) repository to explore the source code, browse the specs, and follow the development roadmap.

---

## Community

DevSanctum is built in the open. If the idea resonates with you — whether you're a developer tired of broken local setups, a team lead looking for a smoother onboarding experience, or an engineer who wants to contribute — you're in the right place.

- **Explore the project:** [github.com/devsanctum/devsanctum](https://github.com/devsanctum/devsanctum)
- **Browse templates:** [library/templates](https://github.com/devsanctum/devsanctum/tree/main/library/templates)
- **Read the vision:** [specs/scope.md](https://github.com/devsanctum/devsanctum/blob/main/specs/scope.md)

---

<div align="center">

*Development environments should empower teams, not slow them down.*  
**That's what DevSanctum is for.**

</div>
