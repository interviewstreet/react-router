# react-router - Agent Guide

This is the agent-facing guide for working in this repository.

## Project Context
- Declarative routing for React

## Setup
See [`agents.yaml`](./agents.yaml) for prerequisites, commands, and ports.

### Setup Hints
- `nvm` may not be loaded in your shell. If `nvm: command not found`, source it first.
- `npm start` runs in the foreground — background it the same way.

## Running the App
- Clone the repo
- Install: `npm install`
- Dev: `npm start &`
- Access: `http://localhost:3000`

## Architecture
- React routing library (v3)
- Entry point: `modules/index.js`

## Working Agreement
- Write modular code
- Keep testable
- Incremental validation
- Commit meaningful checkpoints
- Write tests
- Validate before handoff
