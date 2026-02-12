### OPIUM GOD MODE — Black Authority Verification 😈😈😈🖤🖤🤎🤎
by lowt_x

---

## Overview

MyMateNate is a structured Discord moderation and verification system designed for strict server enforcement.

This bot provides identity verification, age validation, anti-spam monitoring, role conflict detection, and automated disciplinary execution.

Built for controlled environments requiring consistent enforcement logic
😂😂😁😁😁😂😂😂😁😁😁😀😄😘😣🙄🙄🙄🤗🤗😏🤔🤔😣😣🙄😏😏🙄🙄🙄😶😶😑😑😐😐😐
---

## Core Systems

- Identity Verification Modal
- Age Gate Enforcement (16+ required)
- Roblox Profile Validation
- Automatic Role Assignment Engine
- Language Role Conflict Detection (ENG / THAI)
- Anti-Spam Monitor (rate-limit detection)
- Forbidden Link & Pattern Filter
- Auto Timeout System
- Kick Execution Handler
- Manual Ban / Clear Commands
- Periodic Role Scan Loop

---

## Verification Flow

1. User submits nickname, birthdate, Roblox link.
2. Birthdate is validated and age calculated.
3. Roblox URL is validated against allowed patterns.
4. Age requirement enforced (16–100).
5. Roles assigned automatically.
6. Verification logged to designated channel.

Failure cases may result in:
- Immediate kick
- Timeout penalty
- Rejection response

---

## Protection Layer

Spam Detection:
- Tracks message frequency within configurable time window.
- Exceeds threshold → message deleted + timeout.

Link Filtering:
- Blocks suspicious patterns (Nitro scams, Steam gift links, etc.)
- Immediate moderation action on detection.

Role Enforcement:
- Detects users holding both "eng" and "thai" roles.
- Executes removal logic if violation confirmed.
- Includes throttling to prevent repeated actions.

---

## Configuration (.env)

DISCORD_TOKEN=your_bot_token  
VERIFY_CMD=verify  

---

## Adjustable Parameters (in code)

- TIMEOUT_DURATION
- ROLE_CHECK_SCAN_INTERVAL
- SPAM_TIME_WINDOW
- SPAM_MESSAGE_LIMIT
- AGE_ROLE_PREFIX
- VERIFIED_ROLE_NAME
- ADULT_ROLE_NAME

---

## Commands

Prefix: ¿

¿verify         → Open verification panel  
¿checkroles     → Debug role information  
¿scan_roles     → Manual full role scan  
¿van            → Ban with confirmation interface  
¿clear          → Bulk message removal  

---

## Startup Behavior

On launch, the system:

- Displays OPIUM GOD MODE banner
- Initializes verification engine
- Activates anti-spam monitor
- Scans role enforcement matrix
- Sets system status to ONLINE

---

## Build Information

Build Started : 2024-10-12  
Last Updated  : 2026-02-12  
Version       : v3.4.7 (Authority Stable)  
Status        : Enforcement Active  

---

## Enforcement Model

1. Validate
2. Monitor
3. Detect
4. Execute

This bot operates under structured enforcement logic to minimize manual moderation.

---

Private Authority System By lowt_x
