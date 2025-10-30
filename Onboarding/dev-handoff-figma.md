# Developer Handoff - Onboarding / Time Setting

## Figma
Link: (https://www.figma.com/design/E6ChDtYlZPsFndZPkRIrGA/Onboarding?node-id=75-31&t=sY61RbdOQzpF6AwY-1)

## Overview
This delivery includes two screens in the onboarding flow:
1. **Selection** – User decides whether to enable a tech curfew.
2. **Time Setting** – If "Yes" is selected, the user chooses the time to get off tech in the evening.

## Components
- Primary button: "Continue"
- Dialogue buttons: "Yes" and "No, thanks"
- Time picker for curfew selection

## Interaction Notes
- When the user selects **Yes**, the screen transitions to the time picker.
- When the user selects **No, thanks**, the flow skips this step and continues.
- The curfew description text clarifies that Focus Bear blocks distracting apps before bedtime.
- No animation or advanced motion required.

## Style
- Font and colours follow existing app design tokens.
- Layout and alignment consistent with other onboarding steps.

## Checklist
- [x] Frames named correctly in Figma
- [x] Buttons and picker labelled
- [x] Text and logic verified with PM
- [x] Developer comments added in Figma


## Reflection: Preparing a Developer Handoff in Figma

### Q1. What are the biggest challenges in developer handoff, and how can they be avoided?

One of the biggest challenges in a developer handoff is ambiguity caused by incomplete documentation. When a Figma file lacks structure or clear specifications, developers may have to guess layout rules or behavior. This often leads to inconsistencies between the design and the built product. The best way to avoid this is to maintain a clean file structure with clear naming conventions, group related components logically, and include notes for interactions, spacing, and edge cases. Regular communication with developers before and after the handoff also helps identify unclear areas early and prevent unnecessary rework.

---

### Q2. If a developer misinterprets a design, how should a UX designer clarify?

If a developer misinterprets a design, the UX designer should first review the Figma file to confirm whether the misunderstanding came from unclear documentation. The next step is to arrange a short review session or provide written clarification in Figma comments. Instead of only pointing out the mistake, the designer should explain the reasoning behind the design choice, such as usability or accessibility considerations. This approach not only resolves the issue but also helps the developer understand the broader context, improving collaboration and reducing similar misunderstandings in future projects.

---

### Q3. What are the risks of not providing enough detail in a Figma handoff?

Not providing enough detail in a Figma handoff can cause serious alignment and implementation problems. Developers may have to make assumptions about spacing, animation, or responsive behavior, leading to inconsistencies between the design and the actual build. Missing annotations or incomplete component specifications can also slow development, as engineers will need to confirm details individually or redo parts of the interface later. Incomplete documentation increases cognitive load for developers and makes it harder to maintain consistency across pages. To prevent this, designers should use Figma’s Inspect mode, define all shared tokens, and include written notes for key interactions, states, and transitions. A complete, annotated handoff saves time, prevents miscommunication, and ensures that the final product reflects the intended experience.

---

### Q4. Why does the developer handoff come after the design kickoff?

The developer handoff comes after the design kickoff because it represents the transition from design exploration to implementation. During the kickoff, designers, developers, and product managers align on project goals, constraints, and user needs. Once the design has been refined through iteration and validated by testing, the handoff provides a final, approved version for developers to build. Delivering the handoff too early risks passing on designs that may still change, causing inefficiency and confusion. Placing the handoff after the kickoff ensures that teams move from strategy to execution in a clear, structured sequence.

---

## Developer Feedback Evidence

**Developer Feedback – Onboarding / Time Setting**

**Summary**  
Developers reviewed the previous popup design and suggested simplifying it to a consistent full-screen layout to align with the rest of the onboarding sequence.

**Feedback**  
- Popup replaced: Recommended removing the modal and using the standard full-screen format.  
- Implementation: Using the existing onboarding template improves consistency and reduces code complexity.  
- Copy: The conversational tone ("Yes, my phone wrecks my sleep!") approved.  
- Transition: Simple forward navigation between the two screens is sufficient.  

**Changes Made**  
- Removed popup overlay design.  
- Converted both screens to full-screen format.  
- Updated titles and button copy.  
- Verified color and text styles match global tokens.  
- Confirmed component reuse for buttons and time picker.  

**Final Status**  
Design updated based on developer feedback.  
No further changes required. File ready for build.  

> Source: `dev-handoff-feedback.md` and corresponding Figma handoff documentation.
