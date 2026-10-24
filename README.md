# Usami

### A companion that becomes more *herself* through knowing you.

Usami is a proprietary AI companion and VTuber project built around a simple
idea: a character should not feel like a chat window wearing an avatar.

She should have a recognizable identity, remember what matters, adapt to the
person beside her, and express herself through more than text.

> This repository is the public showcase for Usami. The product itself is
> developed in private repositories owned by the Usami Vtuber organization.

## What makes Usami different?

Many companion products are primarily one of three things: a chat interface
around a language model, a scripted character with a fixed personality, or an
avatar that reacts to generated text. Usami is being designed as a complete
personalization system in which those parts work together.

### Personalization is the product, not a feature toggle

Usami is not meant to give every user the same character with a different name.
Her experience is shaped by the relationship built over time: preferences,
conversation context, recurring subjects, boundaries, and the way each user
likes to interact.

### Memory with retrieval, not just a longer chat history

Her memory layer is being built around structured context and RAG. That means
the system can retrieve relevant information when it is useful instead of
blindly sending an ever-growing transcript to a model.

The goal is a memory that is useful, explainable, and controllable — not a
hidden collection of everything a user has ever said.

### A consistent identity across the whole experience

Usami's personality is not supposed to live only inside a system prompt. It is
treated as a product-level concern: behavior, preferences, emotional state,
conversation style, memory, and expression should reinforce one another.

### Embodiment that serves the relationship

The avatar is not decoration placed on top of an AI response. Voice, timing,
expressions, gestures, and visual presence are part of how Usami communicates.
The character should feel present without pretending that animation alone is
intelligence.

### User control matters

A companion that remembers and adapts needs clear boundaries. Usami is being
designed with explicit control over personalization, privacy, memory, and the
ability to understand what the system is doing.

## The architecture

Usami is organized as a set of private services with clear responsibilities:

- **Frontend** — the product experience and character interface.
- **Backend** — accounts, sessions, product APIs, permissions, and operations.
- **AI** — personality, personalization, memory, RAG, model orchestration, and
  provider routing.
- **Contracts** — versioned schemas and communication contracts between
  services.

The public `Usami` repository exists to communicate the project and its
direction. It is not the source code of the commercial product.

## Project status

Usami is under active development. The architecture and character experience
are being built in small, verifiable stages. Some ideas described here are
direction and design intent rather than finished public capabilities.

## Repositories

- [Usami Frontend](https://github.com/UsamiVtuber/Usami-frontend)
- [Usami AI](https://github.com/UsamiVtuber/Usami-AI)
- [Usami Backend](https://github.com/UsamiVtuber/Usami-Backend)
- [Usami Contracts](https://github.com/UsamiVtuber/Usami-Contracts)

## Commercial project

Usami is intended to become a commercial product. The public showcase, brand,
character, source code, models, artwork, and private services may have
different ownership and licensing terms.

The `CC0-1.0` license in this repository applies only to the material actually
published here. It does not grant rights to the private Usami product,
trademarks, character assets, artwork, models, or repositories.

## Follow the project

The public repository will be used for project-level updates, milestones, and
selected showcases as Usami evolves.
