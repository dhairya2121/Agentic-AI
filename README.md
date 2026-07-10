# Agentic-AI

A repository for exploring agentic AI systems, focused on secure credential delegation for AI agents. This project (SecurMCP) investigates how AI agents can safely interact with authenticated services without ever handling raw credentials directly.

## Overview

The core idea is a credential manager that issues short-lived, opaque session handles to agents instead of raw usernames, passwords, or cookies. All authenticated actions are proxied through the credential manager via high-level verbs, so the agent itself never sees sensitive material.

## Goals

- Prevent raw credential/cookie exposure to AI agents
- - Provide reliable login/logout flows across common services
  - - Document and fix failure modes discovered through live testing
   
    - ## Status
   
    - Actively under development and testing.
    - 
