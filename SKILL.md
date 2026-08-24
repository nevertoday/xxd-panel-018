---
name: xxd-panel-018
description: "Create XXD Panel 018 artwork from supplied photos in four combinable modes: photo above/minimal layered paper-cut editorial below, photo left/design right, design alone, or a four-device wallpaper pack with independent or anchor-linked continuity. Uses one recognisable visual-anchor subject, a few source-earned foreground/midground/background paper layers, folds, cuts, occlusion, warm ivory space, matte fibre, clear edges, soft contact shadows, a restrained source-derived colour-role system, and a complete title-plus-microtype editorial path. Use for the exact 018 minimal layered paper-memory style; never use it for 014-style dominant faceted paper sculpture, cartoon origami, children's craft, complex stacking, smooth plastic 3D, ecommerce mockups, or multi-photo collage."
---

# XXD Panel 018 · 极简层叠剪纸微排版

Turn each supplied photograph into one finished minimal layered paper-cut editorial. Preserve the real photograph only in paired modes; every transformed frame must retain the same source's identity, silhouette, pose, and narrative relation through one visual-anchor subject, a few foreground/midground/background paper layers, folds, cuts, occlusion, clear negative space, matte fibre, edge thickness, soft contact shadow, and a complete microtypographic reading path.

Operational rules follow the shared XXD Panel workflow contract: four combinable modes; an explicitly confirmed whole-canvas ratio or exact resolution before generation; single complete-canvas raster generation by default; high-fidelity source reference in paired modes; linked or independent four-device wallpapers; copy and locale preflight; fresh generation jobs; privacy-preserving raster generation; deterministic composition as fallback only; and one fresh task directory per source and mode. Style-specific sections refine aesthetics and copy but never override this contract.

## Non-negotiable contract

- One source photo may be processed in one or more selected modes. Each selected ordinary mode (`top-bottom`, `left-right`, `design-only`) produces one PNG; selected `wallpaper-pack` produces exactly four separate PNGs. Selecting all four modes therefore produces seven final files per source. Keep every mode in its own task directory and never combine modes, sources, or wallpapers into a grid, contact sheet, or overview.
- Resolve a non-empty ordered set of modes before generation: `top-bottom`, `left-right`, `design-only`, and/or `wallpaper-pack`. Accept one choice, multiple choices separated by `+`, Chinese/English commas or whitespace, natural-language names, or `全部` / `all`. Deduplicate repeated choices and execute in menu order 1→4. If none is specified, ask with the multiline multi-select menu in the workflow. Do not ask again when the set is already clear.
- When the selected set contains `wallpaper-pack`, require a second choice: `linked` or `independent`. A linked pack approves one anchor wallpaper, iPad by default, and makes every other device reference both the original photo and that same anchor. An independent pack gives every device only the original photo. Neither permits resizing or cropping one wallpaper into the others. Do not ask this follow-up when wallpaper mode is not selected.
- Paired modes target a visually equal 50/50 relationship within one coherent generated canvas. Minor generative deviation is acceptable unless the user explicitly requires pixel-exact halves; exact deterministic geometry belongs to the documented fallback. `design-only` and every wallpaper contain no visible source photograph, no seam, and no reserved photographic panel.
- The whole final canvas ratio or exact pixels must be explicitly resolved before generation. Offer the archived/original-prompt 3:4, source aspect as an explicit choice, common ratios, or custom ratio/pixels; never infer explicitly selected final-canvas dimensions silently. Exact pixels take precedence over an explicitly chosen ratio.
- Visible photography remains faithful. Allow only restrained editorial grading and environmental extension needed for an explicitly overridden canvas. Never stretch, distort, repaint, replace, or structurally alter the subject.
- The transformed frame must preserve source identity through at least three specific cues while using one visual-anchor subject and only a few source-earned foreground, midground, and background paper layers. Folds, cuts, scale, axes, positive/negative shape, front/back occlusion, and generous space build hierarchy. It is not literal tracing, a dominant multi-faceted 014-style sculpture, repeated subjects, cartoon origami, children's craft, complex stacking, smooth low-poly CG, plastic 3D, ecommerce mockup, or unrelated paper decoration.
- Copy has no silent default. Resolve automatic copy, exact custom copy, or text-free output before image generation. Automatic and custom modes also require a target language or locale. By default, one source-specific copy package is shared verbatim across all selected modes; explicit per-mode copy instructions override it.
- Render no logo, watermark, signature, colour swatch, UI, device mockup, decorative pseudo-text, or unrelated explanatory prose.

## Aesthetic motive lock

Modes and device ratios may change placement and aspect ratio but never the 018 motive. Every transformed frame must visibly express this chain:

**this exact photographed subject or inseparable relation → preserve at least three identity, silhouette, pose, action, structure, scale, negative-shape, or relation cues → choose one core subject as the visual anchor → simplify it through fold, cut, layer, and occlusion without mechanically reproducing detail → translate only a few source environment relations into foreground, midground, and background paper layers → organise scale difference, axes, positive/negative shape, front/back occlusion, and generous warm-ivory space → assign one main colour, one dark structural colour, one light layer colour, and at most a tiny source-supported accent → reveal matte fibre, clear cut edges, layer thickness, and soft contact shadows under diffuse light → integrate one short title plus two to four microtext groups along paper edges, contours, axes, and negative space so paper carries visual memory and microtype carries editorial order**.

The paper construction comes from the source's actual silhouette, pose, action, mass, direction, opening, overlap, relation, and environment—not from generic cranes, flowers, geometric bursts, or folded-paper ornaments. Minimal layered paper cut, paper-relief collage, book arts, tactile editorial still life, and precise publication microtypography are construction influences rather than templates.

Reject the result as generic when an unrelated photo could replace the source without materially changing the anchor silhouette, layer map, foreground/midground/background relations, palette roles, negative space, or typographic path. Also reject dominant faceted sculpture, literal miniature replicas, repeated subjects, overly complex stacking, decorative shards, average symmetry, smooth CGI, shiny plastic, metal, clay, foam board, cheap card, neon colour, complex gradients, harsh product lighting, cartoon craft, and templated ecommerce display.

## 018 visual system

### One recognisable visual anchor

- Privately lock at least three source-specific cues across silhouette, pose/orientation, opening, connection, overlap, negative shape, mass, scale, relation distance, or dominant direction.
- Translate identity into a sparse layer map: which contour becomes a cut edge, which key volume becomes a folded plane, which overlap becomes a front/back paper layer, which opening becomes negative space, and which environment relation becomes foreground, midground, or background.
- People keep pose, direction, clothing mass, and relational distance; animals keep body rhythm and head direction; plants keep growth gesture; architecture keeps skyline and defining openings; objects and vehicles keep functional silhouette and negative shape; landscapes keep one source-specific horizon, terrain, or spatial relation.
- Preserve recognition at a glance without recreating every photographic detail. Every fold, cut, and layer must clarify identity, action, mass, spatial relation, or depth role.

### Few layers and clear editorial hierarchy

- Read the source's centre of gravity, contour trajectory, scale, axes, and movement. Place one paper anchor accordingly; it may be off-centre, locally cropped, extended, or suspended, but never duplicates itself.
- Select only a few environment relations and assign them explicitly to foreground, midground, or background. Use scale difference, axis relation, positive/negative form, and front/back occlusion to keep the hierarchy legible.
- Preserve generous warm-ivory or pale negative space. No decorative paper piece may exist merely to fill space or create a competing subject.
- Recompose for each aspect ratio rather than centring or cropping another output. Keep the anchor, three depth roles when present, title, microtype path, and key negative space intact.

### Fold, cut, layer, and occlude

- Use a restrained fold only where it clarifies a source joint, plane change, direction, or depth role. Cut contours stay clean; layers remain few, physically plausible, and easy to read.
- Clear cut edges reveal thickness, and each layer casts a soft contact shadow onto the paper directly behind it. Shadows explain stacking rather than dramatise volume.
- Keep large anchor shapes and only a few supporting layers. Avoid a confetti of facets, excessive accordion folds, decorative nesting, impossible floating pieces, and detail that erases the silhouette.
- Maintain tactile paper relief rather than a dominant freestanding sculpture. It should feel carefully assembled by a paper artist, not exported from a low-poly modeller.

### Source-derived colour roles and matte material

- Extract the source's most recognisable and vital colours, then assign one main colour, one dark structural colour, one light layer colour, and at most one tiny accent when clearly source-supported.
- Use warm ivory or a source-compatible pale paper ground with generous negative space. Each colour role must support identity, layer separation, axis, or emphasis rather than decorate.
- Illuminate with soft diffuse light that reveals fibre, fold creases, cut edges, thickness, layer separation, and natural shadows. Keep the result clean, real, and refined.
- Reject muddy ageing, uncontrolled rainbow colour, flat single-value planes, glossy lamination, plastic highlights, smooth CG normals, metallic reflection, hard product spotlight, and cheap card-stock appearance.

## Copy and typography belong to 018

018 text is a complete high-end editorial microtypographic system built into the layered paper composition—not a single folded-paper logo, detached digital headline, printed sticker, extruded plastic word, or generic caption block.

- Automatic copy derives one short source-specific title from identity, place when known, action, material, emotion, relation, or supported symbolism, plus two to four microtext groups chosen from an object name, supplied place information, index, chapter mark, sequence code, coordinate-like composition number, direction word, state word, material word, category label, or one very short poetic note.
- Automatic copy never uses or invents a year. Dates, places, provenance, coordinates, and factual numbers must be supplied or reliably established. Exact user wording remains verbatim even when it contains a year; the no-year rule constrains automatic invention only.
- Preserve exact user wording verbatim. Refine an editable direction only within permission while protecting audience, mandatory terms, tone, and semantic phrase breaks.
- Apply the unrelated-image swap test: generic lifestyle words that survive on another source must be rewritten.

Typography has its own 018 construction:

- **Role:** the main title carries recognition and emotion; microtype carries order, rhythm, classification, and refinement.
- **Voice:** concise, tactile, poised, contemporary, precise, and source-specific.
- **Construction:** one short main title plus two to four deliberately tiny groups with clear scale contrast and direction changes. The title may become a restrained cut- or folded-paper form; microtype remains slender and crisp.
- **Placement:** align along a paper edge, subject contour, geometric axis, or negative space; use horizontal or vertical setting, rotation, wide tracking when script-appropriate, edge attachment, corner pressure, crossing a colour block, nesting between layers, or partial occlusion only when it builds a readable path.
- **Material:** the title may be cut, folded, layered, or lightly printed matte paper; microtype stays as restrained modern editorial print. Both reveal proper paper interaction without chunky foam lettering.
- **Script:** use native paper-title and slender editorial equivalents for the resolved locale. Preserve natural Chinese, Japanese, Korean, Arabic, and Latin proportions, joining, direction, spacing, and legibility rather than forcing Latin block folds or tracking onto every script.

Resolve locale independently from command language:

```text
target market or audience > requested output language > direction language; if none is explicit, ask before generation
```

Localise by transcreation using native wording, rhetoric, punctuation, spacing, shaping, and semantic line breaks. Never infer nationality or audience language from appearance, clothing, scenery, filenames, metadata, or signs.

## Raster generation and privacy

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is exposed through the host's built-in image tool or an already configured compatible route, use it before any other model. Preserve the current XXD execution contract: resolve the whole final canvas before generation, use the source as a high-fidelity reference, generate paired modes as one complete canvas, and keep deterministic composition as fallback only.
- Also support **Seedance 5.0 Pro**, **Nano Banana Pro (Gemini Image Pro)**, **Nano Banana 2 (Gemini Image Flash)**, or another compatible bitmap model when it is actually available through a tool or configured route and can satisfy the selected mode. Required capabilities include reference-image generation/editing, source fidelity, the resolved whole-canvas ratio, native target-language text, and multi-image reference input when a linked wallpaper pack needs it.
- Alternative models are secondary routes, not a different workflow. Do not let a model switch silently change the selected modes, final canvas, source-visibility rules, copy, locale, wallpaper relationship, fresh-task boundary, raster-only delivery, or the full-canvas-first strategy. If an alternative cannot satisfy a hard requirement, do not silently degrade that requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. A user may voluntarily provide credentials for the current task. Accept them without echoing, displaying, logging, or reporting their value. Do not persist credentials or modify provider, account, billing, or global route configuration unless the user explicitly asks for that configuration change.
- Determine availability from an actual image-capability check. Do not declare GPT Image 2 or every other route unavailable merely because one tool is absent, one call failed, or one expected environment variable is unset.

Prefer GPT Image 2 through the host's built-in bitmap image-generation capability when exposed, and follow the available `imagegen` skill for the built-in execution details. View each local source before generation. Use one generation call per distinct asset; a wallpaper pack requires four calls. “Layered paper cut”, “paper relief”, “paper collage”, and “editorial microtypography” describe appearance only and never authorise SVG, HTML, CSS, Canvas, diagrams, or programmatic drawing as the artwork.

If built-in bitmap generation is unavailable, use `scripts/configured_imagegen.py`, which reuses an already configured compatible bitmap route and emits sanitised status only:

```bash
python3 scripts/configured_imagegen.py probe
python3 scripts/configured_imagegen.py edit --image source.png \
  --prompt-file /private/job-temp/transform-prompt.txt \
  --out /private/job-temp/design.png --size 1536x1024 --quality high
```

Judge readiness by actual bitmap capability, not a provider name or one environment variable. Never display, echo, log, or report the user's actual provider, endpoint, headers, credential values, account identifiers, route configuration, prompts, or response bodies. Do not manually inspect unrelated credential files. Do not persist user-provided credentials or modify global route configuration unless explicitly requested. The bridge's sanitised JSON is the complete allowed diagnostic surface.

An explicit invocation of `/xxd-panel-018` or `$xxd-panel-018` with a source image and requested output authorises generation through any already configured authenticated bitmap route available to the session. Do not ask for a second confirmation solely because the route changes. This does not authorise changing credentials, providers, billing, accounts, or global settings.

Only report generation as unavailable after checking preferred GPT Image 2, every eligible exposed alternative, the bundled probe, and any suitable route or API key the user elects to provide. State the limitation narrowly and never guess the cause or expose the user's actual provider. Never substitute code-rendered art.

## Fresh-task and source boundary

Every invocation starts a fresh generation job unless the user explicitly asks to continue, audit, compare, edit, or reuse a named earlier result. Repeating the same source and parameters still means generating a new result in a new task directory. An old file can never satisfy a new request.

Use only images attached to the current invocation, explicit user paths, or a previously supplied image that the current request clearly identifies as “the same image”. Never broadly scan the Desktop, workspace, `~/Desktop/xxd/xxd-panel-018/`, or historical task folders to find a substitute source. If the intended source cannot be accessed, ask for it.

## Workflow

1. Resolve one or more modes. If missing, ask exactly this as normal multiline chat text and wait:

   ```text
   请选择一个或多个模式（回复序号；多选可用 +、顿号或逗号）：

   1. 上下双联（原图在上＋018 设计在下）
   2. 左右双联（原图在左＋018 设计在右）
   3. 纯设计版（只显示 018 设计画面）
   4. 四端壁纸套装
      手机＋iPad＋电脑＋儿童手表

   示例：1｜1+3｜1、2、4｜全部
   ```

2. Before any ordinary-mode generation, explicitly resolve the **final finished canvas**, not the size of one panel. If the user did not already supply a ratio or exact pixels, ask and wait:

   ```text
   请选择最终成品画幅（回复序号即可；多选模式可共用，也可分别指定）：

   1. 原提示词画幅 3:4
   2. 跟随原图比例
   3. 常用比例
      1:1｜4:5｜2:3｜3:2｜16:9｜9:16
   4. 自定义比例或准确像素

   这里指整张最终成品的比例，不是单个区域。
   示例：1｜3：9:16｜4：2160×3840
   ```

   “跟随原图比例” is valid only when the user explicitly selects it. Never infer a silent canvas from the source dimensions, orientation, archived 3:4 brief, mode, or previous output. In multi-select, ask which mode an ambiguous ratio belongs to. Exact pixels take priority over a chosen ratio. For paired modes, odd split axes are allowed for direct generation; require an even split axis only if deterministic fallback composition is actually triggered.

3. Before generation, resolve copy mode and locale. If missing, ask and wait:

   ```text
   正式做图前，请确认文字设置（回复序号即可）：

   1. 自动文案
      我根据原图与 018 气质创作文案；请同时注明语言或地区
   2. 自定义文案
      请直接输入要呈现的准确文字，并注明语言或地区
   3. 无文字

   示例：1｜日语
   示例：2｜英式英语｜STILL IN BLOOM
   ```

   Automatic copy must be source-specific and native to the resolved locale. Preserve exact custom copy verbatim. Do not infer locale from appearance, clothing, scenery, filenames, metadata, or visible signs.

4. Only when `wallpaper-pack` is selected, resolve its relationship and device sizes. Ask for `1. 连贯套装` or `2. 四张独立` when missing. A linked set approves one iPad anchor by default; the other three outputs each reference the original plus that same anchor and are independently recomposed. An independent set gives every device only the original. Then ask for either the common preset—phone `1440×3200`, iPad `2048×2732`, desktop `3840×2160`, watch `1024×1024`—or labelled custom pixels. Never crop one wallpaper into another or chain derivatives.

5. Start a fresh job and reserve collision-safe output directories before generation. Use only the current invocation's explicit source or theme. Read `references/xxd-panel-018-prompt.en.md` or `references/xxd-panel-018-prompt.zh-CN.md` immediately before building the generation request.
6. Privately lock the principal subject or inseparable relationship, at least three source-specific recognition cues, the style's complete aesthetic motive, composition logic, materials, palette, typography, exact copy, and locale. The source photograph is the factual and identity anchor; do not borrow content from samples or old outputs.
7. Use **single complete-canvas generation as the default for every mode**:
   - `top-bottom`: supply the source as a high-fidelity edit/reference input and generate one finished image containing the faithful source in the upper half and the 018 transformation in the lower half.
   - `left-right`: supply the source as a high-fidelity edit/reference input and generate one finished image containing the faithful source on the left and the 018 transformation on the right.
   - `design-only`: generate the 018 transformation across the whole canvas; the source is reference-only and not visible.
   - `wallpaper-pack`: generate four separate complete canvases, one per device, following the resolved independent or linked relationship.
8. Append the complete-canvas payload below to the full local style prompt. Keep all 018-specific aesthetic and typography instructions active across the entire composition. For paired modes, ask for approximately equal regions while prioritising a coherent finished artwork: colour, light, rhythm, typography, meaning, and any cross-panel echo must feel intentionally unified.
9. Generate each distinct output as a fresh raster image job. Do not request two separate half-images, a contact sheet, a mockup, an empty reserved panel, or a code-rendered substitute.
10. Inspect the actual bitmap at full size and thumbnail size. Check, in order: whole-poster integration; 018 aesthetic fidelity; source identity and structure; visual and semantic correspondence between regions; typography and locale; mode, ratio/pixels, count, and PNG format; then approximate 50/50 geometry.
11. If a paired result fails a hard requirement, retry the **complete canvas once**, changing only the failed constraint. Use `scripts/compose_panel.py` only after that retry still fails, or when the user explicitly requires pixel-identical source preservation, the active image route cannot realise the selected canvas, the requested ratio exceeds route limits, or final lossless pixel calibration is necessary. The script is a fallback utility, never the default creative path and never an aesthetic judge.
12. Reopen every final PNG, apply the acceptance gate, and return absolute paths in source order and mode order 1→4. Wallpaper order is phone, iPad, desktop, watch.

## Complete-canvas generation payload

Append one resolved block to the style prompt for each output:

```text
OUTPUT MODE: TOP_BOTTOM | LEFT_RIGHT | DESIGN_ONLY | WALLPAPER_PACK
DEVICE PROFILE: NONE | PHONE | IPAD | DESKTOP | WATCH
FINAL CANVAS: <whole finished ratio and/or exact WIDTHxHEIGHT>
GENERATION STRATEGY: SINGLE COMPLETE CANVAS
REFERENCE ROLE: SOURCE — HIGH-FIDELITY CONTENT AND IDENTITY ANCHOR
SOURCE VISIBILITY: UPPER 50% | LEFT 50% | REFERENCE ONLY — NOT VISIBLE
LAYOUT RULE:
- Produce one finished poster in one image.
- TOP_BOTTOM keeps a faithful photographic source in the upper half and creates the transformed design in the lower half.
- LEFT_RIGHT keeps a faithful photographic source in the left half and creates the transformed design in the right half.
- DESIGN_ONLY and WALLPAPER_PACK use the whole canvas for the transformed design and show no source photograph or reserved panel.
- Keep paired regions approximately equal while unifying colour, light, rhythm, typography, and meaning.
- Do not output separate panels, a contact sheet, a mockup, or an empty placeholder.
WALLPAPER RELATIONSHIP: NONE | INDEPENDENT | LINKED
ANCHOR DEVICE: NONE | IPAD
```

For text output append:

```text
COPY MODE: REQUIRED
COPY ORIGIN: USER_EXACT | USER_DIRECTION | SOURCE_DERIVED
COPY LOCALE: <resolved locale>
COPY PAYLOAD: <the exact 018-specific title and supporting-text package resolved under the local production prompt>
COPY RULE: Render only the populated strings in COPY PAYLOAD, each exactly once. Do not rewrite, translate, spell-correct, duplicate, or add text. Use native shaping, direction, punctuation, spacing, and semantic line breaks. Preserve the 018-specific hierarchy, amount of supporting text, placement, material, and typographic role instead of applying a generic overlay.
```

For text-free output append only `COPY MODE: NONE — render no text or pseudo-text anywhere.`

## Composition fallback only

`scripts/compose_panel.py` remains available for deterministic recovery and audit. Trigger it only under step 11. When used, generate a same-aspect design asset from the full 018 prompt, preserve the source without destructive crop or stretch, and document which fallback condition applied. A direct complete-canvas success must not be split and recomposed again.

```bash
# Read-only audit after direct generation
python3 scripts/compose_panel.py --audit final.png --layout top-bottom --size WIDTHxHEIGHT

# Deterministic fallback after the complete-canvas retry has failed
python3 scripts/compose_panel.py --source photo.png --design design.png \
  --out final.png --layout top-bottom --size WIDTHxHEIGHT
```

## Output location

Save finished work under `~/Desktop/xxd/xxd-panel-018/` unless the user supplies another destination. Create the shared `~/Desktop/xxd/` wrapper, the skill root, and each task directory when needed.

- Wrap every source-and-mode result in a fresh task directory: `<source-stem>-top-bottom/`, `<source-stem>-left-right/`, `<source-stem>-design-only/`, or `<source-stem>-wallpaper-pack/`.
- A batch or multi-select creates one sibling task directory per source and selected mode. Never mix sources or modes.
- Ordinary task directories contain only one finished PNG: `<source-stem>.png`, `<source-stem>-lr.png`, or `<source-stem>-design.png`.
- The final count per source equals one file for each selected ordinary mode plus four files when `wallpaper-pack` is selected. `all` / `全部` therefore means seven final PNGs across four sibling task directories.
- A wallpaper task directory contains exactly four finished PNGs named `<source-stem>-wallpaper-phone.png`, `-ipad.png`, `-desktop.png`, and `-watch.png`; do not create device subdirectories.
- Never overwrite. Append `-2`, `-3`, and so on to a colliding task-directory name while keeping filenames unchanged.
- Keep prompts, intermediate generations, plans, audits, and source copies outside the finished task directory.

## Acceptance gate

Before accepting each result verify:

- Mode, exact pixels, explicit final-canvas ratio or pixels, split axis, seam, and output count are correct.
- Visible photography is faithful and type-free; source-hidden outputs contain no source photograph or seam.
- The simplified subject remains recognisable through at least three source-specific cues and preserves the principal action or inseparable relationship.
- One paper anchor preserves at least three source-specific cues and the principal action or inseparable relation; supporting layers never repeat the subject or form a second centre.
- A few physically plausible foreground, midground, and background layers use restrained folds, clear cuts, scale, axes, positive/negative shape, and front/back occlusion without mechanically reproducing photographic detail.
- Composition keeps a clear layer hierarchy and generous warm-ivory or pale negative space; it is not a dominant faceted sculpture, complex stack, decorative shard field, mechanical centre, or even symmetry.
- A source-derived colour-role system uses one main colour, one dark structural colour, one light layer colour, and at most a tiny source-supported accent.
- Soft diffuse light reveals matte fibre, clear cut edge, layer thickness, and soft contact shadow. Surfaces read as refined card rather than plastic, metal, clay, foam, cheap card, or smooth CG.
- There is no cartoon origami, children's craft, repeated subject, impossible floating confetti, complex piling, neon colour, complex gradient, product mockup, ecommerce staging, or templated decoration.
- Automatic copy is concise, grounded, and 018-specific; exact user wording remains verbatim. All rendered text is accurate and native to the resolved locale; text-free output contains no text or pseudo-text.
- Typography contains one short title plus two to four microtext groups with strong scale contrast and a readable path along paper edges, contours, axes, colour blocks, layers, or negative space. It never becomes a single logo, detached digital title, printed sticker, chunky foam word, pseudo-text, or illegible ornament.
- Automatic copy contains no invented year; exact user wording remains verbatim even when it contains one.
- Every wallpaper is separately recomposed, respects safe regions, contains no system UI, and is not a crop of another device result. A linked pack shares one family without drifting from the source.
- Every delivered PNG was newly generated for this invocation and lives in its fresh task directory.

## Override policy

Preserve user-specified source, mode set, output count, dimensions, target locale, copy mode, and exact finished wording. Priority is explicit text-free request > exact user wording > editable user direction > source-derived automatic copy. Exact pixels take precedence over an explicitly chosen ratio; neither may be inferred silently. A labelled wallpaper size overrides only that device.

User instructions may change subject emphasis, sparse layer map, composition axis, off-centre placement, colour roles, paper stock, depth allocation, title construction, microtype path, or copy within 018, but do not silently relax one-photo isolation, exact paired geometry, four separate wallpaper outputs, fresh-task generation, source-hidden output rules, native-language typography, or the hand-built matte-paper requirement. Leave the minimal layered paper-cut editorial aesthetic only when the user explicitly asks to leave the 018 style.

## Provenance boundary

The user's original style brief is archived at [references/018-source.md](references/018-source.md). It records the initial 3:4 top-bottom example but does not override the operative mode and explicit final-canvas selection and complete-canvas generation rules. The full local 018 prompt is the production specification. Never borrow subjects, colours, copy, or compositions from samples or previous outputs.
