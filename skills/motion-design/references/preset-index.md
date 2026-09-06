# Preset index

Use this compact index to select a preset, then read its archived original prompt and linked adaptation guide. Do not generate from the short description or load every template for browsing.

[Open the playable gallery](../assets/gallery.html). The gallery opens locally; previews stream from their public source and require internet. It copies a request into chat and does not launch generation itself.

| Preset | Full template | Best for | Essential input |
|---|---|---|---|
| [Kinetic typography](presets/kinetic-typography.md) | [Source + guide](templates/kinetic-typography.md) | Announcements, offers, courses, and software launches. | A message or something to promote. |
| [Glass UI launch](presets/glass-ui-launch.md) | [Source + guide](templates/glass-ui-launch.md) | SaaS, AI tools, dashboards, and service launches. | A product description or website. |
| [Product hyper-motion](presets/product-hyper-motion.md) | [Source + guide](templates/product-hyper-motion.md) | Food, drinks, beauty, and products with recognizable ingredients or parts. | A product description; a product image if its appearance must match. |
| [Tropical product](presets/tropical-product.md) | [Source + guide](templates/tropical-product.md) | Beverages, skincare, fragrances, and ingredient-led products. | A product or range, with a reference if packaging must match. |
| [Exploded product](presets/exploded-product.md) | [Source + guide](templates/exploded-product.md) | Watches, audio hardware, electronics, and engineered products. | A product reference and the components or features to show. |
| [Blueprint to building](presets/blueprint-to-building.md) | [Source + guide](templates/blueprint-to-building.md) | Property launches, architecture concepts, and development presentations. | A building concept, or references/specifications for a real development. |
| [Hybrid 2D + 3D](presets/hybrid-2d-3d.md) | [Source + guide](templates/hybrid-2d-3d.md) | Education, courses, institutions, and playful brand stories. | An organization, product, or story to explain. |
| [Flat vector explainer](presets/flat-vector-explainer.md) | [Source + guide](templates/flat-vector-explainer.md) | Apps, memberships, services, and approachable how-it-works videos. | A product or service and the problem it solves. |
| [Editorial collage](presets/editorial-collage.md) | [Source + guide](templates/editorial-collage.md) | Educational shorts, thought leadership, and concise concept explainers. | A topic and the point viewers should understand. |
| [Footage + graphics](presets/footage-overlays.md) | [Source + guide](templates/footage-overlays.md) | Talking-head content, product demos, tutorials, and founder updates. | The source video and the message the graphics should support. |

## Names and aliases

- **Kinetic typography** (`kinetic-typography`): kinetic type, animated text, type animation, typography.
- **Glass UI launch** (`glass-ui-launch`): glass UI, SaaS launch, Tepsira, optical glass.
- **Product hyper-motion** (`product-hyper-motion`): ingredient tunnel, burger, Higgs Burger, hyper motion, food assembly.
- **Tropical product** (`tropical-product`): tropical, jungle product, fruit relay, tropical product film.
- **Exploded product** (`exploded-product`): watch, exploded view, component fly-through, macro fly-through.
- **Blueprint to building** (`blueprint-to-building`): blueprint, Higgs Park, architecture, architectural transformation.
- **Hybrid 2D + 3D** (`hybrid-2d-3d`): hybrid, university, 2D 3D, flat characters on 3D.
- **Flat vector explainer** (`flat-vector-explainer`): HiggsFit, pure 2D, vector, flat vector, app explainer.
- **Editorial collage** (`editorial-collage`): paper collage, editorial, science explainer, recorded voice.
- **Footage + graphics** (`footage-overlays`): motion on footage, presenter, overlays, talking head, real footage.

## Defaults and source differences

New motion/launch adaptations default to music plus synchronized effects, no narration, and 15 seconds / 30fps unless explicit campaign choices or source-footage continuity require otherwise. Use one full-film request; references are optional. Retiming and replacing source silence are labeled adaptations. Most use 16:9; Exploded product starts at 9:16. Explicit campaign choices take precedence. The source baselines include distinct endings: Kinetic typography holds its final line; Glass UI freezes the complete final frame; Blueprint to building ends by un-plotting. Retain those endings where they serve the new film; adapt them deliberately rather than adding a generic house fade or assuming a seamless loop.

Source examples may contain audio, branded claims, external reference requirements, or different native durations. These are not inherited permissions or guarantees. The footage section contains two preview clips without a verified input/output relationship. The architectural example has a misleading image-model Recreate parameter, and the watch preview is portrait despite landscape language in its linked prompt. Discover actual tool capabilities at execution time.

[Source article](https://higgsfield.ai/@adilinthewildtempo/blogs/claude-fable-5-1-higgsfield-marketing-studio-300-day). Source mapping observed 2026-09-03. Version 4 archives the exact original prompts with verified hashes and keeps separate adaptation guides. Start from the original text and its effective visual and motion techniques, adapting the sequence and timing to the viewer takeaway. Prefer a suitable current Seedance model; record a different source route as provenance. See [template-adaptation.md](template-adaptation.md).

To extend the library, follow [preset-workflow.md](preset-workflow.md), update the catalog, preset and full template, and rerun `scripts/build_gallery.py`.
