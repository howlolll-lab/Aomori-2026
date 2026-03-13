<style>
/* --- 極簡雜誌風：米白紙質色調 --- */
:root {
  --text-main: #2c2c2c;
  --text-mute: #8e8e8e;
  --bg-color: #f9f7f2; /* 類似 image_8.png 的溫潤紙色 */
  --accent: #b03a2e;
}

body {
  font-family: 'PingFang TC', 'MicroSoft JhengHei', 'Georgia', serif;
  background-color: var(--bg-color);
  color: var(--text-main);
  max-width: 600px;
  margin: 0 auto;
  padding: 50px 25px;
  line-height: 1.9;
  letter-spacing: 0.05em;
}

/* 頂部頁碼感排版 */
.journal-header {
  font-family: 'Helvetica', sans-serif;
  font-size: 10px;
  text-transform: uppercase;
  color: var(--text-mute);
  display: flex;
  justify-content: space-between;
  margin-bottom: 60px;
  border-bottom: 1px solid #e0ddd5;
  padding-bottom: 10px;
}

h1 {
  text-align: center;
  font-size: 24px;
  font-weight: 300;
  margin: 40px 0;
  letter-spacing: 0.2em;
}

h2 {
  font-size: 13px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.2em;
  margin-top: 50px;
  margin-bottom: 25px;
  color: var(--text-mute);
  text-align: center;
}

.itinerary-list {
  list-style: none;
  padding: 0;
}

.itinerary-item {
  margin-bottom: 20px;
  font-size: 14px;
  display: flex;
  align-items: flex-start;
}

.day-index {
  font-family: 'Courier New', monospace;
  font-size: 11px;
  color: var(--text-mute);
  width: 40px;
  margin-top: 4px;
}

.task-content {
  flex: 1;
}

.task-content b {
  color: var(--text-main);
  font-weight: 600;
  display: block;
  margin-bottom: 2px;
}

a {
  color: var(--accent);
  text-decoration: none;
  border-bottom: 1px solid #ddd;
}

/* 圖片佔位符樣式 */
.photo-grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 15px;
  margin: 40px 0;
}

.photo-box {
  background: #eee;
  aspect-ratio: 1/1;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 10px;
  color: #aaa;
  border-radius: 2px;
}

.footer {
  text-align: center;
  font-size: 10px;
  color: var(--text-mute);
  margin-top: 100px;
  text-transform: uppercase;
}
</style>

<div class="journal-header">
  <span>Issue 01 / Aomori</span>
  <span>LAN - 2026</span>
</div>

<h1>AOMORI LIFESTYLE JOURNEY</h1>

---

<h2>Phase 01: Local Immersion</h2>

<div class="itinerary-list">
  <div class="itinerary-item">
    <div class="day-index">D.01</div>
    <div class="task-content"><b>抵達弘前與安頓</b> 入住 Airbnb、辦理單車租借。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.02</div>
    <div class="task-content"><b>虹之味市場實戰</b> 向攤販詢問季節性蘋果品種。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.03</div>
    <div class="task-content"><b>咖啡廳習作</b> 在 <a href="#">星巴克弘前公園前店</a> 與老師見面。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.04</div>
    <div class="task-content"><b>文化閱讀</b> 走訪市立圖書館，查閱津輕歷史。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.05</div>
    <div class="task-content"><b>庶民錢湯體驗</b> 走訪「中央溫泉」感受在地社交。</div>
  </div>
</div>

---

<h2>Visual Notes</h2>

<div class="photo-grid">
  <div class="photo-box">Photo Here</div>
  <div class="photo-box">Photo Here</div>
  <div class="photo-box">Photo Here</div>
</div>

<p class="footer">Captured by LAN • Living in Hirosaki • Powered by GitHub Pages</p>
