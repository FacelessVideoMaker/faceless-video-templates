# Giant fruit-house AI builds

A giant fruit lands in water or on a shore, a doorway is cut in the skin, and a cozy interior glows inside — one locked-wide 6-second reveal. Broken down on [@faceless.recipes](https://www.instagram.com/faceless.recipes/).

**This is our rebuild of a public format**, not Dripora ASMR's confirmed workflow. Demo visuals are an original lemon lagoon house with **no people**, not their orange footage (their thumbnails often show a recurring AI character; leave figures out). Hook example: [She Built a 2-Story Home Inside a 100-Foot Orange That Crashed Into the Ocean](https://www.youtube.com/shorts/UBCDan3SbFk) by Dripora ASMR (@DriporaASMR) — **20,415,344** views, checked Nov 12 2026. The hook clip's own title/tags do not say "AI"; the channel about and later videos do. Views aren't income; results not guaranteed.

Copy the format. Make your own fruits. Never re-upload someone else's clips.

---

## The 3-step recipe

### Tools
- **Claude** (Haiku 4.5 is enough) — idea list
- **Nano Banana** (`google/gemini-nano-banana-2.1`) — 9:16 stills, 2K
- **Veo 3.1 Lite** — image-to-video, 6 s, 1080p, 9:16, **with audio**

---

## Step 1 · IDEA (Claude)

```
List 8 original faceless Short ideas for a giant-object house reveal. Each: one oversized fruit that has landed in water or on a shore, one doorway cut in the skin, one cozy interior payoff. No people, faces, hands, figures, brands, celebrities, or copyrighted places. Do not use orange, watermelon, apple, mango, coconut, pineapple, pumpkin, or rose. Number them 1-8. Keep each line under 12 words.
```

Pick one original fruit (we used a giant lemon in a lagoon). Skip fruits the format is already famous for. Keep the rebuild people-free.

Real Claude sample (4 of 8, shortened): lagoon plum → candlelit interior; lake avocado → warm lamps; beached fig → hanging gardens; passion fruit → cushioned nook.

---

## Step 2 · LOOK (Nano Banana)

Settings: **9:16**, **2K**, photoreal still. No people, no faces, no hands, no figures, no text, no logos.

Hero (lemon lagoon):

```
Cinematic vertical 9:16 still, a giant yellow lemon half-submerged in a calm turquoise lagoon, an arched doorway already cut into the peel, warm golden interior light spilling out onto the water, photoreal, no people, no faces, no hands, no figures, no text, no logos.
```

Series variants — same landed-fruit + arched doorway + warm interior light motif, swap only the fruit and setting:

```
Cinematic vertical 9:16 still, a giant yellow starfruit resting on a wooden pier over calm water, an arched doorway cut into the skin, warm golden interior light spilling out, photoreal, no people, no faces, no hands, no figures, no text, no logos.
```

```
Cinematic vertical 9:16 still, a giant cacao pod on a jungle riverbank, an arched doorway cut into the pod, warm golden interior light spilling out, photoreal, no people, no faces, no hands, no figures, no text, no logos.
```

```
Cinematic vertical 9:16 still, a giant persimmon half-buried in snow, an arched doorway cut into the skin, warm golden interior light spilling out onto the snow, photoreal, no people, no faces, no hands, no figures, no text, no logos.
```

```
Cinematic vertical 9:16 still, a giant kiwi on a black-sand beach, an arched doorway cut into the skin, warm golden interior light spilling out, photoreal, no people, no faces, no hands, no figures, no text, no logos.
```

```
Cinematic vertical 9:16 still, a giant pear perched on a coastal cliff, an arched doorway cut into the skin, warm golden interior light spilling out, photoreal, no people, no faces, no hands, no figures, no text, no logos.
```

Keep the **landed fruit + doorway + glowing interior** so the series feels consistent. Reject stills with people, hands, logos, unreadable text, or a cluttered frame.

---

## Step 3 · ANIMATE (Veo 3.1 Lite + audio)

Settings: image-to-video, hero still as the **first frame**, **generate_audio = true**, **9:16**, **6 s**, **1080p**.

```
Locked wide camera, continuous 6 seconds: the arched doorway in a giant lagoon lemon opens a little wider, warm interior light blooms, gentle ripples around the peel, quiet water ASMR, no music, no voice, no people, no faces, no hands, no cuts.
```

Reject morphing peel, a doorway that collapses, or a person appearing in the interior. The quiet water is the payoff — keep audio on.

---

## Cost (what I actually spent on this rebuild, OpenRouter list prices Nov 12 2026)
- Claude idea list (Haiku 4.5): **$0.001**
- Nano Banana stills ×6 (hero + 5 variants): **$0.319**
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
- **Doorway morphs, peel collapses, or interior jumps:** reject and regenerate; don't fake a good take. Fruit geometry often fails mid-clip.
- **A person or hands appear:** reject. This format should stay people-free even if reference channels use an AI character.
- **Silent clip / no water sound:** confirm `generate_audio = true` and that you're not stripping audio on export.
- **Subject off-center in 9:16:** crop/reframe so the fruit and doorway sit near the vertical center before animating.
- **Interior too dark to read as a home:** ask for warm golden interior light spilling onto the water in the still prompt.

## Rules
- Copy the format, not the videos. Never re-upload someone else's clips.
- Turn on the AI label (YouTube "altered or synthetic content", Instagram "AI info").
- Our footage is tagged as an AI recreation — do the same on yours.

[← Back to all guides](../README.md)
