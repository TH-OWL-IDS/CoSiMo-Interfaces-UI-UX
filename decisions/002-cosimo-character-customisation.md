# 002 — CoSiMo Character Customisation

**Date:** 2026-05-28
**Status:** Accepted

## Context

The default CoSiMo character is a minimal floating face (see [001](001-cosimo-character-visual-identity.md)). While this is intentionally simple and emotionally readable, not all users can or want to interpret facial expressions — including people on the autism spectrum, users with face-processing difficulties, or those who simply prefer a non-anthropomorphic representation.

## Decision

CoSiMo's character is selectable from a defined set of alternatives. Users can choose which character represents CoSiMo for them. The default remains the minimal face. All alternatives in the set must be capable of expressing the same emotional states as the face character — the communication vocabulary stays consistent, only the visual form changes.

The character set itself has not yet been designed. Defining and designing the full set is a separate task.

## Consequences

- No user is forced to interact with a face-based representation.
- The emotional state system (neutral, smiling, content, surprised, etc.) must be implementable across all character types in the set — this constrains what alternative characters can look like.
- The character set must be designed as a cohesive family, not as unrelated options.
- Character selection should be offered early — during onboarding or first contact with CoSiMo.
