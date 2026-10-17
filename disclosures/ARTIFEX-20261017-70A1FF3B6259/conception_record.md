# A public verification protocol for immutable disclosure run c8a30079a0434f0aaa045b72d35ea9de.

Human Conception Record

Origin ID: `ARTIFEX-20261017-ED708752DBC5`  
Origin recorded UTC: `2026-10-17T20:53:53Z`  
Origin hash (SHA-256): `ed708752dbc5628ff3e7b51830dbea5371de51a23ef7af22914e4917934aa5ce`
Evidence scope: `explicit_origin`

## What is the invention?

A public verification protocol for immutable disclosure run c8a30079a0434f0aaa045b72d35ea9de.

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
