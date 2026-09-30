# 🎨 Web Design Resources to Escape AI Slop

A curated collection of websites, libraries, and tools that help build **better-looking, more intentional, and less generic web interfaces**.

> The goal is simple: **don't let AI generate the same boring website everyone else has.**

These resources are useful when building websites with **Cursor, Claude Code, Codex, Lovable, v0, React, Next.js, Tailwind, Three.js**, and other modern frontend stacks.

---

## 📚 Resources

| Resource                                          | What it's useful for                             |
| ------------------------------------------------- | ------------------------------------------------ |
| [21st.dev](https://21st.dev/)                     | React components, templates, UI inspiration      |
| [GSAP](https://gsap.com/)                         | Advanced web animations and interactions         |
| [Taste Skill](https://www.tasteskill.dev/)        | Preventing generic AI-generated frontend designs |
| [ThreeUI](https://threeui.com/browse?sort=recent) | Three.js, WebGL, 3D components and effects       |

---

## 1. 🧩 21st.dev

🔗 **https://21st.dev/**

21st.dev is a large community-driven library of **React components, templates, themes, shaders, gradients, and UI patterns**.

It is especially useful when you want to give an AI coding agent a strong visual reference instead of asking it to invent an entire interface from scratch.

### Useful for

* React components
* Hero sections
* Landing pages
* Cards
* Navigation
* AI chat interfaces
* Gradients
* Shaders
* Animated UI
* shadcn-style components
* Design inspiration

### Why use it?

Instead of:

> "Create a modern SaaS landing page."

You can find a specific visual direction and use it as a reference for your implementation.

21st.dev currently describes itself as a community catalog containing thousands of React components, templates, and shadcn themes.

**Best for:**
`React` · `Next.js` · `Tailwind` · `shadcn/ui` · `AI coding agents`

---

## 2. ✨ GSAP

🔗 **https://gsap.com/**

GSAP (GreenSock Animation Platform) is a professional-grade JavaScript animation library for creating **smooth, controlled web animations**.

It can animate UI elements, SVGs, text, scrolling experiences, and more.

### Useful for

* Scroll animations
* Page transitions
* Text animations
* Micro-interactions
* SVG animations
* Parallax effects
* Timeline-based animations
* Interactive landing pages
* Complex animation sequences

### Important tools

* **GSAP Core**
* **ScrollTrigger**
* **SplitText**
* **Flip**
* **Observer**
* **MotionPath**
* **Draggable**

### Example use cases

```text
User scrolls
    ↓
Hero text moves
    ↓
Image scales
    ↓
Background changes
    ↓
Next section reveals
```

GSAP is particularly useful when a website needs **motion with intention**, rather than random animations added just because an AI suggested them.

**Best for:**
`React` · `Next.js` · `JavaScript` · `Interactive websites` · `Creative portfolios`

---

## 3. 🧠 Taste Skill

🔗 **https://www.tasteskill.dev/**

Taste Skill is specifically designed to help AI coding agents produce **less generic frontend interfaces**.

It describes itself as an **"Anti-Slop Frontend Framework for AI Agents."**

The project provides open-source skill files that can guide tools such as:

* Cursor
* Claude Code
* Codex
* Gemini CLI
* v0
* Lovable
* OpenCode

### What makes it interesting?

Instead of simply telling an AI:

> "Make this website look premium."

Taste Skill provides structured design guidance around things such as:

* Design direction
* Typography
* Spacing
* Color systems
* Layout decisions
* Motion
* Design-system selection
* Dark-mode design
* Redesign workflows
* Pre-flight checks

The current v2 is described as an experimental rewrite that makes the agent infer the appropriate design direction before implementing the interface.

### Installation

```bash
npx skills add Leonxlnx/taste-skill
```

### Best for

**AI-assisted frontend development where you want to avoid:**

* Generic gradients
* Repetitive card layouts
* Random animations
* Default-looking dashboards
* "AI-generated" visual patterns
* Poor typography
* Inconsistent spacing
* Template-like interfaces

**Best for:**
`AI coding agents` · `Frontend design` · `React` · `Next.js` · `AI-assisted development`

---

## 4. 🌌 ThreeUI

🔗 **https://threeui.com/browse?sort=recent**

ThreeUI provides **copy-ready Three.js components, website templates, WebGL backgrounds, hero sections, UI effects, and interactive 3D elements**.

### Useful for

* Three.js
* WebGL
* 3D websites
* Interactive backgrounds
* Hero sections
* 3D assets
* Text animations
* UI effects
* Motion design
* Creative landing pages

### Categories

ThreeUI includes resources for:

* Sections
* Landing Pages
* 3D Assets
* Text Animation
* UI Elements
* Backgrounds
* Buttons
* Hero sections
* Three.js
* CSS
* Motion Design

### Best for

When a normal 2D website isn't enough and you want to experiment with:

```text
WebGL
  +
Three.js
  +
Animation
  +
Interaction
  =
Immersive web experience
```

**Best for:**
`Three.js` · `WebGL` · `React Three Fiber` · `3D websites` · `Creative development`

---

# 🧰 How I Use These Together

These resources become much more powerful when used together.

### Step 1 — Find the visual direction

Use:

**21st.dev**

Find components and layouts that match the visual direction you want.

↓

### Step 2 — Define the design rules

Use:

**Taste Skill**

Give your AI coding agent stronger constraints so it doesn't fall back to generic AI-generated UI.

↓

### Step 3 — Add meaningful motion

Use:

**GSAP**

Add intentional animations and interactions.

↓

### Step 4 — Add 3D when it actually helps

Use:

**ThreeUI**

Introduce WebGL / Three.js elements where they improve the experience.

---

# 🚫 Avoiding AI Slop

When using AI to build a website, avoid blindly accepting:

* ❌ Purple/blue gradient backgrounds everywhere
* ❌ Huge rounded cards for everything
* ❌ Excessive glassmorphism
* ❌ Random floating blobs
* ❌ Unnecessary animations
* ❌ Generic "SaaS" layouts
* ❌ Same typography hierarchy on every project
* ❌ Excessive use of `rounded-2xl`
* ❌ Every section being a card
* ❌ Fake statistics and testimonials
* ❌ Copy-pasted landing-page structures

Instead:

* ✅ Start with a clear visual direction
* ✅ Use real references
* ✅ Choose typography intentionally
* ✅ Establish spacing rules
* ✅ Use animation to communicate hierarchy
* ✅ Make interactions purposeful
* ✅ Use 3D only when it adds value
* ✅ Keep the interface coherent
* ✅ Let the product determine the design

---

# 🧑‍💻 Recommended AI Workflow

A useful workflow for AI-assisted frontend development:

```text
                 IDEA
                   │
                   ▼
          Define visual direction
                   │
                   ▼
              21st.dev
          Find UI references
                   │
                   ▼
             Taste Skill
        Establish design rules
                   │
                   ▼
           AI Coding Agent
       Cursor / Claude / Codex
                   │
                   ▼
                GSAP
        Add intentional motion
                   │
                   ▼
              ThreeUI
       Add 3D where appropriate
                   │
                   ▼
             HUMAN REVIEW
                   │
                   ▼
             FINAL WEBSITE
```

---

# ⭐ Quick Reference

### Need UI inspiration?

👉 [21st.dev](https://21st.dev/)

### Need professional animations?

👉 [GSAP](https://gsap.com/)

### Want AI to stop generating generic interfaces?

👉 [Taste Skill](https://www.tasteskill.dev/)

### Want Three.js / WebGL / 3D components?

👉 [ThreeUI](https://threeui.com/browse?sort=recent)

---

## 🤝 Contributing

Found another resource that helps create better websites and avoid generic AI-generated design?

Feel free to open a Pull Request and add it to this list.

Useful additions include:

* UI component libraries
* Animation libraries
* Design systems
* Typography resources
* WebGL / Three.js resources
* AI frontend skills
* Interaction libraries
* Creative coding tools
* Design inspiration platforms

---

## 📌 Philosophy

> **AI should accelerate creativity, not standardize it.**

Use AI for speed.

Use references for taste.

Use design principles for consistency.

Use your own judgment for the final result.

---

### 🔗 Resources

* https://21st.dev/
* https://gsap.com/
* https://www.tasteskill.dev/
* https://threeui.com/browse?sort=recent
