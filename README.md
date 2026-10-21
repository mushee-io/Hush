# 디자이너의 수정 지옥 (Designer's Revision Run)

A 9:16 arcade runner. Jump over client revisions, grab SAVE (+25) and CMD + Z (+100), clear revisions (+50), and survive the deadline with three hearts.

## Controls
- Space, Up arrow, W, or tap: jump (hold for a higher jump)
- P or Esc: pause

## Deploy to Vercel
Plain static site, no build step.

**Option 1: drag and drop**
1. Go to vercel.com/new and choose to deploy without Git (or use the Vercel dashboard's upload).
2. Drop this folder in. Framework preset: Other. No build command, no output directory.

**Option 2: CLI**
```
npm i -g vercel
cd revision-run
vercel        # preview
vercel --prod # production
```

**Option 3: GitHub**
Push this folder to a repo, import it at vercel.com/new, keep Framework preset as Other and leave build settings empty.

## Files
- `index.html`: the whole game (sprites embedded, fonts from Google Fonts)
- `favicon.svg`: lime pixel heart icon
- `vercel.json`: clean URLs and basic headers
