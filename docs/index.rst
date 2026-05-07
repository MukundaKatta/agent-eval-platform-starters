Agent Evaluation Field Notes
============================

Agent Evaluation Field Notes is a compact public collection of scorecard
templates, trajectory replay checklists, RAG guardrail smoke tests, small
datasets, and demo launch pages for evaluating tool-using AI agents.

The goal is practical repeatability. These artifacts are intentionally small
enough to copy into a real engineering workflow and concrete enough to support
review during agent rollout decisions.

Public Anchors
--------------

* GitHub source: https://github.com/MukundaKatta/agent-eval-platform-starters
* GitLab mirror: https://gitlab.com/mukunda.vjcs6/agent-eval-platform-starters
* Gitea mirror: https://gitea.com/MukundaKatta/agent-eval-platform-starters
* Cloudflare Pages: https://agent-eval-field-notes.pages.dev
* Firebase Hosting: https://agent-eval-field-notes.web.app
* StackBlitz workspace: https://stackblitz.com/github/MukundaKatta/agent-eval-platform-starters

What Is Included
----------------

* Operational scorecard patterns for tool-using agents.
* Trajectory replay notes for debugging agent regressions.
* RAG guardrail smoke tests for prompt injection and vector poisoning checks.
* Starter artifacts for cloud, notebook, data, docs, and developer platforms.
* Small public datasets that can be reused in demos and documentation.

Repository Layout
-----------------

``starter-artifacts/scorecard-api``
  FastAPI scorecard endpoint that returns structured evaluation examples.

``starter-artifacts/static-site``
  Static public landing page for the field-notes surface.

``starter-artifacts/notebook``
  Notebook-style markdown walkthrough for scorecard analysis.

``starter-artifacts/dataset``
  Small CSV and metadata files for platform submissions.

``starter-artifacts/docs``
  Reusable documentation notes and submission copy.
