# Image tools and host compatibility

One shared skill supports Codex and Claude Code. Choose from tools actually exposed in the current session. Tool prefixes differ between clients; the operation names below describe capabilities, not universal callable names.

| Task | Codex | Claude Code |
|---|---|---|
| Browse examples or draft a prompt | Local skill files; no generation required | Same |
| Create needed reference images | Built-in image generation when available, following its tool instructions | Higgsfield MCP image generation; prefer GPT Image 2 |
| Generate the complete film | Higgsfield MCP; suitable current Seedance preferred | Same |
| Inspect and finish | Available playback, audio and Higgsfield media tools | Same; do not assume Codex widgets exist |

Explicit user choices override defaults. If Codex has no built-in image tool, use the connected Higgsfield image route for an authorized image task and state the route change. If Higgsfield is disconnected in Claude Code, finish the prompt/asset plan and explain the missing connection; do not call a nonexistent built-in image tool.

## Higgsfield image generation

1. Decide whether an image is needed at all. Reuse supplied product photos, screenshots or existing assets when they meet the need. A prompt-only film needs no image job.
2. Discover the image model through read-only model search/get operations. The catalog observed September 5, 2026 exposes **GPT Image 2** as `gpt_image_2`, with `resolution` choices `1k`, `2k`, `4k` and `quality` choices `low`, `medium`, `high`. These are an observed preference, not a permanent schema: inspect current availability and parameters before use. Select quality/resolution for the asset's role and requested budget; do not silently accept a low-quality default for a detail-critical reference.
3. Inspect accepted aspect ratios, reference roles and upload requirements. Confirm cost through read-only estimation when supported. Model presence does not establish account access or free generation. If GPT Image 2 is unavailable, explain the limitation and a suitable alternative; preserve any explicit model restriction.
4. Submit only within image/production authorization. A request to review the film prompt first stops before image generation, uploads and video generation. Follow the live tool's result/wait mechanism, inspect the image, and retain its job record.

## Bind images to the film

Record why each image is used: identity, style, motion, start frame or end frame. Keep content references distinct from style references. A general style image must not silently become a fixed opening composition. Do not use a storyboard contact sheet as the literal first frame.

A local image path is not a remote attachment. Use the client's supported upload operation, transfer bytes if the tool requires it, and confirm only after successful transfer. Reuse a Higgsfield-generated asset directly only when the video tool accepts its returned media identifier or URL. A job ID is not automatically a media ID. Bind actual inputs using the video model's current schema; never invent an ID, reuse an unrelated asset, or pass a local path as a public URL.

Keep exact image prompts, selected models/settings, asset roles and returned identifiers in the private campaign workspace. Do not copy account configuration or private asset URLs into this public skill package.

## Connection help

Installation of this skill and authentication to Higgsfield are separate steps. Use the repository's setup instructions and the [official Higgsfield connection guide](https://higgsfield.ai/mcp). This workflow targets MCP in both clients; a CLI-only installation needs its own verified adapter before it can be called equivalent. Do not install or reconfigure a connection just because the user asked to browse or draft.
