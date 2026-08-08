# How to publish a blog post

Only people with access to this GitHub repository (you) can post. No other
logins exist. Every post is a simple text file — GitHub rebuilds the site
automatically each time you add one.

## Publish a new post (from any browser)

1. Go to **github.com/Shadow-Squirrel/direwolf-website**
2. Click the **`_posts`** folder
3. Click **Add file → Create new file**
4. Name the file like this (the date prefix is required):

   ```
   2026-09-15-your-post-title-here.md
   ```

   Lowercase, hyphens between words, ends in `.md`. The words after the date
   become the post's web address.

5. Paste this at the top of the file, then write your post below it:

   ```
   ---
   title: "Your Post Title Here"
   description: "One sentence shown on the blog page and in Google results."
   ---

   Your first paragraph starts here...
   ```

6. Click **Commit changes** (green button, top right), then **Commit changes**
   again in the popup.
7. Wait 5–10 minutes. Your post appears at **direwolfcybersecurity.com/blog**.

## Writing formatting (Markdown cheat sheet)

| You type                          | You get                 |
|-----------------------------------|-------------------------|
| `## Heading`                      | Section heading         |
| `### Smaller heading`             | Sub-heading             |
| `**bold text**`                   | **bold text**           |
| `- item` (one per line)           | Bullet list             |
| `1. item` (one per line)          | Numbered list           |
| `> quote`                         | Highlighted callout box |
| `[link text](https://url.com)`    | A link                  |

Blank line between paragraphs. That's all you need.

## Edit or delete a post

- **Edit:** open the file in `_posts` on GitHub, click the pencil icon, make
  changes, Commit changes.
- **Delete:** open the file, click the trash-can icon (under the `...` menu),
  Commit changes. The post disappears from the site after the rebuild.

## Rules of thumb

- The date in the filename is the publish date shown on the post.
- Keep the `title:` and `description:` lines inside the `---` fences — the
  site uses them for the blog page, browser tab, and search engines.
- After committing, the site takes up to ~10 minutes to update (build + cache).
