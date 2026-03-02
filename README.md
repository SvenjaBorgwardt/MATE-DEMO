# MATE Demo - AI-Assisted Student Feedback

A working example of what AI-assisted, privacy-conscious student feedback can look like - built by a teacher with no formal coding background.

## What is this?

MATE turns traditional grading into an interactive learning experience. Instead of a wall of red marks, students click through individual corrections, see explanations for each error, track their progress across the semester, and get personalized practice exercises targeting exactly the areas they need to improve.

This repository contains a full demo of the system - from individual student feedback to teacher-level analytics across 80 students in 3 classes.

**All data is synthetic. No real student information is included.**

## What's in here

**Student-facing:**

- `index.html` - Interactive feedback with click-to-reveal corrections, color-coded by error type (grammar, vocabulary, IT terminology, content), and a GDPR transparency notice
- `MATE_Progress_2025-IT3A-07.html` - Semester progress dashboard with XP system, level progression, skill radar, grade trajectory, and error reduction tracking
- `MATE_Worksheet_2025-IT3A-07.html` - Personalized practice worksheet scaffolded across five cognitive levels (Bloom's Taxonomy), with a built-in answer key

The feedback and progress pages are cross-linked so students can navigate between them.

**Teacher-facing:**

- `MATE_Teacher_Dashboard.html` - Analytics across 3 classes (80 students): class performance over time, grade distributions, error breakdowns, top performers, red flag alerts for declining students, and sortable student table with XP tracking

All files are fully self-contained. No server, no internet connection, no external dependencies. Open them in any browser - they just work.

## The idea behind it

Traditional feedback is a wall of red marks that students glance at and forget. This approach turns feedback into something students actually engage with:

- Corrections are hidden until the student clicks on them - active recall instead of passive reading
- Each correction includes an explanation of why it matters, not just what's wrong
- The worksheet practices exactly the errors from that student's submission, not generic exercises
- An XP and leveling system makes progress visible and motivating
- The teacher dashboard aggregates correction data into actionable insights across all classes
- Everything runs offline and stays on the student's device

## Privacy by design

- All student text is anonymized locally before any AI processing
- AI analysis runs on EU-based servers only
- No student names or identifying information ever leave the teacher's device
- The teacher reviews and approves all feedback manually
- Final delivery is a static HTML file - no tracking, no analytics, no cookies, no server connections
- Fonts loaded from Bunny Fonts (EU-based CDN, GDPR compliant)

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
