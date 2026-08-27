# Prompt recipes

Use only the recipe relevant to the requested mode. Replace bracketed fields with observed facts, not guesses.

## Master generation prompt

> Original Korean-inspired baby lifestyle fashion photograph of [fictional identity, exact age band and stable features], wearing [precise garment description including silhouette, construction, material, pattern and color]. [Natural age-appropriate action] with [candid expression] in [simple warm setting]. Camera at child eye/chest height, [full body / three-quarter / medium], natural 50–85 mm perspective, generous breathing room, garment unobstructed. Large soft window daylight or open shade from [direction], bright clean exposure, gentle dimensional shadows, warm whites, oatmeal neutrals and low-saturation pastel accents, accurate skin tone, visible natural fabric texture, subtle realistic grain, polished ecommerce clarity with an unforced family-life moment. Preserve realistic child anatomy and exact garment construction.

Negative block:

> adult styling, makeup, fashion-model pose, sexualized framing, glossy studio set, hard flash, dramatic cinema lighting, heavy vintage filter, strong CCD noise, neon colors, orange cast, plastic skin, oversized head, elongated limbs, extra fingers, warped hands or feet, fisheye, extreme wide angle, clutter, unreadable text, invented logo, altered seams, altered print, added trim, duplicated objects

## Identity reference set

> Consistent neutral identity reference sheet for one fictional [age]-old East Asian [baby/toddler], [stable facial and hair features], realistic skin and child proportions, calm friendly presence. Seven separate clean views: front portrait, left and right three-quarter, profile, full body standing or supported according to age, gentle smile, curious neutral expression. Plain warm-cream background, soft daylight, simple unbranded cream cotton clothing, no props, no accessories, no stylization. Keep the same child in every view.

## Garment replacement edit

> Edit the base photograph by replacing only the existing clothing with the supplied garment reference. Reconstruct exactly: [invariants]. Preserve without change the child's identity, apparent age, face, hair, skin, body proportions, hands, feet, pose, expression, gaze, crop, camera perspective, background, props, lighting direction, exposure, shadows and depth of field. Make the replacement garment follow the existing body pose with physically plausible fabric drape and occlusion. Do not redesign, beautify, restyle, add accessories, or change any non-garment pixels unless required for natural garment boundaries.

## Shot deltas

- **Hero:** standing or age-appropriate supported pose, full outfit visible, quiet smile, minimal background.
- **Play:** seated on a cream rug or linen bed, engaged with one small wooden or fabric toy, garment front unobstructed.
- **Motion:** walking, crawling, turning, or reaching according to age; freeze face and clothing detail while allowing slight limb motion.
- **Detail:** medium-close crop centered on neckline, closure, waistband, texture, or print; include enough face/body context to retain warmth.
- **Outdoor:** pale wall or garden path in open shade, light breeze, restrained greenery, no busy street or adult-fashion attitude.
- **Caregiver:** adult hands or partial neutral clothing only, affectionate functional interaction, child and product remain primary.

## Per-shot response format

For each image provide:

1. shot purpose and aspect ratio;
2. prompt delta to append to the master prompt;
3. garment features that must remain visible;
4. expected risk and retouch note.
