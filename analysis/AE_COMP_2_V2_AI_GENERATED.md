# 🎬 AE Comp 2 V2 — Story Title (AI-Generated Style)
## Corona Screen → Zoom Out → Speed's PC + Room

> **New plan:** Mix AI-generated visuals + downloaded PC screen video
> **Why:** Faster, more control, unique visuals
> **Time:** 1.5-2 hours

---

## 🎯 THE CONCEPT (Simplified)

### Animation Flow:
```
0:00 → Corona bottle screen (AI-generated close-up)
0:00 → Speed face inside screen (AI-generated)
0:01 → Begin zoom out
0:02 → Screen pulls back to reveal it's on a TV/Monitor
0:02.5 → Zoom out more
0:03 → Reveal Speed's PC (DOWNLOADED VIDEO)
0:03.5 → Reveal Speed's room behind PC (AI-generated)
0:04 → Title "قصة سبيد" appears
0:04.5 → End
```

### Visual Layers (5 layers):
```
Layer 1 (Bottom): AI-generated room (background)
Layer 2: Downloaded PC screen video
Layer 3: AI-generated Speed face (inside screen)
Layer 4: AI-generated Corona screen frame
Layer 5 (Top): Text "قصة سبيد"
```

---

## 🖼️ AI-GENERATED ASSETS (Use generate_image tool)

### Asset 1: Corona Bottle Screen Close-Up
**For:** Starting frame (0:00 - 0:01)

**Prompt:**
```
Photorealistic extreme close-up of a Corona beer bottle screen 
with golden reflection, dark cinematic background, amber liquid 
visible through the glass, professional product photography, 
4K ultra HD, sharp focus on the bottle label area
```

**Generate:** 3-5 variations to choose the best one.

**File name:** `ai_corona_bottle_closeup.jpg`

---

### Asset 2: Speed's Face Inside the Screen
**For:** What's displayed on the Corona screen (0:00 - 0:01)

**Prompt:**
```
A young black male streamer (20 years old) at a gaming PC, 
streaming live, webcam view, excited expression, RGB lighting 
in background, gaming chair, dark room with neon glow, 
professional streaming setup visible
```

**Generate:** 3-5 variations

**File name:** `ai_speed_in_screen.jpg`

---

### Asset 3: TV/Monitor Frame at Angle
**For:** The screen pulling back (0:01 - 0:02)

**Prompt:**
```
Computer monitor screen showing a live stream on the display, 
slight angle from the side, RGB keyboard visible below, 
gaming desk setup, dark cinematic background with blue-purple 
lighting, sharp focus on screen, photorealistic, 4K
```

**Generate:** 3-5 variations

**File name:** `ai_monitor_angle.jpg`

---

### Asset 4: Speed's Streaming Room (Background)
**For:** Final reveal (0:03 - 0:04)

**Prompt:**
```
Modern gaming streaming room, gaming chair in center facing 
computer setup, multiple monitors, RGB lighting, professional 
streaming equipment, dark atmosphere with colorful neon accents, 
photorealistic, 4K ultra HD, empty room no people, cinematic
```

**Generate:** 3-5 variations

**File name:** `ai_streaming_room.jpg`

---

### Asset 5: Optional — Corona Logo Overlay
**For:** Brand accuracy on screen

**Prompt:**
```
Corona beer logo on transparent background, official branding, 
white and gold, high quality PNG, no background
```

**Generate:** 3-5 variations

**File name:** `ai_corona_logo.png`

---

## 📹 DOWNLOADED ASSET (Only 1!)

### Asset 6: Speed's PC Screen Video
**For:** The actual moment we pull back to reveal Speed's setup

**Search:**
- YouTube: `IShowSpeed gaming setup screen recording`
- YouTube: `IShowSpeed at computer`
- YouTube: `IShowSpeed streaming room tour`
- YouTube: `IShowSpeed screen capture gameplay`
- TikTok: `IShowSpeed setup`

**Best videos to search:**
```
1. "IShowSpeed setup tour 2024"
2. "IShowSpeed gaming room"
3. "IShowSpeed streaming PC screen"
4. "IShowSpeed back view at computer"
5. "IShowSpeed full setup show"
```

**Download:** 1-2 videos (30-60 sec each)

**File name:** `speed_pc_screen_video.mp4`

**Where to place:** Will be used at the reveal moment (0:02.5 - 0:03.5)

---

## 🎨 HOW TO USE THE AI-GENERATED IMAGES

### Method 1: As Static Images (Simplest)
1. Import all AI images to AE
2. Scale + Position each one
3. Animate zoom out
4. Use for the 4-second animation

### Method 2: As Layers with Camera Animation (Best)
1. Stack all AI images in 3D space
2. Use a 3D camera to zoom through them
3. Add motion blur
4. Adjust timing

### Method 3: Hybrid (Recommended)
1. Use AI images for beginning + middle
2. Cross-fade to downloaded Speed video
3. Use AI room as backdrop
4. Add text overlay at end

---

## 🔧 STEP-BY-STEP BUILD

### Step 1: Create New Composition (2 min)
```
1. Composition → New Composition
2. Name: "Story_Title_Speed"
3. Settings:
   - Resolution: 1920x1080
   - Frame rate: 30 fps
   - Duration: 5 seconds
4. Click OK
```

---

### Step 2: Add AI Room (Layer 1 — Bottom) (5 min)
```
1. File → Import → File
2. Select: ai_streaming_room.jpg
3. Drag to timeline (becomes Layer 1)
4. Scale to fit: S = 115%, Position center
5. This will be your final destination
```

---

### Step 3: Add Downloaded Speed Video (Layer 2) (5 min)
```
1. File → Import → File
2. Select: speed_pc_screen_video.mp4
3. Drag to timeline (above Layer 1)
4. Scale to 100%, Position center
5. Move to start at 0:02.5
6. This is what we'll reveal at 0:02.5
```

---

### Step 4: Add AI Corona Bottle (Layer 3) (5 min)
```
1. File → Import → File
2. Select: ai_corona_bottle_closeup.jpg
3. Drag to timeline (above Layer 2)
4. Position: center
5. Scale to 100%
6. This is our starting point
```

---

### Step 5: Add AI Monitor Frame (Layer 4) (5 min)
```
1. File → Import → File
2. Select: ai_monitor_angle.jpg
3. Drag to timeline (above Layer 3)
4. Position: center
5. Scale to 80%
6. This represents the TV screen view at 0:01
```

---

### Step 6: Add AI Speed Face (Layer 5 — Top) (5 min)
```
1. File → Import → File
2. Select: ai_speed_in_screen.jpg
3. Drag to timeline (top of all)
4. Scale to 300% (very close-up, filling screen)
5. Position: center
6. This is what we see ON the Corona screen at 0:00
```

---

### Step 7: Animate the Zoom Out (KEY PART) (45 min)

#### Keyframe animations for each layer:

**Layer 5 (AI Speed Face - on Corona screen):**
```
- 0:00: Scale = 300%, Position = center, Opacity = 100%
- 0:01: Scale = 250%, Position = center, Opacity = 100%
- 0:01.5: Scale = 150%, Opacity = 0%
(Reveals the monitor underneath)
```

**Layer 4 (AI Monitor Frame):**
```
- 0:00: Opacity = 0%
- 0:01: Opacity = 0%
- 0:01.5: Opacity = 100%, Scale = 80%
- 0:02: Opacity = 100%, Scale = 60%
- 0:02.5: Opacity = 0%
```

**Layer 3 (AI Corona Bottle):**
```
- 0:00: Opacity = 100%, Scale = 100%
- 0:01: Opacity = 80%, Scale = 120%
- 0:02: Opacity = 0%, Scale = 150%
(Fades away to reveal the monitor)
```

**Layer 2 (Downloaded Speed Video):**
```
- 0:00: Opacity = 0%
- 0:02.5: Opacity = 100%, Scale = 100%
- 0:04: Opacity = 100%
(Cross-fades in to be the revealed content)
```

**Layer 1 (AI Room Background):**
```
- 0:00: Scale = 120%, Opacity = 30%
- 0:04: Scale = 100%, Opacity = 100%
(Background gets sharper as we zoom in)
```

### Tips for keyframes:
- Select all keyframes → Right-click → Easy Ease (F9)
- This makes motion smooth (not robotic)
- Adjust keyframe spacing for speed control
- More keyframes = more control

---

### Step 8: Add Text "قصة سبيد" (10 min)

```
1. Type tool (T)
2. Click on canvas
3. Type: "قصة سبيد"
4. Settings:
   - Font: Bold Arabic (Cairo, Tajawal, or any)
   - Size: 120
   - Color: White
   - Center on canvas
5. Add stroke (for visibility):
   - Effect → Generate → Stroke
   - Stroke width: 3px
   - Color: Black or Gold (for Corona brand)
```

**Animate text:**
```
- 0:03: Opacity = 0%, Scale = 50%
- 0:03.5: Opacity = 100%, Scale = 110%
- 0:04: Opacity = 100%, Scale = 100%
- 0:04.5: Opacity = 100%
```

---

### Step 9: Add Effects (15 min)

#### Motion Blur (for cinematic feel):
```
1. Select all moving layers (V mark, not the layer switch)
2. Toggle Switches/Modes button at bottom of timeline
3. Click the "Motion Blur" icon (swirl) for each layer
4. This adds realistic blur during the zoom
```

#### Glow (for screen glow):
```
1. Select Layer 4 (monitor) and Layer 5 (Speed face)
2. Effect → Stylize → Glow
3. Settings:
   - Glow Threshold: 60%
   - Glow Radius: 15
   - Glow Intensity: 0.8
4. This makes the screen look like it's emitting light
```

#### Camera Shake (subtle):
```
1. Effect → Perspective → 3D Camera (if using 3D)
2. OR add wiggle:
   - Effect → Distort → Transform
   - Position: Set keyframes with slight movement
```

---

### Step 10: Color Grading (10 min)

```
1. Select Layer 1 (room background)
2. Effect → Lumetri Color
3. Settings for cinematic feel:
   - Contrast: +15
   - Highlights: -20
   - Shadows: +10
   - Saturation: +5
   - Temperature: +5 (warm/golden)
```

Apply same look to all other AI images for consistency.

---

### Step 11: Add Sound Effect (Optional, in Premiere)

When you import this comp to Premiere, add at:
- **0:00 - 0:01:** Subtle hum (Corona bottle ambiance)
- **0:01:** Whoosh (zoom start)
- **0:02:** Boom (reveal moment)
- **0:03:** Music swell (title appears)

---

### Step 12: Save & Render (5 min)

```
1. File → Save As
   - Name: Story_Title_Speed.aep
   - Location: 03_AFTER_EFFECTS/AE_Project/

2. Composition → Add to Render Queue

3. Output Module Settings:
   - Format: H.264
   - Quality: High

4. Output:
   - 02_SOURCE_VIDEO/AE_Exports/Story_Title_Speed.mp4

5. Click Render
```

---

## 📊 COMPLETE TIME ESTIMATE

| Step | Task | Time |
|---|---|---|
| 1 | Generate AI images (5 prompts) | 15-20 min |
| 2 | Download Speed video (1) | 5 min |
| 3 | Create comp | 2 min |
| 4 | Add Layer 1 (room) | 5 min |
| 5 | Add Layer 2 (Speed video) | 5 min |
| 6 | Add Layer 3 (Corona) | 5 min |
| 7 | Add Layer 4 (monitor) | 5 min |
| 8 | Add Layer 5 (Speed face) | 5 min |
| 9 | Animate keyframes | 30-45 min |
| 10 | Add text | 10 min |
| 11 | Add effects (blur, glow) | 15 min |
| 12 | Color grade | 10 min |
| 13 | Save + render | 5 min |
| **TOTAL** | | **2-2.5 hours** |

---

## 🎯 PRO TIPS FOR BETTER RESULTS

### Tip 1: Use one AI tool consistently
- All images should have similar style
- Generate from same AI (consistency)

### Tip 2: Match angles
- Corona close-up, monitor angle, room should all align
- If bottle is angled, monitor should be too

### Tip 3: Add subtle details
- Corona logo on bottle screen
- RGB glow on monitor
- Neon lights in room
- These add realism

### Tip 4: Use 3D layers for easier animation
- Click the 3D cube on each layer
- Then use Camera to zoom through them
- More realistic than just scaling

### Tip 5: Add audio (in Premiere)
- Sound effects matter as much as visuals
- Freesound.org for free SFX

---

## 🎬 IF IT'S NOT PERFECT (Alternatives)

### If AI images don't blend well:
- Add heavy Gaussian Blur to each
- Lower opacity to 50-70%
- Use as background only

### If zoom animation is choppy:
- Add more keyframes
- Use Easy Ease (F9) on ALL keyframes
- Reduce total zoom distance (150% → 100% not 300% → 100%)

### If text doesn't look good:
- Move text to layer ABOVE everything
- Add drop shadow (Effect → Perspective → Drop Shadow)
- Use different font (try Damavand, Majalla, or any bold Arabic)

---

## ✅ CHECKLIST

Before starting:

- [ ] AI images downloaded (5 images: Corona, Speed face, monitor, room, optional logo)
- [ ] Speed video downloaded (1 video)
- [ ] AE project open
- [ ] Composition created
- [ ] All layers added
- [ ] Keyframes animated
- [ ] Text added
- [ ] Effects applied (blur + glow)
- [ ] Comp rendered to MP4
- [ ] File saved

---

**Mix AI + real footage is the fastest path. Start generating!** 🔥
