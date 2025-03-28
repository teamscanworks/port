# RFC-0000: Project Vision

> Status: Final
> Date: 2025-03-25  
> Author: Scanworks Team  
---

## Summary

This document provides an overview of `Port`, including its goals, objectives, scope, deliverables, and timeline.  
Note this is a working document which can be adapted as the project evolves.

---

## Goals

`Port` generally aims at facilitating the translation between Rust-based smart contract programs so as to lower down barriers between ecosytems.

`Port` pursues the two following goals:

- (Enable-migration) Enable seamless migration Rust-based smart contract programs.  
- (Enhance-security) Enhance the security and quality of Stylus contracts by promoting best practices and robust migration patterns through the `Port` framework.

In the first phase of `Port`, we address the general goals above by instantiating them on the translation of Solana programs into Stylus-compatible programs.
As such, the rest of this vision document and the specification documents are instantiated for the particular case of the mentioned translation direction, called `StylusPort`.

See `StylusPort` [specifications](StylusPort/).