# skills-vault

Хранилище скиллов и slash-команд организации **kaidem-clan**.

Назначение — **только хранение**. Чтобы применить, скопируйте нужную папку/файл
в проект:

- `skills/<source>/<skill>/` → в `.claude/skills/` или `.opencode/skills/`
- `commands/<source>/<command>.md` → в `.claude/commands/` или `.opencode/command/`

## Структура

```
skills-vault/
├── AGENTS.md                    # правила ведения хранилища
├── README.md                    # этот файл: навигация по всему содержимому
├── skills/
│   └── <source>/                # скиллы, сгруппированные по источнику
│       └── <skill-name>/        # один скилл = одна папка с SKILL.md
└── commands/
    └── <source>/                # slash-команды по источникам
        └── <command>.md         # одна команда = один .md файл
```

## Навигация по скиллам (269)

### [emilkowalski/skills](https://github.com/emilkowalski/skills) — 12 (MIT)

| Скилл | Описание |
| ----- | -------- |
| `animate` | Построение веб-анимации с нуля: цель, свойства, кривые, длительность, прерывания. Когда нужно «оживить» компонент или сделать переход. |
| `animate-expo` | Анимации в React Native/Expo: Reanimated, Gesture Handler, haptics. Для жестов, шитов, переходов экранов в Expo-приложениях. |
| `animation-vocabulary` | Словарь-обратный поиск: расплывчатое описание эффекта → точный термин («резиновый скролл iOS» → rubber-banding). |
| `apple-design` | Принципы дизайна Apple, переведённые для веба: жесты, спринги, полупрозрачные материалы, типографика, reduced-motion. |
| `ask-sonner` | Гайд по Sonner (React toast-библиотека): установка, promise-тосты, стилизация, типичные проблемы. |
| `emil-design-eng` | Философия UI-полировки Эмиля Ковальски: дизайн компонентов, анимационные решения, невидимые детали. |
| `find-animation-opportunities` | Поиск мест в коде, где анимация нужна (и отсев, где не нужна). Read-only, предлагает значения, не имплементит. |
| `improve-animations` | Аудит анимаций всей кодовой базы + приоритизированный план улучшений для других агентов. Read-only. |
| `pick-ui-library` | Выбор готовой библиотеки под фронтенд-задачу: числа, OTP-инпуты, графики, dnd, тосты, state. Запуск только вручную. |
| `prototype` | Несколько действительно разных версий UI-куска за визуальным переключателем — листаешь живьём, выбираешь лучшую. |
| `review-animations` | Ревью анимационного кода по высокому стандарту крафта (философия Ковальски). По умолчанию — флагать, а не хвалить. |
| `write-swift` | Современный Swift: value types, Swift 6 concurrency, протоколы и дженерики, производительность, Swift Testing. |

### [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills) — 5 (MIT)

| Скилл | Описание |
| ----- | -------- |
| `beautiful-article` | Превращает материалы (URL / PDF / DOCX / Markdown / скриншоты) в красивую одностраничную HTML-статью — офлайн, с сохранением 100% информации. |
| `gpt-image-2` | Генерация/редактирование картинок через GPT Image 2: 80+ шаблонов промптов (постеры, UI, продукты, инфографика, комиксы). |
| `kb-retriever` | Поиск и ответы по локальной базе знаний: индекс-навигация, grep/pdfplumber/pandas, без загрузки файлов целиком. |
| `web-design-engineer` | Сборка и редизайн полированных веб-артефактов на HTML/CSS/JS/React: страницы, дашборды, прототипы, слайды, дата-виз. |
| `web-video-presentation` | Статья/скрипт → клик-driven 16:9 веб-презентация «как видео», с опциональным синтезом озвучки (TTS). |

### [elayadesign/ai-design-skills](https://github.com/elayadesign/ai-design-skills) — 1 (MIT)

| Скилл | Описание |
| ----- | -------- |
| `landing-page-design` | Система создания конвертирующих лендингов: структура, копирайтинг, SEO + строгие визуальные правила (типографика, отступы, hero, иконки, motion). |

### [MengTo/Skills](https://github.com/MengTo/Skills) — 132 (MIT)

#### codex (19)

| Скилл | Описание |
| ----- | -------- |
| `article-prompts-to-skills` | Convert an article, tutorial, or prompt pack into focused reusable AgentSkills, one independent capability per skill, with portable instructions, example prompts… |
| `audit-reference-originality` | Audit a website or digital experience against its supplied source references for originality and plagiarism risk. Use when Codex must compare current or historical site… |
| `audit-verify-explain-grade-5` | Audit work, verify claims with concrete evidence, and explain the result in simple grade-5 language. Use when the user asks to review, audit, check, verify, explain a… |
| `browser-video-recording` | Create polished 60 fps 4:3 4K browser screen-recording style videos from Codex in-app browser captures, with browser-only crop, natural macOS cursor styling, deliberate… |
| `build-daily-inspiration-sites` | Turn a completed daily UI inspiration capture into exactly five original landing-page builds, one per separate Codex task, using Sites. Use when the user asks to turn… |
| `daily-ui-inspiration-capture` | Create a recurring daily UI inspiration capture. Use when the user asks to run, refresh, package, or validate dated UI inspiration bundles, especially for… |
| `elevenlabs-tts` | Generate ElevenLabs text-to-speech audio from scripts or inline text using local voice profiles. Use when the user asks for ElevenLabs, text-to-speech, TTS, narration… |
| `generate-reference-inspired-brand-worlds` | Generate multiple original brand campaign worlds from a supplied visual reference while controlling how close the new work feels without copying protected signature… |
| `html-to-interaction-prompts` | Convert a supplied HTML page or generated HTML reference into a screenshot-backed article containing multiple reusable interaction prompts. Use when the user provides an… |
| `implement-fog-of-war` | Implement, tune, debug, or validate soft wall-aware fog of war and gameplay perception in Three.js action games. Use for orthographic or isometric visibility masks… |
| `iterate-until-verified` | Apply a prompt-agnostic execution and verification loop to any substantial task while preserving the original request. Use when the user asks to fan out work, use… |
| `optimize-web-animations` | Profile, audit, and optimize frontend page performance with emphasis on animation work, memory-leak risks, long-session slowdowns, CSS animations, canvas/WebGL… |
| `performance-profiling` | Guide performance profiling for Apple platform apps with Instruments, Xcode diagnostics, and MetricKit. Use when investigating app hangs, stutters, high CPU, memory… |
| `publish-project-to-github` | Package a finished local project into an intentional GitHub repository, create a strong README and visual preview, push it safely, configure a public GitHub Pages URL… |
| `stitched-full-page-capture` | Capture or repair reliable full-page screenshots for lazy-loaded, scroll-animated, Framer, WebGL/canvas, or reveal-heavy web pages. Use when full-page screenshots are… |
| `video-to-superprompt` | Turn a reference video into a super detailed recreation or inspiration prompt. Use when the user provides, mentions, uploads, links, or points to a video and asks to… |
| `web-technique-to-skill` | Turn a visual or interaction technique you already built into a reusable web-design skill, by isolating the one mechanism that makes it work while reproducing its… |
| `write-like-meng-on-x` | Write, rewrite, review, or continuously refine X/Twitter posts in Meng To's current voice using his deduplicated authored-post corpus, personal and product context… |
| `x-bookmark-quote-posts` | Check a user's latest X/Twitter bookmarks and turn recent saved posts into source-backed quote-post drafts calibrated against the user's latest 100 authored posts. Use… |

#### game-development (20)

| Скилл | Описание |
| ----- | -------- |
| `author-game-levels` | Author or revise readable, flat-world Three.js game levels. Use for movement and camera routes, collision and navigation, encounter zones, landmarks, objectives… |
| `build-game-audio-feedback` | Design or implement responsive audio feedback for a Three.js or web game. Use for action sounds, combat layers, music states, spatial audio, mix priorities, mute… |
| `build-game-camera-controls` | Implement or tune Three.js game cameras. Use for isometric framing, follow behavior, orbit/zoom limits, occlusion, lock-on, camera shake, touch camera controls, and… |
| `build-game-changelog` | Design, implement, backfill, audit, and release in-game changelogs with contiguous versioning, deployment provenance, menu-state navigation, accessible toggle, close… |
| `build-game-inventory` | Build or repair game inventory, loot, equipment, tooltips, drag-and-drop, persistence, and progression systems. Use for item schemas, pickup flows, stack rules… |
| `build-game-map-editor` | Build, extend, or audit production-linked browser map editors for Three.js and isometric games. Use when Codex needs to create a private director view, derive a… |
| `build-game-monster-system` | Build, integrate, audit, or refactor rigged monsters for Three.js and web action games. Use for monster asset contracts, procedural or imported creature rigs, semantic… |
| `build-hybrid-game-assets` | Plan, create, integrate, or audit a hybrid asset pipeline for a Three.js or web game. Use when choosing among imported meshes, procedural 3D geometry, AI-generated… |
| `build-isometric-arpg` | Build or extend a playable isometric action RPG in Three.js, React, or similar web technology. Use for game-loop architecture, camera and movement, zones, combat… |
| `build-mobile-threejs-games` | Build, tune, or test a Three.js game for mobile web. Use for touch movement, action controls, target selection, touch inventory, safe areas, portrait/landscape layouts… |
| `build-rigged-game-assets` | Create, integrate, or audit production-ready rigged 3D characters and monsters with a main model, skeleton, animation library, sockets, collision contracts, separate… |
| `build-threejs-enemy-systems` | Build or refactor reusable, data-driven enemy archetype and moveset systems for Three.js action games. Use for enemy content schemas, model and rig conventions, combat… |
| `build-vesperfall-review-assets` | Build truthful Vesperfall asset-library review pairs from transparent PNG references and live Three.js, FBX, or img2threejs models. Use when adding a character, enemy… |
| `create-game-vfx` | Create readable, performance-safe Three.js game visual effects. Use for attacks, impacts, damage feedback, status effects, spell trails, particles, shaders, telegraphs… |
| `design-action-combat` | Design, implement, tune, or test readable tactical action combat for web games. Use for attack timing, guard and dodge windows, hit contact, posture, lock-on, weapons… |
| `design-game-encounters` | Design, implement, tune, or test Three.js action-game encounters. Use for arena layout, enemy composition, spawn pacing, objectives, boss phases, reward cadence… |
| `optimize-threejs-games` | Profile, diagnose, and improve Three.js or WebGL game performance without regressing gameplay. Use for frame-time drops, CPU/GPU pressure, draw calls, texture and… |
| `ship-web-games` | Package, deploy, and verify a playable Three.js or web game. Use for release builds, asset delivery, private/public deployment, production smoke tests, browser proof… |
| `test-playable-web-games` | Test a playable browser game end to end with deterministic fixtures and real browser evidence. Use for gameplay QA, regression testing, controls, accessibility… |
| `tune-enemy-ai` | Build, debug, balance, or test combat enemy AI for playable action games. Use for aggro, target selection, navigation, spacing, attack choices, telegraphs, retreats… |

#### media (2)

| Скилл | Описание |
| ----- | -------- |
| `aura-asset-images` | Use when you need high-quality stock-style images from Aura Assets (aura.build/assets) similar to Unsplash for design mockups and marketing: backgrounds, abstract… |
| `unsplash-asset-images` | Use when you need to pick high-quality Unsplash images for product/design assets (avatars, headshots, portraits, large website backgrounds, and abstract wallpapers) and… |

#### ui (3)

| Скилл | Описание |
| ----- | -------- |
| `audit-ai-design-slop` | Audit websites, apps, screenshots, mockups, and design code for harmful AI-design clichés, generic generated defaults, and established UI defects. Use when the user… |
| `design-first-ui-prompting` | Use when you need design-first, spec-driven, skimmable prompts for UI generation. Covers prompt structure, constraints, variations, typography/spacing rules, and… |
| `no-ai-design-slop` | Prevent and remove generic AI-generated design defaults, incoherent visual choices, and established UI defects while creating, revising, or reviewing websites, apps… |

#### web-design (88)

| Скилл | Описание |
| ----- | -------- |
| `add-mouse-driven-orbit` | Add restrained mouse-driven orbit and parallax depth to a Three.js hero by damping one pointer target and splitting it across camera translation, look-at, and small… |
| `add-shader-cursor-trail` | Add the Shaders WebGPU mouse effect used for the Tidal Commons hero: a white twinkling halftone cursor trail driven by ChromaFlow, masked through a DotGrid, finished… |
| `agency-grid-layout-minimal` | Create a minimal agency design system with a disciplined editorial grid, oversized typography, quiet uppercase utility labels, restrained image blocks, and subtle… |
| `ambient-section-particles` | Add a restrained particle atmosphere inside one section with configurable shapes, density, gravity, wind, sway, rotation, recycling or settling, pointer disturbance… |
| `animation-on-scroll` | Create an on-scroll animation trigger using IntersectionObserver with Tailwind-friendly animation classes and keyframes. Use when asked for scroll-reveal… |
| `animation-systems` | Use when designing or implementing product-grade web motion like Stripe, Linear, Apple, and Vercel. Covers motion principles, easing/duration defaults, choreography… |
| `atmosphere-background` | Create a dark atmospheric background with drifting vertical light folds, screen-blended glow, and a concentrated luminous corner or lower-edge bloom." --- # Atmosphere… |
| `background-grid-webgl` | Create a perspective WebGL background grid with fading lines, subtle particle haze, slow forward drift, and gentle camera parallax." --- # Background Grid WebGL Skill ##… |
| `beam-glow-states` | Create React loading, processing, selected, current, focus, and pressed states with the border-beam package's animated edge glow. Use when a card, button, input, tab… |
| `beautiful-shadows` | Apply exact Tailwind arbitrary shadow utilities for polished, layered neutral elevation. Use when compact cards, controls, panels, popovers, hero media, feature… |
| `blue-cloudy-clean-modern` | Create a clean modern design system with a luminous blue sky atmosphere, soft drifting cloud light, minimal white framing, and serene premium typography." --- # Blue… |
| `blue-laser-clean-glass-layout` | Create a clean dark glass layout system with a thin blue laser atmosphere, frosted premium shells, and polished dashboard structure." --- # Blue Laser Clean Glass Layout… |
| `book-serif-index` | Create an archival book-reader design system with serif-led pages, mono index navigation, aged paper surfaces, margin notes, and a premium catalog frame." --- # Book… |
| `bright-green-tech-system-webgl` | Create a bright-green technical design system with structured split layouts, hard-framed dark surfaces, mono utility labels, and a prominent WebGL visualization zone."… |
| `build-awwwards-quality-sites` | Art-direct and implement distinctive, motion-rich marketing, editorial, portfolio, and landing websites with original reference-inspired imagery, standout heroes, GSAP… |
| `build-interactive-particle-trail` | Build a cursor or touch particle interaction that emits by distance along the traveled segment into a recycled GPU point pool, with optional keyboard-triggered bursts.… |
| `build-threejs-scroll-worlds` | Build rich, scroll-controlled real-time Three.js experiences as one persistent 3D world whose camera, lighting, atmosphere, materials, objects, DOM story, and… |
| `build-wireframe-scan-reveal` | Reveal Three.js geometry with an expanding world-space scan whose wire cage leads the solid surface, then burns away. Use for wireframe scanning, radial mesh reveals… |
| `cinematic-gsap-lenis-motion-system` | Create premium cinematic web motion systems with GSAP, ScrollTrigger, and Lenis. Use for luxury editorial websites, creative studio portfolios, Awwwards-style… |
| `cinematic-scroll-storytelling` | Create cinematic scroll-driven landing pages with Lenis smooth scrolling, GSAP ScrollTrigger, scroll-linked progression, staggered text reveals, sticky card stacks… |
| `clean-minimal-beige-light-mode` | Create a clean minimal beige light-mode design system with warm neutral shells, quiet process grids, restrained accent color, and elegant low-contrast structure." --- #… |
| `cobejs` | Use when adding a lightweight interactive globe with cobe (canvas setup, markers, interaction, performance, integration with React/Next.js). --- # cobe.js — Lightweight… |
| `company-logos` | Use Iconify Simple Icons logos (64x64) instead of text logos." --- # Company Logos Skill ## Use When - A design needs recognizable brand marks without embedding custom… |
| `container-lines` | Add vertical container-size guide lines with mini corner squares for precise, structured web layouts. Use when asked for container lines, measured layout guides… |
| `corner-diagonals` | Apply diagonal-cut corners and chamfered edges to buttons, cards, panels, and container shells. Use when a design needs precise geometric framing, sci-fi UI surfaces… |
| `corner-lasers` | Create a corner-anchored laser composition with thin beams, a bright emitter node, bloom, and atmospheric glow or fog." --- # Corner Lasers Skill ## Use When - Create a… |
| `css-alpha-masking` | Apply CSS alpha masking with linear-gradient for horizontal or vertical edge fades (mask-image and -webkit-mask-image). Use when asked for alpha masks, fade edges, or… |
| `css-border-gradient` | Apply subtle gradient-border treatments for premium web surfaces. Use when cards, pricing panels, nav bars, modals, buttons, or hero surfaces need a refined edge… |
| `dark-blue-contrasting-clean` | Create a dark-blue clean design system with strong contrast, cobalt gradient feature blocks, crisp framed structure, and restrained premium glow." --- # Dark Blue… |
| `dark-glass-clean-layout` | Create a dark glass layout system with frosted premium shells, clean multi-column workspace structure, floating data cards, and restrained atmospheric depth." --- # Dark… |
| `dither-background` | Create a dark monochrome procedural background with enlarged square pixels and visible Bayer-style ordered dithering. Use when a page needs an atmospheric near-black… |
| `dither-laser-dark-mode` | Create a dark premium design system that combines near-black surfaces, subtle ordered-dither texture, and a thin accent-colored laser atmosphere." --- # Dither Laser… |
| `documentary-brutalist-agency` | Create or redesign creative agency, production studio, architecture, culture, and portfolio websites with billboard typography, hard black-and-white chapters, exposed… |
| `editorial-portfolio-chapters` | Create or redesign creative-studio, agency, photographer, artist, and portfolio websites where project work leads the story. Use for dark editorial shells, full-bleed… |
| `editorial-service-booking` | Create or redesign appointment-based service websites for salons, barbers, spas, wellness studios, clinics, and hospitality brands. Use for warm editorial layouts… |
| `editorial-tech` | Blend editorial magazine composition with precision product-tech detailing using asymmetrical grids, cinematic media bands, mono utility labels, and restrained accent… |
| `falling-leaves` | Build falling leaves that read as leaves, with each one tumbling on its own axis so it presents a face, thins to an edge, and opens out again, and with its sideways slip… |
| `framed-grid-layout` | Create minimal framed grid layouts with thin visible boundary lines, L-shaped corner brackets, subtle diagonal line texture, and strict section alignment. Use when asked… |
| `framed-tech-dark-border-gradient` | Create a framed dark technical design system with border-gradient shells, asymmetrical grid panels, mono utility labeling, and restrained monochrome atmosphere." --- #… |
| `funky-purple-container-tech` | Create a dark container-led technical design system with fuchsia-purple accents, layered rounded shells, crisp frame lines, and playful futuristic focal objects." --- #… |
| `glass-dark-mode-clock` | Create a dark glass design system with frosted shells, soft beam grids, circular clock-like calibration dials, and precise sci-fi instrument framing." --- # Glass Dark… |
| `glass-dark-ui` | Build dark-mode glassmorphism interfaces with readable contrast, frosted surfaces, and gradient borders using a pseudo-element mask. Use when asked for glass cards… |
| `globe-gl` | Use when implementing globe.gl (Globe.GL) for 3D globe data visualization with WebGL/ThreeJS, including setup, data layers (points, arcs, polygons, labels), and… |
| `globe-particles` | Create a globe-like 3D particle visualization with a dense luminous spherical core and thinner orbital ring or flattened disc. Use when a design needs a premium… |
| `gooey-blob-system` | Create a gooey blob system using SVG filters where multiple shapes merge into a single fluid form. Use overlapping circles combined with a Gaussian blur and color matrix… |
| `gsap` | Use when you need to add or debug professional web animations with GSAP (timelines, ScrollTrigger, stagger, transforms) in HTML/CSS/JS/React. Includes patterns for… |
| `gsap-scrolltrigger-storytelling` | Build cinematic sticky product storytelling with GSAP ScrollTrigger, progressive UI reveals, scroll-synced animation, smooth interpolation, and immersive section… |
| `high-contrast-skeuomorphic-clean` | Create a high-contrast clean skeuomorphic design system with molded dark surfaces, crisp light separation, tactile inset depth, and restrained signal accents." --- #… |
| `image-first-grid-layout` | Create an image-led grid design system with full-bleed photography, structural guide lines, anchored content blocks, and restrained technical overlays." --- # Image… |
| `landing-page` | Use when designing or rewriting a high-converting landing page (single-offer page) for SaaS/apps/services. Covers structure, layout patterns, conversion strategies… |
| `light-mode-paper-technical` | Create a light-mode technical design system with warm paper surfaces, dark outer framing, subtle diagonal texture, precise bracketed geometry, and restrained accent… |
| `liquid-metal-border` | Add and tune animated liquid-metal WebGL borders with the React `metal-fx` package. Use when buttons, icon controls, chips, tabs, cards, or selected surfaces need a… |
| `marquee-loop` | Apply seamless infinite marquee loops using duplicated items." --- # Marquee Skill ## Use When - A design needs a seamless infinite loop for logos, testimonials… |
| `masked-reveal` | Create masked staggered word reveals on scroll with GSAP ScrollTrigger. Use when headings, hero copy, section titles, or editorial text should reveal word-by-word… |
| `matterjs` | Use when implementing 2D physics interactions with Matter.js, including Engine/World setup, Render/Runner configuration, adding bodies and constraints, and… |
| `mesh-gradient-dark-blue-clean` | Create a futuristic, premium, clean dark-blue mesh-gradient design system across background rendering, hero shell, navigation, floating nodes, framed sections, CTAs, and… |
| `nested-container-clean-agency` | Create a clean agency design system built from nested containers, with an outer editorial shell, inset dark feature blocks, rounded premium cards, and restrained accent… |
| `nested-container-frames` | Create a container-in-container layout system using nested frames. Use an outer centered container with visible vertical boundary lines and corner markers. Inside, place… |
| `number-details` | Add decorative 01, 02, 03 numeric detail markers." --- # Number Details Skill ## Use When - A section needs subtle 01, 02, 03 markers for process steps, feature groups… |
| `operational-enterprise-ai` | Create or redesign enterprise AI, automation, security, and operations product pages that explain system boundaries, approvals, auditability, exceptions, and rollback.… |
| `orange-clean-paper-saas` | Create a clean paper-toned SaaS design system with warm neutrals, orange accent signals, rounded premium forms, and polished product illustration surfaces." --- # Orange… |
| `pointer-trail-emitter` | Build a cursor trail whose spacing stays constant at any hand speed, by emitting motes per unit of distance travelled rather than on a timer, so a flick draws the same… |
| `pricing-page` | Use when designing or rewriting a high-converting SaaS pricing page (structure, plan design, copywriting, SEO/AEO, FAQs, layout patterns, experiments). Includes… |
| `product-proof-saas` | Create or redesign SaaS and AI product landing pages where a real workflow, interface, or deterministic demo is the central proof. Use for pale atmospheric shells… |
| `progressive-blur` | Create a layered CSS progressive blur (top or bottom) using multiple backdrop-filter masks for depth and softness. Use when asked for “progressive blur”, “gradient blur… |
| `reveal-hover-effect` | Build cursor-following spotlight reveals that expose a second aligned image through a soft radial mask. Use for hover-to-color, before-and-after, x-ray, material… |
| `scroll-progress-timeline` | Turn any ordered process into a data-driven vertical or horizontal scroll story with a base line, progress fill, active step states, responsive collapse, semantic… |
| `scroll-scrubbed-visual-sequence` | Build reversible scroll-controlled visual transformations with a pinned or sticky stage, normalized progress, and video, image-sequence, canvas, SVG, or DOM renderers.… |
| `scroll-scrubbed-word-reveal` | Reveal marked-up text word by word as scroll progress advances, while preserving semantic inline links, emphasis, responsive line wrapping, and reduced-motion… |
| `scroll-world-storytelling` | Turn an article, case study, brand narrative, product journey, or long-form story into a cinematic scroll-driven landing page using one of three renderers: scrubbed… |
| `shaders-cursor-ripples` | Add cursor-following fluid WebGPU distortion over an existing image with the Shaders library's ImageTexture and CursorRipples components. Use when a hero, gallery, or… |
| `skeuomorphic-ui` | Create skeuomorphic web UI surfaces with layered gradients, stacked inner and outer shadows, reflective gradient borders, micro texture, and embossed text or icon… |
| `solar-duotone-bold` | Use Iconify Solar Duotone Bold icon style." --- # Solar Duotone Bold Skill ## Use When - A UI needs cohesive icons with a richer look than generic outline icons. ##… |
| `split-layout-technical` | Create a technical split-screen design system with dual panels, fine frame lines, mono metadata, quiet editorial typography, and premium inset surfaces." --- # Split… |
| `staggered-word-reveal` | Create subtle editorial word-by-word text reveal animations where each word fades and rises into place once it enters the viewport. Use for premium portfolio headlines… |
| `tailwindcss` | Use when designing/implementing UI with Tailwind CSS (layout, typography, responsive, theming, component patterns). Includes quick recipes and conventions for clean… |
| `tech-green-dark-mode-modern` | Create a modern dark-mode technical design system with matte-black surfaces, emerald signal accents, mono system labeling, framed dashboard cards, and restrained glow."… |
| `technical-wireframe-info-layout` | Create a monochrome technical wireframe design system with exploded 3D structure, connector annotations, sparse information labels, and precise dark diagnostic framing."… |
| `thinking-orbs` | Add accessible animated AI loading and agent-status indicators with the React thinking-orbs library. Use when a chat, copilot, voice, search, generation, or tool-running… |
| `threejs` | Use when building or debugging interactive 3D scenes on the web with Three.js (scene/camera/renderer, lights/materials, GLTF loading, controls, performance). Helpful for… |
| `threejs-landscape` | Build a live Three.js landscape that stays quiet behind a subject — a noise heightfield on a polar grid so resolution follows the lens, ground coloured by slope and… |
| `threejs-towers` | Generate architecture procedurally in Three.js and film it assembling — a small geometry vocabulary that builds pagodas, castles, domes and spires from parameters… |
| `threejs-weather` | Put weather into a Three.js scene that reads as weather — rain anchored inside the frustum, a storm that is the rain leaned on rather than a second system, lightning on… |
| `unicorn-studio` | Use when embedding and customizing Unicorn Studio interactive animations on the web (embed, responsive sizing, performance, layering with UI, fallbacks). --- # Unicorn… |
| `vantajs` | Use when adding animated WebGL background effects with Vanta.js (setup, parameters, resizing, performance, integration in React/Next.js). --- # Vanta.js — Animated WebGL… |
| `webgl-3d-object` | Create a real 3D WebGL object with geometric mesh depth, physically based material, directional and ambient lighting, perspective camera, subtle rotation, and floating… |
| `webgl-landing-steering` | Use when creating or refining WebGL-heavy landing pages and you need to steer toward a specific visual outcome (premium, technical, playful, cinematic) while balancing… |
| `webgl-laser` | Create a fixed full-screen WebGL laser background effect with a thin white-hot vertical core, restrained brand-colored halo, and soft smoky fog around the beam. Use only… |

### [jakubkrehel/skills](https://github.com/jakubkrehel/skills) — 11 (MIT)

| Скилл | Описание |
| ----- | -------- |
| `better-accessibility` | Helps your project comply with accessibility standards and best practices. --- # Accessibility Most accessibility is free if you use the platform. Native elements ship… |
| `better-colors` | Helps you build a color system and answer anything about color in your project. You can generate palettes, use semantic tokens, convert between formats, check contrast… |
| `better-interface` | Combines all of the `better-*` skills into a single review across accessibility, layout, writing, typography, color and UI polish. --- # Interface review This skill runs… |
| `better-layout` | Helps with grouping, alignment, reading order, progressive disclosure and other details that make a good layout. --- # Layout Position, spacing and alignment carry… |
| `better-typography` | Focuses on type scale, spacing, sizing, variable fonts, OpenType features, wrapping, truncation and other details that make typography feel great across your product.… |
| `better-ui` | Polishes and improves the UI in your project. Covers concentric border radius, optical alignment, surface depth, contextual icons, hit areas and more. --- # UI polish… |
| `better-writing` | Focuses on improving product copy in your project. --- # Interface writing Clear and brief beats clever; consistent beats varied. The best error message is the… |
| `break` | Renders a component you choose in every state and scenario on a temporary page and stress tests it. disable-model-invocation: true --- # Break This skill takes one… |
| `explain-interface` | Helps you figure out how something was built on the web. disable-model-invocation: true --- # Interface explanation This skill answers how something was built.… |
| `interface-review` | Reviews your work across multiple categories like UI, typography, layout, color, writing and accessibility and gives you a detailed analysis of the findings. --- #… |
| `variant` | Builds multiple variants of a component you're working on and helps you iterate and pick one. disable-model-invocation: true --- # Variants This skill takes one… |

### [codeswithroh/tastemaker](https://github.com/codeswithroh/tastemaker) — 1 (MIT)

| Скилл | Описание |
| ----- | -------- |
| `tastemaker` | Generate genuinely beautiful, on-brand UI instead of generic "AI slop" — use whenever the user asks to build, design, style, or improve a UI, landing page, dashboard… |

### [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills) — 107 (MIT)

#### design-ops (9)

| Скилл | Описание |
| ----- | -------- |
| `design-critique` | Facilitate a structured team critique — framing, feedback rules, and actionable outcomes. Use when running a session with people in the room. For a solo expert review… |
| `design-debt-audit` | Inventory and prioritise accumulated design inconsistencies across a product. Use when drift has built up over time. For token coverage specifically use… |
| `design-impact-reporting` | Communicate design's contribution to business and user outcomes in stakeholder language. Use when reporting results upward. For choosing the metrics in the first place… |
| `design-qa-checklist` | Build a QA checklist for verifying that a build matches the design. Use at implementation review. For the spec engineers build from, use `handoff-spec`. --- # Design QA… |
| `design-review-process` | Establish review gates — criteria, checkpoints, and approval flow. Use when work ships without consistent review. For running one individual session, use… |
| `design-sprint-plan` | Plan and facilitate a design sprint from challenge framing through prototype testing. Use when compressing discovery into days. For ongoing team cadence, use… |
| `handoff-spec` | Write the implementation handoff — measurements, behaviours, assets, states, and edge cases. Use when engineering picks up the work. For verifying the result afterwards… |
| `team-workflow` | Design the team's operating rhythm — task management, collaboration rituals, and tooling. Use when the day-to-day cadence needs structure. For a time-boxed sprint, use… |
| `version-control-strategy` | Define version control for design files, components, and libraries — branching, naming, and release. Use when file history is chaotic. For design system contribution… |

#### design-research (12)

| Скилл | Описание |
| ----- | -------- |
| `affinity-diagram` | Cluster many qualitative data points into themes and insight statements. Use when synthesising across multiple sessions or sources. For a single transcript use… |
| `card-sort-analysis` | Analyse open or closed card sort results into a proposed grouping and label set. Use after running a sort study. For turning that evidence into a full structure, use… |
| `diary-study-plan` | Design a diary study — prompts, cadence, duration, participant criteria, and analysis frame. Use when behaviour unfolds over days or weeks. For a single-session study… |
| `empathy-map` | Build a Says, Thinks, Does, Feels map for one user or segment. Use when sharing user understanding quickly. For a composite archetype with goals and behaviours use… |
| `interview-script` | Write a structured interview guide — warm-up, core exploration, and wrap-up. Use before running interviews. For analysing what comes back, use `summarize-interview`. ---… |
| `jobs-to-be-done` | Map functional, emotional, and social jobs with outcome expectations. Use when reframing decisions around motivation rather than features. For who the user is, use… |
| `journey-map` | Map one persona's end-to-end experience with stages, touchpoints, emotions, and pain points. Use when improving an existing experience. For the multi-channel ecosystem… |
| `research-repository` | Build a repository that makes findings findable, reusable, and cumulative across teams. Use when the same research keeps getting redone. For synthesising one study, use… |
| `summarize-interview` | Turn one interview transcript into themes, supporting quotes, and action items. Use immediately after a session. For synthesising many sessions at once, use… |
| `survey-design` | Design unbiased survey instruments — question wording, scales, and sampling — to measure attitudes at scale. Use when you need quantitative breadth. For behavioural… |
| `usability-test-plan` | Design a usability study — research questions, methodology, participant criteria, metrics, and facilitation guide. Use when planning the study as a whole. For writing… |
| `user-persona` | Build research-grounded personas with goals, frustrations, and behavioural patterns. Use when decisions need a consistent user reference. For one session's emotional… |

#### design-systems (11)

| Скилл | Описание |
| ----- | -------- |
| `accessibility-audit` | Audit an existing interface against WCAG, producing findings with severity ratings and remediation steps. Use when you have a design or build to assess now. Not for… |
| `component-spec` | Specify one component — props, states, variants, accessibility, and usage rules. Use when defining a library component. For the reusable doc scaffold use… |
| `design-system-governance` | Define how the system evolves — contribution model, versioning, deprecation, and change management. Use when multiple teams contribute. For driving uptake use… |
| `design-token` | Define and organise tokens for colour, spacing, type, and elevation with naming and usage rules. Use when establishing the token layer. For auditing existing usage use… |
| `documentation-template` | Generate a reusable documentation scaffold for components, patterns, or guidelines. Use when standardising how the system is documented. For the content of one… |
| `icon-system` | Specify an icon system — grid, sizing, stroke weight, naming, categories, and implementation. Use when standardising iconography. For broader illustration, use… |
| `localization-design` | Design for multiple languages, writing directions, and cultural contexts — text expansion, RTL mirroring, and locale formats. Use when shipping beyond one locale. For… |
| `motion-system` | Define motion tokens — durations, easing vocabulary, and reduced-motion handling — for consistency product-wide. Use when standardising motion across a system. For… |
| `naming-convention` | Establish naming rules for components, tokens, and layers with patterns and worked examples. Use when names are inconsistent or being set. For what the tokens actually… |
| `pattern-library` | Structure a pattern entry — problem context, solution, usage examples, and related patterns. Use when documenting a recurring solution rather than a component. For a… |
| `theming-system` | Design theming architecture — brand variants, dark mode, and high-contrast — mapped through token layers. Use when one system must serve multiple themes. For a single… |

#### designer-toolkit (7)

| Скилл | Описание |
| ----- | -------- |
| `case-study` | Craft a portfolio case study with narrative arc, process evidence, and outcomes. Use when telling a project's story to an external audience. For an internal stakeholder… |
| `design-negotiation` | Advocate for design quality, scope, and timeline with partners and leadership using evidence and shared goals. Use in the conversation itself. For the commercial… |
| `design-rationale` | Write rationale connecting decisions to user needs, business goals, and principles. Use when a decision needs defending in writing. For a live conversation, use… |
| `design-system-adoption` | Create adoption strategy and enablement materials to drive design system usage. Use when the system exists but teams ignore it. For contribution and versioning rules… |
| `design-token-audit` | Audit token usage across a product for coverage, drift, and hard-coded values. Use when tokens exist and you suspect they are being bypassed. For defining tokens in the… |
| `presentation-deck` | Structure a design presentation for a specific audience and decision. Use when presenting internally. For a portfolio narrative use `case-study`; for the written… |
| `ux-writing` | Write interface copy — microcopy, error messages, empty states, and CTAs. Use when the words are the deliverable. For content structure and ownership, use… |

#### interaction-design (22)

| Скилл | Описание |
| ----- | -------- |
| `animation-principles` | Apply animation principles — easing, staging, follow-through — to one specific UI motion. Use when tuning how an animation feels. For product-wide duration and easing… |
| `conversational-ux` | Design voice and conversational interfaces — dialog flows, error recovery, and persona. Use when the interface speaks and listens rather than being tapped. For graphical… |
| `doherty-threshold` | Apply the Doherty Threshold — keep system response under 400ms to preserve user flow. Use when diagnosing perceived slowness or setting a performance budget. For what to… |
| `error-handling-ux` | Design error prevention, detection, and recovery across a product — message content, placement, and escape routes. Use when errors span multiple flows. For validation… |
| `feedback-patterns` | Design confirmations, status updates, and notifications that tell users an action registered. Use when the system must acknowledge success or change. For waiting states… |
| `fitts-law` | Apply Fitts's Law — target acquisition time depends on size and distance. Use when sizing and positioning controls, especially for touch. For how many controls to show… |
| `form-design` | Design a form end to end — field order, grouping, validation, and completion. Use when the artifact is a form. For product-wide error strategy use `error-handling-ux`… |
| `gesture-patterns` | Design gesture interactions for touch and pointer — swipe, drag, long-press, and their discoverability. Use when input is gestural. For OS-standard gestures on iOS and… |
| `hicks-law` | Apply Hick's Law — decision time grows with the number of simultaneous choices. Use when a screen offers too many options at once. For how many items survive in memory… |
| `interfaces-that-feel` | Apply an emotional resonance lens to a UI that is technically correct but flat, prescribing changes at the copy, motion, and interaction layer. Use when a design tests… |
| `jakobs-law` | Apply Jakob's Law — users expect your product to work like the others they already use. Use when deciding whether to innovate on a familiar pattern. For OS-mandated… |
| `loading-states` | Design waiting experiences — spinners, skeletons, optimistic updates, and progressive reveal. Use when content takes time to arrive. For the latency budget itself use… |
| `micro-interaction-spec` | Specify one micro-interaction completely — trigger, rules, feedback, loops, and modes. Use when handing a single interaction to engineering. For motion craft alone use… |
| `millers-law` | Apply Miller's Law — chunk information into groups of about four to fit working memory. Use when grouping fields, menu items, or steps. For reducing the number of… |
| `navigation-patterns` | Select and design a navigation pattern — tabs, drawer, hierarchy, or hub — matched to product structure and user tasks. Use when choosing how users move between… |
| `onboarding-design` | Design the first-run experience — activation path, progressive disclosure, and time to first value. Use for a user's very first session. For the mechanics of the signup… |
| `peak-end-rule` | Apply the Peak-End Rule — a flow is remembered by its most intense moment and its last. Use when designing completion, celebration, or cancellation moments. For… |
| `search-ux` | Design search — query input, zero results, refinement, and result presentation. Use when users retrieve rather than browse. For browse structure, use… |
| `serial-position-effect` | Apply the Serial Position Effect — first and last items in a sequence are recalled best. Use when ordering menus, lists, and steps. For emphasising one item regardless… |
| `state-machine` | Model component behaviour as explicit states, events, and transitions. Use when a component has many interacting states that must be exhaustive. For the feel and… |
| `teslers-law` | Apply Tesler's Law — every process has irreducible complexity that someone must absorb. Use when deciding whether the product or the user carries it. For reducing… |
| `zeigarnik-effect` | Apply the Zeigarnik Effect — incomplete tasks stay mentally active. Use when designing progress indicators, saved drafts, and return hooks. For the emotional shape of… |

#### prototyping-testing (8)

| Скилл | Описание |
| ----- | -------- |
| `a-b-test-design` | Design an A/B experiment — hypothesis, variants, primary metric, and sample size. Use when a change can be measured quantitatively at scale. For observing behaviour… |
| `accessibility-test-plan` | Plan accessibility testing — assistive technologies, participant criteria, WCAG coverage, and session protocol. Use when scheduling testing with real AT users. Not for… |
| `click-test-plan` | Design first-click and click tests for findability and navigation. Use when testing whether people can locate something. For full task-based observation, use… |
| `heuristic-evaluation` | Run an expert review against Nielsen's heuristics and domain criteria, with severity ratings. Use when you need findings without recruiting participants. For a… |
| `prototype-strategy` | Choose prototype fidelity and method to match the design question and the decision at stake. Use before building a prototype. For what to test once it exists, use… |
| `test-scenario` | Write realistic usability task scenarios with success criteria and facilitation notes. Use when you have a study and need the tasks. For the surrounding study design… |
| `user-flow-diagram` | Diagram screen-level paths, decision points, and branch logic. Use when specifying how a feature is traversed. For the emotional end-to-end arc, use `journey-map`… |
| `wireframe-spec` | Specify wireframe layout — content priority, component placement, and annotation. Use when defining structure before visual design. For grid mechanics, use `layout-grid`… |

#### ui-design (19)

| Скилл | Описание |
| ----- | -------- |
| `aesthetic-usability` | Apply the Aesthetic-Usability Effect — polished, consistent interfaces are perceived as more usable and forgive minor friction. Use when justifying visual polish or… |
| `color-system` | Build a product colour system — tonal scales, semantic roles, and contrast compliance. Use when defining or rebuilding colour from scratch. For dark-mode adaptation use… |
| `dark-mode-design` | Adapt an existing palette to dark mode — surface elevation, contrast rebalancing, and desaturation rules. Use when you already have a light palette to translate. For… |
| `data-visualization` | Select chart types and design data encodings — marks, axes, labels, and accessible chart styling. Use when presenting data graphically. Owns chart selection and encoding… |
| `illustration-style` | Define an illustration style guide — visual language, colour usage, and application rules. Use when commissioning or standardising illustration. For icons, use… |
| `law-of-closure` | Apply the Law of Closure — the eye completes implied shapes from partial forms. Use when reducing visual weight by dropping borders or letting negative space suggest… |
| `law-of-common-region` | Apply the Law of Common Region — a shared container, background, or border groups elements regardless of spacing. Use when grouping must survive a tight layout. For… |
| `law-of-continuity` | Apply the Law of Continuity — the eye follows alignment and unbroken paths. Use when sequencing steps, aligning content, or designing carousels and timelines. For… |
| `law-of-figure-ground` | Apply the Law of Figure-Ground — establish which layer is foreground and actionable versus background. Use when designing modals, overlays, and depth. For emphasising… |
| `law-of-proximity` | Apply the Law of Proximity — spatial closeness groups elements more strongly than any other cue. Use when spacing alone must carry grouping. For grouping via containers… |
| `law-of-similarity` | Apply the Law of Similarity — shared colour, shape, or size signals that elements belong to one category. Use when signalling relationships across distance. For grouping… |
| `layout-grid` | Define a responsive grid — columns, gutters, margins, and breakpoint behaviour. Use when establishing page structure. For the spacing scale inside components use… |
| `platform-conventions` | Design to iOS and Android conventions — what each OS mandates, where they diverge, and when to unify. Use when shipping native apps. For breakpoint adaptation use… |
| `readable-measure` | Set line length and measure for comfortable reading across type sizes and breakpoints. Use when tuning body text. Covers measure only — for the full size and weight… |
| `responsive-design` | Design layouts and interactions that adapt across screen sizes and input methods. Use when one design must serve many viewports. For the underlying column grid use… |
| `spacing-system` | Create a spacing scale from a base unit with rules for when each step applies. Use when standardising padding and margins. For page-level columns and gutters, use… |
| `typography-scale` | Create a modular type scale with size, weight, and line-height relationships. Use when establishing typographic structure. For line length only use `readable-measure`… |
| `visual-hierarchy` | Establish hierarchy through size, weight, colour, spacing, and position so the eye lands in the intended order. Use when composing new work. For judging an existing… |
| `von-restorff-effect` | Apply the Von Restorff Effect — the element that differs from its neighbours is the one remembered. Use when a single action must dominate. For overall ordering rather… |

#### ux-strategy (12)

| Скилл | Описание |
| ----- | -------- |
| `business-design` | Read financials, map competitive landscapes, and argue design decisions in the language of value. Use when defending design to commercial stakeholders. For the live… |
| `competitive-analysis` | Compare UX patterns, features, strengths, and gaps across rival products. Use when you need to know what others actually do. For deliberately adopting their conventions… |
| `content-strategy` | Define what content a product needs, how it is structured, and who owns it. Use when content itself is the problem. For the words in the interface use `ux-writing`… |
| `design-brief` | Write a project brief — problem space, constraints, audience, and success criteria. Use at kickoff for one specific project. For long-horizon aspiration use… |
| `design-principles` | Define actionable principles that resolve trade-offs when the team disagrees. Use when the same decisions keep getting relitigated. For a single project's framing, use… |
| `experience-map` | Map the full ecosystem of touchpoints, channels, and relationships across a service. Use when the experience spans more than one product. For one persona's linear… |
| `information-architecture` | Design content structure, hierarchy, labelling, and the navigation model. Use when organising what exists. For the UI that exposes it use `navigation-patterns`… |
| `metrics-definition` | Define UX metrics and KPIs that connect design decisions to measurable outcomes. Use when choosing what to measure. For presenting the results afterwards, use… |
| `north-star-vision` | Articulate a long-horizon product vision that aligns teams and anchors strategy. Use when direction is contested or absent. For near-term project scope, use… |
| `opportunity-framework` | Identify, score, and prioritise design opportunities against impact and effort. Use when there are more ideas than capacity. For framing the one you choose, use… |
| `service-blueprint` | Map service delivery across frontstage actions, backstage processes, and supporting systems. Use when staff and operations are part of the experience. For the… |
| `stakeholder-alignment` | Build alignment artifacts — responsibility matrices, decision rights, and communication plans. Use when unclear ownership stalls decisions. For persuading in the moment… |

#### visual-critique (7)

| Скилл | Описание |
| ----- | -------- |
| `critique-affordance` | Critique a rendered screen's affordances — what looks clickable, state visibility, CTA clarity, and action discoverability. Use when reviewing an existing screen. For… |
| `critique-brand-consistency` | Critique a rendered screen against mood.md, voice.md, and tokens.md. Use when those brand files exist and you are checking compliance. For defining the visual language… |
| `critique-color` | Critique a rendered screen's colour — contrast ratios, palette coherence, and semantic meaning. Use when reviewing one screen. For a product-wide WCAG audit use… |
| `critique-composition` | Critique a rendered screen's composition — balance, whitespace, rhythm, and gestalt grouping. Use when a layout feels off but hierarchy is fine. For emphasis and eye… |
| `critique-information-density` | Critique a rendered screen's density — cognitive load, content prioritisation, scanning patterns, and progressive disclosure. Use when a screen feels overwhelming. For… |
| `critique-typography` | Critique a rendered screen's typography — scale usage, readability, consistency, and token compliance. Use when reviewing type on a screen. For defining the scale… |
| `critique-visual-hierarchy` | Critique a rendered screen's hierarchy — entry point, eye flow, weight distribution, and emphasis. Use when attention lands in the wrong place. For establishing… |

## Навигация по командам (32)

Все команды — из [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills), источник `commands/owl-listener/`. Команды — это готовые воркфлоу, вызывающие скиллы по цепочке; скиллы от команд не зависят.

#### design-ops

| Команда | Описание |
| ------- | -------- |
| `/handoff` | Run the full handoff workflow — specs, measurements, assets, states, and a QA checklist — and output a developer-ready package. |
| `/plan-sprint` | Run a design sprint end to end — challenge framing, schedule, exercises, and prototype test plan. |
| `/setup-workflow` | Set up a team's operating rhythm end to end — rituals, task flow, tooling, review gates, and version control. |

#### design-research

| Команда | Описание |
| ------- | -------- |
| `/discover` | Run a full user research cycle — persona creation, empathy mapping, and journey mapping for a product or feature. |
| `/interview` | Prepare an interview script or summarize an interview transcript into structured insights. |
| `/synthesize` | Synthesize research data into affinity diagrams, themes, and actionable insights. |
| `/usability-test-plan` | Run the full usability study workflow — research questions, participant criteria, tasks, metrics, and facilitation guide. |

#### design-systems

| Команда | Описание |
| ------- | -------- |
| `/audit-system` | Run a comprehensive audit of an existing design system for consistency, completeness, and accessibility. |
| `/create-component` | Scaffold a full component specification end to end — props, states, variants, accessibility, and documentation. |
| `/tokenize` | Extract tokens from an existing design or stylesheet and organise them — naming, structure, and theme mapping. |

#### designer-toolkit

| Команда | Описание |
| ------- | -------- |
| `/build-presentation` | Build a design presentation end to end — audience framing, narrative structure, and supporting rationale. |
| `/write-case-study` | Build a portfolio case study end to end — project framing, process narrative, outcomes, and visuals. |
| `/write-rationale` | Write design rationale for a set of decisions, linking each to user needs, business goals, and principles. |

#### interaction-design

| Команда | Описание |
| ------- | -------- |
| `/design-form` | Design a form end to end — structure, decision points, chunking, validation, errors, and completion. |
| `/design-interaction` | Design a complete interaction flow for a feature or component. |
| `/design-onboarding` | Design a first-run experience end to end — activation path, progressive disclosure, and time to first value. |
| `/error-flow` | Design an error flow end to end — prevention, detection, messaging, and recovery paths. |
| `/map-states` | Model a component's states and transitions end to end — states, events, guards, and edge cases. |

#### prototyping-testing

| Команда | Описание |
| ------- | -------- |
| `/evaluate` | Run a heuristic evaluation end to end — expert review against heuristics with severity ratings and recommended fixes. |
| `/experiment` | Design an A/B experiment end to end — hypothesis, variants, primary metric, and sample size. |
| `/prototype-plan` | Create a prototyping and testing plan for a design initiative. |
| `/test-plan` | Choose a testing method and build the plan around it — method selection, task scenarios, click tests, and accessibility coverage. |

#### ui-design

| Команда | Описание |
| ------- | -------- |
| `/color-palette` | Run the full colour workflow — tonal scales, semantic mapping, contrast checks, dark mode, and chart colours — and output a documented palette. |
| `/design-screen` | Design a complete screen layout from a description or requirements. |
| `/platform-audit` | Audit a design for iOS and Android convention compliance — navigation, controls, typography, and platform-specific gaps. |
| `/responsive-audit` | Audit a design's responsive behaviour across breakpoints — layout, touch targets, and content reflow. |
| `/type-system` | Build a typography system end to end — scale, weights, line heights, measure, and responsive behaviour. |

#### ux-strategy

| Команда | Описание |
| ------- | -------- |
| `/benchmark` | Run a competitive benchmark across a set of products — pattern comparison, gap analysis, and opportunity callouts. |
| `/frame-problem` | Structure an ambiguous design challenge into a clear problem definition with constraints and criteria. |
| `/strategize` | Develop a complete UX strategy for a product or feature area. |

#### visual-critique

| Команда | Описание |
| ------- | -------- |
| `/critique-screen` | Run all seven visual critiques on a screen and output a prioritised fix list. |
| `/critique-ux` | Run a focused UX critique on a screen — affordances, information density, and hierarchy — and output a prioritised fix list. |

> Примечание: `test-plan.md` существовал в двух категориях (design-research и prototyping-testing) с разным содержимым. Версия design-research переименована в `usability-test-plan.md`, версия prototyping-testing оставлена как `test-plan.md`.

## Правила

1. Один скилл — одна папка `skills/<source>/<skill-name>/` с `SKILL.md` внутри;
   все файлы скилла (скрипты, шаблоны, референсы) лежат только внутри его папки.
2. Команды хранятся в `commands/<source>/<command>.md`.
3. При добавлении нового скилла или команды **обязательно** добавьте строку
   в соответствующую секцию навигации выше (см. [AGENTS.md](AGENTS.md)).
4. Новые скиллы от уже известного источника добавляйте в его секцию;
   новый источник — новая секция `###` со ссылкой на репозиторий и лицензией.
5. Перед импортом любого стороннего материала **обязательно** проверьте
   лицензию источника — репозиторий публичный (см. [AGENTS.md](AGENTS.md),
   «Проверка лицензии перед импортом»).
6. При переименовании или удалении синхронизируйте таблицу с содержимым.
7. Не храните в этом репозитории секреты, токены и ключи.

Все импортированные коллекции распространяются под лицензией MIT.
