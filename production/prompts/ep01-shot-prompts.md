# EP01 Shot Prompts

The exact prompts used to make keyframes and video for Episode 1, one section per shot.
Shot ids match [production/shotlists/ep01.csv](../shotlists/ep01.csv). The style follows [bible/style.md](../../bible/style.md).

Prompts never name a studio, a film or a creator. They describe the traits instead.

## Index

| Shot | Scene | Step | Tool | Status |
|---|---|---|---|---|
| [E01-S001-SH130](#e01-s001-sh130) | E01-001, journey 2 of 4 | First keyframe | Nano Banana | v2 (inland), not retested |
| [E01-S001-SH130](#e01-s001-sh130) | E01-001, journey 2 of 4 | Last keyframe | Nano Banana (edit of the first keyframe) | v2 (inland), not retested |
| [E01-S001-SH130](#e01-s001-sh130) | E01-001, journey 2 of 4 | Video | Runway | Test 1 failed (start area read as sea); v2 (inland), not retested |

Status values: `not tested` → `tested` (with a note on the result) → `approved`.

---

## E01-S001-SH130

- **Scene:** E01-001, EXT. CITY INTERSECTION - NIGHT (Universe B). The second of the four journey shots that carry the
  camera from the wreck to the spiritual dimension.
- **Script:** "It keeps rising. Faster. The city shrinks to a scatter of lights. The curve of the Earth falls away."
- **Planned length:** 3 s. Generate 5 s and speed it up in the edit.
- **Camera:** looks forward and slightly upward for the whole shot, so the sky fills most of the frame and the world
  sits in a band at the bottom. It rises straight up and accelerates.
- **Continuity:** the first keyframe is also the last frame of E01-S001-SH120. The last keyframe is also the first
  frame of E01-S001-SH140. No ember-blue glow here: it belongs to E01-S001-SH150.

### First keyframe (Nano Banana)

Just above the city rooftops. Night sky in most of the frame, the skyline in a narrow band at the bottom.

```
A single frame from a stylized 3D animated feature film. Wide 16:9 landscape image.

The camera floats just above the rooftops of a mid-sized American city at night and looks forward and slightly upward, so the night sky fills the upper 85 percent of the frame.

Sky: a deep, desaturated charcoal-navy night sky with a smooth, soft gradient, slightly lighter near the horizon. A few small, crisp, round stars of slightly varied size, sparse because of the city's light. A thin layer of soft, sculpted clouds drifts high above, simplified into smooth rounded volumes, lit faintly from below by the city in a warm grey tone. No moon.

Bottom 15 percent of the frame: a flat horizon line with the simplified silhouettes of low and mid-rise buildings, seen from slightly above. Small warm amber windows and streetlights, soft and matte. Rooftops are still damp from recent rain and carry a gentle sheen. The city lies deep inland on a wide plain: its lights continue all the way to the horizon, with no sea, no lake, no river, no harbor and no coastline anywhere. The city is generic: no landmarks, no signs, no lettering, no logos.

Style: stylized 3D animation with moderately simplified shapes, clean smooth surfaces, soft naturalistic lighting and gentle shadows. Everything is slightly simplified rather than photorealistic. Clean image: no film grain, no lens flare, no bloom, no glow effects, no vignette.

Color: muted and calm. Charcoal, warm grey, soft navy, small amber accents. No saturated or electric blue anywhere.

The frame contains no people, no vehicles, no aircraft, no text and no watermark.
```

### Last keyframe (Nano Banana, as an edit)

At the edge of space. Generate it by uploading the approved first keyframe as the reference image, so the style,
the stars and the colors stay identical.

```
Use the attached image as the exact style reference: the same stylized 3D animated film look, the same star shapes, the same color palette and the same clean render. Create a new frame from the same camera, facing the same direction, after it has risen straight up to the edge of space. Wide 16:9 landscape image.

The camera still looks forward and slightly upward. Space fills the upper 75 percent of the frame: near-black with a very soft charcoal-navy tint, filled with many small, crisp, round stars of slightly varied size, far more than before, evenly scattered. No moon, no sun, no nebula, no galaxy.

Bottom 25 percent of the frame: the curved edge of the Earth, a smooth, gentle arc running from the left edge to the right edge, highest in the center. Everything visible below is land: the interior of a large continent at night, stretching unbroken from the left edge to the right edge and all the way to the curved horizon. There is no ocean, no sea, no coastline, no island and no large lake anywhere in the frame. The land is a dark warm grey-brown, clearly lighter than the black of space, with faint simplified terrain: broad plains and a few low ridges. A few soft cloud patches float far below, smooth and sculpted. City lights are spread across the whole width of the land as many small clusters of tiny warm amber points, joined by faint thin threads of road lights, like a web. One slightly denser cluster sits at the bottom center, where the city was, surrounded by smaller towns on every side.

Along the curve lies a very thin, soft band of pale grey-blue atmosphere, matte and subtle, like a fine line of haze. It does not glow.

Style: stylized 3D animation with simplified shapes, clean smooth surfaces and soft gradients, slightly simplified rather than photorealistic. Clean image: no film grain, no lens flare, no bloom, no glow effects, no vignette.

Color: muted and calm. Near-black, charcoal, soft navy, small amber accents. No saturated or electric blue anywhere.

The frame contains no satellites, no spacecraft, no people, no text and no watermark.
```

### Video (Runway)

Both keyframes are given to Runway. The first three paragraphs tell the model which image is which by its content,
so it cannot run the move backward. If the interface has separate first-frame and last-frame slots, use them and
delete those three paragraphs.

```
Two reference images define this shot.

START IMAGE: the one with a flat horizon and a city skyline of small buildings along the bottom edge, under a night sky with only a few stars. The video begins on exactly this image.

END IMAGE: the one with the curved edge of the Earth along the bottom and a black sky full of stars. The video finishes on exactly this image.

The shot moves from the START IMAGE to the END IMAGE, never the other way: the camera goes up, away from the city, and ends in space.

The camera rises straight up in one continuous, smooth move that keeps accelerating, from just above the city rooftops to the edge of space. It faces forward and slightly upward the whole time, without turning or tilting.

The skyline drops toward the bottom of the frame. Thin clouds rush downward past the camera and fall away below. The city lies deep inland, in the middle of a large continent. As the camera rises, more and more land comes into view around it on every side: neighboring towns, a web of road lights, dark plains. The ground below is land the whole time, from start to finish. No ocean, sea or coastline ever appears. The city lights shrink into one small cluster among many across the continent. The flat horizon bends into the curve of the planet and settles low in the frame. The sky darkens to black and more and more stars appear, sharp and steady.

Stylized 3D animation, clean smooth surfaces, soft light. One continuous shot. Speed builds steadily from slow to very fast.
```

### Test log

- **2026-11-17, test 1 (author):** the video came out wrong: the area the shot starts from appeared to be in the
  middle of the sea. Fix: all three prompts now state that the city is deep inland in a large continent, that the
  ground is land in every direction for the whole shot, and that no ocean or coastline ever appears. The last
  keyframe also makes the land lighter than space and spreads city lights across its whole width, so the dark
  surface cannot be read as water. Not yet retested.

### What to check in the result

- The move runs upward, from the city to space.
- The ground is land the whole way: no sea, no coastline, at any moment of the clip.
- The stars do not flicker. The curve of the Earth forms gradually and does not jump.
- No blue glow anywhere.
- The clip opens and closes on the two keyframes exactly. Reference images only guide the look; keyframes pin the
  first and last frame. If the clip does not land on them, the shared frames with SH120 and SH140 will not match.

### Before this goes into the episode

- Nano Banana and Runway are not on the plan's list of approved tools. Confirm that the plan in use allows commercial
  use of the output.
- Both keyframes must have the same 16:9 ratio and resolution.
