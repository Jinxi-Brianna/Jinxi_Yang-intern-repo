## Reflection

### 1. How can UX ensure a smooth handoff between design and development?
A smooth handoff requires clear, detailed, and consistent documentation, plus ongoing communication. UX should provide developers with Figma files that include spacing, colors, typography, and interaction states (hover, active, error). Any animations or responsive behaviors should be shown through prototypes or GIFs. During handoff, a short walkthrough meeting can confirm that developers understand the intended flow and have the chance to raise any feasibility concerns early.

**Personal example – Focus Bear (Time remaining mismatch):**
I reported an issue where two screens showed different remaining times for the same task, and attached annotated screenshots clearly highlighting the discrepancy and the expected behavior. This allowed the developer to understand the problem immediately, reducing the need for repeated clarifications and improving fix efficiency.

---

### 2. What challenges might arise when design, dev, and product teams have conflicting priorities?
Conflicts often happen when:

Design wants the best possible user experience,

Development wants technical feasibility and efficiency,

Product wants to meet deadlines and business goals.

These differences can lead to delays, scope cuts, or changes in quality. For example, the UX team might want to add a step-by-step onboarding to reduce cognitive load, but the product team may want to launch earlier, and developers may be concerned about building extra screens. Such situations require open discussion to weigh trade-offs, prioritize essential elements, and agree on phased improvements.

**Personal example – Focus Bear (Break routines toggle not reflected in break experience):**
I noticed that when a user turned on “Include in every break?” in Preferences, the Break screen showed no corresponding prompt, causing a disconnect in experience. I reported this to the PM with annotated screenshots. In the updated version, a new button option was added so users can choose to start either a micro-break or a regular break, better linking settings to the actual experience.



---

### 3. If a developer modifies a UX design due to technical limitations, how should a UX designer respond?
The UX designer should first understand the technical constraint by asking the developer for details. Then, they can explore alternative solutions that keep the core user experience intact. For example, if the goal is to replace the current countdown timer with a circular progress ring, but this cannot be built immediately, the designer could agree to first introduce a simpler linear progress bar as an interim solution, and then move to the full progress ring in a later release. This lets users benefit from a clearer visual indicator sooner, while giving the development team more time to implement the final design. Collaboration and flexibility are key — the goal is to maintain usability and accessibility while respecting project constraints.

**Personal example – Focus Bear (“Reflect on the session” visibility issue):**
While testing the “Session Complete” screen, I noticed the “Reflect on the session” option was placed very low on the screen, styled like a minor navigation item, and easy to miss. This caused me — and likely other users — to skip logging achievements without realizing it, leaving the Achievements section in Focus Stats blank. I reported this with annotated screenshots and suggested moving the reflection option above the stats section, making it visually prominent, and adding a clear button such as “What did you achieve?” or “Log your success” to encourage users to complete the step.
