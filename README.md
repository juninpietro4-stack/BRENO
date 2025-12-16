# BRENO <!DOCTYPE html><html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>FF CHEATERS</title>
<style>
:root{
  --bg:#0b0f1a;
  --panel:#121830;
  --card:#1a2147;
  --accent:#6c7bff;
  --accent2:#27e1a5;
  --text:#e8ebff;
  --muted:#aab0ff;
}
*{box-sizing:border-box;font-family:Arial,Helvetica,sans-serif}
body{margin:0;background:radial-gradient(1200px 600px at 10% -10%,#1a1f55,transparent),var(--bg);color:var(--text)}/* Container */ .app{max-width:980px;margin:20px auto;padding:16px} .header{display:flex;align-items:center;justify-content:space-between;background:linear-gradient(135deg,#1b2060,#10143a);border-radius:14px;padding:14px 16px;box-shadow:0 10px 30px rgba(0,0,0,.35);position:relative;z-index:5} .header h1{margin:0;font-size:22px;letter-spacing:.6px} .badge{padding:6px 10px;border-radius:999px;background:rgba(255,255,255,.08);font-size:12px}

/* Tabs */ .tabs{display:flex;gap:8px;margin:14px 0} .tab{flex:1;padding:12px;border-radius:12px;background:var(--panel);border:1px solid rgba(255,255,255,.06);color:var(--muted);text-align:center;cursor:pointer;transition:.2s} .tab.active{background:linear-gradient(135deg,var(--accent),#8f9bff);color:#0b0f1a;font-weight:bold}

/* Panels */ .panel{display:none;background:var(--panel);border-radius:16px;padding:16px;border:1px solid rgba(255,255,255,.06)} .panel.active{display:block} .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px} .card{background:var(--card);border-radius:14px;padding:14px;border:1px solid rgba(255,255,255,.06)} .card h3{margin:0 0 8px;font-size:16px} .card p{margin:0 0 10px;font-size:13px;color:#cfd3ff}

/* Controls */ .row{display:flex;align-items:center;justify-content:space-between;gap:10px;margin:8px 0} label{font-size:13px} input[type="range"]{width:100%} .toggle{appearance:none;width:46px;height:26px;border-radius:999px;background:#2a3170;position:relative;cursor:pointer;transition:.2s} .toggle:checked{background:linear-gradient(135deg,var(--accent2),#7cffcf)} .toggle::after{content:"";position:absolute;width:20px;height:20px;border-radius:50%;background:#fff;top:3px;left:3px;transition:.2s} .toggle:checked::after{left:23px} .button{padding:10px 14px;border-radius:12px;border:none;cursor:pointer;background:linear-gradient(135deg,var(--accent),#9aa6ff);color:#0b0f1a;font-weight:bold} .button.secondary{background:#2a3170;color:#fff}

/* Footer */ .footer{margin-top:14px;text-align:center;font-size:12px;color:#aab0ff} </style>

</head>
<body>
  <div class="app">
    <div class="header">
      <h1>FF CHEATERS</h1>
      <div style="display:flex;align-items:center;gap:8px">
        <span class="badge">Painel v1.0</span>
        <button id="themeBtn" aria-label="Menu de cores" style="background:transparent;border:none;color:#fff;font-size:24px;cursor:pointer;line-height:1">⋮</button>
      </div>
    </div><div id="themeMenu" style="display:none;position:absolute;right:10px;top:60px;z-index:999;background:var(--panel);border:1px solid rgba(255,255,255,.1);border-radius:12px;padding:10px;box-shadow:0 10px 30px rgba(0,0,0,.4);max-width:220px" style="display:none;position:absolute;right:30px;top:90px;background:var(--panel);border:1px solid rgba(255,255,255,.1);border-radius:12px;padding:10px;box-shadow:0 10px 30px rgba(0,0,0,.4);max-width:220px">
  <p style="margin:0 0 8px;font-size:13px;color:#cfd3ff">Trocar cor do painel</p>
  <div style="display:grid;grid-template-columns:1fr 1fr;gap:6px">
    <button class="button secondary" onclick="setTheme('roxo')">Roxo</button>
    <button class="button secondary" onclick="setTheme('verde')">Verde</button>
    <button class="button secondary" onclick="setTheme('vermelho')">Vermelho</button>
    <button class="button secondary" onclick="setTheme('azul')">Azul</button>
    <button class="button secondary" onclick="setTheme('ciano')">Ciano</button>
    <button class="button secondary" onclick="setTheme('rosa')">Rosa</button>
    <button class="button secondary" onclick="setTheme('laranja')">Laranja</button>
    <button class="button secondary" onclick="setTheme('amarelo')">Amarelo</button>
    <button class="button secondary" onclick="setTheme('preto')">Preto</button>
    <button class="button secondary" onclick="setTheme('neon')">Neon</button>
    <button class="button secondary" onclick="setTheme('dourado')">Dourado</button>
    <button class="button secondary" onclick="setTheme('branco')">Branco</button>
  </div>
</div>

<div class="tabs">
  <div class="tab active" data-tab="precision">PRECISION</div>
  <div class="tab" data-tab="opt">OTIMIZAÇÃO</div>
  <div class="tab" data-tab="se">SE</div>
  <div class="tab" data-tab="info">INFO</div>
</div>

<!-- PRECISION -->
<div class="panel active" id="precision">
  <div class="grid">
    <div class="card">
      <h3>AIMBOT REGE</h3>
      <p>Ativação geral do módulo.</p>
      <div class="row"><label>Ativar</label><input class="toggle" type="checkbox" /></div>
    </div>
    <div class="card">
      <h3>RECUO</h3>
      <p>Controle de recuo (toggle).</p>
      <div class="row"><label>Ativar</label><input id="tgRecuo" class="toggle" type="checkbox" /></div>
    </div>
    <div class="card">
      <h3>Precision++</h3>
      <p>Precisão avançada (toggle).</p>
      <div class="row"><label>Ativar</label><input id="tgPrecision" class="toggle" type="checkbox" /></div>
    </div>
    <div class="card">
      <h3>AIMLOCK FIX</h3>
      <p>Fixação extrema.</p>
      <div class="row"><label>Intensidade</label><span id="aimlock">500%</span></div>
      <input type="range" min="0" max="500" value="500" oninput="aimlock.textContent=this.value+'%'" />
    </div>
    <div class="card">
      <h3>Forçar Puxada</h3>
      <p>Puxada automática.</p>
      <div class="row"><label>Força</label><span id="puxada">100%</span></div>
      <input type="range" min="0" max="100" value="100" oninput="puxada.textContent=this.value+'%'" />
    </div>
    <div class="card">
      <h3>Alvo da Mira</h3>
      <p>Escolha onde a mira vai grudar.</p>
      <div class="row">
        <select id="alvo" class="button secondary" style="width:100%">
          <option value="cabeca">Cabeça</option>
          <option value="pescoco">Pescoço</option>
          <option value="peito">Peito</option>
        </select>
      </div>
    </div>
    <div class="card">
      <h3>INJETAR</h3>
      <p>Abre o Free Fire após injeção.</p>
      <button id="btnInject" class="button" style="width:100%">Injetar Funções no Jogo</button>
      <p id="injectStatus" style="margin-top:10px;font-size:13px;color:#cfd3ff"></p>
    </div>
  </div>
</div>

<!-- OTIMIZAÇÃO -->
<div class="panel" id="opt">
  <div class="grid">
    <div class="card">
      <h3>120 FPS</h3>
      <p>Desbloqueio visual.</p>
      <div class="row"><label>Ativar</label><input class="toggle" type="checkbox" checked /></div>
    </div>
    <div class="card">
      <h3>RECOIL</h3>
      <p>Redução inteligente.</p>
      <div class="row"><label>Nível</label><span id="orec">80%</span></div>
      <input type="range" min="0" max="100" value="80" oninput="orec.textContent=this.value+'%'" />
    </div>
    <div class="card">
      <h3>Otimização FF 😈</h3>
      <p>Ajustes automáticos.</p>
      <div class="row"><label>Ativar</label><input class="toggle" type="checkbox" /></div>
    </div>
  </div>
</div>

<!-- SE -->
<div class="panel" id="se">
  <div class="grid">
    <div class="card">
      <h3>Anti-Cheat</h3>
      <p>Proteção básica.</p>
      <div class="row"><label>Ativar</label><input class="toggle" type="checkbox" /></div>
    </div>
    <div class="card">
      <h3>Não puxar em paredes</h3>
      <p>Bloqueio por obstáculo.</p>
      <div class="row"><label>Ativar</label><input class="toggle" type="checkbox" /></div>
    </div>
    <div class="card">
      <h3>Bypass</h3>
      <p>Modo compatibilidade.</p>
      <div class="row"><label>Ativar</label><input class="toggle" type="checkbox" /></div>
    </div>
  </div>
</div>

<!-- INFO -->
<div class="panel" id="info">
  <div class="card">
    <h3>Informações</h3>
    <ul>
      <li>Criador: <strong>FF CHEATERS</strong></li>
      <li>Administradores: <strong>BRENOFF</strong></li>
      <li>Hashiras<br><strong>:gs</strong><br><strong>:</strong></li>
    </ul>
  </div>
</div>

<!-- ANDROID PERMISSION POPUP -->
<div id="androidModal" style="display:none;position:fixed;inset:0;background:rgba(0,0,0,.55);z-index:9999;align-items:center;justify-content:center;">
  <div style="width:92%;max-width:380px;background:#1f1f1f;border-radius:14px;box-shadow:0 20px 40px rgba(0,0,0,.6);overflow:hidden">
    <div style="padding:14px 16px;background:#2a2a2a;font-weight:bold">Permitir FF CHEATERS</div>
    <div style="padding:16px;color:#eaeaea;font-size:14px;line-height:1.4">
      Permitir que <b>FF CHEATERS</b> execute funções avançadas no jogo?
    </div>
    <div style="display:flex;justify-content:flex-end;gap:10px;padding:12px 16px;background:#2a2a2a">
      <button id="denyBtn" style="background:transparent;border:none;color:#9aa6ff;font-weight:bold">NEGAR</button>
      <button id="allowBtn" style="background:transparent;border:none;color:#6cffb3;font-weight:bold">PERMITIR</button>
    </div>
  </div>
</div>

<!-- ANDROID CHOOSER (ABRIR COM) -->
<div id="chooser" style="display:none;position:fixed;inset:0;background:rgba(0,0,0,.55);z-index:10000;align-items:flex-end;">
  <div style="width:100%;background:#fff;border-radius:18px 18px 0 0;padding:14px 14px 10px;">
    <div style="font-weight:bold;color:#000;margin-bottom:10px">Abrir com</div>
    <div style="display:flex;gap:18px;justify-content:center;margin-bottom:12px">
      <div class="appOpt" data-app="ff" style="text-align:center;cursor:pointer">
        <div style="width:56px;height:56px;border-radius:14px;background:#eee;display:flex;align-items:center;justify-content:center;margin:0 auto 6px">FF</div>
        <div style="font-size:12px;color:#000">Free Fire</div>
      </div>
      <div class="appOpt" data-app="ffmax" style="text-align:center;cursor:pointer">
        <div style="width:56px;height:56px;border-radius:14px;background:#eee;display:flex;align-items:center;justify-content:center;margin:0 auto 6px">FF</div>
        <div style="font-size:12px;color:#000">Free Fire MAX</div>
      </div>
    </div>
    <div style="display:flex;align-items:center;gap:8px;margin:6px 0 10px">
      <input id="dontShow" type="checkbox" />
      <label for="dontShow" style="font-size:13px;color:#000">Não mostrar novamente</label>
    </div>
    <button id="cancelChooser" style="width:100%;padding:12px;border:none;border-radius:12px;background:#f2f2f2;color:#000;font-weight:bold">Cancelar</button>
  </div>
</div>

<div class="footer">© 2025 FF CHEATERS</div>

  </div><script>
// Aguarda o DOM carregar
window.addEventListener('DOMContentLoaded',()=>{
  // TABS
  const tabs=document.querySelectorAll('.tab');
  const panels=document.querySelectorAll('.panel');
  tabs.forEach(t=>{
    t.addEventListener('click',()=>{
      tabs.forEach(x=>x.classList.remove('active'));
      panels.forEach(p=>p.classList.remove('active'));
      t.classList.add('active');
      const target=document.getElementById(t.dataset.tab);
      if(target) target.classList.add('active');
    });
  });

  // MENU DE CORES (3 PONTINHOS)
  const themeBtn=document.getElementById('themeBtn');
  const themeMenu=document.getElementById('themeMenu');
  if(themeBtn && themeMenu){
    themeBtn.addEventListener('click',(e)=>{
      e.stopPropagation();
      themeMenu.style.display = (themeMenu.style.display==='block') ? 'none' : 'block';
    });
    document.addEventListener('click',()=>{
      themeMenu.style.display='none';
    });
  }

  // INJETAR (delay + abrir FF)
  const btn=document.getElementById('btnInject');
  const status=document.getElementById('injectStatus');
  if(btn && status){
    btn.addEventListener('click',()=>{
      status.textContent='Injetando...';
      btn.disabled=true;
      setTimeout(()=>{
        status.textContent='Injetado com sucesso ✅';
        const intent='intent://#Intent;action=android.intent.action.MAIN;category=android.intent.category.LAUNCHER;package=com.dts.freefireth;end';
        const intentMax='intent://#Intent;action=android.intent.action.MAIN;category=android.intent.category.LAUNCHER;package=com.dts.freefiremax;end';
        location.href=intent;
        setTimeout(()=>{ location.href=intentMax; },800);
        btn.disabled=false;
      },3000);
    });
  }
});

// THEMES
function setTheme(t){
  const r=document.documentElement.style;
  const themes={
    roxo:{accent:'#6c7bff',accent2:'#27e1a5',bg:'#0b0f1a',panel:'#121830',card:'#1a2147'},
    verde:{accent:'#2bff88',accent2:'#7cffcf',bg:'#08130c',panel:'#0f1f16',card:'#163026'},
    vermelho:{accent:'#ff4b4b',accent2:'#ff8a8a',bg:'#160808',panel:'#2a1010',card:'#3a1616'},
    azul:{accent:'#4bb3ff',accent2:'#8ad3ff',bg:'#081018',panel:'#0f1a2a',card:'#16263a'},
    ciano:{accent:'#00ffd5',accent2:'#6bffe8',bg:'#071514',panel:'#0f2624',card:'#163a37'},
    rosa:{accent:'#ff5bd8',accent2:'#ff9bea',bg:'#160812',panel:'#2a1022',card:'#3a1632'},
    laranja:{accent:'#ff9f43',accent2:'#ffc48a',bg:'#160f08',panel:'#2a1a10',card:'#3a2616'},
    amarelo:{accent:'#ffd400',accent2:'#fff1a8',bg:'#141208',panel:'#242010',card:'#343016'},
    preto:{accent:'#3a3a3a',accent2:'#8a8a8a',bg:'#000000',panel:'#111111',card:'#1e1e1e'},
    neon:{accent:'#00ff66',accent2:'#00ffaa',bg:'#020d08',panel:'#041a10',card:'#063020'},
    dourado:{accent:'#d4af37',accent2:'#ffdd77',bg:'#141108',panel:'#242010',card:'#3a3216'},
    branco:{accent:'#222222',accent2:'#666666',bg:'#f2f4ff',panel:'#ffffff',card:'#e6e9ff'}
  };
  if(themes[t]){
    r.setProperty('--accent',themes[t].accent);
    r.setProperty('--accent2',themes[t].accent2);
    r.setProperty('--bg',themes[t].bg);
    r.setProperty('--panel',themes[t].panel);
    r.setProperty('--card',themes[t].card);
  }
  const themeMenu=document.getElementById('themeMenu');
  if(themeMenu) themeMenu.style.display='none';
}
</script></body>
</html>
