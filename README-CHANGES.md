# Website update — notes for Umair

This is a summary of the changes made to the site, and everything you need to
do to get them live.

## What changed

### Content
- **Hero, About, tagline** rewritten to lead with Data Scientist positioning, with PhD framed as background rather than centerpiece.
- **New "Currently" strip** below the hero: three quick cards showing what you're doing now (Data Scientist role, physics-informed ML focus, location).
- **New "Journey" section** with a visual career timeline (data-driven from `_data/timeline.yml`).
- **Work Experience updated** with expanded bullets — kept **general** (no specific ChampionX / SLB project names), safe to publish.
- **New "Conferences" section** with an interactive world map (Leaflet.js) plus a list. Pins for Vancouver, Barcelona, Guwahati, Bengaluru.
- **New "Gallery" section** — a photo gallery block with a lightbox. Empty state renders now; add photos when ready.
- **PhD Research, Publications, Teaching, Contact** — kept largely unchanged, just relocated in the flow.

### Visual / UX
- **Dark mode toggle** — moon/sun icon in the sidebar (and mobile header). Respects OS preference on first load, then remembers your choice in `localStorage`.
- **Extra CSS variables** for dark-theme palette. Everything reacts smoothly.
- **New styled components**: `.now-strip`, `.journey`, `.conf-grid` / `.conf-map`, `.gallery`, `.lightbox`, `.theme-toggle`.

### Structure & data
- New `_data/timeline.yml` — edit this to change the Journey items.
- New `_data/conferences.yml` — edit this to add/edit conference pins on the map.
- New `_data/gallery.yml` — add photo entries here to populate the gallery.
- Nav updated in `_layouts/default.html` to include the new sections.

## What you need to do

### 1. Install Git (if not already)
- Grab it from https://git-scm.com/download/win, accept defaults.

### 2. Clone the repo (fresh, using Git)
```powershell
cd "$HOME\Documents"
git clone https://github.com/umairhussaincmm/umairhussaincmm.github.io.git
```

### 3. Copy over the updated files
Copy everything from `About_me\website\site\` into your fresh clone, overwriting the old files. Or, if you'd rather cherry-pick, the files that changed are:
- `_config.yml`
- `_layouts/default.html`
- `index.markdown`
- `assets/css/main.scss`
- new: `_data/timeline.yml`
- new: `_data/conferences.yml`
- new: `_data/gallery.yml`
- new: `images/gallery/` (empty folder, will hold your photos)

### 4. Review the diff
```powershell
cd umairhussaincmm.github.io
git status
git diff
```

### 5. Push
```powershell
git add .
git commit -m "Reposition site around Data Scientist role; add Journey, Conferences map, Gallery, dark mode"
git push origin master
```

GitHub Pages will rebuild automatically in ~30 seconds. Refresh `https://umairhussaincmm.github.io/` and you're live.

## How to add photos to the gallery

1. Drop images (JPG/PNG) into `images/gallery/` — recommend ~1200 px on the long side, compressed.
2. Add an entry per photo to `_data/gallery.yml`:
    ```yaml
    - image: convocation-1.jpg
      caption: PhD Convocation, IIT Madras
      location: Chennai, India
      date: 2025
    ```
3. Commit and push. That's it. The "coming soon" empty state auto-disappears when the file has entries.

**Suggested photos to add:**
- PhD convocation
- Conference travel shots (Vancouver, Barcelona, Guwahati, Bengaluru)
- Lab / group photos
- Any deal.II simulation renders you're proud of (crystal growth, phase field snapshots, etc.)

## How to add/edit conferences on the map

Edit `_data/conferences.yml`. Each entry looks like:
```yaml
- title: 16th World Congress on Computational Mechanics (WCCM 2024)
  city: Vancouver
  country: Canada
  date: Jul 2024
  lat: 49.2827
  lng: -123.1207
  venue: Vancouver Convention Centre
```
Latitude/longitude for a new place: quick Google, e.g. "Delft latitude longitude" — take the two numbers.

## How to edit the Journey timeline

Edit `_data/timeline.yml`. Each entry has a `type` — one of:
- `industry` — dark filled marker with an office icon
- `academic` — outlined marker with a graduation cap
- `milestone` — gold-filled marker with a star

## Update the CV PDF (optional but recommended)
The site's "Download CV (PDF)" button currently serves the old `docs/CV_Umair.pdf`. To update it:
1. Open `Umair_Hussain_CV.docx` in Word.
2. Save As → PDF.
3. Save it as `docs/CV_Umair.pdf` in the site folder (overwrite).
4. Commit and push.

## What we did NOT add (yet)
- Interactive FEM demos (heat equation, Kobayashi dendrites, etc.) — Phase 3 in our plan, deferred.
- Blog posts using `_posts/` — deferred.
- Any ChampionX / SLB project details — intentionally omitted for now per your instruction.

## Local preview (optional)
If you ever want to preview locally before pushing:
1. Install Ruby: https://rubyinstaller.org/downloads/ (pick the one with DevKit)
2. `gem install bundler jekyll`
3. In the site folder: `bundle install`, then `bundle exec jekyll serve`
4. Open `http://localhost:4000`
