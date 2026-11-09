# Product Hub

**AI tool that routes late stakeholder feedback to the right owner before it turns into rework.**

Stanford CS 177: Introduction to Product Management with AI · Fall 2026 · Team of 4

## Highlights

- Interviewed 16 PMs at firms like Netflix and Autodesk and found late feedback forces teams to redo work
- Narrowed 3 problem areas to 1, choosing scope and rework because its cost can be measured in wasted hours and review cycles
- Sized a 1.5M-PM market (562.5K serviceable, 5,625 as a first target) from LinkedIn data and interview results
- Prototyped an AI tool that sends small fixes to their owners and routes scope changes to the PM for approval

## Built with

HTML

## My role

Helped run and synthesize the PM interviews, built the market sizing, and presented the market and solution concepts.

## Team

Alexis Tuchinda, Christian Roy, Efrain Angon-Cruz, Natnael Tadesse

## The problem

PRDs rarely land perfectly on the first read. Feedback arrives after building has started, and the PM ends up chasing people across Slack threads, docs, and meetings to figure out what changed and who it affects.

## How it works

Reviewers leave feedback in one place. AI checks each comment against the agreed scope. Small changes go straight to the person who owns that part of the work, and anything that changes the scope goes to the PM to approve before anyone builds it.

## Competitive gap

| Today's option | Where it falls short |
|---|---|
| Slack and meetings | Decisions get buried or arrive after work has started |
| Jira and task trackers | Track tasks, but not why a requirement changed or what it affects |
| Specs in Notion or Google Docs | Hold requirements, but nobody checks new feedback against them |
| Glean and search tools | Help people find information, but do not route feedback or flag scope changes |

## Concepts we explored

| Concept | What it does | Status |
|---|---|---|
| Product Hub | One place for feedback with assigned reviewers; AI sorts feedback, sends it to owners, and suggests scope updates | Lead, prototyped first |
| Drift Watch | Warns the PM when work drifts from the agreed scope | Later candidate |
| The Log | Records scope decisions and why they were made, pulled from Slack and meeting notes | Later candidate |
