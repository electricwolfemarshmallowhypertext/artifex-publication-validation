# A public verification protocol for immutable disclosure run 391ae578c84d416a972940dcced495a0.

Human Conception Record

Origin ID: `ARTIFEX-20261017-9B2731C0821B`  
Origin recorded UTC: `2026-10-17T22:08:51Z`  
Origin hash (SHA-256): `9b2731c0821b230dd15d2b0f2b3bf62b3978679e4cdd915421b30bfab8b8805e`
Evidence scope: `explicit_origin`

## What is the invention?

A public verification protocol for immutable disclosure run 391ae578c84d416a972940dcced495a0.

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
