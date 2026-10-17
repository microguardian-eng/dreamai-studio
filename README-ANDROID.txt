DREAMAI STUDIO — ANDROID PHONE STARTER (v0.2)

WHAT WORKS
- Four prompt workflows: text-to-image, image-to-image, text-to-video, image-to-video.
- Reference image selection and local preview for image-to-image and image-to-video.
- Prompt builder, clipboard copy, local saved prompts, JSON export, configurable provider links.
- Installable PWA shell when served over HTTPS.

IMPORTANT HONEST LIMITATION
This is a mobile-first front-end launcher, not a bundled AI model and not a direct connection to an inference API. It cannot create AI images/videos by itself. It opens the hosted model search page; you must select a working demo, paste the prompt, and manually upload the reference image on that website. No image is uploaded from this app. Hosted demos may have quotas, queues, sign-in requirements, or become unavailable. There is no reliable way to promise unlimited high-quality generation for free.

PHONE-ONLY SETUP
1. Download and extract this ZIP using Android Files or an archive app.
2. Open https://github.com in Chrome, sign in, and create a repository named dreamai-studio. Public repositories expose source code, so do not add passwords or API keys.
3. Upload the contents of this folder to the repository root. If needed, use Chrome menu > Desktop site.
4. In repository Settings > Pages, publish from the main branch and root folder. Open the HTTPS URL GitHub provides.
5. In Chrome menu, choose Add to Home screen / Install app.
6. In DreamAI Studio > Settings, you can keep the default Hugging Face search URLs or paste exact URLs of demos that work for you.
7. Use the mode, write a prompt, press Open model, then paste the copied prompt into the hosted demo. For image-to-image and image-to-video, manually upload the same image on the demo page.

FREE MODEL DISCOVERY
- Image models: https://huggingface.co/spaces?search=flux
- Image editing: https://huggingface.co/spaces?search=image%20edit
- Text to video: https://huggingface.co/spaces?search=text%20to%20video
- Image to video: https://huggingface.co/spaces?search=image%20to%20video
- ZeroGPU docs: https://huggingface.co/docs/hub/main/spaces-zerogpu

Hugging Face documents free ZeroGPU access with a limited daily quota (the docs currently list 5 minutes of daily GPU quota for free accounts). That is useful for occasional tests, not unlimited production. Public Spaces may have different limits. See the official docs for current terms.

FILES
index.html, style.css, app.js, manifest.webmanifest, sw.js, icon.svg.
