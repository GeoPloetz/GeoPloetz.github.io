# Chris Ploetz Academic Website Update

This version includes:
- Chris Ploetz without middle initial
- Professional slate/navy + muted burnt-orange palette
- CAVE Lab as its own tab
- CV as a readable webpage rather than direct download only
- Fieldwork categories: Belize, Guatemala, Honduras, Community Engagement
- Aligned homepage feature cards

## Upload instructions

Upload all files and the assets folder to the root of the GeoPloetz.github.io repository.
Keep the existing CNAME file in GitHub.

## Add homepage image

Place a wide image at:

assets/homepage.jpg

Then replace the hero placeholder in index.html with:

<section class="hero has-image">
  <img src="assets/homepage.jpg" alt="Belize landscape or fieldwork image">
</section>

## Add headshot

Place a square/portrait image at:

assets/headshot.jpg

Then replace the headshot placeholder in index.html with:

<img src="assets/headshot.jpg" alt="Chris Ploetz">