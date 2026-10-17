# A public verification protocol for immutable disclosure run c6ed9bb17cdd453ab0a6769fd32c6320.

Human Conception Record

Origin ID: `ARTIFEX-20261017-39B2D50FD540`  
Origin recorded UTC: `2026-10-17T23:36:07Z`  
Origin hash (SHA-256): `39b2d50fd54070f84e111cfa9dea0579caf9ada6da12367c2987abfa5fe6509e`
Evidence scope: `explicit_origin`

## What is the invention?

A public verification protocol for immutable disclosure run c6ed9bb17cdd453ab0a6769fd32c6320.

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
