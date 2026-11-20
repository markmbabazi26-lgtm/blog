# ClassBlog

A responsive class community website built with HTML, CSS and vanilla JavaScript for static hosting such as GitHub Pages.

## Pages
- `index.html`: homepage, seven-member directory and member search.
- Seven original member profile pages: retained with their content and photographs.
- `blog.html`: searchable article list.
- `article.html?post=<id>`: individual article page.
- `gallery.html`: gallery of the existing member photographs.

## Publish a new article
The site is static and does not include a server-side login or database. To publish an article:

1. Open `posts.json` on GitHub and choose **Edit**.
2. Add an object to the JSON array, separated from the previous object by a comma:

```json
{
  "id": "my-unique-article-id",
  "title": "Your article title",
  "category": "Campus life",
  "date": "2026-11-20",
  "author": "Your name",
  "excerpt": "A short summary for the article list.",
  "paragraphs": [
    "Your first paragraph.",
    "Your next paragraph."
  ]
}
```

3. Give every article a unique `id`, use the date format `YYYY-MM-DD`, and check the JSON commas and quotation marks.
4. Commit your edit. The new story will appear automatically on the Stories page.

Use plain text in the paragraphs; the site escapes HTML for safety.

## Features
- Responsive design and mobile navigation
- Dark/light theme toggle saved in the visitor's browser
- Searchable member directory and article index
- Shared stylesheet and accessible labels
- Original member profiles and photographs preserved

## GitHub Pages
To publish, open repository **Settings → Pages** and select the branch and folder you want GitHub Pages to serve. See [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).
