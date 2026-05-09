[index_2.html](https://github.com/user-attachments/files/27548280/index_2.html)
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GB Home Loans – 호주 홈론 전문가</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;600;700;800&family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
<style>
:root {
  --navy-deep: #1f333f;
  --navy: #254151;
  --blue-light: #62b0c8;
  --blue-mid: #4288b7;
  --warm-gray: #9f968b;
  --dark-brown: #47433d;
  --charcoal: #292827;
  --gold-start: #F5C800;
  --gold-mid: #FFD700;
  --gold-end: #FFC200;
  --white: #ffffff;
  --off-white: #f5f3ef;
  --text-light: rgba(255,255,255,0.85);
  --gold-gradient: linear-gradient(135deg, #F0C000, #FFD700, #FFE033, #FFD700);
  --gold-text: linear-gradient(135deg, #F5C800, #FFE033, #FFD700);
  --card-bg: rgba(255,255,255,0.04);
  --border-gold: rgba(255,215,0,0.3);
  --border-subtle: rgba(98,176,200,0.15);
}

* { margin: 0; padding: 0; box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  background: var(--navy-deep);
  color: var(--white);
  overflow-x: hidden;
  word-break: keep-all;
  -webkit-font-smoothing: antialiased;
}

/* ─── UTILITY ─── */
.gold-text {
  background: var(--gold-text);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
.section-tag {
  display: inline-block;
  font-size: 11px;
  font-weight: 600;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: var(--blue-light);
  border: 1px solid var(--border-subtle);
  padding: 5px 14px;
  border-radius: 20px;
  margin-bottom: 16px;
}

/* ─── FLOATING NAV ─── */
nav {
  position: fixed;
  top: 0; left: 0; right: 0;
  z-index: 100;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 16px 40px;
  background: rgba(31,51,63,0.92);
  backdrop-filter: blur(16px);
  border-bottom: 1px solid var(--border-gold);
}
.nav-logo-wrap { text-decoration: none; display: flex; align-items: center; }
.nav-logo {
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  font-size: 18px;
  font-weight: 800;
  letter-spacing: -0.3px;
}
.nav-links {
  display: flex;
  gap: 32px;
  list-style: none;
}
.nav-links a {
  color: var(--text-light);
  text-decoration: none;
  font-size: 14px;
  font-weight: 500;
  transition: color 0.2s;
}
.nav-links a:hover { color: var(--gold-mid); }
.nav-cta {
  background: var(--gold-gradient);
  color: var(--charcoal);
  padding: 9px 22px;
  border-radius: 6px;
  font-weight: 600;
  font-size: 14px;
  text-decoration: none;
  transition: opacity 0.2s, transform 0.2s;
}
.nav-cta:hover { opacity: 0.9; transform: translateY(-1px); }

/* ─── HERO ─── */
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 120px 24px 80px;
  position: relative;
  overflow: hidden;
  background: radial-gradient(ellipse at 30% 50%, rgba(66,136,183,0.12) 0%, transparent 60%),
              radial-gradient(ellipse at 70% 20%, rgba(201,162,39,0.08) 0%, transparent 50%),
              var(--navy-deep);
}
.hero::before {
  content: '';
  position: absolute;
  top: -100px; left: -100px; right: -100px; bottom: -100px;
  background-image: 
    radial-gradient(1px 1px at 20% 30%, rgba(98,176,200,0.4) 0%, transparent 100%),
    radial-gradient(1px 1px at 80% 70%, rgba(201,162,39,0.3) 0%, transparent 100%),
    radial-gradient(1px 1px at 50% 20%, rgba(98,176,200,0.2) 0%, transparent 100%);
  pointer-events: none;
}
.hero-eyebrow {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 24px;
  animation: fadeUp 0.8s ease both;
}
.hero-eyebrow span {
  font-size: 12px;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: var(--blue-light);
  font-weight: 500;
}
.eyebrow-line { width: 40px; height: 1px; background: var(--blue-light); opacity: 0.5; }
.hero h1 {
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  font-size: clamp(28px, 4.5vw, 58px);
  line-height: 1.25;
  font-weight: 800;
  letter-spacing: -1px;
  margin-bottom: 20px;
  max-width: 820px;
  animation: fadeUp 0.8s 0.1s ease both;
  word-break: keep-all;
}
.hero-line1 {
  display: inline-block;
  white-space: nowrap;
  font-size: clamp(22px, 3.5vw, 46px);
  font-weight: 700;
  color: rgba(255,255,255,0.92);
  letter-spacing: -0.5px;
}
.hero p {
  font-size: clamp(14px, 1.5vw, 17px);
  color: var(--text-light);
  max-width: 480px;
  line-height: 1.9;
  margin-bottom: 40px;
  animation: fadeUp 0.8s 0.2s ease both;
  font-weight: 400;
}
.hero-buttons {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
  justify-content: center;
  animation: fadeUp 0.8s 0.3s ease both;
}
.btn-primary {
  background: var(--gold-gradient);
  color: var(--charcoal);
  padding: 16px 36px;
  border-radius: 8px;
  font-weight: 700;
  font-size: 16px;
  text-decoration: none;
  transition: transform 0.2s, box-shadow 0.2s;
  box-shadow: 0 4px 24px rgba(255,215,0,0.3);
}
.btn-primary:hover { transform: translateY(-2px); box-shadow: 0 8px 32px rgba(255,215,0,0.4); }
.btn-kakao {
  display: flex;
  align-items: center;
  gap: 10px;
  background: #FEE500;
  color: #3C1E1E;
  padding: 16px 28px;
  border-radius: 8px;
  font-weight: 700;
  font-size: 15px;
  text-decoration: none;
  transition: transform 0.2s;
}
.btn-kakao:hover { transform: translateY(-2px); }
.kakao-icon { width: 22px; height: 22px; }
.hero-stats {
  display: flex;
  gap: 48px;
  margin-top: 64px;
  padding-top: 48px;
  border-top: 1px solid var(--border-gold);
  animation: fadeUp 0.8s 0.4s ease both;
  flex-wrap: wrap;
  justify-content: center;
}
.stat { text-align: center; }
.stat-num {
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  font-size: 32px;
  font-weight: 800;
  letter-spacing: -0.5px;
  background: var(--gold-text);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
.stat-label {
  font-size: 12px;
  font-weight: 500;
  color: var(--warm-gray);
  margin-top: 5px;
  letter-spacing: 0.2px;
}
.scroll-indicator {
  position: absolute;
  bottom: 32px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
  color: var(--warm-gray);
  font-size: 11px;
  letter-spacing: 2px;
  text-transform: uppercase;
  animation: bounce 2s infinite;
}
.scroll-arrow {
  width: 1px;
  height: 40px;
  background: linear-gradient(to bottom, var(--warm-gray), transparent);
}

/* ─── CALCULATOR ─── */
.calculator-section {
  padding: 100px 24px;
  background: linear-gradient(180deg, var(--navy-deep) 0%, var(--navy) 100%);
}
.container { max-width: 1100px; margin: 0 auto; }
.section-header { text-align: center; margin-bottom: 60px; }
.section-header h2 {
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  font-size: clamp(26px, 3.2vw, 42px);
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.25;
  margin-bottom: 14px;
}
.section-header p {
  color: var(--text-light);
  font-size: 16px;
  max-width: 520px;
  margin: 0 auto;
  line-height: 1.8;
  font-weight: 400;
}
.calc-wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 32px;
  background: var(--card-bg);
  border: 1px solid var(--border-gold);
  border-radius: 20px;
  padding: 48px;
  backdrop-filter: blur(10px);
  position: relative;
  overflow: hidden;
}
.calc-wrapper::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 2px;
  background: var(--gold-gradient);
}
.calc-inputs h3 {
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: -0.3px;
  margin-bottom: 24px;
  color: var(--blue-light);
}
.form-group { margin-bottom: 18px; }
.form-group label {
  display: block;
  font-size: 12px;
  font-weight: 600;
  color: var(--warm-gray);
  margin-bottom: 7px;
  letter-spacing: 0.8px;
  text-transform: uppercase;
}
.input-wrap { position: relative; }
.input-prefix {
  position: absolute;
  left: 14px;
  top: 50%;
  transform: translateY(-50%);
  color: var(--gold-mid);
  font-weight: 600;
  font-size: 15px;
}
.form-group input,
.form-group select {
  width: 100%;
  background: rgba(255,255,255,0.06);
  border: 1px solid rgba(98,176,200,0.2);
  border-radius: 8px;
  padding: 13px 14px 13px 28px;
  color: var(--white);
  font-size: 15px;
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  transition: border-color 0.2s, background 0.2s;
}
.form-group select { padding-left: 14px; }
.form-group input:focus,
.form-group select:focus {
  outline: none;
  border-color: var(--gold-mid);
  background: rgba(255,215,0,0.05);
}
.form-group select option { background: var(--navy); }
.calc-btn {
  width: 100%;
  background: var(--gold-gradient);
  color: var(--charcoal);
  border: none;
  padding: 16px;
  border-radius: 8px;
  font-weight: 700;
  font-size: 16px;
  cursor: pointer;
  margin-top: 8px;
  transition: transform 0.2s, box-shadow 0.2s;
  font-family: 'DM Sans', sans-serif;
}
.calc-btn:hover { transform: translateY(-2px); box-shadow: 0 8px 24px rgba(255,215,0,0.35); }
.calc-result {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 32px;
  background: rgba(255,255,255,0.03);
  border-radius: 14px;
  border: 1px dashed var(--border-gold);
  min-height: 400px;
}
.result-placeholder {
  color: var(--warm-gray);
  font-size: 15px;
  line-height: 1.6;
}
.result-placeholder .icon { font-size: 48px; margin-bottom: 16px; display: block; }
.result-main { display: none; width: 100%; }
.result-label {
  font-size: 13px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--blue-light);
  margin-bottom: 12px;
}
.result-amount {
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  font-size: clamp(32px, 4.5vw, 52px);
  font-weight: 800;
  letter-spacing: -1px;
  background: var(--gold-text);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 6px;
}
.result-subtitle {
  font-size: 14px;
  color: var(--warm-gray);
  margin-bottom: 32px;
}
.result-breakdown {
  width: 100%;
  border-top: 1px solid var(--border-subtle);
  padding-top: 24px;
  display: grid;
  gap: 14px;
}
.breakdown-row {
  display: flex;
  justify-content: space-between;
  font-size: 14px;
}
.breakdown-row .b-label { color: var(--warm-gray); }
.breakdown-row .b-value { font-weight: 600; color: var(--blue-light); }
.disclaimer-text {
  margin-top: 24px;
  font-size: 11px;
  color: var(--warm-gray);
  line-height: 1.5;
  text-align: left;
  opacity: 0.7;
}

/* ─── BUYING TIMELINE ─── */
.timeline-section {
  padding: 100px 24px;
  background: linear-gradient(180deg, var(--navy) 0%, var(--navy-deep) 100%);
  overflow: hidden;
}
.timeline-wrapper {
  position: relative;
  margin-top: 64px;
}
/* horizontal connector line (desktop) */
.timeline-track {
  display: flex;
  align-items: flex-start;
  gap: 0;
  position: relative;
}
.timeline-track::before {
  content: '';
  position: absolute;
  top: 44px;
  left: calc(44px / 2);
  right: calc(44px / 2);
  height: 2px;
  background: linear-gradient(90deg,
    rgba(255,215,0,0.15),
    rgba(255,215,0,0.6) 20%,
    rgba(255,215,0,0.6) 80%,
    rgba(255,215,0,0.15));
  z-index: 0;
}
.tl-step {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 0 8px;
  position: relative;
  z-index: 1;
  cursor: default;
}
.tl-node {
  width: 44px;
  height: 44px;
  border-radius: 50%;
  background: var(--navy-deep);
  border: 2px solid rgba(255,215,0,0.35);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 18px;
  margin-bottom: 20px;
  transition: border-color 0.3s, transform 0.3s, background 0.3s;
  box-shadow: 0 0 0 0 rgba(255,215,0,0);
  flex-shrink: 0;
}
.tl-step:hover .tl-node {
  border-color: var(--gold-mid);
  background: rgba(255,215,0,0.1);
  transform: scale(1.15);
  box-shadow: 0 0 20px rgba(255,215,0,0.25);
}
.tl-step.active .tl-node {
  border-color: var(--gold-mid);
  background: rgba(255,215,0,0.12);
  box-shadow: 0 0 0 6px rgba(255,215,0,0.06);
}
.tl-body {
  background: rgba(255,255,255,0.03);
  border: 1px solid rgba(98,176,200,0.12);
  border-radius: 14px;
  padding: 20px 16px;
  transition: border-color 0.3s, background 0.3s, transform 0.3s;
  width: 100%;
}
.tl-step:hover .tl-body {
  border-color: rgba(255,215,0,0.3);
  background: rgba(255,255,255,0.05);
  transform: translateY(-4px);
}
.tl-num {
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--gold-mid);
  margin-bottom: 6px;
  opacity: 0.7;
}
.tl-title {
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: -0.2px;
  color: var(--white);
  margin-bottom: 6px;
  line-height: 1.4;
}
.tl-title-en {
  font-size: 10px;
  color: var(--blue-light);
  font-weight: 500;
  letter-spacing: 0.5px;
  margin-bottom: 10px;
  display: block;
  opacity: 0.8;
}
.tl-desc {
  font-size: 12px;
  color: var(--warm-gray);
  line-height: 1.6;
}
.tl-badge {
  display: inline-block;
  font-size: 10px;
  font-weight: 600;
  background: rgba(255,215,0,0.1);
  color: var(--gold-mid);
  border: 1px solid rgba(255,215,0,0.2);
  border-radius: 20px;
  padding: 3px 10px;
  margin-top: 10px;
}

/* arrow connectors between steps */
.tl-arrow {
  display: none;
}

/* mobile: vertical layout */
@media (max-width: 900px) {
  .timeline-track {
    flex-direction: column;
    align-items: stretch;
    gap: 0;
  }
  .timeline-track::before { display: none; }
  .tl-step {
    flex-direction: row;
    text-align: left;
    padding: 0;
    margin-bottom: 16px;
    gap: 16px;
    align-items: flex-start;
  }
  .tl-node { margin-bottom: 0; flex-shrink: 0; margin-top: 4px; }
  .tl-body { flex: 1; }
}

/* ─── PROCESS ─── */
.process-section {
  padding: 100px 24px;
  background: var(--navy-deep);
}
.process-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 24px;
  margin-top: 60px;
}
.process-card {
  background: var(--card-bg);
  border: 1px solid var(--border-subtle);
  border-radius: 16px;
  padding: 36px 28px;
  position: relative;
  overflow: hidden;
  transition: border-color 0.3s, transform 0.3s;
}
.process-card:hover {
  border-color: var(--border-gold);
  transform: translateY(-4px);
}
.process-num {
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  font-size: 52px;
  font-weight: 800;
  color: rgba(255,215,0,0.12);
  position: absolute;
  top: 14px;
  right: 18px;
  line-height: 1;
  letter-spacing: -2px;
}
.process-icon { font-size: 32px; margin-bottom: 16px; }
.process-card h4 {
  font-size: 17px;
  font-weight: 700;
  letter-spacing: -0.2px;
  margin-bottom: 10px;
  color: var(--white);
}
.process-card p { font-size: 13px; color: var(--warm-gray); line-height: 1.7; }

/* ─── ENQUIRY FORM ─── */
.enquiry-section {
  padding: 100px 24px;
  background: linear-gradient(180deg, var(--navy) 0%, #1a2d38 100%);
}
.form-card {
  background: rgba(255,255,255,0.03);
  border: 1px solid var(--border-gold);
  border-radius: 20px;
  padding: 56px 48px;
  position: relative;
  overflow: hidden;
}
.form-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 2px;
  background: var(--gold-gradient);
}
.form-sections { display: grid; gap: 48px; }
.form-section-title {
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  font-size: 17px;
  font-weight: 700;
  letter-spacing: -0.2px;
  color: var(--blue-light);
  margin-bottom: 22px;
  padding-bottom: 12px;
  border-bottom: 1px solid var(--border-subtle);
  display: flex;
  align-items: center;
  gap: 10px;
}
.form-section-title span { font-size: 20px; }
.form-grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
.form-grid-3 { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 20px; }
.form-grid-1 { display: grid; grid-template-columns: 1fr; gap: 20px; }
.col-span-2 { grid-column: span 2; }
.col-span-full { grid-column: 1 / -1; }

/* Full-width enquiry form inputs */
.form-card .form-group input,
.form-card .form-group select,
.form-card .form-group textarea {
  width: 100%;
  background: rgba(255,255,255,0.06);
  border: 1px solid rgba(98,176,200,0.2);
  border-radius: 8px;
  padding: 13px 14px;
  color: var(--white);
  font-size: 14px;
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  transition: border-color 0.2s;
  -webkit-appearance: none;
}
.form-card .form-group input:focus,
.form-card .form-group select:focus,
.form-card .form-group textarea:focus {
  outline: none;
  border-color: var(--gold-mid);
  background: rgba(255,215,0,0.04);
}
/* ─ reset radio/checkbox inside form-card ─ */
.form-card .form-group input[type="radio"],
.form-card .form-group input[type="checkbox"] {
  width: auto !important;
  height: auto !important;
  background: transparent !important;
  border: none !important;
  padding: 0 !important;
  border-radius: 0 !important;
}
/* partner section */
.partner-section {
  display: none;
  margin-top: 20px;
  padding: 20px;
  background: rgba(98,176,200,0.05);
  border: 1px solid rgba(98,176,200,0.2);
  border-radius: 12px;
  grid-column: 1 / -1;
}
.partner-section.visible { display: block; }
.partner-section-title {
  font-size: 13px;
  font-weight: 700;
  color: var(--blue-light);
  margin-bottom: 16px;
  letter-spacing: 0.5px;
  text-transform: uppercase;
}
/* existing property detail */
.property-detail {
  display: none;
  margin-top: 12px;
  grid-column: 1 / -1;
}
.property-detail.visible { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
.form-card .form-group select option { background: var(--navy); }
.form-card .form-group textarea {
  resize: vertical;
  min-height: 100px;
}
.radio-group {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  padding-top: 6px;
}
.radio-option {
  position: relative;
  cursor: pointer;
}
.radio-option input[type="radio"] {
  position: absolute;
  opacity: 0;
  width: 0;
  height: 0;
  pointer-events: none;
}
.radio-option span {
  display: inline-flex;
  align-items: center;
  padding: 9px 20px;
  border-radius: 8px;
  font-size: 14px;
  font-weight: 500;
  color: var(--warm-gray);
  background: rgba(255,255,255,0.04);
  border: 1.5px solid rgba(98,176,200,0.2);
  cursor: pointer;
  transition: all 0.2s;
  user-select: none;
}
.radio-option span:hover {
  border-color: rgba(255,215,0,0.4);
  color: var(--white);
  background: rgba(255,215,0,0.06);
}
.radio-option input[type="radio"]:checked + span {
  background: rgba(255,215,0,0.15);
  border-color: var(--gold-mid);
  color: var(--gold-mid);
  font-weight: 700;
  box-shadow: 0 0 0 3px rgba(255,215,0,0.1);
}
.checkbox-group { display: flex; gap: 10px; flex-wrap: wrap; }
.checkbox-option {
  display: flex;
  align-items: center;
  gap: 8px;
  background: rgba(255,255,255,0.04);
  border: 1px solid var(--border-subtle);
  border-radius: 6px;
  padding: 8px 14px;
  cursor: pointer;
  transition: border-color 0.2s;
}
.checkbox-option:hover { border-color: var(--gold-mid); }
.checkbox-option input { accent-color: var(--gold-mid); }
.checkbox-option span { font-size: 13px; }

.submit-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 16px;
  margin-top: 16px;
}
.submit-btn {
  background: var(--gold-gradient);
  color: var(--charcoal);
  border: none;
  padding: 18px 60px;
  border-radius: 8px;
  font-weight: 700;
  font-size: 18px;
  cursor: pointer;
  transition: transform 0.2s, box-shadow 0.2s;
  font-family: 'DM Sans', sans-serif;
  box-shadow: 0 4px 24px rgba(255,215,0,0.3);
}
.submit-btn:hover { transform: translateY(-2px); box-shadow: 0 8px 32px rgba(255,215,0,0.45); }
.submit-note {
  font-size: 12px;
  color: var(--warm-gray);
  text-align: center;
}
.success-message {
  display: none;
  text-align: center;
  padding: 40px;
}
.success-message h3 {
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
  font-size: 26px;
  font-weight: 800;
  letter-spacing: -0.3px;
  margin-bottom: 12px;
}
.success-message p { color: var(--text-light); font-size: 16px; }

/* ─── CONTACT BAR ─── */
.contact-bar {
  background: var(--charcoal);
  border-top: 1px solid var(--border-gold);
  padding: 60px 24px;
}
.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 32px;
  align-items: center;
}
.contact-item {
  display: flex;
  align-items: center;
  gap: 14px;
}
.contact-icon {
  width: 44px;
  height: 44px;
  background: rgba(255,215,0,0.12);
  border: 1px solid var(--border-gold);
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 18px;
  flex-shrink: 0;
}
.contact-item .c-label { font-size: 11px; color: var(--warm-gray); text-transform: uppercase; letter-spacing: 1px; }
.contact-item .c-val { font-size: 15px; font-weight: 500; color: var(--white); margin-top: 2px; }
.kakao-bar-btn {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: #FEE500;
  color: #3C1E1E;
  padding: 14px 24px;
  border-radius: 8px;
  font-weight: 700;
  font-size: 15px;
  text-decoration: none;
  transition: transform 0.2s;
}
.kakao-bar-btn:hover { transform: translateY(-2px); }

/* ─── FOOTER ─── */
footer {
  background: #141e24;
  padding: 40px 24px;
  text-align: center;
  border-top: 1px solid rgba(98,176,200,0.08);
}
footer p {
  font-size: 12px;
  color: var(--warm-gray);
  line-height: 1.8;
  max-width: 800px;
  margin: 0 auto;
}
footer .footer-logo {
  font-family: 'Playfair Display', serif;
  font-size: 22px;
  font-weight: 700;
  margin-bottom: 20px;
}

/* ─── FLOATING KAKAO ─── */
.floating-kakao {
  position: fixed;
  bottom: 32px;
  right: 32px;
  z-index: 99;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
}
.floating-kakao a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 58px;
  height: 58px;
  background: #FEE500;
  border-radius: 50%;
  box-shadow: 0 4px 20px rgba(254,229,0,0.4);
  font-size: 26px;
  text-decoration: none;
  transition: transform 0.2s, box-shadow 0.2s;
}
.floating-kakao a:hover { transform: translateY(-3px); box-shadow: 0 8px 28px rgba(254,229,0,0.5); }
.floating-label {
  font-size: 10px;
  color: var(--warm-gray);
  letter-spacing: 0.5px;
}

/* ─── SCHEMES SECTION ─── */
.schemes-section {
  padding: 100px 24px;
  background: linear-gradient(180deg, #1a2d38 0%, var(--navy-deep) 100%);
}
.schemes-intro {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin-bottom: 64px;
}
.scheme-card-fed {
  background: rgba(255,215,0,0.05);
  border: 1px solid rgba(255,215,0,0.25);
  border-radius: 16px;
  padding: 28px 24px;
  position: relative;
  overflow: hidden;
  transition: transform 0.2s, border-color 0.2s;
}
.scheme-card-fed:hover { transform: translateY(-3px); border-color: rgba(255,215,0,0.5); }
.scheme-card-fed::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 3px;
  background: var(--gold-gradient);
}
.fed-badge {
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: var(--gold-mid);
  margin-bottom: 10px;
  display: block;
}
.fed-title { font-size: 16px; font-weight: 700; color: var(--white); margin-bottom: 8px; letter-spacing: -0.2px; }
.fed-highlight {
  font-size: 28px;
  font-weight: 800;
  color: var(--gold-mid);
  font-family: 'Inter', sans-serif;
  letter-spacing: -1px;
  margin-bottom: 6px;
  display: block;
}
.fed-desc { font-size: 13px; color: var(--warm-gray); line-height: 1.6; }
.fed-tag {
  display: inline-block;
  font-size: 11px;
  background: rgba(98,176,200,0.12);
  color: var(--blue-light);
  border: 1px solid rgba(98,176,200,0.2);
  border-radius: 4px;
  padding: 3px 8px;
  margin-top: 10px;
  font-weight: 500;
}

/* State tabs */
.state-tabs {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
  margin-bottom: 28px;
  justify-content: center;
}
.state-tab {
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(98,176,200,0.15);
  border-radius: 8px;
  padding: 9px 18px;
  font-size: 13px;
  font-weight: 600;
  color: var(--warm-gray);
  cursor: pointer;
  transition: all 0.2s;
  font-family: 'Noto Sans KR', 'Inter', sans-serif;
}
.state-tab:hover { border-color: var(--gold-mid); color: var(--gold-mid); }
.state-tab.active {
  background: rgba(255,215,0,0.12);
  border-color: var(--gold-mid);
  color: var(--gold-mid);
}

/* State detail panel */
.state-panel {
  display: none;
  animation: fadeUp 0.3s ease both;
}
.state-panel.active { display: block; }
.state-panel-header {
  display: flex;
  align-items: center;
  gap: 16px;
  margin-bottom: 28px;
  padding-bottom: 20px;
  border-bottom: 1px solid var(--border-subtle);
}
.state-flag {
  font-size: 36px;
  width: 56px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: rgba(255,255,255,0.04);
  border-radius: 12px;
  border: 1px solid var(--border-subtle);
}
.state-panel-header h3 {
  font-size: 22px;
  font-weight: 800;
  letter-spacing: -0.3px;
  color: var(--white);
}
.state-panel-header p { font-size: 13px; color: var(--warm-gray); margin-top: 3px; }

.schemes-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 16px;
  margin-bottom: 20px;
}
.scheme-benefit {
  background: rgba(255,255,255,0.03);
  border: 1px solid var(--border-subtle);
  border-radius: 14px;
  padding: 22px 20px;
  transition: border-color 0.2s, transform 0.2s;
}
.scheme-benefit:hover { border-color: rgba(98,176,200,0.3); transform: translateY(-2px); }
.sb-type {
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 8px;
  display: flex;
  align-items: center;
  gap: 6px;
}
.sb-type.grant { color: #4ade80; }
.sb-type.stamp { color: var(--blue-light); }
.sb-type.fhbg { color: var(--gold-mid); }
.sb-type.other { color: #c084fc; }
.sb-amount {
  font-size: 26px;
  font-weight: 800;
  font-family: 'Inter', sans-serif;
  letter-spacing: -0.8px;
  margin-bottom: 6px;
  line-height: 1;
}
.sb-type.grant ~ .sb-amount { color: #4ade80; }
.sb-type.stamp ~ .sb-amount { color: var(--blue-light); }
.sb-type.fhbg ~ .sb-amount { color: var(--gold-mid); }
.sb-type.other ~ .sb-amount { color: #c084fc; }
.sb-title { font-size: 14px; font-weight: 600; color: var(--white); margin-bottom: 8px; }
.sb-conditions { font-size: 12px; color: var(--warm-gray); line-height: 1.7; }
.sb-conditions li { margin-bottom: 3px; padding-left: 12px; position: relative; list-style: none; }
.sb-conditions li::before { content: '→'; position: absolute; left: 0; color: rgba(255,255,255,0.3); font-size: 10px; top: 1px; }
.sb-note {
  margin-top: 10px;
  font-size: 11px;
  background: rgba(255,215,0,0.06);
  border-left: 2px solid rgba(255,215,0,0.3);
  padding: 6px 10px;
  border-radius: 0 4px 4px 0;
  color: rgba(255,215,0,0.8);
}
.scheme-disclaimer {
  text-align: center;
  font-size: 11px;
  color: var(--warm-gray);
  margin-top: 32px;
  padding: 16px;
  background: rgba(255,255,255,0.02);
  border-radius: 8px;
  border: 1px solid var(--border-subtle);
  line-height: 1.6;
  opacity: 0.8;
}

/* ─── ANIMATIONS ─── */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(24px); }
  to { opacity: 1; transform: translateY(0); }
}
@keyframes bounce {
  0%, 100% { transform: translateX(-50%) translateY(0); }
  50% { transform: translateX(-50%) translateY(8px); }
}

.loan-type-select {
  width: 100%;
  background: rgba(255,255,255,0.06);
  border: 1px solid rgba(98,176,200,0.2);
  border-radius: 8px;
  color: var(--white);
  font-size: 14px;
  font-family: 'DM Sans', sans-serif;
  overflow-y: auto;
  -webkit-appearance: none;
  scrollbar-width: thin;
  scrollbar-color: var(--gold-mid) transparent;
}
.loan-type-select option {
  background: var(--navy);
  color: var(--white);
  padding: 12px 16px;
  border-bottom: 1px solid rgba(98,176,200,0.08);
  cursor: pointer;
  font-size: 14px;
}
.loan-type-select option:checked {
  background: rgba(255,215,0,0.15);
  color: var(--gold-mid);
  font-weight: 600;
}
.loan-type-select option:hover {
  background: rgba(255,215,0,0.08);
}
.loan-type-select:focus {
  outline: none;
  border-color: var(--gold-mid);
}
.loan-type-select::-webkit-scrollbar { width: 6px; }
.loan-type-select::-webkit-scrollbar-track { background: transparent; }
.loan-type-select::-webkit-scrollbar-thumb { background: var(--gold-mid); border-radius: 3px; }
/* ─── RESPONSIVE ─── */
@media (max-width: 768px) {
  nav { padding: 14px 20px; }
  .nav-links { display: none; }
  .calc-wrapper { grid-template-columns: 1fr; padding: 28px 20px; }
  .form-grid-2 { grid-template-columns: 1fr; }
  .form-grid-3 { grid-template-columns: 1fr; }
  .form-card { padding: 32px 20px; }
  .col-span-2 { grid-column: span 1; }
  .hero-stats { gap: 24px; }
  .schemes-intro { grid-template-columns: 1fr; }
  .hero-line1 { white-space: normal; }
  .floating-kakao { bottom: 20px; right: 20px; }
}
</style>
</head>
<body>

<!-- ─── NAV ─── -->
<nav>
  <div class="nav-logo"><span class="gold-text">GB</span> Home Loans</div>
  <ul class="nav-links">
    <li><a href="#calculator">대출한도 계산</a></li>
    <li><a href="#process">진행 과정</a></li>
    <li><a href="#schemes">주별 혜택</a></li>
    <li><a href="#enquiry">상담 신청</a></li>
  </ul>
  <a href="http://pf.kakao.com/_razen/chat" target="_blank" class="nav-cta">카카오톡 상담</a>
</nav>

<!-- ─── HERO ─── -->
<section class="hero">
  <div class="hero-eyebrow">
    <div class="eyebrow-line"></div>
    <span>호주 공인 모기지 브로커 · ACL 384704</span>
    <div class="eyebrow-line"></div>
  </div>
  <h1>
    <span class="hero-line1">당신의 호주 내집 마련,</span><br>
    <span class="gold-text">GB Home Loans</span>와 함께
  </h1>
  <p>복잡한 호주 홈론, 한국어로 쉽고 명확하게.<br>수십 개의 은행 중 최적의 조건을 찾아드립니다.</p>
  <div class="hero-buttons">
    <a href="#calculator" class="btn-primary">무료 한도 계산하기 →</a>
    <a href="http://pf.kakao.com/_razen/chat" target="_blank" class="btn-kakao">
      <svg class="kakao-icon" viewBox="0 0 24 24" fill="#3C1E1E"><path d="M12 3C6.477 3 2 6.477 2 10.5c0 2.41 1.36 4.54 3.45 5.93L4.5 20.5l4.1-2.3A11.5 11.5 0 0012 18.5c5.523 0 10-3.477 10-7.5S17.523 3 12 3z"/></svg>
      카카오톡 문의
    </a>
  </div>
  <div class="hero-stats">
    <div class="stat"><div class="stat-num">40+</div><div class="stat-label">제휴 금융기관</div></div>
    <div class="stat"><div class="stat-num">전국</div><div class="stat-label">호주 전지역 서비스</div></div>
    <div class="stat"><div class="stat-num">무료</div><div class="stat-label">브로커 서비스</div></div>
    <div class="stat"><div class="stat-num">한국어</div><div class="stat-label">전문 상담</div></div>
  </div>
  <div class="scroll-indicator">
    <span>SCROLL</span>
    <div class="scroll-arrow"></div>
  </div>
</section>

<!-- ─── CALCULATOR ─── -->
<section class="calculator-section" id="calculator">
  <div class="container">
    <div class="section-header">
      <div class="section-tag">Borrowing Power Calculator</div>
      <h2>내가 받을 수 있는 <span class="gold-text">대출 한도</span>는?</h2>
      <p>소득과 지출을 입력하면 예상 대출 가능 금액을 즉시 계산해드립니다</p>
    </div>
    <div class="calc-wrapper">
      <div class="calc-inputs">
        <h3>💰 소득 및 지출 정보</h3>
        <div class="form-group">
          <label>연 소득 (본인) — Gross Annual Income</label>
          <div class="input-wrap">
            <span class="input-prefix">$</span>
            <input type="number" id="income1" placeholder="예: 90000" min="0">
          </div>
        </div>
        <div class="form-group">
          <label>연 소득 (배우자/공동) — Partner Income</label>
          <div class="input-wrap">
            <span class="input-prefix">$</span>
            <input type="number" id="income2" placeholder="예: 60000 (없으면 0)" min="0" value="0">
          </div>
        </div>
        <div class="form-group">
          <label>기타 소득 (렌트, 투자 등) — Other Income</label>
          <div class="input-wrap">
            <span class="input-prefix">$</span>
            <input type="number" id="otherIncome" placeholder="연간 금액" min="0" value="0">
          </div>
        </div>
        <div class="form-group">
          <label>월 생활비 — Monthly Living Expenses</label>
          <div class="input-wrap">
            <span class="input-prefix">$</span>
            <input type="number" id="expenses" placeholder="예: 3500" min="0">
          </div>
        </div>
        <div class="form-group">
          <label>기존 대출 월 상환액 — Existing Loan Repayments</label>
          <div class="input-wrap">
            <span class="input-prefix">$</span>
            <input type="number" id="debts" placeholder="자동차, 개인 대출 등" min="0" value="0">
          </div>
        </div>
        <div class="form-group">
          <label>부양 가족 수 — Dependants</label>
          <select id="dependants">
            <option value="0">없음</option>
            <option value="1">1명</option>
            <option value="2">2명</option>
            <option value="3">3명</option>
            <option value="4">4명 이상</option>
          </select>
        </div>
        <div class="form-group">
          <label>대출 기간 — Loan Term</label>
          <select id="loanTerm">
            <option value="30">30년</option>
            <option value="25">25년</option>
            <option value="20">20년</option>
          </select>
        </div>
        <button class="calc-btn" onclick="calculateBorrowing()">📊 대출 한도 계산하기</button>
      </div>

      <div class="calc-result" id="calcResult">
        <div class="result-placeholder">
          <span class="icon">🏡</span>
          <p>소득과 지출을 입력하고<br>계산 버튼을 눌러주세요</p>
          <p style="margin-top:12px; font-size:13px; color: rgba(159,150,139,0.6)">실제 한도는 은행 심사에 따라<br>달라질 수 있습니다</p>
        </div>
        <div class="result-main" id="resultMain">
          <div class="result-label">예상 최대 대출 가능 금액</div>
          <div class="result-amount" id="resultAmount">$0</div>
          <div class="result-subtitle" id="resultSubtitle">월 상환액 기준</div>
          <div class="result-breakdown">
            <div class="breakdown-row">
              <span class="b-label">세후 연 소득</span>
              <span class="b-value" id="bNetIncome">—</span>
            </div>
            <div class="breakdown-row">
              <span class="b-label">월 상환 가능 금액</span>
              <span class="b-value" id="bMonthly">—</span>
            </div>
            <div class="breakdown-row">
              <span class="b-label">적용 심사 금리</span>
              <span class="b-value">9.50% p.a.</span>
            </div>
            <div class="breakdown-row">
              <span class="b-label">예상 월 상환액</span>
              <span class="b-value" id="bRepayment">—</span>
            </div>
          </div>
          <p class="disclaimer-text">※ 이 계산은 참고용이며 실제 심사 결과와 다를 수 있습니다. 정확한 한도는 GB Home Loans에 문의해 주세요. 적용 금리: 심사기준금리 9.5% (실제금리 6.5% + 은행버퍼 3%), 30년 원리금 균등상환 기준.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ─── BUYING TIMELINE ─── -->
<section class="timeline-section" id="buying-steps">
  <div class="container">
    <div class="section-header">
      <div class="section-tag">Step-by-Step Guide</div>
      <h2>호주 집 구매 <span class="gold-text">전체 프로세스</span></h2>
      <p>처음이라 막막하신가요? 서류 제출부터 세틀까지 한눈에 확인하세요</p>
    </div>

    <div class="timeline-wrapper">
      <div class="timeline-track">

        <!-- STEP 1 -->
        <div class="tl-step">
          <div class="tl-node">📄</div>
          <div class="tl-body">
            <div class="tl-num">STEP 01</div>
            <div class="tl-title">서류 제출 및 심사</div>
            <span class="tl-title-en">Document Submission & Assessment</span>
            <div class="tl-desc">
              소득증명, 은행 거래내역, ID, 비자 서류를 GB Home Loans에 제출. 브로커가 40개 이상 은행과 비교해 최적 상품을 선별합니다.
            </div>
            <span class="tl-badge">📋 소요: 1~3일</span>
          </div>
        </div>

        <!-- STEP 2 -->
        <div class="tl-step">
          <div class="tl-node">✅</div>
          <div class="tl-body">
            <div class="tl-num">STEP 02</div>
            <div class="tl-title">가승인</div>
            <span class="tl-title-en">Pre-Approval (Conditional Approval)</span>
            <div class="tl-desc">
              은행으로부터 조건부 승인을 받는 단계. 최대 대출 한도가 확정되어 자신감 있게 집을 볼 수 있습니다.
            </div>
            <span class="tl-badge">⏱ 유효기간: 3~6개월</span>
          </div>
        </div>

        <!-- STEP 3 -->
        <div class="tl-step">
          <div class="tl-node">🔎</div>
          <div class="tl-body">
            <div class="tl-num">STEP 03</div>
            <div class="tl-title">인스펙션</div>
            <span class="tl-title-en">Property Inspection</span>
            <div class="tl-desc">
              관심 매물을 직접 방문해 Building &amp; Pest Inspection 진행. 숨겨진 하자를 사전에 파악해 리스크를 줄입니다.
            </div>
            <span class="tl-badge">🏡 건물·해충 검사 필수</span>
          </div>
        </div>

        <!-- STEP 4 -->
        <div class="tl-step">
          <div class="tl-node">🤝</div>
          <div class="tl-body">
            <div class="tl-num">STEP 04</div>
            <div class="tl-title">오퍼 신청</div>
            <span class="tl-title-en">Making an Offer</span>
            <div class="tl-desc">
              프라이빗 세일 또는 경매(Auction)에서 오퍼 제출. 계약서 서명 전 반드시 Solicitor/Conveyancer 검토를 받으세요.
            </div>
            <span class="tl-badge">⚖️ 계약서 검토 권장</span>
          </div>
        </div>

        <!-- STEP 5 -->
        <div class="tl-step">
          <div class="tl-node">🏠</div>
          <div class="tl-body">
            <div class="tl-num">STEP 05</div>
            <div class="tl-title">구매 확정</div>
            <span class="tl-title-en">Exchange of Contracts</span>
            <div class="tl-desc">
              계약서 교환(Exchange) 및 보증금(Deposit) 납부. 이 시점부터 법적 구매 의무가 발생합니다. 은행 최종 승인도 진행됩니다.
            </div>
            <span class="tl-badge">💰 보증금 10% 납부</span>
          </div>
        </div>

        <!-- STEP 6 -->
        <div class="tl-step">
          <div class="tl-node">🎉</div>
          <div class="tl-body">
            <div class="tl-num">STEP 06</div>
            <div class="tl-title">세틀먼트</div>
            <span class="tl-title-en">Settlement</span>
            <div class="tl-desc">
              잔금 지급 및 소유권 이전 완료! 열쇠를 받는 날입니다. GB Home Loans가 은행, Solicitor와 협력해 원활한 세틀을 지원합니다.
            </div>
            <span class="tl-badge">🔑 소유권 이전 완료</span>
          </div>
        </div>

      </div><!-- /timeline-track -->
    </div><!-- /timeline-wrapper -->

    <div style="text-align:center; margin-top:56px;">
      <p style="color:var(--warm-gray); font-size:14px; margin-bottom:24px">
        어느 단계에 계신지 모르겠다면? GB Home Loans가 무료로 상황을 분석해드립니다.
      </p>
      <a href="#enquiry" class="btn-primary" style="display:inline-block">지금 무료 상담 신청하기 →</a>
    </div>
  </div>
</section>

<!-- ─── PROCESS ─── -->
<section class="process-section" id="process">
  <div class="container">
    <div class="section-header">
      <div class="section-tag">How It Works</div>
      <h2>홈론 진행 <span class="gold-text">4단계</span></h2>
      <p>GB Home Loans가 처음부터 끝까지 함께합니다</p>
    </div>
    <div class="process-grid">
      <div class="process-card">
        <div class="process-num">01</div>
        <div class="process-icon">💬</div>
        <h4>무료 상담</h4>
        <p>카카오톡 또는 전화로 현재 상황 파악. 목표, 예산, 비자 상태 등 기초 정보 공유</p>
      </div>
      <div class="process-card">
        <div class="process-num">02</div>
        <div class="process-icon">📋</div>
        <h4>서류 준비</h4>
        <p>소득증명, 은행거래내역, 비자, ID 등 필요 서류 리스트 제공 및 준비 지원</p>
      </div>
      <div class="process-card">
        <div class="process-num">03</div>
        <div class="process-icon">🔍</div>
        <h4>은행 비교 · 신청</h4>
        <p>40개 이상 금융기관 비교, 최적 상품 추천 후 대출 신청 대행</p>
      </div>
      <div class="process-card">
        <div class="process-num">04</div>
        <div class="process-icon">🏠</div>
        <h4>승인 · 정산</h4>
        <p>조건부 승인 → 무조건 승인 → 정산(Settlement) 완료까지 전 과정 지원</p>
      </div>
    </div>
  </div>
</section>

<!-- ─── ENQUIRY FORM ─── -->
<section class="enquiry-section" id="enquiry">
  <div class="container">
    <div class="section-header">
      <div class="section-tag">Pre-Assessment Form</div>
      <h2>홈론 <span class="gold-text">사전 상담 신청</span></h2>
      <p>아래 정보를 입력하시면 브로커가 최적의 솔루션을 준비해 연락드립니다</p>
    </div>

    <div class="form-card">
      <div id="enquiryForm">
        <div class="form-sections">

          <!-- 1. 개인 정보 -->
          <div>
            <div class="form-section-title"><span>👤</span> 개인 정보 Personal Details</div>
            <div class="form-grid-2">
              <div class="form-group">
                <label>이름 (영문) Full Name *</label>
                <input type="text" id="fName" placeholder="First Name Last Name">
              </div>
              <div class="form-group">
                <label>연락처 Phone Number *</label>
                <input type="tel" id="fPhone" placeholder="04XX XXX XXX">
              </div>
              <div class="form-group">
                <label>카카오톡 ID <span style="color:var(--warm-gray);font-weight:400;font-size:11px">(선택 · Optional)</span></label>
                <input type="text" id="fKakao" placeholder="카카오톡 아이디 입력">
              </div>
              <div class="form-group">
                <label>이메일 Email *</label>
                <input type="email" id="fEmail" placeholder="email@example.com">
              </div>
              <div class="form-group">
                <label>생년월일 Date of Birth</label>
                <input type="date" id="fDob">
              </div>
              <div class="form-group">
                <label>거주 주 State of Residence</label>
                <select id="fState">
                  <option value="">선택하세요</option>
                  <option>NSW</option>
                  <option>VIC</option>
                  <option>QLD</option>
                  <option>SA</option>
                  <option>WA</option>
                  <option>TAS</option>
                  <option>ACT</option>
                  <option>NT</option>
                </select>
              </div>
              <div class="form-group">
                <label>비자 / 시민권 Visa / Residency Status *</label>
                <select id="fVisa">
                  <option value="">선택하세요</option>
                  <option>Australian Citizen / 시민권자</option>
                  <option>Permanent Resident / 영주권자</option>
                  <option>Temporary Resident (482, 457 등)</option>
                  <option>Student Visa</option>
                  <option>Partner Visa</option>
                  <option>Graduate Visa (485)</option>
                  <option>기타</option>
                </select>
              </div>
            </div>
          </div>

          <!-- 2. 대출 목적 -->
          <div>
            <div class="form-section-title"><span>🎯</span> 대출 목적 Loan Purpose</div>
            <div class="form-group">
              <label>대출 유형 Loan Type *</label>
              <select id="fLoanType" class="loan-type-select" size="6">
                <option value="firstHome">🏠 첫 집 구매 (First Home Buyer)</option>
                <option value="upgrade">🔄 업그레이드 구매 (Upgrading)</option>
                <option value="investment">📈 투자용 (Investment Property)</option>
                <option value="refinance">🔁 재융자 (Refinance)</option>
                <option value="construction">🔨 신축 (Construction Loan)</option>
                <option value="equity">💳 지분 인출 (Equity Release)</option>
              </select>
              <p style="font-size:11px; color:var(--warm-gray); margin-top:6px">해당하는 항목을 선택하세요</p>
            </div>
            <div class="form-grid-2" style="margin-top:16px">
              <div class="form-group">
                <label>예상 부동산 가격 Property Price</label>
                <div class="input-wrap">
                  <span class="input-prefix">$</span>
                  <input type="number" id="fPropPrice" placeholder="예: 750000" style="padding-left:28px">
                </div>
              </div>
              <div class="form-group">
                <label>준비된 보증금 Deposit Available</label>
                <div class="input-wrap">
                  <span class="input-prefix">$</span>
                  <input type="number" id="fDeposit" placeholder="예: 100000" style="padding-left:28px">
                </div>
              </div>
              <div class="form-group">
                <label>부동산 유형 Property Type</label>
                <select id="fPropType">
                  <option value="">선택하세요</option>
                  <option>House / 주택</option>
                  <option>Apartment / Unit</option>
                  <option>Townhouse</option>
                  <option>Land / 토지</option>
                  <option>아직 미정</option>
                </select>
              </div>
              <div class="form-group">
                <label>구매 예정 시기 Purchase Timeline</label>
                <select id="fTimeline">
                  <option value="">선택하세요</option>
                  <option>즉시 (ASAP)</option>
                  <option>1~3개월 내</option>
                  <option>3~6개월 내</option>
                  <option>6~12개월 내</option>
                  <option>1년 이상</option>
                </select>
              </div>
            </div>
          </div>

          <!-- 3. 고용 & 소득 -->
          <div>
            <div class="form-section-title"><span>💼</span> 고용 및 소득 Employment & Income</div>
            <div class="form-grid-2">
              <div class="form-group">
                <label>고용 형태 Employment Type *</label>
                <select id="fEmployment">
                  <option value="">선택하세요</option>
                  <option>Full-Time PAYG (정규직)</option>
                  <option>Part-Time PAYG (파트타임)</option>
                  <option>Casual (캐주얼)</option>
                  <option>Self-Employed / ABN (자영업)</option>
                  <option>Contractor (컨트랙터)</option>
                  <option>현재 무직 / 구직 중</option>
                </select>
              </div>
              <div class="form-group">
                <label>현 직장 근무 기간 Time in Current Job</label>
                <select id="fJobDuration">
                  <option value="">선택하세요</option>
                  <option>3개월 미만</option>
                  <option>3~6개월</option>
                  <option>6~12개월</option>
                  <option>1~2년</option>
                  <option>2년 이상</option>
                </select>
              </div>
              <div class="form-group">
                <label>연 소득 (세전) Annual Gross Income *</label>
                <div class="input-wrap">
                  <span class="input-prefix">$</span>
                  <input type="number" id="fAnnualIncome" placeholder="예: 90000" style="padding-left:28px">
                </div>
              </div>
              <div class="form-group">
                <label>기타 소득 (있을 경우) Other Income</label>
                <div class="input-wrap">
                  <span class="input-prefix">$</span>
                  <input type="number" id="fOtherIncome" placeholder="렌트, 투자, 정부수당 등" style="padding-left:28px">
                </div>
              </div>
              <div class="form-group" style="grid-column:1/-1">
                <label>공동 신청인 여부 Co-Borrower</label>
                <div class="radio-group">
                  <label class="radio-option"><input type="radio" name="coBorrower" value="yes" onchange="togglePartner(true)"> <span>있음 (배우자/파트너)</span></label>
                  <label class="radio-option"><input type="radio" name="coBorrower" value="no" onchange="togglePartner(false)" checked> <span>없음 (단독)</span></label>
                </div>
                <div class="partner-section" id="partnerSection">
                  <div class="partner-section-title">👫 파트너 고용 및 소득 정보 Partner's Employment & Income</div>
                  <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px">
                    <div class="form-group">
                      <label>파트너 고용 형태 Employment Type</label>
                      <select id="fPartnerEmployment">
                        <option value="">선택하세요</option>
                        <option>Full-Time PAYG (정규직)</option>
                        <option>Part-Time PAYG (파트타임)</option>
                        <option>Casual (캐주얼)</option>
                        <option>Self-Employed / ABN (자영업)</option>
                        <option>Contractor (컨트랙터)</option>
                        <option>현재 무직 / 구직 중</option>
                      </select>
                    </div>
                    <div class="form-group">
                      <label>파트너 연 소득 (세전) Annual Gross Income</label>
                      <div class="input-wrap">
                        <span class="input-prefix">$</span>
                        <input type="number" id="fPartnerIncome" placeholder="예: 70000" style="padding-left:28px">
                      </div>
                    </div>
                    <div class="form-group">
                      <label>파트너 근무 기간 Time in Current Job</label>
                      <select id="fPartnerJobDuration">
                        <option value="">선택하세요</option>
                        <option>3개월 미만</option>
                        <option>3~6개월</option>
                        <option>6~12개월</option>
                        <option>1~2년</option>
                        <option>2년 이상</option>
                      </select>
                    </div>
                    <div class="form-group">
                      <label>파트너 기타 소득 Other Income</label>
                      <div class="input-wrap">
                        <span class="input-prefix">$</span>
                        <input type="number" id="fPartnerOtherIncome" placeholder="렌트, 투자 등" style="padding-left:28px" value="0">
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="form-group">
                <label>부양가족 수 No. of Dependants</label>
                <select id="fDependants">
                  <option value="0">없음</option>
                  <option value="1">1명</option>
                  <option value="2">2명</option>
                  <option value="3">3명</option>
                  <option value="4">4명 이상</option>
                </select>
              </div>
            </div>
          </div>

          <!-- 4. 자산 & 부채 -->
          <div>
            <div class="form-section-title"><span>📊</span> 자산 및 부채 Assets & Liabilities</div>
            <div class="form-grid-2">
              <div class="form-group">
                <label>총 저축액 Total Savings</label>
                <div class="input-wrap">
                  <span class="input-prefix">$</span>
                  <input type="number" id="fSavings" placeholder="은행 잔액 합계" style="padding-left:28px">
                </div>
              </div>
              <div class="form-group">
                <label>저축 기간 Genuine Savings Period</label>
                <select id="fSavingsPeriod">
                  <option value="">선택하세요</option>
                  <option>3개월 미만</option>
                  <option>3~6개월</option>
                  <option>6개월 이상</option>
                </select>
              </div>
              <div class="form-group" style="grid-column:1/-1">
                <label>기존 부동산 소유 여부 Existing Property</label>
                <div class="radio-group">
                  <label class="radio-option"><input type="radio" name="hasProperty" value="yes" onchange="toggleProperty(true)"> <span>있음</span></label>
                  <label class="radio-option"><input type="radio" name="hasProperty" value="no" onchange="toggleProperty(false)" checked> <span>없음</span></label>
                </div>
                <div class="property-detail" id="propertyDetail">
                  <div class="form-group">
                    <label>기존 부동산 주소 Property Address</label>
                    <input type="text" id="fPropertyAddress" placeholder="예: 123 Main St, Sydney NSW 2000">
                  </div>
                  <div class="form-group">
                    <label>예상 부동산 가치 Estimated Value</label>
                    <div class="input-wrap">
                      <span class="input-prefix">$</span>
                      <input type="number" id="fPropertyValue" placeholder="예: 800000" style="padding-left:28px">
                    </div>
                  </div>
                  <div class="form-group">
                    <label>기존 모기지 잔액 Mortgage Balance</label>
                    <div class="input-wrap">
                      <span class="input-prefix">$</span>
                      <input type="number" id="fPropertyMortgage" placeholder="없으면 0" style="padding-left:28px" value="0">
                    </div>
                  </div>
                  <div class="form-group">
                    <label>현재 용도 Current Use</label>
                    <select id="fPropertyUse">
                      <option value="">선택하세요</option>
                      <option>본인 거주 (Owner-Occupied)</option>
                      <option>임대 중 (Investment / Rental)</option>
                      <option>공실 (Vacant)</option>
                    </select>
                  </div>
                </div>
              </div>
              <div class="form-group">
                <label>월 생활비 Monthly Living Expenses</label>
                <div class="input-wrap">
                  <span class="input-prefix">$</span>
                  <input type="number" id="fLivingExp" placeholder="예: 3500" style="padding-left:28px">
                </div>
              </div>
              <div class="form-group">
                <label>신용카드 한도 Credit Card Limit</label>
                <div class="input-wrap">
                  <span class="input-prefix">$</span>
                  <input type="number" id="fCCLimit" placeholder="예: 5000 (없으면 0)" style="padding-left:28px" value="0">
                </div>
              </div>
              <div class="form-group">
                <label>기타 대출 월 상환액 Other Loan Repayments</label>
                <div class="input-wrap">
                  <span class="input-prefix">$</span>
                  <input type="number" id="fOtherLoans" placeholder="자동차, 개인 대출 등" style="padding-left:28px" value="0">
                </div>
              </div>
            </div>
          </div>

          <!-- 5. 추가 정보 -->
          <div>
            <div class="form-section-title"><span>📝</span> 추가 문의사항 Additional Notes</div>
            <div class="form-grid-1">
              <div class="form-group">
                <label>이전에 호주에서 홈론을 신청한 적이 있나요?</label>
                <div class="radio-group">
                  <label class="radio-option"><input type="radio" name="prevLoan" value="yes"> <span>있음</span></label>
                  <label class="radio-option"><input type="radio" name="prevLoan" value="no" checked> <span>없음</span></label>
                </div>
              </div>
              <div class="form-group">
                <label>신용 기록 관련 이슈 Credit History Issues</label>
                <div class="checkbox-group">
                  <label class="checkbox-option"><input type="checkbox" name="credit" value="none"> <span>✅ 없음 (클린)</span></label>
                  <label class="checkbox-option"><input type="checkbox" name="credit" value="default"> <span>⚠️ 연체/Default 이력</span></label>
                  <label class="checkbox-option"><input type="checkbox" name="credit" value="bankruptcy"> <span>❗ 파산 이력</span></label>
                </div>
              </div>
              <div class="form-group">
                <label>궁금하신 점 또는 특이사항 Questions / Special Circumstances</label>
                <textarea id="fNotes" placeholder="예: 비자 만료 예정, 캐주얼 근무 중, 자영업 2년 미만, 부모 지원금 있음 등 자유롭게 작성해 주세요"></textarea>
              </div>
              <div class="form-group">
                <label>어떻게 알게 되셨나요? How did you find us?</label>
                <select id="fSource">
                  <option value="">선택하세요</option>
                  <option>카카오톡 / KakaoTalk</option>
                  <option>인스타그램 / Instagram</option>
                  <option>지인 추천</option>
                  <option>구글 검색</option>
                  <option>기타</option>
                </select>
              </div>
            </div>
          </div>

        </div><!-- /form-sections -->

        <div class="submit-section">
          <button class="submit-btn" onclick="submitForm()">📨 상담 신청 제출하기</button>
          <p class="submit-note">🔒 개인정보는 안전하게 보호되며 상담 목적 외에 사용되지 않습니다<br>
          영업일 기준 1일 내 연락드립니다 · SKSY Family Ventures Pty Ltd · ACL 384704</p>
        </div>
      </div><!-- /enquiryForm -->

      <div class="success-message" id="successMsg">
        <div style="font-size:64px; margin-bottom:16px">🎉</div>
        <h3>상담 신청이 완료되었습니다!</h3>
        <p style="margin-top:12px; color: var(--text-light)">GB Home Loans 팀이 영업일 기준 1일 내 연락드립니다.<br>빠른 상담을 원하시면 카카오톡으로 문의해 주세요.</p>
        <a href="http://pf.kakao.com/_razen/chat" target="_blank" class="btn-kakao" style="margin-top: 32px; display:inline-flex">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="#3C1E1E"><path d="M12 3C6.477 3 2 6.477 2 10.5c0 2.41 1.36 4.54 3.45 5.93L4.5 20.5l4.1-2.3A11.5 11.5 0 0012 18.5c5.523 0 10-3.477 10-7.5S17.523 3 12 3z"/></svg>
          카카오톡으로 바로 문의
        </a>
      </div>
    </div><!-- /form-card -->
  </div>
</section>

<!-- ─── FIRST HOME BUYER SCHEMES ─── -->
<section class="schemes-section" id="schemes">
  <div class="container">
    <div class="section-header">
      <div class="section-tag">First Home Buyer Benefits</div>
      <h2>주(State)별 <span class="gold-text">첫 집 구매 혜택</span> 총정리</h2>
      <p>FHOG · 인지세 면제 · 5% 보증금 지원까지 — 내가 받을 수 있는 혜택을 확인하세요</p>
    </div>

    <!-- Federal Schemes -->
    <div class="schemes-intro">
      <div class="scheme-card-fed">
        <span class="fed-badge">🇦🇺 연방 정부 · Federal</span>
        <div class="fed-title">First Home Guarantee (FHBG)</div>
        <span class="fed-highlight">5% 보증금</span>
        <div class="fed-desc">LMI(대출보험) 없이 집값의 5%만으로 내집 마련 가능. 나머지 15%를 정부가 보증.</div>
        <span class="fed-tag">소득 조건: 단독 $125k / 커플 $200k 이하</span>
      </div>
      <div class="scheme-card-fed">
        <span class="fed-badge">🏘️ 지방 · Regional First Home Guarantee</span>
        <div class="fed-title">지방 지역 첫 집 보증</div>
        <span class="fed-highlight">5% 보증금</span>
        <div class="fed-desc">지방(regional) 또는 지방 이주 시 적용. 가격 상한이 수도권과 다르게 적용됨. 연간 10,000가구 한정.</div>
        <span class="fed-tag">소득 조건: 단독 $125k / 커플 $200k 이하</span>
      </div>
      <div class="scheme-card-fed">
        <span class="fed-badge">👨‍👩‍👧 한부모 · Family Home Guarantee</span>
        <div class="fed-title">한부모 가정 주택 보증</div>
        <span class="fed-highlight">2% 보증금</span>
        <div class="fed-desc">부양 자녀가 있는 한부모 가정은 단 2% 보증금으로 LMI 없이 내집 마련 가능.</div>
        <span class="fed-tag">소득 조건: $125k 이하 · 연간 5,000가구 한정</span>
      </div>
    </div>

    <!-- State Tabs -->
    <div style="text-align:center; margin-bottom:20px">
      <p style="font-size:13px; color:var(--warm-gray)">거주 중이거나 구매 예정인 주(State)를 선택하세요</p>
    </div>
    <div class="state-tabs">
      <button class="state-tab active" onclick="showState('nsw')">🏙️ NSW</button>
      <button class="state-tab" onclick="showState('vic')">🏛️ VIC</button>
      <button class="state-tab" onclick="showState('qld')">☀️ QLD</button>
      <button class="state-tab" onclick="showState('sa')">🌵 SA</button>
      <button class="state-tab" onclick="showState('wa')">🌊 WA</button>
      <button class="state-tab" onclick="showState('tas')">🍃 TAS</button>
      <button class="state-tab" onclick="showState('nt')">🪃 NT</button>
      <button class="state-tab" onclick="showState('act')">🏛 ACT</button>
    </div>

    <!-- NSW -->
    <div class="state-panel active" id="panel-nsw">
      <div class="state-panel-header">
        <div class="state-flag">🏙️</div>
        <div><h3>뉴사우스웨일스 (NSW)</h3><p>시드니 및 NSW 전 지역 적용 혜택</p></div>
      </div>
      <div class="schemes-grid">
        <div class="scheme-benefit">
          <div class="sb-type grant">🟢 FHOG — 첫 집 보조금</div>
          <div class="sb-amount" style="color:#4ade80">$10,000</div>
          <div class="sb-title">First Home Owner Grant (NSW)</div>
          <ul class="sb-conditions">
            <li>신축 주택 또는 신규 건축 계약 (Off-the-plan 포함)</li>
            <li>구매가: 신축 $600,000 이하</li>
            <li>건축 계약: $750,000 이하</li>
            <li>호주 시민권자 또는 영주권자</li>
            <li>최소 6개월 실거주 의무</li>
          </ul>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type stamp">🔵 인지세 혜택 — Stamp Duty</div>
          <div class="sb-amount" style="color:#62b0c8">전액 면제</div>
          <div class="sb-title">First Home Buyer Assistance Scheme</div>
          <ul class="sb-conditions">
            <li>$800,000 미만: 인지세 전액 면제</li>
            <li>$800,000 ~ $1,000,000: 구간별 부분 감면</li>
            <li>기존(중고) 주택도 적용 가능</li>
            <li>이전 부동산 소유 이력 없어야 함</li>
          </ul>
          <div class="sb-note">💡 $800k 미만 기존 주택 구매 시 약 $30,000~$31,000 절약 가능</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type fhbg">⭐ FHBG 가격 상한</div>
          <div class="sb-amount" style="color:var(--gold-mid)">$900k</div>
          <div class="sb-title">연방 5% 보증 가격 한도 (NSW)</div>
          <ul class="sb-conditions">
            <li>시드니 · 수도권 · 주요 지역: $900,000</li>
            <li>기타 NSW 지방 지역: $750,000</li>
            <li>소득 조건: 단독 $125k / 커플 $200k 이하</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- VIC -->
    <div class="state-panel" id="panel-vic">
      <div class="state-panel-header">
        <div class="state-flag">🏛️</div>
        <div><h3>빅토리아 (VIC)</h3><p>멜버른 및 VIC 전 지역 적용 혜택</p></div>
      </div>
      <div class="schemes-grid">
        <div class="scheme-benefit">
          <div class="sb-type grant">🟢 FHOG — 첫 집 보조금</div>
          <div class="sb-amount" style="color:#4ade80">$10,000</div>
          <div class="sb-title">First Home Owner Grant (VIC)</div>
          <ul class="sb-conditions">
            <li>신축 주택 $750,000 이하</li>
            <li>멜버른 외 지방(Regional VIC): <strong style="color:#4ade80">$20,000</strong></li>
            <li>호주 시민권자 또는 영주권자</li>
            <li>최소 12개월 실거주 의무</li>
          </ul>
          <div class="sb-note">💡 지방 지역 구매 시 $20,000으로 상향!</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type stamp">🔵 인지세 혜택 — Stamp Duty</div>
          <div class="sb-amount" style="color:#62b0c8">전액 면제</div>
          <div class="sb-title">First Home Buyer Duty Exemption/Reduction</div>
          <ul class="sb-conditions">
            <li>$600,000 이하: 인지세 전액 면제</li>
            <li>$600,001 ~ $750,000: 구간별 부분 감면</li>
            <li>신축 및 기존 주택 모두 적용</li>
            <li>Off-the-plan 추가 할인 가능</li>
          </ul>
          <div class="sb-note">💡 $600k 미만 기존 주택 약 $31,000 절약</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type fhbg">⭐ FHBG 가격 상한</div>
          <div class="sb-amount" style="color:var(--gold-mid)">$800k</div>
          <div class="sb-title">연방 5% 보증 가격 한도 (VIC)</div>
          <ul class="sb-conditions">
            <li>멜버른 수도권: $800,000</li>
            <li>기타 VIC 지방: $650,000</li>
            <li>소득 조건: 단독 $125k / 커플 $200k 이하</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- QLD -->
    <div class="state-panel" id="panel-qld">
      <div class="state-panel-header">
        <div class="state-flag">☀️</div>
        <div><h3>퀸즐랜드 (QLD)</h3><p>브리즈번 및 QLD 전 지역 적용 혜택</p></div>
      </div>
      <div class="schemes-grid">
        <div class="scheme-benefit">
          <div class="sb-type grant">🟢 FHOG — 첫 집 보조금</div>
          <div class="sb-amount" style="color:#4ade80">$30,000</div>
          <div class="sb-title">First Home Owner Grant (QLD)</div>
          <ul class="sb-conditions">
            <li>신축 주택 또는 건축 계약</li>
            <li>한시적 $30,000 (2026년 6월 30일까지)</li>
            <li>이후 $15,000으로 복귀 예정</li>
            <li>가격 상한 없음 (QLD 전체)</li>
            <li>최소 6개월 실거주 의무</li>
          </ul>
          <div class="sb-note">⚡ 현재 가장 높은 FHOG 주! 기간 한정 $30,000</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type stamp">🔵 인지세 혜택 — Stamp Duty</div>
          <div class="sb-amount" style="color:#62b0c8">감면</div>
          <div class="sb-title">Home Concession (First Home)</div>
          <ul class="sb-conditions">
            <li>주거용 $700,000 이하 감면율 적용</li>
            <li>첫 집 구매자 추가 할인 적용</li>
            <li>신축·기존 모두 적용 가능</li>
          </ul>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type fhbg">⭐ FHBG 가격 상한</div>
          <div class="sb-amount" style="color:var(--gold-mid)">$700k</div>
          <div class="sb-title">연방 5% 보증 가격 한도 (QLD)</div>
          <ul class="sb-conditions">
            <li>브리즈번 수도권: $700,000</li>
            <li>기타 QLD 지방: $550,000</li>
            <li>소득 조건: 단독 $125k / 커플 $200k 이하</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- SA -->
    <div class="state-panel" id="panel-sa">
      <div class="state-panel-header">
        <div class="state-flag">🌵</div>
        <div><h3>사우스오스트레일리아 (SA)</h3><p>애들레이드 및 SA 전 지역 적용 혜택</p></div>
      </div>
      <div class="schemes-grid">
        <div class="scheme-benefit">
          <div class="sb-type grant">🟢 FHOG — 첫 집 보조금</div>
          <div class="sb-amount" style="color:#4ade80">$15,000</div>
          <div class="sb-title">First Home Owner Grant (SA)</div>
          <ul class="sb-conditions">
            <li>신축 주택 또는 Off-the-plan</li>
            <li>가격 상한 없음 (SA 전체)</li>
            <li>호주 시민권자 또는 영주권자</li>
            <li>최소 6개월 실거주 의무</li>
          </ul>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type stamp">🔵 인지세 혜택 — Stamp Duty</div>
          <div class="sb-amount" style="color:#62b0c8">전액 면제</div>
          <div class="sb-title">Off-the-Plan / 신축 인지세 면제</div>
          <ul class="sb-conditions">
            <li>Off-the-plan 신축 아파트 $650,000 이하 전액 면제</li>
            <li>일반 첫 집 구매: 별도 감면 없음</li>
            <li>SA 정부 추가 신축 장려 정책 수시 변경</li>
          </ul>
          <div class="sb-note">💡 애들레이드 CBD Off-the-plan 구매 시 최대 유리</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type fhbg">⭐ FHBG 가격 상한</div>
          <div class="sb-amount" style="color:var(--gold-mid)">$600k</div>
          <div class="sb-title">연방 5% 보증 가격 한도 (SA)</div>
          <ul class="sb-conditions">
            <li>애들레이드 수도권: $600,000</li>
            <li>기타 SA 지방: $450,000</li>
            <li>소득 조건: 단독 $125k / 커플 $200k 이하</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- WA -->
    <div class="state-panel" id="panel-wa">
      <div class="state-panel-header">
        <div class="state-flag">🌊</div>
        <div><h3>웨스턴오스트레일리아 (WA)</h3><p>퍼스 및 WA 전 지역 적용 혜택</p></div>
      </div>
      <div class="schemes-grid">
        <div class="scheme-benefit">
          <div class="sb-type grant">🟢 FHOG — 첫 집 보조금</div>
          <div class="sb-amount" style="color:#4ade80">$10,000</div>
          <div class="sb-title">First Home Owner Grant (WA)</div>
          <ul class="sb-conditions">
            <li>남부 WA (26th parallel 이남) 신축</li>
            <li>북부 WA: $10,000 (기존 주택 포함)</li>
            <li>가격 상한 없음</li>
            <li>최소 6개월 실거주 의무</li>
          </ul>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type stamp">🔵 인지세 혜택 — Stamp Duty</div>
          <div class="sb-amount" style="color:#62b0c8">전액 면제</div>
          <div class="sb-title">First Home Owner Rate / Concession</div>
          <ul class="sb-conditions">
            <li>$450,000 이하: 전액 면제</li>
            <li>$450,001 ~ $600,000: 구간별 부분 감면</li>
            <li>신축·기존 주택 모두 적용</li>
          </ul>
          <div class="sb-note">💡 $450k 이하 약 $15,000 이상 절약</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type fhbg">⭐ FHBG 가격 상한</div>
          <div class="sb-amount" style="color:var(--gold-mid)">$600k</div>
          <div class="sb-title">연방 5% 보증 가격 한도 (WA)</div>
          <ul class="sb-conditions">
            <li>퍼스 수도권: $600,000</li>
            <li>기타 WA 지방: $450,000</li>
            <li>소득 조건: 단독 $125k / 커플 $200k 이하</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- TAS -->
    <div class="state-panel" id="panel-tas">
      <div class="state-panel-header">
        <div class="state-flag">🍃</div>
        <div><h3>태즈매니아 (TAS)</h3><p>호바트 및 TAS 전 지역 적용 혜택</p></div>
      </div>
      <div class="schemes-grid">
        <div class="scheme-benefit">
          <div class="sb-type grant">🟢 FHOG — 첫 집 보조금</div>
          <div class="sb-amount" style="color:#4ade80">$10,000</div>
          <div class="sb-title">First Home Owner Grant (TAS)</div>
          <ul class="sb-conditions">
            <li>신축 주택 또는 신규 건축 계약</li>
            <li>가격 상한 없음</li>
            <li>최소 6개월 실거주 의무</li>
          </ul>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type stamp">🔵 인지세 혜택 — Stamp Duty</div>
          <div class="sb-amount" style="color:#62b0c8">50% 감면</div>
          <div class="sb-title">First Home Buyer Stamp Duty Concession</div>
          <ul class="sb-conditions">
            <li>첫 집 구매자 인지세 50% 감면</li>
            <li>신축 및 기존 주택 모두 적용</li>
            <li>소득 또는 가격 상한 없음</li>
          </ul>
          <div class="sb-note">💡 TAS는 별도 상한 없이 모든 첫 구매에 50% 적용</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type fhbg">⭐ FHBG 가격 상한</div>
          <div class="sb-amount" style="color:var(--gold-mid)">$600k</div>
          <div class="sb-title">연방 5% 보증 가격 한도 (TAS)</div>
          <ul class="sb-conditions">
            <li>호바트 수도권: $600,000</li>
            <li>기타 TAS 지방: $450,000</li>
            <li>소득 조건: 단독 $125k / 커플 $200k 이하</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- NT -->
    <div class="state-panel" id="panel-nt">
      <div class="state-panel-header">
        <div class="state-flag">🪃</div>
        <div><h3>노던 테리토리 (NT)</h3><p>다윈 및 NT 전 지역 적용 혜택</p></div>
      </div>
      <div class="schemes-grid">
        <div class="scheme-benefit">
          <div class="sb-type grant">🟢 FHOG — 첫 집 보조금</div>
          <div class="sb-amount" style="color:#4ade80">$10,000</div>
          <div class="sb-title">First Home Owner Grant (NT)</div>
          <ul class="sb-conditions">
            <li>신축 및 기존 주택 모두 적용 (NT 유일)</li>
            <li>가격 상한 없음</li>
            <li>최소 6개월 실거주 의무</li>
          </ul>
          <div class="sb-note">💡 NT는 기존(중고) 주택에도 FHOG 적용!</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type stamp">🔵 인지세 혜택 — Stamp Duty</div>
          <div class="sb-amount" style="color:#62b0c8">전액 면제</div>
          <div class="sb-title">First Home Owner Stamp Duty Concession</div>
          <ul class="sb-conditions">
            <li>$650,000 이하 전액 면제</li>
            <li>신축·기존 주택 모두 적용</li>
          </ul>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type fhbg">⭐ FHBG 가격 상한</div>
          <div class="sb-amount" style="color:var(--gold-mid)">$600k</div>
          <div class="sb-title">연방 5% 보증 가격 한도 (NT)</div>
          <ul class="sb-conditions">
            <li>NT 전 지역: $600,000</li>
            <li>소득 조건: 단독 $125k / 커플 $200k 이하</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- ACT -->
    <div class="state-panel" id="panel-act">
      <div class="state-panel-header">
        <div class="state-flag">🏛</div>
        <div><h3>호주 수도 특별구 (ACT)</h3><p>캔버라 적용 혜택 — FHOG는 없지만 인지세 면제 최강!</p></div>
      </div>
      <div class="schemes-grid">
        <div class="scheme-benefit">
          <div class="sb-type grant">🟢 FHOG</div>
          <div class="sb-amount" style="color:#6b7280">폐지</div>
          <div class="sb-title">ACT는 FHOG 없음 (2019 폐지)</div>
          <ul class="sb-conditions">
            <li>2019년 7월 이후 ACT FHOG 폐지</li>
            <li>대신 인지세 전액 면제로 대체</li>
          </ul>
          <div class="sb-note">⚠️ FHOG는 없지만 인지세 혜택이 가장 큼</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type stamp">🔵 인지세 혜택 — Stamp Duty</div>
          <div class="sb-amount" style="color:#62b0c8">전액 면제</div>
          <div class="sb-title">Home Buyer Concession Scheme (ACT)</div>
          <ul class="sb-conditions">
            <li>소득 심사 통과 시 인지세 전액 면제</li>
            <li>단독: 최대 $170,000 / 커플: $202,000 (세후)</li>
            <li>구매가 상한: $1,000,000 이하</li>
            <li>신축·기존 주택 모두 적용</li>
          </ul>
          <div class="sb-note">💡 캔버라 $800k 주택 인지세 면제 시 약 $27,000 절약!</div>
        </div>
        <div class="scheme-benefit">
          <div class="sb-type fhbg">⭐ FHBG 가격 상한</div>
          <div class="sb-amount" style="color:var(--gold-mid)">$750k</div>
          <div class="sb-title">연방 5% 보증 가격 한도 (ACT)</div>
          <ul class="sb-conditions">
            <li>ACT 전 지역: $750,000</li>
            <li>소득 조건: 단독 $125k / 커플 $200k 이하</li>
          </ul>
        </div>
      </div>
    </div>

    <p class="scheme-disclaimer">
      ※ 위 정보는 2025–2026 회계연도 기준이며 정부 정책 변경에 따라 달라질 수 있습니다. 최신 정확한 혜택 여부는 반드시 GB Home Loans 브로커와 개인 상황에 맞게 확인하세요.<br>
      FHOG = First Home Owner Grant · FHBG = First Home Guarantee (연방) · 인지세 = Stamp Duty/Transfer Duty
    </p>

  </div>
</section>

<!-- ─── CONTACT BAR ─── -->
<div class="contact-bar">
  <div class="container">
    <div class="contact-grid">
      <div class="contact-item">
        <div class="contact-icon">📞</div>
        <div>
          <div class="c-label">전화 상담</div>
          <div class="c-val">Jay: 0491 798 107</div>
          <div class="c-val">Chris: 0488 38 38 38</div>
        </div>
      </div>
      <div class="contact-item">
        <div class="contact-icon">✉️</div>
        <div>
          <div class="c-label">이메일</div>
          <div class="c-val">info@gbhomeloans.com.au</div>
        </div>
      </div>
      <div class="contact-item">
        <div class="contact-icon">📍</div>
        <div>
          <div class="c-label">오피스</div>
          <div class="c-val">NSW: 3/52 Holker St, Silverwater</div>
          <div class="c-val">SA: 25 Grenfell St, Adelaide</div>
        </div>
      </div>
      <div>
        <a href="http://pf.kakao.com/_razen/chat" target="_blank" class="kakao-bar-btn">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="#3C1E1E"><path d="M12 3C6.477 3 2 6.477 2 10.5c0 2.41 1.36 4.54 3.45 5.93L4.5 20.5l4.1-2.3A11.5 11.5 0 0012 18.5c5.523 0 10-3.477 10-7.5S17.523 3 12 3z"/></svg>
          카카오톡 채널 상담
        </a>
      </div>
    </div>
  </div>
</div>

<!-- ─── FOOTER ─── -->
<footer>
  <div class="footer-logo"><span class="gold-text">GB</span> Home Loans</div>
  <p>
    SKSY Family Ventures Pty Ltd · ABN: 40 620 991 764 · Australian Credit Licence: 384704<br>
    Mortgage Finance Association of Australia Ref: 835247<br><br>
    이 웹사이트에 제공된 정보는 일반적인 참고용이며 개인 금융 조언이 아닙니다. 모든 대출 신청은 개인의 재정 상황 및 은행 심사 기준에 따라 결과가 다를 수 있습니다.<br>
    © 2025 GB Home Loans · www.gbhomeloans.com.au
  </p>
</footer>

<!-- ─── FLOATING KAKAO ─── -->
<div class="floating-kakao">
  <a href="http://pf.kakao.com/_razen/chat" target="_blank" title="카카오톡 상담">
    <svg width="28" height="28" viewBox="0 0 24 24" fill="#3C1E1E"><path d="M12 3C6.477 3 2 6.477 2 10.5c0 2.41 1.36 4.54 3.45 5.93L4.5 20.5l4.1-2.3A11.5 11.5 0 0012 18.5c5.523 0 10-3.477 10-7.5S17.523 3 12 3z"/></svg>
  </a>
  <span class="floating-label">카카오톡</span>
</div>

<!-- ─── SCRIPTS ─── -->
<script>
// ── Tax calculation (Australia 2024-25) ──
function calcTax(gross) {
  let tax = 0;
  if (gross <= 18200) tax = 0;
  else if (gross <= 45000) tax = (gross - 18200) * 0.16;
  else if (gross <= 135000) tax = 4288 + (gross - 45000) * 0.30;
  else if (gross <= 190000) tax = 31288 + (gross - 135000) * 0.37;
  else tax = 51638 + (gross - 190000) * 0.45;
  // Medicare levy 2%
  const medicare = gross > 26000 ? gross * 0.02 : 0;
  return tax + medicare;
}

function formatCurrency(n) {
  return '$' + Math.round(n).toLocaleString('en-AU');
}

function calculateBorrowing() {
  const income1 = parseFloat(document.getElementById('income1').value) || 0;
  const income2 = parseFloat(document.getElementById('income2').value) || 0;
  const otherIncome = parseFloat(document.getElementById('otherIncome').value) || 0;
  const monthlyExpenses = parseFloat(document.getElementById('expenses').value) || 0;
  const monthlyDebts = parseFloat(document.getElementById('debts').value) || 0;
  const dependants = parseInt(document.getElementById('dependants').value) || 0;
  const loanTerm = parseInt(document.getElementById('loanTerm').value) || 30;

  if (income1 === 0) {
    alert('소득을 입력해 주세요.');
    return;
  }

  const totalGross = income1 + income2 + otherIncome;

  // Net income after tax
  const tax1 = calcTax(income1);
  const tax2 = calcTax(income2);
  const netAnnual = totalGross - tax1 - tax2;
  const netMonthly = netAnnual / 12;

  // Dependant cost factor (~$700/month per dependant as buffer)
  const depCost = dependants * 700;

  // Monthly surplus
  const surplus = netMonthly - monthlyExpenses - monthlyDebts - depCost;

  if (surplus <= 200) {
    document.getElementById('resultMain').style.display = 'block';
    document.querySelector('.result-placeholder').style.display = 'none';
    document.getElementById('resultAmount').textContent = '계산 어려움';
    document.getElementById('resultSubtitle').textContent = '소득 대비 지출이 높습니다';
    document.getElementById('bNetIncome').textContent = formatCurrency(netAnnual);
    document.getElementById('bMonthly').textContent = formatCurrency(surplus);
    document.getElementById('bRepayment').textContent = '—';
    return;
  }

  // Banks use a stress-test rate (assessment rate ~9.5%)
  const assessRate = 0.095 / 12;
  const n = loanTerm * 12;
  const factor = assessRate / (1 - Math.pow(1 + assessRate, -n));

  // Borrowing capacity: surplus / monthly_factor
  // Banks typically allow 30-35% debt service ratio; use 30%
  const maxRepayment = surplus * 0.85; // 85% of surplus goes to repayment
  const borrowingCapacity = maxRepayment / factor;

  // Actual repayment at 6.5%
  const actualRate = 0.065 / 12;
  const actualFactor = actualRate / (1 - Math.pow(1 + actualRate, -n));
  const actualRepayment = borrowingCapacity * actualFactor;

  document.querySelector('.result-placeholder').style.display = 'none';
  document.getElementById('resultMain').style.display = 'block';
  document.getElementById('resultAmount').textContent = formatCurrency(borrowingCapacity);
  document.getElementById('resultSubtitle').textContent = `${loanTerm}년 원리금 균등상환 기준`;
  document.getElementById('bNetIncome').textContent = formatCurrency(netAnnual);
  document.getElementById('bMonthly').textContent = formatCurrency(maxRepayment);
  document.getElementById('bRepayment').textContent = formatCurrency(actualRepayment) + '/월';
}

// ── Form submission ──
async function submitForm() {
  const required = {
    'fName': '이름을',
    'fPhone': '연락처를',
    'fEmail': '이메일을',
    'fVisa': '비자 상태를',
    'fEmployment': '고용 형태를',
    'fAnnualIncome': '연 소득을'
  };

  for (const [id, label] of Object.entries(required)) {
    const el = document.getElementById(id);
    if (!el || !el.value.trim()) {
      alert(`${label} 입력해 주세요.`);
      el && el.focus();
      return;
    }
  }

  // 버튼 로딩 상태
  const btn = document.querySelector('.submit-btn');
  btn.textContent = '⏳ 전송 중...';
  btn.disabled = true;

  // 대출 유형 선택값
  const loanTypeEl = document.getElementById('fLoanType');
  const loanType = loanTypeEl?.options[loanTypeEl.selectedIndex]?.text || '미선택';

  const formData = {
    access_key: "80d69326-8d5e-4916-a643-7bf71fe5910e",
    subject: `[GB Home Loans] 상담 신청 - ${document.getElementById('fName').value}`,
    from_name: "GB Home Loans 웹사이트",
    botcheck: "",
    "고객 이름":        document.getElementById('fName').value,
    "연락처":           document.getElementById('fPhone').value,
    "카카오톡 ID":      document.getElementById('fKakao').value || "미기입",
    "이메일":           document.getElementById('fEmail').value,
    "생년월일":         document.getElementById('fDob').value || "미기입",
    "거주 주(State)":   document.getElementById('fState').value || "미기입",
    "비자 상태":        document.getElementById('fVisa').value,
    "대출 유형":        loanType,
    "예상 부동산 가격": "$" + (document.getElementById('fPropPrice').value || "미기입"),
    "보증금":           "$" + (document.getElementById('fDeposit').value || "미기입"),
    "부동산 유형":      document.getElementById('fPropType').value || "미기입",
    "구매 예정 시기":   document.getElementById('fTimeline').value || "미기입",
    "고용 형태":        document.getElementById('fEmployment').value,
    "현직장 근무기간":  document.getElementById('fJobDuration').value || "미기입",
    "연 소득(세전)":    "$" + document.getElementById('fAnnualIncome').value,
    "기타 소득":        "$" + (document.getElementById('fOtherIncome').value || "0"),
    "총 저축액":        "$" + (document.getElementById('fSavings').value || "미기입"),
    "저축 기간":        document.getElementById('fSavingsPeriod').value || "미기입",
    "신용카드 한도":    "$" + (document.getElementById('fCCLimit').value || "0"),
    "기타 대출 상환":   "$" + (document.getElementById('fOtherLoans').value || "0"),
    "월 생활비":        "$" + (document.getElementById('fLivingExp').value || "미기입"),
    "부양가족 수":      document.getElementById('fDependants').value + "명",
    "공동신청인":       document.querySelector('input[name="coBorrower"]:checked')?.value === 'yes' ? '있음' : '없음',
    "파트너 고용형태":  document.getElementById('fPartnerEmployment')?.value || "해당없음",
    "파트너 연소득":    document.getElementById('fPartnerIncome')?.value ? "$" + document.getElementById('fPartnerIncome').value : "해당없음",
    "기존부동산":       document.querySelector('input[name="hasProperty"]:checked')?.value === 'yes' ? '있음' : '없음',
    "부동산 주소":      document.getElementById('fPropertyAddress')?.value || "해당없음",
    "부동산 가치":      document.getElementById('fPropertyValue')?.value ? "$" + document.getElementById('fPropertyValue').value : "해당없음",
    "모기지 잔액":      document.getElementById('fPropertyMortgage')?.value ? "$" + document.getElementById('fPropertyMortgage').value : "해당없음",
    "이전 홈론 신청":   document.querySelector('input[name="prevLoan"]:checked')?.value === 'yes' ? '있음' : '없음',
    "유입 경로":        document.getElementById('fSource').value || "미기입",
    "추가 문의사항":    document.getElementById('fNotes').value || "없음"
  };

  try {
    const response = await fetch("https://api.web3forms.com/submit", {
      method: "POST",
      headers: { "Content-Type": "application/json" },
      body: JSON.stringify(formData)
    });

    const result = await response.json();

    if (result.success) {
      document.getElementById('enquiryForm').style.display = 'none';
      document.getElementById('successMsg').style.display = 'block';
      document.getElementById('successMsg').scrollIntoView({ behavior: 'smooth', block: 'center' });
    } else {
      throw new Error('전송 실패');
    }
  } catch (err) {
    btn.textContent = '📨 상담 신청 제출하기';
    btn.disabled = false;
    alert('전송 중 오류가 발생했습니다.\n카카오톡으로 직접 문의해 주세요.');
  }
}

// ── Toggle partner section ──
function togglePartner(show) {
  const sec = document.getElementById('partnerSection');
  if (show) sec.classList.add('visible');
  else sec.classList.remove('visible');
}

// ── Toggle existing property detail ──
function toggleProperty(show) {
  const sec = document.getElementById('propertyDetail');
  if (show) sec.classList.add('visible');
  else sec.classList.remove('visible');
}

// ── State scheme tabs ──
function showState(state) {
  document.querySelectorAll('.state-panel').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.state-tab').forEach(t => t.classList.remove('active'));
  const panel = document.getElementById('panel-' + state);
  if (panel) panel.classList.add('active');
  event.currentTarget.classList.add('active');
}

document.addEventListener('keydown', function(e) {
  if (e.key === 'Enter' && document.activeElement.closest('.calc-inputs')) {
    calculateBorrowing();
  }
});
</script>
</body>
</html>
