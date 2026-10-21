# Hussnain Training Academy — Assignment 2

**Course:** Web Technologies, BSCS Semester 5  
**Student:** Muhammad Shoaib  
**Roll number:** Fall-24/BSCS/289 (confirm before submission)  
**Section:** I (confirm before submission)

## Run the project
Extract the ZIP and open `index.html`. Keep the media directory beside the HTML files. No installation, database, or account is needed.

## Short explanation (200–300 words)
CSS (Cascading Style Sheets) controls how HTML content looks. It defines colours, typography, spacing, borders, and layout. Separating presentation from content improves readability, makes designs consistent, and reduces repeated maintenance. This website uses a navy and teal palette with readable Arial text.

In the rule `input[type="email"] { background: #eefaf7; }`, `input[type="email"]` is the selector, `background` is the property, and `#eefaf7` is its value. It visibly highlights the email field. Comments in the styles identify element, class, ID, and attribute selectors. Each matches actual content.

Inline CSS appears directly in an element’s style attribute. The home page uses this method exclusively. Embedded CSS consists of rules inside a style element in the document head; the information page demonstrates it. External CSS lives in a separate file linked from HTML. The registration page links to style.css, making its presentation easier to maintain and reuse.

CSS1 introduced foundational font, colour, and spacing features. CSS2 expanded layout, positioning, and media capabilities; CSS2.1 clarified and corrected interoperable behaviour. Modern CSS develops through separate modules, including flexible layout, selectors, and responsive styling, rather than one single version.

Browser support matters because form controls, date pickers, fonts, and media playback can differ. Chromium and Firefox are the intended testing browsers; their completed results must be recorded below. No two-browser testing is claimed without evidence.

The article element is semantic because it identifies a self-contained course description. The div with class table-wrap is non-semantic: it groups the table for horizontal scrolling without assigning content meaning.

## Requirement map
- `index.html`: inline CSS only; header, nav, main, two sections, image, four-course list, footer.
- `information.html`: embedded CSS only; article, aside, four-row/four-column table, local audio and video.
- `registration.html`: external CSS only; every requested input, labelled controls, fieldsets, validation, focus and hover states.
- `style.css`: external styles with selector comments.
- `media/`: original classroom illustration, original instrumental WAV, original silent course-preview MP4. No external assets or licences required.
- Small inline JavaScript handles local success feedback after native validation. It sends and stores no form data and provides no login or server processing.

## Testing checklist — complete before submission
1. Open each page and check all three navigation links.
2. Play the WAV and MP4 using their controls; confirm the image loads.
3. Submit an empty form: required fields must prevent submission.
4. Enter `wrong-email` with other required fields filled: email validation must prevent submission.
5. Enter a seven-character password: minimum length must prevent submission (type it in the browser).
6. Try age 15, 66, then 20: out-of-range ages must be rejected.
7. Confirm only one study mode is selectable and interests remain independent.
8. Complete a valid dummy form: the local success message should appear without navigation. Reset must clear the form and message.
9. Paste or type long comments: the textarea must enforce 500 characters.
10. Repeat in Chromium/Chrome and Firefox; record versions, outcomes, and differences. Native date controls and validation wording may vary.

| Browser | Version | Result | Observed differences |
|---|---|---|---|
| Chromium / Chrome | Not yet recorded | Manual test pending | Record actual observations |
| Firefox | Not yet recorded | Manual test pending | Record actual observations |

## W3C validation evidence — pending
Visit https://validator.w3.org/ and use **File Upload** for each HTML file. Correct any errors and review warnings. Save genuine results to:
- `screenshots/index-validation.png`
- `screenshots/information-validation.png`
- `screenshots/registration-validation.png`

No validator screenshots are fabricated or included as completed evidence.

## GitHub and GitHub Pages submission
Create an empty GitHub repository, then run these commands from the extracted project folder (replace YOUR_USERNAME first):

```bash
git init
git add .
git commit -m "Add three-page training academy assignment"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/training-academy.git
git push -u origin main
```

In the GitHub repository, open **Settings → Pages**, choose deployment from a branch, select `main` and `/ (root)`, then save. Wait for GitHub to show the live URL. Open it and check media and navigation again.

Repository URL: add after publishing.  
Live website URL: add after publishing.

Enter your confirmed name, roll number, section, repository URL, and live URL in the instructor’s shared Google Sheet. GitHub publication and the Sheet entry are not yet completed.
