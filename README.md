# Product Hub

**An AI tool that sends late stakeholder feedback to the right owner before it causes rework.**

Stanford CS 177: Introduction to Product Management with AI · Fall 2026 · Team of 4

## Highlights

- Found that late feedback forces teams to redo work, after interviewing 16 product managers (PMs) at companies including Netflix and Autodesk
- Sized the market at 1.5M PMs, with 562.5K reachable and 5,625 as a first target, using LinkedIn data and interview results
- Prototyped a tool that sends small fixes straight to their owners and routes scope changes to the PM for approval

## Built with

HTML

---

## The problem

A product requirements document (PRD) rarely lands right on the first read. Feedback shows up after building starts, and the PM ends up chasing people across Slack, docs, and meetings to learn what changed and who it affects.

## How it works

Reviewers leave feedback in one place. AI checks each comment against the agreed scope. Small changes go to the person who owns that part of the work. Anything that changes the scope goes to the PM for approval before anyone builds it.

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
