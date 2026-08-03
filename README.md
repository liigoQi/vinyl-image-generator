# Vinyl Image Generator

Turn a sentence, memory, emotion, story, object, place, or source image into a cohesive fictional vinyl release artifact.

This Codex skill directs an image-generation model to create one believable **4:3 landscape product photograph** containing exactly four connected pieces from the same fictional release:

```text
Front sleeve     Vinyl Side A
Vinyl Side B     Back sleeve
```

The skill treats the result as a designed physical object—not a poster or a generic album-cover mockup. It develops a fictional artist identity, sonic character, design history, typography system, tracklist, print process, sleeve materials, and vinyl pressing from the source concept.

## What it does

- Translates emotional and narrative material into a coherent visual language
- Creates a fictional artist, label, catalog number, release history, and tracklist
- Verifies that the invented artist name does not collide with a real musical act when web search is available
- Designs distinct front and back sleeves plus matching Side A and Side B labels
- Specifies believable paper, ink, finishing, vinyl material, lighting, and physical wear
- Handles source images as creative evidence while protecting unnecessary identifying details
- Enforces a centered four-object layout with no overlap, cropping, shrink wrap, or decorative props

## Requirements

- Codex or another agent runtime that supports `SKILL.md` skills
- An image-generation tool capable of following detailed layout instructions
- Optional web search for fictional artist-name collision checks
- Optional image inspection when source images are supplied

## Installation

Clone the repository into your Codex skills directory:

```bash
git clone https://github.com/liigoQi/vinyl-image-generator.git ~/.codex/skills/vinyl-image-generator
```

Restart Codex if the skill is not discovered automatically.

You can also copy the repository folder into any skills directory recognized by your agent runtime. Keep `SKILL.md` at the repository root.

## Usage

Invoke the skill explicitly and provide the source material:

```text
$vinyl-image-generator

We live as we dream—alone.
```

Other examples:

```text
Use $vinyl-image-generator to turn this memory into a fictional record:
The last ferry left before I reached the pier, and the vending machine kept humming.
```

```text
Use $vinyl-image-generator with the attached photograph. Preserve its rainy green palette
and window reflections, but obscure recognizable faces.
```

The skill generates exactly one image, then reports the release concept, tracklist, and visual-production notes.

## Output contract

Every generated image must be:

- Exactly one `4:3 landscape (width:height = 4:3)` image
- A clean 2-by-2 arrangement of front sleeve, Side A, Side B, and back sleeve
- Centered on one flat solid-color background with generous whitespace
- Physically consistent, fully visible, separated, and free of plastic packaging
- Based on one unified fictional release and an entirely invented musical act

See [SKILL.md](SKILL.md) for the full workflow and generation constraints.

## Repository structure

```text
vinyl-image-generator/
├── SKILL.md
├── README.md
├── LICENSE
└── agents/
    └── openai.yaml
```

## Contributing

Issues and pull requests are welcome. Changes should preserve the mandatory four-object layout, fictional-artist safeguards, physical-material logic, and negative constraints. Keep the skill instructions focused and validate the folder before submitting.

## Contributors

- [@liigoQi](https://github.com/liigoQi) — creator and maintainer

## License

Released under the [MIT License](LICENSE).
