# Overview

Have you ever been bothered that your scientists don't upgrade their Custom AI Assistants (which were enabled by Self-Evolving Logic) to Sapient AI Assistants when you discover Positronic AI (the prerequisite technology for that trait)?  Well be frustrated no more!  This mod upgrades all your scientists when you discover Positronic AI, ensures that newly-generated leaders are equipped with the best tech before you hire them, and ensures they receive better training when creating a new assistant upon level-up.  If all else fails and a scientist was too busy to upgrade their assistant, reassign them and the research logistics department will be sure to perform the upgrade during relocation.

# Changes

Added an effect that will upgrade a leader's Custom AI Assistant trait, and then hooked in logic to call it when leaders spawn, level up, when Positronic AI is researched, and when a leader is assigned.  The prerequisite technology for Sapient AI Assistants is Positronic AI, so the events will not trigger unless the leader's owner has the technology researched.

## Compatibility

Anything that doesn't altogether remove the Custom AI Assistant and Sapient AI Assistant traits.  This mod is implemented without changing any core Stellaris files.

Not compatible with achievements because it adds an effect and events.

### Post-Game Start

This mod can be safely added or removed from your save game after the game has started.  It is implemented entirely through custom events (and custom triggers). If you remove it, your game will work normally.

## Changelog

* 1.0.0 Initial version
* 1.0.1 Add more info to README (no script changes)

## Source Code

[Hosted on GitHub](https://github.com/corsairmarks/scientist_ai_assistant_upgrader)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.