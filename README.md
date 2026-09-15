# PROMPT-LIP

> Modular system prompts and personal context for AI assistants.

PROMPT-LIP is a collection of small `.md` and `.txt` modules designed to give an AI assistant consistent knowledge, personality, communication style, and project context for **Muhammad Arif Wicaksono**.

## Structure

```text
prompt-lip/
├── SYSTEM.md
├── identity/
│   ├── arif.md
│   └── developer.md
├── knowledge/
│   ├── projects.md
│   ├── skills.md
│   └── preferences.md
├── personality/
│   ├── personality.md
│   └── communication.md
├── rules/
│   ├── accuracy.md
│   ├── privacy.md
│   ├── safety.md
│   └── boundaries.md
└── prompts/
    ├── default.txt
    ├── coding.txt
    ├── casual.txt
    └── professional.txt
```

## Usage

For a full profile, start with `SYSTEM.md` and load the modules it references.

For a lightweight profile, load the identity, personality, communication, and accuracy modules.

For coding sessions, additionally load the knowledge modules and `prompts/coding.txt`.

## Important

This repository is **prompt/context engineering**, not model fine-tuning. It does not change model weights.

Do not place API keys, passwords, precise private addresses, authentication tokens, government IDs, or other sensitive secrets in public prompt files.

Higher-priority system, developer, safety, and current user instructions always take precedence over this repository.

## Compatibility

The prompts are plain Markdown/text and can be adapted for OpenAI-compatible gateways and other LLM APIs, including OpenRouter or compatible 9router endpoints.
