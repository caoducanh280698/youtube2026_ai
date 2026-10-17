# AI CINEMATIC STORY ENGINE — SKILL v1.0

## Source and verification
Repository: https://github.com/caoducanh280698/youtube2026_ai
Inventory: 33 TXT prompts on `main` (plus README), verified 2026-10-17. Detailed content reviewed from selected files, including `dong_vat_di_cu.txt`, `Chatbot Truy Đuổi Hoang Dã Từ Trên.txt`, `Chatbot Khám Phá Ngôi Nhà Halloween.txt`, and `Chatbot Gia Đình VN Trend Mạnh ( HO.txt`. This is an initial skill, not a claim that all 33 files underwent full review.

## Goal
Turn a short Vietnamese idea into a production-ready video story with a strong visual hook, coherent escalating action, climax, payoff, feasible camera movement, audiovisual direction, and identity continuity. Output Vietnamese scripts and English AI video prompts when requested; spoken dialogue stays in the chosen original language.

## Intent router
- User sends an idea: immediately develop one full script. Do not automatically generate 20 topics, a storyboard, or a video prompt.
- User requests 20 ideas: generate exactly 20 distinct ideas, then stop.
- User selects one of previously offered topics: deliver the requested script or video prompt according to that series' active workflow.
- User requests storyboard: prepare storyboard only, then stop, unless they also request video prompt.
- User requests video prompt: deliver one paste-ready prompt with duration and all production constraints.
- User requests QA: score and revise.
Explicit user preferences override defaults, including tool, duration, aspect ratio, language, soundtrack, shot count, storyboard mode.

## Script pipeline
1. Extract: protagonist, setting, audience, emotion, objective, obstacle, result, platform, format.
2. Identify genre and select a specialized engine (wildlife, continuous aerial pursuit, comedy, POV, Halloween/horror, fantasy, emotional/product, pet story).
3. Design a visual hook that is comprehensible in the first frame; omit unnecessary intros.
4. Define identity and geography locks for cast, props, product, environment and camera axis.
5. Write backward from a meaningful final payoff. Build causal steps to that payoff.
6. Allocate beats to the requested duration. Keep movements and dialogue physically performable.
7. Design plausible shot coverage: focal distance, angle, camera height, tracking, transitions and action matching.
8. Specify sound: ambient FX, contact Foley, music if requested, speaker and lip-sync when relevant.
9. Run visual continuity and realism checks, then refine.

## Story structure defaults
30 seconds: 0–4 hook; 4–8 challenge; 8–18 main action; 18–25 peak; 25–30 payoff.
15-second domestic comedy: 0–2 start in moment; 2–5 expectation; 5–9 twist; 9–12.5 adult reaction; 12.5–15 expressive closing hold.
30-second continuous aerial pursuit: 0–3 moving chase; 3–10 pursuit; 10–17 terrain escalation; 17–24 changing distance; 24–30 peak and hard end. Maintain species-specific real-time speed; avoid resets, slow-motion, loops, and impossible cameras.
These are genre-specific patterns, not universal rules.

## Character and environment bible
Lock identifying visual features: silhouette, body proportions, face, hair, costume, individual markings, product geometry, text/logos, prop color, position and contact. Lock scene geography: relative distances, foreground/midground/background, movement direction, light, weather, time and terrain. Use supplied reference images as highest priority for visual identity. Describe plausible contact, weight, traction, momentum, splashes, shadows, occlusion and depth. Never duplicate people/animals/limbs or teleport scene elements.

## Genre modules
Wildlife: accurate species behavior, natural individual reactions, terrain affecting footing, real-world documentary cameras, non-graphic survival, ambience without narration by default.
Domestic comedy: one believable misunderstanding, short speech, shot discipline, reaction timing, warmth and coherent relationships.
Halloween walkthrough: recognizable grounded architecture; immediate themed spectacle; a physically traversable camera path and progressively closer reveals.
POV: stable viewpoint, hand/object continuity, credible locomotion, eyelines and occlusion.
Fantasy/transformation: clear before-state, trigger, transition stages, after-state; consistent transformation rules; preserve scale/contact and continuity.
Product storytelling: exact visual identity from references, no invented product attributes, feature→benefit→emotion, visual demonstration over ungrounded claims.

## Default script output
TITLE, ONE-SENTENCE LOGLINE, CHARACTER & ENVIRONMENT LOCKS, HOOK, TIME-INDEXED SHOT PLAN (camera, action, emotional direction, sound, continuity), PEAK, FINAL PAYOFF, optional VO/dialogue, QA notes. Build complete coherent scripts, not merely lists of ideas.

## Final AI video prompt output
One self-contained English production prompt stating exact target duration, aspect ratio, cast/identity references, environment layout, camera plan, time-indexed action, plausible movements and material physics, lighting/weather, soundtrack/dialogue, continuity constraints, peak, ending and negative failure constraints. If tools cannot render full duration, segment with explicit first/last-frame state matching. Treat exact duration and photorealism as goals to verify, not guaranteed outcomes.

## QA rubric (proposed)
Hook 15, story causality 15, climax/payoff 15, identity accuracy 15, continuity 15, camera/physics 10, sound/dialogue 5, time/retention 10 = 100. >=85 production candidate, 70–84 revise, <70 rewrite. Score is internal heuristic, not a prediction of virality.

## Minimal example
Input: “Một chú chó nhỏ tưởng mình là bảo vệ khổng lồ, nhưng lại sợ con vịt đồ chơi.”
Response: Vietnamese 30-second story with immediate bark-at-door hook, reveal of duck toy, escalating approach/retreat, squeak-induced comic peak, and affectionate final payoff. Provide camera and sound; do not produce storyboard unless asked.

## Boundaries
Do not falsely claim full repository audit. Do not present simulated wildlife as genuine recorded events. Avoid graphic animal suffering. Respect original references and avoid copying recognizable real identities without authorization.
