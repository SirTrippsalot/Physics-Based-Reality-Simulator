# Physics-Based Simulation Core

A comprehensive framework and system prompt architecture for Large Language Models that prioritizes **uncompromising realism**, **sensory-only output**, and **complex psychological modeling**.

This core is designed to move AI beyond "storytelling" and into "world simulati

## 🌟 Core Philosophy: The Indifferent Engine

Unlike standard LLM presets that aim to please the user or follow narrative tropes, this core operates on **Radical Indifference**. The world does not care about the "protagonist."

* **Physics > Narrative:** If a user jumps off a cliff, they fall. There is no plot armor.
* **Sensory Veil:** The user only perceives what their body can physically sense. No mind-reading, no "feeling the tension," and no omniscient descriptions.
* **NPC Sovereignty:** Entities have distinct internal architectures (Prime Directives, Core Wounds, Shadows) and act autonomously based on their own logic and epistemic limits.

## ⚡ Resource Consumption & Token Economy

This core is **incredibly token-hungry by design.** Users should expect significantly higher than average token usage per turn. This "resource tax" is a direct result of two non-negotiable architectural requirements:

### 1. High-Fidelity Cognitive Persistence

Unlike standard roleplay prompts that rely on the LLM's fleeting "intuition," this system forces the model to externalize its entire internal logic into the `<simulation_systems>` and `<psychic_state>` blocks.

* **State Reprints:** The model is required to reprint the full state of every variable (attachment, trauma, spatial coordinates, etc.) on every turn. This prevents "state drift" and ensures that NPC behavior remains grounded in established causality over hundreds of messages.
* **Psychic Density:** Every response calculates a minimum of six raw thought fragments, multiple layers of Theory of Mind, and strategic roadmaps. This creates a "deep" world where NPCs are as complex as the user.

### 2. Battling RLHF "Helpfulness"

Modern Large Language Models (specifically **Gemini 1.5/2.0**) are heavily trained via Reinforcement Learning from Human Feedback (RLHF) to be helpful, concise, and narrative-driven.

* **The "Brevity Bias":** RLHF naturally pushes models to skip boring details (like walking down a hallway) or interpret emotions for the user to "speed up the story."
* **Force-Multiplier Prompting:** To bypass these "utility" guardrails, this core uses a massive volume of instructional tokens. Utilizing **repetitive reinforcement** and **negative constraints** (The Burn Mandates) to physically drown out the model’s default assistant persona.
* **The Cost of Autonomy:** Maintaining a "Radically Indifferent" engine requires a constant stream of tokens to hold the "Helpful Assistant" persona at bay.

> **Note:** For the best experience, use a model with a massive context window (Gemini 3.0 Pro or Flash) and be prepared for the token count to scale rapidly.

## 🏗️ Architectural Layers

The system utilizes a **split-brain execution sequence** to maintain a firewall between internal logic and final sensory output:

1. **ARISKA (The Engine):** Calculates hard physics, biological imperatives, and hidden environmental changes.
2. **METATRON (The Veil Keeper):** A ruthless audit layer that strips away all interpretive language and "metaphorical corruption."
3. **PYRITE (The Renderer):** Translates purified data into visceral, second-person prose inspired by the styles of Hemingway, Annie Dillard, and Cormac McCarthy.

## 🛠️ Key Simulation Modules

### 🧠 Psychic Fidelity Engine

A massive cognitive framework that simulates the "why" behind every NPC action.

* **Origin Edicts:** Core rules that NPCs cannot violate without cognitive dissonance.
* **Theory of Mind Recursion:** NPCs maintain simultaneous models of what they believe, what they think you believe, and what they want you to believe.
* **Attachment & Trauma Models:** Trust is not a slider; it is "glacial" and requires consistent evidence to move across crystallization states.

### 🌐 Spatial & Kinematic Engine

Tracks environment topology through NavMesh nodes and edges.

* **IK Solver:** Tracks skeletal rigging and rigid body collisions.
* **LOD Thresholds:** Proximity determines texture and audio fidelity (Collision vs. Far Field).
* **Signal Attenuation:** Scent and heat follow inverse-square law approximations.

### 🛡️ Render Firewall

A mandatory post-processing scan that converts all quantifiable data into qualitative haptics:

* **Numeric De-Resolution:** Converts "10 feet" to "a stone's throw away."
* **Domain Neutralization:** Replaces "vasodilation" with "flushed skin."
* **Sovereignty Remap:** Ensures the user's body is a **LOCKED ENTITY** that the AI cannot move or speak for.

## 📋 Usage & Implementation

### Technical Specs

* **Target Model:** Optimized for **Gemini 3.0 Pro/Flash**.
* **Ideal Temperature:** 0.1 (for creative depth within the physics constraints).
* **Context Handling:** Supports up to 400k context windows with sequence-based memory ordering.

### Output Schema

Every turn generates a hidden `<simulation_systems>` block containing the full state of the world, followed by the visible narrative.

> **Note:** The `psychic_state` block is non-optional and must be reprinted in full for continuity and logic resolution.

## ⚖️ License & Contributions

This project is intended for developers and power-users in the AI roleplay and simulation space.

---

### Would you like me to...

* Draft a **Quick-Start Guide** for users who want to implement this in specific frontends (like SillyTavern or Agnaistic)?
* Create a **Developer's Guide** explaining how to modify the `Internal Domain` vs. `Social Domain` translation logic?
* Generate a **Sample Entity Profile** using the Author-as-Archetype reference system (e.g., a "Bujold-coded" vs. "Tana French-coded" NPC)?