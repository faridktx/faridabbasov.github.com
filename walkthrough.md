# Academic Webpage Walkthrough

This guide documents the setup of your professional academic webpage using the `academicpages` template.

## Verified Changes
- **Project Initialized**: Cloned the `academicpages` template.
- **Cleanup**: Removed unused pages (`portfolio`, `posts`, `talks`, `teaching`) to keep the site clean.
- **Resume Integrated**: Copied `FaridAbbasovResume2026.pdf` to the `files/` directory and linked it on the main page.
- **Configuration**: Updated `_config.yml` with your name "Farid Abbasov", placeholders for your specific details, and enabled Google Analytics.
- **Main Page**: Customized `_pages/about.md` to include your introduction, education, and required links.

## Next Steps for You

### 1. Push to GitHub
I have already committed the changes. You just need to push them.
Run this command in your terminal (I cannot do this for you as it requires your password/token):
```bash
cd /Users/faridabbasov/.gemini/antigravity/scratch/academic-page
git push -u origin master
```
(Note: You might need to use `main` instead of `master` if your new repo uses `main` as default. If `master` fails, try `git push -u origin main` or check your branch name with `git branch`).

### 2. Add Your Profile Picture
1.  Find a professional photo of yourself.
2.  Name it `profile.png` (or change the name in `_config.yml`).
3.  Place it in the `images/` folder of the project.

### 3. Configure Google Analytics
**Done!** I have already configured this for you with ID `G-GQCN7644QR`. You don't need to do anything here.

### 4. Final Polish
-   **Education**: Update `_pages/about.md` with your previous degrees.
-   **Social Links**: Open `_config.yml` and add your username to the `linkedin` field (or any others you want to show).
-   **Research Interests**: Add your specific interests to `_pages/about.md`.

## Deliverables for Submission

Here is the information you need to submit:

1.  **URL of the published page**:
    `https://faridktx.github.io/faridabbasov.github.com/`
    *(Note: It may take 1-2 minutes to appear after you push).*

2.  **URL of the GitHub repository**:
    `https://github.com/faridktx/faridabbasov.github.com`

3.  **Google Analytics Screenshot**:
    -   Log in to [Google Analytics](https://analytics.google.com/).
    -   Click on "Reports" -> "Realtime" to see immediate activity (open your site in a new tab to trigger it).
    -   For the assignment ("past week"), you might just see today's data since it's new. Take a screenshot of the main dashboard showing some activity.
