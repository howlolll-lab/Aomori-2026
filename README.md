<style>
/* --- 全域響應式與雜誌風格設定 --- */
:root {
  --text-main: #2c2c2c;
  --text-mute: #8e8e8e;
  --bg-color: #f9f7f2; 
  --accent: #b03a2e;
}

body {
  font-family: 'PingFang TC', 'MicroSoft JhengHei', 'Georgia', serif;
  background-color: var(--bg-color);
  color: var(--text-main);
  margin: 0 auto;
  line-height: 1.9;
  letter-spacing: 0.05em;
  padding: 20px;
}

/* 電腦版限制寬度，手機版自動滿版 */
@media (min-width: 768px) {
  body { max-width: 700px; padding: 60px 0; }
  .photo-grid { grid-template-columns: 1fr 1fr 1fr; }
}

@media (max-width: 767px) {
  body { padding: 30px 15px; }
  .photo-grid { grid-template-columns: 1fr 1fr; }
  h1 { font-size: 20px; }
}

.journal-header {
  font-family: 'Helvetica', sans-serif;
  font-size: 10px;
  text-transform: uppercase;
  color: var(--text-mute);
  display: flex;
  justify-content: space-between;
  margin-bottom: 40px;
  border-bottom: 1px solid #e0ddd5;
  padding-bottom: 10px;
}

h1 {
  text-align: center;
  font-weight: 300;
  margin: 40px 0;
  letter-spacing: 0.2em;
  line-height: 1.4;
}

h2 {
  font-size: 13px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.2em;
  margin-top: 60px;
  margin-bottom: 30px;
  color: var(--text-mute);
  text-align: center;
  border-top: 1px solid #e0ddd5;
  padding-top: 40px;
}

.itinerary-list { list-style: none; padding: 0; }

.itinerary-item {
  margin-bottom: 25px;
  font-size: 14px;
  display: flex;
  align-items: flex-start;
}

.day-index {
  font-family: 'Courier New', monospace;
  font-size: 11px;
  color: var(--text-mute);
  width: 50px;
  margin-top: 4px;
}

.task-content { flex: 1; }

.task-content b {
  color: var(--text-main);
  font-weight: 600;
  display: block;
  margin-bottom: 4px;
}

.photo-grid { display: grid; gap: 15px; margin: 40px 0; }
.photo-box {
  background: #eee;
  aspect-ratio: 1/1;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 10px;
  color: #aaa;
  border-radius: 2px;
  border: 1px solid #e0ddd5;
}

.footer {
  text-align: center;
  font-size: 10px;
  color: var(--text-mute);
  margin-top: 100px;
  text-transform: uppercase;
  padding-bottom: 50px;
}
</style>

<div class="journal-header">
  <span>Issue 01 / Aomori Journey</span>
  <span>LAN - 2026</span>
</div>

<h1>AOMORI LIFESTYLE JOURNEY<br><font size="3" color="#8e8e8e">30-Day Immersion Program</font></h1>

---

<h2>Phase 01: Local Immersion</h2>
<div class="itinerary-list">
  <div class="itinerary-item">
    <div class="day-index">D.01</div>
    <div class="task-content"><b>Arrival & Settling</b> 抵達弘前、Airbnb Check-in、單車租借。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.02</div>
    <div class="task-content"><b>Market Discovery</b> 虹之味市場實戰，練習詢問蘋果產地。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.03</div>
    <div class="task-content"><b>Coffee Session</b> 星巴克弘前公園前店，與語言顧問初面談。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.04</div>
    <div class="task-content"><b>Archive & Study</b> 走訪市立圖書館，查閱津輕刺繡（Kogin-zashi）歷史。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.05</div>
    <div class="task-content"><b>Bathhouse Ritual</b> 體驗在地「中央溫泉」錢湯，觀察澡堂社交。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">W.END</div>
    <div class="task-content"><b>City Wandering</b> 青森市區：睡魔之家 Wa Rasse、A-Factory 蘋果酒品飲。</div>
  </div>
</div>

<h2>Phase 02: Nature & Arts</h2>
<div class="itinerary-list">
  <div class="itinerary-item">
    <div class="day-index">D.08</div>
    <div class="task-content"><b>Creative Space</b> 在「大正浪漫喫茶室」進行寫作習作。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.12</div>
    <div class="task-content"><b>Culinary Task</b> 前往超市購買在地食材，挑戰製作簡單的津輕料理。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">W.END</div>
    <div class="task-content"><b>Mountain Retreat</b> 奧入瀨溪流與十和田湖，體驗「湯治」溫泉療癒。</div>
  </div>
</div>

<h2>Phase 03: Sea & Rail Journey</h2>
<div class="itinerary-list">
  <div class="itinerary-item">
    <div class="day-index">D.15</div>
    <div class="task-content"><b>Mastering Taste</b> 走訪「可否館」，練習用日文描述手沖咖啡風味。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.18</div>
    <div class="task-content"><b>Visual Art</b> 參觀青森縣立美術館，近距離感受 Nara Yoshitomo 藝術。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">W.END</div>
    <div class="task-content"><b>Coastal Route</b> 搭乘五能線 Resort 白神號，探索日本海沿岸村落。</div>
  </div>
</div>

<h2>Phase 04: Final Reflections</h2>
<div class="itinerary-list">
  <div class="itinerary-item">
    <div class="day-index">D.22</div>
    <div class="task-content"><b>Journaling</b> 整理 30 天的生活影像，撰寫日文生活札記。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.27</div>
    <div class="task-content"><b>Gratitude</b> 走訪在地小店選購伴手禮，練習書寫感謝信。</div>
  </div>
  <div class="itinerary-item">
    <div class="day-index">D.30</div>
    <div class="task-content"><b>Homebound</b> 帶著津輕回憶前往機場，Ending of the Journey.</div>
  </div>
</div>

---

<h2>Visual Notes</h2>
<div class="photo-grid">
  <div class="photo-box">Market Finds</div>
  <div class="photo-box">Cafe Workspace</div>
  <div class="photo-box">Onsen Vibes</div>
  <div class="photo-box">Railway View</div>
  <div class="photo-box">Apple Orchard</div>
  <div class="photo-box">Art Museum</div>
</div>

<p class="footer">Captured by LAN • 2026 Aomori Lifestyle Journey • Powered by GitHub</p>
