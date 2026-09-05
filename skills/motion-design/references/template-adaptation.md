# Adapt the full template to the product

Read after selecting a preset and before writing its final prompt or generating images. The archived original at `source.prompt_path` is the production starting text; `templates/<id>.md` is its adaptation guide. Read both in full. Its entire shot sequence, camera behavior, transitions, material rules and ending matter. The gallery description and preset entrypoint are navigation aids, not substitute prompts.

## What stays and what changes

Keep the template's film structure: edited shots versus continuous take, shot order, major scale changes, camera direction/amplitude, light/dark progression, material behavior, transition causes, reading holds and ending. House preferences fill gaps; they do not flatten a selected example into the house style. Seven shots is a Glass UI requirement, not a requirement for every preset.

Replace the product, story, copy, asset content and factual claims with the user's subject. Brand colors can replace hue roles while retaining useful contrast. Recompose for an explicit aspect ratio, retime for an explicit duration, and preserve the user's audio choice. For new launch/motion campaigns, use music and synchronized effects by default, without narration. Replacing source silence is a recorded adaptation; explicit project silence still wins.

Record a meaningful departure with its reason: user request, source ambiguity, a factual correction, a poor semantic fit, or a verified model limitation. Do not silently drop a signature shot because one attractive starting image is easier to animate. A change that removes the defining mechanic should be called a custom adaptation, with the difference identified.

The package stores the exact captured original prompts under `references/source-prompts/`, with hashes and provenance in the catalog. Keep these originals unchanged. The separate parameterized guides aid content mapping. Build the final prompt by editing a copy of the original, retaining its format and unchanged motion language rather than paraphrasing the whole prompt. Archive any genuine source discrepancy and record your correction. Matching a prompt does not guarantee identical output.

## Map content before designing its container

For a real launch, inspect the product's authoritative page and supplied media. Verify the name, release context, capabilities, examples and any numbers used. Collect usable source assets: actual outputs, screenshots, product images, demonstration frames, diagrams or accurate component views. A URL is a lead to inspect, not an asset already obtained.

Build one compact mapping alongside the brief:

| Template shot/phase | Product meaning or claim | Evidence | Visual asset or action | Asset state | Copy | Preserved mechanics / departure |
|---|---|---|---|---|---|---|
| ID and interval from template | What viewers learn | Source URL + section, supplied fact, or creative premise | The specific input, action or output shown | acquired / to create / missing essential | Exact strings or none | Camera, transition and contrast retained; justified changes |

Every product shot needs a defensible relationship to its content. A generic chip, house, waveform, code screen or glass panel is not evidence of a capability simply because the headline names one. A generated depiction may illustrate a supported idea, but label it as an illustration in the asset record and do not present it as a genuine screenshot or test result. Reuse one real workflow across multiple shots when that makes the causal sequence clearer than unrelated feature cards.

For a benchmark, capture the benchmark name/version, compared systems, values, units and relevant conditions. In 15 seconds, show a small number of claims with adequate reading time. Use brief on-screen qualifications when necessary and preserve fuller sources alongside the deliverable. Set numeric chart geometry deterministically when feasible. If three equal-looking decorative bars would imply false data, use honest data or non-quantitative result components.

Use this meaning test before assets and again during review: **with the headline hidden, what in the shot connects it to this particular product or claim?** If the answer is only the color or logo, strengthen the mapped action or asset. Some macro/style inserts need no new claim, but they must remain a recognizable detail of the adjacent product action.

## Compile a complete production brief

1. Read the selected archived original and its adaptation guide and known source differences. Use existing campaign context to resolve fields; ask only for missing essentials.
2. Bind the shot map, product identity, palette roles, exact copy and audio. Resolve every placeholder, including macro contents and embedded UI labels. Select real assets before generating decorative containers.
3. Carry the full template action/camera/transition detail into the master brief. Preserve its timeline, or write an explicit retiming map. Do not replace the timeline with a generic problem/benefit/CTA outline. When compressing a reference duration, scale and round events to delivery frames, then check that reading holds and continuous actions remain feasible. Do not leave source timestamps inside a retimed prompt.
4. Define each asset's role. A material/style frame establishes appearance; it is not automatically the start frame of all shots. Different shots need different compositions in the prompt, but not necessarily different reference images. Start prompt-only or reuse a minimal set of identity references; add a storyboard only for a concrete need and when supported. Keep a canonical identity across those compositions.
5. Follow [creative-brief.md](creative-brief.md), preserving the original prompt format rather than imposing a new skeleton. Save the shot map and a small list of deliberate departures. This is an internal completeness check, not a new user approval gate. For production, proceed through [production.md](production.md).

Keep the full resolved prompt available. Submit all shot instructions and shared rules in one complete-film request by default. Segmentation requires a verified constraint and an explained, accepted change to the method. Do not summarize away the distinctive instructions to fit a model's prompt limit. Select a capable route first. Only an accepted segmentation fallback may divide at actual editorial cuts. Do not split a continuous reference move without identifying the departure.

## Check the result against two standards

**Template fidelity:** Compare actual motion with the selected template's fidelity list: shot count/order, scale changes, camera trajectories, material/light changes, causal transitions and ending. Inspect moments on both sides of cuts and playback for the moving actions. Attractive materials or a technically valid export do not establish this.

**Product relevance:** Check the actual assets, actions, labels and evidence against the shot map. Verify that panels contain meaningful product content, charts encode the right data, and source-demo names/claims have been replaced. Generic scenery under exact headline overlays still fails if the intended product demonstration is absent.

Record each failed requirement, the affected shot and its remedy. Correct the full prompt or use a supported targeted edit within the authorized retry scope; do not automatically create replacement shot clips. If the available model or source assets cannot achieve it, report the precise departure instead of presenting the result as an equally faithful recreation. Finish technical checks only after content and motion are assessed; finishing cannot restore an absent camera move or missing product action.
