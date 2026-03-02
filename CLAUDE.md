# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Content research & marketing materials workspace for **HAUS Coastal Quảng Ngãi** — a real estate project by Haus Group. This is NOT a software codebase; it's a content production workspace for generating sales training materials, presentations, and landing page content.

## Directory Structure

```
Content gioi tiheu HAUS QN/
├── Thong-tin/              ← Source materials (images, videos, text files)
│   ├── *.jpg               ← 19 presentation slides (analyzed)
│   ├── *.mp4               ← 3 project videos (analyzed)
│   ├── *.txt               ← Text content files
│   └── video-frames/       ← Extracted keyframes from videos
├── docs/                   ← Research & documentation
│   └── coastal-quang-ngai-project-research.md  ← Master research doc
├── assets/designs/slides/  ← Generated HTML slide decks
├── plans/                  ← Implementation plans
│   ├── reports/            ← Analysis reports
│   └── templates/          ← Plan templates
├── .claude/                ← Claude Code skills & agents config
└── CLAUDE.md               ← This file
```

## Key Files

- **`docs/coastal-quang-ngai-project-research.md`** — Comprehensive project research compiled from all source materials (19 images + 3 videos + 2 text files). Read this first for full project context.
- **`Thong-tin/`** — Raw source materials. Images are presentation slides; videos are project promo/infra/strategy videos.
- **`assets/designs/slides/`** — Generated HTML presentations (single-file, file:// compatible).

## Working With This Project

- All content is in **Vietnamese** (tiếng Việt có dấu). Always write Vietnamese output.
- Source images in `Thong-tin/` are presentation slides — use Read tool to view them directly (multimodal).
- Videos were analyzed via ffmpeg keyframe extraction → agent analysis. Frames in `Thong-tin/video-frames/`.
- HTML slides use inline CSS/JS, Chart.js from CDN, Google Fonts. Must work with `file://` protocol.

## Brand Guidelines (HAUS)

- Primary color: `#8B2500` (đỏ gạch/brick red)
- Accent: `#C44D2A`
- Background: `#FAFAF8` / `#FFFFFF`
- Fonts: Playfair Display (headings), Inter (body)
- Tone: Premium, sustainable, community-focused, 100-year vision

## Project Context

- **Developer**: HAUS Group ("A Community by HAUS")
- **Product line**: Community by HAUS — affordable for local residents
- **Location**: ĐT626, Nghĩa Hoà, Tư Nghĩa, Quảng Ngãi
- **Key partners**: SWECO (EU), Florian (Italy), Spiko, Swo
- **Reference model**: Seestadt Aspern, Vienna
- **Positioning**: Nordic sustainable community, urban regeneration
