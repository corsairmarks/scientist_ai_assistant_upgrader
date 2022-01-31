# Overview

Have you ever been bothered that your scientists don't upgrade their Custom AI Assistants (which were enabled by Self-Evolving Logic) to Sapient AI Assistants when you discover Positronic AI (the prerequisite technology for that trait)?  Well be frustrated no more!  This mod upgrades all your scientists when you discover Positronic AI, ensures that newly-generated leaders are equipped with the best tech before you hire them, and ensures they receive better training when creating a new assistant upon level-up.  If all else fails and a scientist was too busy to upgrade their assistant, reassign them and the research logistics department will be sure to perform the upgrade during relocation.

If you outlaw AI, the loophole has been closed that previously allowed scientists to still acquire the foul positronic imitations of life.  However, in the spirit of reconciliation, scientists may still us algorithmically-driven artificial "intelligence" to serve the state (i.e. Sapient AI Assistants are downgraded to Custom AI Assistants instead of being wholly removed).  And if you later decide that maybe AI is for you after all, scientists with Custom AI Assistants will be upgraded when you change the policy.

# Changes

Added an effect that will upgrade a leader's Custom AI Assistant trait, and then hooked in logic to call it when leaders spawn, level up, when Positronic AI is researched, and when a leader is assigned.  The prerequisite technology for Sapient AI Assistants is Positronic AI, so the events will not trigger unless the leader's owner has the technology researched.

## Compatibility

Anything that doesn't altogether remove the Custom AI Assistant and Sapient AI Assistant traits.  This mod is implemented without changing any core Stellaris files.

Built for Stellaris version 3.3 "Libra." Not compatible with achievements because it adds an effect and events.

### When to Install

This mod can be safely added or removed from your savegame after the game has started.  It is implemented entirely through custom events and effects. If you remove it, your game will work normally.  Any upgraded scientists will keep their swapped trait.

## Changelog

* 1.0.0 Initial version
* 1.0.1 Add more info to README (no script changes)
* 1.0.2 Maintenance release: adjust code structure (no script changes)
* 1.0.3 Maintenance release (no script changes)
    * Rename to "Leader Traits: Scientist AI Assistant Upgrader" and update thumbnail
    * Add more preview images
    * Update README/description
* 1.0.4 Alter text alignment in thumbnail
* 1.1.0 Enhanced remove/add AI assistants when outlawing/legalizing AI
    * Check for AI being legal before upgrading any scientist traits
    * Mark as compatible for Stellaris 3.1 "Lem"
    * Still usable with previous version 3.0 "Dick" (and likely 2.8 "Butler")
* 1.2.0 Mark as compatible with Stellaris 3.2 "Herbert" - no script changes
    * Still usable with previous versions: 3.1 "Lem" and 3.0 "Dick" (and likely 2.8 "Butler")
* 1.3.0 Mark as compatible with Stellaris 3.3 "Libra" - no script changes
    * Still usable with previous versions: 3.2 "Herbert," 3.1 "Lem," and 3.0 "Dick" (and likely 2.8 "Butler")

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/scientist_ai_assistant_upgrader)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.