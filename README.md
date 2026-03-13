<style>
/* --- 極簡藝術 Zine 風格 (Responsive) --- */
:root {
  --text-main: #333333;
  --bg-color: #f7f3f0; 
  --accent: #b03a2e;
}

body {
  font-family: 'PingFang TC', 'MicroSoft JhengHei', 'serif', 'Georgia';
  background-color: var(--bg-color);
  color: var(--text-main);
  margin: 0 auto;
  line-height: 1.8;
  letter-spacing: 0.1em;
  padding: 40px;
  max-width: 650px;
}

@media (max-width: 767px) {
  body { padding: 25px; }
  .grid-box { grid-template-columns: 1fr !important; }
  .magazine-header { flex-direction: column; gap: 5px; }
}

.magazine-header {
  font-family: 'Courier New', monospace;
  font-size: 10px;
  text-transform: uppercase;
  display: flex;
  justify-content: space-between;
  margin-bottom: 60px;
  border-bottom: 1px solid #ddd;
  padding-bottom: 5px;
}

h1 { text-align: center; font-size: 24px; font-weight: 300; margin: 60px 0; letter-spacing: 0.2em; }
h2 { font-size: 13px; font-weight: 600; text-transform: uppercase; margin-top: 70px; margin-bottom: 30px; text-align: center; color: var(--accent); letter-spacing: 0.3em; }

/* 住宿與老師 藝術網格佈局 */
.grid-box { 
  display: grid; 
  grid-template-columns: 1.2fr 0.8fr; 
  gap: 40px; 
  margin: 50px 0; 
  border-top: 1px solid #333; 
  padding-top: 40px; 
}

.section-title {
  font-family: 'Helvetica', sans-serif;
  font-size: 18px;
  font-weight: 300;
  margin-bottom: 15px;
  display: block;
  letter-spacing: 0.05em;
}

.info-sub {
  font-size: 11px;
  color: #888;
  text-transform: uppercase;
  display: block;
  margin-bottom: 8px;
  letter-spacing: 0.1em;
}

.info-zh {
  font-size: 13px;
  color: #666;
  line-height: 1.6;
  margin-top: 10px;
  display: block;
}

/* 預算表單 */
.budget-list { background: rgba(255,255,255,0.5); padding: 25px; border-radius: 0; border: 1px solid #eee; margin: 30px 0; }
.budget-row { display: flex; justify-content: space-between; font-size: 12px; padding: 10px 0; border-bottom: 1px solid #eee; }

.lifestyle-item { margin-bottom: 35px; font-size: 14px; position: relative; padding-left: 25px; }
.lifestyle-item::before { content: ' '; position: absolute; left: 0; width: 6px; height: 6px; background: var(--accent); border-radius: 50%; top: 8px; }

.footer { text-align: center; font-size: 10px; margin-top: 100px; padding-bottom: 60px; font-family: 'Courier New', monospace; color: #999; }
</style>

<div class="magazine-header">
  <span>HIROSAKI JOURNAL / VOL 01</span>
  <span>ARCHIVE 2026 - LAN</span>
</div>

<h1>AOMORI LIFESTYLE JOURNEY</h1>

<div class="grid-box">
  <div>
    <span class="info-sub">01 / Accommodation</span>
    <span class="section-title">Stay & Base</span>
    <p style="font-size: 15px;"><b>Hirosaki Central Studio</b></p>
    <span class="info-zh">
      鄰近弘前公園的在地公寓。選擇生活機能便利的區域，確保每日能步行至錢湯與咖啡廳習作。
      <br><i>(Located near Hirosaki Park for daily walkability.)</i>
    </span>
  </div>
  <div style="border-left: 1px solid #ddd; padding-left: 30px;">
    <span class="info-sub">02 / Mentorship</span>
    <span class="section-title">Tutor</span>
    <p style="font-size: 15px;"><b>1-on-1 Private Session</b></p>
    <span class="info-zh">
      沈浸式語言顧問。每日 3 小時對話，地點選定於在地歷史建築咖啡廳。
      <br><i>(3-hour daily immersion sessions at historic cafes.)</i>
    </span>
  </div>
</div>

<h2>Financial Plan / 費用預算</h2>
<div class="budget-list">
  <div class="budget-row"><span>Stay (30 Nights) / 住宿費用</span><b>NT$ 32,000</b></div>
  <div class="budget-row"><span>Private Tutor / 私人老師</span><b>NT$ 18,500</b></div>
  <div class="budget-row"><span>Daily Life / 在地生活開銷</span><b>NT$ 15,000</b></div>
  <div class="budget-row"><span>Transport / 交通工具</span><b>NT$ 8,000</b></div>
  <div class="budget-row" style="border:none; margin-top: 15px; font-size: 15px; font-weight: bold;"><span>Est. Total / 總計預算</span><b>NT$ 73,500</b></div>
</div>

---

<h2>Phase 01: Local Immersion / 在地沈浸</h2>
<div class="lifestyle-list">
  <div class="lifestyle-item">
    <b>Arrival & Base Setup</b><br>
    <span class="info-zh">抵達弘前、辦理單車租借，建立為期 30 天的移動動線。</span>
  </div>
  <div class="lifestyle-item">
    <b>Starbucks Ritual</b><br>
    <span class="info-zh">於星巴克弘前公園前店進行初次面談，確立語言學習目標。</span>
  </div>
  <div class="lifestyle-item">
    <b>Sento Social</b><br>
    <span class="info-zh">走訪「中央溫泉」錢湯，透過觀察澡堂社交學習在地禮儀。</span>
  </div>
</div>

<p class="footer">Captured by LAN • AOMORI Living Archive • 2026</p>
