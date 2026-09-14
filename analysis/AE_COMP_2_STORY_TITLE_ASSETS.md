# 🎬 AE Comp 2 — Story Title Animation
## "Inside Corona Screen → Zoom Out → Speed's Room"

> **Concept:** Start inside Corona bottle/screen → zoom out → reveal Speed's room
> **Duration:** 3-4 seconds
> **Style:** Cinematic zoom-out / "infinite zoom" effect

---

## 🎯 THE CONCEPT (Visual Breakdown)

### Timeline:
```
0:00 - Start: Inside the Corona bottle (close-up)
0:01 - Screen shows "Speed" playing inside the bottle
0:01.5 - Quick zoom out
0:02 - Now we're at the TV screen level
0:02.5 - Continue zooming out
0:03 - Reveal Speed's room (his back, PC, camera)
0:03.5 - Title "قصة سبيد" appears over the room
0:04 - End
```

### Detailed Visual Sequence:
```
Frame 1 (0:00): Corona bottle screen showing Speed's face
Frame 2 (0:01): Zoom starts pulling back
Frame 3 (0:01.5): Now we see the TV/monitor in Speed's room
Frame 4 (0:02): Speed's back view (sitting at PC)
Frame 5 (0:02.5): Full room reveal
Frame 6 (0:03): Title fades in
Frame 7 (0:04): Final frame with title + Speed
```

---

## 📥 ASSETS YOU NEED TO DOWNLOAD

### 1. Corona Beer Bottle/Screen Close-up (PRIMARY)

| What | Where to search | Type |
|---|---|---|
| **Corona beer bottle screen** | Pexels: "corona beer bottle" | Free stock |
| **Corona beer glass close-up** | Pexels: "beer bottle close up" | Free stock |
| **Beer bottle background** | Pixabay: "beer bottle screen" | Free stock |
| **Corona label bottle** | Shutterstock (paid) or free alternatives | High-res image |
| **TV monitor screen** | Pexels: "computer screen close" | Free stock |
| **Screen displaying content** | Pexels: "monitor displaying" | Free stock |

**Best free sources:**
- Pexels.com → search "corona"
- Pixabay.com → search "beer bottle"
- Unsplash.com → search "corona bottle"

### 2. Speed's Room/Setup Photos

| What | Where to search | Type |
|---|---|---|
| **Speed gaming setup back view** | Google: "IShowSpeed gaming setup" | Screenshot |
| **Speed's streaming room** | Google: "IShowSpeed room setup" | Screenshot |
| **Speed at PC back view** | Google: "IShowSpeed back view camera" | Screenshot |
| **Speed's PC and camera** | Google: "IShowSpeed streaming PC" | Screenshot |
| **Speed's full setup** | Google: "IShowSpeed room tour" | Video screenshot |

**How to get high-quality screenshots:**
1. Search Google Images for "IShowSpeed gaming setup"
2. Click on large image preview
3. Save full resolution
4. Or screenshot from YouTube videos

### 3. Speed's Face/Stream Image

| What | Where to search | Type |
|---|---|---|
| **Speed streaming screenshot** | Google: "IShowSpeed live stream screenshot" | Screenshot |
| **Speed face on monitor** | Google: "IShowSpeed face in screen" | Screenshot |
| **Speed webcam view** | Google: "IShowSpeed camera view" | Screenshot |

---

## 🎨 COMPLETE ASSET LIST (What to download)

### Priority 1: MUST HAVE
```
1. Corona bottle close-up (high-res image or 4K video)
   - Use as the "starting point" inside the bottle

2. Speed's face/wide-shot screenshot (high-res)
   - Use as the "content" inside the Corona screen

3. Speed's room/PC setup photo (high-res, back view)
   - Use as the "ending point" where we zoom out to

4. Speed's face (clean, centered) - optional
   - For additional zoom layer if needed
```

### Priority 2: NICE TO HAVE
```
5. Corona logo (transparent PNG)
   - For branding accuracy

6. Computer monitor/screen texture
   - For realistic screen effect

7. Speed's hand on mouse/keyboard
   - For foreground detail

8. RGB lighting/gaming setup
   - For room atmosphere
```

---

## 🔍 SPECIFIC SEARCH TERMS (Copy-Paste)

### For Corona Assets:
```
- "corona beer bottle screen close up"
- "corona beer bottle 4k"
- "corona beer label close up"
- "beer bottle screen overlay"
- "corona beer advertisement"
- "beer bottle product shot"
```

### For Speed's Setup:
```
- "IShowSpeed gaming setup 4k"
- "IShowSpeed streaming room"
- "IShowSpeed PC setup back view"
- "IShowSpeed setup tour"
- "IShowSpeed gaming room rgb"
- "IShowSpeed at computer back"
```

### For Speed's Stream:
```
- "IShowSpeed live screenshot"
- "IShowSpeed stream wide shot"
- "IShowSpeed webcam view"
- "IShowSpeed watching himself"
```

---

## 🎬 HOW TO BUILD THE COMP IN AFTER EFFECTS

### Step 1: Create New Composition
```
1. Composition → New Composition
2. Settings:
   - Name: "Story_Title_Speed"
   - Resolution: 1920x1080
   - Frame rate: 30 fps
   - Duration: 4 seconds
3. Click OK
```

### Step 2: Add Corona Bottle Background (Layer 1)
```
1. File → Import → File
2. Select Corona bottle image
3. Drag to timeline (this becomes Layer 1)
4. Scale to fit: S = 150
5. Position: Center it

This will be your zoom-out destination
```

### Step 3: Add TV/Monitor Frame (Layer 2)
```
1. Drag TV/monitor image on top (Layer 2)
2. Position: Center
3. Scale: 100%
4. Opacity: 100%
5. Add Mask:
   - Use Pen tool (G)
   - Draw mask around the screen area
   - Invert mask (Subtract) to hide everything except screen
6. This makes the monitor frame around our "content"
```

### Step 4: Add Speed's Image/Stream Screenshot (Layer 3)
```
1. Drag Speed's stream screenshot (Layer 3)
2. Position it inside the TV mask area
3. Scale to fit
4. This is what's "playing on the TV"
```

### Step 5: Add Speed's Room Photo (Layer 4)
```
1. Drag Speed's room/setup photo (Layer 4)
2. Position: Center
3. Scale: 100%
4. Move layer to BOTTOM (below all others)
5. This is the "big picture" we zoom out to
```

### Step 6: Add Text Title (Layer 5)
```
1. Type tool (T)
2. Click on canvas
3. Type: "قصة سبيد"
4. Font: Bold Arabic (Cairo, Tajawal, or similar)
5. Size: 120
6. Color: White
7. Center on canvas
8. Add stroke (for visibility)
```

### Step 7: Animate the Zoom Out (KEY PART)

#### Option A: Position + Scale Keyframes (Simple)

```
Layer 4 (Speed's room - the destination):
- This stays still

Layer 3 (Speed's stream screenshot - INSIDE):
- 0:00: Scale = 200%, Position = Center
- 0:02: Scale = 100%, Position = Center
- 0:04: Scale = 50%, Position = Center
- Ease: Easy Ease

Layer 2 (TV/Monitor):
- 0:02: Scale = 100%, Position = Center
- 0:04: Scale = 50%, Position = Center

Layer 1 (Corona bottle):
- 0:00: Opacity = 0%
- 0:00.5: Opacity = 0%
- 0:01: Opacity = 100%
- 0:02: Scale = 150%, Opacity = 100%
- 0:02.5: Scale = 100%, Opacity = 80%
- 0:03: Scale = 50%, Opacity = 0%

This creates: Start tiny on corona → zoom out → reveal TV → reveal room
```

#### Option B: Better Method (3D Camera + Position)

```
1. Enable 3D on all layers (click the 3D cube icon)

2. Create Camera:
   - Layer → New → Camera
   - Type: Two-Node Camera
   - Settings: 50mm

3. Animate camera position:
   - 0:00: Z = 1500 (very close to Corona bottle)
   - 0:02: Z = 1000 (zooming out a bit)
   - 0:04: Z = 500 (back to show full room)

4. Animate camera point of interest:
   - 0:00: At Corona bottle position
   - 0:02: At TV position
   - 0:04: At Speed's room
```

#### Option C: EASIEST (Single Layer Zoom)

```
1. Use ONLY Layer 4 (Speed's room)
2. Animate scale + position:
   - 0:00: Scale = 800%, Position = focused on PC screen
   - 0:04: Scale = 100%, Position = full room view

3. Add a "fake" starting image (Corona overlay) that disappears
   - Create a black solid
   - Add Corona bottle image
   - Scale to 200%
   - Opacity: 100% → 0% (fades out as we zoom out)

This is the simplest "infinite zoom" effect
```

### Step 8: Animate Text Title

```
For the "قصة سبيد" text:
1. Move playhead to 0:02
2. Set Opacity = 0%
3. Move playhead to 0:03
4. Set Opacity = 100%
5. Move playhead to 0:04
6. Set Opacity = 100%

Add Scale animation:
1. At 0:02: Scale = 50%
2. At 0:03: Scale = 110% (overshoot)
3. At 0:03.5: Scale = 100% (settle)
```

### Step 9: Add Motion Blur (Optional but Recommended)

```
1. Select all moving layers
2. Check "Motion Blur" (the swirl icon)
3. This adds realistic blur during the zoom
```

### Step 10: Save and Export

```
1. File → Save As → "Story_Title_Speed.aep"
   - Location: 03_AFTER_EFFECTS/AE_Project/
2. Composition → Add to Render Queue
3. Settings:
   - Format: H.264
   - Output: 02_SOURCE_VIDEO/AE_Exports/Story_Title_Speed.mp4
4. Click Render
```

---

## 🎯 PRO TIPS FOR BETTER RESULTS

### Tip 1: Match the perspective
- Corona bottle → TV screen → Room should all have the SAME angle
- Use images shot from the same angle/perspective
- If camera was zooming OUT, all images should look "from the same viewpoint"

### Tip 2: Use consistent lighting
- All images should have similar color temperature
- If room is warm-lit, Corona screen should be warm too

### Tip 3: Add transition effects
- Use Camera-Shake effect during zoom (subtle)
- Add Glow effect (for screen glow)
- Use Light Leak overlays (free from YouTube)

### Tip 4: Sound effects (when placing in Premiere)
- Add "whoosh" zoom sound at 0:01
- Add "boom" reveal at 0:03
- Add "music swell" as title appears

### Tip 5: Save incremental versions
```
- Story_Title_v1.aep (first try)
- Story_Title_v2.aep (after fixing)
- Story_Title_FINAL.aep (after approval)
```

---

## 🛠️ TROUBLESHOOTING (Common Issues)

### Issue 1: Zoom looks flat / unrealistic
**Fix:** Add motion blur + slight camera shake
```
- Effect → Time → Timewarp (for smooth speed)
- Effect → Perspective → 3D Camera (if not using 3D layers)
```

### Issue 2: Images don't blend
**Fix:** Add fade transitions between layers
```
- Each layer: Opacity 0% → 100% → 0% (with overlap)
- Cross-dissolve between zoom stages
```

### Issue 3: Text not visible
**Fix:** Add a dark semi-transparent background under text
```
1. Layer → New → Solid (black)
2. Opacity = 50%
3. Place behind text (Layer 4)
```

### Issue 4: Corona screen looks fake
**Fix:** Use real product photo + apply screen effect
```
- Effect → Simulation → CC Sphere (for wraparound screen)
- Or use a curved surface mapping
```

### Issue 5: Video too short/long
**Fix:** Adjust keyframe positions, OR change comp duration
```
- Composition → Composition Settings → Duration
- Extend to 5 sec if needed
```

---

## 🎬 ALTERNATIVE: Use Templates (Faster)

If building from scratch is too complex, USE TEMPLATES:

### Best templates for "infinite zoom":
1. **Motion Array:** Search "infinite zoom intro"
2. **Envato Elements:** Search "zoom out reveal"
3. **Mixkit (free):** Search "zoom out intro"

### How to customize:
1. Download template
2. Replace placeholder images with your:
   - Corona bottle (first frame)
   - Speed's stream screenshot (inside screen)
   - Speed's room (final reveal)
3. Replace text with "قصة سبيد"
4. Adjust timing
5. Render

**Time saved:** 2-3 hours

---

## 📊 COMPLETE WORKFLOW FOR THIS COMP

| Step | What | Time |
|---|---|---|
| 1 | Download Corona assets | 10 min |
| 2 | Download Speed room assets | 10 min |
| 3 | Create composition | 5 min |
| 4 | Add Corona layer | 10 min |
| 5 | Add TV monitor layer | 15 min |
| 6 | Add Speed stream layer | 15 min |
| 7 | Add Speed room layer | 10 min |
| 8 | Add text title | 10 min |
| 9 | Animate zoom out | 30 min |
| 10 | Animate text appearance | 10 min |
| 11 | Add effects (blur, glow) | 10 min |
| 12 | Preview + adjust | 15 min |
| 13 | Render | 5 min |
| **TOTAL** | | **2.5-3 hours** |

---

## ✅ DOWNLOAD CHECKLIST

Before starting this comp, make sure you have:

### Corona Assets:
```
☐ Corona bottle close-up image (high-res)
☐ OR Corona bottle 4K video
☐ Optional: Corona logo PNG (transparent)
```

### Speed Assets:
```
☐ Speed stream screenshot (high-res, 1920x1080+)
☐ Speed's room/setup photo (high-res, back view)
☐ Speed's PC + camera angle (clear image)
☐ Optional: Speed's face (for layered zoom)
```

### Backup Plan:
```
If you can't find good Corona assets, you can use:
- Any TV monitor at close-up angle
- Any product bottle at close-up angle
- Phone screen showing content
The concept is "infinite zoom" — the specific image matters less
```

---

## 🎯 START HERE

### Right now (first 5 minutes):
1. Open Google
2. Search: "corona beer bottle close up"
3. Click "Images" tab
4. Filter "Large" size
5. Save 3-5 options
6. Search: "IShowSpeed gaming setup back"
7. Save 3-5 options
8. Open After Effects
9. Start building!

---

**Save this guide and start building. You've got this!** 🔥
