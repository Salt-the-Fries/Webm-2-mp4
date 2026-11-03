# WEBM → MP4 Studio

A free, browser-based batch WEBM to MP4 converter. Files are processed locally with FFmpeg WebAssembly and are never uploaded to a server.

## Features
- Batch-select or drag-and-drop multiple WEBM files
- H.264 video + AAC audio MP4 output
- Per-file progress and individual downloads
- No account, watermarks, server-side file quotas, or uploads
- Static site, deployable to GitHub Pages

## Run locally
Serve this directory with any static HTTP server. ES modules and WebAssembly require localhost or HTTPS.

## Deploy
The included GitHub Actions workflow deploys the repository root to GitHub Pages on every push to `main`. In repository Settings → Pages, choose **GitHub Actions** as the build and deployment source.

## Notes
“Unlimited” means no application-imposed upload count or server quota. Browser memory, device performance, and available storage still limit practical batch size. Keep the tab open during conversion. An internet connection is required to download the FFmpeg engine from jsDelivr on first use.
