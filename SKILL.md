---
name: konny-lifestyle-fashion
description: Create or edit consistent Korean-style baby and toddler apparel campaign images with soft daylight, pastel color, candid movement, and faithful garment rendering. Use for model casting, identity sheets, lifestyle scenes, lookbooks, product-focused image sets, and garment replacement; do not use for adult streetwear or plain white-background packshots.
---

# Konny Lifestyle Fashion

Create an original, coherent baby/toddler fashion campaign inspired by the soft Korean lifestyle language defined in [references/style-system.md](references/style-system.md). Treat the reference brand as directional research, never as a request to reproduce a specific copyrighted photograph, logo, layout, or identifiable child.

## Start from the inputs

Identify the deliverable, garment references, intended age range, image count or aspect ratio, and whether a reusable child identity already exists. If a consequential input is missing, make a conservative assumption and state it. Never invent garment construction that is hidden in the reference; flag uncertain details.

If source images are available, inspect them before writing prompts. Extract silhouette, neckline, sleeves, closures, waistband, pockets, seams, trim, print placement, fabric texture, color, and front/back differences. Treat these as garment invariants.

## Choose the mode

- **New campaign:** cast a fictional, age-appropriate East Asian baby or toddler, build an identity sheet, then create scenes.
- **Existing identity:** use the supplied identity reference and preserve face, apparent age, hair, proportions, and distinguishing features.
- **Garment replacement:** edit a selected base image; change only the garment and explicitly lock identity, anatomy, pose, crop, camera, background, shadows, and lighting.
- **Prompt package:** when image generation is unavailable or the user only wants instructions, return production-ready prompts plus the shot list and QA checklist.

Do not claim that an identity is perfectly persistent across tools. Prefer several clean reference views and reject drift.

## Production workflow

1. Write a compact visual brief from the garment, then select one age band and one stable model identity.
2. For a new model, generate a neutral reference set: front, left/right three-quarter, profile, full body, smiling, curious, and calm. Use simple cream clothing and a plain warm background so styling does not contaminate identity.
3. Build a shot list with complementary roles: clean hero, seated play, walking/crawling motion, close garment detail, and optional caregiver interaction. Favor varied angles and expressions over redundant volume.
4. Generate or edit with the fixed style anchors from the style system. Keep a single campaign palette and consistent daylight direction.
5. For each approved composition, replace the clothing only after pose and expression are accepted. Use the source garment as the authoritative visual reference.
6. Run the QA gate below. Regenerate broad failures; reserve manual retouching for localized details.

When a capable image-generation or editing tool is available, use it directly. If the task names Soul ID, Soul 2.0, Higgsfield, or another external service, adapt the prompt package to that interface without pretending the service is connected. Use available MCP tools only when they are actually installed and relevant.

## Prompt construction

Build prompts in this order: subject identity and age; exact garment; natural activity and expression; environment; camera distance and height; light; color/texture treatment; preservation constraints. Use positive descriptions first, then a short negative block.

Do not put brand names in the generation prompt. Translate them into visual properties. Keep text and logos out of the generated garment unless the source clearly contains them and exact reproduction is required; plan those elements for manual finishing.

For reusable prompt patterns and shot recipes, read [references/prompt-recipes.md](references/prompt-recipes.md).

## QA gate

Reject or repair an image when any of these fail:

- identity or apparent age changes across the set;
- anatomy, hands, feet, or child proportions look implausible;
- pose is unsafe or not age-appropriate;
- garment silhouette, openings, seam structure, print scale/placement, or color deviates materially;
- fabric loses its expected drape, rib, mesh, knit, quilting, or softness;
- lighting direction, white balance, grain, or palette breaks campaign continuity;
- the image becomes glossy studio advertising, adult editorial styling, or exaggerated wide-angle imagery;
- copied brand marks, watermarks, UI, or unintended text appear.

Classify remaining garment uncertainty as high, medium, or low. Call out complex prints, lettering, tiny fasteners, lace, piping, and layered accessories for Photoshop or another precise editor rather than claiming exact AI fidelity.

## Deliverable

Return the approved outputs or prompt package with: visual brief, model/identity definition, shot list, master prompt, per-shot prompt deltas, negative prompt, locked invariants, and retouch notes. Keep the fixed style intact while allowing the garment, season, activity, location, crop, and aspect ratio to vary.
