<style>
/* --- 極致藝術 Zine / 雜誌風格 (Aomori Edition) --- */
:root {
  --text-main: #333333;
  --bg-color: #f7f3f0; 
  --accent: #b03a2e;
}

body {
  font-family: 'PingFang TC', 'MicroSoft JhengHei', serif;
  background-color: var(--bg-color);
  color: var(--text-main);
  margin: 0 auto;
  line-height: 1.8;
  letter-spacing: 0.08em;
  padding: 40px 20px;
  max-width: 700px;
}

/* 模擬分頁導覽列 */
.nav-bar {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-bottom: 40px;
  font-family: 'Courier New', monospace;
  font-size: 11px;
  border-bottom: 1px solid #333;
  padding-bottom: 15px;
}

.nav-bar a {
  text-decoration: none;
  color: #888;
  transition: 0.3s;
}

.nav-bar a:hover { color: var(--accent); }

.magazine-header {
  font-family: 'Courier New', monospace;
  font-size: 10px;
  display: flex;
  justify-content: space-between;
  margin-bottom: 30px;
}

h1 { text-align: center; font-size: 26px; font-weight: 300; margin: 40px 0; letter-spacing: 0.3em; }
h2 { font-size: 14px; font-weight: 600; text-transform: uppercase; letter-spacing: 0.2em; margin-top: 80px; margin-bottom: 30px; text-align: center; border-bottom: 1px solid #333; padding-bottom: 10px; }

/* 錯落資訊卡片 */
.zine-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 30px; margin: 40px 0; }
.zine-card { border: 1px solid #333; padding: 20px; position: relative; background: #fff; }
.zine-card::after { content: ''; position: absolute; bottom: -5px; right: -5px; width: 100%; height: 100%; border: 1px solid #333; z-index: -1; }
.card-label { font-family: 'Courier New', monospace; font-size: 9px; background: #333; color: #fff; padding: 2px 8px; position: absolute; top: -10px; left: 10px; }

/* 行程列表 */
.lifestyle-list { list-style: none; padding: 0; }
.lifestyle-item { margin-bottom: 30px; font-size: 14px; border-left: 2px solid #ddd; padding-left: 15px; }
.day-tag { font-family: 'Courier New', monospace; font-size: 11px; color: var(--accent); font-weight: bold; display: block; }

.footer { text-align: center; font-size: 10px; margin-top: 100px; color: #999; letter-spacing: 0.2em; padding-bottom: 60px; }

@media (max-width: 600px) { .zine-grid { grid-template-columns: 1fr; } }
</style>

<div class="magazine-header">
  <span>AOMORI CITY ARCHIVE / 2026</span>
  <span>LAN - LIFE JOURNAL</span>
</div>

<div class="nav-bar">
  <a href="#base">BASE</a>
  <a href="#tutor">TUTOR</a>
  <a href="#itinerary">ITINERARY</a>
  <a href="#budget">BUDGET</a>
</div>

<h1>AOMORI LIFESTYLE JOURNEY</h1>

---

<h2 id="base">Accommodation / 住宿詳細</h2>
<div class="zine-card">
  <span class="card-label">BASE STATION</span>
  <p><b>Aomori City Central Apartment</b></p>
  <p style="font-size: 12px; color: #666;">
    📍 <a href="https://maps.google.com/?q=Aomori+Station">青森站周邊區域 (Shinmachi District)</a><br>
    選擇鄰近 <b>A-Factory</b> 與 <b>Auga 鮮魚市場</b> 的地點，步行即可抵達海濱公園與市區習作空間。
  </p>
</div>

<h2 id="tutor">Private Mentor / 語言顧問</h2>
<div class="zine-grid">
  <div class="zine-card">
    <span class="card-label">TUTOR A</span>
    <p><b>Native Instructor (Online/Offline)</b></p>
    <p style="font-size: 12px; color: #666;">
      🔗 <a href="https://www.italki.com/">iTalki Platform</a><br>
      每週固定 3-5 次會話，專注於青森生活場景應用。
    </p>
  </div>
  <div class="zine-card">
    <span class="card-label">TUTOR B</span>
    <p><b>Local Volunteer Guide</b></p>
    <p style="font-size: 12px; color: #666;">
      📍 <a href="https://www.tic-aomori.jp/">Aomori Tourist Info</a><br>
      預約在地文化翻譯志工，深入了解睡魔祭文化。
    </p>
  </div>
</div>

---

<h2 id="itinerary">Daily Journey / 行程安排</h2>

<div class="lifestyle-list">
  <div class="lifestyle-item">
    <span class="day-tag">PHASE 01: CITY EXPLORATION (AOMORI)</span>
    <b>D.01 - D.05 : 海濱生活圈建立</b><br>
    - 在 <a href="https://maps.google.com/?q=A-Factory">A-Factory</a> 挑選在地食材。<br>
    - 每日早晨至海濱公園散步，在 <a href="https://maps.google.com/?q=Starbucks+Aomori+Llov">Starbucks Aomori</a> 進行首週練習。
  </div>

  <div class="lifestyle-item" style="border-left-color: var(--accent);">
    <span class="day-tag">PHASE 02: HIROSAKI EXCURSION (SIDE TRIP)</span>
    <b>D.10 - D.12 : 弘前古城習作</b><br>
    - 搭乘奧羽本線前往弘前 (約 40 min)。<br>
    - 走訪 <a href="https://maps.google.com/?q=Hirosaki+Castle">弘前公園</a> 與 <a href="https://maps.google.com/?q=Fujita+Memorial+Garden">藤田紀念庭園</a>。<br>
    - 在弘前古蹟星巴克進行下午茶習作。
  </div>

  <div class="lifestyle-item">
    <span class="day-tag">PHASE 03: ARTS & NATURE</span>
    <b>D.15 - D.20 : 藝術沈浸</b><br>
    - 前往 <a href="https://maps.google.com/?q=Aomori+Museum+of+Art">青森縣立美術館</a> 觀賞青森犬。<br>
    - 安排 2D1N 前往奧入瀨溪流。
  </div>
</div>

---

<h2 id="budget">Financial Plan / 預算</h2>
<div style="background: #fff; padding: 25px; border: 1px dashed #333; font-size: 13px;">
  <div style="display: flex; justify-content: space-between; border-bottom: 1px solid #eee; padding: 10px 0;"><span>Accommodation (Stay)</span><b>NT$ 32,000</b></div>
  <div style="display: flex; justify-content: space-between; border-bottom: 1px solid #eee; padding: 10px 0;"><span>Private Mentor</span><b>NT$ 18,500</b></div>
  <div style="display: flex; justify-content: space-between; border-bottom: 1px solid #eee; padding: 10px 0;"><span>Lifestyle & Dining</span><b>NT$ 15,000</b></div>
  <div style="display: flex; justify-content: space-between; padding: 10px 0; font-weight: bold;"><span>Total</span><b>NT$ 73,500</b></div>
</div>

<p class="footer">CAPTURED BY LAN • 2026 AOMORI PROJECT</p>
