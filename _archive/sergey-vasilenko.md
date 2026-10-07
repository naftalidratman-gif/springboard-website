# Sergey Vasilenko — removed from the Team page (archived)

Removed from the "Advisory Board" section of /team on 2026-10-07 at the owner's request.
To restore him, paste the card below back into `team/index.html` inside
`<div class="advisory-grid">` (he was second, between Tal Malca Salhuv and Niv Amir),
and switch the advisory grid back to 4 columns (see note at the bottom).

- **Name:** Sergey Vasilenko
- **Title:** Strategic Advisor, Healthtech
- **LinkedIn:** https://www.linkedin.com/in/sergey-vasilenko/
- **Photo:** `sergey-vasilenko.jpg` in this folder (backup copy; the page used https://i.postimg.cc/FzZYsqkS/Sergey-cropped-v2.jpg)

This folder is blocked from public view by a rule in `/_redirects`.

## Card HTML (exactly as it appeared on the site)

```html
            <article data-reveal="" data-reveal-delay="100" style="min-width: 0; background: #FCFBF7; border: 1px solid #E0D8C7; border-top: 3px solid #C9A24A; display: flex; flex-direction: column;">
              <div role="img" aria-label="Sergey Vasilenko" style="aspect-ratio: 4/5; width: 100%; background-image: url('https://i.postimg.cc/FzZYsqkS/Sergey-cropped-v2.jpg'); background-size: cover; background-position: center top; background-color: #0B2038;"></div>
              <div style="padding: clamp(22px, 2.4vw, 30px); display: grid; grid-template-rows: 36px 52px 32px; align-content: start; flex: 1;">
                <h3 style="font-family: 'Newsreader', serif; font-weight: 600; font-size: clamp(20px, 1.9vw, 25px); line-height: 1.08; color: #0B2038; margin: 0; letter-spacing: -.3px;">Sergey Vasilenko</h3>
                <p style="font-size: 12px; line-height: 1.45; letter-spacing: 1.5px; font-weight: 700; text-transform: uppercase; color: #B08D38; margin: 0;">Strategic Advisor, Healthtech</p>
                <div style="display: flex; align-items: flex-start; align-content: flex-start; gap: 6px 10px; margin: 0; flex-wrap: wrap;">
                  <a href="https://www.linkedin.com/in/sergey-vasilenko/" target="_blank" rel="noopener" style="font-size: 12.5px; font-weight: 600; color: #0B2038; text-decoration: none; border-bottom: 1px solid #C9A24A; padding-bottom: 2px;">LinkedIn →</a>
                </div>
              </div>
            </article>
```

## Grid note

With 4 advisors the `.advisory-grid` rule in `team/index.html` was:

```css
.advisory-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: clamp(20px, 2.4vw, 30px);
  align-items: stretch;
}
```
