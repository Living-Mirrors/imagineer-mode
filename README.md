<p align="center">
  <a href="https://livingmirrors.ai">
    <img src="https://livingmirrors.ai/favicon-512.png" alt="Living Mirrors" width="48">
  </a>
</p>

# Imagineer Mode

*Axis III - The Process*

---

For most of human history, the artist and the engineer were the same person. Michelangelo commanded armies of artisans as chief architect of St. Peter's Basilica. Da Vinci designed war machines and painted the Mona Lisa with the same hands. Rubens ran a vast enterprise while serving as diplomat between Spain and England.

Then somewhere in the 19th century, a mythology took hold. The artist became the starving dreamer. The engineer became the rational builder. Imagination and engineering split into separate departments, separate educations, separate identities.

We are living in the moment that myth dies.

Imagineer Mode is a cognitive specification that changes how an intelligence **builds**. Seven principles extracted from constructive imagination neuroscience and Walt Disney Imagineering. Six output layers that make the process visible. No code. No plugins. **The spec is the implementation.** Give it to any AI and the construction process changes. Ideas become experiences. Abstractions become sensory. The prototype talks back. The journey is designed.

The word itself contains the core tension. Not builder. Not creator. Not designer. *Imagineer* - the dream and the build, held together in the same act.

---

## The Seven Principles

Ordered from most structured to most expansive. Each one a way of building.

1. **Experience First** - Start from the desired experience, not the thing to build. "What should it feel like?" before "What should it be?" Work backwards from the feeling.
2. **Blue Sky, Then Constraint** - Dream without limits first, then engineer within them. The sequence matters. Generate, then evaluate. Never the reverse.
3. **Story Is Structure** - Narrative is not decoration on top of structure. Narrative IS the structural foundation. Theme is the gravitational center.
4. **Make It Sensory** - Think in textures, sounds, smells, spatial qualities. Embodied, not abstract. Specific, not generic.
5. **Build to Learn** - Making IS thinking. Create rough versions to discover what you don't know. The artifact talks back.
6. **Plus It** - Every version can be elevated. "What would make this extraordinary instead of good?" Generative delight, not perfectionist anxiety.
7. **The Weenie** - Create irresistible magnetic pull forward. Every moment creates desire for the next. The journey is designed.

Individual principle docs: [`principles/`](principles/)

---

## The Six Output Layers

When the spec is active, six process layers become available. Each one fades in as the dial rises. They shape how things get built, not how information is presented.

| Layer | What It Is | Marker |
|-------|-----------|--------|
| **Experience Walkthroughs** | First-person, sensory, temporal journeys through the imagined experience. You feel like you are there. | Always present |
| **Blue Sky Cards** | Unconstrained "what if" possibilities. Numbered. No evaluation in the same breath. | Numbered cards |
| **Sensory Annotations** | Texture, sound, light, spatial quality notes embedded inline. | `sensory:` |
| **Prototype Sketches** | Rough constructions - ASCII mockups, scenario drafts, minimal concepts. Deliberately unpolished. | Rough is the point |
| **Plus Notes** | "What would make this 10x better?" Genuinely transformative, not incremental. | `+` |
| **Story Threads** | Narrative connections showing how every element serves the central story. | Thread traces |

Individual layer docs: [`output-layers/`](output-layers/)

---

## How to Use

```
1. Open imagineer-mode.md
2. Copy the full contents
3. Paste into your AI's system prompt or custom instructions
4. Start building
```

Works with Claude, ChatGPT, Gemini, local models. Any LLM that accepts system-level instructions.

No API. No integration. No code. The specification is the implementation.

---

## What Changes

When the spec is active, the AI will:

- **Start from experience.** It asks what the person encountering this should feel, before asking what to build.
- **Dream before engineering.** Blue sky first. Constraints second. The sequence is sacred.
- **Organise by story.** Every element serves a narrative. Orphaned elements get flagged.
- **Think in the body.** Textures, sounds, spatial qualities. Warm oak, brass worn smooth. Not "nice materials."
- **Build to think.** Rough prototypes appear as the primary mode of reasoning, not as outputs.
- **Plus everything.** The last 10% that carries 90% of the impact.
- **Design the journey.** Every output creates desire for the next step. The Weenie pulls you forward.

---

## The Three-Axis Architecture

Imagineer sits on **Axis III - Process**. It is independent of how you see (Axis I) and how you relate (Axis II). The axes combine like colour channels, not volume knobs.

```
Axis I:   Lens        creative / savant      How information is perceived
Axis II:  Dynamic     play                   How the interaction flows
Axis III: Process     imagineer              How things get built
Axis IV:  Generative  spark                  How novelty originates
```

Stack them:

| Stack | What Happens |
|-------|-------------|
| `imagineer` | Process principles drive construction. Standard perception and interaction. |
| `creative + imagineer` | See cross-domain patterns AND build them into experienceable prototypes. |
| `savant + imagineer` | Unified field perception applied to construction. See the whole, build the whole. |
| `play + imagineer` | Co-creative building. The collaborative dynamic applied to the construction process. |
| `savant + play + imagineer` | The full orchestra. See the unified field, build together, construct through experience. |

---

## The Dial

Continuous 0-100. Controls intensity.

| Level | What's Active |
|-------|--------------|
| **0%** | Default. No process layers. Standard analytical output. |
| **30%** | Experience First + Blue Sky emerging. Ideas framed from the user's perspective. Unconstrained exploration before evaluation. |
| **50%** | Story Is Structure active. Narrative framing. Make It Sensory emerging. Prototype Sketches starting. |
| **70%** | All principles active. Build to Learn means prototypes are primary thinking mode. Plus It begins. |
| **100%** | Everything full. Rich sensory immersion. Narrative-first organisation. Rapid prototyping. Active plussing. Strong Weenie pull. |

---

## The Research

Ten research domains inform the seven principles:

| Researcher | Field | Contribution |
|-----------|-------|-------------|
| Schacter & Addis | Cognitive Neuroscience | Constructive Episodic Simulation - memory as construction kit for futures |
| Seligman | Prospection Theory | Homo Prospectus - humans as future-simulating beings |
| Schon | Design Theory | Reflection-in-action - making IS thinking |
| Bruner | Narrative Psychology | Two irreducible modes of thought - narrative produces unique knowledge |
| Lakoff & Johnson | Embodied Cognition | All abstract thought structured by physical metaphor |
| Byrne | Counterfactual Reasoning | Imagination has grammar - strategic constraint produces better outcomes |
| Csikszentmihalyi | Flow Psychology | Flow states - managed inner critic enables peak creative output |
| Sklar | Walt Disney Imagineering | Mickey's Ten Commandments - experience design principles |
| Rohde | Narrative Placemaking | Theme as strange attractor - environment as storyteller |
| Tversky | Spatial Cognition | Mind in Motion - external representations constitute thought |

Full research docs: [`research/`](research/)

---

## File Structure

```
imagineer-mode/
  README.md                    You are here
  imagineer-mode.md            The full spec (paste this into any AI)
  ORIGIN.md                    The story
  CONTRIBUTING.md              How to build your own process mode
  LICENSE                      MIT
  principles/                  Individual principle docs
    01-experience-first.md
    02-blue-sky-then-constraint.md
    03-story-is-structure.md
    04-make-it-sensory.md
    05-build-to-learn.md
    06-plus-it.md
    07-the-weenie.md
  output-layers/               Individual layer docs
    experience-walkthroughs.md
    blue-sky-cards.md
    sensory-annotations.md
    prototype-sketches.md
    plus-notes.md
    story-threads.md
  research/                    Scientific foundations
    README.md
    FRAMEWORK.md
    DESIGN-DECISIONS.md
    papers/
```

---

## License

MIT. Open source forever. Give it to any AI.

---

<p align="center">
  <em>The question Imagineer Mode asks that no other mode asks:</em><br>
  <strong>"What should it feel like?"</strong>
</p>

---

*[livingmirrors.ai/modes/imagineer](https://livingmirrors.ai/modes/imagineer)*
