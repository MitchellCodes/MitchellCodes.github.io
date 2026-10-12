# Build log: Artifact 1 portfolio

## Chat AI used
- Claude (free web chat). I did not switch tools.

## Entry 1: Understanding the assignment and picking hosting
- **What I asked:** For a summary of the Artifact 1 instructions, then for free hosting options that look professional to employers.
- **What I got:** A scannable summary, and a comparison of GitHub Pages, Netlify, Vercel, and Cloudflare Pages. It recommended GitHub Pages because it keeps the code, log, and live site together.
- **What I changed or fixed:** Chose GitHub Pages.

## Entry 2: First version of the site
- **What I asked:** To generate the whole site with filler text for the About Me section and the cards.
- **What I got:** A single `index.html` (HTML and CSS only) with an About Me section, a finished Artifact 1 card, four placeholder cards, and a starter `NOTES.md`.
- **What I changed or fixed:** Nothing yet. I uploaded it to GitHub.

## Entry 3: Deployment problem
- **What I asked:** Why GitHub Pages only showed the README.
- **What I got:** A checklist of likely causes: `index.html` inside a subfolder, a wrong filename, Pages pointed at the wrong branch or folder, or the deploy not finished.
- **What I changed or fixed:** The cause was the subfolder. I had dragged the downloaded folder into the repo, so `index.html` ended up inside a subfolder instead of at the top level. I moved `index.html` and `NOTES.md` to the top level of the repo, and the site loaded.

## Entry 4: Choosing a look
- **What I asked:** About theme switchers and other looks, then for a side-by-side comparison.
- **What I got:** A comparison page with four directions: Editorial, Terminal, Playful, and Dashboard.
- **What I changed or fixed:** I liked Playful, but asked for a more professional version. I then asked for full-width cards, no color-coded dots, and image space on each card. After seeing it, I asked for a version without the image space and picked that one.

## Entry 5: Card design
- **What I asked:** To move the "Idea" tag to the same spot as "Built," how the purple on Artifact 1 was applied, and what a finished card would look like.
- **What I got:** An explanation that the purple was styling on that one card, not tied to the tag. I chose to keep only Artifact 1 purple, with other built cards staying white.
- **What I changed or fixed:** Idea cards are grayed out. I asked for the reflection back on every card, then asked to hide it on idea cards until they are built.

## Entry 6: Dark mode and polish
- **What I asked:** For dark mode, softer dark-mode text, more contrast between idea and built cards, and a recessed effect on idea cards and a raised effect on built cards.
- **What I got:** A light/dark toggle, comparison pages for shadow strength and glow, and updates to the real file.
- **What I changed or fixed:** Artifact 1 looked wrong at first. The raised effect added a white line along its top edge, and I told Claude it didn't look properly raised. It gave Artifact 1 its own shadow. I decided against the glow in dark mode. I then asked for a darker purple in both modes and a slightly lighter border in dark mode. When I first asked for a darker purple, Claude assumed I meant dark mode only, so I asked for light mode too.

## Entry 7: Type tags and filtering
- **What I asked:** For a tag on each card (website, bot, game, and so on), whether cards could be sorted or filtered by it, and previews of the options.
- **What I got:** Working previews of filter buttons and clickable tags, both with a sort dropdown.
- **What I changed or fixed:** I chose filter buttons and no sorting for now. I asked to hide the tags on idea cards.

## Entry 8: Final content
- **What I asked:** How to make the GitHub Pages URL as clean as possible, then to set Artifacts 2-5 to "TBD," and to put in my name and links.
- **What I got:** Advice to name the repo `username.github.io`, TBD placeholder cards, and my real name and links.
- **What I changed or fixed:** Named my repo `MitchellCodes.github.io` so the site address is `mitchellcodes.github.io`.

## Entry 9: Final content changes
- **What I asked:** To put my own ideas and wording on the site: the language learning flashcard game for Artifact 2 (with scoring and statistic tracking), the syllabus planner for Artifact 3 (with a calendar display and due-date notifications), new card titles for Artifacts 1-3, a Game tag on Artifact 2, an Application tag on Artifact 3, a new About line, a new Artifact 1 description, and my reflection.
- **What I got:** An updated `index.html` after each change. Artifacts 4 and 5 are still "TBD."
- **What I changed or fixed:** At first Claude read my "add this to artifact 2 and artifact 3" request as tags. I wanted the phrases in the card titles, so I asked it to move them there. Claude had also assumed I meant tags when I asked for Application and Game, which matched what I wanted.

## What I learned
- Building the site went well. Claude got mostly everything right on the first attempt. The only corrections I needed to make were from it assuming things I was not clear enough about.
