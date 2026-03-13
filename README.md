<style>
/* --- 極致藝術 Zine / 雜誌風格 --- */
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

.magazine-header {
  font-family: 'Courier New', monospace;
  font-size: 10px;
  display: flex;
  justify-content: space-between;
  border-bottom: 1px solid #333;
  padding-bottom: 5px;
  margin-bottom: 50px;
}

h1 { text-align: center; font-size: 24px; font-weight: 300; margin: 50px 0; letter-spacing: 0.3em; }
h2 { font-size: 14px; font-weight: 600; text-transform: uppercase; letter-spacing: 0.2em; margin-top: 60px; margin-bottom: 30px; text-align: center; border-bottom: 1px solid #ddd; padding-bottom: 10px; }

/* 住宿與老師：錯落網格設計 */
.zine-grid { 
  display: grid; 
  grid-template-columns: 1fr 1fr; 
  gap: 30px; 
  margin: 40px 0; 
}

.zine-card {
  border: 1px solid #333;
  padding: 20px;
  position: relative;
  background: rgba(255,255,255,0.3);
}

.zine-card::after {
  content: '';
  position: absolute;
  bottom: -5px;
  right: -5px;
  width: 100%;
  height: 100%;
  border: 1px solid #333;
  z-index: -1;
}

.card-label {
  font-family: 'Courier New', monospace;
  font-size: 10px;
  background: #333;
  color: #fff;
  padding: 2px 8px;
  position: absolute;
  top: -10px;
  left: 10px;
}

.card-title { font-size: 16px; font-weight: 600; display: block; margin-bottom: 10px; }
.card-desc { font-size: 12px; color: #555; line-height: 1.6; }

/* 列表樣式 */
.lifestyle-list { list-style: none; padding: 0; }
.lifestyle-item { margin-bottom: 25px; font-size: 14px; display: flex; align-items: flex-start; }
.day-tag { font-family: 'Courier New', monospace; font-size: 11px; color: var(--accent); width: 50px; flex-shrink: 0; margin-top: 4px; font-weight: bold; }
.content-box b { color: #000; display: block; margin-bottom: 2px; }

/* 費用清單 */
.budget-box {
  margin: 40px 0;
  padding: 25px;
  background: #fff;
  border: 1px dashed #333;
}
.budget-row { display: flex; justify-content: space-between; font-size: 12px; padding: 10px 0; border-bottom: 1px solid #eee; }

.footer { text-align: center; font-size: 10px; margin-top: 100px; color: #999; letter-spacing: 0.2em; padding-bottom: 40px; }

@media (max-width: 600px) {
  .zine-grid { grid-template-columns: 1fr; gap: 40px; }
}
</style>

<div class="magazine-header">
  <span>HIROSAKI LIFE JOURNAL / 2026</span>
  <span>LAN - ARCHIVE</span>
</div>

<h1>LIFESTYLE JOURNEY</h1>

<div class="zine-grid">
  <div class="zine-card">
    <span class="card-label">BASE</span>
    <span class="card-title">Stay & Base</span>
    <div class="card-desc">
      <b>Hirosaki Central Studio</b><br>
      位於弘前公園周邊，選定具備廚房與腳踏車停放空間的在地寓所。
      <br><i>(Walking distance to Chuo Onsen and Starbucks.)</i>
    </div>
  </div>
  
  <div class="zine-card">
    <span class="card-label">LEARN</span>
    <span class="card-title">Private Tutor</span>
    <div class="card-desc">
      <b>1-on-1 Immersion</b><br>
      私人語言顧問。每日 3 小時對話習作，專注於「生活化津輕日語」與在地文化連結。
      <br><i>(Sessions held in historic local cafes.)</i>
    </div>
  </div>
</div>

---

<h2>Phase 01: Local Immersion</h2>
<div class="lifestyle-list">
  <div class="lifestyle-item">
    <div class="day-tag">D.01</div>
    <div class="content-box"><b>Arrival & Setup</b> 抵達弘前、辦理單車租借、超市採買首週物資。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.02</div>
    <div class="content-box"><b>Market Practice</b> 虹之味市場實戰：詢問今日最推薦的蘋果，練習價格交涉。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.03</div>
    <div class="content-box"><b>Orientation</b> 星巴克弘前公園前店：與導師會面，設定為期 30 天的生活目標。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.05</div>
    <div class="content-box"><b>Bathhouse Social</b> 體驗「中央溫泉」錢湯，觀察澡堂社交禮儀。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.07</div>
    <div class="content-box"><b>Weekly Review</b> 整理首週紀錄，在弘前煉瓦倉庫美術館進行冥想。</div>
  </div>
</div>

<h2>Phase 02: Nature & Arts</h2>
<div class="lifestyle-list">
  <div class="lifestyle-item">
    <div class="day-tag">D.10</div>
    <div class="content-box"><b>Culinary Task</b> 挑戰製作「貝燒味噌」或「菊之物」，記錄在地食譜。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.12</div>
    <div class="content-box"><b>Kogin-zashi</b> 參與津輕刺繡體驗課，認識傳統工藝。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.14</div>
    <div class="content-box"><b>Lake Retreat</b> 十和田湖與奧入瀨溪流 2D1N：觀察自然色彩對藝術的影響。</div>
  </div>
</div>

<h2>Phase 03: Connections</h2>
<div class="lifestyle-list">
  <div class="lifestyle-item">
    <div class="day-tag">D.18</div>
    <div class="content-box"><b>Coffee Dialect</b> 走訪「可否館」，與老闆練習用津輕方言聊天。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.21</div>
    <div class="content-box"><b>Museum Day</b> 青森縣立美術館：探索奈良美智藝術作品。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.24</div>
    <div class="content-box"><b>Railway Trip</b> 搭乘五能線，體驗日本海沿岸的鐵道慢生活。</div>
  </div>
</div>

<h2>Phase 04: Final Reflections</h2>
<div class="lifestyle-list">
  <div class="lifestyle-item">
    <div class="day-tag">D.27</div>
    <div class="content-box"><b>Souvenir Hunt</b> A-Factory 選購在地農產，撰寫給導師與鄰居的感謝信。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.29</div>
    <div class="content-box"><b>Archive Prep</b> 整理 30 天的影像與筆記，製作成數位回憶錄。</div>
  </div>
  <div class="lifestyle-item">
    <div class="day-tag">D.30</div>
    <div class="content-box"><b>Farewell</b> 帶著津輕的空氣回程。End of Journey.</div>
  </div>
</div>

---

<h2>Projected Expenses / 預算</h2>
<div class="budget-box">
  <div class="budget-row"><span>Stay (30 Nights) / 住宿總額</span><b>NT$ 32,000</b></div>
  <div class="budget-row"><span>Private Tutor / 導師費用</span><b>NT$ 18,500</b></div>
  <div class="budget-row"><span>Daily Life / 在地生活開銷</span><b>NT$ 15,000</b></div>
  <div class="budget-row"><span>Transportation / 交通工具</span><b>NT$ 8,000</b></div>
  <div class="budget-row" style="border:none; margin-top: 15px; font-size: 15px; font-weight: bold;"><span>Est. Total / 預計總計</span><b>NT$ 73,500</b></div>
</div>

<p class="footer">CAPTURED BY LAN • AOMORI LIFESTYLE PROJECT • 2026</p>
