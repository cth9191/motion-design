# Glass UI launch — source adaptation guide

Preset ID: `glass-ui-launch` · Template version: 4

**Required first read:** [Exact original prompt](../source-prompts/glass-ui-launch.txt). Start the production prompt from that text and keep its original format. The parameterized material below is a content-mapping and fidelity guide, not replacement wording. One full-film request; optional references; current suitable Seedance preferred. Source route and native settings are provenance.

## Source and deliberate differences

Seven source shots, source cut times retained at 15 seconds. The dark passage, two macro inserts, and final full-frame freeze are essential. The published example depicts phone sales; replace those semantics with the new product workflow. Source music and effects remain the default; no narration. Explicit campaign audio choices override this.

[Published prompt and example](https://higgsfield.ai/@adilinthewildtempo/blogs/claude-fable-5-1-higgsfield-marketing-studio-300-day) — section: Launch Video from a Website Link. [Play preview](https://d2ol7oe51mr4n9.cloudfront.net/user_3DiY2MbHSIvzM3FG2DOgC6Cf2MM/fee13558-1de4-46cb-80c6-443935cb8257.mp4). Source model label: `marketing_studio_video` (historical metadata, not a model selection instruction). The catalog stores a source-text fingerprint for version tracking, not proof of output fidelity.

## Bind the subject

BRAND; PROBLEM_QUEUE (a recognizable unresolved task); SELECTED_ITEM; ACTIVE_OBJECT and RESPONSE_OBJECT (a meaningful input/output pair); ACTIVITY_DETAIL; RESPONSE_ACTION; TRACE_STRIP (a real process trace); RESULT_MODULE (a real deliverable plus supported measures); HEADLINE_1, HEADLINE_2, HEADLINE_4, HEADLINE_6; UI_LABELS_BY_SHOT; BRAND_LINE; CTA; PALETTE.

Resolve these semantic fields from the campaign and source material. Numbered/ranged fields mean one concrete binding for each use. Replace every `{{...}}` before submission. Include a per-shot exact-copy list, relevant input assets and expected end state. Never submit this file with unresolved variables. Follow [template-adaptation.md](../template-adaptation.md) for the mapping and fidelity check.

## Asset plan

Apply these asset suggestions only when identity accuracy or the selected model requires them. Prompt-only is valid when sufficient; prefer existing assets and add generated references only for a specific need. Distinct shot compositions do not require an image or video job per shot.

Collect real screenshots, output examples, diagrams or demo frames from the product source. Map the problem, action, response, trace and result before designing glass containers. A style reference can establish material only. Create distinct wide and macro scene references where the selected model needs them; do not force all seven shots to animate one preassembled three-card image. Exact screenshots, text and data can be tracked/composited during finishing.

## Default design bindings

The source names cool white, cobalt refraction, silver rims, pearl interiors and smoked dark glass without exact hex codes. Bind concrete campaign hex values while retaining those light/dark and material roles; do not describe invented hex values as source specifications.

## Audio branch

By default, use restrained electronic rhythm around 120 BPM, compact edit impacts, glass-edge travel sounds, two distinct action/response accents and a fine trace-scan sound. Reduce percussion at the brand reveal; end the beat at 13.8 seconds with a short resolving tone. No speech unless separately requested. Bind AUDIO_SPEC to silence only for an explicit silent campaign.

## Parameterized mapping aid — adapt the original text above

```text
{{FORMAT}} | {{BRAND_OR_SUBJECT}} | {{AUDIO_SPEC}}

WORLD, SUBJECT AND DESIGN
Create a 15-second edited 3D interface film for {{BRAND}}. Its story is {{PROBLEM_QUEUE}} → {{ACTIVE_OBJECT}} → {{RESPONSE_ACTION}} → {{RESULT_MODULE}}. Use rigid transparent panels with visible depth, pale interiors, cool blue edge refraction and narrow silver highlights. Use the resolved {{PALETTE}} while preserving a bright studio for shots 1–2 and 5–7 and a dark studio for shots 3–4. In the dark passage use rounded smoked glass and a pale rear object. Panels must contain the mapped product inputs and outputs. Keep consistent bevels, material response and object identity across different compositions. This is seven camera shots in a shared design world.

CAMERA, EDITING AND MOTION
Large lateral moves and arcs expose thickness and occlusion, then brake into clear landings. Blur belongs to traveling objects or camera travel, not settled type. Headlines are flat overlays whose positions are designed per shot. There is no universal empty left column. Use the two short inserts without main headlines to create scale and rhythm. Maintain one causal activation signal; distinguish an action from the response it causes.

TIMELINE — default 15-second adaptation; retime explicitly for other delivery lengths.

[0.00–2.25s] Shot 1 — select inside the problem
Begin among several depth-separated strips representing {{PROBLEM_QUEUE}}, extremely close to a foreground bevel. Truck quickly to the right over a large distance, passing through gaps. Show actual task structure in the strips, not random app chrome. A restrained edge pulse singles out {{SELECTED_ITEM}}. Finish with that selection visibly distinct, {{HEADLINE_1}} and {{BRAND}} readable, and only this shot’s approved embedded labels.

[2.25–5.00s] Shot 2 — activate the workflow
Hard match-cut the selected strip to a wide bright composition containing {{ACTIVE_OBJECT}} and {{RESPONSE_OBJECT}} at separate depths, connected by a narrow glass ribbon. Arc right roughly 30 degrees, with a fast broad move that settles. A pulse moves from the rear object along the ribbon and activates the front object. Show {{HEADLINE_2}} plus the shot’s short status label. Keep the headline clear of both travel paths.

[5.00–6.00s] Shot 3 — dark activity macro
Cut to an extreme close view of {{ACTIVITY_DETAIL}} inside the dark rounded glass version of the active object. Use a short fast push. One specific state change or pulse shows the product acting. The reflection travels through the smoked glass and settles. No main headline and no newly introduced copy. This is a one-second action insert, not another wide dashboard.

[6.00–8.50s] Shot 4 — reveal the response
Cut to a different three-quarter angle in the same dark world. Pull back rapidly from close to medium to wide, revealing the active object at rest and the rear response object performing {{RESPONSE_ACTION}}. Make the sequence legible as action then response. Preserve rounded rims and clean separation. Land on {{HEADLINE_4}}, {{BRAND}} and the assigned status label.

[8.50–9.50s] Shot 5 — process trace macro
Use a hard graphic match from the response pattern to {{TRACE_STRIP}} in extreme close-up. Return to bright blue-edged glass. Track right quickly along the trace while a narrow scan crosses it. Show only approved trace labels, with no main headline. The trace must belong to the workflow just shown; an arbitrary waveform is appropriate only for an audio product.

[9.50–12.50s] Shot 6 — outcome and evidence
Cut wide as the scan reaches {{RESULT_MODULE}}. Retain the trace beside the actual output and a compact evidence panel. Arc left with medium travel, then settle toward a frontal reading angle. If three comparison bars are appropriate, fix their heights to verified values and accent them sequentially with light; illumination changes, data does not. Otherwise use three non-quantitative output/status components. Show {{HEADLINE_6}}, {{BRAND}} and approved result labels. Let the assembled outcome read clearly.

[12.50–15.00s] Shot 7 — centered brand resolution
Cut to a centered {{BRAND}} lockup, {{BRAND_LINE}} underneath and {{CTA}} with its small directional mark. Use a bright studio and a thin ribbon in the foreground. Camera is static. One reflection slides along the ribbon, then all image motion and lighting stop by 13.8 seconds. Hold the entire composition unchanged from 13.8 to 15.0. End on the held image with no fade or added scene.

COPY AND REFERENCES
{{EXACT_COPY_BY_SHOT}}. No other readable text. Use {{ASSET_BINDINGS}} with their declared identity/style/start/end/overlay roles. Preserve real product identity, supported claims and specified component geometry.

DELIVERY
{{DELIVERY_AND_FINISHING_PLAN}}. Audio follows {{AUDIO_SPEC}} throughout. Submit all timed shots and shared rules as one complete-film request. Separate clips are an accepted fallback only, as described in production.md.
```

## Fidelity checks

- Seven shots with cuts at 2.25, 5, 6, 8.5, 9.5 and 12.5 seconds at the default duration.
- Both a dark macro and a dark pullback survive the adaptation.
- The two macros have no main headline, and their graphic match uses the same workflow evidence.
- Without headlines, the action and result still belong to the selected product.
- Evidence panel values, labels, units and bar geometry agree; ending is fully frozen at 13.8 seconds.

Compare these checks with the rendered motion, not just the prompt. A missing signature action is a failed shot even if its materials look polished. Repair that shot or report the specific departure; do not relabel a generic result as this preset.
