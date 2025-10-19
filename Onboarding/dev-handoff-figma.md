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


# Reflection - Developer Handoff

## What are the biggest challenges in developer handoff, and how can they be avoided?
The main challenge in developer handoff is the gap between how a design looks in Figma and how it behaves once implemented.  
Developers may focus on functionality, while designers care about details like spacing, transitions, or text tone.  
To avoid misunderstandings, the Figma file must be organized and self-explanatory — with clear layer names, annotations for key interactions, and references to reusable components.  
A short written note or checklist before release also helps ensure that developers understand priorities and context.

## If a developer misinterprets a design, how should a UX designer clarify?
The best way to clarify is to show visual examples instead of long explanations.  
I would highlight the relevant frame in Figma, use comments to explain the intention, and provide screenshots or recordings if needed.  
Instead of assigning blame, the focus should be on how the user experience is affected.  
For example, saying “The button should stay fixed so users always see the action” is more effective than “You implemented it wrong.”  
This approach maintains collaboration and keeps communication constructive.

## What are the risks of not providing enough detail in a Figma handoff?
A vague handoff can
