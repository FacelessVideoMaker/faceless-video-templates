# Fallen plant life-cycle AI timelapse

A seed or fruit falls on soil, a sprout rises, and a new plant forms — one locked-camera 6-second timelapse. Broken down on [@faceless.recipes](https://www.instagram.com/faceless.recipes/).

**This is our rebuild of a public format**, not NatureVerse's confirmed workflow. Demo visuals are an original pomegranate life-cycle, not their cucumber footage. Hook example: [From a Fallen Cucumber to a New Plant](https://www.youtube.com/shorts/4c7kX_3J-4Y) by NatureVerse (@NatureWonder4k) — **58,962,527** views, checked Nov 12 2026. Views aren't income; results not guaranteed.

Copy the format. Make your own plants. Never re-upload someone else's clips.

---

## The 3-step recipe

### Tools
- **Claude** (Haiku 4.5 is enough) — idea list
- **Nano Banana** (`google/gemini-nano-banana-2.1`) — 9:16 stills, 2K
- **Veo 3.1 Lite** — image-to-video, 6 s, 1080p, 9:16, **with audio**

---

## Step 1 · IDEA (Claude)

```
List 8 original faceless Short ideas for a plant life-cycle timelapse. Each: one plant or seed that falls, one soil/road setting, one growth payoff (sprout, flower or harvest). No people, faces, brands, celebrities, or copyrighted places. Do not use cucumber, ginger, apple, okra, potato, sweet potato, garlic, or other already-famous versions of this format. Number them 1-8. Keep each line under 12 words.
```

Pick one original plant (we used a fallen pomegranate on a dirt path). Skip plants the format is already famous for.

Real Claude sample (4 of 8, shortened): hillside acorn → oak sapling; gravel path → fennel fronds; field lentil → green shoots; rocky ground → poppy petals.

---

## Step 2 · LOOK (Nano Banana)

Settings: **9:16**, **2K**, photoreal still. No people, no text, no logos.

Hero (pomegranate):

```
Cinematic vertical 9:16 still, macro-to-wide dirt path after rain, a split pomegranate lying on dark soil, a pale green sprout rising from a seed, fine white roots visible in a cutaway of the earth, photoreal, soft natural light, no people, no text, no logos.
```

Series variants — same dirt-path-after-rain + sprout + cutaway roots motif, swap only the plant:

```
Cinematic vertical 9:16 still, dirt path after rain, a split fig lying on dark soil, a pale green sprout rising beside it, fine white roots visible in a cutaway of the earth, photoreal, soft natural light, no people, no text, no logos.
```

```
Cinematic vertical 9:16 still, dirt path after rain, a yellow corn cob lying on dark soil, a pale green sprout rising beside it, fine white roots visible in a cutaway of the earth, photoreal, soft natural light, no people, no text, no logos.
```

```
Cinematic vertical 9:16 still, dirt path after rain, a cacao pod lying on dark soil, a pale green sprout rising beside it, fine white roots visible in a cutaway of the earth, photoreal, soft natural light, no people, no text, no logos.
```

```
Cinematic vertical 9:16 still, dirt path after rain, a head of broccoli lying on dark soil, a pale green sprout rising beside it, fine white roots visible in a cutaway of the earth, photoreal, soft natural light, no people, no text, no logos.
```

```
Cinematic vertical 9:16 still, dirt path after rain, a pear lying on dark soil, a pale green sprout rising beside it, fine white roots visible in a cutaway of the earth, photoreal, soft natural light, no people, no text, no logos.
```

Keep the **fallen plant + cutaway sprout on a wet dirt path** so the series feels consistent. Reject stills with people, logos, unreadable text, or a cluttered frame.

---

## Step 3 · ANIMATE (Veo 3.1 Lite + audio)

Settings: image-to-video, hero still as the **first frame**, **generate_audio = true**, **9:16**, **6 s**, **1080p**.

```
Locked camera, continuous 6 seconds: a sprout pushes out of rain-damp soil beside a fallen pomegranate, the seedling rises and unfurls leaves, small pomegranate fruits form on the new plant; quiet earth/sprout ASMR, no music, no voice, no people, no cuts.
```

Reject morphing fruit, disappearing roots, or a jump cut mid-growth. The quiet earth sound is the payoff — keep audio on.

---

## Cost (what I actually spent on this rebuild, OpenRouter list prices Nov 12 2026)
- Claude idea list (Haiku 4.5): **$0.001**
- Nano Banana stills ×6 (hero + 5 variants): **$0.320**
- Veo 3.1 Lite 6 s 1080p **with audio**: **$0.48**
- Sabrina TTS for the breakdown reel: **~$0.008**
- **Demo total: $0.81**
- **Per Short (1 still + 1 Veo with audio): ~$0.53 (est.)**
- Each extra 6 s video attempt adds ~$0.48

---

## Caption / posting tips
- Hook with the view count in the first line
- Comment-keyword CTA: "Comment GUIDE"
- 5 hashtags max
- Label AI content on Instagram

---

## Troubleshooting
- **Sprout morphs or fruit pops in from nowhere:** reject and regenerate; don't fake a good take. Growth geometry often fails mid-clip.
- **Silent clip / no earth sound:** confirm `generate_audio = true` and that you're not stripping audio on export.
- **People or logos in the still:** tighten the prompt (`no people, no text, no logos`) and regenerate.
- **Subject off-center in 9:16:** crop/reframe so the fallen fruit and sprout sit near the vertical center before animating.
- **Roots look fake or float above the soil:** ask for a clear earth cutaway with fine white roots in the still prompt.

## Rules
- Copy the format, not the videos. Never re-upload someone else's clips.
- Turn on the AI label (YouTube "altered or synthetic content", Instagram "AI info").
- Our footage is tagged as an AI recreation — do the same on yours.

[← Back to all guides](../README.md)
