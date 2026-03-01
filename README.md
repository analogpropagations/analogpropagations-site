# Analog Propagations

A public commonplace book. Things that earn their place — objects, music, food, writing. Discovered slowly. Signal over noise.

**analogpropagations.com** · [@analogpropagations on Bluesky](https://bsky.app/profile/analogpropagations.bsky.social)

---

## Structure

Single file site. Everything lives in `index.html`. No build tools, no dependencies, no CMS. To update the site, edit the file and push to GitHub. Netlify deploys automatically.

---

## Adding an Entry

Copy this block and paste it before the closing `</div>` of the `.entries` div. Fill in the fields and delete the comments.

```html
<div class="entry">
  <div class="entry-meta">
    <span class="entry-category">Listening</span> <!-- Listening / Reading / Places / Objects -->
    <span class="entry-date">Mar 2026</span>
  </div>
  <div>
    <div class="entry-title"><a href="URL" target="_blank">Title of the thing</a></div>
    <p class="entry-body">Two or three paragraphs. What it is, why it earned its place.
    No ratings, no rankings, no hype. Just what's true about it.</p>
    <a href="URL" target="_blank" class="entry-link">Source or buy link →</a>
  </div>
</div>
```

### Notes on writing entries
- Keep it to 2-3 paragraphs max
- Write about why it earned its place, not what it is
- One link at the bottom — the most useful one
- Affiliate links are fine, just make sure it's something you actually own or have experienced

---

## Categories

| Category | What goes here |
|---|---|
| **Listening** | Records, radio stations, podcasts, anything heard |
| **Reading** | Books, essays, longform — things worth finishing |
| **Places** | Locations, moments, photography — anywhere worth going or remembering |
| **Objects** | Things owned and used — gear, tools, notebooks, pens |

---

## Design Notes

- Font stack: Abril Fatface (masthead) · Lora (body) · IBM Plex Mono (labels/meta)
- Colors: Night black `#090b0f` · Cream `#f5f0e8` · Amber `#e8a020`
- Hero fades from dark to cream — no hard edge between header and content
- Tower SVG is pure CSS, no image files needed
- Fully static — no JavaScript frameworks, no external dependencies beyond Google Fonts

---

## Deployment

- **Repo:** GitHub (`analogpropagations-site`)
- **Host:** Netlify (auto-deploys on push to main)
- **Domain:** Registered via Namecheap with privacy enabled
- **Bluesky:** Claim handle, eventually set domain as identifier

---

*No agenda, no algorithm, no schedule, no sponsor.*
