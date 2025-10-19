## 🐻 Onboarding - Time Setting Flow QA


---

###  Reflection

####  If a developer says a UI issue isn’t a priority, how would you advocate for fixing it?  
I would explain how the issue affects user understanding or task completion, not just visual polish.  
For example, in the previous *Time Setting* flow, users had to answer three separate questions (“wake up,” “finish work,” and “sleep”), which created unnecessary friction.  
The new design simplifies this into one clear “tech curfew” step.  

If a developer deprioritises a design issue, I would connect it to measurable user impact — for instance, showing that unclear wording or missing context could confuse first-time users and reduce onboarding completion.  
By framing the fix as a usability improvement rather than a visual tweak, it becomes easier to justify its value and urgency.

---

####  What are the risks of skipping design QA before launch?  
Skipping design QA can lead to inconsistencies between design and implementation that harm usability.  
Even small gaps — such as missing context text or incomplete explanation — can make the flow feel unfinished.  
In onboarding, these details shape the user’s first impression of the product.  
Without QA, such mismatches might go unnoticed until after release, causing confusion or drop-offs that require more time to fix later.

---

####  How can UX designers give clear and actionable feedback to developers during QA?  
Effective feedback should be specific, visual, and prioritised.  
I would provide annotated screenshots highlighting each discrepancy, describe both the *expected* and *actual* behaviour, and note the priority based on user impact.  

For example:  
> **Expected:** Short explanatory text appears under the “tech curfew” question.  
> **Actual:** Text missing in build.  
> **Priority:** Medium — affects clarity for first-time users.  

This structured format keeps feedback concise and helps developers focus on the most impactful issues efficiently.

---

###  Task

#### **Feature Reviewed**  
**Onboarding → Time Setting Flow (Updated)**  

The previous version contained three separate time-related questions:  
1. What time do you wake up?  
2. When do you finish working/studying?  
3. What time do you go to sleep?  

The new version consolidates them into a single question:  
> *“Do you want to have a tech curfew at night so you can sleep better?”*  

If the user selects **Yes**, a time picker appears for setting the curfew time.  
This redesign aims to shorten onboarding and make the purpose of this step clearer.

---

#### **QA Comparison Summary**

| Category | Change Observed | Expected (from redesign spec) | QA Observation | Priority |
|-----------|----------------|--------------------------------|----------------|-----------|
| Flow structure | 3-step time setup merged into 1-step curfew question + time picker | Fewer screens, clearer logic | **Verified** – flow works as intended | — |
| Context communication | Old contextual line (“Focus Bear will pause blocking…”) removed | Should retain a short explanation of purpose |  **Missing explanatory line may reduce clarity for new users** | Medium |
| Layout hierarchy | UI simplified from multi-screen, multi-line layout to single-screen focus | Clean layout with clear primary actions | **Verified** – layout meets design goal | — |
| Visual hierarchy | Consistent button alignment and spacing between question and actions | Uniform across light/dark mode | **Verified** – no issues observed | — |

---

#### **Discussion with Developer**
- **Flow simplification:** Implemented as designed, improves onboarding speed.  
- **Context copy:** Removal confirmed intentional; PM to review if one-line explanation should be reintroduced.  
- **Visual polish:** No blocking issues; all differences within acceptable range.  

---

#### **Summary**
The redesigned *Time Setting* flow successfully simplifies user interaction and enhances clarity.  
The only notable gap is the removal of the explanatory sub-text, which could slightly reduce comprehension for new users.  
Reintroducing a short contextual sentence (e.g., *“Focus Bear will block distractions before bedtime”*) would strengthen the flow’s intent and align it more closely with the original design rationale.

---

#### **📸 Screenshots**
<img width="782" height="480" alt="截屏2025-10-20 00 30 09" src="https://github.com/user-attachments/assets/548843de-5edb-40a5-aef6-d7bc1dee4cf5" />
<img width="529" height="468" alt="截屏2025-10-20 00 30 27" src="https://github.com/user-attachments/assets/79cd5e91-2009-4aed-8933-9b85b4d5c990" />

