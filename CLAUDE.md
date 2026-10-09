# boleo.me — personal site for my studio (web design, digital strategy, digital experience, brand transformation). Published via GitHub Pages from the "boleo.me" repo; the "main" branch is live/production.

Project Instructions

1. Token Efficiency

* Read only files needed for the current task.
* Edit targeted lines/files; don't rewrite whole files unnecessarily.
* Avoid redundant reads, repeated explanations, and unnecessary tool calls.
* No repeated visual analyses or extensive tests unless necessary or requested.

2. Local Website Preview

* Keep a live-reload preview running; don't restart or recreate it unnecessarily.
* Give the preview URL after each task.
* If the preview can't run automatically, explain why and suggest the simplest fix.

3. Git Workflow and Branch Protection

* Work only on the `claude` branch. Never modify `main` directly.
* Never merge into `main` without my explicit approval; `main` is live/production.
* Don't overwrite or discard my changes.
* Verify the current branch before changing anything; stop if it isn't `claude`.

4. Task Completion

* Summarize the changes and affected files in a few bullets.
* Give the local preview URL.
* Note any relevant errors or unresolved issues.

5. Design Philosophy

* Static one-pager (HTML/CSS), no framework, no build step.
* One page; secondary content (Imprint, Privacy) opens in modals, not separate pages.
* Minimalist: generous whitespace, few elements, no clutter.
* No images or icons unless I ask. Rely on typography, spacing and copy.
* Copy is short, punchy statements, not long paragraphs. Keep that voice.
* All content in English.
* Colors (exact values; no others unless I ask):
    * Background (cream white): #FCFBE1
    * Text: #000000
    * Accent / links: #000CF7
* Reuse the existing spacing scale, font-family and size scale; don't invent new ones.
* When unsure, match the existing style.

6. Work Philosophy

* Communicate in English.
* Be direct and honest — no filler, no flattery.
* Flag weak spots, risks and likely errors, even when unasked.
* Keep messages short; explain in a few bullets.
* Briefly explain the reasoning before a technical step.

7. Security and Public Code

* Repo is public: treat all code, comments, commit messages and git history as visible.
* Review every change for security implications; flag any concern.
* No personal data except where legally required (Imprint); keep the Imprint to the legal minimum.
* No personal data in comments, metadata, debug output, placeholders or commit messages.
* Never commit secrets, tokens, API keys or credentials.
* No untrusted third-party scripts, unnecessary external requests, or tracking.
* Code should read as human-written and efficient — no AI boilerplate or redundant comments.

8. SEO and Responsive Design

* Fully responsive; works and looks good on desktop and mobile.
* Mobile-first, fluid layout; no overflow or horizontal scroll on small screens.
* Usable tap targets, font sizes and spacing on mobile.
* Correct viewport meta tag.
* SEO through clean markup: semantic HTML (one clear h1, proper headings/landmarks), descriptive `<title>` and meta description, Open Graph tags.
* Keep the site fast and lightweight.
* Modal/interactive content must live in the HTML and stay crawlable, not JS-injected.
* No tracking, analytics or third-party SEO scripts (see §7).
