# SCOUT

### A PDF-based workflow framework for turning ChatGPT into a persistent, structured personal AI assistant.

**Current Release: SCOUT 3.18 DEV**

SCOUT is an experimental PDF-based AI workflow framework built to explore how far ChatGPT can be extended using natural-language instructions, persistent preferences, durable state, connected tools, and repeatable workflows.

SCOUT is not a conventional software application.

The current prototype is largely written in ordinary English rather than traditional computer code. The PDF provides ChatGPT with a structured operating framework that changes how a SCOUT session is configured, how it works with the user, and how it maintains continuity between sessions.

The idea started with a simple question:

**How much of a useful personal AI system can be built inside ChatGPT before writing a standalone application?**

SCOUT 3.18 is the result so far.

---

## What SCOUT Does

SCOUT is designed to turn a ChatGPT Project into a more persistent personal AI working environment.

Its primary current implementation is the **SCOUT Daily Brief**.

During installation, SCOUT learns the user's preferences for the Daily Brief and establishes a persistent SCOUT state.

Depending on the ChatGPT tools and connected services available to the user, a Daily Brief can incorporate things such as:

- Current date and relevant calendar information
- Weather
- News and topics selected by the user
- Email review
- Calendar review
- Reminders and upcoming priorities
- Other user-defined information

SCOUT is designed to remember the preferences established during setup so the user does not have to rebuild the Daily Brief configuration every time a fresh working chat is started.

---

## Why the PDF Matters

The PDF is not simply documentation about SCOUT.

**The PDF is part of SCOUT.**

It contains the natural-language operating framework used to establish the SCOUT environment inside ChatGPT.

Upload the current SCOUT DEV PDF into the properly configured ChatGPT Project and SCOUT guides the installation process.

Once SCOUT has been successfully installed, its persistent state allows a fresh SCOUT chat to recover the established user configuration instead of requiring the user to start over.

This makes the PDF-based version both a functioning prototype and an experiment in using natural language itself as part of an AI system's operating architecture.

---

## Requirements

SCOUT 3.18 is currently designed for use with current versions of ChatGPT and relies on ChatGPT capabilities that may vary by account, model, platform, and subscription.

For the full intended experience, SCOUT may use connected services including:

- Google Drive
- Gmail
- Google Calendar
- Google Contacts

The appropriate **SCOUT Instructions Kernel** must also be installed in the ChatGPT Project Instructions.

The Instructions Kernel and the SCOUT DEV PDF perform different jobs.

**Do not skip the Instructions Kernel.**

---

## Installing SCOUT

### 1. Create a ChatGPT Project

Create a new Project specifically for SCOUT.

### 2. Install the Current Instructions Kernel

Copy the current SCOUT Instructions Kernel into the Project Instructions.

Make sure you are using the Instructions Kernel version specified for the current SCOUT release.

### 3. Connect Required Services

Enable the supported Google services you intend SCOUT to use.

SCOUT's available functionality depends on the tools and permissions available in your ChatGPT environment.

### 4. Start a Fresh Chat

Inside the SCOUT Project, start a fresh chat.

### 5. Provide the Current SCOUT DEV PDF

Add the current SCOUT DEV PDF to the fresh chat and follow the installation process.

SCOUT will guide you through first-run configuration.

### 6. Complete the Setup

Answer the setup questions normally.

SCOUT will establish the preferences and persistent state used by future SCOUT sessions.

---

# The Daily Brief

The Daily Brief is currently designed primarily as a **scheduled workflow**.

After SCOUT generates the initial Daily Brief, it will ask what time you want your new Daily Brief prepared each day.

**Give SCOUT the time you actually want the Daily Brief generated.**

For example:

`6:00 AM`

SCOUT will establish the Daily Brief schedule using the scheduling functionality available in ChatGPT.

The intended workflow is simple:

**SCOUT generates the new Daily Brief automatically → you return to the same SCOUT chat → you read it or have Voice read it to you.**

This is important.

If you want a fresh Daily Brief waiting for you every morning, complete the scheduling step during installation.

---

## Using SCOUT With Voice

Voice is useful for listening to and discussing a completed Daily Brief.

Once the day's brief has been generated, open the SCOUT chat and use Voice to have ChatGPT read and discuss it with you.

### Current Voice Quirk

During testing, we have observed occasional issues when Voice is first opened in a SCOUT session.

A simple workaround has been reliable during our testing:

1. Open Voice.
2. Close Voice.
3. Open Voice again.
4. Ask it to read your Daily Brief.

The brief should then be available for normal Voice interaction.

### Important: Generating vs. Reading

SCOUT 3.18 currently relies on the scheduled Daily Brief workflow to reliably produce a new brief.

In testing, asking Voice to **generate** a new Daily Brief on demand may result in Voice simply reading the most recently available brief instead.

For that reason, the recommended SCOUT 3.18 workflow is:

**Schedule the Daily Brief during setup and let SCOUT prepare it automatically.**

Then use Voice to read and discuss the completed brief.

---

# Starting a Fresh SCOUT Chat

One of SCOUT's useful features is that you are not permanently tied to the original installation conversation.

Once SCOUT has been successfully installed and its state established, you can start a fresh chat inside the properly configured SCOUT Project and provide the current SCOUT DEV PDF again.

SCOUT should recover the existing persistent configuration and established preferences rather than requiring the complete initial setup again.

This allows the working conversation to be replaced while preserving the SCOUT environment.

---

# Important Note About Daily Brief Schedules

The Daily Brief schedule is associated with the SCOUT chat that established it.

If that chat remains active, its scheduled Daily Brief can continue operating.

If you replace or delete the chat and establish another scheduled Daily Brief in a new SCOUT chat, you may see older schedule entries remain in ChatGPT's schedules/tasks interface.

Schedules associated with deleted chats may appear as **paused**.

Therefore:

**Use one active SCOUT Daily Brief chat at a time.**

When replacing an old SCOUT working chat, be aware that its old paused schedule may remain visible and may need to be cleaned up manually.

Avoid repeatedly creating unnecessary Daily Brief schedules across multiple SCOUT chats.

---

# Installation Troubleshooting

SCOUT includes recovery behavior intended to help when installation encounters a problem.

If SCOUT detects an installation issue and provides a recovery prompt:

**Follow the recovery instructions first.**

It may provide text that needs to be copied and pasted into the normal ChatGPT text input.

If installation still does not complete correctly:

### First Recovery Step

Check Google Drive for the SCOUT state created during the unsuccessful installation.

If an incomplete SCOUT state was created in the root location during the failed installation, remove it and retry the installation from a fresh chat.

### If Problems Continue

Start again with a clean ChatGPT Project:

1. Create a new SCOUT Project.
2. Install the current compatible SCOUT Instructions Kernel in Project Instructions.
3. Confirm the required connected services.
4. Start a **fresh chat**.
5. Provide the latest SCOUT DEV PDF.
6. Run the installation again.

SCOUT was deliberately designed to diagnose and recover from a number of installation problems itself, so follow any recovery instructions it provides before rebuilding the environment manually.

---

# Current Development Version

## SCOUT 3.18 DEV

SCOUT 3.18 is the current tested development baseline.

It combines the established SCOUT Runtime framework with first-run installation guidance intended to make SCOUT usable by people who were not involved in developing it.

This remains experimental software.

ChatGPT itself changes over time, and behavior involving Voice, Projects, connected services, scheduling, permissions, models, and other platform capabilities can change independently of SCOUT.

If something behaves differently from the instructions above, please report it.

---

# Prototype → Standalone

SCOUT 3.18 represents an important stage of the project:

**It is a working prototype built primarily through natural-language AI instructions rather than a conventional software application.**

That was intentional.

The PDF-based system has allowed us to experiment rapidly with:

- Persistent AI workflows
- User preference management
- Durable state
- Connected services
- Daily information gathering
- AI operating instructions
- Session recovery
- Installation and diagnostics
- Human/AI interaction patterns

The next stage is taking what has been learned from the working SCOUT prototype and applying those lessons to standalone software development.

The PDF version therefore serves two purposes:

**It is something people can actually use and test today.**

And:

**It is the working prototype from which the standalone SCOUT architecture is being developed.**

---

# Testing SCOUT

SCOUT is being released so other people can experiment with it.

We are particularly interested in learning how SCOUT behaves across different ChatGPT configurations.

If you test it, useful reports include:

- Successful installations
- Installation failures
- Unexpected behavior
- Daily Brief problems
- Voice behavior
- Scheduling behavior
- Google service integration problems
- Differences between ChatGPT models or platforms
- Recovery behavior
- Ideas that emerge from actually using SCOUT

When reporting an issue, describe what happened, what you expected to happen, and what step you were performing when the problem occurred.

GitHub Issues will be used to organize testing feedback.

---

# Development Method

SCOUT development follows a simple rule:

**Preserve what works. Fix what doesn't.**

The current development cycle is:

`ANALYZE → DESIGN → TEST → PATCH → BUILD → VERSION → RECORD`

Experiments that do not improve the system are not automatically carried forward.

The goal is progressive improvement based on observed behavior rather than rebuilding working systems simply because another approach is possible.

---

# Project Status

**Experimental / Active Development**

SCOUT is not an official OpenAI or ChatGPT product.

It is an independent project designed to experiment with and build upon capabilities available through ChatGPT.

Compatibility may change as ChatGPT itself evolves.

---

# License

No open-source license has currently been granted.

The project is being made available for testing and evaluation while licensing and the future standalone architecture are being developed.

---

# Feedback

Try it.

Break it.

Tell us what happened.

The most useful contribution at this stage is real-world testing.

If SCOUT behaves differently on your system than it does on ours, **we want to know about it.**

---

**SCOUT**

*From a PDF-based AI prototype to a standalone personal AI system.*