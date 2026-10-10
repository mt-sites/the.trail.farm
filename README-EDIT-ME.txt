THE FARM TRAIL — HOW TO EDIT YOUR WEBSITE

1. Open index.html in a code editor (VS Code or Notepad++).
2. Search for EASY EDIT SETTINGS near the beginning of the <body>.
3. Change values inside window.FARMTRAIL_CONFIG:
   name, tagline, heroDescription, facebook, messenger, reel, hours,
   theme, sections, gallery, occasions, and image paths.
4. Replace images in the images folder. You can keep the same filenames
   to avoid updating the config, or change the paths to new files.
5. To hide content, change an item under sections from true to false.
6. Save index.html and open it in a browser to preview.
7. Publish index.html together with the entire images folder and farmtrail-preview.jpg.
8. SOCIAL PREVIEW: Search YOUR-DOMAIN.example in the <head> and replace
   it with your real HTTPS domain; update the preview title/description
   there when those details change. Messenger/WhatsApp/Facebook crawlers
   do not run JavaScript.

The reviews section uses your Jotform widget and requires internet.
The Facebook Reel is a Facebook embed, subject to Facebook/browser playback rules.
Phone and email buttons appear only when those values are provided.
