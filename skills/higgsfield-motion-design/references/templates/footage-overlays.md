# Footage + graphics — source adaptation guide

Preset ID: `footage-overlays` · Template version: 4

**Required first read:** [Exact original prompt](../source-prompts/footage-overlays.txt). Start the production prompt from that text and keep its original format. The parameterized material below is a content-mapping and fidelity guide, not replacement wording. One full-film request; optional references; current suitable Seedance preferred. Source route and native settings are provenance.

## Source and deliberate differences

The source prompt uses two camera setups: a static first view and a newly generated second angle at 5 seconds. It also requests cloned speech. Selecting this visual preset does not request identity cloning, rewritten speech or a synthetic angle. Preserve the two-view structure when suitable footage exists; otherwise keep the supplied footage and record the visual departure. Neither of the two published preview URLs is verified as the input attachment.

[Published prompt and example](https://higgsfield.ai/@adilinthewildtempo/blogs/claude-fable-5-1-higgsfield-marketing-studio-300-day) — section: 2. Motion on Top of Real Footage ($200 - $500 per 60 seconds). [Play preview](https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/d94bfad5-165f-4c27-ba85-bd169b1e3408.mp4). Source model label: `minimax_h3_max` (historical metadata, not a model selection instruction). The catalog stores a source-text fingerprint for version tracking, not proof of output fidelity.

## Bind the subject

FOOTAGE_REFERENCE; GRAPHIC_REFERENCE; CUE_SHEET; OVERLAY_1..4; LEFT_SAFE_ZONE; RIGHT_SAFE_ZONE; SUBJECT_MATTE; PALETTE; CAMERA_B_PLAN.

Resolve these semantic fields from the campaign and source material. Numbered/ranged fields mean one concrete binding for each use. Replace every `{{...}}` before submission. Include a per-shot exact-copy list, relevant input assets and expected end state. Never submit this file with unresolved variables. Follow [template-adaptation.md](../template-adaptation.md) for the mapping and fidelity check.

## Asset plan

Apply these asset suggestions only when identity accuracy or the selected model requires them. Prompt-only is valid when sufficient; prefer existing assets and add generated references only for a specific need. Distinct shot compositions do not require an image or video job per shot.

Essential: the user’s actual footage. Inspect transcript/timing and usable text zones. A generated alternate camera needs explicit task scope and model support; revoicing is a separate operation. Preserve original speech when requested. If the campaign is silent, remove audio at finishing and cue overlays to visible action. Do not fabricate a missing input video or claim that the public previews supply its identity attachment. Adapt the 5-second camera boundary to real footage timing and record the change.

## Default design bindings

Graphic accent #D1FE17 and white #FFFFFF; dark #111111 only for text inside the pill and the check symbol. These source values differ slightly from the house acid color; preserve them unless adapting to the user’s brand. The bold and outline type share one geometric family; the reference specifies Space Grotesk.

## Audio branch

Retain supplied speech and room tone only when requested, preserving its timing. Quiet graphic landing accents may be added if effects are requested. The source has no music. Voice cloning or rewriting is not part of a visual-template selection. In a silent version remove audio and bind cues to visible action.

## Parameterized mapping aid — adapt the original text above

```text
{{FORMAT}} | {{BRAND_OR_SUBJECT}} | {{AUDIO_SPEC}}

WORLD, SUBJECT AND DESIGN
Use {{FOOTAGE_REFERENCE}} as the real identity, wardrobe, environment, lens and lighting reference. Add a consistent graphic system with a bold sans, an outline variation, a rounded pill, strike line, corner brackets, check badge and underline. Default graphic colors are bright yellow-green and white, with dark lettering confined to pills or check symbols. Adapt through {{PALETTE}}. Preserve actual footage details; do not substitute the source article’s presenter, room or laptop. A design reference controls letterform and graphic treatment, not a copied background or layout.

CAMERA, EDITING AND MOTION
Words assemble left-to-right through small letter staggers, resolving from soft blur into crisp stable type in roughly half a second. Use a decisive attack and long settle without bounce. Once built, graphics remain fixed to screen coordinates even over handheld footage; exits dissolve by letter into soft blur. Animate one graphic event at a time. Start each at its corresponding {{CUE_SHEET}} event, never before. Keep face, hands and critical demonstrations visible. One designated large word may be occluded by the presenter using {{SUBJECT_MATTE}}.

TIMELINE — default 15-second adaptation; retime explicitly for other delivery lengths.

[0.00–5.00s] Shot 1 — original static angle
Preserve the supplied static viewpoint or the actual first footage segment. Place {{OVERLAY_1}} in {{LEFT_SAFE_ZONE}} as outlined letters, then fill the outlines with the accent from left to right. Hold and clear it. At the next semantic cue, expand a pill containing {{OVERLAY_2}}, build a nearby check badge and draw its check. Keep these elements stable, then clear before the camera change. Fit timing to the existing speech or demonstration rather than forcing the source’s dialogue.

[5.00–15.00s] Shot 2 — alternate angle and depth headline
Use {{CAMERA_B_PLAN}}: preferably a supplied second angle, or a generated angle only when the request includes that transformation and the model supports identity continuity. The reference motion is a side view around 45 degrees with gentle handheld breathing. In {{RIGHT_SAFE_ZONE}}, build {{OVERLAY_3}}, draw its strike and add corner brackets in sequence. Clear that group at the next cue. Assemble {{OVERLAY_4}} as a large upper-frame word behind the presenter, with head and shoulders correctly occluding it; draw the underline. Hold graphics screen-locked while the footage continues. End with the actual source action, not a generic appended card.

COPY AND REFERENCES
{{EXACT_COPY_BY_SHOT}}. No other readable text. Use {{ASSET_BINDINGS}} with their declared identity/style/start/end/overlay roles. Preserve real product identity, supported claims and specified component geometry.

DELIVERY
{{DELIVERY_AND_FINISHING_PLAN}}. Audio follows {{AUDIO_SPEC}} throughout. Submit all timed shots and shared rules as one complete-film request. Separate clips are an accepted fallback only, as described in production.md.
```

## Fidelity checks

- Actual source identity and key scene details are preserved.
- Cue sheet aligns overlays with meaning; text does not anticipate the spoken claim.
- Graphics stay screen-locked despite camera movement, with correct subject occlusion.
- Synthetic camera or voice changes occur only when part of the user’s request.
- Any missing second angle is disclosed as a template departure rather than silently invented.

Compare these checks with the rendered motion, not just the prompt. A missing signature action is a failed shot even if its materials look polished. Repair that shot or report the specific departure; do not relabel a generic result as this preset.
