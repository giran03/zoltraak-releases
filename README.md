# Zoltraak

> **Currently invitation-only. Zoltraak is available only to invited users. Public access is not available at this time.**

Zoltraak is a desktop download manager with browser integration. Manage file transfers, choose video formats, organize music, and collect media from posts in one app.

## Features

- **File downloads:** segmented HTTP/HTTPS transfers with configurable connections, pause and resume, retries, and recovery after an app restart. Segmentation and resume depend on the source server's support.
- **Queue management:** priorities, bounded concurrency, search, status filters, multi-selection, and bulk actions. A shared bandwidth limit helps control concurrent transfers.
- **Browser integration:** send links and media to the app through a paired browser extension. For supported sources, the extension can share the signed-in session needed to access media.
- **Video:** analyze a page, direct media file, or supported HLS/DASH stream, then choose a discovered format. Separate audio and video streams can be merged using local media tools.
- **Music:** analyze tracks, albums, and playlists; choose an output format; and organize files with metadata, cover art, and filename options. For Spotify, Apple Music, and Deezer, Zoltraak reads catalogue metadata and matches recordings on YouTube Music; those services do not directly supply the audio file. Matching depends on recording availability and is not DRM bypass.
- **Images and galleries:** extract media from supported posts or direct links, preview the results, select what to keep, and send images to the download queue.
- **Folder routing:** match downloads by file extension, domain, or regular expression. Rules apply when a download is added and respect an explicitly chosen destination.
- **Scheduling:** define a daily download window and choose a completion action, such as opening the destination folder or exiting the app.
- **Remux and conversion:** move local audio/video streams into another container, or re-encode when needed. Stream copying preserves the source; re-encoding can change quality.
- **Discord delivery:** send finished files to a configured channel using a webhook or your own bot. Media can be prepared to fit the configured upload budget; the downloaded original remains unchanged.

Media conversion, stream merging, and related processing require local `ffmpeg`/`ffprobe` tools. Source availability, sign-in requirements, and supported formats vary by website.

## Screenshot showcase

These screenshots render the current Zoltraak interface with **demo data** in a temporary browser capture harness. File names, media, progress, and source addresses are illustrative; they are not performance measurements. Each view is captured at 1440 × 900 using the default appearance in dark system mode.

### Downloads

Track segmented file transfers and manage downloading, waiting, paused, and finished items in the same register.

![Zoltraak Downloads view with demo transfers, connection progress, status filters, and queue controls](assets/screenshots/downloads.png)

### Video

Analyze a source and compare available video formats before choosing a download.

![Zoltraak Video view showing a demo source with 1080p, 720p, and 480p MP4 format choices](assets/screenshots/video.png)

### Music

Review a collection's tracks and configure the format, folder layout, and metadata options for your files.

![Zoltraak Music view showing a demo album, selectable tracks, and audio output options](assets/screenshots/music.png)

### Images

Preview extracted media and select the items you want to save from a gallery.

![Zoltraak Images view showing a demo gallery with four selectable landscape illustrations](assets/screenshots/images.png)

### Rules

Route new downloads into folders automatically using extension, domain, or regular-expression matches.

![Zoltraak Rules view showing demo routing rules for archives, documents, software, and installation images](assets/screenshots/rules.png)

## Availability

**Zoltraak is currently available only to invited users.** This repository presents the product and its release materials; it does not grant access. Public access is not available at this time.
