# SCOUT

### A PDF-based workflow framework for turning ChatGPT into a persistent, structured personal AI assistant.

**Current Release: SCOUT 3.18 DEV**

SCOUT is an experimental AI workflow framework built to explore how far ChatGPT can be extended using natural-language instructions, persistent preferences, durable state, connected tools, scheduled workflows, and repeatable operating behavior.

SCOUT is not a conventional software application.

The current prototype is largely written in ordinary English rather than traditional computer code. It uses two files working together inside a ChatGPT Project to establish the SCOUT environment.

**If you just want to try SCOUT, start here.**

---

# Quick Start — What Do I Do With These Two Files?

**SCOUT 3.18 DEV uses two files, and both are required.**

They perform different jobs in different parts of ChatGPT:

- `SCOUT instructions 2.10.txt` — goes into the **ChatGPT Project Instructions**.
- `SCOUT_3.18_DEV.pdf` — is attached and sent as a message in a **new chat inside that Project**.

For SCOUT 3.18 DEV, these two files are the currently matched configuration.

## 1. Create a ChatGPT Project

Create a new ChatGPT Project and name it something recognizable, such as:

`SCOUT`

## 2. Install the Instructions Kernel

Open:

`SCOUT instructions 2.10.txt`

Copy the complete contents of the file.

Open the settings/edit controls for your new SCOUT Project and paste the text into the **Project Instructions**.

Save the Project Instructions.

**Do not skip this step.**

The Instructions Kernel and the SCOUT PDF perform different jobs. SCOUT 3.18 requires both.

## 3. Connect the Services You Want SCOUT to Use

SCOUT can work with supported connected services such as:

- Google Drive
- Gmail
- Google Calendar
- Google Contacts

Available functionality depends on the ChatGPT tools, permissions, account, model, platform, and connected services available to you.

Google Drive is particularly important to SCOUT's persistent state and preference system.

## 4. Start a Fresh Chat

Inside the configured SCOUT Project, start a **new chat**.

## 5. Send the SCOUT PDF

Attach:

`SCOUT_3.18_DEV.pdf`

to the normal ChatGPT message box and send it.

The PDF is not simply documentation.

**The PDF is part of SCOUT.**

SCOUT should recognize the installation environment and begin its startup process.

On a first installation, SCOUT will ask whether you want to install.

**Reply yes and continue.**

## 6. Complete First-Run Setup

Follow SCOUT's setup prompts.

SCOUT will ask for information needed to configure your environment, including things such as:

- Your location
- What time you want your Daily Brief prepared each day
- What you want included in your Daily Brief
- Your personal SCOUT preferences

### Important — Use the Normal Text Message Box for Setup

During initial configuration, enter your answers through the **normal ChatGPT text message box**.

You can:

- Type them
- Use your device's voice-to-text/dictation
- Copy and paste text into the message box

For SCOUT 3.18, do **not** rely on ChatGPT Voice mode to establish or change SCOUT's persistent configuration.

Text and voice-to-text/dictation are different from ChatGPT Voice mode.

Once setup is complete and your Daily Brief has been generated, Voice can be useful for reading and discussing it.

---

# What SCOUT Is Designed to Do

SCOUT is designed to turn a ChatGPT Project into a more persistent personal AI working environment.

Its primary current implementation is the **SCOUT Daily Brief**, but the underlying system also explores:

- Persistent user preferences
- Durable state
- Connected services
- Scheduled workflows
- Session recovery
- Repeatable AI behavior
- Personalized information gathering
- Voice interaction with completed work

The idea started with a simple question:

**How much of a useful personal AI system can be built inside ChatGPT before writing a standalone application?**

SCOUT 3.18 is the result so far.

---

# The SCOUT Daily Brief

The Daily Brief is the primary working feature of SCOUT 3.18.

Depending on your preferences and the ChatGPT tools and connected services available to you, a Daily Brief can incorporate things such as:

- Current date and relevant calendar information
- Weather
- News
- Topics selected by you
- Email review
- Calendar review
- Reminders
- Upcoming priorities
- Other user-defined information

During installation, SCOUT asks what time you want your Daily Brief prepared each day.

**Give SCOUT the time you actually want the brief generated.**

For example:

`6:00 AM`

SCOUT will establish the Daily Brief schedule using the scheduling functionality available in ChatGPT.

The intended workflow is:

**SCOUT prepares your Daily Brief automatically → the brief appears in your active SCOUT Daily Brief chat → you return to that chat → you read it or use Voice to have it read and discussed with you.**

Once the first Daily Brief workflow has been established, that SCOUT chat becomes your active Daily Brief chat.

If you want a fresh Daily Brief waiting for you every morning, complete the scheduling step during installation.

---

# SCOUT Preferences

Persistent preferences are an important part of SCOUT.

SCOUT maintains its own persistent configuration so that preferences associated with your SCOUT environment can survive beyond an individual working conversation.

These preferences are maintained through SCOUT's durable state rather than relying only on the temporary context of a ChatGPT conversation.

This means you can tell SCOUT how you want your Daily Brief structured and how you want certain SCOUT functions to behave.

## Saving a Preference

Do not assume that every passing comment will automatically become a permanent SCOUT preference.

If you want SCOUT to persist something, tell it explicitly.

For example:

`Save this as a SCOUT preference.`

or:

`I want this in my SCOUT preferences.`

Then tell SCOUT what you want remembered.

For SCOUT 3.18, persistent preferences should be entered through the **normal text message box**.

You can type them, dictate them using voice-to-text, or copy and paste them.

Do not rely on ChatGPT Voice mode to establish or modify persistent SCOUT preferences.

SCOUT can then use those saved preferences when performing supported functions in the SCOUT Project.

This allows the SCOUT configuration to remain separate from simply depending on whatever happens to be present in the current ChatGPT conversation.

---

# SCOUT State and Google Drive

SCOUT uses durable state to maintain its established configuration and preferences.

During installation, **SCOUT establishes the required SCOUT state itself.**

A normal user should not need to manually build SCOUT's Google Drive structure before installation.

Let SCOUT perform the installation.

Once the state has been established, SCOUT can use it to recover the existing configuration when working from a fresh SCOUT chat.

Unless SCOUT's recovery instructions specifically tell you otherwise:

**Do not manually alter or delete SCOUT state files as a troubleshooting shortcut.**

---

# If Installation Gets Blocked

ChatGPT or a connected service may occasionally prevent an automated step from completing directly.

SCOUT 3.18 includes recovery behavior for this situation.

If SCOUT cannot complete an installation or Google Drive operation directly, it may provide you with a **recovery prompt**.

When that happens:

1. Read the instructions SCOUT provides.
2. Copy the supplied recovery prompt.
3. Paste it into the normal ChatGPT message box.
4. Send it.

You can also type the requested instruction yourself or use voice-to-text/dictation.

The important distinction is that the instruction must be sent through the **normal text message interface** when SCOUT tells you that this recovery step is required.

Then allow SCOUT to continue.

**Follow SCOUT's recovery instructions before attempting to rebuild the installation manually.**

---

# Using SCOUT With Voice

Voice is useful for listening to and discussing a completed Daily Brief.

Once the day's brief has been generated, open the SCOUT Daily Brief chat and use Voice to have ChatGPT read and discuss it with you.

SCOUT 3.18 currently makes an important distinction:

**Use the normal text interface for installation, persistent configuration, preference changes, and recovery prompts.**

**Use Voice primarily to read and discuss a Daily Brief that has already been generated.**

## Current Voice / Microphone Quirk

During testing, we have observed a significant Voice behavior that users should know about.

Opening the microphone/Voice interface can sometimes result in ChatGPT opening or behaving as though it has entered a new chat/session rather than immediately accessing the expected SCOUT conversation state.

A workaround has been reliable during our testing:

1. Open Voice.
2. Close Voice.
3. Return to the intended SCOUT Daily Brief chat if necessary.
4. Open Voice again.
5. Ask it to read your Daily Brief.

If Voice appears not to know about the Daily Brief you were just viewing, **do not immediately assume your SCOUT configuration or Daily Brief has been lost.**

Close Voice, make sure you are in the correct SCOUT Daily Brief chat, reopen Voice, and try again.

## Generating vs. Reading

SCOUT 3.18 currently relies primarily on the **scheduled Daily Brief workflow** to reliably produce a new brief.

During testing, asking Voice to **generate** a new Daily Brief on demand may result in Voice reading the most recently available brief instead of reliably initiating the complete generation workflow.

For that reason, the recommended SCOUT 3.18 workflow is:

**Schedule the Daily Brief during setup → let SCOUT prepare it automatically → use Voice to read and discuss the completed brief.**

---

# Starting a Fresh SCOUT Chat

You are not permanently tied to the original SCOUT installation conversation.

Once SCOUT has been successfully installed and its durable state has been established, you can start a fresh chat inside the properly configured SCOUT Project.

Provide the current compatible SCOUT DEV PDF to the new chat.

SCOUT should recover the existing persistent configuration and established preferences rather than requiring the complete first-time installation again.

This allows a working conversation to be replaced while preserving the broader SCOUT environment.

---

# Important Note About Daily Brief Schedules

The Daily Brief schedule is associated with the SCOUT chat that established it.

If that chat remains active, its scheduled Daily Brief can continue operating.

If you replace or delete that chat and establish another scheduled Daily Brief in a new SCOUT chat, older schedule entries may remain visible in ChatGPT's schedules/tasks interface.

Schedules associated with deleted chats may appear as **paused**.

Therefore:

**Use one active SCOUT Daily Brief chat at a time.**

When replacing an old SCOUT working chat, be aware that its old paused schedule may remain visible and may need to be cleaned up manually.

Avoid repeatedly creating unnecessary Daily Brief schedules across multiple SCOUT chats.

---

# Installation Troubleshooting

If SCOUT does not behave as expected, **do not immediately delete your SCOUT state or rebuild the installation.**

Start with the simplest checks first.

## Before Changing Anything

### 1. Check Your ChatGPT Version

If you are using the ChatGPT mobile or desktop application, make sure you are running the **latest version of ChatGPT available for your device**.

SCOUT relies on current ChatGPT capabilities. An older version of the ChatGPT application may behave differently from the version on which SCOUT was tested.

If you are using ChatGPT through the web, make sure the page is current and try refreshing it if necessary.

### 2. Check Your Connected Services

Confirm that the connected services SCOUT requires are still connected and available.

Depending on the function you are using, these may include:

- Google Drive
- Gmail
- Google Calendar
- Google Contacts

### 3. Try the Operation Through the Normal Text Interface

If the problem occurred while using Voice, return to the normal SCOUT chat and try the operation through the regular text message box.

You can type the instruction, use voice-to-text/dictation, or copy and paste it.

### 4. Follow SCOUT's Recovery Instructions

SCOUT is designed to diagnose and recover from a number of installation and operating problems.

If SCOUT gives you a recovery instruction or recovery prompt, **follow it before attempting more invasive troubleshooting.**

### 5. Protect Your Existing SCOUT State

**Do not delete or rebuild established SCOUT state as your first troubleshooting step.**

Preserve what is already working.

Only remove or replace SCOUT state when SCOUT's recovery process specifically calls for it or when you have determined that a clean installation is necessary.

---

# If Installation Still Does Not Complete

If SCOUT's normal recovery process does not solve the problem, check whether an incomplete SCOUT state was created during an unsuccessful installation.

If SCOUT specifically identifies an incomplete state and instructs you to remove it, follow those recovery instructions and retry from a fresh chat.

Do not delete established SCOUT state simply because something unexpected happened.

---

# Clean Reinstallation

If the normal troubleshooting and recovery process fails, a clean installation may be appropriate.

1. Make sure you have the latest available ChatGPT version if using the app.
2. Create a new SCOUT Project.
3. Install the compatible SCOUT Instructions Kernel in Project Instructions.
4. Confirm the required connected services.
5. Start a fresh chat.
6. Provide the compatible SCOUT DEV PDF.
7. Run the installation again.
8. Follow any recovery instructions SCOUT provides.

If the problem persists, report it through GitHub Issues.

---

# What Is Working Well in SCOUT 3.18

SCOUT 3.18 is the current tested development baseline.

Areas that have performed well during development and testing include:

- Guided first-run installation
- Establishing persistent SCOUT state
- Persistent user preferences
- Scheduled Daily Brief generation
- Recovering established configuration in fresh SCOUT chats
- Using connected services when available
- Recovery guidance when an installation operation is blocked
- Reading and discussing completed Daily Briefs with Voice
- Maintaining a repeatable working environment through natural-language instructions

SCOUT 3.18 combines the established SCOUT Runtime framework with first-run installation guidance intended to make the system usable by people who were not involved in developing it.

---

# Known Limitations in SCOUT 3.18

SCOUT remains experimental.

Known areas requiring particular attention include:

- Voice does not reliably perform the same setup/configuration operations as the normal text interface.
- Opening Voice may initially behave as though a new chat/session has been opened.
- Voice may read an existing Daily Brief when asked to generate a new one rather than reliably initiating the complete generation workflow.
- Persistent SCOUT preferences should currently be explicitly entered through the normal text interface.
- Connected-service permissions can occasionally interrupt automated installation or Drive operations and require a recovery prompt.
- Daily Brief schedules are associated with the chat in which they were established.
- Old or deleted Daily Brief chats may leave paused schedule entries behind.
- ChatGPT capabilities can differ by account, model, subscription, platform, permissions, and connected services.
- ChatGPT itself changes independently of SCOUT, so platform updates can affect previously tested behavior.

These limitations are part of why SCOUT 3.18 is being released as a **DEV** version for wider testing.

---

# Why the PDF Matters

The SCOUT PDF is not simply a user manual.

**The PDF is part of the operating system of the prototype.**

It contains the natural-language operating framework used to establish SCOUT behavior inside ChatGPT.

The Instructions Kernel and PDF work together:

**Project Instructions Kernel → establishes the SCOUT host environment**

**SCOUT DEV PDF → provides the current SCOUT operating framework and installation/runtime behavior**

This makes the PDF-based version both a functioning prototype and an experiment in using natural language itself as part of an AI system's operating architecture.

---

# Requirements

SCOUT 3.18 is designed for use with current versions of ChatGPT and relies on ChatGPT capabilities that may vary by account, model, platform, permissions, and subscription.

For the full intended experience, SCOUT may use connected services including:

- Google Drive
- Gmail
- Google Calendar
- Google Contacts

The compatible **SCOUT Instructions Kernel must also be installed in the ChatGPT Project Instructions.**

For SCOUT 3.18 DEV:

- Instructions Kernel: `SCOUT instructions 2.10.txt`
- SCOUT package: `SCOUT_3.18_DEV.pdf`

**Do not skip the Instructions Kernel.**

---

# Prototype → Standalone

SCOUT 3.18 represents an important stage of the project.

**It is a working prototype built primarily through natural-language AI instructions rather than as a conventional software application.**

That was intentional.

The PDF-based system has allowed rapid experimentation with:

- Persistent AI workflows
- User preference management
- Durable state
- Connected services
- Daily information gathering
- Scheduled AI workflows
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

If you test SCOUT, we want to hear about both **what works and what fails**.

Useful reports include:

- Successful installations
- Installation failures
- Daily Brief reliability
- Persistent preference behavior
- Fresh-chat recovery
- Voice behavior
- The Voice/new-chat issue
- Scheduling behavior
- Google Drive behavior
- Gmail integration
- Calendar integration
- Google Contacts integration
- Permission or authorization failures
- Recovery-prompt behavior
- Differences between ChatGPT models
- Differences between mobile, desktop, and web
- Differences between account/subscription configurations
- Unexpected behavior
- Features you find genuinely useful
- Features you expected but could not use
- Ideas that emerge from actually using SCOUT

When reporting a problem, please include:

- What you were trying to do
- What happened
- What you expected to happen
- What step you were performing
- Your platform, if relevant
- Your ChatGPT app version, if relevant
- Any error or recovery message SCOUT provided

**GitHub Issues will be used to organize testing feedback.**

Real-world failures are useful development information. Please report them rather than assuming you used SCOUT incorrectly.

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

**Current Release: SC