# The Ultimate GK Challenge

A responsive, open-answer General Knowledge quiz featuring 50 questions across Sri Lankan and World History, Politics and Literature. Built with HTML, CSS and vanilla JavaScript; no server or database is required.

## Features

- 50 questions: 25 Sri Lankan and 25 World questions.
- Six category/region combinations, with the requested 9/9/8/8/8/8 distribution.
- Open-ended typed answers (no multiple-choice options).
- Case-insensitive answer matching, whitespace/punctuation normalization and explicit accepted aliases.
- Immediate feedback, correct answer and short explanation after submission.
- One point per correct answer, progress statistics and final performance rating.
- Full challenge or one-category challenge, randomized question order, review screen and shareable result text.
- Current progress saved in the browser's `localStorage` and restored after refresh.
- Responsive layout for desktop, tablet and mobile.

## Files

```text
gk-quiz/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Run locally

You can open `index.html` directly in a modern browser. For a local web server, open the folder in VS Code and use the Live Server extension. No build step is required.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `gk-quiz`.
2. Upload all four files to the repository's root directory (not inside an extra nested folder).
3. Open the repository's **Settings** tab.
4. Select **Pages** from the sidebar.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/(root)` folder, then save.
7. Wait for GitHub Pages to deploy. Your site will be available at:

   `https://YOUR-GITHUB-USERNAME.github.io/gk-quiz/`

For a repository named `YOUR-GITHUB-USERNAME.github.io`, the site is published at the root URL instead.

Official guide: <https://docs.github.com/en/pages>

## Notes and limitations

- The quiz runs entirely in the participant's browser. Scores and saved progress are local to that browser/device; there is no shared leaderboard or central score database.
- Answer checking uses normalized exact matches against each answer and its accepted aliases. It intentionally does not use broad fuzzy matching, which could award marks for unrelated answers. Add further accepted variants in the relevant question's `aliases` array in `script.js` if needed.
- Google Fonts are loaded from Google Fonts when internet access is available. The site remains functional if the font service is unavailable, using local fallback fonts.
- This project contains educational general-knowledge material. Review question wording and accepted aliases before using it in a formal competition.
"# EPIC-Quiz-2" 
