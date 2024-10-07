# [RFC] Nebula Pack Initial Structure and Goals

**Authors**: Keagan Gilmore

**Status**: Active

## Summary
This RFC proposes the foundational structure and goals for Nebula Pack, a new package manager for Lua designed to improve accessibility for non-Unix systems.

## Motivation
LuaRocks can be challenging to set up, especially for beginners on Windows. Nebula Pack aims to provide a more intuitive and beginner-friendly alternative with better support for low-level modules.

## Design
- Backend and CLI will be built in Go.
- The compiler will be developed in Rust or an alternative language.
- Database structure will manage package data efficiently.
- Automation tools for C/C++ Lua modules will be explored.

## Alternatives
- Improve LuaRocks documentation to help Windows users.
- Modify existing LuaRocks features for easier adoption.

## Drawbacks
- Creating a new package manager may fragment the Lua ecosystem, requiring additional effort to get community buy-in.

## Adoption
- Plan to create conversion tools to migrate LuaRocks packages to Nebula Pack with minimal friction.

## Timeline
- Phase 1: API and CLI (current work).
- Phase 2: Compiler development.
- Phase 3: Community outreach and ecosystem growth.
