# Browse a look, supply the content, create the film

## Show options

Read [preset-index.md](preset-index.md), not every recipe. Start with the user's outcome and recommend up to three matching examples. If the outcome is unknown, show the gallery and describe the main categories in one sentence each. Never substitute invented previews for the actual source examples.

Open `assets/gallery.html` relative to this skill. It is a self-contained local page with embedded catalog data and remote public preview videos; no build step or account is required to browse it. If the app cannot render local HTML, serve the skill directory using a temporary loopback-only HTTP server and open `/assets/gallery.html` with the available browser. A normal link or inline playable preview is a fallback; keep names and IDs visible. Do not publish the gallery to an external host unless asked.

The gallery lets users filter looks, play muted previews, choose a preset, provide an optional campaign brief, and copy a request into chat. It does not submit video jobs, send messages, or automatically transmit form text. Be explicit about the copy-and-paste handoff when using the gallery. Users can instead name the preset directly in the conversation. Do not claim to have received a selection that exists only in an unobserved browser tab or clipboard.

## Show the selected look and request the minimum

Read the selected file under `presets/`, the archived original in `source.prompt_path`, and its linked adaptation guide under `templates/`. Show or link its source preview and summarize its defining motion. Mention a material adaptation, such as a silent version or different format, once. Source clips illustrate a look; they are not deterministic promises or proof of production settings. The gallery shows the exact original prompt and a separately labeled adaptation guide.

Reuse supplied URLs, copy, brand assets, and preferences. For an ordinary new campaign, one useful request is: "Send the website or tell me what you're promoting; I can draft the copy and use your brand colors." This is an example, not wording that must be repeated. Do not require the user to provide timings, models, camera instructions, or finished copy.

Distinguish essential inputs from optional preferences:

- A message, subject, or product is essential; a URL can supply that context.
- A real product's appearance needs a usable product reference when accuracy matters. A fictional product can be designed here.
- The footage-overlay preset requires actual source footage. If source speech is requested, preserve its identity and timing. Apply the campaign audio choice; music/effects do not authorize replacement speech. A source article's presenter is not a stand-in for the user's presenter.
- Architecture accuracy requires supplied references or specifications; otherwise clearly treat the building as conceptual.
- Exact offers, dates, statistics, and product claims must come from the user or a reliable source. Use neutral copy when unknown.
- Existing copy, logos, colors, audience, CTA, aspect ratio, and audio preference are optional when reasonable defaults or current context suffice. Do not turn these into a mandatory questionnaire.

For missing essentials, ask one bundled, concise question while continuing work that does not depend on the answer. Optional missing details do not block progress. If user assets are needed for an external upload, honor the active tool's actual authorization requirements at the handoff; do not add speculative approval gates.

## Continue to the requested deliverable

Preserve the user's current intent. Browsing or selecting a favorite alone is not a request to generate paid media. "Use this for my course and make the video" is production intent: write the brief and continue through asset creation, submission, review, and finishing without asking for the same authorization again. If the user asks for a draft, stop at the draft. If they request a review checkpoint, honor it.

Follow [template-adaptation.md](template-adaptation.md) to bind the full template to the actual product. Preserve its detailed shot structure and motion instructions, map scene meaning to actual source assets, and reconcile every on-screen string. A burger ingredient tunnel might become a coffee-bean-to-cup assembly; a software workflow might be better served by the glass UI preset. Flag a poor fit and use the smallest explained adaptation that keeps the selected look. Never generate from only the short catalog description.

Record a small `campaign.json` in the task's work area once production or substantial revision starts. Suggested fields:

```json
{
  "preset_id": "kinetic-typography",
  "mode": "production",
  "subject": "User's product or message",
  "brand": "Supplied brand or demo name",
  "source_urls": [],
  "copy": [],
  "palette": {},
  "format": {"duration_s": 15, "aspect_ratio": "16:9", "fps": 30},
  "audio": "music_and_effects_no_narration",
  "ending": "hold",
  "template_version": 4,
  "template_path": "references/templates/kinetic-typography.md",
  "shot_map_path": "shot-map.json",
  "template_departures": [],
  "source_prompt_path": "references/source-prompts/kinetic-typography.txt",
  "generation_strategy": "one_full_film_request",
  "inputs": [],
  "explicit_constraints": [],
  "derived_assumptions": [],
  "revision": 1
}
```

Populate real values; do not submit placeholders. Keep generated files and job state in the production manifest described in `production.md`. The campaign record separates user-approved requirements from defaults so a later style change does not accidentally erase them.

The full creative brief remains the project source of truth. Keep the original prompt format as directed by `creative-brief.md`, with the shot map and settings alongside it, then execute `production.md`. Generate images only when the shot plan and selected model benefit from them. Show actual outputs, never represent the gallery preview as a new result.

## Revisions

- **Less frantic / more elegant:** Reduce the number or amplitude of moves, lengthen reading holds, and adjust easing while retaining the selected mechanic.
- **New headline / CTA:** Change the exact-copy contract and affected typography. Reuse passing footage when text was composited separately.
- **Same message, different template:** Keep brand, claims, approved copy, format, and explicit audio preferences; load the new full template and rebuild its content map and dependent motion/assets. Surface any material fit conflict briefly.
- **Vertical:** Recompose subjects, type, and trajectories; follow the house safe-zone guidance. Do not crop off the hero or tracked labels.
- **Another product:** Update the semantic story and identity references, not just the name. Preserve the chosen visual structure where it still fits.

## Adding more presets later

Inspect the source video and full prompt together. Archive the complete original prompt with source link, hash and original settings. Then write a separately labeled parameterized guide retaining shot/phase order, numerical timing where supplied, camera moves, transition mechanics, lighting changes, layer/material rules, asset roles and ending. Distinguish source timings from authored retiming, and preserve enough detail to reproduce the intended motion. A broad style recipe is insufficient. Add the short preset entrypoint as navigation. Keep source link, section, preview URL, observation date and known discrepancies. Do not import commercial claims or identity permissions as defaults, and label adaptations accurately rather than calling them verbatim originals.

Add the card, template path, template version and contiguous default timeline to `assets/presets.json`, then run `scripts/build_gallery.py`. It validates linked preset/template paths and timeline coverage and embeds the full templates in the gallery for inspection. Verify the new preview, full-template view and copied request. Preserve existing preset IDs so old requests still resolve.
