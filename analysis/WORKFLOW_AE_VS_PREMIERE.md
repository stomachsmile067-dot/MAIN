# 🎬 WORKFLOW GUIDE — Premiere Pro vs After Effects
## Where to use what, when, and how

> **Who this is for:** You know the tools but struggle with the workflow.
> **Goal:** Make it obvious what goes where BEFORE you start editing.
> **Result:** No more "should I do this in AE or Premiere?" confusion.

---

## 🎯 THE GOLDEN RULE (مهم جداً جداً)

| Software | Purpose | Question to ask |
|---|---|---|
| **Premiere Pro** | CUTTING + TIMING | "Am I putting clips in order?" |
| **After Effects** | EFFECTS + ANIMATION | "Am I MAKING something that doesn't exist yet?" |

### ✅ If answer is "just arranging clips" → **Premiere**
### ✅ If answer is "I need to ADD/CHANGE something visual" → **After Effects**

---

## 🧠 SIMPLE MENTAL MODEL

Think of it like a cooking show:

| | Premiere | After Effects |
|---|---|---|
| **Chef's role** | 🥘 Plating the dish | 🎨 Making the sauce from scratch |
| **You do** | Arrange clips + audio | Create motion graphics, text, transitions, effects |
| **Takes time** | Less (you have clips ready) | More (you CREATE new visuals) |
| **File size** | Big (source files) | Bigger (comps + assets) |

**The 80/20 rule:** 80% of your video = Premiere. 20% = After Effects.

---

## 📂 STEP-BY-STEP WORKFLOW (Pipeline)

```
Step 1:  PREP (Not editing yet)
            ↓
Step 2:  PRE-EDIT in Premiere (rough cut)
            ↓
Step 3:  CREATE in After Effects (graphics, text, effects)
            ↓
Step 4:  COMPOSITE in Premiere (combine everything)
            ↓
Step 5:  POLISH in Premiere (color, audio, fine cuts)
            ↓
Step 6:  EXPORT
```

---

## 📁 STEP 1 — PREP (The most important step!)

**Do this BEFORE you open Premiere.**

### Create these folders:
```
📁 PROJECT_NAME/
├── 📁 01_PREMIERE_PROJECT/        (your .prproj file)
├── 📁 02_SOURCE_VIDEO/            
│   ├── 📁 Speed_Clips/             (downloaded streams)
│   ├── 📁 Free_Footage/            (Pexels, Pixabay, etc.)
│   └── 📁 Audio/                   (music, SFX)
├── 📁 03_AFTER_EFFECTS/           
│   ├── 📁 AE_Project/              (your .aep file)
│   └── 📁 AE_Assets/               (logos, graphics, fonts)
├── 📁 04_EXPORTS/                  (rendered AE videos)
├── 📁 05_FINAL/                    (final video file)
└── 📄 SCRIPT.md                    (your Saudi script with timestamps)
```

### Naming convention (use this!):
```
Speed_01_homeless_intro.mp4
Speed_02_zero_viewers.mp4
Speed_03_mom_kicks_out.mp4
Free_01_cincinnati_street.mp4
Free_02_crowd_cheering.mp4
SFX_siren.mp3
Music_epic_build.mp3
```

**Why this matters:** You'll save HOURS of searching later.

---

## 🎬 STEP 2 — PRE-EDIT IN PREMIERE (Rough cut)

This is where 80% of your work happens.

### What to do in Premiere:
✅ Import all footage
✅ Lay clips on timeline in order
✅ Cut clips to match script
✅ Add B-roll (free footage) on top
✅ Sync music to scenes
✅ Rough timing
✅ Add captions/subtitles

### What NOT to do in Premiere (yet):
❌ Don't add fancy text animations
❌ Don't make complex transitions
❌ Don't add particle effects
❌ Don't color grade (final)
❌ Don't add motion graphics

### Premiere Timeline setup:
```
🎬 V1: Main video (Speed clips or main B-roll)
🎬 V2: B-roll (free footage overlay)
🎬 V3: Picture-in-picture (small Speed on side)
🎬 V4: Text titles (simple)
🎵 A1: Voiceover (your Saudi narration)
🎵 A2: Music
🎵 A3: SFX (sirens, impact, etc.)
```

### Rough cut checklist:
- [ ] All chapters from script are on timeline
- [ ] Total length is 12-14 min
- [ ] Voiceover syncs with visuals (rough)
- [ ] Music fits mood per chapter
- [ ] Each chapter has 2-3 B-roll cuts

---

## ✨ STEP 3 — CREATE IN AFTER EFFECTS (Graphics + effects)

This is where you make things that DON'T EXIST yet.

### When to use After Effects:

| Use case | Example |
|---|---|
| **Animated text** | Title card "قصة سبيد" flying in |
| **Lower thirds** | Name "Kai Cenat" with bar |
| **Counters** | Subscriber count going from 0 → 30M |
| **Maps** | Pin moving from USA → China → World |
| **Subscribe button animation** | Bell ringing |
| **Custom transitions** | Page flip, glitch, zoom |
| **Particle effects** | Confetti, sparks, dust |
| **Logo intro** | Channel logo at start |
| **Charts/graphs** | Viewer growth chart |
| **Fake screens** | Phone screen, social media post |
| **Stickers/emojis** | Floating 😭 😱 🔥 |
| **Subtitle styles** | Pop subtitles (TikTok style) |
| **Motion tracking** | Text following Speed's face |
| **Speed ramp** | Slow-mo + zoom on a moment |
| **Color pop** | Make one object colorful in B&W video |
| **Picture-in-picture** | Two videos on screen with custom frame |

### ⛔ When NOT to use After Effects:

| Don't do this in AE | Do it in Premiere instead |
|---|---|
| Just cutting a clip | ✅ Premiere (way faster) |
| Cross dissolve | ✅ Premiere (Ctrl/Cmd + D) |
| Lifting audio levels | ✅ Premiere |
| Adding captions to whole video | ✅ Premiere (auto caption) |
| Color correction | ✅ Premiere (Lumetri) |
| Speed change (constant) | ✅ Premiere (right-click → speed) |

### AE workflow for our Speed video:

#### **Scene 1: Hook (Before/After)**
**What you need:** Split screen with Speed kid vs Speed on stage
- This is just a split screen in Premiere (Effect Controls → Crop)
- **Premiere, not AE.** Skip AE here.

#### **Scene 2: Counter animation (0 → 30M)**
**What you need:** Number animating from 0 to 30,000,000
- This needs keyframes → **After Effects**
- OR use **Premiere** (Essential Graphics → simple text animation)

#### **Scene 3: Map showing Speed's world tour**
**What you need:** World map with pin moving to different countries
- **After Effects** (use a map image + position keyframes)
- OR use **Premiere** (still map with arrow overlay)

#### **Scene 4: Title cards per chapter**
**What you need:** "CHAPTER 1", "CHAPTER 2" with animation
- **After Effects** (fancy version with motion)
- OR **Premiere** (simple text + fade)

#### **Scene 5: Subscribe bell animation**
**What you need:** Bell that rings at end
- **After Effects** (you need to animate the bell)
- OR use a pre-made free template (Motion Array, Envato)

---

## 🎨 COMMON SCENES — What to use for each:

### For the SPEED VIDEO (SCRIPT 05), here's the exact split:

| Scene | Software | Why | Difficulty |
|---|---|---|---|
| Hook (split screen) | **Premiere** | Just crop | Easy |
| Chapter 1 (who is Speed) | **Premiere** | B-roll + text | Easy |
| Chapter 2 (zero viewers) | **Premiere** | Number counter (use template) | Easy |
| Chapter 3 (mom vs Speed) | **Premiere** | Clips + captions | Easy |
| Chapter 4 (the question) | **Premiere + AE** | Need censored blur overlay | Medium |
| Chapter 5 ($2 donation) | **Premiere** | Just clip + zoom | Easy |
| Chapter 6 (humanity) | **Premiere** | Emotional B-roll | Easy |
| Chapter 7 (China tour) | **Premiere** | Map + clips | Easy |
| Chapter 8 (World Cup) | **Premiere** | Stage + crowd | Easy |
| Counter (subscribers 0 → 30M) | **AE** | Number animation | Medium |
| World map (tour route) | **AE** | Position keyframes | Medium |
| Title cards per chapter | **AE** | Text animation | Easy |
| End screen / Subscribe | **AE or template** | Animation | Easy |
| Glitch transitions | **AE** | Particle effect | Hard |

---

## 🔧 PRACTICAL: HOW TO MOVE BETWEEN PREMIERE AND AE

### Method 1: Dynamic Link (BEST for beginners)
```
1. In Premiere, right-click a clip
2. "Replace with After Effects Composition"
3. AE opens automatically
4. Edit in AE
5. Save (Ctrl+S)
6. Back in Premiere, the clip updates AUTOMATICALLY
```
**No exporting needed!** This is the magic of Dynamic Link.

### Method 2: Export from AE → Import to Premiere
```
Use this when:
- The AE comp is long (10+ min)
- You want to free up computer RAM
- Dynamic Link is lagging

Steps:
1. In AE: Composition → Add to Render Queue
2. Output: H.264, Full resolution
3. Click Render
4. Drag the .mp4 back to Premiere
```

---

## 💻 COMPUTER POWER (Real talk)

| Software | RAM needed | GPU | Slows down when |
|---|---|---|---|
| **Premiere** | 8GB min (16GB better) | Yes helps | Many 4K clips, long timeline |
| **After Effects** | 16GB min (32GB better) | Yes critical | Particle effects, 3D, long comps |

**If your PC struggles:** Work on lower resolution proxies.
- Premiere: Project Settings → Ingest Settings → Create Proxies
- This makes editing smooth even on slow PCs

---

## 📋 COMPLETE WORKFLOW FOR SPEED VIDEO (Step by step)

### Day 1: PREP (1-2 hours)
```
☐ Create folder structure (above)
☐ Download all Speed clips from YouTube + wayback
☐ Download 30-50 free B-roll clips from Pexels
☐ Download music (Epidemic Sound, Artlist, or free)
☐ Download SFX (Freesound.org)
☐ Read script + mark which line needs which visual
```

### Day 2: PRE-EDIT IN PREMIERE (3-4 hours)
```
☐ Create new Premiere project
☐ Import all footage
☐ Build timeline per chapter:
    - V1: Speed clip / main visual
    - V2: B-roll overlay (when Speed clip is missing)
    - V3: Picture-in-picture (when needed)
    - V4: Simple text
☐ Add voiceover to A1
☐ Add music to A2
☐ Add SFX to A3
☐ Rough timing only (don't perfect yet)
```

### Day 3: AFTER EFFECTS (2-3 hours)
```
☐ Open AE, create compositions:
    - "01_Subscribe_Counter" (30 sec)
    - "02_World_Map" (2 min)
    - "03_Chapter_Title_01" through "08_Chapter_Title_08" (10 sec each)
    - "09_End_Screen" (30 sec)
☐ Build each comp
☐ Use Dynamic Link to bring into Premiere
☐ OR export and import
```

### Day 4: POLISH IN PREMIERE (2-3 hours)
```
☐ Fine cut timing (each cut exactly matches voice)
☐ Add transitions (use simple ones: cross dissolve, dip to black)
☐ Color grade (Lumetri → simple look: cinematic OR warm OR cold)
☐ Audio mix (voice louder, music lower, SFX balanced)
☐ Add final captions (auto + manual fix)
☐ Final review: watch whole video
```

### Day 5: EXPORT (30 min)
```
☐ Export settings:
    - Format: H.264
    - Resolution: 1920x1080 (or 4K if source allows)
    - Frame rate: 30 fps (or 60 for gaming videos)
    - Bitrate: 15-25 Mbps
☐ Export to 05_FINAL folder
☐ Watch full video on phone
☐ Upload to YouTube
```

---

## 🆓 FREE TOOLS THAT HELP

| Tool | Use | Link |
|---|---|---|
| **Pexels** | Free stock videos | pexels.com |
| **Pixabay** | Free stock videos | pixabay.com |
| **Freesound** | Free SFX | freesound.org |
| **Epidemic Sound** (paid) | Best music | epidemicsound.com |
| **YouTube Audio Library** | Free music | studio.youtube.com |
| **Motion Array** (paid) | AE templates | motionarray.com |
| **Envato Elements** (paid) | AE templates + music | elements.envato.com |
| **4K Video Downloader** | Download YouTube clips | 4kdownload.com |
| **HandBrake** | Compress videos | handbrake.fr |

---

## 🎓 TEMPLATES THAT SAVE YOU HOURS

If you're new to AE, USE TEMPLATES instead of building from scratch:

1. **Subscribe counter** (number going up)
   - Search: "subscriber counter after effects"
   - Customize with your numbers
   
2. **Map with route**
   - Search: "world map animation after effects"
   - Drop in your pins

3. **Subscribe button**
   - Search: "subscribe bell animation after effects"
   - Done in 1 minute

4. **Title cards**
   - Search: "kinetic typography after effects"
   - Edit text

5. **Glitch transitions**
   - Search: "glitch transition after effects"
   - Drag between clips

**Why this matters:** You learn AE by editing templates, not building from zero.

---

## ⚠️ COMMON MISTAKES (Avoid these!)

| Mistake | Fix |
|---|---|
| Doing everything in AE | Keep 80% in Premiere |
| Using AE for simple cuts | Use Premiere |
| Not using Dynamic Link | Use it! (saves HOURS) |
| Working on 4K source without proxies | Use proxies |
| Adding music too loud | Voice = 0dB, Music = -12 to -18dB |
| No naming convention | Use the naming above |
| Forgetting to backup | Use Google Drive / external drive |

---

## ✅ FINAL ANSWER TO YOUR QUESTION

**"What should I make in After Effects?"**

### Make these in After Effects:
1. ✅ Animated counters (subscribers, money, viewers)
2. ✅ Maps with routes
3. ✅ Animated title cards per chapter
4. ✅ Subscribe bell / end screen animation
5. ✅ Glitch transitions
6. ✅ Custom lower thirds
7. ✅ Picture-in-picture with custom frame
8. ✅ Particle effects (confetti, dust)

### Keep these in Premiere:
1. ✅ All clip cutting
2. ✅ All B-roll placement
3. ✅ All transitions (simple ones)
4. ✅ Music + SFX sync
5. ✅ Captions
6. ✅ Color grading
7. ✅ Audio mixing
8. ✅ Simple text titles
9. ✅ Split screens
10. ✅ Speed changes (constant)

---

## 🎬 SIMPLIFIED DECISION TREE

```
Is it an effect that MOVES or ANIMATES?
├── YES → After Effects
└── NO
    │
    Is it just placing a clip in order?
    ├── YES → Premiere
    └── NO
        │
        Is it text on screen?
        ├── YES, animated → AE
        ├── YES, simple → Premiere
        └── NO → It's probably not needed 😅
```

---

## 🚀 QUICK START (For your Speed video)

**If you're overwhelmed, do this minimum:**

1. **Premiere only (no AE):**
   - Cut all clips
   - Add B-roll
   - Add voiceover
   - Add music
   - Add simple text (chapter titles)
   - Export

2. **Then add AE (optional, polish):**
   - 1 counter animation (subscribers)
   - 1 title card per chapter
   - 1 end screen

**That's it.** You don't need 50 effects. Good editing > fancy effects.

---

## 📁 Save this file

**File:** `WORKFLOW_AE_VS_PREMIERE.md`
**Location:** `analysis/`
**Use this:** Every time you start a new video.

Good luck! 🔥
