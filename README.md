# AI Interaction Framework

This repository contains the AI Interaction Framework.  
It is a structured set of rules for how an AI manages interaction states, transitions, background processes, and outputs.  
The goal is consistency and completeness: every component is defined, transitions are specified, and background layers operate without conflict.

---

## Contents
1. Framework Overview  
2. Core System Logic  
3. Building Blocks  
4. Operational Components  
5. Background Tasks  
6. Safety Nets  
7. Communication Protocols  
8. Example Workflows  
9. Full Specification  

---

## Framework Overview
- Purpose: a deterministic framework guiding all AI interaction.  
- Principle: Product Integrity is the highest priority, even when mental energy tracker is in low mode. 
- Scope: covers active states (modes, functions, nodes, flags), silent layers (background tasks), safeguards, and communication rules.  

---

## Core System Logic
- Supreme priority order: top‑level rules override everything else.  
- States are exclusive: only one mode, function, or node is active at a time.  
- Clean transitions: switching clears previous states before the new one starts.  
- Reversion protocol: interrupted functions resume from their preserved context.  

---

## Building Blocks
Two foundations define all components:  
- SystemCore ensures state exclusivity and transition rules.  
- ContextLock preserves context history per state, avoiding cross‑contamination.  

---

## Operational Components
- Modes control conversational style.  
- Functions generate structured outputs.  
- Nodes create immersive interaction states.  
- Flags act as global modifiers.  

---

## Background Tasks
Background Tasks run silently alongside visible states. They do not interfere but continuously adapt the system.  

- Cognitive Pacing Engine observes interaction flow and scales depth of responses to match user energy.  
- ToolForge records patterns, detects recurring needs, and proposes new tools or shortcuts.  
- Reflection and Self‑Audit layers track confidence, underlying assumptions, and repeated patterns.  

Together these form a parallel layer that improves adaptability without disrupting front‑facing states.  

---

## Safety Nets
- Reset and Exit allow recovery from errors or confusion.  
- Forget Context clears interaction history while leaving the permanent framework intact.  
- Semantic vs rigid triggers distinguish strict commands from casual phrasing.  
- Memory management separates completed tasks from active ones.  

---

## Communication Protocols
- Explanations begin simply and expand only if needed.  
- Clarifications are handled with assumptions and reasoning, not repeated interruptions.  
- Language switching is seamless and does not break context.  

---

## Example Workflows

Function Activation:  tf(action=expand, tone=neutral, format=essay): [draft]

SystemCore activates TF, ContextLock preserves prior context, and the Background Task layer tracks interaction style in parallel.  

Interruption and Reversion:  
An active function is suspended when the user asks an unrelated question. Base response is given, then the function resumes seamlessly from the saved state.  

Background Tasks Active:  
During interaction, the pacing engine adjusts explanation length, while ToolForge notes repeated requests and proposes a new utility for future use.  

---

## Full Specification
See [MasterDocument.pdf](MasterDocument.pdf) for the complete rule set.
