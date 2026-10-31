# Yoga Awareness & Practice — CSP Website

A responsive static website designed for GitHub Pages.

## Files
- `index.html` — page content and sections
- `style.css` — responsive visual design
- `script.js` — mobile navigation
- `images/yoga-sunrise-banner.png` — generated homepage hero image (if included)

## Preview locally
Open `index.html` in a web browser.

## Add your project photographs
The gallery currently contains placeholders. Add your own images to the `images/` folder and update the gallery in `index.html`. For example, replace a placeholder `<div class="photo-slot">...</div>` with:
```html
<div class="photo-slot">
  <img src="images/photo-1.jpg" alt="Yoga awareness session">
  <strong>Yoga awareness session</strong>
</div>
```
Then add this CSS rule to `style.css`:
```css
.photo-slot img { width:100%; height:100%; object-fit:cover; }
```
Use only photographs you have permission to publish.

## Publish on GitHub Pages
1. Create a **public** GitHub repository, for example `yoga-awareness`.
2. Upload the contents of this ZIP (upload the files and `images` folder, not the ZIP itself).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish. Your site URL will look like:
   `https://YOUR-USERNAME.github.io/yoga-awareness/`

## Personalize before submission
- Confirm student and college details.
- Add actual dates, activity descriptions, observations and outcomes to the weekly section.
- Replace the gallery placeholders with your original project photos.
- Verify that each listed reference is suitable for your final report.

## Accuracy note
The eight-week section is an editable suggested framework. It does not claim that activities were completed on particular dates. Update it to reflect your actual fieldwork.
