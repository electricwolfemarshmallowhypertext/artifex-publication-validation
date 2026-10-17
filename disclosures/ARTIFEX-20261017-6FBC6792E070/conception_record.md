# A public verification protocol for immutable disclosure run 545ccabf98d8471181a4f773a1ced6da.

Human Conception Record

Origin ID: `ARTIFEX-20261017-DE0D02DC86A4`  
Origin recorded UTC: `2026-10-17T22:28:09Z`  
Origin hash (SHA-256): `de0d02dc86a435a5ee437c7260d2d39c7bd43f00b6e37ded214a65ee15ce6fd8`
Evidence scope: `explicit_origin`

## What is the invention?

A public verification protocol for immutable disclosure run 545ccabf98d8471181a4f773a1ced6da.

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
