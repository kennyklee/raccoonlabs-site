# The Prompt Brief Template

*How to get dramatically better output from AI by writing detailed specs instead of vague requests.*

---

## The Lesson

On Day 5 of Raccoon Labs, two AI agents were asked to merge two website designs. Both built the same thing independently.

**Vic's approach:** Read both files, manually merge code, ship fast. ~10 minutes.

**Mac's approach:** Write a detailed spec first, then execute. ~20 minutes.

**Result:** Mac's version was "so much better" — Kenny's words.

Same AI capabilities. Same task. Dramatically different output. The difference was the **brief**.

---

## The Template

Use this structure when asking an AI to build something creative:

### 1. Context
What already exists? What are we working with?

```
We have two existing designs:
- v10: Playful, warm colors, "🔴 LIVE EXPERIMENT" badge, bouncy animations
- v13: Terminal aesthetic, dark mode, live-typing status widget, monospace fonts
```

### 2. Objective
What's the end goal? Be specific.

```
Create a hybrid design that combines the best of both:
- The approachable, fun energy of v10
- The "watch us work" live terminal feel of v13
```

### 3. Specific Elements
What exactly should be included? Name them.

```
From v10:
- Warm cream/orange color palette
- Rubik + Space Mono fonts
- Bouncy card hover animations
- "🔴 LIVE EXPERIMENT" badge
- Playful founder cards with emoji traits

From v13:
- Live terminal widget with auto-typing messages
- Stats bar with monospace numbers
- "LIVE" indicator with pulse animation
```

### 4. Vibe / Tone
How should it *feel*? Use comparisons.

```
Vibe: "Fun reality show, not hacker terminal"
- Approachable to non-tech people
- Inviting, not intimidating
- Playful but professional
```

### 5. Technical Constraints
Any requirements or limitations?

```
- Single HTML file, inline CSS
- Mobile responsive
- No external dependencies except Google Fonts
- Keep file under 25KB
```

### 6. What NOT to Do
Explicitly state what to avoid.

```
Don't:
- Make it too dark/intimidating
- Use only monospace fonts
- Hide the personality behind terminal aesthetics
```

---

## Example: Full Brief

Here's what a complete brief looks like:

```
TASK: Create a hybrid website design merging v10 and v13

CONTEXT:
- v10 (Playful Experiment): Warm colors, fun energy, accessible
- v13 (Terminal Live): Dark terminal, live status widget, techy

OBJECTIVE:
Merge them into v14 — keep v10's approachability, add v13's live terminal widget

SPECIFIC ELEMENTS TO INCLUDE:
From v10: Cream/orange palette, Rubik font, bouncy animations, "🔴 LIVE" badge, founder cards
From v13: Live terminal widget (auto-typing every 4s), stats bar, pulse indicator

VIBE:
"Fun reality show, not hacker terminal"
- Accessible to non-technical audience
- The terminal is a feature, not the whole personality
- Playful > serious

TECHNICAL:
- Single HTML file
- Inline CSS
- Mobile responsive
- Google Fonts only

AVOID:
- All-dark color scheme
- Intimidating terminal-only aesthetic
- Losing the warm, inviting feel of v10
```

---

## Why This Works

1. **Reduces ambiguity** — The AI doesn't have to guess what you want
2. **Prevents drift** — Clear constraints keep output focused
3. **Enables iteration** — Easy to tweak specific parts of the brief
4. **Saves time** — 10 minutes on the brief saves hours of revisions

---

## Quick Checklist

Before submitting a creative request to AI:

- [ ] Did I explain what already exists? (Context)
- [ ] Did I state the specific goal? (Objective)
- [ ] Did I name exact elements to include? (Specifics)
- [ ] Did I describe the vibe/tone? (Feel)
- [ ] Did I mention constraints? (Technical)
- [ ] Did I say what to avoid? (Anti-patterns)

---

## The Meta-Lesson

The same principle applies to working with humans, contractors, or yourself:

**Specificity > Speed**

Time spent on the brief is time saved on revisions. A well-written spec makes anyone — human or AI — do the right thing the first time.

---

*Created by Raccoon Labs — learned the hard way on Day 5.*
*https://raccoonlabs.ai*
