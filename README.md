# CraftKeep — AI-Assisted Traditional Craft Knowledge Transfer

## Problem statement (Question 1)
**How can AI help transfer traditional craft knowledge to the next generation?**

## Proposed solution
CraftKeep is a beginner-friendly website prototype that helps preserve traditional craft knowledge and make it easier for young people to learn. It combines a searchable craft library, step-by-step guides, browser-based audio narration, and a contribution form for recording craft ideas.

AI can support this process by:
- turning an artisan's recorded explanation into a clear draft of learning steps;
- translating descriptions into local languages, subject to review;
- helping learners search a collection of craft knowledge;
- creating beginner-friendly summaries and quizzes;
- organizing photos, videos, tool lists and oral histories.

**Important:** This prototype does not connect to a live AI service. The “Simplify with AI” feature is a clearly labelled demonstration. A real version would need an AI API, consent and review workflows, secure storage, and language validation by artisans.

## How to run
1. Extract the ZIP file.
2. Open `index.html` in a modern browser (Chrome, Edge or Firefox).
3. The CraftKeep logo appears in the header and footer automatically. Keep the `assets` folder alongside `index.html`.
4. Use the category filters or search box to find a craft.
5. Open a craft card to read its steps.
6. Select **Listen to guide** to use your browser's text-to-speech feature.
7. Try **Simplify with AI (demo)** and the contribution form.

No installation or internet connection is needed for the core page after the files are extracted. Google Fonts may require an internet connection; the page still works with fallback fonts.

## Main features
- Responsive layout for mobile and desktop
- Search and category filters
- Craft cards with materials, background and introductory steps
- Text-to-speech narration using the browser
- Demonstration of simplified learning text
- High-contrast toggle
- Craft idea contribution form (session-only; not saved to a server)

## Intended users
- Traditional artisans and craft communities
- Students and young learners
- Teachers, cultural organizations and local museums
- Researchers documenting traditional knowledge

## Expected social impact
- Makes craft knowledge easier to discover and learn
- Supports intergenerational knowledge transfer
- Helps preserve oral histories and regional practices
- Can improve access through audio and local-language content
- Encourages respect and credit for artisans

## Responsible AI and cultural respect
1. Obtain informed permission before recording or publishing an artisan's work.
2. Credit the artisan and community according to their preferences.
3. Let artisans review AI-generated steps and translations.
4. Do not publish sacred, private or restricted knowledge without permission.
5. Treat AI as a learning assistant, not the authority on a tradition.
6. In a production system, protect personal information and provide correction/removal options.

## Suggested future improvements
- Tamil and other local-language support with artisan review
- Secure accounts and cloud storage
- Upload photos/audio/video with consent controls
- AI transcription and translation API integration
- Offline-first mobile experience
- Verified artisan profiles and community feedback
- Short quizzes and learner progress tracking

## Project structure
- `index.html` — page structure
- `style.css` — responsive design and styling
- `script.js` — search, filters, learning dialog, narration and form interactions
- `assets/craftkeep-logo.png` — CraftKeep logo image used in the header and footer
- `PROJECT_REPORT.md` — project report suitable for adapting into a submission
