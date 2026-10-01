# YouTube Package — "Edit Like Iman Gadzhi in 5 Minutes"

Video: Makar Edits. Animated "Monthly earnings" chart widget in After Effects, made with built-in tools only. Runtime about 5:07.

---

## 0. Research summary (why everything below looks the way it does)

**Thumbnails (CTR data and creator strategy)**
- Paddy Galloway (MrBeast's former strategist) says a thumbnail is "80–90% psychology of the click, 10–20% design". He names 5 thumbnail types: Moment, Story, **Result**, **Transformation (before/after)** and Novelty. For tutorials, **Result** and **Transformation** are the strongest, so 2 of our 3 variants use them.
- Keep thumbnail text to **5 words or fewer**. Text should *open a curiosity loop*, not repeat the title. This matters most for talking-head and education channels like yours.
- Thumbnails with **more than 3 distinct visual elements get ~23% lower CTR**. That's why each prompt below is limited to face + hero object + text (the AE icon counts as a small accent).
- **Expressive face with eye contact** (raised brows, slightly open mouth) beats a neutral face by ~30–38%.
- High-contrast combos (yellow/green on dark navy, dark on bright) do best. Bright green (money, growth) is the natural accent here because it's also the color of your chart.
- Visual order: **face first, hero object second, text third.**

**Nano Banana Pro (Gemini 3 Pro Image) prompting**
- Write in **natural flowing sentences**, not keyword soup. The model understands prose better.
- Put the **aspect ratio first**: "16:9, 1280×720 YouTube thumbnail".
- Put any text you want rendered **inside quotation marks**, and name the font style, weight, color and position.
- **Identity lock**: upload one clear, well-lit, unfiltered photo of your face. **Label each reference's role** ("Image 1 = my face, use ONLY for identity"). Add "keep facial features exactly the same as Image 1".
- Up to 14 reference images are supported, with roughly 6 at high fidelity. Upload the **official After Effects icon PNG as Image 2** so the logo isn't hallucinated.
- If a result is 80% right, **don't regenerate. Edit conversationally** ("change only the headline text to…", "make the face 15% larger").
- Ask for a **text-safe area** and keep the headline in the central ~60% of the frame so the YouTube timestamp badge (bottom-right) doesn't cover it.

**Titles**
- Viral patterns: specific numbers, curiosity gaps, **time markers ("in 5 minutes")**, a name people already search ("Edit like ___"), and a **40–60 character** sweet spot.
- "Edit like Iman Gadzhi" is an **existing search phrase**. There are whole tutorials and playlists with that wording, so it brings in search traffic *and* browse clicks.

**A/B testing (YouTube Test & Compare, 2026)**
- You can now test **up to 3 thumbnails** and also titles. **Test one variable at a time.** Run thumbnails first with the title fixed, then titles with the winning thumbnail.
- **Don't stop a test early** and don't edit the title or thumbnail while it runs (that resets the test). Variants must be **really different**, not small tweaks.
- Upload at **1280×720 or larger**.

---

## 1. Titles

**Main title (your idea, kept):**
> **EDIT LIKE IMAN GADZHI IN 5 MINUTES**

Title A/B set (use after the thumbnail test is finished):
1. **EDIT LIKE IMAN GADZHI IN 5 MINUTES** (search phrase + time marker; safest)
2. **This "Expensive" Iman Gadzhi Animation Takes 5 Minutes** (curiosity gap: looks expensive vs. takes 5 min)
3. **How Iman Gadzhi & Hormozi Editors Make Charts Look Expensive** (two big names, a "how" curiosity gap, fits the money niche)

Backup options:
- Iman Gadzhi Motion Graphics in After Effects (No Plugins)
- The Clean Animation Every Business YouTuber Uses (After Effects)
- Stop Making Cheap Animations — Do This Instead (After Effects)

> ⚠️ Honest-packaging note: at 4:47 you say *"I'm using a plugin here"* for easing. You also say it can be done manually in the Graph Editor, so "No plugins" is still true. The description below says this openly, so nobody can call it bait in the comments.

---

## 2. Three Nano Banana Pro prompts (Google Flow)

**Before generating:**
1. **Image 1:** a sharp, front-lit, unfiltered close-up photo of your face. Ideally shoot it with the expression you want (surprised/confident). The model keeps expressions better than it invents them.
2. **Image 2:** the official Adobe After Effects app icon (PNG).
3. *(Optional) Image 3:* a screenshot of your finished chart widget from the video. It makes the "hero object" match your real animation exactly.
4. Generate 3–4 outputs per prompt. Pick the best one, then fix small things with short follow-up edits instead of regenerating.
5. Check spelling in every headline before exporting.

> I did not include Iman Gadzhi's or Alex Hormozi's faces on purpose. Generating real people's likeness looks like endorsement, and Nano Banana often blocks it anyway. Their **names** go in the title, and **your face** sells the thumbnail.

---

### PROMPT 1 — "THE RESULT" (bright, clean, Iman-style; stands out on dark-mode YouTube)

```
16:9 YouTube thumbnail, 1280x720, ultra-sharp, premium commercial design, high click-through style.

References: Image 1 is my face — use it ONLY for identity. Keep my facial features exactly the same as Image 1: same eyes, nose, lips, jawline, skin tone, hair texture and hairstyle. No beautification, no age change. Image 2 is the official Adobe After Effects app icon — reproduce it exactly, do not redesign it. Image 3 (if provided) is the chart widget — match its layout.

Composition: Left 40% of the frame — an extreme close-up of me from chest up, head slightly turned toward the right side of the frame, eyes looking directly into the camera, eyebrows raised, mouth slightly open in an impressed "wow" expression. Shallow depth of field, soft cinematic key light from the front-right, a crisp white rim light separating my hair and shoulders from the background.

Right 60% of the frame: the hero object — a floating, slightly 3D-tilted white rounded-corner card with soft drop shadow, like a premium fintech app widget. Inside the card: small thin grey text "Monthly earnings", below it a big bold black number "$3,000", a small pill badge in the top-right corner with soft mint-green background and green text "+95%", and a bright emerald-green line chart rising sharply from bottom-left to top-right with smooth curved segments, a glowing green dot at the tip of the line, and a soft green-to-transparent gradient fill under the line. Faint motion-blur streaks behind the card suggest it is animating.

Background: clean light pastel sky-blue (#CFE3F7) with a very subtle thin white grid pattern and a soft radial white glow behind the card. Minimal, luxurious, lots of breathing room.

Accent: the After Effects icon from Image 2, medium size, floating at the top-left above my head, tilted 10 degrees, with a soft purple glow.

Text: one headline at the top-right above the card, in a heavy bold geometric sans-serif (like Proxima Nova Black / Montserrat ExtraBold), all caps, dark navy (#0B1530) with the word "5 MIN" highlighted in emerald green: "IMAN STYLE IN 5 MIN". Keep the text fully inside the central safe area; nothing in the bottom-right corner.

Color palette: pastel blue, pure white, emerald green #19C37D, deep navy, a touch of After Effects purple. High contrast, clean, expensive, Apple-keynote aesthetic. No clutter, no extra icons, no extra text, no watermark, no arrows.
```

---

### PROMPT 2 — "BEFORE → AFTER" (transformation; strongest curiosity gap)

```
16:9 YouTube thumbnail, 1280x720, hyper-detailed, bold, high-contrast, designed to be readable at small mobile size.

References: Image 1 is my face — use ONLY for identity, keep my facial features exactly the same as Image 1 (eyes, nose, lips, jawline, skin tone, hair). Image 2 is the official Adobe After Effects icon — reproduce it exactly.

Composition: The frame is split diagonally into two halves by a thin glowing white line.
LEFT HALF ("before"): desaturated, flat grey background; a boring, ugly, cheap-looking default chart — a sharp-cornered grey box, a jagged thin grey line, default Arial text, slightly blurry. A small red label in the corner: "BEFORE". It should look clearly amateur.
RIGHT HALF ("after"): deep dark navy background (#070B1A) with a subtle glowing grid; a stunning premium fintech widget — white rounded-corner card with soft shadow, thin grey text "Monthly earnings", bold "$3,000", a mint-green "+95%" pill badge, and a thick glowing emerald-green line chart rising upward with a bright dot at its tip and a green gradient glow beneath it. Small green light particles and subtle motion blur. A small green label: "AFTER".

Me: In the center-front, overlapping the split line, a close-up of me from chest up, facing camera, confident smirk, one eyebrow raised, pointing with my index finger toward the right "after" side. Strong rim light: cool grey on the left edge of my face, emerald green on the right edge. Sharp focus on my eyes.

Accent: the After Effects icon from Image 2, small, floating next to the "after" card with a purple glow.

Text: large headline across the top center in an extra-bold condensed sans-serif, all caps, white with a thin black outline and soft shadow: "NO PLUGINS". Short, huge, perfectly legible. Keep all text inside the central safe area and away from the bottom-right corner.

Color palette: dead grey vs. deep navy + electric emerald green #22E07A + white + AE purple. The "after" side must feel twice as bright and expensive as the "before" side. No extra text, no logos except the AE icon, no watermark.
```

---

### PROMPT 3 — "DARK LUXURY / MONEY" (aspirational, Iman-Gadzhi cinematic mood)

```
16:9 YouTube thumbnail, 1280x720, cinematic, luxury, moody, premium entrepreneur aesthetic, ultra-sharp 4K detail.

References: Image 1 is my face — use ONLY for identity; keep my facial features exactly the same as Image 1, same skin tone, hair and proportions, no beautification. Image 2 is the official Adobe After Effects app icon — reproduce it exactly.

Composition: Right 45% of the frame — a tight close-up of my face and shoulders, three-quarter angle, looking straight into the lens with an intense, serious, "I know something you don't" expression. Low-key cinematic lighting: dramatic soft key light from the left, deep shadows on the right side of my face, a thin emerald-green rim light on my jaw and hair. Wearing a plain black t-shirt. Subtle film grain.

Left 55%: a large, glossy, 3D-rendered After Effects icon from Image 2, slightly tilted, floating in space with a strong purple-blue glow and a reflection on a glossy black floor. Behind it, a huge glowing emerald-green growth line chart sweeping upward from bottom-left to top-right across the background, with a bright glowing dot at the top and a soft green gradient fill fading into darkness. A small floating white rounded card near the line reading "$3,000 / month".

Background: near-black navy (#05070F) with a faint fine grid and soft volumetric haze; a warm subtle light leak in the top corner. Luxury, high-end, expensive, like a premium business documentary.

Text: headline at the top-left, two lines, extra-bold geometric sans-serif, all caps. Line 1 in white: "EDIT LIKE". Line 2, larger, in glowing emerald green #1EE07F: "IMAN GADZHI". Crisp, perfectly spelled, high contrast, inside the central safe area, nothing in the bottom-right corner.

Color palette: black, deep navy, emerald green, After Effects purple, white. Maximum contrast, minimal elements, no clutter, no extra text, no watermark.
```

**Quick-fix follow-ups for Flow (use instead of regenerating):**
- "Keep everything the same, but make my face 20% larger and closer to the camera."
- "Change only the headline text to "IMAN STYLE IN 5 MIN" — exact spelling, same font."
- "Make the green line brighter and add more glow; keep the rest identical."
- "Make my facial features match Image 1 more closely; do not change anything else."
- "Remove any extra text or small icons that are not in the prompt."

**A/B plan:**
- Week 1: upload all 3 thumbnails to *Test & Compare*, with the title fixed to "EDIT LIKE IMAN GADZHI IN 5 MINUTES". Let YouTube pick the winner and don't stop it early.
- Week 2: lock the winning thumbnail and test the 3 titles.

---

## 3. Description (copy-paste)

```
Edit like Iman Gadzhi in 5 minutes: build the clean, "expensive" animated money chart from business YouTube & fintech ads in After Effects, with zero third-party plugins.

📁 FREE project file + expressions (number counter & bounce script): [TELEGRAM LINK]
🎬 Need a professional video editor? Order here: [SERVICES LINK]

⏱ CHAPTERS
0:00 Intro: why "simple" editing is the expensive kind
0:39 Design: background & rounded card
0:58 Typography: "Monthly earnings", $0 & green badge
1:25 Free project file + drawing the data line (Pen tool)
1:54 Trim Paths: making the line grow
2:12 The leading data point
2:23 Make the dot follow the line (mask path trick)
2:43 Premium gradient fill under the line
3:18 Animate the gradient (alpha matte linked to the dot)
3:40 Animated numbers with expressions ($0 → $3,000)
3:53 Bounce-in animation (scale + bounce expression)
4:10 Matte reveal: sliding badge & text + motion blur
4:33 Bounce-out: squash & stretch by hand
4:51 Sound design & final result

━━━━━━━━━━━━━━━━━━━━━━

🎯 WHAT THIS VIDEO IS
You've seen this animation a thousand times: a clean white card pops onto the screen, a green line climbs, a glowing dot races to the top, and "$0" counts up to "$3,000". It's in Iman Gadzhi's videos, in Alex Hormozi's content, and in nearly every fintech app ad. It looks simple, and that simplicity is exactly what clients pay for.

Most beginners think this look needs expensive software or a plugin pack. It doesn't. I build it from scratch in Adobe After Effects with only built-in tools: shape layers, Trim Paths, masks, gradient fills, track mattes and a couple of expressions. You end up with a reusable premium asset you can sell to clients.

🧠 WHO IS IMAN GADZHI?
Iman Gadzhi is a British entrepreneur and YouTuber. He started a social-media marketing agency (IAG Media) as a teenager and went on to build online education businesses such as Educate.io, teaching agency owners, freelancers and video editors how to make money online. His YouTube channel is one of the most-copied in the business/self-improvement space, and a big reason is how it's edited.

🎨 THE "IMAN GADZHI STYLE", EXPLAINED
• Minimal and luxurious: lots of empty space, soft light backgrounds or subtle grids, nothing cluttered.
• Clean typography: thin sans-serif labels combined with bold numbers (Proxima Nova-type fonts).
• Data as storytelling: charts that grow, numbers that count up, cards and badges that pop in, so abstract ideas like "income" or "growth" become something you can see.
• Smooth, physical motion: everything eases in and out, bounces slightly, and has motion blur. Nothing just appears.
• Cinematic B-roll + calm, uplifting music: talking-head content made to feel like a documentary.
• Rounded corners, soft shadows, one strong accent color (often green for money). It looks like a premium app UI.
The result feels expensive, trustworthy and easy to watch, and that keeps viewers watching.

💼 WHO IS ALEX HORMOZI?
Alex Hormozi is an American entrepreneur and investor, founder of Acquisition.com (a firm that invests in and scales founder-led businesses) and author of the bestselling books "$100M Offers" and "$100M Leads". He's one of the biggest business educators online. His editing style is fast cuts every few seconds, punchy zoom-ins, bold word-by-word captions, sound effects and constant motion graphics that make every point visual. It created a whole industry of "Hormozi-style editors".

Iman is calm luxury and Hormozi is high energy, but they share one core thing: clean, data-driven motion graphics like the one we build today. If you can make this animation, you can work on content for both styles.

💰 WHY THIS MATTERS FOR YOU AS AN EDITOR
• It's what clients ask for. Business coaches, founders, finance creators and fintech brands all want "the Iman Gadzhi / Hormozi look".
• It's a premium upsell. A custom animated chart or number counter costs much more than a basic cut, and once you've built it you can reuse and restyle it for every client.
• It boosts retention. Moving visuals that show what the speaker is saying keep viewers watching longer, which is the number your clients care about.
• It makes your portfolio look expensive. One clean motion-graphics shot can set you apart from 100 editors who only do jump cuts and captions.

(At 4:47 I use an easing plugin to save time, but you can do the same easing manually in the Graph Editor. No plugin is required.)

If this helped, like, subscribe, and comment which creator's editing style I should break down next. I'm Makar, and this is Makar Edits.

#aftereffects #imangadzhi #motiongraphics #videoediting #alexhormozi
```

**Tags (YouTube tags field):**
`edit like iman gadzhi, iman gadzhi editing style, iman gadzhi after effects, iman gadzhi motion graphics, alex hormozi editing style, hormozi style editing, after effects tutorial, after effects chart animation, animated graph after effects, line graph animation, number counter after effects, trim paths after effects, after effects expressions, motion graphics tutorial, no plugins after effects, video editing tutorial, makar edits`
