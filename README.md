# mikemurray.dev

Personal blog built with [Hugo](https://gohugo.io/).

## Getting Started

1. [Install Hugo](https://gohugo.io/installation/)
2. Run the dev server:
   ```bash
   cd mmdev
   hugo server -D
   ```
3. Open [http://localhost:1313](http://localhost:1313)

The `-D` flag includes draft posts.

## Writing a New Post

```bash
cd mmdev
hugo new posts/my-new-post.md
```

This creates `content/posts/my-new-post.md` with front matter. Posts start as drafts — set `draft = false` when ready to publish.

The URL slug is derived from the filename (e.g. `my-new-post.md` becomes `/my-new-post/`).

## Analytics

Page views are tracked with [GoatCounter](https://www.goatcounter.com/). The tracking script is in `mmdev/layouts/_default/baseof.html` and applies to all pages.

Dashboard: [mikemurraydev.goatcounter.com](https://mikemurraydev.goatcounter.com)
