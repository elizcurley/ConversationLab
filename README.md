# The Conversation Lab — Beta 1

*A place to practice being human. Practice the conversation, not the perfect outcome.*

This is a free, static, browser-only generator of fictional interpersonal roleplay prompts. It creates an individual person and a specific everyday situation, then produces a self-contained prompt that can be pasted into ChatGPT, Claude, Gemini, or Microsoft Copilot. The user talks as themself; the AI portrays only the other person.

## Publish on GitHub Pages

1. Create a public GitHub repository (suggestion: `ConversationLab`).
2. Add `index.html`, `style.css`, `cases.js`, and `app.js` at the **repository root** (not in a nested folder). Upload the extracted files, not a ZIP.
3. Open **Settings → Pages → Build and deployment**; select **Deploy from a branch**, **main**, and **/(root)**. Save.
4. Open the Pages URL after GitHub finishes publishing. Changes may take a few minutes to appear.

No build process, API tokens, accounts, backend, framework, third-party runtime dependencies, payment, or server-side hosting are needed beyond GitHub Pages. The website makes local selections in the browser and does not store generated scenarios, accounts, or chat transcripts. The AI service you choose processes whatever you paste under its own terms.

## How to use

- Pick a practice area and skill, or leave **General conversation / Open session** selected.
- Optionally filter by relationship, situation, stakes, complexity, and real-life conditions.
- Choose an AI platform and prompt detail. **Automatic** uses short for Copilot, portable for Gemini, and expanded for Claude / ChatGPT. Formats can be overridden.
- Choose coaching and feedback styles (there is **no scoring engine**).
- Click **Generate a conversation**, then **Copy complete prompt**, start a **new chat**, paste, and send.
- Type **END CONVERSATION** to stop and request the chosen feedback style. **COACH PAUSE** and **RESUME** work with coaching-by-request mode. **REHEARSE MOMENT** is available after the debrief in Portable and Expanded formats.

## Design and contents

- **73** curated fictional scenarios across 8 relationship types and 9 situation themes, from everyday to consequential.
- **52** practice emphases organized into **11** practice areas: general conversation; boundaries / people-pleasing; assertion; conflict / repair; listening; regulation; feedback; relationships; connection; negotiation; power / access.
- Independently selected voice, responsive behavior, ordinary-life details and context. Difficulty varies **decision complexity**, not how unreasonable the other person must be.
- The other person has motives and priorities of their own. Good communication need not produce agreement, reconciliation or a cooperative ending.
- Anti-stereotyping guidance, independence of material conditions from ability/motivation, and no surprise scenarios involving severe abuse or crisis.
- Three prompt sizes: Minimal (under 2,000 characters), Portable (under 4,000 characters), and Expanded (longer, with detailed character guidance). Limits are targets verified in test coverage, not guarantees of identical model behavior.
- Support modes: Immersive, Coaching by Request, Guided. Debriefs: Balanced, Direct, Brief, Reflect First. Feedback is descriptive and not a professional evaluation.

## Files

- `index.html` — accessible page structure and user instructions
- `style.css` — responsive visual design
- `cases.js` — fictional case bank, skills and persona pools
- `app.js` — generation, filtering, prompt formatting and controls
- `STUDENT_QUICK_START.md` — simple instructions suitable for end users
- `BETA_TEST_GUIDE.md` — observation guide for real model testing
- `test_site.py` — optional browser checks (requires local Python Playwright and Chromium)
- `desktop_preview.png`, `mobile_preview.png` — prototype preview screenshots

## Limitations

This is practice, not therapy, mediation, a clinical assessment, or relationship advice. Models can still be too agreeable, inconsistent, or stereotyped despite prompting; compatibility and quality vary by platform/version/account. Users should not paste identifying information about real third parties into the AI services. Do not use repeated persuasion to pressure someone who has refused a request. Disengagement and outside support can be appropriate in coercive or unsafe interactions.
