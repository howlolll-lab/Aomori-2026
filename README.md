<style>
/* --- 極簡雜誌分頁系統 --- */
:root {
  --bg: #f7f3f0;
  --text: #2c2c2c;
  --accent: #b03a2e;
}

body {
  font-family: 'PingFang TC', 'MicroSoft JhengHei', serif;
  background-color: var(--bg);
  color: var(--text);
  margin: 0 auto;
  padding: 0;
  max-width: 800px;
  scroll-behavior: smooth;
}

/* 分頁模擬：每個 Section 強制留白 */
.page-section {
  min-height: 100vh;
  padding: 80px 20px;
  border-bottom: 1px solid #ddd;
}

/* 封面首頁 (圖三/五風格) */
.cover-hero {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.cover-image {
  width: 280px;
  height: 380px;
  background: #e0ddd5;
  margin: 30px 0;
  border: 1px solid #333;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 10px;
  color: #999;
}

/* 頂部導覽列 (圖八風格) */
.nav-bar {
  position: sticky;
  top: 0;
  background: rgba(247, 243, 240, 0.95);
  display: flex;
  justify-content: center;
  gap: 25px;
  padding: 20px;
  z-index: 100;
  border-bottom: 1px solid #333;
  font-family: 'Courier New', monospace;
  font-size: 12px;
}
.nav-bar a { text-decoration: none; color: #333; font-weight: bold; }

/* 日曆系統 (圖二風格) */
.calendar-grid {
  width: 100%;
  border-collapse: collapse;
  margin-top: 30px;
  background: #fff;
}
.calendar-grid th { padding: 10px; border: 1px solid #333; font-size: 10px; }
.calendar-grid td {
  border: 1px solid #333;
  width: 14.2%;
  height: 90px;
  vertical-align: top;
  padding: 5px;
  transition: 0.2s;
}
.calendar-grid td:hover { background: #fdfaf0; }
.day-num { font-family: 'Courier New', monospace; font-size: 11px; color: #999; }
.day-link { display: block; font-size: 10px; text-decoration: none; color: #333; margin-top: 5px; line-height: 1.3; }

/* 住宿與老師卡片 */
.info-card { border: 1px solid #333; padding: 25px; margin: 20px 0; position: relative; background: #fff; }
.info-card::after { content: ''; position: absolute; bottom: -5px; right: -5px; width: 100%; height: 100%; border: 1px solid #333; z-index: -1; }

.back-home { display: block; margin-top: 50px; font-size: 10px; color: #aaa; text-align: center; text-decoration: none; }
</style>

<div class="page-section cover-hero" id="home">
  <div style="letter-spacing: 0.5em; font-size: 12px;">MARCH 2026</div>
  <h1 style="font-size: 40px; font-weight: 200; letter-spacing: 0.3em;">AOMORI</h1>
  <div class="cover-image">
    <img src="https://via.placeholder.com/280x380.png?text=Main+Cover+Photo" style="width:100%; height:100%; object-fit:cover;">
  </div>
  <p style="font-family: serif; italic; opacity: 0.6;">30 Days Lifestyle Archive</p>
  <p style="margin-top: 20px; font-size: 12px;">↓ SCROLL OR USE MENU</p>
</div>

<div class="nav-bar">
  <a href="#base">BASE</a>
  <a href="#tutor">TUTOR</a>
  <a href="#schedule">SCHEDULE</a>
  <a href="#budget">BUDGET</a>
</div>

<div class="page-section" id="base">
  <h2 style="text-align: center; letter-spacing: 0.4em;">STAY & BASE</h2>
  <div class="info-card">
    <b>Aomori Shinmachi Central Base</b><br>
    📍 <a href="https://maps.app.goo.gl/xxx">青森市新町 1-XX-XX</a><br>
    🏠 類型：在地寓所 (Airbnb)<br>
    💡 備註：鄰近 A-Factory 與 Auga 市場，生活動線極佳。
  </div>
  <a href="#home" class="back-home">↑ RETURN TO COVER</a>
</div>

<div class="page-section" id="tutor">
  <h2 style="text-align: center; letter-spacing: 0.4em;">PRIVATE MENTOR</h2>
  <div class="info-card">
    <b>Sato-san (Language Counselor)</b><br>
    📍 會面地點：<a href="https://maps.app.goo.gl/xxx">Starbucks Aomori Shinmachi</a><br>
    💬 習作重點：沈浸式對話、津輕方言入門、日常場景練習。
  </div>
  <a href="#home" class="back-home">↑ RETURN TO COVER</a>
</div>

<div class="page-section" id="schedule">
  <h2 style="text-align: center; letter-spacing: 0.4em;">30-DAY CALENDAR</h2>
  <table class="calendar-grid">
    <tr><th>SUN</th><th>MON</th><th>TUE</th><th>WED</th><th>THU</th><th>FRI</th><th>SAT</th></tr>
    <tr>
      <td><span class="day-num">01</span><a href="#d01" class="day-link">抵達/安頓</a></td>
      <td><span class="day-num">02</span><a href="#details" class="day-link">導師見面</a></td>
      <td><span class="day-num">03</span><a href="#details" class="day-link">新町散策</a></td>
      <td><span class="day-num">04</span><a href="#details" class="day-link">錢湯習作</a></td>
      <td><span class="day-num">05</span><a href="#details" class="day-link">市場對話</a></td>
      <td><span class="day-num">06</span><a href="#details" class="day-link">藝術探索</a></td>
      <td><span class="day-num">07</span><a href="#details" class="day-link">弘前遠征</a></td>
    </tr>
    <tr>
      <td><span class="day-num">08</span><a href="#details" class="day-link">自由計畫</a></td>
      <td><span class="day-num">09</span><a href="#details" class="day-link">超市挑戰</a></td>
      <td><span class="day-num">10</span><a href="#details" class="day-link">咖啡習作</a></td>
      <td><span class="day-num">11</span><a href="#details" class="day-link">刺繡課</a></td>
      <td><span class="day-num">12</span><a href="#details" class="day-link">圖書館</a></td>
      <td><span class="day-num">13</span><a href="#details" class="day-link">淺蟲溫泉</a></td>
      <td><span class="day-num">14</span><a href="#details" class="day-link">弘前 (泊)</a></td>
    </tr>
    </table>
  
  <div id="d01" style="margin-top: 60px;">
    <h3>Day 01 Detailed 行程詳情</h3>
    <p>抵達青森車站，辦理單車租借。下午前往 A-Factory 購買首日晚餐食材。確認錢湯「中央古川」營業時間。</p>
  </div>
  
  <a href="#home" class="back-home">↑ RETURN TO COVER</a>
</div>

<div class="page-section" id="budget">
  <h2 style="text-align: center; letter-spacing: 0.4em;">BUDGET</h2>
  <div style="background: #fff; padding: 25px; border: 1px solid #333;">
    <p>Stay: NT$ 32,000</p>
    <p>Tutor: NT$ 18,500</p>
    <p>Total: NT$ 73,500</p>
  </div>
  <a href="#home" class="back-home">↑ RETURN TO COVER</a>
</div>
