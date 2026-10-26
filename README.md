# భగవద్గీత — Clean Source Code

A React + TypeScript + Vite starter app. This package intentionally contains **no Google Drive links, video IDs, or user-provided video files**.

## Features
- Telugu UI with 18 Bhagavad Gita chapter names
- Chapter selector
- Shloka list with Chapter 1 entries shown first
- Clicking a shloka attempts to play its corresponding local MP4
- Clear error state when a video file is missing
- Responsive layout for desktop and mobile

## Run locally
1. Install Node.js (LTS).
2. Extract this ZIP.
3. Open a terminal in the extracted folder.
4. Run `npm install`.
5. Run `npm run dev`.
6. Open the local URL shown by Vite.

## Add your own videos
Put files under `public/videos/`, using the paths expected by `src/data.ts`. Example:
`public/videos/chapter-01/shloka-001.mp4`

Edit `src/data.ts` to configure the correct number of shlokas and each local file path. This ZIP does not include videos and does not verify external links.

## Build
Run `npm run build`. The production output is generated in `dist/`.

## Important
This is a clean starter source project, not a copy of an existing private app repository. It has no actual Bhagavad Gita video media bundled, so playback works only after you add the corresponding local video files.