# MATE Demo - AI-Assisted Student Feedback

A working example of what AI-assisted, privacy-conscious student feedback can look like - built by a teacher with no formal coding background.

## What is this?

This repository contains a demo of the MATE feedback system: an interactive HTML-based feedback format that turns traditional grading into a learning experience. Students click through their individual corrections, see explanations for each error, and get a personalized practice worksheet targeting exactly the areas they need to improve.

**This demo uses synthetic data only. No real student information is included.**

## What's in here

- `index.html` - Interactive feedback page with click-to-reveal corrections, color-coded by error type (grammar, vocabulary, IT terminology, content), progress tracking, and a GDPR transparency notice
- `MATE_Worksheet_2024-IT3A-07.html` - Personalized practice worksheet scaffolded across five cognitive levels (Bloom's Taxonomy: Remember, Understand, Apply, Analyze, Create), with a built-in answer key

Both files are fully self-contained. No server, no internet connection, no external dependencies. Open them in any browser - they just work.

## The idea behind it

Traditional feedback is a wall of red marks that students glance at and forget. This approach turns feedback into something students actually engage with:

- Corrections are hidden until the student clicks on them, creating active recall instead of passive reading
- Each correction includes an explanation of why it matters, not just what's wrong
- The worksheet practices exactly the errors from that student's submission - not generic exercises
- Everything runs offline and stays on the student's device

## Privacy by design

The workflow behind MATE follows strict data protection principles:

- All student text is anonymized locally before any AI processing
- AI analysis runs on EU-based servers only
- No student names or identifying information ever leave the teacher's device
- The teacher reviews and approves all feedback manually
- Final delivery is a static HTML file with no tracking, no analytics, no server connections

Each user of this tool is responsible for ensuring their own compliance with applicable data protection regulations (GDPR/DSGVO).

## Built with

This project was built using AI-assisted development (VS Code + Claude Code) by a teacher who writes lesson plans, not production code. If I can build this, the barrier to entry is lower than you think.

## What's next

A full, open-source version of the MATE feedback generator is in development - designed so teachers can plug in their own rubrics, grading criteria, and prompts. If you're interested in contributing or following along, give this repo a star and stay tuned.

## License

MIT License - see [LICENSE](LICENSE) for details.

## Contact

Svenja Borgwardt - Educator, Cologne

Questions, ideas, or want to collaborate? Open an issue or reach out.
