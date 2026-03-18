# Attendance Risk Report - GitHub Pages version

This package is ready to publish on GitHub Pages.

## Files
- `index.html` — the live interactive report page

## Publish to GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. In GitHub, open **Settings**.
4. Open **Pages**.
5. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
6. Save.
7. GitHub will give you a public site URL.

## Update the report later
Open `index.html` and update these values inside the `report` object:

```js
const report = {
  baseline: 434,
  current: 269,
  newRisks: 29,
  existingRisks: 240,
  improving: 120,
  declining: 87,
  noChange: 33
};
```

Then commit the changes to GitHub and your live page will update.

## Suggested repo name
`attendance-risk-report`

## Optional customizations
- Replace the title text
- Add your logo
- Add more weeks to the trend chart
- Link this page from SharePoint or Teams
