# ExplainQuest development blog

A standalone static blog for Robert Dresner. Open index.html in a browser to preview it. No installation, build step, external font, API key, or database is needed for the blog itself.

## Publish on GitHub Pages

1. Create a public GitHub repository, such as explainquest-blog.
2. Upload index.html to the repository root. You can also upload this README and .nojekyll.
3. Open Settings > Pages.
4. Select Deploy from a branch, main, and / (root), then Save.
5. Wait for the deployment and use the link shown in Settings > Pages.

The resulting address normally follows https://YOUR-USERNAME.github.io/explainquest-blog/.
Upload the files inside the ZIP, not the ZIP itself. If an index.html already exists in your repository, replace it with this file.

## Personalize before submission

The initial entry is a draft dated November 3, 2026. Review it so it reflects your own plans and the date you want to publish. The role remains Backend / Database until your assignment is confirmed. The technology stack is explicitly marked as proposed, based on the pitch. No completed implementation work is claimed.

## Add a weekly post

Open index.html and find ADD NEW POSTS HERE. Copy the existing article and place the new one above it. Give each post a unique id, such as week-02. Change the week, date, title, and text. Use YYYY-MM-DD in the datetime attribute. Update the entry count, the Read the first entry link and its label if you want it to point to the latest entry, and the Next in the journal text.

A useful weekly entry describes what you worked on, one technical decision, a problem or lesson, how you checked the result, and your next step. Include only work you actually completed. Commit the changes in GitHub to update the live site.

The site has anchor navigation and a native expandable Next steps section. All article content remains in the HTML for easy editing and access without JavaScript.
