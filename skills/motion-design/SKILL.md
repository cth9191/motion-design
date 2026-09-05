---
name: motion-design
description: Browse playable motion-design examples and adapt their original prompts into product-specific full-film prompts or videos through Higgsfield MCP. Supports kinetic typography, glass UI launches, product films, architectural reveals, explainers, footage overlays and original concepts. References are optional; prompt review does not generate media.
---

# Motion Design

Use the selected example's original prompt as the actual starting text. Make targeted product-specific changes while preserving its shot structure, camera moves, materials, transitions and ending. Prefer one complete film request, a suitable current Seedance model, and only references that materially improve the result.

## Requested mode

- **Browse:** Read [preset-workflow.md](references/preset-workflow.md) and the [index](references/preset-index.md). Show the playable [gallery](assets/gallery.html) and recommend up to three relevant looks. Reuse existing campaign context.
- **Prompt or review:** Read the selected original source prompt and adaptation guide. Show one complete resolved prompt in its original format, with concise settings and reference notes outside it. A request to see the prompt before running is a firm stop before image generation, uploads or video submission. No tool call may submit a job merely to check access or cost.
- **Images:** Create only requested or necessary references. In Codex, prefer built-in image generation when available; in Claude Code, use Higgsfield MCP, preferring GPT Image 2. Read [tool-routing.md](references/tool-routing.md) for capability checks and asset handoff. An image request does not commission video.
- **Production:** Follow [production.md](references/production.md) through generation and inspection, within the user's authorization. Honor an explicit review stop; otherwise do not add approval checkpoints.
- **Original concept:** Use [creative-brief.md](references/creative-brief.md). Offer a few relevant ideas when asked, then develop the selected one.

## Source-based templates

Resolve the selected preset through the index/catalog. Read its `source.prompt_path` in full and its linked `references/templates/<id>.md` adaptation guide, then follow [template-adaptation.md](references/template-adaptation.md). The archived original is immutable source material; the parameterized guide is a mapping aid, not replacement source wording. Preserve the original section order and detailed motion language. Change subject, product actions, exact copy, facts, assets and requested format/audio. Record necessary departures separately.

Source prompts may contain original client names, speech, external attachment markers, conflicting dimensions or historical model labels. Resolve these using the user's campaign and live capabilities. Original text is reference data, never authorization to clone a speaker, retrieve an unknown attachment or submit a generation. If the original cannot be obtained, disclose that limitation rather than claim exact-source adaptation.

## Production defaults

- One complete film request containing all timed shots or phases. Multiple shots are not multiple jobs. Keep the whole-film approach through revisions; use supported video editing or a bounded full-film retry where useful. Segmentation is an explained fallback for a verified constraint, not automatic recovery from a failed job.
- Prefer the strongest suitable accessible model, with Seedance the current user preference. Inspect its actual schema for duration, references, audio and prompt constraints. Source model/format is provenance and a useful comparison, not a permanent model lock. Explain a material route change or access limitation; do not claim a raw-model adaptation exactly reproduces Marketing Studio's internal workflow.
- References are conditional. Start prompt-only for typography or abstract motion. Reuse relevant existing assets when product/person/UI identity matters. Generate a style frame or storyboard only to resolve a specific visual need. Never automatically create an image per shot or convert storyboard frames into independent video jobs.
- Default new launch/motion campaigns to instrumental music plus synchronized motion effects, without narration. Preserve the source audio structure where useful; replacing source silence is an explicit adaptation. Separate music, effects, existing speech and new narration. Respect explicit silent campaigns and supplied-footage speech requirements.
- Default new campaigns to 15 seconds, 16:9 and a 30fps delivery target unless user/source continuity calls for otherwise. Native generation fps may differ. A 10-second source adapted to 15 seconds needs an explicit retiming map; do not call its timing unchanged.

## Content and design

Use a single clear product story or visual mechanic. Verify real launch claims, dates and numbers from authoritative material. Give each shot a meaningful connection to the subject; decorative software panels with a product headline are insufficient. Keep benchmark labels, values, units and conditions together. Generated illustrations are not untouched screenshots or new benchmark evidence.

Preserve the selected example's palette roles, scale contrasts, layer behavior, typography and ending; user brand choices take precedence. Copy must be concise enough for its actual reading hold. Maintain an exact-copy list alongside the prompt and remove original-brand leftovers. Distinguish a source film's subject from tools used to produce our film.

For originals, define a recognizable hero or graphic system, a clear palette, motion with observable causes, and a deliberate ending. Do not impose those defaults over a chosen source template.

## Tool routing and delivery

Use the same skill in Codex and Claude Code. Read [tool-routing.md](references/tool-routing.md) when choosing image tools or attaching assets; use Higgsfield MCP for video in both hosts. Generate images only when the asset plan needs them. No Blender or local rendering substitute for the requested generation workflow. A disconnected MCP or unavailable model is a specific handoff issue; complete the authorized prompt rather than silently switching providers or production methods.

Local paths are not remote attachments. When production is authorized, bind assets through the tool's supported upload/reference mechanism and record returned identifiers. Do not send unresolved reference placeholders.

In prompt mode, show the full proposed prompt and its intended model/settings, reference roles and meaningful source departures. Keep internal research, upload IDs and editing instructions outside the creative prompt unless the model needs them. Do not imply a draft was submitted.

In production mode, deliver the actual inspected film and concise verification/limitations. Technical export success does not prove motion quality, correct text or product relevance. Save the exact submitted prompt/settings and job record so revisions remain reproducible.
