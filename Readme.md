# KeysPanel Blog

Every post in this repo appears on https://keyspanel.shop/blog automatically. No website rebuild is needed. New or edited posts appear within about 5 minutes (instantly if the webhook is set up).

## Add a post

1. Create a folder: `posts/your-post-slug/`
   - The folder name becomes the link: `keyspanel.shop/blog/your-post-slug`
   - Use only lowercase letters, numbers and dashes.
2. Inside it, create `index.md` (copy `posts/welcome-to-the-keyspanel-blog/index.md` as a start).
3. Put that post's images and videos in the same folder.
4. Commit. Done.

## Post settings (top of index.md)

```yaml
---
title: How Digital Game Keys Work
description: One or two sentences. Shown on cards and in Google.
date: 2026-11-27
updated: 2026-12-02
author: KeysPanel
category: Guides
tags: [steam, beginners]
cover: ./cover.jpg
coverStyle: cover
featured: true
trending: true
pinned: 1
draft: false
---
```

| Setting | What it does |
|---|---|
| `title` | Post title (required) |
| `description` | Summary for cards, link previews and Google |
| `date` | Publish date, `YYYY-MM-DD`. A future date schedules the post: it stays hidden until that day |
| `updated` | Optional "Updated on" date |
| `author` | Defaults to KeysPanel |
| `category` | Used for the filter on the blog page |
| `tags` | `[one, two]` |
| `cover` | `./cover.jpg` from the post folder, or a full `https://` link |
| `coverStyle` | `cover` (fills the box, default) or `contain` (whole image visible, good for logos) |
| `featured` | `true` = big card at the top of the blog page, and shown on the home page |
| `trending` | `true` = "Trending" badge, and shown in the home page blog section |
| `pinned` | Number. Higher shows first on the home page among featured/trending posts |
| `draft` | `true` = hidden from the website |

The home page shows 3 posts: featured and trending posts first, then the latest.

## Writing

Normal Markdown works: headings (`##`), **bold**, *italic*, lists, links, tables, `code`, quotes.

The post title is already shown at the top, so start sections with `##`.

### Images

```md
![Alt text](./screenshot.png)
![Alt text](./screenshot.png "A caption under the image")
![Alt text](./screenshot.png "wide | Caption")
![Alt text](https://example.com/image.png)
```

Styles go before the `|` in the quotes, and can be combined (`"wide rounded | Caption"`):

| Style | Look |
|---|---|
| `wide` | Wider than the text column |
| `full` | Full screen width |
| `small` | Small and centred |
| `left` / `right` | Floats beside the text on desktop |
| `rounded` | Extra round corners |
| `plain` | No border or rounding |

### Gallery

```md
:::gallery
![One](./1.jpg "Caption one")
![Two](./2.jpg)
![Three](./3.jpg)
:::
```

### Videos and embeds

Each goes on its own line:

```md
@[youtube](https://youtu.be/VIDEO_ID)
@[youtube](https://www.youtube.com/watch?v=VIDEO_ID "Optional caption")
@[vimeo](https://vimeo.com/123456)
@[video](./demo.mp4)
@[video](https://example.com/clip.mp4)
@[embed](https://any-https-page-that-allows-embedding)
```

A YouTube, Vimeo or `.mp4` link alone on its own line is embedded automatically too.

Videos uploaded to this repo should be under 20 MB. For bigger videos, use YouTube or a direct link.

### Button

```md
@[button](/store "Browse the store")
@[button](https://t.me/yourchannel "Join our Telegram")
```

### Callout boxes

```md
> [!TIP]
> Helpful advice.

> [!NOTE]
> Extra information.

> [!IMPORTANT]
> Key point.

> [!WARNING]
> Be careful.

> [!CAUTION]
> Risky action.
```

## Rules

- Raw HTML is not rendered (shown as text) for safety. Use the features above instead.
- Keep image files reasonably small (under 1 MB is ideal). Use `.jpg` or `.webp` for photos.
