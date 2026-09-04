# Kinetic typography — source adaptation guide

Preset ID: `kinetic-typography` · Template version: 4

**Required first read:** [Exact original prompt](../source-prompts/kinetic-typography.txt). Start the production prompt from that text and keep its original format. The parameterized material below is a content-mapping and fidelity guide, not replacement wording. One full-film request; optional references; current suitable Seedance preferred. Source route and native settings are provenance.

## Source and deliberate differences

The published prompt specifies a 10-second continuous flat composition with a final hold, despite being described as a loop. Default adaptation stretches its five phases to 15 seconds. It is not a seamless loop unless a reset is explicitly designed; do not claim that a final headline matches the sparse opening.

[Published prompt and example](https://higgsfield.ai/@adilinthewildtempo/blogs/claude-fable-5-1-higgsfield-marketing-studio-300-day) — section: Recreate Any Video from a Reference. [Play preview](https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/75a6c434-a18a-4484-81b0-387308743279.mp4). Source model label: `minimax_h3` (historical metadata, not a model selection instruction). The catalog stores a source-text fingerprint for version tracking, not proof of output fidelity.

## Bind the subject

BRAND; OPENING_LINES (two short lines); PERIPHERAL_LABELS (up to six supported capabilities); THUMBNAILS (six relevant outputs or assets); CHIPS (up to three truthful short labels); BRIDGE_ICON; BRIDGE_LINE; BENEFIT_LINE; REPLACEMENT_LINE; SCROLL_ITEMS; FINAL_LINE; PALETTE.

Resolve these semantic fields from the campaign and source material. Numbered/ranged fields mean one concrete binding for each use. Replace every `{{...}}` before submission. Include a per-shot exact-copy list, relevant input assets and expected end state. Never submit this file with unresolved variables. Follow [template-adaptation.md](../template-adaptation.md) for the mapping and fidelity check.

## Asset plan

Apply these asset suggestions only when identity accuracy or the selected model requires them. Prompt-only is valid when sufficient; prefer existing assets and add generated references only for a specific need. Distinct shot compositions do not require an image or video job per shot.

No hero image is required. Source or generate six meaningful thumbnail images if the card phase uses photography; software cards should show the product’s actual work, not unrelated action sports. Prefer deterministic compositing for long exact-copy lists. The 10-second source timing is 0–2, 2–4, 4–5.5, 5.5–7.5, 7.5–10; the 15-second template uses a 1.5 timing multiplier.

## Default design bindings

Source role values: neutral base #EAEAE3; upper-left pink/lilac haze #F3DDEB; lower-right pale lime haze #E2E7B4; main ink #1A1A18; inactive type #C2C3B4. Brief landing accents use #8C0F45, #C87D3E, #E33966 and #ADC50D. Cards have rounded corners and small two-degree tilts. Source word entries rise about 20 pixels at its composition scale; scale that distance with the output size.

## Audio branch

The source prompt is silent. For a new launch/motion campaign, replace its silence clauses with instrumental music and synchronized effects and record that departure. Preserve an explicit silent request. Do not add narration by default.

## Parameterized mapping aid — adapt the original text above

```text
{{FORMAT}} | {{BRAND_OR_SUBJECT}} | {{AUDIO_SPEC}}

WORLD, SUBJECT AND DESIGN
Build an entirely flat graphic film with a locked frame. Start with a very light neutral base and faint pink/lilac and lime gradient regions, plus fine even grain; adapt those hues through {{PALETTE}}. Use one heavy geometric sans with close tracking, centered composition and dark ink. A small family of four punctuation/spark/arrow marks occupies the initially sparse center. No dimensional camera, lens blur, extruded letters, bevels or object shadows. Thumbnails depict the actual subject’s outputs or relevant imagery.

CAMERA, EDITING AND MOTION
Entrances decelerate cleanly without elastic rebound; exits accelerate away. Only fast-moving layers receive directional blur. Keep the background stationary and sharp. Headline words briefly flash palette accents on landing, returning to ink within about four native frames. Allow only the specified slight card rotation. Use graphic replacement and scale changes rather than dissolves. The inactive first bridge line may change to a lighter ink value as specified.

TIMELINE — default 15-second adaptation; retime explicitly for other delivery lengths.

[0.00–3.00s] Phase 1 — headline and orbiting labels
Build {{OPENING_LINES}} word by word. Each word rises a small distance into place and stops. Main type is about seven percent of frame height. Place up to six {{PERIPHERAL_LABELS}} around the open margins in small gray type, about 2.5 percent of frame height. These labels settle and stay still; keep the two-line headline readable at the center.

[3.00–6.00s] Phase 2 — six image cards
Bring six rounded 16:9 {{THUMBNAILS}} in from outside the frame: two upper left, two upper right, one lower left, one lower right, with shallow overlap and roughly two-degree tilts. Begin each in a harsh two-color treatment and resolve all six to full color around 4.35 seconds. Add up to three small dark pills containing {{CHIPS}} in the accent color. Protect the existing center headline throughout.

[6.00–8.25s] Phase 3 — collapse and bridge
Move the six cards and their pills inward together, collect the labels and headline into the same small stack, then shrink the stack to a point. Briefly expose the clear gradient. Introduce {{BRIDGE_ICON}} at the exact center, approximately thirty percent of frame height. Use a ring with rotating hands only when time is the message; a different simple icon must support an equally clear large-to-inline transformation.

[8.25–11.25s] Phase 4 — inline icon and replacement
Reduce the bridge icon to inline size as {{BRIDGE_LINE}} slides in and locks beside it. Add {{BENEFIT_LINE}} below. Around 9.9 seconds replace that lower line word by word in the same position with {{REPLACEMENT_LINE}}. Lighten the upper line and its icon without moving them. Keep the new benefit in dark ink.

[11.25–15.00s] Phase 5 — scrolling list and conclusion
Extend the typography into a centered vertical list of {{SCROLL_ITEMS}}. Scroll upward; only the item crossing the center reading band is dark, with the rest light gray. Keep two inward-pointing arrows fixed at the sides of that band. Decelerate until {{FINAL_LINE}} is centered between them. Add one small sparkle below. Hold completely still for at least the final 0.5 seconds. No appended CTA card or automatic loop reset.

COPY AND REFERENCES
{{EXACT_COPY_BY_SHOT}}. No other readable text. Use {{ASSET_BINDINGS}} with their declared identity/style/start/end/overlay roles. Preserve real product identity, supported claims and specified component geometry.

DELIVERY
{{DELIVERY_AND_FINISHING_PLAN}}. Audio follows {{AUDIO_SPEC}} throughout. Submit all timed shots and shared rules as one complete-film request. Separate clips are an accepted fallback only, as described in production.md.
```

## Fidelity checks

- Five graphic phases occur inside one fixed frame; no simulated camera drift.
- Six cards never obscure the headline and transform together before the bridge.
- Scrolling emphasis remains aligned with stationary arrows.
- No inherited free, unlimited, price or availability claim survives without support.
- Final hold is not mislabeled as a seamless loop.

Compare these checks with the rendered motion, not just the prompt. A missing signature action is a failed shot even if its materials look polished. Repair that shot or report the specific departure; do not relabel a generic result as this preset.
