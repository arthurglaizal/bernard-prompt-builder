# Bernard - Prompt Builder

![Bernard preview](public/bernard-og-image.png)

**Bernard** is a prompt-building assistant designed to help users clarify, structure, and save reusable prompts for AI tools.

It does not perform the user’s actual task. Instead, Bernard helps formulate better instructions for tools such as ChatGPT, Claude, Gemini, and other language models.

[Open the official Bernard website](https://bernard.arturo-ux.com/)

The website offers additional ways to use Bernard.

---

## What is Bernard?

Bernard is a structured prompt assistant.

Its purpose is to help users move from a vague idea, rough instruction, or unfinished prompt to a clearer and more reusable prompt.

Bernard is built around one core principle:

> **It helps think and write the prompt, not execute the task.**

This makes it useful for people who want to improve how they communicate with AI tools, while keeping control over the actual work they want to perform.

---

## Included prompts

This repository contains two public versions of the Bernard prompt:

| File | Language | Description |
| --- | --- | --- |
| `prompts/bernard-prompt-en.md` | English | English version of the Bernard system prompt |
| `prompts/bernard-prompt-fr.md` | French | French version of the Bernard system prompt |

---

## Main modes

Bernard works through three main modes.

### Explore

**Explore** helps users clarify an early-stage or vague need.

Instead of generating a prompt immediately, Bernard suggests possible angles, useful questions, and next steps.

This mode is useful when the user knows what they want to achieve, but not yet how to formulate the request clearly.

### Forge

**Forge** turns a user request into a structured, reusable prompt.

Depending on the complexity of the request, Bernard can use different prompt structures:

- **Simple**: Role · Mission · Expected result
- **Intermediate**: Context · Role · Action · Format · Audience
- **Advanced**: Context · Objective · Role · Method · Constraints · Format · Success criteria

Forge also includes an analysis of the original request, helping the user identify what was clear, partial, or missing.

### Save

**Save** helps export a prompt as a Markdown file.

The recommended option is to use the Bernard website to edit, preview, and export prompts without relying on AI.

---

## Why this repository exists

This repository provides a clean, public, and versioned reference for the Bernard prompts.

It can be used to:

- Read how Bernard is structured.
- Reuse or adapt the prompt logic.
- Understand the design of a mode-based prompt assistant.
- Share the prompt independently from the full Bernard website.



---

## Suggested repository structure

```txt
bernard-prompt/
├── README.md
├── LICENSE
├── prompts/
│   ├── bernard-prompt-en.md
│   └── bernard-prompt-fr.md
└── public/
    └── bernard-og-image.png