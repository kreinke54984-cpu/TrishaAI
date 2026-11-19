# Trisha Android PWA — upgraded free prototype

## Included
- Installable Progressive Web App for Android Chrome
- Stylized, gently animated full-body avatar illustration (CSS)
- Chat interface
- Browser speech-to-text where supported
- Browser text-to-speech where supported
- Offline shell caching

## Honest limitations
This is **not** a real generative AI model, photorealistic 3D human, or live video call. The replies are simple local conversation logic. The avatar is a stylized CSS illustration, not a realistic full-body human animation. A true intelligent model and photorealistic talking avatar require hosted services, hardware, or a local model; reliable always-free hosted access cannot be guaranteed.

## Install on Android
A PWA must be served over HTTPS to install reliably. Easiest free publishing route:
1. Create a GitHub account and a public repository named `trisha-companion`.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. In repository Settings -> Pages, deploy from the `main` branch and root folder.
4. Open the resulting HTTPS Pages address in Chrome on Android.
5. Use Chrome menu -> Add to Home screen / Install app.
6. Allow microphone access when prompted. Speech recognition support varies by browser and device.

## Privacy
The starter does not send typed messages to a server. Browser speech recognition may be processed by the browser/platform provider. Do not enter sensitive personal information. The app does not record or store conversation history permanently.

## To add real AI later
A secure backend must call a language model provider; keep credentials server-side. A separate streaming avatar/video provider is needed for a photorealistic talking full-body character. Free tiers and availability can change.
