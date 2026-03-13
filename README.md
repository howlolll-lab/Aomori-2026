<style>
/* --- 獨立分頁 App 模擬系統 --- */
:root {
  --bg-color: #f0f0f0; /* 淺灰色背景 */
  --text-main: #2c2c2c;
  --accent: #0066cc; /* Aomori 藍 */
  --card-bg: #fff;
}

body {
  font-family: 'PingFang TC', 'MicroSoft JhengHei', 'SF Pro Display', sans-serif;
  background-color: var(--bg-color);
  color: var(--text-main);
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}

/* 獨立分頁設定：滿版高度且不互見 */
.app-page {
  min-height: 100vh;
  padding: 60px 20px 40px; /* 留出頂部選單空間 */
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  box-sizing: border-box;
  /* 加入極大垂直邊距，確保跳轉後上下皆空 */
  margin-bottom: 50vh; 
}

/* 頂部導覽列 (模擬圖四) */
.nav-bar {
  position: sticky;
  top: 0;
  background-color: rgba(240, 240, 240, 0.95); /* 淺灰半透明 */
  display: flex;
  justify-content: space-around;
  padding: 20px 0;
  border-bottom: 1px solid #ddd;
  font-family: 'Courier New', monospace;
  font-size: 11px;
  z-index: 999;
}
.nav-bar a { text-decoration: none; color: #888; }
.nav-bar a:hover { color: var(--accent); }

/* --- 日曆頁面風格 (模仿圖六) --- */
.calendar-zine-grid {
  display: grid;
  grid-template-columns: repeat(7, 1fr);
  gap: 15px; /* 留白 */
  margin: 40px 0;
}

.zine-day-card {
  aspect-ratio: 1/1; /* 正方形小圖 */
  border: 1px solid #333;
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 5px;
  transition: 0.3s;
  background: #fff; /* 預設白色小塊 */
}

.zine-day-card:hover {
  transform: scale(1.05);
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.day-num {
  font-family: 'Courier New', monospace;
  font-size: 10px;
  background: #333;
  color: #fff;
  padding: 1px 4px;
  position: absolute;
  top: 0; left: 0;
}

/* 藝術網格連結：隱形但點得到 */
.zine-link {
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  opacity: 0;
  z-index: 10;
}

/* 頁面標題 */
h2 {
  font-size: 13px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.3em;
  color: var(--text-main);
  text-align: center;
  margin-bottom: 40px;
  font-family: 'Courier New', monospace;
}

/* --- 手機適應性 --- */
@media (max-width: 600px) {
  .calendar-zine-grid { grid-template-columns: repeat(4, 1fr); gap: 10px; }
  .nav-bar { font-size: 10px; }
}
</style>

<div class="nav-bar">
  <a href="#home">AOMORI 2026</a>
  <a href="#base">BASE</a>
  <a href="#tutor">TUTOR</a>
  <a href="#calendar">SCHEDULE</a>
  <a href="#budget">BUDGET</a>
</div>

<div class="app-page cover-section" id="home">
  <div style="text-align:center; padding-top:20vh;">
    <h1 style="font-size: 32px; font-weight: 200; letter-spacing: 0.3em; color: var(--accent);">AOMORI-2026</h1>
    <p style="font-size: 12px; color: #888;">Living Archive</p>
    <p style="margin-top: 40px; font-size: 10px;">↓ 點擊下方 SCHEDULE 開始旅程 ↓</p>
  </div>
</div>

<div class="app-page" id="base">
  <h2>BASE & STAY</h2>
  <div style="background: #fff; border: 1px solid #333; padding: 25px;">
    <b>青森站周邊在地公寓 (Airbnb)</b><br>
    📍 地址：<a href="#">青森市新町 1-XX-XX</a><br>
    🏠 類型：Local Studio<br>
    💡 備註：鄰近市場與 A-Factory，步行 5 分鐘可達。
  </div>
</div>

<div class="app-page" id="tutor">
  <h2>PRIVATE MENTOR</h2>
  <div style="background: #fff; border: 1px solid #333; padding: 25px;">
    <b>Sato-san (Language Counselor)</b><br>
    📍 會面地點：<a href="#">Starbucks Aomori Shinmachi</a><br>
    💬 習作重點：沈浸式對話、津輕方言、在地人脈連結習作。
  </div>
</div>

<div class="app-page" id="calendar">
  <h2>30-Day Calendar Schedule</h2>
  
  <p style="font-size: 10px; text-align: center; color: #999; margin-top: -20px;">MARCH / 2026</p>

  <div class="calendar-zine-grid">
    <div class="zine-day-card">
      <span class="day-num">01</span>
      抵達青森<br>環境安頓
    </div>
    <div class="zine-day-card">
      <span class="day-num">02</span>
      市場對話<br>導師面談
    </div>
    <div class="zine-day-card">
      <span class="day-num">03</span>
      習作：<br>新町散策
    </div>
    <div class="zine-day-card">
      <span class="day-num">04</span>
      錢湯習作
    </div>
    <div class="zine-day-card">
      <span class="day-num">05</span>
      語言課 01
    </div>
    <div class="zine-day-card">
      <span class="day-num">06</span>
      圖書館<br>習作
    </div>
    <div class="zine-day-card">
      <span class="day-num">07</span>
      弘前遠征
    </div>
    </div>
  
  <p style="font-size: 10px; color: #aaa; text-align: center; margin-top: 40px;">*每一格小圖網格皆為獨立行程任務。</p>
</div>

<div class="app-page" id="budget">
  <h2>FINANCIAL PLAN</h2>
  <div style="background: #fff; border: 1px dashed #333; padding: 25px; text-align: center; font-family: 'Courier New', monospace; font-size: 13px;">
    Stay: NT$ 32,000 / Tutor: NT$ 18,500<br>
    Total: NT$ 73,500
  </div>
</div>
