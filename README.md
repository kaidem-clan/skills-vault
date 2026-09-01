# skills-vault

Хранилище скиллов (агентных навыков) организации **kaidem-clan**.

Назначение — **только хранение**. Чтобы применить скилл, скопируйте нужную папку
из этого репозитория в проект (например, в `.opencode/skills/` или `.claude/skills/`).

## Структура

```
skills-vault/
└── <skill-name>/      # один скилл = одна папка
    └── SKILL.md       # описание и инструкции скилла
```

## Навигация по скиллам

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
| `beautiful-article` | Превращает материалы (URL / PDF / DOCX / Markdown / скриншоты) в красивую одностраничную HTML-статью — офлайн, с сохранением 100% информации. |
| `gpt-image-2` | Генерация/редактирование картинок через GPT Image 2: 80+ шаблонов промптов (постеры, UI, продукты, инфографика, комиксы). |
| `kb-retriever` | Поиск и ответы по локальной базе знаний: индекс-навигация, grep/pdfplumber/pandas, без загрузки файлов целиком. |
| `web-design-engineer` | Сборка и редизайн полированных веб-артефактов на HTML/CSS/JS/React: страницы, дашборды, прототипы, слайды, дата-виз. |
| `web-video-presentation` | Статья/скрипт → клик-driven 16:9 веб-презентация «как видео», с опциональным синтезом озвучки (TTS). |
| `landing-page-design` | Система создания конвертирующих лендингов: структура, копирайтинг, SEO + строгие визуальные правила (типографика, отступы, hero, иконки, motion). |

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
| `aura-asset-images` | Use when you need high-quality stock-style images from Aura Assets (aura.build/assets) similar to Unsplash for design mockups and marketing: backgrounds, abstract… |
| `unsplash-asset-images` | Use when you need to pick high-quality Unsplash images for product/design assets (avatars, headshots, portraits, large website backgrounds, and abstract wallpapers) and… |
| `audit-ai-design-slop` | Audit websites, apps, screenshots, mockups, and design code for harmful AI-design clichés, generic generated defaults, and established UI defects. Use when the user… |
| `design-first-ui-prompting` | Use when you need design-first, spec-driven, skimmable prompts for UI generation. Covers prompt structure, constraints, variations, typography/spacing rules, and… |
| `no-ai-design-slop` | Prevent and remove generic AI-generated design defaults, incoherent visual choices, and established UI defects while creating, revising, or reviewing websites, apps… |
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
> Источник скиллов `animate`…`write-swift`: [emilkowalski/skills](https://github.com/emilkowalski/skills) (лицензия MIT).
> Источник скиллов `beautiful-article`…`web-video-presentation`: [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills) (лицензия MIT).
> Источник скилла `landing-page-design`: [elayadesign/ai-design-skills](https://github.com/elayadesign/ai-design-skills) (лицензия MIT).
> Источник скиллов `article-prompts-to-skills`…`webgl-laser` (категории codex / game-development / media / ui / web-design): [MengTo/Skills](https://github.com/MengTo/Skills) (лицензия MIT).

## Правила

1. Один скилл — одна папка в корне репозитория, внутри обязателен `SKILL.md`.
2. При добавлении нового скилла **обязательно** добавьте его в таблицу
   «Навигация по скиллам» выше (см. [AGENTS.md](AGENTS.md)).
3. Скиллы должны быть самодостаточными: без ссылок на файлы вне своей папки.
4. Не храните в этом репозитории секреты, токены и ключи.
