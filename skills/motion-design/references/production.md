# Full-film production and media handoff

Read only for authorized asset/video production. User-requested prompt review ends before generation or upload.

## Resolve the film and route

Read the selected original source prompt and adaptation guide. Bind the content using [template-adaptation.md](template-adaptation.md), and create the compact before/after review record in [quality-review.md](quality-review.md). Select the strongest suitable accessible model, preferring current Seedance. Inspect duration, aspect ratio, resolution, reference roles/limits, audio support and prompt limits through actual tools.

Keep source endpoint/format as provenance. A Marketing Studio SaaS source and a Seedance adaptation are different routes; preserve the creative template while disclosing this difference. Do not guess an unavailable preset slug or interpret catalog exposure as account entitlement. Use read-only estimation for cost/access preflight when supported, never generation as a probe.

One request should contain the entire film. A provider failure does not establish that the duration or shot count is unsupported. Inspect the returned error and current schema before changing approach. If the preferred route is unavailable, explain a concrete suitable fallback. A material change to the user's one-film method requires their acceptance; do not silently begin separate clip production.

## Decide whether references help

- **Prompt-only:** Type, abstract motion and scenes whose identity can be expressed adequately in text.
- **Existing assets:** Product appearance, recognizable people, actual software outputs or supplied footage. Use the minimum set covering the required identity/content.
- **Generated references:** A style frame, hero design or storyboard that resolves a specific ambiguity. Follow [tool-routing.md](tool-routing.md): Codex built-in image generation when available; Claude Code via Higgsfield MCP, preferring GPT Image 2. Inspect the result. A storyboard is optional full-film reference material, not an instruction to create one video per frame.

Identify each asset's purpose: identity, style, motion reference, start frame or end frame. A generic reference must not accidentally become a start frame that fixes the film to one layout. Use a storyboard contact sheet only when supported as a general reference and explicitly describe its panels as temporal guidance; never supply it as the literal opening image.

Reuse acquired assets. Do not regenerate source screenshots to make them look more polished. Only create assets the chosen request will actually use. Record whether the model output is an illustration or preserves original source media; do not promise pixel-exact screenshots from conditioning alone.

## Submit the complete request

Upload/attach only the selected assets through the supported media mechanism, then bind real media identifiers and roles. Preserve the exact reviewed creative prompt; technical adaptation should not silently change its content. Include every shot and shared motion rule in the same request, with one requested output by default. Never send unresolved source attachment markers, draft paths or placeholders as remote inputs.

For audio-enabled campaigns, include both the soundscape and music directions in the full prompt and enable native audio where supported. Music and effects do not imply narration. If native audio is unavailable, explain the needed audio route before changing the workflow. Respect explicit silence or source-speech instructions.

Save a small record with source prompt hash, adapted prompt, deliberate changes, exact-copy list, source/evidence URLs, actual input roles, model/settings, job ID/status and eventual result. A failed or uncertain submission is not a completed film. Rejoin an existing job after an uncertain response instead of submitting a duplicate.

## Inspect and revise

Inspect playback for the full sequence: shot order, transitions, camera amplitudes, light/dark passages, pacing, identity, text, data and ending. Compare with both the original reference and product content map. Fill the observed result and evidence in the [quality review](quality-review.md), including any uninspected requirement. Representative stills alone cannot establish smooth temporal behavior.

Listen for music/effects synchronization, unintended speech, clipped audio and a clean ending. Exact copy and benchmark values must survive the rendered frames; prompt instructions are not proof. The original preview's polish is not a guarantee of first-attempt output.

Default to one corrective full-film generation or supported targeted video edit within the authorized run, unless the user sets another retry/budget limit. Retain the original result for comparison. After that, report the unresolved issue and next action rather than starting an unbounded paid loop. Do not make segmentation the corrective default.

Technical finishing such as trimming/conforming is optional and must not replace the intended generation method. An exact typography/source-media composite is a disclosed fallback when generated content fails, not a mandatory production pipeline. Use available Higgsfield media tools for finishing; do not introduce Blender. Verify the delivered duration, dimensions, fps, audio, copy and final hold. A 15-second 30fps delivery has 450 frames, but frame count alone says nothing about visual fidelity.

Deliver the inspected film or the precise remaining limitation. Distinguish prompt-ready, submitted, completed and reviewed states.
