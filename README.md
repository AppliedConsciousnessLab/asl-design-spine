# ASL Design Spine

This repository is the canonical design spine for Applied Safety Lab (ASL).

It defines:
- What is allowed to exist
- Who has authority to approve change
- How canon is promoted
- How systems are governed across time

It does NOT contain:
- Data
- Runtime state
- Secrets
- Automation
- User content
- AI outputs

## Core Principle

HUMANS THINK.  
SYSTEMS PERSIST.

If an artifact can change without explicit approval, it does not belong here.

## Authority Model

GitHub (this repo) defines canon and constraints.  
Supabase records state and memory.  
Automation executes approved movement.  
AI assists but never decides.

## Change Policy

This repository changes only when:
- A new backbone version is declared
- Changes are approved by the canonical authority
- The change is logged in the CHANGELOG

This is a governance system, not a workflow.
