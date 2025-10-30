# Design Kickoff Summary – Onboarding / Time Setting Redesign

**Meeting Date:** September 20, 2025  
**Duration:** 45 minutes  
**Location:** Google Meet
**Feature:** Onboarding / Time Setting Redesign  


## Attendees
- Jeremy Nagel – Lead Developer (Facilitator)  
- Mia Nguyen – Product Manager  
- Jinxi Yang – UX Design Intern (Observer)

---

## Purpose of Meeting
To align on the goals, feasibility, and development requirements for the redesigned Onboarding flow before implementation begins.

---

## Discussion Summary

**1. Overview of Design Goals**  
- The redesign simplifies the time-setting experience by replacing the old popup with a full-screen layout that follows the onboarding template.  
- The aim is to create a more consistent onboarding flow and reduce cognitive load for users.  
- The design includes a clear title, a native time picker, and a confirmation message for user feedback.

**2. Developer Feedback and Notes**  
- **Component Reuse:** Developers confirmed that the existing onboarding template can be reused, which reduces code duplication.  
- **Time Picker:** The iOS and Android teams agreed to use native pickers for accessibility and stability.  
- **Animation:** Developers preferred a simple forward screen transition to avoid unnecessary complexity.  
- **Performance:** The Android developer suggested minimizing animations for low-end devices.  
- **Data Handling:** The “tech curfew” and “reflect reminder” features will require separate state variables to prevent data overlap.

**3. Technical Constraints Identified**  
- Limited customization of the native time picker on iOS.  
- The backend structure currently supports only one active schedule variable and will need an update to handle both time settings.  
- Color and typography tokens in Figma must match the shared component library to ensure automated linking in implementation.

---

## Action Items

| Task | Owner | Due Date | Status |
|------|--------|----------|--------|
| Confirm feasibility of dual schedule support in backend | Jeremy | Sept 23 | In Progress |
| Update Figma component token mapping | Jinxi | Sept 24 | Planned |
| QA checklist for both mobile platforms | Mia | Sept 25 | Planned |

---

## Observations and Learning

As an observer, I learned how a design kickoff helps establish alignment between designers, developers, and product managers. Early discussions about feasibility prevented potential rework by clarifying technical constraints before the build began. I also noticed that developers value well-documented design files that use consistent components and naming conventions.  

Through this meeting, I gained a clearer understanding of how technical feedback can shape the final design decisions. The developers’ comments on native picker limitations and backend variables showed me how UX design choices must balance user experience with system constraints. Observing the meeting helped me better understand how to prepare for future design kickoffs and how to document Figma files to support smoother developer collaboration.

> Supporting materials:

> <img width="343" height="424" alt="截屏2025-10-31 01 57 37" src="https://github.com/user-attachments/assets/59bc454d-dab5-4986-b651-77080f825ae4" />
