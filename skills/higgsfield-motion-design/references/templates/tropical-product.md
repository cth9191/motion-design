# Tropical product — source adaptation guide

Preset ID: `tropical-product` · Template version: 4

**Required first read:** [Exact original prompt](../source-prompts/tropical-product.txt). Start the production prompt from that text and keep its original format. The parameterized material below is a content-mapping and fidelity guide, not replacement wording. One full-film request; optional references; current suitable Seedance preferred. Source route and native settings are provenance.

## Source and deliberate differences

Five source compositions with slow motion, not a fast hyper-motion or variant-relay film. The source explicitly repeats identical bottles in the three-product view. Its header says 16:9 and 24fps but also gives vertical safe-zone guidance; use the campaign format and conform delivery fps separately.

[Published prompt and example](https://higgsfield.ai/@adilinthewildtempo/blogs/claude-fable-5-1-higgsfield-marketing-studio-300-day) — section: Hyper-Motion from One Message. [Play preview](https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/a95756c8-1f3f-4d93-9ea9-a14832aba4bd.mp4). Source model label: `marketing_studio_video` (historical metadata, not a model selection instruction). The catalog stores a source-text fingerprint for version tracking, not proof of output fidelity.

## Bind the subject

BRAND; PRODUCT_REFERENCE; IDENTITY_ANCHOR; INGREDIENT_CAST; SERVING_OBJECT; PRODUCT_CONTENTS; PALETTE.

Resolve these semantic fields from the campaign and source material. Numbered/ranged fields mean one concrete binding for each use. Replace every `{{...}}` before submission. Include a per-shot exact-copy list, relevant input assets and expected end state. Never submit this file with unresolved variables. Follow [template-adaptation.md](../template-adaptation.md) for the mapping and fidelity check.

## Asset plan

Apply these asset suggestions only when identity accuracy or the selected model requires them. Prompt-only is valid when sufficient; prefer existing assets and add generated references only for a specific need. Distinct shot compositions do not require an image or video job per shot.

Use the actual product reference; the source’s image placeholder is not an available attachment. One packaging identity reference can support the five different scene compositions. Derive repeated products from that identity. Choose ingredients from product information; do not invent flavors or ingredients simply because they look tropical.

## Default design bindings

Environment roles: deep green #0E3B24, lit green #3FA65B, sunlight #FFC63F, cool fill #1B6E75 and specular white #FFFFFF. Product colors come from the real product reference. Reference condensation calls for roughly 0.5–2 mm droplets over about seventy percent of the surface; scale droplets to the actual product rather than painting oversized beads.

## Audio branch

The source prompt is silent. For a new launch/motion campaign, replace its silence clauses with instrumental music and synchronized effects and record that departure. Preserve an explicit silent request. Do not add narration by default.

## Parameterized mapping aid — adapt the original text above

```text
{{FORMAT}} | {{BRAND_OR_SUBJECT}} | {{AUDIO_SPEC}}

WORLD, SUBJECT AND DESIGN
Place {{PRODUCT_REFERENCE}} in a tropical clearing with layered deep-green foliage, wet dark stone and warm sunlight entering from above left. Use gold for backlight, a cool teal fill, and restrained humid depth. The product retains its exact packaging colors, silhouette, closure, label position and {{IDENTITY_ANCHOR}}. Environmental colors do not recolor the label. Condensation has varied real-scale beads, some merging and following gravity. {{INGREDIENT_CAST}} is a fixed set of relevant natural ingredients with fibrous skins, wet interiors and credible sizes. The only readable text is approved print on the product; there are no title overlays.

CAMERA, EDITING AND MOTION
Use slow motorized camera drift with long easing and shallow focus. Cuts connect quiet moments without dissolves or morphs. Ingredients follow stable gentle arcs and avoid covering the product’s identifying feature. Only the central levitation composition suspends the hero; in the other scenes it rests on the stage. Keep the mood slow and tactile. The final impact is the one major physical accent. Preserve natural depth and material detail without decorative flare or glow overlays.

TIMELINE — default 15-second adaptation; retime explicitly for other delivery lengths.

[0.00–2.50s] Shot 1 — condensation reveal
Frame the product standing on wet stone. Slowly boom from its base toward its closure while the upper-left sunlight catches the wet body. Let two appropriate ingredients pass in the defocused foreground without hiding the identity anchor. Keep foliage soft and secondary.

[2.50–4.50s] Shot 2 — identical depth row
Cut to three identical copies of the same product staggered in depth. Dolly gently right while focus transfers from the rear copy to the front-facing hero. Land the wordmark and identity anchor near the composition center. A relevant ingredient can cross at middle depth. This is a depth study, not three new flavors or packages.

[4.50–8.50s] Shot 3 — suspended product system
Cut to the hero levitating over the stone at about a 15-degree tilt, turning slowly around its long axis. Arrange six items from {{INGREDIENT_CAST}} on gentle orbits at distinct depths. Make a slow half-orbit around the complete arrangement. Backlight passes behind the product; suspended droplets and pollen add scale without overwhelming it.

[8.50–11.00s] Shot 4 — closure macro
Cut close to the closure and upper product body, with {{IDENTITY_ANCHOR}} still entering the composition. Drift around the closure in a slow orbital tilt. Shift focus from closure detail toward the label. Resolve condensation sharply; use cool vapor only if physically plausible for the product.

[11.00–15.00s] Shot 5 — serving impact and hold
Cut to the hero beside {{SERVING_OBJECT}} on the same wet stage. Drop a small number of relevant ingredients into {{PRODUCT_CONTENTS}} in pronounced slow motion. Show the impact, a controlled crown or displacement, and droplets landing on the stage. Have the splash settle before 14.0 seconds, then hold the final product tableau for one second. For non-liquid products substitute an appropriate contact event and record that change; do not invent a beverage use. No added type or unrelated endcard.

COPY AND REFERENCES
{{EXACT_COPY_BY_SHOT}}. No other readable text. Use {{ASSET_BINDINGS}} with their declared identity/style/start/end/overlay roles. Preserve real product identity, supported claims and specified component geometry.

DELIVERY
{{DELIVERY_AND_FINISHING_PLAN}}. Audio follows {{AUDIO_SPEC}} throughout. Submit all timed shots and shared rules as one complete-film request. Separate clips are an accepted fallback only, as described in production.md.
```

## Fidelity checks

- Camera remains slow through all five compositions.
- Only shot 3 levitates the hero; shot 2 repeats identical packages.
- Packaging stays stable and the final physical action matches the real product.
- No graphic headlines or CTA are added to this product-only preset.

Compare these checks with the rendered motion, not just the prompt. A missing signature action is a failed shot even if its materials look polished. Repair that shot or report the specific departure; do not relabel a generic result as this preset.
