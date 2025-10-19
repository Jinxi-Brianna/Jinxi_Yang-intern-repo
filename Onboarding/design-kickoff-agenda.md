# Design Kickoff Agenda - Onboarding / Time Setting Redesign

## Purpose
Prepare for the implementation of the updated onboarding Time Setting flow and ensure the design handoff file is clear and ready for development.

## Context
This kickoff was conducted to review the redesign of the Time Setting section, which changes the old popup format to a consistent full-screen layout.

## Goals
1. Present the updated design and its purpose.  
2. Review logic between the two screens (“Tech Curfew” → “Time Picker”).  
3. Confirm that styles and components follow existing design tokens.  
4. Identify potential implementation questions or unknowns before build.  
5. Finalize the handoff file for development.

## Agenda
| Step | Topic |
|------|--------|
| 1 | Overview of redesign goals |
| 2 | Walkthrough of the Figma flow |
| 3 | Review of interactions and transitions |
| 4 | Check component reuse and consistency |
| 5 | List follow-up actions or documentation updates |

## Key Topics
- Why the popup version was replaced with a full-screen layout.  
- How the “Yes / No thanks” logic connects to the next onboarding step.  
- Use of the existing button and time picker components.  
- Consistency with other onboarding steps (Goals → Routine → Timing).  

## Expected Outcome
- All redesign intentions documented in Figma comments.  
- Clear structure and logic ready for handoff.  
- No unresolved design questions before build.

# Reflection - Design Kickoff Preparation

## How does a good design kickoff help prevent development issues later?
A clear design kickoff ensures that the design intent, logic, and constraints are fully documented before implementation begins.  
Even if no formal meeting happens, preparing a structured agenda helps identify unclear elements in the Figma file.  
By reviewing interactions and confirming component reuse in advance, many potential misunderstandings between design and development can be avoided later.

## What questions should a UX designer ask developers to identify technical constraints early?
Typical questions include:
- Can the existing component library support this layout?
- Will this interaction require additional backend data or logic?
- Are there any platform-specific limits for the animation or input behavior?
- What information does the developer need to start building confidently?

Asking these questions early allows designers to simplify or adjust designs before the build stage, saving time during development.

## How can designers make sure that developers fully understand the UX vision?
Designers should document both *what the user sees* and *why it matters*.  
This includes short explanations in Figma comments describing user intent, flow purpose, and expected outcomes.  
Consistent naming, clean layers, and concise annotations help developers interpret the vision accurately, even without a live walkthrough.  
A clear Figma file often communicates the UX intent better than long explanations.

## Summary
Preparing a kickoff, even informally, made me realise that design clarity starts before any code is written.  
By anticipating developer questions and ensuring the file explains itself, I can reduce confusion and make collaboration smoother once development begins.

