
  ![on-push](../../actions/workflows/on-push.yaml/badge.svg)
  ![on-pull-request](../../actions/workflows/on-pull-request.yaml/badge.svg)
  ![on-schedule](../../actions/workflows/on-schedule.yaml/badge.svg)

  # LAMA Website

  Visit **[jatinchowdhury18.github.io/lab-website](https://jatinchowdhury18.github.io/lab-website)** 🚀

  _Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_

## Running locally:

Run on localhost
```
bundle exec jekyll serve --open-url --livereload --trace
```

Generate citations:
```
source ./.venv/bin/activate && python3 ./_cite/cite.py
```

---

TODO:
- Mark/Jatin
  - Repository
  - Hosting through MIT
  - Content
    - Lab logo
    - Image to use for "Research" section
    - Image to use for "Projects" section
    - Team image
    - Contact info
    - Page descriptions:
      - Home
      - Research
      - Projects
      - Team
      - Lab equipment page
  - Features
    - Pick a few projects and research papers to feature
- Everyone
  - Personal page
    - Bio (2-3 paragraphs)
    - Headshot
    - Personal links (GitHub, Google Scholar, personal website, etc.)
  - Projects: Description, links, 1-2 photos
  - Papers
    - Title
    - Authors
    - Link to paper (if available)
    - Links to supporting material (website, GitHub page, etc)
    - 1 image (optional)
