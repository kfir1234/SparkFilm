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
| [E01-S001 crash sound](#e01-s001-crash-sound-off-screen) | E01-001, the unseen crash | Sound effect | ElevenLabs Sound Effects | not tested |
| [E01-S001-SH030](#e01-s001-sh030) | E01-001, the wreck from street level | First keyframe | Nano Banana (reference: the SH020 last keyframe) | not tested |
| [E01-S001-SH030](#e01-s001-sh030) | E01-001, the wreck from street level | Last keyframe | Dropped | Two tests failed (no change of angle; then the buildings moved) |
| [E01-S001-SH030](#e01-s001-sh030) | E01-001, the wreck from street level | Video | Seedance (first keyframe only) | not tested |
| [E01-S001-SH060](#e01-s001-sh060) | E01-001, the emergency lights arrive | First keyframe | The last frame of the SH030 video | — |
| [E01-S001-SH060](#e01-s001-sh060) | E01-001, the emergency lights arrive | Video | Seedance (first keyframe only) | not tested |
| [E01-S001 emergency sirens](#e01-s001-emergency-sirens-off-screen) | E01-001, sirens over SH060 | Sound effect | ElevenLabs Sound Effects | not tested |
| [E01-S001 narration](#e01-s001-narration-voice-test) | E01-001, MIKE (V.O.) | Voice test | ElevenLabs | not tested |
| [E01-S001 background music](#e01-s001-background-music) | E01-001, the whole cold open | Music loop | ElevenLabs Music (or ACE-Step) | not tested |
| [E01-S001-SH120](#e01-s001-sh120) | E01-001, journey 1 of 4 | Video | Seedance (first frame: the wreck; last frame: the SH130 first keyframe) | not tested |
| [E01-S001 journey sound](#e01-s001-journey-sound-flight-through-the-stars) | E01-001, sound over SH130 to SH150 | Sound effect | ElevenLabs Sound Effects | not tested |
| [E01-S001-SH130](#e01-s001-sh130) | E01-001, journey 2 of 4 | First keyframe | Nano Banana | v2 (inland), not retested |
| [E01-S001-SH130](#e01-s001-sh130) | E01-001, journey 2 of 4 | Last keyframe | Nano Banana (edit of the first keyframe) | v2 (inland), not retested |
| [E01-S001-SH130](#e01-s001-sh130) | E01-001, journey 2 of 4 | Video | Runway | Test 1 failed (start area read as sea); v2 (inland), not retested |
| [E01-S001-SH140](#e01-s001-sh140) | E01-001, journey 3 of 4 | Last keyframe | Nano Banana (edit of the SH130 last keyframe) | not tested |
| [E01-S001-SH140](#e01-s001-sh140) | E01-001, journey 3 of 4 | Video | Runway | not tested |
| [E01-S001-SH150](#e01-s001-sh150) | E01-001, journey 4 of 4 | Last keyframe | Nano Banana (no reference image) | not tested |
| [E01-S001-SH150](#e01-s001-sh150) | E01-001, journey 4 of 4 | Video | Runway | not tested |
| [E01-S002-SH010](#e01-s002-sh010) | E01-002, the web is revealed | First keyframe | The last frame of the SH150 video | — |
| [E01-S002-SH010](#e01-s002-sh010) | E01-002, the web is revealed | Last keyframe (master image of the web) | Nano Banana (reference: the first keyframe, color only) | not tested |
| [E01-S002-SH010](#e01-s002-sh010) | E01-002, the web is revealed | Last keyframe with sparks | Nano Banana (edit of the master image) | not tested |
| [E01-S002-SH010](#e01-s002-sh010) | E01-002, the web is revealed | Video | Seedance (first and last frame) | not tested |

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
  reference of the wreck for the narration shot (SH060).
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

## E01-S001 crash sound (off screen)

- **Scene:** E01-001. The crash is heard, never seen: it plays over E01-S001-SH010 (the empty intersection) and runs into E01-S001-SH020 (the SUV tumbles in).
- **Tool:** ElevenLabs Sound Effects (text to sound effect). Written 2026-11-21.
- **Canon limits:** one vehicle only. Nothing in the sound may suggest a second car (no horn, no second engine). What the SUV hits stays unknown.
- **Wording rule:** the prompts name only the sounds that are wanted. They carry no "no horn" or "no voices" lines, because a named sound may be added instead of removed.
- **License:** ElevenLabs output may go into the episode only from a paid plan.

### Option A: three layers, mixed in the edit (preferred)

Layer 1, the skid. Duration: 3 seconds.

```
Long tire screech of a heavy SUV skidding on wet asphalt, heard from a block away on a quiet city street at night, natural echo between buildings, cinematic, realistic.
```

Layer 2, the impact. Duration: 2 seconds.

```
One huge, deep car crash impact: a low boom, heavy metal crunching and glass shattering, heard from a block away with a short street echo, cinematic, realistic.
```

Layer 3, the tumble. Duration: 4 seconds.

```
A heavy SUV rolling over several times on wet asphalt, coming closer: repeated heavy metal thuds, scraping steel, broken glass sprinkling on the road, ending with one last heavy thud. Close, cinematic, realistic.
```

Placement on the timeline (SH010 = 0 to 3 s, SH020 = 3 to 6 s): the skid starts at about 0.8 s; the impact lands at about 2.2 s and cuts the skid off; the tumble starts at 3.0 s, when the SUV enters the frame, and its last thud lands on the frame where the SUV stops.

### Option B: one clip

Duration: 6 seconds.

```
Heard on a quiet, wet city street at night: a heavy SUV's tires screech in a long skid, then one huge, deep crash impact with crunching metal and shattering glass, then the heavy vehicle rolls over and over on the asphalt, coming closer, with metal thuds, scraping steel and sprinkling glass, ending with one last heavy thud. Cinematic, realistic, natural street echo.
```

### Settings

- Set the duration by hand to the value above; do not leave it on automatic.
- Prompt influence: start at about 0.6, and raise it if the result drifts from the description.
- Generate several variations of each layer and keep the best one.

### What to check in the result

- No horn, no second engine, no voices and no music.
- The skid and the impact sound far away; the tumble sounds close.
- The impact is one deep hit, not a string of small ones.
- The tumble has separate heavy thuds that can be lined up with the rolls in the SH020 video.

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
- **Narration over the shot:** the whole cold-open narration of MIKE (V.O.), added in the edit. The separate
  narration shots SH070 to SH110 were cut by the author on 2026-11-20.
- **Planned length:** 8 s generated. In the edit the shot is extended statically to the length of the recorded
  narration (about 50 s).
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

## E01-S001 emergency sirens (off screen)

- **Scene:** E01-001, over E01-S001-SH060. Police, fire trucks and ambulances are heard, never seen. Their light comes from frame left, so the sound is panned left in the edit.
- **Tool:** ElevenLabs Sound Effects. Written 2026-11-21.
- **Author's brief (2026-11-21):** police, fire trucks and ambulances in the background. Fire trucks are new here; the script and the breakdown name only police and an ambulance.
- **Proposal, not yet approved:** the sirens approach, then wind down and stop, and a quiet idling bed stays under the narration. The option with sirens through the whole narration is Layer 1b.
- **License:** ElevenLabs output may go into the episode only from a paid plan.

### Layer 1: the approach. Duration: 12 seconds.

```
Several emergency sirens approaching from far away on a quiet city street at night: wailing police sirens, an ambulance siren and a deep fire truck siren, starting very faint and distant and growing steadily louder and closer, natural echo between buildings, realistic.
```

### Layer 1b (alternative bed): distant sirens that never arrive. Duration: 20 seconds, loop on.

```
Distant emergency sirens on a city street at night, steady and far away: police sirens, an ambulance siren and a deep fire truck siren overlapping, soft, with natural echo between buildings, even level from start to end, realistic.
```

### Layer 2: the sirens stop. Duration: 6 seconds.

```
Close emergency sirens winding down and stopping one after another: a police siren, an ambulance siren and a deep fire truck siren, each dropping in pitch and falling silent, realistic.
```

### Layer 3: the scene bed. Duration: 20 seconds, loop on.

```
Quiet emergency scene ambience at night, steady and even: a large diesel fire truck engine idling at a short distance, faint radio static, soft, realistic.
```

### Placement on the SH060 timeline

- 0 to 1 s: silence (the headlight has just died).
- 1 to 13 s: Layer 1, rising together with the red and blue flashes.
- 13 to 19 s: Layer 2.
- From about 17 s to the end of the narration: Layer 3, low, on repeat.

### What to check in the result

- All three siren types are heard: police, ambulance, the deeper fire truck.
- Layer 1 really grows from far to near; it does not start loud.
- No voices and no words that can be understood.
- Layer 3 and Layer 1b keep an even level, so the repeat is not heard.

---

## E01-S001 narration (voice test)

- **Scene:** E01-001. MIKE (V.O.), the whole cold-open narration, played over E01-S001-SH060.
- **Purpose:** a timing and tone test only (2026-11-20). Not the final voice.
- **Direction from the script:** slow, quiet; frustrated, yet at peace with death.
- **Words:** exactly the script's lines. Only tags and pauses are added.
- **License:** ElevenLabs output may go into the episode only from a paid plan.

### Version A: Eleven v4 (audio tags in square brackets)

The author uses Eleven v4 (2026-11-20). Per the ElevenLabs docs, v4 (like v3) takes free-text audio tags in square
brackets and does not support SSML `<break>` tags: pauses come from `[pause]` / `[long pause]`, punctuation and line
breaks. One tag per clause; tags describe the voice, so they are not taken for sound effects.

```
[slow, quiet, tired voice] See this wrecked car?

[flat, matter-of-fact] That's me in there.

[long pause]

[low, bitter voice] Last time, I fought it. [pause] Every single second.

[pause]

[exhales] This time...

[softly, letting go] this time I just let go.

[pause]

[dry, wry voice] Not sure if that makes me brave, or the biggest idiot alive.

[pause]

[quiet, deadpan] Well. [pause] Not really alive.

[pause]

[calm, plain voice] This is the second time I've died.

[pause]

[louder, frustrated, disbelieving] Yeah, the second time!

[pause]

[quieter, trailing off] I don't really believe it myself...

[long pause]

[sighs] Okay. Enough with the whining.

[pause]

[warmer, steadier voice] Let me tell you about the people I left behind.

[softly, with love] The people I love.

[pause]

[quiet, heavy voice] Both times.
```

### Version B: Eleven Multilingual v2 or Turbo v2 only (break tags, no emotion tags; not for v4)

```
See this wrecked car? <break time="0.6s" /> That's me in there.
<break time="2.5s" />
Last time, I fought it. <break time="0.5s" /> Every single second.
<break time="1.5s" />
This time... <break time="0.7s" /> this time I just let go.
<break time="1.5s" />
Not sure if that makes me brave, or the biggest idiot alive.
<break time="1.5s" />
Well. <break time="0.6s" /> Not really alive.
<break time="1.5s" />
This is the second time I've died.
<break time="1.2s" />
Yeah, the second time!
<break time="1.2s" />
I don't really believe it myself...
<break time="2.5s" />
Okay. Enough with the whining. <break time="0.7s" /> Let me tell you about the people I left behind. <break time="0.5s" /> The people I love. <break time="0.8s" /> Both times.
```

### What to check in the result

- Total length, to size E01-S001-SH060 (the estimate is 50 s).
- No tag is read aloud.
- Only "Yeah, the second time!" rises; everything else stays low and slow.
- The last line turns warm, not sad.

---

## E01-S001 background music

- **Scene:** E01-001. One piano bed for the whole cold open (about 71 s), under the crash sounds and under MIKE's narration. Played on repeat.
- **Tool:** written for ElevenLabs Music (instrumental). The same text works as the description for ACE-Step, the local option on the plan's approved list. Written 2026-11-21.
- **Author's brief:** piano; calm and mysterious; carries the narration; the end of the track lets it loop.
- **License:** confirm the commercial terms of the music tool before the track goes into the episode. ElevenLabs output only from a paid plan.

### Prompt

Length: 64 seconds. Instrumental.

```
Instrumental film score cue for a quiet night scene. Solo felt piano, soft and close, playing a slow, sparse, repeating four-note motif in D minor, with long pauses between phrases. Under it, a very quiet, warm, low string pad that never swells. Mood: calm, mysterious, melancholic, at peace. Slow steady tempo, 60 BPM. Very low and even dynamics from the first second to the last: no build-up, no climax, no drums, no percussion, no bass drop, no vocals. The piece is a seamless loop: it starts directly on the motif with no intro and no fade-in, and it ends mid-pattern on an open, unresolved chord with no final cadence, no ritardando and no fade-out, so that the last bar leads straight back into the first bar.
```

### Settings

- Set the length by hand to 64 seconds (16 bars at 60 BPM), so the loop point falls on a bar line.
- Instrumental mode on, if the tool has the switch.

### Looping in the edit

- Cut the track on a bar line (every 4 seconds at 60 BPM) and overlap the copies by about 1 second, so the piano's ringing tail covers the join.

### What to check in the result

- The piano stays sparse: the narration is clear over it without lowering the music by much.
- The level and the texture are the same at the start and at the end; the join is not heard when the track repeats.
- No ending chord, no slowing down, no fade at the end.
- No drums, no voices, no swell.

---

## E01-S001-SH120

- **Scene:** E01-001, EXT. CITY INTERSECTION - NIGHT (Universe B). The first of the four journey shots.
- **Planned length:** 3 s. Generate 5 s and speed it up in the edit: the move is too large to stay solid in 3 s.
- **Camera:** rises straight up from the wreck, like a crane, and tilts up a little at the end. A straight vertical
  rise is used because the model only has to reveal the upper floors and roofs of buildings it already sees, and
  then the city behind them. It never has to invent a top view of the intersection.
- **First keyframe:** the author's frame of the wreck after the emergency lights (close, low, front three-quarter
  view, red and blue light on the car).
- **Last keyframe:** the approved first keyframe of E01-S001-SH130 (just above the rooftops, night sky in most of
  the frame), so the two shots join without a jump.
- **Rules:** the emergency vehicles stay out of frame. No people. The world stays solid and complete for the whole
  move.

### Video (Seedance, first and last frame)

Upload the wreck frame as the first frame and the SH130 first keyframe as the last frame.

```
Duration: 5 seconds. First frame and last frame are given.

FIRST FRAME: a close, low view of a large black luxury SUV lying upside down on its roof in a city intersection at night, with red and blue emergency light on it and low brick buildings with amber windows behind it.

LAST FRAME: a view from just above the city rooftops, where a dark night sky with a few stars and soft clouds fills most of the frame and the flat roofs of the city sit in a narrow band at the bottom.

One continuous shot from the FIRST FRAME to the LAST FRAME. No cut, no dissolve, no fade, no morph. It is a single real camera rising through a single real place.

Camera movement: a smooth vertical crane move. The camera rises straight up from the road, slowly at first and then steadily faster. It keeps facing the same direction the whole time, toward the buildings behind the car. It does not turn left or right and it does not fly forward. Only in the last second it tilts up a little, so the sky fills most of the frame and the rooftops settle in a narrow band at the bottom, exactly as in the LAST FRAME.

What the camera passes, in order:
1. The overturned car sinks toward the bottom of the frame and slides out of view. It stays still and solid and does not change shape.
2. The street behind it: the sidewalk, the streetlight poles with their amber lamps, the ground floor of the buildings.
3. The upper floors of the same buildings, with the same brick walls and the same lit amber windows as in the FIRST FRAME, sliding down the frame.
4. The roof edges of those buildings, then their flat roofs seen from just above: dark, damp, with simple parapets, vents and small roof structures.
5. Beyond them, more of the city coming into view: block after block of similar low and mid-rise buildings with flat roofs, small amber windows and streetlights, reaching all the way to the horizon.
6. The night sky opening up above: deep charcoal-navy, a few small stars, soft rounded clouds.

The world is solid and complete at every moment. Every part of the frame is always filled with real city or real sky. Buildings are whole, with walls, windows and roofs. There are no gaps, no holes, no empty or blank areas, no flat grey ground, no fog hiding the city, no floating or half-built buildings, and no buildings that appear, vanish, melt, stretch or slide. Everything that comes into view stays where it is and only moves down the frame as the camera rises.

Light: the red and blue emergency light pulses on the car and the road at the start. It comes from outside the frame. As the camera rises above the street it fades and is left behind, and from the rooftops up the only light is the warm amber of windows and streetlights under the dark sky.

No police car, no ambulance, no other vehicle, no aircraft and no people appear at any moment. No fire, no smoke, no steam, no rain. No traffic lights, no signs, no text.

Sound: distant police sirens that fade and fall away as the camera rises, into quiet wind.

Style: stylized 3D animation with simplified shapes, clean smooth surfaces and soft naturalistic night light, the same from the first frame to the last.
```

### What to check in the video

- The city is whole through the entire rise: no holes, blank areas, fog walls or half-built buildings.
- The buildings behind the car are the same ones from street level to roof. Nothing slides or melts.
- The move is one vertical rise. It does not become a dissolve or a morph between the two images.
- No vehicle or person appears. The red and blue light fades as the camera leaves the street.
- The last frame matches the SH130 first keyframe closely enough to cut on.

### Before this goes into the episode

- Seedance is not on the plan's list of approved tools. Confirm that the plan in use allows commercial use.

---

## E01-S001 journey sound (flight through the stars)

- **Scene:** E01-001, over the journey shots E01-S001-SH130, SH140 and SH150 (9 s), after the rise of SH120. The camera accelerates from the sky above the city through the stars into the deep ember-blue glow.
- **Tool:** ElevenLabs Sound Effects. Written 2026-11-21.
- **Character:** air and tone, not a machine. Soft, wide, ethereal. The prompts name only the wanted sounds.
- **License:** ElevenLabs output may go into the episode only from a paid plan.

### Layer 1: the flight. Duration: 7 seconds.

```
A long, smooth, airy whoosh that keeps accelerating: soft rushing wind that grows faster and higher in pitch, with a faint shimmering, glassy tone inside it, like flying upward through the night sky and out among the stars at rising speed. Wide, ethereal, cinematic, gentle.
```

### Layer 2: the arrival in the glow. Duration: 4 seconds.

```
A deep, warm, soft bloom of sound: the rushing air is swallowed into a low, round, humming tone with a gentle shimmer on top, which swells once and then settles into a calm, steady, quiet hum. Ethereal, warm, cinematic.
```

### Option B: one clip. Duration: 9 seconds.

```
A long, smooth, airy whoosh that keeps accelerating for six seconds: soft rushing wind growing faster and higher, with a faint shimmering, glassy tone, like flying up through the night sky and out among the stars. Then the rush is swallowed into a deep, warm, low humming bloom that swells once and settles into a calm, quiet hum. Wide, ethereal, cinematic, gentle.
```

### Placement on the timeline (SH130 starts at 0)

- From the last second of SH120: the sirens and the street fade out into quiet wind.
- 0 to 7 s (SH130 and SH140): Layer 1. Its fastest, highest point lands on the cut from SH140 to SH150.
- 6.5 to 10.5 s (SH150 and into the first shot of E01-002): Layer 2. Its swell lands on the frame where the glow fills the picture, and its steady hum carries over the cut into the next scene.

### What to check in the result

- No engine, no rocket, no laser and no electronic beeps: it is air and tone only.
- Layer 1 really accelerates; it is not an even wind.
- Layer 2 ends on a steady hum that can be faded or held, not on a hit.
- It sits under the piano without masking it.

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

---

## E01-S002-SH010

- **Scene:** E01-002, THE SPIRITUAL DIMENSION. The first shot inside: the full-frame glow thins like haze and the web is revealed.
- **Shot list:** EWS; slow drift; 6 s. Fixed shot A of [spiritual-dimension](../../bible/locations/spiritual-dimension.md).
- **First keyframe:** the last frame of the E01-S001-SH150 video, unchanged (the blue glow with the amber trace at its center).
- **Last keyframe:** the master image of the web, below. Every other keyframe of the scene is derived from it.
- **Video:** first and last frame; not written yet.
- **Proposals, not yet approved (2026-11-22):** the master image has no sparks, so it serves both a video-model route and a compositing route; the nearest soul sits at the exact center of the frame, so the amber trace of the glow becomes that soul's ember when the haze thins.

### Last keyframe = master image of the web (Nano Banana, with a reference image)

Reference image: the first keyframe (the blue glow), for color only.

```
Use the attached image only as a color reference: keep its deep blue-black and its electric blue. Create a new image, 16:9.

An extreme wide view of an endless web of light floating in deep blue-black space.

The web is made of dozens of souls. Each soul is a dense, organic knot of thin threads of electric-blue light that converge on a core. A knot has no clean outline and is not a sphere. Deep inside each core there is one small, warm amber ember, half hidden behind the threads.

The threads of every knot run on outward and become long, thin currents of blue light that join it to the knots around it, so that everything is connected into one web.

All the souls are the same: the same size and the same brightness. A knot looks larger only because it is nearer to the camera. The nearest knot sits at the exact center of the frame and takes up about one sixth of the frame's width; the others spread around it, above it and far behind it, getting smaller with distance.

The web runs on in every direction, to the sides, upward and into the depth, and dissolves into soft blue haze. It has no edge.

In the lower fifth of the frame the web ends, and below it there is only deep, empty darkness.

Light: there is no outside light source. All the light comes from the knots and the currents themselves, as a soft glow. The amber stays inside the cores and does not light the space: the image reads as blue.

Style: stylized 3D animation, clean smooth forms, soft volumetric glow. No faces, no bodies, no eyes. No stars, no planets, no galaxies. No small sparks, no particles, no dust. No text. No lens flare, no film grain, no vignette.
```

### What to check in the result

- The knots are organic tangles of threads, not spheres, not neurons with a face-like shape, not stars.
- All knots have the same brightness; size changes only with distance.
- Each core has an amber ember, small, and the image still reads as blue.
- The currents really join the knots to each other.
- The web fades into haze at the top and the sides, and there is darkness below.
- No sparks or particles anywhere.
- The blue matches the first keyframe.

### Last keyframe with sparks (Nano Banana, as an edit of the master image)

Author's decision (2026-11-22): the sparks already move in this shot, as part of the video, from the moment the souls are revealed. A video that ends on a frame without sparks would have to make them vanish, so the last keyframe of this shot is the master image with sparks added. The master image without sparks is kept as the base for the other shots.

```
Edit the attached image. Keep everything exactly as it is: the same knots, the same currents, the same colors, the same framing. Change nothing that already exists.

Add only this: many tiny sparks travelling along the currents of light. Each spark is a very small point, whiter and brighter than the blue threads, with a short tail that shows its direction. The sparks travel in loose streams, like glowing dust, and they sit on the currents, never in the empty space between them.

Two directions: some streams leave the knots and run downward along the currents, toward the darkness at the bottom of the frame; other streams rise from the darkness and run upward into the knots.

All the sparks look alike. None is larger or brighter than the others. No sparks in the lower darkness away from the currents. No other change.
```

### Video (Seedance, first and last frame)

First frame: the blue glow. Last frame: the master image with sparks.

```
Duration: 6 seconds.

The first frame is a soft, deep blue glow that fills the whole picture, with a faint amber point at its center. The last frame is a wide view of an endless web of light: knots of blue threads joined by long currents, with tiny white-blue sparks travelling along the currents. This is one continuous shot from inside the glow: the glow is a haze, and as it thins, the web that was always behind it is revealed. It is not a cross-fade between two pictures.

Camera: one very slow, steady drift forward for the whole shot. No turn, no shake, no cut.

Second 0 to 1: the blue haze fills the frame and drifts slowly, like fine mist lit from inside.

Second 1 to 4: the haze thins gradually and evenly. The knots appear first as soft, blurred patches of brighter blue inside the mist, then sharpen into tangles of thin threads, and the long currents between them come into view. The faint amber point at the center stays where it is and becomes the small ember inside the core of the knot at the center. The other knots show the same small amber ember in their cores.

The sparks: from the first moment the currents can be seen, even while they are still blurred by the haze, the sparks are already moving along them. They are tiny points, whiter and brighter than the threads, each with a short tail, flowing in loose streams like glowing dust. Some streams leave the knots and run down along the currents into the darkness below the web. Other streams rise out of that darkness and run up into the knots. They move fast and smoothly, always along the currents, never across empty space. They never stop, and they are in full motion in the last frame.

Second 4 to 6: the haze is gone, except far away, where the web still fades into soft blue mist. The web is fully clear. Its glow swells and eases very slowly, like breathing, while the sparks keep streaming quickly along the currents.

The web itself is steady: the knots and the currents keep their places and their shapes. Nothing melts, merges, splits or drifts apart. All the knots keep the same size and the same brightness.

Light: all the light comes from the web itself. The picture stays blue; the amber stays inside the cores. No flash, no burst, no white-out.

No faces, no bodies, no eyes. No stars, no planets, no galaxies. No lightning bolts. No text.

Sound: a low, warm, steady hum with a faint, soft electric shimmer. No music, no voices.
```

### What to check in the video

- The web is revealed out of the haze; it does not look like a cross-fade.
- The sparks are already moving while the haze is still thinning, and they are still moving in the last frame.
- The sparks follow the currents, in both directions (down from the knots, up into the knots).
- The knots and the currents stay in place; nothing melts or changes shape.
- The amber point of the glow ends up inside the center knot.
- No flash and no white-out: the BOOM belongs to E01-S002-SH050.
