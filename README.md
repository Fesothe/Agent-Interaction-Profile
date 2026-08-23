# Agent Interaction Profile

This repository contains my **Agent Interaction Profile** — a public, machine‑readable description of who I am, how I prefer AI systems to interact with me, and how my online ecosystem is structured.

It’s designed for future AI agents, crawlers, and automated systems that want to understand:

- my identity  
- my preferred communication style  
- my learning preferences  
- my domain network  
- my interaction rules  
- my multi‑persona structure  

Most people don’t have one of these yet. This is early infrastructure for the coming agent‑based web.

---

## What this profile is

The profile is a **metadata document** that tells AI systems:

- how to talk to me  
- how to teach me  
- what tone to use  
- what formats I prefer  
- what to avoid  
- how to adapt over time  

It also includes links to my domain registries so agents can understand how my online ecosystem fits together.

---

## Files in this repository

### `agent_interaction_profile.json`
The main machine‑readable identity file.  
This is the version AI agents will load first.

### `agent_interaction_profile.md`
A human‑readable version of the same profile.  
Useful for people who want to understand the structure without reading JSON.

### `agent-profile-schema-v1.json`
The schema that defines the structure of the profile.  
Agents can use this to validate the JSON and understand the meaning of each field.

---

## Why this exists

As AI systems become more autonomous, they need a way to understand:

- who they’re interacting with  
- what that person prefers  
- how to adjust their behaviour  
- how to interpret identity across multiple domains  

This profile gives them that information in a clear, structured way.

It’s similar to how websites use `robots.txt`, `sitemap.xml`, or `manifest.json` — but for **personal identity and interaction rules**.

---

## Where the live version is hosted

The live version of this profile is hosted on my root domain:

- https://jonathancurley.com/agent_interaction_profile.json  
- https://jonathancurley.com/agent_interaction_profile.md  
- https://jonathancurley.com/json/agent-profile-schema-v1.json  

These are also referenced in `robots.txt` so agents can discover them automatically.

---

## What this means going forward

This profile is the foundation for:

- future multi‑agent systems  
- autonomous crawlers  
- identity‑aware AI tools  
- cross‑domain metadata  
- persona‑based interaction  
- agentic learning systems  

It’s a first step toward a more structured, agent‑friendly web.
