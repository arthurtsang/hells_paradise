# *Hell’s Paradise* historical context — NotebookLM & video series outline

This file **does not replace** `Hell's Paradise's Historical Context.md`. Use it to **split one long source** into **shorter generation passes** in NotebookLM (or any tool that ingests text and outputs audio/video).

## How to use this with NotebookLM

1. **Upload** `Hell's Paradise's Historical Context.md` as your primary source (or keep it in the same notebook).
2. **Add this outline** as a second source so the model knows your intended **episode boundaries**.
3. For each video below, start a **new chat** or **new generation** and paste:
   - the **Video prompt** (one fenced block per episode: main instructions, then **MANGA / ANIME ANCHORS**, then **SERIES CONTINUITY** where that footer applies), and optionally
   - “**Limit scope to:**” + the **Source span** line so the model does not pull the whole glossary every time.
4. If the tool still drifts too wide, **duplicate** the main doc into smaller files by copying only the listed headings into `Part-01-….md`, etc., and upload **one part per notebook** for stricter isolation.
5. **Continuity:** Generators often **re-open** with a long block on **秦始皇** and **徐福東渡** even when the episode is about talismans or the *Changes*. **Episodes 04–17 (incl. optional 17):** the **Series continuity footer** is **inside** each **Video prompt**—paste the **entire** fenced block. For **Episode 03** or ad hoc use, copy the standalone footer in [Continuity: avoid repeating earlier episodes](#continuity-avoid-repeating-earlier-episodes).
6. If repetition persists, upload an excerpt that **omits** `### 1.` (Xu Fu voyages) for later episodes, and add one hand-written line: “Xu Fu expeditions: see Episode 02 only.”

**Tip:** Treat **Glossary** (especially the **cross-reference index**) and **References** as a **bonus episode** or appendix cards—not the main narrative.

**Episodes 01–03 (already produced):** The **Source span** and **Goal** are unchanged; each **Video prompt** is one **fenced block** that now includes **Manga tie-in** inside it (single copy-paste). **Optionally** add the standalone **Series continuity footer** from [Continuity](#continuity-avoid-repeating-earlier-episodes) when regenerating **Episode 03** only. **Episodes 04–17:** Each **Video prompt** is one **fenced block**: **main instructions → Manga tie-in → Series continuity footer** (single copy-paste).

**What changed vs older outlines:** the parent doc now includes **Traditional Chinese + Japanese** glosses, **Kotaku’s three rings** (瀛州 / 方丈 / 蓬莱), **道士**, **§3a talismans** (**太上老君急急如律令**), a full **易經 / 周易 / 十翼** divination block, **Tensen honorific titles**, **Appendix D** (Hong Kong epilogue **雙龍過江** / **雙龍之道**), an expanded **Appendix C** (**Banko** / **盤古** + Taoist **元始天王** note), and **Appendix E** (**辟餌服生の斎** vs **服餌辟穀**—optional character-play echo, **not** author-confirmed). Episode numbers below match those additions. **Episodes 01–17:** **Manga tie-in** and (for **04–17**) **Series continuity** are **inside** the same **Video prompt** fence—no separate **Manga tie-in** section below each episode.

---

## Continuity: avoid repeating earlier episodes

NotebookLM and similar tools often **default to a “textbook opening”**: unification under Qin, the First Emperor’s fear of death, then **Xu Fu sent east**—even when your prompt is about **符**, **易經**, or **neidan**. That wastes time and **duplicates Episode 02** (and the one-line teasers in **01**).

### Which episode “owns” which history

| Topic | Primary episode | Later episodes should… |
|--------|-----------------|-------------------------|
| Two Xu Fu expeditions, *Shiji* / Sima Qian, fleets, youths, sea monsters, **Penglai / Fangzhang / Yingzhou** as *history-myth* | **02** | Use **at most one short sentence** of recap, or none |
| Qin court **fangshi**, **waidan** in context, **Kotaku** rings, **道士**, manga “catalyst” (Xu Fu **as plot premise**, not voyage play-by-play) | **03** | Assume **03** for waidan-to-fiction; **do not** replay the two-voyage timeline |
| Philosophical vs religious Taoism at Qin unification, **Tensen** as adepts | **04** | No expedition narrative |
| Cinnabar, mercury, poisoning, **tomb** archaeology, Terracotta parallel | **05** | May name the emperor **only** as needed for poison/tomb; **no** second full “Sima Qian expedition” block |
| Taiji / *Changes* / Five Phases / talismans / neidan / appendices | **08–16**, **07** | Treat Qin–Xu Fu as **already taught** unless one clause ties this beat to the island |

### Series continuity footer (reference — **embedded in Episodes 04–17** prompts)

The following is **duplicated inside** each **Episode 04–17** (including **optional 17**) `Video prompt` so you can **copy-paste one block** with **manga anchors** already included. Use this standalone version only for **Episode 03** or **custom instructions**:

```text
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## Episode map (quick reference)

| # | Working title | Rough length |
|---|----------------|--------------|
| 01 | What this project is (繁體中文 + Japanese + *Jyutping* for viewers new to China or Taoism) | 4–7 min |
| 02 | Xu Fu and the voyages for immortal islands | 8–14 min |
| 03 | Court alchemists, **Kotaku’s three rings**, Dōshi, and how the manga twists history | 8–14 min |
| 04 | Taoism in the Qin era and “heavenly immortals” in the story | 6–10 min |
| 05 | Mercury elixirs and the emperor’s tomb | 8–12 min |
| 06 | Laozi and the *Dao De Jing* (philosophy vs later mysticism) | 6–10 min |
| 07 | **Taoist talismans (符)** and **太上老君急急如律令** (§3a) | 7–12 min |
| 08 | Taiji, *Book of Changes* intro, trigrams, Zhang Sanfeng note | 8–12 min |
| 09 | **易經 / 周易**, lost **Yi**, **十翼** (繫辭・文言・說卦・序卦・雜卦), and fortune-telling | 10–15 min |
| 10 | Five Elements, Zou Yan, cycles, and *Hell’s Paradise* hooks | 8–12 min |
| 11 | Tao (タオ), Tan, qi, rituals, and feng shui in the plot | 8–14 min |
| 12 | Lord Tensen: flowers, **honorific titles**, and the five training methods | 12–16 min |
| 13 | Kishikai vs corpse liberation; real Chinese “five methods” sources | 8–12 min |
| 14 | External alchemy rituals vs the manga’s “factory island” (incl. **符** in the chamber) | 8–14 min |
| 15 | Internal alchemy, tanden, zhoutian, and wuxia tropes | 10–16 min |
| 16 | Conclusion, **Appendices A–E**, references, and where to read next | 10–16 min |
| **17 (opt.)** | **Glossary sprint** (incl. EN · 繁 · JP cross-reference rows) | shorts / flashcards |

---

## 01 — Viewer orientation: *Hell’s Paradise*, China, and how this doc works

**Source span:** Title block, **“For English readers”** callout, first long paragraph of the introduction (through “twisted into suffering…”), and the **compile paragraph** that lists what the full document covers (through **Appendix E** / **§3a** / glossary mention—stop before `### 1.`).

**Goal:** A self-contained **trailer-level** explanation: what the series is, why **Qin China** and **Taoist immortality lore** matter, what **Kotaku / Shinsenkyō** evokes, and how **English + Traditional Chinese + Cantonese *Jyutping* + Japanese** (manga spellings, [official glossary](https://www.jigokuraku.com/glossary/)) appear in the parent document—**without** diving into Xu Fu yet.

### Video prompt (paste into NotebookLM / video tool)

```text
Create an educational overview video (voiceover + on-screen text) for viewers who know *Hell’s Paradise* / *Jigokuraku* but have little background in Chinese history or Taoism.

Structure:
1) One sentence: what *Hell’s Paradise* is (Japanese manga/anime borrowing Chinese Qin-era immortality quests and Taoist imagery).
2) Plain English: who the First Emperor of Qin was in one line; who Xu Fu is in one line (no detail yet).
3) Explain “islands of the immortals” and why Shinsenkyō / Kotaku mirrors Penglai-style paradise myth—then the doc’s theme: paradise twisted by obsession.
4) Explain the document’s reading convention: English first, then **Traditional Chinese (繁體)** characters, then Cantonese Jyutping in italics; add Japanese where the manga uses it (e.g. 天仙 *tensen*, タオ, こたく).
5) One line: the written doc also covers **talismans**, **Change**-style divination, **appendices** (A–E: e.g. Hong Kong epilogue, optional **辟餌服生の斎** / **服餌辟穀** echo)—episodes later unpack each layer.
6) End with: “The next episodes unpack history, cosmology, alchemy, and how the story rewrites each layer.”

Tone: calm, curious, non-judgmental. Avoid spoiling plot beats beyond “immortality quest goes wrong.” Visuals: abstract maps, waves, island silhouettes, old brush textures—no copyrighted character art unless the user supplies it.

---
MANGA / ANIME ANCHORS:
- **Frequency:** At least **every 90–120 seconds**, explicitly tie the doc’s history/Taoism setup to *Hell’s Paradise* / *Jigokuraku*—by **scene type**, **character**, or **[official glossary](https://www.jigokuraku.com/glossary/)** entry name (Japanese ok).
- **Where the story introduces the premise (name these beats):** Opening **death-row / execution** context and **幕府** mission to find **仙薬**; **神仙郷** *Shinsenkyō* and **こたく** *Kotaku* as the island names viewers hear; **画眉丸** and **山田浅右衛門 佐切** as the pair who carry the “China + Tao” vocabulary into the plot; title **地獄楽** as the frame (“paradise” vs “hell”).
- **Dive prompts:** When you mention **Penglai-style** isles, say how the **manga** labels them (**瀛州 / 方丈 / 蓬莱** in materials; JP readings **Eishū, Hōjō, Hōrai** from the glossary)—even if Episode 01 only **teases** rings, name them so viewers connect to later episodes.
- **Avoid:** Inventing **chapter numbers** unless you verify them; prefer **“early episodes,” “briefing scenes,” “landing arc.”**
- **On-screen text:** When a term appears, show **manga-style spellings** once: e.g. **天仙** *tensen*, **タオ**, **こたく**—then return to the doc’s 繁體 + *Jyutping* convention.
```

---

## 02 — Xu Fu: two expeditions, Sima Qian, and the eastern immortal isles

**Source span:** `### 1.` through the end of the **second expedition** subsection (including **Penglai / Fangzhang / Yingzhou**, fleets, **Anqi Sheng**, Langya)—stop before `#### Context in Taoist mysticism`.

**Goal:** **History-first** episode: primary source (*Records of the Grand Historian*), dates, what was sent east, why the court believed in **fangshi**, and why Xu Fu’s disappearance matters culturally.

### Video prompt

```text
Educational video: Xu Fu’s elixir expeditions under the First Emperor of Qin (3rd c. BCE). Audience: English speakers, no prior Chinese history required.

Cover in order:
- Sima Qian as historian; *Records of the Grand Historian* as the main textual anchor.
- First expedition (219 BCE): three divine islands, immortals, elixir, purification, youths sent east; sea creatures / excuse for return.
- Second expedition (~210 BCE): scale (crafts, grain, ships), Langya, then disappearance; brief mention of legends (Japan / “vast plain and marshes”).
- Name the three isles: Penglai, Fangzhang, Yingzhou—what they meant in imagination (not geography lessons).
- Close with “unsolved mystery bridging fact and legend.”

Use maps and ships as generic visuals; label proper nouns on screen with Chinese characters + Jyutping once each. No gore.

---
MANGA / ANIME ANCHORS:
- **Frequency:** Each major history beat (expedition, islands, Sima Qian) should include **one line** on how *Jigokuraku* **reuses or inverts** it—via **徐福** / **Jofuku**, **蓮** *Rien*, or **island lore** in dialogue/flashback.
- **Where the manga names Xu Fu / the quest:** Cite **official glossary** **[徐福](https://www.jigokuraku.com/glossary/)** (Japanese text); note that the work treats him as the **historical catalyst** who reached the island **before** the main plot. When you name **Penglai, Fangzhang, Yingzhou**, connect to **in-story** echoes (**蓬莱 / 方丈 / 瀛** naming) as **preview** of Episode 03’s ring structure—without repeating 03’s full table.
- **Dive prompts:** Contrast **《史記》/ Sima Qian** as **real historiography** with **what characters believe** in-world (immortals, **仙薬**); optional one beat on **岩隠れ** / Gabimaru’s village rumor of **不死** tying the **Qin immortality obsession** to **Japanese** plot.
- **Avoid** fabricating **panel citations**; say **“flashback,” “exposition,” “glossary wording”** when sourcing manga-side claims.
```

---

## 03 — External alchemy in context + **Kotaku’s rings** + *Hell’s Paradise* as historical parody

**Source span:** `#### Context in Taoist mysticism…` through `#### *Hell’s Paradise*: Xu Fu as the historical catalyst` (includes **#### *Hell’s Paradise*: Kotaku’s three nested regions**—瀛州 / 方丈 / 蓬莱, **道士**, waidan, peaches, then manga: Rien, Flower Tao, Lord Tensen, Tan, “factory of suffering”).

**Goal:** Bridge **Han-era** development of external alchemy vs **Qin-era** practice; explain how the **three island rings** **rename** classical **Yingzhou / Fangzhang / Penglai**; **道士** as a Japanese **lexical borrow**; then **one clear paragraph** on how the manga maps **waidan** → **Tan** and **Penglai** → **horror**.

### Video prompt

```text
Video bridging real Taoist external alchemy (waidan) in late Warring States / Qin with the fictional island in *Hell’s Paradise*.

Do **not** replay the two Xu Fu expeditions or Sima Qian scene-by-scene—that is Episode **02**. At most **one** bridging sentence (“After the court had already chased immortality east…”), then continue.

Explain:
- fangshi: court adepts—alchemists, ritualists—not “wizards” in a fantasy-game sense.
- What waidan aimed to do (elixir, minerals, ritual purity) vs when formal texts flourished (Western Han onward, Taiqing later).
- Kotaku’s three nested regions (official glossary): 瀛州 / 方丈 / 蓬莱 as echoes of the classical eastern peaks—outer / middle / inner.
- 道士 (dōshi): Chinese “Taoist adept” word reused for Tensen disciples in-fiction.
- Penglai myth cluster: eternal life, peaches, immortals—then the manga inversion: artificial Tensen, Tan as harvested life-force, island as corrupted paradise.

Tone: analytical, respectful to religious history; clear “fiction vs history” signposting every 60–90 seconds. Visuals: cauldrons, cinnabar red, island mist turning sinister (stylized, not violent).

---
MANGA / ANIME ANCHORS:
- **Frequency:** **Every subsection** (fangshi/waidan, three rings, 道士, Tan inversion) must open or close with a **manga-native** pointer: **[official glossary](https://www.jigokuraku.com/glossary/)** Japanese headword, **romanized island band** (Eishū / Hōjō / Hōrai), or **plot mechanism** (Flower Tao, **丹** *tan*, Tensen).
- **Where this lives in the story:** **Landing on Kotaku** through **Hōrai**-ward travel; **道士** rank ladder and **天仙** *tensen* as **fiction-specific** hierarchy; **蓮** *Rien* / **徐福** backstory as the **“Xu Fu catalyst”** paragraph in the parent doc—say explicitly that viewers meet these **after** the Edo setup (Episode 01) and **alongside** island exploration (not only history lectures).
- **Dive prompts:** Walk through the **three nested regions** table **with glossary readings**: **瀛州** *Eishū*, **方丈** *Hōjō*, **蓬莱** *Hōrai*—and **one sentence each** on **what lives there** (門神, 竈神, **Lord Tensen**) per glossary blurbs. For **waidan → Tan**, name **外丹花** / arborification as the **manga’s** “factory” mirror.
- **Optional precision:** If the tool allows, add **“Compare: parent doc §1 table vs glossary 瀛州/方丈/蓬莱 entries”** so the script does not drift from **authorized** spellings.
```

---

## 04 — Taoism in the Qin era and the Lord Tensen as “adepti”

**Source span:** `### 1a. Taoism…` entire section.

**Goal:** **Philosophical Taoism (道家)** vs **emerging religious Taoism (道教)** in plain English; **qi**, **Five Elements**, **fangshi**; why **Tensen** parallel **sennin / 仙** language (incl. **天仙** *tensen*).

### Video prompt

```text
Explain early Taoism at the time of Qin unification for a general audience.

Do **not** retell Xu Fu’s voyages or “youths sent east”—Episode **02** owns that. If you mention fangshi, do it as a **role** (court adepts), not as a voyage recap.

Sections:
1) Two strands: philosophical (Laozi/Zhuangzi, harmony with the Way) vs religious/immortality-seeking (later formalization, but roots already present).
2) Practical court layer: fangshi and external alchemy patronage.
3) Pivot to *Hell’s Paradise*: Lord Tensen as “heavenly immortals” / mountain immortals (仙人) and Japanese 天仙 *tensen*; why “adeptus” is a fair gloss; powers listed briefly (regeneration, elements, yin-yang switching).

Avoid deep cosmology here—that is the next block of episodes. On-screen: simple diagram yin/yang split once. Characters + Jyutping for 道家, 道教, 方士, 天仙.

---
MANGA / ANIME ANCHORS:
- **Glossary:** [天仙](https://www.jigokuraku.com/glossary/) *tensen*, **道士** *dōshi*, **氣** *ki*; tie **Lord Tensen** to **仙人** / *sennin* language the cast uses.
- **Where in the story:** Island **rulers** introduced as **天仙**; disciples as **道士**; contrast **道家 / 道教** doc labels with **what characters call each other** (e.g. Tensen as “immortals”).
- **Dive:** For each of **philosophical vs religious** Taoism, give **one manga-side example** (e.g. Flower Tao / training as “religious” layer; “Way” talk as philosophical echo)—without long plot recap.
- **Frequency:** At least **three** explicit **glossary or on-screen term** callbacks (Japanese/繁體) in the episode.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 05 — Mercury, cinnabar, elixir poisoning, and the First Emperor’s tomb

**Source span:** `### 2.` entire (mercury/cinnabar, poisoning narrative, archaeology, connection to manga, broader cautionary context, Terracotta Army image mention as optional B-roll credit).

**Goal:** **Science + history** episode: chronic mercury, tomb rivers of mercury, soil evidence, irony vs Xu Fu plot in manga.

### Video prompt

```text
Documentary-style episode: did mercury “immortality” elixirs kill the First Emperor of Qin? Tie alchemy to toxicology and archaeology.

Episode **02** already told the Xu Fu expedition story—do **not** reopen the two-voyage narrative or Sima Qian’s fleet beats here. You may name Xu Fu **once** if needed for “court still chasing elixirs,” then focus on **cinnabar → mercury → body → tomb**.

Outline:
- Cinnabar → mercury; why alchemists valued “liquid silver” symbolically.
- Chronic poisoning symptoms tied cautiously to historical character (no fake diagnosis tone—use “matches patterns”).
- Tomb description (Sima Qian) + modern mercury anomalies near the mound; what is still sealed.
- Short parallel: manga’s Tan / paradise poisoned vs historical elixir poisoning.
- Closing: Terracotta Army as a different kind of “immortality” (political legacy).

Use labeled diagrams (Hg symbol), cross-section schematic of tomb—not literal excavation footage unless licensed. Neutral, educational.

---
MANGA / ANIME ANCHORS:
- **Parallel beat:** When discussing **mercury / elixir poisoning**, name **丹** *tan* and **仙薬** *sen'yaku* from the [glossary](https://www.jigokuraku.com/glossary/) as the **story’s** “elixir” mirror—**dark inversion** of historical pills.
- **Where in the story:** Characters link **immortality** to the **island** and **Xu Fu** lore; **do not** re-narrate island arcs—**one clause** max tying tomb **irony** (“seeking life, taking poison”) to **Tan** harvesting theme.
- **Dive:** Optional single line on **岩隠れ** chief **immortality rumor** vs **archaeological** mercury (fact vs in-world gossip).
- **Frequency:** **Two** glossary or manga vocabulary touches plus the **historical** core.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 06 — Laozi and the *Dao De Jing*: what the classic does *not* say

**Source span:** `### 3.` entire.

**Goal:** Prevent viewers from flattening all “Tao” into one thing: **classic ≠ alchemy manual**; **Lord Lao** elevation in religious Taoism; manga blends layers.

### Video prompt

```text
Short philosophy primer: Laozi and the *Dao De Jing* for *Hell’s Paradise* fans.

Cover:
- The Way (道) as ineffable order; wu wei (無為) in one practical sentence.
- Explicit contrast: this text does not systematize qi-for-alchemy, rituals, gods, immortality cults the way later Taoism does.
- How religious Taoism still treats the same book as scripture (deification of Laozi / Lord Lao the Most High).
- Last beat: why the manga’s “Tao (タオ)” can mix philosophical language with battle-shōnen cultivation tropes—creative fusion, not a quote from the *Dao De Jing*.

Visuals: ink wash abstraction, turning pages (generic), yin-yang symbol once. Tone: precise, not preachy.

---
MANGA / ANIME ANCHORS:
- **Glossary / story:** Contrast classical **道** with in-story **タオ** (power system); mention **太上老君** where the doc ties **Lord Lao** to **符** and later **§3a** (preview **Episode 07**).
- **Where in the story:** Battle dialogue and training use **“Tao”** in a **shōnen** sense—quote **that** fusion, not the *Dao De Jing* as if it were a spellbook.
- **Dive:** One beat on **Japanese** katakana **タオ** vs Chinese **道** on **official** materials / tankōbon glosses.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 07 — Taoist **talismans (符)** and **太上老君急急如律令** (§3a)

**Source span:** `### 3a.` entire (through the Commons **Daoist charm** image caption).

**Goal:** **Material religion** episode: **符** in organized Taoism; **如律令** as Han legal boilerplate; full spell string; **center vs margin** of a charm; **靈符** vs **霊符**; tie to **明目法** in the official glossary.

### Video prompt

```text
Educational segment on Taoist talismans (符) for manga readers who saw spirit-talisman divination in *Hell’s Paradise*.

Cover:
- What a fu is: paper/fabric charm, seals, “magic writing” traditions (cloud-seal / thunder style) without overclaiming one manga panel.
- 急急如律令: Han document tone adopted into spirit commands; 太上老君 as authority.
- Layout: peripheral command text vs center “what this charm does.”
- Mention 靈符 (Traditional) vs 霊符 (Japanese materials) and 明目法 from the official glossary.
- One sentence: talismans also bound elixir chambers in historical waidan (cross-ref §14 / §7).

Tone: respectful; clear fiction vs religious history. If using the doc’s Wikimedia charm image, keep the file credit on screen.

---
MANGA / ANIME ANCHORS:
- **Glossary:** [明目法](https://www.jigokuraku.com/glossary/) *Meimoku-hō*, **靈符** / **霊符** *reifu*; **符** as medium for **divination** in-fiction.
- **Where in the story:** Any **spirit-talisman / fortune** scene—describe **when** the work shows **札** or **霊符** (no fabricated chapter numbers; say “island arc,” “Hōrai infiltration,” etc.).
- **Dive:** Parent doc **§3a** + **急急如律令** / **太上老君** string—tie to **on-screen** charm geometry if the user supplies **fair-use** stills; otherwise stay descriptive.
- **Cross-episode:** Point to **§7 / Episode 14** for **符** bounding **elixir** chambers.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 08 — Taiji, *Book of Changes* intro, Eight Trigrams, and the Zhang Sanfeng note

**Source span:** `### 4.` from `#### **Taiji**` through **Relation to *Hell’s Paradise*** (stop **before** `#### **易經**`).

**Goal:** **Cosmology 101** part A: **Taiji → Two Modes → Four Images → Eight Trigrams → 64 hexagrams**; optional **Zhang Sanfeng / taijiquan** debunk; Tensen **yin–yang** hook—**without** yet diving into the long **易經** divination subsection.

### Video prompt

```text
Cosmology explainer (part A) for English viewers: Taiji (Supreme Ultimate), Two Modes, Four Images, Eight Trigrams, sixty-four hexagrams.

Include:
- The Xici quotation in Traditional form (易有太極…) once on screen.
- Table walkthrough: 太極, 兩儀, 四象, 八卦, 六十四卦 with Jyutping.
- Optional 30s: Zhang Sanfeng / tai chi shares the characters 太極 but is not the origin of cosmology (debunk confusion).
- Close: how Tensen elemental yin-yang logic sits in this correlative world-picture.

Use animated compass trigram. Next episode handles 易經 wings and casting. Pace slowly; repeat “Taiji → two → four → eight” once on screen.

---
MANGA / ANIME ANCHORS:
- **Story hook:** **Tensen** **yin–yang** switching and **elemental Tao**—map to **Taiji → 兩儀** logic from the doc’s **§4** (no need to name every fight).
- **Where in the story:** Call out **陰陽** *on’yō* / **陰陽** as read in materials when **powers** clash; optional **八卦** imagery if it appears in **official art** or **chapter title cards** (describe, don’t claim a specific vol. unless verified).
- **Dive:** **Zhang Sanfeng** note stays **historical debunk**—one line only that **太極拳** is **not** the manga’s power system.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 09 — **易經 / 周易**, lost **Yi**, **十翼**, and how Change divination worked

**Source span:** `### 4.` from `#### **易經**` through the end of that subsection (through “…into **modern** **East Asian** **fiction**.”)—stop before `**Note on “Cheung Sam Fung”**`.

**Goal:** **Divination history** episode: **易經** vs surviving **周易**; **連山 / 歸藏**; table of **繫辭・文言・說卦・序卦・雜卦** (+ mention **彖傳 / 象傳**); yarrow / coins; **變爻** and **之卦**; layered reading; manga tie (卦 / 明目法).

### Video prompt

```text
Teach the Book of Changes package for fans who heard “I Ching” but never cast a hexagram.

Sections:
1) 易經 vs 周易: oracle core vs whole received book.
2) Three Yi (三易): 連山 / 歸藏 lost or fragmentary; Zhou Yi is what survives for practice.
3) Ten Wings: explain each wing’s job in interpretation (繫辭 cosmology, 文言 on Qian/Kun, 說卦 trigram images, 序卦 sequence story, 雜卦 contrasts) plus 彖傳 / 象傳 in one line each.
4) Fortune-telling schematic: question → stalks or three coins → six through nine → changing lines → 之卦 → how readers stack 卦辭/爻辭 with commentaries.
5) One beat: *Hell’s Paradise* gestures at this stack when it uses Change-style divination language.

Visuals: hexagram lines animating, generic coins, no copyrighted manga panels unless supplied.

---
MANGA / ANIME ANCHORS:
- **Glossary:** Link **明目法** again to **卦**-style **fate** reading; **易經** *Ekikyō* as the **cultural package** the story **gestures** at.
- **Where in the story:** Narration or visuals that sound like **divination** / **oracle** language—tie to **周易** + **十翼** stack **once** with a concrete **in-story** example (e.g. “reading” conditions, omens).
- **Dive:** **連山 / 歸藏** as **lost books** parallel **in-fiction lost techniques**—**one sentence**, no new lore invention.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 10 — Five Elements, Zou Yan, two cycles, and wuxing diagrams

**Source span:** `### 4.` from `**Note on “Cheung Sam Fung”**` through the end of `### 4.` (Five Elements, Zou Yan, two cycles, wuxing diagram)—ends before `### 5.`.

**Goal:** **Cosmology 101** part B: Five Phases **separate** from the *Changes* core; **mutual production / restraint / draining**; link to Tensen **harvest** theme.

### Video prompt

```text
Cosmology explainer (part B): Five Elements (Five Phases) merged under Han with Changes interpretation.

Include:
- Explicit: Five Phases do not originate inside the received Zhou Yi core the way Taiji language does—Zou Yan / School of Naturalists.
- Mutual production vs mutual restraint; “draining / depletion” as the moral hook for *Hell’s Paradise* harvesting Tao.
- Rotate five-phase ring (generic diagram).

Assume viewers may have watched the previous episode on Change divination—do not repeat Ten Wings detail here.

---
MANGA / ANIME ANCHORS:
- **Glossary:** [相克](https://www.jigokuraku.com/glossary/) / [相生](https://www.jigokuraku.com/glossary/) *sōkoku* / *sōshō*; **五行** *gogyo*; **氣** attributes.
- **Where in the story:** **Tensen** battles and **Tao** interactions—**harvest / drain** theme; name **one** character moment where **相克** matters tactically (generic wording if needed).
- **Dive:** Doc’s **“draining cycle”** ↔ manga’s **absorbing Tao**—explicit compare/contrast **one paragraph**.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 11 — Qi, manga Tao (タオ), Tan, ritual timeline, feng shui

**Source span:** `### 5.` entire.

**Goal:** **Power system** episode grounded in real terms: **氣** *hei3* / Japanese **氣** *ki*, **dan** / **Tan**, **waidan** timeline, **feng shui / kan yu**, island as geomantic site.

### Video prompt

```text
Explainer tying real Taoist/geomantic vocabulary to *Hell’s Paradise*’s Tao and Tan.

Structure:
1) Qi (氣) as vital energy—note Japanese reading ki with same graph in the manga materials.
2) Tan (丹) as elixir pellet; waidan vs story’s harvested Tan after Flower Tao / arborification (dark parody stated clearly).
3) Manga Tao: five elements + yin-yang; overlap with qi but distinct term in-story (タオ vs 道).
4) Five training methods named once with “these are real historical hygiene / meditation clusters.”
5) Feng shui + kan yu: wind-water, dragon veins, site qi—then island as “geomantic engine” in the plot.
Optional one-liner (no deep dive): the official glossary rite **辟餌服生の斎** (five-element qi for 徐福)—full **optional echo** of **服餌辟穀** is **Appendix E** in the parent doc; Episode **16** summarizes it.

Tone: fan-friendly but accurate; label Japanese katakana “Tao” vs Chinese 道 on screen once. No sexual detail beyond naming fangzhongshu as “bedchamber arts” in historical context.

---
MANGA / ANIME ANCHORS:
- **Glossary sweep:** [氣](https://www.jigokuraku.com/glossary/), [丹](https://www.jigokuraku.com/glossary/), [丹田](https://www.jigokuraku.com/glossary/), **内丹法 / 外丹法**, **周天**, **守一**, **胎息**, **導引**, **房中術** as listed—match each to **Tensen** who **specializes** (parent doc **§6** table).
- **Where in the story:** **Kotaku** as **geomantic** “engine”; **風水**-flavored **site** logic—tie to **island** layout (three rings) **without** replaying **Episode 03**’s full table.
- **Dive:** **辟餌服生の斎** (glossary)—**one line** + pointer to **Appendix E** / **Episode 16** for the **服餌辟穀** hypothesis.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 12 — Lord Tensen: flowers, **honorific titles**, and the five training paths

**Source span:** `### 6.` from opening through **Areas of expertise: the five training methods** (bulleted flower symbolism + **Honorific titles** table + five methods list)—stop before `#### Kishikai`.

**Goal:** **Character-symbolism** episode: lotus, peony, chrysanthemum, etc.; **Fugen Jōtei**, **Nyoi Genkun**, etc., as **Buddhist–Taoist–imperial** titling; map each Tensen to a **real cultivation category**.

### Video prompt

```text
Character-design-as-culture video: Lord Tensen’s flower names and honorific epithets.

Part A — Flowers: for each named Tensen, give flower, Chinese characters + Jyutping, 2–3 symbolism bullets, one line linking to story theme.

Part B — Honorifics: walk the table (romanization + Traditional gloss column): explain these are layered religious/bureaucratic titles (君/帝/公/上帝/大聖 flavors), not verified interview “official English” for every syllable—check Viz volume notes for publisher-exact romanization.

Part C — Five training methods (daoyin, taixi, shouyi, zhoutian, fangzhongshu)—each one sentence: what the body/mind is doing.

Visuals: botanical plates, hanzi calligraphy, simple human silhouette for breath paths (abstract). Spoiler level: medium—assume audience has seen character designs.

---
MANGA / ANIME ANCHORS:
- **Per-Tensen:** For each **flower name**, cite **romanization + 繁體** as in parent doc / **Viz** notes; pair with **honorific title** (e.g. **Fugen Jōtei**, **Nyoi Genkun**) and **one** **manga** personality beat.
- **Glossary:** [天仙](https://www.jigokuraku.com/glossary/) ranks **道士 → 地仙 → 上仙 → 神仙 → 天仙**—read aloud as **official** ladder.
- **Where in the story:** **Training** montages and **disciple** scenes—map **導引 / 胎息 / 守一 / 周天 / 房中** to **which** Tensen **studies** which (doc table).
- **Dive:** **Spoiler-aware:** **Kishikai** namedrop allowed as **preview** of **Episode 13**—**one line** only if keeping **Episode 12** focused on **titles + flowers**.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 13 — Kishikai, 尸解, and historical parallels (Mawangdui, texts)

**Source span:** `### 6.` from `#### Kishikai` through the **historical parallels** bullets and image captions (through the takeaway before `### 7`).

**Goal:** **Etymology + museums** episode: fiction term vs Taoist **corpse liberation**; Mawangdui daoyin; Ge Hong; **Book of Han** catalog angle.

### Video prompt

```text
Deep-dive: Kishikai (鬼尸解) vs classical 尸解 (“corpse liberation”) in Taoist hagiography—what is attested, what is manga invention.

Cover:
- 尸解 tropes: substitute body, sword/staff, ascended “true person.”
- Prefix 鬼 as horror/demon twist—etymological pun, not a sect manual heading.
- Historical parallels: daoyin charts (Mawangdui), taixi in *Baopuzi*, shouyi in *Taiping* / commentary traditions, zhoutian as later inner-alchemy choreography, fangzhongshu tomb texts + Han bibliographic category.

End with explicit disclaimer: the manga bundles real lineages into a modern “cultivation checklist.” Visuals: Wellcome-style exercise chart feel (non-copy), generic bamboo slips.

---
MANGA / ANIME ANCHORS:
- **Term:** [鬼尸解](https://www.jigokuraku.com/glossary/) *Kishikai* vs classical **尸解**—show **transformation** context (Tensen **battle form**).
- **Where in the story:** Major fights where **Kishikai** triggers—**describe** visual (horror upgrade) **without** full fight choreography.
- **Dive:** Etymology pun **鬼 + 尸解**—**one** **manga** line of dialogue or **narration** style if known from anime adaptation; else stay analytic.
- **Safety:** Reiterate **fiction** term ≠ **Daoist manual** heading (parent doc **Appendix A**).

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 14 — Taiqing-style external alchemy vs *Hell’s Paradise* ritual parody

**Source span:** `### 7.` entire including **Direct comparison** bullet list.

**Goal:** **Ritual structure** episode: vows, purity, elixir chamber **bounded with 符** (cross-ref **§3a / episode 07**), firing cycles, ninefold refinement—mirrored as **island-scale industrial horror**.

### Video prompt

```text
Episode comparing historical Taiqing-style external alchemy stages to the manga’s “factory” logic.

Walk through simplified ritual stages (transmission, purification, sealed chamber with talismans 符, timing, compounding, ingestion goal).
Then parallel each to *Hell’s Paradise*: Tan as victim-compounded elixir; island as dānshì; discipline vs extraction; draining cycles; hubris theme.

Visuals: furnace cross-section, generic seal/talisman geometry, island overlay as diagram. Tone: dark but educational—focus on historical human cost of real elixirs too (mercury).

---
MANGA / ANIME ANCHORS:
- **Cross-ref:** **§3a** **符** + **§7** ritual chamber—**Rentan** / palace labs where **Tan** is processed; [外丹花](https://www.jigokuraku.com/glossary/), **丹** pipeline.
- **Where in the story:** **Elixir retrieval** arc beats—**parallel** historical **Taiqing** steps to **in-story** “stages” (purification → extraction) **without** narrating whole arc.
- **Dive:** **Nine elixirs** lore (doc **§7**) vs **Tensen** “refinement” **one** explicit contrast sentence.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 15 — Internal alchemy (*neidan*), tanden, zhoutian, and martial fiction

**Source span:** `### 8.` entire (through the waidan/neidan fusion bullets and “scholarly reconstruction” disclaimer).

**Goal:** **Body-as-laboratory** + **why shōnen “circulate qi”** sounds Taoist: microcosmic orbit, **tanden** in Japanese arts, wuxia/xianxia popularization; **丹田** as plot-critical weak point (echoes **Appendix D** recovery logic without full epilogue spoilers unless desired).

### Video prompt

```text
Teach internal alchemy (neidan) for fans who know “cultivation” tropes but not the medieval Chinese sources.

Sections:
1) Neidan vs waidan—mnemonic “pill outside vs cauldron inside.”
2) Three treasures (essence, qi, spirit) in plain English.
3) Dantian / tanden: not a literal organ; lower field as breath center; Japanese martial pedagogy (dojo, kendo, etc.) in one paragraph.
4) Zhoutian: astronomy metaphor → body circuit; lesser circuit / microcosmic orbit; overlap with TCM channels.
5) Wuxia / xianxia as popularizer—Jin Yong name-drop as “channel, not inventor.”
6) Map back to Tensen training list and the doc’s claim: weaponized neidan logic.

Visuals: meridian schematic (generic educational), star wheel, calm voice. Avoid medical claims; say “traditional frameworks describe…”
Optional one-line hook: tanden damage/regrowth can justify long in-story time skips (Banko / epilogue)—only if you want spoilers.

---
MANGA / ANIME ANCHORS:
- **Glossary:** [丹田](https://www.jigokuraku.com/glossary/) *tanden* as **weak point**; **周天**, **内丹法**; tie **胚珠** / Kishikai **tanden** shift if spoilers allowed.
- **Where in the story:** **Sagiri** **Tao restoration** touching **Gabimaru**—**one** **non-explicit** sentence on **complementary Tao**; **training** spars on **Hōrai**.
- **Dive:** **Neidan** metaphors in **shōnen** body vocabulary—map **three treasures** to **氣** drain/regen in combat **one** example.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## 16 — Themes, **Appendices A–E**, and reading next

**Source span:** `### Conclusion…`, `## Appendices` (**A**, **B**, **C**, **D**, **E**), `## References…` (including **Anqi Sheng** and primary texts bullets)—**skip** the full **Glossary** tables unless you want a rapid-fire “definitions” coda (then use optional **17**).

**Goal:** **Synthesis + citations** episode: moral thesis; **Kishikai** recap; **Eight Immortals** as interpretive; **Banko / 盤古**; **Hong Kong epilogue** (**雙龍過江** / **雙龍之道**, British Hong Kong tripod, **Ju Fa / Gui Fa**, English “WAY OF THE TWINS” vs Chinese **雙龍**); **Appendix E** (**辟餌服生の斎** vs **服餌辟穀**—optional echo, **weak** semantic link, **no** official glossary confirmation); Watson / Needham pointers.

### Video prompt

```text
Closing episode: thematic summary of *Hell’s Paradise* as a critique of forced immortality and broken cosmic balance.

Do **not** spend minutes re-narrating 秦始皇 or Xu Fu’s expeditions—viewers have Episodes **01–02** (and **05** for poison/tomb). **At most one clause** tying “Qin immortality obsession” to the moral thesis, then move to appendices and reading list.

Include:
- Paradise vs hell; harmony vs harvest; waidan predation vs neidan self-cultivation fused in the antagonists’ system.
- Appendix A (Kishikai vs 尸解) one-minute recap.
- Appendix B: “Eight Immortals” fan comparisons vs authorial evidence—stay cautious.
- Appendix C: Banko vs mythic Pangu (盤古)—thematic rhyme, not a Taoist Canon footnote.
- Appendix D: epilogue in British-occupied Hong Kong; 雙龍過江 idiom; 雙龍之道 vs English “THE WAY OF THE TWINS”; three-way power sketch (British / triads / Qing agents) as atmosphere not documentary transcript; optional: century-scale regrowth justifying the time jump.
- Appendix E (short): official **辟餌服生の斎** definition from *Jigokuraku* glossary (five-element qi for 徐福); then **hypothesis only**—graph overlap with **服餌辟穀** (辟穀 + medicinals per zh.wikipedia 辟穀 article); contrast self-cultivation vs manga predation; label as reader-side, not verified intertext.
- “Where to read next”: *Records of the Grand Historian* (Watson), *Dao De Jing*, *Book of Changes* + Ten Wings, *Baopuzi*, Needham as dense orientation.

Tone: reflective. Visuals: slower pacing, quote cards with proper nouns + characters. Invite viewers to read the full written doc for glossary + EN/繁/JP cross-reference.

---
MANGA / ANIME ANCHORS:
- **Appendices → panels:** **A** *Kishikai* fights; **B** Tensen vs **八仙** fan comparisons; **C** **Banko** / **盤古** scale; **D** epilogue **雙龍過江** title cards + **Hong Kong**; **E** **辟餌服生の斎** (glossary) + **服餌辟穀** doc hypothesis—**one manga beat each** where possible.
- **Spoilers:** Full **late-arc** and **epilogue** allowed—label **“major spoilers.”**
- **Dive:** For **Appendix D**, compare **English** “THE WAY OF THE TWINS” vs **雙龍之道** as **published** title cards (Viz / JP).
- **Reading list:** Keep Watson / Needham—**add** “re-read **glossary** entries” as homework.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## Optional 17 — Glossary sprint (flashcards)

**Source span:** `## Glossary` including **### Cross-reference index** and all subsections (People through Tensen flower table).

**Goal:** **Not a narrative video**—good for **shorts**, **carousel script**, or **Anki-style** audio. If NotebookLM struggles with tables, export glossary bullets to plain text first.

### Video prompt

```text
Generate a fast-paced “term of the day” montage (30–45s per term) from a glossary: each beat shows English term, Traditional Chinese characters, Cantonese Jyutping, Japanese where listed, one-line definition, and which main-essay section it belongs to.

No storytelling—just crisp definitions. Voice: neutral narrator. On-screen text must stay readable; pause between terms.

---
MANGA / ANIME ANCHORS:
- **Source:** Parent doc **Glossary** + **Cross-reference index** table—each flashcard: **English / 繁體 / JP** as listed; add **“manga fandom term”** column when the row has **Kotaku**, **Tensen**, **Banko**, etc.
- **Glossary:** Prefer [official glossary](https://www.jigokuraku.com/glossary/) **Japanese** headwords for **series-coined** terms.
- **Where in the story:** For **story-specific** rows, **one** **usage** note (e.g. **こたく**, **タオ**, **鬼尸解**)—**no** Xu Fu essay.
- **Pace:** **30–45 s** per term—**zero** Sima Qian backstory unless the term **is** Xu Fu / Qin.

---
SERIES CONTINUITY — DO NOT REPEAT EARLIER EPISODES:
- Do **not** retell the biography of **秦始皇 (Qin Shi Huang)** or the **two 徐福 (Xu Fu) expeditions** (Sima Qian, fleets, youths sent east, sea monsters, Langya)—**Episode 02** already covered that; **Episode 01** only teased it in one line each.
- **Maximum** for any of the above: **one short sentence** of recap or “as we established…” then proceed **only** with this episode’s topic.
- If the source text still contains long Xu Fu paragraphs, **do not narrate them**; treat them as reference the audience already watched.
- Open **in medias res** with this episode’s first required bullet, not a general “In ancient China…” history lesson unless this episode is **01**, **02**, or **05** (tomb/poison context only).
```

---

## File maintenance

- If you **edit headings** in `Hell's Paradise's Historical Context.md`, update the **Source span** lines in this outline to match.
- To **stop Xu Fu loops**, upload excerpts that **cut `### 1.`** (voyages) for Episodes **06–16**; keep a single line: “Xu Fu / Qin expeditions: Episode 02.”
- New major headings since older versions of this file: **`### 3a.`**, **`#### **易經**` (under §4)**, **`### Appendix D`**, **`### Appendix E`** (**辟餌服生の斎** / **服餌辟穀**), expanded intro **compile** paragraph, **Glossary cross-reference index**.
- For strict NotebookLM isolation, consider saving **per-episode excerpts** as separate `.md` files and uploading **only one excerpt + this prompt** per generation.
- **Episodes 01–17:** Paste the **entire** **Video prompt** fence for that episode (**main text → MANGA / ANIME ANCHORS → SERIES CONTINUITY** where listed); keep **[official glossary](https://www.jigokuraku.com/glossary/)** open when generating. For **Episode 03** only, you may **append** the standalone footer from [Continuity](#continuity-avoid-repeating-earlier-episodes) if regenerating without editing the prompt.
