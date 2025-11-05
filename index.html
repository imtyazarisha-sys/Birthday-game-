<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>For My Handsome 💫</title>
  <style>
    :root{
      --bg1:#fffafc; --bg2:#f7fbff; --accent:#ff7aa2; --muted:#6b6b6b;
      --card:rgba(255,255,255,0.85);
      font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Noto Sans',Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{margin:0;background:linear-gradient(180deg,var(--bg1),var(--bg2));color:#222;display:flex;align-items:flex-start;justify-content:center;padding:18px}
    .container{width:100%;max-width:920px;margin:0 auto}
    .card{background:var(--card);backdrop-filter:blur(6px);border-radius:16px;padding:16px;box-shadow:0 8px 30px rgba(20,20,30,0.06)}
    header{display:flex;align-items:center;gap:12px;padding:6px 2px}
    .brand{display:flex;flex-direction:column}
    .title{font-size:18px;font-weight:800;color:var(--accent);line-height:1}
    .subtitle{font-size:13px;color:var(--muted)}
    .top-controls{display:flex;gap:8px;margin-left:auto}
    .btn{background:var(--accent);color:white;border:0;padding:8px 12px;border-radius:10px;font-weight:700;cursor:pointer}
    .btn.ghost{background:transparent;color:var(--accent);border:1px solid rgba(0,0,0,0.06)}
    .game-stage{margin-top:12px}
    .stage{display:none;padding:12px;border-radius:12px}
    .stage.active{display:block}
    .playbox{background:linear-gradient(180deg, rgba(255,255,255,0.9), rgba(255,255,255,0.8));border-radius:12px;padding:12px}
    .playfield{width:100%;height:48vw;max-height:420px;border-radius:10px;background:linear-gradient(180deg,#fff,#fff9);position:relative;overflow:hidden;display:flex;align-items:center;justify-content:center}
    .heart{position:absolute;font-size:28px;cursor:pointer;user-select:none;transition:transform .12s ease, opacity .25s}
    .scorebar{display:flex;justify-content:space-between;align-items:center;padding:8px}
    .boxes{display:flex;gap:12px;justify-content:center;align-items:flex-end;padding:18px}
    .box{width:28vw;max-width:120px;height:28vw;max-height:120px;border-radius:12px;background:linear-gradient(180deg,#fff,#fffefc);display:flex;align-items:center;justify-content:center;box-shadow:0 8px 18px rgba(0,0,0,0.06);cursor:pointer;position:relative}
    .box.locked{opacity:0.5;filter:grayscale(.1)}
    .question{font-weight:700;margin-bottom:10px}
    .options{display:flex;flex-direction:column;gap:8px}
    .opt{background:#fff;border-radius:10px;padding:10px;border:1px solid rgba(0,0,0,0.04);cursor:pointer}
    .opt.correct{outline:3px solid rgba(50,200,120,0.12)}
    .opt.wrong{opacity:0.6}
    .story{padding:12px;border-radius:10px;background:linear-gradient(180deg,#fff,#fffefc)}
    .final{font-weight:800;color:var(--accent);font-size:18px;margin-top:12px}
    .wish{background:linear-gradient(90deg,#ffffffaa,#fff7fb);padding:10px;border-radius:10px;margin-top:10px;font-weight:600}
    footer{margin-top:12px;text-align:center;color:var(--muted);font-size:12px}
    canvas.confetti{position:fixed;left:0;top:0;width:100%;height:100%;pointer-events:none;z-index:9999}
    .emoji-pop{position:fixed;left:50%;top:30%;transform:translateX(-50%);font-size:46px;opacity:0;transition:opacity .45s, transform .45s}
    .emoji-pop.show{opacity:1;transform:translateX(-50%) translateY(-6px)}
    #unmuteOverlayBtn{position:fixed;left:50%;top:60%;transform:translateX(-50%);padding:10px 14px;border-radius:10px;background:var(--accent);color:#fff;border:0;z-index:2100;display:none}
    @media(min-width:720px){ .game-grid{display:grid;grid-template-columns:1fr 360px;gap:14px} .playfield{height:320px} }
    @media(max-width:520px){ .playfield{height:60vw} .boxes{gap:8px} .box{width:28vw;height:28vw} }
  </style>
</head>
<body>
  <canvas class="confetti" id="confettiCanvas"></canvas>

  <div class="container">
    <div class="card">
      <header>
        <div class="brand">
          <div class="title">For My Handsome 💫</div>
          <div class="subtitle">Chalo khelte hain — ek-ek level complete karo aur surprise unlock karo 🌸</div>
        </div>
        <div class="top-controls">
          <button class="btn" id="soundToggle">Play Music</button>
          <button class="btn ghost" id="restartAll">Restart</button>
        </div>
      </header>

      <div class="game-stage">
        <div style="display:flex;gap:8px;align-items:center;margin-top:10px">
          <div id="levelBadges" style="display:flex;gap:8px;align-items:center">
            <div class="badge" data-level="1">Level 1</div>
            <div class="badge" data-level="2">Level 2</div>
            <div class="badge" data-level="3">Level 3</div>
            <div class="badge" data-level="4">Level 4</div>
          </div>
        </div>

        <div class="game-grid" style="margin-top:12px">
          <div>
            <section id="level1" class="stage active playbox">
              <div class="scorebar"><div id="l1score">Score: 0</div><div id="l1timer">Time: 20</div></div>
              <div class="playfield" id="playfield" aria-label="game field">
                <div style="text-align:center;color:var(--muted)">Level 1: Hearts pe click karo aur 100 points banao 💖</div>
              </div>
              <div style="display:flex;gap:8px;justify-content:center;margin-top:12px">
                <button class="btn" id="startBtn">Start Game</button>
                <button class="btn ghost" id="rulesBtn">Rules</button>
              </div>
              <div class="wish" id="wish1" style="display:none">
                Every heart you collected is a wish I’m sending your way 💖<br>
                May your day glow softer than pastel skies.
              </div>
            </section>

            <section id="level2" class="stage playbox" aria-hidden="true">
              <div style="font-weight:800">Level 2: Choose a gift box 🎁</div>
              <div style="font-size:13px;color:var(--muted);margin-top:6px">Sahi box choose karo to agla level unlock hoga.</div>
              <div class="boxes" id="boxes">
                <div class="box" data-index="0">🎀</div>
                <div class="box" data-index="1">🎁</div>
                <div class="box" data-index="2">📦</div>
              </div>
              <div class="wish" id="wish2" style="display:none">
                Some gifts can’t be wrapped — like peace, laughter, and people who care. You already have all three, my handsome ✨
              </div>
            </section>

            <section id="level3" class="stage playbox" aria-hidden="true">
              <div style="font-weight:800">Level 3: Quiz — thoda personal 💬</div>
              <div style="font-size:13px;color:var(--muted);margin-top:6px">Har question ka sahi answer choose karo to agla message unlock hoga.</div>
              <div id="quizArea" style="margin-top:12px"></div>
              <div class="wish" id="wish3" style="display:none">
                You remembered every moment that mattered — and that’s what makes you unforgettable 💫
              </div>
            </section>

            <section id="level4" class="stage playbox" aria-hidden="true">
              <div style="font-weight:800">Level 4: Story ending 🌈</div>
              <div class="story" style="margin-top:8px">
                <div>Yeh chhoti si kahani tumhari hi hai — har step pe dua aur khushi.</div>
                <div style="margin-top:8px">May your heart always find peace in Allah’s plan 🤍</div>
                <div style="margin-top:8px">Mere sath or mere baad bhi hamesha khush rehna😭 I love you so much ... May Allah keep you happy here and in the hereafter or har dunya m mujhe apke sth rakhe🥹 Allah apko bhot kamyabi de...Every smile on your face is a dua I make quietly.</div>
                <div class="final">Happy Birthday my handsome 🌸</div>
              </div>
              <div id="finalUnlock" style="display:none;margin-top:12px">
                <div style="font-weight:800">Final Surprise</div>
                <div style="margin-top:10px">You’re more than a day worth celebrating — you’re the calm, the chaos, and the charm in every season 🌸</div>
              </div>
            </section>
          </div>

          <div style="min-width:220px">
            <div style="background:linear-gradient(180deg,#fff,#fffefc);padding:12px;border-radius:12px;box-shadow:0 10px 20px rgba(0,0,0,0.04);">
              <div style="font-weight:800">Surprise Area</div>
              <div id="surpriseArea" style="margin-top:8px;color:var(--muted)">Koi surprise unlock nahi hua — pehle level khelo 😊</div>
              <div style="margin-top:12px" id="progressBox"><div style="font-weight:700">Progress</div><div id="progressText" style="margin-top:6px;color:var(--muted)">Level 1 available</div></div>
            </div>
            <div style="margin-top:12px;text-align:center;color:var(--muted)">Tip: Use headphones for soft nasheed</div>
          </div>
        </div>

        <footer>Made with dua & pastel vibes 🌸 — open this file in browser (mobile friendly).</footer>
      </div>
    </div>
  </div>

  <div class="emoji-pop" id="aliyaPop">🥹💖</div>

  <!-- Hidden YouTube player (IFrame API) -->
  <div id="ytplayerWrap" style="display:none"><div id="ytplayer"></div></div>
  <button id="unmuteOverlayBtn">Tap to unmute nasheed</button>

<script>
/* CONFIG */
const TARGET_SCORE = 100;
const L1_TIME = 20;
const HEART_EMOJI = '💖';
const YT_VIDEO_ID = 'ivrumxRUz_Y'; // your YouTube ID

let currentLevel = 1;
let unlocked = {1:true,2:false,3:false,4:false};

/* Level1 */
let l1score = 0, l1time = L1_TIME, l1running = false, l1spawn, l1timer;
const playfield = document.getElementById('playfield');
const l1scoreEl = document.getElementById('l1score');
const l1timerEl = document.getElementById('l1timer');

/* Level2 */
const boxes = document.querySelectorAll('.box');
let correctBox = Math.floor(Math.random()*3);

/* Quiz */
const QUIZ = [
  { q:'Humari pehli baar kb baat hui thi?', opts:['5 April','11 April','15 April'], answerIndex:1 },
  { q:'Mere sath khush ho ya nhi?', opts:['Hamesha 😊','Kabhi kabhi 😅','Pata nahi 🙈'], answerIndex:0 },
  { q:'Sb khatre mein honge to pehle kiske liye daudoge?', opts:['Male friends','Female friends','Aliya'], answerIndex:2 }
];
let quizIndex=0, correctAnswers=0;

/* YouTube IFrame API */
let ytPlayer = null;
function onYouTubeIframeAPIReady(){
  ytPlayer = new YT.Player('ytplayer', {
    height: '0', width: '0',
    videoId: YT_VIDEO_ID,
    playerVars: { autoplay: 1, loop: 1, playlist: YT_VIDEO_ID, controls: 0, modestbranding: 1, rel:0, iv_load_policy:3 },
    events: {
      'onReady': (e)=> {
        try { e.target.mute(); e.target.playVideo(); } catch(e){ }
      }
    }
  });
}
(function loadYTapi(){ const s = document.createElement('script'); s.src = "https://www.youtube.com/iframe_api"; document.head.appendChild(s); })();

/* Music controls */
const soundToggle = document.getElementById('soundToggle');
const unmuteOverlayBtn = document.getElementById('unmuteOverlayBtn');
soundToggle.addEventListener('click', ()=> {
  if(!ytPlayer) { alert('Player initializing — thoda sa intezaar karo and try again.'); return; }
  const state = ytPlayer.getPlayerState();
  if(state !== YT.PlayerState.PLAYING){
    ytPlayer.playVideo();
    soundToggle.textContent = 'Pause Music';
    ytPlayer.unMute();
  } else {
    ytPlayer.pauseVideo();
    soundToggle.textContent = 'Play Music';
  }
});
unmuteOverlayBtn.addEventListener('click', ()=> {
  if(!ytPlayer) return;
  ytPlayer.unMute();
  ytPlayer.playVideo();
  soundToggle.textContent = 'Pause Music';
  unmuteOverlayBtn.style.display = 'none';
});

/* Autoplay attempt */
function tryAutoplayYT(){
  if(!ytPlayer){ setTimeout(tryAutoplayYT, 600); return; }
  try {
    ytPlayer.mute();
    ytPlayer.playVideo();
    setTimeout(()=> {
      const st = ytPlayer.getPlayerState();
      if(st !== YT.PlayerState.PLAYING){
        unmuteOverlayBtn.style.display = 'block';
      } else {
        unmuteOverlayBtn.style.display = 'none';
        soundToggle.textContent = 'Pause Music';
      }
    }, 900);
  } catch(e){ unmuteOverlayBtn.style.display = 'block'; }
}
window.addEventListener('load', ()=> setTimeout(tryAutoplayYT, 600));

/* Game logic */
function spawnHeart(){
  const el = document.createElement('div'); el.className='heart'; el.textContent = HEART_EMOJI;
  const size = Math.round(Math.random()*26)+18; el.style.fontSize = size+'px';
  const x = Math.random()*88+6; const y = Math.random()*70+10; el.style.left = x+'%'; el.style.top = y+'%';
  playfield.appendChild(el);
  el.addEventListener('click', ()=>{
    if(!l1running) return;
    l1score += 10; l1scoreEl.textContent = 'Score: '+l1score;
    el.style.transform = 'scale(.3) rotate(-30deg)'; el.style.opacity = '0'; setTimeout(()=>el.remove(),160);
    if(l1score >= TARGET_SCORE) finishLevel1(true);
  });
  setTimeout(()=>{ if(el.parentNode) el.remove() }, 2600);
}
function startLevel1(){
  if(l1running) return;
  l1running = true; l1score = 0; l1time = L1_TIME; l1scoreEl.textContent='Score: 0'; l1timerEl.textContent='Time: '+l1time;
  document.getElementById('surpriseArea').textContent = 'Khel shuru ho gaya — hearts ko click karo!';
  l1spawn = setInterval(spawnHeart,650);
  l1timer = setInterval(()=>{ l1time--; l1timerEl.textContent = 'Time: '+l1time; if(l1time<=0) finishLevel1(false); },1000);
}
function finishLevel1(success){
  l1running = false; clearInterval(l1spawn); clearInterval(l1timer);
  document.querySelectorAll('.heart').forEach(h=>h.remove());
  if(success){
    unlocked[2] = true; document.getElementById('surpriseArea').innerHTML = '<strong>Level 1 complete!</strong><br>Every heart you collected is a wish I’m sending your way 💖';
    document.getElementById('wish1').style.display='block';
    setTimeout(()=>{ showLevel(2); },900);
  } else {
    document.getElementById('surpriseArea').textContent = `Nice! You scored ${l1score}. Try again to unlock the surprise.`;
  }
}
document.getElementById('startBtn').addEventListener('click', startLevel1);
document.getElementById('rulesBtn').addEventListener('click', ()=> alert('Click appearing hearts to collect points. Har heart = 10 points. Reach 100 to unlock the next level.'));

boxes.forEach(b=> b.addEventListener('click', (ev)=>{
  const idx = Number(b.getAttribute('data-index'));
  b.style.transform = 'translateY(-8px)'; setTimeout(()=> b.style.transform='translateY(0)',300);
  if(idx === correctBox){
    unlocked[3] = true;
    document.getElementById('surpriseArea').innerHTML = '<strong>Level 2 complete!</strong><br>Some gifts can’t be wrapped — you already have peace & laughter ✨';
    document.getElementById('wish2').style.display='block';
    fireConfetti();
    boxes.forEach((bx,i)=>{ if(i===idx) bx.style.boxShadow='0 8px 30px rgba(255,122,162,0.18)'; else bx.classList.add('locked'); });
    setTimeout(()=> showLevel(3),900);
  } else {
    document.getElementById('surpriseArea').textContent = 'Oh! Yeh box khali nikla — try a different one.';
  }
}));

const quizArea = document.getElementById('quizArea');
function renderQuiz(){
  quizArea.innerHTML='';
  const qObj = QUIZ[quizIndex];
  const qEl = document.createElement('div'); qEl.className='question'; qEl.textContent = `Q${quizIndex+1}. ${qObj.q}`;
  quizArea.appendChild(qEl);
  const opts = document.createElement('div'); opts.className='options';
  qObj.opts.forEach((optText, idx)=>{
    const o = document.createElement('div'); o.className='opt'; o.textContent = optText; o.addEventListener('click', ()=> handleAnswer(idx));
    opts.appendChild(o);
  });
  quizArea.appendChild(opts);
}
function handleAnswer(idx){
  const qObj = QUIZ[quizIndex];
  const opts = document.querySelectorAll('.opt');
  opts.forEach((o,i)=>{ o.style.pointerEvents='none'; if(i===qObj.answerIndex) o.classList.add('correct'); if(i!==qObj.answerIndex && i===idx) o.classList.add('wrong'); });
  const correct = (idx === qObj.answerIndex);
  if(correct){ correctAnswers++; document.getElementById('surpriseArea').textContent = 'Correct!'; }
  else { document.getElementById('surpriseArea').textContent = 'Oops—thoda galat. Par agla try karke dekh!'; }

  if(quizIndex===2 && idx===2){
    const pop = document.getElementById('aliyaPop'); pop.classList.add('show'); setTimeout(()=> pop.classList.remove('show'),1800);
  }

  setTimeout(()=>{
    quizIndex++;
    if(quizIndex < QUIZ.length){ renderQuiz(); }
    else finishQuiz();
  },900);
}
function finishQuiz(){
  if(correctAnswers >= QUIZ.length){
    unlocked[4] = true; document.getElementById('wish3').style.display='block';
    document.getElementById('surpriseArea').innerHTML = '<strong>Level 3 complete!</strong><br>You remembered every moment that mattered — and that’s what makes you unforgettable 💫';
    setTimeout(()=> showLevel(4),900);
  } else {
    document.getElementById('surpriseArea').textContent = `You answered ${correctAnswers} / ${QUIZ.length} correctly. Do try again!`;
    quizIndex=0; correctAnswers=0; setTimeout(()=> renderQuiz(),900);
  }
}

const obs = new MutationObserver((mut)=>{
  mut.forEach(m=>{
    if(m.target.classList && m.target.classList.contains('stage')){
      if(m.target.id === 'level3' && m.target.classList.contains('active')){
        quizIndex=0; correctAnswers=0; renderQuiz();
      }
      if(m.target.id === 'level4' && m.target.classList.contains('active')){
        document.getElementById('finalUnlock').style.display='block';
        document.getElementById('surpriseArea').innerHTML = '<strong>Final Level!</strong><br>May your heart always find peace in Allah\\'s plan 🤍';
        fireConfetti();
      }
    }
  });
});
document.querySelectorAll('.stage').forEach(s=> obs.observe(s,{attributes:true,attributeFilter:['class']}));

function showLevel(n){ document.querySelectorAll('.stage').forEach(s=> s.classList.remove('active')); const el = document.getElementById('level'+n); if(el){ el.classList.add('active'); el.removeAttribute('aria-hidden'); } currentLevel = n; updateProgress(); }
function updateProgress(){ const prog = document.getElementById('progressText'); prog.textContent = `Current: Level ${currentLevel} — ` + (unlocked[currentLevel] ? 'Unlocked' : 'Locked'); }

function fireConfetti(){
  const canvas = document.getElementById('confettiCanvas');
  canvas.width = window.innerWidth; canvas.height = window.innerHeight;
  const ctx = canvas.getContext('2d'); const parts=[];
  for(let i=0;i<120;i++) parts.push({x:Math.random()*canvas.width,y:Math.random()*-canvas.height,vx:(Math.random()*4)-2,vy:Math.random()*6+2,size:Math.random()*12+6,color:`hsl(${Math.random()*360},70%,60%)`,rot:Math.random()*360});
  let t=0; function draw(){ ctx.clearRect(0,0,canvas.width,canvas.height);
    for(const p of parts){ p.x+=p.vx; p.y+=p.vy; p.rot+=6; ctx.save(); ctx.translate(p.x,p.y); ctx.rotate(p.rot*Math.PI/180); ctx.fillStyle=p.color; ctx.fillRect(-p.size/2,-p.size/2,p.size,p.size); ctx.restore(); }
    t++; if(t<240) requestAnimationFrame(draw); else ctx.clearRect(0,0,canvas.width,canvas.height);
  } draw();
}

document.getElementById('restartAll').addEventListener('click', ()=> location.reload());
window.addEventListener('keydown',(e)=>{ if(e.code==='Space') startLevel1(); });
document.querySelectorAll('[data-level]').forEach(b=> b.addEventListener('click', ()=>{ const lvl = Number(b.getAttribute('data-level')); if(unlocked[lvl]) showLevel(lvl); else alert('Yeh level abhi locked hai. Pehle pichla level complete karo.'); }));

function init(){ showLevel(1); document.getElementById('progressText').textContent='Level 1 available'; correctBox=Math.floor(Math.random()*3); }
init();

</script>
</body>
</html>
