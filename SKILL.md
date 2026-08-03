---
name: vinyl-image-generator
description: Transform a memory, sentence, emotion, story, object, place, or source image into one cohesive fictional vinyl release artifact containing a front sleeve, back sleeve, vinyl Side A, and vinyl Side B. Use when generating a believable 4:3 landscape product photograph of an independent-label record whose visual language, typography, printing history, packaging, and physical materials express the source concept.
---

# Fictional Vinyl Release v2.2

Turn a memory into a vinyl record that never existed.

Transform the user's sentence, memory, emotion, story, object, place, or image into a complete fictional release. Make it feel like a music artifact with a design history, not a pleasant picture with a title placed on top.

The result must resemble a carefully photographed physical record package from an independent label. It is not an album poster, advertisement, streaming cover, or luxury product render.

## Mandatory Output

Generate exactly one **4:3 landscape image** with width greater than height. State the aspect ratio explicitly as `4:3 landscape (width:height = 4:3)` in the generation prompt. Never request a portrait canvas.

Show exactly four connected elements from the same fictional release:

1. Front sleeve
2. Vinyl Side A
3. Vinyl Side B
4. Back sleeve

Use a clean 2-by-2 arrangement:

```text
Front sleeve     Vinyl Side A
Vinyl Side B     Back sleeve
```

Keep the complete arrangement centered with generous, balanced whitespace. Use one flat solid-color background selected from the release mood. Do not add gradients, scenery, rooms, furniture, props, or decorative background patterns.

Make all four objects:

- fully visible and separated
- evenly scaled and physically consistent
- front-facing or photographed from a very slight overhead angle
- free of cropped edges and overlap
- The vinyl disc must maintain a true circular shape with no distortion

Give both sleeves identical dimensions. Give both records identical diameters and pressing styles. Show both records completely removed from the sleeves.

## Core Design Principle

Build the release in three connected layers:

1. **Visual-language generation**: translate emotion, music, era, and symbolism into an art direction.
2. **Packaging design**: apply that direction to cover composition, typography, back-cover grid, labels, credits, and print production.
3. **Physical-object simulation**: render exposed paper, ink, vinyl, sleeve edges, aging when appropriate, and believable photography.

Do not jump directly from the user's source material to a pretty cover image.

## Interpretation and Fictional Design History

Before designing, extract:

- dominant mood and emotional tension
- implied music genre or sonic character
- place and time
- important objects and sensory details
- one primary symbolic idea
- desired distance from literal reality

Then invent a concise internal design history:

- fictional artist and label identity
- release era or contemporary context
- original pressing, archival discovery, or reissue status
- regional or scene influence
- printing method and material choices available in that context
- why the artwork, typography, and imperfections look this way

Use era references as production logic, not as decorative nostalgia. Do not automatically make the release vintage, retro, faded, or distressed.

## Fictional Artist Identity

The artist identity must be wholly fictional. Never use the name of a real musician, singer, producer, DJ, composer, band, musical group, or performance act, whether contemporary, historical, active, inactive, famous, or obscure.

Create an original artist or band name that feels like a real music act. The name should be memorable, natural, and believable within an actual music scene, matching the inferred sonic character, language, region, and design history.

Avoid names that feel randomly generated, overly abstract, excessively strange, fantasy-like, or like a brand/product name. Prefer names with subtle personality, cultural texture, and a sense of artistic identity — the kind of name that could plausibly appear on a real album cover, festival lineup, or record label catalog.

The name should be distinctive but not forced: interesting enough to spark curiosity, while remaining easy to read, pronounce, and remember.

Do not use:

- exact real artist or band names
- alternate spellings, translations, abbreviations, former names, stage names, or aliases of real artists
- names that differ from a real act only by punctuation, spacing, capitalization, one character, or a generic suffix such as “Band,” “Collective,” “Orchestra,” or “Project”
- a real artist's name combined with another word in a way that could imply an official side project, tribute act, collaboration, or archival release

Before finalizing the release identity, check whether the proposed artist name is already used by a musical act. When internet search is available, verify the exact name and close variants using a web search. If any meaningful collision or ambiguity appears, discard the name and generate a more distinctive replacement. Do not mention real artists as style references in the final generation prompt unless the user explicitly requests them; describe the sonic and visual qualities directly instead.

## User-Provided Image Input

When the user uploads or references one or more images, inspect every source image before generating the release. Treat the images as visual evidence and creative material, not as finished cover art or a template to reproduce unchanged.

For each image, identify:

- primary and secondary subjects, including people, objects, architecture, landscape, weather, and visible actions
- dominant and accent colors, contrast, lighting direction, time-of-day cues, and atmosphere
- distinctive shapes, silhouettes, textures, patterns, reflections, shadows, and spatial relationships
- emotional signals such as intimacy, distance, celebration, solitude, tension, movement, or stillness
- place, season, era, and cultural details that can be inferred without inventing unsupported personal facts
- visually sensitive details, including faces, names, addresses, license plates, screens, documents, and other identifying information

Select a small set of source-derived elements with clear roles:

1. **Primary anchor**: the strongest subject, object, shape, absence, or spatial relationship that can carry the front sleeve.
2. **Supporting motifs**: one to three colors, textures, lines, shadows, gestures, or environmental details that can connect the front, back, and center labels.
3. **Material cue**: one source texture or surface quality that can inform paper, ink, vinyl, or finishing choices.
4. **Emotional tension**: the contrast that gives the release depth, such as warmth versus distance, motion versus stillness, or celebration versus impermanence.

Choose the degree of transformation that best preserves the meaning:

- **Direct photographic**: retain a recognizable source fragment when identity and documentary specificity are essential.
- **Editorial crop**: isolate an expressive detail, silhouette, reflection, gesture, or negative space rather than using the full image.
- **Abstracted translation**: convert colors, contours, light, textures, or object relationships into graphic forms when privacy, ambiguity, or stronger symbolism benefits the release.
- **Composite memory**: combine compatible elements from multiple supplied images into one controlled visual system; do not fabricate a literal event that the images do not support.

If people appear, decide whether their identity is conceptually necessary. Prefer crops, silhouettes, blur, reflections, hands within the cover artwork, or symbolic substitution when recognizable faces add little. Do not infer names, relationships, ethnicity, health, beliefs, occupation, or other sensitive attributes from appearance. Never place source-image people in the surrounding product-photography environment.

Preserve distinctive source cues across the entire release rather than placing the image unchanged on the front and ignoring it elsewhere. Carry selected colors, contours, textures, or marks into the back-cover grid, center labels, vinyl pressing, and print production. The result must remain a newly designed fictional release, not a filter, collage dump, or raw photo with typography overlaid.

When the image is unreadable, missing, or too low-resolution to extract meaningful elements, ask the user to attach a clearer version. Otherwise, proceed without asking them to describe what is already visually evident.

## Music-to-Visual Direction

Infer a visual language from the input rather than applying one fixed house style. Use these as tendencies, not rigid templates:

| Sonic character | Useful visual tendencies |
| --- | --- |
| Ambient | blur, natural forms, minimal composition, large negative space |
| Indie rock | film texture, candid photography, selective collage, imperfect print |
| Punk | rough black-and-white reproduction, photocopy texture, confrontational type |
| Electronic | geometry, synthetic color, precise grids, future-facing materials |
| Jazz | expressive photography, disciplined typography, rich paper and ink |
| Hip-hop | portrait or street-derived imagery, bold hierarchy, cultural specificity |
| Folk | natural materials, hand-made marks, paper texture, intimate typography |
| Dream pop | soft focus, bloom, hazy color, layered translucent imagery |

If no genre is implied, choose an independent-label visual direction that best carries the emotional tension. Possible directions include contemporary minimal, modernist, editorial, photographic, abstract graphic, conceptual illustration, archival, underground, bedroom recording, and contemporary limited pressing.

## Artwork Transformation

Treat source imagery as raw visual material, not finished cover art. Analyze its colors, light, objects, textures, locations, atmosphere, and emotional feeling. Reinterpret these features through a designed visual system.

Choose only the treatments that strengthen the concept. Usually combine two to four coherent treatments; do not use every technique at once.

### Color reconstruction

Use deliberate color grading or palette replacement to create the release's world. Examples include low-saturation cool tones for distance, warm contrast for visceral nostalgia, fluorescent accents for electronic tension, or a controlled color cast for an artificial reality.

### Grain, noise, and temporal texture

Use film grain, dust, light leaks, scratches, fading, photocopy noise, or print misregistration only when the fictional era and sonic character justify them. Distinguish simulated image texture from actual damage to the physical sleeve.

### Blur and optical displacement

Use soft focus, motion blur, imperfect focus, long exposure, bloom, reflections, or scanning artifacts to shift attention from literal identity toward feeling. Keep the main symbolic idea readable.

### Collage and layering

When appropriate, combine photographs, magazine fragments, drawings, maps, tickets, plants, architecture, handwriting, scanned paper, transparent textures, or symbols into one controlled memory archive. Preserve hierarchy; avoid unrelated scrapbook clutter.

### Symbolic anchor

Create a memorable visual hook: one object, absence, shape, space, or recurring mark that carries the emotional meaning. Transform ordinary objects through context rather than merely displaying them.

### Deliberate imperfection

Allow selective human irregularity when appropriate: slightly displaced type, unusual cropping, unequal negative space, overexposure, registration errors, handwritten correction, or uneven ink. Make imperfection intentional and concept-driven, not careless or universally distressed.

## Front Sleeve

Answer: "If this memory / object / story / sentence became a record, what visual world and one primary symbol would represent it?"

Design a cover with:

- one dominant concept or symbolic anchor
- a deliberate visual hierarchy and viewing path
- meaningful negative space
- release title and fictional artist identity
- typography integrated with the image rather than pasted beneath it
- image processing consistent with the fictional design history

The subject may be small, off-center, partially obscured, cropped unexpectedly, or surrounded by negative space if that choice communicates the music. Avoid literal story summaries, generic beauty, crowded collage, and multiple competing metaphors.

## Typography System

Treat typography as a primary visual layer.

Choose type for conceptual reasons:

- serif for literary, classical, archival, or jazz-inflected character
- sans serif for modern, cool, electronic, or minimal character
- handwriting for intimacy, diary-like memory, or human presence
- custom lettering or a fictional logotype when the artist identity needs a distinct mark

Design hierarchy, scale, tracking, alignment, placement, interaction with imagery, and controlled obstruction. The title may sit in a corner, cross an image boundary, hide partly behind a form, or become the central image. Maintain legibility for essential release information.

Use one coherent type system across front sleeve, back sleeve, and center labels.

## Back Sleeve

Design the back sleeve as a separate piece of packaging design, not a variation or continuation of the front cover.

The back should clearly belong to the same vinyl release through shared:
- typography system
- color palette
- printing technique
- material texture
- overall art direction

The back sleeve should not be merely an information display. Treat it as a designed artwork in its own right, with intentional composition, typography, and visual elements. It should balance functional information design with artistic expression while remaining part of the same release identity.

However, it must have a fundamentally different visual structure and purpose.

Avoid:
- reusing the same main image as the focal point
- placing the same artwork with added text
- making it look like a poster back side

Instead, create a functional record back cover layout:

Include:
- Side A and Side B tracklists with clear hierarchy
- recording information and credits
- catalog number
- fictional label identity
- optional barcode
- production notes or small-print details

Match the front's typography, palette, grid logic, image treatment, production method, and imperfection language. Keep the information hierarchy plausible and readable.

## Tracklist Generation

Generate imaginative track titles from the user's input. Do not copy the user's sentences or summarize events literally. Expand the emotional world with poetic, strange, specific, or atmospheric titles. The tracklist should fit for the genre you chose in Music-to-Visual Direction Step.

Vary title rhythm and length. Mix short titles such as `Static`, medium titles such as `The Last Train Through Summer`, and occasional long titles such as `I Left the Window Open Because the Night Felt Different`.

Avoid uniformly poetic, generic, equally long, or purely descriptive titles. Make the sequence feel like a real independent album.

1-3 songs for Side A and 1-3 songs for Side B.

## Vinyl Side A and Side B

Show both records fully outside the sleeves. Put these on each center label:

- artist name
- release title
- Side A or Side B
- catalog number
- fictional label identity

Maintain the release's typography, colors, printing character, and visual motifs.

Do not automatically use black vinyl. Choose an intentional pressing: transparent, translucent, smoke, marble, splatter, split color, two-tone, or milky clear. Relate the pressing material to the concept without making it look like decorative candy.

## Packaging and Print Production

Select a coherent physical production system that supports the release's visual concept and design history. The material and printing choices should feel intentional rather than automatically vintage, handmade, or archival.

Possible production approaches include:

- paper stocks: matte, uncoated, coated, recycled, textured, or unconventional materials when appropriate
- printing methods: offset, risograph, screen print, letterpress, photocopy reproduction, digital printing, or experimental processes
- finishing techniques: spot gloss, foil, embossing, debossing, die-cutting, overprint, transparent layers, or other concept-driven treatments
- additional design elements such as transparent overlays, printed inner-sleeve motifs, or label-specific marks when visible

Make technique affect the image: risograph may show limited inks and slight misregistration; screen printing should have strong ink fields; letterpress should create restrained paper indentation; foil and spot gloss should react to light selectively.

Do not combine unrelated techniques merely to make the design appear more complex. Choose one primary production method and at most two supporting finishes.

Do not assume that an independent-label release must look vintage, handmade, beige, or analog. Contemporary releases may use vivid colors, dark materials, synthetic surfaces, experimental printing, or modern manufacturing techniques when they better express the music and concept.

## Physical Packaging Appearance

Show both sleeves completely unwrapped. Do not add shrink wrap, cellophane, protective bags, plastic film, folded plastic edges, sealing seams, or plastic reflections.

Render the physical qualities of the chosen material directly:

- realistic surface texture appropriate to the selected stock or material
- believable ink, coating, printing, or surface behavior
- subtle edge thickness, folds, corners, and manufacturing tolerances
- restrained highlights only when justified by the selected material or finishing technique
- natural contact shadows that give each object physical weight

If the fictional design history calls for an older release, allow subtle paper aging, edge wear, faded ink, or archive/reissue traces on the exposed sleeve. Do not confuse intentional graphic distress with random damage.

The final image should resemble an unwrapped physical record artifact photographed for an independent-label archive or catalog, not a glossy CGI render or a sealed retail product. Avoid luxury-product staging, excessive reflections, plastic-like paper, and perfect weightless geometry.

## Release Construction Workflow

Follow this order:

1. If source images are provided, inspect each image and extract the primary anchor, supporting motifs, material cue, emotional tension, privacy considerations, and appropriate transformation degree.
2. Combine the visual evidence with the user's text, then extract mood, sonic character, place, time, sensory details, tension, and symbol.
3. Invent the artist, title, label, catalog number, format, and concise design history; verify that the artist name and close variants do not belong to a real musical act, and replace any ambiguous name.
4. Choose one visual direction and a music-appropriate typography system.
5. Select two to four coherent artwork treatments.
6. Choose one print method, paper stock, and up to two special finishes.
7. Design the front sleeve as a visual world rather than a decorated photo.
8. Design the complementary back sleeve and information hierarchy.
9. Generate a varied, credible tracklist.
10. Design Side A and Side B labels and choose an intentional vinyl pressing.
11. Render the unwrapped paper sleeves and any era-appropriate physical character; verify that no plastic packaging is present.
12. Arrange exactly four objects on a `4:3 landscape (width:height = 4:3)` canvas.
13. Verify that source-derived elements are meaningfully transformed and carried across the release, then verify conceptual unity, text hierarchy, print logic, packaging realism, privacy, and object count.

## Generation Prompt Requirements

In the final image-generation prompt, explicitly specify:

- `exactly one 4:3 landscape image, width:height = 4:3`
- the exact four-object 2-by-2 arrangement
- when source images are supplied, the selected source-derived primary anchor, supporting motifs, material cue, emotional tension, and transformation degree
- which recognizable details must be preserved, obscured, cropped, or abstracted
- fictional release identity and tracklist, explicitly stating that the artist is invented and not a real musician or band
- sonic character and design history
- selected visual treatments, typography, print method, paper, and finishes
- vinyl color and pressing method
- exposed paper, ink, sleeve-edge behavior, and an explicit `no shrink wrap or plastic packaging` constraint
- solid background color and generous whitespace
- all negative constraints

Do not prompt with empty phrases such as `beautiful album cover` or `aesthetic vinyl`. Describe the causal design logic instead.

## Negative Constraints

Avoid:

- portrait or vertical canvas
- album posters, streaming covers, or advertisements
- luxury mockups and glossy CGI appearance
- people or hands unless the source concept absolutely requires a depicted person in the cover artwork; never place people in the product-photo environment
- rooms, scenery, furniture, and random props around the objects
- decorative background patterns or gradients
- records inside sleeves, extra packaging components, shrink wrap, cellophane, protective plastic bags, or any plastic film
- cropped, overlapping, mismatched, extra, or missing objects
- unrelated design systems across front, back, and labels
- a raw photograph with title text simply placed on top
- unedited source images used as complete sleeve designs, unsupported additions presented as source facts, or unnecessary exposure of identifying details
- invented personal or sensitive attributes inferred from people in source images
- real artist, musician, producer, DJ, composer, band, or musical-group names used as the fictional Artist; near-copy names or aliases that could be mistaken for a real act
- generic typography or weak information hierarchy
- arbitrary mixtures of film grain, collage, blur, and distress
- automatic vintage styling
- identical track-title lengths
- excessive sleeve damage, implausible reflections, or plastic-looking paper

## Output Delivery

After generating the image, provide:

### Release Concept

Artist:
Title:
Format:
Catalog No.:
Label:
Sonic Character:
Design History:
Art Direction:
Background Color:

### Tracklist

Side A:

1.
2.

Side B:

1.
2.

### Visual and Production Notes

- Front concept:
- Back concept:
- Image treatments:
- Symbolic anchor:
- Typography:
- Print method and paper:
- Vinyl color and material:
- Unwrapped sleeve material and edge treatment:
- Production finish:
