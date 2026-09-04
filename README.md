# Higgsfield Motion Design

A Codex skill for choosing a motion-design example, adapting its original prompt to a product or topic, and generating one complete film through Higgsfield MCP.

**Status:** working prototype; skill and catalog version 4. This repository packages the installed skill. Proposed improvements are tracked in [ROADMAP.md](ROADMAP.md), not claimed as completed.

## What it includes

- Ten presets with playable source examples, archived original prompts, and separate adaptation guides.
- Prompt review before generation when requested.
- One complete film request by default, with Seedance preferred when suitable and accessible.
- Optional image references, instrumental music and motion effects, and result inspection.
- Source provenance and hashes so original prompts remain separate from adaptations.

This is an independently assembled workflow, not an official Higgsfield product. Model output can alter text, charts, timing, and visual details; review remains necessary.

## Requirements

- Codex with support for local skills.
- An authenticated Higgsfield MCP connection for media generation.
- Access to the selected model and sufficient credits or an applicable allowance.
- Built-in image generation only when a task benefits from new reference images.
- Python 3.10+ only for rebuilding the gallery or serving it locally.

The skill does not install the Higgsfield MCP server or include account credentials. Browsing the gallery and drafting prompts do not submit video jobs. Reference videos stream from their original public hosts.

## Install in Codex

Ask Codex:

```text
$skill-installer

Install the skill from:
https://github.com/cth9191/higgsfield-motion-design/tree/main/skills/higgsfield-motion-design
```

The repository is public. Higgsfield generation still uses each person's own authenticated account. The skill installer stops if the destination already exists; use an explicit update request for an existing installation.

The installable directory is [skills/higgsfield-motion-design](skills/higgsfield-motion-design). Its entrypoint is [SKILL.md](skills/higgsfield-motion-design/SKILL.md).

## Use it

Browse styles:

```text
$higgsfield-motion-design

Show me the available motion-graphics styles with their examples.
```

Try a topic:

```text
$higgsfield-motion-design

Create a beginner-friendly, 15-second flat vector explainer about
how LLMs generate an answer. Use the flat-vector-explainer template
and Seedance 2.5 through Higgsfield MCP.
Show me the full adapted prompt before generating.
```

Try a website:

```text
$higgsfield-motion-design

Use the website URL I provide to propose a 15-second promo.
Choose a suitable template, focus on one main benefit, and show me
the complete adapted prompt before generating.
```

After reviewing a prompt, ask Codex to generate it. A request to see the prompt first stops before image generation, uploads, or paid video submission.

References are conditional. A simple conceptual film may be prompt-only; a product or interface may need actual source assets. Multiple shots remain parts of one film request.

## Presets

Kinetic typography · Glass UI launch · Product hyper-motion · Tropical product · Exploded product · Blueprint to building · Hybrid 2D + 3D · Flat vector explainer · Editorial collage · Footage + graphics.

See the [preset index](skills/higgsfield-motion-design/references/preset-index.md) for descriptions and requirements.

## Preview the gallery

Open `skills/higgsfield-motion-design/assets/gallery.html` from a local checkout. GitHub displays its source rather than serving it as a website.

Alternatively, from the repository root:

```sh
python -m http.server 8765 --bind 127.0.0.1 --directory skills/higgsfield-motion-design
```

Then visit [the local gallery](http://127.0.0.1:8765/assets/gallery.html). The gallery helps select a look and copy a request; it does not launch generation.

## Maintain the package

Edit the copy under `skills/higgsfield-motion-design/`, then run:

```sh
python skills/higgsfield-motion-design/scripts/build_gallery.py
```

The builder validates preset IDs, linked resources, timing coverage, and original-prompt hashes, then refreshes the gallery and index. Commit those generated files with the changes. GitHub Actions runs the same check.

Treat archived source prompts as immutable. Edit the adaptation guides and workflow instructions when improving behavior. A source correction needs matching provenance and hash updates.

The repository and a locally installed skill are separate copies. Editing one does not automatically update the other.

## Attribution and scope

See [ATTRIBUTION.md](ATTRIBUTION.md) for source provenance. This repository includes the reusable skill and source-reference library; campaign videos, account configuration, and private generation records are not included.

No repository-wide license has been selected. Third-party source material is identified separately from the workflow and adaptation guides.
