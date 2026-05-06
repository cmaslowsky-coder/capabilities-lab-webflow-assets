* { margin: 0; padding: 0; box-sizing: border-box; }
html, body { overflow-x: hidden; }
body {
  background: #0d4036;
  color: #143830;
  font-family: 'Inter', system-ui, sans-serif;
  line-height: 1.55;
  -webkit-font-smoothing: antialiased;
}

/* ═══ WORLD ═══ */
.jungle { position: relative; height: 700vh; }

.sky, .plane, .vignette {
  position: fixed;
  top: 0; left: 0;
  width: 100vw;
  height: 100vh;
  pointer-events: none;
}

/* Brighter tropical sky — sun-warmed top to deep emerald bottom */
.sky {
  z-index: 1;
  background: linear-gradient(180deg,
    #fff5d8 0%,
    #fce8a8 5%,
    #f5dd8a 10%,
    #d8e885 18%,
    #aedb78 26%,
    #7ecc66 36%,
    #5ab068 46%,
    #3d9a62 56%,
    #2c8458 66%,
    #1f6e4d 76%,
    #155947 86%,
    #0d4036 100%);
  background-size: 100% 700vh;
  background-position: 0 0;
  background-repeat: no-repeat;
}

/* Depth planes */
.plane { will-change: transform; }
.plane.far    { z-index: 2; }
.plane.back   { z-index: 3; }
.plane.mid    { z-index: 4; }
.plane.lights { z-index: 5; mix-blend-mode: screen; opacity: 0.55; }
.plane.near   { z-index: 6; }

.plant {
  position: absolute;
  left: 50%;
  transform: translate(-50%, -50%);
}
.plant svg { display: block; width: 100%; height: 100%; }

/* Subtle vignette — much lighter than before */
.vignette {
  z-index: 50;
  background: radial-gradient(ellipse at center, transparent 55%, rgba(10, 40, 30, 0.35) 100%);
}

/* ═══ CONTENT ═══ */
.content { position: relative; z-index: 100; }

.zone {
  min-height: 100vh;
  padding: 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

/* Cream card — the central readable container */
.card {
  background: rgba(253, 248, 235, 0.96);
  backdrop-filter: blur(6px);
  -webkit-backdrop-filter: blur(6px);
  padding: clamp(2rem, 4vw, 3rem) clamp(1.8rem, 4vw, 3.2rem);
  max-width: min(720px, 92vw);
  width: 100%;
  border-radius: 3px;
  box-shadow:
    0 30px 80px rgba(10, 30, 20, 0.28),
    0 8px 20px rgba(10, 30, 20, 0.12);
  border-top: 1px solid rgba(255, 255, 255, 0.7);
  border-left: 1px solid rgba(255, 255, 255, 0.4);
  position: relative;
}
.card.wide { max-width: min(880px, 94vw); }

.eyebrow {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-weight: 400;
  font-size: 0.78rem;
  letter-spacing: 0.35em;
  text-transform: uppercase;
  color: #b8722a;
  margin-bottom: 1.4rem;
  display: block;
}

h1, h2, h3 {
  font-family: 'Cormorant Garamond', serif;
  font-weight: 300;
  color: #143830;
  letter-spacing: -0.01em;
}

h1 {
  font-size: clamp(2.6rem, 6vw, 4.4rem);
  line-height: 1.02;
  margin-bottom: 1.2rem;
}
h1 em { font-style: italic; color: #1d6b4f; font-weight: 400; }

h2 {
  font-size: clamp(2rem, 4.5vw, 3rem);
  line-height: 1.08;
  margin-bottom: 1.4rem;
}
h2 em { font-style: italic; color: #1d6b4f; }

h3 {
  font-size: clamp(1.3rem, 2.4vw, 1.65rem);
  line-height: 1.2;
  margin-bottom: 0.4rem;
  font-weight: 400;
}

.subtitle {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: clamp(1.1rem, 1.6vw, 1.35rem);
  color: #2a5544;
  line-height: 1.5;
  margin-bottom: 1.5rem;
}

.body {
  font-size: clamp(0.98rem, 1.15vw, 1.08rem);
  line-height: 1.7;
  color: #2a4d3c;
  margin-bottom: 1rem;
}
.body strong { color: #143830; font-weight: 600; }

/* ─── Hero ─── */
.zone.hero { color: #143830; }
.zone.hero .card { background: rgba(253, 248, 235, 0.78); padding: clamp(2.2rem, 4.5vw, 3.5rem); text-align: center; }
.brand {
  font-family: 'Inter', sans-serif;
  font-size: 0.78rem;
  font-weight: 500;
  letter-spacing: 0.4em;
  text-transform: uppercase;
  color: #b8722a;
  margin-bottom: 1.6rem;
  display: block;
}
.zone.hero h1 { color: #0d3a30; }
.zone.hero .tagline {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: clamp(1.1rem, 1.6vw, 1.3rem);
  color: #2a5544;
  line-height: 1.55;
  max-width: 540px;
  margin: 0 auto;
}
.scroll-cue {
  position: absolute;
  bottom: 3rem;
  left: 50%;
  transform: translateX(-50%);
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: 0.78rem;
  letter-spacing: 0.4em;
  text-transform: uppercase;
  color: rgba(20, 60, 40, 0.65);
  animation: pulse 3s ease-in-out infinite;
}
@keyframes pulse {
  0%,100% { opacity: 0.45; transform: translateX(-50%) translateY(0); }
  50% { opacity: 0.9; transform: translateX(-50%) translateY(8px); }
}

/* ─── Stat callout ─── */
.stat {
  margin: 1.8rem 0 1.4rem;
  padding: 1.4rem 1.6rem;
  border-left: 3px solid #b8722a;
  background: rgba(184, 114, 42, 0.06);
}
.stat .num {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: clamp(2.2rem, 4vw, 3rem);
  font-weight: 400;
  color: #b8722a;
  line-height: 1;
  margin-bottom: 0.4rem;
  display: block;
}
.stat .text {
  font-size: 0.98rem;
  color: #2a4d3c;
  line-height: 1.55;
}
.stat .source {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: 0.85rem;
  color: #6b8a78;
  margin-top: 0.6rem;
  display: block;
}

/* ─── Pain list ─── */
.pains { list-style: none; margin-top: 1rem; }
.pains li {
  display: flex;
  gap: 1.2rem;
  margin-bottom: 1.4rem;
  align-items: baseline;
}
.pains .num {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: 1.7rem;
  color: #b8722a;
  font-weight: 400;
  flex-shrink: 0;
  min-width: 1.8rem;
  line-height: 1;
}
.pains .text {
  font-size: 0.98rem;
  line-height: 1.6;
  color: #2a4d3c;
}
.pains .text strong { color: #143830; font-weight: 600; }

/* ─── Sector list ─── */
.sectors {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0.8rem 2rem;
  margin-top: 1.4rem;
  padding-top: 1.2rem;
  border-top: 1px solid rgba(20, 56, 48, 0.15);
}
.sector {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: 1.15rem;
  color: #1d6b4f;
  padding: 0.4rem 0;
}

/* ─── Service grid ─── */
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.2rem;
  margin-top: 1.4rem;
}
.service {
  padding: 1rem 0.8rem 1rem 1rem;
  border-left: 2px solid #b8722a;
}
.service h3 {
  font-size: 1.05rem;
  font-weight: 500;
  color: #143830;
  margin-bottom: 0.4rem;
  line-height: 1.25;
}
.service p {
  font-size: 0.86rem;
  line-height: 1.5;
  color: #44665a;
}

/* ─── Outcomes grid ─── */
.outcomes {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0.5rem 2rem;
  margin-top: 1.2rem;
}
.outcome {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: 1.05rem;
  color: #1d6b4f;
  padding: 0.4rem 0;
  border-bottom: 1px solid rgba(20, 56, 48, 0.1);
}

/* ─── Coda ─── */
.zone.coda .card { text-align: center; }
.zone.coda .quote {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-weight: 300;
  font-size: clamp(1.4rem, 2.6vw, 2rem);
  line-height: 1.4;
  color: #143830;
  margin-bottom: 1.8rem;
}
.cta {
  display: inline-block;
  padding: 0.85rem 2rem;
  background: #143830;
  color: #fdf8eb;
  text-decoration: none;
  font-family: 'Inter', sans-serif;
  font-size: 0.85rem;
  font-weight: 500;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  border-radius: 2px;
  transition: background 0.3s ease;
  margin-top: 0.8rem;
}
.cta:hover { background: #1d6b4f; }
.colophon {
  font-family: 'Cormorant Garamond', serif;
  font-size: 0.78rem;
  letter-spacing: 0.4em;
  text-transform: uppercase;
  color: #b8722a;
  opacity: 0.85;
  margin-top: 2.4rem;
  display: block;
}

/* ─── Mobile ─── */
@media (max-width: 720px) {
  .services { grid-template-columns: 1fr; gap: 1rem; }
  .outcomes { grid-template-columns: 1fr; }
  .sectors { grid-template-columns: 1fr; gap: 0.4rem; }
  .pains li { gap: 0.8rem; }
  .pains .num { font-size: 1.4rem; }
}
