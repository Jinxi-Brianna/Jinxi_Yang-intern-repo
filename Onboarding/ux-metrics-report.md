## Task

### Key Metric: Onboarding Drop-off Rate

Based on PostHog funnel data from the past 7 days:

| Step                          | Users | Conversion | Drop-off |
|-------------------------------|--------|------------|----------|
| First installed mobile app    | 292    | 100%       | –        |
| Active Mobile Events          | 82     | 28.08%     | ▼ 71.92% |
| Day 1 usage                   | 14     | 4.79%      | ▼ 82.93% |
| Day 2 usage                   | 3      | 1.03%      | ▼ 78.57% |

Only **1.03%** of users return to the app on Day 2, suggesting major drop-off shortly after installation.

---

### Possible Causes

- **Onboarding flow is too long and fragmented**  
  Users may abandon setup before reaching the “morning routine” due to excessive steps and cognitive load.

- **Lack of immediate value demonstration**  
  Users don’t experience the core benefit (e.g., app blocking) early enough to be convinced.

- **Mismatch between user-set goals and suggested habits**  
  This creates confusion and disconnects between intention and action.

- **Visual and interaction issues**  
  Non-clickable elements, awkward transitions, and unclear copy reduce trust and clarity.

---

### Suggested UX Improvement

**Introduce an Early Value Moment During Onboarding**  
- Automatically show a demo or simulation of the app-blocking feature right after installation.
- Make this moment interactive or animated, helping users understand the product’s purpose immediately.
- This can be paired with a simplified onboarding process that postpones optional steps.

---

### Collaboration with PM / Developer

To understand how the onboarding drop-off metric is tracked, I spoke with a PM and a developer on the team. They explained that the current PostHog funnel is based on broad events like app installation and general usage activity, but it doesn’t yet track individual onboarding steps in detail.

This means we can see *that* users are dropping off early, but not *exactly where* in the onboarding flow it happens.

From this discussion, I learned that more detailed event tracking (e.g., step-by-step onboarding actions) would be helpful for pinpointing problem areas and evaluating the impact of future design changes. It also highlighted the importance of aligning UX improvements with what’s technically feasible to track.

---

## Reflection

### If a UX metric shows poor user engagement, how would you determine the cause?

When a key engagement metric is low—such as a high drop-off rate or low feature adoption—I would first locate **where** and **when** the issue occurs using tools like funnel analysis, heatmaps, or session recordings. Next, I would explore **why** it happens through qualitative methods, such as user interviews, open-ended surveys, or usability testing. Often, metrics show *what* is going wrong, but not *why*. For example, a low registration completion rate may be due to confusing form design, privacy concerns, or unclear value proposition—all of which need qualitative input to understand.

---

### What are the risks of relying too much on numbers instead of qualitative feedback?

Over-reliance on quantitative data can lead to **misinterpretation of behavior**, **oversimplified conclusions**, and **missed context**. Numbers can show *what* users are doing—but not *why* they behave that way or how they feel. For example, a high bounce rate may appear negative, but without context, we can’t know if users were simply satisfied quickly or frustrated and left. Additionally, without qualitative validation, teams may optimize for short-term metrics (e.g. clicks) at the expense of long-term satisfaction or trust.

---

### How can UX designers use metrics to convince stakeholders to invest in usability improvements?

UX metrics can be powerful when tied directly to business outcomes. I would present data such as task failure rates, error frequency, or user drop-off points, and then connect them to tangible impacts—like revenue loss, customer churn, or support volume. For example: “60% of users abandon checkout at the payment screen, costing an estimated $X/month in lost revenue.” Clear, objective data makes usability issues feel measurable and solvable. I would also use A/B test results or usability scores to demonstrate the ROI of past improvements, building a strong case for future investment.
