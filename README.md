# 🎛️ GridAmp Player

An embeddable, customizable retro synthwave media player designed for art galleries, DeviantArt journals, Sta.sh posts, and portfolio websites. Stream audio directly from Suno AI generations, custom MP3 links, or direct video media streams with dynamic multi-band spectrum visualizers and skin wraps.

---

## 🚀 Quick iFrame Embed Code

Copy and paste this `<iframe>` snippet directly into your website, blog, or Sta.sh layout to embed the live player hosted via GitHub Pages:

```html
<iframe 
  src="[https://klankdon.github.io/GridAmp_player/](https://klankdon.github.io/GridAmp_player/)" 
  width="100%" 
  height="450" 
  frameborder="0" 
  allow="autoplay; encrypted-media" 
  style="border-radius: 16px; border: none; overflow: hidden;">
</iframe>
---
🎨 Dynamic URL Query Skinning
You can customize the player appearance and initial audio stream directly through URL query parameters without modifying any code:

HTML
<!-- Example: Witch & Pumpkin Theme with Custom Artwork Wrap and Suno Track -->
<iframe 
  src="[https://klankdon.github.io/GridAmp_player/?theme=matrix&bg=https://domain.com/skin.png&autoplay=true&track=https://domain.com/audio.mp3&title=Cyber](https://klankdon.github.io/GridAmp_player/?theme=matrix&bg=https://domain.com/skin.png&autoplay=true&track=https://domain.com/audio.mp3&title=Cyber) Track" 
  width="100%" 
  height="450" 
  frameborder="0" 
  allow="autoplay; encrypted-media" 
  style="border-radius: 16px; border: none;">
</iframe>
URL Parameters:
theme: Palette preset (outrun, obsidian, gold, matrix)

bg: Direct image URL (JPG/PNG/GIF) to wrap onto the chassis

autoplay: Set to true or 1 for auto-playback

track: Direct URL to an MP3 or direct video media stream (including Sta.sh / Wix MP4s)

title: Track title display text

artist: Artist name display text

💾 Standalone Download
If you prefer to host the player on your own web server or use it offline:

Download the raw index.html file.

Open it directly in any web browser—no build tools, Node modules, or external servers required!

⚡ Features
Web Audio API Visualizer: Dynamic multi-band equalizer canvas with fallback mode for cross-domain streams.

Custom Image Wraps: Drag-and-drop or load JPG/PNG artwork directly onto the hardware chassis with custom blending modes and scaling.

Sta.sh & Video Audio Stream Support: Ingests direct MP4 video streams and Wix media CDN links into the audio engine.

Theme Config Import/Export: Save and share custom skin JSON configurations.

Created for mimir-vibe & open-source web audio embeds.
