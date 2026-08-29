<p align="center"><img src="./data/images/banner.svg" alt="GPT-Image2 Prompt System" width="800" /></p>

<h3 align="center">Prompt as Code | GPT-Image2 Industrial Prompt Engine & Template Library, 500+ Reverse-Engineered Cases, 20+ Industrial Templates</h3>

<p align="center">
  <a href="https://github.com/lucianvaleblackthorn/awesome-gpt-image-2"><img src="https://img.shields.io/github/stars/lucianvaleblackthorn/awesome-gpt-image-2?style=flat-square&color=rgb(25%2C%20121%2C%20255)" alt="Stars"></a>
  <a href="https://github.com/lucianvaleblackthorn/awesome-gpt-image-2"><img src="https://img.shields.io/github/forks/lucianvaleblackthorn/awesome-gpt-image-2?style=flat-square&color=green" alt="Forks"></a>
  <a href="https://github.com/lucianvaleblackthorn/awesome-gpt-image-2"><img src="https://img.shields.io/badge/Cases-538-blueviolet?style=flat-square" alt="Cases"></a>
  <a href="https://github.com/lucianvaleblackthorn/awesome-gpt-image-2"><img src="https://img.shields.io/badge/100%25-Original_AI_Rewritten-green?style=flat-square" alt="Original"></a>
</p>

<p align="center">
  <strong>English</strong>
</p>

## About This Fork

This is an **English-language fork** of the original [awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) project by **freestylefly**. All Chinese and Japanese content has been translated to English. Full attribution is preserved under the MIT License.

## Project Vision

After GPT-Image2 became widely available, AI image generation moved from "can it make an image?" to "can it make stable, controllable, reusable images?" This project turns scattered community examples into Prompt-as-Code assets that are easier for agents and automation workflows to reuse.

The core goal is simple: compress prose-style prompts into structured protocols. When you need batch generation, template systems, or production workflows, this structure is more valuable than a pile of isolated examples.

- Atomic schema: split subjects, lighting, materials, layout, and visual details into composable parts
- Workflow friendly: designed for agents, scripts, and automation systems
- Structured control: improve controllability for layout, copy, and information hierarchy

## Quick Links

- [Full case gallery](docs/gallery.md)
- [Gallery Part 1: cases 1-165](docs/gallery-part-1.md)
- [Gallery Part 2: cases 166-538](docs/gallery-part-2.md)
- [Industrial prompt templates and pitfalls guide](docs/templates.md)
- [Agent skill: GPT-Image2 Style Library](agents/skills/gpt-image-2-style-library/SKILL.md)
- [MIT License](LICENSE)
- [Full disclaimer](docs/disclaimer.md#section-disclaimer)

## Category Overview

Start with the case album to find a visual direction, then open the prompt template categories to turn that direction into reusable structure.

### Case Album

| Category | Cases | Description |
|---|---|---|
| UI & Interfaces | 73 | Apps, websites, dashboards, social screenshots, and product interfaces |
| Charts & Infographics | 52 | Infographics, knowledge maps, technical explainers, and structured diagrams |
| Posters & Typography | 88 | Event posters, covers, type-driven visuals, and strong layout compositions |
| Products & E-commerce | 41 | Product shots, detail pages, packaging, selling points, and ads |
| Brand & Logos | 27 | Logos, identity systems, brand touchpoints, and campaign visuals |
| Architecture & Spaces | 12 | Architecture renders, interiors, city maps, and spatial concepts |
| Photography & Realism | 78 | Portraits, phone photography, film texture, and commercial photography |
| Illustration & Art | 58 | Illustration, art styles, material experiments, and decorative images |
| Characters & People | 31 | Character design, pose references, cards, and 3D toys |
| Scenes & Storytelling | 21 | Storyboards, narrative scenes, livestream frames, and worldbuilding |
| History & Classical Themes | 16 | Classical scrolls, historical figures, traditional themes, and poetry visuals |
| Documents & Publishing | 10 | White papers, manuals, encyclopedic plates, and publishing layouts |
| Other Use Cases | 28 | Creative experiments, special tasks, mixed workflows, and practical cases |

### Prompt Template Categories

| Category | Template Entry | Core Capability |
|---|---|---|
| UI & Interfaces | [View Prompts](docs/templates.md#tpl-ui) | Components, page hierarchy, screenshot texture |
| Charts & Infographics | [View Prompts](docs/templates.md#tpl-infographic) | Modules, arrows, data structure, readability |
| Posters & Typography | [View Prompts](docs/templates.md#tpl-poster) | Layout, headline systems, people, visual impact |
| Products & E-commerce | [View Prompts](docs/templates.md#tpl-product) | Selling points, packaging, detail pages, ad composition |
| Brand & Logos | [View Prompts](docs/templates.md#tpl-brand) | Identity systems, logo construction, brand touchpoints |
| Architecture & Spaces | [View Prompts](docs/templates.md#tpl-architecture) | Renders, interior lighting, spatial narratives |
| Photography & Realism | [View Prompts](docs/templates.md#tpl-photo) | Portrait, film texture, commercial lighting, realism |
| Illustration & Art | [View Prompts](docs/templates.md#tpl-illustration) | Style systems, material experiments, artistic expression |
| Characters & People | [View Prompts](docs/templates.md#tpl-character) | Character sheets, pose references, figure cards |
| Scenes & Storytelling | [View Prompts](docs/templates.md#tpl-scene) | Storyboards, narrative scenes, worldbuilding |
| History & Classical Themes | [View Prompts](docs/templates.md#tpl-history) | Classical scrolls, historical figures, poetry visuals |
| Documents & Publishing | [View Prompts](docs/templates.md#tpl-document) | White papers, manuals, publishing layouts |

## Agent Skill: GPT-Image2 Style Library

Install the GPT-Image2 style library into Claude Code and Codex. Install a skill that lets your agent auto-select from templates, styles, scenes, and pitfall rules sourced from this site, and directly output copyable GPT-Image2 prompts.

```bash
npx gpt-image-2-style-library
```

Example request: `Use the gpt-image-2-style-library skill to generate a city life system map`

## Acknowledgments

This project is a fork of the original [awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) by freestylefly. The original project compiled 538+ GPT-Image2 prompt cases and 20+ industrial prompt templates from the community. All credit for the original research and curation goes to freestylefly.

This fork translates all content to English while preserving the MIT License and full attribution to the original author.

## License

MIT License — see [LICENSE](LICENSE) for details.
