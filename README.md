# x-media

Public media hosting for [@mahdi](https://x.com/mahdi) X posts. Buffer pulls images from the raw GitHub URLs in this repo when scheduling posts with screenshots.

## Layout

Put files under:

```
screenshots/YYYY-MM-DD/filename.png
```

Example: `screenshots/2026-10-08/staging-is-a-rumour.png`

## Buffer / raw URL

Buffer needs a **direct, publicly downloadable** file URL — not the GitHub blob page.

Pattern:

```
https://raw.githubusercontent.com/mahdi/x-media/main/screenshots/YYYY-MM-DD/filename.png
```

## Rules

- Do **not** put secrets, credentials, private screenshots, or anything that should not be public.
- Keep files small: under ~2MB each.
- Preferred formats: PNG, JPG, WebP.
- Prefer clear, cropped screenshots that read well in the X timeline.
