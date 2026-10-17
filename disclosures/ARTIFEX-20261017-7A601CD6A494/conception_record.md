# A public verification protocol for immutable disclosure run 0a3f74cee77542f590a052b7cdbc8e74.

Human Conception Record

Origin ID: `ARTIFEX-20261017-B7662B2B5850`  
Origin recorded UTC: `2026-10-17T20:21:07Z`  
Origin hash (SHA-256): `b7662b2b5850d44de98b1b4bdf376303008bc3e8ca1fbe9b21d1ab3c090acf2f`
Evidence scope: `explicit_origin`

## What is the invention?

A public verification protocol for immutable disclosure run 0a3f74cee77542f590a052b7cdbc8e74.

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
