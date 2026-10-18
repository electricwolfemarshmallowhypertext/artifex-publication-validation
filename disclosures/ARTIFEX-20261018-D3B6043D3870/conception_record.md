# A public verification protocol for immutable disclosure run 7ca2e79a00294d8dad147972c1f78cec.

Human Conception Record

Origin ID: `ARTIFEX-20261018-6E2487FA5592`  
Origin recorded UTC: `2026-10-18T04:24:41Z`  
Origin hash (SHA-256): `6e2487fa559297a6474fc08bc3eab57bee83ef42f5f168acf6180d77096e98c7`
Evidence scope: `explicit_origin`

## What is the invention?

A public verification protocol for immutable disclosure run 7ca2e79a00294d8dad147972c1f78cec.

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
