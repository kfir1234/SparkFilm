# EP01 Shot Prompts

The exact prompts used to make keyframes and video for Episode 1, one section per shot.
Shot ids match [production/shotlists/ep01.csv](../shotlists/ep01.csv). The style follows [bible/style.md](../../bible/style.md).

Prompts never name a studio, a film or a creator. They describe the traits instead.

## Index

| Shot | Scene | Step | Tool | Status |
|---|---|---|---|---|
| [E01-S001-SH010](#e01-s001-sh010) | E01-001, opening shot | Keyframe (held still, no video) | Nano Banana | not tested |
| [E01-S001-SH020](#e01-s001-sh020) | E01-001, the SUV tumbles in | First keyframe | The SH010 keyframe, unchanged | — |
| [E01-S001-SH020](#e01-s001-sh020) | E01-001, the SUV tumbles in | Last keyframe | Nano Banana (edit of the SH010 keyframe) | not tested |
| [E01-S001-SH020](#e01-s001-sh020) | E01-001, the SUV tumbles in | Video | Runway | not tested |
| [E01-S001-SH030](#e01-s001-sh030) | E01-001, the wreck from street level | First keyframe | Nano Banana (reference: the SH020 last keyframe) | not tested |
| [E01-S001-SH030](#e01-s001-sh030) | E01-001, the wreck from street level | Last keyframe | Dropped | Two tests failed (no change of angle; then the buildings moved) |
| [E01-S001-SH030](#e01-s001-sh030) | E01-001, the wreck from street level | Video | Seedance (first keyframe only) | not tested |
| [E01-S001-SH060](#e01-s001-sh060) | E01-001, the emergency lights arrive | First keyframe | The last frame of the SH030 video | — |
| [E01-S001-SH060](#e01-s001-sh060) | E01-001, the emergency lights arrive | Video | Seedance (first keyframe only) | not tested |
| [E01-S001-SH130](#e01-s001-sh130) | E01-001, journey 2 of 4 | First keyframe | Nano Banana | v2 (inland), not retested |
| [E01-S001-SH130](#e01-s001-sh130) | E01-001, journey 2 of 4 | Last keyframe | Nano Banana (edit of the first keyframe) | v2 (inland), not retested |
| [E01-S001-SH130](#e01-s001-sh130) | E01-001, journey 2 of 4 | Video | Runway | Test 1 failed (start area read as sea); v2 (inland), not retested |
| [E01-S001-SH140](#e01-s001-sh140) | E01-001, journey 3 of 4 | Last keyframe | Nano Banana (edit of the SH130 last keyframe) | not tested |
| [E01-S001-SH140](#e01-s001-sh140) | E01-001, journey 3 of 4 | Video | Runway | not tested |
| [E01-S001-SH150](#e01-s001-sh150) | E01-001, journey 4 of 4 | Last keyframe | Nano Banana (no reference image) | not tested |
| [E01-S001-SH150](#e01-s001-sh150) | E01-001, journey 4 of 4 | Video | Runway | not tested |

Status values: `not tested` → `tested` (with a note on the result) → `approved`.

---

## E01-S001-SH010

- **Scene:** E01-001, EXT. CITY INTERSECTION - NIGHT (Universe B). The first shot of the film.
- **Planned length:** 3 s.
- **Camera:** extreme wide, high angle, static. Plate A of
  [bible/locations/city-intersection.md](../../bible/locations/city-intersection.md).
- **No video is generated for this shot (author's decision, 2026-11-18).** It is one still frame, held for 3 s in
  the edit. The same image is the first frame of E01-S001-SH020, so the cut between them is invisible.
- **The intersection is empty.** The black SUV tumbles in only in E01-S001-SH020. The collision is never seen.
- **Layout approved by the author on 2026-11-18** and recorded in the location file: camera on a roof corner looking
  diagonally. The approved image becomes the visual reference for the scene.
- **No traffic lights (author's decision, 2026-11-18).** The intersection has no traffic lights, stop signs or road
  signs at all, to prevent editing mistakes between shots. The wet asphalt reflects the streetlights and the lit
  windows.

### Keyframe (Nano Banana)

```
A single frame from a stylized 3D animated feature film. Wide 16:9 landscape image.

An extreme wide shot of a quiet city intersection at night, seen from a high angle, as if from the roof corner of a four-storey building. The camera looks diagonally down across the intersection, so the crossing sits in the center of the frame like a diamond: one street runs from the lower left corner of the frame to the upper right, the other from the lower right to the upper left. The whole intersection and all four street corners are visible. Only a thin strip of dark night sky shows at the very top.

The streets: two ordinary two-lane streets in a quiet American city district. Dark asphalt, soaked from recent rain. The rain has stopped. The road surface is smooth and glossy, with a few shallow puddles. Simple white crosswalk stripes on all four sides and plain lane lines. The intersection is completely empty. It is an uncontrolled crossing: there are no traffic lights, no signal poles, no stop signs and no road signs of any kind.

Streetlights: a few tall, plain streetlight poles with warm amber lamps along the sidewalks, the only poles in the scene. Their light lays soft warm pools on the sidewalks and the road, and stretches across the wet asphalt as long, soft amber reflections, the strongest color in the image.

Buildings: one low building of two or three storeys on each corner, with simple, slightly simplified shapes: flat roofs, plain brick or plaster walls in warm grey and muted brown, large dark shop windows at street level. Two or three upper windows glow a soft warm amber. Wide, clean sidewalks. Very few objects: no parked cars, no trash cans, no benches, no trees.

Style: stylized 3D animation with moderately simplified shapes, clean smooth surfaces, soft naturalistic lighting and gentle shadows. Slightly simplified rather than photorealistic. Everything is in focus. Clean image: no film grain, no lens flare, no bloom, no glow effects, no vignette.

Color and light: a dim, calm night in warm grey and charcoal tones, with nothing lost in deep black shadow. Amber from the streetlights, the windows and their reflections is the only accent color. No red or green lights, and no saturated or electric blue anywhere.

The frame contains no people, no vehicles, no animals, no traffic lights, no signs, no lettering, no logos, no text and no watermark.
```

### What to check in the result

- The intersection is empty: no vehicles and no people.
- No traffic lights, stop signs or road signs anywhere, and no red or green light.
- No signs, lettering or logos on the buildings.
- The center of the intersection is clear and well lit enough to read: the SUV ends there on its roof.
- The night is dim and warm-grey, not blue, and nothing is lost in black.

---

## E01-S001-SH020

- **Scene:** E01-001, EXT. CITY INTERSECTION - NIGHT (Universe B).
- **Script:** "A big, expensive black SUV tumbles into the intersection, rolling over and over. Glass sprays across
  the asphalt. It comes to rest on its roof, in the middle of the intersection."
- **Planned length:** 3 s.
- **Camera:** the same plate as SH010: extreme wide, high angle, static.
- **First keyframe:** the approved SH010 keyframe, unchanged (the empty intersection).
- **Last keyframe:** the SUV has just landed on its roof in the middle of the intersection. A settled pose is
  used rather than a mid-roll pose, because it is far more stable to generate and gives the video model a clear
  target. E01-S001-SH030 (medium shot) then shows the still wreck from street level, where the headlight flickers and goes out. This frame is also the wide
  reference of the wreck for the narration shots (SH060 to SH110).
- **The car is a large black luxury SUV (author's decision, 2026-11-18).** Its exact look is a proposal (P), not
  locked: tall, boxy and imposing, glossy black, no badge; windows opaque; one headlight still on. See
  [bible/props/black-suv.md](../../bible/props/black-suv.md); lock it once the author approves the image.
- **Rules:** no other car, no driver, no interior, no blood, no fire.

### Last keyframe (Nano Banana, as an edit)

Generate it by uploading the approved SH010 keyframe.

```
Edit the attached image. Keep everything exactly as it is: the same camera position and angle, the same buildings, streets, crosswalks, streetlights, reflections, colors and style. Do not move or change anything that is already in the image. Only add what is described below.

Add one car: a large, expensive-looking black luxury SUV that has just rolled over and landed upside down, resting on its roof in the exact middle of the intersection. It is a tall, long, imposing vehicle with a boxy, upright body, a flat roofline and big wheels. The car is the same stylized 3D animation style as the rest of the image: simplified, smooth shapes, glossy black paint, no badge, no logo and no license plate text.

Position: the car lies at a slight diagonal, with its nose pointing toward the upper right of the frame. It came from the street that enters from the lower left corner. Seen from this high angle, its dark, flat, simplified underside faces up, with all four big wheels in the air. It sits slightly tilted, not perfectly level, as if it has only just landed. It is clearly a big vehicle, about as wide as one traffic lane, but still small in the frame, in proportion to the two-lane streets, and the whole intersection is still visible around it.

Damage: the roof edges are crushed against the asphalt and the body panels are dented and creased, with simplified, clean dents. All the windows are shattered into opaque, pale, frosted crackle, so nothing inside the car can be seen. One headlight is still on and throws a short, soft, pale warm-white pool of light across the wet asphalt in front of the car. The other lights are dark.

On the road: a trail of small, pale glass fragments and a few long, faint scrape marks runs across the wet asphalt from the lower left street to the car, marking the path it rolled along. The fragments catch the amber streetlight as tiny highlights.

The night stays dim and calm in warm grey and charcoal tones with amber accents. No red or green light, and no saturated or electric blue.

The frame contains no second car, no other vehicles, no people, no driver, no body, no blood, no fire, no smoke, no traffic lights, no signs, no text and no watermark.
```

### Video (Runway)

Both keyframes are given to Runway: the SH010 keyframe (empty intersection) and the last keyframe above. The first
three paragraphs tell the model which image is which by its content. If the interface has separate first-frame and
last-frame slots, use them and delete those three paragraphs.

Required length: 3 s. Set the same duration in the Runway interface if it offers it; if it only offers 5 s,
generate 5 s and speed it up or trim it in the edit.

The prompt describes the car in full, because in the last keyframe it lies upside down and its type is hard to read.

```
Duration: 3 seconds.

Two reference images define this shot. They show the same city intersection at night from the same high camera position.

START IMAGE: the one where the intersection is completely empty, with no vehicle anywhere. The video begins on exactly this image.

END IMAGE: the one where a black car lies upside down on its roof in the middle of the intersection, with a trail of broken glass behind it. The video finishes on exactly this image.

The shot moves from the START IMAGE to the END IMAGE, never the other way: the intersection starts empty and the car ends on its roof in the middle.

The camera is completely static, locked on a tripod: no pan, no tilt, no zoom, no drift, no shake.

The car: a large black luxury SUV. It is a tall, long, heavy, expensive-looking vehicle with a boxy, upright body, a flat roofline, big wheels, glossy black paint and dark tinted windows that nothing can be seen through. It has no badge and no logo. It is the car lying on its roof in the END IMAGE. It is the only vehicle in the whole shot.

The action: for the first half second the intersection is empty and still. Then the SUV bursts into the frame from the street at the lower left corner, already out of control and already rolling. It tumbles sideways, roof over wheels, two full rolls across the wet asphalt toward the center of the intersection, heavy and fast. With each impact on the road its windows shatter and small pale glass fragments spray outward and scatter along its path, and the body panels dent. On the last roll it lands on its roof in the exact middle of the intersection, slides a short way, rocks once and stops, exactly as in the END IMAGE, with one headlight still on.

Nothing hits the SUV inside the frame. No other car, no headlights of another vehicle and no people appear at any moment. No driver is ever visible. No fire, no explosion, no smoke, no blood.

The buildings, the streetlights and the road markings stay perfectly fixed and unchanged. The amber reflections on the wet asphalt break and shimmer only where the SUV passes.

Stylized 3D animation, clean smooth surfaces, soft naturalistic night light. One continuous static shot, 3 seconds long.
```

### What to check in the video

- The car reads as a large luxury SUV while it rolls: tall, boxy, big wheels. Not a sedan, a pickup or a van.
- It enters from the lower left already rolling. It never drives in normally, and nothing hits it in the frame.
- The car keeps one shape and one size through the roll: no melting, stretching or doubling.
- The clip ends on the last keyframe exactly: on its roof, in the middle, one headlight on.
- The camera and the buildings do not move.

### What to check in the result

- Everything except the car, the glass and the scrape marks is identical to the SH010 keyframe.
- The car reads as a large luxury SUV, not a sedan or a pickup. It is on its roof, in the middle of the
  intersection, and in proportion to the streets.
- The windows are opaque. Nothing inside the car is visible.
- No second car, no people, no blood, no fire.
- The car is readable against the dark road: the headlight pool and the amber reflections separate it.

---

## E01-S001-SH030

- **Scene:** E01-001, EXT. CITY INTERSECTION - NIGHT (Universe B).
- **Script:** "It comes to rest on its roof, in the middle of the intersection."
- **Planned length:** 3 s.
- **Camera:** medium shot at street level, moving slightly: a slow, small arc to the right with a small push in.
  A new angle, not plate A **(P)**: the camera stands on the road
  on the lower-right side of plate A, at about waist height, and looks across the intersection at the side of the
  upturned SUV. The nose points to frame right and the glass trail comes in from frame left, so the direction of
  travel matches SH020.
- **What the video shows (author's decision, 2026-11-18):** 3 s of the still wreck. The SUV does not move, because
  SH020 already ends with it stopped on its roof. No wheel turns (author: a wheel that starts turning here would look
  artificial). The only movement is the slight camera move and the one lit headlight, which flickers and goes out.
  From the end of this shot on, the wreck has no lights on.
- **First keyframe:** the SUV fully settled on its roof, seen side-on. It is a new image made with the approved
  SH020 last keyframe as the reference for the car, the location and the style.
- **No last keyframe (author's decision, 2026-11-18).** The video is made from the first keyframe only, in
  Seedance; the prompt describes the final framing. The last frame of the clip becomes the first keyframe of the
  next shot.
- **Rules:** no other car, no driver, no interior, no blood, no fire, no smoke.

### First keyframe (Nano Banana, with a reference image)

Generate it by uploading the approved SH020 last keyframe (the SUV on its roof, seen from above).

```
Use the attached image as the reference for the location, the car, the light and the style. Create a new image of the same scene, at the same moment, from a new camera position at street level. Wide 16:9 landscape image. A single frame from a stylized 3D animated feature film.

Camera: a medium shot from a camera standing on the wet road, at about waist height, a few car lengths away from the car. The camera looks straight across the intersection at the long side of the overturned car. The car fills about half the width of the frame and sits in the center, with wet asphalt in the foreground and the street corner behind it.

The car: the same large black luxury SUV as in the attached image, lying upside down on its roof in the middle of the intersection, completely still and settled. It is a tall, long, heavy, expensive-looking vehicle with a boxy, upright body, a flat roofline and big wheels, in glossy black paint, with no badge, no logo and no license plate text. Its nose points toward the right side of the frame. Its flat roof is pressed against the asphalt and its dark, simplified underside faces the sky, with the big wheels up in the air at the top of the car. It rests level and stable.

Damage: the roof edges and the window pillars are crushed against the road and the body panels are dented and creased, with simplified, clean dents. All the windows are shattered into opaque, pale, frosted crackle, so nothing inside the car can be seen. One headlight, low near the ground at the right end of the car, is still on and throws a short, soft, pale warm-white pool of light across the wet asphalt. All the other lights are dark.

On the road: small, pale glass fragments lie scattered on the wet asphalt around the car and in a trail that leads away toward the left edge of the frame, with a few long, faint scrape marks along the same path. The fragments catch the amber streetlight as tiny highlights. The wet asphalt shows a soft, dark reflection of the car.

Background: the same quiet intersection as in the attached image. Behind the car, a street corner with a low two or three storey building with plain brick or plaster walls in warm grey and muted brown, large dark shop windows, and one or two upper windows glowing soft amber. Tall, plain streetlight poles with warm amber lamps, and their long amber reflections on the wet road. White crosswalk stripes. The streets are empty.

Style: stylized 3D animation with moderately simplified shapes, clean smooth surfaces, soft naturalistic lighting and gentle shadows, matching the attached image. Everything is in focus. Clean image: no film grain, no lens flare, no bloom, no glow effects, no vignette.

Color and light: a dim, calm night in warm grey and charcoal tones, with nothing lost in deep black shadow. Amber from the streetlights and windows is the only accent color. No red or green light, and no saturated or electric blue.

The frame contains no second car, no other vehicles, no people, no driver, no body, no blood, no fire, no smoke, no steam, no traffic lights, no signs, no lettering, no text and no watermark.
```

### What to check in the result

- The car matches the SH020 last keyframe: a large black luxury SUV, same damage, one headlight on.
- It lies on its roof, wheels up, nose to frame right, level and settled.
- The windows are opaque. Nothing inside the car is visible.
- The glass trail leads to frame left.
- No traffic lights or signs in the background, no second car, no people.
- The black car separates from the dark background: the amber reflections and the headlight pool outline it.

### Last keyframe: dropped

Tested on 2026-11-18 as a Nano Banana edit of the first keyframe. Version 1 (a small move) came out almost identical
to the first keyframe. Version 2 (a larger move) changed the angle but moved the buildings around the car. The
author's decision: no last keyframe for this shot. The video is generated from the first keyframe only, and the
prompt describes the final framing in words.

### Video (Seedance, image to video, first keyframe only)

Upload only the approved first keyframe as the start image.

Required length: 3 s. If the interface does not offer 3 s, pick the shortest length it offers and speed the clip up
or trim it in the edit.

The author takes the last frame of the generated clip as the first keyframe of the next shot.

```
Duration: 3 seconds. Image to video. The attached image is the first frame.

The scene: a large black luxury SUV lies upside down on its roof in the middle of a quiet city intersection at night, on wet asphalt, under amber streetlights. It is a tall, long, heavy vehicle with a boxy body, a flat roofline and big wheels. Its windows are shattered to an opaque pale crackle and nothing inside can be seen. One headlight at its front end is still on.

Camera movement: one slow, smooth, continuous move for the whole 3 seconds. Starting from the side view in the first frame, the camera glides to the right in a gentle arc around the front corner of the car, about 30 degrees around it. At the same time it moves a little closer to the car and sinks from waist height to about knee height. The camera keeps looking at the car the whole time. The speed is even from start to finish. No shake, no handheld wobble, no zoom, no cut.

The final frame: a front three-quarter view of the car from a low camera. The front end of the car, with its grille, its bumper and its headlights, faces the camera and fills the right half of the frame. The long side of the car runs away toward the left in perspective. The car is larger than in the first frame and fills about two thirds of the width of the frame. In the final frame both headlights are dark, there is no pool of light on the road, and the car is lit only by the amber streetlights. The camera settles gently on this framing at the end.

The car is completely still and rigid, like a solid object. It does not rock, slide, shake, bend or change shape, size or damage at any moment. None of the wheels turn.

The headlight: the one lit headlight is the only thing that changes. For the first second it shines steadily, as in the first frame. Then it flickers weakly and unevenly, three or four times, each time dimmer, and its pale pool of light on the wet asphalt flickers with it. At about two and a half seconds it goes out completely and stays dark until the end. It is a small, quiet, dying light: no flash, no spark, no burst. No other light on the car ever turns on.

The surroundings are a fixed, solid place. The buildings, the streetlights, the sidewalks and the crosswalk stripes stay exactly where they are in the first frame. As the camera moves they only shift in perspective, as real objects do. No building, pole, sign or light appears, disappears, slides or changes shape. The parts of the street that come into view at the edges are plain: the same kind of low building, empty sidewalk and wet road. The glass fragments lie still on the asphalt.

No other car, no people and no driver appear at any moment. No traffic lights, no signs, no text. No fire, no explosion, no smoke, no steam, no sparks, no blood. No rain is falling.

Style: the same stylized 3D animation as the first frame, with clean smooth surfaces and soft naturalistic night light in warm grey and charcoal tones with amber accents. One continuous shot.
```

### What to check in the video

- The buildings and streetlights stay in place through the camera move: nothing slides, appears or melts.
- The car does not move or deform: same shape, damage and size.
- No wheel turns.
- The headlight flickers a few times and goes out before the end. No sparks or flashes, and no other light comes on.
- The camera move is slow, even and smooth.
- The last frame is clean enough to use as a keyframe: sharp, front three-quarter view, headlights dark, no artifacts.
- No steam, smoke, signs or people.

### Before this goes into the episode

- Seedance is not on the plan's list of approved tools. Confirm that the plan in use allows commercial use.

---

## E01-S001-SH060

- **Scene:** E01-001, EXT. CITY INTERSECTION - NIGHT (Universe B).
- **Script:** "Distant sirens rise. Red and blue light washes over the wreck."
- **Narration over the shot:** MIKE (V.O.): "See this wrecked car? That's me in there." Added in the edit.
- **Planned length:** 8 s.
- **Camera:** continues from the end of SH030: medium shot, low, front three-quarter view of the wreck, moving very
  slightly.
- **First keyframe:** the last frame of the approved SH030 video (the wreck with its headlights dark). No last
  keyframe.
- **What the video shows (author's decision, 2026-11-18):** red and blue flashes begin on the dark wreck and the wet
  road and grow stronger while police sirens rise. **The emergency vehicles stay out of frame**: only their light is
  seen. The turning wheel (SH040) and the hubcap (SH050) were cut, so this shot follows SH030 directly.
- **Color rule:** the emergency red and blue is the one place in this scene where saturated color is allowed.

### Video (Seedance, image to video, first keyframe only)

Upload only the last frame of the approved SH030 video as the start image.

Required length: 8 s. The narration and the final siren sound are added in the edit; any sound the model makes is
only a guide.

```
Duration: 8 seconds. Image to video. The attached image is the first frame.

The scene: a large black luxury SUV lies upside down on its roof in the middle of a quiet city intersection at night, on wet asphalt, under amber streetlights. All its lights are off. Its windows are shattered to an opaque pale crackle and nothing inside can be seen. The street is empty and silent.

Camera movement: very small and very slow. For the whole 8 seconds the camera drifts a little further to the right around the front of the car and a little closer to it, staying low near the ground and looking at the car. The whole move is only about one step long. The speed is even from start to finish. No shake, no handheld wobble, no zoom, no cut. The framing at the end is almost the same as in the first frame.

The emergency lights: for the first second nothing changes and the scene is dark and still, lit only by the amber streetlights. Then a faint flashing light begins to reach the scene from far away, from outside the left edge of the frame: red, then blue, then red, alternating in a steady rhythm, like the roof lights of police cars that are approaching but are never seen. At first the flashes are weak and only touch the wet road at the left. Over the next seconds they grow steadily stronger and spread, until by the end red and blue light washes in turns over the whole wreck: it slides across the glossy black paint, glints on the big wheels, glitters on the glass fragments on the road and stretches as long red and blue reflections across the wet asphalt. Between the flashes the amber streetlight is still there.

The source of the flashing light always stays outside the frame. No police car, no ambulance, no vehicle of any kind, no light bar and no headlights enter the frame at any moment. No people appear.

The car is completely still and rigid, like a solid object. It does not rock, slide, shake or change shape, size or damage. No wheel turns. None of its own lights turn on.

The surroundings are a fixed, solid place. The buildings, the streetlights, the sidewalks and the crosswalk stripes stay exactly where they are in the first frame and only shift slightly in perspective with the camera. Nothing appears, disappears or changes shape. Only the color of the light on them changes with the flashes.

Sound: silence at first, then distant police sirens that slowly rise and come closer. No voices, no speech, no music.

No driver, no body, no blood. No fire, no explosion, no smoke, no steam, no sparks. No rain is falling. No traffic lights, no signs, no text.

Style: the same stylized 3D animation as the first frame, with clean smooth surfaces and soft naturalistic night light. One continuous shot.
```

### What to check in the video

- No vehicle, light bar or person ever enters the frame. Only the flashing light is seen.
- The flashes start faint from the left and grow; red and blue alternate. They do not start at full strength.
- The wreck's own lights stay off and it does not move or deform.
- The buildings and streetlights stay in place.
- The camera move is tiny and smooth, so the cut from SH030 is not felt.

### Before this goes into the episode

- Seedance is not on the plan's list of approved tools. Confirm that the plan in use allows commercial use.

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

---

## E01-S001-SH140

- **Scene:** E01-001, EXT. CITY INTERSECTION - NIGHT (Universe B). The third of the four journey shots.
- **Script:** "Stars stretch into streaks. Galaxies rush past."
- **Planned length:** 4 s.
- **Camera:** faces the same direction as in SH130 and flies forward at extreme speed. The Earth is gone.
- **Continuity:** the first keyframe is the last keyframe of E01-S001-SH130 (edge of space, curved Earth at the
  bottom). The last keyframe is also the first frame of E01-S001-SH150. No ember-blue glow here: it appears and
  grows inside SH150. The streaks converge on the point where that glow will appear.

### Last keyframe (Nano Banana, as an edit)

Deep intergalactic space at extreme speed. Generate it by uploading the approved last keyframe of SH130 as the
reference image, so the style, the star shapes and the colors stay identical.

```
Use the attached image as the exact style reference: the same stylized 3D animated film look, the same clean render, the same muted color palette and the same small, crisp, round stars. Create a new frame from the same camera, much later in the same journey: the camera has left the planet far behind and is flying forward through deep intergalactic space at extreme speed. Wide 16:9 landscape image.

The planet is completely gone. There is no Earth, no horizon, no atmosphere line, no land, no clouds and no city lights anywhere in the frame. Space fills the entire image: near-black with a very soft charcoal-navy tint.

Speed: the stars are stretched into thin, clean, straight streaks of light that all radiate outward from one single vanishing point at the exact center of the frame. Near the center the streaks are very short, almost points, and tightly packed. Toward the edges they grow longer and sparser, reaching past the borders of the frame. The streaks are pale warm white with a few in soft amber, matte and sharp-edged, like fine brush lines. The exact center of the frame is the darkest part of the image: a small, calm, empty area of black with only a few tiny round stars in it. Nothing glows there.

Galaxies: five to seven galaxies of different sizes are scattered around the frame, none at the center. They are simplified, sculpted shapes with smooth soft gradients: a few flat spiral discs seen at different tilts, one or two soft oval ones. Their colors are muted: pale cream, warm grey, dusty rose and soft amber. The two largest sit near the left and right edges, partly cut off by the frame and slightly stretched along the direction of travel, as if rushing past the camera. The smaller ones lie farther in, closer to the center, and are sharper and less stretched.

Style: stylized 3D animation with simplified shapes, clean smooth surfaces and soft gradients, slightly simplified rather than photorealistic. Clean image: no film grain, no lens flare, no bloom, no glow effects, no light rays, no vignette. This is not a tunnel and not a wormhole: open space in every direction.

Color: muted and calm. Near-black, charcoal, soft navy, pale warm white, small amber and dusty rose accents. No blue glow, and no saturated or electric blue anywhere in the frame.

The frame contains no planets, no sun, no moon, no nebula clouds, no spacecraft, no people, no text and no watermark.
```

### Video (Runway)

Both keyframes are given to Runway: the last keyframe of SH130 and the last keyframe of SH140. The first three
paragraphs tell the model which image is which by its content. If the interface has separate first-frame and
last-frame slots, use them and delete those three paragraphs.

```
Two reference images define this shot.

START IMAGE: the one with the curved edge of a planet along the bottom, dotted with tiny city lights, under a black sky full of small round stars. The video begins on exactly this image.

END IMAGE: the one with no planet at all, where the stars are stretched into long streaks radiating from the center of the frame and several galaxies sit around the edges. The video finishes on exactly this image.

The shot moves from the START IMAGE to the END IMAGE, never the other way: the camera leaves the planet and ends in deep space.

The camera flies straight forward into space in one continuous, smooth move that keeps accelerating to extreme speed. It faces the same direction the whole time, without turning, tilting or rolling.

The curved edge of the planet slides down and out of the bottom of the frame within the first moments and never comes back. From then on there is only open space. The stars begin as small steady points. As the speed builds, they stretch into thin straight streaks that radiate outward from a single point at the exact center of the frame, short near the center and long toward the edges. Galaxies appear as tiny shapes near the center, grow as the camera approaches, and rush past the left, right, top and bottom edges of the frame, one after another. The center of the frame stays dark and empty for the whole shot.

Stylized 3D animation, clean smooth surfaces, soft gradients, muted colors. No blue glow, no flash, no tunnel, no wormhole. One continuous shot. Speed builds steadily from fast to extremely fast.
```

### What to check in the result

- The move runs forward and away from the planet. The planet leaves through the bottom of the frame and never returns.
- The streaks grow gradually out of the points. They do not pop in.
- The clip opens and closes on the two keyframes exactly, so it joins SH130 and SH150.
- No trace of the Earth, the horizon or the atmosphere line.
- All streaks point to one vanishing point at the exact center, and the center is dark and empty.
- No blue glow and no saturated blue: the ember-blue glow must be new when it appears in SH150.
- The galaxies match the series style: simplified and sculpted, not photographic.
- Same 16:9 ratio and resolution as the SH130 keyframes.

---

## E01-S001-SH150

- **Scene:** E01-001, EXT. CITY INTERSECTION - NIGHT (Universe B). The last of the four journey shots.
- **Script:** "Ahead, a glow: a deep ember blue, as if lit from the inside. It swallows the frame."
- **Planned length:** 2 s.
- **Camera:** flies straight forward into the glow.
- **Continuity:** the first keyframe is the last keyframe of E01-S001-SH140 (streaks and galaxies, dark center).
  The last keyframe is also the first frame of E01-S002-SH010, where the glow thins like haze and the web of souls
  is revealed behind it. So the glow must read as haze, and nothing of the web may show yet.
- **Color:** this is the first frame of the film where saturated blue is allowed. The glow belongs to the
  spiritual dimension's palette ([bible/locations/spiritual-dimension.md](../../bible/locations/spiritual-dimension.md)).

### Last keyframe (Nano Banana)

The glow fills the whole frame. Generated without a reference image: nothing of the earlier frames remains in it.

```
A single frame from a stylized 3D animated feature film. Wide 16:9 landscape image.

The entire frame, from edge to edge, is filled with a soft, luminous haze of deep ember blue: a rich, saturated electric blue that looks as if it is lit from the inside, like the blue heart of a flame seen through mist. There are no objects, no shapes and no horizon. The image is pure glowing haze.

Light: the glow comes from within the haze itself, not from a visible light source. It is brightest at the exact center of the frame, a luminous electric blue, and falls off very gradually and smoothly toward the edges, where it deepens into a dark blue-black. The edges are still blue, never pure black.

Deep inside the brightest part, at the exact center, there is a very faint hint of warm amber, small and soft, like an ember seen far away through thick blue fog. It is barely noticeable and tints only the very center. The image as a whole reads as blue.

Texture: the haze is soft and volumetric, with very gentle, slow variations in density, like fine mist. There are no hard edges, no streaks, no lines, no threads, no sparks, no particles and no stars.

Style: clean, smooth render with soft gradients, in the look of a stylized 3D animated film. The gradient is perfectly smooth, with no color banding. No film grain, no lens flare, no light rays, no vignette.

Color: electric blue and deep blue-black, with a trace of amber at the center only. No white, no purple, no green, no teal.

The frame contains no planets, no galaxies, no figures, no faces, no text and no watermark.
```

### Video (Runway)

Both keyframes are given to Runway: the last keyframe of SH140 and the last keyframe of SH150. The first three
paragraphs tell the model which image is which by its content. If the interface has separate first-frame and
last-frame slots, use them and delete those three paragraphs.

Planned length 2 s. Generate 5 s and speed it up in the edit.

```
Two reference images define this shot.

START IMAGE: the one showing deep space, with stars stretched into long streaks radiating from a dark center and several galaxies around the edges. The video begins on exactly this image.

END IMAGE: the one that is entirely filled with a soft, glowing deep blue haze, with no stars and no objects at all. The video finishes on exactly this image.

The shot moves from the START IMAGE to the END IMAGE, never the other way: it begins in dark space and ends inside the blue glow.

The camera flies straight forward through deep space at extreme speed, in one continuous, smooth move. It faces the same direction the whole time, without turning, tilting or rolling.

At the very start, a tiny point of deep blue light appears at the exact center of the frame, in the dark spot where all the star streaks converge. The camera rushes straight toward it. The point grows steadily into a soft, round, glowing blue haze, brightest at its center, with a faint warm amber trace deep inside. The star streaks and the galaxies keep rushing outward past the edges of the frame. As the glow expands from the center, it covers them one after another, until the last streaks vanish at the edges and the blue haze fills the whole frame.

The glow grows smoothly and continuously, like flying into a cloud of light. It has soft edges and no hard outline. No flash, no explosion, no white-out, no tunnel, no wormhole, no lens flare, no light rays.

Stylized 3D animation, clean smooth render, soft gradients. One continuous shot.
```

### What to check in the result

- The move runs forward, from dark space into the glow.
- The glow is born at the exact center and grows smoothly. It does not flash, pulse or jump.
- The frame never goes white. The BOOM flash belongs to E01-S002-SH050, not here.
- The clip opens and closes on the two keyframes exactly, so it joins SH140 and E01-S002-SH010.
- The glow covers the whole frame. No stars, streaks or galaxies are left.
- The brightest point is at the exact center, where the streaks of SH140 converge.
- The center is not blown out to white.
- The amber is a trace at the center only. The frame reads as blue.
- Nothing of the web shows: no threads, no knots, no sparks.
- The gradient is smooth, without banding. Same 16:9 ratio and resolution as the other journey keyframes.
