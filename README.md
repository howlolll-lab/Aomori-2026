<style>
/* --- 雜誌首頁風格與日曆導覽系統 --- */
:root {
  --bg-color: #f7f3f0;
  --text-main: #2c2c2c;
  --accent: #b03a2e;
  --line: #333333;
}

body {
  font-family: 'PingFang TC', 'MicroSoft JhengHei', serif;
  background-color: var(--bg-color);
  color: var(--text-main);
  margin: 0 auto;
  padding: 40px 20px;
  max-width: 800px;
}

/* 封面大圖風格 (模擬圖三) */
.cover-container {
  text-align: center;
  padding: 100px 0;
  border: 1px solid var(--line);
  margin-bottom: 60px;
  position: relative;
}
.cover-title {
  font-size: 42px;
  letter-spacing: 0.4em;
  font-weight: 200;
  margin: 20px 0;
}
.cover-subtitle {
  font-size: 12px;
  letter-spacing: 0.2em;
  color: #888;
  text-transform: uppercase;
}

/* 模擬圖八的分頁目錄 */
.nav-menu {
  display: flex;
  justify-content: center;
  gap: 30px;
  border-top: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
  padding: 15px 0;
  margin-bottom: 60px;
  font-family: 'Courier New', monospace;
  font-size: 13px;
}
.nav-menu a { text-decoration: none; color: var(--text-main); font-weight: bold; }

/* 日曆表格 (模擬圖二) */
.calendar-table {
  width: 100%;
  border-collapse: collapse;
  margin-bottom: 80px;
  background: #fff;
}
.calendar-table th {
  padding: 10px;
  border: 1px solid #ddd;
  font-size: 10px;
  text-transform: uppercase;
  background: #fdfdfd;
}
.calendar-table td {
  border: 1px solid #ddd;
  width: 14.2%;
  height: 100px;
  vertical-align: top;
  padding: 8px;
  position: relative;
  transition: 0.2s;
}
.calendar-table td:hover { background: #f9f7f2; }
.day-label { font-family: 'Courier New', monospace; font-size: 12px; color: #aaa; }
.event-link {
  display: block;
  font-size: 11px;
  color: var(--text-main);
  text-decoration: none;
  margin-top: 10px;
  line-height: 1.4;
}
.event-link:hover { color: var(--accent); }

/* 詳細內容區塊 */
.detail-section {
  padding: 60px 0;
  border-top: 1px solid #eee;
}
.back-to-top { font-size: 10px; color: #ccc; text-decoration: none; float: right; }

@media (max-width: 600px) {
  .calendar-table td { height: 70px; font-size: 9px; }
  .cover-title { font-size: 28px; }
}
</style>

<div class="cover-container" id="home">
  <div class="cover-subtitle">Issue 01 / Aomori Archive</div>
  <h1 class="cover-title">Aomori-2026</h1>
  <div style="width: 200px; height: 260px; background: #eee; margin: 40px auto; display: flex; align-items: center; justify-content: center; color: #aaa; font-size: 10px;">
    MAIN COVER IMAGE<br>(Place your photo here)
  </div>
  <div class="cover-subtitle">30 Days of Living in Tsugaru</div>
</div>

<div class="nav-menu">
  <a href="#base">BASE / 住宿</a>
  <a href="#tutor">TUTOR / 導師</a>
  <a href="#calendar">SCHEDULE / 行程</a>
  <a href="#budget">BUDGET / 預算</a>
</div>

---

<h2 id="calendar" style="text-align: center; letter-spacing: 0.3em;">MARCH CALENDAR</h2>

<table class="calendar-table">
  <thead>
    <tr><th>Sun</th><th>Mon</th><th>Tue</th><th>Wed</th><th>Thu</th><th>Fri</th><th>Sat</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><span class="day-label">01</span><a href="#day01" class="event-link">抵達青森<br>環境安頓</a></td>
      <td><span class="day-label">02</span><a href="#day02" class="event-link">市場實戰<br>導師見面</a></td>
      <td><span class="day-label">03</span><a href="#day03" class="event-link">習作：<br>新町散策</a></td>
      <td><span class="day-label">04</span><a href="#day04" class="event-link">錢湯文化<br>練習</a></td>
      <td><span class="day-label">05</span><a href="#day05" class="event-link">語言課 01<br>日常對話</a></td>
      <td><span class="day-label">06</span><a href="#day06" class="event-link">圖書館<br>文獻查閱</a></td>
      <td><span class="day-label">07</span><a href="#day07" class="event-link">弘前單日<br>探訪</a></td>
    </tr>
    <tr>
      <td><span class="day-label">08</span><a href="#day08" class="event-link">藝術感：<br>縣立美術館</a></td>
      <td><span class="day-label">09</span><a href="#day09" class="event-link">超市挑戰<br>食材辨識</a></td>
      <td><span class="day-label">10</span><a href="#day10" class="event-link">語言課 02<br>料理用語</a></td>
      <td><span class="day-label">11</span><a href="#day11" class="event-link">咖啡館習作<br>可否館</a></td>
      <td><span class="day-label">12</span><a href="#day12" class="event-link">自由日<br>海邊冥想</a></td>
      <td><span class="day-label">13</span><a href="#day13" class="event-link">淺蟲溫泉<br>外地練習</a></td>
      <td><span class="day-label">14</span><a href="#day14" class="event-link">弘前二日<br>(Stay)</a></td>
    </tr>
    </tbody>
</table>

---

<h2 id="base" style="text-align: center;">Base & Stay / 住宿詳細</h2>
<div style="border: 1px solid #333; padding: 30px; margin: 20px 0;">
  <b>Aomori Shinmachi Apartment</b><br>
  📍 地址：<a href="#">青森市新町 1-XX-XX</a><br>
  🔗 連結：<a href="#">Airbnb 預約頁面</a><br>
  💡 備註：鄰近 A-Factory，步行 5 分鐘可達青森車站。
</div>

<h2 id="tutor" style="text-align: center;">Private Tutor / 私人導師</h2>
<div style="border: 1px solid #333; padding: 30px; margin: 20px 0;">
  <b>Sato-san (Language Mentor)</b><br>
  📍 地點：<a href="#">Starbucks Aomori Shinmachi</a><br>
  💬 方式：1-on-1沈浸式對談 (每週一至五 10:00-13:00)
</div>

---

<h2 style="text-align: center;">Daily Detailed / 詳細行程內容</h2>

<div class="detail-section" id="day01">
  <a href="#home" class="back-to-top">↑ BACK TO COVER</a>
  <h3>Day 01: Arrival & Connection</h3>
  <p>抵達青森車站後，先行前往新町公寓 Check-in。下午租借腳踏車，確認住家周圍的超市、錢湯位置。晚上與導師進行線上確認。</p>
</div>

<div class="detail-section" id="day02">
  <a href="#home" class="back-to-top">↑ BACK TO COVER</a>
  <h3>Day 02: Market & First Session</h3>
  <p>早晨前往 Auga 鮮魚市場練習詢問今日鮮魚種類。10:00 於星巴克與佐藤導師進行第一次實體習作，設定首週詞彙清單。</p>
</div>

<p style="text-align: center; font-size: 10px; color: #999; margin-top: 100px;">
  PRIVATE ARCHIVE • LAN AOMORI 2026 • POWERED BY GITHUB & VERCEL
</p>
