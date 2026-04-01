<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Whitten Family Command Center</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  :root {
    --bg: #0a0e1a;
    --panel: #111827;
    --border: #1f2937;
    --text: #f1f5f9;
    --muted: #94a3b8;
    --nick: #3b82f6;
    --sarah: #ec4899;
    --alyssa: #a855f7;
    --zach: #22c55e;
    --zoey: #f59e0b;
    --aryan: #ef4444;
    --mystical: #06b6d4;
    --alex: #6366f1;
    --family: #ffffff;
  }
  body { background: var(--bg); color: var(--text); font-family: 'Segoe UI', sans-serif; height: 100vh; overflow: hidden; display: flex; flex-direction: column; }

  /* HEADER */
  header { display: flex; align-items: center; justify-content: space-between; padding: 10px 20px; background: var(--panel); border-bottom: 1px solid var(--border); flex-shrink: 0; }
  .logo { font-size: 1.3rem; font-weight: 700; color: var(--text); }
  .logo span { color: var(--nick); }
  .clock-weather { display: flex; align-items: center; gap: 20px; }
  #clock { font-size: 2rem; font-weight: 700; letter-spacing: 2px; }
  #date-display { font-size: 0.85rem; color: var(--muted); }
  #weather-widget { text-align: right; }
  #weather-temp { font-size: 1.4rem; font-weight: 700; }
  #weather-desc { font-size: 0.75rem; color: var(--muted); }

  /* MAIN LAYOUT */
  .main { display: grid; grid-template-columns: 280px 1fr 280px; gap: 10px; padding: 10px; flex: 1; overflow: hidden; }

  /* PANELS */
  .panel { background: var(--panel); border: 1px solid var(--border); border-radius: 12px; overflow: hidden; display: flex; flex-direction: column; }
  .panel-header { padding: 10px 14px; font-size: 0.8rem; font-weight: 600; text-transform: uppercase; letter-spacing: 1px; color: var(--muted); border-bottom: 1px solid var(--border); display: flex; justify-content: space-between; align-items: center; flex-shrink: 0; }
  .panel-body { padding: 10px; overflow-y: auto; flex: 1; }

  /* CALENDAR */
  .cal-nav { display: flex; align-items: center; justify-content: space-between; margin-bottom: 8px; }
  .cal-nav button { background: var(--border); border: none; color: var(--text); padding: 4px 10px; border-radius: 6px; cursor: pointer; font-size: 0.85rem; }
  .cal-nav button:hover { background: #374151; }
  .cal-title { font-size: 1rem; font-weight: 700; }
  .cal-grid { display: grid; grid-template-columns: repeat(7, 1fr); gap: 2px; }
  .cal-day-label { text-align: center; font-size: 0.65rem; color: var(--muted); padding: 4px 0; font-weight: 600; }
  .cal-cell { min-height: 72px; padding: 3px; border-radius: 6px; border: 1px solid transparent; cursor: pointer; transition: background 0.15s; position: relative; }
  .cal-cell:hover { background: #1f2937; }
  .cal-cell.today { border-color: var(--nick); background: rgba(59,130,246,0.08); }
  .cal-cell.other-month { opacity: 0.35; }
  .cal-num { font-size: 0.7rem; font-weight: 600; color: var(--muted); margin-bottom: 2px; }
  .cal-cell.today .cal-num { color: var(--nick); background: var(--nick); color: white; width: 18px; height: 18px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 0.65rem; }
  .cal-event { font-size: 0.55rem; padding: 1px 3px; border-radius: 3px; margin-bottom: 1px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; font-weight: 500; }

  /* UPCOMING */
  .upcoming-item { padding: 8px; border-radius: 8px; margin-bottom: 6px; border-left: 3px solid var(--nick); background: rgba(255,255,255,0.03); }
  .upcoming-date { font-size: 0.65rem; color: var(--muted); }
  .upcoming-title { font-size: 0.82rem; font-weight: 600; }
  .upcoming-time { font-size: 0.65rem; color: var(--muted); }

  /* CHORES */
  .member-section { margin-bottom: 10px; }
  .member-name { font-size: 0.75rem; font-weight: 700; padding: 3px 8px; border-radius: 20px; display: inline-block; margin-bottom: 5px; color: white; }
  .chore-item { display: flex; align-items: center; gap: 8px; padding: 5px 6px; border-radius: 6px; margin-bottom: 3px; background: rgba(255,255,255,0.03); }
  .chore-item.done { opacity: 0.45; }
  .chore-item.done .chore-text { text-decoration: line-through; }
  .chore-cb { width: 15px; height: 15px; cursor: pointer; accent-color: var(--nick); flex-shrink: 0; }
  .chore-text { font-size: 0.78rem; flex: 1; }
  .chore-del { background: none; border: none; color: #ef4444; cursor: pointer; font-size: 0.8rem; padding: 0 2px; }
  .add-chore { display: flex; gap: 4px; margin-top: 6px; }
  .add-chore input { flex: 1; background: var(--bg); border: 1px solid var(--border); color: var(--text); padding: 4px 8px; border-radius: 6px; font-size: 0.75rem; }
  .add-chore select { background: var(--bg); border: 1px solid var(--border); color: var(--text); padding: 4px 6px; border-radius: 6px; font-size: 0.75rem; }
  .add-chore button { background: var(--nick); border: none; color: white; padding: 4px 10px; border-radius: 6px; cursor: pointer; font-size: 0.75rem; }

  /* SHOPPING */
  .shop-item { display: flex; align-items: center; gap: 8px; padding: 5px 6px; border-radius: 6px; margin-bottom: 3px; background: rgba(255,255,255,0.03); }
  .shop-item.done { opacity: 0.45; }
  .shop-item.done span { text-decoration: line-through; }
  .shop-text { font-size: 0.78rem; flex: 1; }
  .add-shop { display: flex; gap: 4px; margin-top: 6px; }
  .add-shop input { flex: 1; background: var(--bg); border: 1px solid var(--border); color: var(--text); padding: 4px 8px; border-radius: 6px; font-size: 0.75rem; }
  .add-shop button { background: var(--zoey); border: none; color: white; padding: 4px 10px; border-radius: 6px; cursor: pointer; font-size: 0.75rem; }

  /* AI ASSISTANT */
  .ai-bar { padding: 8px 10px; border-top: 1px solid var(--border); background: var(--panel); flex-shrink: 0; }
  .ai-messages { height: 120px; overflow-y: auto; padding: 6px; background: var(--bg); border-radius: 8px; margin-bottom: 6px; }
  .ai-msg { margin-bottom: 6px; font-size: 0.78rem; line-height: 1.4; }
  .ai-msg.user { color: var(--nick); }
  .ai-msg.user::before { content: "Nick: "; font-weight: 700; }
  .ai-msg.assistant { color: var(--text); }
  .ai-msg.assistant::before { content: "🤖 "; }
  .ai-input-row { display: flex; gap: 6px; }
  .ai-input-row input { flex: 1; background: var(--border); border: none; color: var(--text); padding: 8px 12px; border-radius: 8px; font-size: 0.82rem; }
  .ai-input-row input::placeholder { color: var(--muted); }
  .ai-input-row button { background: var(--nick); border: none; color: white; padding: 8px 16px; border-radius: 8px; cursor: pointer; font-weight: 600; font-size: 0.82rem; }
  .ai-input-row button:disabled { opacity: 0.5; cursor: not-allowed; }

  /* LEGEND */
  .legend { display: flex; flex-wrap: wrap; gap: 6px; padding: 6px 10px; border-top: 1px solid var(--border); flex-shrink: 0; }
  .legend-item { display: flex; align-items: center; gap: 4px; font-size: 0.65rem; color: var(--muted); }
  .legend-dot { width: 8px; height: 8px; border-radius: 50%; }

  /* ADD EVENT MODAL */
  .modal-overlay { position: fixed; inset: 0; background: rgba(0,0,0,0.7); z-index: 100; display: none; align-items: center; justify-content: center; }
  .modal-overlay.open { display: flex; }
  .modal { background: var(--panel); border: 1px solid var(--border); border-radius: 16px; padding: 20px; width: 360px; }
  .modal h3 { margin-bottom: 14px; font-size: 1rem; }
  .modal input, .modal select { width: 100%; background: var(--bg); border: 1px solid var(--border); color: var(--text); padding: 8px 10px; border-radius: 8px; font-size: 0.82rem; margin-bottom: 8px; }
  .modal-btns { display: flex; gap: 8px; margin-top: 4px; }
  .modal-btns button { flex: 1; padding: 8px; border-radius: 8px; border: none; cursor: pointer; font-weight: 600; font-size: 0.82rem; }
  .btn-save { background: var(--nick); color: white; }
  .btn-cancel { background: var(--border); color: var(--text); }

  .right-col { display: flex; flex-direction: column; gap: 10px; overflow: hidden; }
  .panel.chores { flex: 1; min-height: 0; }
  .panel.shopping { flex-shrink: 0; max-height: 220px; }

  ::-webkit-scrollbar { width: 4px; }
  ::-webkit-scrollbar-track { background: transparent; }
  ::-webkit-scrollbar-thumb { background: var(--border); border-radius: 2px; }
</style>
</head>
<body>

<!-- HEADER -->
<header>
  <div>
    <div class="logo">Whitten <span>Command Center</span></div>
    <div id="date-display"></div>
  </div>
  <div class="clock-weather">
    <div id="clock">00:00:00</div>
    <div id="weather-widget">
      <div id="weather-temp">--°F</div>
      <div id="weather-desc">Loading weather...</div>
    </div>
  </div>
</header>

<!-- MAIN -->
<div class="main">

  <!-- LEFT: UPCOMING + LEGEND -->
  <div class="panel">
    <div class="panel-header">📅 Upcoming Events</div>
    <div class="panel-body" id="upcoming-list"><div style="color:var(--muted);font-size:0.8rem;">Loading calendar...</div></div>
    <div class="legend" id="legend"></div>
  </div>

  <!-- CENTER: CALENDAR -->
  <div class="panel">
    <div class="panel-header">
      <span>Family Calendar</span>
      <button onclick="openAddEvent()" style="background:var(--nick);border:none;color:white;padding:3px 10px;border-radius:6px;cursor:pointer;font-size:0.75rem;">+ Add Event</button>
    </div>
    <div class="panel-body">
      <div class="cal-nav">
        <button onclick="changeMonth(-1)">◀</button>
        <div class="cal-title" id="cal-title"></div>
        <button onclick="changeMonth(1)">▶</button>
      </div>
      <div class="cal-grid" id="cal-grid"></div>
    </div>
  </div>

  <!-- RIGHT: CHORES + SHOPPING -->
  <div class="right-col">
    <div class="panel chores">
      <div class="panel-header">✅ Chores & Tasks</div>
      <div class="panel-body" id="chores-panel">
        <div class="add-chore">
          <input id="chore-input" placeholder="New chore..." />
          <select id="chore-member">
            <option value="Nick">Nick</option>
            <option value="Sarah">Sarah</option>
            <option value="Alyssa">Alyssa</option>
            <option value="Zach">Zach</option>
            <option value="Zoey">Zoey</option>
            <option value="Aryan">Aryan</option>
            <option value="Mystical">Mystical</option>
          </select>
          <button onclick="addChore()">Add</button>
        </div>
        <div id="chores-list" style="margin-top:8px;"></div>
      </div>
    </div>
    <div class="panel shopping">
      <div class="panel-header">🛒 Shopping List</div>
      <div class="panel-body">
        <div class="add-shop">
          <input id="shop-input" placeholder="Add item..." onkeydown="if(event.key==='Enter')addShop()" />
          <button onclick="addShop()">Add</button>
        </div>
        <div id="shop-list" style="margin-top:6px;"></div>
      </div>
    </div>
  </div>

</div>

<!-- AI ASSISTANT -->
<div class="ai-bar">
  <div class="ai-messages" id="ai-messages">
    <div class="ai-msg assistant">Hey Whitten family! I'm your Command Center AI. Ask me about your schedule, chores, shopping — anything!</div>
  </div>
  <div class="ai-input-row">
    <input id="ai-input" placeholder="Ask me anything... 'What's on the calendar this week?' or 'Who hasn't done their chores?'" onkeydown="if(event.key==='Enter')sendAI()" />
    <button id="ai-btn" onclick="sendAI()">Ask AI</button>
  </div>
</div>

<!-- ADD EVENT MODAL -->
<div class="modal-overlay" id="modal">
  <div class="modal">
    <h3>➕ Add Family Event</h3>
    <input type="text" id="evt-title" placeholder="Event title" />
    <input type="date" id="evt-date" />
    <input type="time" id="evt-time" placeholder="Time (optional)" />
    <select id="evt-member">
      <option value="family">Whole Family</option>
      <option value="Nick">Nick</option>
      <option value="Sarah">Sarah</option>
      <option value="Alyssa">Alyssa</option>
      <option value="Zach">Zach</option>
      <option value="Zoey">Zoey</option>
      <option value="Aryan">Aryan</option>
      <option value="Mystical">Mystical</option>
      <option value="Alex">Alex</option>
    </select>
    <div class="modal-btns">
      <button class="btn-save" onclick="saveEvent()">Save Event</button>
      <button class="btn-cancel" onclick="closeModal()">Cancel</button>
    </div>
  </div>
</div>

<script>
// ── COLORS ──────────────────────────────────────────────
const COLORS = {
  Nick:'#3b82f6', Sarah:'#ec4899', Alyssa:'#a855f7',
  Zach:'#22c55e', Zoey:'#f59e0b', Aryan:'#ef4444',
  Mystical:'#06b6d4', Alex:'#6366f1', family:'#ffffff'
};
const MEMBERS = ['Nick','Sarah','Alyssa','Zach','Zoey','Aryan','Mystical'];
const AGES = { Nick: 'Dad', Sarah: 'Mom', Alyssa: 16, Zach: 14, Zoey: 12, Aryan: 8, Mystical: 9, Alex: 'Adult' };

// ── STORAGE ──────────────────────────────────────────────
async function load(key) {
  try { const r = await window.storage.get(key); return r ? JSON.parse(r.value) : null; } catch { return null; }
}
async function save(key, val) {
  try { await window.storage.set(key, JSON.stringify(val)); } catch(e) { console.error(e); }
}

// ── CLOCK ────────────────────────────────────────────────
function updateClock() {
  const now = new Date();
  document.getElementById('clock').textContent = now.toLocaleTimeString('en-US', {hour:'2-digit',minute:'2-digit',second:'2-digit'});
  document.getElementById('date-display').textContent = now.toLocaleDateString('en-US', {weekday:'long',year:'numeric',month:'long',day:'numeric'});
}
setInterval(updateClock, 1000); updateClock();

// ── WEATHER ──────────────────────────────────────────────
async function loadWeather() {
  try {
    const r = await fetch('https://api.open-meteo.com/v1/forecast?latitude=37.0842&longitude=-94.5133&current_weather=true&temperature_unit=fahrenheit');
    const d = await r.json();
    const t = Math.round(d.current_weather.temperature);
    const codes = {0:'Clear ☀️',1:'Mostly Clear 🌤',2:'Partly Cloudy ⛅',3:'Overcast ☁️',45:'Foggy 🌫',48:'Foggy 🌫',51:'Drizzle 🌦',53:'Drizzle 🌦',55:'Drizzle 🌦',61:'Rainy 🌧',63:'Rainy 🌧',65:'Heavy Rain 🌧',71:'Snow 🌨',73:'Snow 🌨',75:'Heavy Snow ❄️',80:'Showers 🌦',81:'Showers 🌦',95:'Thunderstorm ⛈',96:'Thunderstorm ⛈'};
    document.getElementById('weather-temp').textContent = t + '°F';
    document.getElementById('weather-desc').textContent = codes[d.current_weather.weathercode] || 'Joplin, MO';
  } catch { document.getElementById('weather-desc').textContent = 'Joplin, MO'; }
}
loadWeather(); setInterval(loadWeather, 600000);

// ── CALENDAR STATE ────────────────────────────────────────
let calYear, calMonth, events = [];
const now = new Date();
calYear = now.getFullYear(); calMonth = now.getMonth();

async function initEvents() {
  const stored = await load('events') || [];
  events = stored;
  await fetchICloud();
  renderCalendar();
  renderUpcoming();
  renderLegend();
}

async function fetchICloud() {
  const url = 'https://p133-caldav.icloud.com/published/2/MTQ2OTEzMTUwOTE0NjkxMxmkHbe2_xBl00L0KzKIR9DBPvHOuAIlJMKKqWP8KG_k6QYdBt4krNnPIjGB3fk5wJrvLeC19RaB49rZhdl2b38';
  try {
    const proxy = `https://api.allorigins.win/get?url=${encodeURIComponent(url)}`;
    const res = await fetch(proxy);
    const data = await res.json();
    const ics = data.contents;
    parseICS(ics);
  } catch(e) { console.log('iCloud fetch failed, using manual events only'); }
}

function parseICS(ics) {
  if (!ics) return;
  const lines = ics.replace(/\r\n /g,'').split(/\r\n|\n/);
  let evt = null;
  lines.forEach(line => {
    if (line === 'BEGIN:VEVENT') evt = {};
    else if (line === 'END:VEVENT' && evt) {
      if (evt.title && evt.date) {
        const exists = events.find(e => e.id === evt.id);
        if (!exists) events.push(evt);
      }
      evt = null;
    } else if (evt) {
      if (line.startsWith('SUMMARY:')) evt.title = line.slice(8);
      else if (line.startsWith('DTSTART')) {
        const val = line.split(':')[1];
        if (val && val.length >= 8) {
          const y = val.slice(0,4), m = val.slice(4,6), d = val.slice(6,8);
          evt.date = `${y}-${m}-${d}`;
          if (val.length > 8) {
            const h = val.slice(9,11), mn = val.slice(11,13);
            evt.time = `${h}:${mn}`;
          }
        }
      }
      else if (line.startsWith('UID:')) evt.id = 'ical-' + line.slice(4);
    }
  });
  // Assign colors based on known names
  events.forEach(e => {
    if (!e.member) {
      const t = (e.title||'').toLowerCase();
      if (t.includes('zach')) e.member = 'Zach';
      else if (t.includes('alyssa')) e.member = 'Alyssa';
      else if (t.includes('zoey')) e.member = 'Zoey';
      else if (t.includes('aryan')) e.member = 'Aryan';
      else if (t.includes('mystical')) e.member = 'Mystical';
      else if (t.includes('sarah')) e.member = 'Sarah';
      else if (t.includes('nick')) e.member = 'Nick';
      else if (t.includes('alex')) e.member = 'Alex';
      else e.member = 'family';
    }
  });
}

function renderCalendar() {
  const months = ['January','February','March','April','May','June','July','August','September','October','November','December'];
  document.getElementById('cal-title').textContent = `${months[calMonth]} ${calYear}`;
  const grid = document.getElementById('cal-grid');
  grid.innerHTML = '';
  ['Sun','Mon','Tue','Wed','Thu','Fri','Sat'].forEach(d => {
    const el = document.createElement('div');
    el.className = 'cal-day-label'; el.textContent = d;
    grid.appendChild(el);
  });
  const first = new Date(calYear, calMonth, 1).getDay();
  const days = new Date(calYear, calMonth+1, 0).getDate();
  const prevDays = new Date(calYear, calMonth, 0).getDate();
  const today = new Date();

  for (let i = 0; i < first; i++) {
    const cell = document.createElement('div');
    cell.className = 'cal-cell other-month';
    const n = document.createElement('div'); n.className = 'cal-num';
    n.textContent = prevDays - first + 1 + i; cell.appendChild(n);
    grid.appendChild(cell);
  }
  for (let d = 1; d <= days; d++) {
    const cell = document.createElement('div'); cell.className = 'cal-cell';
    const isToday = d === today.getDate() && calMonth === today.getMonth() && calYear === today.getFullYear();
    if (isToday) cell.classList.add('today');
    const n = document.createElement('div'); n.className = 'cal-num'; n.textContent = d; cell.appendChild(n);
    const dateStr = `${calYear}-${String(calMonth+1).padStart(2,'0')}-${String(d).padStart(2,'0')}`;
    const dayEvts = events.filter(e => e.date === dateStr);
    dayEvts.slice(0,3).forEach(e => {
      const ev = document.createElement('div'); ev.className = 'cal-event';
      ev.style.background = (COLORS[e.member]||'#fff') + '30';
      ev.style.color = COLORS[e.member]||'#fff';
      ev.style.borderLeft = `2px solid ${COLORS[e.member]||'#fff'}`;
      ev.textContent = e.title; cell.appendChild(ev);
    });
    if (dayEvts.length > 3) {
      const more = document.createElement('div'); more.style.fontSize='0.5rem'; more.style.color='var(--muted)';
      more.textContent = `+${dayEvts.length-3} more`; cell.appendChild(more);
    }
    grid.appendChild(cell);
  }
}

function changeMonth(dir) { calMonth += dir; if (calMonth > 11) { calMonth=0; calYear++; } if (calMonth < 0) { calMonth=11; calYear--; } renderCalendar(); }

function renderUpcoming() {
  const list = document.getElementById('upcoming-list'); list.innerHTML = '';
  const today = new Date(); today.setHours(0,0,0,0);
  const soon = events.filter(e => { const d = new Date(e.date+'T12:00:00'); return d >= today; })
    .sort((a,b) => new Date(a.date+'T12:00:00') - new Date(b.date+'T12:00:00')).slice(0,15);
  if (!soon.length) { list.innerHTML = '<div style="color:var(--muted);font-size:0.8rem;">No upcoming events</div>'; return; }
  soon.forEach(e => {
    const d = new Date(e.date+'T12:00:00');
    const item = document.createElement('div'); item.className = 'upcoming-item';
    item.style.borderLeftColor = COLORS[e.member]||'#fff';
    item.innerHTML = `<div class="upcoming-date">${d.toLocaleDateString('en-US',{weekday:'short',month:'short',day:'numeric'})}</div>
      <div class="upcoming-title">${e.title}</div>
      ${e.time ? `<div class="upcoming-time">⏰ ${formatTime(e.time)}</div>` : ''}`;
    list.appendChild(item);
  });
}

function formatTime(t) {
  if (!t) return '';
  const [h,m] = t.split(':').map(Number);
  const ampm = h >= 12 ? 'PM' : 'AM';
  return `${h%12||12}:${String(m).padStart(2,'0')} ${ampm}`;
}

function renderLegend() {
  const leg = document.getElementById('legend'); leg.innerHTML = '';
  Object.entries(COLORS).forEach(([name,color]) => {
    const item = document.createElement('div'); item.className = 'legend-item';
    item.innerHTML = `<div class="legend-dot" style="background:${color}"></div><span>${name}</span>`;
    leg.appendChild(item);
  });
}

// ── ADD EVENT ─────────────────────────────────────────────
function openAddEvent() {
  document.getElementById('evt-date').value = new Date().toISOString().split('T')[0];
  document.getElementById('modal').classList.add('open');
}
function closeModal() { document.getElementById('modal').classList.remove('open'); }
async function saveEvent() {
  const title = document.getElementById('evt-title').value.trim();
  const date = document.getElementById('evt-date').value;
  const time = document.getElementById('evt-time').value;
  const member = document.getElementById('evt-member').value;
  if (!title || !date) return;
  const evt = { id: Date.now().toString(), title, date, time, member };
  events.push(evt);
  const manual = (await load('events') || []);
  manual.push(evt); await save('events', manual);
  renderCalendar(); renderUpcoming();
  document.getElementById('evt-title').value = '';
  closeModal();
}

// ── CHORES ────────────────────────────────────────────────
let chores = [];
async function initChores() {
  chores = await load('chores') || getDefaultChores();
  renderChores();
}
function getDefaultChores() {
  return [
    // Nick - Dad duties
    {id:'c1',text:'Mow the lawn',member:'Nick',done:false},
    {id:'c2',text:'Take out trash cans',member:'Nick',done:false},
    // Sarah - Mom duties
    {id:'c3',text:'Grocery run',member:'Sarah',done:false},
    {id:'c4',text:'Meal planning for the week',member:'Sarah',done:false},
    // Alyssa - 16 (capable of most tasks)
    {id:'c5',text:'Vacuum living room & hallway',member:'Alyssa',done:false},
    {id:'c6',text:'Clean upstairs bathroom',member:'Alyssa',done:false},
    {id:'c7',text:'Do own laundry (wash & fold)',member:'Alyssa',done:false},
    // Zach - 14 (good for heavier kid chores)
    {id:'c8',text:'Wash & dry dishes after dinner',member:'Zach',done:false},
    {id:'c9',text:'Sweep kitchen & dining room',member:'Zach',done:false},
    {id:'c10',text:'Bring in trash cans after pickup',member:'Zach',done:false},
    // Zoey - 12 (moderate chores)
    {id:'c11',text:'Wipe down kitchen counters',member:'Zoey',done:false},
    {id:'c12',text:'Feed pets (if applicable)',member:'Zoey',done:false},
    {id:'c13',text:'Tidy up living room',member:'Zoey',done:false},
    // Mystical - 9 (simple but real chores)
    {id:'c14',text:'Set the dinner table',member:'Mystical',done:false},
    {id:'c15',text:'Pick up toys & bedroom floor',member:'Mystical',done:false},
    // Aryan - 8 (simple tasks)
    {id:'c16',text:'Clear own plate after meals',member:'Aryan',done:false},
    {id:'c17',text:'Put dirty clothes in hamper',member:'Aryan',done:false},
  ];
}
function renderChores() {
  const list = document.getElementById('chores-list'); list.innerHTML = '';
  MEMBERS.forEach(member => {
    const mine = chores.filter(c => c.member === member);
    if (!mine.length) return;
    const sec = document.createElement('div'); sec.className = 'member-section';
    const nm = document.createElement('div'); nm.className = 'member-name';
    nm.style.background = COLORS[member]; nm.textContent = member; sec.appendChild(nm);
    mine.forEach(c => {
      const row = document.createElement('div'); row.className = 'chore-item' + (c.done?' done':'');
      row.innerHTML = `<input type="checkbox" class="chore-cb" ${c.done?'checked':''} onchange="toggleChore('${c.id}')">
        <span class="chore-text">${c.text}</span>
        <button class="chore-del" onclick="delChore('${c.id}')">✕</button>`;
      sec.appendChild(row);
    });
    list.appendChild(sec);
  });
}
async function toggleChore(id) { const c = chores.find(x=>x.id===id); if(c){c.done=!c.done;} await save('chores',chores); renderChores(); }
async function delChore(id) { chores = chores.filter(x=>x.id!==id); await save('chores',chores); renderChores(); }
async function addChore() {
  const txt = document.getElementById('chore-input').value.trim();
  const member = document.getElementById('chore-member').value;
  if (!txt) return;
  chores.push({id:Date.now().toString(),text:txt,member,done:false});
  await save('chores',chores); renderChores();
  document.getElementById('chore-input').value='';
}
document.getElementById('chore-input').addEventListener('keydown', e => { if(e.key==='Enter') addChore(); });

// ── SHOPPING ──────────────────────────────────────────────
let shopItems = [];
async function initShop() { shopItems = await load('shop') || []; renderShop(); }
function renderShop() {
  const list = document.getElementById('shop-list'); list.innerHTML = '';
  shopItems.forEach(item => {
    const row = document.createElement('div'); row.className='shop-item'+(item.done?' done':'');
    row.innerHTML=`<input type="checkbox" class="chore-cb" ${item.done?'checked':''} onchange="toggleShop('${item.id}')">
      <span class="shop-text">${item.text}</span>
      <button class="chore-del" onclick="delShop('${item.id}')">✕</button>`;
    list.appendChild(row);
  });
}
async function addShop() {
  const txt = document.getElementById('shop-input').value.trim(); if(!txt) return;
  shopItems.push({id:Date.now().toString(),text:txt,done:false});
  await save('shop',shopItems); renderShop(); document.getElementById('shop-input').value='';
}
async function toggleShop(id) { const i=shopItems.find(x=>x.id===id); if(i) i.done=!i.done; await save('shop',shopItems); renderShop(); }
async function delShop(id) { shopItems=shopItems.filter(x=>x.id!==id); await save('shop',shopItems); renderShop(); }

// ── AI ASSISTANT ──────────────────────────────────────────
let aiHistory = [];
async function sendAI() {
  const inp = document.getElementById('ai-input');
  const msg = inp.value.trim(); if (!msg) return;
  inp.value = '';
  addAIMsg('user', msg);
  document.getElementById('ai-btn').disabled = true;

  const today = new Date();
  const upcoming = events.filter(e => new Date(e.date+'T12:00:00') >= today)
    .sort((a,b)=>new Date(a.date+'T12:00:00')-new Date(b.date+'T12:00:00')).slice(0,20)
    .map(e=>`${e.date}${e.time?' '+e.time:''}: ${e.title} (${e.member})`).join('\n');
  const pendingChores = chores.filter(c=>!c.done).map(c=>`${c.member}: ${c.text}`).join('\n');
  const shopList = shopItems.filter(s=>!s.done).map(s=>s.text).join(', ');

  const systemPrompt = `You are the Whitten Family Command Center AI assistant. You're helpful, warm, and a little fun. 
Today is ${today.toLocaleDateString('en-US',{weekday:'long',year:'numeric',month:'long',day:'numeric'})}.
Family members: Nick (Dad), Sarah (Mom), Alyssa (16, older daughter), Zach (14, son), Zoey (12, daughter), Aryan (8, son), Mystical (9, daughter), Alex (adult son, out of home).
When suggesting chores, keep them age-appropriate: Aryan(8) and Mystical(9) get simple tasks, Zoey(12) gets moderate tasks, Zach(14) and Alyssa(16) can handle most household chores.
Location: Joplin, Missouri.

Upcoming calendar events:
${upcoming || 'None loaded yet'}

Pending chores:
${pendingChores || 'All done!'}

Shopping list:
${shopList || 'Empty'}

Keep responses concise (2-4 sentences max) since this is a dashboard display. Be helpful and friendly!`;

  aiHistory.push({role:'user', content: msg});

  try {
    const res = await fetch('/.netlify/functions/claude', {
      method:'POST',
      headers:{'Content-Type':'application/json'},
      body: JSON.stringify({
        system: systemPrompt,
        messages: aiHistory
      })
    });
    const data = await res.json();
    const reply = data.content?.[0]?.text || 'Sorry, I had trouble responding.';
    aiHistory.push({role:'assistant', content: reply});
    if (aiHistory.length > 20) aiHistory = aiHistory.slice(-20);
    addAIMsg('assistant', reply);
  } catch(e) {
    addAIMsg('assistant', 'Connection error. Check your internet and try again!');
  }
  document.getElementById('ai-btn').disabled = false;
}

function addAIMsg(role, text) {
  const box = document.getElementById('ai-messages');
  const msg = document.createElement('div'); msg.className = `ai-msg ${role}`;
  msg.textContent = text; box.appendChild(msg);
  box.scrollTop = box.scrollHeight;
}

// ── INIT ──────────────────────────────────────────────────
initEvents();
initChores();
initShop();
setInterval(() => { fetchICloud().then(()=>{renderCalendar();renderUpcoming();}); }, 300000);
</script>
</body>
</html>
