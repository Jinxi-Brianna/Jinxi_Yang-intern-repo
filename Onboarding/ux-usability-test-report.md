# Usability Test Report

## 🕒 Session Info
- **Participant:** Rita  
- **Date & Time:** 15 August, 2:00 PM  
- **Location:** In-person test session at home  
- **Facilitator:** Jinxi Yang (myself)  
- **Platform:** iOS version of Focus Bear
## 1. Participant Question Responses

**1. How easy or difficult was it to start the Focus Session?**  
It was relatively easy to start a Focus Session — both the “Start a focus session” button on the Habits page and the Focus tab lead to the same setup screen. However, having two identical entry points feels redundant and slightly unnecessary.  
<img width="619" height="533" alt="截屏2025-08-15 15 10 02" src="https://github.com/user-attachments/assets/1a18baed-e09f-4a41-896d-209e783a1ae9" />

**2. Was anything unclear or confusing during the process?**  
Yes — once the Focus Session started, I couldn’t edit the Focus Goal, which was unexpected. Also, the two-step flow (time setup screen → separate countdown screen) felt unnecessarily long.  
The “Edit Time” label was also misleading — I initially thought it meant resetting the total session length, but it actually extends the session.
<img width="409" height="424" alt="截屏2025-08-15 15 10 11" src="https://github.com/user-attachments/assets/54c112db-e809-4948-9d76-3e6d56ea8d0c" />

**3. Did you notice any labels, icons, or buttons that were hard to understand?**  
The “Focus Goal” field could be more clearly explained — it’s not obvious if it’s required or optional. The end-session flow also wasn’t immediately clear, as it required selecting a reason for ending.  
<img width="353" height="337" alt="截屏2025-08-15 15 10 19" src="https://github.com/user-attachments/assets/3cb8e571-47c6-4c2c-91ff-7ed560f3f574" />

**4. If you could change one thing about the Focus Session setup, what would it be?**  
I would merge the time setup and countdown into one screen with a default 25-minute option, and allow quick adjustments via a wheel or slider. I would also simplify ending a session (e.g., long-press to pause, then choose “Complete” or “Break”).  
Rename or redesign the “Edit Time” feature to clearly indicate extension (e.g., ‘Extend +’).

**5. On a scale from 0–10, how would you rate the overall usability of this feature? Why?**  
**6/10** – The basic flow is functional and relatively easy to find, but the redundancy in entry points, inability to edit the Focus Goal, and the extra steps between setting and starting the timer reduce efficiency. Ending a session is also more complicated than necessary.  

---

## 2. Observation Log – Focus Session Test

| Step / Interaction       | User Action | Observation | Pain Points / Suggestions |
|--------------------------|-------------|-------------|---------------------------|
| Entry to Focus Session   | Used both: (1) Habits page → “Start a focus session”, (2) Directly clicked Focus tab | Both entry points lead to the same time-setting screen | Feels redundant; consider keeping one clear entry path |
| Setting Focus Goal       | Did not enter a goal before starting timer, but wanted to add/edit after session began | Cannot add or edit Focus Goal once timer has started | Allow adding or editing the goal during the session for flexibility |
| Starting the Timer       | Set time on separate screen, then moved to another screen for countdown | Feels like too many steps; not streamlined | Suggest combining time setting and countdown in one screen with default 25 min and quick adjust option |
| Ending a Session         | Pressed End button after timer started | Required selecting a reason for ending | Consider simpler stop/pause interaction (e.g., hold for 3 seconds to pause, then choose Complete/Break) |
|Editing Time              |Tried to adjust session to 25 minutes mid-session|Feature extended session by +25 mins (total 50 mins)|Label “Edit Time” misleading — expected to reset total duration. Suggest renaming to “Extend” and provide confirmation message (e.g., Extended +10 min, total 35)|

---
## 3.Summary & Recommendation
Based on the observations and participant feedback, it is recommended to redesign the Focus Session interface in the Focus Bear iPhone app to improve efficiency, flexibility, and clarity.
Key opportunities for redesign include:
1. Consolidate the two identical entry points into a single, clear starting path.
2. Make the Focus Goal field more visible and allow adding or editing it during an active session.
3. Merge the time setup and countdown into a single screen with a default time option and quick adjustment controls.
4. Introduce a flexible pause option to temporarily stop a session without fully ending it.
5. Clarify time adjustment: Replace the misleading “Edit Time” label with “Extend” (or a + icon next to the timer), and provide clear feedback when time is extended.
## 4. Reflection

**What surprised you the most about how your test participant used the app?**  
I was surprised that the participant immediately noticed the redundancy between the two entry points (Habits page and Focus tab) and questioned the need for both. This suggests that users quickly identify unnecessary complexity even when it doesn’t block task completion.  

**Did they encounter any issues that you didn’t expect?**  
Yes — I did not expect the inability to edit the Focus Goal after the timer started to be such a notable pain point. The participant also found the multi-step transition from time setup to countdown overly complicated, which I had assumed might feel normal for a first-time user.  

**How could this test improve your approach to UX design?**  
This test reinforced the importance of evaluating the **efficiency of task flows** and not just their clarity. Even if users can find the right buttons and complete the task, unnecessary steps or redundant elements can reduce satisfaction. In future designs, I would aim to streamline flows, ensure key inputs are editable during use, and minimise interruptions in starting or ending a core activity.  
