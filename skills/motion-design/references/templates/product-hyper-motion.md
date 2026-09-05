# Product hyper-motion — source adaptation guide

Preset ID: `product-hyper-motion` · Template version: 4

**Required first read:** [Exact original prompt](../source-prompts/product-hyper-motion.txt). Start the production prompt from that text and keep its original format. The parameterized material below is a content-mapping and fidelity guide, not replacement wording. One full-film request; optional references; current suitable Seedance preferred. Source route and native settings are provenance.

## Source and deliberate differences

Seven source shots and their cut times are preserved. The original uses a burger, a diner and a supplied final image. Substitute a physically meaningful ingredient/component sequence, setting and designed end image; the source end-image attachment is not included with the article.

[Published prompt and example](https://higgsfield.ai/@adilinthewildtempo/blogs/claude-fable-5-1-higgsfield-marketing-studio-300-day) — section: 3. Hyper-Motion (the style every brand orders). [Play preview](https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/d1e752b7-ea6b-4553-98c6-15c8f3bf0cb4.mp4). Source model label: `marketing_studio_video` (historical metadata, not a model selection instruction). The catalog stores a source-text fingerprint for version tracking, not proof of output fidelity.

## Bind the subject

BRAND; HERO_REFERENCE; SETTING; COMPONENTS_IN_ASSEMBLY_ORDER; TRIGGER_COMPONENT; SURFACE_DETAIL; FINISHING_DETAIL; IDENTITY_ANCHOR; ENDCARD_REFERENCE; WORDMARK; TAGLINE; OPTIONAL_MASCOT; PALETTE.

Resolve these semantic fields from the campaign and source material. Numbered/ranged fields mean one concrete binding for each use. Replace every `{{...}}` before submission. Include a per-shot exact-copy list, relevant input assets and expected end state. Never submit this file with unresolved variables. Follow [template-adaptation.md](../template-adaptation.md) for the mapping and fidelity check.

## Asset plan

Apply these asset suggestions only when identity accuracy or the selected model requires them. Prompt-only is valid when sufficient; prefer existing assets and add generated references only for a specific need. Distinct shot compositions do not require an image or video job per shot.

Use a real product reference and a correct component inventory. Design the new brand’s final graphic before video generation; it replaces the source’s missing attachment. Generate separate preparation/tunnel/assembly references only as needed. For a product without a truthful component assembly, explain the fit problem and select a minimal material journey rather than inventing internals.

## Default design bindings

Source physical-world anchor is burgundy #A02128, with cream, bread gold and cheese orange. Bind exact values for the new material/brand roles. The final flat card uses red and cream. Maintain the warm physical light / dark rim-lit tunnel / flat graphic contrast.

## Audio branch

For the default music/effects version, use an orchestral pulse that suspends at the trigger apex, becomes airy in the tunnel, regains weight on the return and resolves with the graphic endcard. Synchronize preparation detail, passing components, weighted landings and paper-graphic arrivals. Narration is a separate requested branch: write new product-specific phrases for 0–2.5, 3.5–5.5, 7–10, 10.5–12, 12.8–13.5 and 14–15 seconds, then verify a natural reading fits. Do not inherit burger copy or add voice merely because the example contains it.

## Parameterized mapping aid — adapt the original text above

```text
{{FORMAT}} | {{BRAND_OR_SUBJECT}} | {{AUDIO_SPEC}}

WORLD, SUBJECT AND DESIGN
Create a high-energy physical product film for {{BRAND}}. Move through four linked environments/actions: tactile preparation in {{SETTING}}, flight through a deep accent-colored component tunnel, return to the preparation surface for assembly, and a flat graphic endcard. The finished hero must match {{HERO_REFERENCE}} and retain {{IDENTITY_ANCHOR}}. Use warm hard practical-looking light in the physical setting, hard edge light in the tunnel, and even illumination on the final graphic. Default color roles are burgundy, cream, warm gold and a small ingredient accent. Preserve material texture and natural irregularity; no generic smooth plastic substitutes.

CAMERA, EDITING AND MOTION
Use close probe-like passes, short slow-motion accents and strong speed ramps. Camera motion is smooth and purposeful, with large near/middle/far parallax. Enter the tunnel by following a falling component and leave by following components toward the assembly surface. In the assembly the camera and arriving parts travel in opposite orbital directions. Every landed part remains present and partially visible; the stack only grows. Soft ingredients compress briefly on landing, rigid components seat without deformation. Thin slices retain their identity. Keep typography confined to the endcard except existing approved product marks.

TIMELINE — default 15-second adaptation; retime explicitly for other delivery lengths.

[0.00–2.00s] Shot 1 — tactile preparation macro
Start in active {{SURFACE_DETAIL}}, using a fast low oblique pass across the preparation surface, roughly an 18-degree view. Show the small material events that explain the product: texture, beads, fibers or a precise component action. Any vapor or droplets must continue moving naturally; avoid static steam and unsupported fire effects.

[2.00–2.80s] Shot 2 — physical trigger
Cut to an oblique view around 47 degrees as {{TRIGGER_COMPONENT}} flips or lifts. Briefly slow its apex. As it starts falling, inherit that downward vector in a whip transition into the dark accent tunnel. The physical action motivates the transition; do not switch worlds before it falls.

[2.80–5.30s] Shot 3 — travel through components
Fly straight through a tunnel made from {{COMPONENTS_IN_ASSEMBLY_ORDER}}, rotating steadily around the travel axis. Nearby parts pass close and blur while distant ones retain readable shapes. Keep their material-specific traces small and coherent. Build a warm exit ahead; finish with the parts converging and streaming toward it.

[5.30–6.00s] Shot 4 — return to the surface
Follow the same descending stream as the original {{SETTING}} rises into view. Reveal the base component waiting on the assembly surface. Match motion, exposure and light direction through the return so it feels connected to the tunnel exit.

[6.00–10.50s] Shot 5 — counter-orbit assembly
Camera circles clockwise while incoming components approach counterclockwise, each crossing the foreground before landing. Assemble {{COMPONENTS_IN_ASSEMBLY_ORDER}} in its actual functional order. At every landing retain all prior layers, their edges and {{IDENTITY_ANCHOR}}. Use brief compression and damped recovery for soft parts. Give the final crown/cover a short slow-motion descent and one small settling action. Finish with the complete, correct hero silhouette.

[10.50–12.00s] Shot 6 — overhead hero
Continue the orbital momentum into a rising spiral that reaches an overhead product view. Let {{FINISHING_DETAIL}} remain subtly alive while the complete construction is readable. Keep the product’s established size and component count; do not replace it with a differently assembled beauty render.

[12.00–15.00s] Shot 7 — graphic endcard build
Snap-wipe into the flat branded background. Assemble {{WORDMARK}} with sequential descending letters and small elastic settles. Draw a thin orbit ring in the opposite direction, unfurl {{TAGLINE}} below, and bring in {{OPTIONAL_MASCOT}} only if appropriate to the brand. Move simple border strips in opposite directions. Schedule these actions to settle by 14.2 seconds, then hold the full {{ENDCARD_REFERENCE}} composition through 15.0. The final target image must actually be attached when using an end-frame role.

COPY AND REFERENCES
{{EXACT_COPY_BY_SHOT}}. No other readable text. Use {{ASSET_BINDINGS}} with their declared identity/style/start/end/overlay roles. Preserve real product identity, supported claims and specified component geometry.

DELIVERY
{{DELIVERY_AND_FINISHING_PLAN}}. Audio follows {{AUDIO_SPEC}} throughout. Submit all timed shots and shared rules as one complete-film request. Separate clips are an accepted fallback only, as described in production.md.
```

## Fidelity checks

- Both tunnel transitions inherit the specified component motion.
- Assembly order and persistence are correct; no landed part disappears.
- Counter-orbit is visible, with camera and parts traveling opposite ways.
- The target endcard belongs to the new brand and is reached without a late random cut.

Compare these checks with the rendered motion, not just the prompt. A missing signature action is a failed shot even if its materials look polished. Repair that shot or report the specific departure; do not relabel a generic result as this preset.
