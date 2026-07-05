:root {
  --ink: #151617;
  --muted: #707479;
  --line: #d9dcdf;
  --paper: #f4f3ef;
  --white: #fcfcfa;
  --blue: #4169e1;
  --blue-soft: #dce4ff;
  --dark: #111315;
  --sans: "DM Sans", "Noto Sans SC", sans-serif;
  --cn: "Noto Sans SC", sans-serif;
  --side: clamp(24px, 6vw, 96px);
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 84px;
}

body {
  color: var(--ink);
  background: var(--paper);
  font-family: var(--sans);
  font-size: 16px;
  line-height: 1.7;
  overflow-x: hidden;
  -webkit-font-smoothing: antialiased;
}

body.menu-open {
  overflow: hidden;
}

a {
  color: inherit;
  text-decoration: none;
}

button {
  color: inherit;
  font: inherit;
}

::selection {
  color: var(--white);
  background: var(--blue);
}

.noise {
  position: fixed;
  z-index: 999;
  inset: 0;
  pointer-events: none;
  opacity: 0.035;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 180 180' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.9' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='.65'/%3E%3C/svg%3E");
}

.site-header {
  position: fixed;
  z-index: 100;
  top: 0;
  left: 0;
  width: 100%;
  height: 84px;
  padding: 0 var(--side);
  display: flex;
  align-items: center;
  justify-content: space-between;
  transition: background 0.3s ease, box-shadow 0.3s ease, height 0.3s ease;
}

.site-header.scrolled {
  height: 68px;
  background: rgba(244, 243, 239, 0.86);
  box-shadow: 0 1px 0 rgba(21, 22, 23, 0.08);
  backdrop-filter: blur(14px);
}

.logo {
  display: flex;
  align-items: center;
  gap: 11px;
  font-size: 14px;
  font-weight: 600;
  letter-spacing: 0.08em;
}

.logo i {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: var(--blue);
}

.nav {
  display: flex;
  align-items: center;
  gap: clamp(24px, 3vw, 48px);
}

.nav a {
  position: relative;
  color: #46494d;
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.nav a::after {
  position: absolute;
  bottom: -7px;
  left: 0;
  width: 0;
  height: 1px;
  content: "";
  background: var(--blue);
  transition: width 0.25s ease;
}

.nav a:hover::after,
.nav a.active::after {
  width: 100%;
}

.menu-toggle {
  display: none;
  width: 42px;
  height: 42px;
  border: 0;
  background: transparent;
  cursor: pointer;
}

.menu-toggle span {
  display: block;
  width: 22px;
  height: 1px;
  margin: 6px auto;
  background: var(--ink);
  transition: transform 0.25s ease;
}

.hero {
  position: relative;
  min-height: 100vh;
  min-height: 720px;
  padding: 130px var(--side) 74px;
  display: flex;
  align-items: center;
  overflow: hidden;
  background:
    radial-gradient(circle at 76% 47%, rgba(65, 105, 225, 0.09), transparent 25%),
    linear-gradient(115deg, var(--white) 0%, var(--paper) 58%, #eceef4 100%);
}

.hero::before {
  position: absolute;
  right: 18%;
  bottom: -13%;
  width: 1px;
  height: 82%;
  content: "";
  background: linear-gradient(transparent, rgba(21, 22, 23, 0.2), transparent);
  transform: rotate(42deg);
}

.hero-content {
  position: relative;
  z-index: 3;
  width: min(810px, 73%);
}

.eyebrow {
  margin-bottom: 24px;
  color: var(--blue);
  font-size: 11px;
  font-weight: 600;
  letter-spacing: 0.24em;
}

.hero h1 {
  font-family: var(--cn);
  font-size: clamp(76px, 10.5vw, 158px);
  font-weight: 500;
  letter-spacing: -0.07em;
  line-height: 0.95;
}

.accent {
  color: var(--blue);
}

.hero-role {
  margin: 30px 0 16px;
  color: #303337;
  font-family: var(--cn);
  font-size: clamp(17px, 2vw, 24px);
  font-weight: 400;
  letter-spacing: 0.06em;
}

.hero-intro {
  max-width: 650px;
  color: var(--muted);
  font-family: var(--cn);
  font-size: clamp(15px, 1.3vw, 18px);
  font-weight: 300;
  line-height: 2;
}

.button {
  width: 150px;
  height: 52px;
  margin-top: 36px;
  padding: 0 21px;
  display: inline-flex;
  align-items: center;
  justify-content: space-between;
  color: var(--white);
  background: var(--dark);
  border-radius: 2px;
  font-family: var(--cn);
  font-size: 13px;
  transition: transform 0.25s ease, background 0.25s ease;
}

.button:hover {
  background: var(--blue);
  transform: translateY(-3px);
}

.button-arrow {
  font-size: 18px;
  transition: transform 0.25s ease;
}

.button:hover .button-arrow {
  transform: translate(3px, 3px);
}

.hero-orbit {
  position: absolute;
  z-index: 1;
  border: 1px solid rgba(21, 22, 23, 0.14);
  border-radius: 50%;
}

.orbit-one {
  top: 15%;
  right: -8%;
  width: clamp(390px, 45vw, 690px);
  aspect-ratio: 1;
}

.orbit-two {
  top: 31%;
  right: 4%;
  width: clamp(240px, 27vw, 420px);
  aspect-ratio: 1;
  border-color: rgba(65, 105, 225, 0.2);
}

.hero-dot {
  position: absolute;
  z-index: 2;
  border-radius: 50%;
}

.dot-one {
  top: 21%;
  right: 16%;
  width: 13px;
  height: 13px;
  background: var(--blue);
  box-shadow: 0 0 0 9px rgba(65, 105, 225, 0.1);
}

.dot-two {
  right: 33%;
  bottom: 17%;
  width: 8px;
  height: 8px;
  background: var(--ink);
}

.hero-index {
  position: absolute;
  z-index: 3;
  right: var(--side);
  bottom: 74px;
  display: grid;
  gap: 7px;
  color: var(--muted);
  font-size: 9px;
  letter-spacing: 0.19em;
  text-align: right;
}

.scroll-hint {
  position: absolute;
  z-index: 3;
  bottom: 42px;
  left: 50%;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 10px;
  color: var(--muted);
  font-size: 8px;
  letter-spacing: 0.2em;
  transform: translateX(-50%);
}

.scroll-hint i {
  position: relative;
  width: 1px;
  height: 35px;
  overflow: hidden;
  background: var(--line);
}

.scroll-hint i::after {
  position: absolute;
  top: -100%;
  left: 0;
  width: 100%;
  height: 100%;
  content: "";
  background: var(--blue);
  animation: scroll-line 2s ease-in-out infinite;
}

.hero-reveal {
  opacity: 0;
  transform: translateY(24px);
  animation: hero-in 0.8s cubic-bezier(0.2, 0.7, 0.2, 1) forwards;
}

.hero-reveal:nth-child(2) { animation-delay: 0.1s; }
.hero-reveal:nth-child(3) { animation-delay: 0.2s; }
.hero-reveal:nth-child(4) { animation-delay: 0.3s; }
.hero-reveal:nth-child(5) { animation-delay: 0.4s; }

.section {
  padding: clamp(100px, 12vw, 180px) var(--side);
}

.section-heading {
  display: grid;
  grid-template-columns: clamp(65px, 9vw, 140px) 1fr;
  margin-bottom: clamp(60px, 8vw, 110px);
}

.section-number {
  padding-top: 3px;
  color: var(--muted);
  font-size: 10px;
  letter-spacing: 0.18em;
}

.section-heading .eyebrow {
  margin-bottom: 16px;
}

.section h2,
.contact h2 {
  font-family: var(--cn);
  font-size: clamp(34px, 4.5vw, 65px);
  font-weight: 400;
  letter-spacing: -0.04em;
  line-height: 1.35;
}

.about {
  background: var(--paper);
}

.about-grid {
  display: grid;
  grid-template-columns: minmax(270px, 0.8fr) minmax(400px, 1.2fr);
  gap: clamp(50px, 9vw, 150px);
  padding-left: clamp(65px, 9vw, 140px);
}

.about-mark {
  position: relative;
  min-height: 420px;
  display: grid;
  place-items: center;
  overflow: hidden;
  background:
    linear-gradient(rgba(255,255,255,0.6), rgba(255,255,255,0.6)),
    repeating-linear-gradient(90deg, transparent 0 39px, rgba(21,22,23,0.06) 40px),
    repeating-linear-gradient(0deg, transparent 0 39px, rgba(21,22,23,0.06) 40px);
  border: 1px solid var(--line);
}

.about-mark::before,
.about-mark::after {
  position: absolute;
  content: "";
  border-radius: 50%;
}

.about-mark::before {
  top: 12%;
  right: -25%;
  width: 70%;
  aspect-ratio: 1;
  border: 1px solid rgba(65, 105, 225, 0.3);
}

.about-mark::after {
  bottom: 14%;
  left: 15%;
  width: 9px;
  height: 9px;
  background: var(--blue);
}

.about-mark > span {
  z-index: 1;
  font-family: var(--cn);
  font-size: clamp(110px, 15vw, 190px);
  font-weight: 300;
}

.about-mark-caption {
  position: absolute;
  right: 19px;
  bottom: 18px;
  color: var(--muted);
  font-size: 8px;
  letter-spacing: 0.16em;
  line-height: 1.8;
  text-align: right;
}

.about-copy {
  max-width: 700px;
  align-self: center;
}

.about-copy p {
  margin-bottom: 23px;
  color: #62666a;
  font-family: var(--cn);
  font-weight: 300;
  line-height: 2.05;
}

.about-copy .lead {
  margin-bottom: 30px;
  color: var(--ink);
  font-size: clamp(20px, 2vw, 28px);
  font-weight: 400;
  line-height: 1.75;
}

.about-meta {
  margin-top: 45px;
  padding-top: 20px;
  display: flex;
  flex-wrap: wrap;
  gap: 22px 35px;
  border-top: 1px solid var(--line);
}

.about-meta span {
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.08em;
}

.about-meta i {
  margin-right: 8px;
  color: var(--blue);
  font-size: 9px;
  font-style: normal;
}

.direction {
  background: var(--white);
}

.direction-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 14px;
  padding-left: clamp(65px, 9vw, 140px);
}

.direction-card {
  min-height: 330px;
  padding: clamp(28px, 3.5vw, 48px);
  display: flex;
  flex-direction: column;
  background: var(--paper);
  border: 1px solid transparent;
  transition: transform 0.35s ease, border-color 0.35s ease, box-shadow 0.35s ease;
}

.direction-card:hover {
  z-index: 2;
  border-color: var(--blue);
  box-shadow: 0 24px 60px rgba(21, 22, 23, 0.08);
  transform: translateY(-7px);
}

.card-top {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.card-number {
  color: var(--muted);
  font-size: 9px;
  letter-spacing: 0.18em;
}

.card-icon {
  color: var(--blue);
  font-size: 25px;
  font-weight: 300;
}

.direction-card h3 {
  margin-top: auto;
  font-size: clamp(22px, 2vw, 29px);
  font-weight: 500;
  letter-spacing: -0.03em;
}

.direction-card p {
  max-width: 520px;
  margin-top: 14px;
  color: var(--muted);
  font-family: var(--cn);
  font-size: 14px;
  font-weight: 300;
  line-height: 1.9;
}

.card-tag {
  margin-top: 25px;
  color: #8c9094;
  font-size: 9px;
  letter-spacing: 0.16em;
  text-transform: uppercase;
}

.skills {
  background: var(--paper);
}

.skills-list {
  padding-left: clamp(65px, 9vw, 140px);
}

.skill-group {
  padding: 34px 0;
  display: grid;
  grid-template-columns: minmax(245px, 0.7fr) 1.3fr;
  gap: 35px;
  align-items: start;
  border-top: 1px solid var(--line);
}

.skill-group:last-child {
  border-bottom: 1px solid var(--line);
}

.skill-title {
  display: flex;
  gap: 22px;
  align-items: baseline;
}

.skill-title span {
  color: var(--blue);
  font-size: 9px;
  letter-spacing: 0.15em;
}

.skill-title h3 {
  font-size: clamp(19px, 2vw, 25px);
  font-weight: 500;
  letter-spacing: -0.02em;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.skill-tags span {
  padding: 8px 15px;
  color: #55595d;
  background: rgba(255, 255, 255, 0.68);
  border: 1px solid #dcdee0;
  border-radius: 100px;
  font-family: var(--cn);
  font-size: 12px;
  font-weight: 300;
  transition: color 0.25s ease, border-color 0.25s ease, transform 0.25s ease;
}

.skill-tags span:hover {
  color: var(--blue);
  border-color: var(--blue);
  transform: translateY(-2px);
}

.values {
  position: relative;
  padding: clamp(110px, 14vw, 210px) var(--side);
  overflow: hidden;
  color: var(--white);
  background:
    radial-gradient(circle at 85% 20%, rgba(65, 105, 225, 0.27), transparent 24%),
    var(--dark);
}

.values::before {
  position: absolute;
  top: -30%;
  right: -7%;
  width: min(55vw, 780px);
  aspect-ratio: 1;
  content: "";
  border: 1px solid rgba(255, 255, 255, 0.12);
  border-radius: 50%;
}

.values::after {
  position: absolute;
  right: 12%;
  bottom: -25%;
  width: min(32vw, 480px);
  aspect-ratio: 1;
  content: "";
  border: 1px solid rgba(65, 105, 225, 0.45);
  border-radius: 50%;
}

.values-inner {
  position: relative;
  z-index: 1;
  max-width: 1100px;
}

.eyebrow.light {
  color: #8da6ff;
}

.values blockquote {
  font-family: var(--cn);
  font-size: clamp(32px, 5vw, 72px);
  font-weight: 300;
  letter-spacing: -0.045em;
  line-height: 1.55;
}

.values blockquote span {
  color: #9cb0f5;
}

.values-footer {
  margin-top: clamp(60px, 8vw, 110px);
  padding-top: 20px;
  display: flex;
  justify-content: space-between;
  color: #858a90;
  border-top: 1px solid #33373b;
  font-size: 9px;
  letter-spacing: 0.2em;
}

.contact {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: clamp(60px, 10vw, 160px);
  background: var(--white);
}

.contact-intro > p:not(.eyebrow) {
  margin-top: 28px;
  color: var(--muted);
  font-family: var(--cn);
  font-weight: 300;
}

.mail-link {
  margin-top: 48px;
  padding-bottom: 8px;
  display: inline-flex;
  align-items: center;
  gap: 25px;
  border-bottom: 1px solid var(--ink);
  font-size: clamp(16px, 1.6vw, 22px);
  transition: color 0.25s ease, border-color 0.25s ease;
}

.mail-link:hover {
  color: var(--blue);
  border-color: var(--blue);
}

.mail-link span {
  font-size: 20px;
  transition: transform 0.25s ease;
}

.mail-link:hover span {
  transform: translate(4px, -4px);
}

.contact-details {
  align-self: end;
}

.contact-row {
  padding: 23px 0;
  display: grid;
  grid-template-columns: 105px 1fr;
  gap: 20px;
  color: #4e5256;
  border-top: 1px solid var(--line);
  font-size: 13px;
  line-height: 1.7;
}

.contact-row:last-child {
  border-bottom: 1px solid var(--line);
}

.contact-label {
  color: var(--muted);
  font-size: 9px;
  letter-spacing: 0.16em;
}

.footer {
  padding: 26px var(--side);
  display: flex;
  align-items: center;
  justify-content: space-between;
  color: #8a8d90;
  background: var(--white);
  border-top: 1px solid var(--line);
  font-size: 9px;
  letter-spacing: 0.12em;
}

.footer a {
  transition: color 0.2s ease;
}

.footer a:hover {
  color: var(--blue);
}

.reveal {
  opacity: 0;
  transform: translateY(32px);
  transition: opacity 0.8s ease, transform 0.8s cubic-bezier(0.2, 0.7, 0.2, 1);
}

.reveal.is-visible {
  opacity: 1;
  transform: translateY(0);
}

@keyframes hero-in {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes scroll-line {
  0% { transform: translateY(0); }
  55%, 100% { transform: translateY(200%); }
}

@media (max-width: 900px) {
  .about-grid {
    grid-template-columns: 0.7fr 1fr;
    gap: 45px;
  }

  .skill-group {
    grid-template-columns: 1fr;
    gap: 22px;
  }

  .contact {
    grid-template-columns: 1fr;
  }

  .contact-details {
    max-width: 560px;
  }
}

@media (max-width: 680px) {
  :root {
    --side: 22px;
  }

  html {
    scroll-padding-top: 64px;
  }

  .site-header {
    height: 68px;
  }

  .menu-toggle {
    z-index: 2;
    display: block;
  }

  .menu-open .menu-toggle span:first-child {
    transform: translateY(3.5px) rotate(45deg);
  }

  .menu-open .menu-toggle span:last-child {
    transform: translateY(-3.5px) rotate(-45deg);
  }

  .nav {
    position: fixed;
    inset: 0;
    padding: 100px var(--side) 50px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    gap: 24px;
    visibility: hidden;
    opacity: 0;
    background: rgba(244, 243, 239, 0.98);
    transition: opacity 0.25s ease, visibility 0.25s ease;
  }

  .menu-open .nav {
    visibility: visible;
    opacity: 1;
  }

  .nav a {
    font-size: 32px;
    font-weight: 400;
    letter-spacing: -0.02em;
    text-transform: none;
  }

  .hero {
    min-height: 700px;
    padding-top: 105px;
    align-items: center;
  }

  .hero-content {
    width: 100%;
  }

  .hero h1 {
    font-size: clamp(70px, 24vw, 105px);
  }

  .hero-role {
    margin-top: 25px;
    font-size: 16px;
  }

  .hero-intro {
    max-width: 95%;
    font-size: 14px;
    line-height: 1.9;
  }

  .orbit-one {
    top: 13%;
    right: -60%;
    width: 130vw;
  }

  .orbit-two {
    top: 24%;
    right: -22%;
    width: 72vw;
  }

  .dot-one {
    top: 20%;
    right: 15%;
  }

  .hero-index,
  .scroll-hint {
    display: none;
  }

  .section-heading {
    grid-template-columns: 37px 1fr;
    margin-bottom: 55px;
  }

  .section h2,
  .contact h2 {
    font-size: 35px;
  }

  .about-grid,
  .direction-grid,
  .skills-list {
    padding-left: 0;
  }

  .about-grid {
    grid-template-columns: 1fr;
  }

  .about-mark {
    min-height: 310px;
  }

  .about-mark > span {
    font-size: 125px;
  }

  .about-copy .lead {
    font-size: 20px;
  }

  .direction-grid {
    grid-template-columns: 1fr;
  }

  .direction-card {
    min-height: 285px;
  }

  .skill-group {
    padding: 28px 0;
  }

  .values {
    padding-top: 110px;
    padding-bottom: 110px;
  }

  .values blockquote {
    font-size: 31px;
    line-height: 1.65;
  }

  .values blockquote br {
    display: none;
  }

  .values-footer {
    flex-direction: column;
    gap: 10px;
  }

  .mail-link {
    max-width: 100%;
    gap: 12px;
    font-size: 15px;
  }

  .contact-row {
    grid-template-columns: 88px 1fr;
  }

  .footer {
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
  }
}

@media (prefers-reduced-motion: reduce) {
  html {
    scroll-behavior: auto;
  }

  *,
  *::before,
  *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
  }
}
