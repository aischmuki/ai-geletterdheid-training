<!DOCTYPE html>
<html lang="nl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Module 01 — Wat is AI eigenlijk?</title>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;background:#F8F9FB;color:#111;min-height:100vh;padding:40px 16px;display:flex;justify-content:center}
.w{width:100%;max-width:660px}
.prog{display:flex;gap:5px;align-items:center;margin-bottom:1.75rem}
.prog-seg{height:3px;flex:1;border-radius:2px;background:#E2E8F0;transition:background .35s}
.prog-seg.on{background:#4F7EF7}
.prog-seg.dim{background:#A5B4FF}
.prog-lbl{font-size:11px;color:#94A3B8;white-space:nowrap}
.badge{display:inline-block;font-size:11px;font-weight:600;letter-spacing:.05em;text-transform:uppercase;padding:3px 10px;border-radius:20px;background:#EEF2FF;color:#3730A3;margin-bottom:1rem}
.h1{font-size:24px;font-weight:700;color:#0F172A;line-height:1.2;margin-bottom:.75rem}
.body{font-size:15px;color:#475569;line-height:1.75;margin-bottom:1rem}
.callout{border-left:3px solid #4F7EF7;border-radius:0;padding:12px 16px;background:#F1F5FF;font-size:14px;font-style:italic;color:#1E3A8A;margin:1rem 0 1.25rem;line-height:1.6}
.two-col{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin:1rem 0}
.col-card{background:#F8FAFC;border:1px solid #E2E8F0;border-radius:10px;padding:14px 16px}
.col-card h4{font-size:13px;font-weight:600;color:#0F172A;margin-bottom:8px}
.col-card p{font-size:13px;color:#475569;line-height:1.6}
.nav{display:flex;justify-content:space-between;align-items:center;margin-top:1.5rem;padding-top:1rem;border-top:1px solid #F1F5F9}
.dots{display:flex;gap:4px;align-items:center}
.dot{height:7px;border-radius:4px;background:#E2E8F0;transition:all .2s}
.dot.cur{width:18px;background:#4F7EF7}
.dot.past{width:7px;background:#4F7EF7}
.dot.fut{width:7px}
.btn-p{background:#4F7EF7;color:#fff;border:none;padding:10px 22px;border-radius:8px;font-size:14px;font-weight:600;cursor:pointer}
.btn-p:hover{opacity:.88}
.btn-p:disabled{opacity:.45;cursor:default}
.btn-g{background:#fff;border:1px solid #E2E8F0;color:#64748B;padding:10px 22px;border-radius:8px;font-size:14px;cursor:pointer}
.btn-g:hover{background:#F8FAFC}
.oef-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(140px,1fr));gap:8px;margin:1rem 0}
.oef-item{padding:11px 14px;border:1px solid #E2E8F0;border-radius:8px;background:#fff;cursor:pointer;font-size:13px;color:#334155;text-align:center;transition:all .2s;line-height:1.4}
.oef-item:hover:not(.locked){border-color:#A5B4FF;background:#EEF2FF}
.oef-item.ai{border-color:#059669;background:#ECFDF5;color:#065F46;font-weight:500}
.oef-item.geen{border-color:#94A3B8;background:#F8FAFC;color:#64748B}
.oef-item.locked{cursor:default}
.oef-legend{display:flex;gap:16px;font-size:12px;color:#64748B;margin-top:.75rem}
.leg-dot{width:10px;height:10px;border-radius:50%;display:inline-block;margin-right:4px;vertical-align:middle}
.q-text{font-size:18px;font-weight:600;color:#0F172A;line-height:1.4;margin-bottom:1.25rem}
.opt{display:flex;align-items:flex-start;gap:10px;padding:12px 14px;border:1px solid #E2E8F0;border-radius:10px;margin-bottom:8px;cursor:pointer;font-size:14px;color:#334155;background:#fff;transition:border .15s,background .15s;line-height:1.5}
.opt:hover:not(.locked){border-color:#A5B4FF;background:#F5F7FF}
.opt.ok{border-color:#059669;background:#ECFDF5;color:#065F46}
.opt.no{border-color:#DC2626;background:#FEF2F2;color:#991B1B}
.opt.hint{border-color:#059669;background:#F0FDF4;color:#166534}
.opt.locked{cursor:default}
.opt-k{width:22px;height:22px;border-radius:6px;background:#F1F5F9;border:1px solid #E2E8F0;display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:600;flex-shrink:0;margin-top:1px;color:#64748B}
.fb{padding:12px 14px;border-radius:10px;font-size:13px;line-height:1.6;margin-bottom:.75rem}
.fb-ok{background:#ECFDF5;border:1px solid #6EE7B7;color:#065F46}
.fb-no{background:#FEF2F2;border:1px solid #FCA5A5;color:#991B1B}
.sc-row{display:flex;justify-content:space-between;align-items:center;margin-top:.5rem}
.sc-lbl{font-size:12px;color:#94A3B8}
.sum-list{list-style:none;padding:0;margin:0 0 1rem}
.sum-list li{display:flex;align-items:flex-start;gap:10px;font-size:14px;color:#475569;line-height:1.6;padding:10px 0;border-bottom:1px solid #F1F5F9}
.sum-list li:last-child{border-bottom:none}
.sum-icon{color:#4F7EF7;font-size:18px;flex-shrink:0;margin-top:1px}
.assign-card{background:#F8FAFC;border:1px solid #E2E8F0;border-radius:12px;padding:1rem 1.25rem;margin-bottom:1rem}
.assign-card h3{font-size:15px;font-weight:600;color:#0F172A;margin-bottom:.75rem}
.assign-card li{font-size:13px;color:#475569;margin-bottom:7px;line-height:1.6}
.fb-card{background:#FFFBEB;border:1px solid #FDE68A;border-radius:12px;padding:1rem 1.25rem;margin-top:1rem}
.fb-card-lbl{font-size:10px;font-weight:700;letter-spacing:.07em;text-transform:uppercase;color:#B45309;margin-bottom:.5rem}
.fb-card p{font-size:14px;color:#78350F;line-height:1.7}
.comp{text-align:center;padding:3rem 1rem}
.comp-circle{width:80px;height:80px;border-radius:50%;border:2px solid #4F7EF7;background:#EEF2FF;display:flex;align-items:center;justify-content:center;margin:0 auto 1.25rem;font-size:36px;color:#3730A3}
.comp-title{font-size:26px;font-weight:700;color:#0F172A;margin-bottom:.5rem}
.comp-sub{font-size:15px;color:#64748B;margin-bottom:.75rem;line-height:1.65;max-width:420px;margin-left:auto;margin-right:auto}
.comp-quote{font-size:13px;font-style:italic;color:#94A3B8;margin-bottom:1.5rem;max-width:420px;margin-left:auto;margin-right:auto}
.pill{display:inline-block;background:#F1F5F9;border:1px solid #E2E8F0;border-radius:20px;padding:5px 14px;font-size:13px;color:#64748B;margin-bottom:1.25rem}
.view{display:none}.view.active{display:block}
textarea{width:100%;min-height:120px;border:1px solid #E2E8F0;border-radius:10px;padding:10px 12px;font-size:14px;font-family:inherit;color:#334155;background:#fff;resize:vertical;line-height:1.6;margin-bottom:.75rem}
textarea:focus{outline:none;border-color:#4F7EF7;box-shadow:0 0 0 3px rgba(79,126,247,.12)}
textarea:disabled{background:#F8FAFC;opacity:.7}
</style>
</head>
<body>
<div class="w">

  <div class="prog">
    <span class="prog-lbl">Les</span>
    <div class="prog-seg dim" id="ps0"></div>
    <span class="prog-lbl">Oefening</span>
    <div class="prog-seg" id="ps1"></div>
    <span class="prog-lbl">Quiz</span>
    <div class="prog-seg" id="ps2"></div>
    <span class="prog-lbl">Opdracht</span>
    <div class="prog-seg" id="ps3"></div>
    <span class="prog-lbl">Klaar</span>
    <div class="prog-seg" id="ps4"></div>
  </div>

  <!-- SLIDES -->
  <div class="view active" id="v-slides">
    <div class="badge">Module 01 &middot; <span id="snum">1/6</span></div>
    <div id="slide-content"></div>
    <div class="nav">
      <button class="btn-g" id="sprev" onclick="prevS()">&#8592; Vorige</button>
      <div class="dots" id="sdots"></div>
      <button class="btn-p" id="snext" onclick="nextS()">Volgende &#8594;</button>
    </div>
  </div>

  <!-- OEFENING -->
  <div class="view" id="v-oef">
    <div class="badge">Module 01 &middot; oefening</div>
    <div class="h1">AI of geen AI?</div>
    <p class="body">Klik op elke toepassing om te zien of er AI in zit. Bedenk zelf eerst — daarna zie je het antwoord en de toelichting.</p>
    <div class="oef-grid" id="oef-grid"></div>
    <div class="oef-legend" id="oef-legend" style="display:none">
      <span><span class="leg-dot" style="background:#059669"></span>Bevat AI</span>
      <span><span class="leg-dot" style="background:#888"></span>Geen AI</span>
    </div>
    <div id="oef-uitleg" style="margin-top:1rem"></div>
    <div class="nav">
      <button class="btn-g" onclick="show('slides');renderSlide()">&#8592; Terug</button>
      <span></span>
      <button class="btn-p" id="oef-next" onclick="show('quiz');showQ()" style="opacity:.4" disabled>Naar de quiz &#8594;</button>
    </div>
  </div>

  <!-- QUIZ -->
  <div class="view" id="v-quiz">
    <div class="badge">Module 01 &middot; <span id="qnum">vraag 1/5</span></div>
    <div class="q-text" id="qtext"></div>
    <div id="qopts"></div>
    <div id="qfb"></div>
    <div class="sc-row">
      <span class="sc-lbl" id="qsc">Score: 0/0</span>
      <button class="btn-p" id="qnext" onclick="nextQ()" style="display:none">Volgende &#8594;</button>
    </div>
  </div>

  <!-- OPDRACHT -->
  <div class="view" id="v-assign">
    <div class="badge">Module 01 &middot; opdracht</div>
    <div class="h1">AI in jouw eigen wereld</div>
    <p class="body">Theorie wordt pas kennis als je het verbindt met je eigen werkcontext. Neem even de tijd voor deze reflectie.</p>
    <div class="assign-card">
      <h3>Beantwoord de volgende vragen</h3>
      <ul style="padding-left:16px">
        <li>Beschrijf een AI-toepassing die je (bewust of onbewust) gebruikt in je werk of privéleven.</li>
        <li>Wat doet dit systeem waarschijnlijk met jouw data?</li>
        <li>Noem één situatie waarin de output fout of misleidend kon zijn — en waarom dat ertoe doet.</li>
      </ul>
    </div>
    <textarea id="ata" placeholder="Schrijf hier je antwoord..."></textarea>
    <div id="afb"></div>
    <div style="text-align:right">
      <button class="btn-p" id="abtn" onclick="submitA()">Verstuur &amp; ontvang feedback</button>
    </div>
  </div>

  <!-- COMPLETE -->
  <div class="view" id="v-comp">
    <div class="comp">
      <div class="comp-circle">&#10003;</div>
      <div class="comp-title">Module 01 afgerond</div>
      <div class="pill" id="fpill"></div>
      <p class="comp-sub">Je begrijpt nu wat AI is, hoe het verschilt van gewone software, waarom AI menselijk kan lijken zonder het te zijn — en waarom dat ertoe doet in jouw werk.</p>
      <p class="comp-quote">"Hoe beter we begrijpen wat AI is, hoe beter we kunnen bepalen wanneer we AI wel — en juist niet — moeten vertrouwen."</p>
      <button class="btn-p" onclick="restart()">Opnieuw bekijken</button>
    </div>
  </div>

</div>

<script>
const SLIDES=[
  {
    title:'Waarom AI-begrip belangrijk is',
    body:'Kunstmatige intelligentie is verweven in zoekmachines, sociale media, klantenservice, tekstverwerking, navigatie en besluitvorming. Toch gebruiken veel mensen AI zonder te begrijpen wat het is, hoe het werkt en welke invloed het heeft.',
    extra:'<div class="callout">AI-geletterdheid begint niet bij tools, maar bij begrip. Pas wanneer we begrijpen hoe AI werkt, kunnen we AI bewust, kritisch en verantwoord gebruiken.</div>'
  },
  {
    title:'Wat verstaan we onder AI?',
    body:'AI staat voor Artificial Intelligence — kunstmatige intelligentie. Het gaat om systemen die menselijke taken gedeeltelijk kunnen nabootsen: taal verwerken, patronen herkennen, voorspellingen maken, samenvatten of aanbevelingen doen.',
    extra:'<div class="callout">AI-systemen doen dit niet doordat ze "denken" zoals mensen — maar doordat ze grote hoeveelheden data analyseren en patronen herkennen.</div>'
  },
  {
    title:'Traditionele software vs. AI',
    body:'Traditionele software werkt op vaste regels: ALS dit, DAN dat. De ontwikkelaar schrijft elke stap voor. AI werkt anders: het analyseert data, herkent patronen en voorspelt wat waarschijnlijk het beste antwoord is.',
    extra:'<div class="two-col"><div class="col-card"><h4>Traditionele software</h4><p>Volgt vaste instructies. Een formulier controleert: is het BSN correct ingevuld? Klopt het format? Altijd hetzelfde resultaat bij dezelfde invoer.</p></div><div class="col-card"><h4>AI-systeem</h4><p>Leert van voorbeelden. Een AI kan documenten samenvatten, patronen herkennen in meldingen of burgers helpen via een chatbot — flexibel, maar ook feilbaar.</p></div></div>'
  },
  {
    title:'Waarom AI menselijk lijkt',
    body:'Mensen kennen snel menselijke eigenschappen toe aan technologie. Wanneer AI vloeiend schrijft, vriendelijk reageert en overtuigend communiceert, ontstaat de indruk dat AI begrijpt, redeneert of bewust keuzes maakt.',
    extra:'<div class="callout">Taalvaardigheid is niet hetzelfde als begrip. AI kan overtuigend schrijven en tegelijkertijd feitelijke fouten maken, bronnen verzinnen of informatie verkeerd interpreteren.</div>'
  },
  {
    title:'Hallucinaties: overtuigend fout',
    body:'Een hallucinatie ontstaat wanneer AI onjuiste informatie genereert, maar deze presenteert alsof het volledig klopt. Dit is geen bewuste leugen — het is een structureel gevolg van hoe AI werkt: voorspellen wat waarschijnlijk volgt, ook als de data ontbreekt.',
    extra:'<div class="callout">AI waarschuwt je niet wanneer het hallucineert. Het klinkt even zelfverzekerd als wanneer het wél klopt. Verificatie is daarom geen optie — het is een vereiste.</div>'
  },
  {
    title:'Samenvatting',
    body:'Je hebt nu de kern van module 1 doorlopen. Dit zijn de vier inzichten die je meeneemt:',
    extra:'<ul class="sum-list"><li><span class="sum-icon">&#8226;</span>AI is geen menselijk bewustzijn — het herkent patronen en voorspelt waarschijnlijkheden.</li><li><span class="sum-icon">&#8226;</span>AI verschilt fundamenteel van traditionele software: het leert, in plaats van regels te volgen.</li><li><span class="sum-icon">&#8226;</span>AI kan krachtig én feilbaar zijn — ook wanneer het overtuigend klinkt.</li><li><span class="sum-icon">&#8226;</span>AI-begrip is noodzakelijk om AI verantwoord te gebruiken in je werk.</li></ul>'
  }
];

const OEFS=[
  {label:'Google Maps',ai:true,uitleg:'AI berekent routes op basis van realtime verkeersdata en voorspelt reistijden.'},
  {label:'TikTok feed',ai:true,uitleg:'AI bepaalt wat je ziet op basis van kijkgedrag, interacties en vergelijkbare gebruikers.'},
  {label:'Spamfilter',ai:true,uitleg:'AI herkent patronen in e-mails om spam te onderscheiden van reguliere berichten.'},
  {label:'Chatbot klantenservice',ai:true,uitleg:'AI verwerkt tekst en genereert antwoorden op basis van trainingsdata en context.'},
  {label:'Rekenmachine',ai:false,uitleg:'Geen AI — een rekenmachine volgt vaste wiskundige regels zonder te leren of te voorspellen.'},
  {label:'Netflix aanbevelingen',ai:true,uitleg:'AI analyseert kijkgedrag en vergelijkt dit met miljoenen andere gebruikers om aanbevelingen te doen.'},
  {label:'Vertaalsoftware',ai:true,uitleg:'Moderne vertaaltools zoals DeepL gebruiken AI om context en betekenis te vertalen, niet alleen woorden.'},
  {label:'PDF-formulier',ai:false,uitleg:'Geen AI — een standaard formulier controleert vaste regels, zoals verplichte velden of formats.'},
];

const QS=[
  {q:'Hoe werkt een AI-systeem fundamenteel anders dan traditionele software?',opts:['Het is sneller en nauwkeuriger','Het leert patronen uit data in plaats van vaste regels te volgen','Het heeft altijd een internetverbinding nodig','Het maakt geen fouten'],c:1,expl:'Traditionele software volgt geprogrammeerde regels. AI leert van voorbeelden en voorspelt op basis van patronen — fundamenteel anders.'},
  {q:'Wat is de kernboodschap van module 1?',opts:['AI denkt sneller dan mensen','AI herkent patronen en voorspelt waarschijnlijkheden — het denkt niet zoals mensen','AI is altijd betrouwbaarder dan menselijk oordeel','AI begrijpt taal beter dan mensen'],c:1,expl:'AI simuleert begrip door patronen te herkennen in data. Er is geen sprake van echt denken, redeneren of bewustzijn.'},
  {q:'Wat is een AI-hallucinatie?',opts:['Een visuele fout in een AI-interface','Een situatie waarin AI zelfverzekerd onjuiste informatie presenteert','Een bewuste leugen van een AI-systeem','Een technische storing waardoor AI niet reageert'],c:1,expl:'Hallucinaties zijn structureel: AI voorspelt wat waarschijnlijk volgt, ook als de feitelijke basis ontbreekt. Het systeem waarschuwt je daar niet voor.'},
  {q:'Waarom lijkt AI soms menselijk, terwijl het dat niet is?',opts:['Omdat AI een bewustzijn heeft ontwikkeld','Omdat vloeiende taal en vriendelijke toon de indruk wekken van begrip en intentie','Omdat AI altijd correcte informatie geeft','Omdat AI getraind is op menselijke emoties'],c:1,expl:'Mensen schrijven snel menselijke eigenschappen toe aan systemen die vloeiend communiceren. Maar taalvaardigheid is niet hetzelfde als begrip.'},
  {q:'Welke van deze toepassingen bevat GEEN AI?',opts:['Een chatbot op een overheidswebsite','Netflix-aanbevelingen','Een rekenmachine','Een spamfilter'],c:2,expl:'Een rekenmachine volgt vaste wiskundige regels. Er is geen leren, geen patroonherkenning, geen voorspelling — dus geen AI.'},
];

let si=0,qi=0,score=0,picked=null,oefClicked=0;

function renderSlide(){
  const s=SLIDES[si];
  document.getElementById('slide-content').innerHTML='<div class="h1">'+s.title+'</div><p class="body">'+s.body+'</p>'+(s.extra||'');
  document.getElementById('snum').textContent=(si+1)+'/'+SLIDES.length;
  document.getElementById('sprev').disabled=si===0;
  document.getElementById('snext').textContent=si===SLIDES.length-1?'Naar de oefening \u2192':'Volgende \u2192';
  const d=document.getElementById('sdots');
  d.innerHTML=SLIDES.map((_,i)=>'<div class="dot'+(i===si?' cur':i<si?' past':' fut')+'" style="width:'+(i===si?'18':'7')+'px"></div>').join('');
}

function prevS(){if(si>0){si--;renderSlide();}}
function nextS(){if(si<SLIDES.length-1){si++;renderSlide();}else{show('oef');setP(1);renderOef();}}

function renderOef(){
  document.getElementById('oef-grid').innerHTML=OEFS.map((o,i)=>
    '<div class="oef-item" id="oi'+i+'" onclick="pickOef('+i+')">'+o.label+'</div>'
  ).join('');
}

function pickOef(i){
  const el=document.getElementById('oi'+i),o=OEFS[i];
  if(el.classList.contains('locked'))return;
  el.classList.add('locked',o.ai?'ai':'geen');
  oefClicked++;
  const u=document.getElementById('oef-uitleg');
  u.innerHTML='<div class="fb '+(o.ai?'fb-ok':'fb-no')+'"><strong>'+o.label+'</strong> — '+(o.ai?'Bevat AI. ':'Geen AI. ')+o.uitleg+'</div>'+u.innerHTML;
  if(oefClicked===OEFS.length){
    document.getElementById('oef-legend').style.display='flex';
    const nb=document.getElementById('oef-next');
    nb.disabled=false;nb.style.opacity='1';
  }
}

function showQ(){
  const q=QS[qi];picked=null;
  document.getElementById('qnum').textContent='vraag '+(qi+1)+'/'+QS.length;
  document.getElementById('qtext').textContent=q.q;
  document.getElementById('qfb').innerHTML='';
  document.getElementById('qnext').style.display='none';
  document.getElementById('qsc').textContent='Score: '+score+'/'+qi;
  document.getElementById('qopts').innerHTML=q.opts.map((o,i)=>
    '<div class="opt" id="qo'+i+'" onclick="pickQ('+i+')"><div class="opt-k">'+['A','B','C','D'][i]+'</div>'+o+'</div>'
  ).join('');
  setP(2);
}

function pickQ(i){
  if(picked!==null)return;
  picked=i;const q=QS[qi],cor=i===q.c;
  if(cor)score++;
  document.querySelectorAll('.opt').forEach((el,idx)=>{
    el.classList.add('locked');
    if(idx===q.c)el.classList.add(i===q.c?'ok':'hint');
    if(idx===i&&!cor)el.classList.add('no');
  });
  document.getElementById('qfb').innerHTML='<div class="fb '+(cor?'fb-ok':'fb-no')+'">'+(cor?'\u2713 Correct. ':'\u2717 Niet correct. ')+q.expl+'</div>';
  document.getElementById('qnext').style.display='inline-block';
  document.getElementById('qsc').textContent='Score: '+score+'/'+(qi+1);
}

function nextQ(){
  if(qi<QS.length-1){qi++;showQ();}
  else{show('assign');setP(3);}
}

async function submitA(){
  const ta=document.getElementById('ata');
  if(!ta.value.trim())return;
  ta.disabled=true;
  const btn=document.getElementById('abtn');
  btn.textContent='Feedback laden\u2026';btn.disabled=true;
  try{
    // Vervang 'JOUW_API_KEY_HIER' door je eigen key, of route via een backend proxy
    const r=await fetch('https://api.anthropic.com/v1/messages',{
      method:'POST',
      headers:{'Content-Type':'application/json','anthropic-version':'2023-06-01','x-api-key':'JOUW_API_KEY_HIER'},
      body:JSON.stringify({
        model:'claude-sonnet-4-20250514',max_tokens:200,
        system:'Je bent een deskundige coach voor overheidsmedewerkers in AI-geletterdheid. Geef korte, bemoedigende, concrete feedback (max 80 woorden, geen bullets). Warm maar direct. Sluit aan bij de werkcontext van de overheid. Taal: Nederlands.',
        messages:[{role:'user',content:'Module: Wat is AI eigenlijk?\nOpdracht: Beschrijf een AI-toepassing, wat het systeem met data doet, en een situatie waarin output fout of misleidend kon zijn.\nAntwoord: '+ta.value}]
      })
    });
    const d=await r.json();
    showFb(d.content?.[0]?.text||fallback());
  }catch{showFb(fallback());}
}

function fallback(){
  return'Goed werk. Je hebt de kern geraakt: een toepassing benoemen, nadenken over data en een reëel risico formuleren — dat is precies wat kritisch AI-gebruik in de overheid vraagt.';
}

function showFb(txt){
  document.getElementById('afb').innerHTML='<div class="fb-card"><div class="fb-card-lbl">Coach-feedback</div><p>'+txt+'</p></div>';
  const btn=document.getElementById('abtn');
  btn.textContent='Module afronden \u2192';btn.disabled=false;
  btn.onclick=()=>{
    document.getElementById('fpill').textContent=score+' van '+QS.length+' quizvragen goed';
    show('comp');setP(4);
  };
}

function show(v){
  ['slides','oef','quiz','assign','comp'].forEach(n=>document.getElementById('v-'+n).classList.remove('active'));
  document.getElementById('v-'+v).classList.add('active');
}

function setP(n){
  for(let i=0;i<5;i++){
    const el=document.getElementById('ps'+i);
    el.className='prog-seg'+(i<n?' on':i===n?' dim':'');
  }
}

function restart(){
  si=0;qi=0;score=0;picked=null;oefClicked=0;
  document.getElementById('ata').value='';
  document.getElementById('ata').disabled=false;
  document.getElementById('afb').innerHTML='';
  const b=document.getElementById('abtn');
  b.textContent='Verstuur & ontvang feedback';
  b.disabled=false;b.onclick=submitA;
  renderSlide();renderOef();
  document.getElementById('oef-uitleg').innerHTML='';
  document.getElementById('oef-legend').style.display='none';
  const nb=document.getElementById('oef-next');
  nb.disabled=true;nb.style.opacity='.4';
  show('slides');setP(0);
}

renderSlide();renderOef();
</script>
</body>
</html>
