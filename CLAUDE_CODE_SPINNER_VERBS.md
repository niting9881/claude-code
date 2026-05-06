# Claude Code Spinner Verbs Guide

A comprehensive reference guide to the 185+ spinner verbs that appear while Claude Code processes your commands.

## Table of Contents

- [Overview](#overview)
- [What Are Spinner Verbs?](#what-are-spinner-verbs)
- [Verb Categories](#verb-categories)
  - [Cognitive Processing](#cognitive-processing)
  - [Culinary & Cooking](#culinary--cooking)
  - [Physical Processes](#physical-processes)
  - [Dance & Movement](#dance--movement)
  - [Whimsical & Brand-Specific](#whimsical--brand-specific)
- [Key Facts](#key-facts)
- [Customization](#customization)
- [Resources](#resources)

---

## Overview

Claude Code displays rotating spinner text while processing your commands. This isn't just functional feedback—it's a delightful personality feature that makes the wait more engaging. The verbs are carefully curated to reflect the "thinking" happening behind the scenes, using creative metaphors from cooking, dance, physics, and brand-specific references.

**Total Verbs:** 185+ (Modern Era v1.0.49+), now expanded to 191+ entries

---

## What Are Spinner Verbs?

When you run Claude Code, you'll see messages like:

```
Thinking...
Brewing...
Moonwalking...
Cerebrating...
```

Each message appears briefly (fractions of a second) before being replaced by another, creating an animated effect. This provides visual feedback that your code is being processed while adding personality to the CLI experience.

### Purpose

- **Visual Feedback:** Users know Claude is actively working
- **Personality:** Makes the tool feel less robotic and more engaging
- **Creative Expression:** Anthropic has fun with language and metaphor
- **Community:** Users enjoy spotting different verbs and discussing favorites

---

## Verb Categories

Spinner verbs fall into distinct semantic categories, each using metaphor to represent computational work:

### Cognitive Processing

These verbs represent actual mental/intellectual work:

| Verb | Meaning |
|------|---------|
| **Thinking** | General deep contemplation and analysis |
| **Cerebrating** | Intensive brain activity and focus |
| **Cogitating** | Thoughtful, reflective thinking process |
| **Ruminating** | Pondering deeply over extended time |
| **Analyzing** | Breaking down problems systematically |
| **Computing** | Mathematical processing and calculation |
| **Evaluating** | Assessing options and possibilities |
| **Deliberating** | Weighing options carefully |
| **Reasoning** | Logical deduction and inference |
| **Synthesizing** | Combining elements into coherence |

**Use Case:** Represents genuine computational thinking and problem-solving.

---

### Culinary & Cooking

These verbs use food and cooking metaphors to describe gradual transformation:

| Verb | Meaning |
|------|---------|
| **Baking** | Slow, steady processing and refinement |
| **Brewing** | Building something complex and rich |
| **Marinating** | Letting ideas soak and develop fully |
| **Simmering** | Gentle, sustained and careful work |
| **Julienning** | Fine, precise cuts and details |
| **Caramelizing** | Turning raw elements into refined output |
| **Whisking** | Rapid blending and mixing together |
| **Proofing** | Testing and verifying correctness |
| **Seasoning** | Adding flavor and refinement |
| **Kneading** | Working through resistance gradually |
| **Fermenting** | Slow transformation over time |
| **Flambeing** | Dramatic, showy execution |
| **Tempering** | Bringing to right conditions carefully |

**Use Case:** Emphasizes gradual refinement and careful work on complex tasks.

---

### Physical Processes

These verbs describe mechanical transformations and energy transfer:

| Verb | Meaning |
|------|---------|
| **Churning** | Continuous rotation and mixing |
| **Percolating** | Slow but steady continuous progress |
| **Coalescing** | Bringing separate parts together |
| **Oscillating** | Back-and-forth balanced processing |
| **Forging** | Shaping through intense hard work |
| **Combusting** | Explosive, rapid execution |
| **Reverberating** | Echoing and propagating effects |
| **Magnetizing** | Attracting and organizing elements |
| **Resonating** | Creating harmonious alignment |
| **Vibrating** | Continuous energetic movement |

**Use Case:** Suggests dynamic, energetic computational work.

---

### Dance & Movement

These verbs add personality through movement metaphors:

| Verb | Meaning |
|------|---------|
| **Moonwalking** | Going backward with style and grace |
| **Beboppin'** | Rhythmic and jazzy processing |
| **Waltzing** | Smooth, flowing and elegant progression |
| **Canoodling** | Intimate and cozy code handling |
| **Lollygagging** | Leisurely and unhurried processing |
| **Sock-hopping** | Playful, bouncy execution |
| **Twirling** | Rotating and spiraling patterns |
| **Moseying** | Leisurely wandering through logic |
| **Jitterbugging** | Fast, energetic movement |

**Use Case:** Pure fun and personality—shows Claude doesn't take itself too seriously.

---

### Whimsical & Brand-Specific

These verbs embrace absurdity and brand identity:

| Verb | Meaning |
|------|---------|
| **Clauding** | Busy with Claude (brand Easter egg) |
| **Conjuring** | Creating something magical and new |
| **Manifesting** | Bringing possibilities into being |
| **Actualizing** | Making abstract concepts real |
| **Apotheosizing** | Elevating to ultimate form |
| **Transpiling** | Converting between code forms |
| **Decoupling** | Separating intertwined systems |
| **Evangelizing** | Spreading your code gospel |
| **Optimizing** | Making supremely efficient |
| **Wibbling** | Playful wobbling (not a real word!) |
| **Whatchamacalliting** | Doing the ineffable and mysterious |
| **Unraveling** | Untangling complex logic |

**Use Case:** Adds humor, brand connection, and technical in-jokes.

---

## Key Facts

### Distribution

- **Total Verbs:** 185+ (expanded from original 106)
- **Cognitive Verbs:** ~18 verbs focused on thinking
- **Culinary Verbs:** ~20 verbs using food metaphors
- **Physical Verbs:** ~15 verbs describing processes
- **Dance/Movement:** ~12 verbs for personality
- **Whimsical:** ~20 verbs for fun and brand-specific references

### Behavior

- **Duration:** Each verb appears for fractions of a second before rotating to next
- **Order:** Random selection from the full verb pool
- **Frequency:** Cycles continuously during processing
- **Visibility:** Terminal/CLI only (not visible in programmatic output)

### Evolution

- **Original Release:** ~106 verbs
- **Modern Era (v1.0.49+):** Expanded to 185+ verbs
- **Current Version:** 191+ entries with semantic analysis

---

## Customization

You can customize spinner verbs for your own use of Claude Code!

### How to Customize

1. Open or create `~/.claude/settings.json`
2. Add a custom verbs array:

```json
{
  "spinner_verbs": [
    "Thinking",
    "Pondering",
    "Contemplating",
    "Your Custom Verb"
  ]
}
```

### Community Custom Sets

Users have created elaborate custom verb sets including:

- **Literary Themes:** References from favorite books
- **Movie References:** Quotes and terms from films
- **Military Terms:** Professional jargon from military service
- **Coffee Culture:** Coffee-related activities and terminology
- **Philosophical Concepts:** Abstract philosophical terms
- **Personal Interests:** Custom themed around hobbies

### Example Custom Configuration

```json
{
  "spinner_verbs": [
    "Conjuring",
    "Manifesting",
    "Crystallizing",
    "Weaving",
    "Transcribing",
    "Architecting",
    "Orchestrating",
    "Synthesizing",
    "Harmonizing",
    "Illuminating"
  ]
}
```

---

## Resources

### Official Documentation

- **[Spinner Verbs Dictionary on GitHub](https://github.com/claude-code-book/spinner-verbs-dictionary)**
  - Definitive reference with 191 entries
  - IPA phonetics included
  - Free PDF download available
  - Humorous field sightings documented

- **[The Claudionary](https://claudionary.com/)**
  - Interactive guide to spinner verbs
  - Community contributions
  - Visual browsing interface

### Community Resources

- **[List of 187 Claude Spinner Verbs](https://deepakness.com/raw/claude-spinner-verbs/)**
  - Quick reference list
  - Easy to search and filter

- **[Claude Code Spinner Verbs Repository](https://github.com/wynandw87/claude-code-spinner-verbs)**
  - 1,900+ curated spinner verbs
  - Organized by 88 themed categories
  - Extensible for custom configurations

- **[Daniel Miessler - Customizing Spinner Verbs](https://danielmiessler.com/blog/customized-spinner-verbs-in-claude-code)**
  - Guide to customization
  - Configuration examples
  - Best practices

### Blog Posts & Articles

- **[Claude Code 2.1.23 Is Out With Spinner Verbs](https://medium.com/@joe.njenga/claude-code-2-1-23-is-out-with-spinner-verbs-i-tested-it-ae94a6325f79)** (Medium)
  - Feature deep-dive
  - Real-world testing
  - Usage examples

- **[One Piece Adventure Spinner Theme](https://alexop.dev/posts/claude-code-spinner-verbs-one-piece/)** (Alex's Dev Blog)
  - Creative customization example
  - Themed verb sets
  - Implementation guide

---

## Fun Facts

### Design Philosophy

The spinner verbs embody Anthropic's design philosophy:

1. **Personality Over Minimalism:** The tool communicates as a character, not just a utility
2. **Metaphor as Communication:** Different verb categories help users understand different types of work
3. **Community & Culture:** Verbs become inside jokes and points of connection
4. **Accessibility Through Levity:** Humor makes technology more approachable

### Semantic Grouping

Research into the verbs reveals sophisticated semantic organization:

- **Cognitive verbs** cluster around mental processes
- **Physical verbs** group by type of transformation
- **Culinary verbs** progress from raw to refined
- **Dance verbs** emphasize rhythm and style
- **Whimsical verbs** serve as Easter eggs and brand markers

### Cultural Impact

- Users actively discuss favorite spinner verbs on social media
- Community has created 1,900+ variants and themed custom sets
- The verbs have inspired academic interest in human-computer interaction
- Developers treat them as a sign of personality in AI tooling

---

## Contributing

If you have interesting spinner verbs to suggest or creative custom configurations to share:

1. Check existing resources for duplication
2. Ensure verbs are creative yet clear
3. Consider semantic grouping
4. Share in community forums or create a PR to relevant repositories

---

## License

This guide is created as a reference for the Claude Code project and community. Information sourced from:

- Official Claude Code documentation
- github.com/claude-code-book/spinner-verbs-dictionary
- Community resources and repositories

**Last Updated:** May 2026

---

## See Also

- [Claude Code Documentation](https://docs.claude.com/)
- [Claude Code GitHub Repository](https://github.com/anthropics/claude-code)
- [Anthropic Official Site](https://www.anthropic.com/)

---

*This guide celebrates the joy of thoughtful, personality-driven development tools.*
