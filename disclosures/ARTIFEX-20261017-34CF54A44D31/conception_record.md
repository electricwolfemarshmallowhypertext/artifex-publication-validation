# A public verification protocol for immutable disclosure run 6e26c6420fd34a9094f1b28fa978d4c1.

Human Conception Record

Origin ID: `ARTIFEX-20261017-CF777ECFF29C`  
Origin recorded UTC: `2026-10-17T21:13:47Z`  
Origin hash (SHA-256): `cf777ecff29ceb58a9eb9cbb9458824722667cf3dcb7d6255f564879a51618cd`
Evidence scope: `explicit_origin`

## What is the invention?

A public verification protocol for immutable disclosure run 6e26c6420fd34a9094f1b28fa978d4c1.

## What problem does it solve?

Defensive disclosures need proof that their signed artifacts are reachable without credentials.

## How does it work?

Push a signed commit and tag, then retrieve the repository and tagged artifacts without authentication.

## What are the essential parts?

A public repository check, signed commit, immutable tag, tagged receipt lookup, and deterministic hash comparison.

## What did AI help build?

AI produced the implementation, public access checks, failure paths, documentation, and integration test harness.

## What did you decide, design, or change?

The human required unauthenticated verification, selected the tagged-tree invariant, and approved the final mechanism.
