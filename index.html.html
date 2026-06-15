<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GP Construcción · Indicadores Servicios BIM en obra</title>
<style>
:root{
  /* Identidad corporativa GP Construcción — azul marino / acero */
  --ink:#0B1B33; --navy:#13294B; --navy2:#1C3A63; --navy3:#27497A;
  --teal:#2F6BB0; --teal-br:#5E93D1; --teal-dk:#21507F;   /* acento azul acero */
  --paper:#F1F4F8; --surface:#FFFFFF; --line:#D7DEE8; --line2:#E8EDF3;
  --txt:#1A2533; --muted:#5C6B7E; --muted2:#8A98A8;
  --green:#2E8B5B; --green-bg:#E3F2E9;
  --amber:#C98424; --amber-bg:#FAEED6;
  --red:#C0473F; --red-bg:#F6E0DE;
  --slate:#76859A; --slate-bg:#EAEEF3;
  --mono:ui-monospace,"SF Mono","JetBrains Mono",Menlo,Consolas,monospace;
  --sans:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  --r:8px; --r-sm:6px;
}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{font-family:var(--sans);color:var(--txt);background:var(--paper);
  -webkit-font-smoothing:antialiased;font-size:14px;line-height:1.45}
.mono{font-family:var(--mono);font-variant-numeric:tabular-nums;letter-spacing:-.02em}
button{font-family:inherit;cursor:pointer}
input,select,textarea{font-family:inherit}
:focus-visible{outline:2px solid var(--teal);outline-offset:2px;border-radius:4px}

/* ---------- Top command bar ---------- */
.bar{position:sticky;top:0;z-index:40;background:var(--navy);
  color:#EAF0F8;border-bottom:3px solid var(--teal)}
.bar__grid{display:none}
.bar__in{position:relative;max-width:1280px;margin:0 auto;padding:13px 22px;
  display:flex;align-items:center;gap:20px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:13px;min-width:0}
.logo{width:42px;height:42px;flex:none}
.brand h1{font-size:15.5px;margin:0;font-weight:700;letter-spacing:.01em;white-space:nowrap}
.brand .eyebrow{font-size:9.5px;letter-spacing:.22em;color:#9FBFE6;
  text-transform:uppercase;margin:0 0 2px;font-weight:600}
.statusword{font-size:9.5px;letter-spacing:.16em;text-transform:uppercase;color:#9FBFE6;
  font-weight:600;border-left:1px solid rgba(255,255,255,.2);padding-left:9px;margin-left:2px}

.kpis{display:flex;gap:10px;margin-left:auto;flex-wrap:wrap}
.kpi{background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.14);
  border-radius:var(--r-sm);padding:6px 13px;min-width:96px}
.kpi .lab{font-size:9px;letter-spacing:.13em;text-transform:uppercase;color:#9FBFE6;white-space:nowrap}
.kpi .val{font-size:20px;font-weight:700;line-height:1.1}
.kpi .val small{font-size:11px;color:#AEC2DC;font-weight:500}

.tools{display:flex;gap:7px;flex-wrap:wrap;width:100%;margin-top:2px;
  border-top:1px solid rgba(255,255,255,.13);padding-top:11px}
.tbtn{background:rgba(255,255,255,.07);color:#E4ECF7;border:1px solid rgba(255,255,255,.18);
  border-radius:var(--r-sm);padding:7px 12px;font-size:12px;font-weight:600;
  display:inline-flex;align-items:center;gap:6px;transition:.15s}
.tbtn:hover{background:rgba(94,147,209,.28);border-color:var(--teal-br)}
.tbtn--solid{background:var(--teal);color:#fff;border-color:var(--teal)}
.tbtn--solid:hover{background:var(--teal-dk);border-color:var(--teal-dk)}
.tbtn--ghost{background:transparent}
.tbtn svg{width:14px;height:14px}
.spacer{flex:1}

/* ---------- Tabs ---------- */
.tabs{max-width:1280px;margin:0 auto;padding:0 22px;display:flex;gap:2px;
  position:sticky;top:0;z-index:30}
.tabwrap{background:var(--paper);position:sticky;top:53px;z-index:30;border-bottom:1px solid var(--line)}
.tab{appearance:none;background:none;border:none;padding:13px 16px 11px;font-size:13px;
  font-weight:600;color:var(--muted);border-bottom:2.5px solid transparent;display:flex;gap:7px;align-items:center}
.tab[aria-selected="true"]{color:var(--navy);border-bottom-color:var(--teal)}
.tab .num{font-family:var(--mono);font-size:10px;color:var(--muted2);
  background:var(--line2);border-radius:20px;padding:1px 7px}
.tab[aria-selected="true"] .num{background:var(--teal);color:#fff}

/* ---------- Layout ---------- */
.wrap{max-width:1280px;margin:0 auto;padding:22px}
.banner{background:var(--amber-bg);border:1px solid #efd09a;color:#7a5512;
  border-radius:var(--r-sm);padding:9px 14px;font-size:12.5px;margin-bottom:16px;display:none;
  align-items:center;gap:9px}
.banner.show{display:flex}
.banner svg{width:16px;height:16px;flex:none}

.sec-head{display:flex;align-items:baseline;gap:12px;margin:2px 0 16px}
.sec-head h2{font-size:18px;margin:0;font-weight:700;letter-spacing:-.01em}
.sec-head .sub{font-size:12.5px;color:var(--muted)}
.eyebrow{font-size:10px;letter-spacing:.22em;text-transform:uppercase;color:var(--teal-dk);font-weight:700;margin-bottom:5px}

/* cards */
.card{background:var(--surface);border:1px solid var(--line);border-radius:var(--r);
  box-shadow:0 1px 2px rgba(15,42,58,.04)}
.grid{display:grid;gap:14px}

/* service summary (tablero) */
.svc-grid{grid-template-columns:repeat(auto-fit,minmax(232px,1fr))}
.svc{padding:16px 17px;position:relative;overflow:hidden}
.svc::before{content:"";position:absolute;left:0;top:0;bottom:0;width:4px;background:var(--teal)}
.svc__tag{font-family:var(--mono);font-size:11px;color:var(--teal-dk);font-weight:700}
.svc__name{font-size:13.5px;font-weight:700;margin:3px 0 2px;line-height:1.25}
.svc__desc{font-size:11px;color:var(--muted);min-height:28px}
.svc__big{font-family:var(--mono);font-size:34px;font-weight:700;line-height:1;margin:8px 0 3px}
.svc__meta{display:flex;justify-content:space-between;font-size:10.5px;color:var(--muted2);margin-top:8px}

/* meter */
.meter{height:8px;background:var(--line2);border-radius:20px;overflow:hidden;position:relative}
.meter__fill{display:block;height:100%;background:linear-gradient(90deg,var(--teal-dk),var(--teal));
  border-radius:20px;transition:width .5s cubic-bezier(.2,.7,.3,1)}
.meter--sm{height:6px}
.meter--lg{height:11px}

/* KPI strip in tablero */
.strip{grid-template-columns:repeat(auto-fit,minmax(150px,1fr));margin-bottom:14px}
.stat{padding:14px 16px}
.stat .lab{font-size:10px;letter-spacing:.14em;text-transform:uppercase;color:var(--muted);font-weight:600}
.stat .v{font-family:var(--mono);font-size:27px;font-weight:700;margin-top:3px}
.stat .v small{font-size:13px;color:var(--muted)}

/* ranking bars */
.rank{padding:18px 20px}
.rank h3,.split h3,.cat h3{font-size:13px;font-weight:700;margin:0 0 14px;
  display:flex;align-items:center;gap:8px}
.rank h3 .eyebrow,.split h3 .eyebrow,.cat h3 .eyebrow{margin:0}
.rrow{display:grid;grid-template-columns:160px 1fr 46px;align-items:center;gap:12px;margin-bottom:9px}
.rrow .nm{font-size:12px;font-weight:600;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.rrow .pc{font-family:var(--mono);font-size:12.5px;font-weight:700;text-align:right}
.two{display:grid;grid-template-columns:1.6fr 1fr;gap:14px}
@media(max-width:820px){.two{grid-template-columns:1fr}.rrow{grid-template-columns:120px 1fr 42px}}

.split-row{display:flex;align-items:center;justify-content:space-between;
  padding:11px 0;border-bottom:1px solid var(--line2)}
.split-row:last-child{border-bottom:none}
.split-row .nm{font-size:12.5px;font-weight:600}
.split-row .nm small{display:block;color:var(--muted);font-weight:400;font-size:10.5px}
.split-row .pc{font-family:var(--mono);font-size:20px;font-weight:700}
.split{padding:18px 20px}

/* pills */
.pill{font-size:10px;font-weight:700;letter-spacing:.02em;padding:2.5px 9px;border-radius:20px;
  display:inline-flex;align-items:center;gap:4px;white-space:nowrap}
.pill::before{content:"";width:6px;height:6px;border-radius:50%;background:currentColor;opacity:.85}
.p-green{color:var(--green);background:var(--green-bg)}
.p-amber{color:var(--amber);background:var(--amber-bg)}
.p-red{color:var(--red);background:var(--red-bg)}
.p-slate{color:var(--slate);background:var(--slate-bg)}

/* ---------- Captura ---------- */
.cap-top{display:flex;gap:14px;align-items:flex-end;flex-wrap:wrap;margin-bottom:16px}
.field{display:flex;flex-direction:column;gap:4px}
.field label{font-size:10px;letter-spacing:.1em;text-transform:uppercase;color:var(--muted);font-weight:700}
select.input,input.input,textarea.input{border:1px solid var(--line);border-radius:var(--r-sm);
  padding:9px 11px;font-size:13px;background:var(--surface);color:var(--txt)}
select.input{min-width:280px;font-weight:600}
.cap-meta{margin-left:auto;display:flex;gap:18px;align-items:center}
.cap-meta .blk{text-align:right}
.cap-meta .blk .l{font-size:10px;letter-spacing:.12em;text-transform:uppercase;color:var(--muted);font-weight:600}
.cap-meta .blk .n{font-family:var(--mono);font-size:26px;font-weight:700;line-height:1}

.svccard{margin-bottom:14px;overflow:hidden}
.svccard__head{display:flex;align-items:center;gap:14px;padding:13px 18px;cursor:pointer;
  background:linear-gradient(180deg,#fff,#fbfdfd);border-bottom:1px solid var(--line2)}
.svccard__head .idx{font-family:var(--mono);font-weight:700;font-size:13px;color:#fff;background:var(--navy);
  width:26px;height:26px;border-radius:7px;display:grid;place-items:center;flex:none}
.svccard__head .ti{flex:1;min-width:0}
.svccard__head .ti b{font-size:14px;display:block}
.svccard__head .ti span{font-size:11px;color:var(--muted)}
.svccard__head .hp{display:flex;align-items:center;gap:12px}
.svccard__head .hp .pc{font-family:var(--mono);font-size:20px;font-weight:700;min-width:54px;text-align:right}
.svccard__head .hp .meter{width:120px}
.chev{transition:transform .2s;color:var(--muted2);flex:none}
.svccard.collapsed .chev{transform:rotate(-90deg)}
.svccard.collapsed .svccard__body{display:none}
.svccard__body{padding:6px 18px 14px}

.grouplab{font-size:10px;letter-spacing:.16em;text-transform:uppercase;font-weight:700;
  color:var(--teal-dk);margin:14px 0 6px;display:flex;align-items:center;gap:8px}
.grouplab.res{color:var(--amber)}
.grouplab::after{content:"";flex:1;height:1px;background:var(--line2)}

.ind{display:grid;grid-template-columns:1fr 142px 130px 1fr;gap:14px;align-items:center;
  padding:10px 0;border-bottom:1px solid var(--line2)}
.ind:last-child{border-bottom:none}
.ind .iname{font-size:12.5px;font-weight:600}
.ind .iname .pill{margin-left:0;margin-top:4px}
.slidewrap{display:flex;align-items:center;gap:9px}
.slidewrap input[type=range]{flex:1;accent-color:var(--teal);height:4px}
.numbox{width:62px;border:1px solid var(--line);border-radius:6px;padding:6px 7px;
  font-family:var(--mono);font-size:13px;font-weight:700;text-align:center}
.numbox::-webkit-inner-spin-button{opacity:.4}
.cmt{border:1px solid var(--line);border-radius:6px;padding:7px 9px;font-size:12px;width:100%;resize:vertical;min-height:34px}
.ind .iright{display:flex;align-items:center;gap:8px}
@media(max-width:740px){.ind{grid-template-columns:1fr;gap:8px}.cap-meta{margin-left:0}}

.iconbtn{background:none;border:1px solid var(--line);border-radius:6px;width:30px;height:30px;
  display:grid;place-items:center;color:var(--muted);flex:none}
.iconbtn:hover{border-color:var(--red);color:var(--red)}
.iconbtn svg{width:14px;height:14px}

/* ---------- Consolidado ---------- */
.tablewrap{overflow:auto;border:1px solid var(--line);border-radius:var(--r);background:#fff}
table{border-collapse:collapse;width:100%;min-width:760px}
th,td{padding:10px 12px;text-align:left;font-size:12.5px;border-bottom:1px solid var(--line2)}
thead th{background:var(--navy);color:#eaf6f4;font-size:10px;letter-spacing:.06em;
  text-transform:uppercase;font-weight:600;position:sticky;top:0}
thead th.num,td.num{text-align:center}
tbody tr:hover{background:#f6fafa}
td .cell{display:flex;flex-direction:column;gap:4px;align-items:center}
td .cell .meter{width:60px}
td .cell .pc{font-family:var(--mono);font-weight:700;font-size:12px}
td.proj{font-weight:600}
td.proj small{display:block;color:var(--muted);font-weight:400}
tfoot td{background:var(--navy2);color:#eaf6f4;font-weight:700;font-family:var(--mono)}
tfoot td:first-child{font-family:var(--sans)}
.cart-tag{font-size:9.5px;font-weight:700;letter-spacing:.04em;padding:1.5px 7px;border-radius:5px}
.cart-BTS{background:#e4f1f5;color:#16627a}
.cart-MT{background:#efeafa;color:#5b3d9e}

/* ---------- Catálogo ---------- */
.cat{padding:16px 18px;margin-bottom:14px}
.cat__head{display:flex;align-items:center;gap:13px;margin-bottom:12px}
.cat__head .idx{font-family:var(--mono);font-weight:700;color:#fff;background:var(--teal-dk);
  width:26px;height:26px;border-radius:7px;display:grid;place-items:center}
.cat__head b{font-size:14px}
.cat__head input.svcname{border:1px solid transparent;border-radius:6px;padding:5px 8px;
  font-size:14px;font-weight:700;flex:1;background:transparent}
.cat__head input.svcname:hover{border-color:var(--line)}
.cat__head input.svcname:focus{border-color:var(--teal);background:#fff}
.catrow{display:flex;align-items:center;gap:10px;padding:7px 0;border-bottom:1px solid var(--line2)}
.catrow:last-of-type{border-bottom:none}
.catrow .gtag{font-size:9px;font-weight:700;letter-spacing:.04em;padding:2px 7px;border-radius:5px;flex:none;cursor:pointer}
.gtag.prod{background:var(--blue-lt,#E7EEF6);color:var(--teal-dk)}
.gtag.res{background:var(--amber-bg);color:var(--amber)}
.catrow input.iedit{flex:1;border:1px solid transparent;border-radius:6px;padding:6px 8px;font-size:12.5px;background:transparent}
.catrow input.iedit:hover{border-color:var(--line)}
.catrow input.iedit:focus{border-color:var(--teal);background:#fff}
.addrow{display:flex;gap:8px;margin-top:10px}
.addrow input{flex:1;border:1px solid var(--line);border-radius:6px;padding:8px 10px;font-size:12.5px}
.miniadd{background:var(--navy);color:#fff;border:none;border-radius:6px;padding:8px 14px;font-size:12px;font-weight:600}
.miniadd:hover{background:var(--navy2)}

.hint{font-size:11.5px;color:var(--muted);margin-top:6px}
.empty{padding:50px 20px;text-align:center;color:var(--muted)}
.empty svg{width:40px;height:40px;color:var(--line);margin-bottom:10px}
.foot{max-width:1280px;margin:8px auto 30px;padding:0 22px;font-size:11px;color:var(--muted2);
  display:flex;justify-content:space-between;gap:14px;flex-wrap:wrap}
.foot .mono{color:var(--muted)}

/* toast */
.toast{position:fixed;bottom:22px;left:50%;transform:translateX(-50%) translateY(20px);
  background:var(--navy);color:#eaf6f4;padding:11px 18px;border-radius:var(--r-sm);font-size:13px;
  box-shadow:0 8px 24px rgba(8,25,31,.3);opacity:0;pointer-events:none;transition:.25s;z-index:90;
  display:flex;align-items:center;gap:9px}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0)}
.toast svg{width:16px;height:16px;color:var(--teal-br)}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
.hidden{display:none!important}
</style>
</head>
<body>

<header class="bar">
  <div class="bar__grid"></div>
  <div class="bar__in">
    <div class="brand">
      <svg class="logo" viewBox="0 0 48 48"><rect x="2" y="2" width="44" height="44" rx="8" fill="#FFFFFF"/><rect x="2.5" y="2.5" width="43" height="43" rx="7.5" fill="none" stroke="#2F6BB0" stroke-width="2"/><text x="24" y="30.5" text-anchor="middle" font-family="system-ui,Arial,sans-serif" font-weight="800" font-size="20" fill="#13294B" letter-spacing="-1">GP</text><rect x="13" y="36" width="22" height="3" rx="1.5" fill="#2F6BB0"/></svg>
      <div>
        <p class="eyebrow">GP Construcción · BIM en campo</p>
        <h1>Indicadores Servicios BIM en obra <span class="statusword">Panel de control</span></h1>
      </div>
    </div>
    <div class="kpis">
      <div class="kpi"><div class="lab">Proyectos</div><div class="val mono" id="k-proj">0</div></div>
      <div class="kpi"><div class="lab">Avance global</div><div class="val mono" id="k-glob">0<small>%</small></div></div>
      <div class="kpi"><div class="lab">Indicadores</div><div class="val mono" id="k-ind">0</div></div>
      <div class="kpi"><div class="lab">Capturados</div><div class="val mono" id="k-fill">0<small>%</small></div></div>
    </div>
    <div class="tools">
      <button class="tbtn tbtn--solid" id="t-add">+ Proyecto</button>
      <button class="tbtn" id="t-export">Exportar datos</button>
      <button class="tbtn" id="t-import">Importar datos</button>
      <button class="tbtn" id="t-csv">Exportar CSV</button>
      <span class="spacer"></span>
      <button class="tbtn tbtn--ghost" id="t-reset">Reiniciar</button>
      <input type="file" id="file-import" accept="application/json" class="hidden">
    </div>
  </div>
</header>

<div class="tabwrap">
  <nav class="tabs" role="tablist">
    <button class="tab" role="tab" aria-selected="true" data-view="tablero">Tablero</button>
    <button class="tab" role="tab" aria-selected="false" data-view="captura">Captura de resultados</button>
    <button class="tab" role="tab" aria-selected="false" data-view="consolidado">Consolidado</button>
    <button class="tab" role="tab" aria-selected="false" data-view="catalogo">Indicadores <span class="num" id="catcount">0</span></button>
  </nav>
</div>

<main class="wrap">
  <div class="banner" id="banner">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 9v4m0 4h.01M10.3 3.9 1.8 18a2 2 0 0 0 1.7 3h17a2 2 0 0 0 1.7-3L13.7 3.9a2 2 0 0 0-3.4 0z"/></svg>
    <span><b>Modo vista previa.</b> Aquí los cambios no se guardan al recargar. Publica el archivo en tu portal (ahí sí persisten) o usa <b>Exportar datos</b> para conservar lo capturado.</span>
  </div>

  <section id="view-tablero"></section>
  <section id="view-captura" class="hidden"></section>
  <section id="view-consolidado" class="hidden"></section>
  <section id="view-catalogo" class="hidden"></section>
</main>

<footer class="foot">
  <span>GP Construcción · BIM en campo · Indicadores de producción por servicio · 5 servicios BIM en obra</span>
  <span class="mono" id="updated">—</span>
</footer>

<div class="toast" id="toast"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M20 6 9 17l-5-5"/></svg><span id="toast-msg"></span></div>

<script>
"use strict";
/* ===================== Persistencia ===================== */
const KEY="gp_vdc_indicadores_bim_v2";
let storageOK=true;
try{const t="__t";localStorage.setItem(t,"1");localStorage.removeItem(t);}catch(e){storageOK=false;}
function save(){ state.updated=Date.now();
  if(!storageOK)return;
  try{localStorage.setItem(KEY,JSON.stringify(state));}catch(e){storageOK=false;document.getElementById("banner").classList.add("show");}
}
function load(){ if(!storageOK)return null;
  try{const r=localStorage.getItem(KEY);return r?JSON.parse(r):null;}catch(e){return null;} }

/* ===================== Catálogo semilla (PDF) ===================== */
function seedCatalog(){
  const mk=(n,g)=>({id:uid(),nombre:n,grupo:g});
  return {
    S1:{nombre:"Registro de avance de obra en modelo BIM",
        desc:"Registro del avance constructivo sobre el modelo BIM.",
        indicadores:[mk("Frecuencia de captura de avance","prod"),mk("Relación de capturas registradas en modelo","prod"),mk("Steel Tracking activo","prod")]},
    S2:{nombre:"Documentación As-Built desde especialidades",
        desc:"Generación de documentación As-Built desde modelos de especialidades.",
        indicadores:[mk("Número de planos — Planos GP","prod"),mk("Número de planos — Planos Subcontratistas","prod"),mk("Revisiones del cliente — Tipo de revisión","prod"),mk("Revisiones del cliente — Asignación a GP","prod"),mk("Revisiones del cliente — Asignación a Subcontratista","prod"),mk("Tiempo de respuesta a correcciones","prod"),mk("Programa de entrega","prod"),mk("Rendimiento semanal","prod"),mk("Tiempo de liberación del cliente","res")]},
    S3:{nombre:"Coordinación de modelo As-Built",
        desc:"Integración y coordinación de modelos As-Built de especialidades.",
        indicadores:[mk("Frecuencia de workshops","prod"),mk("Incidencias por cambios de revisión","prod"),mk("Validación As-Built vs. lo ejecutado","prod"),mk("Tiempo de respuesta a ajustes","prod"),mk("Tiempo de liberación del cliente","res")]},
    S4:{nombre:"Cuantificaciones desde modelo BIM",
        desc:"Extracción y generación de cantidades desde el modelo BIM.",
        indicadores:[mk("Tipología de cuantificación","prod"),mk("Tiempo de respuesta","prod"),mk("Modelado requerido para cuantificación","prod"),mk("Uso declarado de la cuantificación","prod"),mk("Evidencia de utilización para el propósito","res")]},
    S5:{nombre:"Coordinación BIM en obra",
        desc:"Coordinación BIM directamente en obra y workshops en sitio.",
        indicadores:[mk("Puesta en marcha de Command Center","prod"),mk("Despliegue en frentes de trabajo (workshops en sitio)","prod"),mk("Registro de issues de workshops","prod"),mk("Habilitar herramientas en móviles","prod"),mk("Generación de contenido adicional de ejecución","prod"),mk("Disminución de retrabajos","res"),mk("Disminución de incidentes por planeación","res")]}
  };
}
const SK=["S1","S2","S3","S4","S5"];

/* ===================== Proyectos semilla ===================== */
function seedProjects(){
  const P=[
    ["627 - LEGO Packing","Angel Flores","BTS"],["649 - PEPSI Co.","Ricardo Sauceda","BTS"],
    ["000 - Tren Suburbano","Saúl Sánchez","BTS"],["680 - Volvo","Imelda Espinoza","BTS"],
    ["693 - Hospital Infantil","Karla Sanchez","BTS"],["KIO MEX05","Carlos Acevedo","BTS"],
    ["KIO MEX08","Carlos Acevedo","BTS"],["696 - MT02 PI Libramiento","Scarlet Najera","MT"],
    ["706 - MT04 Ciénega","Scarlet Najera","MT"],["704 - MT06 ABB","Scarlet Najera","MT"],
    ["711 - MT02 León","Scarlet Najera","MT"]
  ];
  return P.map(([nombre,responsable,cartera])=>({id:uid(),nombre,responsable,cartera,valores:{}}));
}
function uid(){return Math.random().toString(36).slice(2,9);}

/* ===================== Estado ===================== */
let state=load()||{catalog:seedCatalog(),projects:seedProjects(),updated:Date.now()};
let current=state.projects[0]?state.projects[0].id:null;
let activeView="tablero";

/* ===================== Cálculos ===================== */
function prodInds(sk){return state.catalog[sk].indicadores.filter(i=>i.grupo==="prod");}
function allInds(sk){return state.catalog[sk].indicadores;}
function val(p,id){return (p.valores[id]&&typeof p.valores[id].avance==="number")?p.valores[id].avance:null;}
function servicePct(p,sk){
  const inds=prodInds(sk); if(!inds.length)return 0;
  let s=0; inds.forEach(i=>{const v=val(p,i.id); s+=(v==null?0:v);});
  return s/inds.length;
}
function projectPct(p){let s=0;SK.forEach(sk=>s+=servicePct(p,sk));return s/SK.length;}
function portfolioServicePct(sk){if(!state.projects.length)return 0;let s=0;state.projects.forEach(p=>s+=servicePct(p,sk));return s/state.projects.length;}
function portfolioPct(){if(!state.projects.length)return 0;let s=0;state.projects.forEach(p=>s+=projectPct(p));return s/state.projects.length;}
function totalIndicators(){let n=0;SK.forEach(sk=>n+=prodInds(sk).length);return n;}
function fillRate(){
  const tot=totalIndicators()*state.projects.length; if(!tot)return 0;
  let f=0; state.projects.forEach(p=>SK.forEach(sk=>prodInds(sk).forEach(i=>{if(val(p,i.id)!=null)f++;})));
  return f/tot*100;
}
function statusOf(p){ if(p>=80)return{c:"p-green",t:"En meta"}; if(p>=50)return{c:"p-amber",t:"En progreso"}; if(p>0)return{c:"p-red",t:"Requiere atención"}; return{c:"p-slate",t:"Sin captura"}; }
const R=x=>Math.round(x);

/* ===================== Render: header + updated ===================== */
function renderHeader(){
  document.getElementById("k-proj").textContent=state.projects.length;
  document.getElementById("k-glob").innerHTML=R(portfolioPct())+'<small>%</small>';
  document.getElementById("k-ind").textContent=totalIndicators();
  document.getElementById("k-fill").innerHTML=R(fillRate())+'<small>%</small>';
  document.getElementById("catcount").textContent=SK.reduce((a,sk)=>a+allInds(sk).length,0);
  const d=new Date(state.updated);
  document.getElementById("updated").textContent="Actualizado "+d.toLocaleDateString("es-MX",{day:"2-digit",month:"short"})+" "+d.toLocaleTimeString("es-MX",{hour:"2-digit",minute:"2-digit"});
}

/* ===================== Render: Tablero ===================== */
function renderTablero(){
  const root=document.getElementById("view-tablero");
  const meta={S1:"S1",S2:"S2",S3:"S3",S4:"S4",S5:"S5"};
  let svc="";
  SK.forEach(sk=>{
    const pct=portfolioServicePct(sk),st=statusOf(pct),c=state.catalog[sk];
    svc+=`<div class="card svc">
      <div class="svc__tag">${meta[sk]} · ${prodInds(sk).length} indicadores</div>
      <div class="svc__name">${esc(c.nombre)}</div>
      <div class="svc__desc">${esc(c.desc||"")}</div>
      <div class="svc__big mono">${R(pct)}<span style="font-size:16px">%</span></div>
      <div class="meter meter--lg"><span class="meter__fill" style="width:${pct}%"></span></div>
      <div class="svc__meta"><span class="pill ${st.c}">${st.t}</span><span>avance de producción</span></div>
    </div>`;
  });

  // ranking
  const ranked=[...state.projects].map(p=>({n:p.nombre,v:projectPct(p)})).sort((a,b)=>b.v-a.v);
  let rk="";
  ranked.forEach(r=>{rk+=`<div class="rrow"><span class="nm">${esc(r.n)}</span>
    <span class="meter"><span class="meter__fill" style="width:${r.v}%"></span></span>
    <span class="pc">${R(r.v)}%</span></div>`;});
  if(!ranked.length)rk=`<div class="empty">Sin proyectos. Usa “+ Proyecto”.</div>`;

  // cartera
  const carts=[["BTS","Built-to-Suit"],["MT","Mantenimiento / obra"]];
  let cs="";
  carts.forEach(([code,lbl])=>{
    const ps=state.projects.filter(p=>p.cartera===code);
    const v=ps.length?ps.reduce((a,p)=>a+projectPct(p),0)/ps.length:0;
    cs+=`<div class="split-row"><div class="nm">${code} <small>${lbl} · ${ps.length} proy.</small></div><div class="pc">${R(v)}%</div></div>`;
  });

  root.innerHTML=`
    <div class="sec-head"><div><div class="eyebrow">Resultado general</div><h2>Avance de los 5 servicios</h2></div>
      <span class="sub">Promedio de la cartera · calculado desde los indicadores de producción capturados</span></div>
    <div class="grid strip">
      <div class="card stat"><div class="lab">Avance global</div><div class="v">${R(portfolioPct())}<small>%</small></div></div>
      <div class="card stat"><div class="lab">Proyectos activos</div><div class="v">${state.projects.length}</div></div>
      <div class="card stat"><div class="lab">Indicadores / proyecto</div><div class="v">${totalIndicators()}</div></div>
      <div class="card stat"><div class="lab">Avance capturado</div><div class="v">${R(fillRate())}<small>%</small></div></div>
    </div>
    <div class="grid svc-grid" style="margin-bottom:14px">${svc}</div>
    <div class="two">
      <div class="card rank"><h3><span class="eyebrow">Por proyecto</span></h3>${rk}</div>
      <div class="card split"><h3><span class="eyebrow">Por cartera</span></h3>${cs}
        <div class="hint">Captura los indicadores en la pestaña <b>Captura de resultados</b> para alimentar estos promedios.</div>
      </div>
    </div>`;
}

/* ===================== Render: Captura ===================== */
function renderCaptura(){
  const root=document.getElementById("view-captura");
  if(!state.projects.length){root.innerHTML=`<div class="empty"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M3 7h18M3 12h18M3 17h18"/></svg><div>Agrega un proyecto para comenzar la captura.</div></div>`;return;}
  if(!state.projects.find(p=>p.id===current))current=state.projects[0].id;
  const p=state.projects.find(p=>p.id===current);
  const opts=state.projects.map(x=>`<option value="${x.id}" ${x.id===current?"selected":""}>${esc(x.nombre)} — ${esc(x.responsable)}</option>`).join("");

  let cards="";
  SK.forEach((sk,si)=>{
    const c=state.catalog[sk],pct=servicePct(p,sk),st=statusOf(pct);
    const groups=[["prod","Indicadores de producción"],["res","Indicadores de resultado"]];
    let body="";
    groups.forEach(([g,glab])=>{
      const inds=c.indicadores.filter(i=>i.grupo===g);
      if(!inds.length)return;
      body+=`<div class="grouplab ${g==="res"?"res":""}">${glab}</div>`;
      inds.forEach(i=>{
        const v=val(p,i.id), shown=v==null?0:v;
        const cm=(p.valores[i.id]&&p.valores[i.id].comentario)||"";
        const ist=statusOf(v==null?-1:v);
        body+=`<div class="ind" data-ind="${i.id}">
          <div class="iname">${esc(i.nombre)} <span class="pill ${ist.c}" data-pill="${i.id}">${v==null?"Sin captura":ist.t}</span></div>
          <div class="slidewrap"><input type="range" min="0" max="100" step="5" value="${shown}" data-range="${i.id}" aria-label="Avance ${esc(i.nombre)}"></div>
          <div class="iright"><input type="number" class="numbox" min="0" max="100" value="${v==null?"":v}" placeholder="—" data-num="${i.id}"><span class="mono" style="font-size:11px;color:var(--muted)">%</span></div>
          <textarea class="cmt" placeholder="Comentario / evidencia (opcional)" data-cmt="${i.id}">${esc(cm)}</textarea>
        </div>`;
      });
    });
    cards+=`<div class="card svccard" data-svc="${sk}">
      <div class="svccard__head" data-toggle="${sk}">
        <span class="idx">${si+1}</span>
        <div class="ti"><b>${esc(c.nombre)}</b><span>${prodInds(sk).length} de producción · ${allInds(sk).length} en total</span></div>
        <div class="hp"><span class="pill ${st.c}" data-spill="${sk}">${st.t}</span>
          <span class="meter" style="width:120px"><span class="meter__fill" data-smeter="${sk}" style="width:${pct}%"></span></span>
          <span class="pc" data-spc="${sk}">${R(pct)}%</span></div>
        <svg class="chev" viewBox="0 0 24 24" width="18" height="18" fill="none" stroke="currentColor" stroke-width="2"><path d="m6 9 6 6 6-6"/></svg>
      </div>
      <div class="svccard__body">${body}</div>
    </div>`;
  });

  root.innerHTML=`
    <div class="sec-head"><div><div class="eyebrow">Captura por colaborador</div><h2>Resultados por proyecto</h2></div>
      <span class="sub">Cada responsable registra el avance de sus indicadores de producción</span></div>
    <div class="cap-top">
      <div class="field"><label>Proyecto</label><select class="input" id="proj-select">${opts}</select></div>
      <div class="field"><label>Responsable</label><input class="input" id="proj-resp" value="${esc(p.responsable)}" style="min-width:170px"></div>
      <div class="field"><label>Cartera</label><select class="input" id="proj-cart" style="min-width:90px">
        <option value="BTS" ${p.cartera==="BTS"?"selected":""}>BTS</option>
        <option value="MT" ${p.cartera==="MT"?"selected":""}>MT</option></select></div>
      <div class="cap-meta">
        <div class="blk"><div class="l">Avance del proyecto</div><div class="n" id="proj-total">${R(projectPct(p))}%</div></div>
        <button class="iconbtn" id="proj-del" title="Eliminar proyecto"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 6h18M8 6V4h8v2M19 6l-1 14H6L5 6"/></svg></button>
      </div>
    </div>
    ${cards}`;
}

/* live update sin re-render (mantiene foco) */
function updateIndicator(p,sk,id){
  const ist=statusOf(val(p,id)==null?-1:val(p,id));
  const pill=document.querySelector(`[data-pill="${id}"]`);
  if(pill){pill.className="pill "+ist.c;pill.textContent=val(p,id)==null?"Sin captura":ist.t;pill.setAttribute("data-pill",id);}
  const pct=servicePct(p,sk),st=statusOf(pct);
  const sm=document.querySelector(`[data-smeter="${sk}"]`); if(sm)sm.style.width=pct+"%";
  const spc=document.querySelector(`[data-spc="${sk}"]`); if(spc)spc.textContent=R(pct)+"%";
  const sp=document.querySelector(`[data-spill="${sk}"]`); if(sp){sp.className="pill "+st.c;sp.textContent=st.t;sp.setAttribute("data-spill",sk);}
  const pt=document.getElementById("proj-total"); if(pt)pt.textContent=R(projectPct(p))+"%";
  renderHeader();
}

/* ===================== Render: Consolidado ===================== */
function renderConsolidado(){
  const root=document.getElementById("view-consolidado");
  let rows="";
  state.projects.forEach(p=>{
    let cells="";
    SK.forEach(sk=>{const v=servicePct(p,sk);
      cells+=`<td class="num"><div class="cell"><span class="meter"><span class="meter__fill" style="width:${v}%"></span></span><span class="pc">${R(v)}%</span></div></td>`;});
    const tot=projectPct(p),st=statusOf(tot);
    rows+=`<tr><td class="proj">${esc(p.nombre)}<small>${esc(p.responsable)}</small></td>
      <td><span class="cart-tag cart-${p.cartera}">${p.cartera}</span></td>
      ${cells}
      <td class="num"><span class="pc mono" style="font-weight:700">${R(tot)}%</span></td>
      <td><span class="pill ${st.c}">${st.t}</span></td></tr>`;
  });
  let foot="";
  SK.forEach(sk=>foot+=`<td class="num">${R(portfolioServicePct(sk))}%</td>`);
  root.innerHTML=`
    <div class="sec-head"><div><div class="eyebrow">Estatus por proyecto</div><h2>Matriz consolidada</h2></div>
      <span class="sub">Avance de producción por servicio · ${state.projects.length} proyectos</span></div>
    <div class="tablewrap"><table>
      <thead><tr><th>Proyecto</th><th>Cartera</th>
        <th class="num">S1 Reg.<br>avance</th><th class="num">S2 Doc.<br>As-Built</th><th class="num">S3 Coord.<br>As-Built</th><th class="num">S4 Cuanti-<br>ficaciones</th><th class="num">S5 Coord.<br>obra</th>
        <th class="num">General</th><th>Estatus</th></tr></thead>
      <tbody>${rows||`<tr><td colspan="9" class="empty">Sin proyectos.</td></tr>`}</tbody>
      <tfoot><tr><td>Promedio cartera</td><td></td>${foot}<td class="num">${R(portfolioPct())}%</td><td></td></tr></tfoot>
    </table></div>
    <div class="hint">Exporta esta matriz con <b>Exportar CSV</b> (barra superior) para compartirla o subirla a tu reporte.</div>`;
}

/* ===================== Render: Catálogo ===================== */
function renderCatalogo(){
  const root=document.getElementById("view-catalogo");
  let cards="";
  SK.forEach((sk,si)=>{
    const c=state.catalog[sk];
    let rows="";
    c.indicadores.forEach(i=>{
      rows+=`<div class="catrow" data-row="${i.id}">
        <span class="gtag ${i.grupo==="res"?"res":"prod"}" data-toggle-grupo="${sk}|${i.id}" title="Cambiar tipo">${i.grupo==="res"?"Resultado":"Producción"}</span>
        <input class="iedit" value="${esc(i.nombre)}" data-rename="${sk}|${i.id}">
        <button class="iconbtn" data-delind="${sk}|${i.id}" title="Quitar indicador"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6 6 18M6 6l12 12"/></svg></button>
      </div>`;
    });
    cards+=`<div class="card cat" data-cat="${sk}">
      <div class="cat__head"><span class="idx">${si+1}</span>
        <input class="svcname" value="${esc(c.nombre)}" data-svcname="${sk}">
        <span class="pill p-slate">${prodInds(sk).length} prod · ${allInds(sk).length} total</span></div>
      ${rows}
      <div class="addrow"><input placeholder="Nuevo indicador de producción para este servicio…" data-newind="${sk}">
        <button class="miniadd" data-addind="${sk}">Agregar</button></div>
    </div>`;
  });
  root.innerHTML=`
    <div class="sec-head"><div><div class="eyebrow">Control manual</div><h2>Catálogo de indicadores</h2></div>
      <span class="sub">Tú defines qué mide cada servicio · aplica a todos los proyectos</span></div>
    <div class="hint" style="margin:-6px 0 16px">Edita el nombre de un servicio o de un indicador haciendo clic sobre el texto. El tag <b>Producción / Resultado</b> se cambia con un clic. Solo los de <b>producción</b> cuentan para el avance.</div>
    ${cards}`;
}

/* ===================== Router ===================== */
function render(){renderHeader();
  ({tablero:renderTablero,captura:renderCaptura,consolidado:renderConsolidado,catalogo:renderCatalogo}[activeView])();}
function show(view){activeView=view;
  document.querySelectorAll(".tab").forEach(t=>t.setAttribute("aria-selected",t.dataset.view===view));
  ["tablero","captura","consolidado","catalogo"].forEach(v=>document.getElementById("view-"+v).classList.toggle("hidden",v!==view));
  render();}

/* ===================== Utilidades ===================== */
function esc(s){return String(s==null?"":s).replace(/[&<>"]/g,m=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[m]));}
let toastT;
function toast(msg){const t=document.getElementById("toast");document.getElementById("toast-msg").textContent=msg;
  t.classList.add("show");clearTimeout(toastT);toastT=setTimeout(()=>t.classList.remove("show"),2200);}

/* ===================== Eventos globales ===================== */
document.querySelectorAll(".tab").forEach(t=>t.addEventListener("click",()=>show(t.dataset.view)));

document.getElementById("t-add").addEventListener("click",()=>{
  const n=prompt("Nombre del proyecto:");if(!n)return;
  const r=prompt("Responsable:","Por asignar")||"Por asignar";
  const c=(prompt("Cartera (BTS / MT):","BTS")||"BTS").toUpperCase()==="MT"?"MT":"BTS";
  const np={id:uid(),nombre:n.trim(),responsable:r.trim(),cartera:c,valores:{}};
  state.projects.push(np);current=np.id;save();show("captura");toast("Proyecto agregado");
});
document.getElementById("t-reset").addEventListener("click",()=>{
  if(!confirm("Esto restaura los 5 servicios y los 11 proyectos base, y borra lo capturado. ¿Continuar?"))return;
  state={catalog:seedCatalog(),projects:seedProjects(),updated:Date.now()};current=state.projects[0].id;save();render();toast("Datos reiniciados");
});
document.getElementById("t-export").addEventListener("click",()=>{
  const blob=new Blob([JSON.stringify(state,null,2)],{type:"application/json"});
  const a=document.createElement("a");a.href=URL.createObjectURL(blob);
  a.download="VDC_indicadores_"+new Date().toISOString().slice(0,10)+".json";a.click();toast("Datos exportados (.json)");
});
document.getElementById("t-import").addEventListener("click",()=>document.getElementById("file-import").click());
document.getElementById("file-import").addEventListener("change",e=>{
  const f=e.target.files[0];if(!f)return;const rd=new FileReader();
  rd.onload=()=>{try{const d=JSON.parse(rd.result);
    if(!d.catalog||!d.projects)throw 0;
    state=d;current=state.projects[0]?state.projects[0].id:null;save();render();toast("Datos importados");
  }catch(err){alert("Archivo no válido. Debe ser un export de este tablero.");}};
  rd.readAsText(f);e.target.value="";
});
document.getElementById("t-csv").addEventListener("click",()=>{
  let rows=[["Proyecto","Responsable","Cartera","S1 Registro avance","S2 Doc As-Built","S3 Coord As-Built","S4 Cuantificaciones","S5 Coord obra","General","Estatus"]];
  state.projects.forEach(p=>{const r=[p.nombre,p.responsable,p.cartera];
    SK.forEach(sk=>r.push(R(servicePct(p,sk))+"%"));
    const t=projectPct(p);r.push(R(t)+"%",statusOf(t).t);rows.push(r);});
  const csv=rows.map(r=>r.map(c=>`"${String(c).replace(/"/g,'""')}"`).join(",")).join("\n");
  const blob=new Blob(["\ufeff"+csv],{type:"text/csv;charset=utf-8"});
  const a=document.createElement("a");a.href=URL.createObjectURL(blob);
  a.download="VDC_consolidado_"+new Date().toISOString().slice(0,10)+".csv";a.click();toast("CSV exportado");
});

/* ===================== Delegación: Captura ===================== */
document.getElementById("view-captura").addEventListener("input",e=>{
  const p=state.projects.find(x=>x.id===current);if(!p)return;
  const t=e.target;
  if(t.dataset.range!=null){const id=t.dataset.range,v=+t.value;
    p.valores[id]=Object.assign({},p.valores[id],{avance:v});
    const nb=document.querySelector(`[data-num="${id}"]`);if(nb)nb.value=v;
    updateIndicator(p,svcOf(id),id);save();}
  else if(t.dataset.num!=null){const id=t.dataset.num;let v=t.value===""?null:Math.max(0,Math.min(100,+t.value));
    p.valores[id]=Object.assign({},p.valores[id],{avance:v});
    const rg=document.querySelector(`[data-range="${id}"]`);if(rg)rg.value=v==null?0:v;
    updateIndicator(p,svcOf(id),id);save();}
  else if(t.dataset.cmt!=null){const id=t.dataset.cmt;
    p.valores[id]=Object.assign({},p.valores[id],{comentario:t.value});save();}
  else if(t.id==="proj-resp"){p.responsable=t.value;save();renderHeader();}
});
document.getElementById("view-captura").addEventListener("change",e=>{
  const p=state.projects.find(x=>x.id===current);if(!p)return;
  if(e.target.id==="proj-select"){current=e.target.value;render();}
  else if(e.target.id==="proj-cart"){p.cartera=e.target.value;save();}
});
document.getElementById("view-captura").addEventListener("click",e=>{
  const tog=e.target.closest("[data-toggle]");
  if(tog){tog.parentElement.classList.toggle("collapsed");return;}
  if(e.target.closest("#proj-del")){
    const p=state.projects.find(x=>x.id===current);if(!p)return;
    if(!confirm(`¿Eliminar el proyecto “${p.nombre}” y sus capturas?`))return;
    state.projects=state.projects.filter(x=>x.id!==current);
    current=state.projects[0]?state.projects[0].id:null;save();render();toast("Proyecto eliminado");}
});
function svcOf(id){for(const sk of SK){if(state.catalog[sk].indicadores.some(i=>i.id===id))return sk;}return"S1";}

/* ===================== Delegación: Catálogo ===================== */
document.getElementById("view-catalogo").addEventListener("input",e=>{
  const t=e.target;
  if(t.dataset.svcname!=null){state.catalog[t.dataset.svcname].nombre=t.value;save();renderHeader();}
  else if(t.dataset.rename!=null){const[sk,id]=t.dataset.rename.split("|");
    const i=state.catalog[sk].indicadores.find(x=>x.id===id);if(i){i.nombre=t.value;save();}}
});
document.getElementById("view-catalogo").addEventListener("click",e=>{
  const tg=e.target.closest("[data-toggle-grupo]");
  if(tg){const[sk,id]=tg.dataset.toggleGrupo.split("|");
    const i=state.catalog[sk].indicadores.find(x=>x.id===id);
    if(i){i.grupo=i.grupo==="prod"?"res":"prod";save();renderCatalogo();renderHeader();}return;}
  const del=e.target.closest("[data-delind]");
  if(del){const[sk,id]=del.dataset.delind.split("|");
    if(!confirm("¿Quitar este indicador de todos los proyectos?"))return;
    state.catalog[sk].indicadores=state.catalog[sk].indicadores.filter(x=>x.id!==id);
    state.projects.forEach(p=>{delete p.valores[id];});save();renderCatalogo();renderHeader();toast("Indicador eliminado");return;}
  const add=e.target.closest("[data-addind]");
  if(add){const sk=add.dataset.addind;const inp=document.querySelector(`[data-newind="${sk}"]`);
    const n=inp.value.trim();if(!n)return;
    state.catalog[sk].indicadores.push({id:uid(),nombre:n,grupo:"prod"});
    inp.value="";save();renderCatalogo();renderHeader();toast("Indicador agregado");}
});
document.getElementById("view-catalogo").addEventListener("keydown",e=>{
  if(e.key==="Enter"&&e.target.dataset.newind!=null){e.preventDefault();
    document.querySelector(`[data-addind="${e.target.dataset.newind}"]`).click();}
});

/* ===================== Init ===================== */
if(!storageOK)document.getElementById("banner").classList.add("show");
show("tablero");
</script>
</body>
</html>
