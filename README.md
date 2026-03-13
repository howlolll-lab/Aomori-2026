<style>
/* --- 極致藝術 Zine / 雜誌風格 (Aomori City Focus) --- */
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

.nav-bar a { text-decoration: none; color: #888; }

h1 { text-align: center; font-size: 24px; font-weight: 300; margin: 40px 0; letter-spacing: 0.3em; }
h2 { font-size: 14px; font-weight: 600; text-transform: uppercase; margin-top: 60px; text-align: center; color: var(--accent); }

.zine-card { border: 1px solid #333; padding: 25px; margin: 30px 0; background: #fff; position: relative; }
.zine-card::after { content: ''; position: absolute; bottom: -6px; right: -6px; width: 100%; height: 100%; border: 1px solid #333; z-index: -1; }
.label { font-family: 'Courier New', monospace; font-size: 9px; background: #333; color: #fff; padding: 2px 8px; position: absolute; top: -10px; left: 10px; }

.lifestyle-list { list-style: none; padding: 0; }
.lifestyle-item { margin-bottom: 30px; font-size: 14px; border-left: 2px solid #ddd; padding-left: 15px; }
.day-tag { font-family: 'Courier New', monospace; font-size: 11px; color: var(--accent); font-weight: bold; }

.footer { text-align: center; font-size: 10px; margin-top: 100px; color: #999; }
</style>

<div class="nav-bar">
  <a href="#base">BASE</a> / <a href="#tutor">TUTOR</a> / <a href="#daily">DAILY</a> / <a href="#budget">BUDGET</a>
</div>

<h1>AOMORI LIFE ARCHIVE</h1>

<h2 id="base">Base & Stay</h2>
<div class="zine-card">
  <span class="label">LOCATION</span>
  <b>Aomori City Central Apartment</b>
  <p style="font-size: 13px; color: #555; margin-top: 10px;">
    📍 <a href="https://maps.app.goo.gl/3Z6S6X7Z6S6X7Z6S6">青森市新町 1-XX-XX</a> (Airbnb / Guesthouse)<br>
    鄰近青森車站，步行 5 分鐘可達 <a href="https://maps.app.goo.gl/AomoriAFactory">A-Factory</a> 與海濱。
  </p>
</div>

<h2 id="tutor">Mentor / Private Support</h2>
<div class="zine-card">
  <span class="label">TUTOR</span>
  <b>Language Counselor / Local Guide</b>
  <p style="font-size: 13px; color: #555; margin-top: 10px;">
    👩‍🏫 <b>Instructor:</b> Sato-san (Native Speaker)<br>
    💬 <b>Sessions:</b> 每週一至五，10:00 - 13:00<br>
    📍 <b>Location:</b> <a href="https://maps.app.goo.gl/AomoriStarbucks">Starbucks Aomori Shinmachi</a>
  </p>
</div>

<h2 id="daily">30-Day Itinerary</h2>
<div class="lifestyle-list">
  <div class="lifestyle-item">
    <span class="day-tag">PHASE 01: CITY IMMERSION</span>
    <b>D.01-D.07 青森市區適應期</b><br>
    - 至 <a href="https://maps.app.goo.gl/AugaMarket">Auga 鮮魚市場</a> 吃早餐練習日文。<br>
    - 走訪 <a href="https://maps.app.goo.gl/WaRasse">睡魔之家 Wa Rasse</a> 了解在地工藝。
  </div>
  <div class="lifestyle-item">
    <span class="day-tag">PHASE 02: HIROSAKI EXCURSION</span>
    <b>D.14-D.15 弘前二日習作</b><br>
    - 前往 <a href="https://maps.app.goo.gl/HirosakiPark">弘前公園</a> 散步。<br>
    - 在 <a href="https://maps.app.goo.gl/HirosakiStarbucks">弘前古蹟星巴克</a> 進行深度習作。
  </div>
  <div class="lifestyle-item">
    <span class="day-tag">PHASE 03: ARTS & WINTER</span>
    <b>D.20-D.25 藝術沈浸</b><br>
    - 前往 <a href="https://maps.app.goo.gl/AomoriMuseum">青森縣立美術館</a>。<br>
    - 到 <a href="https://maps.app.goo.gl/AsamushiOnsen">淺蟲溫泉</a> 體驗海邊錢湯文化。
  </div>
</div>

<h2 id="budget">Budget</h2>
<div style="background: #fff; padding: 20px; border: 1px dashed #333; font-size: 13px;">
  <div style="display: flex; justify-content: space-between; border-bottom: 1px solid #eee; padding: 5px 0;"><span>Stay</span><b>NT$ 32,000</b></div>
  <div style="display: flex; justify-content: space-between; border-bottom: 1px solid #eee; padding: 5px 0;"><span>Tutor</span><b>NT$ 18,500</b></div>
  <div style="display: flex; justify-content: space-between; padding: 5px 0; font-weight: bold;"><span>Total</span><b>NT$ 73,500</b></div>
</div>

<p class="footer">PRIVATE ARCHIVE • LAN AOMORI 2026</p>
