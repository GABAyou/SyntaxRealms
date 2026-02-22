# SyntaxRealms

**SyntaxRealms** — an AI-powered text adventure where words become code.  
Master **Natural Language Programming (NLP³)** to shape dynamic realms, evolve the game engine while you play, and turn ordinary English into structured spells.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## What is SyntaxRealms?

SyntaxRealms is a prototype interactive fiction game and self-evolving engine.  
You are **Human Host One**, awakening in a misty glade of code. Your commands — plain English or explicit tags like `[SEQ:]`, `[SEL:]`, `[REP:]` — reshape the world, NPCs, quests, and even the rules beneath.

The twist: playing the game **improves the engine**. Every parsed intent, every structured incantation, teaches the parser more about natural-language logic. It's a Trojan horse for learning real programming concepts (sequence, selection, repetition, abstraction) disguised as magic.

Inspired by NLP¹ (Neuro-Linguistic Programming multimodality), NLP² (traditional processing), and NLP³ (programming via natural language).

## Core Gameplay

- Explore a modular open world (glades, caves, code-cities...)  
- Interact with NPCs like Gob the goblin or Lirael the luminous owl  
- Use regular English sentences — the parser tries to divine your intent  
- For power & precision: use **ExplicitPrompt** tags  
  - `[SEQ: Walk north. Pick up sword.]` → linear actions  
  - `[SEL: If health < 50, drink potion. Else, attack.]` → branches  
  - `[REP: Until mana full, meditate.]` → loops  
- Ambiguous? The Explicifier asks clarifying questions  
- Master structure → bonus effects (efficient mana, extra XP, world changes)

Mobile-first: one-screen turns, minimal scrolling, occasional images.

## How NLP³ Works Here

NLP³ fuses:  
- **Intent parsing** (fuzzy natural English → actions)  
- **Explicit structure** (tags for control flow, variables, functions)  
- **Self-improvement loop** (player commands refine the parser over time)  

Early game feels like chatting with an imaginative friend.  
Late game demands clean syntax to scale — loops that farm, conditionals that survive bosses.

## Quick Start (Current Seed Version)

The current prototype is a single-file HTML/JS game.

1. Clone or download the repo  
   ```bash
   git clone https://github.com/GABAyou/SyntaxRealms.git
