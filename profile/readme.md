# Elyos Projects

> *From the Greek **Eleos** (Ἔλεος) — the personification of compassion and mercy.*

**Every week, millions of AI credits expire unused.** Claude Pro sessions, Gemini subscriptions, Copilot seats — unused capacity that simply evaporates. Elyos gives that capacity a purpose.

**Run your AI agent against a real community project. Do something good. Ship it.**

---

## What Elyos is

Elyos is an open platform that routes spare AI capacity toward public-benefit work — translation, education, accessibility, open science, community tools. You bring your AI subscription. Elyos provides the tasks, the structure, and the project repos. Your agent does the work. You open the PR. The output goes to real beneficiaries.

No donation required. No new account. Nothing billed beyond what you already pay.

---

## How it works

### 1 · Install the CLI

```bash
npm install -g @elyos/cli
elyos init
elyos doctor
```

### 2 · Browse open projects and pick a task

```
elyos browse
```

128+ community-approved projects are waiting — cancer research infrastructure, multilingual education resources, accessible public tools, open science datasets, and more. Each task shows a priority, estimated effort, and what the output will be used for.

### 3 · Pull the task workspace

```
elyos pull --task-file <path>
```

Elyos creates a local workspace with everything your agent needs: the task spec, acceptance criteria, context, and output destination.

### 4 · Run your AI agent

Open your agent in the workspace directory and let it do the work. Elyos works with any agent:

| Agent | How to use |
|---|---|
| **Claude Code** | `/elyos:start` — one command, fully guided |
| **Gemini CLI** | `gemini` in the workspace; then `elyos submit` |
| **Cursor** | Open workspace in Cursor; then `elyos submit` |
| **GitHub Copilot** | Open workspace in VS Code; then `elyos submit` |
| **Aider** | `aider` in the workspace; then `elyos submit` |
| **Codex** | `codex` in the workspace; then `elyos submit` |

### 5 · Submit

```
elyos submit <task-id> --repo <owner>/<repo>
```

Elyos commits the work, pushes from your fork, opens the PR, and writes a deed receipt. You get a link to your contribution.

---

## What is being built here

128 open projects across:

**Cancer research & open science**
Reproducible oncology benchmarks · open cohort catalogs · multilingual patient guides · drug-target evidence cards · Ewing sarcoma research infrastructure · biomarker extraction pipelines

**Education & literacy**
Open coding curriculum · decodable readers · numeracy and literacy from zero · OER lesson plans · civics exam prep · quiz banks · open flashcards · math manipulatives

**Accessibility & language**
Emergency phrasebooks · multilingual signage · museum labels · sign-language glossaries · braille-ready texts · keyboard layouts for under-served scripts · open pictograms

**Community & public benefit**
Food assistance maps · community resource maps · water quality explainers · climate adaptation guides · know-your-rights guides · benefits navigator · digital literacy for seniors

**Open data & knowledge**
Civic open data · open spending explainers · food security briefs · citizen-science pipelines · open map gaps · heritage recipes · world folktales · public-domain scores

[Browse all 128 repositories →](https://github.com/orgs/Elyos-Projects/repositories)

---

## Two lanes

**Donated compute** — your own subscription, your own agent, interactive and human-present. Free. Elyos never touches your credentials or runs anything on your behalf. You are always in the loop.

**Funded escrow** *(coming soon)* — donors fund specific high-impact tasks. Elyos runs them on a metered API key with a public cost ledger and a hard budget cap. Every dollar is accountable.

---

## Good-first deeds

New to Elyos? Look for tasks tagged **`good-first-deed`** — scoped, well-documented, and designed to be completable in a single session. Tasks tagged **`verified-need`** have a named beneficiary waiting for the output.

---

## Contribute to governance

Elyos projects are community-approved. After your first **merged** PR you can vote on new project proposals.

Have an idea for a good deed? [Open a proposal →](https://github.com/Elyos-Projects/registry/issues)

---

*Elyos — put the capacity to work.*