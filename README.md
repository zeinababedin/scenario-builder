# Scenario Builder (Beginner-Friendly)

## What this project is
Scenario Builder is the starting point for a simple, beginner-friendly tool that will help turn social media ideas into quick scenarios and clear storyboards. Everything here is written in plain English so someone with no coding or AI experience can follow along.

## What problem it solves
Coming up with content ideas is easy; turning them into well-structured posts or videos is harder. This project will grow into a guide that takes a rough idea and shows how to turn it into:
- A quick scenario that fits the audience and platform.
- A storyboard that maps out visuals, text, and pacing.

## What it will be able to do in the future
These features are **not built yet**, but the project is designed to grow toward:
- Adapting scenarios to different audiences (age, platform, interests).
- Matching tone (formal, casual, friendly, professional) and style (e.g., Persian colloquial, formal Arabic, casual Arabic).
- Supporting formats like vlogs, long-form YouTube videos, short reels, or TikTok clips.
- Converting scenarios into step-by-step storyboards.

## How the project is organized (kept very simple)
- `inputs/ideas.md`: Where you write your raw ideas or prompts. Nothing fancy—just notes.
- `scenarios/personalized_scenarios.md`: A placeholder for turning ideas into quick scenarios. No automation yet.
- `storyboards/storyboard_outline.md`: A placeholder for outlining storyboard frames once scenarios are ready.

Each file has comments in plain English explaining its purpose. The goal is clarity over code.

## How the parts will connect later
1. **Start with ideas**: Jot down an idea in `inputs/ideas.md`.
2. **Expand to scenarios**: Sketch how the idea could become a scenario in `scenarios/personalized_scenarios.md` (think: who it’s for, what platform, what tone).
3. **Shape a storyboard**: Turn the scenario into a simple storyboard outline in `storyboards/storyboard_outline.md` (visuals, text, and timing).

## What is intentionally **not** included yet
- No AI, agent, or automation code.
- No external services or complex setup.
- No programming knowledge required to read or edit these files.

## Getting started (for complete beginners)
1. Open the `inputs/ideas.md` file and type a few content ideas.
2. Open `scenarios/personalized_scenarios.md` and write how each idea might look as a short scenario.
3. Open `storyboards/storyboard_outline.md` and outline how that scenario could play out frame by frame.

Take it step by step. The project will stay simple and grow gradually.

## New: Beginner-friendly preferences page
To capture basic preferences (audience, tone, format, language) and keep them between visits, use the new `preferences.html` page.

### How to run it
1. Open the `preferences.html` file in your web browser (double-click it or right-click and choose “Open with browser”).
2. You will see four text fields and a **Save preferences** button.

### How to use and test it
1. Fill in all four fields (all are required).
2. Click **Save preferences**.
3. A **Preferences summary** box on the same page updates immediately with what you saved.
4. Refresh the page; your saved values should still appear because they are stored in your browser’s `localStorage`.
5. Edit any value and click **Save preferences** again to update both the stored data and the summary.

That’s it—no setup, servers, or installs needed.
