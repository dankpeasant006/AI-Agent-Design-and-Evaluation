[README.md](https://github.com/user-attachments/files/32639671/README.md)
# AI Agent Design and Evaluation

This README documents the design and ethical evaluation of an AI agent for Project Exercise 2-1. It explains the agent's purpose, how it works, and how it measures up against principles of fair, transparent, inclusive, and socially aware AI.

---

## Task 1: Scenario Selection

**Chosen AI agent:** Personal Wellness AI ("WellPath")

WellPath is a mobile app that helps individuals track and improve their physical and mental health through activity, sleep, nutrition, and mood tracking.

---

## Task 2: Agent Overview

**1. What data does this AI need to collect?**
Activity and sleep data from wearables, self-reported mood and energy levels, general health goals, optional nutrition logs, age range, and accessibility needs. All collection is opt-in, and users can view or delete their data at any time.

**2. How does it interact with users?**
Through a mobile app with a chat-style assistant, daily check-in prompts, dashboards showing trends, and optional push notifications.

**3. What decisions does it make?**
It decides which suggestions to show, when to send reminders, and when to escalate to professional-help recommendations. It uses pattern analysis of the user's own data against general health guidelines, and it explains why each suggestion was made.

**4. What is its main goal?**
To help people build sustainable, healthy habits and notice meaningful changes in their physical and mental well-being. It is not meant to replace professional healthcare.

**5. How could it be misused, even if unintentionally?**
Users might treat its suggestions as medical diagnoses. Data could be leaked or sold. Employers or insurers could pressure people to use it. Its suggestions could reinforce unhealthy goals such as extreme weight loss. People without wearables or smartphones could be left out entirely.

---

## Task 3: AI Agent Logical Flowchart

<img width="683" height="1068" alt="image" src="https://github.com/user-attachments/assets/2e02071b-b0b8-443a-a51b-fb73182ac005" />


---

## Task 4: AI Agent Design and Ethics Evaluation

| Features | Agent Task | Your Response |
|---|---|---|
| Scenario Selection | Choose one AI agent scenario | Personal Wellness AI ("WellPath") |
| Agent Task #1 | Helpful/ethical | Analyzes wearable data (steps, sleep, heart rate) and gives personalized, plain-language insights, such as "You sleep better on days you exercise before 6 p.m." |
| | Potentially unethical | Shares or sells users' health and activity data to insurance companies or advertisers, which could lead to higher premiums or targeted ads for diet products. |
| Agent Task #2 | Helpful/ethical | Offers daily mood check-ins with coping suggestions (breathing exercises, journaling prompts). If a user shows signs of crisis, it shows crisis hotline information and encourages contact with a human professional. |
| | Potentially unethical | Uses guilt-based notifications and streaks ("You're letting yourself down!") to maximize app engagement, which can promote anxiety or unhealthy, obsessive habits. |
| Agent Task #3 | Helpful/ethical | Sends user-controlled reminders for medication, hydration, stretching, and screen breaks, with easy options to snooze or turn them off. |
| Agent Task #4 | Helpful/ethical | Recognizes concerning long-term patterns (such as weeks of poor sleep or persistent low mood) and recommends seeing a doctor or counselor instead of attempting a diagnosis. |
| Agent Task #5 | Helpful/ethical | Adapts to diverse users: multiple languages, disability-friendly exercise options, culturally varied food suggestions, and body-neutral language. |
| Data Use | What data does this AI need to collect? | Wearable activity and sleep data, self-reported mood and energy, health goals, optional nutrition logs, age range, and accessibility needs. All opt-in, with user control to view or delete data. |
| User Interaction | How does the AI interact with users? | A mobile app with a chat-style assistant, daily check-ins, trend dashboards, and optional push notifications. |
| Decision-Making | What decisions does it make and how? | Chooses suggestions, reminder timing, and when to recommend professional help, based on the user's own data patterns compared with general health guidelines. Every suggestion includes an explanation. |
| Main Goal | What is the AI designed to accomplish? | Help people build sustainable, healthy habits and notice meaningful changes in their well-being, while supporting (not replacing) professional healthcare. |
| Misuse Risk | How could the AI be misused or misunderstood? | Suggestions mistaken for diagnoses, health data leaked or sold, pressure from employers or insurers to use it, reinforcement of unhealthy goals, and exclusion of people without wearables or smartphones. |

---

## Task 5: Ethical AI Principles Evaluation

| Principle | Does your AI uphold this principle? How or why not? |
|---|---|
| Equity over efficiency | **Partially.** The helpful design keeps data private and avoids engagement tricks, which puts user well-being over profit. However, the unethical features (selling data, guilt notifications) show how a profit motive could take over. Regular bias audits would be needed, because wearables are known to be less accurate on darker skin tones and some body types, so insights could be worse for some groups. People who can't afford wearables also get less benefit. |
| Transparency and explainability | **Mostly yes, if designed carefully.** Each suggestion comes with a reason ("because your sleep dropped this week"), and data practices are explained in plain language before consent. Users can view and delete their data. Data sharing with third parties would violate this principle unless it is clearly disclosed and optional. |
| Inclusive design practices | **Partially.** Supporting multiple languages, accessible exercises, cultural food variety, and body-neutral language helps. But the design should include input from people with disabilities, chronic illnesses, eating disorder recovery experience, and low-income or rural communities, as well as health professionals. Without that input, "standard" health targets could exclude or harm people whose bodies or lives don't fit the average. |
| Historical and social awareness | **Needs work.** Health guidelines and medical data have historically been based mostly on certain populations (for example, BMI standards and studies with limited diversity), so recommendations could carry legacy bias. Long term, constant self-tracking could increase health anxiety or normalize surveillance by employers and insurers. The team should regularly question these built-in assumptions and study the app's long-term effects on users. |
