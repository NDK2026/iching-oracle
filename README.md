# iching-oracle
Predictive analysis 
<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1"/>
<title>I Ching Recruitment Oracle</title>
<link href="https://fonts.googleapis.com/css2?family=IM+Fell+English:ital@0;1&family=Crimson+Text:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet"/>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#080604;color:#e8d5a3;font-family:'Crimson Text',Georgia,serif;min-height:100vh;overflow-x:hidden}
::-webkit-scrollbar{width:3px}::-webkit-scrollbar-thumb{background:#2a2010}
.page{max-width:680px;margin:0 auto;padding:40px 20px}
.hidden{display:none!important}
.label{font-size:10px;letter-spacing:2.5px;color:#7a6440;display:block;margin-bottom:10px}
.italic{font-style:italic;color:#a89060;line-height:1.9;font-size:14px}
.gold{color:#c8a96e}
.dim{color:#5a4830}
.card{background:#110e08;border:1px solid #2a2010;border-radius:2px;padding:24px;margin-bottom:14px}
.card-gold{border-left:3px solid #c8a96e}
.divider{width:60px;height:1px;background:linear-gradient(90deg,transparent,#c8a96e,transparent);margin:20px auto}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:14px}
.btn{background:transparent;border:1px solid #c8a96e;color:#c8a96e;padding:12px 36px;font-size:11px;letter-spacing:3px;font-family:inherit;cursor:pointer;border-radius:2px;transition:all .25s}
.btn:hover{background:#c8a96e18}
.btn-dim{border-color:#3a2e18;color:#5a4830}
.btn-dim:hover{background:#1a1510}
.btn-row{display:flex;justify-content:center;gap:14px;flex-wrap:wrap}
input[type=range]{-webkit-appearance:none;appearance:none;height:3px;background:#2a2010;outline:none;width:100%;border-radius:2px}
input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:13px;height:13px;background:#c8a96e;border-radius:50%;cursor:pointer;box-shadow:0 0 8px #c8a96e80}
select,input[type=text]{background:#0d0b07;border:1px solid #2a2010;color:#e8d5a3;border-radius:2px;padding:8px 12px;width:100%;font-family:inherit;font-size:14px;outline:none}
select:focus,input[type=text]:focus{border-color:#c8a96e50}
.hx-line{display:flex;justify-content:center;align-items:center;height:16px;margin-bottom:5px}
.hx-solid{width:60px;height:5px;background:linear-gradient(90deg,#8a6930,#e8d5a3,#8a6930);border-radius:2px}
.hx-broken{display:flex;gap:8px}
.hx-broken span{width:24px;height:5px;background:linear-gradient(90deg,#8a6930,#c8a96e);border-radius:2px}
.hx-broken span:last-child{background:linear-gradient(90deg,#c8a96e,#8a6930)}
.hx-moving .hx-solid{box-shadow:0 0 10px #c8a96e;animation:shimmer 1.5s infinite}
.trigrams{display:flex;justify-content:center;gap:24px;margin-bottom:32px}
.tg{font-size:22px;color:#c8a96e30}
.omen-badge{display:inline-block;border:1px solid currentColor;padding:7px 24px;border-radius:2px;font-size:11px;letter-spacing:3px}
.line-row{display:flex;gap:18px;align-items:flex-start;border-bottom:1px solid #1e1810;padding:13px 0}
.line-glyph{flex-shrink:0;width:68px;text-align:center}
.line-tag{font-size:9px;letter-spacing:1px;color:#3a2e18;margin-top:4px}
.line-tag.moving{color:#c8a96e;animation:shimmer 1.5s infinite}
.cast-step{padding:11px 0;font-size:12px;letter-spacing:2px;border-bottom:1px solid #1a1208;color:#2a2010;transition:color .4s}
.cast-step.done{color:#c8a96e}
.topnav{display:flex;gap:10px;margin-bottom:36px}
@keyframes shimmer{0%,100%{opacity:.4}50%{opacity:1}}
@keyframes fadeUp{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:translateY(0)}}
@keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-7px)}}
.fade-up{animation:fadeUp .6s ease both}
</style>
</head>
<body>

<!-- INTRO -->

<div id="screen-intro" class="page">
  <div style="text-align:center;padding-top:20px">
    <div class="label" style="text-align:center;letter-spacing:6px;margin-bottom:28px">易經 · YI JING</div>
    <div style="font-size:64px;margin-bottom:14px;filter:drop-shadow(0 0 24px #c8a96e50);animation:float 4s ease-in-out infinite">☯</div>
    <h1 style="font-family:'IM Fell English',serif;font-weight:400;font-size:30px;letter-spacing:2px;margin-bottom:8px;color:#e8d5a3">The Recruitment Oracle</h1>
    <p class="italic dim" style="font-size:13px;letter-spacing:1px">Pattern as Oracle · Pattern as Counsel</p>
    <div class="divider"></div>
    <div class="trigrams">
      <span class="tg" style="animation:float 3s ease-in-out infinite;animation-delay:.0s">☰</span>
      <span class="tg" style="animation:float 3s ease-in-out infinite;animation-delay:.3s">☷</span>
      <span class="tg" style="animation:float 3s ease-in-out infinite;animation-delay:.6s">☳</span>
      <span class="tg" style="animation:float 3s ease-in-out infinite;animation-delay:.9s">☵</span>
      <span class="tg" style="animation:float 3s ease-in-out infinite;animation-delay:1.2s">☲</span>
      <span class="tg" style="animation:float 3s ease-in-out infinite;animation-delay:1.5s">☴</span>
      <span class="tg" style="animation:float 3s ease-in-out infinite;animation-delay:1.8s">☶</span>
      <span class="tg" style="animation:float 3s ease-in-out infinite;animation-delay:2.1s">☱</span>
    </div>
    <div class="card" style="max-width:480px;margin:0 auto 36px;text-align:left">
      <p class="italic" style="margin-bottom:14px">"The I Ching does not predict fixed outcomes. It reads the <em>configuration of forces</em> — and returns counsel about what is latent, what is moving, what is hidden."</p>
      <p style="font-size:13px;color:#5a4830;line-height:1.8">This oracle maps a candidate's pattern of qualities onto the 64 hexagrams of the Book of Changes — reading not a score, but a <em>living arrangement of forces</em> — and speaks to timing, hidden strength, shadow, and trajectory.</p>
    </div>
    <button class="btn" onclick="showScreen('input')">BEGIN THE CONSULTATION</button>
    <div style="margin-top:52px;font-size:11px;color:#2a2010;letter-spacing:3px">易 · THE BOOK OF CHANGES · 易</div>
  </div>
</div>

<!-- INPUT -->

<div id="screen-input" class="page hidden">
  <div class="topnav">
    <button class="btn btn-dim" onclick="showScreen('intro')">← BACK</button>
  </div>
  <div class="label" style="letter-spacing:4px;margin-bottom:4px">易經 · THE SEEKER'S PROFILE</div>
  <h2 style="font-family:'IM Fell English',serif;font-weight:400;font-size:22px;color:#c8a96e;margin-bottom:28px">Configure the Candidate</h2>
  <div class="card">
    <label class="label">SEEKER'S NAME <span class="dim">(OPTIONAL)</span></label>
    <input type="text" id="f-name" placeholder="Candidate name…"/>
  </div>
  <div class="grid2">
    <div class="card">
      <label class="label">YEARS OF EXPERIENCE</label>
      <div style="display:flex;justify-content:space-between;margin-bottom:10px">
        <span class="gold" style="font-size:22px" id="v-experience">5</span>
        <span class="dim" style="font-size:11px;align-self:flex-end">yrs</span>
      </div>
      <input type="range" min="0" max="20" value="5" oninput="upd('experience',this.value)"/>
    </div>
    <div class="card">
      <label class="label">EDUCATION LEVEL</label>
      <select id="f-education">
        <option>High School</option><option>Associate's</option><option selected>Bachelor's</option><option>Master's</option><option>PhD</option>
      </select>
    </div>
    <div class="card">
      <label class="label">SKILLS ALIGNMENT</label>
      <div style="display:flex;justify-content:space-between;margin-bottom:10px">
        <span class="gold" style="font-size:22px" id="v-skills_match">70</span>
        <span class="dim" style="font-size:11px;align-self:flex-end">%</span>
      </div>
      <input type="range" min="0" max="100" value="70" oninput="upd('skills_match',this.value)"/>
    </div>
    <div class="card">
      <label class="label">CULTURE RESONANCE</label>
      <div style="display:flex;justify-content:space-between;margin-bottom:10px">
        <span class="gold" style="font-size:22px" id="v-culture_fit">7</span>
        <span class="dim" style="font-size:11px;align-self:flex-end">/10</span>
      </div>
      <input type="range" min="1" max="10" value="7" oninput="upd('culture_fit',this.value)"/>
    </div>
    <div class="card">
      <label class="label">LEADERSHIP HISTORY</label>
      <select id="f-leadership">
        <option>None</option><option selected>Team Lead</option><option>Manager</option><option>Director</option><option>C-Suite</option>
      </select>
    </div>
    <div class="card">
      <label class="label">ADAPTABILITY</label>
      <div style="display:flex;justify-content:space-between;margin-bottom:10px">
        <span class="gold" style="font-size:22px" id="v-adaptability">7</span>
        <span class="dim" style="font-size:11px;align-self:flex-end">/10</span>
      </div>
      <input type="range" min="1" max="10" value="7" oninput="upd('adaptability',this.value)"/>
    </div>
    <div class="card">
      <label class="label">COMMUNICATION</label>
      <div style="display:flex;justify-content:space-between;margin-bottom:10px">
        <span class="gold" style="font-size:22px" id="v-communication">7</span>
        <span class="dim" style="font-size:11px;align-self:flex-end">/10</span>
      </div>
      <input type="range" min="1" max="10" value="7" oninput="upd('communication',this.value)"/>
    </div>
    <div class="card">
      <label class="label">TECHNICAL DEPTH</label>
      <div style="display:flex;justify-content:space-between;margin-bottom:10px">
        <span class="gold" style="font-size:22px" id="v-technical_depth">7</span>
        <span class="dim" style="font-size:11px;align-self:flex-end">/10</span>
      </div>
      <input type="range" min="1" max="10" value="7" oninput="upd('technical_depth',this.value)"/>
    </div>
    <div class="card">
      <label class="label">SOUGHT POSITION</label>
      <input type="text" id="f-role" placeholder="e.g. Senior Engineer"/>
    </div>
    <div class="card">
      <label class="label">DOMAIN / INDUSTRY</label>
      <input type="text" id="f-industry" placeholder="e.g. FinTech, Healthcare"/>
    </div>
    <div class="card">
      <label class="label">INTERVIEW PRESENCE</label>
      <div style="display:flex;justify-content:space-between;margin-bottom:10px">
        <span class="gold" style="font-size:22px" id="v-interview_score">7</span>
        <span class="dim" style="font-size:11px;align-self:flex-end">/10</span>
      </div>
      <input type="range" min="1" max="10" value="7" oninput="upd('interview_score',this.value)"/>
    </div>
    <div class="card">
      <label class="label">REFERENCE QUALITY</label>
      <select id="f-references">
        <option>Poor</option><option>Average</option><option selected>Good</option><option>Excellent</option>
      </select>
    </div>
  </div>
  <div class="btn-row" style="margin-top:28px">
    <button class="btn" onclick="castHexagram()">☯ CAST THE HEXAGRAM</button>
  </div>
</div>

<!-- CASTING -->

<div id="screen-casting" class="page hidden">
  <div style="text-align:center;padding-top:80px">
    <div class="label" style="text-align:center;letter-spacing:5px;margin-bottom:36px">THE YARROW STALKS FALL</div>
    <div id="cast-steps" style="max-width:360px;margin:0 auto"></div>
    <div id="cast-hex" style="margin-top:32px"></div>
    <div id="cast-status" class="dim" style="font-size:11px;letter-spacing:3px;margin-top:14px;animation:shimmer 2s infinite"></div>
  </div>
</div>

<!-- ORACLE -->

<div id="screen-oracle" class="page hidden">
  <div class="topnav">
    <button class="btn btn-dim" onclick="showScreen('input')">← PROFILE</button>
    <button class="btn btn-dim" onclick="newConsult()">↺ NEW</button>
  </div>
  <div id="oracle-content"></div>
</div>

<script>
const HEXAGRAMS=[
  {num:1,name:"Qian",title:"The Creative",symbol:"䷀",lines:[1,1,1,1,1,1],element:"Heaven",quality:"Originating strength — exceptional potential awaits activation"},
  {num:2,name:"Kun",title:"The Receptive",symbol:"䷁",lines:[0,0,0,0,0,0],element:"Earth",quality:"Yielding capacity — strength through adaptability and deep listening"},
  {num:3,name:"Zhun",title:"Difficulty at the Beginning",symbol:"䷂",lines:[1,0,0,0,1,0],element:"Water/Thunder",quality:"Initial chaos births order — the candidate stands at threshold"},
  {num:11,name:"Tai",title:"Peace",symbol:"䷊",lines:[1,1,1,0,0,0],element:"Heaven/Earth",quality:"Perfect alignment of forces — heaven and earth in accord"},
  {num:14,name:"Da You",title:"Great Possession",symbol:"䷍",lines:[1,0,1,1,1,1],element:"Fire/Heaven",quality:"The fire above heaven — rare combination of brilliance and position"},
  {num:15,name:"Qian",title:"Modesty",symbol:"䷎",lines:[0,0,1,0,0,0],element:"Earth/Mountain",quality:"Mountain beneath earth — great capacity concealed within humility"},
  {num:24,name:"Fu",title:"Return",symbol:"䷗",lines:[1,0,0,0,0,0],element:"Earth/Thunder",quality:"The turning point — latent power beginning its ascent"},
  {num:29,name:"Kan",title:"The Abysmal",symbol:"䷜",lines:[0,1,0,0,1,0],element:"Water",quality:"Danger navigated through constancy — tested by adversity, proven"},
  {num:30,name:"Li",title:"The Clinging",symbol:"䷝",lines:[1,0,1,1,0,1],element:"Fire",quality:"Fire clings to what it illuminates — clarity, vision, brilliance"},
  {num:34,name:"Da Zhuang",title:"Great Power",symbol:"䷡",lines:[1,1,1,1,0,0],element:"Thunder/Heaven",quality:"Thunder above heaven — power that cannot be contained"},
  {num:40,name:"Jie",title:"Deliverance",symbol:"䷧",lines:[0,1,0,0,0,1],element:"Thunder/Water",quality:"The obstruction dissolves — movement after long stillness"},
  {num:42,name:"Yi",title:"Increase",symbol:"䷩",lines:[1,0,0,0,1,1],element:"Wind/Thunder",quality:"Increase flows downward — favorable for great undertakings"},
  {num:48,name:"Jing",title:"The Well",symbol:"䷯",lines:[0,1,0,1,1,0],element:"Water/Wind",quality:"The inexhaustible source — deep competence that nourishes all"},
  {num:50,name:"Ding",title:"The Cauldron",symbol:"䷱",lines:[1,0,1,1,0,1],element:"Fire/Wind",quality:"Transformation through refinement — raw potential cooked into mastery"},
  {num:55,name:"Feng",title:"Abundance",symbol:"䷶",lines:[1,0,0,1,0,1],element:"Thunder/Fire",quality:"The zenith of brightness — a peak moment demanding decisive action"},
  {num:63,name:"Ji Ji",title:"After Completion",symbol:"䷾",lines:[1,0,1,0,1,0],element:"Water/Fire",quality:"All lines in right place — mastery achieved, vigilance now required"},
  {num:64,name:"Wei Ji",title:"Before Completion",symbol:"䷿",lines:[0,1,0,1,0,1],element:"Fire/Water",quality:"The threshold — everything poised, the crossing not yet made"},
];

const OMEN={
  "AUSPICIOUS":{color:"#c8a96e",label:"大吉 · AUSPICIOUS"},
  "FAVORABLE":{color:"#86efac",label:"吉 · FAVORABLE"},
  "NEUTRAL":{color:"#94a3b8",label:"中 · NEUTRAL"},
  "CAUTION":{color:"#f59e0b",label:"戒 · CAUTION"},
  "INAUSPICIOUS":{color:"#f87171",label:"凶 · INAUSPICIOUS"},
};

let vals={experience:5,skills_match:70,culture_fit:7,adaptability:7,communication:7,technical_depth:7,interview_score:7};

function upd(id,v){vals[id]=+v;document.getElementById('v-'+id).textContent=v}

function showScreen(id){
  ['intro','input','casting','oracle'].forEach(s=>{
    const el=document.getElementById('screen-'+s);
    if(!el)return;
    if(s===id){el.classList.remove('hidden');el.style.display='block';}
    else{el.classList.add('hidden');el.style.display='none';}
  });
  window.scrollTo(0,0);
}

function getVals(){
  return{
    name:document.getElementById('f-name').value,
    education:document.getElementById('f-education').value,
    leadership:document.getElementById('f-leadership').value,
    role:document.getElementById('f-role').value,
    industry:document.getElementById('f-industry').value,
    references:document.getElementById('f-references').value,
    ...vals
  };
}

function selectHex(v){
  const refMap={Poor:0,Average:0.3,Good:0.7,Excellent:1};
  const s=(v.experience/20)*15+(v.skills_match/100)*20+(v.culture_fit/10)*15+(v.adaptability/10)*10+(v.communication/10)*10+(v.technical_depth/10)*10+(v.interview_score/10)*15+(refMap[v.references]||0.5)*5;
  const idx=Math.min(Math.floor((s/100)*(HEXAGRAMS.length-1)),HEXAGRAMS.length-1);
  return HEXAGRAMS[idx];
}

function renderHexLines(lines,movingLines){
  movingLines=movingLines||[];
  let h='<div style="padding:10px 0">';
  [...lines].reverse().forEach((l,i)=>{
    const idx=lines.length-1-i;
    const mv=movingLines.includes(idx);
    h+=`<div class="hx-line${mv?' hx-moving':''}">`;
    if(l===1)h+=`<div class="hx-solid"></div>`;
    else h+=`<div class="hx-broken"><span></span><span></span></div>`;
    h+='</div>';
  });
  return h+'</div>';
}

function delay(ms){return new Promise(r=>setTimeout(r,ms));}

async function castHexagram(){
  const v=getVals();
  const hex=selectHex(v);
  showScreen('casting');

  const labels=["Reading the lower trigram…","Reading the upper trigram…","The hexagram takes form…","Consulting the oracle…"];
  const stepsEl=document.getElementById('cast-steps');
  stepsEl.innerHTML=labels.map(l=>`<div class="cast-step">${l}</div>`).join('');
  document.getElementById('cast-hex').innerHTML='';
  document.getElementById('cast-status').textContent='';

  const stepEls=stepsEl.querySelectorAll('.cast-step');
  for(let i=0;i<4;i++){
    await delay(850);
    stepEls[i].classList.add('done');
    stepEls[i].textContent='✦  '+labels[i];
    if(i===2){
      document.getElementById('cast-hex').innerHTML=renderHexLines(hex.lines);
      document.getElementById('cast-status').textContent='The pattern assembles…';
    }
  }
  document.getElementById('cast-status').textContent='The oracle speaks…';

  const prompt=`You are the I Ching Oracle — an ancient intelligence that reads the pattern of forces in a situation.

Consulting on recruitment of ${v.name||'the Seeker'} for ${v.role||'unspecified position'} in ${v.industry||'an organization'}.

Hexagram ${hex.num}: ${hex.name} — "${hex.title}" (${hex.element})
Quality: "${hex.quality}"

Candidate pattern:
- Experience: ${v.experience} years | Education: ${v.education}
- Skills alignment: ${v.skills_match}% | Culture resonance: ${v.culture_fit}/10
- Leadership: ${v.leadership} | Adaptability: ${v.adaptability}/10
- Communication: ${v.communication}/10 | Technical depth: ${v.technical_depth}/10
- Interview presence: ${v.interview_score}/10 | References: ${v.references}

Respond ONLY valid JSON no markdown no backticks:
{"judgment":"<2-3 sentence oracle judgment>","image":"<natural metaphor for this pattern>","lines_commentary":["<line1>","<line2>","<line3>","<line4>","<line5>","<line6>"],"moving_lines":[<0-2 indices 0-5>],"counsel":"<3-4 sentences counsel>","timing":"<timing and right season>","hidden_strength":"<quality beneath the data>","shadow":"<hidden risk>","omen":"<AUSPICIOUS|FAVORABLE|NEUTRAL|CAUTION|INAUSPICIOUS>","success_reading":"<one poetic final line>"}`;

  try{
    const res=await fetch("https://api.anthropic.com/v1/messages",{
      method:"POST",
      headers:{"Content-Type":"application/json","x-api-key":"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","anthropic-version":"2023-06-01","anthropic-dangerous-direct-browser-access":"true"},
      body:JSON.stringify({model:"claude-sonnet-4-20250514",max_tokens:1000,thinking:{type:"enabled",budget_tokens:5000},messages:[{role:"user",content:prompt}]})
    });
    const data=await res.json();
    const block=data.content&&data.content.find(function(b){return b.type==="text";});
    if(block){
      const oracle=JSON.parse(block.text.replace(/```json|```/g,"").trim());
      renderOracle(oracle,hex,v.name);
      showScreen('oracle');
    }
  }catch(e){
    document.getElementById('oracle-content').innerHTML='<p style="color:#f87171;text-align:center;padding:60px 20px">The oracle could not be reached. Please try again.</p>';
    showScreen('oracle');
  }
}

function renderOracle(o,hex,name){
  const oc=OMEN[o.omen]||OMEN["NEUTRAL"];
  const mv=o.moving_lines||[];

  let linesHtml='';
  [...hex.lines].forEach(function(_,i){
    const idx=hex.lines.length-1-i;
    const line=hex.lines[idx];
    const isM=mv.includes(idx);
    const lineGlyph=line===1
      ?`<div class="hx-solid${isM?' hx-moving':''}"></div>`
      :`<div class="hx-broken"><span></span><span></span></div>`;
    linesHtml+=`<div class="line-row">
      <div class="line-glyph">
        <div style="display:flex;justify-content:center;margin-bottom:4px">${lineGlyph}</div>
        <div class="line-tag${isM?' moving':''}">${isM?'MOVING':'LINE '+(idx+1)}</div>
      </div>
      <p class="italic" style="font-size:13px;margin:0">${(o.lines_commentary&&o.lines_commentary[idx])||''}</p>
    </div>`;
  });

  document.getElementById('oracle-content').innerHTML=`
    <div style="text-align:center;margin-bottom:44px" class="fade-up">
      <div class="label" style="text-align:center;letter-spacing:4px;margin-bottom:14px">THE ORACLE READS · ${name||'THE SEEKER'}</div>
      <div style="font-size:72px;line-height:1;margin-bottom:10px;filter:drop-shadow(0 0 24px #c8a96e50)">${hex.symbol}</div>
      <div style="font-family:'IM Fell English',serif;font-size:26px;font-weight:400;color:#e8d5a3;margin-bottom:4px">${hex.num}. ${hex.title}</div>
      <div style="font-size:12px;letter-spacing:3px;color:#7a6440;margin-bottom:4px">${hex.name} · ${hex.element}</div>
      <div style="font-size:12px;color:#4a3820;font-style:italic;margin-bottom:22px">${hex.quality}</div>
      <div class="omen-badge" style="color:${oc.color};border-color:${oc.color};background:${oc.color}12">${oc.label}</div>
    </div>
    <div class="card card-gold fade-up">
      <span class="label">THE JUDGMENT</span>
      <p class="italic" style="color:#e8d5a3;font-size:15px;margin:0">${o.judgment}</p>
    </div>
    <div class="card fade-up">
      <span class="label">THE IMAGE</span>
      <p class="italic" style="margin:0">${o.image}</p>
    </div>
    <div class="card fade-up">
      <span class="label" style="margin-bottom:18px">THE SIX LINES</span>
      ${linesHtml}
    </div>
    <div class="grid2 fade-up">
      <div class="card" style="border-top:2px solid #1e3a1e">
        <span class="label" style="color:#4a7a4a">✦ HIDDEN STRENGTH</span>
        <p class="italic" style="color:#86efac80;font-size:13px;margin:0">${o.hidden_strength}</p>
      </div>
      <div class="card" style="border-top:2px solid #3a1e1e">
        <span class="label" style="color:#7a3a3a">☯ SHADOW</span>
        <p class="italic" style="color:#f8717180;font-size:13px;margin:0">${o.shadow}</p>
      </div>
    </div>
    <div class="card fade-up">
      <span class="label">COUNSEL TO THE ORGANIZATION</span>
      <p class="italic" style="color:#c8a96e;font-size:14px;margin:0 0 20px">${o.counsel}</p>
      <div style="border-top:1px solid #1e1810;padding-top:18px">
        <span class="label">ON TIMING</span>
        <p class="italic" style="font-size:13px;margin:0">${o.timing}</p>
      </div>
    </div>
    <div style="text-align:center;padding:40px 0 28px;border-top:1px solid #1e1810" class="fade-up">
      <span class="label" style="text-align:center;letter-spacing:4px;margin-bottom:18px">THE ORACLE'S FINAL WORD</span>
      <div class="divider"></div>
      <p style="font-family:'IM Fell English',serif;font-style:italic;font-size:19px;color:#c8a96e;line-height:1.9;max-width:440px;margin:0 auto;text-shadow:0 0 30px #c8a96e30">"${o.success_reading}"</p>
    </div>
    <div class="btn-row" style="padding-bottom:56px">
      <button class="btn" onclick="castHexagram()">RE-CAST ☯</button>
      <button class="btn btn-dim" onclick="newConsult()">NEW CONSULTATION</button>
    </div>`;
}

function newConsult(){
  document.getElementById('f-name').value='';
  document.getElementById('f-role').value='';
  document.getElementById('f-industry').value='';
  showScreen('intro');
}

showScreen('intro');
</script>

</body>
</html>
