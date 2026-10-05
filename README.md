# media

Finished social media for the three channels. Nothing here is a source file or a
build artefact -- only what actually gets posted.

## Layout

```
<channel>/images/<post>/   stills, carousel slides, covers
<channel>/carousels/<set>/ ViennaAistudio carousel sets
<channel>/captions/        caption text, one file per batch
```

**Videos are not in the tree.** Git keeps every version of a binary for ever, which
would bloat this repo within months. They are attached to one release per channel
instead: GitHub puts no limit on release size or bandwidth, and deleting an asset
there really deletes it.

## Video URLs

```
https://github.com/faraznkz/media/releases/download/<channel>/<file>
```

For example:

```
https://github.com/faraznkz/media/releases/download/lingofa/2026-10-03-artikel-quiz-1.mp4
```

These are public and need no token, which is why the repo is public: TikTok's
Content Posting API cannot read a local file, so the video has to be fetchable.
Instagram, YouTube and Facebook upload straight from the PC and do not need this.

## Channels

### Lingofa

Destinations: Instagram, TikTok, YouTube

30 videos (14.0 MB) in release [`lingofa`](https://github.com/faraznkz/media/releases/tag/lingofa).

- `2026-09-28-daily5-day11-nagoo.mp4`
- `2026-09-28-daily5-day12-tohin.mp4`
- `2026-09-28-daily5-day13-maani-dovom.mp4`
- `2026-09-28-sentences-11-daava.mp4`
- `2026-09-28-sentences-12-taarof.mp4`
- `2026-10-03-artikel-quiz-1.mp4`
- `2026-10-03-artikel-quiz-2.mp4`
- `2026-10-03-artikel-quiz-3.mp4`
- `2026-10-03-artikel-quiz-4.mp4`
- `2026-10-03-artikel-quiz-5.mp4`
- `2026-10-03-daily5-day14-pul.mp4`
- `2026-10-03-daily5-day15-doctor.mp4`
- `2026-10-03-daily5-day16-kar.mp4`
- `2026-10-03-daily5-day17-khune.mp4`
- `2026-10-03-daily5-day18-tarifha.mp4`
- `2026-10-03-daily5-day19-ghalat.mp4`
- `2026-10-03-daily5-day20-vaght.mp4`
- `2026-10-03-sentences-13-ezterari.mp4`
- `2026-10-03-sentences-14-kharid.mp4`
- `2026-10-03-sentences-15-ghatar.mp4`
- `2026-10-03-sentences-16-telefon.mp4`
- `2026-10-03-sentences-17-na.mp4`
- `2026-10-03-sentences-18-mehmooni.mp4`
- `2026-10-03-sentences-19-edare.mp4`
- `2026-10-03-sentences-20-jodaei.mp4`
- `2026-10-04-viral-1-adat.mp4`
- `2026-10-04-viral-2-talafoz.mp4`
- `2026-10-04-viral-3-otrish.mp4`
- `2026-10-04-viral-4-pul.mp4`
- `2026-10-04-viral-5-ghalat.mp4`

### ThePhilosoFix

Destinations: YouTube, TikTok, Instagram

5 videos (121.2 MB) in release [`philosofix`](https://github.com/faraznkz/media/releases/tag/philosofix).

- `01-machiavelli-appearance.mp4`
- `02-schopenhauer-alone.mp4`
- `03-jung-mask.mp4`
- `04-seneca-time.mp4`
- `05-nietzsche-why.mp4`

### ViennaAistudio

Destinations: Instagram, Facebook, TikTok

9 videos (43.0 MB) in release [`viennaaistudio`](https://github.com/faraznkz/media/releases/tag/viennaaistudio).

- `nein-reel-v3.mp4`
- `r1.mp4`
- `r2.mp4`
- `r3.mp4`
- `r4.mp4`
- `r5.mp4`
- `r6.mp4`
- `r7.mp4`
- `r8.mp4`

## What is deliberately missing

ThePhilosoFix long-form episodes. They run to hundreds of megabytes, go straight to
YouTube from the PC, and the user reviews each one before it is published.

## Housekeeping

Delete a release asset once its post is live. The archive is OneDrive; this repo is
a serving layer, not a library.
