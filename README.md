# 🌟 Awesome Veo3 (and Veo 3.1)

> A community‑curated hub of tools, demos, guides, prompts, research, and links around **Veo 3** and the newly released **Veo 3.1** — Google’s vision for cinematic AI video + audio.

---

## 📚 Table of Contents

- [Overview: Veo 3 & Veo 3.1](#overview-veo-3--veo-31)  
- [Key Features & Differences](#key-features--differences)  
- [Getting Started](#getting-started)  
- [Official Resources](#official-resources)  
- [Guides, Tutorials & Walkthroughs](#guides-tutorials--walkthroughs)  
- [Prompt Collections & Patterns](#prompt-collections--patterns)  
- [Demo Repositories & Examples](#demo-repositories--examples)  
- [Community & Discussions](#community--discussions)  
- [Research & Ethics / Impact](#research--ethics--impact)  
- [Roadmap & Known Limitations](#roadmap--known-limitations)  
- [Contributing](#contributing)  
- [License](#license)

---

## 🧠 Overview: Veo 3 & Veo 3.1

### Veo 3

Veo 3, launched in 2025, is Google DeepMind / Gemini’s AI video generation model that lets you produce **short, high-quality video clips with native audio** (dialogue, ambience, sound effects).

Key aspects:
- Videos up to ~8 seconds  
- Synchronous audio woven into the output (ambient sounds, effects, etc.)  
- Supports text → video, image → video modes  
- Available via Gemini UI, Vertex AI APIs, and integrated into tools like **Flow** and **Google Vids**  
- In Canva, users can “Create a Video Clip” via Veo 3 integration  
- Safety & watermark measures: outputs carry a visible watermark and embedded “SynthID” watermark  

### Veo 3.1

Veo 3.1 enhances Veo 3’s capabilities with more narrative control, audio richness, and creative features. Released in a “paid preview” via Gemini API and Flow editor.

What’s new / improved:
- Richer native audio — natural dialog, synchronized effects, ambient sound  
- “Ingredients to Video” — reference images to guide generation  
- “Frames to Video” / interpolation — generate transitions between a first and last frame  
- Scene / video extension — extend existing clips seamlessly  
- Better prompt adherence and reliability  
- Integration with Flow editor: granular editing, lighting / shadow control  

---

## 🛠 Key Features & Differences

| Feature / Capability | Veo 3 | Veo 3.1 |
|----------------------|-------|---------|
| Audio | ✅ native audio | ✅ richer audio |
| Image‑guided video | basic | enhanced |
| Frame interpolation | — | ✅ yes |
| Video extension | basic | ✅ yes |
| Prompt adherence | solid | ✅ improved |
| Flow editor | basic | ✅ advanced |
| Watermark | SynthID | SynthID |
| Video length | ~8s | longer possible |

---

## 🚀 Getting Started

1. **Access**
   - Use via Gemini (Pro / Ultra) or Vertex AI  
   - Veo 3.1 via Gemini API (paid preview)

2. **Example Code**
   ```python
   from google import genai
   from google.genai import types

   client = genai.Client()

   op = client.models.generate_videos(
       model="veo-3.1-generate-preview",
       prompt="A calm forest at dawn, birds chirping and soft mist",
       config=types.GenerateVideosConfig()
   )
   ```

3. **Tools**
   - Flow editor (advanced control)  
   - Google Vids (direct clip generation)  
   - Canva (short AI clips with sound)  

---

## 📖 Official Resources

- Google Developers — Introducing Veo 3.1  
- DeepMind — Veo model overview  
- Vertex AI Docs — Veo API reference  
- Flow updates blog  
- Workspace blog — Veo 3 in Google Vids  

---

## 🎓 Guides, Tutorials & Walkthroughs

- *Veo 3 Tutorial* — YouTube walkthroughs  
- *Veo 3 Explained* — Medium article  
- *Meet Flow: AI Filmmaking* — Google blog  

---

## 🪶 Prompt Collections & Patterns

- Reddit threads with community prompts  
- Collections for cinematic, camera motion, lighting, sound direction, and transitions  

---

## 📂 Demo Repositories & Examples

- Showcase prompt → video results  
- Demos of interpolation, extensions, and transitions  

---

## 🌐 Community & Discussions

- Reddit: r/VEO3, r/aiVideo  
- YouTube and Discord creator communities  

---

## 🧪 Research, Ethics & Impact

- Articles on watermarking and AI realism  
- Deepfake & misinformation discussion  
- Responsible use guidelines from Google Cloud  

---

## 🗺️ Roadmap & Known Limitations

- Short clip length (~8s) until longer output fully supported  
- Audio/lip sync improving  
- Future: object removal, long-sequence consistency, social integrations  

---

## 🤝 Contributing

1. Fork repo  
2. Add links, guides, or examples  
3. Submit pull request  

---

## 📄 License

Licensed under the **MIT License**.
