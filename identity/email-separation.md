# Identity & Email Separation

## Purpose

This document defines the canonical separation between:
- Human identity
- System ownership
- Infrastructure authority
- Public-facing communication

This separation is mandatory and non-negotiable.

It exists to ensure:
- Audit safety
- Continuity under personnel change
- Legal clarity
- Prevention of authority drift
- Protection against social, technical, and organizational failure modes

---

## Core Principle (CANONICAL)

HUMANS THINK.  
SYSTEMS PERSIST.

If an email is tied to a person, it must never own infrastructure.  
If an email owns infrastructure, it must never be a person.

---

## Canonical Email Roles

### 1) hykinenterprise@gmail.com  
**STATUS:** CANONICAL SYSTEM EMAIL (PRIMARY)

**Purpose:**  
This email represents the system itself, not a human.

**Used for:**
- Supabase (Primary Owner Account)
- WordPress (Admin / System Owner)
- Infrastructure services
- Automation platforms
- Billing for core systems
- Long-term continuity and transfer safety

**Why:**
- Neutral
- Non-personal
- Durable across role changes
- Can be handed to trusted operations without identity leakage

**Rules:**
- This email OWNS SYSTEMS
- This email does NOT represent a human
- This email does NOT engage in creative work
- This email does NOT participate in conversations

**LOCK:** YES  
**CHANGE POLICY:** Forbidden without backbone version bump

---

### 2) bradley.b.kurtis@gmail.com  
**STATUS:** CANONICAL HUMAN / CREATOR EMAIL

**Purpose:**  
This email represents human cognition, authorship, and creative work.

**Used for:**
- ChatGPT Plus (paid tier)
- Research
- Writing
- Strategy
- Emotional Physics and consciousness work
- Human–AI collaboration

**Why:**
- Tied to human thought, not infrastructure
- Safe to rotate tools without breaking systems
- Prevents accidental authority escalation

**Rules:**
- This email THINKS
- This email does NOT own infrastructure
- This email does NOT control billing
- This email does NOT have irreversible system authority

**LOCK:** YES  
**CHANGE POLICY:** Allowed only for personal tool rotation

---

### 3) bk@hy-kin.com  
**STATUS:** PROFESSIONAL ALIAS / PUBLIC-FACING

**Purpose:**  
This email represents outward-facing communication.

**Used for:**
- External correspondence
- Partnerships
- Advisors
- Boards
- High-trust communications

**Why:**
- Brand-aligned
- Human-facing
- Clean separation from backend authority

**Rules:**
- This email COMMUNICATES
- This email does NOT own systems
- This email does NOT hold billing authority
- This email does NOT access canonical infrastructure

**LOCK:** YES  
**CHANGE POLICY:** Allowed for branding only

---

## WordPress Architecture

**Owner Email:** hykinenterprise@gmail.com  
**Admin:** hykinenterprise@gmail.com  
**Author Attribution:** BB (display only)

**Rules:**
- WordPress is a PLATFORM, not canon
- Ownership remains with the system email
- Authors are logical, not infrastructural

**LOCK:** YES

---

## Supabase Architecture

**Primary Owner:** hykinenterprise@gmail.com  

**Secondary Access (Explicitly Allowed):**
- bradley.b.kurtis@gmail.com (collaborator)
- bk@hy-kin.com (limited, non-owner)

**Rules:**
- ONE primary owner only
- All other emails are collaborators
- No shared ownership
- No role ambiguity

**LOCK:** YES

---

## ChatGPT / AI Stack

**Paid Tier:** bradley.b.kurtis@gmail.com  
**Role:** Creative Engine / Cognition Node

**Rules:**
- AI tools bind to the HUMAN
- Systems bind to the COMPANY
- AI may assist but never own, decide, or persist canon

**LOCK:** YES

---

## Authority Boundary

- Human identity may think, propose, and decide
- Systems may store, enforce, and persist
- AI may assist but has zero authority

Any violation of this separation is a governance failure.

---

## Status

- Architecture reviewed
- No conflicts detected
- Safe for scaling
- Safe for audits
- Safe for handoff
- Safe for sanity

**LOCK STATE:** FINAL
