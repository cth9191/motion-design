# Exploded product — source adaptation guide

Preset ID: `exploded-product` · Template version: 4

**Required first read:** [Exact original prompt](../source-prompts/exploded-product.txt). Start the production prompt from that text and keep its original format. The parameterized material below is a content-mapping and fidelity guide, not replacement wording. One full-film request; optional references; current suitable Seedance preferred. Source route and native settings are provenance.

## Source and deliberate differences

One continuous source take with four macro feature stops and reassembly. The preview is portrait although the linked prompt contains mixed framing language. Library default is 9:16. All source watch specifications are examples, not facts about a new product.

[Published prompt and example](https://higgsfield.ai/@adilinthewildtempo/blogs/claude-fable-5-1-higgsfield-marketing-studio-300-day) — section: The Watch. [Play preview](https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/9eb4a7a5-d79c-459a-8a8d-593e912aa7a3.mp4). Source model label: `marketing_studio_video` (historical metadata, not a model selection instruction). The catalog stores a source-text fingerprint for version tracking, not proof of output fidelity.

## Bind the subject

BRAND; HERO_REFERENCE; IDENTITY_ANCHOR; ORDERED_COMPONENT_STACK; COMPONENT_1..4; VALUE_1..4; LABEL_1..4; ANCHOR_1..4; PALETTE.

Resolve these semantic fields from the campaign and source material. Numbered/ranged fields mean one concrete binding for each use. Replace every `{{...}}` before submission. Include a per-shot exact-copy list, relevant input assets and expected end state. Never submit this file with unresolved variables. Follow [template-adaptation.md](../template-adaptation.md) for the mapping and fidelity check.

## Asset plan

Apply these asset suggestions only when identity accuracy or the selected model requires them. Prompt-only is valid when sufficient; prefer existing assets and add generated references only for a specific need. Distinct shot compositions do not require an image or video job per shot.

Require real component references or verified teardown/CAD information for technical accuracy. Record source and units for every metric; unverified durability claims become neutral feature descriptions. Exact leaders and text are best tracked in finishing. Multiple reference images do not authorize unsupported end-frame roles.

## Default design bindings

Background #000000; graphic type and leaders #FFFFFF. The product carries its real materials; hard cold rims separate it from black. Each callout has a dominant heavy value and a smaller uppercase, widely tracked label. Do not replace pure black with a gray studio floor.

## Audio branch

For the default music/effects version, use product-specific operating sounds, a stretched low accent during separation, fast travel whooshes with quiet macro holds, and distinct mechanical seating sounds during reassembly. A tense rhythmic score can stretch into a drone during slow motion and resolve into a sustained final note. An unrelated product must not inherit a watch ticking sound.

## Parameterized mapping aid — adapt the original text above

```text
{{FORMAT}} | {{BRAND_OR_SUBJECT}} | {{AUDIO_SPEC}}

WORLD, SUBJECT AND DESIGN
Stage {{HERO_REFERENCE}} upright in a pure black void with hard cool rim light. Maintain the product’s proportions, materials and {{IDENTITY_ANCHOR}}. Use the actual {{ORDERED_COMPONENT_STACK}}; no invented technical internals. The graphic system is white geometric sans: a very large bold value above a small widely spaced uppercase label, with a thin leader line. No decorative floor, haze, gradients or glowing typography. If the subject has a legitimate ongoing motion, such as a timepiece second hand, preserve it through the final hold.

CAMERA, EDITING AND MOTION
Make one continuous take with no editorial cuts. Rigid parts separate only along one vertical axis into an evenly spaced exploded stack. The camera then flies between layers, banking quickly with travel blur and slowing to sharp macro holds. At each hold one leader stays attached to its specific physical anchor; the value/label behaves as tracked geometry. Only one callout exists at a time. Reassembly reverses the same axis and component order without dissolving or morphing pieces.

TIMELINE — default 15-second adaptation; retime explicitly for other delivery lengths.

[0.00–1.50s] Phase 1 — complete hero
Open centered on the intact product and make a short fast push toward its most recognizable face. Show a functioning detail if applicable. Keep the silhouette readable before separation begins.

[1.50–3.50s] Phase 2 — slow exploded separation
Stretch time into a slow-motion separation of {{ORDERED_COMPONENT_STACK}}. Preserve rigid shapes, equal ordered gaps and the single axis. The complete list remains present; no components appear by fading.

[3.50–4.50s] Phase 3 — enter the stack
Return to normal action speed and dive into the suspended layers. Use nearby edges for strong parallax, then brake for the first detail.

[4.50–6.00s] Phase 4 — first component
Glide into {{COMPONENT_1}} until its useful detail fills the frame. Pin a leader to {{ANCHOR_1}} and show {{VALUE_1}} above {{LABEL_1}}. Keep settled text sharp and anchored. Remove it before the next callout.

[6.00–7.50s] Phase 5 — second component
Whip onward through the existing stack to {{COMPONENT_2}}, then decelerate into a macro hold. Track {{VALUE_2}} and {{LABEL_2}} to {{ANCHOR_2}}. Let the actual component behavior explain the claim. Exit the callout before leaving.

[7.50–9.00s] Phase 6 — third component
Continue without a cut to {{COMPONENT_3}}. Reveal its material or mechanism in extreme close-up, with {{VALUE_3}} and {{LABEL_3}} attached to {{ANCHOR_3}}. Travel may blur; the reading hold must not.

[9.00–10.00s] Phase 7 — fourth component
Bank to {{COMPONENT_4}} and settle quickly enough to read {{VALUE_4}} over {{LABEL_4}}, anchored at {{ANCHOR_4}}. Remove the lockup by 10 seconds. Use a short nonnumeric feature term when no supported metric exists.

[10.00–12.50s] Phase 8 — reassembly
Swing to a side view of the whole stack. Rejoin every component along the original axis in reverse separation order. Each part seats crisply, with motion blur only in travel. Close the outer housing last. Arc toward the frontal hero view as the complete product resumes its normal state.

[12.50–15.00s] Phase 9 — title and hero hold
Lock the camera completely. Resolve {{BRAND}} from soft blur into sharp white lettering below the product. Hold that composition on pure black. The camera and title stay still; legitimate product activity can continue. No appended fade or new scene.

COPY AND REFERENCES
{{EXACT_COPY_BY_SHOT}}. No other readable text. Use {{ASSET_BINDINGS}} with their declared identity/style/start/end/overlay roles. Preserve real product identity, supported claims and specified component geometry.

DELIVERY
{{DELIVERY_AND_FINISHING_PLAN}}. Audio follows {{AUDIO_SPEC}} throughout. Submit all timed shots and shared rules as one complete-film request. Separate clips are an accepted fallback only, as described in production.md.
```

## Fidelity checks

- One unbroken camera route connects separation, all four macro stops and reassembly.
- Rigid parts retain their original number, order and axis.
- Each leader follows its own component; only one metric is visible.
- Values and labels are product-specific and sourced, with no inherited watch claims.

Compare these checks with the rendered motion, not just the prompt. A missing signature action is a failed shot even if its materials look polished. Repair that shot or report the specific departure; do not relabel a generic result as this preset.
