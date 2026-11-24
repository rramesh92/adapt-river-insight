# Adaptive Learning Engine

Build a polished, clickable web prototype for Swift River Adaptive Clinical Simulation Engine, using the current Swift River / ATI design language, layout patterns, and general visual style as the reference. The prototype should feel like an extension of the existing Swift River educator and learner experience, with a clean healthcare edtech interface, muted clinical colors, white space, card-based panels, left navigation, top utility bar, and clear learner/faculty/admin separation. The product is an AI layer inside Swift River that personalizes unfolding nursing simulations in real time.

Product concept

This is an AI-powered adaptive simulation engine for nursing education. The system changes patient cues, branching difficulty, escalation timing, hint levels, and remediation depth based on the learner’s choices, confidence, and historical performance. It should support multiple user types: students, faculty, program admins, and content authors. The goal is to improve clinical judgment practice, make one scenario usable across multiple skill levels, and give institutions better outcomes visibility.

Core user types

Student.

Faculty/instructor.

Program administrator.

Content author / curriculum designer.

Required application structure

Create a multi-role prototype with role switching. Include these main areas:

Landing / overview page.

Student simulation experience.

Faculty dashboard.

Admin outcomes dashboard.

Scenario authoring / adaptive rules page.

Remediation and debrief page.

Settings / governance page.

Main student flow

The student opens a case from a dashboard showing assigned scenarios, progress, and readiness level. When entering a simulation, the screen shows:

Patient summary.

Current step in the unfolding scenario.

Vital signs or clinical cues.

Actions available.

AI adaptive note explaining why the simulation is adjusting.

Hint / ask for help / continue options.
The simulation should branch based on actions. Include at least three decision points:

Initial assessment.

Prioritization / escalation decision.

Follow-up or handoff decision.
Each branch should show different feedback depending on whether the learner is correct, partially correct, or incorrect. The UI should also show a “simulation adapts to your performance” indicator without revealing hidden answers too early.

Faculty flow

Build a faculty dashboard that shows:

Class roster.

Scenario assignment status.

Heatmap of common weak skills.

Individual and cohort performance summaries.

Auto-generated debrief questions.

Suggested remediation groups.

Ability to compare performance across sections.
Faculty should be able to click into any student and see their simulation path, missed cues, timing, and AI-generated debrief summary.

Admin flow

Build an admin view that shows:

Program-level outcomes.

Cohort comparisons.

Clinical judgment readiness trends.

Completion rates.

Time spent in simulation.

Risk flags for at-risk learners.

Export / reporting actions.
This section should feel enterprise-ready and suitable for leadership review.

Content author flow

Build an authoring screen where an educator can define:

Base scenario title.

Specialty area.

Difficulty level.

Learning objectives.

Allowed adaptive rules.

Branching thresholds.

Handoff cues.

Remediation tags.

Review status.
Show a visual rule builder such as:

If learner misses cue X twice, increase support.

If learner is high-performing, reduce hints and increase complexity.

If learner selects unsafe priority, trigger debrief path B.
The author should be able to preview the case before publishing.

AI behaviors to showcase

The AI should do all of the following in the prototype:

Adjust scenario difficulty in real time.

Generate personalized hints.

Summarize missed clinical judgment patterns.

Recommend remediation.

Produce debrief questions.

Show cohort insights.

Explain why the simulation adapted, in plain language.
Keep the AI visible but non-intrusive, as a side panel or status card.

Demo-friendly interactions

Include clickable states for:

Switching roles.

Starting a simulation.

Making choices in the case.

Opening AI feedback.

Viewing debrief summary.

Viewing cohort analytics.

Editing adaptive rules.

Previewing the same scenario in beginner vs advanced mode.

Visual and UX requirements

Use a polished healthcare education aesthetic.

Design should feel consistent with Swift River / ATI: professional, academic, clinical, and enterprise-ready.

Use card layouts, clear labels, and calm colors.

Use icons, progress indicators, and subtle status badges.

Avoid playful or consumer-app styling.

Keep the prototype presentation-friendly and believable for a board-level pitch.

Prototype success criteria

The final prototype should clearly show:

How the simulation adapts.

How each user type benefits.

How the system improves learning, faculty efficiency, and institutional visibility.

How the same scenario serves different learners differently.

How AI remains supportive, explainable, and instructor-controlled.

Final output

Generate a working clickable prototype with realistic placeholder data, clear flows, and polished visuals. The demo should be easy to present in 5 to 7 minutes.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://adapt-river-insight.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/23dde9ca-e1e4-46ba-9ef1-c546b1304d5c).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
