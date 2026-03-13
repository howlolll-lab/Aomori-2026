<style>
/* --- Minimalist Responsive Journal Style --- */
:root {
  --text-main: #2c2c2c;
  --text-mute: #8e8e8e;
  --bg-color: #f9f7f2; 
  --accent: #b03a2e;
  --line: #e0ddd5;
}

body {
  font-family: 'PingFang TC', 'MicroSoft JhengHei', 'Georgia', serif;
  background-color: var(--bg-color);
  color: var(--text-main);
  margin: 0 auto;
  line-height: 2.0;
  letter-spacing: 0.05em;
  padding: 20px;
}

@media (min-width: 768px) {
  body { max-width: 750px; padding: 80px 0; }
  .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; }
  .photo-grid { grid-template-columns: 1fr 1fr 1fr; }
}

@media (max-width: 767px) {
  body { padding: 40px 20px; }
  .grid-2 { display: block; }
  .photo-grid { grid-template-columns: 1fr 1fr; }
  .mobile-space { margin-top: 40px; }
}

.journal-header {
  font-family: 'Helvetica', sans-serif;
  font-size: 10px;
  text-transform: uppercase;
  color: var(--text-mute);
  display: flex;
  justify-content: space-between;
  margin-bottom: 40px;
  border-bottom: 1px solid var(--line);
  padding-bottom: 10px;
}

h1 { text-align: center; font-weight: 300; margin: 60px 0; letter-spacing: 0.3em; line-height: 1.4; font-size: 24px; }
h2 { font-size: 12px; font-weight: 600; text-transform: uppercase; letter-spacing: 0.25em; margin: 60px 0 30px; color: var(--text-mute); text-align: center; border-top: 1px solid var(--line); padding-top: 50px; }
h3 { font-size: 14px; font-weight: 600; margin-bottom: 20px; border-left: 2px solid var(--accent); padding-left: 15px; }

.itinerary-list { list-style: none; padding: 0; }
.itinerary-item { margin-bottom: 25px; font-size: 14px; display: flex; }
.day-index { font-family: 'Courier New', monospace; font-size: 11px; color: var(--text-mute); width: 50px; }
.task-content b { color: var(--text-main); display: block; margin-bottom: 4px; }

.budget-table { width: 100%; border-collapse: collapse; font-size: 13px; margin-bottom: 30px; }
.budget-table td { padding: 10px 0; border-bottom: 1px solid #eee; }
.budget-table td:last-child { text-align: right; font-family: 'Courier New', monospace; }

.photo-grid { display: grid; gap: 15px; margin: 40px 0; }
.photo-box { background: #fff; aspect-ratio: 1/1; display: flex; align-items: center; justify-content: center; font-size: 9px; color: #ccc; border: 1px solid var(--line); text-transform: uppercase; }

.footer { text-align: center; font-size: 10px; color: var(--text-mute); margin-top: 120px; padding-bottom: 60px; letter-spacing: 0.2em; }
</style>

<div class="journal-header">
  <span>Issue 01 / Vol. 2026</span>
  <span>LAN - Aomori Archive</span>
</div>

<h1>AOMORI LIFESTYLE JOURNEY</h1>

---

<div class="grid-2">
  <div>
    <h3>Stay & Base</h3>
    <p style="font-size: 14px; color: #555;">
      <b>Location:</b> Hirosaki Central District<br>
      <b>Style:</b> Local Guesthouse / Airbnb<br>
      <b>Vibe:</b> 靠近弘前公園，步行可達中央溫泉與星巴克古蹟店。
    </p>
  </div>
  <div class="mobile-space">
    <h3>Private Tutor</h3>
    <p style="font-size: 14px; color: #555;">
      <b>Mentor:</b> Native Instructor (Hirosaki Univ. Affiliate)<br>
      <b>Session:</b> 3 Hours / Daily (Mon-Fri)<br>
      <b>Base:</b> Selected Cafes (Starbucks, Taisho Roman, etc.)
    </p>
  </div>
</div>

---

<h2>Projected Expenses (Budget)</h2>
<table class="budget-table">
  <tr><td>Stay (30 Nights / Local Studio)</td><td>NT$ 32,000</td></tr>
  <tr><td>Private Tutor (40 Hours Session)</td><td>NT$ 18,500</td></tr>
  <tr><td>Transportation (MaaS, JR Rail, Bike)</td><td>NT$ 8,000</td></tr>
  <tr><td>Daily Life (Food, Onsen, Groceries)</td><td>NT$ 15,000</td></tr>
  <tr style="font-weight: bold; border-bottom: 2px solid var(--text-main);"><td>Total Estimate</td><td>NT$ 73,500</td></tr>
</table>

---

<h2>Phase 01: Local Immersion</h2>
<div class="itinerary-list">
  <div class="itinerary-item">
    <div class="day-index">D.01</div>
    <div class="task-content"><b>Arrival & Settling</b> 抵達弘前、Airbnb Check-in、單車租借。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.02</div>
    <div class="task-content"><b>Market Discovery</b> 虹之味市場實戰，練習詢問蘋果產地與口感。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.03</div>
    <div class="task-content"><b>Coffee Session</b> 星巴克弘前公園前店，與語言顧問初次交流。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.05</div>
    <div class="task-content"><b>Bathhouse Ritual</b> 體驗在地「中央溫泉」錢湯，感受庶民日常。</div>
  </div>
</div>

<h2>Phase 02: Nature & Arts</h2>
<div class="itinerary-list">
  <div class="itinerary-item">
    <div class="day-index">D.12</div>
    <div class="task-content"><b>Culinary Task</b> 前往超市購買在地食材，挑戰製作簡單的津輕料理。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">W.END</div>
    <div class="task-content"><b>Mountain Retreat</b> 奧入瀨溪流與十和田湖，體驗「湯治」療癒。</div>
  </div>
</div>

<h2>Visual Notes</h2>
<div class="photo-grid">
  <div class="photo-box">Plate 01: Market</div>
  <div class="photo-box">Plate 02: Coffee</div>
  <div class="photo-box">Plate 03: Street</div>
  <div class="photo-box">Plate 04: Library</div>
  <div class="photo-box">Plate 05: Onsen</div>
  <div class="photo-box">Plate 06: Nature</div>
</div>

<p class="footer">CAPTURED BY LAN • AOMORI LIFESTYLE PROJECT • 2026</p>
