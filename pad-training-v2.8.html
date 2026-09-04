<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover, maximum-scale=1">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="default">
<meta name="apple-mobile-web-app-title" content="Pad Training">
<link id="touchIcon" rel="apple-touch-icon" href="">
<link id="manifestLink" rel="manifest" href="">
<title>Pad Training</title>
<style>
:root{
  --snow:#FCFAFA; --steel:#C8D3D5; --mist:#A4B8C4; --teal:#6E8387;
  --ink:#22292B; --ink-soft:#5A686C; --line:#E4EAEB;
  --green:#4F8A5B; --amber:#C08A3E; --red:#B4544A;
  --warn-bg:#F7EFE6; --warn-text:#8A6A3E; --warn-border:#E8D5BE;
  --surface:#fff; --surface-soft:#F7F9F9;
  --sig-g-bg:#F0F6F1; --sig-g-bd:#CFE3D3;
  --sig-a-bg:#FBF4E9; --sig-a-bd:#EEDDC2;
  --sig-r-bg:#FAEDEB; --sig-r-bd:#EFD2CE;
  --chrome-94:rgba(252,250,250,.94); --chrome-96:rgba(252,250,250,.96);
  --accent:var(--teal);
  --safe-b:env(safe-area-inset-bottom,0px);
}
:root[data-theme="dark"]{
  --snow:#181D1F; --steel:#2F3A3D; --mist:#5C6F76;
  --ink:#ECEEEE; --ink-soft:#9BABB0; --line:#333D40;
  --warn-bg:#332C1F; --warn-text:#D9B074; --warn-border:#4A3E28;
  --surface:#242B2D; --surface-soft:#2C3436;
  --sig-g-bg:#1C2E22; --sig-g-bd:#2C4A36;
  --sig-a-bg:#332B1C; --sig-a-bd:#4A3D24;
  --sig-r-bg:#331F1D; --sig-r-bd:#4A2D29;
  --chrome-94:rgba(24,29,31,.94); --chrome-96:rgba(24,29,31,.96);
}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
html,body{margin:0;padding:0}
body{
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Arial,sans-serif;
  background:var(--snow); color:var(--ink);
  font-size:16px; line-height:1.45;
  -webkit-text-size-adjust:100%;
}
button{font-family:inherit;font-size:inherit;cursor:pointer;border:none;background:none;color:inherit}
input,select{font-family:inherit;font-size:16px}

/* ---------- Splash ---------- */
#splash{position:fixed;inset:0;background:var(--snow);display:flex;flex-direction:column;
  align-items:center;justify-content:center;z-index:100;transition:opacity .45s}
#splash.gone{opacity:0;pointer-events:none}
.logo{width:76px;height:76px;border-radius:22px;object-fit:cover;display:block}
.logo-sub{margin-top:14px;color:var(--ink-soft);font-size:14px;letter-spacing:.08em}

/* ---------- Lock ---------- */
#lock{position:fixed;inset:0;background:var(--snow);z-index:90;display:none;
  flex-direction:column;align-items:center;justify-content:center;gap:20px;padding:24px}
#lock.on{display:flex}
.pin-dots{display:flex;gap:12px}
.pin-dot{width:13px;height:13px;border-radius:50%;border:1.5px solid var(--mist)}
.pin-dot.f{background:var(--accent);border-color:var(--accent)}
.pin-pad{display:grid;grid-template-columns:repeat(3,68px);gap:14px;margin-top:8px}
.pin-key{height:68px;border-radius:50%;background:var(--surface);border:1px solid var(--line);
  font-size:24px;font-weight:500;display:flex;align-items:center;justify-content:center}
.pin-key:active{background:var(--steel)}
.pin-key.blank{background:none;border:none}
.shake{animation:sh .4s}
@keyframes sh{25%{transform:translateX(-8px)}75%{transform:translateX(8px)}}

/* ---------- Chrome ---------- */
header{position:sticky;top:0;z-index:40;background:var(--chrome-94);
  backdrop-filter:saturate(180%) blur(12px);border-bottom:1px solid var(--line);
  padding:calc(env(safe-area-inset-top,0px) + 10px) 16px 10px;
  display:flex;align-items:center;gap:12px;min-height:52px}
header h1{font-size:17px;font-weight:600;margin:0;flex:1;letter-spacing:-.01em}
.icon-btn{width:38px;height:38px;border-radius:11px;display:flex;align-items:center;
  justify-content:center;font-size:19px;color:var(--accent);flex:none}
.icon-btn:active{background:var(--steel)}
main{padding:16px 16px calc(94px + var(--safe-b))}
.view{display:none}.view.on{display:block}

nav{position:fixed;bottom:0;left:0;right:0;z-index:40;display:flex;
  background:var(--chrome-96);backdrop-filter:saturate(180%) blur(12px);
  border-top:1px solid var(--line);padding-bottom:var(--safe-b)}
nav button{flex:1;padding:9px 4px 8px;display:flex;flex-direction:column;align-items:center;
  gap:3px;font-size:10.5px;color:var(--ink-soft);letter-spacing:.01em}
nav button .ic{font-size:20px;line-height:1}
nav button.on{color:var(--accent);font-weight:600}

/* ---------- Cards ---------- */
.card{background:var(--surface);border:1px solid var(--line);border-radius:15px;padding:15px;margin-bottom:11px}
.card.tap:active{background:var(--surface-soft)}
.row{display:flex;align-items:center;gap:12px}
.grow{flex:1;min-width:0}
.t{font-weight:600;font-size:15.5px;letter-spacing:-.01em}
.s{font-size:13px;color:var(--ink-soft);margin-top:3px}
.xs{font-size:11.5px;color:var(--ink-soft)}
.pill{display:inline-block;padding:3px 9px;border-radius:999px;background:var(--steel);
  font-size:11px;font-weight:600;color:var(--accent)}
.sec{font-size:11.5px;font-weight:700;color:var(--ink-soft);letter-spacing:.06em;
  margin:22px 0 9px}
.sec:first-child{margin-top:2px}
.empty{text-align:center;padding:44px 22px;color:var(--ink-soft)}
.empty .big{font-size:38px;margin-bottom:10px}

/* ---------- Buttons ---------- */
.btn{display:block;width:100%;padding:14px;border-radius:13px;background:var(--accent);
  color:#fff;font-weight:600;font-size:15.5px;text-align:center}
.btn:active{opacity:.82}
.btn.ghost{background:var(--surface);color:var(--accent);border:1.5px solid var(--accent)}
.btn.sm{padding:10px;font-size:14px}
.btn[disabled]{opacity:.4;pointer-events:none}

/* ---------- Signal ---------- */
.signal{border-radius:15px;padding:15px;margin-bottom:13px;border:1px solid}
.signal.g{background:var(--sig-g-bg);border-color:var(--sig-g-bd)}
.signal.a{background:var(--sig-a-bg);border-color:var(--sig-a-bd)}
.signal.r{background:var(--sig-r-bg);border-color:var(--sig-r-bd)}
.signal .hd{display:flex;align-items:center;gap:9px;font-weight:700;font-size:14.5px}
.dot{width:11px;height:11px;border-radius:50%;flex:none}
.signal.g .dot{background:var(--green)} .signal.g .hd{color:var(--green)}
.signal.a .dot{background:var(--amber)} .signal.a .hd{color:var(--amber)}
.signal.r .dot{background:var(--red)}   .signal.r .hd{color:var(--red)}
.signal .body{margin-top:8px;font-size:13.5px;line-height:1.5}
.signal ul{margin:7px 0 0;padding-left:17px;font-size:13px}
.signal li{margin-bottom:3px}

/* ---------- Inputs ---------- */
.field{margin-bottom:15px}
.lab{font-size:12.5px;font-weight:600;color:var(--ink-soft);margin-bottom:6px;display:block}
.inp{width:100%;padding:12px 13px;border:1.5px solid var(--line);border-radius:11px;
  background:var(--surface);color:var(--ink);font-size:16px;outline:none}
.inp:focus{border-color:var(--mist)}
.inp.mini{padding:10px 8px;text-align:center;font-weight:600}
select.inp{-webkit-appearance:none;appearance:none;
  background-image:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='8'><path d='M1 1l5 5 5-5' stroke='%235A686C' stroke-width='2' fill='none'/></svg>");
  background-repeat:no-repeat;background-position:right 13px center}
:root[data-theme="dark"] select.inp{
  background-image:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='8'><path d='M1 1l5 5 5-5' stroke='%239BABB0' stroke-width='2' fill='none'/></svg>");}

/* scale buttons (check-in) */
.scale{display:flex;gap:6px}
.scale button{flex:1;padding:11px 0;border-radius:10px;border:1.5px solid var(--line);
  background:var(--surface);font-weight:600;font-size:15px;color:var(--ink-soft)}
.scale button.on{background:var(--accent);border-color:var(--accent);color:#fff}

/* RPE */
.rpe{display:flex;gap:5px}
.rpe button{flex:1;padding:9px 0;border-radius:9px;border:1.5px solid var(--line);
  background:var(--surface);font-weight:600;font-size:14px;color:var(--ink-soft)}
.rpe button.on{background:var(--accent);border-color:var(--accent);color:#fff}

/* ---------- Set rows ---------- */
.exc{background:var(--surface);border:1px solid var(--line);border-radius:15px;margin-bottom:11px;overflow:hidden}
.exc.warn{border-color:var(--warn-border)}
.exc-h{padding:13px 14px;display:flex;align-items:flex-start;gap:10px}
.exc.warn .exc-h{background:var(--warn-bg)}
.exc-h .n{width:23px;height:23px;border-radius:7px;background:var(--steel);color:var(--accent);
  font-size:11.5px;font-weight:700;display:flex;align-items:center;justify-content:center;flex:none;margin-top:1px}
.exc-b{padding:0 14px 13px;border-top:1px solid var(--line);display:none}
.exc.open .exc-b{display:block}
.presc{font-size:12px;color:var(--ink-soft);padding:9px 0 11px;line-height:1.5}
.setrow{border-top:1px solid var(--line);padding:11px 0}
.setrow:first-of-type{border-top:none}
.setlab{font-size:11.5px;font-weight:700;color:var(--ink-soft);margin-bottom:7px;
  display:flex;align-items:center;gap:8px}
.grid{display:grid;gap:7px}
.g2{grid-template-columns:1fr 1fr}
.g3{grid-template-columns:1fr 1fr 1fr}
.unit{font-size:10.5px;color:var(--ink-soft);text-align:center;margin-top:3px}
.side-tag{padding:2px 7px;border-radius:6px;background:var(--steel);color:var(--accent);
  font-size:10px;font-weight:700}
.copy-btn{margin-left:auto;padding:4px 9px;border-radius:7px;border:1px solid var(--mist);
  color:var(--accent);font-size:11px;font-weight:600}
.copy-btn:active{background:var(--steel)}
.saved{font-size:11px;color:var(--green);font-weight:600}
.addset{width:100%;padding:9px;border-radius:9px;border:1.5px dashed var(--line);
  color:var(--ink-soft);font-size:12.5px;font-weight:600;margin-top:9px}
.addset:active{background:var(--surface-soft)}
.donebar{height:3px;background:var(--line);border-radius:2px;overflow:hidden;margin-top:9px}
.donebar i{display:block;height:100%;background:var(--accent);border-radius:2px;transition:width .25s}

/* ---------- History ---------- */
.hist{display:flex;gap:8px;overflow-x:auto;padding:2px 0 4px;-webkit-overflow-scrolling:touch}
.hcol{flex:none;min-width:74px;background:var(--surface-soft);border-radius:11px;padding:9px 8px;text-align:center}
.hcol .d{font-size:10px;color:var(--ink-soft)}
.hcol .v{font-size:15px;font-weight:700;margin-top:3px}
.hcol .r{font-size:10.5px;color:var(--ink-soft);margin-top:1px}
.asym{margin-top:9px;padding:9px 11px;border-radius:10px;font-size:12.5px;font-weight:600}
.asym.ok{background:var(--sig-g-bg);color:var(--green)}
.asym.no{background:var(--sig-r-bg);color:var(--red)}
.spark{display:flex;align-items:flex-end;gap:3px;height:38px;margin-top:9px}
.spark i{flex:1;background:var(--mist);border-radius:2px 2px 0 0;min-height:3px}
.spark i.last{background:var(--accent)}

/* ---------- Sheet ---------- */
.sheet-bg{position:fixed;inset:0;background:rgba(34,41,43,.42);z-index:60;display:none}
.sheet-bg.on{display:block}
.sheet{position:fixed;left:0;right:0;bottom:0;z-index:61;background:var(--snow);
  border-radius:20px 20px 0 0;padding:8px 16px calc(24px + var(--safe-b));
  transform:translateY(100%);transition:transform .28s cubic-bezier(.3,.9,.4,1);
  max-height:88vh;overflow-y:auto;-webkit-overflow-scrolling:touch}
.sheet.on{transform:translateY(0)}
.handle{width:38px;height:4px;border-radius:2px;background:var(--steel);margin:6px auto 14px}
.sheet h2{font-size:17px;margin:0 0 14px;font-weight:600}

.toast{position:fixed;left:50%;transform:translateX(-50%) translateY(20px);
  bottom:calc(84px + var(--safe-b));background:var(--ink);color:var(--snow);
  padding:11px 18px;border-radius:11px;font-size:13.5px;font-weight:500;z-index:80;
  opacity:0;transition:all .25s;pointer-events:none;max-width:88%;text-align:center}
.toast.on{opacity:1;transform:translateX(-50%) translateY(0)}
.note{font-size:12px;color:var(--ink-soft);line-height:1.5;background:var(--surface-soft);
  padding:11px 13px;border-radius:11px;margin-bottom:12px}
.note.warn{background:var(--warn-bg)}
.refrow{display:flex;gap:11px;align-items:flex-start;padding:11px 14px;border-top:1px solid var(--line)}
.refrow:first-child{border-top:none}
.refrow .ck{width:23px;height:23px;border-radius:7px;border:1.5px solid var(--mist);
  display:flex;align-items:center;justify-content:center;font-size:13px;color:#fff;flex:none;margin-top:1px}
.refrow.on .ck{background:var(--accent);border-color:var(--accent)}
.refrow.on .t{color:var(--ink-soft);text-decoration:line-through}
.refrow:active{background:var(--surface-soft)}
.del-btn{margin-left:auto;width:24px;height:24px;border-radius:7px;color:var(--ink-soft);
  font-size:12px;border:1px solid var(--line);display:flex;align-items:center;justify-content:center}
.del-btn:active{background:var(--steel)}
.mini-btn{width:32px;height:28px;border-radius:8px;border:1px solid var(--line);
  color:var(--accent);font-size:14px;background:var(--surface)}
.mini-btn:active{background:var(--steel)}
.rpe-box{margin-top:14px;padding:12px;border-radius:12px;background:var(--surface-soft);border:1px solid var(--line)}
.rpe-day{border-color:var(--mist)}

.del-btn{margin-left:auto;width:34px;height:32px;border-radius:9px;color:var(--red);
  font-size:15px;border:1px solid var(--line);display:flex;align-items:center;justify-content:center;background:var(--surface)}
.del-btn:active{background:var(--sig-r-bg);border-color:var(--red)}
.setrow.is-done{opacity:.62}
.exc.complete .exc-h .n{background:var(--accent);color:#fff}

.week{padding:16px 15px 13px}
.wk-nav{display:flex;gap:6px;margin-top:9px}
.wk-nav button{width:30px;height:26px;border-radius:8px;border:1px solid var(--line);
  color:var(--accent);font-size:14px;background:var(--surface)}
.wk-nav button:not([disabled]):active{background:var(--steel)}
.wk-nav button[disabled]{opacity:.3}
.wk-nav button:not(:first-child):not(:last-child){width:auto;padding:0 11px;font-size:12px;font-weight:600}
.wk-labels{display:flex;gap:5px;margin-top:14px;border-top:1px solid var(--line);padding-top:12px}
.wk-l{flex:1;text-align:center;padding:6px 0;border-radius:9px;cursor:pointer}
.wk-l span{display:block;font-size:10.5px;font-weight:700;color:var(--ink-soft)}
.wk-l i{display:block;font-style:normal;font-size:13px;font-weight:600;margin-top:2px}
.wk-l.done{background:var(--accent)}
.wk-l.done span,.wk-l.done i{color:#fff}
.wk-l.manual{background:var(--mist)}
.wk-l.manual span,.wk-l.manual i{color:#fff}
.wk-l.today{border:1.5px dashed var(--mist)}
.wk-l.missed i{color:var(--line)}
.wk-l:active{opacity:.7}
.metric-v{font-size:22px;font-weight:700;letter-spacing:-.02em;line-height:1.1}
.delta{font-weight:700;margin-left:3px}
.delta.up{color:var(--green)} .delta.down{color:var(--red)}
.mgrid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:11px}
.mtile{padding:10px 6px;margin-bottom:0;text-align:center;overflow:hidden}
.mtile .t{font-size:11px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.mtile .metric-v{font-size:17px;margin-top:2px}
.mtile .xs{margin-top:1px}
.mtile .spark{height:18px;margin-top:5px;gap:2px}
.mtile-add{display:flex;align-items:center;justify-content:center;
  border:1.5px dashed var(--line);background:none;color:var(--mist);font-size:24px;min-height:82px}
.photo-strip{display:flex;gap:8px;overflow-x:auto;-webkit-overflow-scrolling:touch;padding:1px}
.photo-strip img{width:74px;height:74px;object-fit:cover;border-radius:11px;flex:none}
.photo-add{width:74px;height:74px;border-radius:11px;border:1.5px dashed var(--line);
  color:var(--mist);font-size:26px;flex:none;background:var(--surface)}
.photo-add:active{background:var(--surface-soft)}
.rpe-in{text-align:center;font-weight:700;font-size:20px;padding:12px}
.rpe-big{font-size:30px;font-weight:700;color:var(--accent);line-height:1;letter-spacing:-.02em}


</style>
</head>
<body>

<div id="splash"><img class="logo" id="splashLogo" alt="Pad Training"><div class="logo-sub" id="splashSub">PAD TRAINING</div></div>

<div id="lock">
  <img class="logo" id="lockLogo" alt="Pad Training" style="width:56px;height:56px;border-radius:17px">
  <div id="lockMsg" style="font-size:14px;color:var(--ink-soft)"></div>
  <div class="pin-dots" id="pinDots"></div>
  <div class="pin-pad" id="pinPad"></div>
</div>

<header>
  <button class="icon-btn" id="backBtn" style="display:none">‹</button>
  <img id="homeLogo" alt="" style="width:30px;height:30px;border-radius:9px;object-fit:cover;flex:none;display:none">
  <h1 id="title">Pad Training</h1>
  <button class="icon-btn" id="actBtn" style="display:none">⋯</button>
</header>

<main>
  <div class="view on" id="v-home"></div>
  <div class="view" id="v-session"></div>
  <div class="view" id="v-progress"></div>
  <div class="view" id="v-tests"></div>
  <div class="view" id="v-settings"></div>
</main>

<nav>
  <button class="on" data-nav="home"><span class="ic">◇</span><span id="nHome">Hoy</span></button>
  <button data-nav="progress"><span class="ic">◈</span><span id="nProg">Progreso</span></button>
  <button data-nav="tests"><span class="ic">◎</span><span id="nTests">Expectations</span></button>
  <button data-nav="settings"><span class="ic">⚙</span><span id="nSet">Ajustes</span></button>
</nav>

<div class="sheet-bg" id="sheetBg"></div>
<div class="sheet" id="sheet"><div class="handle"></div><div id="sheetC"></div></div>
<input type="file" id="photoInput" accept="image/*" style="display:none">
<div class="toast" id="toast"></div>

<script>
"use strict";

/* ============================================================
   i18n
   ============================================================ */
const I18N={
es:{app:"Pad Training",guestUser:"usuario",today:"Hoy",progress:"Progreso",settings:"Ajustes",
 pickDay:"Elige la sesión de hoy",start:"Empezar sesión",resume:"Continuar sesión",
 checkin:"Check-in previo",checkinSub:"Cuatro datos antes de entrenar. Definen la señal de carga.",
 sleep:"Sueño anoche",heel:"Dolor de talón al despertar",groin:"Dolor de ingle",energy:"Energía general",
 sleepH:"1 = fatal · 5 = perfecto",painH:"0 = sin dolor · 5 = mucho dolor",energyH:"1 = vacío · 5 = pleno",
 toSession:"Ver la sesión",green:"Sube la carga",amber:"Mantén la carga",red:"Baja la carga",
 setN:"Serie",left:"Izq",right:"Der",sameL:"= Izq",addSet:"Añadir serie",
 kg:"kg",reps:"reps",secs:"seg",m:"metros",contacts:"contactos",time:"tiempo (s)",min:"minutos",rpe:"RPE",
 done:"Hecho",saved:"Guardado",finish:"Terminar sesión",finished:"Sesión guardada",
 noHist:"Sin registros todavía",lastLoads:"Cargas anteriores",asymOk:"Simetría correcta",
 asymNo:"Asimetría alta",pickEx:"Elige un ejercicio",volume:"Volumen",
 lang:"Idioma",accent:"Color",name:"Tu nombre",pin:"Bloqueo con PIN",
 pinOn:"Pedir PIN al abrir",setPin:"Definir PIN",resetPin:"Restablecer PIN",
 backup:"Descargar copia de seguridad",restore:"Restaurar desde copia",
 exportCsv:"Exportar datos (CSV)",
 exportCsvNote:"Descarga 3 archivos CSV (sesiones, métricas, expectations) para abrir en Excel, Numbers o Google Sheets. No sirven para restaurar: para eso usa la copia de seguridad.",
 csvDate:"Fecha",csvProgram:"Programa",csvDay:"Día",csvExercise:"Ejercicio",csvSet:"Serie",csvSide:"Lado",csvDone:"Hecho",csvMetric:"Métrica",csvValue:"Valor",csvUnit:"Unidad",csvTest:"Test",
 exDeleted:"ejercicio eliminado",progDeleted:"programa eliminado",dayDeleted:"día eliminado",
 enterPin:"Introduce tu PIN",wrongPin:"PIN incorrecto",newPin:"Nuevo PIN de 4 dígitos",
 repeatPin:"Repite el PIN",pinSet:"PIN activado",pinOff:"PIN desactivado",
 typeReset:"Escribe BORRAR para confirmar",resetWarn:"Restablecer el PIN borra TODOS tus datos. No hay copia en ningún servidor.",
 noSess:"Aún no has entrenado",noSessSub:"Elige una sesión para empezar.",
 progSub:"Toca un ejercicio para ver su histórico.",sessions:"sesiones",
 discard:"Descartar sesión",nothing:"Nada que guardar",confDiscard:"¿Descartar esta sesión sin guardarla?",editDay:"Editar ejercicios",editNote:"Renombrar conserva el histórico. Ocultar un ejercicio no borra sus registros: puedes restaurarlo cuando quieras.",edit:"Editar",hide:"Ocultar",restore:"Restaurar",hidden:"Ejercicio oculto",restored:"Restaurado",addEx:"Añadir ejercicio",resetDay:"Restaurar el día original",confReset:"Esto devuelve el día a los ejercicios originales del programa. Tus registros no se borran. ¿Seguir?",exName:"Nombre",exPresc:"Prescripción",exType:"Tipo de registro",exSides:"Cómo lo registras",oneEntry:"Entrada única",twoSides:"Izq y der",sidesHelp:"Dos lados te da el cálculo de asimetría. Entrada única es más rápido de escribir.",save:"Guardar",needName:"Ponle un nombre",doneMark:"Hecho",undo:"Deshacer",saveEx:"Guardar ejercicio",exSaved:"Ejercicio guardado",delSet:"Borrar serie",setDeleted:"Serie borrada",cleared:"Serie vaciada",rpeRange:"El RPE va de 1 a 10",thisWeek:"Esta semana",lastWeek:"Semana pasada",of:"de",ringHelp:"Se rellena sola al terminar una sesión. Toca un día para marcarlo a mano.",autoDay:"Ese día ya tiene una sesión registrada",inProgress:"En curso",metrics:"Métricas",addMetric:"Añadir métrica",editMetric:"Editar métrica",delMetric:"Borrar métrica",confDelMetric:"Se borra la métrica y todos sus valores. ¿Seguir?",mName:"Nombre",mUnit:"Unidad",mCad:"Cada cuántos días la mides",mCadHelp:"Deja vacío si no quieres recordatorio. 42 = cada 6 semanas.",newValue:"Nuevo valor",addValue:"Añadir valor",needValue:"Escribe un valor",date:"Fecha",history:"Histórico",noData:"Sin datos",dueNow:"Toca medirla",daysLeft:"días para la próxima",photos:"Fotos de progreso",photoHelp:"Opcional. Se guardan solo en este teléfono, reducidas para ocupar poco.",photoAdded:"Foto añadida",photoFull:"No cabe: borra alguna foto antigua",delPhoto:"Borrar foto",rpeEx:"RPE del ejercicio",rpeHelp:"Uno por ejercicio, no por serie. De 1 a 10, admite decimales (7,5).",rpeDay:"RPE acumulado del día",rpeNone:"Marca el RPE de al menos un ejercicio.",rpeCarry:"Este promedio se usa para calcular la señal de tu próxima sesión.",exercises:"ejercicios",nutrition:"Nutrición y descanso del día",prescribed:"Prescrito",
 tabTests:"Expectations",testsSub:"Toca un test para añadir un valor, fijar un objetivo o ver su histórico.",
 addTest:"Añadir test",editTest:"Editar test",delTest:"Borrar test",
 delTestConfirm:"Se borra el test y todo su histórico. ¿Seguir?",goal:"Objetivo",remaining:"Falta",
 manual:"manual",useCalc:"Usar calculado",
 bmiNote:"El IMC se calcula solo, a partir de tu peso corporal y tu altura (1,73 m). Añade valores de peso para que aparezcan aquí.",
 warnFascia:"Fascia plantar: si el talón duele al despertar, no hagas este test. Sigue el protocolo Rathleff.",
 exercise:"Ejercicio",coopMeters:"Metros en 12 minutos",cmH:"Altura (cm)",cmL:"Altura izquierda (cm)",
 cmR:"Altura derecha (cm)",cmLong:"Distancia (cm)",cmNoLoad:"Sin lastre (cm)",cmLoad10:"Con 10% del peso (cm)",
 cmLoad20:"Con 20% del peso (cm)",cmLoad30:"Con 30% del peso (cm)",sprintTotal:"Tiempo total 30 m (s)",
 sprintSplit:"Parcial 20-30 m (s)",power:"Potencia",asymmetry:"Asimetría",elastic:"Índice elástico",
 maxSpeedKmh:"Vel. máxima",avgSpeed:"Vel. media",vsStraight:"Dif. vs recto",
 dropAt10:"Caída al 10%",dropAt20:"Caída al 20%",dropAt30:"Caída al 30%",meters:"Metros",
 programs:"Programas",activePill:"Activo",addProgram:"Añadir programa",editProgram:"Editar programa",
 progName:"Nombre del programa",progNote:"Nota (opcional)",
 confDuplicate:"Se duplica el programa con IDs de ejercicio nuevos: su histórico será independiente. ¿Seguir?",
 duplicated:"Programa duplicado",
 confDelProgram:"Se borra el programa. Los registros históricos asociados se conservan pero quedarán huérfanos. ¿Seguir?",
 maxPrograms:"Máximo 10 programas",minPrograms:"Debe quedar al menos un programa",
 copySuffix:" (copia)",noDays:"Este programa todavía no tiene días",
 allPrograms:"Ver todos los programas",onlyActiveProg:"Solo el programa activo",
 confSwitchProg:"Tienes una sesión sin terminar de otro programa. ¿La descartas al cambiar?",
 noOriginal:"Este programa no tiene versión original para restaurar",
 daysWord:"días",manageProg:"Gestionar programas",
 noProgProgress:"Sin progreso registrado en este programa",
 otherProgHint:"registradas en otros programas. Toca \"Ver todos los programas\" para verlas.",
 dayName:"Nombre del día",dayCode:"Código (opcional)",dayTitle:"Título de la sesión",
 dayDow:"Día de la semana",addDay:"Añadir día",
 confDelDay:"Se borra el día. Los registros históricos de sus ejercicios se conservan pero quedarán huérfanos. ¿Seguir?",
 addBlock:"Añadir bloque",blockName:"Nombre del bloque",blockNormal:"Normal",blockRefOpt:"Referencia (checklist)",
 confDelBlock:"Se borra el bloque y sus ejercicios. El histórico se conserva pero queda huérfano. ¿Seguir?",
 noBlocks:"Este día todavía no tiene bloques",delDay:"Borrar día",blocksWord:"bloques",logoPick:"Elige el logo de la app",logoNote:"El icono de la pantalla de inicio se actualiza la próxima vez que añadas la app. Si ya la añadiste, quítala y vuelve a añadirla.",
 theme:"Tema",themeLight:"Claro",themeDark:"Oscuro",
 manageMetrics:"Gestionar métricas",noCustomMetrics:"Aún no has añadido métricas propias."},
en:{app:"Pad Training",guestUser:"user",today:"Today",progress:"Progress",settings:"Settings",
 pickDay:"Choose today's session",start:"Start session",resume:"Resume session",
 checkin:"Pre-session check-in",checkinSub:"Four inputs before training. They set the load signal.",
 sleep:"Sleep last night",heel:"Heel pain on waking",groin:"Groin pain",energy:"Overall energy",
 sleepH:"1 = terrible · 5 = perfect",painH:"0 = none · 5 = severe",energyH:"1 = empty · 5 = full",
 toSession:"View session",green:"Add load",amber:"Hold load",red:"Reduce load",
 setN:"Set",left:"L",right:"R",sameL:"= L",addSet:"Add set",
 kg:"kg",reps:"reps",secs:"sec",m:"metres",contacts:"contacts",time:"time (s)",min:"minutes",rpe:"RPE",
 done:"Done",saved:"Saved",finish:"Finish session",finished:"Session saved",
 noHist:"No records yet",lastLoads:"Previous loads",asymOk:"Symmetry fine",
 asymNo:"High asymmetry",pickEx:"Pick an exercise",volume:"Volume",
 lang:"Language",accent:"Colour",name:"Your name",pin:"PIN lock",
 pinOn:"Ask for PIN on open",setPin:"Set PIN",resetPin:"Reset PIN",
 backup:"Download backup",restore:"Restore from backup",
 exportCsv:"Export data (CSV)",
 exportCsvNote:"Downloads 3 CSV files (sessions, metrics, expectations) to open in Excel, Numbers or Google Sheets. Not for restoring data: use the backup for that.",
 csvDate:"Date",csvProgram:"Programme",csvDay:"Day",csvExercise:"Exercise",csvSet:"Set",csvSide:"Side",csvDone:"Done",csvMetric:"Metric",csvValue:"Value",csvUnit:"Unit",csvTest:"Test",
 exDeleted:"exercise deleted",progDeleted:"programme deleted",dayDeleted:"day deleted",
 enterPin:"Enter your PIN",wrongPin:"Wrong PIN",newPin:"New 4-digit PIN",
 repeatPin:"Repeat PIN",pinSet:"PIN enabled",pinOff:"PIN disabled",
 typeReset:"Type DELETE to confirm",resetWarn:"Resetting the PIN erases ALL your data. There is no server copy.",
 noSess:"No training yet",noSessSub:"Pick a session to start.",
 progSub:"Tap an exercise to see its history.",sessions:"sessions",
 discard:"Discard session",nothing:"Nothing to save",confDiscard:"Discard this session without saving?",editDay:"Edit exercises",editNote:"Renaming keeps the history. Hiding an exercise does not delete its records: you can restore it any time.",edit:"Edit",hide:"Hide",restore:"Restore",hidden:"Exercise hidden",restored:"Restored",addEx:"Add exercise",resetDay:"Restore original day",confReset:"This returns the day to the original programme exercises. Your records are kept. Continue?",exName:"Name",exPresc:"Prescription",exType:"Record type",exSides:"How you log it",oneEntry:"Single entry",twoSides:"L and R",sidesHelp:"Two sides gives you the asymmetry figure. Single entry is faster to type.",save:"Save",needName:"Give it a name",doneMark:"Done",undo:"Undo",saveEx:"Save exercise",exSaved:"Exercise saved",delSet:"Delete set",setDeleted:"Set deleted",cleared:"Set cleared",rpeRange:"RPE runs from 1 to 10",thisWeek:"This week",lastWeek:"Last week",of:"of",ringHelp:"Fills itself when you finish a session. Tap a day to mark it by hand.",autoDay:"That day already has a session",inProgress:"In progress",metrics:"Metrics",addMetric:"Add metric",editMetric:"Edit metric",delMetric:"Delete metric",confDelMetric:"This deletes the metric and all its values. Continue?",mName:"Name",mUnit:"Unit",mCad:"Measure every how many days",mCadHelp:"Leave empty for no reminder. 42 = every 6 weeks.",newValue:"New value",addValue:"Add value",needValue:"Enter a value",date:"Date",history:"History",noData:"No data",dueNow:"Due now",daysLeft:"days to next",photos:"Progress photos",photoHelp:"Optional. Stored on this phone only, resized to stay small.",photoAdded:"Photo added",photoFull:"Out of space: delete an old photo",delPhoto:"Delete photo",rpeEx:"Exercise RPE",rpeHelp:"One per exercise, not per set. 1 to 10, decimals allowed (7.5).",rpeDay:"Session RPE",rpeNone:"Set the RPE on at least one exercise.",rpeCarry:"This average feeds the signal for your next session.",exercises:"exercises",nutrition:"Nutrition and rest today",prescribed:"Prescribed",
 tabTests:"Expectations",testsSub:"Tap a test to add a value, set a goal, or see its history.",
 addTest:"Add test",editTest:"Edit test",delTest:"Delete test",
 delTestConfirm:"This deletes the test and all its history. Continue?",goal:"Goal",remaining:"Remaining",
 manual:"manual",useCalc:"Use calculated",
 bmiNote:"BMI is calculated automatically from your body weight and height (1.73 m). Add weight entries so they show up here.",
 warnFascia:"Plantar fascia: if your heel hurts on waking, skip this test. Follow the Rathleff protocol.",
 exercise:"Exercise",coopMeters:"Metres in 12 minutes",cmH:"Height (cm)",cmL:"Left height (cm)",
 cmR:"Right height (cm)",cmLong:"Distance (cm)",cmNoLoad:"No load (cm)",cmLoad10:"With 10% bodyweight (cm)",
 cmLoad20:"With 20% bodyweight (cm)",cmLoad30:"With 30% bodyweight (cm)",sprintTotal:"Total time 30 m (s)",
 sprintSplit:"20-30 m split (s)",power:"Power",asymmetry:"Asymmetry",elastic:"Elastic index",
 maxSpeedKmh:"Max speed",avgSpeed:"Avg speed",vsStraight:"Diff vs straight",
 dropAt10:"Drop at 10%",dropAt20:"Drop at 20%",dropAt30:"Drop at 30%",meters:"Metres",
 programs:"Programmes",activePill:"Active",addProgram:"Add programme",editProgram:"Edit programme",
 progName:"Programme name",progNote:"Note (optional)",
 confDuplicate:"This duplicates the programme with new exercise IDs: its history will be independent. Continue?",
 duplicated:"Programme duplicated",
 confDelProgram:"This deletes the programme. Its historical records are kept but become orphaned. Continue?",
 maxPrograms:"Maximum 10 programmes",minPrograms:"At least one programme must remain",
 copySuffix:" (copy)",noDays:"This programme has no days yet",
 allPrograms:"View all programmes",onlyActiveProg:"Active programme only",
 confSwitchProg:"You have an unfinished session from another programme. Discard it to switch?",
 noOriginal:"This programme has no original version to restore",
 daysWord:"days",manageProg:"Manage programmes",
 noProgProgress:"No progress recorded for this programme",
 otherProgHint:"recorded in other programmes. Tap \"View all programmes\" to see them.",
 dayName:"Day name",dayCode:"Code (optional)",dayTitle:"Session title",
 dayDow:"Day of the week",addDay:"Add day",
 confDelDay:"This deletes the day. Its exercises' historical records are kept but become orphaned. Continue?",
 addBlock:"Add block",blockName:"Block name",blockNormal:"Normal",blockRefOpt:"Reference (checklist)",
 confDelBlock:"This deletes the block and its exercises. History is kept but becomes orphaned. Continue?",
 noBlocks:"This day has no blocks yet",delDay:"Delete day",blocksWord:"blocks",logoPick:"Choose the app logo",logoNote:"The home screen icon updates the next time you add the app. If you already added it, remove it and add it again.",
 theme:"Theme",themeLight:"Light",themeDark:"Dark",
 manageMetrics:"Manage metrics",noCustomMetrics:"You haven't added any custom metrics yet."},
pl:{app:"Pad Training",guestUser:"użytkowniku",today:"Dziś",progress:"Postęp",settings:"Ustawienia",
 pickDay:"Wybierz dzisiejszy trening",start:"Zacznij trening",resume:"Wznów trening",
 checkin:"Check-in przed treningiem",checkinSub:"Cztery dane przed treningiem. Ustalają sygnał obciążenia.",
 sleep:"Sen ostatniej nocy",heel:"Ból pięty po przebudzeniu",groin:"Ból pachwiny",energy:"Ogólna energia",
 sleepH:"1 = fatalnie · 5 = idealnie",painH:"0 = brak · 5 = silny",energyH:"1 = pusto · 5 = pełnia",
 toSession:"Zobacz trening",green:"Zwiększ obciążenie",amber:"Utrzymaj obciążenie",red:"Zmniejsz obciążenie",
 setN:"Seria",left:"L",right:"P",sameL:"= L",addSet:"Dodaj serię",
 kg:"kg",reps:"powt.",secs:"sek",m:"metry",contacts:"kontakty",time:"czas (s)",min:"minuty",rpe:"RPE",
 done:"Gotowe",saved:"Zapisano",finish:"Zakończ trening",finished:"Trening zapisany",
 noHist:"Brak zapisów",lastLoads:"Poprzednie obciążenia",asymOk:"Symetria dobra",
 asymNo:"Duża asymetria",pickEx:"Wybierz ćwiczenie",volume:"Objętość",
 lang:"Język",accent:"Kolor",name:"Twoje imię",pin:"Blokada PIN",
 pinOn:"Pytaj o PIN przy otwarciu",setPin:"Ustaw PIN",resetPin:"Zresetuj PIN",
 backup:"Pobierz kopię zapasową",restore:"Przywróć z kopii",
 exportCsv:"Eksportuj dane (CSV)",
 exportCsvNote:"Pobiera 3 pliki CSV (treningi, metryki, expectations) do otwarcia w Excelu, Numbers lub Arkuszach Google. Nie służą do przywracania danych: do tego użyj kopii zapasowej.",
 csvDate:"Data",csvProgram:"Program",csvDay:"Dzień",csvExercise:"Ćwiczenie",csvSet:"Seria",csvSide:"Strona",csvDone:"Wykonano",csvMetric:"Metryka",csvValue:"Wartość",csvUnit:"Jednostka",csvTest:"Test",
 exDeleted:"usunięte ćwiczenie",progDeleted:"usunięty program",dayDeleted:"usunięty dzień",
 enterPin:"Wpisz PIN",wrongPin:"Błędny PIN",newPin:"Nowy 4-cyfrowy PIN",
 repeatPin:"Powtórz PIN",pinSet:"PIN włączony",pinOff:"PIN wyłączony",
 typeReset:"Wpisz USUN aby potwierdzić",resetWarn:"Reset PIN-u usuwa WSZYSTKIE dane. Nie ma kopii na serwerze.",
 noSess:"Brak treningów",noSessSub:"Wybierz trening aby zacząć.",
 progSub:"Dotknij ćwiczenia aby zobaczyć historię.",sessions:"treningi",
 discard:"Odrzuć trening",nothing:"Nie ma co zapisać",confDiscard:"Odrzucić ten trening bez zapisu?",editDay:"Edytuj ćwiczenia",editNote:"Zmiana nazwy zachowuje historię. Ukrycie ćwiczenia nie usuwa zapisów: możesz je przywrócić.",edit:"Edytuj",hide:"Ukryj",restore:"Przywróć",hidden:"Ćwiczenie ukryte",restored:"Przywrócono",addEx:"Dodaj ćwiczenie",resetDay:"Przywróć oryginalny dzień",confReset:"To przywraca oryginalne ćwiczenia programu. Zapisy zostają. Kontynuować?",exName:"Nazwa",exPresc:"Zalecenie",exType:"Typ zapisu",exSides:"Jak zapisujesz",oneEntry:"Jeden wpis",twoSides:"L i P",sidesHelp:"Dwie strony dają wskaźnik asymetrii. Jeden wpis jest szybszy.",save:"Zapisz",needName:"Podaj nazwę",doneMark:"Zrobione",undo:"Cofnij",saveEx:"Zapisz ćwiczenie",exSaved:"Ćwiczenie zapisane",delSet:"Usuń serię",setDeleted:"Seria usunięta",cleared:"Seria wyczyszczona",rpeRange:"RPE od 1 do 10",thisWeek:"Ten tydzień",lastWeek:"Poprzedni tydzień",of:"z",ringHelp:"Wypełnia się po zakończeniu treningu. Dotknij dnia aby oznaczyć ręcznie.",autoDay:"Ten dzień ma już trening",inProgress:"W trakcie",metrics:"Metryki",addMetric:"Dodaj metrykę",editMetric:"Edytuj metrykę",delMetric:"Usuń metrykę",confDelMetric:"To usuwa metrykę i wszystkie wartości. Kontynuować?",mName:"Nazwa",mUnit:"Jednostka",mCad:"Co ile dni mierzysz",mCadHelp:"Zostaw puste bez przypomnienia. 42 = co 6 tygodni.",newValue:"Nowa wartość",addValue:"Dodaj wartość",needValue:"Wpisz wartość",date:"Data",history:"Historia",noData:"Brak danych",dueNow:"Czas zmierzyć",daysLeft:"dni do następnego",photos:"Zdjęcia postępu",photoHelp:"Opcjonalne. Tylko na tym telefonie, pomniejszone.",photoAdded:"Zdjęcie dodane",photoFull:"Brak miejsca: usuń stare zdjęcie",delPhoto:"Usuń zdjęcie",rpeEx:"RPE ćwiczenia",rpeHelp:"Jedno na ćwiczenie, nie na serię. Od 1 do 10, dozwolone dziesiętne (7,5).",rpeDay:"RPE treningu",rpeNone:"Ustaw RPE przy co najmniej jednym ćwiczeniu.",rpeCarry:"Ta średnia zasila sygnał następnego treningu.",exercises:"ćwiczenia",nutrition:"Żywienie i odpoczynek dziś",prescribed:"Zalecane",
 tabTests:"Expectations",testsSub:"Dotknij testu, aby dodać wartość, ustawić cel lub zobaczyć historię.",
 addTest:"Dodaj test",editTest:"Edytuj test",delTest:"Usuń test",
 delTestConfirm:"To usuwa test i całą jego historię. Kontynuować?",goal:"Cel",remaining:"Pozostało",
 manual:"ręcznie",useCalc:"Użyj obliczonego",
 bmiNote:"BMI liczy się automatycznie na podstawie masy ciała i wzrostu (1,73 m). Dodaj wpisy wagi, aby się tu pojawiły.",
 warnFascia:"Rozcięgno podeszwowe: jeśli pięta boli po przebudzeniu, nie wykonuj tego testu. Trzymaj się protokołu Rathleffa.",
 exercise:"Ćwiczenie",coopMeters:"Metry w 12 minut",cmH:"Wysokość (cm)",cmL:"Wysokość lewa (cm)",
 cmR:"Wysokość prawa (cm)",cmLong:"Odległość (cm)",cmNoLoad:"Bez obciążenia (cm)",cmLoad10:"Z 10% masy ciała (cm)",
 cmLoad20:"Z 20% masy ciała (cm)",cmLoad30:"Z 30% masy ciała (cm)",sprintTotal:"Czas całkowity 30 m (s)",
 sprintSplit:"Odcinek 20-30 m (s)",power:"Moc",asymmetry:"Asymetria",elastic:"Wskaźnik elastyczności",
 maxSpeedKmh:"Maks. prędkość",avgSpeed:"Śr. prędkość",vsStraight:"Różnica vs prosto",
 dropAt10:"Spadek przy 10%",dropAt20:"Spadek przy 20%",dropAt30:"Spadek przy 30%",meters:"Metry",
 programs:"Programy",activePill:"Aktywny",addProgram:"Dodaj program",editProgram:"Edytuj program",
 progName:"Nazwa programu",progNote:"Notatka (opcjonalnie)",
 confDuplicate:"To duplikuje program z nowymi ID ćwiczeń: jego historia będzie niezależna. Kontynuować?",
 duplicated:"Program zduplikowany",
 confDelProgram:"To usuwa program. Powiązane zapisy historyczne zostają, ale staną się osierocone. Kontynuować?",
 maxPrograms:"Maksymalnie 10 programów",minPrograms:"Musi zostać co najmniej jeden program",
 copySuffix:" (kopia)",noDays:"Ten program nie ma jeszcze dni",
 allPrograms:"Pokaż wszystkie programy",onlyActiveProg:"Tylko aktywny program",
 confSwitchProg:"Masz nieukończony trening z innego programu. Odrzucić go, aby przełączyć?",
 noOriginal:"Ten program nie ma oryginalnej wersji do przywrócenia",
 daysWord:"dni",manageProg:"Zarządzaj programami",
 noProgProgress:"Brak zarejestrowanego postępu w tym programie",
 otherProgHint:"zarejestrowanych w innych programach. Dotknij \"Pokaż wszystkie programy\", aby je zobaczyć.",
 dayName:"Nazwa dnia",dayCode:"Kod (opcjonalnie)",dayTitle:"Tytuł sesji",
 dayDow:"Dzień tygodnia",addDay:"Dodaj dzień",
 confDelDay:"To usuwa dzień. Zapisy historyczne jego ćwiczeń zostają, ale staną się osierocone. Kontynuować?",
 addBlock:"Dodaj blok",blockName:"Nazwa bloku",blockNormal:"Zwykły",blockRefOpt:"Referencyjny (checklista)",
 confDelBlock:"To usuwa blok i jego ćwiczenia. Historia zostaje, ale staje się osierocona. Kontynuować?",
 noBlocks:"Ten dzień nie ma jeszcze bloków",delDay:"Usuń dzień",blocksWord:"bloki",logoPick:"Wybierz logo aplikacji",logoNote:"Ikona na ekranie głównym zaktualizuje się przy następnym dodaniu aplikacji. Jeśli już ją dodałeś, usuń ją i dodaj ponownie.",
 theme:"Motyw",themeLight:"Jasny",themeDark:"Ciemny",
 manageMetrics:"Zarządzaj metrykami",noCustomMetrics:"Nie dodałeś jeszcze własnych metryk."}
};
let L="es";
const t=k=>(I18N[L]&&I18N[L][k])||I18N.es[k]||k;

/* ============================================================
   Storage
   ============================================================ */
const K="padtrain_v2";
const DEF={settings:{lang:"es",accent:"#6E8387",name:"",pinHash:"",pinOn:false,logoVariant:"1",theme:"light"},
           logs:[],draft:null,program:null,programs:null,activeProgramId:null,
           metrics:null,tests:null,photos:[],marks:{}};
let DB=load();
function load(){try{const r=localStorage.getItem(K);
  if(!r)return JSON.parse(JSON.stringify(DEF));
  return Object.assign(JSON.parse(JSON.stringify(DEF)),JSON.parse(r));}
  catch(e){return JSON.parse(JSON.stringify(DEF));}}
function save(){try{localStorage.setItem(K,JSON.stringify(DB));}catch(e){toast("No se pudo guardar");}}

/* ============================================================
   Program — cargado del Excel de Iván (Verano 360)
   type: load | bw | iso | dist | plyo | sprint | tech
   uni:true => registro izquierda/derecha
   ============================================================ */
const PROGRAM={id:"prog_verano360",name:"Verano 360",note:"",builtin:true,days:[
{id:"lun",day:"Lunes",code:"MD-5",title:"Tren inferior: fuerza máxima + core",
 blocks:[
 {n:"Calentamiento — RAMP",ref:true,ex:[
  {id:"lun_bici",name:"Bici",type:"tech",p:"continuo · 3 min"},
  {id:"lun_act",name:"Puente de glúteo · clamshell · monster walk",type:"bw",p:"2 × 12-15"},
  {id:"lun_mob",name:"Zancada con rotación · WGS · leg swings",type:"tech",p:"8 / lado · 3 min"},
  {id:"lun_ramp",name:"Series de aproximación (búlgara y landmine)",type:"load",p:"2-3 series · 8-10 / 5-6 / 3-4"}]},
 {n:"Trabajo principal",ex:[
  {id:"lun_bulg",name:"Sentadilla búlgara (RFE) con mancuernas",type:"load",uni:true,p:"4 × 6 / pierna · 2 min · RPE 7-8",
   w:"Carga ~85-90% del peso corporal por pierna. PARA si aparece dolor inguinal o testicular."},
  {id:"lun_land",name:"Landmine Squat",type:"load",p:"4 × 6-8 · 2 min · RPE 8",
   w:"EXHALA en el empuje: sin apnea máxima de Valsalva (presión sobre la malla)."},
  {id:"lun_slrdl",name:"Single-Leg RDL con mancuerna",type:"load",uni:true,p:"3 × 8-10 · 90 s · RPE 8",
   w:"Bisagra unilateral con columna neutra. La versión con barra está excluida."},
  {id:"lun_abd",name:"Máquina de abductor",type:"load",p:"3 × 12 · 60 s · RPE 7"},
  {id:"lun_plank",name:"Plancha con extensión de brazo",type:"iso",p:"3 × 30 s · 45 s · RPE 7",
   w:"Anti-extensión: patrón seguro post-hernia. Cero crunches y cero sit-ups."},
  {id:"lun_pallof",name:"Pallof press en polea",type:"iso",uni:true,p:"3 × 10 / lado · 45 s · RPE 7"}]},
 {n:"Estiramiento estático",ref:true,ex:[
  {id:"lun_st1",name:"Cuádriceps · flexor de cadera · glúteo figura-4",type:"tech",p:"2 × 30 s / lado"},
  {id:"lun_st2",name:"Isquiosurales con columna NEUTRA",type:"tech",p:"2 × 30 s / lado",
   w:"Espalda recta, bisagra desde la cadera. Redondear es flexión espinal, excluida."},
  {id:"lun_st3",name:"Aductor rana — SUAVE · gemelo y sóleo",type:"tech",p:"2 × 30 s",
   w:"Si reproduce el dolor irradiado a zona testicular, sáltalo y repórtalo al fisio."}]}],
 nutri:["06:45 Pre-entreno: 20-25 g whey + plátano","CHO del día 4-5 g/kg (~305-380 g)",
        "Creatina 5 g · D3 2000 UI + K2","16:00 corte de cafeína","21:30 pre-sueño 35-40 g proteína","21:45-22:00 dormir (8 h)"]},

{id:"mar",day:"Martes",code:"MD-4",title:"Tren superior + Copenhagen y Nordic",
 blocks:[
 {n:"Calentamiento",ref:true,ex:[
  {id:"mar_raise",name:"Remo en máquina o bici suave",type:"tech",p:"continuo · 4 min"},
  {id:"mar_act",name:"Band pull-apart · face pull · rotación externa",type:"bw",p:"2 × 15"},
  {id:"mar_ramp",name:"Series de aproximación de press y remo",type:"load",p:"2-3 series · 8-10 / 5-6 / 3-4"}]},
 {n:"Trabajo principal — fuerza",ex:[
  {id:"mar_bench",name:"Press banca con mancuernas o fondos",type:"load",p:"4 × 6-8 · 2 min · RPE 8"},
  {id:"mar_row",name:"Remo con mancuerna a 1 brazo",type:"load",uni:true,p:"4 × 8 / lado · 90 s · RPE 8",
   w:"Con apoyo. El remo con barra inclinado está excluido de forma permanente."},
  {id:"mar_ohp",name:"Press militar sentado con mancuernas",type:"load",p:"3 × 8 · 90 s · RPE 7-8",
   w:"Sentado con respaldo: reduce la demanda de presión intraabdominal."},
  {id:"mar_pull",name:"Dominadas o jalón al pecho",type:"load",p:"3 × 8-10 · 90 s · RPE 8"}]},
 {n:"Prevención — ingle, isquios, tronco",ex:[
  {id:"mar_copen",name:"Copenhagen Adduction",type:"bw",uni:true,p:"2-3 × 6-15 / lado · 45 s · RPE 7-8",
   w:"PILAR del programa. No subas de nivel si hay dolor o pierdes el control del descenso."},
  {id:"mar_nordic",name:"Nordic hamstring curl",type:"bw",p:"2-3 × 5-8 · 60 s",
   w:"Introducir MUY gradual: genera mucho DOMS. Empezar en 2×5."},
  {id:"mar_carry",name:"Farmer's carry y Suitcase carry",type:"dist",uni:true,p:"3 × 30 m · 60 s · RPE 7",
   w:"Anti-flexión lateral sin flexionar la columna. Ideal post-hernia."}]},
 {n:"Estiramiento estático",ref:true,ex:[
  {id:"mar_st1",name:"Pectoral · dorsal · tríceps y bíceps",type:"tech",p:"2 × 30 s / lado"},
  {id:"mar_st2",name:"Rotación torácica (open book)",type:"tech",p:"2 × 30 s / lado"},
  {id:"mar_st3",name:"Aductor suave post-Copenhagen",type:"tech",p:"2 × 30 s",
   w:"SUAVE tras el excéntrico. Si reproduce el dolor irradiado, sáltalo."}]}],
 nutri:["06:45 Pre-entreno: 20 g whey","CHO del día 3-4 g/kg (~230-305 g)",
        "1 h antes del Copenhagen: 15 g gelatina + 50 mg vit C","Creatina 5 g · Omega-3 1-2 g",
        "16:00 corte de cafeína","21:30 pre-sueño 35-40 g proteína","21:45-22:00 dormir (8 h)"]},

{id:"mie",day:"Miércoles",code:"MD-3",title:"Potencia, velocidad y trineo",
 blocks:[
 {n:"Calentamiento — RAMP completo",ref:true,ex:[
  {id:"mie_raise",name:"Trote progresivo · skipping A/B · carioca",type:"tech",p:"continuo · 4 min",
   w:"Nunca saltar en frío: riesgo directo para fascia plantar y Aquiles."},
  {id:"mie_act",name:"Puente · clamshell · elevación de talón · short foot",type:"bw",p:"2 × 12-15"},
  {id:"mie_mob",name:"Leg swings · dorsiflexión en pared",type:"tech",p:"8-10 / lado"},
  {id:"mie_pot",name:"Sprints progresivos 70→85→95%",type:"sprint",p:"3-4 × 20 m"}]},
 {n:"Trabajo principal — potencia",ex:[
  {id:"mie_bme",name:"Barbell Max Effort (sentadilla dividida)",type:"iso",uni:true,p:"3 × 4 s máximo · 2 min",
   w:"Esfuerzo isométrico máximo: exhala o cuenta en voz alta durante el empuje. Nunca aguantes el aire."},
  {id:"mie_plyo",name:"Squat jumps → saltos horizontales → pogos",type:"plyo",p:"30-60 contactos · RPE 8",
   w:"Aterrizajes suaves sobre césped. Si el talón amanece peor, recorta el volumen 50%."},
  {id:"mie_acc",name:"Sprints 0-10 m desde parado",type:"sprint",p:"6 × 10 m · descanso completo"},
  {id:"mie_sled",name:"Empuje y arrastre de trineo",type:"dist",p:"6 × 15-20 m · 90 s · RPE 8-9"},
  {id:"mie_cod",name:"Cambio de dirección (505, cortes 45° y 90°)",type:"plyo",p:"4-6 reps · 90 s"}]},
 {n:"Estiramiento estático",ref:true,ex:[
  {id:"mie_st1",name:"Gemelo y sóleo · fascia con pelota",type:"tech",p:"2 × 30-45 s / lado",
   w:"Prioritario hoy: mayor carga sobre el complejo Aquiles-fascia plantar."},
  {id:"mie_st2",name:"Cuádriceps · flexor de cadera · isquios neutros",type:"tech",p:"2 × 30 s / lado"},
  {id:"mie_st3",name:"Aductor suave · glúteo figura-4",type:"tech",p:"2 × 30 s / lado",
   w:"Los sprints y cortes cargan mucho el aductor: control obligado."}]}],
 nutri:["06:45 Pre-entreno: 20-25 g whey + plátano","Cafeína 3 mg/kg (~230 mg) opcional",
        "CHO del día 4-5 g/kg (~305-380 g)","Creatina 5 g · D3 2000 UI + K2",
        "16:00 corte de cafeína","21:30 pre-sueño 35-40 g proteína","21:45-22:00 dormir (8 h)"]},

{id:"jue",day:"Jueves",code:"MD-2",title:"Core, movilidad, técnica y prevención",
 blocks:[
 {n:"Calentamiento",ref:true,ex:[
  {id:"jue_raise",name:"Caminata rápida o bici suave",type:"tech",p:"continuo · 4 min"},
  {id:"jue_act",name:"Short foot · toe yoga · puente · bird-dog",type:"bw",p:"2 × 10-12"}]},
 {n:"Prevención — fascia plantar (Rathleff)",ex:[
  {id:"jue_rath",name:"Elevación de talón unilateral con toalla",type:"load",uni:true,
   p:"Sem 1-2: 3×12 · Sem 3-4: 4×10 · Sem 5+: 5×8 · tempo 3-2-3",
   w:"Carga alta lenta cada 2 días. El dolor matutino debe volver a tu línea de base."}]},
 {n:"Core — anti-rotación y anti-flexión lateral",ex:[
  {id:"jue_pallof",name:"Pallof press",type:"iso",uni:true,p:"3 × 10 / lado · 45 s · RPE 7"},
  {id:"jue_suit",name:"Suitcase carry",type:"dist",uni:true,p:"3 × 30 m / lado · 45 s · RPE 7",
   w:"Presión intraabdominal controlada sin flexionar la columna."},
  {id:"jue_bird",name:"Bird-dog + dead bug",type:"bw",uni:true,p:"3 × 8 / lado · 45 s · RPE 6",
   w:"Columna NEUTRA. Cero crunches, sit-ups o giros rusos con peso."}]},
 {n:"Potencia de disparo",ex:[
  {id:"jue_mb",name:"Lanzamiento rotacional de balón medicinal",type:"load",uni:true,p:"4 × 6 / lado · 60 s · RPE 8-9"},
  {id:"jue_chop",name:"Chops y lifts en polea",type:"load",uni:true,p:"3 × 10 / lado · 45 s · RPE 7-8",
   w:"Patrón diagonal SIN flexión espinal cargada."},
  {id:"jue_hf",name:"Flexores de cadera resistidos",type:"load",uni:true,p:"3 × 12 / lado · 45 s · RPE 7"}]},
 {n:"Técnica — pase y escaneo",ex:[
  {id:"jue_pass",name:"Pases contra pared, ambos pies",type:"plyo",p:"200-300 contactos"},
  {id:"jue_scan",name:"Recepción orientada + escaneo",type:"tech",p:"integrado · 4 min"}]},
 {n:"Movilidad y estiramiento",ref:true,ex:[
  {id:"jue_mob1",name:"90/90 de cadera · sentadilla profunda sostenida",type:"tech",p:"3 × 45 s"},
  {id:"jue_mob2",name:"Dorsiflexión en pared · open book",type:"tech",p:"10 / lado"},
  {id:"jue_st1",name:"Flexor · cuádriceps · isquios · glúteo",type:"tech",p:"2 × 30 s / lado"},
  {id:"jue_st2",name:"Aductor · gemelo · fascia con pelota",type:"tech",p:"2 × 30-45 s / lado"}]}],
 nutri:["06:45 Solo agua (400-500 ml) + café si quieres","CHO del día 2-3 g/kg — día BAJO (~150-230 g)",
        "1 h antes: 15 g gelatina + 50 mg vit C","Creatina 5 g · D3 + K2 con el almuerzo",
        "16:00 corte de cafeína","21:30 pre-sueño 35-40 g proteína","21:45-22:00 dormir (8 h)"]},

{id:"vie",day:"Viernes",code:"MD-1",title:"Priming ligero u OFF",
 blocks:[
 {n:"Calentamiento",ref:true,ex:[
  {id:"vie_raise",name:"Trote muy suave + movilidad articular",type:"tech",p:"continuo · 5 min"},
  {id:"vie_act",name:"Puente · clamshell · short foot · band pull-apart",type:"bw",p:"1-2 × 10-12"}]},
 {n:"Priming (opcional)",ex:[
  {id:"vie_spr",name:"Sprints al 90% (NO al máximo)",type:"sprint",p:"2-3 × 20 m"},
  {id:"vie_plyo",name:"Saltos bajos: pogos y squat jumps",type:"plyo",p:"10-15 contactos",
   w:"Volumen mínimo por la fascia plantar. Si el talón molesta, elimina este bloque."},
  {id:"vie_iso",name:"Isométricos cortos",type:"iso",p:"3 × 5 s · 60 s"},
  {id:"vie_tech",name:"Toques ligeros de balón",type:"tech",p:"5 min · sin disparos potentes"}]},
 {n:"Estiramiento suave",ref:true,ex:[
  {id:"vie_st1",name:"Flexor de cadera · glúteo · torácica",type:"tech",p:"2 × 30 s / lado"},
  {id:"vie_st2",name:"Aductor suave · gemelo · pelota bajo el arco",type:"tech",p:"2 × 30 s"}]},
 {n:"Checklist pre-partido",ref:true,ex:[
  {id:"vie_bag",name:"Preparar bolsa: botines, ropa, botella",type:"tech",p:"hoy, no mañana"},
  {id:"vie_sleep",name:"Dormir 21:45-22:00 — objetivo 8 h",type:"tech",p:"—"}]}],
 nutri:["CHO del día ALTO 5-6 g/kg (~380-460 g)","19:00-20:00 cena con carbohidrato — innegociable",
        "CERO alcohol esta noche","16:00 corte de cafeína","21:45-22:00 dormir (8 h)"]},

{id:"sab",day:"Sábado",code:"MD",title:"Partido 11:00",
 blocks:[
 {n:"Calentamiento RAMP (10:30-10:57)",ref:true,ex:[
  {id:"sab_raise",name:"Trote · skipping · desplazamientos laterales",type:"tech",p:"4 min"},
  {id:"sab_act",name:"Puente · clamshell · WGS · leg swings",type:"tech",p:"10-12 / lado · 5 min"},
  {id:"sab_copen",name:"Copenhagen isométrico corto",type:"iso",uni:true,p:"2 × 10-15 s / lado",
   w:"Solo isométrico corto hoy. NO el Copenhagen completo."},
  {id:"sab_pot",name:"Sprints progresivos + saltos",type:"sprint",p:"4-5 reps · terminar 5-7 min antes"},
  {id:"sab_ball",name:"Toques y 2-3 disparos progresivos",type:"tech",p:"5 min"}]},
 {n:"Partido",ex:[
  {id:"sab_match",name:"Partido 6v6 / 7v7",type:"check",p:"duración real",
   w:"Ante dolor agudo inguinal o testicular, bulto abdominal nuevo, o dolor que impide apoyar: SALIR."}]},
 {n:"Recuperación",ref:true,ex:[
  {id:"sab_cool",name:"Vuelta a la calma: trote suave + caminata",type:"tech",p:"5-8 min"},
  {id:"sab_st",name:"Aductor · gemelo y fascia · flexor · isquios",type:"tech",p:"2 × 30-45 s / lado",
   w:"Aductor es prioridad absoluta hoy: los cortes del partido son su mayor estresor."}]}],
 nutri:["07:00 Comida pre-partido: 150-250 g CHO + proteína","08:00 Hidratación 400-500 ml",
        "10:00 Cafeína 3 mg/kg opcional","Post: CHO 1,0-1,2 g/kg/h + 20-40 g proteína",
        "Reponer 1,25-1,5 L por kg perdido, con sodio"]},

{id:"dom",day:"Domingo",code:"MD+1",title:"Recuperación activa",
 blocks:[
 {n:"Movilización de tejidos",ref:true,ex:[
  {id:"dom_foam",name:"Foam roll: cuádriceps · glúteo · dorsal · torácica",type:"tech",p:"60-90 s / zona",
   w:"No rodar con presión directa sobre la cicatriz umbilical."},
  {id:"dom_calf",name:"Foam roll gemelo y sóleo",type:"tech",p:"60-90 s / lado"},
  {id:"dom_ball",name:"Pelota bajo el arco del pie",type:"tech",p:"2 × 60 s / pie"}]},
 {n:"Movilidad dirigida",ref:true,ex:[
  {id:"dom_hip",name:"90/90 con transiciones · sentadilla profunda",type:"tech",p:"3 × 45 s"},
  {id:"dom_ank",name:"Dorsiflexión en pared · círculos de tobillo",type:"tech",p:"10-12 / lado"},
  {id:"dom_thor",name:"Open book · extensión torácica en foam roller",type:"tech",p:"10 / lado"}]},
 {n:"Respiración y control de presión",ex:[
  {id:"dom_br1",name:"Respiración diafragmática 360º",type:"check",p:"3 × 8 respiraciones · 4 s in / 6 s out",
   w:"Expandir costillas en 360º, NO empujar la panza. Base de tu seguridad al cargar."},
  {id:"dom_br2",name:"Exhalación con activación de transverso",type:"check",p:"3 × 8"}]},
 {n:"Caminata y estiramiento",ref:true,ex:[
  {id:"dom_walk",name:"Caminata a ritmo cómodo",type:"tech",p:"30-45 min"},
  {id:"dom_st",name:"Estiramiento completo (flexor, isquios, aductor, gemelo, pectoral)",type:"tech",p:"2 × 30-45 s / lado"}]}],
 nutri:["Día de descanso: CHO 2-3 g/kg","Mantener 150-165 g de proteína","Creatina 5 g","Dormir 8 h"]}
]};

/* ============================================================
   Program — Plan B — Casa (segundo programa por defecto)
   Material: 2 KB de 4 kg, banda corta fuerte, mat, foam roller,
   sillas de 40 cm, pelotas de tenis, bola de fisio.
   Principio: la carga sale de tempo, pausas isométricas y trabajo
   unilateral, no del peso.
   ============================================================ */
const PROGRAM_CASA={id:"prog_casa",name:"Plan B — Casa",builtin:true,
 note:"La carga sale del tempo y las pausas, no del peso. Cuando 4 × 12 a tempo 4-1-1 te resulte RPE 7 o menos, sube primero a 5 s de bajada, luego a 2 KB, luego a 15 reps. En ese orden.",
 days:[
{id:"casa_lun",day:"Lunes CASA",dow:0,code:"MD-5",title:"Tren inferior: fuerza + core",
 blocks:[
 {n:"Calentamiento",ref:true,ex:[
  {id:"casa_lun_marcha",name:"Marcha en el sitio, rodillas altas, talones al glúteo, desplazamiento lateral",type:"tech",p:"continuo · 4 min"},
  {id:"casa_lun_puente",name:"Puente de glúteo, clamshell con banda, monster walk lateral",type:"bw",p:"2 × 12-15"},
  {id:"casa_lun_zancada",name:"Zancada con rotación torácica, world's greatest stretch, leg swings",type:"tech",p:"8 / lado · 3 min"}]},
 {n:"Trabajo principal",ex:[
  {id:"casa_lun_bulg",name:"Sentadilla búlgara con pie trasero en silla, 1 KB al pecho",type:"load",uni:true,p:"4 × 10-12 / pierna · 2 min · tempo 4-1-1 · RPE 8-9",
   w:"PARA si aparece dolor inguinal o testicular."},
  {id:"casa_lun_bulgiso",name:"Sentadilla búlgara isométrica en el punto bajo",type:"iso",uni:true,p:"3 × 20-30 s / pierna · 60 s · RPE 8",
   w:"Exhala durante el sostén, sin apnea."},
  {id:"casa_lun_step",name:"Step-up explosivo a la silla con 2 KB",type:"load",uni:true,p:"3 × 12 / pierna · 90 s · bajada 3 s, subida explosiva · RPE 8"},
  {id:"casa_lun_puentekb",name:"Puente de glúteo a una pierna con hombros en la silla y KB en la cadera",type:"load",uni:true,p:"3 × 12-15 / pierna · 90 s · pausa 3 s arriba · RPE 8",
   w:"EXHALA al empujar la cadera, sin apnea."},
  {id:"casa_lun_extcadera",name:"Extensión de cadera en suelo o puente con talones en la silla",type:"bw",p:"3 × 15 · 60 s · RPE 7",
   w:"Columna neutra: el movimiento sale de la cadera, no de arquear la espalda baja."},
  {id:"casa_lun_plank",name:"Plancha con extensión de brazo alternada",type:"iso",p:"3 × 30 s · 45 s · RPE 7",
   w:"Anti-extensión: patrón seguro post-hernia. Cero crunches y cero sit-ups."},
  {id:"casa_lun_pallof",name:"Pallof press con banda anclada",type:"iso",uni:true,p:"3 × 10 / lado · 45 s · RPE 7"}]},
 {n:"Estiramiento estático",ref:true,ex:[
  {id:"casa_lun_st1",name:"Cuádriceps de pie, flexor de cadera en zancada, glúteo figura-4",type:"tech",p:"2 × 30 s / lado"},
  {id:"casa_lun_st2",name:"Isquiosurales con columna neutra",type:"tech",p:"2 × 30 s / lado",
   w:"Espalda recta, bisagra desde la cadera. Redondear es flexión espinal, excluida."},
  {id:"casa_lun_st3",name:"Aductor rana suave, gemelo y sóleo, pelota de tenis bajo el arco",type:"tech",p:"2 × 30 s",
   w:"Si reproduce el dolor irradiado a zona testicular, sáltalo y repórtalo al fisio."}]}],
 nutri:[]},

{id:"casa_jue",day:"Jueves CASA",dow:3,code:"MD-2",title:"Core, movilidad, técnica y prevención",
 blocks:[
 {n:"Calentamiento",ref:true,ex:[
  {id:"casa_jue_walk",name:"Caminata rápida o bici suave",type:"tech",p:"continuo · 4 min"},
  {id:"casa_jue_act",name:"Short foot, toe yoga, puente de glúteo, bird-dog",type:"bw",p:"2 × 10-12"}]},
 {n:"Prevención — fascia plantar",ex:[
  {id:"casa_jue_rath",name:"Elevación de talón unilateral con toalla bajo los dedos, sujetando KB",type:"load",uni:true,
   p:"Sem 1-2: 3×12 · Sem 3-4: 4×10 · Sem 5+: 5×8 · tempo 3-2-3",
   w:"Carga alta lenta cada 2 días. El dolor matutino debe volver a tu línea de base."}]},
 {n:"Core",ex:[
  {id:"casa_jue_pallof",name:"Pallof press con banda anclada",type:"iso",uni:true,p:"3 × 10 / lado · 45 s · RPE 7"},
  {id:"casa_jue_suitcase",name:"Suitcase carry con 1 KB",type:"iso",uni:true,p:"3 × 45-60 s / lado · 45 s · RPE 7",
   w:"Presión intraabdominal controlada sin flexionar la columna."},
  {id:"casa_jue_birddog",name:"Bird-dog y dead bug",type:"bw",uni:true,p:"3 × 8 / lado · 45 s · RPE 6",
   w:"Columna neutra. Cero crunches, sit-ups o giros rusos con peso."}]},
 {n:"Potencia de disparo",ex:[
  {id:"casa_jue_rot",name:"Rotación explosiva con banda anclada al costado",type:"bw",uni:true,p:"4 × 8 / lado · 60 s · RPE 8",
   w:"La rotación sale de cadera y tronco, nunca de la lumbar."},
  {id:"casa_jue_chop",name:"Chops y lifts con banda",type:"bw",uni:true,p:"3 × 10 / lado · 45 s · RPE 7-8"},
  {id:"casa_jue_hip",name:"Flexores de cadera resistidos con banda en el tobillo",type:"bw",uni:true,p:"3 × 12 / lado · 45 s · RPE 7"}]},
 {n:"Técnica",ex:[
  {id:"casa_jue_tech",name:"Trabajo de suela y toque sobre el mat, ambos pies",type:"tech",p:"6-8 min continuos"},
  {id:"casa_jue_scan",name:"Escaneo en seco: mirar por encima del hombro antes de cada toque",type:"check",p:"integrado"}]},
 {n:"Movilidad y estiramiento",ref:true,ex:[
  {id:"casa_jue_mob1",name:"90/90 de cadera, sentadilla profunda sostenida",type:"tech",p:"3 × 45 s"},
  {id:"casa_jue_mob2",name:"Dorsiflexión en pared, extensión torácica sobre foam roller, open book",type:"tech",p:"10 / lado"},
  {id:"casa_jue_st1",name:"Flexor, cuádriceps, isquios con columna neutra, glúteo",type:"tech",p:"2 × 30 s / lado"},
  {id:"casa_jue_st2",name:"Aductor, gemelo, fascia con pelota de tenis",type:"tech",p:"2 × 30-45 s / lado"}]}],
 nutri:[]}
]};

const DEFAULT_PROGRAMS=[PROGRAM,PROGRAM_CASA];

/* ============================================================
   Migración DB.program (v2.4 y anteriores) → DB.programs
   ============================================================ */
function migratePrograms(){
  if(!DB.programs||!DB.programs.length){
    if(DB.program&&DB.program.days){
      const migrated={id:"prog_verano360",name:DB.program.name||"Verano 360",
        note:"",builtin:true,days:DB.program.days};
      DB.programs=[migrated,JSON.parse(JSON.stringify(PROGRAM_CASA))];
      DB.activeProgramId=migrated.id;
      (DB.logs||[]).forEach(lg=>{if(!lg.programId)lg.programId=migrated.id;});
      if(DB.draft&&!DB.draft.programId)DB.draft.programId=migrated.id;
    }else{
      DB.programs=JSON.parse(JSON.stringify(DEFAULT_PROGRAMS));
      DB.activeProgramId=DB.programs[0].id;
    }
    delete DB.program;
    save();
  }
  if(!DB.activeProgramId||!DB.programs.find(p=>p.id===DB.activeProgramId)){
    DB.activeProgramId=DB.programs[0].id;save();
  }
}
migratePrograms();

/* ============================================================
   Field definitions per exercise type
   ============================================================ */
const FIELDS={
 load:[{k:"kg",l:"kg"},{k:"reps",l:"reps"}],
 bw:[{k:"reps",l:"reps"}],
 iso:[{k:"secs",l:"secs"}],
 dist:[{k:"m",l:"m"},{k:"kg",l:"kg"}],
 plyo:[{k:"contacts",l:"contacts"}],
 sprint:[{k:"m",l:"m"},{k:"time",l:"time"}],
 tech:[{k:"min",l:"min"}],
 check:[]
};
const HAS_RPE={load:1,bw:1,iso:1,dist:1,plyo:1,sprint:0,tech:0,check:0};

/* ============================================================
   Utils
   ============================================================ */
const $=s=>document.querySelector(s);
const esc=s=>String(s==null?"":s).replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
function num(v){if(v==null)return null;const s=String(v).replace(",",".").trim();
  if(s==="")return null;const n=parseFloat(s);return isNaN(n)?null:n;}
function toast(m){const e=$("#toast");e.textContent=m;e.classList.add("on");
  clearTimeout(e._t);e._t=setTimeout(()=>e.classList.remove("on"),1900);}
function today(){return new Date().toISOString().slice(0,10);}
function fmtD(d){const x=new Date(d+"T12:00:00");
  return x.toLocaleDateString(L==="es"?"es-ES":L==="pl"?"pl-PL":"en-GB",{day:"numeric",month:"short"});}
async function sha(s){const b=new TextEncoder().encode(s);
  const h=await crypto.subtle.digest("SHA-256",b);
  return Array.from(new Uint8Array(h)).map(x=>x.toString(16).padStart(2,"0")).join("");}
function activeProgram(){return DB.programs.find(p=>p.id===DB.activeProgramId)||DB.programs[0];}
function getProgram(id){return DB.programs.find(p=>p.id===id);}
function findEx(id){for(const p of DB.programs)for(const d of p.days)for(const b of d.blocks)
  for(const e of b.ex)if(e.id===id)return{ex:e,day:d,block:b,program:p};return null;}
function dayById(id){for(const p of DB.programs){const d=p.days.find(x=>x.id===id);if(d)return d;}return null;}
function programOfDay(id){return DB.programs.find(p=>p.days.some(d=>d.id===id));}

/* ============================================================
   Signal engine
   ============================================================ */
function computeSignal(ci,dayId){
  const reasons=[],acts=[];
  let level="g";
  // Rígido: dolor en zonas con historial
  if(ci.groin>=2){level="r";reasons.push("Dolor de ingle por encima de tu línea de base");
    acts.push("Salta el Copenhagen y cualquier ejercicio que tire del aductor");
    acts.push("Si el dolor irradia a zona testicular, no entrenes y contacta al fisio");}
  if(ci.heel>=2){if(level!=="r")level="r";
    reasons.push("Dolor de talón por encima de tu línea de base");
    acts.push("Sin pliometría, sin sprints y sin saltos hoy");
    acts.push("Mantén solo el Rathleff a baja carga");}
  if(level!=="r"){
    // fatiga acumulada de la sesión previa del mismo día
    const prev=DB.logs.filter(x=>x.dayId===dayId).slice(-1)[0];
    const lastAny=DB.logs.slice(-1)[0];
    let hardPrev=false,hardYday=false;
    const avgOf=lg=>{if(!lg)return null;
      if(typeof lg.avgRpe==="number")return lg.avgRpe;
      const rs=(lg.entries||[]).map(e=>e.rpe).filter(Boolean);
      return rs.length?rs.reduce((a,b)=>a+b,0)/rs.length:null;};
    const a1=avgOf(prev); if(a1!=null&&a1>=8.5)hardPrev=true;
    const a2=avgOf(lastAny); if(a2!=null&&a2>=9)hardYday=true;
    const low=(ci.sleep<=2)||(ci.energy<=2);
    if(low||hardPrev||hardYday){level="a";
      if(ci.sleep<=2)reasons.push("Dormiste mal");
      if(ci.energy<=2)reasons.push("Energía baja");
      if(hardPrev)reasons.push("La última vez que hiciste este día cerraste con RPE "+a1.toFixed(1));
      if(hardYday&&!hardPrev)reasons.push("Tu sesión más reciente cerró con RPE "+a2.toFixed(1));
      acts.push("Repite las cargas de la última sesión, sin subir");
      acts.push("Si a mitad de sesión el RPE se dispara, corta una serie por ejercicio");
    }else{
      reasons.push("Check-in en verde y sin dolor por encima de tu base");
      acts.push("Sube 2,5 kg o 1 repetición en el primer ejercicio de fuerza");
      acts.push("Solo sube en UN ejercicio por sesión, no en todos");
    }
  }
  return{level,reasons,acts,
   label:level==="g"?t("green"):level==="a"?t("amber"):t("red")};
}

/* ============================================================
   Router
   ============================================================ */
let VIEW="home",CTX={};
function go(v,ctx){VIEW=v;CTX=ctx||{};render();window.scrollTo(0,0);}
function render(){
  document.querySelectorAll(".view").forEach(e=>e.classList.remove("on"));
  document.querySelectorAll("nav button").forEach(b=>
    b.classList.toggle("on",b.dataset.nav===VIEW));
  $("#backBtn").style.display=(VIEW==="session")?"flex":"none";
  $("#actBtn").style.display="none";
  $("#homeLogo").style.display=(VIEW==="home")?"block":"none";
  if(VIEW==="home"){const nm=DB.settings.name||t("guestUser");
      $("#title").textContent=L==="es"?"Hola, "+nm:L==="pl"?"Cześć, "+nm:"Hi, "+nm;
      $("#v-home").classList.add("on");renderHome();}
  if(VIEW==="session"){$("#v-session").classList.add("on");renderSession();}
  if(VIEW==="progress"){$("#title").textContent=t("progress");
    $("#v-progress").classList.add("on");renderProgress();}
  if(VIEW==="tests"){$("#title").textContent=t("tabTests");
    $("#v-tests").classList.add("on");renderTests();}
  if(VIEW==="settings"){$("#title").textContent=t("settings");
    $("#v-settings").classList.add("on");renderSettings();}
}
document.querySelectorAll("nav button").forEach(b=>
  b.onclick=()=>go(b.dataset.nav));
$("#backBtn").onclick=()=>go("home");

/* ============================================================
   Home
   ============================================================ */
/* ============================================================
   Semana
   ============================================================ */
const DAY_ORDER=["lun","mar","mie","jue","vie","sab","dom"];
function mondayOf(d){const x=new Date(d);const w=(x.getDay()+6)%7;
  x.setDate(x.getDate()-w);x.setHours(12,0,0,0);return x;}
function iso(d){return new Date(d).toISOString().slice(0,10);}
function weekDates(offset){
  const m=mondayOf(new Date());m.setDate(m.getDate()+(offset||0)*7);
  return Array.from({length:7},(_,i)=>{const x=new Date(m);x.setDate(m.getDate()+i);return iso(x);});
}
function weekKey(offset){return weekDates(offset)[0];}
function dayState(dateStr){
  if(DB.logs.some(l=>l.date===dateStr))return "done";
  if((DB.marks||{})[dateStr])return "manual";
  const td=iso(new Date());
  if(dateStr<td)return "missed";
  if(dateStr===td)return "today";
  return "future";
}
window.toggleMark=function(dateStr){
  if(DB.logs.some(l=>l.date===dateStr)){toast(t("autoDay"));return;}
  if(!DB.marks)DB.marks={};
  if(DB.marks[dateStr])delete DB.marks[dateStr];else DB.marks[dateStr]=true;
  save();renderHome();
};
function ringSVG(offset){
  const dates=weekDates(offset);
  const R=52,C=64,SW=11,gap=5;
  const seg=(360/7);
  const parts=dates.map((ds,i)=>{
    const st=i*seg-90+gap/2, en=(i+1)*seg-90-gap/2;
    const a=(deg)=>[C+R*Math.cos(deg*Math.PI/180),C+R*Math.sin(deg*Math.PI/180)];
    const [x1,y1]=a(st),[x2,y2]=a(en);
    const s=dayState(ds);
    const col=s==="done"?"var(--accent)":s==="manual"?"var(--mist)":
              s==="today"?"var(--steel)":"var(--line)";
    const dash=(s==="today")?'stroke-dasharray="3 4"':"";
    return `<path d="M${x1.toFixed(1)} ${y1.toFixed(1)} A${R} ${R} 0 0 1 ${x2.toFixed(1)} ${y2.toFixed(1)}"
      fill="none" stroke="${col}" stroke-width="${SW}" stroke-linecap="round" ${dash}
      style="cursor:pointer" onclick="toggleMark('${ds}')"></path>`;
  }).join("");
  const n=dates.filter(d=>dayState(d)==="done"||dayState(d)==="manual").length;
  return `<svg viewBox="0 0 128 128" width="128" height="128" role="img"
    aria-label="${n} ${t("of")} 7">${parts}
    <text x="64" y="60" text-anchor="middle" font-size="30" font-weight="700"
      fill="var(--ink)" font-family="-apple-system,sans-serif">${n}</text>
    <text x="64" y="78" text-anchor="middle" font-size="11"
      fill="var(--ink-soft)" font-family="-apple-system,sans-serif">${t("of")} 7</text></svg>`;
}
function weekLabels(offset){
  const dates=weekDates(offset);
  const L7=(L==="es"?["L","M","X","J","V","S","D"]:L==="pl"?["P","W","Ś","C","P","S","N"]:["M","T","W","T","F","S","S"]);
  return `<div class="wk-labels">`+dates.map((ds,i)=>{
    const s=dayState(ds);
    return `<div class="wk-l ${s}" onclick="toggleMark('${ds}')">
      <span>${L7[i]}</span><i>${+ds.slice(8,10)}</i></div>`;}).join("")+`</div>`;
}

/* ============================================================
   Métricas
   ============================================================ */
const DEFAULT_METRICS=[
  {id:"m_weight",name:"Peso corporal",unit:"kg",cadence:42,entries:[],linkedTest:"t_weight"},
  {id:"m_speed", name:"Velocidad máxima",unit:"km/h",cadence:0,entries:[],linkedTest:"t_sprint"},
  {id:"m_jump",  name:"Salto máximo",unit:"cm",cadence:0,entries:[],linkedTest:"t_cmj"}
];
function metrics(){if(!DB.metrics)DB.metrics=JSON.parse(JSON.stringify(DEFAULT_METRICS));return DB.metrics;}
function customMetrics(){return metrics().filter(m=>!m.linkedTest);}
function sparkMini(vals){
  if(vals.length<2)return"";
  const mx=Math.max(...vals,1),mn=Math.min(...vals,0);
  return `<div class="spark">${vals.map((v,i)=>
    `<i class="${i===vals.length-1?"last":""}" style="height:${Math.max(10,((v-mn)/((mx-mn)||1))*88+12)}%"></i>`).join("")}</div>`;
}
function metricTile(m){
  if(m.linkedTest){
    const lt=getTest(m.linkedTest);
    if(!lt)return"";
    const es=sortedEntries(lt);
    const last=es[0];
    const lastVal=last?entryPrimary(last,lt):null;
    const vals=es.slice(0,8).reverse().map(e=>entryPrimary(e,lt)).filter(v=>v!=null);
    return `<div class="card tap mtile" onclick="openTest('${lt.id}')">
      <div class="t">${esc(lt.name)}</div>
      <div class="metric-v">${lastVal!=null?String(lastVal).replace(".",","):"—"}</div>
      <div class="xs">${esc(lt.unit)}</div>
      ${sparkMini(vals)}</div>`;
  }
  const es=(m.entries||[]).slice().sort((a,b)=>a.date<b.date?1:-1);
  const last=es[0];
  const vals=es.slice(0,8).reverse().map(e=>e.value);
  return `<div class="card tap mtile" onclick="openMetric('${m.id}')">
    <div class="t">${esc(m.name)}</div>
    <div class="metric-v">${last?String(last.value).replace(".",","):"—"}</div>
    <div class="xs">${esc(m.unit)}</div>
    ${sparkMini(vals)}</div>`;
}
window.openMetricManager=function(){
  let h=`<h2>${t("manageMetrics")}</h2>`;
  const list=customMetrics();
  if(!list.length)h+=`<div class="xs" style="padding:2px 2px 10px">${t("noCustomMetrics")}</div>`;
  list.forEach(m=>{
    h+=`<div class="card" style="padding:11px 12px">
      <div class="row" style="align-items:flex-start">
        <div class="grow">
          <div class="t" style="font-size:14px">${esc(m.name)}</div>
          <div class="xs" style="margin-top:3px">${esc(m.unit)}${m.cadence?` · ${m.cadence} ${t("daysWord")}`:""}</div>
        </div>
        <div style="display:flex;flex-direction:column;gap:4px">
          <button class="mini-btn" onclick="moveMetric('${m.id}',-1)">↑</button>
          <button class="mini-btn" onclick="moveMetric('${m.id}',1)">↓</button>
        </div>
      </div>
      <button class="btn ghost sm" style="margin-top:9px" onclick="editMetric('${m.id}')">${t("edit")}</button>
    </div>`;
  });
  h+=`<button class="addset" onclick="editMetric()">+ ${t("addMetric")}</button>`;
  sheet(h);
};
window.moveMetric=function(id,dir){
  const list=customMetrics();
  const i=list.findIndex(m=>m.id===id);
  const j=i+dir;
  if(i<0||j<0||j>=list.length)return;
  const all=metrics();
  const realI=all.indexOf(list[i]),realJ=all.indexOf(list[j]);
  const tmp=all[realI];all[realI]=all[realJ];all[realJ]=tmp;
  save();openMetricManager();renderHome();
};
window.openMetric=function(id){
  const m=metrics().find(x=>x.id===id);if(!m)return;
  const es=(m.entries||[]).slice().sort((a,b)=>a.date<b.date?1:-1);
  let h=`<h2>${esc(m.name)}</h2>
  <div class="field"><label class="lab">${t("newValue")} (${esc(m.unit)})</label>
    <input class="inp" id="mv" type="text" inputmode="decimal" autocomplete="off" placeholder="—"></div>
  <div class="field"><label class="lab">${t("date")}</label>
    <input class="inp" id="md" type="date" value="${iso(new Date())}"></div>
  <button class="btn" id="mAdd">${t("addValue")}</button>
  <div class="sec">${t("history").toUpperCase()}</div>`;
  if(!es.length)h+=`<div class="xs" style="padding:4px 2px 12px">${t("noData")}</div>`;
  es.forEach((e,i)=>{
    h+=`<div class="card" style="padding:10px 12px"><div class="row">
      <div class="grow"><div class="t" style="font-size:14px">${String(e.value).replace(".",",")} ${esc(m.unit)}</div>
      <div class="xs" style="margin-top:2px">${fmtD(e.date)}</div></div>
      <button class="del-btn" onclick="delMetricVal('${m.id}',${i})">✕</button></div></div>`;
  });
  h+=`<button class="btn ghost sm" style="margin-top:14px" onclick="editMetric('${m.id}')">${t("editMetric")}</button>`;
  sheet(h);
  $("#mAdd").onclick=()=>{
    const v=num($("#mv").value);
    if(v==null){toast(t("needValue"));return;}
    m.entries.push({date:$("#md").value||iso(new Date()),value:Math.round(v*100)/100});
    save();openMetric(id);renderHome();toast(t("saved"));
  };
};
window.delMetricVal=function(id,i){
  const m=metrics().find(x=>x.id===id);
  const es=(m.entries||[]).slice().sort((a,b)=>a.date<b.date?1:-1);
  const target=es[i];
  m.entries=m.entries.filter(x=>x!==target);
  save();openMetric(id);renderHome();
};
window.editMetric=function(id){
  const isNew=!id;
  const m=isNew?{id:"m_"+Date.now(),name:"",unit:"",cadence:0,entries:[]}:metrics().find(x=>x.id===id);
  sheet(`<h2>${isNew?t("addMetric"):t("editMetric")}</h2>
  <div class="field"><label class="lab">${t("mName")}</label>
    <input class="inp" id="emN" type="text" value="${esc(m.name)}" placeholder="Salto vertical"></div>
  <div class="field"><label class="lab">${t("mUnit")}</label>
    <input class="inp" id="emU" type="text" value="${esc(m.unit)}" placeholder="cm"></div>
  <div class="field"><label class="lab">${t("mCad")}</label>
    <input class="inp" id="emC" type="text" inputmode="decimal" value="${m.cadence||""}" placeholder="42">
    <div class="xs" style="margin-top:6px">${t("mCadHelp")}</div></div>
  <button class="btn" id="emS">${t("save")}</button>
  ${isNew?"":`<button class="btn ghost sm" style="margin-top:9px;color:var(--red);border-color:var(--red)"
     onclick="delMetric('${m.id}')">${t("delMetric")}</button>`}`);
  $("#emS").onclick=()=>{
    const n=$("#emN").value.trim();
    if(!n){toast(t("needName"));return;}
    m.name=n;m.unit=$("#emU").value.trim();m.cadence=num($("#emC").value)||0;
    if(isNew)metrics().push(m);
    save();openMetricManager();renderHome();toast(t("saved"));
  };
};
window.delMetric=function(id){
  if(!confirm(t("confDelMetric")))return;
  DB.metrics=metrics().filter(x=>x.id!==id);
  save();openMetricManager();renderHome();
};

/* ============================================================
   Expectations — tests, objetivos y retest
   HEIGHT_M: altura fija de Iván, usada para IMC y Sayers power.
   ============================================================ */
const HEIGHT_M=1.73;
const DEFAULT_TESTS=[
 {id:"t_weight",kind:"weight",name:"Peso corporal",unit:"kg",cadence:42,goal:null,entries:[]},
 {id:"t_bmi",kind:"bmi",name:"IMC",unit:"",cadence:42,goal:null,entries:[]},
 {id:"t_rm",kind:"rm",name:"Fuerza máxima (1RM)",unit:"kg",cadence:28,goal:null,entries:[]},
 {id:"t_cooper",kind:"cooper",name:"Test de Cooper (VO2max)",unit:"ml/kg/min",cadence:28,goal:null,entries:[]},
 {id:"t_cmj",kind:"cmj",name:"CMJ bilateral",unit:"cm",cadence:28,goal:null,entries:[]},
 {id:"t_cmj_uni",kind:"cmj_uni",name:"CMJ unilateral",unit:"cm",cadence:28,goal:null,entries:[]},
 {id:"t_sj",kind:"sj",name:"Squat jump",unit:"cm",cadence:28,goal:null,entries:[]},
 {id:"t_longjump",kind:"longjump",name:"Salto de longitud",unit:"cm",cadence:28,goal:null,entries:[]},
 {id:"t_loaded",kind:"loaded",name:"Saltos progresivos con carga",unit:"cm",cadence:28,goal:null,entries:[]},
 {id:"t_sprint",kind:"sprint",name:"Sprint 30 m recto",unit:"m/s",cadence:28,goal:null,entries:[]},
 {id:"t_sprint_curve",kind:"sprint_curve",name:"Sprint 30 m curvo",unit:"m/s",cadence:28,goal:null,entries:[]}
];
const TEST_KINDS={
 weight:{fields:[{k:"kg",l:"kg"}],calc:(r)=>({primary:r.kg==null?null:r.kg,extras:[]})},
 rm:{fields:[{k:"ex",l:"exercise",type:"text"},{k:"kg",l:"kg"},{k:"reps",l:"reps"}],
  calc:(r)=>({primary:(r.kg!=null&&r.reps!=null)?+(r.kg*(1+r.reps/30)).toFixed(1):null,extras:[]})},
 cooper:{fields:[{k:"m",l:"coopMeters"}],
  calc:(r)=>({primary:r.m!=null?+(((r.m-504.9)/44.73).toFixed(1)):null,
    extras:r.m!=null?[{l:"meters",v:r.m,u:"m"}]:[]})},
 cmj:{fields:[{k:"h",l:"cmH"}],injury:"plyo",
  calc:(r,ctx)=>{const extras=[];const bw=ctx.weight();
    if(bw!=null&&r.h!=null)extras.push({l:"power",v:Math.round(60.7*r.h+45.3*bw-2055),u:"W"});
    return{primary:r.h==null?null:r.h,extras};}},
 cmj_uni:{fields:[{k:"l",l:"cmL"},{k:"r",l:"cmR"}],injury:"plyo",
  calc:(r,ctx)=>{const extras=[];const bw=ctx.weight();
    const avg=(r.l!=null&&r.r!=null)?(r.l+r.r)/2:(r.l!=null?r.l:(r.r!=null?r.r:null));
    if(bw!=null&&avg!=null)extras.push({l:"power",v:Math.round(60.7*avg+45.3*bw-2055),u:"W"});
    if(r.l!=null&&r.r!=null&&Math.max(r.l,r.r)>0)
      extras.push({l:"asymmetry",v:(Math.abs(r.l-r.r)/Math.max(r.l,r.r)*100).toFixed(0),u:"%"});
    return{primary:avg==null?null:+avg.toFixed(1),extras};}},
 sj:{fields:[{k:"h",l:"cmH"}],injury:"plyo",
  calc:(r,ctx)=>{const extras=[];const cmj=ctx.cmj();
    if(cmj!=null&&r.h!=null)extras.push({l:"elastic",v:(r.h-cmj).toFixed(1),u:"cm"});
    return{primary:r.h==null?null:r.h,extras};}},
 longjump:{fields:[{k:"cm",l:"cmLong"}],injury:"plyo",
  calc:(r)=>({primary:r.cm==null?null:r.cm,extras:[]})},
 loaded:{fields:[{k:"h0",l:"cmNoLoad"},{k:"h10",l:"cmLoad10"},{k:"h20",l:"cmLoad20"},{k:"h30",l:"cmLoad30"}],injury:"plyo",
  calc:(r)=>{const extras=[];
    [["h10","dropAt10"],["h20","dropAt20"],["h30","dropAt30"]].forEach(([k,lab])=>{
      if(r.h0!=null&&r[k]!=null&&r.h0>0)extras.push({l:lab,v:((r.h0-r[k])/r.h0*100).toFixed(0),u:"%"});
    });
    return{primary:r.h0==null?null:r.h0,extras};}},
 sprint:{fields:[{k:"t30",l:"sprintTotal"},{k:"t2030",l:"sprintSplit"}],injury:"sprint",
  calc:(r)=>{const extras=[];let primary=null;
    if(r.t2030>0){primary=+(10/r.t2030).toFixed(2);extras.push({l:"maxSpeedKmh",v:(primary*3.6).toFixed(1),u:"km/h"});}
    if(r.t30>0)extras.push({l:"avgSpeed",v:(30/r.t30).toFixed(2),u:"m/s"});
    return{primary,extras};}},
 sprint_curve:{fields:[{k:"t30",l:"sprintTotal"},{k:"t2030",l:"sprintSplit"}],injury:"sprint",
  calc:(r,ctx)=>{const extras=[];let primary=null;
    if(r.t2030>0){primary=+(10/r.t2030).toFixed(2);extras.push({l:"maxSpeedKmh",v:(primary*3.6).toFixed(1),u:"km/h"});}
    if(r.t30>0)extras.push({l:"avgSpeed",v:(30/r.t30).toFixed(2),u:"m/s"});
    const straight=ctx.sprintStraight();
    if(straight!=null&&primary!=null)extras.push({l:"vsStraight",v:(primary-straight).toFixed(2),u:"m/s"});
    return{primary,extras};}},
 custom:{fields:[{k:"v",l:"newValue"}],calc:(r)=>({primary:r.v==null?null:r.v,extras:[]})}
};
function tests(){if(!DB.tests)DB.tests=JSON.parse(JSON.stringify(DEFAULT_TESTS));return DB.tests;}
function getTest(id){return tests().find(x=>x.id===id);}
function sortedEntries(test){return (test.entries||[]).slice().sort((a,b)=>a.date<b.date?1:-1);}
function testCtx(){
  return{
   weight:()=>{const w=getTest("t_weight");if(!w)return null;const es=sortedEntries(w);
     return es.length?entryPrimary(es[0],w):null;},
   cmj:()=>{const c=getTest("t_cmj");if(!c)return null;const es=sortedEntries(c);
     return es.length?entryPrimary(es[0],c):null;},
   sprintStraight:()=>{const s=getTest("t_sprint");if(!s)return null;const es=sortedEntries(s);
     return es.length?entryPrimary(es[0],s):null;}
  };
}
function calcResult(test,raw){
  if(test.kind==="bmi"){
    const kg=raw&&raw.kg;
    return{primary:kg==null?null:+(kg/(HEIGHT_M*HEIGHT_M)).toFixed(1),extras:[]};
  }
  const def=TEST_KINDS[test.kind]||TEST_KINDS.custom;
  return def.calc(raw||{},testCtx())||{primary:null,extras:[]};
}
function entryPrimary(entry,test){
  if(entry.override!=null)return entry.override;
  return calcResult(test,entry.raw).primary;
}
function syncBmi(){
  const w=getTest("t_weight"),b=getTest("t_bmi");
  if(!w||!b)return;
  b.entries=w.entries.map(we=>{
    const kg=entryPrimary(we,w);
    const existing=b.entries.find(x=>x.date===we.date);
    return{date:we.date,raw:{kg},override:existing?existing.override:null};
  });
}
function testProgress(test){
  const es=sortedEntries(test);if(!es.length||test.goal==null)return null;
  const last=entryPrimary(es[0],test),first=entryPrimary(es[es.length-1],test);
  if(last==null||first==null)return null;
  let pct;
  if(test.goal>=first)pct=(last-first)/((test.goal-first)||1)*100;
  else pct=(first-last)/((first-test.goal)||1)*100;
  pct=Math.max(0,Math.min(100,pct));
  return{pct,last};
}
function testCard(test){
  const es=sortedEntries(test);
  const last=es[0],prev=es[1];
  const lastVal=last?entryPrimary(last,test):null;
  const prevVal=prev?entryPrimary(prev,test):null;
  let delta="";
  if(lastVal!=null&&prevVal!=null){
    const d=lastVal-prevVal,sign=d>0?"+":"";
    delta=`<span class="delta ${d>0?"up":d<0?"down":""}">${sign}${(Math.round(d*100)/100).toString().replace(".",",")}</span>`;
  }
  let due="";
  if(test.cadence&&last){
    const days=Math.round((Date.now()-new Date(last.date+"T12:00:00"))/864e5);
    if(days>=test.cadence)due=`<span class="pill" style="background:var(--warn-bg);color:var(--warn-text)">${t("dueNow")}</span>`;
    else due=`<span class="xs">${test.cadence-days} ${t("daysLeft")}</span>`;
  }
  const vals=es.slice(0,8).reverse().map(e=>entryPrimary(e,test)).filter(v=>v!=null);
  const mx=Math.max(...vals,1),mn=Math.min(...vals,0);
  const spark=vals.length>1?`<div class="spark">${vals.map((v,i)=>
    `<i class="${i===vals.length-1?"last":""}" style="height:${Math.max(10,((v-mn)/((mx-mn)||1))*88+12)}%"></i>`).join("")}</div>`:"";
  let goalBar="";
  if(test.goal!=null){
    const p=testProgress(test);
    if(p)goalBar=`<div class="xs" style="margin-top:8px">${t("goal")} ${String(test.goal).replace(".",",")} ${esc(test.unit)}
      · ${t("remaining")} ${(Math.round(Math.abs(test.goal-p.last)*100)/100).toString().replace(".",",")} ${esc(test.unit)}</div>
      <div class="donebar"><i style="width:${p.pct}%"></i></div>`;
  }
  const overridden=last&&last.override!=null;
  return `<div class="card tap" onclick="openTest('${test.id}')">
    <div class="row"><div class="grow">
      <div class="t" style="font-size:14px">${esc(test.name)}</div>
      <div class="xs" style="margin-top:4px">${last?fmtD(last.date):t("noData")} ${due}
        ${overridden?`<span class="xs" style="color:var(--amber)">· ${t("manual")}</span>`:""}</div>
    </div><div style="text-align:right">
      <div class="metric-v">${lastVal!=null?String(lastVal).replace(".",","):"—"}</div>
      <div class="xs">${esc(test.unit)} ${delta}</div>
    </div></div>${spark}${goalBar}</div>`;
}
function renderTests(){
  let h=`<div class="note">${t("testsSub")}</div>`;
  tests().forEach(ts=>{h+=testCard(ts);});
  h+=`<button class="addset" onclick="editTestDef()">+ ${t("addTest")}</button>`;
  $("#v-tests").innerHTML=h;
}
window.openTest=function(id){
  if(CTX.testId!==id)CTX.testEditIdx=null;
  CTX.testId=id;
  const test=getTest(id);if(!test)return;
  const def=TEST_KINDS[test.kind]||TEST_KINDS.custom;
  const isBmi=test.kind==="bmi";
  let h=`<h2>${esc(test.name)}</h2>`;
  if(def.injury)h+=`<div class="note warn">⚠️ ${t("warnFascia")}</div>`;
  if(!isBmi){
    h+=`<div class="sec" style="margin-top:0">${t("newValue").toUpperCase()}</div>`;
    def.fields.forEach(fd=>{
      const label=(test.kind==="custom"&&test.unit)?test.unit:t(fd.l);
      h+=`<div class="field"><label class="lab">${esc(label)}</label>
        <input class="inp" id="tf_${fd.k}" type="text" ${fd.type==="text"?"":'inputmode="decimal"'}
          autocomplete="off" placeholder="—"></div>`;
    });
    h+=`<div class="field"><label class="lab">${t("date")}</label>
      <input class="inp" id="tDate" type="date" value="${iso(new Date())}"></div>
    <button class="btn" id="tAdd">${t("addValue")}</button>`;
  }else{
    h+=`<div class="note">${t("bmiNote")}</div>`;
  }
  h+=`<div class="grid g2" style="margin-top:16px">
    <div class="field" style="margin-bottom:0"><label class="lab">${t("goal")}</label>
      <input class="inp" id="tGoal" type="text" inputmode="decimal" autocomplete="off"
        value="${test.goal!=null?String(test.goal).replace(".",","):""}" placeholder="—"></div>
    <div class="field" style="margin-bottom:0"><label class="lab">${t("mCad")}</label>
      <input class="inp" id="tCad" type="text" inputmode="decimal" autocomplete="off"
        value="${test.cadence||""}" placeholder="28"></div>
  </div>
  <button class="btn ghost sm" id="tGoalSave">${t("save")}</button>`;
  h+=`<div class="sec">${t("history").toUpperCase()}</div>`;
  const es=sortedEntries(test);
  if(!es.length)h+=`<div class="xs" style="padding:4px 2px 12px">${t("noData")}</div>`;
  es.forEach((e,i)=>{
    const r=calcResult(test,e.raw);
    const primary=e.override!=null?e.override:r.primary;
    const overridden=e.override!=null;
    const editing=CTX.testEditIdx===i;
    h+=`<div class="card" style="padding:10px 12px"><div class="row"><div class="grow">
        <div class="t" style="font-size:14px">${primary!=null?String(primary).replace(".",","):"—"} ${esc(test.unit)}
          ${overridden?`<span class="xs" style="color:var(--amber)">· ${t("manual")}</span>`:""}</div>
        <div class="xs" style="margin-top:2px">${fmtD(e.date)}</div>
        ${(r.extras||[]).length?`<div class="xs" style="margin-top:4px">${r.extras.map(x=>
          `${t(x.l)}: ${String(x.v).replace(".",",")}${x.u?" "+x.u:""}`).join(" · ")}</div>`:""}
      </div>
      <button class="mini-btn" onclick="toggleTestEdit(${i})">✎</button>
      ${!isBmi?`<button class="del-btn" onclick="delTestVal('${test.id}',${i})">✕</button>`:""}
      </div>
      ${editing?`<div style="margin-top:9px;display:flex;gap:7px">
        <input class="inp" id="ovIn" type="text" inputmode="decimal" autocomplete="off"
          value="${overridden?String(e.override).replace(".",","):""}"
          placeholder="${r.primary!=null?String(r.primary).replace(".",","):"—"}">
        <button class="btn sm" style="width:auto;padding:10px 14px" onclick="saveOverride(${i})">${t("save")}</button>
      </div>
      ${overridden?`<button class="btn ghost sm" style="margin-top:7px" onclick="clearOverride(${i})">${t("useCalc")}</button>`:""}`:""}
      </div>`;
  });
  if(test.kind==="custom")
    h+=`<button class="btn ghost sm" style="margin-top:14px;color:var(--red);border-color:var(--red)"
      onclick="delTestDef('${test.id}')">${t("delTest")}</button>`;
  sheet(h);
  if(!isBmi){
    $("#tAdd").onclick=()=>{
      const raw={};
      def.fields.forEach(fd=>{
        raw[fd.k]=fd.type==="text"?$("#tf_"+fd.k).value.trim():num($("#tf_"+fd.k).value);
      });
      const hasAny=def.fields.some(fd=>fd.type==="text"?raw[fd.k]:raw[fd.k]!=null);
      if(!hasAny){toast(t("needValue"));return;}
      test.entries.push({date:$("#tDate").value||iso(new Date()),raw,override:null});
      if(test.id==="t_weight")syncBmi();
      save();CTX.testEditIdx=null;openTest(id);renderHome();renderTests();toast(t("saved"));
    };
  }
  $("#tGoalSave").onclick=()=>{
    test.goal=num($("#tGoal").value);
    test.cadence=num($("#tCad").value)||0;
    save();toast(t("saved"));openTest(id);renderTests();
  };
};
window.toggleTestEdit=function(i){CTX.testEditIdx=(CTX.testEditIdx===i)?null:i;openTest(CTX.testId);};
window.saveOverride=function(i){
  const test=getTest(CTX.testId);const es=sortedEntries(test);const target=es[i];
  if(!target)return;
  const v=num($("#ovIn").value);
  if(v==null){toast(t("needValue"));return;}
  target.override=v;
  save();CTX.testEditIdx=null;openTest(CTX.testId);renderHome();renderTests();
};
window.clearOverride=function(i){
  const test=getTest(CTX.testId);const es=sortedEntries(test);const target=es[i];
  if(!target)return;
  target.override=null;
  save();CTX.testEditIdx=null;openTest(CTX.testId);renderHome();renderTests();
};
window.delTestVal=function(id,i){
  const test=getTest(id);const es=sortedEntries(test);const target=es[i];
  if(!target)return;
  test.entries=test.entries.filter(x=>x!==target);
  if(id==="t_weight")syncBmi();
  save();openTest(id);renderHome();renderTests();
};
window.editTestDef=function(id){
  const isNew=!id;
  const test=isNew?{id:"ct_"+Date.now(),kind:"custom",name:"",unit:"",cadence:28,goal:null,entries:[]}:getTest(id);
  sheet(`<h2>${isNew?t("addTest"):t("editTest")}</h2>
  <div class="field"><label class="lab">${t("mName")}</label>
    <input class="inp" id="etN" type="text" value="${esc(test.name)}" placeholder="Movilidad de tobillo"></div>
  <div class="field"><label class="lab">${t("mUnit")}</label>
    <input class="inp" id="etU" type="text" value="${esc(test.unit)}" placeholder="cm"></div>
  <div class="field"><label class="lab">${t("mCad")}</label>
    <input class="inp" id="etC" type="text" inputmode="decimal" value="${test.cadence||""}" placeholder="28"></div>
  <button class="btn" id="etS">${t("save")}</button>`);
  $("#etS").onclick=()=>{
    const n=$("#etN").value.trim();
    if(!n){toast(t("needName"));return;}
    test.name=n;test.unit=$("#etU").value.trim();test.cadence=num($("#etC").value)||0;
    if(isNew)tests().push(test);
    save();closeSheet();renderTests();renderHome();toast(t("saved"));
  };
};
window.delTestDef=function(id){
  if(!confirm(t("delTestConfirm")))return;
  DB.tests=tests().filter(x=>x.id!==id);
  save();closeSheet();renderTests();renderHome();
};

/* ============================================================
   Fotos
   ============================================================ */
function photos(){if(!DB.photos)DB.photos=[];return DB.photos;}
window.pickPhoto=function(){$("#photoInput").click();};
function handlePhoto(ev){
  const f=ev.target.files[0];if(!f)return;
  const rd=new FileReader();
  rd.onload=()=>{
    const img=new Image();
    img.onload=()=>{
      const MAX=900;
      let w=img.width,hh=img.height;
      if(w>hh&&w>MAX){hh=hh*MAX/w;w=MAX;}
      else if(hh>MAX){w=w*MAX/hh;hh=MAX;}
      const cv=document.createElement("canvas");cv.width=w;cv.height=hh;
      cv.getContext("2d").drawImage(img,0,0,w,hh);
      const data=cv.toDataURL("image/jpeg",0.7);
      photos().unshift({id:Date.now(),date:iso(new Date()),data});
      try{save();toast(t("photoAdded"));}
      catch(e){photos().shift();toast(t("photoFull"));}
      renderHome();
    };
    img.src=rd.result;
  };
  rd.readAsDataURL(f);
  ev.target.value="";
}
window.openPhoto=function(id){
  const p=photos().find(x=>x.id===id);if(!p)return;
  sheet(`<h2>${fmtD(p.date)}</h2>
    <img src="${p.data}" style="width:100%;border-radius:14px;display:block">
    <button class="btn ghost sm" style="margin-top:14px;color:var(--red);border-color:var(--red)"
      onclick="delPhoto(${id})">${t("delPhoto")}</button>`);
};
window.delPhoto=function(id){
  DB.photos=photos().filter(x=>x.id!==id);save();closeSheet();renderHome();
};

/* ============================================================
   Home
   ============================================================ */
function renderHome(){
  const d=DB.draft;
  const off=CTX.wk||0;
  let h="";

  /* anillo semanal */
  h+=`<div class="card week">
    <div class="row" style="align-items:center;gap:16px">
      <div style="flex:none">${ringSVG(off)}</div>
      <div class="grow">
        <div class="t" style="font-size:14px">${off===0?t("thisWeek"):off===-1?t("lastWeek"):fmtD(weekKey(off))}</div>
        <div class="xs" style="margin-top:4px">${t("ringHelp")}</div>
        <div class="wk-nav">
          <button onclick="wkNav(-1)">‹</button>
          ${off!==0?`<button onclick="wkNav(0,true)">${t("today")}</button>`:""}
          <button onclick="wkNav(1)" ${off>=0?"disabled":""}>›</button>
        </div>
      </div>
    </div>
    ${weekLabels(off)}
  </div>`;

  /* programa activo */
  h+=`<div class="sec">${t("programs").toUpperCase()}</div>
  <div class="card tap" onclick="openProgramSwitcher()">
    <div class="row"><div class="grow">
      <div class="t" style="font-size:14px">${esc(activeProgram().name)}</div>
      ${activeProgram().note?`<div class="s">${esc(activeProgram().note)}</div>`:""}
      <div class="xs" style="margin-top:5px">${DB.programs.length} ${t("programs").toLowerCase()}</div>
    </div><div style="color:var(--mist);font-size:22px">›</div></div></div>`;

  /* sesión en curso */
  if(d){
    const day=dayById(d.dayId);
    h+=`<div class="sec">${t("inProgress").toUpperCase()}</div>
    <div class="card tap" onclick="go('session')">
      <div class="row"><div class="grow">
        <div class="t">${esc(day.day)} · ${esc(day.code)}</div>
        <div class="s">${esc(day.title)}</div></div>
        <span class="pill">${countDone(d)}</span></div>
      <div class="donebar"><i style="width:${pctDone(d)}%"></i></div></div>
    <button class="btn" onclick="go('session')">${t("resume")}</button>`;
  }

  /* métricas */
  h+=`<div class="sec" style="display:flex;align-items:center;gap:8px">
    <span class="grow">${t("metrics").toUpperCase()}</span>
    <button class="mini-btn" onclick="openMetricManager()">✎</button>
  </div>`;
  h+=`<div class="mgrid">`;
  metrics().forEach(m=>{h+=metricTile(m);});
  h+=`<button class="card mtile mtile-add" onclick="editMetric()">+</button>`;
  h+=`</div>`;

  /* fotos */
  h+=`<div class="sec">${t("photos").toUpperCase()}</div>`;
  const ph=photos();
  h+=`<div class="card"><div class="photo-strip">
    <button class="photo-add" onclick="pickPhoto()">+</button>
    ${ph.slice(0,12).map(p=>`<img src="${p.data}" onclick="openPhoto(${p.id})">`).join("")}
  </div>${ph.length?"":`<div class="xs" style="margin-top:9px">${t("photoHelp")}</div>`}</div>`;

  /* sesiones */
  h+=`<div class="sec">${t("pickDay").toUpperCase()}</div>`;
  const wd=new Date().getDay();
  const todayIdx=(wd+6)%7;
  const todayId=DAY_ORDER[todayIdx];
  const apDays=activeProgram().days;
  if(!apDays.length){
    h+=`<div class="empty"><div class="big">◇</div><div class="t">${t("noDays")}</div></div>
    <button class="btn ghost sm" onclick="editProgramDef('${activeProgram().id}')">+ ${t("addDay")}</button>`;
  }
  apDays.forEach(day=>{
    const n=DB.logs.filter(x=>x.dayId===day.id).length;
    const isT=day.dow!=null?day.dow===todayIdx:day.id===todayId;
    h+=`<div class="card tap" onclick="startDay('${day.id}')">
      <div class="row"><div class="grow">
        <div class="t">${esc(day.day)} ${isT?`<span class="pill" style="margin-left:6px">${t("today").toLowerCase()}</span>`:""}</div>
        <div class="s">${esc(day.title)}</div>
        <div class="xs" style="margin-top:5px">${esc(day.code)} · ${n} ${t("sessions")}</div>
      </div>
      <button class="mini-btn" onclick="event.stopPropagation();openEditor('${day.id}')">✎</button>
      <div style="color:var(--mist);font-size:22px;margin-left:6px">›</div></div></div>`;
  });
  $("#v-home").innerHTML=h;
  const pi=$("#photoInput");if(pi)pi.onchange=handlePhoto;
}
window.wkNav=function(dir,abs){
  if(abs){CTX.wk=0;}else{CTX.wk=(CTX.wk||0)+dir;if(CTX.wk>0)CTX.wk=0;}
  renderHome();
};
function countDone(d){const total=allEx(d.dayId).length;
  const done=new Set(d.entries.map(e=>e.exId)).size;return done+"/"+total;}
function pctDone(d){const total=allEx(d.dayId).length||1;
  const done=new Set(d.entries.map(e=>e.exId)).size;return Math.round(done/total*100);}
function allEx(dayId){const day=dayById(dayId);const a=[];
  day.blocks.forEach(b=>b.ex.forEach(e=>a.push(e)));return a;}

window.startDay=function(id){
  if(DB.draft&&DB.draft.dayId!==id){
    if(!confirm("Tienes una sesión sin terminar. ¿La descartas?"))return;
    DB.draft=null;
  }
  if(!DB.draft){openCheckin(id);}else{go("session");}
};

/* ============================================================
   Check-in
   ============================================================ */
function openCheckin(dayId){
  const v={sleep:3,heel:0,groin:0,energy:3};
  const scale=(k,from,to)=>{let s="";
    for(let i=from;i<=to;i++)s+=`<button data-k="${k}" data-v="${i}"
      class="${v[k]===i?"on":""}">${i}</button>`;return s;};
  sheet(`<h2>${t("checkin")}</h2>
    <div class="note">${t("checkinSub")}</div>
    <div class="field"><label class="lab">${t("sleep")}</label>
      <div class="scale" id="sc-sleep">${scale("sleep",1,5)}</div>
      <div class="xs" style="margin-top:5px">${t("sleepH")}</div></div>
    <div class="field"><label class="lab">${t("heel")}</label>
      <div class="scale" id="sc-heel">${scale("heel",0,5)}</div>
      <div class="xs" style="margin-top:5px">${t("painH")}</div></div>
    <div class="field"><label class="lab">${t("groin")}</label>
      <div class="scale" id="sc-groin">${scale("groin",0,5)}</div>
      <div class="xs" style="margin-top:5px">${t("painH")}</div></div>
    <div class="field"><label class="lab">${t("energy")}</label>
      <div class="scale" id="sc-energy">${scale("energy",1,5)}</div>
      <div class="xs" style="margin-top:5px">${t("energyH")}</div></div>
    <button class="btn" id="ciGo">${t("toSession")}</button>`);
  $("#sheetC").querySelectorAll(".scale button").forEach(b=>{
    b.onclick=()=>{const k=b.dataset.k;v[k]=+b.dataset.v;
      b.parentElement.querySelectorAll("button").forEach(x=>x.classList.remove("on"));
      b.classList.add("on");};});
  $("#ciGo").onclick=()=>{
    DB.draft={dayId,programId:DB.activeProgramId,date:today(),checkin:v,signal:computeSignal(v,dayId),entries:[],rpe:{},checks:{}};
    save();closeSheet();go("session");
  };
}

/* ============================================================
   Session capture
   ============================================================ */
function renderSession(){
  const d=DB.draft;
  if(!d){go("home");return;}
  const day=dayById(d.dayId);
  $("#title").textContent=day.day+" · "+day.code;
  $("#actBtn").style.display="flex";
  $("#actBtn").textContent="✎";
  $("#actBtn").onclick=()=>openEditor(d.dayId);
  const s=d.signal;
  let h=`<div class="signal ${s.level}">
    <div class="hd"><span class="dot"></span>${esc(s.label)}</div>
    <div class="body">${esc(s.reasons.join(". "))}.</div>
    <ul>${s.acts.map(a=>`<li>${esc(a)}</li>`).join("")}</ul></div>`;

  if(day.nutri&&day.nutri.length){
    h+=`<div class="card" style="margin-bottom:13px">
      <div class="lab" style="margin-bottom:7px">${t("nutrition")}</div>
      <div class="s" style="margin:0">${day.nutri.map(x=>`• ${esc(x)}`).join("<br>")}</div></div>`;
  }

  day.blocks.forEach(b=>{
    const vis=b.ex.filter(e=>!e.hidden);
    if(!vis.length)return;
    h+=`<div class="sec">${esc(b.n.toUpperCase())}${b.ref?` <span class="pill" style="margin-left:6px;font-weight:600">referencia</span>`:""}</div>`;
    if(b.ref){
      h+=`<div class="card" style="padding:4px 0">`;
      vis.forEach(ex=>{
        const on=!!(d.checks&&d.checks[ex.id]);
        h+=`<div class="refrow ${on?"on":""}" onclick="toggleCheck('${ex.id}')">
          <div class="ck">${on?"✓":""}</div>
          <div class="grow"><div class="t" style="font-size:14px">${esc(ex.name)}</div>
            <div class="xs" style="margin-top:2px">${esc(ex.p)}</div>
            ${ex.w?`<div class="xs" style="margin-top:5px;color:var(--warn-text)">⚠️ ${esc(ex.w)}</div>`:""}
          </div></div>`;
      });
      h+=`</div>`;
      return;
    }
    const checks=vis.filter(e=>e.type==="check");
    const rest=vis.filter(e=>e.type!=="check");
    if(checks.length){
      h+=`<div class="card" style="padding:4px 0">`;
      checks.forEach(ex=>{
        const on=!!(d.checks&&d.checks[ex.id]);
        h+=`<div class="refrow ${on?"on":""}" onclick="toggleCheck('${ex.id}')">
          <div class="ck">${on?"✓":""}</div>
          <div class="grow"><div class="t" style="font-size:14px">${esc(ex.name)}</div>
            <div class="xs" style="margin-top:2px">${esc(ex.p)}</div>
            ${ex.w?`<div class="xs" style="margin-top:5px;color:var(--warn-text)">⚠️ ${esc(ex.w)}</div>`:""}
          </div></div>`;
      });
      h+=`</div>`;
    }
    rest.forEach(ex=>{
      const ents=d.entries.filter(e=>e.exId===ex.id);
      const open=CTX.open===ex.id;
      const filled=ents.filter(e=>rowHasData(e,ex));
      const doneEx=filled.length&&filled.every(e=>e.done);
      h+=`<div class="exc ${ex.w?"warn":""} ${open?"open":""} ${doneEx?"complete":""}" id="ex-${ex.id}">
        <div class="exc-h" onclick="toggleEx('${ex.id}')">
          <div class="n">${doneEx?"✓":(filled.length||"")}</div>
          <div class="grow"><div class="t">${esc(ex.name)}</div>
            <div class="xs" style="margin-top:3px">${esc(ex.p)}
              ${ex.uni?`<span class="side-tag" style="margin-left:5px">2 lados</span>`:""}
              ${(d.rpe||{})[ex.id]!=null?`<span class="side-tag" style="margin-left:5px">RPE ${String(d.rpe[ex.id]).replace(".",",")}</span>`:""}</div></div>
          <div style="color:var(--mist);font-size:18px">${open?"⌃":"⌄"}</div></div>
        <div class="exc-b">${open?setsHTML(ex,ents):""}</div></div>`;
    });
  });
  h+=rpeSummary(d,day);
  h+=`<button class="btn" style="margin-top:18px" onclick="finishSession()">${t("finish")}</button>
      <button class="btn ghost sm" style="margin-top:9px" onclick="discardSession()">${t("discard")}</button>`;
  $("#v-session").innerHTML=h;
}
window.toggleCheck=function(exId){
  const d=DB.draft;if(!d.checks)d.checks={};
  d.checks[exId]=!d.checks[exId];save();renderSession();
};
window.toggleEx=function(id){CTX.open=CTX.open===id?null:id;renderSession();
  if(CTX.open){const el=document.getElementById("ex-"+id);
    if(el)setTimeout(()=>el.scrollIntoView({block:"center",behavior:"smooth"}),60);}};

function rowsOf(exId){
  const d=DB.draft;
  if(!d.entries)d.entries=[];
  let r=d.entries.filter(x=>x.exId===exId).sort((a,b)=>a.set-b.set);
  if(!r.length){const e={exId,set:0};d.entries.push(e);r=[e];}
  r.forEach((x,i)=>x.set=i);
  return r;
}
function setsHTML(ex,ents){
  const f=FIELDS[ex.type]||FIELDS.tech;
  const rows=rowsOf(ex.id);
  let h="";
  if(ex.w)h+=`<div class="note warn" style="margin-top:11px">⚠️ ${esc(ex.w)}</div>`;
  h+=`<div class="presc">${t("prescribed")}: ${esc(ex.p)}</div>`;
  h+=histHTML(ex);
  rows.forEach((e,i)=>{
    h+=`<div class="setrow ${e.done?"is-done":""}">
      <div class="setlab">${t("setN")} ${i+1}
        ${e.done?`<span class="saved">✓ ${t("doneMark")}</span>`:""}
        <button class="del-btn" onclick="delSet('${ex.id}',${i})" aria-label="${t("delSet")}">✕</button></div>`;
    if(ex.uni){
      h+=sideBlock(ex,f,i,"L",e);
      h+=sideBlock(ex,f,i,"R",e,true);
    }else{
      h+=inputsRow(ex,f,i,"",e);
    }
    h+=`<button class="btn sm ${e.done?"ghost":""}" style="margin-top:10px"
        onclick="markSet('${ex.id}',${i})">${e.done?t("undo"):t("done")}</button></div>`;
  });
  h+=`<button class="addset" onclick="addSet('${ex.id}')">+ ${t("addSet")}</button>`;
  if(HAS_RPE[ex.type]){
    const cur=(DB.draft.rpe||{})[ex.id];
    h+=`<div class="rpe-box"><div class="lab">${t("rpeEx")}</div>
      <input class="inp rpe-in" type="text" inputmode="decimal" autocomplete="off"
        id="rpe_${ex.id}" value="${cur==null?"":String(cur).replace(".",",")}" placeholder="7,5">
      <div class="xs" style="margin-top:6px">${t("rpeHelp")}</div></div>`;
  }
  h+=`<button class="btn" style="margin-top:14px" onclick="saveExercise('${ex.id}')">${t("saveEx")}</button>`;
  return h;
}
window.addSet=function(exId){
  const d=DB.draft;const rows=rowsOf(exId);
  const prev=rows[rows.length-1];
  const e={exId,set:rows.length};
  if(prev){const ex=findEx(exId).ex;(FIELDS[ex.type]||FIELDS.tech).forEach(fd=>{
    if(ex.uni){e["l_"+fd.k]=prev["l_"+fd.k];e["r_"+fd.k]=prev["r_"+fd.k];}
    else e[fd.k]=prev[fd.k];});}
  d.entries.push(e);save();renderSession();
};
window.delSet=function(exId,i){
  const d=DB.draft;
  const rows=rowsOf(exId);
  if(rows.length<=1){
    const only=rows[0];
    Object.keys(only).forEach(k=>{if(k!=="exId"&&k!=="set")delete only[k];});
    save();renderSession();toast(t("cleared"));return;
  }
  const target=rows[i];
  d.entries=d.entries.filter(x=>x!==target);
  d.entries.filter(x=>x.exId===exId).sort((a,b)=>a.set-b.set).forEach((x,j)=>x.set=j);
  save();renderSession();toast(t("setDeleted"));
};
function sideBlock(ex,f,i,side,e,isR){
  const lbl=side==="L"?t("left"):t("right");
  return `<div style="margin-top:${isR?"9px":"4px"}">
    <div class="setlab"><span class="side-tag">${lbl}</span>
      ${isR?`<button class="copy-btn" onclick="copySide('${ex.id}',${i})">${t("sameL")}</button>`:""}</div>
    ${inputsRow(ex,f,i,side,e)}</div>`;
}
function inputsRow(ex,f,i,side,e){
  const cls=f.length===1?"":f.length===2?"g2":"g3";
  return `<div class="grid ${cls}">`+f.map(fd=>{
    const id=`in_${ex.id}_${i}_${side}_${fd.k}`;
    let val=e?(side?e[side.toLowerCase()+"_"+fd.k]:e[fd.k]):null;
    if(val==null)val="";
    return `<div><input class="inp mini" type="text" inputmode="decimal"
      autocomplete="off" autocorrect="off" spellcheck="false"
      id="${id}" value="${esc(String(val).replace(".",","))}" placeholder="—"
      oninput="stashRow('${ex.id}',${i})">
      <div class="unit">${t(fd.l)}</div></div>`;
  }).join("")+`</div>`;
}
window.copySide=function(exId,i){
  const ex=findEx(exId).ex,f=FIELDS[ex.type]||FIELDS.tech;
  f.forEach(fd=>{
    const a=document.getElementById(`in_${exId}_${i}_L_${fd.k}`);
    const b=document.getElementById(`in_${exId}_${i}_R_${fd.k}`);
    if(a&&b)b.value=a.value;});
  stashRow(exId,i);
};
/* Escritura silenciosa: protege ante un recargado de Safari a media sesión */
window.stashRow=function(exId,i){
  const ex=findEx(exId).ex;const f=FIELDS[ex.type]||FIELDS.tech;
  const e=rowsOf(exId)[i];if(!e)return;
  e.uni=!!ex.uni;e.type=ex.type;
  f.forEach(fd=>{
    if(ex.uni){["L","R"].forEach(sd=>{
      const el=document.getElementById(`in_${exId}_${i}_${sd}_${fd.k}`);
      if(el)e[sd.toLowerCase()+"_"+fd.k]=num(el.value);});
      delete e[fd.k];
    }else{
      const el=document.getElementById(`in_${exId}_${i}__${fd.k}`);
      if(el)e[fd.k]=num(el.value);
      delete e["l_"+fd.k];delete e["r_"+fd.k];
    }});
  e.date=today();save();
};
function rowHasData(e,ex){
  const f=FIELDS[ex.type]||FIELDS.tech;
  return f.some(fd=>ex.uni
    ?(e["l_"+fd.k]!=null||e["r_"+fd.k]!=null)
    :e[fd.k]!=null);
}
window.markSet=function(exId,i){
  stashRow(exId,i);
  const ex=findEx(exId).ex;const e=rowsOf(exId)[i];
  if(!e.done&&!rowHasData(e,ex)){toast(t("nothing"));return;}
  e.done=!e.done;save();renderSession();
};
window.stashRpe=function(exId){
  const el=document.getElementById("rpe_"+exId);if(!el)return;
  const d=DB.draft;if(!d.rpe)d.rpe={};
  let v=num(el.value);
  if(v==null){delete d.rpe[exId];save();return true;}
  if(v<1||v>10){toast(t("rpeRange"));return false;}
  d.rpe[exId]=Math.round(v*10)/10;save();return true;
};
window.saveExercise=function(exId){
  const ex=findEx(exId).ex;
  rowsOf(exId).forEach((e,i)=>stashRow(exId,i));
  if(HAS_RPE[ex.type]&&!stashRpe(exId))return;
  const d=DB.draft;
  const rows=rowsOf(exId).filter(e=>rowHasData(e,ex));
  const empty=rowsOf(exId).filter(e=>!rowHasData(e,ex));
  if(!rows.length&&!(d.rpe||{})[exId]){toast(t("nothing"));return;}
  // descarta filas vacías sobrantes
  if(rows.length)d.entries=d.entries.filter(x=>x.exId!==exId||rowHasData(x,ex));
  d.entries.filter(x=>x.exId===exId).forEach((x,j)=>{x.set=j;x.done=true;});
  save();CTX.open=null;renderSession();toast(t("exSaved"));
};
function sessionRpe(rpeMap){
  const v=Object.values(rpeMap||{}).filter(x=>typeof x==="number");
  if(!v.length)return null;
  return v.reduce((a,b)=>a+b,0)/v.length;
}
function rpeSummary(d,day){
  const avg=sessionRpe(d.rpe);
  const n=Object.keys(d.rpe||{}).length;
  if(avg==null)return `<div class="card" style="margin-top:18px"><div class="lab" style="margin:0">${t("rpeDay")}</div>
    <div class="xs" style="margin-top:5px">${t("rpeNone")}</div></div>`;
  return `<div class="card rpe-day" style="margin-top:18px">
    <div class="row"><div class="grow">
      <div class="lab" style="margin:0">${t("rpeDay")}</div>
      <div class="xs" style="margin-top:4px">${n} ${t("exercises")}</div></div>
    <div class="rpe-big">${avg.toFixed(1).replace(".",",")}</div></div>
    <div class="xs" style="margin-top:8px">${t("rpeCarry")}</div></div>`;
}
window.discardSession=function(){
  if(!confirm(t("confDiscard")))return;
  DB.draft=null;save();go("home");
};
window.finishSession=function(){
  const d=DB.draft;
  if(!d.entries.length&&!(d.checks&&Object.values(d.checks).some(Boolean))&&!Object.keys(d.rpe||{}).length){
    toast(t("nothing"));return;}
  d.entries=d.entries.filter(x=>{const r=findEx(x.exId);return r&&rowHasData(x,r.ex);});
  DB.logs.push({id:Date.now(),dayId:d.dayId,programId:d.programId||DB.activeProgramId,date:d.date,
    checkin:d.checkin,signal:d.signal.level,entries:d.entries,
    checks:d.checks||{},rpe:d.rpe||{},avgRpe:sessionRpe(d.rpe)});
  DB.draft=null;save();toast(t("finished"));go("home");
};

/* ============================================================
   Exercise editor
   ============================================================ */
const TYPE_LABELS={load:"Carga (kg + reps)",bw:"Peso corporal (reps)",
  iso:"Isométrico (segundos)",dist:"Distancia (m + kg)",plyo:"Contactos",
  sprint:"Sprint (m + tiempo)",tech:"Técnica / tiempo (min)",check:"Solo casilla"};

function openEditor(dayId){
  const day=dayById(dayId);
  const owner=programOfDay(dayId);
  let h=`<h2>${esc(day.day)} · ${t("editDay")}</h2>
   <div class="note">${t("editNote")}</div>`;
  if(!day.blocks.length)h+=`<div class="xs" style="padding:2px 2px 10px">${t("noBlocks")}</div>`;
  day.blocks.forEach((b,bi)=>{
    h+=`<div class="sec" style="margin-top:16px;display:flex;align-items:center;gap:8px">
      <span class="grow">${esc(b.n.toUpperCase())}
      ${b.ref?`<span class="pill" style="margin-left:6px;font-weight:600">referencia</span>`:""}</span>
      <button class="mini-btn" onclick="delBlock('${dayId}',${bi})">✕</button></div>`;
    b.ex.forEach((ex,ei)=>{
      h+=`<div class="card" style="padding:11px 12px;${ex.hidden?"opacity:.45":""}">
        <div class="row" style="align-items:flex-start">
          <div class="grow">
            <div class="t" style="font-size:14px">${esc(ex.name)}${ex.hidden?" · oculto":""}</div>
            <div class="xs" style="margin-top:3px">${esc(ex.p)}</div>
            <div class="xs" style="margin-top:4px">${esc(TYPE_LABELS[ex.type]||ex.type)}${ex.uni?" · 2 lados":""}</div>
          </div>
          <div style="display:flex;flex-direction:column;gap:4px">
            <button class="mini-btn" onclick="moveEx('${dayId}',${bi},${ei},-1)">↑</button>
            <button class="mini-btn" onclick="moveEx('${dayId}',${bi},${ei},1)">↓</button>
          </div>
        </div>
        <div style="display:flex;gap:7px;margin-top:9px">
          <button class="btn ghost sm" style="flex:1" onclick="editEx('${dayId}',${bi},${ei})">${t("edit")}</button>
          <button class="btn ghost sm" style="flex:1;color:var(--red);border-color:var(--red)"
            onclick="hideEx('${dayId}',${bi},${ei})">${ex.hidden?t("restore"):t("hide")}</button>
        </div></div>`;
    });
    h+=`<button class="addset" onclick="editEx('${dayId}',${bi},-1)">+ ${t("addEx")}</button>`;
  });
  h+=`<button class="addset" style="margin-top:9px" onclick="openAddBlock('${dayId}')">+ ${t("addBlock")}</button>`;
  if(owner&&DEFAULT_PROGRAMS.find(p=>p.id===owner.id))
    h+=`<button class="btn ghost" style="margin-top:20px" onclick="resetDay('${dayId}')">${t("resetDay")}</button>`;
  sheet(h);
}
window.openAddBlock=function(dayId){
  let ref=false;
  sheet(`<h2>${t("addBlock")}</h2>
  <div class="field"><label class="lab">${t("blockName")}</label>
    <input class="inp" id="nbName" type="text" placeholder="Core"></div>
  <div class="field"><label class="lab">${t("exType")}</label>
    <div class="scale" id="nbRef">
      <button data-v="0" class="on">${t("blockNormal")}</button>
      <button data-v="1">${t("blockRefOpt")}</button>
    </div></div>
  <button class="btn" id="nbSave">${t("save")}</button>`);
  $("#nbRef").querySelectorAll("button").forEach(b=>b.onclick=()=>{
    ref=b.dataset.v==="1";
    $("#nbRef").querySelectorAll("button").forEach(x=>x.classList.remove("on"));
    b.classList.add("on");});
  $("#nbSave").onclick=()=>{
    const n=$("#nbName").value.trim();
    if(!n){toast(t("needName"));return;}
    const day=dayById(dayId);
    const block={n,ex:[]};
    if(ref)block.ref=true;
    day.blocks.push(block);
    save();openEditor(dayId);toast(t("saved"));
  };
};
window.delBlock=function(dayId,bi){
  if(!confirm(t("confDelBlock")))return;
  const day=dayById(dayId);
  day.blocks.splice(bi,1);
  save();openEditor(dayId);
};
window.moveEx=function(dayId,bi,ei,dir){
  const b=dayById(dayId).blocks[bi];
  const j=ei+dir;if(j<0||j>=b.ex.length)return;
  const x=b.ex[ei];b.ex[ei]=b.ex[j];b.ex[j]=x;
  save();openEditor(dayId);
};
window.hideEx=function(dayId,bi,ei){
  const ex=dayById(dayId).blocks[bi].ex[ei];
  ex.hidden=!ex.hidden;save();openEditor(dayId);
  toast(ex.hidden?t("hidden"):t("restored"));
};
window.resetDay=function(dayId){
  const owner=programOfDay(dayId);
  if(!owner)return;
  const defProg=DEFAULT_PROGRAMS.find(p=>p.id===owner.id);
  if(!defProg){toast(t("noOriginal"));return;}
  const orig=defProg.days.find(d=>d.id===dayId);
  if(!orig)return;
  if(!confirm(t("confReset")))return;
  const i=owner.days.findIndex(d=>d.id===dayId);
  owner.days[i]=JSON.parse(JSON.stringify(orig));
  save();closeSheet();renderSession();toast(t("restored"));
};
window.editEx=function(dayId,bi,ei){
  const b=dayById(dayId).blocks[bi];
  const isNew=ei<0;
  const ex=isNew?{id:"cust_"+Date.now(),name:"",type:"load",p:"",uni:false}:b.ex[ei];
  let h=`<h2>${isNew?t("addEx"):t("edit")}</h2>
  <div class="field"><label class="lab">${t("exName")}</label>
    <input class="inp" id="edName" type="text" value="${esc(ex.name)}" placeholder="Sentadilla búlgara"></div>
  <div class="field"><label class="lab">${t("exPresc")}</label>
    <input class="inp" id="edP" type="text" value="${esc(ex.p)}" placeholder="4 × 6 / pierna · 2 min · RPE 7-8"></div>
  <div class="field"><label class="lab">${t("exType")}</label>
    <select class="inp" id="edType">${Object.entries(TYPE_LABELS).map(([k,v])=>
      `<option value="${k}"${ex.type===k?" selected":""}>${esc(v)}</option>`).join("")}</select></div>
  <div class="field"><label class="lab">${t("exSides")}</label>
    <div class="scale" id="edUni">
      <button data-v="0" class="${!ex.uni?"on":""}">${t("oneEntry")}</button>
      <button data-v="1" class="${ex.uni?"on":""}">${t("twoSides")}</button>
    </div>
    <div class="xs" style="margin-top:6px">${t("sidesHelp")}</div></div>
  ${ex.w?`<div class="note warn">⚠️ ${esc(ex.w)}</div>`:""}
  <button class="btn" id="edSave">${t("save")}</button>`;
  sheet(h);
  let uni=!!ex.uni;
  $("#edUni").querySelectorAll("button").forEach(btn=>btn.onclick=()=>{
    uni=btn.dataset.v==="1";
    $("#edUni").querySelectorAll("button").forEach(x=>x.classList.remove("on"));
    btn.classList.add("on");});
  $("#edSave").onclick=()=>{
    const nm=$("#edName").value.trim();
    if(!nm){toast(t("needName"));return;}
    ex.name=nm;ex.p=$("#edP").value.trim();ex.type=$("#edType").value;ex.uni=uni;
    if(isNew)b.ex.push(ex);
    save();openEditor(dayId);toast(t("saved"));
  };
};

/* ============================================================
   History (inline + progress view)
   ============================================================ */
function exHistory(exId){
  const out=[];
  DB.logs.slice().reverse().forEach(lg=>{
    const es=lg.entries.filter(e=>e.exId===exId);
    let rp=(lg.rpe||{})[exId];
    if(rp==null){const old=es.map(e=>e.rpe).filter(Boolean);
      rp=old.length?Math.max(...old):null;}
    if(es.length||rp!=null)out.push({date:lg.date,sets:es,rpe:rp});
  });
  return out;
}
function entUni(s,ex){return s.uni!=null?s.uni:!!ex.uni;}
function bestOf(sets,ex){
  const f=(FIELDS[ex.type]||FIELDS.tech)[0].k;
  let b=null;
  sets.forEach(s=>{
    const vals=entUni(s,ex)?[s["l_"+f],s["r_"+f]]:[s[f]];
    vals.forEach(v=>{if(v!=null&&(b==null||v>b))b=v;});
  });
  return b;
}
function histHTML(ex){
  const h=exHistory(ex.id).slice(0,6);
  if(!h.length)return `<div class="xs" style="padding:2px 0 10px">${t("noHist")}</div>`;
  const f=(FIELDS[ex.type]||FIELDS.tech)[0];
  let s=`<div class="lab" style="margin-top:4px">${t("lastLoads")}</div><div class="hist">`;
  h.forEach(r=>{
    const b=bestOf(r.sets,ex);
    const rp=r.rpe!=null?"RPE "+r.rpe:"";
    s+=`<div class="hcol"><div class="d">${fmtD(r.date)}</div>
      <div class="v">${b==null?"—":b}<span style="font-size:10px;font-weight:500"> ${t(f.l)}</span></div>
      <div class="r">${esc(rp)}</div></div>`;
  });
  s+=`</div>`;
  const last=h[0];const k=f.k;
  if(last.sets.some(x=>entUni(x,ex))){
    let lv=null,rv=null;
    last.sets.forEach(x=>{if(x["l_"+k]!=null)lv=Math.max(lv==null?-1e9:lv,x["l_"+k]);
                          if(x["r_"+k]!=null)rv=Math.max(rv==null?-1e9:rv,x["r_"+k]);});
    if(lv!=null&&rv!=null&&Math.max(lv,rv)>0){
      const diff=Math.abs(lv-rv)/Math.max(lv,rv)*100;
      const ok=diff<10;
      s+=`<div class="asym ${ok?"ok":"no"}">${ok?t("asymOk"):t("asymNo")} · ${diff.toFixed(0)}%
        (${t("left")} ${lv} / ${t("right")} ${rv})</div>`;
    }
  }
  return s;
}

function renderProgress(){
  if(!DB.logs.length){
    $("#v-progress").innerHTML=`<div class="empty"><div class="big">◈</div>
      <div class="t">${t("noSess")}</div><div class="s">${t("noSessSub")}</div></div>`;return;}
  const showAll=!!CTX.progAll;
  let h=`<div class="note">${t("progSub")}</div>
    <button class="btn ghost sm" style="width:auto;padding:8px 14px;margin-bottom:13px"
      onclick="toggleProgAll()">${showAll?t("onlyActiveProg"):t("allPrograms")}</button>`;
  const progList=showAll?DB.programs:[activeProgram()];
  let anyCards=false;
  progList.forEach(prog=>{
    prog.days.forEach(day=>{
      const ids=[];day.blocks.forEach(b=>b.ex.forEach(e=>{
        if(exHistory(e.id).length)ids.push(e);}));
      if(!ids.length)return;
      anyCards=true;
      h+=`<div class="sec">${showAll?esc(prog.name)+" · ":""}${esc(day.day.toUpperCase())}</div>`;
      ids.forEach(ex=>{
        const hist=exHistory(ex.id);
        const f=(FIELDS[ex.type]||FIELDS.tech)[0];
        const vals=hist.slice(0,8).reverse().map(r=>bestOf(r.sets,ex)).filter(v=>v!=null);
        const mx=Math.max(...vals,1);
        h+=`<div class="card tap" onclick="openEx('${ex.id}')">
          <div class="row"><div class="grow"><div class="t">${esc(ex.name)}</div>
          <div class="xs" style="margin-top:3px">${hist.length} ${t("sessions")} · ${t("lastLoads").toLowerCase()} ${bestOf(hist[0].sets,ex)??"—"} ${t(f.l)}</div></div></div>
          <div class="spark">${vals.map((v,i)=>
            `<i class="${i===vals.length-1?"last":""}" style="height:${Math.max(8,v/mx*100)}%"></i>`).join("")}</div>
        </div>`;
      });
    });
  });
  if(!anyCards){
    if(!showAll){
      const otherCount=DB.logs.filter(l=>l.programId&&l.programId!==activeProgram().id).length;
      h+=otherCount
        ?`<div class="empty"><div class="big">◈</div><div class="t">${t("noProgProgress")}</div>
           <div class="s">${otherCount} ${t("sessions")} ${t("otherProgHint")}</div></div>`
        :`<div class="empty"><div class="big">◈</div><div class="t">${t("noProgProgress")}</div></div>`;
    }else{
      h+=`<div class="empty"><div class="big">◈</div><div class="t">${t("noProgProgress")}</div></div>`;
    }
  }
  $("#v-progress").innerHTML=h;
}
window.toggleProgAll=function(){CTX.progAll=!CTX.progAll;renderProgress();};
window.openEx=function(id){
  const r=findEx(id);if(!r)return;
  const ex=r.ex,hist=exHistory(id);
  const f=(FIELDS[ex.type]||FIELDS.tech);
  let h=`<h2>${esc(ex.name)}</h2>
    <div class="note">${esc(r.program.name)} · ${esc(r.day.day)} · ${esc(ex.p)}</div>`;
  hist.forEach(rec=>{
    h+=`<div class="card"><div class="row"><div class="grow">
      <div class="t" style="font-size:14px">${fmtD(rec.date)}</div></div></div>`;
    rec.sets.sort((a,b)=>a.set-b.set).forEach((s,i)=>{
      const parts=[];
      f.forEach(fd=>{
        if(ex.uni){
          const a=s["l_"+fd.k],b=s["r_"+fd.k];
          if(a!=null||b!=null)parts.push(`${t(fd.l)} ${a??"—"}/${b??"—"}`);
        }else if(s[fd.k]!=null)parts.push(`${s[fd.k]} ${t(fd.l)}`);
      });
      h+=`<div class="xs" style="margin-top:5px">${t("setN")} ${i+1} — ${esc(parts.join(" · "))||"—"}</div>`;
    });
    if(rec.rpe!=null)h+=`<div class="xs" style="margin-top:7px;font-weight:600;color:var(--accent)">RPE ${rec.rpe}</div>`;
    h+=`</div>`;
  });
  sheet(h);
};

/* ============================================================
   Programas — cambiar, crear, duplicar, renombrar, borrar
   ============================================================ */
function programSwitcherHTML(){
  let h=`<h2>${t("programs")}</h2>`;
  DB.programs.forEach(p=>{
    const active=p.id===DB.activeProgramId;
    const n=DB.logs.filter(l=>l.programId===p.id).length;
    h+=`<div class="card ${active?"":"tap"}" ${active?"":`onclick="setActiveProgram('${p.id}')"`}>
      <div class="row"><div class="grow">
        <div class="t" style="font-size:14px">${esc(p.name)}
          ${active?`<span class="pill" style="margin-left:6px">${t("activePill")}</span>`:""}</div>
        ${p.note?`<div class="s">${esc(p.note)}</div>`:""}
        <div class="xs" style="margin-top:4px">${p.days.length} ${t("daysWord")} · ${n} ${t("sessions")}</div>
      </div>
      <div style="display:flex;gap:6px">
        <button class="mini-btn" onclick="event.stopPropagation();editProgramDef('${p.id}')">✎</button>
        <button class="mini-btn" onclick="event.stopPropagation();duplicateProgram('${p.id}')">⧉</button>
        <button class="del-btn" onclick="event.stopPropagation();delProgram('${p.id}')">✕</button>
      </div></div></div>`;
  });
  h+=`<button class="addset" onclick="editProgramDef()" ${DB.programs.length>=10?"disabled":""}>+ ${t("addProgram")}</button>`;
  return h;
}
window.openProgramSwitcher=function(){sheet(programSwitcherHTML());};
window.setActiveProgram=function(id){
  if(DB.activeProgramId===id){closeSheet();return;}
  if(DB.draft&&DB.draft.programId&&DB.draft.programId!==id){
    if(!confirm(t("confSwitchProg")))return;
    DB.draft=null;
  }
  DB.activeProgramId=id;save();closeSheet();render();toast(t("saved"));
};
window.editProgramDef=function(id){
  const isNew=!id;
  if(isNew&&DB.programs.length>=10){toast(t("maxPrograms"));return;}
  const p=isNew?{id:"prog_"+Date.now(),name:"",note:"",builtin:false,days:[]}:getProgram(id);
  let h=`<h2>${isNew?t("addProgram"):t("editProgram")}</h2>
  <div class="field"><label class="lab">${t("progName")}</label>
    <input class="inp" id="pgN" type="text" value="${esc(p.name)}" placeholder="Fuerza en casa"></div>
  <div class="field"><label class="lab">${t("progNote")}</label>
    <input class="inp" id="pgNote" type="text" value="${esc(p.note||"")}" placeholder="—"></div>
  <button class="btn" id="pgSave">${t("save")}</button>`;
  if(!isNew){
    h+=`<div class="sec">${t("daysWord").toUpperCase()}</div>`;
    if(!p.days.length)h+=`<div class="xs" style="padding:2px 2px 10px">${t("noDays")}</div>`;
    p.days.forEach((day,di)=>{
      h+=`<div class="card" style="padding:11px 12px">
        <div class="row" style="align-items:flex-start">
          <div class="grow">
            <div class="t" style="font-size:14px">${esc(day.day)}</div>
            <div class="xs" style="margin-top:3px">${esc(day.code||"")} ${esc(day.title||"")}</div>
            <div class="xs" style="margin-top:3px">${day.blocks.length} ${t("blocksWord")}</div>
          </div>
          <div style="display:flex;flex-direction:column;gap:4px">
            <button class="mini-btn" onclick="moveDay('${p.id}',${di},-1)">↑</button>
            <button class="mini-btn" onclick="moveDay('${p.id}',${di},1)">↓</button>
          </div>
        </div>
        <div style="display:flex;gap:7px;margin-top:9px">
          <button class="btn ghost sm" style="flex:1" onclick="openEditor('${day.id}')">${t("edit")}</button>
          <button class="btn ghost sm" style="flex:1;color:var(--red);border-color:var(--red)"
            onclick="delDay('${p.id}','${day.id}')">${t("delDay")}</button>
        </div></div>`;
    });
    h+=`<button class="addset" onclick="openAddDay('${p.id}')">+ ${t("addDay")}</button>`;
  }
  sheet(h);
  $("#pgSave").onclick=()=>{
    const n=$("#pgN").value.trim();
    if(!n){toast(t("needName"));return;}
    p.name=n;p.note=$("#pgNote").value.trim();
    if(isNew)DB.programs.push(p);
    save();editProgramDef(p.id);renderHome();toast(t("saved"));
  };
};
window.moveDay=function(programId,di,dir){
  const p=getProgram(programId);
  const j=di+dir;if(j<0||j>=p.days.length)return;
  const x=p.days[di];p.days[di]=p.days[j];p.days[j]=x;
  save();editProgramDef(programId);
};
window.delDay=function(programId,dayId){
  if(!confirm(t("confDelDay")))return;
  const p=getProgram(programId);
  p.days=p.days.filter(d=>d.id!==dayId);
  if(DB.draft&&DB.draft.dayId===dayId)DB.draft=null;
  save();editProgramDef(programId);renderHome();
};
window.openAddDay=function(programId){
  const L7=(L==="es"?["L","M","X","J","V","S","D"]:L==="pl"?["P","W","Ś","C","P","S","N"]:["M","T","W","T","F","S","S"]);
  let dow=0;
  sheet(`<h2>${t("addDay")}</h2>
  <div class="field"><label class="lab">${t("dayName")}</label>
    <input class="inp" id="ndName" type="text" placeholder="Lunes CASA"></div>
  <div class="field"><label class="lab">${t("dayCode")}</label>
    <input class="inp" id="ndCode" type="text" placeholder="MD-5"></div>
  <div class="field"><label class="lab">${t("dayTitle")}</label>
    <input class="inp" id="ndTitle" type="text" placeholder="Tren inferior"></div>
  <div class="field"><label class="lab">${t("dayDow")}</label>
    <div class="scale" id="ndDow">${L7.map((l,i)=>
      `<button data-v="${i}" class="${i===0?"on":""}">${l}</button>`).join("")}</div></div>
  <button class="btn" id="ndSave">${t("save")}</button>`);
  $("#ndDow").querySelectorAll("button").forEach(b=>b.onclick=()=>{
    dow=+b.dataset.v;
    $("#ndDow").querySelectorAll("button").forEach(x=>x.classList.remove("on"));
    b.classList.add("on");});
  $("#ndSave").onclick=()=>{
    const n=$("#ndName").value.trim();
    if(!n){toast(t("needName"));return;}
    const p=getProgram(programId);
    p.days.push({id:"day_"+Date.now(),day:n,dow,code:$("#ndCode").value.trim(),
      title:$("#ndTitle").value.trim(),blocks:[],nutri:[]});
    save();editProgramDef(programId);renderHome();toast(t("saved"));
  };
};
window.duplicateProgram=function(id){
  if(DB.programs.length>=10){toast(t("maxPrograms"));return;}
  const src=getProgram(id);if(!src)return;
  if(!confirm(t("confDuplicate")))return;
  const copy=JSON.parse(JSON.stringify(src));
  copy.id="prog_"+Date.now();
  copy.name=src.name+t("copySuffix");
  copy.builtin=false;
  let ctr=0;
  copy.days.forEach(d=>{
    ctr++;d.id="day_"+Date.now().toString(36)+"_"+ctr+"_"+Math.random().toString(36).slice(2,6);
    d.blocks.forEach(b=>b.ex.forEach(e=>{
      ctr++;e.id="ex_"+Date.now().toString(36)+"_"+ctr+"_"+Math.random().toString(36).slice(2,6);
    }));
  });
  DB.programs.push(copy);
  save();openProgramSwitcher();toast(t("duplicated"));
};
window.delProgram=function(id){
  if(DB.programs.length<=1){toast(t("minPrograms"));return;}
  if(!confirm(t("confDelProgram")))return;
  DB.programs=DB.programs.filter(x=>x.id!==id);
  if(DB.activeProgramId===id)DB.activeProgramId=DB.programs[0].id;
  if(DB.draft&&DB.draft.programId===id)DB.draft=null;
  save();openProgramSwitcher();renderHome();toast(t("saved"));
};

/* ============================================================
   Settings
   ============================================================ */
const ACCENTS=[["#6E8387","Slate Teal"],["#A4B8C4","Mist Blue"],
  ["#7C8F6E","Verde salvia"],["#8C7A94","Malva"],["#A8836B","Arcilla"],["#5E7A93","Azul acero"]];
function renderSettings(){
  const st=DB.settings;
  let h=`<div class="sec">PERFIL</div>
  <div class="card"><div class="field" style="margin:0">
    <label class="lab">${t("name")}</label>
    <input class="inp" id="setName" type="text" value="${esc(st.name)}" placeholder="Iván"></div></div>

  <div class="sec">${t("programs").toUpperCase()}</div>
  <div class="card">
    <div class="row"><div class="grow"><div class="t" style="font-size:14px">${esc(activeProgram().name)}</div>
      <div class="xs" style="margin-top:3px">${DB.programs.length} ${t("programs").toLowerCase()}</div></div>
      <button class="btn sm ghost" style="width:auto;padding:8px 15px" onclick="openProgramSwitcher()">${t("manageProg")}</button>
    </div>
  </div>

  <div class="sec">${t("lang").toUpperCase()}</div>
  <div class="card"><select class="inp" id="setLang">
    <option value="es"${L==="es"?" selected":""}>Español</option>
    <option value="en"${L==="en"?" selected":""}>English</option>
    <option value="pl"${L==="pl"?" selected":""}>Polski</option>
  </select></div>

  <div class="sec">${t("accent").toUpperCase()}</div>
  <div class="card"><div style="display:flex;gap:11px;flex-wrap:wrap">
    ${ACCENTS.map(([c,n])=>`<button onclick="setAccent('${c}')" title="${n}"
      style="width:42px;height:42px;border-radius:12px;background:${c};
      border:3px solid ${st.accent===c?"var(--ink)":"transparent"}"></button>`).join("")}
  </div></div>

  <div class="sec">${t("theme").toUpperCase()}</div>
  <div class="card"><div class="scale">
    <button onclick="setTheme('light')" class="${st.theme!=="dark"?"on":""}">${t("themeLight")}</button>
    <button onclick="setTheme('dark')" class="${st.theme==="dark"?"on":""}">${t("themeDark")}</button>
  </div></div>

  <div class="sec">LOGO</div>
  <div class="card">
    <div class="xs" style="margin-bottom:10px">${t("logoPick")}</div>
    <div style="display:flex;gap:11px">
      <img src="${LOGO_DATA['1'].i180}" onclick="setLogoVariant('1')"
        style="width:52px;height:52px;border-radius:15px;object-fit:cover;border:3px solid ${st.logoVariant==='1'?"var(--ink)":"transparent"}">
      <img src="${LOGO_DATA['2'].i180}" onclick="setLogoVariant('2')"
        style="width:52px;height:52px;border-radius:15px;object-fit:cover;border:3px solid ${st.logoVariant==='2'?"var(--ink)":"transparent"}">
    </div>
    <div class="note" style="margin:11px 0 0">${t("logoNote")}</div>
  </div>

  <div class="sec">${t("pin").toUpperCase()}</div>
  <div class="card">
    <div class="row"><div class="grow"><div class="t" style="font-size:14px">${t("pinOn")}</div>
      <div class="xs" style="margin-top:3px">${st.pinOn?"Activado":"Desactivado"}</div></div>
      <button class="btn sm ghost" style="width:auto;padding:8px 15px"
        onclick="${st.pinOn?"disablePin()":"enablePin()"}">${st.pinOn?"Quitar":"Activar"}</button>
    </div>
    ${st.pinOn?`<button class="btn ghost sm" style="margin-top:11px" onclick="enablePin()">${t("setPin")}</button>`:""}
    <div class="note" style="margin:11px 0 0">${t("resetWarn")}</div>
  </div>

  <div class="sec">DATOS</div>
  <div class="card">
    <button class="btn ghost sm" onclick="backup()">${t("backup")}</button>
    <button class="btn ghost sm" style="margin-top:9px" onclick="$('#restoreFile').click()">${t("restore")}</button>
    <input type="file" id="restoreFile" accept="application/json" style="display:none">
    <div class="note" style="margin:11px 0 0">Tus datos viven solo en este teléfono. Descarga una copia de vez en cuando: si borras Safari o cambias de móvil, no hay servidor donde recuperarlos.</div>
    <button class="btn ghost sm" style="margin-top:15px" onclick="exportCSV()">${t("exportCsv")}</button>
    <div class="note" style="margin:11px 0 0">${t("exportCsvNote")}</div>
  </div>
  <div class="xs" style="text-align:center;margin-top:22px">Pad Training · Fase 1</div>`;
  $("#v-settings").innerHTML=h;
  $("#setName").onchange=e=>{DB.settings.name=e.target.value.trim();save();};
  $("#setLang").onchange=e=>{L=e.target.value;DB.settings.lang=L;save();applyLang();render();};
  $("#restoreFile").onchange=doRestore;
}
window.setAccent=function(c){DB.settings.accent=c;save();applyAccent();render();};
function applyAccent(){
  document.documentElement.style.setProperty("--accent",DB.settings.accent);
  /* Safari a veces no repinta los elementos que heredan una custom property
     cambiada por JS si ningún otro atributo suyo cambia a la vez. Forzamos
     un reflow y, además, quien llama a esto siempre re-renderiza la vista. */
  void document.documentElement.offsetHeight;
}
window.setTheme=function(v){DB.settings.theme=v;save();applyTheme();render();};
function applyTheme(){
  if(DB.settings.theme==="dark")document.documentElement.setAttribute("data-theme","dark");
  else document.documentElement.removeAttribute("data-theme");
  void document.documentElement.offsetHeight;
}
function applyLang(){document.documentElement.lang=L;
  $("#nHome").textContent=t("today");$("#nProg").textContent=t("progress");
  $("#nTests").textContent=t("tabTests");$("#nSet").textContent=t("settings");}

window.backup=function(){
  const blob=new Blob([JSON.stringify(DB,null,2)],{type:"application/json"});
  const a=document.createElement("a");a.href=URL.createObjectURL(blob);
  a.download="pad-training-"+today()+".json";a.click();
  setTimeout(()=>URL.revokeObjectURL(a.href),1000);
};
function doRestore(e){
  const f=e.target.files[0];if(!f)return;
  const r=new FileReader();
  r.onload=()=>{try{const j=JSON.parse(r.result);
    if(!j.logs)throw 0;
    if(!confirm("Esto reemplaza todos los datos actuales. ¿Seguir?"))return;
    DB=Object.assign(JSON.parse(JSON.stringify(DEF)),j);
    migratePrograms();
    save();L=DB.settings.lang||"es";applyLang();applyAccent();applyLogo();applyTheme();go("home");toast("Datos restaurados");
  }catch(err){toast("Archivo no válido");}};
  r.readAsText(f);
}

/* ============================================================
   Exportar CSV — tablas planas para ver/analizar (no restaurables;
   para restaurar todo, usa Backup en JSON)
   ============================================================ */
function csvCell(v){
  const s=v==null?"":String(v);
  return /[",;\n\r]/.test(s)?'"'+s.replace(/"/g,'""')+'"':s;
}
function csvNum(v){return v==null?"":String(v).replace(".",",");}
function downloadCSV(rows,filename){
  const csv="\uFEFF"+rows.map(r=>r.map(csvCell).join(",")).join("\r\n");
  const blob=new Blob([csv],{type:"text/csv;charset=utf-8"});
  const a=document.createElement("a");a.href=URL.createObjectURL(blob);
  a.download=filename;a.click();
  setTimeout(()=>URL.revokeObjectURL(a.href),1000);
}
function csvExName(exId){const f=findEx(exId);return f?f.ex.name:"("+t("exDeleted")+")";}
const CSV_FIELD_KEYS=["kg","reps","secs","m","time","contacts","min"];
function buildSessionsRows(){
  const head=[t("csvDate"),t("csvProgram"),t("csvDay"),t("csvExercise"),t("csvSet"),
    t("csvSide")].concat(CSV_FIELD_KEYS.map(k=>t(k))).concat([t("rpe"),t("csvDone")]);
  const rows=[head];
  DB.logs.slice().sort((a,b)=>a.date<b.date?1:-1).forEach(lg=>{
    const day=dayById(lg.dayId);
    const prog=getProgram(lg.programId);
    const progName=prog?prog.name:"("+t("progDeleted")+")";
    const dayName=day?day.day:"("+t("dayDeleted")+")";
    const rpeMap=lg.rpe||{};
    (lg.entries||[]).forEach(e=>{
      const exName=csvExName(e.exId);
      const rpe=rpeMap[e.exId]!=null?csvNum(rpeMap[e.exId]):"";
      const done=e.done?"✓":"";
      if(e.uni){
        ["l","r"].forEach(sd=>{
          const has=CSV_FIELD_KEYS.some(k=>e[sd+"_"+k]!=null);
          if(!has)return;
          rows.push([lg.date,progName,dayName,exName,(e.set||0)+1,sd==="l"?"L":"R"]
            .concat(CSV_FIELD_KEYS.map(k=>csvNum(e[sd+"_"+k]))).concat([rpe,done]));
        });
      }else{
        rows.push([lg.date,progName,dayName,exName,(e.set||0)+1,""]
          .concat(CSV_FIELD_KEYS.map(k=>csvNum(e[k]))).concat([rpe,done]));
      }
    });
    Object.keys(lg.checks||{}).forEach(exId=>{
      if(!lg.checks[exId])return;
      rows.push([lg.date,progName,dayName,csvExName(exId),"",""]
        .concat(CSV_FIELD_KEYS.map(()=>"")).concat(["","✓"]));
    });
  });
  return rows;
}
function buildMetricsRows(){
  const head=[t("csvDate"),t("csvMetric"),t("csvValue"),t("csvUnit")];
  const rows=[head];
  customMetrics().forEach(m=>{
    (m.entries||[]).slice().sort((a,b)=>a.date<b.date?1:-1).forEach(e=>{
      rows.push([e.date,m.name,csvNum(e.value),m.unit||""]);
    });
  });
  return rows;
}
function buildTestsRows(){
  const head=[t("csvDate"),t("csvTest"),t("csvValue"),t("csvUnit")];
  const rows=[head];
  tests().forEach(ts=>{
    sortedEntries(ts).forEach(e=>{
      rows.push([e.date,ts.name,csvNum(entryPrimary(e,ts)),ts.unit||""]);
    });
  });
  return rows;
}
window.exportCSV=function(){
  downloadCSV(buildSessionsRows(),"pad-training-sesiones-"+today()+".csv");
  setTimeout(()=>downloadCSV(buildMetricsRows(),"pad-training-metricas-"+today()+".csv"),350);
  setTimeout(()=>downloadCSV(buildTestsRows(),"pad-training-expectations-"+today()+".csv"),700);
  toast(t("saved"));
};

/* ============================================================
   PIN
   ============================================================ */
let pinBuf="",pinMode="check",pinTmp="";
function drawDots(){$("#pinDots").innerHTML=[0,1,2,3].map(i=>
  `<div class="pin-dot ${i<pinBuf.length?"f":""}"></div>`).join("");}
function buildPad(){
  const keys=[1,2,3,4,5,6,7,8,9,"",0,"⌫"];
  $("#pinPad").innerHTML=keys.map(k=>
    k===""?`<div class="pin-key blank"></div>`
    :`<button class="pin-key" data-k="${k}">${k}</button>`).join("");
  $("#pinPad").querySelectorAll("button").forEach(b=>b.onclick=()=>pinKey(b.dataset.k));
}
function pinKey(k){
  if(k==="⌫"){pinBuf=pinBuf.slice(0,-1);drawDots();return;}
  if(pinBuf.length>=4)return;
  pinBuf+=k;drawDots();
  if(pinBuf.length===4)setTimeout(pinSubmit,120);
}
async function pinSubmit(){
  const h=await sha(pinBuf);
  if(pinMode==="check"){
    if(h===DB.settings.pinHash){$("#lock").classList.remove("on");pinBuf="";}
    else{$("#lock").classList.add("shake");
      setTimeout(()=>$("#lock").classList.remove("shake"),420);
      $("#lockMsg").textContent=t("wrongPin");pinBuf="";drawDots();}
  }else if(pinMode==="new"){
    pinTmp=h;pinBuf="";drawDots();pinMode="repeat";
    $("#lockMsg").textContent=t("repeatPin");
  }else if(pinMode==="repeat"){
    if(h===pinTmp){DB.settings.pinHash=h;DB.settings.pinOn=true;save();
      $("#lock").classList.remove("on");pinBuf="";toast(t("pinSet"));renderSettings();}
    else{$("#lockMsg").textContent=t("wrongPin");pinBuf="";drawDots();
      pinMode="new";setTimeout(()=>$("#lockMsg").textContent=t("newPin"),1200);}
  }
}
window.enablePin=function(){
  pinMode="new";pinBuf="";pinTmp="";drawDots();
  $("#lockMsg").textContent=t("newPin");$("#lock").classList.add("on");
};
window.disablePin=function(){
  DB.settings.pinOn=false;DB.settings.pinHash="";save();
  toast(t("pinOff"));renderSettings();
};

/* ============================================================
   Sheet
   ============================================================ */
function sheet(html){$("#sheetC").innerHTML=html;
  $("#sheetBg").classList.add("on");setTimeout(()=>$("#sheet").classList.add("on"),10);}
function closeSheet(){$("#sheet").classList.remove("on");
  setTimeout(()=>$("#sheetBg").classList.remove("on"),260);}
$("#sheetBg").onclick=closeSheet;

/* ============================================================
   Logo — dos variantes precargadas, el usuario elige en Ajustes
   ============================================================ */
const LOGO_DATA={"1":{"i180":"data:image/png;base64,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","manifest":"data:application/manifest+json;base64,eyJuYW1lIjoiUGFkIFRyYWluaW5nIiwic2hvcnRfbmFtZSI6IlBhZCBUcmFpbmluZyIsImRpc3BsYXkiOiJzdGFuZGFsb25lIiwic3RhcnRfdXJsIjoiLiIsInRoZW1lX2NvbG9yIjoiI0ZDRkFGQSIsImJhY2tncm91bmRfY29sb3IiOiIjRkNGQUZBIiwiaWNvbnMiOlt7InNyYyI6ImRhdGE6aW1hZ2UvcG5nO2Jhc2U2NCxpVkJPUncwS0dnb0FBQUFOU1VoRVVnQUFBTUFBQUFEQUNBTUFBQUJsQXB3MUFBQUFrRkJNVkVYTDQvTzkydTZzenVPUHVkQjFwYjlna0tsSWQ0ODJhSUF6WjM4eVozODBaWDR5Wm40eFpYMDNZM295Wkh3eVlub3hZM3N4WVhnd1lub3dZSGN2WVhrdVlIa3ZZSGN1WUhjdVlIWXRZSGN2WDNZdFgzWXZYWFF0WEhRc1czSXJXbkVxV0c4cFYyOG9WbTBvVld3blZHc21VMm9vVUdZbVQyVWxVbWdsVG1Ra1QyVWpUR0lqU2w0ZlFWUVJKVEFBQUFDNU5qSE9BQUFzYTBsRVFWUjQycjFkaVhxaVdKUTJMcGh5VjR4V2tCMUJVTERlLyszbWJIZERUSFhQZk5PM1VvcWE2UG52MlJkdzlPZm45ZXphS3ZRUHgvUDVRaXNJNk9aczF2RUlMOEtyY2t5UCtQanNuK2lKdzBHZXhZTXpQSTN2d2IrRWQwZjVROS8vRG9Jd2pLSXdESU1nOFAwNHJ0cnUrUmNDUno4Ui8yekR3NG8rSFQ4b3VNQS9XV2NoQU82SkpvMUY2S2VqNDRrQndBRS9MYStmVGpaKy9mdW5QYjV6R0lXQ0FIWUpzTy9DNWtjUTd3RThxODNuNmp1S21GVGM5dUFpQUM3Zlo3T0JaMDIvSmh3aDRaYWVqdkxxeWRldjJLVGJEK0ZYZ0RYQUFWN3lRWmZvY2x6TlA5UG52d2JRK2I4T1FLL2VhU05CUWZCOXVUZzc2TWlOa0Nsc09XcDRyd0RPTmdEL2RQWjlIMGtPQXdNZ3dFK0NtOE15ZU1lR1lRRGRmbjZFcmI4bzJZWmJCU0J3RklCcE9CNlZJTkhSMFFpSEFuQThHZ0FuOVp5dE1xZlRLVGdGZ1JGU0JZQSs3Uko5cjRMdUh3TjQrcisrTDJiakRRTmdOMkNUVHU1dVc4dmVaa3NaM0EwLytacHBTdHh3QmY3NThuMEtpTWZFQ3FZZmQ1RStPN3FzOXM5L0JPQlpmWDVIWjJ2dkxXbTM5VzRBUUE5S2ovNitvaWk4cUNBZ1FvSDFjVDREQ1N5NUpRalY4KzhBbnB0VmRERTc3MzZ5dFpkSGV4Zi90bXh4Tyt1bkZJb1RpZEMzOVlFbkJVQ3N0bUNKdnpiUHZ3SG81a1M1b1Y4a1FTeTJFdWdYdWc5azdMOStvdjg4d0NOTGhteVovYVk3eSswRVNvNCt1NThCVk12b2ZIbXo3MEFsR0hRMDdhZkRjYS9YWVE4UER0dnREdStPZUlPdklpSTQ0bDhCaDNBK3NVUGJDLzE3ZFhNQTFQRG1YN2lNdEY3VUNwUWN5WXBXMVE4QW5sdWduOS9nL0dMdmZ0UGZSN0FMN3ZwTk93WUxyT3MzSHRLRHkvYzNISDMzZjNWZzJiL0Q3eDVGRWZIQkFhQU80a1A0ZkFmZ3VWZ0Y1MitIbjh4NHBIczNuM3Q2V2NmV3M5YWEweS85NzlmeUVDQ1dnQlhnek1hVlBBUW93dGR6R0FEUS8vdDRDaXpSQVRFOEhzNGdlSjQzZ3pXZFRtZi8xY0lOMkNDR0UybWp6MjRCQVFBQy96a0lZTDI2b1A0SHR1akQ1aTg4SW4zNkg1R05TeithNzVSZFJRU1hrQUJjNG1NNEJDQmRYWlJUMTVibUVzODkzbmlXaU05UHVwMS8vanVCK0pUZi96U0grcFhQejRXc3o0VStuck9NMHNjeWhKTXdBQ0k5MUlQcUZVRDdLMkliZGxJRzczQ01pSHg0bS9sQlRPVmhoLy94NWdpSGVFOVA3bmFiRFQ2N1V3c2U0ak8wVml0K2FtZGVWYmViSGIrWnZJaytKdk8xRVBWYThNWUdHQ0FoQWxESVpOWDFBWFR6aUgyMk50bUh5NDdJOStaZ05nMDVmMStiRGY3eTFpRlpJS3FYWmUyRTZLT0dicURnZy8yR01SelJKQ2tsaUhBbHk2Y0w0TG04aU92UUFLSTVrYjg1RHhOL2NENVVIU2tTZHdOL3RCRnNyd0FRd2VFRkFQTDBlQ0FJY3d6RGJBQlJyQUlqQVpBZVRMUkpNblE2ZTBqKzU2bFBpSHcwZm9wQm9BN3dVNFc0eGZBZjBrdTBGQUJYaUN3RzhBT0dNTDhvRGtRQzRLdXlBWFMvSWlkY1BsNjJ1UDN6STlPeGVWME9NM3BrRW4ycmhaRVppLzZGb3A4QWJIYXU2TkNOZm5ONTdyeEFKckFNQ1FmZ05oWWhHckVIVU9Sek5ISzhiSkQremVGenVWeXVWa3Y2dElYWnZRRVE5aVliQ25HdFZxdU5oUXplRVUzUFVsNW5kZDg0NzdGUXo0aytINDl6VWdSYmhHQjlHUURkS2xMZW10d3YwZStkTmt0ZStIbjBvZW9CYmErMXNTU3c5S0hhSkM3eHR4Y01ZRWwzL01mNng0Sm9kb1BlUWJiS3Rra2FnUUVRaXlVYUdRWklCZ0g3djBQNnZ4ZWFjcUwrVThpbjNkT2ZyaEE0ZTcvQVA0WGZoc2RBUHJBQWJ2UmZ5MXBzVmhieHpwdFlERkhhNFNPQ00yZk1pZ09zeHdpZ1hVWnNnMVMrU1BRN0gyaDRRUTlvZTVlckY4MWdFVmxxZmhIWlM1VEJQdjJmdmQzWHg2dlZxM0NDR0FXSVFHWDhBb0JZTURJTU9IK0xBaFA5eEhPMStRckJwOFVQb0duRnlycUF6MXpRQjR1TUw4MWY4Q0tXT0F2RmE5Rmp3VHNBRko4amdubGtBNGhpbndHSUNXSUZPQjhpc0ovZUdSbXZKTWI1OEtYREVxR09OM3F6K0hSNVJzTER2K0srQWdLNGRGWGdoUlhzQjhFS2Nmb0F3UkFnMkVRU1R4Z1dBSUNRSXZLUUFSd3ZjN0EvNTQwdHRQM2RzNVJDVkdOSi9IQ1FzdjFpbGUxeER3RXNOaFlBclZKQXNsYXVuWmdoeVp0OC96Y0kwVVZWanFJWUVId1hDT0Q1R1NrTlJnYUFBc3crRHh0WDZEV0dJVzRRcFQwaUdjRG5WL0sxKzc0d1ZKczFEQUR0eldKbElDeUlBd3ZMUWxNT0ovVDd3ZDRJRVFDSTR5amVQUUZBOXl1VXBBZnJoQ1JBRjNuVEpkbkRuOWZTQ0gzLytjK0xOeDEvakdlYkkwaU1lcFhlVlhrS0ZqN0V2eUNGNnJuSkxZdS9UeVd2SUlEWTB0dUtINHNRUVhMb0FFQjFORVhiMDNrUEREaGFuUDFjRGhDMzZKRXFjdEo3ZGhGUFI3VEczbVd1WHpiRWkrN3dQZHhzakdFMStrdWJ6eDRNZ2h4bUFTc0FJdmh1L295ZW1LZ0dyQU9uZlF3TWdBQmkxd2Z3OS9VQ1lCNGgvUjhmbzQvUnlQdWVHdzlzRUpCbjB3QldZcGZzT0hEdkFBZ1h5QUtGQU5ZbEJBRGdCR2o3c1J4NVBnQURMam9nVzdGWHRmZC8rY0tBUVQzL3Rad25VNkNlRnlENEVnZTlzTll2a3IxZlMrYUViVkpsOTNlSDdSWVJVQ3BBTjNPbEJRd2dQanhISEVad0laSTBBQm13Y3h6VFQ3Ym96VnA4eHQ1SUEvZ1lqUzhvNEFzdFJIRGJkNU1iVVd3VHpZa044bW43bVd4Z3dUNFNRNG9BanQyb091Z29GTFFZTllDaXkrMVdRTEE3N2R1ZnY0blQ0aENPRGYyQVlKYk1BY0RTQXRDM0JHUlhiUUNTbVlFRUlmbU1BRUtLZVdJaHVMU2o4SGlSUUJVUVFBN2pYZXlZWEduRFcxOHcvUFJtY1ozWjlNTmFiOUZkazAvaldFazVOMmF5RlYySkN6dUEvQnpZQWttNUhWRUFnTmdDRUYxSCs2TmthMkNEUUlWbkM4aUZNY1Z6Zy96bHY1R2c1V3AzV1d2S3gvUXptdWFMM1hMSU9mSlQ3TmwwdnJUYmNrbVBWUmdJbDNKN3VQVThQelphRUNXajNVa0J1R0FVTkR0emdxY3pKQTFnK1EvVmdQU3gxZ3dZNDhKNzM5KzllRHVGeFZKaHp2Y091bkxKTGlEVUhZTzV0MUFzUUNYNFBUcFFEa054YUxBaENjSjZoQ0RRU2U0Q0EzcTJlN3k0SWpJTVlMTUwwckZGUHEzUkxGdHNqQmR4bkxaWVZlVUhkaXFBOEpVTEM3anJoOHdRSlFqWUdjZmhTRWxRd0dIUW5DWElMSzBNR0NZcXAvdXpBRzIyVjIva1VJOU1tRnlSa1FPZVE3eVp5cEtaL2kwYlVJWEFEM3crRGpjQ0FMQWdnRWdEK0tZd0FzS2cvbExhZ0FCV1F6SWdIa3JUdjlydDcxT1hlZ1F3WGtlYlhraGs4anc3eXpjQWZOOGdVSWVnQkZIQ0FJZ0ZJK0VSL01ZZUFiRDFPdll3c0J5cG1LMW5oaVQ2Vi9mQWdEZ2N2d0FZZjh6S2pRbTRUYks2dEJ5WmNyK2d2Sm9EQ29ib3czN3VCUW43WlFad0NoU0FiUWc2dk1kYWpQell0WTR0R1lpVmpqdVhFc1JwSDZFZUF2MzcybnVsZi93eHZXOTM0Z2o0QmluSEVHS0huRjN0dFAwODdzOWFnL2MrMDMyaXg2ZHpBSjVnbitpOEJnQ2NUejUyN29nRGFJUjJoK0cxY3hHc0RBQU5odVJuczl2N2ora0FnUEU0aVE2YmhRRkFZU20rNWU1ZzE4Y08xSFV5Q0pnREoweHF6dDhYL3dRQVVoY0FCSEdzQTJoRmc5MDc4dGthNmZSTEF6QThRUUNMemRhUHE4a1FnSTk1Y2R4dFhsTkt0dFp3djkxdFNYNlB6QUFNaFB5OTdrbDlmZjJtZGpzQ29KQ2FUU2tDT0F1QWFCQ0FYUzFEcDh4S3g1ekFuSEZuVkFNRkNBRGs2Nkg5QnlXNDd3OGFnREw2OUxhTHd5WExzankvYkE2Y1FYTHZpbndaWTBJQU5POEFkdFJQNDBobHh5UkNVbE1uQUpmTjMrcTJWdTZ0QzFjYmRoTUwzTmQ5Y1BjR0pRaVV3RCt1bG1yL1lmSHViSGFYWk1OVmZDODdjZU9QQUNoZmhFdDZhTVNCSUNkWHhrV2lrY3dwWEhvQU5vWmtwejY3R2FvejZzSVY2dUkrYUdmREFDYTM4UGVPd3ZPRnlSczN4K1RibTN4dzZnTUJ4NGw3bHpieExGWmNZd2NBOHhBQnFCclJDQ3ZYeUlUTCtYQWhBTnFqNzl4YXdRQWI3UEtjVW9YZFBteUhkWGc4THZLQTFIZ3BSdit3WFJ5eTVXdzhNbXVhYkhRcndwVG1RSUNBZUJCMkEwQVZKeEFBU3hFRCtOcjhzSFpEbFY1aGloUW5Ob2N3YVNiRDlJL1haWERjaWZGaDBZczNzNCtSU2h6d2J1VEZZc0dKM2R3OFlBYWMwSnlDRlpxSEJldEFwQUh3SWdDUWY2K1dLdVhqbElZem05Y2FtaTAvYXY5WHUyT1VGKzhBZVBmZ1RBQkkrMWVmM3hmY2ZTZnFIazNyTGNkaU80bUttQU1uY2NRRUlFL2lDMWZhd3g4QUxBVEEwaTQyMjFYK1YvSUJ3T0Y4S2Rmajl3Q09PeWswcmo1WGlkY25Id0JNYXY5b3pCN1pJalJIQ09CRUN6bVF4Tnd1RytTQUpFeTZ6dno1QzVZcU5iK1VRaGVtS0VUYmVqajY5VHNBSDdPSHY5OXQrRGMvdncvVEYvSmhUVURNd1BFTEJIQUYyLzJSWGRxSkc5Y0E0SXBocUZTSExBQmtoWTRvT2lySS9iUktna3RUdGxuWWxXZ0ZnTzhXaHlScjUyOEJkRm15VzJ5bzRvamIvMkhuREdQT2ZpWkYrSFdFWUE0MkhyVWNnenFjWE9DUkpBZ3BrQVBYUkR1eTZBMEFUcEpjQUdRN2pFWW9BR2Izd2NaZmp0NXM3YjBUb1ducWVaZkxBbnpmTHBtcDdUZjRHTUF0QWhZY3Q1aFBZbGE1M1RPQTB4bENKR3lBTVlDUUhRSDVBWm0xT2g4aUpVS0RhWXJrNDcxT0Y5Zk5PUnZjYmFJWlY3TGVhREcrOWpHTE5vdnZ5NlJQdnZaMmJSenVJWjVUZTArNXBRK0JVT0R2SVJZaU15b0F0Q01qaE9jajZjRDNacU5xQmpZUWloU0lKUTc5VnFFTkZIeWxTbkZ2RUNoVEgrM21rOUVBOFFUQTZ3REFUaVhGKzYzSkxEbHVKZzZrY1Jqd2hDQnhnR1dzRDJEK013QU83RDVOMDJ5M1N6enRqeWF3SE1MZ3NYN1JtME82OE1iWGpjTTJSUUNIclI3VzJSOHByS1pSQXd1QTlDeEhhb1pLT1BBYktmdjE2MU8xdXBZc1VVc2xRcXJzdTdMYnBkd1dPdVNURVljRUh5TWttRUhBZnprVThzRlNUdDVSRHlyUU5YbTBwL0JObDZZeGtFWUZEaUVZOVJrQXlKQUJvRWEvREFjV243YUdraXlwZEd1MVZFOXZsSnVURHRjeHpDMjdNcDMwMXRRcWRMMXpkR1NvcWp6eWFZeUtVSnhPT0MrRkxrQVZTT2Z6NkpyMmRJQkhnem1VV0d5czZxV2tLb3VsbGNaaWQ4VUNzT0JnNkxBUDR0dEVTOGJrRmNEa3cwTDNGa0VGQU9JVEpRTUhQYTEyOHFVa2dYVFA1M0ZQaWRWY0d3TEExb0RwTktyT3BDNXJMZXptMThxWkY5Z0hTVHMxQm5QV3AzODIxVld1eWV3ZGdJOXAxd0tBNENnQkJJWVBPR3ZqZjUrNFJnMzJud0ZvQkNNelQ2Z0FiSFNuZEtGN0sxWXU3NWgrM1cwLytGSGFyVW5tY1VGNDN3ZmdhYXBuczhuYmNLOXI2elR5bWZ3OWhRK3E3Qk93M2I5OHp1TWk0UUZyYkRTTnpJQXdwcFRldDRrUkVJQ3BRaXhNaDBLellMa3kxWHcvdXJhZEo5UjYzdlFGd0h5bTZQZW03d0JNdXE0dEdRQmxOUkkvY09XVHQveXlRQUN4amtkSFBKbmw3eS9raVQxT2FGYlNGN0JhWDVJQ2Y2cVdrSVFSSzVrR3dpaTA2VHBPck9iaDdCV0F0MGJDNFdEOUhvRDNiQi9YSlBUWkRLRUluYzZRU2xMaE16UUFTZ0lRMmFFRVRhaGN1RFpOU1NwMmdLMkUzV25YOC9Oa1RQVTQwK0VRcGxYWFBic3diTHZRR3dBdzg2ck84N3gxU09MMWxnRk5rVWFCNk9VQjV6V3BlQTRXVk5Xa0YvTkVBSEEwYWdaK21RTTZoYWRpalkxZ0tRMWVrWCtxaUdnRzdBNWZNY2hROThSRlUzWTlBRGc1RlZaVkZlS0xrMkVFYXp6ZG9rakM0UHpGSFBqaXdxMlFUcmNoQUtnaHE0K2wyODBBQ0FKendKUVRJY3VTUkd1MU5FMklsWXJjbVB5VkZDWUFkNVJWZ0FBeHZESmdRa09EM25ydENmMURBS2JQcm51VUZDWWN1UkJ4NFRGRVFjQXl0SmluRlRpeW1Ca2dWc2dTSWFudDdpWDFja3R4R3l2MEZBQWdSQ0pIUVp6ZENFRTNBR0JDUlFjYTVKUFhYZ1dvUlFtNlFySVNuQlNBRTNrdzY4U0lTQURFRGdlNHJFSm1OR1FuanFHSVN0ZTExVVNueGNNblNES1hVMVl5MW9laFJCQVgxYU1GTXNBR0RRSGd5VTN6MG9zR0E0QXFnNFQ5Sko3cDY4dm5zcUVHb0VRSVdDQ3QxaEdXSkRpcFZ4eXc2NkpxeEdxbGpMNlNld1dBV2lEODNPRjRTZkw2OW1pNzlRQUFRa0RMUFBVaVFHMGpFa1NGTEJ5by9vYWx0MThBcEhVR0xPQTJaY0lBZUZUMDRwRVNtLzZBZFA0RmdLNk9ia2pxamY0eUV5Q2ZQNFZ4V2xSTkZ3N1FyeUZNaGdGTXdJSjFUUVUyaUFCOHFjVURsMmJPaGdFa0JvQnNQMWtoYitaRnU1ZXErc2FwU01nRUdTeTBTYWFWdGxxQ0VCMkRLQ21xdGhta2Z6SWR4Q1gwcjBtQWlqUkJEZEFBVkpOYlZ4SmpOS01JUVBxczhjZzZxNEVBV0kyTmcxUEhza1lXZWN1akxFdTRKN3ZqdVJwZ3doWWlpdUxXelJ5aG1meTRMQVY0bERuR3lTakVaeDdHRDh5c29oUnpvdzBESUMyT2syU2t6b2dpRVpxaEdUMWEvWTJkVzJFMERkek41UURtY0xiTk5rb0hWaFJhYklNNHZVSklNWFhXNUMrTEZJQVlnQnF3RndEcXJDOG1YSld5RkFCU1lRRWdKNU1JZ0pmQytrR05vYXBhT05BZmU1eTdRSVo3VUJ3Z1ErdUhTZEdGL3h6QUdOOW4zSkVHbzNsa0FJY3ZGUU5aSTFvS1FGcWpEcE1FS1FCOCtoUUJjSFRBZEZwM2g1MlpyajF1THpwNzlMTE5Udk9BU290eDBiYlRpVTMzRHhBa1Q2TWdvc3JCd3dhbkwrM0R6a0hnanJzcURxU29BN0dJME5IbHdLNHZQVVM3R1FyR3U5TmVaNCtqY2JROU9BQkFDNm9PcmIxVnN4Mi94YUNUYUxKQVFGYmdmMzJqK2w2c004cnNhVkVGSUk0aUEwQ2RLMkFCVU9abG8zaXczV2tBcDMweU41TW9YcmJUUXJTZzFES0d6TUN1T0RPRmlHRDZoZ0hJeVRiUENFRHdHMDlmK2JKUGg3TkNvVmdBc0FnbEFJQlB3MFFKT2lDQTM2cWdhaGtkWndZVkZjeXZQWjBlam1ZMU5pbFdVbTdlSFU1KzhpQUYrZERFZlh3SWhCYzJXRVhkTHFVQUlReWs2Mjc1WHpPckdHTTBtdGIwcXdrdEZpR2ZLbDhJNEx6WjhZa0JPNmVTZm5BQWhNM2FydGhDNkxVVEFPQUt0bGs0TVZRekRwb1pHbzFmdFhwc0FMUUoyc2FRQmhERFFJMEk2UkRJQXBEVU9jcVFBcURQYXpzSUFET3liWG9BdWxtR21VYVEzQ3J0UlNjUUlVUGt0MklmQjlpeitZZGR0TFdHaGtZZnI1YkpLa2VrWUVNcGJUUW50SEx3RUlWS2ZtTGhnQTNnY2xFbm5DZ1IydG1PeXpMOTFBSkZBNEdwaTZmMjBPdXU4VW1MRzlEdkRkV2NGWmllY1oyYU1zQzZUZExzV3BiWExLWW10amFieW9iS3JHZ01aclJDQUlrTmdCRUlCMnpQNnc3NGM2cDZvdHhMeWc2enJxdVNrekZhb041djZSOUVNTEhMR0JSeWI3TVMwc3JBTnAyUkdaaG1BSmtMQU1NaFVlSXZCOERPdUFEVmNRTU9jT2F5cGpNTU1BdFBBdTN4anZGNDlQRVRnckVMWUxhZVNobUFTeTFrRjdBQ2tKZFpHTVo5OGxHSUdFQnFBSHdIRndwSEZRQ3JCYUNseHd6Z2dCUjloUWtDZUZMMkJUbFVFVkg0aXdpMzVmUUg2a2tQYkI4OVc2K3IxS05VemM2VENjUnNmaTNqd09ZQTBSdkhXNXNEYVFiaE5FN3MrdjVSS2JGQlFDZVhLTUU1YWlaOEJWSGVTUG9MRExpbDBZa3o4Sy9EVHdyd0lrU1VvTTNEbGhQbFhxSVB2emlaSmFYbHdVUnBFd0tRQ2dmU2RNVDVNTTRpaUJJYjYrT0t2aGFqNHpsS3JnMG5qMEIvSG9kMG91Zmg2L3RjVGx6Nng0NnBsQ2FZb1o5UGRxTkVlZnBTcVFCdWpXY2dTRnA0Qk1ER0FwQW02VWlLanlkdFJqZktodllHYjQ1cTZ1QndEcUswYkZwSUhsc0lJREg4SW1qSFUrNDU5SStuYTJCVGgvUEh0aGJNTlBtYzZYdnZFbjBVdUhrWlJGeUI0TmhOQWNnTUFMeE93bjZ2T1BCdHpzdmhrNFFWaXFOSkV3NTdRSEN0bThmalZtYVlnTkRUeHlDNE93eUFIRVdXNXlCZ3F2bjhSbldDNDV0RUgwZG02MUNwTVNNQUVicGR4WTZtYVNyRlhab0tRUUFuSGZ3STJYS3FNdzNTcVdUemlEekl3V2hUL25GaWtGOUJrdGdHYUZ3OTlmSWNHZkkwK1lKaCtqYlJCd2lNd0xBQU9OQmN0U05JUjlnODI1LzJxTVNCQXNEVzVpaVVTd05IbjdsTlplTXdRZ1ppeTk5bmpLZExVTm9TaEZVcU1sU2s3RE5iaGh6eUJ4S0dIb0o1cnNpbnRTVUFtZEtDRWFqdlhpalVvUVFUdWQycUd1dStmL2I1WWU4SDBTWEMvUHVrNG9zd2JPMWgxK21UeVdjTTNkaXlRMytodjRkZ05DbGpSWDZpUllnQXBBYkFYb2xRb0hLdTQxNlpIMzRSYjdROUJZSDUvZzZDeTllWFVnMndyWEZuT1lHUlo5RVBUTEMxb3cvZ2ZhYk1YbUZleGhROXN5ZllMZ0JBWVFBRUFnRG9KUUE2YnBEOXAra3ZCcUJFU21uRjNpb2hmVUV1M05sVVZ1Z2phQkVDaHptenYrZWJUdVB5UWFkcmlDSGRMeklFa0NrQU9BUmlBWEJ5WWlseDB6NGpBeHhGTU5ZSlgvaTZKSmtEQU91RTdRTVdJWGg2LzVJRE5nTHZBWUdxbHFIOUlnY0E0QWw0WVdHTFdBQWJEdjdRQzdmYlBiVTRzVXRPTysrZkVRRGJJYjd1Z2dWUUgxMGl5T1h0T0tJQytodHdzbFdEQ0J3Ty9DTUFGb1QxZzhKbkRhQm9TZ0dBbmhnak9lNG9Ed1B3L1JOa3FPbzZRZWFJYnhUOVg1YzRMVndkNkpxbXVzS3FiaUJHejZrRFlQYlBhaFlTcUhiM2E1WUlncGdCZ0JhekVHRW9jWmJkSlJFS3R6ZzF1OThxeWtTL3pSVXZ2b3dPeUhuQU5NNFR4Rm5aV2RzTVdYb0ZuQzd5SEJGMHJlMmd2WC9JQWtHdzdwcFNXSUFCRVlrUUtrSEdIS0RPZ01rSEFwb2MzOWxuSU96cGdoZUU0YUQxMkRLcVhBVkpzcXBiMi81cTNRSDE4Q0ZGVWQxY2FBTis0QWNVczJmWDFvV1JvUzNyUU1ZSXNwRzVoc3FYQW1BaVo2QlBKaUJCU3ZhVzdCd01OMlFrRWdHMFk5dGZ0ZmVZSkxVb3VyV2RZMDduZ3dDbWIrbnZIbldSNmZoenl6cVFNUUlFOEUydHdPUDVGRG9BZVBkcFRzRzlxb2pLYTVSWWdZNzgvZzA2QUVtQ0xla2pVTDRycHE1MTV3YlozakFIQmlGTVBmU0hqd3BsWGx3djZ3QndsekRrb0FNUWluNWpTa1BGM1hBdjIyOFBXcEFJdVI3NTYydi9GVVZmdXk4dVFwMEJRUDNvUERkNW1ZWGwvVkd1M2Ntc3lmb3RnQmNFcy9iSk5jY3JTU09zTEQ4Q0FGQXVWQzljQUlDYXNSQVRrQWhGUFFCNEZzNmV1djVuSFJNaHpjZERIczI5WFg0aEFOK1hFQ0xzUjlkTlhBUTQ5REVldVVtT2w3NEhNSFVibXlHbFRKQnpWRVhHQURJTklKYzFrdG44UUhRQWg0ME9FZ1h4Q1B6ZTEyUFljRXM5QjZEL0s1bCswT3hQZFB6R2E4Q0VjUXBKamhOMmZ1aktrRE1UMXpiVWhUVTBqei9HazFjTTAxbjFGUHFidWdTakF6a0FBa0FSZXBRRmdBSHFpN3dZWVFHR0crSm5OcU43aVp0NWhGOVA3cXRSZmpydkVpeVdWRFhIYTc2Y0FFU25CYmI0Smg5L1dWNFhocHlDOFdLUTR4NG5abXZKV05HZjMycTBaeUx6Mlg1VGdsVVNEaFQ1S0NJQTJncUZPS01tSWR4K0svUHYrbHdLQmVCVVQzWE5zejdSZVdoUmt1Tmw3YXJ4ei9SUE95UWZMNC9EN2t6Vkh5MEVrT0p6dTVuRFFkUUFvRmNEOERkWFZHS0ZZSVNUUTN6WnIxTW9BSmorbzNVaWtYMDJDRkFieHVHSEhsK2FaMEdvWmFqckMxRi9xTEtxMXZZbGZLWm01cGd2QjdPdWhIZ1Z6TFlQQkpDTDBRRzVPU0VBaGFBQUVjSTVOS3hPQnd4QWJNM2VQaEdLaElqa0IvS3ZVM0FKUzg4NlIrOU9WNTZEWUNpL1VkVHpFLzNyZHEwdVhvTVkxanI4RzAyZjNkTmFLaENuZ0Vxb3hRSDlQUGMzQlNvRm15RUVnRWtKSnNhK2J3QW9ENnpQSkxJWWdPZXVOSjRkN0liUjVReXFCSWEwNlg1RU1GbDM2N20rK2c2QzRBRXBMSEpQQjZpbmdMYTUxVmMyKy9SVCtLREVOUVJEU2dkQ25FYytFM2tobVZFaVhNME1ibDBBM0RPTWt0WVVkOGZoSStGaGVFajBpUVZ1RG04WEtTcFNBRW5qQ1lCVjNIMGhudktKNWxaVk5mb3QydjBVdHR6ZmxBWUFtRkY5VlVBRndQZDlTM0tNOFB2Y05jZGVaOTUwTXpYS04rMndNa1RGWTFCaktoYzl3OGtyaFBGNDFuYXBvbCt5ZVc5bUQzcjBGaVpEb0FCVlhiUGpSU1lVQ0tCdUljeDlCUUNHaEFEd0NVSHVPVkRPSlFURDVOcDByZGhyMk5WYkVYUDFPMGtMR2Zmb3ZCNkVNZGFJV3BkK3VuRFJWTy9ESVBtM0c5QmZzdzZ3ek9mK0ZnRXdvcUpnUHhEd1FBS0hFcjdGQWdRZ3d3bzA4MFdqTzFGeWZZQzk1UHBVaFJNK0NWK3VKVTd5c3BHQkZTeG5qZlg1aUJPdzYxMlZpZ0tZZWdvT1FSR0VhZHVYSGFSZjczK1JxNThpRDdabER3RExUeCtBcnptZ3o4VUVBRGk5R2FVRjJzdXVXcTlUdU1NUnBWZ0J1RmFQVnRWU1d1V3RrSHE4N3FwU1lBdUFGNFpVWU95ZUx1MUFQZXgvY3lQNkVjQ1ZxR2NBMTdZcU5RTHlBMnFIbFE0NDBrKytpKzAvUks1ZjZBWHlTbzAyWWFoVjUwSi9uS1E1WjVCZDU5aEVBQVBicncyUUFRQXlWR0Z4dDNvNnhJUHVOZzF1ZjFVcWkxL29GVzdoVDF3enFxNk1HU01BZGQ2Zmt2K2o2dmlEcndKcmp3MzBPQzFWYlJjakxSd0U1akdHT0FNV05PMEFoSmJJZCtsbkZxekRGRlNEVkxqVmtnTjdEOUlQOG9NNUtab2dTQ3FLSy84RUNLQzZLcEVhaVFyNENzQmVBK0FEUG50RlhXY3Z3T3Y1Z2FqVXVqb042UjRXNktRQ25sL0w2dllRQkJvQ0hJVGVLLzFTMmtYR29JcVQxalpFUGRBTzBvUDdYMTdaQ1REeEtFM0VBV1pCVVlnbmxoTzZJK1lBQWxMeGc5RHZtK3VsNGw0bjZaVkZCWGlOMlY0czAwZjRTZ0V2S1RHeUtsdnRBUDFPY1hyZFBVaHltSHcwL21WOUpRQkZMdklQOU1OREFRRFBFM3RHa2I1QUxQbUJHT2VVZ3dBU0hEbUY5OFFEWGZyS0FkUnlBRHJyK3dQMERBTEZMRkdsUzNvQnN2ajZacGlnMTF6WG9Yc0krTm5KcEdsdlFEdFREd1RXU0R2dFA0c0tVWXVBTklDckFJaDBVeE01RUtOZkRyUnZJd0J5M1EvclFtbW9ya1ZaVitoUXFGcWdBTUFMV1FGaTFEeFVUVTR2YndqQVZEODVtWFpNK2szMlh3Z3MxT1lMZ0JJQjNFUTdOQWNJd0VWRWlBT0wwd1VCbkp4clo4cjBLUk9LYmgyOWV4elp4ZU1rd1hqbFd0MGF4dERxOG1JNFFMNmR4b3k5N2txa1YweW9pQWdqdUpZV2dCb0NqSnBscUN4SE5BTExvNldveExGLzJ2c25IRGc5UTVibTZ3dXU0a1VPNGI5dW1GT1JqSXBqcHZDTnp5R0NETVdvSmd4VVdoUUUzczhBSmhCVm9lQm80UkNsVlN3b1pVVStjQUFEUEF0QXhBU3lHYVdMUktzTDM1N2t3aXNoQStEbXM2bFR4bEoxTmM4Z2N5QnNoeTBEYzFTaExVUzlaSldRaTA2K0JUQnB5MXFUZjJYRGlUZTVSYjRBcUdyRmtwR01FbUdIbndHQTVGQnd6VmVCRGpoZlpBQ21XV3ZJdGdVSUFKV3c1d1htM3ZDaHRTZ2s4Z0lRUEl0QkxUQ0o4TmhydGJRWHp0SUF3REZIL2cwQWtCYkQvM3BrTjJMSkNtRjR6ZjlKWkM1bTdGcG9qVFQ5NXJHQXlVcThQaUFFMkNscEFtL2p0VVJ4UWdRUTRrMm03OHR5NDNGUks1ZWJhOUxGZnVvVkhtL0VBVUpRMWlPckc2NEFpR1BRWXlMbS9HOWpMNjNkMXd5SU1oa1RtdFZSU2ljNGt3dTZGaWhPemFPYkRlYnY5dVRIN0pFV3ZmVWVBRUFBam1nQVFDa0JDTXlGTk15Z2xHb1NScmJHMmtEb0x2TlZwank3bzVuS0dBVmlBQ1lJL1hnbTJYc1dyQlVMVUQ1by8rbWZBQ0Nxd3owQmdJVVNaUUJnQjRjNUVPcXJuenVqWHBGRjhkQktvdnVVaDV3K1JoOXhUdjJUQkFzNUtVblRZMjNPWXBxOVowR2J5cjRyK1N1dU52bW9BeG9BclpHYW9rWVNBRUJpaElZdnB1OGljSXlPUzM5NkRjZFdwcCtrdXBXYmdXOHJyQTdnK0FjV2hIY2pPbGZqZjJ1elVJa2JqRk5yZlBZK2lnMkNIb0N3ejRMSTZwbS9yRFI5clBYSmVTUFl5VXdEQU9kY1hqdDltamNBK0lrRkdWTU5rbmNWQjFZNkNCUUFFaUlHRUw4QllBMnEvUTBBT3VaSFpiVzF1dHowb25HUUNWVEFqRWw3NzFrd29TQ0JEWkhpZ011QzZGaTNsS2toZ0RzREVORkFBR25VVzVwRCt0R2dBRUVtMEhUVDhZVFBvcHlFWFdsbWV1QzF1dW5XMG5DQlhmNmh3NEcrZ0VKUWtTS2JBM3dYbjI1WXE2anZoTUVBaVBzQXRHUTU5RWZ4SUFnSTdwaEdOY2ZWVmdXM2haQUZrT2FBSjlhbDUvVlBBS2FkQnFCaUlLR2NjTnpyR0VUb2dYSHJuWlU0NlFPdzdMdmpxRjU4c0JOQ1FIeU5ua3BDVEV5QmVaNGhSa3VVbDFnd3FvaEdpUHlmNFh0M1BKNDg3clVHY09XWUdpMis4c1FDb0JJaHNnQ3dJMk1BNFlBZy9XQkVVVXdRUVBkY3p5UkZiK3RDaG5wU2l1MW94SXNpYXF5YWh6ODBCOUpXQUxEMFc0RTB5MUhrTnkwblBTQkFvQU44TWdkZnI4cmhnSzI3YjNRZ2tWd0FxU3l3cnNpVk5lNEtVU3MzbzZZS0FIaTAvTHlrbWRWN0ZzeTdXcWRiUXZsVmI3K3lRamRPZkc0M0JLQzNWZ0dJQnFUZjBnd09ReE5wL1pQMkk1VlVWMVJWL2ZhR1BZbU1mSEZHU3R5NmFYNzdUZ3ZBZ05VNld3SHhFZUUzZGdoRnFHbFVtSGdmSlltakE5bmd4cnNHTkRGdGM3WmV5QUk4OThTa1lHMk4wd0FaazU4VEFJMkE3enZ2VFZEdGRaSXdsbGNLZHZvSWtxQmhIUkFPb0o3SkpFVnFBWWcxRStKSWdoMEZJSEVBeUdNd05XV2xrMGlzVlZCRFNBQVVwU3A0ZGFaZXNYNlhtRFUzaVpWTHk0QUtnRHNBWUN1RUMzV0FMUFVBQUJNclJ5clcxK1FiQkd4QzRUN0ZDYTRicDE1WTB5OFlnRlJnTWNkOFJUQWdSalFLakFCTTlDbjJuK212RkFEVVlRWmdobmdKUU1waUhzV1dLRmxTUXpqcGtjd3VhMFNnclNBb0RkZlZLaHhtVUxFb1pUZFYxYXUxa0RTdEIwYWZpZzRNS1FQZ01vUWJTZFN4QmxEM0FXU2U1d0V6OU9rZExOK08yR3Q2OWZBMUt3QWhLSzZVQ0RkMzZrZ284YUZiNEU3VEw3V1FQdlNqQ3B4bGJwdmFNcUJYVFg1RkloU1REbURiNEY3ZitoendnQU5Kck05UElSUkpYM0Vsem95dFAyUjdqMUlFc2lMMVpHNXFNUXhNQ0FoQjIrRS9td2w5Q0hoQ2FHUG45bGRGUDhYUTl6c0RBRU1LMjA5bU5IVUJFT0ZPcFVHUUpLcnE4QXBBalFFRHBRVkV1UVYxRlZWYmtYWGdXbEZhYVpWWmhpSFE2VmdBZ0wwdjFhWUZBTkJMVzU2UUoyNm9ZSUFjUUZkamlWQXFvdE1YSGtXMmlIdHY5eE9hZkdHZnhiMFRUYnVrbFZpbHdQckVFSUpuRjNyU2RWcXJ6blpwVXJCYUE3amhTa1NFNkVIVGpESkRUWVpLSExNT3VMYlNJVnNkeElsRGUwWXBKSFd5dE9nSUFJNEx5RzQzcXVEbHlOR1R2cmN0ck1RTDN1dlN0a0t5L2ZkN1pRQlErVm9CVUpRQmdIbk81d2NwRXhOclM1UEs3NlZxMDNXNmtncjlhYVlwcHdoQ0FkQzF3WklyTEE4WGdkdEpvTTd3clE5QTZBZVJBUUFoQWNCb0FyZkRBRWlUM1BQbU9UbFhWOEJqVGd4bFNFMm1CZFhNV3FMaUJlVzRTSHhva3NGdVMxQ1dYak1DZ2RDM3FYcTA0SEdyNjlLTkgxaUNrSVVhUUVNaTlCanBuUlVBbHVycVBiWjJXc05WQURKbnBTNEFyZzF4YlkzcVF5SkZQVEV5TVJTMzVnVkFiWnYvT3lHNE5ReUFaWWhFS0RYRTVYUFB5MFZ5V0d4WWRUWENUQ093UktlL1VBbFNSM3gwZGdVRUtSNjR1dHoxVzl1MThzRkNmWTBDVk5rYzRJMUFBRVl5TWdDUTJkcWJtc29DU1V1YUNmRXl1Mk9FbmtpVzNTY0FhZVpLa0pUb21BZTNXOThhMmYzSlIvTVNnZFlHUUJWSDBvQlZBREl0R1FpQUR1SytqZGY3YlE1b3M1a0R1V1Z6Y202b3UvUWJsMVJ5RktrMXVRK0JBcEY3YmZaZXJSdUx6SzJwNDFnQU1JSlJvc2xLc3IzbmhiVHJRMDRxRmV1aTkxOUhtMHAyc3J3d0lKeXRWOEU5a1NXMnFIMXhhOXpsaythd2krQ21WbFBGYWFjQWtCVktNaUVJZmhJOEIwcWJlNXNCU2xyUzFGaEpNWlVpTjVrdWhzcU5TNzl1VU5Tb3lyeDUxQTN1cjhlRHVzTTlCQlhSaXpmWDZFb0FGQXRHaVZZQ29BZk1VSlk0L2twazNqR1Vhc2ZGMGhnSnlveng3SE9ndEZKRHBRZFcvOFBwRU4vcTNtSzNTd0R1ZWRSMGJFYUpBZmRSYk9nbk0yVFJiNDRjQUdySEZma2NNV2REd2xNNHVhMHE4WlFZeXNzRzloQVFaVlhsa0srMGwwU29UdUxXQW5CLzJHWTB6VUpRZ2l5VjZOTDJXSmtUSGVRcVNsWmpTSTRLdnlpdkNTeXYyanBXS3BiUkdCNEt3STEwd0piL2lpTTNCSEdOMGs0QlFBYTBvOElpa1dRbzd3VTlZaUZWZEtrMzNpTFp0VUd1NXBvalhTWW44cWdkS1pia3diTC9ZUDlVT1NKMHg1OUt2SEJWa1FScEFIY0EwTWFaaXNheTdMcEFHYko4clFDd1hlMEFBSzBOSExybE5vQ3JYZCt4eXVTbSs5U3dNZ2hOdDZxdkFUVkhvU1JGWlpKMkZvQ203a1pkbEtmYUxlVXgyS0ZjSys0QS9ha3QrcS9yMVhaZUM4NExkWkl1RHRZQjBHajZRUUZvengwT0tCdGEzZks0ZEFDVXo5RXp6clZaekxJQ293bnRaMW03SGZ1VHlpYS9BQ2hlZWtPTzRLdnNYRnRIVG1wdkNvSFN5b29BR05veGk2bklBaldrd2xIYnRUWUhucU0vdVE3RGNIc2pZRUdoMVZZZjJDNUs2M0NoWjE3MHlsVnpsTHNUWmRrcnJKa0NBd0d3N0tQZVpObitPd2NRdGVndjA1dEhoY09BVy90bjlLZE5jZ01ndTJJNGtXbTdvNzF0b1FhTWpQUW9rbDgzdjFES3EwUmVWUmFjK0tZeUhyWXkvM0hUSmY2WEpNQUlXaFhIRGdNZU5YNExTaGRmYzB0RElUR2VGMGJ3RlFQTXJPOWJtZEV0UmFrcVd6cnJpbjl0aEp6VEZHcUprNGpjYTBVOUorMHllc01BYm1sVThTaWpBbkRGNzZGNUpsZU12b0MwbE9ZQ0lTRHlDd25TcEtyRHNtR0lWb21pM1llekRhYmRGeFhKdjc1a0tFNmdRL2s1ZGkxQVkrL0NHUEcxMmw4MFJaeDBEZ01lTlgyVlVaWEpocEpzcDZESDg5UXg3ZGQrYUVCeWt4ZXVsZSt0c25RTGcwUFUzKy9LVEJLQU84b1A3bnl0YVJiZHBoU2lUc0tIQytETzM4WDBqSysyYkJRcElNaXNrb2hzdW0xZGNtdUc1K3JVOGJYbnRXbnUxUmVzSEl1ci9MVVJldEVJUEhUTlUzTlA0MHBOWXhvSm91OGpTM1ZQbjFDVUlhcEJZZUliMjhvWU0xT1Vta3gzNnlYeWR3QzhoSmRXbk9hRXkzb0ovWm9UOXh4OW1BVUFiK1VMMWJya3FnQVFoYVh2ZVl0aVNGM2wwVlVVVlNtbnpRTk5OOS9VeXZQV1RueGpuR3hGaGxNQ1ZIc0ovUUxnWGhqNkgrSzh5MDU5cFYzQ09xamo0SG8vbnk4c29YcWwzNDB2eloya0xZWm9oY01XSE9YSlVHc3hKcm9yOGh2MXZ6RUFaTGQ1LzBrRENBQUdIemZ6cFlLWkdvOFZDTFUvbjgvVHE1S1dYRm5IL3Z5WHFZTFhaYy9ZYUxyTHVvK0FiMjhBZ0lTSGxWYnZ0NjIrU3RodkR2Mjgycm96WCt2SUFJUityTVhXSVNDSXJINW5ZUTFRV2NWN0M0RElmZjNlWEJvRUZRRzR5UTNiVGRsdzF3Qkp3SkFtUlo5K1lZRDZZczJrbGdGQjlyUkFUQUlJdHZuVkRXeEVlNGNCdkdiaUw2VEREMDJFVXAxV1N6MjZYa04ybi80SGlEL2FueDc5YmZtMHY5cTBLaGlBeEprZ0g3ZnJlbzVYQ2IvMllrdkZBTnUrSzUzdEFiZ1B1U3hsSm1zZFE5enVOWnRQeTJaYXEwemp1SG5kLzZaenYxdzJxUTBIME1kQzNuZExBY0VpTEhTZnVkWlRScStXMGE0aWMvT0tGb1U4SXZXVnpzeHZqUzRVTnRybXVIUXI0NFBYaGJ4YTgvZ3FlMUFNTUYvdkc5ZEdUYkc5RDUvY1ZLZ0ppeUN0YlN0b1RQdUFyS013VkhZd3hpVkIxbG83UUdoSWliWGtENjNIL1FhN0g2VnQ1OWdmbDM3ckM1Ynptc09ZZ29mcDBNZUErc1Q0YmMzYk1MMHFvUkJpV0NKNjFwRUlwdTExRno5ajAwWS85eGVTVFdLR2s2RjVFaW55OVdTMUtNQzllLzJLNitwYVcrVWJMa0hkSG0yVGJ2RzdxQmZyUFYvdnpSazRjSXAzdWdCZ0N1NG1zZWluUHlZbktuS0pZaTJIVDhXcEtFcXExam1mUXl2d3ZSMzRqdTVuanRQVzBwK1Z2SldMbUUwUnJxMnYxWmI3aGZzbHVGdSsycjVaZkJMUmxzK2xrSytDVWw4SkZaZ2J2Z3hWWUliRUF2NEdzamkvOVNwMkJnREZFQU5mODU2WGF1QmFjWUNxbU9vaUtueHVNUDdrSEgrL3BwQlZwUjN6VllVYWxTcWhzTW1wcGJ3ZytVcy9oSkRhcVZNeUZmb05nTnZ3MTd6L2VhWmNrdGRoTUwzWDR6RmNCLyt2bGlKZnk0OUR2d1Bnei9PYXExa3VnbEhCL2UzbWxzLytjOW8xL2N3QVNNZHMrbDBBZjU2M3ROSjJ2YVNzbFJPNjF4cm12MTZhbm5lVXFtUDY2ZHlDcndZQSt1dlEzd01BL2lDOTNlNjJZMUpWVE9UZG82VWI5WTUwTDJjY3RmOXY2K0dzc3VzUjNBZnc1MW1VOTVzcXI5NXJMa3ZxV216enNQM2s0NjBWYjR6S3VZZTJMaHFqSXZ2aUVxNEJhQXh0VXovLy9BM0FuMmViVlRjSGdKcU91alhLYytwQ3g2MXArbEdNazVCWUpiY2ZGL3lXWXV2RDNmWldPSTFQMTkwTC9RTUFBRUpWM0tpY2NUZXBFdDlWQm84KzI0Vzd0MVM1ckxRcEhBcUsvKzFTQ0JRMzdvL25BTEZEQUVBVHFpdkh1U3FBWWZKVXBkN0d3VmhNSXVneTRQOUMrY1BwNE55YmJwRFVZUURBaGFhb3NYd3RyU2pqWlY3VGJ6VzJjQnNXalhjMHVzVGFxMzNWaUh2YlBmLzhLd0FBb2F2ejBtUVpUcmJkRS9xZjluSlFDeDRtc2JXRjNSSWFwMnZ6ZUVmOWp3QUlRd3VKMW8waXlWcy9WUCtiVmxyQnJ6WTJ3N3V0bFhXZzVYZC93TjQvZjZEeFJ3Q0lBVUJ3a2ZMZHVnMVNQN3pMQXdBY01JNzloS1B1WitKeC9ROVlqNWZWbUwrdnpnQUFBQUJKUlU1RXJrSmdnZz09Iiwic2l6ZXMiOiIxOTJ4MTkyIiwidHlwZSI6ImltYWdlL3BuZyJ9LHsic3JjIjoiZGF0YTppbWFnZS9wbmc7YmFzZTY0LGlWQk9SdzBLR2dvQUFBQU5TVWhFVWdBQUFnQUFBQUlBQ0FNQUFBRERwaVRJQUFBQWtGQk1WRVhGNFBHdHorU1N2Tk40cDhGbWxyQlBmcGMzYVlFelozOHhhSUF6Wlg0eVpuNHhaWDAzWW5reVpId3lZbmt4WTNzeFlYZ3dZbm93WUhjdlkzb3ZZWGd0WW5rdVlIa3ZZSGN1WUhjdllIWXNZSGd2WDNZdFgzWXZYWFF0WEhNc1czSXJXWEVxV0c4cFYyNG9WbTBvVld3blZHc21VMm9vVUdZbVQyVWxVbWdsVG1Ra1RtUWpTVjBlUVZNVEtEUUFBQUNiRlNjM0FBQ0FsVWxFUVZSNDJ1MmRoMkxpT3JPQXFjNnlvWWNBRzNBRGd5azIrLzV2ZDlTN1pObVF0aWU2OXorYkVDREU4M2xtTkpyUyt2dGU2d1pXbWFacFBCOU5KclBaWW8zV1Zsa2JzTVJ2MXE2MVlJcytnbDVtZW9MNEpPMGQxcXM1V1BMVFoyQVpYaXYrQUg0SEg1dlArV2ZXZmdOL1NId1RZWUhmdklKUGczOTVpRmFFRnY1NlF4ZDQyblMweWNFcTRKVjhOekcxM2tYMlpabWx3MkR3OU92NStmbmxSYjQrUHdCNEFnQ3Z6TXZMY3ZJOEdBVERKQzNMZDhHZzlYamg1OE9uWDArVDE3ZHR0TjNPcDJBdDFuWUV2QUhBRjVZS3l5RmRFd0RxVDZBVTVndkRZaEM0a0pwakdicFJ0WDR3K21JUkFQNWZoZ0FDQUR3QlBCckZjYlNkajM0RlFWN2V2allBdDJJWUJNOXZiMGtNL3B6MStrOElBVmc4SEFEMUFqOE9BUGJVVHdjQWY3RmVMaEVNNEtkeEhHOG52NEpoOFZoRjBIcmdyUSswL3RQck5vcmdyUS9XMjl0U2x6cjkyK2pYNHFJcVZWT3M4QUZkMnhxMXZDZ3FqUlV1ZlBGN3JFL3cwMVpVUEFJTGRvTlNkNUYzWDB6bjdHOE90U1ZkRXZ6WHY3MlJxd2N2N084QVF2RFZBTGlWWVJEOGZwVnVidU50L3dVQm9OTCtpZ0JJQ2hJczhERzJtK1VvQ0lKSE1mQVFBRzU1RUV3QXBndEp3NjlObXAvKzJXWUFuT3JmckY0cnpJQUVnUWlBck9VVkVabmVwMUxsVnorTnZ2dHFQcmVKWHdDQWZxbGVVZkRhdHkxZ0lMeDlFUURBemYvckxZNDIyL244N1FlQTl3ZmdkVGxmejViYjdYTXdmSUJQMkxyYjdRTTMvM2I3NTgveTdjOW14VVJ0RnFObEMwaUZqMTlvd1FBK3pEVjd4VDdQSkRyTmVSUi81UEUrbFFwZWY1cjRwd2pDaDR2TEZndmRZUUpFNndqWEd4QSs4ZzJqUDJCZmNQdFVBS0R1ZjQzQVIxc3FnbjQ4QUZ4UTN3Y0F5OTEvSndEa0VpM0JQOUViMkJiY1BnMkFXOW9QWnR2RmFpMTdiNm9Cb0ZKMUF1QjFlZFZMTFRsOHhoL3BFcEVSMEozSmhYbFY3UFNxZmNZVjMvN041NkpjTno1THZLWUxJYWdLZnZJclNHK2ZBZ0M4KzVlYjhYaSsvZ0hnUXdHUU5lcHFHNytPc3R1SEF3QnQvMXYwWi9GbnBXM1Q1QTlyRkQvK2dRY0FxdEt2WEs1d2tETkVZOWhXbXQ1bEJaYnlVODg0OUlvc0lMT1ZiZ0JsRUxiaUErSmw0eGVQckRkZ1E2TDR0Ymt2MEJBQUpQNFZ2WnAzQUNCR1BENEZBRmxwVkFLZ0JoSDhBYUJhZ0Y2TXh3QkFBa1R4NzZZSU5BTGdCc1MvdFd6U1RFWkErOGo0SWE0TTZVWDE4T2hxQ1YrUmhDNFllZnRtb0VWOUNZNGhheDlPZldCbWVyZnRGdjY5OUlMUkl5VU9nT3djV2dBd21GSzhncUQ4SUFDQThYK0ozeFpNd3Q4YmdNWGlud0FBUGkySWJoOEJRQmtFY2JUOXMzV0kyN1FSTk83dXFEMkYvM3J0eFJvdVJaMXpmN3AybkJkYWNXL2JnMncrRFRKait5KytrM3Fad0JQbWN1UjNxNGFDN1d1empaTFhCa3FnTGdDM0lkejRTeC85RGdBcUFuenZCTURDbmwvZ3Rid0J3TWVHd2lsRDFXVmlBSWhhd0pwQ29mNHNUcEw2VVlGV1hlZnZWL1JIZE9Sc2VSRzFoUzNyYU8ybWZTUU9UbElNTG9MTEk3WG1vdENnODByZEJyb3UxbjBBUUFTZTZ5cUJWczNiLysxTnZPVi9BUGhhQUVSUi9GWlRDYlJxT2Y5UEVZelpTdUszLzBVR0owak5sTEs1NUViQjFGTDFVbjVYUS9HckI4eldGK2g1UmZTeDFVcTA4QmIvV0kyWktkcytVd0NONTg5b1A0eWZnOXY3QUZDZ3NQOVN1ZjgvR2dDblpMOElBSTZ6d1lZQXFJbFRkZ0NBSFlpQy9EMEFHQWJiN1o5MURRUHcvd1hBY1RUMEFRQUFCSUx3NFFBZzgvL25qM2xyWHkzOGlvQ2NiRys5QlRhank1bmZlWWY0ZWJxUUZRT1prTXJJZ3YyUTFIcG9hZ1lBSnhXYXQ0VExhT1R0Q0xSOHpmK3ZFUHhLQXdCbUUvQUZBSmhNL2lFQTlPVjRJa0FEK0lLM1J3SlE5Q2NSL1lqZUxyLzFqN2ZyMjFvQ204MGNBT0JIYTJxQnh3WWhQQVh2dmZ5RFFuQS84QllVandNZzdDL2YvdndBOEowQUNOL2VndXhSQUF5RDVYSzVVZ0h3RGdCWXZhVUdGM3RtWCs0ZkczL20rU3NmallGYzJPUU5SUzBBc0N0NGV3UUE4T2h2UHA4dkxRQlVXemtuQU11bGFsZGY3QXRMY1RLQnRZYmFnazh3L2RqNFpQNFNmYUhINGVmZ3pLbFB3SitTUFY0UGdNWHNJd0NJb2pBT2dnY0FBT1UvdlRNclhuQ1dvSGhHNEgvMFlyNitZckh4eXp1cFhzK21KZnh3cFA1c05CbU5KdktiVi93aXI4L0JueXpTVWNrZC9HdGZwY1Y5eGo4NkRUQlJVQWFBL0ZST0dwSXpDOUVMWTQrb1lNdEgvdk1IQUVEUDRjREhwNWNBQS9ENkNyL25GOE53VDlKTERQK2xON2tvYy9JTmZnci9BZnlYZmpjYU1WSGhYMjhTbmdJbUpVYitDUHJMWG9DRlhMNit3di9oUDJhNTFLMk9TQWQ1RWY1NzRZdmhKY0tpSlJvQlh2QjdBWWlBSC9DcmNqUFFxcFQvNndzczcxdHNQZHcvTVhGUnNkenc3MXVOZ3FEL3Mxd3JBR3N3V2VEcmFFeWU1a0l3cEE0cUdtQURDS2pTQWExSytVK21yeStOQWNDKzFubzdlNEtpNy8wc2NUbEJHQ3kyNU5oRjlRRzhBUUM2WXhOVjZZQldwZno1NGJZamR4ZmJDQ0VzTktNZTlCb21LL1gvV1JFNlplcVVzWTg2Z0NVZzBCaXN4ZENQZUhTb0pCRXFBS0R0NE5Pd01RRFEvcyttalFHQWVuODkra2VGVHlWc0ZUL2w0MTZiTUZyQ2JZTW5BTFRFWEFBQTdBYUhUUUVZQm0rdmF5RWYxbHE5SjI1c2VXT045WGJ5UGFUZmZ4QUE3K1VYVEdCVm5EbkhtR1lSTW05UkJTQ0szcmJPb3lFSEFHR3dmZmtERUdnQUFOenFMb0wrUDIvREhXYjlrVHdFd1V5dXZ2TUg0QTA4dW5VZEQ5c0J5SU8zUCtyMmoyZkZXM0xqRVFUcjJYWTdzcmg4THZjWExmVkIweE9kN3lBK3dyNGkvek8rQi80dWtKZjJ3TWNzaHlsNE05Y2JyVXd1SURZRndybEFXUitBTW5oOW5UWUJBTzVvVFRjLzltMUhNRDR5bWJIak14b0RnTjlQOVlqSlZJalk4ZTIzR09ZemJPWkhaTW5CbkJIL2NxYUVsWlM0em1qeW9nU0U1RGdqL0EzUEUveDc0SC9veTlDWDdETk5jS3laeDUxbmNxd2FQMVg0TVhwd05oazhtVUVJbm1iTDJXelJBQUI0TG5DckM4QU55UC8xanhyMUYrdGlqTG54NENHVCtLSHNSL1FpU1dzQTF2UHp5OGkyNE04SHY0VUZJenZvd2NIVDA0Q3U1OTgwNXZmN04zNFlpT2daUHYwSnJ3SDY3Ky9mK0YvOGp2QmYrQmg5bXZoYndCdmdYNEMvZ1oveDkyLytnZURqK09VRCtqSDVCK1lmbnNTZjJIZUdDeUJnTnlJL25Vekc0QXNUQk1GTURiMUxBS2o5QnJnZkVOa0phTm5rLy9MbnovcTFOZ0NMYmFTSkg3STdtNHdHNU0rZG9UOFQzeWo4WGlXWFE3NDM2WTk1ckJkMm5aUFlJQUN3ZDhCMDRLOUdJeTVQS01Kbi9BWDhNWHl2d1lBSEN5bGE5SHY4OXVEK0p0K3dmK212UmkrWUNGTGxuNWQrTlpzWm9zYWNEUGdFOFNud2E0R01NYURBWUFBWHl5WUFoSW1WQUFzQXdhL053cHF5NERpLzJ6NnBubkV3bWswTXZGY3M0OFdieUxlTGNHdng5MmIza2YraUw4Q0hCc3B0eXQvVHFNQk03eWIrRlpLaHF2Zm5qcEdCZVZJWmVIclRIUEhOYXNNNkMzQWpRTHNQNG4vaTUyRWRBTUxnYmI2dUN3RFlyUTc2VnVsUEpvOEVRRklnV0t2SUFFd21uZ0t6QUNEZnpwOEJ3SVE2R0FvRHdhZ0JBRUFIV0JKRVdtWUg4TzExcVJlaU90STN3Rjg1V2k5VThjOG05ZTc3QnkvMVBoN0orc1BqMWVwVHZVWFB4VThkUDZQWU5XL1c5QkhBODVUTjBXeTdFRzlQQ0lCcUJxRE1JMkdGVVdMZUNyU01Ec0NmemVLdExnQnJ5ZmozZ3dFMyt6OEEzQU1BM0N0TUJqSUMyN29BUkhHOE5Mb0JKZ0NDNSsxS1ZQeVZBRUR4VDJUeFQyWjMzZnoyNitLOFp1ckRDZ0ExUHhFRlFMY1dOUUJRam9WckFzRHR3MndrSWhDTTEzenpiWElESTMzRmt6OStBT1JCdUZqWEFtQXkyd2E5cml4KzBSUi9FQUE4WWVoZkJBQjhLeUd3ckF0QUZKbU1RTXZnQUd3MzlpeGtFd1RnVCt4eitaTzd2NEd5Rmk0TXZabnRDRlRlL1ZhVlhkdUFlTzhtYk5LZG1VV3RCb1VxYjRXcGlFQXd3N2xsY21LSUU0RFlZQVJhaGdoUXVLNER3R3drMy82REJzci9Cd0RyeHhKZk5wdk1Cb0lTR0t6ckFRRGNnR0UxQUdtd1hSbDdlcHQ2ZVV5bjAvRjRFVWkzLytET3kweitadnNPcVhKclpkMnlEZXA4dHBFek9pbkVvZHhvZVNIZ2FReGhxSGdtS29HMzVWcVRrUFgrUjN2QnNncUFXN0JkckdzQU1KNU9CZTh2NEpIUU93Q1FYbSt6clo4TWdCQ0gva2dBb0VzeENZVEE0TFlPQURCUitPWUdBQmlBN2RxY2tVd0JFTTNBZER3ZjkvbnRQNW9NRkpVNG05VlhwYU5LQjlGYmRFSzBlS0FoSUw2UDltdk5kejBWUGpsZ1VCR3dhM0lEQU9MWDFyOWJmaEgxS2dVQ3BrUmNMaU1nZktjSEJGdnFEaUJlMWdCZ0hBNjQrZzhXSmptT3Zpd0FocERMdHdCZ0RPNDZqc0JrdTY0QlFKVDhLbDBBM0lLM2NHbXNSRlF6UDlGaHJyajc2dzlnM0VjK3RhUG5kdXdTeVJyVEtDSjl6OVVnOEdONmQvTXZZVWROOEt6SCtFYjhwZlJQZTJLTG5DN3AvTkxESUkrL1FEMUVWRGFzdWdVWmo4ZFRRUW44Tm1vQW14R0l0b29Sa0FFWS90cUdwcnZmblBvcnlSLzcvajhBY0FDY3QvWWRBT0RGdHdOUGRRQUk0MStoSFFDZ0FHd3RhVXdORHBqOHUwejkvMVlXMXBjT09WUkl4eXhoWThCR2ZjY0dBRWhtUzM4cEZUci9ML25UN3JCcXBqUUNkVTlzckdwY2MxOFErdTE4d0VDVkJsRDhRQW1BNGZQUzF0TFpBRURFb2ovOVlEYjZBZUJqQVFEMlJTREFINEFvK2gzYUFDaURhR092U1ZRalFOdCt0eXQ1L3ppdFFsNWNWejZKaXBPbmFXanExQWFCR3BPMWFQMkJjWkhmS2Y1cVdmandzMnZWaHJySzE1Y1RMU3NFK2lkMitwR1dlTkpZSUVDdEMvRGVDb29BREY5dDNyOE9nQ2ovR1RyMk00aS9BZ0Q1VWxJQUxQZkNEd0FxQU1BWERMZ2ZzUFlGSUlwZWhtWUF5dURORmdEUzlnTUxRZjhUOC85TXI1VDFpb2tTY0FGZ3ZKeXFzR3VJSDJmd1NlelJwK3FpaDkvOXRuOUtBd0ErWXEvNDRKVVJLaE1DWURjd2Y2SUVqRkRUSURrbHpBYUFwQUphZ2djNDM2eTNmZ0FzSXViLzk2bjUvd0hnd3dHWVRxY2pUc0JXQjhBTVFmZ2FtZ0FvZ3MxOGJUZ0FVcXVTa2Y1WDVQOWNkYTJzdGtGK2l2QkVMRGN4RTlOanFSczI3WGVKMjFUNVNmUjc2Y1ZQbGV1M0h3Q09nSmlZYmxycnNCeE81WjNPS1FIQnkxYWZRb1pteitvQWlPZkNMYTRBbnFjckd3RHlUa0NVLzFxUS96OEFnUExpcncrQVFNRFNQSWJPcEFPRWdIQ0xLNER0NXMrMkVnQ1UvejBSN0QrcWtyQmVNZEVOckVTQVl6RGdvcUNiUzV5WWo1VTN2M29rV1Y4K3BoSGRUTDRYTlg4S2Jkc3EyQXVQeFkyVkRZVEhBMEEzZ2tqODgrbWNob1FDS0NNZjhVc2JnUmFQQWN6bmIxdkhZQmVoMjB0ZjhQOCtBZ0R1RjlEL1diYlBaZ0NFMy9WZ0FOQUxQaGVBK1hUOXhBblllQUVRUlR3YzJPTEh3Tk9sRlFENFgxb0tNdGt5K2EvUVp4WTJUTzhBZ0JoUWhsL0JTODJyTmZEWHo1OEtBUDcxZGxQdzNnQk1sM1EzT05pdS9RQUlFNllDS0FEaGM2VHNBYkh2cDFWOVQxanlkMzh5MWpiTkpta3FGOTlHaVBJU3Q0Z3dHTkxCQTY3WHFaQ1hhUEZOZ1NzeE11V2gvWW5ENEIwRnNQc3VjaFdDNVl4U2pnVWk4Y00xblZNQ2xsdFBMeUJoQmNNdHBnQlcyMG9BVVA0ZmN3QmgzY0lQQUY4QkFFWkFFUG02Z2V4UXNFWHpBTFpyWTFkNkxRRjBSdVgvSk1uZkFJQ1hJMjIyRzVWS1d0YndEQUEvNmY4V2QvNzZ1M3Q4WWg2MjlnYWdubVZRczZIRWZBQ2FpODBBQUd2Q0NORDZoVm55QTJsZUFBSEFrQW1xQXpDREdRRFVBVURuZjE4SkFPZ1FmRVVBYkQ5ckJNQlVXa3orMDgyQVpRaWgzbERWQUx5TVJRREtJQmFQZ1dpbG1RUUFub1lXOU9RQWdISVJxNlg3NURZQnlnOUVVZlB2T1c2TUJxa1kzQTJBS2R6dk9NWndBU0JraDFhRkpxeEhIQlVIWUxMcW4rcExkZ09DQ0x2dGxXYUE3Z1F4QVBsVHRLNEFBT3QvR2dIb0x4QzhQd0I4RVFEbTh3MGg0Q255QWlDTVNUU3doVjNBWmZobU9BTVFBVUFuVUN3Q01KaE5XQUJBdm95MkF3QlA5Vi81SkM1RUlnWGZ1TDBHQVBnTHdGdlVFci9zTFFxWmhySU1YV2xQTEpCaEE4QzY3Y04yMzJnQ0lBQWtYeno0NCtVSWJpTlNJMEFBMkc3ZWJITUpCQURXZEFjUUxDYmZIQURjUWlUNEJkWlQ4S1JGaitzRFFETlFhSFJDbEtsMHpsVUp3S3dSQVBQTkU4ME44QU9BaEFJUUFGa1EyWHRSODc1dk02b0ErdHVSNFV4YjNFYlZDYWY2SW1DOVVmMGk5eW9BejcrZXdXMHdHZ3duYjI4dlR3QUV5Y1cwYmYyNCt0ZFNuZkNGNExjRGJ5MkNOcDMwek1SbEw1em5nQndBSm5PNVRTZ3hBcU9JaWR4Vktwb01Td2JBOEdYckFjQmtHN0FJd09SN0F6Q0M0ay9HL1c2bjNXcTNPNzMrMjl1akFYaDYrZ0FBYUZzSWJMQ3BFUWk5QUlqRGtBSndDMnpkNkhrT01QSUJxUUZZajlSV0xHNEFIb2VEdkFHc1pVekVJTkRnNlJlZ3VkMWlxOU1QbHdGNGpwRFhhQTc5eUh0RkxkOVFOaVcwdXhSRFMyeFQ1SjA2eUp1SnNmQ3ZVUVA4MmRLZEFNVENXQlVneWo5T2tRMW80WU5BRHdCb0NLQUxVd0MrTXdEZ3BneWVYM290ZVhYNlc5THo2NUVBZ0YvN1lRQnNWcVJhSUpoWEF3QVFTRkVzQ0FLUXZOcG1VL0s2Z01WaVRvdUFnb2twcTBWTm5WWER3STlGUUhoSDM3TjdsZ3M0Zmg2RVFidWxyZDZmWjFtRWp2dy8wUVNZMHhEVXh3Ymk4V2J0NUdFcWZDcCtwUXlJVkczUnJTRHpBeVBYaWljNUJ1QTIzSG9Bd0dLQStBejQrd0l3ZUg1SytpM1Q2Z3hmZm4xckFPWWtTelNZK1FBUWJZY0VnS2RJSFRrRjNwSjlnM3NETHRnaDBHaGlER09LMTZWT1NzMERyWUtuQm5oS3pmS0hCTXllTEJsQlV2QkhkZ0g1WDg5ZlVnbUF1dmYzeUFuVUFSQlN2OGdhOUVVLzBJMUFpQTZFQUFENXN3OEFUQUdzUjk4YmdLZWsxN0t0ZGpDUkNQaHVBTXhKUkRpWVJoNEFvTlJBQUVDNEVLZVRHREtDMFlId0V6a0VjTmJQRG1vY3AzcUhnbXBIa2UyWXdQT2liYjlsWCszaHI4SHdTYXNHTWhZM3FZbkhvdmoxZ3l2SHFaRzFpSkRYUVkvUjRnaElSMzZVQlFqQXhISXViQVJna0VNQWJrRzBxZ1JnRWZWcERIRDBqUUVBOTMva2tqK3dBakhZc2YvK3JnQnNwbVFycUlVRFRRQ0ViME1JZ05nVVNnU0FLaGEwQ1Z6VExVQkZpdHRBdytCRHpJQ25tWGllakxiRGxudjE0bDhUS1h3dmFuUVpCSUVOOHlHNEJvRGQ5VE1BSVBZRmtBRVFKQzRmL0d4V1c2d0Nna0cwQ2FPTiswZ1lPUUd0di9tdnFCS0FHVlVBL2RuM0JtQVdkeW9BYVBXM2cwOEJRQ3NLYXdMQVpyc084QXdFV0JGUUJRQThFV3o5VFg5dkxOMUFOblEyS0E4Qyt2VE5WQlhpbzFUK0hRdDEvbjRlalovM3ZTcjV0OXJqRjlUclF1NEl3aiszd2RMWno0NlVBTFo4YmtTL2NqUVNrR1lucU9JUG8xQTc5OFViZ1NEb0Q2SlFUQXd4dW9ISlV3RUFHTDVVQWpDanB3RDkyZWpiQWpCN0dZK1RmcXQ2ZGRNQjk5Ty9Hd0FoMkFpZzBTTkJIRldjQmdBQUZ1bmYxaTE0bXpzQjJHNTVFT2pKNUp2b2RYdm0wcHlQMnhscTBJRXJQWm1OcDV1MGJicmwyN29SbVBDTkdrNDExUUh3OW5jdEFQQ0RZRXViSWxzU3FESW1WR0ZndmlIVForWnhWSVZBc3QzNEFVQVR3ZnFMMGZjRllEcWZubnV5NFBtU01HZ3ZKNlB2Q3dCVkFZT2tHb0I0Y0d1QlRjRFMyRzZRVndTeElGQXdjL1czdGJYbnE3MDVmTFQ2eHhNNDVzdGsyTElCZ01WUEllaGxnekVMejhpeEhPbWRmMWRramNzM2dLUHcyZGdTY1VaOFA2eit4U09nVUE4QkN0OXVpUTJJS2dHSTAyY0V3S3dLZ0FVSkFzMUdzKzhLd0hnNlgxMjdWdkdMR0lBVmJrYmZHSUFKdGdITE9LTGpvNndBak1wVyttcytmZE1CWUFoc3Q3QVpHTTBFblZWMnVEWTN3YmhQL2Q4VkxYckdjNWptMHl4bytRTFFPNUJSQnlQdFNQODNsbVVsQUU5UHFpdnNiQ2JDVFlEU0EwSUZRSmEzZ0FCZmIyam9YZjhwY1I0SEl3QmVpbGI4YXo2dkFDQWl4V0NCdGVYcDF3WUFOcElIRnpEdmlGNWZ1KzFDWUxnZGo4a0l1VzhJd0JOV0FlNThnQWc0aWVsYjNncWZYMTlaK3kvZEFVUnpDWEFRZ0NnQVlTejRqSFQyZGpmYzUzNlVzM3IwdlJ4QThDR21MeS96K2E1ZmVmOXpBSHFIeWVzVVh2ekp5SHc0VlBucDlaZGd3UnMyZjdJeEdQT0ZOMzVpQ0pnRFlCRStPaElhWVFBMnNlZ0RtT3hBdkFFQVRGNFhiZ0FVQy9BTkFaZ3RwcHZ3M1BFUVB5V2dQZHl1LzBBWmZFc0E4RDRnR0ZVQkVNZnpyUFcwbU5vQkVGUEJlZ0hPUzFCR1lKaGFZRHNBa0x2c3ZYLzRGdzRDbXkxV1ljZzlnSGJWUWlyZ09OMU1OUUJxbnorSmxTU09nV1UwRUd5cC9UQ2xnbXprakZBSkFCb0tpT1Zna01rV2pGdS93RnU3QVNESjRIMjBCL2llQUlSUnlMY0FYZ0MwVTNnbEh3akE4K2dEQVNBMklLb0NJSXhlbUFaZ2pVRGxxaUFnNnhGdUI5dGZJMitLR1FBREJxWmUvanc0ak1vMzVWTlM4NVZESC80aEFLRE03UEYwRlViWjBGZjhoSUQrWVJYT3h5aXh1N0YzeXNyWEJrb1JrVHlIVkhiL3BvN2lqN25CUzhkS1gvNHhzUUZUdmc5Z2UwZTFaMkJySkUyajFRR1kwREJnY0I4QXJKZmNSd0tBUTBCVDhGY1hQVy94UXdMYXJlNFZhb0R2RGNCVEdsY0JNRzlOS2dCWWJNa21jREFaTVNmUUFvQnRiMmhvaUZKUnpDa0MwQkFHNGdEQ0VNQTJUQTlRcUw3eVJ3Z01remt5QVRCUC9DRUFDSnRBM3B4Y2J3enVCRUJMQlpjUjRMbUJtSUEwb1FUWWhva0FBQlp1QUlnUDJFWG5BTjhSZ1BGMHN3MnYvVG9LQUJIUU84ODMzeGFBTVFZZ1NTc0FpRGV0MlVKc0JpWVVpTENlTU1RRldJN3dMb0J2QWgzTE1zaEhCK0Q5RG9pd0J6Q1pUZWZncnk2NnJYWWQ4UU1BT25tNG1jN2NBRGd6VTJrQVdXbUJpb2FTRzBMQVV2Q0hid0x0Um9COGJmd3hzUUhSanFvQXdYRElDTFFXaTdVMmUwd0VnR2FEQnJQdkNjRExINEI5Tm16WHUvK2hJempjaFpzSEFQRDdNd0FJTVFDenZSOEFhaFJZTEFtbFlhQmc1QnFHTjdNNGhCb0ZIQUMxTzRObktOalEvTk8yQTBERHdHZC80QjZ3VjFQODJBYUU0UlNPZmFsdUYySEpJNWRQa2JRQlErYXpYd1dBK2R4bEJDdy9wSkdBSndCQUREWjdkd0ZBYzBFK0VRQlRaWkFmQUdNWUE0amlVNmUyL0lFTjJJZmhldm55UFFFZ1hxQUhBUFA1YXFVQ0FBaFlvVFdkam9rUDJKdU50QXlGK2dEQXJwSzhZdnB4QUtqRENXZ01BRnpGVlJUSDUyRjlCUUFJQ0FBQmkra1k3RjN0RGVpczh4SDA1bFpLVXFncWZpUnhXZ0Z1TmdGeWJ3RHdQLzR3enhlWFFrRzdGRVVEcFF4U0RRQ2paOG5lZWtNMkFkT2FBRmlUQmhvQm9GNWE2VHN6QUdnSE1KNXZ3amdwZWcza0QyekFOWXptQUlDSnRYMm9ZMENHc1M3Z2dRQWd1YzJuTmdENE5nQVM0QVpndFhJQk1PMTFTVTM0ZHdSZ3VvR24zdGRPSXdBNnB6aUcwY0J2Q01COFNrNERmQUFBencrTkFPRFAwZU5OQVNhaTRKMEFpTk9jRlhQQXV3c3E3VDUvVjF4T2pvR2ovYTlnL3drQWNaSVAyMDFXcXozTjRtZytIczlHbFNaQVpsQ1VONmRkbTB5bkYvK3UxbW9iSUNaeTFCbGNhUThqR1FEWk9pd3dBQ0UwQVVLMmtCNE5iTUg3Zjc2eEFqQWRDTHRBQ3NEaW13QXdtODQzVVpJVy9WWXpBdnJYS05wTUh3eUFQRmp3WGdCV0VnRFljNE9ab1FTQSthNFNBT2pzRzd3QThsdkg4NEFCd0VMOXNHTW9BOERHZ1hYUXN6cXZyYUovdHk1aDhXSWJmNEN2UFBoVmkza1l4cnNNUm9FYUFkQXR3cGhFZzJ4cGpWSnRvRndyS043d0pQUnZubnNyOW44VkFPRDdBUG8vaWdESFlMVmU4UmNKRzdycG1od0g3UmtBaGpOQllCNWlid0RHSTNZalk2Ri9Dd0NBQXRpZnNuYTdvUTNJMDVqRUF1NEFBUDc5QWdBNkFvOEdBSWl6TmdCa1c2RTdnUnVUQnFnWEM5RGNRWFZpb3lwejZaSEtIditpUlJEdFAvamxhN0FGU0hkRjBHcEtRSEJPb25Dem5NMUdOaDFnQUlEL2NkcW9hMXNDQlJyRHNjWUFpRlpkTXdNVUF3TUFzSXNEQlFCOGpRRVk3NWdUV0FVQTNQcnpPTUNHeGdGQ1RRTjhGd0NBLzdyYWhNa3VLM3VOQWVnWENiaUJNQUNqZXdGUVJuOGFBWmhTVSs4RkFIakJrdW1OMVVvRWdJUUN4M3RQQUhBYkFEMFN5Q1BCNDNGZDhZc0FXQVltNjQyMUtnQ3dXZ3p4QkJDK0s5d0JUT2RobE93T1JhY3hBTjBpU2VKd2phVTFNTG1BVW85UWU4TWZ1ZHVmZHA2Q0gxbXZKYUhUcUNCVit3dDF6WlpMOU9vbFdPSmdYNlRNQ1FCWmtzUnNmSndPd2I4TkFKQi9uT3l1WWJ2cGFuWHl3M2NGWU9BRVlMTmhBR3dYMkFUQTE2L21hcE5vbGhJOHFHc0NyRTZnNmdxYUFGRHN3ck5scXV2enM5Uk1YQXkyRUFBaTRBTDBXNDBKYUE4djRQcUJpd0g5d0pGeEUyaEw4YlBYK0VrSXlDSVZ4SS9xQWFSVEFZMForaVVHZ1BkMVJ2czlETUEwUytKWXJoQ1NkSUFLd09vZkF5Qk8wclRvTlFjQU9BRng4aWdBWGw1ZVVNSUhsUFRyZWpGZHdPKy9DZ0M0RVFnMUF5WUFacWJXRlJQVFNCUDVSNVVBcUYzV3BVRmdzbUtGYmhXZERxT043SkM3Y01GTXNNMFdLSURHVVFCOEhJQzhRTEN2bm8wbVNpR1EydkZIQ2ZHcDF3SW1GN0ZHOVdNVStIMTVXUmlXYUFMb2U0Q0hNVDNHdFNTTG1nRWtRZ0xBSVUyU3hPUUlVZ1QrZVFEeXJMa0JBRTdBWlFldjNaMEFvQzNFWUxKTjlpaEZLOW52MHpkNFZqMnVBWUJEL2Q0SEFOMEdVdjJ4UXJ0TE5pYUVBdkEwblRSZkJnUmMvVEtmOWFSWmVkK29QQ1lEUU90dXBodTRCOGl1dy9ZOUt6c2dGWUNpZ1hyZlFNWHBVMDBmL2g1OHhzSExObmtMK3IxdXB3UGVzOVBwOW9LWHQrZlJsQ3J1Q2dEazhMcG9CcGJpTWdBUUh0S1V1SUZLUzdIL0N3RDMrWURRQzB6VHhnREFMNTUvUDAyaUtPaDNsZTVVN1Y0UXYyN0Ryd0dBTEh4cFNnQURZR1lyL3B2b3lTMWVZekRsZzVIR3l4aElBdThMeXdIakpMc2pERVM4d0JTbzdYQytub214UUszbnQrNzBBWmZ2QlJpc1g4OXZjZEF6dHlickgySWdCVEtPZDIzYUhockZycmlDYTJteG5UeXVyZ2lQdTRTNGdhRjVtTmkvRFVDYTVXWDNMZ0I2NVc2WHhKVUFERVk2QU0vUHYzNi9KY08rdlRGZGQ3OFA1NThOZ0RnY2xLcC9JU2xjQnNCVzJXWWRrYXc4NnROTXdLT1ZkZ1VBS0JrRUFBRERnSmRMNXg0TDBPb1dXUVpWd0pxY0I5QkRKNk1HRUlOZkw1UGZ6MitKTkpYQzBKYzBqWlVBanpHWnhnN0FraGQwY0IvZUNvQ3BSckFLZ0xVM0FEN1RFVDhjZ0t3STcvSUIyNTBpYndUQTVOZHpIUFVydTFKMjlqTTRKT3BUQWRCTWdEQW9VS2dNbk4ydHJCMFFOSGloRlFBa21ObHNqUThDeXVBK0FOclpOY3RnTkJBT1RWUk9mYVh0cWJ6QTNUK3VGajhzUTArZVNJQklBVUJ0R21SVS96U0VqQ1FucGduTnFSTjQzR0VuTUJMN1Jrb0pJZjhzQUNIYUJaYjNiUUxBTnFBNDFBWmdNRXJtdlhiTGF3V3prUmdVL2tJQXFEN0E2S0ZMVElwcVFKQmdBdlQ4YTJnQUZ1c3dqbmVIT3pjQmFCdEFOTUJpTWh0WkFhQ0h2L0NqUFEyMm9hLzRnU01ZRGFaclEyWU52VUNtMWtIaStSR1huSkFTQ2dCZ0pvQmtoc053bHFsTHdMOEt3SG9iUmdpQWJ2dE9BTXA2QUR3OUxUZDliL0ZERlFBRXRuNzdHZ0FvU3dRZ21QQXhtSEx1MDBnZGYybHFoVlhSSDYvWjlzOThOSXlUd2RiYktFNTNoN3pvM09rRDlNb0R1SVRvUUVnRXdIeEc5VHg2ZW82OGJMOFFEVGlINFI4Z3dJV3NCWlNESlMwUGw2WVBtZXFDQkFBT0NJQTREblVUUU04QzdnV0FqVTM2aWdCYzh6dmwzKzdXQUFDSVB3N3FpUi9ZZ0NJS3QrRzNBOEE0UjRNSzJ6Sml3MlFHbkQzSHphT1krY2N3TEp3T3ZrQUF3R3lnOEY0QU9nVURZRExoK0J0T3FuOC9EY0pocjFWM3RjOUpGTUh6UnBaakszbTZQR3RNOUJPcEFWanB0WUhFQ2FRbVlDOEFnRHFNazdQaGUwM0E5d0FnSzRLN0FjalBuZ0E4dld4ckdYOEtRSlFKQUpnVHh4OEhBS2tOOGdaZ0VTa0F5Tk15akZLMkYwZ2FabVpVR1FEcHZkMTU1SHdxL0NzR1lKZmxaZjllQU5yaGRaL0NlM1EreHZuZCtxLzhQZmo5Ni9mdlg5dmEycDkwSmIzaUEyZFhreFV4TVVSc0k4S3pnM21MRjlUYmJVMEFPR2RnSHhqci9lTGVEd0JINGR6M0JHQlk3SGR1QU9EZC8rdHQyN1BNSW5BMUpRWS9iUVZGL0hVQlVFeUFLbU9IK0MxVmxQYkoyUjRBT0d2SnVDN0dBSVJSZXNqTDN0MEE5S0VUQUFHWWl3REkzdC9USURINy9sVWRTVnM0N1F5YWdLV2NTYXNEUUV0R2xkd3hFd0JnQ1FDay8xY0Fkc2ZMSXdBb2ovc0tBSDdQNTcwNnNsZERUZEZYQUVBOVYxU09nemtBSnZFT3ZGczdXTnRscTc2ZWVUYWZBUUQ1SWZEMWFQSUNyc3MyakhkNWNXOGNDQVVDemxsSzNEU3h0QlZIZm1BWEl1UGVyNDZLQ2VNd25KTWNiOTRoUkV3dUVmc0hLd0FzRnFzVjlRbHhXamdzNlZreUFMSmQ2aW9PY1drQUhRQkxnVlI5QUFaVkFBd2FBekNZSUJPNWVSd0F1UVFBUndCSzUyWHkvSnIwN2hCL3V4MWM0V25kcGo0QS9DeUFBMERqQUJvQW9SV0FiV01BYW5iM3FnREFIRTBhNlAzMzNRbmpzRGN3dUY2ajhTWks4K0x1UUNDS0JLVkpDQXRsWjJTVWxIajI4L3djRGJ2M2lCOTRtU2VVc3dYRHdiaE1YQUJBYlJ4RTVTNEFnSlUzaVF0dmFTaElBaUNSNUM5M0RQd0hBUmlNbHNsK3Z6OWVpK0tVUFFDQVUxNWN6K2Z6UHBvTk5BQ2VuMU41NzkrdTM0MG96S0dWRGplTkFhQTd0b1lBQ05JMmJBTzlmSUFhczdOVTk5SEQrVE5ONGFSdm9GdVIzOEZ6c2tINXQ5MWVQei9oWUU3bkRnNDZaUXJlcnR2dEJVa3lDSERsR1luVFRaNWZGUFhmS05LVTczWVFnRFhlNFMybVkzbEJLdFRlZ1JRQThCOWN4Z3RyeDJodEdKd2N0aHpJSnNBQndNSUxnS2N2Q3dCUHhnZXZtdno2OVNhbVlYV0ovTzlSQkIyZXlEdGMvdnBGQVFDeWV0N091M2VLSCtVY0hSQUFHd0xBUWpUNWxRQk1lUU1odWd1QUFLeHJBaUNtcGEyRkIvZzI4T1VSQU9nYlNLL3RuMmtPTDN1eG1DUXkrZjI4VkQyeURscnRaZ2gwNU5odXU3Lzg5UnUxRUVmeVQ0TE9mY0xIYWFkNXZzZkZCMU90VnlBRndGUXd6ZzZEU1BoM3hZdERlVm80MmdZbUJJQ05ObXo0SHdOZ05ub2Q2aHV5T3dEb2FMSDlidmhDRk03c1pjL04vMTBKQi9uNTh3SEFFbGQ4U3lCL25oTDJNcm5IQ0JoYndUa1E0SWZNSWdEVzB5WGlrZjFlQnFiVEdLSUQ2b3ZmRk56cmhCdlU4ZVczTUlqNnZsQnplY0o1cDMvbVUzb1lKSFVMcFVFZzZ4UVJLRlBZN1pNT2VvSkFDQURzV0drSTd3THpEUUV3QlFja0FHQWU5dEI4R3RlUkZwZXZnd3YwTS9PYkpUQU42ZW5YNWpIeTd4VEZKYyt5SkJRQm1OQnhjVkFvS2dCaUlJZ0JJUGY3bnMvZm51b0JzQkJiRFhFajhFVUJVTEt5c1V2Mk1oc2t0dU00QXdBNkRGam5ZM3VCZjJoTDVBM0FibURRd2J1Kys4TU1BSURETGhFMEFMRUJKRUZBdS9leHBJU21jUlFBYmdDc0FLaEd3QTRBY1FFWUFFOHZmUDdMQndBZ093THdoWEt1a2ZReU1tdkpNUnkrM1hFc2pvT3lyRmw4cThFS3VuL3RSNncrQU9CMGdOVkhGZ0EwKzA4QllOMkNhSU4vN3VSN0FxRHRBcjRBQUZMdHB3aUFtb0ttQUFEakp6djdlWHdUQU94dmRvYkIvL1pqVmdnQk9Hb0FUR2hISGdjQXFJc1g3dlJMYjM4czViblZCM0FBSU80RVRDWkFTRkp6SWlDUFNOQk9BMlh4eTVKa3VYYjJJd0hqNFFIc1hMaGV2OWdWZ0JzQTIzS2tjSXdlSnY5dUNVMEEyZ2R1WWJUWmt2MXZBbUNGaExTaTFVQmh5SnErVDNVQTRzaXdEL2lYQU5odXA4ZXVJKytxVzF2K2p1eXVicmY5cU5XL1FTY3d6elFBZUV2bStnRE02d01neGdLRVNPRE1VQmxFeGVRODl6ZGxCMm5xWC9mMmFOYnRieFVCT2dYZVdDVXdtMEVQS014Y0dWbmR1Z1IwblNWOW5VY0JFQklBMGpqY2J1YUdSbUlVQU40WG11Ny9WMHBGTVBNRElBRlNKQkRYQm5FQXRCWXhEUUN3YUlFR0FPREdiZ29BejdVQVdHeGdFbmphZmlBQVhTY0EzVWNSMENtUkNUZ3pBSVM0and3QTd0c3BBVUJYSlFCeDdBR0FNUlpvM2daYXRvSnFyTTdoQnNvbithTHdEY21Ec3ZwWFN3bGd6dndLMWdIbXNRMEFtSDdWclVsQUJRQ1BJcUIzUXdBY1lON3BsalRveDV1QTZWUldCL0l0dWpMTmtCR0QvV1JrU0VST0EybFdzS1ZKMUtjQ3dCMzhCZ0FnQTdEY2hIQXFST3AwdG5xMUNPaTZBQUR2MXUwOGhvQlFBQ0Q4YkFEa1g2YldCazVrQUFRRStIbWRuQW5Nb1hETzJlQUd3Wm8rekJHUXE0UFJubW14WG9Td0dVemhMQUxxOWVyb0FQQmNTMmNIOG00UEFnRHNBVGdBa1FUQVdHa3JLUi9VcnFSU1lDRzh4MUsvQmhRQW5CTVkybnFHMXdGZzhxNEFLTGxlbzlHekh3RFQxVGFLa2pTN3VucUJkR29CQUUvL2V6eDNWOHprcFFBOGhvQStWQUFNZ0kwTEFHenVjVHRQZFA3L1dBRGtWblVtQUdBVEEzdGxBSjhLcjdmdk5TWVBqYVFwSEpaRTMrcm1BaWdFdUlHOVFQS0xJLyt2MCtrM0JNQ0tVK2NCQkhTS1VnQmdHMjYwRGtGcS9SL3Q2VVozQVN2VkNOQ3l2NUNhZ0FNQ0lBclZyR0RIY2ZDSEFJQXp2QndBd0FkckFKRGxqaUlRSU5KK0RSV0E1TjkzaUxmYmZ3d0EwQVdFZ2NCUEJVRGRCSG9Eb0ozWXEyTTdiR1A5ZktadlVRMmdCbjkwQUtaejVBSkNBSVlXbVlDSGV6VUE2R0lBZWk2SGdyaVVkeXFBSVFVQU9Xb1FBRGtRaEdWaEF3QjNkVnJKRStWVkFITFpCT2kxQWY4SUFMdkRDYWpUSHBXSkp0TitmUUQ2VmdGMytvOEJBTHVBOENqQUFjQnFwUUpBWEFBTXdPcGhBSEFJakpWQnY1ZThaRjNMMXBjZFB0c2c1Y0hBT24vUGxQRExheTkveStYRUJnQ0FBcmdVUlRtMGliZ2YxQWNnNk5uMFNZOEIwTG5iQllRQW5LRUZpQ01XQ2VUYVg2ci9FMGNDYk1YZ0QzYi94RVEvOE85RUJpQ0tsTm9nYVdyWXZ3QkFBUjJxdmtuR01LRzNoZ2JBOGdjQURJM1JIdkNFZ0FQUXVUTUsrS1VBNE9FR0lSYk1BSGhWdS94YkFMQ0hncVFucThkQzFvSS9zUUc0Y1JLSENFQ3BoM3RRUWpjRm9GdkRBZ1JEZ3hGQTV1UkJBQkFGVUFrQVJVQXMvek1BRURJZGovNDM0dHZBaEFQQUVmam5BTGhBQUc2NUltVjBNdy9EK2dBQUFvWmhYNUV4K21sLzJIOElBSjNpNndBZ3hwbmdLTW9WYjJQTzVnV3M1SUpWc1drLzJ4TzZwbjlLUjhMNnJEK3g5TjlRRHloWFpFcHJzWUlBQUNjUUV3QkhIWGY1Z3ZMUGdjZ2FBQkFNMDM1SDVhbmJUNE5IQU5EQkNnQUNBSDFBbExHeG1VOFhndlFwQ1NJQXNDazRCd0NmQUc5RFU1U1hiUVBaWVpDTXdEOEd3STZvZ1BKVzludlM2ZytMRU4yenRRRUFCT1I5akJGNUdLd2dIVUlBdW5jRGdCWEFGd0JBclEyMHpBdkFBSEFJQkFEbzJCOG9TM1Axdm1Yalo5ditEY1FrQVV3SC9wVTZBT0FEeldCVDRKUUJjTHZsQWdMOUlNK0hTR1NOQUFpTHZOOWpxcVFMYUFxSGlrUFpWUDVZQWVBNFlBWWIrdUpBa0tGdk5EVUNVQ0J2WUZFQW9CalIxMGJ2RGp1Qk1RSkFzZ0gvS0FDN25OZ0F1QW9vSkNEQllYNHJReVQvbWdCUUd6RE1pL0kyUkMvRk1JWGt6ZTRIb0tRSzROTUJXRHNiQklnQXlCMXN4S3dzSm5kYkI0OG5PUzc4KzdjNUQ0Qk9GT2Vab2MreUNUQ04zVjIrb1k1d1pCOXdJNHQ4VVRhU1AxY0JPUkJVQWVRK3pQT3loUDhxOHUvY3F3Q3VGN0JUUXlZQUFMQmFMMHl6bUpkTExoR3MvUTJGL3ZMMzRaZ0FjRHhrQ2dEeXVnOEE2cGgvTWdCYkZBdSt5QVJRQUlLR0FFQVZBSTFBa1FPMDRJTDN2NllBR2dMUVpRcmdldnBzQUJiUzltSmJDWUJ4SExqWU9zY3gybE5XKzlMZ0w3WGdYNXpCNjNBQjBmV0JQUUV6YUFOMEFrb3FmMThBWkJVQXJNQXd6ZkVDNGhlMFNlY09BanFkZ0NvQWJBRndCVDhlM2JZd0RRV3JDUUQ0NTM4SEFMQUJGMEtBeElBby8zb0FZQUlnQXZDNkRxSDREZkp2VkhQWXZWRUY4UGtBaUcrTngwNklNNE40SUdoTnp5ZkV3Y0FhQkpJOUVFSTUycUVQVHkvbFQ1Y2JmV2pDbHpGZ1gwRTNDWTBHQUFSY2RBSUVBOUFBQU9RSWtJWEVUMkV5Vmh0NkE1QnpCUUEyZ1NnTUZPRmt6dmw4cXF0L0xoQTkvNHVMWEY0UWdLY2dPUUcrVWpRN1VOb0kvbU1Bek9hYktOM3REL21KRWNBb0dBb0t3UDh3U0NBZ0NBVHhtNDFKUXc4UTdnRy9FZ0RPSGtFWUFIMnVqUVNBS0xiZjdpVldHSGdEZ0FWUDk2SE1KQUFBWUVyQUxqdWVyaUlBQ0lHaG9BRHFBc0RNUUVERWIzVW1tbXdCTVFENVliOGphZnNPQUtoQU9BQUtCR29vV0FTQXRBaW9OQUhmR1FDWUU1Q2syZm5LL1FDQ1FGTUFLQUo5Y1ZtZGlWcnlIekw1dzVxUXd6Nkp2eElBOHRRUVlYTG9lS2FMSHpVeEVLZmJ1SWFDSzgwOXFBd3R6YjdVS2FGYzhCd0FkakMwQU5jSWRRZEhib0JrQnNKZXJ5RUFYUldBbnQyWnJDUC8zbzBEY01wSkhEZ2lUaUMvd09oaVEvRkRKMUROQWxmci9EV25rRGlCeVFrNGdYc0FRR3J6QTMwQkNMNDRBSXQxaUxjQ0owUUFSeUFYNU45bEl2WUNRSFFGaWZoZG13bFArWk5EQUtJQWpnZTBCYkFCUU9QL1RRR0lUOGZqd1EzQWRtRUZRRXdJR2NCbTJab1JHTlA4WmRNQU1HdUdCOC93eGdDb3V6d25BUHdwN0xlaGR2cHJiQVNPWjZJRUtBT0ZJSC8vcEZEWkRQQlYvVGJlSGlBUEE3TzZyYmw0Y1ZscURnVkFGTHpUQ0tnQTdIWXByZzk5UndEa0FPRm5BTEFpanVBNXp5OVhrUUR4ZExnMkFGMkQrTjN2VXNjQVhFOEtBTlBQQUlDa0diS1NBL0sxSVJDRVA1MjBHV1R5RjJiZDBVTUNMR2xhOWFISkZCOG9tZUk4eXBQRkFXTXZMNGFuMFBvUVZDR2FIYzZuNitYQ2ZZRit0eTRBTmhWUTQxM3NJYURpeG1NQVlBOTQyTk5PdmxDNnd0MjFYR0lQQUFNZ0h0Z2J4YTZGaFlnUGNEMXpBRFFDNENnUkJBRExONVhIeGtrQXJJMEE2SU9PeGRyOUNnQnNnYjVHQU16V1d6UW1CaEJ3aEZyZ1F2WUR0MG9BOUI4YVZFQk5paHc3QUFiQTVaUkQ2U0FBTmdZQTZCa0FuZzMveHRhakFkZzZBQkJNd0orWklWZkJPT2xXQmdEcmUwTTBWNDMwY3IzdUR2NU9WRk9BRVZpZ0dRRXhJR0MzT3h4eTRBeGlBbTVETGprc1BDN0lybVYxN0QveVZpT1crb1Nib0FCeUJBQ3lBQklBUzc0NEFCd0JCd0JDckFjRGtFSUE5cnNrU2MwQUpJa3ZBS1B2QU1BS1hBRkFRTHJQanNjOEowWWdhd1JBNXo3eG0vT0o0U0VnQitDVTV6aFEvOGtBQ0NaZ0xkbC95UVNNdGhheDh4bjNwcDJBMnRqbFdYMFNsYUdzNmFVTm4zR0lqb2dBbWhVSXlGd3V0K0VXSWJETHNpTjJCdUUyUUJKZnRZaUprTytUdnc0QmZJQVpBSlFKbE9Nb0lHN2ppWStDMGMyRnhEMFRPVmlLQjBJZTRnZUxBWEErUWdEZ3I3R1lnSVVBZ0QwZjRDTUEwRVJiQndCY0tiNUdJMk1COFBCa0lNZVI0VjYzN3JJRDBHa01BS3BQdWZFdDREVkhNVG9Hd0p6bkFoZ0FNTFVCcUFWQWJBVmd2YjRmQUgzZ25XVU96T2paTVB6YkJnQnUvMGtoZUhtaERxQktBSjBYREFOQzBBOElvV29EWmlEUGNZNUlIeW4vUndCUXY5T1kxSGlVT1FCRUFjQVkzUTcxYjRKeTVRN2dVbDhtQUF4blFCb0FDVFVCR2dBeFdmOFdBTkJEbWM5RDJEQUM3QWJJNmVEUVplNXJBTkNrMVp3SUFIY0E4QllBWmdMaENOMm5BN0RTYkw4T3dMb0NBRnM4MEFLQTZnVHFBRHcvdnp3RG9XTkRZQWVBQlpQcHU4TmFNUlFXempLVUkxTG10UUVnSHVNOWtqY0FFQXJ5eHdvQTllOGlUVjJJQTRnUEFMd0JVQkR3QmlDT0JRQ004OEpVQUo3WFZ1K2Z0cmVjYUhsQ3p2SitaK0gveXdSREFmNFA2cEFaSHA1czhQLzV3U1BGYUF3STJNQ2VJYnQ5ZGo1ZEdqa0I5OS82ZWsxUlg1TC9DZTRBeUdSM3VnT2dleXppK0l0eU1NWC90R0lmRVlCNEVqekIwMEFNUUVvQjRCQjhmUUNnWXArQlhjL3JyMThEc010YitnQXdHS0JHMjlNNXVCVEpicmMvSWhYUS93emhTd0FRQjREdEFLRUNPS0t5elNqOGZBRFU2a0FKQ0Y0YlNPT0Fqa2lnWmU3cHhBS0FtdDMzSXE3bjRPa3RqV0FXWnJCTXRuQ1BKNzYvY21SSVU0L2c3MERkMVZIVGlCUWVEZ0lBZ2srU1A0V2dvMFlBWUM0NDhnREVUQ0FqQUZ1cEdKaVBlMUZjZmhzQVQ4bkpaUUxBN2pENW1nQ0FiMys5amZ1a1UxZTdHeHppbDlua3BSSUFiQVl3QU5BSW9GVGhNdjlNQUVqditVSXlBREFHQUxlQVpnQ0VmZi9qQWFEL05RQmdha25HTTRKZW5XS3Zoa0FRT2U4MG9PYjNNb3N5V01iU09MWk9zUHY5NnhuK2tEcURtZ25ndVViQURNdzNNQ0FFYk1BZFRrRG5FVGFBZkpIZlNsSCthQXVBZXZmRTVCaG9PcFhTZ01VOFRmUFpuN0tsMXg2YUlRQlNjaGJBQUdCNmdDTHdGUUdZVG4rOWFjTlllekYwQlNvQmdQM0hLQUJ4aW5MRnk3dWNnTVlFdElWaEJZRVlBY0Jid0F6c0FDSSt5T05yQUdEb0VTTDBCMWg0QVNESEE0d3cwR05EUGNNZnIvbGthK2o4M3ZrekdDRUE4Sm1nd1FqdzhkVFFEUXdwQUVVWmZyejg1V21TOVBhbkJ1Q0F0NEJSekRNQnAvenFXZ0NnYlVBdENNakp2aGdBZGhvb0FrQVh0QXRmREFEeS9xUFkyUG0vRTc4c0Y2OU5BQ2g2SDAyQU5tUkVkZ0N5RE9WcU13RFFCTWpIQXhEVUJVQVlRa3RZbU5GZXdZT0ZsOXFYaGErSVg1eUZhcnI3eVVaenNoMWFodlVjRnR0WHNVRFpDQUVLUHM0V1c1SW5US1BCTHRrK0hBSERaMmZGb0NnTmFFKzY5NUVCSDNTTHd3QVFhN1EyMnJJYUFqRVE5UFQwRkF5Uzh4RmxIVlpFQXI4UUFOUHBlSlRhR3Y4SDZYTHRDd0RKRWNRcUlOQkUybTZyUFlEdlB3RjJ6aHJwM2JnRFlBU0FRL0RSQUN3TS9jSVhXazdnb3I3VEo4aGNOdkxTaXdUeTBWODczZmZ0dzNwbWFLaUc1Z1lhQUZqQUU0RVliZ1F2OGtiUU1RdkVDa0duZTYvOFd5MDRHNFRzQUdIM1RtR2FJd1FBSHZjTG9kK3RzRFliT3dJVkFCQVQwQVFBb2d3K0hvQXczTmtIUHdUSjJCc0FkQ1lFTzRpS3dVRFhJQmdLd2IxYXdQWXI4dktDMHdEaER1QWpBQWc4QVZBUk1QY0pmSzBCZ0xqRDAzNXFBd0ExeGQyRW04d3grNmw3SE1OREU4TldFQVBBRGgvaFpoSmNKbG8wWE9LOHNFN0xhOTE1RW14OTJ6S0hFUUNnLy9ld1dDK0phRFVBbmZySGs0Q1hHK2N5aWwvTkNIcml1NEEwRlFOQjh2cHlBSVJYMTZpR09OeHMvUUdJWU9PSUk5NEg5THJ0bHZkcTM1TUxadGRmUlk3UGdIWmZDb0NaT0kyQ2ZXWHNGZXlXUEUvMU5lM3lOQk9ndHNWRzNnNzRJM0xYZlJxa20rMTZTdVBGbWdFUUo0a1NBUGJIQzNBQ2JyMGE0cjhQQVlmK0tpRUFRQUdnU2gwaUtkN3VqNjYzdDdjMUQveUsvOHJiUUFrQVdoVW81QVFLY1FCdUJCVHh3MjNnVndJQXRuME9YYUxxbjhONkFLQnFzZkxTYTlWZURUZUhqay9maHBVZ3FCcjg2d0ZBSjlIQW9WVEc4ZkZQTTdNVUo2NFRYdGtVdU5kNkFSM0FPTTFEeDZqMVZ2OEswK2ZvcjliS2lOa2NRUmhQREhISmNGb1UvVmFqMVhrd0FLMndRSG1nVXAxT1NQc3hWQ3A4NTlKQ1FtTWVDcWEvMGJDK0dBRFFaRjljczU5YS9TSk5vZzNlTW5zQUVNYmIrRHJzdEJxdWR2MUFvZFBUQ0VvckFCWnYvd01BMkM2NEM0aFBKY25zWUF6Qkg3b05uSW5SSFI3U0VVNTU3RU9ncThVUHQ0Qnc5RStXRjdtcnZDNG9nUExjckpmMFZ4c0FJSDJEbHJoOWZwcjNXbmVzVHQxQWNiZmQ0cU9GK05naFlzQVFBR2tpbE9tRW9URDJsNC8yREkyenZuV1pXM2FERkFCb0FnNEg2SFJvQU9BSHZoZ0FjUXE3L2JsbVA2VkZ0a3VpTjE4QTVzZm10NzhuQVFvRTlybEZMYUMveWd4V2dud3RBUFJwQWNaUThOT0w3WWgzeE4wKzYyelBpVlpFb0M2NGE0ZWpuMDVGMlhOMDF5b0xOR1YxQStOQkFnQWlCT2p0M3BiTCtaKzMrYUhmdW5mVk5BUGRqc3VBbGRrUkJvR01WUm9HRVp0U3dPalVEKzFGeXJ2aERpRTdaQUowQUtqNHZ4WUFxTnZqcGV4YlI3VjBldVhKRzREbDY5dXgxM3JBcW5WbTZKd3JQU3p4TWNCWEFZQ1ZobGxtaG9nQS9IN3h5UFhTQmM5elFMUWNVajRXRDdsczg1QzAreXp6cnBCTEpROEFHcGFYL0FBQm1FKzFqeUJXQ2krUi9BL2Qxa05XcHdZQjNaNXJRa0J4UVpsQWlkcTgxeERLZGZsNC9DWFc1OFJUTklnaHRRQWdPb0ZmQndBYXQrM2I5bGc5TkdKcm4wVGhwaEtBMlNaOWtQdzlkUUFwSituYmUwVEFqNThqRStEcTNQamhBRWpkUVJrQTJqYnd4Wkh4clpiNzZYbmVobk5qdWRZWXV3QTRnNnN3NzdLNzNSU1ZWTzJUT05xd054ckpud2VXaHkyMjIrVnlHM2RhclE4bGdBQmdteXVORWdQQjU0ZGVRQlNLZXQwQmcxYjBHenBJa2M1NUNBQW5tSHl5WjRuaFBCa1V1NkpmRTRCYllKNzkxTWVUbG9FVFVBWEEyOXY2OEVENTF5R2daNWtyRFA2QW5MUWNEY1BrY014UVpURDhwSnRLUGZDQkFBaUh3cklKNEFBNDZ6M0VyKzBlbnpJWkIyL2FJcFRCeGJ0NjZGTWM4SmhGQXNDU0pvaHFxYVh3WU9YdDNHMjFQcG9BWXFlTWM0VmhhVkMvSzgweTZ2ZURNU0RodU45Rm03bER6ZHZoc0NTRUloY1RBdkFVeFBqMGNiY1RDRWlFaFRxRWZDa0E4T3luc3RjVkduS1NYaTBsbWJTc0FDQkhJekVBMDNQdnNmS3ZzUnZzS1pQTFdHbFEwT2RvQ0dsSXZYNFE3ZzZIWFRSZmJTdEUvbTRBVUFSb2h4Qmhha1ZOQUhURnI2aC9Dd2R2c0pJanpZNms2ZjhOT0lKQ1l4NzRaYi9FT1ZXbjR4NE8yaGJUcUZrOUdUeXdlbm1kcjE4ZnNQOXZRZ0RxTFFQdWJKTVBBK1N2anh2bFNTaTkvaWdCZjlseWpneENITlZ5RVVORDFTY0NBSnFBQTdRQnU1VEVIeFVBaUFuNEtnQWNqbnpxdzFCdTBEY2tEZGF2QklDNURZRFo2MmFjQnEzSHI0NDNBTGx1d1RyZElRT2dvNTl4RVFyNkFZUmcrN2FOUGh3QURJRXlMOGprQkk1YzRaNGF4Nzg2QUdHVTRuN2ZwTTF6T2V6enlWOGxiYkFQbXlzbmNNU2UxRktYbHBTaEhlQnFFN2ZmQVFBL1J4QjhWdURIOU5XV05EMHlhOHpSUTR4UTFoOW14LzEyRTlZRVFOdmdFUUN1cEE4RkEwQVVmZ3JXVndJQXp2NDZpWU5mY2xRYk9peHV0TElXZGxiS25BQXN0OXZGb3gxQWJ5TUE1ODJHWVpybnhWQXdYNGdLcjJtVFJCUDArblBvR0g0Z0FLc1ZNUU5pcDBnVEFMTE1sZllmdGNYUG53YWNRSWg4c3VNTjMyL3FZaFlBMWxUUDUxcVNLZ1JnT3Qxc1pydCs2MzFXbFJHZ3N5VUFBa1V4eFBQbVVKL2xsSTJ1ck80bVNsanJ4OGNkVEd1TzNRQm8vUjdvQWs3Z1FBUUFaNkVsSWdCcHlnQ0EzU2RVUCtDakFZREFKK2todnhZbUFsaHJwVE5xckdjQ0FHNHA1dk53dTMwZkExQnBCSHBrc01BUWpSa0Nmd1BTWC8xaFdPQ3ZldDdUSmpFRHZTQTdKMXVMUHlnQllBcngxUUNBbEI2SUFBaE9vQWlBcnZjRkJHcHMvWFIzRUFLQStycmdmWUEyOTRXM1Z6OW1xS0RDQUFDTS80Tkxzbmo0RGxCUUFUMkgrTW1BR2N4QW1KTXBkbkRhbUQ1c3JyS3BPUGwxMDNOcWpnWlVBaERQUlFDZ3BEVW44R3NCTU1jekgzWUhQS1JOR3ZzaWRkZmVvNXA2Q3dDYktFeUdyZmRicnR1Znp4WEFnNmFFWVdOc2JsR2R6dkswTTBLeUNXTnRhK2dFQUFvNnFRV0FtSldNVGNDS0h0TXdBT0JjQU5mSmJ6Mm5UNk5rTVVVZC9uYlo0WHhScDM2dzV0clhNL1FBWUQyRkJnQnVxYkNOTmlkZkQ1Qkc2SlNzSGZkcmVzN2JYMGFBRHh2VFpvMjFmUWtBekFYSDVDMkt5WUdCNFdBb05pL2tCRDZsRndZQWl3UlI4ZVAvK2dJd2VHOEFVSWMvMk5zTGR2dzNBbkM1d0p6NkJGMEZBd0Q0ajlnSHZ1TG5VY2FPWGlwb1ZRRTlsL2lGK1JLQlBteXM5clJKK2pzRDRBdkVqUUQ0N1FPQWNWNEFBK0NQQW9DaCtrTVZ2NWNCa0V0RVVFZ1l0WGhNVURoUTB3RzRxaEttTitLMmFnWUEwQXpkemFYakszN1dNSmJLeE04TDZGbmwzK3RKVTRhQ1FKZzJaWncxNVkvQThCakZDVVZBTzBCVVQzaVJydGMwQU5zR1V0SERmNnNCV0lzQVRMd0E4RzRob2dBQW0rQ2lBNEh6NlhxVkhBRmNWWGs2dzc1cXJMWCtSQVVBWGgwdkJVRGFOcUdZRFhoenNFZnJlaVBBQTlROVNmelN4SHB0bVdlTitTdUJkdis4Mjd3N0FJc0ZEQUhBU2RVTDNpdUNtWUNwcS82cm52aE5TZ0wrTHVRSG9pT2gvSElsYzEvb1FsWFZXUDdRWVYxTkdVZTRxY3dHVGRIZVhEMDhBQ3orZmlGdU0vTytKd0prSTBCbUNKakViNTQxMWhBQTlvazZ3L1BXZFVTZ0FwRE1BK2dGWWdDeUhkd0hZc0dMTHFBR0FPNVZZZ1RnOStMOUFaaVM2Vy9BRTRSbTRNcWxUL3NxSnZqK3AvTlZSUUNRY1V5SGZyZC9kNmpIbWZwZUJMUU5ZaFpuU3VnSTJJZE4xZklFV3YxcjdDQkFCK0Jwd0FIWTcvMEFXSDB5QUJJQndBN2d1UytvcVJacXF4ZmowVG9iMmsyRi9lWXA2Z3NIRkVEUDUvN3ZCamZUS25zK0JKQ2JYeFcvZmM1VXp6RnMwSDlEQ0g5enZ0L0d0dlNoZXdEZzljQ29NbWdxK0FBTWdMNE9RRlBoMjJHWTBqYS82UjdPZllHamY2NWdYVTVvQW5JcTJQK0YvRklZQVVRWDRkcnhrWDk1czZ4K3A3cC9RRWUrd2JXQk1rWUUzTVdsM21ZZzNrZkM3Q2MxQzFEMkJEZ0FzQ1dWR1FBY0IvQUVZT29Fd040L2FyR29BY0JxUXdyNkFBRUFBYnBJS2pXMC8vUFZ5Z1pBa2h5SEh2THYzZXpMZzRCMmxmaDFBcXFMaTRFdThFR2dIUjVqWGxWV0FRRDJBYTZWQUtqZFFlYW9QbENOQlBieExzRFkvc3NrWnY3OXdydTdJQ3NSUndUczkxbDJ4QXYzVkF6eC9uK3R0eTNIZ1dSd2FZcGVkZkNuZTNPdGZuVlFDS1p5dWVXdk1PQlZYZTZuQkJBQnVLaWc0akFJYUFCNkdvZ0JTQk1LZ0FpQ0FNQnE5VVVBb0g3QURpSUFGMDZreDM4eERsT2JBSUJ4NUtKVDZRRGE5VDlldlVvQ3VrUGQ5WE1nNE5sZHdOTU1kTEpkbkx3UEFEUVJrRGlCU2h4QUFVRHl3ZlNKc3Z5eHhhSVdBSWkvT2ZJRHVKSktVVE1OVWlrejFXQmJMdCsyNkVROFBTZlZCcURVVDVubDc3dFZBTFM5eEYrL3U0UWZBdDB6Ni9WQkFMQkVBdWRvV004T0FvQXFBM2JzWWlvQTRPTi9lRkdoL1dkeEFCMkFpUXNBbnFMSGpjbVVySVg4OEtJU0FPUUpTdG5MRVN1VjBnRllMTGNraGxqVkI0Q003Wk5PR0V2MTRER3ZkQU1xbEgvalhuUHRTZ3FRQmJwR3NTTU1WQjhBUEM2R2kydTZrR1RGQVJqWmt2MmdyUGtFVVM1azlvNnkvTjBhQWZLSC9RQ2hweTF2cGJQV3k0cm5xTVFpanRPMDdGVUIwRE5LWDBhZ1h3VkFUNXdqL3ZoK28xVUVESGVzOTc5ckNRRGt4eXhqQUtpdVlCVUFmejRGZ1BsR3FITEF5bzU4VGdzQUtJUmNkcW84Z05JbWZnR0JzaW9ZMEcwZy8xcHQ1dHdFZE04UjNnazhDSUROMUFHQTRBUk9KelBUMXA5b2UzR0djQzBBMU8veFBuUk9LcWZZMlRkdXFHMWdaN2xBcVNSUnZEdGVpbllGQUQyWC9Ca0IvUW9BT3JVQmFEeHB4a2hBc0UvU0pLNWFDSUFSQXVCOHhNSGdIUmMvTlFWR0FFUUdCQUJtZGdDbWp3Wmd0ZGx1TnJobEFtNmVBdFBXSEFERXNMQzR5S3YyQUxsVC9pd1Z0UUtBOWljRDBMMG11elI2R0FDYUNaQWt4Z0FZemFmRzhOOTBRVjZnS2dYaEhabWpTUFJMWmJjUU1pWVZkczJCUGJQZThQeHMwd3VYTkp0d2Q4akxZVlZXYjVYOENRRlZtOG4zQnFDQ2dIYTZSOVBtbFBFL2tRckE2SGxBdG9ISHcySC9EUUhBN1JMeEZFM2J5T0xsY2swQ1IrZThkRzhDMnEyK0xIODBWN2FRTXcvZ0UyNjk2aVBoendNQUVCQmNVenh6L0NFQVFPc3FBeUNvYzE0Wk5KcVBMYmtlOEJVcytDTnErc1lBc05tSmNKb2VFUC9TSGxMR0FDUkFBVlFDQVB4bktiOVFXSW9XR0xiYUZkdUFXZ0RjTTI3TzFpb3QxWnQvNmdBZ0V3QkhWRk1BU0huQTl3RUF1Z08waTdvSEFGVzd3T0ltRHU2d0luQXIycDhNUUlVUjZCVzdQWjQ2L1FnQTZPaFkwUVRBd1d0RXJiUEpvZk9wSWpyck1TQTUyVVdMS25EbUZEWTRMbHk2dTR1aCtXQndXSGdsQUtWVi9ySVpLQ3NEQVo4TlFBYVRJNVBFRUJCZ0c3ek5hRElhRFhFZzZJaERRY1FFeER6R212NWJBRlJrQTNVVStjTnNnOHRGSjZEU0MrelY4d0x2R0RwcEpnRUJJTXlDcXdsQUtpMDJQbDVHWUFyTmdGZ1hvQU5RRWRGOUhBQnVVN0ZHRFlHejQrbmlEUUFSUDEwcUFSNEE5QjhmQ0s2aENYb0ZjT3Rnb3AreDhZOEpnQU1IUUYzZkdvRGxHOG9FakpQOUFmYVhxelFCWW9ycEJWVnRuTUNpREh3YkFQb0ZqTzA5RElBdEJrQnkyekFBRTJBSVFnNEF0ZzNJNFJ1UHhjZ1BlVUFNSTA2bmVDQzlDSUJHeVhKNUp3QUxKSDlnQWZhb3RZaWZEMEN5ekU0blVya0QwQ0hwaC80K1FMOStMTGlwTDlBeHRoczhrVkZBNUxETUFRRE1wajRmZFFDRTZtQXJBUEQ3N3dSQTFUWXd2M0g1NStJNlVUdEFkd0dWeDRFTlRnUHVtRUdxZGhzckxnOEVnRHFCZkNzNHhnc0RRUUdZMElmOUFNRHZTTVpmTEswQTNJa0FMZ1pCMCtGTzE4SWpEaUNNYm9WNUV1eS9NZ0hENm9TQUpnRGNNWVZTYVpkYUZGQ28rOVNBQUJzSnVvRmxtd1FBWUFJT09CZ3NiZ2FWWGNCM0J3QU9oNnVLNE4yb0FrQ0NQOERtS1JuOEY5c0JDc0N0NzVFUjhva0FERkdaL01NQW9EV0JmR3Fna05YRjA4SkhjMG40S2dEcWVRNWVKTFZreG9maTFjb1FxdHdCTERaWS9yc01UNGl0T3Nhai90L2xETTlIb1BCeDB0bmhESFFBOXdNcWZNQk84SWtBUUFVQUFVQ2pSMWltSnhjL0JBQ2JBQndJUXI0dUFtQy8zM01BK0haUUFrQ0t1SDgvQUtvaWVLMGhHdHdHSEVDWVo0NGFLSElBQ0FGQS9ubFZaVURRMkFiYzdRWEFmc21rVzk3aFVRQm9zOE9sRXgwWEFKYTZBSEUzcVFqY2RLaFh5d3pJdjIyT1drd251K3lBV3d0VjVmSjA0ZUEyNkFDY3lhMFByOHArajQzQUNRTlFWSjRGZFlmTm5ZQzdwdEczY2I5azBpeUxqeDh6dW9FQ0FIZ2JxQUVnbFlmL0V3QlVpcTRGL09jQ2w1bnQrYVVnQU9URUJsU25sUVIzQUhBZkFwMU90N2c5R2dEV0oxQ2NIc1lHQ1BQaTBMRnpUUGpFRGdFL1cwYWRRQjRZQzRKT1lBelBnZytvdXh6dzNpcFZBRENmNk5yaDlwa1lnRDMwQnRDRVVRaEFWVFNoM2I4UEFOdzdycUg0a1FIQVRzRDVpTE85ZFFTUVpEZEEvQk51QWlRQXVCSFk3ZjRsQU1waFpWVUg4S0N2bC9OaHY5dnJBQ0FiVU9rQnREdkRld0ZvckFkd3YreDNBOEMwV0duWWFEcjJLL1kzQTREUGxwc0FZTE1RWk1JdUJ3Q21kMVFYZHBVbDdEUzNnMlVuTkRBQ3ZvR2JRZEtpc0xLMkJCZUczQXRBQXdSZ0l6cldML05DQU5ocGVaNTQ3VUlNd1BWMHlzOGNBUFRYTWdUK09RREt5cW9Pc0JXOEhvNlpCWURxY0RLMEFBOEd3QmNGTFA4N0FaQjFBQWFBOUFlQ1JaY3IwU0hFeGFJZUFGRFhUSFQ4K05keURvaC9Vb2d3U25zcFI1RElnN2l6RWRyMTdFbVA0Y3FFWHVRR25IZkUrNmRSVVFCQUJtTkI1M05sTUJFQUVEd0lnSHIrQUh6dWtEZE12VjVRS0N2VHZEcnEyKzNDMGZOb01zNnVlTk9EdDRGMGNRejJld2JBZkc0RUlHd09BTTdqbFJPQkh3RUFpUy9LQUdBbklQZnA4WEU1eHpzUmdJUUFjRHhYM3Yrd3RpQU1QZ0VBV0d1WXM1VEd4d0tBeEkvblZxcW1BQ2lGaUNlRkxweDdNcm13Z0I0d3EwV2lYZ0FzellzMkE4TUFrQWJITVBJSlQ0TnpYeHNBaERpOHByczlIT0lPcmh5NmVnaUF3N1dvN2k4RE5vSFpRd0h3OGdkUUg5cnlKZ0p3WWdEczk2Sk9aMWFOQW5BeUFJQmZnci82dHdEd3NRSHdPSys0WmpzOHd4bGJVYUFEVG1YWThaQi9aeGgrT0FCTS9UUDVQeFlBM0NOYU5BR3NZZlJxUlFHWWJGanlwOUxyYjB3UGd1aFJrcGdTUmxOTTlZcFJSNW5Zc21xOThSYm5zSFFzMmRGQkE3ZnFmUUFKNXhmWGZZVDZFdUpCM3Z2Q2E4UXMyQVBrZkJmNE9BQWNDSFNGMjE4RmdQZ3lCdkh2OW9JSllIRlBGdnNVRnNzSGtBRGdYNHNBekEwQWpHc0NJR1lIT3dGZ1I0bUdKVXhaaDMyVEVBQzR5emlzNy9kcis5dFB6OGNkTkFYSC9mRjZESHBlTHdON2dBOEdvTXVzdnlUL2l6Y0FWeFQ0ZEFHQWVnV0xBS0JhTFBJMTJ3YU80Vk5zQUtpNVpLekVUd1VBK1pjV0FCUWhnODhCWjBURDFvUndCL21HRnl3WjRRQnNjUFVnMXdEbGJlamQ5clhWZ2RONjBqUWM5cnVlcndFV0FNdi9nd0Fnc3liMG51bm9RSU5FTTJVQW1IY0hBQmlNUmxuQkFOaWIxNWNGNE05NnNZNXh3QzZlRFdaYk13Q1JDb0NYRzloNFpFUzdYNmJERHdJQTk2THNEUTA5MDYrNGIxbzFBQU1mQU1oOFdrd0FYSGgweE5vR0FCU2FrZ3lDd2oza2lFZzhESmJTVEtmby9kVUhUUnIrZFFrZW5yenVrZ0RQWE9nL0o5RUUzTzNJS3VDcVFUcHhHd09RN2c5SE9ta2tlRDhBNFBCWDFGajA0VTRnbVMyajNQdFEvRnJQZk53MWx4eG83OGxlanJ1QmJJT0hUQURXQUNoa3RHY2JQN3pvY1hockl3S0FGbXJFc0hZRElLY0RvRnZaQndBNStaaW1EUk9UdnhZQWVQa2RUUVd6M0EyTzhTWkNuNHZZZ2pjWmdJeVBHbmszRlFEemNjSGx6L04wNktrQ1JGblcwUVIwMHN4UW41bEJGTUQ1ZkR4NkFuQ0I1Y0VIT3dEaGxrNnBacTdnYW1VR0FFWjFzZkwyQUVDWE5WdmlROFN0ZjROcUI1Y0JMeGNBaDlkZFh4WmpOOWt0Tnpob2hiUy9BQUR1TEVtOHdGcGVRQk1GVUtBWkFFRmZhd0ttaWJKZFo5NlkwbUFLNnIzOFpwWS9CNEI0Z0hLTUY4a1l1RGJZQ2NRQWtGQXdmQ0pYL2hpQkZoOVR6aVhrQUFCYjd2Y0VBTDVobEdreG1YYVFqRGN1QUU0MHFmZWRWQUJYQUdnTVFBVUNuZG9qNTdyU21LbWhhV1FPVlFBY2dLd0NnRU1EQUZZZUdtQW1BeUNra2pZRGdFYWpzQVlZdlJnSFAvZTN2MkdzU2x3U0FOUUx5RHZ2UVFCc01RamxuK0loRUVNSkFZMkJkcU9aYzNoRXBuYnp5L0l2YUo1bmxRYVkrQUVRYldnSEx2WHV4MXNDQm9CUTZ5djM5aEJ6aWJsa1pSOWdQdGNRb0E2SEt0VDFiQlNaWTNMQmRocEdNZ0JvSDhnQklGbTk3Y2NUUU5KeGdmenBHSWdnd0tPZ1RBZzBtanBJZWhCcjBwZGFHZ0FQRUIvd01iY2V5MVFHQVBnREFBQWdqd1BLZ1QremtJRzQ4RU1FZ0NqNktnQkUyL0hPRXBScjc0QzBQUUM0ZFR2dkFRQXdBSGdDRUY5RGlRR0dRZTJSWTdUN2ZDL0liemUzL0ZGVlUzNThJQUNoU3dNc2hBNGhRaERYMkFnRVFpQUNJSnFCdVcycEFBQjUyb2MrOUFvRkFOd2tIdGtBUEdjRUE1QjNIazBBN0RGYWxFRCtJWk0vR3draU13REVhUG5kUFZkTFdYanJoOFl1cHNyOWo4dGFEbnhyYndaZ0Y4SUl6ZlNBQmkzZ0xZTXBHQUIyQVJGdHdiaFI3VCtNQmxRQk1GVXFTdThESUF5M1FKcU9sdC9wVG5VQ01BREpic2NPQkV2VTZPdkJCQ0FEQVAyL0lSMENJNDJGa1Jqb1ZBK2QwK2RMREl1YlcvcjAvdmNFWU44SUFFWDl3ek9CaldZQ2FQUk9ET3RQelV2MytUVGhVd0RndjFpYXJwYmZ2ZXMwSkNwcksrd0VrQW80aTJObnU0L1ZBVUQrL2ZLQ0hBQlIvaElGTEQ1WTBWdElsLzNGMnI5WWx6OHlBTUk1Z0g3RWo0SElvZ21zN1QyZ1k2TXp6QXMrSEpTQUlFYmk2d0NBWEpFNGpsMURIenJITURJQWdMcEVjUlVBSjAxM0hya1Z3QVY1RnZsTEE2S0FWOUNwYWpESVI0b004OUxldTlvd053OVZOVDBhQUxvSmhBQnNMUUQweVhFdzZ4dmdCY0JjRGYxaHoxQVZQeXdpM09LZWdLaXV6VG4wWWJqSGpVTTNtelVESUdRN1FRNEFjZ1BhajNRQXFBUFl0eXhLZ0t1MkhEMFJiQ0Z5T0t6SzNiWGNKSDZ1QUhKVm1IczV6RWNCd0tlQlp4RUFGUUVYQUNzckFBWUhzQ0VBY0hJMUJRREpQMDNianV6Ky9oVjNqcGNCUUoxaTRVWkFtRHc5ZkJRQmFNUmNYaXJ5dDgwSDYvY3EycFQ1ckxJMHk1LzB0VGlmUFFFWSt3QUF0NEUwRExSYUwvajhFUFFRemdsRUFNem5NZ0JDWWJBYkFLdjdod2VBNGNtMXVQTjVraVJaMkc2SkE5UFV5VWtvZjRPWWdEVnpIR0NGOE9GOEZpZFBCdzhpQU11L3dBNWdYeDhUcGlpQ1hzditXL3QzeXI4ZzhqK2ZzVGdWajA2RUlBdkhreEVCQUJKQXBDODdnRjhQZ0RSTjg5RGRJbSszZzhPenFnQW95ZnlYOW9QdWY5a0FHSDA1QWtDM1pmcmNwTlY3QTltL093RENKaEE1Z1JTQUZWYmZLZ0QwSkY5cURhQnVCRlh4aStjTW1nbkFEaUNPNmNJeTM5UU53SDZQaCtiQUU0SDFoczFRaGpiZ2ZENUpvOGNmb0FPby9JRUNFQXhBcjJkeDZNSHF0Qno5M1pySnZ4QzZXc0VxVmdhQUVnd1NJNzBjQUhod1FBQXdCb0srRkFEQWxTOEtWNU84WVhFNDdCSUxBTWZ6NlhRUlo4OFBPL2NoMEJia0wwUUFlajBIQVkwQWNQWXZMZ1FIOEIwQWtFMEFGVHh6NEFBQThFL3V6MEpETTBGZDkvTUhLd0hnK3dBcVJkankrMXJnOFgzRzFlbEFaeHdUQUQ5MXlCZlFIdnM5R1RyTENjanZJZ0NWNC9mUWROa0tBeUFBMEhYZzIyOHVmcjREUkNiZ2VHUUFpSzRmMlFKbUJ3UUEzZ2JDN0JFakFDUWo2Q3NCc0R1Y2lnTGJiclA4d1c3OGtoLzNEZ0F1a2hHNGxXZzBlUFBiSDVYalN3YWc1MXJRQ1hRQUVOUVVmbG1JNG45SEFPaFdjRXRqY3Z4ME9DVFlZd0Mwblowc2FwY0RLTDByL2xjUWZ4VEdVQUdneEM1ODI3WjVUd1RTSWFPRHp1TXUrVGxMRXhvT1ltTWwwSnd4RWcwVUFFRGpRQnNwQWZ3QityZ1dYOWdCVkFIUWQraXZ2Sjc0VlFCSVR6TU9nQ1pOUG1xTkFKRGo5SkhqZHdFQXVQSGd6KzVaYzZSTDFDRExEc0FCOTNtUUpvQU11L1VSSUx4MWh5WEpBUnNHUGdxZ2g3WUJsRnROL3QxbXduOW5BTGo0alN1U0FCQ0Y2SUJBRi85cVRkRGlpbDljS0FnRWh6N2dNbjlibW54d0srSGhCblFDWWhVQTJBSjVuK0VhMzBLYS80Q0I4a2VBTnVQcDlBc2lmN2NESUUrTUh2WXREUi9CKzNtSTNTQi8rQWZCRWJvbklud2ExNUVFU3I4aFRZK2dDWmhONThBRWtESkNzZ21VbzBWZkM0QWtwUUNVUFhPYU5MTEhWUUNJUmtCU0FqNElDTDJZME8xZkpYLzFjQTlGZW0zNHdwbVZaVzBBcVBYSHJVM2ZBUURSQkhnQ1lFREFCWUJtWEV5L0JuWDdPNTVJZ1JlOHNwMnVXaU5SMFA1WXU0VFB6bVFtQVBXN1FBUVVHZ0czZnBjcVpUWS94QTRBYk1YUzdXTXh5UEszQU5BVlRVRFl0eEFRK0NzQXVaWDk1Y1FhMjNJQWxMQ09EQUNRTkFZZ3h3Q2dDZUttTUJDSkJINHhBTXBiTHFaWWRVaW1aRXJiSTFrQUFBaEErRW16SDNVWUhFYWdReEV3WkkyMXFla0hBUFNMMG5ELzkzc2VBQXlIUFVPaEIzaU9sL3lWTVFab1UvTVJBSWhIUXJKa252Q2ZQdDdNNTFZM1VBYUErM2tXYWVNUU1BY0M1M1hCcVI4VUFFaUF5QUQ4THFmTk1VNkhQWTRGUmJJTlFFWmdEN3lBMDlWQWdJZ0FGNzc0RlhIOEJQRVhLQVhJR2dIU0Uzc1FBQ0Vpb0t2Wkw2LzdYNUUvdFAzVS81UFZQeFpuSm43QnBZb0NRV0JQUGp6U3hyaVdRUENYQlFDSVMvR3ZTMW9aV1FsQWpxSkJ5bDRBK3dJOVJ4dDIwcTZsMnd1bytDOTVKc25mRDRCZ21BN0pEOFVDejlLbEFBckwwZ0E0SE40SkFDNGRVZE9ENytnMjBBcUFxdlQ1MTZLOFBRREFlWDBzcCtjMkZLKzMwQjNsY2pwbWNHUVNCNENPemtwZ2lSRHM5U0MzZnhjUktJT2VzeGkvMTgrWlJIS2NBaDdZandBc0FBenpVRzBsaSt1NzY0a2ZDaDRESURpQTByRXVhWGJMcGFrQ2dKSkNMeWZTR3ZsZ1BRMzhPZ0NRYlFDV1dRRlQ3ZUExelV0Si9nZllIYzBGUUM2cEFCbUJXd25JNmlvMVcvaEc3ZlVML212QVRZTlN3QjN5TndJQW5ZQXdMd0x4YWIyaFpldGYyR1V2empUNVBBRG1UZ0FNUXBlL25zOTUvcTRTYXNJRlByZ2tCQVdEU0ZhWGtOS0JyOWxOcVkyL25vOFprYjhPQUFxRUhGajdkek1COEwxeVdOVWh5cTgvTEFUS1lQMVhHc3Z5OXdZZ2dBQ1V4WkFsalF4TGMrekhmdU5mOE4xUHRuOG4zZjdMUHA5cFJRU0FnZ0tnZFFqNGlnQ2dwQjZUeEhoN0xBREF3UmVBd2p3aFhvM0dLUThoOFdkSk9LeTQveTBBUUJXUTVLaGxGVEFoMEhnWHB2cWVva0w4SHdkQTVOb0djZ0RDK2R6aEJ0cHlQb3dBMEpIQUVBRGNuZ2hLRWRnQU9iSFRJQ3J3NThCTzc2bXdEYVFqeHJFSlFDM2Y0THRjQ2k4Q0RFeWd1eitrNG5lbUFIUnRLbUNZQXJHVDMxN2t3MUM5LzMza2Y3a0lnMDJnOE9FeUozWWFBVUJuYzJkaFBFSm1ST0RyQUlDYVB1Tk52T20rSk5mdGRNUVdvQUlBSEE5c1FnRE0vc2Z5RHdLbi9qY0N3QWxJcWV6U1lkQWY2Z1UrMWRML0lBRGtUU0JmdEZLSGJnUERqZGtOcEVWZzhnOVpZdGthWjN4dFRBREFkRERTRFNiYWtzemU4MGs0ektFeVkxZnVDcmNBWkJNbzZuOHlReGZhQUJnTlBJdFRZSXA2Q0pSNW90MysxZkpYakFCMEJNTTB5MGtjcWQvTGJqZVgrUEZuRlh3K09NeE1EUDRjaE1XS1F2bkpEN2NNN044WUJvTG1PUVBnS1BtTE9ITDBKUUU0WDYvYU5GK2hOY2I1c04rbmJnQU9DQUNCZ0tJV0FZVisrMXZPQUkwMVhveUFJWVNBaEJGN3ZjSXd0WmdQTFpUdStoTTEvUGtuQU1BRE9CUUE0M0d3VU85aFN2YUFlV05TZFFGMUswTURBRGk3bTVaNUg4L1NZWTRxLzlPWkdnQklRQ1F2WWdRT2NEdUpSZ0plaktPQnExYXVpdDkyQm13SG9COFFCR2dZdWRjcmJ3WUFaUEZqc1ova2lXYjArSmRrZGl1Yk9VbjgvQWtRZ09seWlvNkRpUk1JMzhCa0t1NEd3TFNhQUJBakFQWnNmSTlCL21nUXNqY0FnaU9ndlp2YkNBemxBc0I2QVBTMHFrSDBCdWdvVXpubDFTeitTUlArQndBUWJVVHhZd0RFYWwzQkJJaDdSR1VyS0JhQ3dYcVJ0ZEJ5VXRvT3lrc0lCT0ZZTGlRQUovWVZtdml2c0RWU3RrZnpNaVBUaXNsYlFEL3dpUHdBTmhYVXBGTE15VGxRQlNqMVAvWUVFQWNCR0FMK0JqQzV5Q2wrYVpnbEVUb1JQSFVBOWVJT3dRUW9LMGIzSndzRmsvSXdsUk1GQU9udXgvODJBb0RmLzFvOFFOa1ZrSXdnRVlEajhhUzU4RWorRjFUbG1pWldBTkI3d09iUDhHODhIaEFBS0pSdVE4QzhicVhYL2E4M0JqR1hpdENPWXJDL2dBc0E0MTJQOS83dkRvRHFCaklSQWZlTUFEQU54VFpDSEFHREFSRFZ2NVFRNGdhQWxuY2NqbElnaDE0eHBQOFBoMTBhVzhXUElZcGgrMC9vREpGeGdDNGxZRm1wcC94N1hSOEN5RFB4d0QvZDZwdVVQNVcvQmdBLzg5RzJnRmlxakJRS0FObE1palpFV2dZQXlQMUtBQWcrRmdBeXZpVy9xQnNsVWhTZlZnRUFkQUNLQlJ4UVBBQmYzMHRSRTRIQVMveFdBSG9hQUtodlVDZFhiMzRiQVBsSEFoQ0tDZFpjQmFCL1liTm9DZ0J0SWdMTk92NFpXWHJpTis4eVFaL2dCUUFpQUcva29SOXd4VWM2V1AyZjJJd2NGd0QwVkpqc2tHQ2x5RldZRCs2TlFPNGxmanNBQWdMc2laME82aklsM1AxNGVMbm05R0hCbjVuUVZmV3ZpRitVNXZISVdJbW5Nd21Bc3hHQVk5WVMwMnUxZUFBL0MrQUEwSzI5Nk9Scm0wR2x5RndHUUQwYjVPNDhkdU9oSDNDR0FRRVlEOGZlWDU2VENTbEo0cEIraE9zRVNidmtmWWJlUnZJRmkxb3FvRmNUQUEwQjhYa3dDNkZmMGdxUHk4WG84Yk84ai9zQkdQc0NFSW1wRlJvR01nQ2JLUWZBSUU4ZEFQanoxVnpwQTZXS1h6SUNrQURreEFIaFVRV0pKMTlsc0R0K0dyczFBSDBQTkF3TXZBc2lBUGtVdGkyaCtZamVTLzRPRGFBL0RlV2hCQ1V0OExPSUg3dHJSb1dkR1hYK3dRUUFXTWwwQ2VSd3ByT3l6N2crekdRQ05QRS9Hb0R0cGlZQWNJSkhoaEU0bjJoREJPd0E0UGxvdmdEQTNlQ1pEb2lYdklyS25VRFlCQUFMQWp6bkFMb0Jxc1AvNlFDRStnSUNZeUxUbkVDbTFmbVNHazdQY2M4SEFRRGJDcFhVYnBiV2dZMDQrbnVFRHc3MVA1WitoUnVJQVFCdmtaR3JjdFlBRUVFd2d4SDRBT0NIZ0pCMEF0d0FkY3QzUGhOSWN5ekFzd3FBR0FLcUI4Q2ZQMllBQkkvUkNnQ04xZGtCRVBySzBwdWFBaUMwR2F3SkFCbDluRkkvN2lEMHRzRUFSRkhGL1UvZmdkYkprWTBsUk9BcWJnbk1TelFDalFEUUVKRFRqbHI5RWpnMkpnQ29BQmtBVk1ndUFCUkZZUUdBRUNENEV2enBWUUJFbndJQWt5QVBlMEMvTG9sckFnQTNoQm5aV0o3WTVzc0xnSExvUllDcjg2TkIvcDEyT3l3dUNnREhvdzJBQTk0RXZqTUFrWkVCSlJSTUFaaE9ZUnNSdWVpSG5manhxSitIK0NrQXNnOVA5dkpVaG1JajNKUnRBVjJSUU8zbDZJOGxwMFBFcTNReXdBaTRCd0NLZ0Q0U290MUJNUzA3QUVkQkFXUWVQZ0NORnFzQXpKZEFoaWNKQVBIUXNCa0FxOVYwT2w4QkFORHVubmdBM0N2RWNhSEdBTWhDcExhQVRMbWxFM0xyQTBBOVNuSkFoQ0R3TVFPWHV3Q3d6UVJwdDNybFdRejJuQzFPbjJicGF3S3dBUUJzUkFDT1pnQmk0UWFrL2o4N3JnczNvZ21BNmgvUGd4SmJpZEIrY21UOEpQZjQ1WW9nMHQxUFZmMG1CQ1JkTGk0b2VDcGppL0R4TmdGUFR4VTY1dUF0eFpsQklJZmh6UVRjaGc4VVB5OFVnVzFPd0VmZzRWNWJqRTRHd0hTU3B5dCt0dklFWGZRVGR3S2xhTUk3QWJEZHZoY0ErT3U3QWFEbnhEbVB3Sm93WUViZ1BRRG90RHBmRkFEY2RVTVdsUVlBblRFckh2a0pBSWlIeWZDZFZJRXJxcjhDQUhXSmoxc1VQd2VBN2dNUUJobTVUTnowVW85QTFBY2FBdjMzQUFBWWdlTEF5L3d0aXd0WkZqbXZDTERKSHYraHFRb0Eyd1p5cUpvQUFBTjdBZ0Q4UElEZStIRG9sTjNiL3lBQXNOc2dBTEFYL21wNCs4bEwxQVJYb2Fyb2x2ZmZBd0JzQkVTMy9HTUJZSHNINWdTS1JrQlN6R0VZUDRrQVVHZGZiaVdtTlAwU25UOVowZ3lBeUg5WlZiNU9pdXd3eUpzSWNucCt3Tkhoc3lwK0RzSDF5dE1IYnJmZ0hRQUFLcUFEazF0UXBwOHBucFA1TEFzQTlDUUJtUUM2Q3ppeEVLTWNYSUpQLzNjQlNOQnNhQjBBK0djZlRTRllmRUlqNVkvY0tveEF3OG1Bc04vaDBRWkFscjBYQUxrWkFPMDRUVmJMVDlKWmdOQk9EQTBkVmxyOWhDYnRMOEpGaDBJOGNJazJBc2s5aWNONGx4MVFSOG1VbW9BZDJ4TXlBUENsTUJrRGZ3SjZ6UUJvdDlNckJFQ1ZaNWJWRXI4ZkFBVUZRUE0zNFJNL0hvQW9lbDhBb2pBNW4xT1lsSDI4SHBLVXpOVmtBTUJEWWpHOWdtK2tLUUhFSFNRWmdyUlR3V01CQUg3ZzhSMEJJTHVBQmdBd1ViSExPOEFBckVNMWQ1VEJ3TnY5ZTZ4TitBQ0pHNlRQdG9IUjdqVHM0ZGFBN1Y1d3ZlNzJPK3dTd214UnZDVThaRkk2UGJ1WTVPajRkQkxLeTFHRElkbzEraDRBbEo1UndBODhzamtlZW0ydldlU1ZCb0J2SzQvSmZCNnUxeHdBTWNPQVI1MC9Ib0NIM1BJT0FMYm5ZVmVlRTUrbEpJeUlYUUo1YUpxMFBUaWUrZUV4QVFDMm01V212andHQUFCb3R6aDhKQUJuS3dDeE1iSEdDWUNoaEVpV3Nmb1YvamQ2aDZYdUU1T2oycSsvbSs4aUdsTVdCbXBrYkpUZW5tNnZ1UHg1VW1xaFRxL29Qc1FHZEhEamMxOS9YLzNLZVBxakxBeEFyZ0hBQ1BrSEFVaTJrV0hpWkh1WWJtTVZBSFdBSXJxMDNDZkVBRnhMdy9paTdrTUFnRnZCeStITEFzQXNBUWRnb1FCZ2FQdGgwL0h2STNvTkFPRCt2UmtuVHJibmNjUVBsV2g0Z01lSVdKTXQ2aExDUkNUZ0JoamxyNXFCcGhQaW9RcTRtaDAvWWFPbStJZllZN0VBb0lnNGdkYjVqK1FEbktWMHczOE5BSGhnZURLUEcrb2MwcDBDUUpxcUtLZ0FYSW95TjNlVDdENENBS0FDMnFmenB3S0F2MjVWWkZoUUFGWWhqeE56QUVMNUFPbGhmbDVkQUhEa3IraGJCMDRDa2JNQUlVWkJucmErMysrWU1ZRGVJTlFBWmNkci9GdjNEaThnT3pxMmVPcVJzTC82aDlLRkFHei84RUNRS0g3OHYzOE5nT1NRV252QmhsZFlWQzRCd0xVQkNSUmtFZ0RYUzltM2puOTdFQUNkeS9sczJBbDhMUUNTRVRjQllzNllJWWY0L1JFd0JZU3ArRlBYd01GZWllNTRLdlpFMGdadzFqWlBJYVNuQmRlaTdUVUJzdHU5UXdXVStmbGdPdTNKYklmQzNEd0lVVC9UUW9kQlcyb0NUbExGZ2JUK0NRQlNkQTluZG9tMTgzMlMyZ0NnL29BSXdQRmd0U2VLRjNBSEFPME83SG4zNlFDNDBxdUViV0JzcWlBeFZCSzg1NGJQOFBHSStNRmRmSFZJRE00YlpLSldEdzFGaHpBanhTVEhyT2c2QnBnMmxMOFdFTzdEYU5EUnNmVlRTLzhsMVY4TkFBa0ZYNFNDUTFKM2p0YjErazhBZ0tvSkQ3dkNaZ0hhYU9od0RPL3duUzhBNS94RXB6L3B6ZVJiN1ljQWdIS0RqbDhYQU5rSjNNYkdNMk1WQWRFRVdGRUl0Uk5vaTNOblB4QVd0MzlBY0Vkd3k1WmQyN3d1cUxTTFhlWUdBQ0d3cDYwbDhsUGF0bzcvRXAyQWJuTUM0RHNGQmZBQ2pub0NNQTFTaVVkV0p1ZXZMZ0N5S3dnSXVQNHJBSnhQZGdEYU1QSU9iclE5UnNBRGdOT3BjTTJ2YkQ4RUFId2k4T2tBSkpFdkFLRUZBUFdoU20xZUJZQWljQnNBT0FFTXRnaEh2Y1hjQUpRNThMY3lFZ0pTczQwWkFyZ2NEWFVzenB3QTlCdUtYL01Edyt1UkpZWmtyT1VQT3hWeW1vQnFBRkNYTUR3eDRCOEZBTy9qTUFDdWdXMjk4bkk5ZXdNQSs5VmVYUE1yV2MxSTl5NEVVRjdBUWNnTStnd0FmRTFBb290ZkVHVTFBTUxqdkJiWUdkMnhiLzVvOUFjSmt3eU1MTXArMnk2emZnbTdES01PQTBZRWNCSTUxTGxIM0Z5c2hCTUhiZS9XVVVyLzc5Z0pkQzQ0VTBOTENHTmhxWU94RUxUS0M1Uk13UFZ5RXNvUWZiZUJQZ0FZc3drL0hBRGNYTEFjZGl3aXd3TUhZWnRwTHdEdzNMRmJ6LzUyM2VCaEFMU0RRa3JXK3dBQThyc0FxTkR0TGhNZ3BKcmFNanNjMno1ekZUZ1FKNnI2T01Heis2NXBWaHNlQlZBZ0FNNkhQYTB5TkFDQXU4b2dBd0FuVncyTjc0VG55VW0xNDNjQjBPcVZ2Q1hBVVRzY3NqcUJadzBBMlNhY2RpZ0Jqd0VBTTU5UE5CLzZrd0J3YW9DN0FFQno0eDBESjlFQVVFOEF6bWplQ0V3SHRZMS9Bd3JnY1FDMDIvbjFjd0ZJRkRrbzF6OGUxUURBSS9GRDdnZFNBWUR0Q2NJUjRBNVpBRHd5MmpheHI5dk4wYWdCMUdkeUx3QWc1cExqbGlMSW1wREJSWDBiQUwxaC8xRUFkTkNCd0Vrc0VMVWtoWmkyZ2ZvSlAzOXdoeTcwaWZUWXd0RmdpSUVXQ3Y0SEFEalFJUVBtaVgzZGJwOE1ITXhyQVZEWWVFcUg5em1CMHR0Q0czQ3RCNEIydTJzQVhDa0F1UVFBbVQwdkEyRHB1NGZqckFJQThTTUJFRG9CeEZwMnB5eHcrU215K0ZGTE1lQUNrQmJ6YU9Da2NlTG9EV3VBL0VqM0FWVDhGQUJ5R0lRYTFMR1JGVUhYK0hZQXAvNWQrMEJsSHdCVms5QU8yQ0orc1p5TEMxMERnQWsyRlFHNC9qOEFLRytoVVNJNW5qanBBOEJSQUFCcUZIVUdaSmNNZ0JRYkFONjdEeGdXcCt1N0FsQTRBWEQwM1pJQVNFeU9YS2czK2ZCd0EwVWpJS1owYTZXZ2FtR29YamFlNHJhU1Y1YkViMmppUFdUenhwQUoyTzhNNFdDeUNVU2RCUzl5V1pBd3ZoUzhIUjRBeUFxR3V0MzdDZWlYcUpzbExkNTBOd0JsUlYzR3BCQkJzR200Q1RlYml3cUFGaEJxVlRSZXN3QVFPZ0h3OWdNZURnQXU1S0dDUVYrR2ZPTGt1UklBYUdCNXEvTGJyYStPaU82emFjUVBBNkJib28zNll3R0FjWUJ3YmdaQTNnV2tqUUN3YVFBeEpGUUpRRnh2YVgya2tBWFlrekV6Wk9Lb1dzelg1NE1hWUxkeENvQ01BRTBId1JyZ0trNHRDdVVFd0lEM2wrOC9Db0JPaVNRazkzQXhwSDhkM0gzaFpKOFFBUUEwQUdtMGZqSTJJMFVBN1A0aEFQRGRpWXI2TVFiOVhKZzRxQU9RcGs0QU1GQzhVVXcva0dZTTNFT0FCRUQrN2dDY0hBQ1krdStMenBrRUFIdWlFdE9UQzB0OUQ0Wk1mUi9VbGZBTm0rZ01zcVJPckxZdjhyQzVFazE5R2FhbE5ISHdoSWRvNzJsU09NME1saExDSUFEcTRMSWNqWkFoa3lXRkZUekVDK3kwaDdCMTRKWDNDekgyZ0ZSYUFkdnJnaVVBeUdFUTBBQW5xUWFheGdTdTExYWEvZ01Bb0RSKzUzUkllQnNvQUtBNG9nSkFKZ0ZRTlY5bytCZ0EwRWxWTlFEYyt6ZG1CT3RuQVZZQXVDWWdBS2lPb09pSEVRQWlpWkxRQklBSkFROEFaTDBlaTcyZVJBRG9aNVJieU9IK1B5eDRZNXM0aWthT0lnRDJ0R09FbkJBcUFuRGlZMmVyNWt1bGp3Z0Z0WHNFZ0xPOVlRd1d1ckRsT3gvZHA4Snc5aVhZQjFBQXpMM0pZVWQrYndEaXh3TWdiL0tkQVBEUEtKNEVZZ0RRRWU3RktqUHFBYURoYVJ3QXVUQ0V0WStBQUZ3dnZnRGNpc1pXUUFhZzhBREFFUFZ6SkFVSUFGd3VWeU1BcDNjQ3dNc1JmQ2dBWkZac2FaczRTa1lPb2ppUUJ3RGk1T25LT1pQTlE0STh1Z1FCNEY3Z1F3REl2UUhRTDY3a2VOTzZnRmhpeENMaG1sVUJzZ2NnQVNBN0FhYklBTXZsMmUzd3VHZytjYlEweWYrQ0UyOEVBRmpqRUtGRWxBQWdUQzJyVkFMOXU5TUN5Q0NSazVnWFFIcDVpNzA4VE9XZFZnUk91ekJpSnVCcU1BSHdkUEFEQUhEaThFZ0FjbTNlcER5dEcrd0J6MlRrbmc4QUpwcjBpZmJjRmJ4YkEzd29BR1ErSlFmQXNmbE9yRTRnU3dlc2RjUGJHd0VhQVRBOXFHWHo3VE02WnNveS9nTjVBR2R1QUdUVnozc0Y0QTVTckVlTWhRRHR3YUovSHdFSWdBSnUxZzBBOEg1ZTlRRUl3NHQ2R0NTMXcwSzdnRHNCcU52TzVaMEFPTktKOFdiNUl3QU9QZ0NBYXcwdWxRU0F5YWdvRFBUdnlndm80c0dJRndVQXRhR2I1ZmozRVFDd1M2ekxKUjI3dG9HV0RuNWkrLytLNHo1VnBwVUFpRTlrNFVBOEdzWThJSklOblJOakFHWUE5cXd1d0d2V3BFQkFlRStaVUpkT1JzME5jMEtPMW1DZitReUFCUHBPT3lRbDRUajRwRHVBaWcvd2JRRklkd1FBazlqd3FMNjhMZ0FYcjhsQzkrNEdQZzZBaXhXQU5KWmpiWjRBR0xXNnU0V1QwY25Uay9NY1RxQ1FDMHlDUXp5ZFg1ZzJxWW9mVHAzTnFRRlFlNFBJaXd5WThTVEE0QXMyNlI3YVk1RXF1QkhNRG5yTEw2ME5vQ0IxMlFCd0FFSVJnT3YxbEhzQm9LM3ZBUUNkQ25NMXpYL0E4cyt5bWdEVTFRSEVGMnpRTWFKSEl4V25TZ0RFYWFKR0FCUWZnQUhBemdNSkpCeUFuZm5LTXkrTEFlRHc4U29TL0dPN2VObHVqbzRFSU0reEFhbnpRaUxDNUJpSFR4dmw4c2RuN2NlTW13QlY4Zk4yVVJRQWl6M3hVd0oxQ2NBcGkvdzhRQkcvZkF4MDlDb094bG5CaG93Z3FpYitNUUJTQXNCSkd3QnlJZnZyQmdBMElLQmtVYUZlRFFMQ2J3R0FNVEhQa3JGakR0cFlMSTA4RklUOXF6cUE4aXdJRFFHY3pvZkhoY3NBd0wrY3RHSFk3OHpPbjl4QWtyUVM5eDA2TGdjSjhyck9JUElCT1FCblh3RE81Mm9BSWt0T0lQNzNxd0xBNWtQVkJBRDRnVWQ1OWdOZXRQYXVLUURWbzJadjl6bUQvZHRIQTBCakFNSmhrSDZ4YWNHTUJJQXM3WW9zUGs4QWpIcmR2UFdqV0NpdFhvZ2pTQ0ttdVBFL2NuelFmOUVseFVIZy9kNjgrUk1CeU9qSTJrdFRBc3FhTlFOREFnRHdWcTU0aUlBNE1ONlVGR0k2L0ZFU2ZZZ0p1SlRVRGhJQ1RyUXpDTHhNL3g0QXgrUDVMSTBCSVpOUzdnTkEzVmRXRWNEMkExNEVvS3FGVHdSZ2x6aVd1ZzBVSlYyUjAyY040TnFFcjJScVdzblFuOHIzZGVKY3FOT0pEMmFpcmNFMUNGaWJTTkVFb0hleEVWQ2FOY0t0c1N0QXM5YkprZkRaTlVqTWNDcGdBMkF2QTRCSHBKMncwQ0VDOU90L0N3QlkzU3VPQVRuZUNZQjl3bVFWQWNLOEtmZjkzN3Q5TWdEbWF2bEUzd1pLWW5QbThURUFqSVpGWmNRS1FPSy9SQVF5Vk9TdEZsc3h1YXNRNklFZzBpYUd6cE43VndSNjNad0RjTG1jVkJQQVF6L2NIWFE2ZjFTekF3QWltQk5ZMHMzd2hZM0d3c2JnWHdjQVh6VmVYMzBQQUZZSXFoQW9xaERvZ1MyQUZ3QThXK2hkQUhCQVlBYkE2QWJxNXp1eUtYRDVtaW9BTHZGcm41WCtDYmpwTndXQXFuNUovT1lBTUI4dUtBRkFKNDRYM2twQVk2QU1BQU45ODJreGZLeC9zd01naXAvcWdNcnRINHZ4bUFDZ0EvSW9DUDhhQUh6aS9PTUFPTGxHem50NGc3Y3lSQWdvdW9DV21zRDhvdkt4QU9ETnJ6OEFQRUhhZUxWM1V4TUFrdkR0dXp2TjI3T1RKbjRJeFlUWVJKK0tVeURVL0c1NEZWVUpXeERnL3FGVWpRTWRRVFd3VkY4RjRPSWlKSDZ4cVFTOHBHTGRFamtQTnVaODhnSGoxZ0FROXV6NFJGeXc5andoaENhRm5ZUWZzekdaSHcvQUxuMHNBR0tLUHdmQWRJdlhCa0FZTVd4R29QUUlDbUJ2WUlqRTN5Y0xmWmtxZWFzNEV2aHBBRmowclJ1QWlnaVBwdWx0ckdrZmdtSmxva1RwODgzek8vVlRucDF0eVFEUStXRktSWjQyVXRTc0Ivd1F1SlhGTU9pek5TeTF4R1U3QUpVSFFCUUFRYnhrR3lnQklMdUFYd2tBTGJqM3ZRRnc1SkpybVVSZkJnQ0xaQ2dBY2FMV2p6aWlPN0lKTUhYblQxWFhqejlpUC9QVjFrNnM4cElocUZncUFKYUpIV0pjc1I0QzFmVUV1dnd2cCtZQWlNZTlTTXdvRkJ4ZFdCd0lNOHdCd09ML0FlQWhBQlJsVXdTRUU0YlBBMkR2QTBDU21rdDBOWG1aRG0ra1RnemlMMU5oc0VpYmNzSjlQa1dlbkFjdkFFVFY3NWpNSzU0czhLdG1RTUR2bE5DdEFLb0JzRzc5VU9EbkpKLzJJZ0RpNk1UU1lxNE1BM0pROGdQQTR3Q3dJbEJEL284QklHOENnTVVFb0N1ZTdPWWNBRDExdUZhczFpSlgxd3dIN1ltbW9zNmRQZGU3aHVJWGNWRE9YaWdBRjJVVmQ2a0JKWFVaSGdXZExOV2ZsZUdmTTgvN3BhN2VEaVh1WGloY1Z3NEEzd2IrQUNBTlpqVUNRRS9hcWdHb3FRWFUwalVrbTdzQXVPWWlBZDRBcEViZmpPbmMvWVk0Z2FtNWN0TkNnZnlPYWZYeUFNQlUxR2xZNm16WW5mM2dSNTNLaVJIUXpsNXQyMEZmQkd4TkM2VFNOWUVBTFFSMFBuc0JRQ085U01wbUFPUkFrQThBdTVERUFYWS9BRFFId05LMlFDaGQrbHdBWENLU0FEQWQ1OFo2cUZZVnZIYmtJenVEWHF6czZxM0tJTEJyV3JmUXBKOWVmNy90b0U4Q29hRjBFUmR2WFhBclowMzFWeG9CTmNLRFBpTUNJSlFCMERObVBRQ0lTSk9vWFdJNXovOEI0TE1CVUl0KzZ3UGdWTXNZZ09rdVNaMEZuQzZQRG8xMlNoVUFUQWdZeFc0RFFJajdjREh6REUrREdmQVJ2ekMxUndkQU9CbzZQUklBSEt1bE9ZeDFYVUFUQUtjVVZlOFZGUUJjTHI0QWpQYnBIUUR3YytCYUFOaGQvRThDUU5BQXJuU3h1dUovRHdCd1c3K2FBRWc2bUFnN3hVZFlUMUovMVlxVWJvOHRvSHdLcmQzd3NqVE5Ca0I2bE9kMWlsOXBqcUJiL0h4Y2R5WmtoeDNWaXl4Z1VOeUZnRkMvZWozaG82RHp1ZGIyajlsK0ZZQXpDdGdsSElETFNUM1pyZ2RBc1A4RUFOeGUvL3NCNE5BQWp3U2dlRWNBampCYUUyWmxOUURKenV5Uk1aMU5BTmlsZ3NqdUR3TFpUSUFHZ0Z6UWFZbncyREs5OEZNVkpKek9uNjBPUTJ1eFJrNVRyQm1qZGVTUExNQlY3dnh3OWxvbmVzSWo3KzlPbHdNMEFPRkJjREhZSmxCMEFXR0hrQ29BY0ZKZ2tPeCtBREFBNE1vWkxmd0J1RHdhZ0F3QmtQc0FVT0VFc2tDQStQZ0hBcUNiQUFzQTluelBld0VRSmFJY0RGM2RhY09Gai9SSk45K1RkZjZUUndpQTVYc1NBRTQ3WkFJdUpRZk1BTUJGQk1Bb0QyVHZNUUN6Vk1uYmE1QzJyMGpTNWhVNGQvMWNva1lBOUd6QXZaL3Y3MnpTYXdKQXVKSkZVUk1CdFlYSjlZUTdlTlFDNEdSYlVOUm9DZ0RkQlZJZElLaUlFd01ncmdDQWJ3TitBSEFENE5ZRUFnMTZENXZIQUNEYzRpYzBCeVRodjh3QlFHSUVnSDJiN0trWHFHZnVKUlc1M3BMd2RkMmVXaDZ4QWtDbHJEci9PNm04TjlQVC9meWlmNkxXTjVrQjFJZmZHQkdzMEFJVml6ZngwbnFBT1FISU5kR3o3M0owYXBzeCtWTmpkWkwzQXVBM1Z3S1E3cWtYK0FQQW1UdUVGZ0FhZ0hDOTBwVE5od0Z3dlI0UUFEa0Y0R0lHNENxYUFLc251Q09uQVdGYTZlU1pjL2N0WjNZbVdUdTB2M2xqYnlqMGs5UDg4UUZmSlFRV3o4L2NxazhMQzRzUTFFVUE3eVF1NGt4UER4Tnd5dVVjLzVNb1d5RFdERG5xaFhUVXdCZlBDZllBQUVnRTI0REJMdjRCb0FxQStzYUFBWEIrSUFCbjNIVExDNEJJT1F2VXQyMEVnQ0ExRnVhcEFPakpmVmJ4ZXh6cG1mWjJWamJNUi80VUEyOG5VR3ZSbzRibXRiaTdIbC96bHorWHlibkdjZ0FBUy83T1VQeHhWbG9CWUNiZzNOcFVBekFXTXNQL2p3QVlDZEIyWGswQWtHN0tCd0tRSVFCeUR3Qk9yWVVpUW9NTjRKRUFIWURVWGxYZ2NPaFNRN2hQUDlIYm1hTTZTbDhmZXhRd3ExcDBQcE5oRXlpYWdFdzdvQ2ZadDZJVUdpRWd5a1NiNlZsMThNZCt1VXJqOVpxaWM1cUNIelpmRFFZQUFWQzA0SGF4QWdCdUE5SWZBQVFBOHE4S3dCbDMrUzJyQVRpVnJVT1VWbVR0SmJzaDJRaW1PM2FlYnluck02ZjIxOVR4ZTVFRi9WSEZFT3liUkg0T2xyNzhGUVA3aEJRZE5TcEVqK1ZxUVNDTG53TGc4UDcwSXdudEErVDVOVU9id0tNRkFERVNEQUJJS3dGZ2FXR2JmZm9EZ0RpM1cvY0dLM1BISGZmL3lSTUFKdW1UL0JYL2hsa0FGd0Fvai9SWXR2STNsUCtmV0ZQeEJSdHc0RDh6Vk82TFA3S0luazVvbEU5MXJBQ1l6M1VzaC93ZUFKaGs2d2dEbS8xQ1pYYTd2Q2ZVVFlHRUFBNzY4SzlaRE9Ca0dPeGVaUXBPeEEyUitJUGZIaE5xQWJTcUFIS0FTZVIvZ1FDVXIwWUFwTURnbnRpQTlBY0FKd0J5OVZoTkFNNTFBVGpiQUVCN2dEQjNBb0IvK1hWL2E1VXZhWnE0TW5EaHQyUWZNTjh4T0p3dFB1UVFrQ0V4ci9Jc3YvcVF2N2I0TGJLdEFJRC9VUFVESktQTTAzSmM3cUFpQ1RFSVhCT0FrNmdCVkI4QUpYQ0hoUWtBNFF1MFVnREFaSmRVQW5BUTg4SitBUGphQUJ6UWFXMVdPZ0Vndno2K3RXNUxtcDJoY0NDSzZJQXJCSVBJblBwcksveXZqUFJZUjNkVSszZU9uOUxRcjFiOFc0VUFQZnMxR0FENVNFZ3dCb2FCbk1xbUVBK3h1TXFMbWVGTGJmdFBpNEMwUkJDQ0VicWhrNHNLZ01FVExNNzUzOVp0azFRRGtFbTV3VDhBUEJxQTg2TUFnUE5uc1NBTER3Q3V4K0p2NjI4ZW01SkI1TU9aTkJ2UVVFQmliZE1qV2daUDhUc0FjSXE0V2M1SDV0THpTa2QrOTlndUp3QzVzQmZna2hZRUwwZGxXVitIeGdBSUJ1QjBQV2Z3OGlkbnVlN0lIQW00N2tvQVFMSDFBR0FYQmF3KzVBZUFMdzBBQ3Vza2hSY0F5UTBBVUM0elE0YW1janliMHJ5ZzFQWlVzZHVZZHpVZjNSWnFpVnhWM3AyanlWY0RBRXdIUHBiUlhiYlluQ1ZmVEFKQVA0OWhKWjMxSEVCVEZnaEc0SFRleC9RY3FEVDZudHoyVUFCdWs0TUhBRlFGakE5ZkVZQkQ5dVVCME83OGR3SUE1UUxHaFJjQXdBZUVBSXozaG14TmtRa2tENVlhS0NkMEtQNmNQZnhyYmRCcmxHeDFoTmVpOFN0MGdmSGd4NGFBWHFsamo4NExnVnFoUkpmS0d0WGxhS2N4Zk85NGJuSVVmTkhOeVNuUGtQeDNXdUdoR2dOR2xRaEhCTUJmb045OUFOaVNGcGY3SHdEcUFxQ2NGNzRuQUVnQlJDYy9BSUFQQ0FFbzQ3M3B0RmJ0djBrUEJKSzlRODYySDFUa2F4dGpQS29zdmZ3OFcvc2ZwZXhmRjdjVkFEMUhVd0pCRmFIYWovZmtXbDdxbnhZTnVqZWJHQUNrQUtKRXRBQmFHSWo1bzlmZERRRnc4d05nVDBxRUJ0a1BBSThFNFB4QUFMQUNpQytsSHdEQUFpQUFRaXNBOGxhTnFBREVpL1drMTlhd1M1R2ltclJ0MVBtbUptNWUzcDdGOXhPL01mWGlWc0RRQjNWWG1BQWRBS1Z6aTNad2cxNUpKU3p0OUpUK1A2d0ptRDNrZkxua3FCNkllQUNsUGY1TTFybkFBUHpOazcwWEFCRTlFZmdCNEVzQ0FBd0FLUWl6N2dFa0FLQUxnQUFvNDh6UlhKdHUxY0NWSDVEa3dLd2loZHNxZnRVTzZJLzQ1M001T3p4a2ZGcVFNZHZEM0kzZjRReldLZG1Wam9ucFFaRVd0cTJzK3VLeEkzblBLSGY3Rmc2Vnp6Z1I1S2plLzVJVEtBQ1EzZ2dBdC9EZ0JjQStGZnpBSHdBYUFjRHYvOGNEc01ORjI0VXZBTkFGUUFEOFRjbGdUVzNYcGh6aDdpZFlCUVNaclhHSG10MnBpZEl1WjJVanFFdlNzYVVUVmIyajBzTWM4SkYzZXNhQ3NGcWlQMnVKSWt4d2dpUlBKajlQYXZsbkFrRGZaTElqSlp3SWxFUjVxUU9nTGZpeXJHQUE1TW5SQ3dDNkZleFA5K24zQk9CNC9HY0J5Rk8wQTBoTFB3QXUxL2pHQUxqRngwdzdoS0ZLZ2NrS2lEdUxnMzRRZ1AvRlJrV3YxMmlJMVZtVnV6a2xIR1NUS3BldUVZRHFoQTZMZm5mV2dqUkFnSmR3TThWTkx2K0piLytwckxXZWp6b0E2cFpTMU9ud2hzWjluSzk2K3pFekF1ZmRYd0dBZ3g4QXU4TVlBaEN3aVBBUEFENEltQUE0bXdDd2xKcFVBM0M5SHJFSGVDZzlBU2l5a2dQd3QwZ09SdFZzQ05BZ0ZSQUVvOE91T2pOVDlNb3FUMnJGblI0RHBsYnFwbjlpcDBHczlkdjAreC9kTUFDb2dxZmJQMUhiS3owZkx0WWw1aC9UVkE5U0RocExNVUFlQmpZUmdDMEFBZUEyUFhvQ3NJOEN2TURPNFFlQXJ3SUFiQWtEQVNBR3dBT0F5eW43S3dEd045MXIydGtXcXAwU0FwTHFYdHdHL2U0SzFFaDJvdnI0cG1MTXRoY0RvcWkwMm8rSEFHQnE2NDJFVHRXLzF1akZsanR5TVJaNFl1a2UwREY4bU9zTktLK0dDQkJjeEFKUUFNcm80QXRBUm94QUFMTUV2amdBeXM4L0FvQ0tBejRoRUNzQndHMy90UUVBWjl5M0tUVTBvTFFCa040a0FHN2g0ZUE0UzVYa21oSVZFUERkWXVycXhxMXRCTzBqT2p3S3VJekpHdFVBZU9oMzViSDNBMERXQkdxY3lBQ0F5eURRZmhBd0Q2ZndCK0NVLzVVQStGdWttUzhBV1VnQUdQd0E4RFVBMkdNRmNDbTlBYmpzU2dVQW9BSzBhMjg3aVQxUU4yQ0VIaU5Sd24yMUdUQmlaVHE2SlE5eDJmckwzRkR0Q2Q3cWFQSHlkQUJxOVdteWJ2MndSQ3M3K2xtWGJnTGsxazZpL1Q5bEtCR1BoZ0JWQUF3SWdHK29CV0FBL04zdEQ3NEFaSWNoSVdDNjMyWG1kcHhmQ1FBOCt1V0RBUkMxd01uUVZLWnFtWDEvRXdDb0VpaE5NbU1QWWpNQXNDQkFCYUNNanQ0QVpIdnFCc3l6YkdkUDQ2NEp3T0ZnQlVCRndLT3VXNlRuL0pFQTZKbGU3d2ZBQ1VhQTBEU09YZUVFUURZQVhBRndBRzRoVndFR2k2eElkTWNJT0dhTjB2VE5FOXlFMzZ1MjZYQUFvS3NFUzdoUERldHp4VUIvb3NtN0FRRDg1TjREQUd2S2tKQzdKM1g1Vll1TERxU0x1MG4rQlQvNXVlcXBJQW9BWkNmb0NjQ0JiUVUyR1hZRGZnRDRCQURBZGg3WDQ1amxid1VndVJrQUlHNmdsRDZqSnVXUmYrR1RFcVlERHRhZ2dVUDhlbHF2dytNM2Y2OUkydDdsVi9JQXpwcUVEVVgvOVQzL2sxaTFMMFQrU0hqZjBkWFAvUFZKck9SVkRRRGZ6QjF3SlliOS9pOU1ad0dDQWhBQStGc21SMzhBTWs3QXVNbjkvd1BBQXdEQS9yK28vNzBBS0xLYkVZQmJjbFNMWmxVcEhvUjVpMGZtQjR4U3J4d2U4MTdmQndEOUpKL1BjamdlS3hzN0NsdDdYWGg2K2w4ekFIaUlYNDRGbkhLRGIwY1JzTFR4djJnTlhZd1pQZWRzbDZDQmJJVnBDcFZsd1I4SkNrQUVBS2lBODFIY1Bic0J5STdNRHhna1lDK1FmVjhBYk4vVkJZQnUvYW01TjhRQUhnakFPVlgxdjNJS1lGdWlBcEFBdUNYa0QzSUlTcHk2eWdrSW9vTXRvS2Y0ZU9hYy9Vb1Q0SWpqSFQyV1FleDNIdXBJSlIxYzRIaU9Pdy9vU2NmODZxN09XanBrRjc4QVFFN3pzZzM2MzVJRFFBeUhxQUFrQU1CR29CWUFnaFVJd2g4QVBnNEErTjhqRVg5bXV2L3RBQlFYV1FISUFOelNQUXlhSEswQTBKZ1BLNjg1TUFJR3FlcEFPRWV5cWsveUtOQzFadlBwMWtBSDQvemdaUVFBaC9meGQxY2h0NTg1Z1NZQW5Da0FLZ0lzbnd0UDhVdlQzT2ovNFNlYVRFRlJIQ1FGSUFNQXRvTDFBQUFFRExrWnlQNEhBTURiL0NRNC9GWUFUaElBaGl5dmV3RElVdXo5cGJsdERKME5BSm9MYWdIZ2I3N1hqdG4xNEExQmdEeHh3d2dZN1k0SFh3L1BGUGkvQndCTDd2N3g0WGY5eVhEWVo0dnlHaWY4bUZOODNBZCtjbDNmZVUvYXNHUW4reGdxQ3dLWGZmblhCUUJVQVRVQVFKZWVCUVNBSjdEL0FlRGRBVGp1OE1TdWRIY3hlZjl1QUs3NVh5Y0FmNHY0ZU5BQjBOdHpNUTBBL3ZxTW00RlJESDZteWRmUmhjOWlBQ296OVk2R2pmejdXUHV6VnZibkJFQkV3VExqeTVibTU3SEE3YitqWFZpTTdwOXBBMGpCZ0YvdWJoVUEvSTEzK2VIZ0JjQ0JUbEE1bnlPdUJLWnBWdTNnZjM4QVRqNEFuQjRIQU1yakJFODhzajVjRnZQdkJLQTRsMytyQUxqOXlUTUZBRnVNOXdEekxNNXdmc1pweDVWQU1OOVZUT0V3QlcrUGFuRE9IcXhWajI4Y0FIaDE0TEErd1RDVVhjbmFNRlFFcTA4MnZQaFNmNUVDa2NNdUpRTWIwMHRaQXdEMnYvT3RFb0MvNWRzNXJ3c0F1Q0ZDVHNBZ1RBOWZDNEQ4TGdCc0ozWWZCd0NwL2RnbEtacll1VXNQUlZrZmdPdDFyOG5mQU1EZjNVRUFRTysrb1FKd0prVXZoN0dJd0k1bTgxcTF0eHpuT2RzQWNPL2pLalo1SitGVXBoa0E5b05iSG13NXFXckNSSXcrcnNmUk85QUV3QmwzZndDN1B5bjRVeWwraWdBa3FQanJBOEF0RXRKcDdBQWNqaUlBZ0lCVExOaUJZWmhhNy8wYUFGUnQ1T3NCb0hkaXVBdUEwd2NDQUxaK1VZUW53ZXhPamtIRVRnQ3lteGNBZjh2NHpIWUM1c0F0SmVRb1hxdkxKUmZzUUJDTW96MlVMVkFuaHpzOXMwYWVuZkhPdjE1TkVOQVVYZmtGVnRXdFRtQ0hyenp4SkYrdi9kMjFLdjJmaEpWSTJpY3EvY2ZqbmZMQ01ZZmFjUWhVRktsQi9rWUEvbDdpWXhNQXdKOTYySWdJRERicEFZcnYwd0E0TndmQTBJLzFZd0hBN3d6Ky81aWxDWlAvb2JBUEltZDN1a244cENPTUh3QzNPSk1kUVZwbnl3cDFqZ1lBOEo5NjJEekphZ0F5OEJsTDFRQjZYc3daLzQrWmNuSGp4bnY1dTEwM3FieXZ4bmErRWdBUzlJUFNSMlYvc1BZL3lTNnVTZlN1dTc4b1RBNkFEWUMvdHhEY2RrcStMUlcrMkZOZEJ3Q21xVWFqUUdJZ1RMTjMzSjJiRFRzNWdmbTJBTUFEbi9OeGp5cCtFUUF3OG50eFNMOEtnR3QrcXdFQWRBT08rVmxLeTVmaU9ZSnpkaFNIWjhDUFhoU25kQ3dhZ21Bd0dJY3gyRnprWjZpVnRTRWJqWmZTY2N0VVorTmRpTUgvYThuUk5wVndYazRYdFhjSDcrZFJFZC9SWndlZ3IzRG01L2w4Mk5NOVA5bjRhOHJmOCs0blR1REJMSDhiQUpDQVBHOEtBUGg5S2Q4UkRBYjR2K041R0NXN1RQVDVIUkc4QndUMU5OMGdudEhMU29IZXdlS2psYVU3OUdYWDZpZWE4akpPK2lPQUlpRDZMTnZoTzU4Q2tHcXVuNmYzejhSdmRnQmRBUHpOZDJjNUg4TTJTRThGQU9NTlZFNDRwQURBQlRWQk1Cd0V3OUZvT0Fack9wM09IV3REVnVpMUlyRHd2N0d5SXJUWXQraG1pdkVEOUdFKytVVDkzbU9sNUgrdXVlcTBxV0tTaWszVnRmbWMxaytSSGk2NitCM2JmL2xJR1AwdksvL1dCZUJ2dGo4M0J3Qk5TcnBtNFhoQTVJKzBRQ0Q2aHdQM0dnbHJMS3daV0JQeCs2bTBPRUtyRmZ3dmVHUTFueXBjNFIvaC8zTFc2TnJDRmZvdWdwNkJTUGdEREtINFdFVEJqR1A0WS9sVjhEK3hCRUNjN0F3M3Y3cjVjd053SVEzQmFnSndDNCs1R0cyUnFtM1ZwQXNwYmlKTXlyb2V3dUVReXZNSkNmOUpFRHlXN1FTczUyZjQzUVNJbFR3d21ZZ2l4a0tIQytxTkJWbWl5RmRyc2tScDRxOFYrZktMN2FWaUlyYWd5R1I5UTNRTzFUTGlDN2o2MGIrU2RCUFZVUFFkMmRPbytzaE9wbnUvUXYwcmFTRlhPQnVxQVFDd2Q5amRBQ0QzTXcySFNBRThvUVgveFJpSU4vbGtnbTkwK3UxWVgzWUF3TTJNbHlodUxPUGFBRVQ4bHZVRlFMdkxZNThsa3lLYk1HVDRzN3d3Uzc4cStxdit3Q1YvRndCL2J4dFBBTlN6RTMxaTdpbUxJUVZBRTRCRk5jQVFyTEZ4S1dxZnIrbVUrQTlFOXFyZXgrSU9WVDBnU0Z3VXZvb0FsVjRrZWhWY3BxcCtwMThqQ1lhUlNvd0hBT0w5ajJuQ08zNGcvS3RWK0JVQXFJVWgxenk3TlFUZzd5MDY4N3JhV2dBb0NPQVBmY216SkF6blRPb1VBQ3hISkZjcTZPRllGRFJlK0JGczJEa0E4N2tzWEtlVDZGelVSVVN5b2I2WUxFa3UyeVRSM0V2Nm5lckdXUnhMRlFmd0FWS3dSenJtbDhJcGU3Zjkxd0FvOHNRbGZ6Y0FmMjl2OEdSUXljc1F2RUJwM3liM3NSWS9DV05BLy96d2UvWVQvbVA2VlBkbEtQOTN5ekNEM0h6d3c0TERaN2Y4S3dDQUpjTnF2cTF0aE5KUmJtV3VBbEQ4UHlYMnlRQllBNEMrQVB3dFgyd1ZWRnFrUmhxZGR6RWk4Q1BCaDRyZmN2ckRFYmhlMHdyNVZ3THd0NXdmSHdmQUR3TVB2ZnVyQWRoVnliOGFBQmdQT0FHZEQ0UXVISythYXJPZzRMbER5Rk5tZmhoNHVOcTNSMzlGTW9wclZpbC9Ed0QrM3JMeitXQlByVHVLQU1nSnRBU0J3ckdjZjdUNUp6L2k5d0xnQXZiLzFmTDNBUUMyRDhLRDZYTm5WcFlNZ0RoRDE4M0F1eXpqOVhOZjBFb3BmQi94dy9CdmNmSzQvLzBBK0h2TDAzUFdDQUM2SmNSaGdVdnhiWmI5K3Q4dFJLdFNrMzVXOVFFckFBRDcvOEpIL240QW9IN3kwQVhJbFhLWG82VzEwcG1lejdPb0FQN1B0ZmhaTlByUmFNa25QYTc4ajBQcEoxbFBBUDZXOGZGODFJcWkzQURraHQ1V1A4Sy9hNWxMZmcwWmdEdFArWHNEQU9lTG9sWW9KLytFUEQyYnl0VUJHOWUxdzMrVkIva0RZZ0U4ZmJKaDBYZnh2cXlYeS9jQndCRHZVUjhFdDF0KysvdG9BSUFqa09Dc3Avb0FXQk9qSkdHN3VUQy93QXFBNDhmL09BREZ0VGo0eTc4R0FLaWJMQkRseVpxR2FRV0FkVWlwR29WUjFSajdJbzVRc2hUUTJWN0dzdTlrWmVyUm1JbGVYUDRqcFEramlCRi9ENVBtZW5jQTREZEpXVU9vZFFBQVN1QndQVW10TDZzR3BobFNPTzNYV2lxNXNxZlBHbHNtVm1mWnNwL3B1WmlXMmFyR2VhdktiekQrU3UweENrWU50WU5BdmRaMUVDN0Y5WHk0L1gwdkFQN2Vpb1IxUDZ5b3FmUUdnTTY5UkxQdmNySG03aW9LU0h5YUpCV2hSdTlrUTRxazZGNmFBc0IxaUNjQXVoM3pCb0NxRHBMT1YvaDd6a2d0N0l0YThxOEpBT3dqbFFFbDRDeTZOSTVNbENuUWkyYVVsRzVidVp6VHB6RDE0VExrZDFjQklQMWJXY3RqMGptT2VnOHVlSnQxME5DcW93RnEzdjROQUFCS0lEMmprb3VUYlU5UUF3QTE2OTVRajIvdHBreC9JZzdTMHBHU1M3V2xvdDczQnFCUkl3Qno4WWluRmdDYi83cnlydzhBUU9DMFA1OE1PbDQ5RmRTSHFPZW04ZWxXVXV3RklkSkFScTQ1ekpQYk5hQ3NjNVFxQnpXWlJhUytrOW41SU4yOVhiLzhhbXZ1NFFuQU9iL1ZsMllEQU1CMklOM1RxLzBEZ0FhQTZ1WjhFQURYZmRsQS9zMEErSHNyMCtOVnZjcG5RNzhNVFJvbWNUY0d3R0ViNUhmVjRoRjNpbDVEb0xyOHoyRlNQQUNvRm45ZTNCcUpzaGtBYUQ5d1FNVk0xMDhBNFBRRGdHcjg4MXREUVRZRkFIbUR4K3RGRUMydHRyVU94YURxV3BXdENzREpZaFZzcGFGK1V6Z3FycjI1TTYvRHBiLzZoQXlNdjhRODBQbU84RkRlV1B6M0FJQzBBRFlFUHdCOElnRFg0eDNpdnc4QTZBdGtlNm9GVG1wVnJkNFMvMlEzQURVV2Z3bmJDRFlveTNmTFNRa2hlNzdHUjZNTFllVkhBTkRZOWo4R0FPUU9wdWZySmVjemo2OVM4TzJoQU9EMytmb0FXQTlzT1FERlF6VEEzZUsvSHdDSXdHVjNSRmNLZGdvN21XSXlCZ0Rrci9qVHdQZVhrLzVxYzNTM2VWamxmWmMxWTllVzF0dnM1ai9uNWUxdThkMFBBTFlFMmZHTU9tYjRBU0RHZFBYMlM1cG5iUUtnMlo3OTN3SGdlaTRlSVA0SEFRQVF1QlU1Wk9CaXlRR1FSRjhWeGIrb3h6N21wcm9LSnZLWTFQdEYzdUFkVEpzMnA0NXZldS9ubDhkSS8zRUFJQWJLZkhjNE1UVndFaVZVSHdEdWwzOFNBSTN2L0hjRzRKTG5ENVArUXdIQXRnQXJBdDB0cnA2Q0xzMUVxTnFpTmRtRFBWVFNna1NyZkRqZEFXeWVEM0krQWVIZkhpbXl4d0pBRkVHYVpEbnF0Smlmem84QXdIYkU4djhCQUY3TC9TRi9zUERmQlFBQ1FYazU3UFo3b0F6T1owZTAxSnk0NVFBQXR0WXl5dnBoYXQvUWNjY2phR09XcS9MaWhnQmN6OWZUcFFTeXY3MkhyTjRGQUVJQlZBWXdZL3lLNW1kV1czNHZBSGdYdmc4Q3dGNkE4UUVBZ0w4SmJQWGZTZlpvL1FlUDAvbmZsK3VQZndBQUFBQkpSVTVFcmtKZ2dnPT0iLCJzaXplcyI6IjUxMng1MTIiLCJ0eXBlIjoiaW1hZ2UvcG5nIn1dfQ=="},"2":{"i180":"data:image/png;base64,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","manifest":"data:application/manifest+json;base64,eyJuYW1lIjoiUGFkIFRyYWluaW5nIiwic2hvcnRfbmFtZSI6IlBhZCBUcmFpbmluZyIsImRpc3BsYXkiOiJzdGFuZGFsb25lIiwic3RhcnRfdXJsIjoiLiIsInRoZW1lX2NvbG9yIjoiI0ZDRkFGQSIsImJhY2tncm91bmRfY29sb3IiOiIjRkNGQUZBIiwiaWNvbnMiOlt7InNyYyI6ImRhdGE6aW1hZ2UvcG5nO2Jhc2U2NCxpVkJPUncwS0dnb0FBQUFOU1VoRVVnQUFBTUFBQUFEQUNBTUFBQUJsQXB3MUFBQUFrRkJNVkVYNit2cjI5dmZzNy9QbjdQSGQ1T3pYM3VmVzNlZlQzdWZUM09YUjIrVFEydVBQMmVMTzJPSE8xK0RNMitYTDJPSE4xK0RLMStISzErREsxOS9KMStETTF1REoxdURKMXQvSjF0Ni8zT2FvMk9ISzFkL0kxZC9JMWQ3STFkM0kxTi9IMU43SDFkM0gxTjNIMU56SDA5N0cwOXpGMHR5eTArUEN6OXErek5lNXlOT296ZWF3d015Z3VNZU9wclJxZ1pHSCt6Q3dBQUFyblVsRVFWUjQyc1c5Q1p1aVNOTTI2b0xpUWdtTlpXRzFvallDaFJiWS8vL2ZuVmh6UWF5WjU3dXVkMDdPdEtXb0VIZkdIcEdrby9ITE1ScU54cE5nc2RwZDh5emJIdzZIWFA0ZXRsbVd3b3QwZHpoa2NDek40TVdCeGc3R0FROXY4VlcyM2FWcGhnY1BHVHhKVTN4Rkg2UEhqRTRGcjlKMFIrL2w4SHdyWjRKUlhBK3JXVEJCUW40WXI4a2ZUMmZSb1RpZkQ4Y01LTndMZ0QwRFFKcXp3MzZQZitqRi9vQWZFZElPV1NhUEdUOERBRHNBcXEvczJPS1V3TkV0dnBrTG9seE84bkcrWE02N3hjOFlYcEEvbnN6ZXl2S1l2Uno1MHdFNUFoZmVIV0E2MzNIT00rUlBob2gzeUF6ekNZTmsrM3pPL0pqajRTMXdkMCtjUFIxV3dmaC9BZ0NUdnppY0Qra1d6Z0w4M3hJRmZObU1TYklqN2VFZytTSmlSUzcwQXlrRHlCM2tQb0JjdUlsUDRPbVdycmNuU2N3djI5bmtYd01ZalNhTDhyemJFY1VLWU9zQTJLWXYrWkl5MWgxSlBEeHVNeUxiVXAwYk12RkVlRTd2TFpYSW5EbVFrVmpDOCszN2Z2Y0N3alA5a3htUUw1S2NlVndYK2cvdWhQMkFaVWpraUVhTEliZFVXd1I2eUx5REtwVHU4dDJnSUQxSlQ3QXRqcVNxaDhQN2p4UytBRUJYSTVIeFVPVE90NXh2T2dCeWxoNkxpdDlSUVRqczNpL0o5SjhBak1hTEVsaW5acUF2bjVZVVMwYWFlcUR5N1k3c0pZazgvc3NOOFI2YTNFWFEwd0lIUUM0QXlEWm4rOU5zL0NPQTBTU3B3SXFCUGNNdk1SLzUzSHQzdXQrSmxsd0lqV21xMzk5Slk5L1RPSVlqOEJqak05SUYvZzYvVE9HREF1Y2R2MElQZUxwM1BBTjgrQjJlNFJXeTNHTVBIS0gzaS9YNEJ3Q2o2ZW1DTTU5NlhFL0pKcUpKaVJNaTdTMkpJaUFRRENNOHh2Z2lpcUtFUm9SakU2M3hBeEdQVGF4UGt3US9udkMzNlVuQ1IwSEFkL2h0UERtZFpwZUlaL1BVQU16aUlUMG1rNWNBUmtFSmxqY24wNkR5QVNZbnBmbWtpOUpZcldGczlGVVV3YXZWaWc3QzN5VTgzZUNyeldiRmIyeGdyUEVJd0dJczZ4V0JXdlBnRTBmMGpDNkVrQmhqNm12V0RnQmsyK05oK2dMQUtMaGs3QTZOdVlTNW9WTkZ5OFZzRnZ5SFl6WmJNREsweENSQjc2a3EyODVINE5LL0pUdUFZRmx5Z0o4d2JldkZMSmhPSi8veG1FNERCQkVoQnM5WVlBUTJmUVl3R2szUFd6WUJCR0JMY2dOU3VnVHErWVQvN2FCckJyTlZ6S2JBT0NFQ3NKMDhBNWc0SDhOd0pvbVRkUnd0aVBvcDhwVEhmSTcvOFBIL2VBUUJBd21XWUFZTWFhRHRNTG03RDhjV3FmMWZmM2d3QWZoNnZVVHlrZnA1R0M0V2l6QUV5c01RL3l6bS9wajFYczZHRU01bEF1eGt6TTN4MXlDVUMyb1JBUURZb29VSEFCN20rZGFHZ3huSnozbzJKVWxrc2hjNHd2a2l4RWNkaXo0UVF6OWlzdFRPWno0SG1Yb0ZPcGNENW1NT2h4RkRzRkFBcVFESTBtdmdjUUFNNkRzbUo4WjRnaDFiTVh3bWllbEhKb1FMNXNHL0dNNWNoL09aRXMzc3NoQWNrWndiK3Awdkl4bXpOU0hZc1hjZ3ExU29JdVAwanlhSDdYNS9FcmVCNWllS0ZpNzVvUUd3WUFDTGY4UXc4M0dvN3BqWjltWjY3bEkvNndzaU1rR1VtUU1VelBEMjBkZ1JvV1VGcEJmaTlsSTAvak9rWHdYRUFpQXBJaHpoayt6YjU4aWltZnZHN0ZsY1hncS9BMVdGRVNBRVN3V1FvdC9lWmRzaU1BQkcwL0tRYXdnRlhrem94Ky9pZEJQOU12RkxvbDVrQ1VrVml1ZjJzbzZxVytHMjh6bTNNR2FEeWo3M0VNZ0VCS1FJQmdORys3dlRSQUNBQllJc1JPZy9nNElreVZ6RVI4aGxFMFI4V0JwWkVuNlFMcE5WbWptTU1HcGlKWDgrYzJkMWJqSDRySEFJTnlhQ0VTd2xPZ1FSd1pMQjlqSlRKUWl1Qnc1ZjZiODBTa0QrQTVsTlZsdVpjd1FBZzBqSHgrVXlOQXh3UjZnTVdJU0dKRSs2RFFJamlHSzRlbWV4V09ZUVg2d2s4aVVFWURSelpjSGJ3VWxQMG5nRDVqL0FieS9DaFpIOXBVNzYwZ3g4QmVhSlRHd29ZMkh4OUdUY24zeVZzZENTSFhydzdka1dJVjBqQkFSdkgycE55UkFwQzZibDF1U2hFTDlGU0wvYVN5R2VoUjhlbUhJTGdERzRsd3lmYktpeE1lNGNPN2FZaitsY3pkMnppZW5tQ1FJRVlrVFZxZTJaQmF0SzVQOEltZ0grSzBENWNVOGhwRnJTTVdZMkFQUWlIb0FuSDJ6bmVjWnFQdThaWXNjK3k0VWQwNmNJUWk5NWpTdGl3ZVM2ejlVQ1FZcnlhd2IwTHh6Nmx3TEF5czVxMVFPd1ZDMWh1UTJORjVYUWVPWklpWWlPb1RUa1E0YmhTcjAxRkFZQTZFSGtWNnAyNkF1Q21nSHM5eENIcHNBQUNHTXQrS1Uva0hBR0FNL3dYWmRGeGk2NTVBc0VGOEJDQUN5c2xDenNsRnV5bGVQbTlTeVluV3h4QnlLMkM3amo4ZW9pMHcrK0lJdGpZSUR6ZFRZMks4NjBlc05YWjBjZjVvYitLUWVER3N5R1p0WlpySTJJaTRDS2tpMmN4K1hDbkIvK3pvSjFtVk11L282RzlMMEFHWnJreG9mbEVLZ0NBMEpEa2N3Ni9BVUFuQ0FLNlM3NWZBVjZZSDB6RE5EWVhoSE1qVndhNDd3d2RLK3Npc204TGZtb1FNUFg4MkJXVnJuTmJvNFFWZ2UxVzE4NkFKZVdEbVlpbG9WR1U5L1ZlclZjOVFBb0N0WWNCUUNFaytvWkJHNU1FdmJrQkMreGNNeERYM0NaUjdNZ3FpbGVrMUxGYVRxYWwwNHBKaytDWUc3bmxHYkFpQXdoUVBvcGZWK3Z6QXd0ekp6UnhNNE4vV29PZzZtcXNzNjVQQ3ljQzYxVVVPSG9TditULzFkNm1YQTJieXFud2dNQjBlcmcwRjh1UUlNWGFpaHhRdFlPK1Rya09WK1FNRm94RWc2UUJvVGhoZ1p5Z2VuM2JjTkNvSnU1ZDZmS1N1elNjSHlGQ0s1TnpuVmhUQnhQaXhIWElDUVkzUWZCd2t3SEdSdzZpOHFPRDBBdUlkTWtqSEFBRVBtZkRFRXNVZWhKalpHUXBkcTJkVzhZcFJOcTRMOVoxQlFPZ0dUa0ZQT3lJZ0VOV01qSFpUS2MwMkpKWjgzLzZPbHFIYTFFSTFRbjJCc0FnQm5RLzZrREVTdzRMV0xKc1U2UnAyYkZVK1VSSHlYUm1pWFdzMzNob3FsenF1SlRMK1F3a2l3U0daQlZTOUFBUGFXZWp3M1FPbG9MNFpIOHdkUERVWmtlZ1VBbW5aVEFvUjhSZ0dqTzV0WTlFZjBpTGl0VEdKTzVXY3UvaFA3U2xkZG1PcGRoQXpLRTFTTDhmMXVPTW9jRjlTeFkwcWZXaHA5SUljKzYwcTBvaUFOY2xsc3ZqVjBTUHpEMzZBY0VZYkJpRnBBZFlnM3dERVJrdVl5a3UxZno1U2s4M1lFRnBnSXhzcVg0dkxnR3dkcXdqSVU5c21lVmtUaW5qZGdlcmEwSWhaeU5MY0xQeng2QzVkcjFzU3hHeHNpc1NCeFh3bVF0c3NyMUhLdUJBS0k3YUlFSGdCQ0FDTlhYWUViOFhGdDVqTXc1STUwYy9IOXQ1bVc5OGxXQWtzMVZqd0V3d25EbkJoeHFUMFhiak1vNStoWkY2NmluMDJ6NTdtQkpqU2tkSFN3SG1sTXd0NGFHemhZTkRaMGZsN0hpYlVnTDVvdW96d0JFc0ZzYi84VU9qV0pBNDI1WFZpV3N1cTFGZUozSldxL3V0N3JJZkFDc0FzMHVXQm9iS1dyRnhFcmxQSW5rajVXaWZteEU1SzAyeUlBdkhBNkErTENTd05zRVFCTHZHazltcitzcVFHU05OM3dtV3QvdkRJQjZoS09EYlZEZElnQmd2dUNjQmlqZW1mby9veEFMb1JFR1d4SU5XOTRNL1FqaFN5MVJ2VjVxekc5Q1ozMHVVRVNkcmJWTDFIYXZsS3drdW9NTVVVWURBV25Pam96aXVlSzJucTJzYlBTRUp0bWxpWFF4RkFCcmwxcEJEYkVYeTNYbEFqQ00yRFR4eWttM1FqY1YxUU9JSU9wTExqdWZ0ZnpiN1JRQXpidHlBT2l2Ym0relZhTEs0eEMvazY1SmtrU1dlQVdLdHRTWTh5VWhTSnNYQUlwbzFhZVlvK3VaQ2JjQlB0c0t0UnBXMytUUDd1UGUzaXJwbSthWkE2Qys3WUFEWW51RWU0bjBqbmE3blU2K0J5RVJVeXJPZzZLaHhiN3MwMDhJTmsyVE9Demc1S2FmZTRaZ2x5TGJzVm83Sms4QWJNOEFvQzQwQkJwcGp6T3Y2dnRodG82ZTdMMmNTd0dJQkNXcTNwRzFXaElmck9wZnp3QVF3Ym5aUlV1RGdLYmN5VDJuRkxJQ0MxZ1BJNWt1UVJDaDhOUElrQU9OMGR3UnQ2N1JEVGNBSVBKY1lLTGM5QUJFMnAxVEZSTWQwTmdzUWduNkdnRHdlUzlqQWVDVzBDVnpnOXh0TWdFcFdxcjVUcHkrSVY1SEFXUXRBRGhKSFFVNGtOR3lCSkNnWndBYWt6eXh3Rm9rVm1VRW9Bbmc2bkI3Q2FCSjBSQ1ptVGZrVStvVFFONHdnV2grUlhvVk9SWkRaWmtCN0JGQW9iMWtBa0IrUUFCb3RKa1k4NU5FdUFxSW53cVFuU05MQ1ROQlU3OVZWTnczei9RVGdQWjIzS3djQUVROVpzMGhaUTJRUHdSVFBNWGFsMkYvUnJORDI1SXZKc29sbEVBaldoa0FrUXVBcUNVZGhsZEsvRzduS0FOaFhsb0E5ZjN6SllDY0xLa3orVUs5R2NFc0huYi9SalFPKzdZVEFCd0x5Zm9XRWFGRVF3WGxuRXozTGtrY2c2cEd5YmlhbFZSWXdJaEV0L3NMQ2RyYzcwVk1ITEQwQnh0L2hPQXRVclkvZnR4aXh1R0FBSzVTelVVT0hJa0ZDR0EzZS80UzBpcjBSalR6OUpLR0VWQmdBRVUyYU1kWDRPa0hyU2dFRTdlMlRGYk1BQ0UvM0d6RVRXdlVXdDl4WllyVnVGMlMrQmlZQTNVaHF6VkcrWjROYXRFMHZobjEzWmlLa3ZpRTJET3BheTRiY1B0dmZiKzlBdEMwZWJSRUFLSzZ6ekhyNStmdFh1WFV3MGlpbUdhclIvOTZtd01BY0FRcVFvVUJjR3N0Z0xWeEFaN3hvV24zQWJDaFhsRXFNQTluaXpCcFA4SkJOL0FaZkxYWDNUSTAwejlBUGxpcXRpNm9CNE1ySzF3MnErZk1lZ0JFaVkvbjJnTWc0VkFTK2RhVEFhUXhTVkFVQ3dBd1FsUlVuT0Vhdy9GMCtvSURRUFY0TXRYNUR3ZnAvMnpicHNiUzIwNG16T0hBbXR4YWZuUUFRQ2loU0k2cUE0bUp2aDFqak9TNjNnQVZBZGdncXJ6bStRZlN1UEUyVVFEZjN3NkNrTjhjRS8zRDB3K2o2MjZZY0NYSUFCYlpLSEdOVUpTZkNZQXVMUUlBa2hVN1Nxd01pSzAzMmRsUVZQVUJsMUl3QkdSQXVKZ0QvZU1KdC8yL0ZNQzNCVEFlNlpvd29QL3oxWGdBZFZXMkl3Q3N6Q2FrNXRsbEFKV204cU5DV01DT2JHM0RHemNRMHFERTVRRnJBazBSdVRHUS8rbEUxb1NNUDcvN1N2QzlNZXRLd1BTL3BMOTlkQkNxNWR1ZEFKRFFrWE1yZWtVQU5La2tEbkJNVWRTdUZSTDY0emp4Z2xEWEhzRmdGcEFmV0MzRGVXU3F1WlBQNzI4Nyt3d2dHT3RDbE5mVER3d0FBR0FrODlRMW9US2ZURWllK1FCTVVsOC9tZEdFQU95SWp6dmp6NHdiSUFBN0JyREdSS0FLVEVuNnEzUHBKelFCc1FmUkJWOHY2Yi8vUlFDZ29pbTVuMFJyQ0VZZW92VjdKcUdFSkRSYVZsRUFiaUlKLzIzWkRxU3NWVHVkKzExTWxnNzduaEV0dDhMeTF5ME9RdWxyZE4xM2IzU2Zac1ZPMDcxRTBDa0FOVVFjYlRrQ3ZVNC9FSUNhVVZKaUxvMDJEWmpSbFJlT21reEd4SkZYc3BGMUlGT2R4cnpZalhtOHZiY2Y3STluSDQ5bkFKMzJiQlpkSjRiMXE1ZjNmMzQ5U0lUSURxVTBhVzVBQ3ZNWko1QVB0QzJiVVJJZXNrSVVDNEVqeThOVjVHYnlIZ0I2aG92UVVndEFWK3NoZ3FRR0JmejE4ZXZYcjQrbUd3RHd0K1VhZFFBZiswMTBmejBCYUlFQkJLREtYUVRXbkNDQVREbVFjeWpoQWZBRDJZVHBwaldVT3lhYW1aQXlBR0VJcmZ5TGtxYmw2YnUxajcrUDd5Y0FqMGRiMXMyNUlURWZjSE9rd2dvQTY3YzhPVEd0ZFhRR2g5TXVnTndBT0lWclUveEJ4RzhZR0NLWk1Za05ycDlGZFVEaUNVS1NaZ0lnaWFNVUFQejkreGVFQUI4SEFPQmhlV3gvRDRVYXFBRUVnR08xRklsUENVQmsxa25FY1o2L0FGQWpCNXpLcEZqN21CZWhLeGNTNFFQUHZqQUFBYVI1MHhKNUJPSkpncjYvSC9JbTBUOEk0T3VCMzJ3RmdKNmI1Q2JtVlpoNHpBMGxEQUF4by90dzdlZnlRQ2xiVWlGV1Fta0poeEs2QWw4bVRpL052Uk1paCtqL05tOE9NZUNMQldnSWdCMHByWVRMRC8xZ2p1MHBBR2d4SStQZ3pOb2dDNEJqT00zRzR1UXRjZWlIc3pmM1ZvaDhCWUJGck91ZUdZQUZ2Ti84WmtzNlVIa0FIQTZrQmtDbUthVlU1dEFQekttZllDTUlTaTFNL2tKd01JTGp0Y1J2dXBpWEdaSFhOMEx3R0ZKaE5xVDRKdEUvQU9EcjkwUHBSd0RjRHNabDJDeEZkckdRd3dFeW83S2NQejlKTUNmZEFKNWwrQTZablIzZTNtTXlZVTNrT2Q1TCtQUnBEa2wxMnlLVkx3QVFnbzdvSDBMUS9mVUJaSzZTeFJaQnZuZEZTRHl4VmlYQ3RZMkVFbU53OEVFQlNFQWlmUzFxVE5EcVdqQnYxK1ltQ0Y0QUFBUktQMEh3VUlnQStRQmlDeUJTRGhRRW9IRUJTSDhKbGRncDdmSzh2bk84UURLVWJyVUdRYUdQZElzQXlrWlpnQWhRaklicC8rMlBMNWNQUkQ4eEFEMUpVL1k1RUJrQWwxVHlBWjU0eDR3Mjk5eHdnT2VWdUJiVFN2c2RyNUdYN3Q1cXljVVJMRzlpZzVFUndDbHU5L3UvQnFDQ2hBYm85ME1GaUFIVVoxbytHYWV4NDhnWXozRkxBR1NGaHdESW1BTUtnQkZZQlkzSkg2UWEyMUlDUE1lNGpjdXhpQUFuQ0d0THBBZkRBTDRHQVZCQThkazVEQ0FBSlFJZ29oMVBUQUN5dEErQVYreWVYQURSbXV3TWVrTCtQbllIalBRdnFUdzQ1WHZsWmxRU1I3eDR3d0pKMFFzV3ZHSkFHSVN1QUtFS2tBZ1pHVW9kV1FCZHl4UUFXVS9OQnpJU29ia0o1U2hHWmc1aUVBalA4REZLcEFDeG1FMUdjc3NURlpTWHE0anVWeUFwZ3Bqb20zTUFGQTk1OWpVQUFOVGdreGJnVGgrcXdjeUFwcnFjUDdheDZ5ZU5OdGhvMU5HQkxQT3NVTFMyOTJzWWV4b25hY3dWQ0JTZzZaaGorM0dBYWtEV0NEOUVxZ1FzQUhvL1ArVVd3dkUwL0VRRVF3QStKN3h5ZGRRYStnbEFuWjgvUEVkc3pWR2VEUVBBMmloeEFCVVMvcTFqQndOUHhEWk91QWEwbUlkMm9mK0NHa05rVDlGcVplRFB1a2ZMTTZzM2xZNG13UkFEZnY4T1I1TXhwNXF0YUxCdzROUUxKVmlRMEs3bUJ3WlFERmdoaUVhdCt0cXZjUnpuNk1CaUhkdjFaQkV2aU9LbENTQm5IeEFWUHQ3d1RsZzdVRjAraHdEb2pTSFR5YzNTanh3NDh4SjZGd1c3QlhSa3JmWEV2aFY2QnFCZjMrMDB3NlorUm5VTGxmN3dkbkRXSmEyQWNjZG1QZmJJRnd5VEFRaUJ5VE52Um9CdW9zU3BoRCtlRlhVOGNlWUFFQTZVb1phRDRQTnZMRDVxUmhNT1Nzak54VTM3Uzd0MHQ3YU9WOXJjb0pVbzYra3orVGhHbzJjRTRUU3dBSVI4WkVCNUpnQjhMNCtqQm1oR2MrR0FVNVVRQUswQTRENmgzaU5HMVMyNklRaHZqMEpQOEpiZnV1N001ZkNQcm1zTzdKaGxuY1FNNW5wNGpKOFFkRi9LeUNWbFlrSitYZU9Od0hvellDK3MzaGZFQWFwc0hmWk9nNE5FaVB2V203WGNQcFJFYjJTSGRwUUw0QjF2Q09EUTNMckgvZU55TEJ2SXdycGJtV3hXUXYvc0Ivb0hFTUE4c0R1YzNidHlIc3pDMWE4U3FDOC9mZ25acWNNQnRVSlVtV3NFZ05VQjVBQURrRmdvbFRBejNyRkQzQ1ZxbDNPd2xKaTkzaWtGNis1MVRLYVY2WitNZnJpM2FqenEwZjk0TEdmTHpXYlZQTHFOMUpRQVVMaU0wbml6c1dta05lbHhmTkZnemkxc1VUNXdhNitoV2V1QmJ0alRIdEJpQ3ZDQXJRVUIwQVFSRXRSc0xZc0ladUYwOU9QZFlhT0pTejltT0krMnZkM0JEYmZZNWRqd0trZTgvNHFjaTVzeHFVcG1SK0VBVDd6anlCd0E1ZzVCT1lQZTR4alJBdjY4dmp2cEx3S0kxdG8rSGYvRC9XMUdpRFMva1hub3dOTjlidXdpUWJxQlpMbGNiemE5dkRLVy9rQXBJWVFyUW1LRnRCTEo3cGNMRzN3ZjV4dkh0SGx6TThramxUTHphTVV0K05YRUF6Q2R2UjJ1TSs4bXdQSFlUditqMHp3WmsxQzNRRVRyQkFGQ3VGZzlBK0R5ZW5uTzNGZ0lHL1VFd0M2TlMwUnlFbE1YWUZCWWY5RGtVZXBvZWNSS3NISVpNQTNlYnBRRXQyL0J0TStDYjByT09GSG1PT2picm10eElNeVdTeFBaSzRBalpjMjBZUUdubE93UkZJQ2s4ekRmcWtDcXZpcU9rdjEyVEQvYTVDem1GQ0Z4R1JEY2pKNTBnY3NXSnA4VGY1TW5tMXB3RDBKQWpYdFhrUFk1QXpERlhWbnRoQUJPaTdWRTBReUFxM0tPTDVUaVFDWEpvNVFRcWp5V0ROTVZvTGUvZHJSVGU0L24rUHZ4c0lXalRzYTMxOHl4RUtZQnJXTndPUERPbmppWExSU01JN01jaUYwQThVQmlqWitsNUpHajM2YjRpTkY3TExienNRUTJLRUFQQjhEZnQ2a0Y4UFhvM09KMXA2OEdpbzNZK1E1aXNTaXBwOFFPZ0N5em9ZVFVVOEQ0WXdjc2RZWVRVQ0VBVEI3dkhEclcxUWZmM2R3RTQ2bmV0enR0LzNyRHNtQVNkaTl5L3UrQmFpa0U1V0c4Y1MxaWZwSStzVlBZVWdEWDBMU3dPWFIxQWFUcUViQUlCaXlRQVhGTG1ZSFgyY1RwblVJejBXQ2Yvcjg3Q3lCNENXQVF3U2JjMnZRV0xuOHFiRWFtNjBZVlFMVXd2VTF6NDErcTFRMzZQNk1iM1F0a2dRencvSmVNM0diUldnQ1RXUTlBT3haazRLVysvd1VBRjBTZEppYVlWZ0JONmZhSmNlSHhGVXhMdFFTTG8wM20xRUhBOU1jY1hySEdWSFZONUZmRmFVOWxtMjNUbWk3U2RMTHNBWGc0MHZXYUEzME0zUFc0blVTSTZiR29URGp0MVlVd0ZnSU83SFpibHdOWjJoOW1tUyt3b2E2cXF1REFIV3VqSFFHZzIwNmVPTkNOOVRidHlVRC82V2NBOS9yZEVXUUJvRXRmbndIc3Q1WURwaktBeit4ekJpQ0Q2WSt6NnRiTkp0Wmo5UURjTEFlQ0h6bndqS0RGTlg2eVB4RUF5QXRkN0pIS2NodGV2SFVDQURVQW9Db28xa1oxY3hHelJjZTdCVVFiWmV4NVp5UjFrUFd0dXhvQTAxSEh6UTQxcGpOVkQ1Q3V4ODhJdnZ0ZGcrNHVQVE9Tb3FJSFFHL2l1eUFIUXF5azQvSXNMZVJsOWtid3c0NllJTHQycEtsZnVreE96ZjNSV2lzMERwaCtiUXFJQk9GRDgrOEJZSXUyNDlhM3pwM21BN3I0ZUdRMlNxa1FBS2FPaVJHaExITUJIUGhXeS9ncHhsVUFYYWMwWXN6VENnQkNvRlVZZkxQN1h3QjhZK0xSM3BycUNVQnVBZkRUaW5RQWwwQlFIekx4QU5oTmQweXhWY00rUWZRSEd6UUJDd21wOGFpekNHWWpTMy93K0NjQWJvZjhRUzBwN04xbnRrZm1WS2RGQjZSRFV5L1EvWnIyVjJvMjFCRXQ1dHZWWlNPUmxkd2l4OUZIaHQyQngyMmlJZ1IvUjlXRHRlQXhaZnJad043Ly9pT0FieVcvMDRnZFdGREkvT1VjekYxY0FMSml5d0N3dDYrYlhRN1loK2srSzVTQkxlbitUWXdXRFlESDFBRUF5WEdENWFyWmFLeDdYZURqUHpPQUFVaGprd0dnMWdxQWdxc1NsMzZQckFKSFZpOFRXU0hucXJBeFJVSS8xYllnK2FJRmszTmFxTWpOZ2JiNzIweU11NXBPZEhNeVUvdkJKOWVuRmhwWW1oOTdnZ0tnWWtzZUY2VUE0TTNXUm5wN2JnRUFyZ3ZxL3U1b2E2elUyV3ZLQkhTMDN3UXVUUWw1YlJPV1JoZkNBVXJUQXV0d3hYUDVPNDdNdVZGc0lkQjVKcDlEWFdXbEh3RlFIWVZvMkJlU0QrdzVvZEg5eHdxSUwwR0plY3NBbzdpNTJZNkNwU2dtQUVTL2xCbUNNS1JvTjZlYUtFVCtUdWovdkdGSzBLbDFGVGFFVXR6OTlEcHBOZ0xob3ZWZDZ5ZzJGaXBNVGl6RU1vQllaY1hkNDZzWFZFZFloRlA2SnRQMWNybUpqUkw4dlJsVE9yVGxTeU0wU1I3V2ZVc1JZd1R1R1JPRGg1ZEZ5S2VrYlZZY1BRQ0ZYU3VoSEdnWlFHcmNyd3NnTXdBMnErVjZNYVhWNXZCdnVvcXd3NVRtWmNPMWlvT2pzTDBSdkQxa1RqdkJjSkVjYmpydS9qNE5SY2xOQXdyZnNNbDM0V0N1MExYVHVaaFI1TUR5T1hMck13RmxhSlB1YkhXNnZIQXNWMmlqKyszVmpqdkJUUnJkSFJXMUFFTm4zbm9Db0lLbVhZK0dLa0VJb0NZQUdvNUtQc0FMWCt1bEY0Qm1MNldvdm0rQ0dkK29HcmQxUmdETzB1aisrN2NKaHVtL0N2M2Z0akpucG1IYVBSTXZ6RElBcUNXUVNqUmFGWm1mMEdCT2pBQThnck1lQmluWVErUjhBK0tYbStVeWJMdGJoZnR3T1FEK3RzR1ErSFJLdisxMVBPNTZyM1FJd3VXUnJ1UjNtbm1ERXBSbkNHZXVsZWlBQ1NVa3ZLZUU1dDNmR05IYjdFemJoaWtHbnQzNTE2OWZtMS9sL2ZHQVdCRkQ3RXZOSFVxaTR6N3pNUVR6dTNxbHp1blZQQjV4dU5uZ2tzZGJuM2lIZkduODFWVlpscm1JRUpaVldJbUJ3UE1aQVRTWVVzYTdBKzd4NW01MDV5bUMxa1loem9HVFlEL3ZiMGRMYlRQYm9XUksyemR6UzNxd2FGcXpVc1VGQURyZmZaUWZ2ejQrNnNmZklmSXQvVlIycCt5RFJhZ3BuVDR4QTZnWndNNngrbG5xTWtGRmlBQThOTnFuWVBlaUFDd0NmQWVOMzlWV2dzVnlmbnZWM1VlSEZScFBhODNReWczM3pRREE1V2hFU0JmTnVTdTJqQi9RM1ZsMUMwUzljWkhmemYzcU5BSTRmMUF3d3ZXdWgyL01YZDMwNXAvSzY1N2lkdDB3K1ZTOHFldXlPSjd6N01vaVZFbVRUQUVVRlh2aW5Xd3UrS3pFeGozVHNoUm5jUlpFNjVjcyt6anJTb01YQ0o3bW4vc0QzcnM5NGczNTFMYXBRRXd1K2Z1MWN2eUFBZ0Rod2xpbVhpVE9QbzhlQUdldnlFTENub2NUNis2emo0OUNDM1pERUhTQ3YvMEdoK2k4cjdNZTlVWitVQU53MWsxVlFnQmtKcWNIQU80MlNtWWJTRDhrNVkvYTZyU3VrZ1JmWGhTMUZrM2QwcjlJV3RlZmYyR0JGTGxmRU0velgrTW8yQStjTGthRUhCMG9CTUR1dVlxUzl2ZEF6U3U3TUVnaVJmS0srN0tFZHl3UHpPQzZTbi82TFEvd05GL3YzVFB0Y0dvalAxVWx5OVFobkJZQW1idHEwUUdRZWI0NHQ2U25OdmNSTW5XRkc1MGFBT0JaOUsxSEQ4UGdjZyt0VHYvKy9kazhFYS9GUzJRQTBrOVhVVDlRbVZDaWNIUmdtYjZiekNVMXUrWEs1b3RXQ2VyR1ZLZHBkUTlQVHM0MXh4dHFjdHQxZlM0OGhqcjEzNzkxRmRkWGVHOEhxV2Y2NFFvK2dGbzV3TnBjME1MWGVtbGNzQzNDMGM1L3Job1hTcWJSTUJZaHFmc0tnbFlOaWtIUS9mNXBmSDJHclVjNkU4L2x5MHB0emdBSDhLMUNWdTVTTUpmcVhtM3BpNTJCY1o2cE9tMHNYRldZc2syV1g1cytCRVl4ekFKbjdWRDRwM1dvTi9RTEFHUUJVVlBWRXN6SmZXU0tUUUJrenA2QXFkMWY5eGxBMCtoVjBNUGtabDNTci9mamxib0hJbUlXd3o4aCtBeFlaWHZVMTFLQ1ZSWlV0V09GV0FjSUErc0FXTkgzMUkzbUJoakFkZDNhdVlLc3pJQmtQMTZGc3dpdXh5Sm1qS0lnNkg1Ly9zU0N6dzJiL0Z2VEkxOG5tVWhXQUxucUFPbHdYbHhyQVNCYnJLck56SHNiTkZOTEZxd3VRZERwNFdSNXRWd0d0QTV0amZtZEtJazE3ZDBqeHNWWlB3QUlxM3ZUdU5SWGxhSC9JUFIvVkxVSjVqTFhqQ0tBaXFvU3FXTTA3ZTVKQm9lWW0rcGExenBCeklETmFqR2wyNWhHNDJWcHRNU09kODNmWHdFQUJEY2xYVmdMczRNQ2FyYW96endSY3N2cklCV2l4THR0NXNSeHZaMmhkUnNUb1A5Q1RZNjZ2TEFHb3dRRlVzSWRUeTlWSlYwb1l4Y2I2Y0dPSnovSVVDMWVsMGNKODNBcEpmZlMyTGl1bmhkLzYvTDdhc0gzTm9qd3ArNWUzYzd1MWdVMUIzQjJTaHlGN2srYUJHYjF6Nm8rbDBiUldTdERrK2Ivd0lMTi9TWnlXZXFRRXB6dVlQMVIxbTZIaGdId0hkMGlRaWFLVTBlY2V4dDlpOHJ3d0F1Y3oyZXV1cWVGelhDWHpibGlXNlVZN29vdW1HNSs4QVhOWFF5blkza1VRS1lBMnQ3YTZUdzdVRFF2QU53QWprWG9JTUpFUjg0RnQyZis1UG1GQUh4OFlMS1pwdFU5REhoM3BCa1l4UEphbGNaVUFZcTJOUEMrdXRkQzlINDNsditjUHdQSVhRQTU3cEt0YXlWbzNhakppVzFkRjk3OGN6NjcrOUtmU3pGRW1NcWR6MGZOOXovcTlxWTdGc1JkQytsVGlVd2doUVFPZEozWlM2Sjd2R2JCSjJXL0pZU2VGd2NBWjRjazFSOWxhVzlCa1FWUFJHWWhIT0JmUUVpZHZlcEIydmFJZ2VpSG5LaXdlM0xsWEtvaHRsVk4yMzFzTnBEcWI4N3RBNnV4YUtzSUE5clU3bEh5dmVmaHIwZjMvUm9CeXBDR2JqM3pZYXhRNitZRE5xWEU4dm91Y3dHb0Zjb3ltR25aai9Gc05wT1JTMlFmdE04OHJqZDZkTCtPeCtQNTJGTEtYMS9PbHd2N1BNb2Z1cWI4aGJkcC9lU1N2ejcvdERmeTdaNENpQkdpRng0QXo0d0NCMGlFYkJMZ2JxZXZDR1JyVzNYZ0NPQURaS21nMHVoZlRBL2FqdFp4M1dxeUlSdzR5ZW8wVUFXKzFla2xnczlQbEErc3UzR0U1c2N5RkVwVUJLQ1gwSENlcUFDcy9UU2JEem5ldkRCZDF0eElGaTM4dFNrNnJ1TUNaMW1nbHRjY2ZIZCtndllhUWN0YWtLc1E5VU9ab3BJY2hGUE1FYW15QWtBUmNuL25RRGtnZHRPMGgvVXZ6SHh4MUFsd2lPUk11Ynhjemc2QWY0ZmdpOGtyQ3h0Qis3ODFjYTE1alk5UWdwc0NHQUNRa1IxNlAxS1IyejNRbEFHS0pVY0F1WmlvQ3dOd0ZxTGhiUmpuTTdLZ0IwQXl0RmUybE8va2t3ZzZMNTZDU1FYd3gxU25aYzJjaE5NK0FIY1h1dHhGSUZzTW4wR3J6MVFZcTV4TVgxSjk4aEtsNkVEcjlJd0U1akFIdXU3dUc2SWVBRCtjenUzQ1Z3THdNZndUT2YyaENtRUFGQUtnTS9SVFRBRDBsOWZhcVJkNWlmNWprQWx5TTJWZHVVTGtWS1pxQVhDNjhOMnNxSVFISnlNYitCMld2TWVDZ1ZGVVpkTm9MbXg2S2dqZ3JBQ0dTaFZEVE9BYlN1SEwxMmRQZ0FiR2hOTlVaY25NVm9VbXBmUTcyODdQcXBod2dqencyZkJBMTY0NGFaamNoMUdpRWwrcjJsWXhwSDdsVkZ1ZUdQQlE5c205ZXJsdXp5bkp1Z0tRS29zRndBbU4xMWIxNTl5S2xBK0FiWkltK3JhZURITHNBUENUWkljSlBiZE1LeUZ2Q3NCTnk2VlhmWFVBY0hrZGYzN0tUZXJoZ0dueU9mUHZBVUFNUjZQVXA2THdTeFVtMlMrd2MxSTcyQVlodVBULzVhV2NXT280NWIwZll5R3FqQklMQi9DM21uaXRod0Znc3NyTUYzMlRGUnpQRjZCZkhBTkVkMmkwU3duYU5IMVIraytWcldIMGN1U0hVNG52VExXYVRSanlyN3djajdhMGxzcUNCNjNNU1YxRnRtbHpBZkRzVzlKOUdNUUJ0STlteVZPcEFKd01oakpDdHJlY0Z3ZzBEMEhuRlZDdER6RTJyRHdmMVl2Wm1uTmhPY0E1c2U0UkJuSmFyK3dQY1BYbjNkVm1jdk0wOFZlUWNRZ1lpa0xDVGljbHg0emtnbzZnVk9iYzNDeS96NFIrWjE2RVJLSVpiZlE2QUNvRlVGQzhUUUFxVldKZmdXMUNtWE9CaVNjZTRvZ1NVbUpRMVpKS3I1cUNTVGtFN2JnQjRNblh2WWZnMFd1Q2FGT1BFWnpQdVdORXMvVHFPcks4R0VtOWkwVm81VlNEYkFwajAwbVZHa2pMQ2dnMEthVXNGWUJ3QVlsVkFKTFcxazRsek1Id0RNSHR6QThBMEZDaXM5Rm9ZWmNlTTREbkg4QlN6OHVkTk1vaW1iSUwwMXhWWnYyZkFxZ0ZBSHlTTW44cUw5UXZFSFJQM1QycUdOOEV3QitPZURGdkhRZ2xPSnd1TkpocjFyMEF3cTZ4TFBJTHVPNUxrWmNpRWlVbWpBS0EwbngyQnVXMXBHSU94VEtrM2RleU5GTFUzSWJrcU92VEx6ZUVLZ2ZRWGlNQW91Z0llY3NBQUN5MU5XMFRQLzJJbTBsZUNFTXBZb0V0Mnl2TXJUZi94aWl4NURCUENKUWk2SEdocndyT3lnSUdnT2MrWGNyejBmeUtIUHhwR3J0YUJkNGZhWDZDQUc2eEJrSDluMnpMVWVRTmdFb2xab0IrcmJZSWxnSlJRa1JhY1hvOG9BbHQ5OVNjMUw0a24veFMyQ0FHQVhBNFhVaGpZNlFCUGdLNHgwTS9YTWN5QnNRemdGcFBUTk5yYTBSeUtDZkNMNURNQ0lDYU9WVndldXlVaW9ZUk9KMTVObVRna0hNM0ttZ2FXZ1NvT2Ntb1VBbkJwUTZIZkNpU0xncDNxZTcxZW5YRmhiNmMreHpJVCtUcmxFa29RNnpRdGZFVnQ1NWY2UHFkZVVrSkx1WEZpMk8yb0tzS2dDNDdNcFlkQWRUN3dWVEFJckNHMUQ3VHd5cE9OQ05vV29Gb05rRmxKVGExQjZGZnYvWTc4N1U5b1JQZG93b2dnRW91T2pLSkxxN1Z1TGs5UGFQQnVlbml5QUR4T0o4dktDVEZ4YUpRaFNDalRJcFNsbXhYUzNGcTVjVjRpdWJaTjN1OWJmSGxsV251NlFBSnd0WTYrUUY0cHg2WnlhWEZKbm4xQkNBZlVsSmphT2dodHdLbDNCRXdUQU56Zzc5MXBRTzFGMTNjM1VSQ1k5a0dQdVd4Z0FqRDJ5QnBKUzluNmVmVGFDK0pEL1ZadS9xY2U5ME5vbCtjbHFPcVVqc21xazVTcktZNnN2c1pjbUpVWjJiRXhabS9Vam1DZE9zM0VTejlkV1hGMVdaa01NMFBCWUNtSlJxOVhYT1RrSUNCUGRmOVdFZ0FYQXBiV2ZFQXNLVkR5K01BdUNnQTdsQ2dXYklBNnJwNmxpTy93V29CVU9ab0lZQUVQVm9uRkpxTjV2Z2JJZ0lBTXUrNnp2VUhNVjM1QVZJdTBpZk1OY1M1MEJWT0lqeC8vb0M1TzFzaEF3RFhxMXZtSjV0N1V2RXpxbUE3Q0hmNXA2MUQ3UTBYamhXcWJqZlp3NnBBNjVSZGcxRlFTMDViMFpLeGUxVTU5MmtZNjQ1bTNOVEtRSWxMbmxNTklTNkZWekZpM1lacHBpaUlickRGR2lQRjEwVWxJVkp0MWJtNStjT2huLzRaQ1RyUy9iL0VnUkovZ3ZLNG40d21YSjVRR1FJV1hGNW9jQzR6a2tzU28wN0FMOXJaWjJiMkJ3Qnc0R2R6aUdmNkpSL2ltMFEwSHE2SkFXQkZBY0Rwc0FjVndKL0NrZ0tNVkhiYXN2RmpDTWZ5bXdOUEFRUWkrME5rNWc0QTBnTnBSUUZQMUtHeDNsUVNYZmg1RURWWlRYZFZ6eTRBenJlbVl3YmdjaUVBUUQ4RkZOUi9pRHBSZ2c3ZXpVeEYwWEZOVGpwR2tBczNFTXB0YmltT0ExOVRJNDBVZ0FNTHBCakU3MUo1enNPNkJvRWl6VnZIQ29rcmEvRE80MDUxR0hTM3hzMGZKbVFqYzZQR1hkVlVHb2hhK3J3cUZwL1V2WVQxQTdsN0JDVkdpdXdLQUJBVmZneFZVYWluYVVRajFIc000TFN5dmpWQ3YwVGFsd1A5SU9KS1l6T3A0NE1RRlI0SGZQSnpQZElYcEx4NENqa3VwZXRERUE3aVlTK1gyOGtSY2ZLSGlWWmtmV1Zha1FBSkErZ25UMENDQU1Cb1dwK1VsNHpnWHV1aVJwVUhTL3V6WHhhU1M0by9iZkJoRUZ3NCs4VDNMaUpuRWhvOW5jcEVEdTZsVkg0dXVJR2QxUUQ0LzFoT0NjQTRJUldvZE0wYkxtVzlWYjB5cnAxN0d6bTdjUjNOckN4YnlQMm9RMm5OalZoNWdZY1hqQ3ZEMWVSWkJTaUVmcEVnZktkYzgyOXEwdTloU1ZJZ05mSWJJTmozNTEzUHFwZXFCdUxvM0ZEQTQ4Uis2ekpJNzFPRVpRSGt0c2xIejdiZ3dlNW1GejIrY2dZcXpEdTNqTGVWNUFRcVJNaUQrc21RRm4wV1FQUlRYQzRtdVhGWGxSelBwQUFjUkZ6eVA0VmgwSVhkUjJYT2NpazF2dW9GN0RLd1ZWL2ZhZXNEdVJXQ1ZhMWF5NithSWd0T2FvZTBtM0lIbGMrUGZlVzFXa3JYeDVtOW1NdFczbFVOQUZxTWtOdjVWSG9sWXExNk11WDE0OWdiSGZMbWp2TERBa1FyYlZDaGlBRmoxb0kzVmdzdVkvTDY0UmE4WHAzdkI1c0J2aXN6U2I4eFZ4OVV2aTd0Z0JkSCsxMDlXaG5qaEo4OUdmdFd1UFZrbXY3N3JSUDZlUk05eWdRV0k5Mzhad1NHU09iUTZRZUJSd093aDJ3WWdPdWhQWkhGeTU3UERnTDB2K2RMZVpSbTRNV0dHR2ozQ0FERlZwd2ptVE1kdVNhWWd2V0JFUFh4MXkwNWtwZThUaXlBOFdqV3FDK1FsaHdpYnBzYmJaeVpGMDVqMkdxQ3BkeVYyY0tKVjVsTVNzaTRENFh2MUpXWmZ0Q2lzemdMampmT1oxdjdPMU1lVUZCVjIyd0NlRk1iZXE0RHUvMFNDbEpVbjdTMnhrcy9xVllEdW95OWhMTVRWZ3hZblVLS1dQbUZZdTdjU0UvbEZPbk9uRHRnZWxCcHFrOUVBOXRMV1pwVlNxbXBZbzAvbHlqUHRIMnBxVGplMklTZTY1bitzckw4dk96a29EbWc5Rk9rMnRSU2tJNmQ1LzNwZkQ3eHVQS1FWNmNDam9DOWhHZndpU3MrbnBsZUFWRENSeGtVZmt1WE1pSHhWL2dMaC9BTlhlS0VRbmZWNWl5VDcyMmhSemIwVkwyWm54WTNQekJiYzI1U1hDdS9LWWRmODlkemFsbm45czlERmc5N1IveWxyZnJrUGpCdTVqNEZuWDlhb3dyOFBFMUdEZ0Q1aldWUmc2TFducFlwK2RGM0J5L3hmem00OGUvZGlrVjVEcFlScHlPUEE4eURvTW1OSXQ5dUxnVER3eCtHVktVNitmZmpCenQ5MUNQeWZmNi83V1RUVFBkV3VOYldpaUFPbmpxL1R1Lzh6SExBaWl4NllCcUx6MjJVLzJhNDVWNHovNmdCYW9ENkFJd1VjVnpuTGlCKy9QOHp2R0xwVGFiLzRzaVBCYUFJS2dnQnVGOGtDRjQzSXY0TDRqdTNiVTVkdDhObDc5SGYrNzM2MFRRcEplSHFOMGU3LzNxMFR6Y0JZVkdnWGswOCtpMEE5bWVqOGR3MFVDdW4rdGYrVjZON0xwTnEyeGJrcDZ4blk1OStGNENNNmFFKzVnYkJpeHJzRDRqdTd2WC9uNEY0dm9MWFVWOHZkVEx0a1Q4RVlEU2VsVmlvS0hTUit1MjFwL20vSEtaR3hOTi9LdXJ5YWZxSEFZeEdrMVZOZ3NSNXNtMnBlSDl1dDMvamlsKzdhSFMwcmhzZThPKzJhWTd1ZFRaNUp2OEZBSkNqeGJVdTg2dmZmM2Z2VG5BdjRUM3gzamFVdVBTOHd0VGNuZ3AwcGtaVUY3UEphSWorVndDQUM3TkQzVlRWdFhJYThBYkcvejU2WDhLWGZPalYyVzdtQmdqNDh4YThJUDhIQUxTaDdwWW1RQXBPVFZNMy8vSEFhNVlyMmpsMlBCNzlyd0FRd3lSWUpKVkFxTDFHdk42ajBQRC9PbDIxVzNRMngrU21CbG1FWU45cjVCM24rL2IraDZhKzdoYkJWRk1XNjYwODh2OC9hdlVMSlZmL3Y4SUFBQUFBU1VWT1JLNUNZSUk9Iiwic2l6ZXMiOiIxOTJ4MTkyIiwidHlwZSI6ImltYWdlL3BuZyJ9LHsic3JjIjoiZGF0YTppbWFnZS9wbmc7YmFzZTY0LGlWQk9SdzBLR2dvQUFBQU5TVWhFVWdBQUFnQUFBQUlBQ0FNQUFBRERwaVRJQUFBQWtGQk1WRVg2K3ZyMzkvZnM4UFhwN1BMZTVPelgzdWZXM2ViVDN1ZlQzT1hSMitUUTJ1UFAyZUxPMk9ITzErRE0yK1hMMk9ITjErREsxK0xLMStETDE5L0oxK0hNMXVESjF1REoxdC9MMXQ2ejJ1UEwxZC9JMWQvSTFkN0kxZDNJMU4vSDFON0gxZDNIMU4zSDFOekgwOS9HMDl6RjB0eS8wdU9sMCtUQ3o5cSt6TmU0eU5PbnplYXh3TXlldDhhT3BiUnBnSkFoQzBXa0FBQ0Nua2xFUVZSNDJ1MmRDV1BpT2c2QU9jSk5vYVVITGVjRGtqWmhBdjMvLzI3aks1WnMyWEdBVGp1ejQ5M1hhVGtDaWI1SXNpeExqZWJsbzlFdy9tendIK3lmZGp1S3VxUFgxeVJOZDdQNWZENHJmand2RnNYL0Y0c1ZHM001Rm53ODh5ZlVZK3pGNnRmSDUyZnhwSDV3TmdNdlVFZVE0L24rZmp5K0I0TzkrZm1adlY0ZVJ3eitmWW94aytOWmowWDVJV0pNcCtKZi9FbmlwYy9pOE95bitpcnNMM2hpai9Mb2ovcUk3T25WU3IwQXZ2aDVnY2RqVW94NDMrOUU3WGFMWCtDR3VNSTNITTFiRGlIOHFIKzMzcTlmRnhzbDA1VVl4Um10aTdGalF6NjBXcS8xNmFySHlqZXdYODBuQlR2NnI1Vnh6UmJXVldSb0dhOHIzMGhSaEFEVk9OcWZSQjVSSEJYK0xvNE9rR1V2M2EzaE85MUhaVWNxWHJwK2ZiMGJkcVBXemNWL05RRGdHT3lYUXZpajJYWTUzMnllWHA2ZWxzdnRDZ01BUkdsZlZPTWFZZEZncWFoakZ2L2FsODFHd05JVXBsaXNyNkh1Vktoc2ZBQ2dqNkIrUjhmQ3RIaU9yRjY0WEM2TDIybC8xKzIwV3o4VGdPSm5xeDBOWDIyRS93RndEUURGbXpiRktGNi8yVHdVTDE2L2pqcFI2NGNBMEFET1FLdmR2WDlHTXBSbk9xZUc0K0hRWWIzZHBBUEsxMENMR2tJeTZJWGFRYkJmYmgyUmdxSGlCTXp2cSs4UjYyT2dNU3hjb3Z2WHUxRTNhamQvamcvQU5ILzM3cFU4OVg4QTNCWUE3bmdXdnUzZFhmZFdldUJxOFJkMi8rNzFlZjcwNGo1MTZpcldGSEhWaTkwQU1JTlFDbEk3NHZBN2ZUc0FwYVcwQVZBK01meVUrL3ZwdzNSNjE3MkpHcmhhL0ozWDErZkgxOWVYZndEOE5nQ2VGL2ZUKzlmNWREeUltdC9xQXpSYVVhSDd4OCtMUjlPaFVwTnE2M3BkUVVrTmpQU25vRW00aml6QVNUa3Q1VG1jdGJzTkRRbENwZkFkNHNkVFhYd2tQTW5rRDcwOFRCL3ZPdTN2QW9DSi8rNjFHSXRuZk5yL0FQaE5BTXdmWjQvTUcyai9mZ0JZeUs4US84TXpwZmkwK0dzQmNJbWxvTVZtenZBQUFNV1BFZ0R4Z2RnY2VHU01oQU5GcHg2WnplQ1ZxRDdPaXA3WmxvOUJZWnZ6UmpWZUNyN3ZobGRwZ1V0dGYzUkh6WGovRHdEWS9TUUF1RUs3dnh0ZmdjQ0ZybC8vN3RuditqdytldjBtV21uZkFnRXZXcmE2RC94SWw5QnFlS1VrQVBCbHBJclJNVFBxZWo2eThmdzh2cnZydEg0akFPM3U2K0poNFFjQVg5aC9BSHdOQURPcDBoNGZYeTlGb1A3dDMrcE0xNjVnYUxWWEZ2b0NQZjM1RWhMcXowT2hDYkMrbVA1enRYSkwySU9BNHoydW8wQUFtT1VwOU1EZDNmQ2lTV0Y5NHo5NmZYMTYrZ2ZBandKZ3daYXR4M2Y5OWxjRDBHaVA1clAxNjNLNXRKZGliNi9CcndJQVhxTTVsVXZnbVA2cHkrNzZPaXR5S2djZ3FBQkFrKzBCd0g3WXZrOTBXZ0ovOE9scDlqaDlyVzhINnQzK25idlppMnN4L3Y4RWdQa1BCWUNmMHNQelhmUjFBRFRhZzlkbmEzMGl5QVJVdUU5VVlJUzR5cTdZTEJsb1VVd1NBeDlMQzY2R3hTaGZUSjlVaGMvb2RnQTlsc0d4aEkyenFWNWZYenZOTHdLZ0VkMnIzS2QvQVB4Y0FLYVBvL2JYQU5CNWZkeXNSR3hDNlgrb2I0M3pxWW1BMXdDb2dLMUkwWFBPNzZBODdadysvaXY0QTBWNkNVbXo1K2dYT3dEUTMvSVcwV3lYWmJCZXFBSXU0dGlQczZmcHJKWVpDRmIvNC9YclhnV25xTFhyM3dhQXZZNUhLSWRhQUpCQ005NzdZd0hBRFBQUHIyVUdRdVYvOTdyZmIzNFBBTkFFV0JKbFF2UUNvT1RBWW1UaURUeGM5bGdDSUI1bVA5bC83QzBZcXZKNGoxTTNBTVNaZWw5V2V4WjZJUURzM09Zc2hiUjFXd0NpNTVuSzM2VWMwcm1aVEZ2VGUvZGNadk9PcGU3aUdmVWl4OUJQcWh2Y2VVVDNSeUcxNGY4cVVFS2tHMklxRHNCMHdKd0NxeCs1UXZTeWVIMGV0bTRKUUhmeC9MSmFielllQUZZZUFPUmYrZzFpa1JiT3lLWlR2bXhiak9LT1ZVOHNGbzlJaTdPd04wdjJWemU0dXJrZnhYdkYraFA3VyswSzRJSWVUNmZ5Tnk3UjhrbjJNbllNS0dkeDFDbDdoL2hGNlJIMXBIaUJXRTNTWDB0K0FiWU5RYitJL2FmbHd2UDUxTk1RQUxaaXBzNUNMRjBWbDBtL0x4QUE1Z21VbCsybFVHcjNkKzNiQWREZkxQRzBuMUJsOXBjellYL1dDL0hzQWd1aHFEdE5iT2NZODFHS1NyeEIzNzNxSmVJTmN0d2JZd3pHcEJpallzRERqczNCWGpTbG53UVl5WTh2UHdGcUZmMncvbmg0Z29KTThCMmhuc0xiV05qTGlGMGt2b2pnUXF3SkxoN2hPaWc3Y25RYkFCcXQvc0pJN0s0SEFMdEhsTXp2YlFERVpSQkNrc0xTRjlZRVFMeEV5VlcrSEYvN0VSanNoY1BSY01oZk9CRmpaSTRKR0NOOVdQWWZEWUI0MXhSL0wvRUcvZkVtQUNVaDRna05BSVQ0K1ZuOEJiVFNoUUN3S2N5aWN3c0FHcTA3dlMwSFQvbkpyMlFhT0MxQWRPUEEzN21ZaHVLNkRZdWhSRElTTDhMaVlTOFFieWlIbHFYNGUxQU0vZHRBdlV3ZVpHZ09DQUE0b0Q2dVNZZjVMdlR4SThBUTFpdUlPVTNQbUJyUVo2bk1RZEpwVHRnd1B6K0hUQWFxNWYrNmVGa1owZDhBQUxUcDVHY0pyNU82YVBvU0RrcEo4Vi9nbFRYRk02QUhmS3JYNi9mVmI3MmU0K1hpMzM0eDFNZWpneEhrbE9pb2wwMm9KekJhQWwrSkIzOTZvSTZveU1hd1NVNGdBRDRFdkFBc25sKzd6U3NCYUxUdVgxQUVHMitwTTl3OGZkZER6Y25nWnlmTjc0OGhPWmlZbEtoNldtcmlvb3EvMUFYdXkxRkt0bGUrUWYzR2Z2WTVBejM1YTcrblIxOGZRUS8xWnZFTStCZ1hOWDMrdFF3aUtNekVmL3hWUFhSRS9GYUJBTUJvd2tnWVl4ZlZnWUxyeWNYaWZseE5RRVhxeC9ocHZnb0F3SnlybDRhTW0zZHhFVVlGQi8xdXQ5c0pHRjArT3VXcnc5NUZqU2lxL3g3alMzYmxLTDlXeC9tbHVtQVlqenBPc2Z5ZHdjRitTdjB6NUJkc2Nna0FlaEwxUEg2dUpNQWYvbmw4ZWpBOVBRSUEydDVEQlRrYWRBdFJSRzB3V3EzMnYwR05pREhiNTNaaENKMEZ5aHg0dzFUTUxGUVQ0Tlgvajh1WDF3c0I0Q2NnZkx0K2g0dSs5WHVId3V5cVk1VEhnc2RGVDVrZld1UDc2WmVYMzdVdERzMHg2UFNMaXljOVloN051QVNBd2pub1hncEFvelY5bWFGVUNHUUNqRlYyUGJ0VEhpOGptRXUvRGMvMVN3V05QNlI5UStxZ3p0S2ZhaDAvK0FPeEp0VGYxVkFHbmY1Z05PUU93aGo1QS9QcVJWSTIreFNyaGYzbVJRQTBXc1A3MlRVQUZOKzdDN1grWHdYQXRSckdCTUIrdkdTZzEyY2V3ZVVBM084NzlRQlFUL1JGV3IrNW5vTUJNRlMvRXYrd0FMY2ZFWWErU2luS045RFgzM3NwYlJndUZKSDNMZnJKNi9CcWs5ZkY0Uk1VeHFCUUF0T0pXci93WlRNQktKUUdtTDIyTHdDZzJYMTRXRndJUUtIN2hlYkg1eWh3cUFOQU84Q2dWd09BM3V6NkFsQ3lnUys3M0FENEFLQ2VqYUx1Z0VjUDRDSldNQUJQRDc1MUFVZnRwMFpuNXZrVXZmTld6dmVaNFBXa2o5LzhwSHNiMVpyQUZTK1hiMUUvOVZCLytkOU9QUkNSdy9WNFpIK00vVXo1ZkZSdnVONUFYYndPbXh1T3l1bTFjMXFvRnRyRWszSm41TFJWRTRCR2REOTlyQTlBb2Z5TGVXdzNvdFFZbitsMjJWeFhEL3lYZUFqTnBQRnoxTXk2Nnh0OThBSGxxNm1wT0RsVDc1QWY0SHdCKzZ4ckloWW1yVFlDL2NLeXFqaHlMUUNtRDI1SDBKWDkvZURUTWhZQXpPNnpzT1p3TUNoMFA5WmhESFFwNm42MzArMTNnNGNMQUNRSCsyV1ZJcnRvVkJ6bmxoL2xnb0E3QTZQSkJDSXdvMVEvcm4vSDd1VDdUaDBBaWduQXcxTmRBRVFJczJ0OVp5RnhFR205RGdEMUtMandWWWU4amRoL1B3QUVCSVVoR0xKRmlOb0FQQ3lpY0FBYXpkNzk4MzNWUXBSSTQ1QnhIN0hXWVlxLzhGM1U2QkhEZkx4YmIxUWFBQnhzdlI0QTd6Rm8ybTZCQkdhQUkxQ3VSbHNJbUlFaGRhcytUVitqY0IrZ015NndxYzVnZ3dBdzhRODZsdG4vQjhCTklMQVFHTllHNE5HVkptaFhmbTFFcjdqaW0xM1JTbWZOU3RkL09CemdpUjhUZndmTHZ3OEhCRUQ5M1hkNmNyVU1oNDhUSlE1YW1oNFptMHMzRGhmRWZOckNBbjZKT2xZRXFZRm82TkFBZHVhaUR0eS92dEtPb0FWQW84MVNVMm9EME1lUXNnRnU2bjhBWEFrQVZnTlJiektwQjhDQ2xSU0txa3dBbndDMmhvc1grRlk2NjBNWUFKbThVc2kvZ3gwL1V6a2I0c2NMOG5CcC9uSkIxeUxDcWNnVnRPNXBJSlE0Zjk2OURHeWk0WFVOQXI0aFJHRElVdER1cDNDeWpvc2YyUWI4NlNVS0FhRHp1cGpWQVdBOExleC9aSWovSHdEWEFPQkhnUC9YanJveVl5UWNnSmY1YTZ2U0NXeTA3KzZlVWFxL0t4OVpBTURpZmlQZy9FZTBaK1lBQUluK1NsVmYyeXBRYXIrcnpaYmZ2N01lY1l2UHNCY3VWNU9rekg1TEpDS3F4YVh1c0pRUm5TYUFwMzgwQXEvOUtnQWF6ZjZNendDcUFKaE5Td0JHSFhqM2R6dFVZT1lmQUxjQ0FOaUJhREFlNjlSNnMvNGRBY0RpbVpnTDRyNFBqZTd5b1Z6NFdlK2crUFZHdlhMcGR6eWFqRVozNFBidmRqdVc1TTFVUEJ1QVBuaGRhUnB1Sm0wd3lYUk5HMGxkakowMktoaHA2WFZhZmJQNFo0WHFkODVvelRkMTFZSUR0d1JSLzI0NG1UeVlpWU53TzRac2dxRmMraGZiQ0NBQUd1MzlpOTZZdC9NQ3dCTHhXZnduQW9GSzU5WC93d0d3cFZzRGdBRGJId3dBMWdMRlhIczhuTllCWVA3YTlVMERHODNSZXEyRkRnRXc5MEFXNnYrZXIvdEdVUDI3TDMrUEVMNzZUYy8xZ0ZId0I0VnJ4SVFDdzB4d2drZ0drQ29CdURqa2czRnpJd3ErS3ZjRCtVVXZVOGpwclltcWFLTjJBOW8rQUtMbEloZ0Fudk9sM2I5Tzk0Y0MwUDBMQVNndXR0SUJ4WHhRSnd5R0FHQ0dnNkFMMkZvOHE4NGM5cjVrV0gvM2tlVjlqQWJqTGpYMXB5SzlVdUlsQ3oyUklXL2pnQkwyMWZsQzZmV0JZSkhzS0xrYmY5Z1VrTXZDcmhDeU44S2pYMXdiZzB0aTJ5ekptazBHaS8rUHh1TUpTaHpHNC9IeEVaUnhtYjJZZmlDY0FuUTJpMEFBN25qaVY0Y00vVlFDb0JSQ0lBQllsbjN3WUQwQUtFM3d4d0tnSjRSUkJEY3FVbHJnRVJYeWVUWDhRQmdDQUJuZkxnRGt4aDhlQVNybGo3KzVsakFPQWFPRklMM3ZobllPeTJISjBwWXZyVDVyQTFCclRkcWJabkloQUhWRFdXVUNrVmdibW9VQThEaDdmTzI0TkVDM0hnQWRPUG4vQjhCdkJxQUxDZWlQUXdFb0NIakF5NEk2QzdETkMvOWIwdGZsYWtRSW1LVitUOGVqdXk0Vis0TTc4V3h2endrQU9VdkVURmh1WGRkSTkzTDdnSjZaZ0ZjQ05VUkRCMzhyVEVMZ0hOYjNpWXFBdThmcDlNbk9GTU9MUWdzVkVlNVNBRFNhM2ZXaUdnQzU3M044cCtaL0VSSHhxdzFBNWJBQjZOZWRCbHJYa2oxd2V3Q2c4M29kQUNIejE1S0EwVGdZZ1BuTG9rMFlnVWI3MWVqUWlVU3ZBSkFMUUhlanFMei9MZEVnQklobFlPZ0c2b0ZlaHJmblZnTGdTek90QVlBeENheUpnUWtBc2FPMEZscVZBUFFoQVd4bGNFcVZVUU50Yjh1UU1KNEtxam93eXhvQUFQbi9MQUN1MGdCL0lBRGRyaUxnK1RFVWdNWHpjOXNDb0JHdG54Y1ZKZDFrQWtoaC8rOGlHWWlDWHhGTTl3aHZyaFFwdEFrWUFXdVk0T2pyQWxpQ1FRRmJ5RjFYV3FuUFdic3M5OHkwMmtSR3VmdGQ5dHZMKzRUQ2drZlArK0tDcXowR2k3dDdleEdJWEJSNnhzVmpoQUlZYlJaaEFMRFNMZXIraDdkV3J6WUFwZzd3QUtDdlRJOHErdUM2eTBtdnZ6cFBMeFFBNmxOOUFEaDl1cDU3WUFCZzJrVDVFa2xBOS9WdTloQUV3T3daVFFTMEIyQVZyaldYZ0htdGwwSHAvL1c3SmdCbTBCZXFjc3V6TTJYdHZ2OFJBSElGNlFJQWZOTTBJOGJUQ1ZIWnZ4c0FZRnpSQlZmaGdNVXpBUUJaVkE2RkEwVVFjRzEzYnpZck5ZdjdmekRzU1AzZjdmVnNBUHFXTFRmRGZ1VVRWd0hnSEpVQWhLVC9mZzBBdmFzQm9EUkF2NmY4Z05Hc0dnRCt3T1BqWFJNQklLY0FsUUN3NWQrUnpGQ05qTHYrU3dIbzkzUlFLQVNBUG1sMFE5WmpyZ1hBTjRzazE4WDV6S1huaE1DVlJRZXZRamtYdUp1RkFUQ2JyOUdLUUxQUmpaY3JzeDhDcUZET054blBwcFBwYU5DWEM0Qmk5WmRNNnlOTmdLWDhLUUJBNFNUcTNYclprSXd0NENXSUMzWUhBYkdaem9CcmFjSjdZenNCOE8yUUlLZEwwSGtpRGFCeUJPMit1RlpaWVJITHhTc0NyZGY5SmdDQUtRTWdrdnIvSHdDbFp2NW1BTmd6VWdmMDU0RUFQTzRqZmZzWEZtQUxFMEZ3SEZCMUpwRjd2MlUyU3FmZmdWTS8vVysvWHdHQUZqbGQ3UTlVVDZ1S0R2YW9tNEVTVWEyTlFGMDdEVXdkc2RPaHdoQjFOUUNVTGJWSENwMWh3QldBVm1BNkMyekJ1eDVxQUJyTlFTVUFZZy9vU0swQVJjUVovUkFBcUp3eXNuZ0F0ZlhmQ1FEOHJRVEFpbEdRQVVuNXUzb2hCUUMrd1M4Qm9DK25BcDFDVlFjQk1OdTNOUUd0L1dxemNvMVMvWE1BSWpVQjdCTHVpam52SjRUb252U2p5cEYrQU5RS0V0Q1hlSzhSL04wcmZCc0N6OFNOU2xPQU43RmJxMVBxMzdaaFdxejB3cWdQZ05JTjZGZDJyeGNBUEd5NkdvQm92M1JwQUF6QW5UQUFVYi83NXdKUVVRTGtad0VRcEFQbHUrV1ozYTJEQUpnK0FEZXcrK0lGUUxRbFpFUHFtVzZmMnU0WElHVzc5S3FTTlZFL0ZzOE9iUitTdkQrNjFzN0RNUGtESmVCTU82QUFnQi9YcC9PZkZRQ0czUG9odHprMVEzYSt1Q05uQWtIZE91NG5hazJ3c0FDTHB4QUF4dU94dkZTbFFic0dBQ0hqaXdEb2h3SkE3S3FvTGdUazFRRHFReTBBWEpFUTlZWWFBSUNUclFXQUpHQzRYNGNBOFBEU1Vmc0NvdFdjU0FXR2JZQTRBTU03R1hFeTUySkk3UEFNb0dRSFRrRVA2VWVITG9LYytwQ0xCVWRJdW5Ya2o5V0FYdHlqYWhtUU43V2QvMVNweGJWOGpidkhkeXNSeVJUOER5R2Z6bjZQL1lCeVhtQzArQlNWbzRwWjRHaStEQU5BWHFUK1RRRVlqYjRSQUZXODdCc0JVTWJ3V2dDR3cxSUZKQ1lBRWdFTXdHeldGZ0MwRjA5eld2V1h3U0FPd0wwRXJCZGdxZUQzOHQ3bW5sRzVTdGl6dEtjWks4WUFXTEp2OFlCNHM5VnFrM1BDWUFEY1lWc3kvRjBWREhldWw5a0lHUGVlakFhc041c1ZrRjBaSHNiOVBtYVBNaFlVN1Y1Q0FKZ1A1VHpERHdDdTZ2K1ZBTWdZbUFGQUx4QUFvNmFqaTRBYkFtQmNuSzhBUUJMUTJ4OUNBSmdOK1c2d3huQXpSNzJNaVRaVkxCQzBrRTRtNlpWUkNrdm9OZWp3RDNGckYyRUF5dDlndzQxQjVTQXNEdzZyaVBpWVEvNmlHR2c3QW9VNlhRZ1lnamNXS0lrSk1GYlBTRGZDK2EzYlNlNzd1bFZZQmdLK2tNMTVlSFpRSE1mTWxudjdaTTlrQ2RuV2ZyR3FCbUN4R0luTE0vZ2JBR2hEclc4KzhpY0F3R295a1FBSUZkQVBCSURQQTZKMHNWeFY5REJtemV6RUJlejY1aU40Y2k4RXlWcGdsSEkxQVJpVjdaa0VBQUhxMzZFVTZiVWhHZ0JXdHRpZUFBQW1qUFVoNXdibm5qTnFnNzhkZG9lSDlrT2s2cStLbWhFTDZXd3F5RTkxa1NieER2ZmVKUUJZM3pFQU92dkZ2QnFBaFl3QkRPb0NnT3ovVHdHZ0VMVVpRbzJpZGwwQWVoY0NNQm9HQWVDN0NtNEFSQVdCUVpva2NTVUFmSmRZY3hUdjE1Vjl6RjlmdTlnRElCSEFJVDVydmpjY21BaGdjeUQ3KzQwcU1ERDBmaGdBeVAySDRvY1lLQVRzOU1Dd3ZRejJFNDVZdC9rQVZQOUVHelFjTTdNN1RnR3pyQ0tmU2FFQ1lqOEF4WDNOMW9SYnI5dDFkU1A3dFl3QjlQOThBR2o1Q3dha0ZTRHlRLzhjQUFRQjQweW9BQzhBejNHWCtZQ2JoVmY4QW9CU0FmUXJGYk5uMG1lMmVLUTdMbXJmRUxnL0hvVklyUkU1QVdpM1hQTHZpU2VwWlFGSGduTi9ZSWJ3TUkrZUJTOHpLQ2FmSDFYT2w2bTM0Y0ZQdXBjV1JtQlhzU3F3M3QyeE1OQkROUUM3aFE0Qy8ra0F5R1QyQ1JvS2dZS0F6amNCQVAyaHF3QVFmdUE4UzZzQldJMWFqV2hUQ2NCcUZROUxCV0JyTmF5RjhOd09mdW1SYjZpM2pVeEc0RWxEODBJQ29CRXdBS2lRZjRtQTFBRVlBRmRFbDV6QlVZNWYrYmhQcnZERVBTeEFGOXRnUUgwVU53TDlqRThFZEE5QkVBUlMvNjZYcisxR1ovTlVEY0MrVThxZkFBQzR0VmNDZ0JyczNoZ0FBWUdRLzRRWWlvQzI1UUg4RGdEd3RiZ0dnT0ZRT0FKSjRRVm9IZUFBb1BBQyt3Z0FnQUNvRUxSK3RtSUExdmR5QVdETytVWXVGcXhIWVQ5cEd3VUxBZzJEQmtEV1ZkTWF3QzEvaFVEVWlxb0E4SVZ5SE0xanJhczJDaDh1Q0N3RUZCbDlqdjU5SnFhQ1RnQUt1VElBN2dJQTJQRkVrTTdBQXdCeWJYOHNBRjc1U3dTaWRnZHZFZWo5T0FCR0l5OEFRNTZETXNpeUFBRDZqWFMyZEU4Q2l3Y0tETGJTQWd6NjhEYTMyck03Ulc0TzFTTmQvNDRmQnc4cHUrQkpIbkNzRStuYWdDVUFuYWp0bDc5QW9OM3U2LzJBY0I5emFITGJBRWU1Z005bk9yK2VJYTZCYXNFcHVrc0hMNnJ4azArWUNpaHU0em1xRHdEL0xjYTZzWjJ0cWdDSUZ5b0c4RWNEd0g3YThuOHZCaWFnTUFMRHpvOEFnTFhpQXFIU0VlVmZrWU5mZ2Z0Q0JjVFZBTXhudUNFQUFVQXloQmFBdVBnd3M0T085c3B6OGdHZ3pwZ0FRQ0VBVlo4emJteDBKRUF0NkpEODM4dGhxSUNvUFhSM3VqQVdjc0d5dHhrQXcxY0NMWWFaTjRQallkMkZ0Y28wbWdDd2lmQXdZelBCSGRqZVF3Q3diK3ptbFFEc2VKeTB4MC9ZTk1rSUFIZTQvL3NCNEQ4bVBVTDhCZ1JNQlhTR0tyRy9KZ0RZKy9rMkFOalhHdmJUTEUzakNnRFNSa0lBc0dORHJSRXY5Ni9DQW9DN0gzdytWbmpZZFlFYVFaNFVvZXdSQ3VDaE1aZ2Jhak5BcHBpWUFLaGdFRW9JS2VUdkZEOWdRS2lBQVY5Vk1aMUFpTVBBam45ZzRadUM4dHdLeXVDWFYyaXNDTGpIVHhzelpSeEgxL3p4cTlEYkgxTWVDL0IxZjBvYmNSVUF1NFN2QTNTR2Z6WUEzVTdVcXdCQUlzRDh3TTZJcjZ1WjA4QS9DNERwa1JtQnVBSUExUnJjNFFZV0pDUjhFdGpGb2pjMDBNZzZPL1c0SVhWYitQWUFWMGl1RHdGRldKcWJnY2NJMkNsaDNiNVFBTy9lVVJxQjlvaUhWREVBWm4wemExK3IyME5IWXFmYzRWTG5qeXF2VVdDb29QaSsyVkdFQTJWOU40cUNWVFVBc1pnRTl2OW9BTHI5dmxBQUlRQVVCTFI3OThOKzl6c0FHTjhRZ1BUSWcwRTdEd0R6aGxrTnhwQi92RStrQ3pBczVlR01ZeXB4d2IrMTRuS2VFWEQ5Nk5QVU9CQ1RJWHRwQ08vUEVnQU1lNUZYK1JzQVJOSDlhRWlrSFpOWjhPUkNPSVlCbkFoYStqYXV3LzA5ZVMzd3BTS2labFQwdmZqdWEyNERrdXNBMktYQ0JSZ014N1VCb0NEL0RnQ0tuME91QU42cmhpWmc4anJTNVUydUJnRG9nTjhIUUg5OFBOWUZ3RFlBY1RvUVBxQzlqT3NJM2pxOE9sdkN0dmlOT0poYnp6a0J3UHN5RkFEOVVTL0FBd0NUd1VJRmJCOUh3MEhGamg1bitpWUdRVHc2MG40dERVRGdNQzc5ZU93RW9NOEFTRUZpeUFVQUpFbmFLUzNBSHdrQVg4NGZ5eWxBRFFJZTVuZTNCV0JvS3JFdkI2QjN6TFBTRGF3Q0FCa0J0UkMwaTVNMGpaUVBhQzdtT0lLYVduaFF0cFo2TXdGUS82TDVZcld2NDZ3cnBRQmc0aGx6Qy9BZU1oUUJVVzkvUHhwVTdNMTJiSXpEZTE2ZDYyZitRRG1hSVFldUdxR1llWC9RemZKamh0TkRiUUIwZVZnYWdDeG1RZlRPRHdQQXlvcHpBOURyRFlhUDNBSzgxeUVnaXZiUFk0OEtDQWVnekFmNHZRQVV2L2JTdkxRQmxRQ1FUbUJjQUxEbkFBeUduZ1ZjZURialN3ZnBBQVhkLzVBRXVHd2pBZWdQeDQ5aExpRHlBNlBOK2g1NkFYUlhFN3RveFlCTW11bzcxczFzVStxNEJ2QmZmYWM0N3hEK1YzK1pTemR3ZHlrQVNacXRlWUxFOEk4Rm9EOFlQVStpVVBGckJLTEpudlhGRzF3QUFDNkQ0TW1pK0ZvQVJvTlpMdDNBWUFETU9VQ1NIdStZQnVoWDZoNDNBUGQ2dUtkK3pnbVFEd0NITTJDNGE2UDdmZThDQUhxOStQN3hUa1FEcUIzZmptWm9QY0FLa2N6cW5qMVgzejh1QjlsT3RtV0QxZlNmNWprTmdFNE9xUVpneUFFWVUxNi8va0J6SGR1eS9oUUE4QkhuL05jWmZBZ0JnRXRpOUxnTGRnR1JDdGpPRjYvRnhNMW9hS2RMZnRBQTlMejdlK2pGUWh6eWNBRXdyQXZBMkFFQXpBNnFCcURQVE1CZzVBRmdWQVVBMjF4Y0FxQVhmbjBhNFlZQURPZjFMSUFpSUpva2k0VnlCQzhHd0prWXJpNll1V0xtQnFDMkJyaWZIb1VUVUEyQTlnQlFWbUNjcGxtM0JNQ1p2REx5ZWdCQzlnQUNLdUxsaVlGVnJJSHJCOGw5QW9YM2V1ajFhZ0xBRVloNjJXYXpHQSt0VEVPclJKK3JqcSsxVjlobERCeXJwQzRXVUNLQmF6NXhmMzkzUHlrQXlGQnlLQzhNd1RaN2h3S1FaVHlXUHJ3S0FLQUZwaVVMK0w3L0tnQUd3L0h6SnFvcmZnNUFMOHJTL1dJNkd0NEFBUDlPc2E4QjRQbnVmbFFiQUdRSUFBQWpLalJmTllVMXB2bGM5S3hNcmVrVG1GckJ5Z3V5d3c5SWo5cG1BSmpnd2dWY1hBYkFKRXF6ZUQyYlRJWjlUMzhLR2dHN2dpSlJSaG12Q1ZRQUFETUQxQ0liQ3AxYUFDeGVYNlVKU0RFQU15aHBQd0NKQktCM0d3QjRGK3ZmQ1VCeGI5MHYwc0dsQUV5TzhXNDJHWTFFWERVY0FLcUVwbFVhN2ljQkFCL1FKbUFYc3pCQXFnRHdMRWxYVC9DbGpMVUdRSk1EQkVUNWFuMjY1b3pKQVFBc0xpZ0JHRDJ2azZ6WGUzKy95QWIwc2pTZVQ2ZGpsbWJyYjFKQWwvNnNlTGxHSUhENXhFNmhKdnhDOWRzekF5RExjNWtXWk1jQmhLeXJBRGhtSmdCcVJUSUlBSGh6Y3dBZUh4L3ZRd0M0ZHdOUXpJZUNBUmcvNzlMMEFnVWdWVUNXSmF1bktac0tEa0lCc0JCd3RRVFJadUNyQUZnc1pneUFZelVBK0ZrK0tXUzVZQkFBYzlYT2xkM244djNWbi9vQmpRQjJBZzFuME40K2FDNnFqMkNtRXF5NU54aE1wdk00U3dnQTNvb0IvNlVSaUpKakdxK21CWEdEWVQvNHhqYmxUMVNsaDFxQVlXcXVqcEFMSjVTWGJOMkJHb1BueFdiemNzeHpuUk13dDI5MjBnbjh1UUJvMkFNQVlGWjJNbDBseHdsaEFRSUJtQnpUWlBkNHozVE9Wd0l3K25rQWlKWEF3Z1hRQUpnZjRCQS84dnFCM09XZzFINUZIZ3pXa0VRQVRVOEdjV1p3ZnppYXJ0SWpkZ0d3NFAwQTlIckhMTm5ORi9lQlhnRGNsS2gvOHdBZ3ZxbVpHMEJjSWhvQXdnYnJSeGJydzJGVEFLQmlnUllBUXRJaEFIVERBTUJUKzU4Q1FKWmhDMUFIZ0VuRTdwNVZKUUJtRHlrb2FhSmFQU3crOTdVQUhBUUFtUThBTXl0WUFyQVR5U0FNQUhacWhqWTJEQUFWMUNkY1BFcjhsQnM0dG1QRmNCSmtaQWRUZFhha0R6QWN6M1paU2dIZ01nbW1EVWdMRzdBcXZyWmNGWFRkN3NhTjdlaEhZL2NtQUdaZ2FGM1JlekFmZ2lGMkloeHN4NGltMDlsdXUxMGVUOG9HMkhsaDBnbjhpd0ZnQ2lET0hxTDNDd0Y0Zis4ZGJnS0FzeXo1VHdCZ3RTTERRRHR1QVRBQUZRdjVkbmlmTUFSdXdZTkpJTFZnWU8rVE02YUJkdkZBcGdDU3JCZFZDOW9KQVBjQzJaS1FDQWo3NWQraDczNVBhWG9iQUFJQmJTWDFlaHFRdWZqRHZQalQ2UndDd09zRnJleUo0TjhPd0tyd1lxTGU1UUJNZXV6dTJWMEtnRjJiWGxTbWJxdHFkSUVBcU1XVEx3SEFUQk1BK2NBc0VKd2ZHUUQ5a0IwcjVzWVdBb0RGczF2OGxrTkl6UXpKSW1OMC9iRENBdHd2RXRNSHJCa042ckdyRjYvbTB6RUJRRlVQT3JNWWNSTU1WcEZRMm93K0xLRlVuT0xZYVVROVhqSUZ3RG9HQU1UYitRd3UrQU1md0FrQVV3QTNCT0RlZi8vZkhvRHhZcDltNlJVQUZCUEJRZ1d5bVdCOUFLamE5TExsWHZGZnM5Rm90VHZkcndiZ2tKOU9WUURvUDNUdEdCa0dMaFFBMEFBMUV2NWczTmdBSU1RUjlPYVB3ZlJYVXY1bElzN3dlWjJreDhPVkFMQnA5RzQxdXg4TkxRVENoQytrMzdaS1V4ZGFRSG1OQTEwa2IreVpEWkpwRkk3bGRBYkFQaWswd0NrSG1jRjJBWmdxQUk1L0xnQmlJZWc0aWQ2dkFlQTk1ellnSElDSWxuNHZnbldweFRQTlp2UmpBSURCUVcwQ01zb0VqSXlGb1FvUVZCaklVdlRRczNFWUNYOXVYR2tNY0tPU010MWlPbU9Cckl1V0FnRUM3UG9WTm1BMm5ZaUMvRXJ3dldEVnoyNStSMkhhWnRRbDFnVnJKRkk3bnlvQWlQZnhKaGNBeUdBd0ZMeVMrNWNDb0hLQnZnV0FLUVBnbVBjbTF3T1FKcXNnQUtKZzZVc0dtaTJSWWZqOUFGaEpvUUtBSXdLQXF1WmhDVXJONkpSMGlTaXdHZWZRVDVFR0FpdEV5eFdrT3FuMGgwTjJDUW9MY0hRRDhDYUhmeHFnQVpnVW54VU9RSEY3QzkzUENsUDFaSG5hSHZoTGxDZVArbW9pU0pqWWl2dkxOeEFBWldZd2NnREIzc0N2QWtBWS9lOEVJRDlHdndjQWwrbjNGeVl0WHRmcGN3REl0ZFhmQm9CV0NHVmRHQVJBcDMvdnlsUWtBRERYZmcwQXl2d3dRdXhrcUlqZVBLOEtLTklOOVVZRkFMTVZBNEM1QUcrVTNOOSt5ZUZkRU9vZFR4eUErWFRLQWVqM3lIYTA5dDFmSVgxRlFDdWE4cnVmTjJhOWNOQ0dZN0dQa3hjWEFNN2R3WDhWQUxzMHk3TnJBWGdQQXNEcVNGWXRmc0ZBdXoxL0ZIMlp2dzhBdFJ4a3BZTkJKOURjNmxPeHg4dlc1OWErQUVVSEZMMzY2WFFGY1VpbzNIUnBiZ2JoQU16andnZE1mUURvbjE0QTJIb0Fzd0hLQkhnRHZ1THVENUkrenpwclQ5UEhLV01BbmJCN2kxMndmMmdCQUJzRTZ5WEF2eG1Bd2djOFBWd0x3Q1FYMGVBd0FOamtuclVrbVlTT1hqVEs0dmxjcFVwK0N3QmErTUFKbEV0QjFRQzRONE5pelc0NGdhWm4rSXdIdGdldTVPaHk1Y2RNeTJjQVBESWY4S1MzQkwyOVdjcGZtd0NIUThqc05QY0NkNHRuVmpWcVlFcWY4UDJZOHArRUQ3Ymd1R01XWmxaQThQZ3NUMUF2LzhKYmFIRnY3cWp6akVVY3g4djhEQUJZbWYwaC94OEE2RjBEQUw5RDJRVk1rMm9BMnFYNDY4aC8wbnZLTTJaaCtIaFVXcEdLQlY0SmdDU0FCQUNHQmhBQUdlRUVCaUF3TnNSSStIYndRZnhDUi80WXRWMXNZUFlLS2hFWU1nQUtIekMzQVBobGpUY25BU1VBR1FkZ05NQUFPSXcvRnZCVE1Zd0hqQmZreHpUZXpVc0F5bk9uRjRYdlF5Rll4UHRreXdIZ2tTRG1CZW82RWY4bkFCeXZBMERZNkNNUEJsY0NZTXYvcVJ4ZUFQNHJBR0FHK25zQldKaDlnNWdQcUFIbzFTMzE0Vm4xZ2VJMkRRRGJQUXJkSWNkMFVDV0dPM29FaUluZ2VKRWVUN25ZR081VS93UUNqSUkzVUNXZ09FaHhpN0xFME5GQWl6K2lwbjVBL0U5dytGVENFMXR1WWswZWVTMC83Z2VVbDRiRmM4VGx3TDV4a0JqbUJRQUhDRUN5VTZXZnJEaUFtUzl1YVlEZkIwRGhETTJ1QllBak1McFRBRXdzQUh4ZWdOWUVFb0NNelFQM0lqUFlCVURiTXY1UEZhTjgzZHRibnBjbG5ZVVd1QVVBTEE0YUJnQjdrQVNBeTErWmdGRmdBS0pHL2ljMkFtcmdHYkdWRklYM0RBN29Qa0U4MDJaNHR5c0F5Tm9tQUpRbWNNdS9ONG5lU3dENitnTXM3Ui9Wa1Q2QTRPa3RPK1V5Wld0dUFzRHVCM1k1VElOWXVmNG1BSWhMQUk3YUJQeDJBRHlhb0FZQU1JZ1lBa0MzTjdoamNhQjVxM2NsQUwwSEppQ2VGYWdCc09kK0Y4aGZBc0JNakdqdDhUMEFtTUVCTmphYnJjZ0lQRHBOQU5vYVl1OXFBRi8zT1VBSFNPRS9zck9WdTBpQkVpUnlSMVVnR0FSL3lzTFFYQU1NcG9YOGoza3ZBSUEzMGdLVTBmcUpFTkJxT3VxVEJzQ2UralBoRmdTRlVmQ1dpK1BIY1VtQWlBYzQ3cFY3cTRjQStrTUYydGhpVUp5VTAwQUtBT1FFbWdBY0RvZGJBWEFmRHNDc3ZQc2hBTGlnZ0FNQTFCdWdJMXJFOTlPODMrclI4ZzhGSUNvQXlFYThWdXBvMU8zWStwODdmNWFYOTQ0QWVQZmc4SmFmeFlKakNRQ3I2dndOQUVDMXNHUUUrS2FCbGVVaDdxdlNQOFZaTGRBWmNuMW5UZ09ubGsyQUMwRWFBQ1grcU5OaEtaZGlGTUlwRkVCdDhiL0IxaEh0bGp4WXN4MFJvVjhjK05VaTE5SVhBTHhYQUpERzBnbGdidkFqZGFjRU80RWxBREVKQUU0TS84c0FZRElweGMrbEZyMjlYUTdBcE5lR0IydTBJdlAyYjluYTN3UkFEbHIrNzIrbnM2N2xwZ0M0LzQwQVVJN0Jjcm5jN3NwUWNFY0RvRDJ3bXVJdnY3NDNCVXcvSXM1M1NucUU1VUxRQUZSbUs0TXpyWVl4MmlFYXdBVGhYWHFBNXRHYWJYejd0MHY1UHpra2Jxd3VXQW9nVTBsYllnTW5FUDUwcXRhSnpWMzFBWXZCMCttcWNBS2YxR0tRWGd3d053R1RBT0NNb0ZBQTlLTDJ4UUNVTDRNQW1DOGlBQ2p0ZjFUYy9uempCYnh0dGRnOTRTQ0RFS2IrYmZrem5wRDZ0OFVQQVNBWEdBMEFqbWVSdXM5YnZKRUEyR1VWZmg4QW1RRUFZUUwwamdZZkFLVVlEUUR1ZlJyZzJRdkFzQVNncndBb2RIS2phWTZDZ0hmak5xZWpnWmdCNi81WFhMV2gvRXZOVDl6ellRRGs1MUpHQ1FmZzBRVEFWUDlPQUNBS0ZnQ0pId0NyZFJ6S0NnWUEySnQwUmpVQThMb0hXQ2V3azU3Tk5BRFlDd1lyQVdJS0tCUkF1OUhrVzNBTUFxSUFBRXdsVUlpMXhhWGVhT0NETlpUODIwRCtoTEozRFRRMWVDdGNnRE1Hb0R4UkRRQThmN2dRUTVab0VrOEtBSllRZ0IzWkhDd1FnTEVUQUtwV1RFVWtKeGdBRVJpd3JRVUNnQTJsQWFUODhTaUU5djdMSTNlWEZZZ2F0anJoQ2tYTy9zekFmNDFzYy9YeTRsUE90d01BUnNycUFHQWJBWHRmQUpyb1Y5WUk4N2oveGk1Z1Y5QUFMZzRJQ0xBUGpQSUIrOG9EWUF0eUJBRE5SdnRYME1CK1lJdVNQeHVzRGJtKy81K3F4RS9tRzRtM3ZCVVc0S3hzQUFkZ1BsODhTOHNJVFlDNEFnNUh6TjVOVHBrQW1STkltSUMvQklCdVA1TDdMMjBFV3UrMUFmZzFzZVRQOS9NVi83WTdiSDkzejV6NFhRVEE2Vk1Ed0VNQkZnQ1BGd053dUJBQTNTMUlad1NOYUNjd1NQVFdab0FLUHhHWEZOSlRRYjFLcml1RmlUWnh2TWxyL3k2UzIyOXRDSnFUdWlyZzEwZlU0REtuUmhuNmZac1lvdGUxaDRoRUpFakMwOU9rZUdOMlBHc0FsS2UrQUJHUTZYUTJYeENGVllrS0lSWUE4ZWJ3QkhJQ2QzYmJrTDhHZ0I0cnR6TjhiYnRHSWJKZm9RU1V2N1ljMGk5RzcwM2MvVzhWb3dLQXQ3ZGovbGtDb0F6MUJnTUExd1hxQXJBTkE4RHNHeGFVRCtBb0ZBZkY1UURBelFrQndITUZBSHd5S0hiWVR0ZHQ5NGhPditvT3QvemJ2YmVuQVBGWEFNQWZZQllBQU1ERk5FZWhZSG9Wa0dndWdDODJBMkFmUHgydGZRRy9FUURIZ3REWEFOQWZ4dnVvWFpaaU1lVWZuZW9TOE9ZQklIb0xHeDRBM2prQTNBSWdBT0tiQVRBUEJJRHNHMmpzQ3dqSkNGS2F4d1JBNWJMd3Z4eGJCYWg4UUJNQW1DbW4xd09IWlVCd0xCc2NSaFFFVWE4MkFGd0R1UFRKTVp3QVo4WWhrLy9wRXdFZ1d6MnpxYUNSR1UxMTEzTmFZRmtsYkwrT2w3a1hBTFFZZEJzQTJDZFhBbUN2R1p0U3J3R0FhdEQzbkdYT2VseFJaMUlYZ05PdmxzK2c1RytYRGlqLy9Bd0JPR29BWnJjR0lLc0dBSWwvaHdEb2RIcFdtV3BIVlhEMmt6c3V4Z3IyNDB3SHVjZG1nTnU4NjRzRHFMd1k3UTdOK0JHVWprRWFnTzBHdmw5azJjQkZRR2YwZnE0TmdGdjhVWUhUOFZvQ2lsOUtCU0N5ZHNwNXdGeWxCN0tyUUZuT0NnRGtaVnJ2ZDZVSkVHZ0ZMUWYvTmdBV2k1c0FNSlRsWVBiWmNjWVRka1RXRmdKZ2NQaFZHNEFUNlV5MGVYVzM3SHpLajFjRDhKWnpEK0JuQUlDREE3dmRUdGFJUXRQQUNnRFU1NnZVWm1qdUgrSFpZQTBBWDZneWcyUm1IR05FVFFWbkVpRUlnS3dQVXNoL3ZFNlBlZlkwTWJidWlmdS85NVNlenZWc3dPbDBmdTlFaHVobGViL3gvblJqQUhJQ0FKRWxUZ05nNVFUWVJSU1lDZUFBNURyR0VNTUp2L3J0andkQWxFbDgzTE5kSUZrNnNZczQ5bnFUNUhpdUQ4QnAyQ2Z0U1M4NXNudjJjaHZBSVNoK2ZQQTVvQUlnL3k0QW9GckFUV09WQ1dDVHJMQ3U4SFQraW94b3pRd3FlUHVZY3NEMDEwZWRHeXRXQk5tN3phdzRGQWFaczFvUWVYR3k3NU1CckJ3c0lnU0hMTDhBZ0hPVzlpaC9ZbjdNeFJMKzI1WGpDQzJBVUFHbUNaak5yUFF3QndEYS9ncWZtZGNKRkFBY0xRRFEzc0JLQUhwL0FnQTd0aEdVcmF1OVA1aFZPQWJ4OFhpNkJJQlRkaUFJR0FpYXJnZEFSQUYvRGdER3psRnRBalFBVHVGakRhUUJRREZ0TFZNbFNTN2J1VVpBdmRNQVFBdzdNN2FVLy8xOW9RQ09ESUR6NmZqK0lGZG5Ib3BSL0hoNno4VXpkUUg0L015emFROFVkK2N1UldFQWlodjNCZ0FjajJjVEFMVi9aeldIQ0R3R2loK2FWdzVBNFFRdWp5REtiTW4vTHdKZ3FRSEloSTkxT0loLzJlTml4YTIyQnZnOEg1NTduVWhYZ1dkamtiRzVHL2V0cndSQXpBRy9Id0M3YklDeE00aWJVYXN5a0FNRW5jSWtBSmlXdzVDcGZnazJCUllBK0FYNmVHSml5aXZyM1QvL0p3SDRQTXRMK2Y2ZWxPSS9pd1dYZXJQQVFqS2ZuNmZCNHVGaDFCMU1XZUM1Y0NsR215UTlmaW9BUHE3eEF0OWtFQWliQUxHUFh4QXdueGxXVThzMmFNeDNza3FZQ3dDME0rZ3ZBWUJyNTVQTXN1UmZuOHVmaSt4WFhRM0FDSGd2TGtCeElRcC9LRG13cW9Ocy9aWWY3WFFWQU85bEZQQ25BR0FORXdCUGRRQzQzZ2NEdHk0QTdxY3pWcFlZbWdKc0JoQUEyRnZFQUJTZnliaDhYdXhTY2E5ejZjaXJ5aTdyU2NuL0lnRFlXMDlLUHZ4bytVa2Q3VW9BampJR29BRTRBZ0RFd3Uxc2hwUGl2UURZRndqVkNZU0JvRzhINEZuVXBiNEpBUHhqbnhjeEF5QVhBSHlDSzZzZnFRMkFlaXRIZ0FsSlB5SmtkZzBBYWZGZFA4OFExWjhGUUJrSU1nRUFCY0JjU1NCY2FtTTFjVE8rbDl6NWhnQ0FKb0ZVKytJdDhOd0VBT1dsbUJlNFFnQktCc0JmbHdDZzNzOU52dFFscFFMSVB6NnVtUUpDQldBQ0VJdjBUZXFzWVNoc1RBR2dML1k4UHNDa1VITnY0RjhLUUNsek9NNjFKd0dsRStBNlduNGRBUG5wODBjRElCTkNhQk5nelVOb0FLWlRKbVA3ZXhtN0hTaW5rQURBZW44SlFIR1pWcXcxa0J1QVMrVHZCa0FGYno4K0xpY2dQNTAvRFJmQU5nSGtXWHNCbUlNcDlYUzJNZ0hBQzhMR05QQldBSWdiKzdsYzhmMjlBRkJDTzE4a2Yyd0RiSncrcnBILzIrbjBhWGlyUHdRQVVDdFFwNFJwQUp5VFA3TXB5TE9SR1NUOE9pUkxROXhJL0krelIwMEl2Z2ptQmVFUHJYWUFnRE1wc0FzQklISGlOKzAxOHMvVjFLUStBTTZoQVZDWGllVUV2aHlkQUJBVlFwVGQrV01CSUFtNFRBRW9BSXlqbFRLN1J2NXZRUDQvQmdBelZaQWxoQ1FhZ09FOWJ1Wko5QTNHWWVBZ0FEQUVjTzBZYkF2SFowbWUrbndyTmpMbjFHMTdtUUpRa1FCOHRQTk5BUGc0WVpoQUhJaEhuT1FtcmtzQlVNTUNBTmNKTkNxRS9Oa0FMQThNZ05JSW5HOERnS1VDdE1pdThnQnl0d0w0R1FBWVc4TzYvVzdYREFVYkFHalp6V1p3NFJhbWhSSkRWRVRTTUlBS1labzM5emxQU2dEWU5CQ3FBQ1MxMDhVQTRLTnBpVjNsQTM2UUN1Q0lBRGhzVml2bzBka1lsRG40OWtSUXZYRytWbDNEVUpVd1o2bFlOd0RkcndRQWFvTnJBRWdOQWtyQlhRb0FJcUFjUVA0ZkZ5NEM1bWRNRTFRQTN3OUFPUXZncllQWk5jMTQzVTF5TXdpeFRLa0JvTHc4UStrcnJhNWVUUGJOb0xTZGNkNnMwYkVFSU1kQ1V3RDgrblVwQVRlV1A1b0JhQU9BQVRnY0Rrb21FQUY0M2tSSTJKdzFyL1o3dVRuVXFCT0krNGYrTFFCSU45QW00SHloK0JVQ2x2aWwvQzlWQUliOGZ3NEFPRVN3MmFraVVaa3dBZWFHMEhKRG92YmVIaC9sb284MDY0OXlpUFJPR1NMU0FIZ3puZlJIaWQ4VUhmcHpNQUE3WlFNTUF0aGl6cTlmdHlFQXkvL2ppaEFRY0FDMEJWQXVRQ0grd3hhYUFGY296TGtncEp6QU9OR0xRVmxhbFJadUFuRFFHc0FMQUx6NzFiY1FBTUFsL2dzQTBNMmhRUUVhYW1iQUFZalREQklBM0xkckFGQ2VBQmo1TlFCSUEvQzdBSWczWlptNExMQk9vRjRQVXROQWJnS0c1UFp3d3hMQWIyQW5jNVVBak85aE9XeXEvbFBaSFZnMzFHUmpPbFVmaVUwQml3WHY1Tm9WUUVBUmNGc0FQbTZtQUdvQW9LNXNEZkhQWnJ0RUFaRExiWWRrS1pBZkMwQzU2YWNjK2lOcEFBUUJPU2JndGdCOGZIeGNwd0ErU1FYd3JRRG9KQUVIQUwyK0NZQlZIMFlyWmZWRkZ3dGdFc29tQ0hMbnAzQU03bEUzWVdMSHAyZ0dvdmQvZ3BKMHhxblBSVDBMUUlCRzRQTjhGUUFmT1NuK1MrVC80VElBdGcrNG9RR3dNVUQzQTM0cE13RXZzZ2hkVmxhSnNtUWRBTUNnTmdDekdRTEFYTzRYRHdRQm9MdEJEd2JhR0l6dDFZQTRTWkFWMEhIaHF3RDRjSTFyNVU4cWdHOEJnRjROWms1Z0NqU0FUL3c0WENOaUVXcFc1d0xnMGM1dTFycS9iQUdnQ2dHV0NFalRNSnBNSmtnRHpHWHNHaEpRV29HZkFjREhDVGtBWjFNQmxBQVU0aGNBd0VtZ3l3MjBBRUNoNE4xRENZRHVHMmNZKzBvQWpoeUErMjhCQUEvZURZNlBpUVhBWEtnc1pBV1VEdmdLK1g5Y0xIOUNBZnhNQUxZSUFFZWgyQ0FBeWtaSWJBcXZBZ1EwQUhyRFB3ZWcyeFVOZ05odkhJR0JuaGVNMFhLUVVBR3AzTTJpQ1dBMjRQVDJBd0FvY3dvSitac213QUpBUzljS0FMa0FtTm9BSkZ1cU40UXJKM0MzZ3dBTXhoVlZ3bXgzRkVTdFFPQnZDcFBkalpwREkyRDhSZnNuMmYrQkQ3SFBFL2dDRTd3aXlGY3ZoQTRBazRFcm5ZQmJHb0N6eXdEWUFHdzI2ajZGQy93Vit3TE1rTUY4OTkrT3RZNVZWU2lUdzliYUd2UjFBTUJvWFNBQWhQclh1L0s2b2hGTU9TOGdBU2o5Z0V6SEE2NnpBVGZUQU1vQkpCVkFPUW40RWdEeUdnQm8yN0F0VEVEaUJzQkN3UHdtT0krdFhPekRtOTFNNnkvcmZsSU5tbVVuSU9FSmNDMkFIRUdSeUNRSVVPbk1wUW80ZjRIOFA2NkpBRGdWUUNiV0FnOEhBQUNXcjNkbkVIWVZHQUFQTUNmd1N3RVlqMzBBeU5MUDBpRzQ5d0hBN243US9ja0RnUHh3QXdBY0VSSXE0UFFGQUh6VVRBS3dEY0R2QU9DbEJnQndoUWpHQVJ3QXlIVkJ1SDZuaEsxMnRKZ1FQT0tTRnpxM0NKVDhBNjBaV2UrbnRxekxCd25vQ1ROUThvZDF3RTU2Z2tlMU9IeUZDdmlvR0pkbGdaV3JTa2orTUJzQUFZQ2RRRG83Z0Z3bW5hL1g4Uk1OZ000Sy9ya0FzSXJjVGR5b3BkeW43UVVBUklTdXRRRlhBeURMeVg1ODVGRCtyaW5BdHdLZ013RlVSdENoQ2dEdXVaYzU2Z0FBMjFsaHFrc20rOUt4ZjF6VXBXeitZblJxS1FsQWNVRTQrK1JtQU1ZRDVFVHdNZ0NZN0lRQ3Y0U0FYa3MwSEduMVBnZ0hBTWNBU2hkUUJBTEZXc0I4SHJnaVNEL01LNFJRQUpCeEFCc0E3eXpBQW1CVS9uNDFBTHo0TysvOWhQcDB0R1NwamtvQVZyRnFlbm4wVFFSWml4ajFxME1CVkFMZ1lRQzFtL2t2eUFBb0FMWUZBTXZseTgwQlNId0FHT3ZFUXBVcUFNemR3VVMram9yTndlbUtEUFkvUDBMOUJMZTJtS1gvVmV5SHRYNW80R0x0ckhHTHFOYlNsWk5CQ2NGb3JCR1E1NFdNZ0xJQnFHT0lOTXhRMGx6TzRPa0FDK0FoWUdKMG0yb2JlWUNrQnlnQllGUHdZaUw0OG1MdURLU2s3Q0dqQUtDc0ZYeTAyOGI5WEFCNDZ3Kzc5MHVUTmUwakFCZzVBRWh0QUlSY3VhaUZnUllHUlJiKy9qQUErTGdjZ0Y0VE5wcmlmNXdjTXdBYmdQamJBQUE1NDZ0eWU3QjdHdWpJMk1NQXdCcEJNNW4vOThqKzFUdU5RQXlnTDZOL3N2Y1Q3dnpBT25WRW5hNmVCK2cwQVhBMUNpT3dXc2NnR0NBbWduQkdWc2lzMTI1aEY0TzEvNVlxb213dzllRlgvbTRBZWxENmlvQWMzditHQXBBQTZGMEJTd1pBeUs0QXAvakZ2b0FuYW5md2p3ZWdHeFZ1UDlIMG9jVlVBQW5BMk5oOHZ0c2VTZ0pNQUpqd0cvUm9SUlBWV1V6K2M1RUttUEJHWTJiRG1jYnBEUExLZmlnQXlnVlVzeW5MQklDa2ZCV0dtNHg4WHhBQ1VEN0k0c1M0K1pWcUFzaGovb04yMDlYM1l5akVqd0RnSzBQRktCT0V4TkpRSW9xY3lWQ0FiTzh3aVZ6Q0x6VkJUMW1Lai9DQkFXZ1ozY2FFQW11MDNmSkhBS2dkZkVGNWdNYThFQzRlc3NXZ0Z4TUFjMmZBendPZytLeWV1MUI3VjZXSkVBREFzUEI4dFFJRUZBQmtUSzZUTnU0Q2FmYURVMEdIM3RzdklOdTZBRXlhZEsraHh2d2tFNVh5SHc5QWNRUHBuVUhDQklqcEdscUdENGxHd0ZyZjZIeHc4N3N5RE53ZDlKODdvakF6TlRyM2szNVBaUWtaNllKNGVYaStPc2hNY1dVRHlvbVpMWHZsWkNnSVdoT0ZRS0FaZ0FpMEhhMUdtaTBSbXN4dCtjczRvRFFCb3BxWERnTFJKWUFxdzhIelhReHJCSEVBWk8wUnoycmdkd1BRSDQ3S3ppLzJhRWZ4Wk5nUEFJQTV3VXZ1QjhqQ0lXYzVNWE0yQWpNWWFFMms4T3NDOFBIbWJEYlZ6RTY1US80L0JRQlVMUnc3Z1o3VlAxUDgxTmQwN0FVd0UwSDZ3L0VxaVR3amZSNE45WUtROUIxaDdqZ3pMWExQMFVydWJHQmxmNlB5M20rMUtnaVFETFRleXZCQURRQStQbnJvRS9Rc3B2aHRncVJ2eWw5TkE4dmxZQ1R5ZVFVQWR1cWcyQmZnY0FKL0tnREQrMW1hZGp3QVpQRjR4RlNGRXdEaEVRZ0FSQVAwNGhxTUFtNStXdzlFTlJEUUwyUk5aVnQwdTZFZVpmNjFCL0FEQUFEcVFmY05yQWtBUFNjQmZlSE5YVUJ3T1dqTUduLzBlaTRFZXIxajlqd2U2WjZoZXVETkF5cFpuQkdRNzV0Qy9xM3dJUWhvVGtEd0lBUUM5dFB0d2tZOWovOG41UytUZ2plMkNaajdFYkJqeGc0QXpMcndWd0l3dXlVQW8vRTk2L3N3dFZxK3FEV0F5VFEvN2hmM0l5Y0FURFd3WS9IQVpIRU50bkVhdCt2ZC9pRDQzR2kwNndBZ3hxUWRBb0I5Ky84UUFQUzJBQjBJR21BQXJPM3AxTkl2bFJFRU5oQ3FTSkdSWlR5ZHg4VW5IaWFNZ0Y0SDlQeGcvL1o3MHlUTGoyazhtNDZHUTFNTFdINWhvUXVtRHc5eFI5ekxyZnFqS1QyQmp6cmkvemo1QU1qbFJqQmIvbWtxeGM4QTJKZ0FpQ2czWEI3MjFBblZLV0g3NUlBQWlISHYwSjhId0hpMlpnVWYwOGxrMExOSGY1SVU5dnlZSnF1bis1RURnRDRhZzlGclZGdjdtM1pnOHZGUkR3QStoYVV0V0g1Q3QzOW0zUDAvQjRBNVV4OG1BSEFKV0FBZ3AxNnFsMWR0QUl3K3BIZVBUN3ZDWkoveVpQbGdiZ29ZREhxVEYrYlA1Vm15bXQrUDRjd1JpRjRGQ3ZrdjNYNi9kZUhkRHdtSTZnSHc1bTFlZUxMQ3YxRCtNaHRnczFuUzJRRHplWTI2UWZNa3hnREkya056V0F2Q1VTanlXd0M0Znk0K2xnRndPaDZUaDBtNVdGY0luemQvZVVoeTFxMHJTM2VyKzVFSGdES250TnU5VHY0S2dhaU9EM0QrY01yL1BqdWZUekFIR0lzL1NjVDkveE1BMk9IbFlCYWVnWnRCUkVDb2RBbXhzTFdUQ0xmK1BzN0FjckFpQkZjZXZIOHV2SFplOXYrVVN3TDBlSGg0T0J4WnM1N0NDVWkyei9kc2V4RFMrYjFlSHpjTEs1eUk1clh5bDU1QTlQWVJ6TUQ1NUpqRDlLYnBTUUVnWlk3dmZRWEFWaS9ZUU5IanZZSkJBQmdtSUVFbWdGVnNBQlZDdmcyQTUyY0Z3UE5DMUh2a2x5bVRYWDhLMGZNR1FNVjlrWXBuamxrYUw0bzNqVXdBc1BoRlRsbnpXdmtyQWtKbkFzVlhUSi9KWm1NajFtenFYTGJ5aFVQZCtmTHVYODFuODI4QkFFNE9ZSjFBcG1RQkFXcHpuZ0dBU3ZuWFc4Vmc3Y0JIR2FoNFZPMS9OU0hxL2w4czlxa0E0SlAxZmpvVVFsKyt2RHdjM292L0hUZ2E3QWtCUURFVlpQc0NTTld2Q0dqZFJQNmFnREFBVHVjOE81ZzliQXQxTklpTE15dStmTEpMNG9OSVd4U1NqN0g0WDE1ZXRNTm5MRy9VTVFCOE1TZzl3QnBCb2d3NUJzRElDUHBXQU5aN0ZibjkvRHp4dGovdjdKcXcxajlKeWxiMmVjVW4xaDB5V2RFQXFMYXhyTk5UVk1vZjVKUmNUa0F2RUFDMjlGUVlzSW14cTZYWEg2ZkgweWw3NkxWVllMZ3dDdjNoMDdhNHpvZkRpeGliRGV0MFJxNnEvQllBWUpCUUFuQWtBTEIyQnpPNVVuVTlkY2VRc3YwVmJDT21sb2JsTGpJWXVpOEk0SFV0M3RWV1AzWWVvdVpienUraU9XL2pwSGFTbWNxL3VQLzQvZCs2MFdnR3p3YkYwbU4rZk8rQmZReHNqQTdNQThpemR6WkxsSXVEWXN0RDFCdk5Wdk9YbHhtWFBBVEEzdzdBazRXakFGQkZva29BZGl0ZElWVEorcnNCS005b3RsTEx0N0s4MzFuVU55cXJmWWl5cnptM0FYUG1namdCdUxIOCtkcEE4eTFFLzR0T00rZGp0bWFLcUMrbk1wUFJPa3U1Qi92K3p2NldTNXRneVNqcURPNllYeVBpb1NEbGd0cjZHdzVBWEI4QVdDY1FoSUlkOGgraC9RQ3V6U0NnQVI0SGdLeHdXWHdzV0w4SGhmNWgrVjhGUUxLYVRjdFZaQk1BWm5QYnQ1Uy8wQUd0dHlENWMxSlBXWGJnVTVmQ2tTMytQV1JINFFFeUFCZ1RZb1piTG5LWEZQVDUxSFlpazJ6MTBNdHN3UUN3YXVFMkFFU05rQjhGZ0t6NVhUWm5LZ0hRZjRjQTBJa2FOd2FBRVJBRnlWOTgxMU1LSnZsY2liRWVRYWRmNzdxenJmekdDb0kyVXpTTWdpNTNzQVlXQU82Vmxwc0JvSlNEQUVCM0RFR0xRU05ReDYwaU1kUlVYWEpibUc0M2hNUy9LcXQ5Z3Q1UG42andzNXhHRndEczVyTXluOXd5QVR3QWNGdjU4MDArYjFYeWgyMnFRUGJQU2ZXdUxIeURkNkVETkFDQWd6YTNOdHdlRk9mRkFtQ3FIc3Iwa3NGQ3dSZ0FsVzMyM1FBOHcyQUJEWUN6OTFNUUFPM2J5NS92UzZpNC9VdkxCY3FVY3dES0wvOUx0TE9kU0R0Z3F3S1ovY3lzUVhGYWNuM0xLSWhUQjRCRExRRGdVdUhXV0E0ZU9ZY1BBRmc3MU5nVkpyMUhFT2RZc1dxZlIxZnJueEFBaE52ZGp3TGszMjdyZjl0QkU4VkNxL1FxbEQvZmhZYmIxU0Z6OXVzWEpBRDNPTGVjZ25aSGJZUWREQWFHS1FpYkNPNzNNUUlBYnc5M3RJejVYZ0FTVVBMZDFhM3I2Tk1BL0pJMUF3SkFLdEU4SEFCR3dKdlArVGZLMUZPOTV0d0VBSk9nR1lqMFd0aHZCQUNWaURuS3hTRGJDUnlpMG9ISVJhRTZYU0lIVVFNQUVWanRSZVNKVkFGcVc1VXNlQlNyRmNIaEVKdUFibmZrTlFCQTZHMjFhaHNJUU12aEJ4SmRCUnowL2lvQlVNT0ZnV1NnTUFXaU9OSWxwbUJXM0ZDNGIrRDJjRkRMVE5yYyt3SEluQUNBMmlBNDgvY0dBTmdFZ0JaN1BnQzZuZTZvNnpVQU9qdWp1TGI5dXozckI3Mi82NkpaZVMwVmdHNS9ZOVpLZGE1Nko0YkJnRFlJVWd0MGV2M2VKUUFjYWdJQU9nYnRZQ2lZVjJoVXZRTE1ldUVTQWR3QW5BSUFtQXBJalpyZ0NnQlNzSi9QN05aek91ayt1RHNBQURJQy9idTI5LzR2NWQvZloyVkg2RHhiZEVQMFFMUFI5dDMrYXQrUHEzT1pFd0NLQW9GQVd5REF5bU1OaHBQUnFBNENzLzBtMmVaNitkRUN3Rm9PcmdrQWFobHpJd0IwMncvZDhlT01XbXo2QVJpTU9vMUc1ZjBmUmQzWERPelJ5Tkw5Zm4vWGlkb1ZFRFNialkrVHRmaGppSjl1Tm5XcUJNQ0VRQ29CamtCWkZPRXJBVUE5dzFCYU9BREFGRHp2M280YmdJdkNrSzdna0FRQXJBR0EvWHlKM3ROdFdWWGRaWjJkUytFRXF0V0FvYW9zeGlQV2QvYkdjaUJVSWY3T3E0ck5xSEhLRnVreEV3ajRwZzNOWm1Rdi81YmlON3FOV2IxbWZsVUM4RTRvQWU0TEtGZWd6SDRQQUdFZTc1Z0owQWtJU2F6RlQ2U0UyUUJJRGRCM0FpQmxhd0pnZXYyZVBIYWoxcWNDSUxjY0s5QmRTd0V3blV3TUFBYUR1eTVYQUcwM0FNWGRuN0xqbkV3dHpSNjhjeE1nSDIrU3hoKzFKWExRcTE3eC92WmVQU3dFb2k0L1E5MUVZeEtVRHdBQlNKSjROYThGUU9vSG9KU3REVUNGQmtDcmdCcUFXRVNDekpZUHB2elp1YXhKQUlhRFYrRUIrQURvc3F4RE1zemdKVUErM0ppY1VPVHZiSGVtZGZXYStxVUFDQ2NBR0lKMnA5L2xLa0FCZ0tiZmxFS2dBS2pTQUtoOVBBUmdNTEtGN3dFQTVnS1NBSmdCYlEwQUlrQmNTdFJaUXhUVCt3OEFvSFlXOS91ajhWM1R0QUJxdXEvTVA1TS8zUmFlWlNGazNjZ0RBSXZYdDA2RzhyY2EwNTZzZm5NbkRFQ1FEakFSRVBNQkFFRGxuS0FBSUZZWlFkeHhNbk1DaVk0aENJQzBMZ0NxU2RTbEFLZ3NOSU1BUS83Y21PMXNBQVlpQzd6WjhnTFF5ZkxjSlgrMmhwTjJJMy9rcUNuY1FLZjRZWk1SNUIyaUFrWHZkUkFRSzhnRkFYMVlJZEh3QTRnU01mRyszQmh5bEIxRFhBRGcvYUlpSFNDMlRjQ1lYdnlUQUR6cWF2Q1ZhMWNVQUx6OW8xbncvMlQyVlpBSjdxczVVM3dsQUdKTTl5MVFXOFl1TU5KcVJ3dWYvRGtCSFhvdVVCNWxZdHFtZ0VaVDVxczRBaUVnYUFTNEdXQ0JZWVk5MlRhRENBVEZMNmh0SEJJL3l3Z3Fad0UvQmdDcTd3dmFUNVc1QVJpTzVuY3lCdXdFb0ZBQW45NXhXZ3dpUHdEdDg2ZnQyMWNpWUwwaURBQ2dCWGpJc2pmOEdnQ29qVUV4OWdIRzQxb0FCRGM3MDF2WnVCT0FpbjBUbTZtVktwdHpHeUI2aTBrRXB0TzRSeXNBSFFDNFc1ejlBSHptSFRzcUNBL1ZicDQvYmMvT2o0Q2pDT1ZiWFhld0lHQm9KMk82S2dYTzhkN0E1R3NCRUQwZ1JEK0lLd0dRQkJ5cHZmUXF2WGs1ZnpFQkdFNVhhZFJvT1FFby91dTgzbFVvZ0dMczdyb21BZWhRelRjZDlBbnFOK2FwUTFyTEcyUU10Q01lUmtGRmNtOERBRFlDOWl4Z1BOTDV1MGFvSDBUODZDWkhRWHRhdVFuZzFCRUU2TDEwY2dmOXkrYUZseWZTRzh1SDQ4Y2s0OVZadUt3SkU5Q09YdlBqWi9XSTkzZ21ZQmlTWnUveWJzU0VEZ2pSQkJxQnFOMTdtWTZuUWFzQzh4M3NIR29CWUt3R1ZnSXcvazBBUUIyQVIxbE9uWmRRd0FBVU44VHpQazFiVGRvQmtET0FZeDRnLzgvVHZvdThBTk9UYUovUHQ1Qy9ya2RZeHhlSTJwUG44YVFtQUhrUUFJWWphQVNDaUNhdnF2REh2WnJ5SVlHSFZMbEZ0S3dBQUJRQnVwNStIQjhPTHp4OVdpOU4zait2aytPNjZSRi80UUJrcHhBQVB0ZDNrVEY1UkU1QTYzUytoZnpybVFLdEE2S0g2WVNPL0JqR1lCNmJBQkNOSTY4R1FQOXlKUUJ6RTRETWtyNHFvUkxIMjQwQndQM3pJczd5dmgrQWZSWWsvODlUditNR29IajgxemNBVUdMUWEvZlloUnlQZ2dBNDNBcUFrZFVMSGtWNWJiZHZObk1BWUJlK2tqN2dTcFo2TDQyQUhMaUVqdWlzdWl0d21lbmM2ZUpnVC8rbFdkNXhCUUZFRERETnd3RDQ3SFJkUHNCWEFDQWdDSTRMUkwwWERvQ1ZpV1UyRmxneFcra3VGLy9EQUpnYkFLU1pPY1R0N3dDQWJTdy81bEVGQUlIeS8zem8rQUJvdjUrK0U0QmViN2xpNWZkdkRBQjJBMVViUmc0QXkxRWVQZXR0ZmhBQlI0RWF1dTJwVmMxS3ZZeFY5NVVBeEFxQUZGTlFicU9OT1FBOERxRHYvNElmdHJHODdiVUE0UUFjSXlOK2dNZms1dkwvRlRZYmtOdEt0cXhFQnI3NFpPUEk0bXB0MGU3Z2c4Y0UvRXdBek9FR2dKVVdxUUNnazRVQ2NHcDVBWWkrRjRCSmt1MVhpOFh6clFGd1RnTjVGa0xwK0tsRzRJWUpxQjZrbWlvemdtRUFLa2tvQ3ZoVzZsalZ1V0VIaFBKUFdJNkhINEFvMUFYNFBMZXNHQ0lHNFBZRWhFWUdKNVBpeHpIZWljM2pYcHZMTnR0dVhWWENpTlhBSHdHQWFGYkZSUTB4WVA4SzhUc0JZTm1rZEFoSWlhMTlDZ1hncyswZDBlbDAraTRBMk1pT2FiTDVPZ0RZaThvQ0lRcUFzZHpSVTdZQjlwc0FiQVFJRWp3QTdFb2RJTVN1L3NQM1B3NTVGQzRyUy9ObysxUkFIUUFpUHdEbnIxQUJBb01nQVBJc1NWWnplNGFON1M0TmdDc1E5S01BNEZucE84MkJIQTRBZU50WVhsenF0d0Z3L2xZQWpua2h6dDBYQWJEYjZheGdhQUtrMEFNQThJaWVIamhEQ1JraEtIckJoVmxCVTN6NDhoQUFRQ3NQQjhCMUdINzgzbGNCSUhyV1ZOcUNveWlSNEw3Qk5BQzRUbUFoZmpzWVRKYUsvUkVBQ0RVQUJna0F0M1piNWdOV0FOQnVIb01CY0I2Rko1Vk12azREQkFFZ3QwZXV2Z1FBbzBZUTJ4cldIMmtBNW5QQ0NUU2xTWCtuc3ZLUml4Q0VBQlQrcmh5RS9aK3lPV1FTQk1CZDhDeWcwZlpvZ09qaDYzeUFnUGp3citPSmgzYmpGWG5YYVZmYm5nYkdLaVZNMzNVL0dnQlRHM2dBRU5YRkloOEFyV1k3T0E3Z0IrRDlXd0ZnSXVVYlpHUFFXT1k2QUhSZEVCVXFWTTMzT0FBRERnQnpBbGtPZ1JaL3VUUU14VDZmdTFxZWdnOTFzVEpmZ2UycnlodlJNSmlsMDhBY1FBRFE4UURBVnZMUGVLdmgyVkdINEhQYjhQcUE3K2ZUbHhQZ2xQOWJyalpJcWh4Zmx6Tm9oWUkxQUlZSmdHMWp2eFVBcEFYVWQ5SFRoRW9BRmo2NXRWcU5rdzBBaVVEVThnTHc2enNCK0NXcVpYSUM5amNCQU5lT05icUhjeE13NE5OQUxub05nS3p2eTB2K0VFSldXc21VT1BqQ05DZkcxNE1QMHAwSVpuSkxXUUhBc1FLQUxnVUFzWmZiSy85MjUvUWJBSERPQ0grcDZtbVo4T3BjZDVzSEFIeVp2d2dBL0VHMUFKaE5aN1VCRU9YbDhpanlBZEJzbkNqNVd3UWNtMTRGMFA5T0FJNUhYU2NsVlh1OWJnT0FVU1ZJZEEwN2d1VmdrZThwbW4vQWVwK0VHMmpmdytVekloY1JGNzZrMm1PUlVVNmlMTmJ6UXRVV0ttNk5UZ1VBUFJvQWd3QmZXbGtCd09MOGV3Q3cvY0JmdjBRQkpRMkE5dXJzeXpZM080YXcvVFN3TnNBZkJ3QlpGdzBCMEs4QW9IRW01WThCMkRlOEFIVFM4L244dXdCQUJQeVNkUk5Ba284ZmdPMmhEZ0Q2WWVtRW13Q29IV0JxeHhjUkNKb1Rnd1RBMXdBRHlOelhOOXNBZ044Yis4Z2pmMFpBVkEzQXVkSDBhNEQ4L0Z0VWdBVUFsNzh1bGNVSjRGN0FhajV6QUdCcGdHb244SWNBRURoTUFMeE9RSnNWZUVoSkFDQUJiVDhBVVhUNi9BNEFmbW41bHdDSVZOOWJBWUNyeU1xV2E4b0pITWtLZjBvbnM2M2RaWGFvVC95bXkwSFNRUWhXWmFEcjNhaTRQYkQ4OTVGMUIxUW1vSERPdkFEd2x2RTVKWDhBd0xCS0FkeWRQMytEQ1REM0RDajVJd0RZUXZrT3RCbkd3V0RLQjFnUkNTRVhBYUJxUVhGTmNITUErT1FDRnlRdyswT1gveUlBemdQL09oNGo0T1FsSUcwMC9UNWdKLzg4LzFZQWZyMlZaU2RndGJ5ODNDaDlMUUJhOGFOVkdUME4xSXRCV3Ric0k4cHVBQlFBT3A3am0rV1RSbUJjQURBZUV5V0o3TUlvUEhxb3ZpZ0RJUE1EMEdZVlg2a0tMcW9ZOVZxVUdLeFNBRjl2QW1RUCsxL3lIN1lYQ1pkTHBOWjRNUVNyQk8wTUFuM0o1ejhiZ0pIYy9EYUN6VURweWpnR0FCV1JBQkVOYWpReUZ3RG5mcVBwbndKRTNlTnZCZ0RkL3RKL09TRW5RS2Y1WEFlQURyZGFTYUdGRFBqZVR6ME5mRVQxSUJ6eVZlb0dyVm5wS1NCZXdGRGx3MEFsU3JNeHFHb01qQW9ONjdMbVhBWGNWUUhBbWo5MGFBTE9yTWg0UlJEZzlmVDVtMHpBTDJuN3hlMS8va1FBUUJVUXh6RE5RMS9SQW9ENGhnRG96VDlsQjVpcU9HNXRBR0FyNlNIdUFxa2g4QUJRU0RIdmhCRFF6TTZtSi9CNVByWXE1ZC91Wjc5SEFmRGNFQ0YvS0g1WU1GSFYvUWdINExCMUFvRE5nTnlpa2NycnFnQ0FnU0I3THdpcDN3MEFkUGlIV3NLWWxxcC93T3QvbWlXQVpZRVV0VGw2S2h0RXE3b2lYQU44bnJ1ZENnQmtTOWpjQU9EWUZ2MkYvY2xnci9ubjd3T2czR051VkV6RkFGaXpPNTBTZGprQXUyOEdRSlQ5c25ySGdnbzVDb0FWQnVEOHljczh0U3ZpUWJ5ZmJPZFlWdkU1bGkwR0svS0JoeWRROXZmcnh3bmYvcC9ucndIQWZCQTBEV01tZ0YveXN0Sy95Z2NUN1lBcUVUQjhrem5wcjNMaFM4dlArMEwzalNaUWZIU1pEbUNtUVJvQ2tRNXFBbkR1ZDlwVk9vQzdncnFuZExQOG8xMGgvMjczL0hrTzF3QWZ5cFc3WFBxb290bVpBRURhZGlQWlJxYUU0VXFoWW1zWWpzU1ZhZUdWQUFqaHc3MUJ0d1ZBOTZRYjlEa0EzVUxrWGRFQlNBTFFMWDBCRHdCVktxQU4yd0tEd1ZwMVZNbC9PTXpMVGphVnd1Zmo3YVA0NVhMcEd3WHRmaDhBTWlrME02YUJlRHlhcWFEK2FNOE1yK3lhTmFTMDg5Y1RYV0E3M1U3VWtyM2YyNUhXQVgxVnMwNmJBSkVQSUZ1TlZLcUFkc3Rnb0ZrMkdQU1B6bjZ2dXo5VUM3OVFBSk5lYjNLSkRyRExEZHZ5MXdCd045QmNGQklwWVV0N2F4Z0VBSFFPL1ZZQVpnQUFyZjRqZUpNV0NFU3lJVWpmRFVDUUN0QVFORjJWZ09oRmdOZjBCTnNYK1FCNGUvdDRpNlNoYVVXVDJuZS9xK2VBcWsxVkFzQW5ndFNxNEhVQXJFSUFtSDJGQmhEeTczUkU1L2VHMXRUTmRzY1BRTmxyNXR3TkljQlRDY3doLzd2ajBTZ0E3cFIvY2ZPM29YMXBUZW9JMzFMOW4wYlJkRU1ESkVtUUJrZ2RBTUFrTHMxQWJBT2daZ0RNRDNpY0diSjFpZDZac0lMWC9WanRNOTM5b1ZEMnZQRVhISVVTa0FUd3FvVUtBSllUakNKQlBCWVFSRUE3VFBKbElsQjJWTTBMei9wdWRCaUFOOVBGaUlKOWZtZkxHVmgzdEN5YnFWdkNyc3p1MHZNWVpnV0w4bm83MkJiQVdBejZDUUNJMHYvZFFvQzY3WWV3ejRBQU53QktCZHpkZGRzM0hyekdNSlZPWkRIQW1vcTh0WlJuS2VFdHZ2eGJwZkRQdXZXWVUvNEdBTEwyeTQwQUFLS1U4VFd3TTBpc0F6eVgrd09NdDlsWkJYTlB1dHJNWEFOZzVTOUZKMmh1QWFLbTNmYUR0VzZVZmJSQWxUeVJFNGlhRFRFLzhMWFQ5bTRWcmcvQVBzL0pmTkt6NFEwdzh6OWgzOWJRWDQxMmxjMC91NlNQUHRRR1FLd0k2Y3Z1emduY2tVMmp2QUFjdndXQUxpdjUyMGFkdlRnQnpVNHhSV1ROVS9oRWNBcUR3Um0wQVovNTNWMTBXdzNReVhKSE9wbXBCajQrSm9iMEpRRVRSeUZKL3g0RjZ2NC93Y3FwMmJVQW1PK1ViaUFDWURCeHpPWDV6N2xuVkpjTWtFT3UvVEFBQnF6bU54bkdqKzdrMGxCWkowOXNKekVCK016aTBVMEppRjZQWjBzVURnWStlT1A2SnVvOXpRaG8vVHJaVldTclpPKzgveEVBbklBZ0FDQUNaY3VZSHdVQW0raTNtaTZ2YlRpZTBBQ2tSc2ZCTk83Y2tJRG9Mc3VoS0N3QndrZmZtbzYyaGU5bnE4VllsZXdOblhQNkdnRHdESUkwQVJOeUttZUUrQU9tZ0M0QW1CTW9GMzc3NDQ0ekw3L1ZXZk1LNGFwN0Z0OUNBSnJPNm41emhTTjRNd0pZbDVuc2JFN0ZLUVQ0aDBjT0FIaUZ5U0NWWHlGL0F3Q3orSWNUZ05nQUFQVUwrQ0VBc0puQWZkUnFpN3lPeUJqdFZyVG5pd1lUQWdCREJad1creHNSRUhYdTR2U00xMkxjQ0h5ZW5TM0xtdS9CWXFlM01HRUE4cm9BSkc0QTdNb3hLemdMR0kzTXdwOGU3ODZjQmxaVUROQ0JJTjRuZXpJYXY5cVNMd2xvNzFkMlR0QmNBNkM5Z005VHZMZ0pBY1h0Zjh6T254NEFNQVJQWlhqQmFGalNFa25wRjR1ZmtqOEFZR1hleVR0ZUllU01JNEc2VGxnNURmeGFBRmhPV0RBQXJCWFdlTDEzeXI4WVNmcFNBVUJKUUw1NHZRRUJ2TW5ZMlZpTlp3TTFqZ1lRdUt1TE5KdVhDOStXL3hjQUFFSUVLQTVRaUdZYVd2YWp0ak1JY3dIWXpPNCtTVDN5ajdKc081K2lBaUZtS0VqSDB2TEY5WDVBbGZ4TkNFNm50bWVIK3VYU0I0ckhhS0FnRndUam5abUF0VE5yQlBGWDdieTFncjhmZ05raXpYUWZkV04wT3YzalVYWUxNUUNnVk1CblBycnJSTkYxOG8rUCtkbEl4ekxFYjJBZ0RCaDJJdFc0VFBTay9HOE5nSzRTZ0RLQ1ZEN0FkTzdiMFZ1NUhCUThIWHljSjFuK05PbVZFaGZoZjlFNnJkZWJKSG1lSUFKRVRZSDRZS29BVmZkNzhkcU5ybkgvOThlam1ZOUppNzlFSUhKYXNNN3dldkdmY2dvQXNTUnNPSUs3NG5GemR6QlJKdXhuQWNCclBxY1BQU0I0TUNiSjhaVHpUZEVPQUk3WUJoUlhkSkZlN2doRW5WSHAvMEVGOFBIaEkyRGlORi9EcEw3a25mTC9PZ0JBaVNBVEFJZE1yZjEvSVJ6Z1RZVmxrd3RlOERHWjlNaXhPWjdPT2ErT013ZkpTTVdYM2g0c0c2QUlTT1A5aFRvZ3VtTkkyZkwzQTNCKzY5QVdyTlBiWk9mNnNxK1V2eXlqcmlmNTZscnYwaVJOeXI2QmFocjRvd0VvcHE2ODJsZDJnTGQ5TVZpSW9QZ3R6YzluVVNKdGhqNWVBWkRaS29DNWd1bGRiVWVBQ2V5VkhleXpqdnc1QUtmSnVLY05HQmlGL2FvdmV6enJ6TDhDQUt0RW42b1RtSUtjd0dtSVZpZVdsZW1OZ25ZOUFLbkxZMWJ5OTNRNlpoUFdzbndpZzc1eVBLVkhYaDVGZEkrZkcyR3JCRGFlUmdTYzAzM2hDRVExdGY5cmxzTWVrK2RnQU03dmhRS2pETmlENkZoenJqY3E1Wi9wU3RvSFBqWWJjYTFqOXJpY0JzcWtRTGhtaEphRGZ3UUFZbEduRU9INWRFd21lRHc4UEx3WFQvR2RzVXdGN0FNQTBOSXJsRUJjYTBZWTlWbmhVU29mM3l2L0Q3NmdlOG8ycEFGTGorZTY4aWU2NS80T0FHU0p6aG9BME5LbWVsU0JIQkdydE1CT0x1c1hodjc0L3Y3d3hNWURIMCtIdy90UmxVZFI1WkhLWm1QQ1lxWEtDU0FJT0JkUFpZRUlNRzk5enorTWxMOEpBTi9CaXdBNEg3TUhucmVpakJjM1lJTURWd0NYaTU4QzRFZ0JjRGlJeWVBT0FWRG1CRUo1L3l3QVpEeVBSM056aHNEN2V5SDN3OHRMOFpNVnlKWDFVY29lYUNRQXRBb29Mbnp4VEJhUHFoZ29MSGYzTHVNVWZWTDdNU29CRUNyZ1VPaXN5V1Jhb0Z2cXNBUFBLTHRjL0VRWHpSc0N3QjdhRkdNSkFDaW5nV294Q0ZiMzhSaUFBRk5nTzRMRlkzTzFxTXZ2SWxrTWtWRWdPT1Naa21kWkkwOVV4dEFtUU5RelNWVzdTWXFBejBLdDVIbkd2SUhJTSsrL1M0WDR6NEh5SjN5QUFqYVdnLy8wOVBKY0FGQkE4UEx5OEpCa2FUMEZFSEQ3dzE1cXBSdklocmpHekFrOHdON0JJbm5ZN0JINW93Q1FlenpabFRySmtxaDZidmVwNnVPb0Nta1dBSllYWU95cktONVp2SGR4UjBGUWFQNytJaE1YbU5xT0VTTC9EN2tZZWM0NHZJY3RzMTVMM3ZqZ2VLempBZnFrZnlFQVlocEFBYUIrc1FCSURBQ3NWSEFxREVUdkVIUldCWUVWUW5leGNnSEUyaXRZWkFIbE1VNjZDMTc1YVJvQTB3c3dKOTdubko5U0ZpL3UrbUxiRVordWRmdjl1MzNHMzJlMWwwY3lDWkgvV1dxYm8xSmcvTFRPZ1JNL2NxM1JyZjhCQUhLNXQvVHpDQUJpSXlIa0p3Snd6RUV4QkZPUW9qYUNEd0NMQUN2MkFvT3A0dktKaE5MY1V2MUVEbEFnQU1Xbm5MZ0NLenNnTytWL3FocU91eDhwZ0pzQVlMVnJnRm5CaytwRklGOHcyS2cvQkt2YTY4N0JPclB2aktzNjQ5MFlzam9PNnlEOThxTHFHWlhBYWlOd2NpZmVjQ2RUY2lLdThJbVV2cFVDOEZFSmdGNkk0R1VjeW1SdlIrU25ydmp6STNuL2k0YktmT3NmdTQvZEFNUi9DZ0JuVjhUOEpIMkFDZ0FxQ0NqMWk3ekNWZm5ZWWZMSEFFZ2poa0pTOVlSdlNUKzN1K2xtNnU2L1BRQXhEUUQyOVR5TFFYckNVUkZFVWkvYmdVb2ZydTBSd0tjOWJEUUFzdDFjUFFMQzErVUQ1Zi9oMmRsRGJlKzUvTzYzZ2tDSmFLZ3FBUkNYWEV3REhTWkFPNEkvRVFDSENqaFhBNENOUU0zOHkydmwvM0U2T2ZaMTFoZS85K1kvbXUxVWJ3d0FkeVdTMGdTb2ppSG1nckJuTXVnTkJWRUZCRlZSR3B6ZGIxOUFBRUM4Rlc4dE1DaE9lV2NDa09OY3ZjdkZIeTUvdHdvNDF3RWdwd1loZmd6QWJpTUV0eTFHSWNPWmJRTDRIdElnRS9EOUFKd2N1Nk5QRUlDZEc0Q3JDU0JNZFNnQUozSm52eitsMUM5OCt2NVBzeFFCQUhyclhBTkEyYXNyTWJhR2FRQzhEWUxjOHZiQWdOdVVHVms5Vm5rc0VkamtQWE1rQUM4dkxJbVZHUzJvQWk1R2dQYlVnZ0d3Q05DN0NFbjVxKythdThlUkFnREtYM2ZXQWhsK2lRa0FNUW44UVFBa2VqM0hqdU9jVVgwOEZ3Q3k3L3pSUWNENUNnQStQbW9DWUs0a3EvSnlZWGU4VS9ndUFIYTNBcUJzMlZZRzF0aGlFSzhTRnRRaTJGejFxUzRmUHRjTlk2WFJzZU00VVA0bUFJd0E3Z2FXWDlxcEEwSVJzTVVmQ01DSFRWeDVxUFBudVpiZ2FmRmo4NS9xenBvN0l5RUVkZzhIQUFUNkFDc1RnTW5zTndBQVFubjJsaXNNUUFZQUtIV0lEQWY2ZEVBWUFwZG9mNVFaVEFkOHpsY0szd1lndVFVQWpzVmdCTUJvT2dzU1ArZ1BHTElZQktKRWNRdytraVlBRjhaSVpKMXNDSUJvZFFZZFFZS0FFQWdNWmYxUmx3QVNnTGY4Y3ExUCtmOEpLWDQzQURKejFOb2NTZ0VRZnlzQVppd1hsY1lCaFZFOEFHUTZETzhRaVIrQUM4WHZVQUZ5MTNBdlArV25pd1JQM3YrM0FvRDBBQ0FBdkNMTG82NFVIbWdHQWxMRGdCc0lscCtBNE9pNkdHbzNGSElyVjV2RFlhdW1Fa2dINURRQlhod3VGRC9ZSldUSy8rUGpyZGZMYnlKK0xYK2lzVEs0SW9sek1ValhjUTRHWU9GWkNid0ZBQ3NybWc5dVhWd1hJd01LQUFOd09PQ0FvRjhIK0VBNFh5aCtZck5nZWFDM3QyaHlvZWlCOFAwQXdFdHlLUURDSXpOTUFBVEF1OC9ETmVsRDhyYlpFQlBCaFBUZ3pMSW9tZHJyTE5vUklBQ0FJMmdmcHc0Q0YwcmYyaWtJRk1uYjJ5UktUdGNJM3RML1JuZHRkaFgxTlhhSGdxdTZoMzhYQUhIaWtCd3Vpb0FCbU5NQVVMUEJNQVJLRmZEeGNVTUNSUGJnSkRxcTg2aWo4aTBBdFBFM0FBRGxYaDdEQWNDT2dRNEVaY0FKbk92R0VKNjlYbWJuQWQwa3JHTEx5S3AwQWpBQk9FUUdpNklrcGRjRGM5cmdVU2dDUWlDNG1nQmEvcHlBS0FvMDl5N3hwNGI0ZDNCZ0o5Q3pHQVFsMUtCYXRkc0ErT3FEM0JZQWk0Q2MyaENmUU1kWEo3cUtZSUE2REUzQUtjd0kzRklIbFBuRGsvWWtCSURNZmZNYkJxQzhDQmdBdFRmd1R3YmdTTW0vVElMd0FDRDlRUHRBdFhYQXh4WERua2U4Q1FJU2Q0eEhuaDhOQUR1Zkx3RkFlUThZQVpHa1gwWUNwMFk3Y0U4WllGeUhEaGNuOTRtZkN3NFJnQmxBV1JBU0FHdDlBUjBwczYxSm9CYTRXZ1Z3QkJnRjVnNkN0NmlkVlFUNXZQZSs2ZjhEQVBTRkY3TGFzdGVXZXdOUlJoRGFHZlJqQU5ncEFBQUJqaVNZQ2dDVUdjZ3lseEtBK2NZbk53RWZOeDFDQlVROVMvN2lTMVlLdmdZQWJHelRwQVlBYUNWQTV3U3lLOGRNd016c0FlL2VIYlJhVVZXSEtoWUYrWmRBeWp0ekFKQnFBSXdzUTVWZExLY3hLQ1RrUkFDaVlCbUJyd0NnTUFLWjFtYitPejkxaVI4NWdPWWtUbG5jSGRBQVdtM2FMV09DQUpqK2ZnQU1CTXhGRUJzQVhtQUE2QUZUbTFRZ1FDd2EzVmdGQ0FDZTJFeEFBNURWbEg4WUFEZ2xMQndBdG4xYy9tb0NnTyt4eXdHbzlBTEFMSzRVbnIwR0ZrTUFiRjlVcnk4U2RpRDNaK1VBQXI0RWdFbTdsd2RZZmJmNko2YUEySk9IdTROUmhSQjExVkNWc0I4SkFHVEF1aVFWQURBOUlBMkJwc255S2FzUnVMa0trTTJBSjcxaUp2RERBQ0F5UlVvQXlqcUJ0aE5JVGdKUk9Eb1VCTEFFVVJLUXVzWFBrbURGcWN4Z08ydFVQcERYRHRySHlCazBaNVorQmhnQk54Yy85d1BieDl3ZjZ5UEZENWYvREJlUU1nSk9BSXpWd0Q4REFQTXlWQUFndTBxcXpCWmFDZmd4dUxVYkFCckNUMXE5SERzMjVxbDY3LzRyQU5pUkFKU09YL2wwbVJVc2N3TExRRkR0R2dFR0VqUVBlZ21pUEVYejVLa2srSjBHQUZZZFp2L3huOXdXQUR0QUJCZDhHS2hOZnJjV1B6Y0NhWTZtdFRES2svcUZqOVgvaWg1bWhSQzVnaDRUTC90REFCQVhRZjFIQXNCNmlMQnlrOVBSaEpXZTV4Uzg3TmI3NUlEVFJFSVp1TEVqaUFnb1pnS2hBS2hyOFdVQWdLbWZQdURPeUFyRytVQmtwYkRnL1FCdUFNVDhIYm1DdEFPa2drRHcvcGR0cDBlakNXc3NPT2oxKzZQWDE1ZW4xWHJ6WCtrSzZGbGxWVmFXSnVCc2xnRzVpUTVvTDNOZDVZOFdmS3J2QlZyNTg2dTJXQ3k4QU1DZVFjbHVoZmNGL1VRQWpMbUFld1pNQUNDYmpnKzZVYnZKMnJhMG8rSHk2VW5rRENjNExsVE5RRW5BU1hRQWJMYWl0NXNCOEJTMU05WHhwd29BZWM1ZkJvQVpCQWIxQVhSR2tGSE9xU3E5QnpwL2xaTkMvWDNLS0xRQUFDby9Jd1VpVnVwZjIvNlI2RG5TNjNkaHk3NTIvNG5GaDhyYXh6aStGSUpBRGc3WGVydVZCcGkwQjhjc0N3TUFxRVdKUC9EbUtRRHNLbUdnY1NTc0NQbWpBZERlZ09rQWVRQW9GSDlrdE95THhxUHB3d3RNRTdCanpHNEc4alkrV3U4MkFMeTk5ZHJaOFdJQVFPai9lZ0FjZXdOanRWV1Btd0NWRVNTcWhGaXJ1N2hybUYySHhvQUE4NEZLbEFKUEFITUFMb1UyQU5EN0x3RG85enJzOWplNmRiWDZvOG5UNXBDa0NSMWtQcnF6RC9LeGRiVDIyNDJtZ3RIZ2FJWjdrQWVzejFvbU8vSWgzZDhkY1Z1WkQ1Z213TmdkN0UwSit4a0FzTHYyVUFPQVFhL1hhZUdHZzRLQTBiUUE0SkRBVEpITXRlS0kwbko2cXZzak9GcjdObWFnTUFMWjhjOEFZRGpDQUhqeU82QnE4UUpBT1lFZ0lWRlpPaVkxclFtVThPT2RYdlhVQUxDMnc1MjIxWENTeSt6KzRZVmR3NlNjRDRZZ2tCMGZrUGdWQWRHdHBvSTk1WnQ1aHhDNnZpSUtnRXJYbWdnRTdXeFovRVVBREZuRGNkUndzRVNnc3lnQlNNd1lvenNySzIwMTdBYW14V052dC9FRGhCZndZd0ZJU2llUUFhQThRQTFBWldGd0U0SFFsd29BZGx0VDhhbGh0TWVTTWFEeGlNMEIyazJpUFRScjJqU2VyMkoreElNQkFNKy9KQk5QM3JOZWsyeisxb3B1TkJPSUpybTF5UThyZm52Z1FtQkdCV2I0Mk12TG9hd1BBTnJHMlpMNGV3Q1kzSGRhN1lodTF0TlpLUUFPT3NLQVYyRHc0a3o2L3I1dG05cEUvZnAybTVsQUx5b2pBZDhQQUphQ1RnaGhGVUtHdW1lUXFoVklCSDJvY0JETTJ2YVFvSk1hOVFJbkFHQzNNd0hRZVUrNjQ5Qnd1b2hha2FNUWJMUmRyVW9BM091TllFRW1TWG90UnozWmR1OVdFNEhKa2Rqb2FTRnZuejI2aUxCdWd3a0FNZ0dxeWZqZkNjRDllUDdjZHJZYmJFMFRkVTJUaXB5REVvRElWVkM0M2I0UkFMMTJlc1E3UGI0WEFKWENLWmVEbFFub2dXbWdzeGdJMVVFY2k5OFpGU0tpVU9ZZitnSnNOcW9NRnVnMHdUbDRTTWJ1aHBPdGJscThWeUlGdFlBN0YyUGZvcXVKczhQZEtoYlFIdVF3SG14czk0dmoyTEhjUXl6SW1hNTVBVUJpQWtDWUFLTno2QjhNd0d5WkRkMGRKOXM5WHNIYkJnQXZPZlBhUzlJbFNGcnVEcWFUMnl3S1BERXY0SWNBSUo1UUFNeFhvRlp3M3dEQXBmR3RPUjQyTHZKdk94OFVibXNnZGpwQkFKandYOHJ5Z0FBQTFtN2tPUEUwbkJ5d1RqT0Y1SlY2TmVXdlF6TFNJOHd6VHdQVHllazJDNE9US00wTlJ4QnQ5NHQzN3RWZTR0NkRDWHZNQkpqVHdLb2FRWDh3QVBOVmt1Wnh4eHFxSEhqdmdSV1lSUURBNVNaTER4enpVKzZXZitmOXVrUWhNQkhvZVFGWXJYNHJBT0RBc0d1WWNBTE51aDZPWUpEcCtPa2E1TVMzVjFSd2YrOC90Q0JVZnRYbFpxTVVQMVA5Wm90c2tmdjFjamlrV1o3MWVoMnI0YUI0WUpLZGhBcVFPQ1Y0cGNFRWdOY3NuN2dhbVBhbVZ3SUFWY0JSbEQyVUFCd1M2Zmt5TjFpZE1RMEFLTmxHM1llRUU1anNWRXFvWEVWYS9GVUFGTi8wd2RGdnNEY3E1c084MTFCQ0F3QVJVQUNjM3lkTWdYU2tEdUdTNTBEMUh0TFRsZHZHZ0FyNER3TncrRTRBME1vTTdCY3dHRTBkNldDZW1JN0k5Q1FBc0NQRlRNYTdFZ2VNd0hJRGhxdGgyZnpBK3MzbDJSTXQvOGtoTzUwbEFCczl3VFFSZ05zSUNnQ09COGZSMHVQNTJuMkRZRTBJemdNa0FISWlYQVdBdkJMcVY4Z0ZjQUp6eXduOCt3Q1liemtBSjBhQWJ0UTFrSW1CazhrbU80cHVZM3d1WEEyQUtGbCtTaDlJQUI2eS9JWUE5STc1RHdFQWkyNkZPNGFNSDhVeU1OenI2UUZBNTNxdmxtWkhJa1A4L0lrbEszQk1yeUN0bG1EZ3FFY1pBWlVOQjArblkvb3dzUWZ2T0huS3kwcFoyeTJySklGekRsVGVVVm1rNkhRK0g5OG52WDV2TU9pTHd5Z0Y4TVQ3VjE2Wks2cHR3Sk9RVDlrQ1dPLzNLRTdZNy83TlBjdkJMOHZZRDREbEJQb0JXRndLd0NvQUFQaEM3NkFBS0Z0TjhDNVQ3NmIwSDU3ZXMvd2syODFsNVE3WmN0RVJhUUlNUUtGUUpnUHplTXllbks4SDRBT29BQmNBbGY2L0Q0QTVyNWxYQndCclkwanBCUExsWUNINENnQndaeEFvYjlJVWFBRElOV1RxTXBBR0p4WWRSOWx0WHNpTVM3M3NPdmwweUZURFNWQWxBUVNaOUxTd3JGS1d5NUwxeDNkTG9Rd0dENGY4OHdZQWxKdUZleGwzQTJYaG04UzU1OU1KQURRQzhBVVdBQWw1TmY5Z0FFcXRWUUxBQ1NpRS92SlVqa055NUlXYVR6bzdQaGlBVS9INmcyeGV5c1preXYwSldVcjBSbnRGcFEzNFdRQ2dybUVjZ0lCYWY4NTBVR1hLTjVSWHM2UXNIVVRBL01vcUVNU090NVNiV0ZTL09kWnVrTGNjNVYxSEQ2emxhTW83dHAxaGJpVHpBcmRidGJnQ2pBQXNWaXhxL0JWdlN0OFpBZ1ZKVDRmRDhwRG11U29tZXpNYkFISzJBQUkxRFlCOUI3S3pPdVJHeXlEVDJJY0NNTDBhQUhtemIxWjFoaGVBalFFQTc4MGwrZ3BLQnQ3Rnc1OEFnQ3pGSyswUWdOUUVnSmNMVklkTFpZUlFseE8rRVFDc2JOUVhBWkJlQm9CMGtGd0FlSXFCMnBFZVhYU2lBT0N3ZFFGZ25iRlorVWdmbVFHd2xEaHRWZkthNmpuTSt3S0NsbjI2NHlTNEVHYUNCUUNnbkFTVys0SUVBcnA4S1N3b2ZTTUM4cE11NGFDSy8rUDR1TG9lbFZ0dlVGcDRjVVpiQTRBNHNGejhud1ZBb2dFNG01V2VUNlcwUWdFNEdsMXJSSjhpV2EzeWpDdEszd2FBNHlsWDRjQXZBT0IwSVFCNmF4Z0dnRmdNMW5FSVhJQU1ydld5LzdheW9WRUZBTHVkdFNRRVBjVkMvRXZsUFpSZGpqUFViS3lzMEtzN2pwNWhzU1R1QXlndllMdE5VSG9BNkZjQTZ3YUxuZzltVGZIYnhJTjE1clpnb1BoU3FBRlF1QWxBcTJ5R0JrRHRoZldSZnlNQUh1ZTJCZ0JHNXBJQndCbDM2dnAwQVlDekRMd0FlS3ZLMzRRQTJTWmJaWWNkZmlBQTQ2b0FzR3NibUpYdGhVdWFtZUltQUZETjhNUnY1cVJCbVFCZnY4R3k0Wnh5dGlVQW00MlpKSmJWQStCS0FqQUF4ekk3VENkL3VpYkJRVERzRWlNcE5ERkt5OVlBWURDWkJRQkF6OVh0ZEQvMzNWNE5BTm5pTXZIMkcxUW1vUnFBTEFQZHA4UDZ5NXh1Z1FBRzRPQUdBR2RZVmdGUUhNd0xnRGgrR0FDam53RUFXelp3QStEcE9Ia3lBV0ErZ0VjRDVQNGVzRGQyQmZOVERxb0ZKTW51c0xzSkFEd1FGQVRBQXUweE5kdkdnVWhnd0U0QU95dklPaG0zQ1NnZFhzVENWZ0hBTWdPb050Y3dmSGMrK3pwT1NnQmtqZ0VFQUhjY3Erd0JpOXJMWEVtQUJLQU1CaUJCd1l0V3l3VEVLQ2VRYkJsVG1vQWZBMENzbWx2V0J3RDJHN1RFZFNrQVoxOVh3ZHRFQkNRQXlrUDlXZ0IyZ1FEczRoMm9FalptRFNPQ0FhQ013TXBlY3JTRC9xVFcweVlBendiTVdRQlNBWTZPaytWY1M2Y1hiL0Jta1F5MkhxYTdDWkVOWnE2eEF3eUFNMnlISi9NQzZVdFNvd0lMSzVWcTdBN0dyV090ck9BL0F3Q1ZHMEFCa05ObHdIWERNUklBU2dQUTJ1VFQwV3JxR2pQQUFUQlVRUEo5QUpSS3U3U3NEQUJ5TFNBSWdOVXFBQUNNZ0dmSkVHWUhMVTBBbkEwblRRRFVhb0RJTml5M0RTZW95Y1NKSXNEWmJPd0tBZ29BanVkU1FjSHRBZjZwWU0zZHdXQWRGSXZqcndQZzVKSC9SUUJZWFdESmRuTVhXNEZTQTZpZXVOOEhBTnFtVXpaekY3dUQ1L1NhYzgwZHdnSExmNnRWQlFCS2V5L0w3aWF3MjV5amE2UFJjRW9sNEc0MmFrVVFyUVllY3hkTGZnSk9sd09BVEJUWkVMd0dBbXlxdmxwQkFJN1FCT2o5aGV5L2FnQUdmeG9BVUhDbmt3MUFHZ3hBTFFJdWJEWEhBa0VHQU5JVHZBcUFlUTBBekdKZFlwTithUUw2c21NSXpEMGwwMUlDeFYrYkNsKzJRQ0U4WHZTaGpPQ1FsWCt0bG1NY0FJVVR6d3F5QU1ock5SalN5MFlYSUtBQkFGL3drTVN4cnhTd1YveE1XQ1FBZXRrRjdBNythd0E0MGxWL2laNXpGUUJjU3NDRmRrQ3ZWWDBuQUhSOWdGejNEQXFvQ1dMbkJRY0FjREVRc3FDWUtQdmlKc0JvT2laSzhLbVpvRElCc25ZTWVSemtVSlJXNVhZRTVCSUFRRUNhSEhTSG45cTVRVUpXc2QwMWJBZUNjb0VBSEhuRGlEOEdBTHNyQ05GME1BQUFSOGRSWDMrWml4RTRuVDRsQURrQUlQa0dBSkFrZElVUTJEZVEycFh1U1V4emZuczZ3eHZPOGpidTlHRWpVRnoyaS9aVS9jUmRwNUprSzVhV05BQ3lXYTRKRXBLMnU4SFEyZTQ5WDBQK1p3T0FqT2lLWXQ1U2x0azFPem1JNVdBTXdJSHFNZnNsQUZUczgvZ2lBTnd0SVl5MmN3RUFIRVBhQzduNno5ZmFPSElTU2NzL0VJQ3lWdkI0TkpxRTlBc0xuUGE1TFVjUUFMQnVRTm5sRkxVR09ycmFzeHNYVjYwRTZNeGdvblB0UlFUVW1BK3d0RFd3V3VVQ29LTHlzdG5ZV3lXRWtBQmdRZnc5QU1DV0VJVDhzM29BaENIZ25BNEVHd0toQUw0VEFIVU1VQjhJbXdBUkNzYnlYaXllbngvcERlcGVCN0FhZ0NXTStMb25meWg2SE1jV0FVY3QvZnhvV1FEVWRRRG5CWk8ySkF3QVl1SG9GT0lCZkJycmxabHVqYmlqU2lyTjNYMWJvREhZbFZuQnVreFliTmNaL2xzQThCU0RoeFVnZGF4ZHpZaWRBSVF4NEVXZ1VndUliUXMvQ1FBcE9OUXhaR3gzRDJjQWVDdUVlVjFBMTFpYUFEanpBTTAwa3FTaTdUQnFQWmFnREhsaEFFQnVzTHU1VUFnQ2hDL2doT0JVeWg4RG9QTkNZbGpoWDVWVThvUi96S1RReEFiQUZNUGZCMENXWFE5QTVwMVVFdTJsWEFUb2pCU3l3Zno1OC9zQk1QdDdtd0RrMkFSVVRnRUQ0anY0WlJpQU1sWERUaVpUZXdUa2hnNVFReENuZEJBSVpLZ1luMUdEeStwVWxkWHVNT2FlRDBBR2dDNlE3NEpKaThBTEZFWEVkY1ZRVVJuUk5nSEFCdHMxM0ZoUzZBR0ZnbU9JMUY4S2dMZjRaeTBBcWhvTm5tb2d3Q2I2ZUlGU2hKVlIwdUxQQUVEM0RVeHBFd0Qzb3lPSjAvWEJuVUJRR3dtVmJBOXFFK0dPR09WTFhBQjQyZzRueGtxN2NpYzFBcTZXSWxjcUFTcWR4TXhheGFFZ1ZETmNBMkRlTTJUMVZ2RTcyeGNRbXdEb01GQTVEZnpkQU14bnNHNWs4VkZmRHdEb3lYSTRWQVBnNkNwVGh3REhoZ0l5a2VTN0FYQ1U3azQ4MDBDN1JWRGxtZzk0cWU5ZFphMXdVUjBNN3BFeGY5L0tOb004Z1RXcE1BSWxBTER2bms0TU0zWUkybGJBYVFuQ3ZjRlBMeE5xMlFyRUs0U3RXc0dKRzFhYVVQTWJkYk1VQUhCbmtHRUNRUGZ3dnc0QVR3ZmVLZ0FJaGlyYWl3VlBDU3ZrLzIwQWtPVzc0VFJ3T0s1WUR2YkhmUjB6UHl4d1c5OXZjWThNMVMxSGkwNzAwS0ZMZmJuN0w4Tkt2RFFBNEFDWEdJS2FCRkFBZ0hCd1hHdVBNRFlIRUlCanhjNmc4Z2pUMmQ4R2dQNzdOZ0R3SktsaktBSG5NQUJPM3cwQU13T3FDcDhGQUwwWVZCTUFzNGlkRWRHeC9iMnQyQ1dQcTRVcndjTitRbkc1Sm9UOE9DQiszSVBMZGlkTkFFeFBnQXd1dTdWQURRTE14T1VjOXhRSEJPQWxNVzhpaUY0T2hna2hqZ29odTkzZkJvQmFHTkpOaDY4QUlQVUJnQ0c0QUlHekxmL3ZBd0J2UEVKTzRQQmVUUU1kYXhLdTdjdlk0eU83Qk5GN2cwc1RRSW5LQVlCWit4VklVMHUvQ2dEc0NBSVZVTjF2MXJkQ2RBNEdBRnFBVkUvY1RBQnFiZzNUQU93cUFGQUMrLzhGUUdjWHBFRWRKc004QWY4dTB4OEFnRDBkZzA3Zy9YZzhuVjJ4S1JTZUFON1hhVWhoeS8vZWJvMHVlYUNkc0pRNEsrOUE0RU1Ea0pnbW9QaHdpZGQySzQ0b1BsSlU1MG5NMHNGK0JJSml3NGdEY3V2YXlVcGRwZ0FRYVd4d0V2ZWlHNmk0dDRiSkdtUko0dHdlYmdPUWZCVUFacGpmQnNCcWsyZ0Q0QmkxQVZESFZmRkV3eGVvQ0FsVTJJR1FmVVY2bGNnQUlNdXVCaUNwQ1FDdTJnQTB3T2orL243cUwxQkhsekVpQUpqUGkxblgxZ1VBRjZENWdPcWFpd0Z3dEJkVENLaDFGRFJKak10QUNEWXdabWRDcTVGSWhSYndaUXlFQW9DUzF4UUF3R21sVW1OVjNkUVhlaDB1TVhvR2hRTWdXOGNxQU1ZM0JJQjNnUGx5QUhUdnhkc0RRQ0NRWDZVRVRqOE5nUEl5cG5KMzZEMXJ5MU9HZnowQXVDYUdJSmpCckxjNEFkVUdVMWRzRkpkZVFaQkEyVm5OOU9CZWNuTVNDZU04NmdCS3J1VjdUUy9DTVNHRXJZVFNJQjFRRXdGNzk1b0dnQ29XbzliTGwrcDZteGFndEErN2xPZ2U3dXNYQUxOdEVRRFRHd0tnUDBZQjROSUNDV3djZlIwQXRGZEJyekZhT2lDcFdDT3NSQ0JFL2xjQTROeVZRd0RnYmhnQk53M0RWR3NCUU5pdU1CY0Fhc0YxdDBJcXUycVdwN1pyeE5nVTFCZ0hxeURvUVNTWm1hVFl2WHBwQUx5K3dFVUVFTnNYUWY2YVhTMUkzRGU2OTRKSW82SDk3NWgvWlZBZ2dta0E0cmFzQm1BZXRpdlFEd0M2VGI4TkFLd0J3Z0dnTXcwd0FCNEdxdVIvSFFDcnJ3WmdOYjhCQU95M3JUSzhUZ0FTTmpFWER4aFR2d3NBWUw2RkFZQzIrOUFIVUw2R0pYc2pVNndxTEJDY01tWnNOSFR2WUxNQkVBVXVFUUFPaTV6WUFCQmhJQ3NTU0FBUXoxekZBRHdCS1dxcHYzUzlYUUFRRXI1WS9PNFVJaU83UU9zWThhL2hjbEo5SmNQbUF4WGJ5b0lBc0JMWTRONCs0dktEMEt2NHppY0xBTE5RYXpVQXlUOEFyTjZ5bHlrQnYvaS9Bb0FzR0FBOG9VWUFaSUVsd3VhdU9LRDY3VElBOEwvMEVvTDFGdml5bWdBWXFNSFdnczZrMDlBcFlaRDhLd0J3WkFYb0VxM3lzdk52ZWp3WnN3QXp1eUFFZ09QRFpuRWJBSlJWTmdGZzU4bjZOamdCa0s3QjVRQ3dUOTdLWVFGZ2h3NkZrMkFBQU51TmV4REk2OWtCOXlabUN3RHg1UU1CMlBJamhBRkFYa094TzVqVmlNbGZXQjNaWU1IYlMvNGduNDJXb2dyMjdWd0pBbHBjSGdCd2ZvRlpleEE0ZzVBVXBPc1BTYW1JdHJCOG1MdkxkQWdDb1FDWUNrRDNqekd1Z2hWM3RkZHBtUVZnTXM5Vm40VFVxQmFPVEVBVkFJZC9BTkJhd09NUEJPb0I0djYvRlFEOEdHV1pmQThBZU44TnRIM1NCSnpTUmVnU3RDc0s2TjdXVjI5S0Q2VWNlREQ5VmJhMkwyQjRlK0FGYUxuUXJRWFNOSE9uRG5xenlITmZGUXU5alFWNkpDcDRHckxOY3NWNzBTb2ZVQUpBM2kyTlZTVUF4K2ZkVlFERThlN0hBS0R1S1dGUDRXcURXakVBQUxBWFZRR1F1allrNXJYRzhjWUE3UGd4am1FQWtKYzAxcTE0OHBkOThkVEZ0VUVaQUhOeWM2OHJLOGpEaWhPQW1HeUhBVU9SQjdYQ0FCY0tWT3dITGtWWWljbFVyM2x5WW5nNUFjZWpHd0I2SHVBdjBwandvK1JuQkVCTVdNZTRrVlFEc04xdkNqMXhEUUNydnhBQUlrQmNFUmdLRVArTkFGang3NVNlenRacXNBbEEybkRvNTdnc0VYSTZwV3YyU0VCeFVLcnNMN0VTNk5mZWdad1lsY0xjVjBwQXlPUzUxYUVHTFZlOENnQVBzY1g5WldHWDZjUWRJYjZFQUJPQTFBREFESVpWMWdyY2lhOEVBVWdTV0MyOHZLNXBZMTRGUU9FRXpQOEI0QVhBdllza2pJR2JBeENMcjNLdUFHQzdXOXNBcUNyOEFJQmN0T2k4ckRLNEFZQlBwdDY4UU45cXZ2TUZxS2l3U1lnWjlvVW1BRzFNd2dsS2xldUV0UkdnREVBaUFERE5VcEQ0RjRzRUtRQm5SdUJtczBnYlNUVUFwM1QxRDRETEFmQmpRTlN5dWg2QWxPY3ZCUUN3M3pmaU9kbkVTMVRPbEwyWThoMy9EbER4QXdPZzE0WXFhdm1FelBZQ0FhQzNFaDNjK3d3SUcyR3ExMG9BVU56bzRFd1hPUjVyYUFHSC9OVmVaZ3FBQ2dSbXM4VTZCUmFBeUFsV3NqcHNGcStOKzFVQUFQRXUzdjhEd0E5QTlYNUNtRDJpdHBjNUNsbGRCd0FQNGhhVHdHb0E5b1BHM1g2NzN4dktBVGJpNFBHcmpHZFRpZTJEVGplUUVqKzVGT2NLNE5xcE9aWUU3QlRBTFh5eWdqdDFLYUZQcDM4dnR5UnFuRlliODJ2WXU1RmRRUUgzUG9MajBWL0tEdFVLZFhuSm5qM0NTejBIQUFCUWU0T1g2MDVqR0FjQWtDOTVPdDM4SHdDVkFBVHNKNnNDQU13QkxnSmd5eFhBc2V5WTdBYmdhUjAxdWdVQWF5T0h2MHdNVjE3Z1NleWJYSzFtZ2U3ZmZCNEVnTkg4b3hvQUl2TUxBK0MyRWRZZUF5aFBDTURPQjRCZUlNTHVvSU9BbXVKSEFOak9IMDRIY1ZVTUxNT0E1MVBWcm9EbGE3c1JWUU5RRUhCYzhEQjZNQURlYkl5L0JRQVhBZ2lBU2d5Y0JhMHVCV0FsdnNGSnV3QnVBTzVhalhaODJPdFl2Vm1BV1FHUWkzTjFWS2FzZHY5SzJUb0NOVmlXME91cThoaEJUTWh0QU9TTDdjM0VCOWVnVEpXZFoxdzdWNkFDQWNNQXhDaDRDeE5zZmUzYkVyNnZJQWNXUUc0THNacXl2YTVHelVZNzJYb0FLQW5JOXV3NzdXYi9BQWdCd0ZXdFVzd1E0VnpSZWY5ZkRNQks3R0k2QVF2Z0JHRGRiVFphZDRmVjJwNElsaFc0bFFvUWtZbXFFTERQL1RxWXE3b21NNGNxQUt4TUx5eDg5OGM3OHdBcUFJQ3hWM3FuQWJFRFdRRkFaWkpiT0pEaXAxMUFNN3ZDWVl1bDgzNDJYQUJ6bHlGNy8rc2lhalFhbldUaEIwQzRnUm12dEJEL0E4QURnRjJreUtzUFBOVnNMd2RncTZLQWVoTG9CbURkTGdDSTRzT09BcUFNQlFrQWNnMkEwU3FrU3ZuREs3bURHNFY4WHVQQkRQNVkrNHR3cHBIOTBjN1M0cmEwVlhFWUF3Q3pxS0N5SWJwTVlld3NTNUxTZVdQaDRrOWk5d0s0WjB2SVU2TFdnUXdBa3QxdXpjYUNKZmdwQU81YXpVYmhCSGdCVURhZ1VBR2N5bjhBaEFEZ3pTTC9RZ0NXWlJEb2ZJSStJQTFBNFFJVUFMUmVGNlFzWUdxNFZnSEpxc1lrMEJQNk1Rc0hWQURnV3hJbVA5RFRYT0FRTWx3QW1BYkYyc1R1akErbXRjVHZEQU5oQUN4YlFDa0FzUmhNQUxDUEdzM2lmOTE0N1FOQXhZSk9SLzVBOGcrQTZ3RndGN1MrRW9CWXBRSUZBZkRhNWdCRXlZWldxNFlOT0lrMHFNMHNZQm5ZbSs1QjdWSEVUbGRndmlkVTlXajV4bFdmQXUwRW92WWZINmdDcFNhUFZtVExYRmJTR2VTT3lyVW1DcmIwRTk5Mk9LTWVteExFWnJOSkxRV2dPcWJIOHAwQWdNVmRzOGtBYUMxV1FRQ2NtUkVvSGxuL0xBQkVUdHNQQk1CVHVoamU5MFkzZzZzQUVBYkFWQUF1QU5ZZERrQ3pPWFFvMVJJQXBRSXlVWGx6TmF0SUJITk9CbmZlR3VGQk8wRHg1Z1lpSkV3VkozQUFnUDhtQU1CUmFCTUFxMUFoeHNFQWdMSUw4RGRDL1BheHlZMGhhcndjQkZiNStheDdrV1l3SXhRQVVNaXRtQVJ5QUlxSm9CY0FiUU55Y1FiSlB3QW9BRXg5VUFrQVVjMzhHZ0JlWHFSbU9XTUxrSklBRk9PeEpRRm9MelpiTzlVeVJsNmdNQUpIY1FveUl1d3QvMnNlai8vMDl3bXc1b3IrYmVFRUFHekhCMDRHTVhMUzRNZmcxSEJWUWtMdklOMmE1WWxVUVN1OVY5V3pyazFPRDdHd2FmRlhsc1J3YlEyUklZRHNCSHNRWldaS3VCenIzZWJRYlVnVDBCeHR6TEE2QXFBazRIeVNTbXY3WXdFd3M0RUNBYUJXTFMwQXpObEFmUUJjNFFMcTVxOE5RSnlWSHFDaEFCSzVLd2dDc0Q3RWtRS2dFZTJ4RGpCV0JMVVhjRDdKRFhGbDV4L0REUGpuZlo1QnVpSCt5K0JKQ2JPL0N2SHRsQ3hOQU5UbmJlMENaWHJkR0FGTG43ZGQ1SzZpaUdsZ1FSeGRCUUpiNGt3YkFBQUFYWFY4dGRvY1hsdE5CVUM3QW9DU2dMTXdBaG1MQnZ3RElBQUFuSG44bFFETTVBd2cxeDFJdEFLSUNRQ1NibE1CMEd6MmpRcHFSaWdJVEFWUDBtYkZML05WZ0FuQUJhZ3F4WTlZcVRVdkZQV1RxRVZtcDRSdzNBZFVqNEFWR1dBeXFJb1dXN2FKTm4xcW96MHhRNlI0SU1SUFgxR2pleEFQeVM5ZkVtQUFRQ1lBbUFJaUtTdzMrMGdEMElqWWlpQU5nQkVMS0FuWVBxeC9GZ0N1TElOQUFPaXhOWGNHMVFTQWlCSVE5em8xNmdHZzFvQk1Bd0NuZ0FZQXdnSklEZEI2M1d4ZGN4azhGVHlmNVZ3dzNVSXZ4TjRHUXJrc2x0aGQxTlNMN3VLUHRBc1VPOTVVQXdBY0ZLcFJ0Y281SmI2dzloVzZlRUQveTcxZzJjbFdBS1FCbUw4a25RWUFvTkZKUWdBUUJNaTVZQnIvQStEYkFEQ21ZSEluaUFnQjJRcUFBaUJ1TnlFQXJmM1c5UVV0RlhCV0FhenQwdW9QWks3MWVBRHdYcDlxL28wQWtETGZZWWdoRTY5c3Z4WGhWZFV0S2MvUjJrZGU2MFFvOFpNYjZsem5Qd2V4dUplbnBiei9qNm9JWmRsNm9Dd01nZTZLNVdheDZEY2hBTTFHUC9ZQmtNS0pnQ2Jnc0x3S2dOcmJoendBNkdYRFlBRE1qQU1TQVBvTjN3OEFqQUErcGRBQjFBcmdXSzRERWdDMEd4aUFObE1CWk5hVTdRV1VqbUFhejBrQXlQcEFOd1NBMU9UMlN3TFdwaW9CTUh2VC9CNEFkc0VBTEF0dEx1ZHBHU1YvRkFTVXZ5eUxLY0JkMDlBQXpVR01CS2VYeXhJckdzUUl5SUFmWURTTGhWSUk4dnE5dTNqODhiL2lOZFFxb1BzT3JnQ2dNcWVJa3ZVbEFGQ1RKV3Y5QW1zQ0tnTElmaytQUXY0bjJJVllBMUIyeVNnL2JQbXlsM05BRFFDTEJxNjNIZ0FNSTNCU1dRN3hjdnMzQUtDbi9OcEIrQ0lBUkhXcUd3R3czRzdWL1greTI1Q25OQUNyelZiT0FTRUF6YnU5ckVGdFJ3TlNQQk5nSDVRbklzVWxqVitxcHZmR01mMTFBc0NsaVZGZHUrQm9nRDMvZDRCQUpmcHVMNzZwZytVUFN4VlJBQ0JSZWFvdGNBaVdod3pkLzZZQ1NIUnRNSDFMcnZkSnAya0N3QmNFVnFzZGRhMzBtcERJRHVPZmxFdlBJMDMrQWZDTkFORHlCMEVBQW9EVlhpc0F2aHdzb29ITjE4V2VyOWpUQUpoRzRKeXJ0SmFDZ0hXTnJDQTZoN2R5N2IvaUZUQjQ1dlEvM1NiQUEwQmx3YklhVS9uaXBkdXFMVTg3ZndRRjdRdllxWjFucDdOcEFFQy9hQlJkWGMxWFc3RU9hQUJRcUlEMW1nWWdUclFSa0FtaS9OUEt4S2J0L09zQVVDV1NsYVcrSElEbFVxN3pnelYvRlFjSUJrQi9oUUFBck85N1V3QldMM0VtdDVtUjhxY0IrSzl3Mm9BQ0tLVFBCMGZoUHJiNXhsTkJuUnlFZEFCTmdHZnlaa2Z0WEQ3eU5xaE9VR3oxV0xXdkgydTBzZGs1aW45QUw5STNNYk8vQXAyMVk2Y1BsM00vMXc1SlpMSXFWMDhZMEZ3bkEvMlBIUUJkSVJ5ZXhqNytid2tWQUFDQTdSUDFBcUNOZ0xJQ0o1WGRpQU1DL3dENExRQ2thblB4eWVoQXFZdk4yUUFVV21sOUp3UnZPb0hGR01ackNvRXljeVhEMFFCQVFKYnM1bDUxNVZyNXB5QUlCTUNvYk9vSFFIUmQ5UUt3M1hrbnI5UlhzUHJYK3dBZzNVdTZ2NlpWYnNQTXZWN1A5dVdtYzNEL0d3cUFBNEJPYVg4NHJQZFFBVUFBV0RodzZRSUFHQUZJd0xuYzc1QW15OVYyK3hNQjRBMnJSYStsRGJUM29xOFViQ20xMmJETzF1WlpFQUFvTjZKTUZkejZBUUM1QmtiYXdRVUFGS2ZCOW9BcitaOC9zZnh6MUhURUJtQTNiRFl4QU5JQXNORlAxbnQxR3RBSUFBU09pSURQczk3aW5HeVh5OVdsdzFEb3U1WGZOU0w5U0lvNGxpeTdnY08vSVVpOEF2Vm50YjhoK1U0cWNLWDBpck9PRVY2dmNGNGNuSFZ4MkN3T3BmaHpTdjQ2RlRSR1ZvMzVBT3REdStFR29KWHNxd0RRYm9Ba0lOZmJIQW9sc1BzSHdGY0RzRHlrWlcyUnZPeEhiOGcvS3p0RVlBRFcrMjRUYXdBNGlxbGdLay9FVEdoSllEQUFFc0NtZ3dDQlcyZ0FiNTROc1k2MDhsdzU2ZnlGSWlDZTlRTGcyRnhJcmU5WWhRL3RaSW1BdEFrYytXZjdQNC9hL0g4NkhBRGRKTWlZeHQ2MWZBQTBtNlBFRFlCV0FYQXlXSXhqQ3UzQVh3TEE4b3NCWUw1QWZRQ1dRUHo2OXJmbDd3QmduU0FQRUFNZ3BvTHhOaTZzd0o3S0RrVGhJRVRBQ2V4elRlZ2JxRlpXc0hQeE55aGVhaDlaNkhhSDhPSGNUTFFXNFM5OWVUR1A0OTFJUUtVTlV5L2NRbXZqT3JtbDJTWmUycktITFd4T2hlVnZ6d0FTUTk4VVBuQXlhamE5QUxEa01HSWhEclpRSlFtQVNpQk5OaS8vQUxnOUFFOHZoeFRJLzF5cWZ5eC9Id0R4dnRXb0FxQjVGMU1Bd0sxdUpRRTVJQUFxZ1N5Sml4a0g2ZHZRUVNBeWc5Y2RWcXFNbVpxa2VCMC9zMDZ3TWhYTHVmSHRLQUNNU0lCNGtWa21FNWtJVnpOemVENGJSUWRFSUVsQmFUbHQvWUg4MFF4QUJZR0FSZHJzVFFOZ0E5QnN0RjZUYlJVQWxBNDQ1N0FHUWhxdmxuODRBQnZ6R3dVRFFHbUFLd0RZc05ZT01hdzJDTFEvSVg4WEFKdERwOWwwQXFCbmhkSCtQOWNtRnpNa2pBbUFkdUJZV0lMdDhrVjN1cjY4YXhnRmdMN3N6b2EwWmZoMzR4QzZJRm9YK3RMYi80eDM0U3RnN3hhS1RaUjA3eEZXVnR4b05BQjVVLyt1VnFvR09RNFRLeFNURkJXYlBMbmxmd1N0NTlIZHNpbk9hdGlxQkVDNEFmRm12U1lCS0s0V1ZnRUdBYWNDQVZqNE10bHVYbTRNZ0U1VnVnMEFlR3ZPTndHZ2k5QmpBT0prdTkwY3NQUzUrQ241NHltZ0FjQ0I5UVpvTjV3QW9JZGFkOFVsV0ZNNjRIQmd2U3g0dlpzalpRVkVVQUFWUDAyU0xjOHpNZXI1MktYNzdVSWJqcVF3L0R6eXhLQzQxQjBrQzRFZGlPcCtacDFIZlVUSERNOStlWGtrREFEVHYxcW1qbjJCNHBaQ3pRdjFwKzJLaVZqaGp4cjN2dEQrbjlqOU8rVWtBSGorWDhnL2FqYURBQ2dJZUk0WERnQXNOOEFrb05BQ3FDS3FTRXhnSjdQQkFNQkdodDhFZ0tyamMyc0EwQVpBUHdCd255QUNJTjV0ZDViMHhkMWZKWDhLZ01JQjdEWkRBV0NyUXB0RERBck1JMmN3aFFsaUZnTHMyK1hIektxSHpDS1RtODFpc1ZpdkM2SEVMT1M4THdjN3J2aEpqTDAxeEdNQUEvM1VicWVmMnN0b2huN0xuaXJrcENwemw1KzNRemdhRFlaZEczdXBaZ0tlMGtIaWFlS2M5OFZWaWcrOGM3TlZWZG9RUDVJLzdqbVFtRDNVbDl0Uk14d0F0bHQwNndSQTd4Z21DUkFJVUNXeVVWdjB4TjR5NmRrNW5Wd3pQRElnNjdQNHlqbVFaVjZxcXo3SVI3MDFZa0FGS2JMVkNDMStLSDhQQUx2WFZzTUhnT1VIZFBlN1BhV0IxVnlncklLdW15SURNL0RKTFVHZGZobGZQV3EyNy9oeDQzUVc0cWZsYnpjZU53SFl0eHZOT2dBMG15UGFCT3N0NDZsRmdJRUFZUW4raHVIcStmT0ZuMWhLM3hLL01mL0xVS2x4RGNBNmpwck5DZ0RNeDF1dnlZRXNnUVVBeUdCTE5OTVpWQXo4alJEOExza0x0MTlKLy9Qc1VmOUUwL0Z5Q3JoeHk5OEpBTXNRVEh3QUFHTUZDTUFJS0kvd0h3TVg2aGx3NzBQeDIvTFBNZzhBcWhwTWxRbG82QlJ4T1JYWVZ3S0FFRGlkYkFiNEZ5Kys2dkczWWlBdlg1Nkg2MnYrU3QvcjFkVm1QL0w4VW5PUWk3Zm5sZThWbWJlRThLblpIN1QrTEFhTVV1UlhjYjk1Q1FCTUJ3UUFvT1JLdXdLU0FYWUNKenhYeVdnWERUM2o4OXpxOFVSMWI2bng1cS8yTTYybTQ2Y3pmZXRiNHMrUHRnSEFBTXhqS2dKTUE0Qk1BYzhQT2h5STJrRmlYaWJEQWNSMHdFSUFlYkNuZjhNM3dPWHlpTjhoZnhqUkZ1Ty81V2JRYkY0SUFDc2l1M1dFNGdRQUxrK0FRQUNkMUw4Uk5zNjA5TDMzUHdaZ2VSZzJ3d0hBSmtENEFmKzVBUUNXNEdpN0FqWUUvd1I2c2VTeDVuU0pQN2FhRGM0UG85WTFBQlFFckYwQVlGOEFOOGsrT2ZYQWp5YmhaM3d6di9DMStPM2Izd0pndlJ0VXlOOWpBaFFCZk04d3NSckRONDNxSm1rWmJwTitPbFZBOEg4NVhFSjJ5SjN5bVhLUC9PTVlOUWplN3BJSy9SOEFBSXNJcFVzSEFDaFZGQzRPR0F6OGcrRFNnVVFQaEc4Ri8xVXRFQWpBUzlwdjFRZkFScUQxbU96MlpwcTRJMXY0SHdOZkkvd1RFcjR4b1ZhelA3eEZmcjVLdTgzbUxRQm90TzZTVlNVQUtad0cwd3o4QStGQzRWdml6N0g0d1lLMkJtRHBpZi82QWJEOWdHWS9YajV0Vmh0VVQ3Wk16b05td0F5Y2tReGdIb0xueHpSQU1ERVp2Y2czejNaZWFQU0txamNUUW5POXpmdFczMmZteERnYTFsOVZoQzgzeUc2V3krVnVFU1QvSUFDS0YzWGk1V0xoQVNEUlVTRktEZVQvQWp5WERLZnM4ZXFmT2Y5bm14b080M2J6Y2dEc1BORkc5THArWmQxbWlIcHRhTjhZRHJQbS95QzRrZWpwNERZWGZxcHlYbVQyWDZHcEY2OWRSLzdIaFFBd1IyQzRmcllBNEgrallvSldzRDMvZWdpQ0R3dGZpTi8wcy9BTUVuNXAvZzBBQ3U5Lzh4cW0vdXNBVURnQzBldmk2V1c3ZFFGZ00zQ2tOWUZxUWZhM0RId3FBU2VtWGtMU1YzbnJhL0ZMQldBQXNGd2U3dHJObXdFQWZtKzA3N2N2bTRXaklhdTFTR2lzamVYL3hnWER0NkpwNUZkeU1heldxODB1WVBaZkh3Qk9RS3Y3K3JwWTd5b0ErSWZBVFVUdkZYNW1kQm92cTNvczlqWFV2d2VBcG9PRzl0M0NVZWNiSVpDNUlLams0RmFjZUQvcHB5TlpsYzFnWkNQckNPQnlGZTc5WFFJQVV3S2QzWEsxWGk0M05BQ1VJU0Fvc09Yd0kvSXYzWGJYL1hYTTVCN3FHSkxzSTc2cmpaZTZQOW9oL2xRSGY5Z1dDTGFibE4zKzllVHZOUUdVVVNoOHdidUVBYkFKV2lTOE5Bbm4zekJsRDYrcHZ2dVY3ZCt6RFkxcmYrN1BiUUJnQzhiUlp2KzZzQW1vQk9BZkJGY2tzZEdiVVJRQThXRzczNDlxMy82MUFaQ2oxZDh2Rm53VDN0NkxRQVVFTmhCT1JEeUg4UjJkT0I1OE9JREkyOE5iZFNUeWtsSGlCMXZYZHN0RC9IcUorQzhEZ0RtRG85MTJ1ZDV2Tm1nak9keDhCVHVqRXlKeWljc3J5NHNIY1JEOEphNDRMdmlHWnBZbkpldTZwd2U3ek5zQTdQZnh0cmdMdC9GZDFMcEUvQmRxQUc0SFh2ZnIxOFhEWXJHMjkrMTYzY0gvdTNFZHdLNmRpT0xtTDI2LzdXYVRiRHF0eG1YeXZ3d0FoVUN5WVp0OXF3QlFXdUFmQzljSkgyOW5WNEcvUWdjdzhUY3ZIWTNHVlFqczE0c04zV29NSXdCSlNLdk90K0ppT0MrUlIzT2FUN20vUWVVTmVMMVV2VjhCdk15ekI3bU0reWI3MTh2di9xc0FFQWkwKy91WTZZRDlPZ2dBeDI1bzZrSzdaVURMSmVSRDRHV0ZSNGMvRGRuUWh5SlJvS1dLNUEybENvOWpIZDBHd056eHZpNHMvM2FmdkVaWGlmOHFBRVM0cU4zZEY2N0lZcTNhWU9CZC80NE45ZkNrYVYrblhQQzRRTnJFcDZXR3NQRVhvTDVRRms0VktYUW4xWDRBU2x2cHJqN0FLNVRIKzNWeDNVZVJWZkw5dHdOUVRBcWoxelErMEFBRWFnSDdNbnpCeU9wcGl6cHE1ZmJmMVF2QWRyVXRMdTFkcDkxc1lBQit0d1lvUVdoMzdrU0ZiKzZiSm5ROWp2cG00R2VQci8zT21WUDVjK252dTIxOXYzODdBSnlCN2lKT2Rqd3hyVDRBRlFNWFhmRyswUHVDQzcrRi92aktGd1llWDduemdTL1doWEo0NWsxODM0dWFNR0hqK3pXQStEcnRhQlNuc21aV1dWZ3Y5bFhjdVZnVzloTmZmTHZYRWxubGR3NjhBcWlBMVg2N1pUN1Z1aCsxbThvSHY4TDIzMW9EQ0FpYXJlanVOUzYrdGV5bWtwQUFtUEZpZlhtVHRJSVA4R2hDQUhBUldvNjM0SWNxd1hWLzdEVUE4TXVWTU5WYWFQMzluUksrOUw1cUFPQjhSYU54UXdTVUl1Z1hGTWdDYjZVZGNGYmlzaTh2dWpUVXRiS3ZuVmU3WEdkL3pBL3dQSS9GblpSSWU0L29VMjc4N21jOXV2ZXYvU2hxTmJXNlJiclhrOUQ5ZSs1K3l4ZzBXKzJvYzdjdnZudXNxNnlxSHpFc3ZWcVdTRVFsRTRrYWJ3RWw0MVNOUnJNQUtIZ0VYMmNITmRXMTZoQlcrc1BOcjY4S1JUcFE5OVllNUcvSTBtVHhQT3hHN2JaUXNJUzhyd1hnZjVrZDhyVzBSVHFoQUFBQUFFbEZUa1N1UW1DQyIsInNpemVzIjoiNTEyeDUxMiIsInR5cGUiOiJpbWFnZS9wbmcifV19"}};
function applyLogo(){
  const v=LOGO_DATA[DB.settings.logoVariant]||LOGO_DATA["1"];
  const sp=$("#splashLogo"),lk=$("#lockLogo"),hl=$("#homeLogo");
  if(sp)sp.src=v.i180;
  if(lk)lk.src=v.i180;
  if(hl)hl.src=v.i180;
  const ti=$("#touchIcon"),ml=$("#manifestLink");
  if(ti)ti.href=v.i180;
  if(ml)ml.href=v.manifest;
}
window.setLogoVariant=function(v){
  DB.settings.logoVariant=v;save();applyLogo();renderSettings();
};

/* ============================================================
   Boot
   ============================================================ */
(function boot(){
  L=DB.settings.lang||"es";
  applyLang();applyAccent();applyLogo();applyTheme();buildPad();drawDots();
  render();
  setTimeout(()=>{
    $("#splash").classList.add("gone");
    if(DB.settings.pinOn&&DB.settings.pinHash){
      pinMode="check";$("#lockMsg").textContent=t("enterPin");
      $("#lock").classList.add("on");
    }
  },900);
})();
</script>
</body>
</html>
