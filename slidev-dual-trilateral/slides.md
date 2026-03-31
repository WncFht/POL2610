---
theme: default
title: Why Do Japan and South Korea Want Both U.S. Security Insurance and a China Interface
info: |
  POL2610 presentation on alliance management, dual-trilateral order, and differentiated Japan/ROK strategies.
author: Codex
layout: cover
aspectRatio: 16/9
download: false
colorSchema: light
drawings:
  enabled: false
transition: fade
fonts:
  sans: IBM Plex Sans
  serif: Source Serif 4
  mono: IBM Plex Mono
---

<style>
:root {
  --ink: #1c2a3a;
  --muted: #556274;
  --blue: #2d5a88;
  --gold: #9a6130;
  --paper: #fbf7ef;
  --paper-deep: #f2eadc;
  --line: rgba(28, 42, 58, 0.12);
  --panel: rgba(255, 251, 244, 0.88);
}

.slidev-layout {
  background: linear-gradient(180deg, #fbf7ef 0%, #f4ede2 100%);
  color: var(--ink);
}

.slidev-layout.cover {
  background:
    radial-gradient(circle at 15% 15%, rgba(255, 246, 228, 0.95) 0%, rgba(255, 246, 228, 0.7) 20%, transparent 42%),
    linear-gradient(140deg, #fbf7ef 0%, #efe4d3 70%, #e7dbc7 100%);
}

h1, h2, h3, h4 {
  font-family: "Source Serif 4", Georgia, serif;
  color: var(--ink);
  letter-spacing: -0.02em;
}

p, li, div, span, table {
  font-family: "IBM Plex Sans", Arial, sans-serif;
}

.eyebrow {
  font-size: 0.76rem;
  text-transform: uppercase;
  letter-spacing: 0.18em;
  font-weight: 700;
  color: var(--blue);
  margin-bottom: 0.85rem;
}

.cover-subtitle {
  font-size: 1.22rem;
  color: #31475f;
  max-width: 760px;
  margin-top: 1rem;
}

.question-pill {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
  margin-top: 1.35rem;
  border-radius: 999px;
  padding: 0.45rem 0.9rem;
  background: rgba(45, 90, 136, 0.11);
  border: 1px solid rgba(45, 90, 136, 0.18);
  color: var(--blue);
  font-weight: 700;
  font-size: 0.9rem;
}

.page-shell {
  padding: 2.2rem 3rem 2rem;
}

.slide-title {
  font-size: 2.05rem;
  line-height: 1.05;
  margin-bottom: 0.35rem;
}

.slide-lead {
  font-size: 1rem;
  color: var(--muted);
  margin-bottom: 1rem;
  max-width: 920px;
}

.diagram-card {
  border-radius: 28px;
  background: rgba(255, 251, 244, 0.82);
  border: 1px solid var(--line);
  box-shadow: 0 14px 34px rgba(15, 23, 42, 0.08);
  padding: 0.85rem;
}

.diagram-img {
  width: 100%;
  display: block;
}

.concept-grid {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 1rem;
  align-items: stretch;
}

.concept-stack,
.two-panel,
.case-grid,
.validation-grid {
  display: grid;
  gap: 1rem;
}

.concept-stack {
  grid-template-rows: 1fr 1fr;
}

.two-panel,
.validation-grid {
  grid-template-columns: 1fr 1fr;
}

.case-grid {
  grid-template-columns: repeat(3, 1fr);
}

.panel {
  border-radius: 24px;
  background: var(--panel);
  border: 1px solid var(--line);
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.07);
  padding: 1.05rem 1.1rem;
}

.panel h3 {
  font-size: 1.18rem;
  margin-bottom: 0.35rem;
}

.mini-label {
  font-size: 0.7rem;
  text-transform: uppercase;
  letter-spacing: 0.14em;
  font-weight: 700;
  margin-bottom: 0.4rem;
}

.blue-label {
  color: var(--blue);
}

.gold-label {
  color: var(--gold);
}

.panel p {
  font-size: 0.92rem;
  line-height: 1.45;
  color: #334155;
}

.claim-banner {
  border-left: 6px solid var(--blue);
  background: rgba(45, 90, 136, 0.08);
  border-radius: 18px;
  padding: 0.95rem 1rem;
  margin-bottom: 1rem;
  font-size: 1rem;
  line-height: 1.45;
  color: #223548;
}

.scope-note {
  margin-top: 0.85rem;
  font-size: 0.88rem;
  line-height: 1.42;
  color: #556274;
}

.comparison-wrap {
  margin-top: 0.6rem;
  border-radius: 26px;
  overflow: hidden;
  background: rgba(255, 251, 244, 0.82);
  border: 1px solid var(--line);
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.08);
}

.comparison-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.94rem;
}

.comparison-table th,
.comparison-table td {
  padding: 0.95rem 1rem;
  vertical-align: top;
  border-bottom: 1px solid rgba(28, 42, 58, 0.09);
}

.comparison-table th {
  background: rgba(240, 234, 223, 0.72);
  font-size: 0.95rem;
  font-weight: 700;
  text-align: left;
}

.comparison-table tr:last-child td {
  border-bottom: none;
}

.row-label {
  width: 24%;
  font-weight: 700;
  color: #2b3d51;
}

.summary-line {
  margin-top: 0.95rem;
  font-size: 0.96rem;
  color: #475569;
  max-width: 980px;
}

.statement-wrap {
  max-width: 980px;
  margin: 0 auto;
  text-align: center;
}

.statement-main {
  font-family: "Source Serif 4", Georgia, serif;
  font-size: 2.35rem;
  line-height: 1.18;
  font-weight: 700;
  color: #172334;
}

.statement-sub {
  margin-top: 1rem;
  font-size: 1.05rem;
  line-height: 1.5;
  color: #4f5f71;
}

.statement-trace {
  display: flex;
  justify-content: center;
  gap: 0.75rem;
  flex-wrap: wrap;
  margin-top: 1.2rem;
}

.trace-pill {
  border-radius: 999px;
  padding: 0.42rem 0.8rem;
  font-size: 0.82rem;
  font-weight: 700;
  background: rgba(45, 90, 136, 0.11);
  border: 1px solid rgba(45, 90, 136, 0.15);
  color: var(--blue);
}

.caption-right {
  margin-top: 0.6rem;
  text-align: right;
  font-size: 0.8rem;
  color: #6a7788;
}

.cover-grid {
  display: grid;
  grid-template-columns: 1.05fr 0.95fr;
  gap: 1.6rem;
  align-items: center;
}

.cover-copy {
  max-width: 640px;
}

.cover-visuals {
  display: grid;
  gap: 0.95rem;
}

.photo-card {
  position: relative;
  overflow: hidden;
  border-radius: 28px;
  background: rgba(255, 251, 244, 0.88);
  border: 1px solid var(--line);
  box-shadow: 0 16px 34px rgba(15, 23, 42, 0.08);
}

.photo-card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.contained-visual img {
  object-fit: contain;
  background: rgba(255, 251, 244, 0.76);
  padding: 0.9rem;
}

.photo-card.tall {
  height: 312px;
}

.photo-card.medium {
  height: 186px;
}

.photo-card.media-photo {
  min-height: 388px;
}

.photo-tag {
  position: absolute;
  top: 16px;
  left: 16px;
  border-radius: 999px;
  padding: 0.38rem 0.72rem;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #ffffff;
  backdrop-filter: blur(6px);
}

.photo-tag.blue {
  background: rgba(45, 90, 136, 0.88);
}

.photo-tag.gold {
  background: rgba(154, 97, 48, 0.88);
}

.photo-caption {
  position: absolute;
  left: 16px;
  bottom: 16px;
  max-width: calc(100% - 32px);
  padding: 0.48rem 0.72rem;
  border-radius: 14px;
  background: rgba(255, 250, 243, 0.94);
  color: #233548;
  font-size: 0.82rem;
  font-weight: 700;
  box-shadow: 0 8px 18px rgba(15, 23, 42, 0.08);
}

.floating-note {
  position: absolute;
  right: 16px;
  top: 16px;
  border-radius: 14px;
  padding: 0.42rem 0.64rem;
  background: rgba(255, 250, 243, 0.94);
  color: #233548;
  font-size: 0.78rem;
  font-weight: 700;
  box-shadow: 0 8px 18px rgba(15, 23, 42, 0.08);
}

.floating-note.bottom {
  left: 16px;
  right: auto;
  top: auto;
  bottom: 16px;
}

.track-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}

.track-card {
  border-radius: 28px;
  background: rgba(255, 251, 244, 0.86);
  border: 1px solid var(--line);
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.08);
  padding: 1rem;
}

.track-head {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 0.8rem;
  margin-bottom: 0.8rem;
}

.track-title {
  font-size: 1rem;
  font-weight: 700;
}

.track-title.blue {
  color: var(--blue);
}

.track-title.gold {
  color: var(--gold);
}

.track-kicker {
  font-size: 0.72rem;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: #667386;
  font-weight: 700;
}

.track-image {
  height: 220px;
  border-radius: 20px;
  overflow: hidden;
  border: 1px solid rgba(28, 42, 58, 0.1);
}

.track-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.milestone-list {
  display: grid;
  gap: 0.56rem;
  margin-top: 0.9rem;
}

.milestone-item {
  display: grid;
  grid-template-columns: 86px 1fr;
  gap: 0.6rem;
  align-items: start;
  font-size: 0.84rem;
  line-height: 1.35;
  color: #2b3d51;
}

.milestone-date {
  font-weight: 700;
}

.milestone-date.blue {
  color: var(--blue);
}

.milestone-date.gold {
  color: var(--gold);
}

.book-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 0.85rem;
}

.book-card {
  border-radius: 20px;
  overflow: hidden;
  background: rgba(255, 251, 244, 0.84);
  border: 1px solid var(--line);
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.08);
}

.book-image {
  aspect-ratio: 0.73;
  background: #f2eadc;
}

.book-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.book-meta {
  padding: 0.72rem 0.78rem 0.84rem;
}

.book-tag {
  margin-bottom: 0.3rem;
  font-size: 0.7rem;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: #667386;
  font-weight: 700;
}

.book-title {
  font-size: 0.84rem;
  line-height: 1.35;
  color: #243548;
  font-weight: 700;
}

.theory-note {
  margin-top: 0.72rem;
  font-size: 0.82rem;
  color: #667386;
}

.media-split {
  display: grid;
  grid-template-columns: 0.95fr 1.05fr;
  gap: 1rem;
  align-items: stretch;
}

.stack-grid {
  display: grid;
  gap: 0.85rem;
}

.lane-stack {
  display: grid;
  gap: 0.9rem;
}

.lane-card {
  border-radius: 24px;
  background: var(--panel);
  border: 1px solid var(--line);
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.07);
  padding: 1rem 1.08rem;
}

.lane-card.blue {
  border-left: 6px solid var(--blue);
}

.lane-card.gold {
  border-left: 6px solid var(--gold);
}

.lane-card h3 {
  font-size: 1.18rem;
  margin-bottom: 0.34rem;
}

.lane-card p,
.lane-card li {
  font-size: 0.9rem;
  line-height: 1.45;
  color: #334155;
}

.lane-card ul {
  margin: 0.55rem 0 0 1.05rem;
}

.reference-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
  margin-top: 0.8rem;
}

.reference-card {
  border-radius: 24px;
  background: rgba(255, 251, 244, 0.86);
  border: 1px solid var(--line);
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.07);
  padding: 1rem 1.1rem;
}

.reference-card h3 {
  font-size: 1.14rem;
  margin-bottom: 0.45rem;
}

.reference-list {
  margin: 0;
  padding-left: 1rem;
}

.reference-list li {
  margin-bottom: 0.42rem;
  font-size: 0.82rem;
  line-height: 1.32;
  color: #334155;
}

.reference-note {
  margin-top: 0.7rem;
  font-size: 0.8rem;
  color: #64748b;
}
</style>

<div class="cover-grid">
  <div class="cover-copy">
    <div class="eyebrow">POL2610 / Northeast Asia / 2023-2025</div>
    <h1>Why Do Japan and South Korea Want Both?</h1>
    <div class="cover-subtitle">U.S. security insurance and a China interface</div>
    <div class="question-pill">Alliance management, not simple side-choosing</div>
  </div>
  <div class="cover-visuals">
    <div class="photo-card tall">
      <img src="/assets/camp-david-2023.jpg" alt="Leaders at Camp David in August 2023" />
      <div class="photo-tag blue">Security Track</div>
      <div class="photo-caption">Camp David leaders photo, August 2023</div>
    </div>
    <div class="photo-card medium">
      <img src="/assets/cjk-summit-2024.jpg" alt="Leaders at the CJK Summit in Seoul in May 2024" />
      <div class="photo-tag gold">Interface Track</div>
      <div class="photo-caption">CJK Summit in Seoul, May 2024</div>
    </div>
  </div>
</div>

<!--
Purpose: Hook the audience with the central puzzle and frame the talk as alliance management.
Open: "If Japan and South Korea are moving closer to the United States, why are they still keeping channels with China?"
Beats:
1. The coexistence of the two tracks looks contradictory.
2. The argument is about managing two strategic risks at once.
3. The rest of the talk explains how those risks are managed.
Transition: "To see why this matters, we first need a quick visual overview of the two tracks."
Time: 50s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell" style="padding:1.8rem 2.45rem 1.2rem;">
  <div class="slide-title" style="font-size:1.82rem;margin-bottom:0.2rem;">One Region, Two Tracks</div>
  <div class="slide-lead" style="margin-bottom:0.7rem;font-size:0.92rem;">From 2023 to 2025, security institutionalization and China-facing interfaces advanced in parallel.</div>
  <div style="display:grid;grid-template-columns:1fr 1fr;gap:0.82rem;">
    <div class="track-card" style="padding:0.84rem 0.88rem;">
      <div class="track-head" style="margin-bottom:0.55rem;">
        <div class="track-title blue" style="font-size:0.96rem;">Security insurance</div>
        <div class="track-kicker" style="font-size:0.66rem;">U.S. - Japan - ROK</div>
      </div>
      <div class="track-image" style="height:214px;">
        <img src="/assets/camp-david-meeting-2023.jpg" alt="Trilateral Camp David meeting in 2023" />
      </div>
      <div class="milestone-list" style="gap:0.42rem;margin-top:0.72rem;">
        <div class="milestone-item" style="grid-template-columns:78px 1fr;font-size:0.8rem;"><span class="milestone-date blue">Apr 2023</span><span>Washington Declaration sharpened reassurance.</span></div>
        <div class="milestone-item" style="grid-template-columns:78px 1fr;font-size:0.8rem;"><span class="milestone-date blue">Aug 2023</span><span>Camp David regularized trilateral consultation.</span></div>
        <div class="milestone-item" style="grid-template-columns:78px 1fr;font-size:0.8rem;"><span class="milestone-date blue">Jul 2024</span><span>Defense trilateralism linked to extended deterrence.</span></div>
        <div class="milestone-item" style="grid-template-columns:78px 1fr;font-size:0.8rem;"><span class="milestone-date blue">Jan 2025</span><span>4th NCG confirmed institutionalization.</span></div>
      </div>
    </div>
    <div class="track-card" style="padding:0.84rem 0.88rem;">
      <div class="track-head" style="margin-bottom:0.55rem;">
        <div class="track-title gold" style="font-size:0.96rem;">China-facing interface</div>
        <div class="track-kicker" style="font-size:0.66rem;">CJK / bilateral channels</div>
      </div>
      <div class="track-image" style="height:214px;">
        <img src="/assets/cjk-summit-2024.jpg" alt="CJK Summit in Seoul in 2024" />
      </div>
      <div class="milestone-list" style="gap:0.42rem;margin-top:0.72rem;">
        <div class="milestone-item" style="grid-template-columns:78px 1fr;font-size:0.8rem;"><span class="milestone-date gold">May 2024</span><span>9th CJK Summit revived functional cooperation.</span></div>
        <div class="milestone-item" style="grid-template-columns:78px 1fr;font-size:0.8rem;"><span class="milestone-date gold">May 2024</span><span>ROK-China foreign ministers kept diplomacy active.</span></div>
        <div class="milestone-item" style="grid-template-columns:78px 1fr;font-size:0.8rem;"><span class="milestone-date gold">Mar 2025</span><span>CJK foreign ministers sustained the lane.</span></div>
        <div class="milestone-item" style="grid-template-columns:78px 1fr;font-size:0.8rem;"><span class="milestone-date gold">Mar 2025</span><span>Japan-China dialogue preserved governance channels.</span></div>
      </div>
    </div>
  </div>
</div>

<!--
Purpose: Establish the empirical base with one visual map of the period.
Open: "Northeast Asia did not move in one direction. It moved on two tracks at the same time."
Beats:
1. Track one is U.S.-Japan-ROK reassurance and deterrence.
2. Track two is the revived CJK and China-facing interface track.
3. Briefly point to the two photos: one visualizes security institutionalization, the other shows diplomatic interface revival.
4. The coexistence of these tracks is the fact the rest of the talk explains.
Transition: "Now the question becomes how to explain this without treating it as indecision."
Time: 1m20s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell">
  <div class="slide-title">Key Idea: Alliance Management, Not Simple Side-Choosing</div>
  <div class="slide-lead">The same allies manage two opposite risks: abandonment and entrapment.</div>
  <div class="concept-grid">
    <div>
      <div class="book-grid">
        <div class="book-card">
          <div class="book-image">
            <img src="/assets/ipus-alliance-dilemma-cover.png" alt="Alliance dilemma literature cover" />
          </div>
          <div class="book-meta">
            <div class="book-tag">Theory</div>
            <div class="book-title">Alliance dilemma: abandonment and entrapment</div>
          </div>
        </div>
        <div class="book-card">
          <div class="book-image">
            <img src="/assets/us-alliances-cover.png" alt="Extended deterrence and alliance literature cover" />
          </div>
          <div class="book-meta">
            <div class="book-tag">Deterrence</div>
            <div class="book-title">U.S. nuclear weapons and alliances in Northeast Asia</div>
          </div>
        </div>
        <div class="book-card">
          <div class="book-image">
            <img src="/assets/kei-middle-power-cover.png" alt="Middle power diplomacy literature cover" />
          </div>
          <div class="book-meta">
            <div class="book-tag">Middle Power</div>
            <div class="book-title">Why allies still preserve room under great-power rivalry</div>
          </div>
        </div>
      </div>
      <div class="theory-note">The analytical frame combines alliance dilemma logic with middle-power risk management.</div>
    </div>
    <div class="concept-stack">
      <div class="panel">
        <div class="mini-label blue-label">Risk Reduction 1</div>
        <h3>Reduce abandonment</h3>
        <p>Ask for more visible, procedural, and durable U.S. commitments.</p>
      </div>
      <div class="panel">
        <div class="mini-label gold-label">Risk Reduction 2</div>
        <h3>Reduce entrapment</h3>
        <p>Keep a limited China interface to avoid rupture, retaliation, and uncontrolled escalation.</p>
      </div>
    </div>
  </div>
</div>

<!--
Purpose: Introduce the theory in the lightest possible form.
Open: "I explain this through alliance theory, especially the alliance dilemma."
Beats:
1. Define abandonment in plain language.
2. Define entrapment in plain language.
3. Use the three book covers as a quick cue that the argument is grounded in alliance and middle-power literature.
4. Show how U.S. reassurance and China interface preservation answer different risks.
Transition: "With that frame in mind, let me turn to Japan first."
Time: 1m20s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell">
  <div class="slide-title" style="font-size:1.82rem;margin-bottom:0.32rem;">Japan Case 1: Why Tokyo Wanted Harder U.S. Insurance</div>
  <div style="display:grid;grid-template-columns:0.88fr 1.12fr;gap:0.9rem;align-items:start;">
    <div class="photo-card" style="height:430px;">
      <img src="/assets/tri-chod-yokota-2024.jpg" alt="U.S., Japan, and South Korea defense chiefs at Yokota in 2024" />
      <div class="photo-tag blue">Procedure</div>
      <div class="photo-caption">Trilateral chiefs of defense, Yokota, July 2024</div>
    </div>
    <div style="display:grid;gap:0.68rem;">
      <div class="claim-banner" style="margin-bottom:0;padding:0.8rem 0.92rem;font-size:0.94rem;">Japan wanted U.S. commitments that were more institutional, more visible, and more predictable.</div>
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:0.68rem;">
        <EvidenceCard label="2023 Aug" title="Camp David" body="Regularized trilateral meetings, exercises, and faster consultation." accent="blue" />
        <EvidenceCard label="2024 Jul" title="Extended deterrence statement" body="Moved reassurance toward more formal bilateral consultation." accent="blue" />
        <EvidenceCard label="2024 Dec" title="Guidelines for Extended Deterrence" body="Turned reassurance into a more explicit planning framework." accent="blue" style="grid-column:1 / -1;" />
      </div>
    </div>
  </div>
  <div class="scope-note" style="margin-top:0.45rem;font-size:0.82rem;">Interpretation: Tokyo was reducing abandonment risk through procedure, not relying on trust alone.</div>
</div>

<!--
Purpose: Show the security-insurance side of the Japan case.
Open: "Japan first looks like a clear case of stronger alliance reassurance."
Beats:
1. Security conditions looked worse to Tokyo.
2. Camp David regularized trilateral cooperation.
3. The Yokota photo shows reassurance as repeated military coordination, not just text.
4. Bilateral extended deterrence documents made reassurance more formal.
5. Tie the slide back to abandonment reduction.
Transition: "But Japan is not only a story of harder balancing."
Time: 1m25s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell" style="padding:1.9rem 2.6rem 1.45rem;">
  <div class="slide-title" style="font-size:1.74rem;margin-bottom:0.28rem;">Japan Case 2: Why Tokyo Still Kept China Channels Open</div>
  <div style="display:grid;grid-template-columns:0.8fr 1.2fr;gap:0.82rem;align-items:start;">
    <div class="photo-card contained-visual" style="height:404px;">
      <img src="/assets/china-japan-juncture-cover.png" alt="Book cover on China-Japan relations at a new juncture" />
      <div class="photo-tag gold">China Channel</div>
      <div class="photo-caption" style="font-size:0.76rem;">Issue-specific channels still mattered.</div>
    </div>
    <div style="display:grid;gap:0.6rem;">
      <div class="slide-lead" style="margin-bottom:0;font-size:0.9rem;line-height:1.35;">Japan balanced harder, but it did not erase narrow channels for crisis management and economic governance.</div>
      <div style="display:grid;gap:0.6rem;">
        <EvidenceCard label="Security interface" title="Japan-China defense hotline" body="A narrow channel for avoiding contingencies even under sharper competition." accent="gold" />
        <EvidenceCard label="Economic interface" title="High-level economic dialogue" body="A controlled venue for business conditions, green economy, export controls, and critical minerals." accent="gold" />
      </div>
    </div>
  </div>
  <div class="scope-note" style="margin-top:0.36rem;font-size:0.78rem;">This was a limited interface inside a balancing-heavy strategy.</div>
</div>

<!--
Purpose: Prevent the audience from reading Japan as pure containment.
Open: "Even as Tokyo strengthened deterrence, it still kept some China-facing channels open."
Beats:
1. The hotline shows crisis-management logic.
2. The economic dialogue shows controlled governance logic.
3. The book cover can be used as a visual cue that China-Japan ties entered a new juncture rather than disappearing.
4. The interface is narrow, but it still matters.
Transition: "South Korea faces the same dilemma, but the balance is different."
Time: 1m15s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell">
  <div class="slide-title" style="font-size:1.82rem;margin-bottom:0.32rem;">South Korea Case 1: Why Seoul Wanted Even More Reassurance</div>
  <div style="display:grid;grid-template-columns:0.88fr 1.12fr;gap:0.9rem;align-items:start;">
    <div class="photo-card" style="height:430px;">
      <img src="/assets/us-japan-rok-bmd-2023.jpg" alt="Trilateral ballistic missile defense exercise among the U.S., Japan, and South Korea in 2023" />
      <div class="photo-tag blue">Visibility</div>
      <div class="photo-caption">Trilateral missile-defense exercise, April 2023</div>
    </div>
    <div style="display:grid;gap:0.68rem;">
      <div class="claim-banner" style="margin-bottom:0;padding:0.8rem 0.92rem;font-size:0.92rem;">South Korea pushed for an even more visible reassurance upgrade because the nuclear problem is more immediate on the peninsula.</div>
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:0.68rem;">
        <EvidenceCard label="2023 Apr" title="Washington Declaration" body="Created a sharper reassurance upgrade centered on nuclear consultation." accent="red" />
        <EvidenceCard label="2023-2025" title="NCG process" body="Turned reassurance into continuing planning, consultation, and coordination." accent="red" />
        <EvidenceCard label="Visible signal" title="Strategic asset visibility" body="Made U.S. deterrence more legible to Seoul and its domestic audience." accent="red" style="grid-column:1 / -1;" />
      </div>
    </div>
  </div>
  <div class="scope-note" style="margin-top:0.45rem;font-size:0.82rem;">Interpretation: Seoul demanded reassurance that was not only stronger than before, but also more visible.</div>
</div>

<!--
Purpose: Show why the Korea case is a stronger reassurance case than Japan.
Open: "If Japan wanted more reassurance, South Korea wanted even more."
Beats:
1. Washington Declaration sharpened reassurance.
2. NCG turned it into a continuing process.
3. Use the exercise photo to emphasize that reassurance also had a visible operational side.
4. Peninsula nuclear anxiety makes U.S. credibility more immediate.
Transition: "But stronger reassurance did not erase South Korea's China interface."
Time: 1m25s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell" style="padding:1.9rem 2.6rem 1.45rem;">
  <div class="slide-title" style="font-size:1.74rem;margin-bottom:0.28rem;">South Korea Case 2: Why Seoul Also Kept a China Interface</div>
  <div style="display:grid;grid-template-columns:0.8fr 1.2fr;gap:0.82rem;align-items:start;">
    <div class="photo-card contained-visual" style="height:404px;">
      <img src="/assets/china-korean-peninsula-cover.png" alt="Book cover on China and the Korean Peninsula" />
      <div class="photo-tag gold">Peninsula Context</div>
      <div class="photo-caption" style="font-size:0.76rem;">China still matters around the peninsula.</div>
    </div>
    <div style="display:grid;gap:0.6rem;">
      <div style="display:grid;gap:0.6rem;">
        <div class="panel" style="padding:0.78rem 0.84rem;">
          <div class="mini-label gold-label">Why China still matters</div>
          <h3>More than trade</h3>
          <p>China still matters for North Korea, peninsula stability, and the wider diplomatic environment around Korea.</p>
        </div>
        <EvidenceCard label="2024 May" title="Korea-China foreign ministers' meeting" body="Seoul reaffirmed mutual respect, reciprocity, shared interests, and strategic communication." accent="gold" />
      </div>
    </div>
  </div>
  <div class="scope-note" style="margin-top:0.36rem;font-size:0.78rem;">Seoul wanted stronger U.S. insurance without erasing diplomatic room with China.</div>
</div>

<!--
Purpose: Explain why South Korea keeps a thicker China interface than Japan.
Open: "South Korea did not abandon its China interface, because the strategic costs were too high."
Beats:
1. China matters beyond economics because of the peninsula.
2. The foreign ministers' meeting shows the interface was preserved.
3. The book cover helps signal the wider peninsula context behind Seoul's diplomacy.
4. This is alliance management under tighter constraints, not anti-alliance behavior.
Transition: "Now we can compare the two countries directly."
Time: 1m15s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell">
  <div class="slide-title">Japan and South Korea: Same Dilemma, Different Balance</div>
  <div class="comparison-wrap">
    <table class="comparison-table">
      <thead>
        <tr>
          <th></th>
          <th>Japan</th>
          <th>South Korea</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="row-label">Security insurance</td>
          <td>Institutional trilateralism plus bilateral extended deterrence</td>
          <td>Washington Declaration, NCG, and stronger visibility of reassurance</td>
        </tr>
        <tr>
          <td class="row-label">China interface</td>
          <td>Narrower and more controlled: hotline plus economic dialogue</td>
          <td>Thicker and more necessary: diplomacy shaped by peninsula realities</td>
        </tr>
        <tr>
          <td class="row-label">Main driver</td>
          <td>Balancing against sharper regional insecurity</td>
          <td>Balancing plus stronger exposure to nuclear and diplomatic spillover</td>
        </tr>
        <tr>
          <td class="row-label">Bottom line</td>
          <td>Balancing-heavy</td>
          <td>Interface-heavy</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<!--
Purpose: Make the two-case distinction memorable.
Open: "The logic is the same in both cases, but the weighting is different."
Beats:
1. Japan is more balancing-heavy.
2. South Korea is more interface-heavy.
3. Both still fit the same alliance-management framework.
Transition: "Once we compare them, we can scale the argument up to the regional level."
Time: 1m10s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell" style="padding:1.85rem 2.55rem 1.35rem;">
  <div class="slide-title" style="font-size:1.8rem;margin-bottom:0.24rem;">What This Says About Northeast Asia</div>
  <div class="slide-lead" style="margin-bottom:0.62rem;font-size:0.94rem;">The region is becoming bifurcated by function, not fully split by membership.</div>
  <div style="display:grid;grid-template-columns:0.82fr 1.18fr;gap:0.82rem;align-items:start;">
    <div style="display:grid;gap:0.72rem;">
      <div class="photo-card" style="height:170px;">
        <img src="/assets/camp-david-2023.jpg" alt="Leaders at Camp David in August 2023" />
        <div class="photo-tag blue">Hard-security lane</div>
        <div class="photo-caption" style="font-size:0.76rem;">Institutionalized security cooperation</div>
      </div>
      <div class="photo-card" style="height:170px;">
        <img src="/assets/cjk-summit-2024.jpg" alt="Leaders at the CJK Summit in Seoul in May 2024" />
        <div class="photo-tag gold">Interface lane</div>
        <div class="photo-caption" style="font-size:0.76rem;">Diplomatic and functional channels remained active</div>
      </div>
    </div>
    <div style="display:grid;gap:0.72rem;">
      <div class="lane-card blue" style="padding:0.86rem 0.96rem;">
        <div class="mini-label blue-label">Upper layer</div>
        <h3>Hard-security lane</h3>
        <p style="font-size:0.84rem;line-height:1.34;">Deterrence, consultation, exercises, and extended deterrence are increasingly organized through U.S.-Japan-ROK mechanisms.</p>
        <ul style="margin-top:0.42rem;">
          <li>U.S. - Japan - South Korea</li>
          <li>Camp David, extended deterrence, NCG</li>
        </ul>
      </div>
      <div class="lane-card gold" style="padding:0.86rem 0.96rem;">
        <div class="mini-label gold-label">Lower layer</div>
        <h3>China-facing interface lane</h3>
        <p style="font-size:0.84rem;line-height:1.34;">Buffering, diplomacy, economic governance, and crisis management still depend on China-linked channels.</p>
        <ul style="margin-top:0.42rem;">
          <li>China-Japan, China-ROK, and CJK</li>
          <li>Hotline, economic dialogue, foreign ministers, summitry</li>
        </ul>
      </div>
    </div>
  </div>
  <div class="summary-line" style="margin-top:0.5rem;font-size:0.88rem;">Hard security increasingly runs through U.S.-Japan-ROK; buffering, diplomacy, and governance still require China-facing interfaces.</div>
</div>

<!--
Purpose: Convert the two country cases into a regional-order argument.
Open: "If we put the two cases together, a broader regional logic becomes visible."
Beats:
1. Hard security is increasingly organized through the U.S.-Japan-ROK lane.
2. Buffering and governance still need China-facing channels.
3. The two photos help show that both lanes were real and visible, not just abstract categories.
4. The order is bifurcated by function, not fully split by membership.
Transition: "A final check is whether this pattern survived beyond 2025."
Time: 1m20s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell">
  <div class="slide-title">Did the Pattern Stop in 2025?</div>
  <div class="validation-grid">
    <EvidenceCard label="After 2025" title="U.S.-Japan-ROK track kept deepening" body="Later meetings and coordinating machinery suggest continuing institutional consolidation." accent="blue" />
    <EvidenceCard label="After 2025" title="CJK track remained slower but alive" body="The China-facing side did not vanish, even if it moved at a more cautious pace." accent="gold" />
  </div>
  <div class="summary-line">Later evidence validates the pattern rather than overturning it.</div>
</div>

<!--
Purpose: Validate the argument with post-2025 evidence without starting a new section.
Open: "A reasonable challenge is whether this pattern ended in 2025. It did not."
Beats:
1. The U.S.-Japan-ROK side kept deepening.
2. The CJK side remained slower but alive.
3. The post-2025 evidence supports the original argument.
Transition: "So let me end with the shortest version of the claim."
Time: 50s
-->

---
layout: statement
class: text-center
---

<div class="statement-wrap">
  <div class="statement-main">Japan and South Korea use two institutional tracks to manage two strategic risks.</div>
  <div class="statement-sub">U.S. security insurance reduces abandonment. China-facing interfaces reduce entrapment and instability.</div>
  <div class="statement-trace">
    <span class="trace-pill">Alliance management</span>
    <span class="trace-pill">Balancing-heavy Japan</span>
    <span class="trace-pill">Interface-heavy South Korea</span>
  </div>
</div>

<!--
Purpose: Leave the audience with one sentence they can remember.
Open: "My conclusion is simple."
Beats:
1. Japan and South Korea are not simply choosing one side.
2. They manage two strategic risks through two institutional tracks.
3. This is the clearest sign of a bifurcated but still connected regional order.
Transition: "End."
Time: 50s
-->

---
layout: none
class: px-0 py-0
---

<div class="page-shell" style="padding:1.7rem 2.2rem 1.3rem;">
  <div class="slide-title" style="font-size:1.9rem;">Selected References</div>
  <div class="reference-grid">
    <div class="reference-card">
      <h3>Official Documents</h3>
      <ul class="reference-list">
        <li>White House / Kantei. 2023. <i>The Spirit of Camp David</i>; <i>Commitment to Consult</i>; <i>Camp David Principles</i>.</li>
        <li>White House. 2023. <i>Washington Declaration</i>.</li>
        <li>U.S. Department of Defense. 2024. <i>Japan-United States-Republic of Korea Trilateral Ministerial Joint Press Statement</i>.</li>
        <li>MOFA Japan / U.S. DoD. 2024. <i>Joint Statement of the U.S.-Japan Ministerial Meeting on Extended Deterrence</i>; <i>Guidelines for Extended Deterrence</i>.</li>
        <li>U.S. Department of Defense. 2025. <i>Joint Press Statement on the Fourth Nuclear Consultative Group Meeting</i>.</li>
        <li>Japan MOD / MOFA Japan / ROK MOFA / FMPRC. 2023-2025. Japan-China hotline; Japan-China economic dialogue; Korea-China FM meeting; 9th summit and 11th trilateral FM meeting.</li>
      </ul>
    </div>
    <div class="reference-card">
      <h3>Scholarship and Analysis</h3>
      <ul class="reference-list">
        <li>Tsuruoka, Michito. <i>US Nuclear Weapons and US Alliances in North-East Asia</i>.</li>
        <li>Goh, Evelyn. <i>The Asia Pacific's “Age of Uncertainty”</i>.</li>
        <li><i>East Asia's Alliance Dilemma: Public Perceptions of the Competing Risks of Extended Nuclear Deterrence</i>. 2024.</li>
        <li><i>After Hedging</i>. 2023.</li>
        <li><i>Security-Economics Tradeoff: Public Support for the Quad in South Korea</i>. 2024.</li>
        <li><i>Soft Wedging: China's Strategic Response to the Japan-South Korea Entente under U.S.-led Trilateral Security Cooperation</i>. 2025.</li>
      </ul>
      <div class="reference-note">Analytical keywords: alliance management, abandonment, entrapment, interface preservation, functional bifurcation.</div>
    </div>
  </div>
</div>

<!--
Purpose: Provide a clean end-of-deck reference page without overloading the argument slides.
Open: "I will stop here, and these are the core references behind the deck."
Beats:
1. Point to the official-document column first.
2. Then point to the scholarship column.
3. Mention that the full source ledger is available in the project workspace.
Transition: "End."
Time: 20s
-->
