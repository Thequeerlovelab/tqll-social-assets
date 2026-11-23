# tqll-social-assets

Public image hosting for The Queer Love Lab's social posts. Buffer can only attach images from a
public, direct link, so approved carousel and post images live here.

- **Not connected to Netlify:** pushing here never triggers a website deploy or uses Netlify credits.
- **No PRs:** images are pushed straight to `main`, and only after David's final "go" (Gate 3 in the
  weekly content skill). Nothing unapproved is ever pushed here.
- **Everything here is public.** Only finished, approved post images belong here: no drafts, client
  material, personal data or fonts.

## Structure

```
<YYYY-MM-DD>/<slug>/TQLL_<IG|TT>_<kind>_<slug>_<theme>_NN_vX.png
```

`IG` = 1080x1350 feed (Instagram, Facebook), `TT` = 1080x1920 (TikTok).

## Link format for Buffer

```
https://raw.githubusercontent.com/Thequeerlovelab/tqll-social-assets/main/<YYYY-MM-DD>/<slug>/<file>
```

Check every link returns `200` and `image/png` before scheduling.

## Archive

Each published piece is also archived in Google Drive:
`TQLL - Brand and Marketing/Social/Outputs/<YYYY-MM-DD> <piece>/` (zip of the images plus a PDF preview).
The render kit lives in the private `qll-website` repo under `brand/`.
