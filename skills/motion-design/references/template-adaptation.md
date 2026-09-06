# Adapt the full template to the product

Read after selecting a preset and before writing its final prompt or generating images. The archived original at `source.prompt_path` is the production starting text; `templates/<id>.md` is its adaptation guide. Read both in full. Its entire shot sequence, camera behavior, transitions, material rules and ending matter. The gallery description and preset entrypoint are navigation aids, not substitute prompts.

## What stays and what changes

Use the source's visual character and effective motion as the foundation. Its sequence, scene count and durations describe how that source tells its story; keep them where they fit and rebuild them where this subject needs different actions or emphasis. Preserve useful specificity in scale changes, camera behavior, materials, transition causes and typography. Close recreation is appropriate when explicitly requested; otherwise the communication goal governs the sequence. Do not flatten the source into generic house styling.

Replace the product, story, copy, asset content and factual claims with the user's subject. Brand colors can replace hue roles while retaining useful contrast. Recompose for an explicit aspect ratio, retime for an explicit duration, and preserve the user's audio choice. For new launch/motion campaigns, use music and synchronized effects by default, without narration. Replacing source silence is a recorded adaptation; explicit project silence still wins.

Record a meaningful departure with its reason: user request, source ambiguity, a factual correction, a poor semantic fit, or a verified model limitation. Do not silently drop a signature shot because one attractive starting image is easier to animate. A change that removes the defining mechanic should be called a custom adaptation, with the difference identified.

The package stores the exact captured original prompts under `references/source-prompts/`, with hashes and provenance in the catalog. Keep these originals unchanged. The separate parameterized guides aid content mapping. Build from a copy of the original, retaining useful wording and detail while rewriting story-dependent sections. Keep its format where it helps; section order is not a constraint on a clearer story. Archive any genuine source discrepancy and record your correction. Matching a prompt does not guarantee identical output.

## Map content before designing its container

For a real launch, inspect the product's authoritative page and supplied media. Verify the name, release context, capabilities, examples and any numbers used. Collect usable source assets: actual outputs, screenshots, product images, demonstration frames, diagrams or accurate component views. A URL is a lead to inspect, not an asset already obtained.

State the viewer takeaway and a short sequence first. For content that needs evidence or asset tracking, this compact mapping can help; do not require a separate table for a simple brief:

| Template shot/phase | Product meaning or claim | Evidence | Visual asset or action | Asset state | Copy | Preserved mechanics / departure |
|---|---|---|---|---|---|---|
| ID and interval from template | What viewers learn | Source URL + section, supplied fact, or creative premise | The specific input, action or output shown | acquired / to create / missing essential | Exact strings or none | Camera, transition and contrast retained; justified changes |

Every product shot needs a defensible relationship to its content. A generic chip, house, waveform, code screen or glass panel is not evidence of a capability simply because the headline names one. A generated depiction may illustrate a supported idea, but label it as an illustration in the asset record and do not present it as a genuine screenshot or test result. Reuse one real workflow across multiple shots when that makes the causal sequence clearer than unrelated feature cards.

For a benchmark, capture the benchmark name/version, compared systems, values, units and relevant conditions. In 15 seconds, show a small number of claims with adequate reading time. Use brief on-screen qualifications when necessary and preserve fuller sources alongside the deliverable. Set numeric chart geometry deterministically when feasible. If three equal-looking decorative bars would imply false data, use honest data or non-quantitative result components.

Use this meaning test before assets and again during review: **with the headline hidden, what in the shot connects it to this particular product or claim?** If the answer is only the color or logo, strengthen the mapped action or asset. Some macro/style inserts need no new claim, but they must remain a recognizable detail of the adjacent product action.

## Compile a complete production brief

1. Read the selected archived original and its adaptation guide and known source differences. Use existing campaign context to resolve fields; ask only for missing essentials.
2. Bind the shot map, product identity, palette roles, exact copy and audio. Resolve every placeholder, including macro contents and embedded UI labels. Select real assets before generating decorative containers.
3. Write a concrete timeline for the new sequence, retaining useful source action/camera/transition detail. Give each beat time for its action and understanding, then move on; do not fill duration by proportionally stretching holds. Explain meaningful structural changes briefly. When retaining the same sequence at a different duration, record the retiming. Remove obsolete source timestamps and keep actions and reading holds feasible.
4. Define each asset's role. A material/style frame establishes appearance; it is not automatically the start frame of all shots. Different shots need different compositions in the prompt, but not necessarily different reference images. Start prompt-only or reuse a minimal set of identity references; add a storyboard only for a concrete need and when supported. Keep a canonical identity across those compositions.
5. Follow [creative-brief.md](creative-brief.md). Save the short sequence or shot map and a small list of deliberate departures. This is an internal completeness check, not a new user approval gate. For production, proceed through [production.md](production.md).

Keep the full resolved prompt available. Submit all shot instructions and shared rules in one complete-film request by default. Segmentation requires a verified constraint and an explained, accepted change to the method. Do not summarize away the distinctive instructions to fit a model's prompt limit. Select a capable route first. Only an accepted segmentation fallback may divide at actual editorial cuts. Do not split a continuous reference move without identifying the departure.

## Review the actual film

**Communication:** Can a viewer follow the intended takeaway from the actual actions and sequence? For an explanation, check that causes and results are shown, not merely named. For a reveal or brand film, check that the intended impression builds toward a meaningful ending. Readable text alone is insufficient.

**Motion and source character:** Compare the actual film with the adapted brief and the source techniques intentionally retained. Inspect both sides of transitions: does the outgoing action lead clearly into the next composition, with enough reading time and no unnecessary lingering? Source shot count/order is binding only when retained in the brief or explicitly requested. Attractive materials or a valid export do not establish clean motion.

**Product relevance:** Check the actual assets, actions, labels and evidence against the shot map. Verify that panels contain meaningful product content, charts encode the right data, and source-demo names/claims have been replaced. Generic scenery under exact headline overlays still fails if the intended product demonstration is absent.

Record each failed requirement, the affected shot and its remedy. Correct the full prompt or use a supported targeted edit within the authorized retry scope; do not automatically create replacement shot clips. If the available model or source assets cannot achieve it, report the precise departure instead of presenting the result as an equally faithful recreation. Finish technical checks only after content and motion are assessed; finishing cannot restore an absent camera move or missing product action.
