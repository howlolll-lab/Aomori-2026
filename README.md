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
h2 { font-size: 14px; font-weight: 500; text-transform: uppercase; margin-top: 60px; text-align: center; color: var(--accent); }

/* 住宿與老師 網格佈局 */
.grid-box { display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px; margin: 40px 0; border-top: 1px solid #ddd; padding-top: 30px; }
.info-label { font-size: 11px; color: #888; text-transform: uppercase; display: block; margin-bottom: 5px; }
.info-value { font-size: 15px; font-weight: 500; }

/* 預算表單 */
.budget-list { background: #fff; padding: 25px; border-radius: 2px; border: 1px solid #eee; margin: 30px 0; }
.budget-row { display: flex; justify-content: space-between; font-size: 13px; padding: 8px 0; border-bottom: 1px dashed #eee; }

.lifestyle-item { margin-bottom: 30px; font-size: 14px; position: relative; padding-left: 20px; }
.lifestyle-item::before { content: '●'; position: absolute; left: 0; color: var(--accent); font-size: 10px; top: 2px; }

.footer { text-align: center; font-size: 10px; margin-top: 100px; padding-bottom: 60px; font-family: 'Courier New', monospace; }
</style>

<div class="magazine-header">
  <span>HIROSAKI JOURNAL</span>
  <span>LAN - 2026 Archive</span>
</div>

<h1>AOMORI LIFESTYLE JOURNEY</h1>

<div class="grid-box">
  <div>
    <span class="info-label">Base / Stay</span>
    <span class="info-value">弘前公園附近 Airbnb / Local Studio</span>
    <p style="font-size: 12px; color: #666; margin-top: 10px;">
      選擇鄰近中央溫泉與星巴克古蹟店的區域，步行即可抵達每日習作地點。
    </p>
  </div>
  <div>
    <span class="info-label">Instructor</span>
    <span class="info-value">1-on-1 Private Tutor</span>
    <p style="font-size: 12px; color: #666; margin-top: 10px;">
      每週五天，每日 3 小時沈浸式對話習作。
    </p>
  </div>
</div>

<h2>Estimated Budget</h2>
<div class="budget-list">
  <div class="budget-row"><span>Accommodation (30 nights)</span><b>NT$ 32,000</b></div>
  <div class="budget-row"><span>Private Language Support</span><b>NT$ 18,500</b></div>
  <div class="budget-row"><span>Local Food & Onsen</span><b>NT$ 15,000</b></div>
  <div class="budget-row"><span>Transportation (JR & Bike)</span><b>NT$ 8,000</b></div>
  <div class="budget-row" style="border:none; margin-top: 10px; font-size: 16px;"><span>Total</span><b>NT$ 73,500</b></div>
</div>

---

<h2>Phase 01: Local Immersion</h2>
<div class="lifestyle-list">
  <div class="lifestyle-item"><b>Arrival</b> 抵達與安頓：租借單車、建立在地生活動線。</div>
  <div class="lifestyle-item"><b>Daily Ritual</b> 星巴克弘前公園前店：與老師見面、設定生活任務。</div>
  <div class="lifestyle-item"><b>Social</b> 體驗「中央溫泉」錢湯文化：觀察在地人的社交禮儀。</div>
</div>

<p class="footer">Captured by LAN • AOMORI Living Archive</p>
