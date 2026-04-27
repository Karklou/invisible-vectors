# Invisible Vectors — Mapping the Hidden Plumbing of Ideas

> *Who or what carried this idea without knowing it — and what shape does that invisible network take?*

---

## What this is

A data art and analytical research project tracing how ideas survive suppression across centuries — not through their conscious defenders, but through the unexpected actors who carried them without understanding what they were carrying.

The prototype case: **heliocentrism**, from Aristarchus of Samos (~310 BC) to Newton (1687). Twenty centuries.

The central finding: the most important vectors for the survival of the heliocentric idea were not its conscious defenders. They were the indirect actors — medieval scribes reproducing a school text without reading it as astronomy, a commercial printer who let a distorting preface pass without reaction, an institution that preserved the enemy of the idea and made its eventual resurgence possible.

This is not a history of science project. It is a method for making visible what has never been seen directly: **the structure of unconscious transmission networks**.

---

## The analytical framework

Three categories of vectors:

- **Conscious vectors** — actors who knowingly transmitted the idea
- **Unconscious vectors** — actors who carried it without grasping its significance
- **Non-human vectors** — objects, institutions, infrastructure

The core claim: intentionality cannot be detected algorithmically. It must be contextually inferred. Qualitative classification is the mandatory foundation — NLP and graph tools come after, never before.

The framework has been validated on five historical cases (Hunayn ibn Ishaq, Carolingian scribes of Martianus Capella, Rheticus, Petreius, Bayt al-Hikmah). Each case produced a non-trivial result. The framework held without proliferating categories.

---

## The visual grammar

The distinction between conscious and unconscious transmission is encoded visually without a legend:

| Variable | Conscious | Unconscious |
|---|---|---|
| Opacity | Full | Reduced |
| Stroke weight | Heavy | Light |
| Shape | Closed (circle) | Open / fragmented |
| Size | — | Encodes agentivity |

Non-human institutional actors use a distinct geometric form (hatched rectangle).

The current prototype implements two states:
- **Synchronic** — the chain as its actors perceived it
- **Analytic** — the chain re-read from the activation point, dormant transmissions revealed

---

## Perceptual test — open question

**Can the conscious/unconscious distinction be read without a legend?**

This is the core hypothesis of the visual grammar. It has not yet been empirically validated.

Look at the prototype. Before reading any label: which node appears to be acting intentionally?

→ **[Live prototype](https://karklou.github.io/invisible-vectors)**

Feedback welcome — open an issue or comment directly.

---

## Structure

```
two-states.html   Active prototype — two-state system (synchronic / analytic)
perceptual-test.html         Archived — initial perceptual test (6 nodes, node grammar only)
sperceptual-test-compact.html          Archived — compact layout variant
```

---

## Theoretical underpinning (invisible in the work)

**Thomas Kuhn** — *The Structure of Scientific Revolutions*. The dominant paradigm resists, then shifts. Suppression is not an anomaly — it is how normal science operates.

**Bruno Latour** — Actor-Network Theory. Science as a network of human and non-human actors. A text, a translation, an institution are actors in their own right.

These frameworks constrain analytical and visual choices without appearing in the work itself.

---

## Status

- Analytical framework (classification method): **complete**
- Visual grammar — node system: **complete, prototype built**
- Visual grammar — edge system (dormant transmission encoding): **in progress**
- Full heliocentric dataset: **in progress**

---

## About

Built by [Karl V](https://karklou.github.io/KarlV) — data artist, strategic analyst, method builder.

This project is part of a larger system (Mosaic) whose central question is: *what invisible infrastructure makes ideas survive?*

The method is designed to be reusable — applicable to any suppressed idea, any historical period, producing something non-trivial each time.
