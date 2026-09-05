# Hybrid 2D + 3D — source adaptation guide

Preset ID: `hybrid-2d-3d` · Template version: 4

**Required first read:** [Exact original prompt](../source-prompts/hybrid-2d-3d.txt). Start the production prompt from that text and keep its original format. The parameterized material below is a content-mapping and fidelity guide, not replacement wording. One full-film request; optional references; current suitable Seedance preferred. Source route and native settings are provenance.

## Source and deliberate differences

Eight source phases mix cinematic 3D objects with consistently flat 2D characters. Preserve the physical interactions and rendering separation. Academic objects are semantic slots, not mandatory imagery for unrelated products. The ending pops away 2D first and fades 3D last.

[Published prompt and example](https://higgsfield.ai/@adilinthewildtempo/blogs/claude-fable-5-1-higgsfield-marketing-studio-300-day) — section: 5. 2D Explainer Motion ($300 - $800 to start). [Play preview](https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/4d56be98-74fb-4616-9269-db37ea998171.mp4). Source model label: `marketing_studio_video` (historical metadata, not a model selection instruction). The catalog stores a source-text fingerprint for version tracking, not proof of output fidelity.

## Bind the subject

BRAND; HERO_STRUCTURE; IDENTITY_ANCHOR; STEP_OBJECTS; ORBIT_OBJECT; DISPLAY_OBJECT; REWARD_OBJECT; CHARACTER_REFERENCE; HEADLINES_BY_PHASE; FEATURE_CHIPS; BRAND_LINE; CTA; PALETTE.

Resolve these semantic fields from the campaign and source material. Numbered/ranged fields mean one concrete binding for each use. Replace every `{{...}}` before submission. Include a per-shot exact-copy list, relevant input assets and expected end state. Never submit this file with unresolved variables. Follow [template-adaptation.md](../template-adaptation.md) for the mapping and fidelity check.

## Asset plan

Apply these asset suggestions only when identity accuracy or the selected model requires them. Prompt-only is valid when sufficient; prefer existing assets and add generated references only for a specific need. Distinct shot compositions do not require an image or video job per shot.

Create a representative frame containing both a 3D prop and the flat character to establish the layer rule. Derive distinct scene references from the same character and material family. Select props that express the new organization’s actual activity; do not leave a graduation cap or admissions copy in an unrelated campaign.

## Default design bindings

Accent #D1EF17, ink #14151B, violet #6C2BFF, coral #FF5A4E, off-white #F7F4EC and flat skin fill #E8A87C. Match the accent between flat and lit layers. Reference type staggers about 40 ms per word and draws its accent marker over 200 ms; doodles use short drawn-on frame steps.

## Audio branch

The source prompt is silent. For a new launch/motion campaign, replace its silence clauses with instrumental music and synchronized effects and record that departure. Preserve an explicit silent request. Do not add narration by default.

## Parameterized mapping aid — adapt the original text above

```text
{{FORMAT}} | {{BRAND_OR_SUBJECT}} | {{AUDIO_SPEC}}

WORLD, SUBJECT AND DESIGN
Create a hybrid launch where physical 3D objects carry a graphic 2D cast. Use {{HERO_STRUCTURE}}, {{STEP_OBJECTS}}, {{ORBIT_OBJECT}}, {{DISPLAY_OBJECT}} and {{REWARD_OBJECT}} as real representations of the organization’s story. Give 3D materials proper reflection, mass and soft contact shadows under one large upper-left key. Characters, arrows and chips use flat solid colors, no shading and no cast shadows. Their flat image may reflect in 3D glass without acquiring shaded volume. Keep {{CHARACTER_REFERENCE}} and {{IDENTITY_ANCHOR}} consistent. Alternate dark ink, warm off-white and one strong accent world through {{PALETTE}}.

CAMERA, EDITING AND MOTION
3D moves use cinematic rises, arcs and brief slow motion; 2D uses anticipation, up to twenty percent squash/stretch, fast drawn smears and settled poses. The contact between layers is the signature: a character landing tilts a physical prop, a ramp carries the character, and a physical reward settles against them. Headlines enter word by word with a short stagger and an accent swipe behind one phrase. Use hard cuts and matches on action or color. Never shade the character to make the contact easier.

TIMELINE — default 15-second adaptation; retime explicitly for other delivery lengths.

[0.00–1.80s] Phase 1 — structure and graphic sparks
Raise {{HERO_STRUCTURE}} from below the dark frame. Activate {{IDENTITY_ANCHOR}} in an ordered progression. Pop flat stars or scribble accents around those activations. Land the first approved headline with one accent swipe. Keep 3D rise and flat punctuation visually distinct.

[1.80–3.60s] Phase 2 — people emerge
Orbit about thirty degrees. Bring small flat characters out of a meaningful opening in the structure, carrying subject-relevant graphic props. Continue them along a clear lower-frame path. Draw an arrow back to the origin and show a short supported feature chip.

[3.60–5.40s] Phase 3 — climb with physical response
Cut to the light world. Arrange three {{STEP_OBJECTS}} as climbable forms. The recurring character runs in, anticipates, and hops between them. Each landing tilts the physical object around two degrees, then settles. On the highest step plant a flat accent-colored marker. Show the progress headline.

[5.40–7.20s] Phase 4 — color match and counter-orbit
Let the marker’s accent color motivate the cut to an accent world. Float {{ORBIT_OBJECT}} at center with physically plausible motion. Orbit flat relevant doodles around it in the opposite direction. Snap three brief {{FEATURE_CHIPS}} beneath it with a stagger; claims must be supported.

[7.20–9.00s] Phase 5 — activity around the display
Toss the central object upward and replace its departing silhouette with a simple flat mark. Switch back to the light world. Assemble the graphic cast around {{DISPLAY_OBJECT}}, a dimensional surface showing a simple flat example of the real activity. Stagger character arrivals and then let the scene read.

[9.00–10.80s] Phase 6 — display becomes a ramp
Have one character rise and approach the display as it tips into a traversable ramp. The character walks up its physical surface into the dark world. Their reflection may appear in the ramp, but their body remains flat and unlit. Place the transformation headline above the path.

[10.80–12.60s] Phase 7 — tangible reward
Lower {{REWARD_OBJECT}} toward the character with one measured rotation and a real material highlight. Let it settle in contact with the flat character or a support they occupy. Add flat geometric confetti. Use a short factual milestone chip only if appropriate.

[12.60–15.00s] Phase 8 — hybrid lockup
Return the small {{HERO_STRUCTURE}} at the bottom of a dark frame and place the recurring character on it, carrying the result. Build {{BRAND}}, {{BRAND_LINE}} and {{CTA}} by 13.5 seconds. Hold for 0.8 seconds through 14.3. Pop the 2D pieces away through 14.5, fade the 3D structure through 14.9, and leave the final 0.1 seconds empty. Preserve that layer exit order.

COPY AND REFERENCES
{{EXACT_COPY_BY_SHOT}}. No other readable text. Use {{ASSET_BINDINGS}} with their declared identity/style/start/end/overlay roles. Preserve real product identity, supported claims and specified component geometry.

DELIVERY
{{DELIVERY_AND_FINISHING_PLAN}}. Audio follows {{AUDIO_SPEC}} throughout. Submit all timed shots and shared rules as one complete-film request. Separate clips are an accepted fallback only, as described in production.md.
```

## Fidelity checks

- At least the climb, ramp and reward show real cross-layer contact.
- 2D remains flat with no shading or cast shadow throughout.
- The same character connects all phases and source university claims are replaced.
- The final layer-specific exit fits the requested duration.

Compare these checks with the rendered motion, not just the prompt. A missing signature action is a failed shot even if its materials look polished. Repair that shot or report the specific departure; do not relabel a generic result as this preset.
