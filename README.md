# SlideOut — Policies & Support

Public-facing policy and support pages for SlideOut, served via GitHub Pages.

## Live URLs (after enabling Pages)

- **Home:** https://bosie-tech.github.io/slideout-policies/
- **Privacy Policy:** https://bosie-tech.github.io/slideout-policies/privacy.html
- **Support:** https://bosie-tech.github.io/slideout-policies/support.html

App Store Connect → SlideOut → App Information:
- Privacy Policy URL → `https://bosie-tech.github.io/slideout-policies/privacy.html`
- Support URL → `https://bosie-tech.github.io/slideout-policies/support.html`

## Local preview

```bash
cd ~/slideout-policies
python3 -m http.server 8000
# open http://localhost:8000
```

## Editing

Plain HTML + a single `style.css`. No build step. Edit the .html files directly and push.

## Updating the privacy effective date

When the policy changes materially, update both the "Effective" and "Last Updated" dates near the top of `privacy.html`.
