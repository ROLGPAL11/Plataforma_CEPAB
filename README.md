[Directorio_CEPAB_3.html](https://github.com/user-attachments/files/32716531/Directorio_CEPAB_3.html)
# Plataforma_CEPAB
CONTROL DE EMBARCACIONES Y PERSONAL A BORDO.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<script>
/* Modo día / noche. La primera vez sigue la configuración del sistema (Windows/Mac); cuando el usuario
   elige con el botón ☀/🌙 se recuerda su elección (clave «cepab_tema», compartida por las herramientas CEPAB).
   Se aplica antes de pintar la página para evitar el parpadeo. */
(function(){var K='cepab_tema',d=document.documentElement;
 function guardado(){try{var t=localStorage.getItem(K);return t==='dia'||t==='noche'?t:null}catch(e){return null}}
 function sistema(){return window.matchMedia&&matchMedia('(prefers-color-scheme: dark)').matches?'noche':'dia'}
 d.setAttribute('data-tema',guardado()||sistema());
 window.temaUI=function(){var t=d.getAttribute('data-tema');document.querySelectorAll('[data-tema-btn]').forEach(function(b){b.setAttribute('aria-pressed',String(b.getAttribute('data-tema-btn')===t))})};
 window.temaPoner=function(t,guardar){if(t!=='dia'&&t!=='noche')return;d.setAttribute('data-tema',t);if(guardar){try{localStorage.setItem(K,t)}catch(e){}}window.temaUI()};
 if(window.matchMedia){var mq=matchMedia('(prefers-color-scheme: dark)'),f=function(e){if(!guardado())window.temaPoner(e.matches?'noche':'dia',false)};
  if(mq.addEventListener)mq.addEventListener('change',f);else if(mq.addListener)mq.addListener(f)}
 window.addEventListener('storage',function(e){if(e.key===K)window.temaPoner(e.newValue||sistema(),false)});
 document.addEventListener('DOMContentLoaded',window.temaUI);
})();
</script>
    <title>Solicitudes y Directorio CEPAB — DEE</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Lucide Icons -->
    <!-- Los íconos van integrados en el script principal (no dependen de internet) -->
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Source+Serif+4:wght@600;700&display=swap" rel="stylesheet">
    
<script>
/* Modo día/noche: los colores de Tailwind que cambian entre modos se leen de variables CSS
   (con el color original como respaldo). Las variables solo se redefinen en el modo alterno (ver <style id="temaCSS">). */
(function(){var SH=[50,100,200,300,400,500,600,700,800,900,950],NEU={slate:1,gray:1,zinc:1,neutral:1,stone:1},
 PAL={"slate":["248 250 252","241 245 249","226 232 240","203 213 225","148 163 184","100 116 139","71 85 105","51 65 85","30 41 59","15 23 42","2 6 23"],"red":["254 242 242","254 226 226","254 202 202","252 165 165","248 113 113","239 68 68","220 38 38","185 28 28","153 27 27","127 29 29","69 10 10"],"orange":["255 247 237","255 237 213","254 215 170","253 186 116","251 146 60","249 115 22","234 88 12","194 65 12","154 52 18","124 45 18","67 20 7"],"amber":["255 251 235","254 243 199","253 230 138","252 211 77","251 191 36","245 158 11","217 119 6","180 83 9","146 64 14","120 53 15","69 26 3"],"emerald":["236 253 243","209 250 227","167 240 201","110 224 168","52 199 132","18 167 104","0 136 80","0 113 63","6 92 62","11 77 60","4 43 32"],"teal":["236 253 243","209 250 227","167 240 201","110 224 168","52 199 132","18 167 104","0 136 80","0 113 63","6 92 62","11 77 60","4 43 32"],"cyan":["236 253 243","209 250 227","167 240 201","110 224 168","52 199 132","18 167 104","0 136 80","0 113 63","6 92 62","11 77 60","4 43 32"],"blue":["239 246 255","219 234 254","191 219 254","147 197 253","96 165 250","59 130 246","37 99 235","29 78 216","30 64 175","30 58 138","23 37 84"]},
 CAMBIA={"b":{"n":[50,100,200,300],"a":[50,100,200,300]},"t":{"n":[500,600,700,800,900,950],"a":[500,600,700,800,900,950]},"o":{"n":[50,100,200,300],"a":[50,100,200,300]},"r":{"n":[50,100,200,300],"a":[50,100,200,300]},"p":{"n":[300,400],"a":[]},"bw":1},
 U={"b":"backgroundColor","t":"textColor","o":"borderColor","r":"ringColor","p":"placeholderColor"},ext={fontFamily:{sans:['Inter','sans-serif'],serif:['"Source Serif 4"','Georgia','serif']},colors:{"emerald":{"50":"#ecfdf3","100":"#d1fae3","200":"#a7f0c9","300":"#6ee0a8","400":"#34c784","500":"#12a768","600":"#008850","700":"#00713f","800":"#065c3e","900":"#0b4d3c","950":"#042b20"},"teal":{"50":"#ecfdf3","100":"#d1fae3","200":"#a7f0c9","300":"#6ee0a8","400":"#34c784","500":"#12a768","600":"#008850","700":"#00713f","800":"#065c3e","900":"#0b4d3c","950":"#042b20"},"cyan":{"50":"#ecfdf3","100":"#d1fae3","200":"#a7f0c9","300":"#6ee0a8","400":"#34c784","500":"#12a768","600":"#008850","700":"#00713f","800":"#065c3e","900":"#0b4d3c","950":"#042b20"},"sky":{"50":"#ecfdf3","100":"#d1fae3","200":"#a7f0c9","300":"#6ee0a8","400":"#34c784","500":"#12a768","600":"#008850","700":"#00713f","800":"#065c3e","900":"#0b4d3c","950":"#042b20"},"indigo":{"50":"#ecfdf3","100":"#d1fae3","200":"#a7f0c9","300":"#6ee0a8","400":"#34c784","500":"#12a768","600":"#008850","700":"#00713f","800":"#065c3e","900":"#0b4d3c","950":"#042b20"},"purple":{"50":"#ecfdf3","100":"#d1fae3","200":"#a7f0c9","300":"#6ee0a8","400":"#34c784","500":"#12a768","600":"#008850","700":"#00713f","800":"#065c3e","900":"#0b4d3c","950":"#042b20"},"violet":{"50":"#ecfdf3","100":"#d1fae3","200":"#a7f0c9","300":"#6ee0a8","400":"#34c784","500":"#12a768","600":"#008850","700":"#00713f","800":"#065c3e","900":"#0b4d3c","950":"#042b20"},"green":{"50":"#ecfdf3","100":"#d1fae3","200":"#a7f0c9","300":"#6ee0a8","400":"#34c784","500":"#12a768","600":"#008850","700":"#00713f","800":"#065c3e","900":"#0b4d3c","950":"#042b20"},"lime":{"50":"#ecfdf3","100":"#d1fae3","200":"#a7f0c9","300":"#6ee0a8","400":"#34c784","500":"#12a768","600":"#008850","700":"#00713f","800":"#065c3e","900":"#0b4d3c","950":"#042b20"},"oro":{"50":"#fbf8f1","100":"#f5ecd8","200":"#ead6ad","300":"#dcbc7c","400":"#cda158","500":"#b8863a","600":"#9c6d2c","700":"#7c5524","800":"#5e4120","900":"#4b351d","950":"#2a1c0d"}},borderRadius:{xl:'.5rem','2xl':'.625rem','3xl':'.875rem'}};
 Object.keys(U).forEach(function(u){var o=ext[U[u]]={};Object.keys(PAL).forEach(function(f){var ss=CAMBIA[u][NEU[f]?'n':'a'];if(!ss.length)return;o[f]={};
  ss.forEach(function(s){o[f][s]='rgb(var(--'+u+'-'+f+'-'+s+', '+PAL[f][SH.indexOf(s)]+') / <alpha-value>)'})})});
 if(CAMBIA.bw)ext.backgroundColor.white='rgb(var(--b-white, 255 255 255) / <alpha-value>)';
 if(window.tailwind)tailwind.config={theme:{extend:ext}};})();
</script>
    <style>
        svg[data-icon] { flex-shrink: 0; }
        .campo-error { border-color:#ef4444 !important; box-shadow:0 0 0 3px rgba(239,68,68,.25) !important; }
        .custom-shadow {
            box-shadow: 0 10px 30px -10px rgba(4, 120, 87, 0.15);
        }
        pre::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }
        pre::-webkit-scrollbar-track {
            background: rgba(15, 23, 42, 0.5); 
            border-radius: 4px;
        }
        pre::-webkit-scrollbar-thumb {
            background: rgba(52, 211, 153, 0.3); 
            border-radius: 4px;
        }
    </style>
<style id="instCSS">
/* ===== Imagen institucional CEPAB — común a las dos herramientas (no depende de Tailwind) ===== */
:root{--iv9:#0b4d3c;--iv95:#042b20;--iv6:#008850;--io5:#b8863a;--io3:#dcbc7c;
 --logo-pemex:url("data:image/png;base64,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");--logo-cepab:url("data:image/png;base64,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")}
.logo-pemex,.logo-cepab{display:inline-block;vertical-align:middle;background:center/contain no-repeat;-webkit-print-color-adjust:exact;print-color-adjust:exact;flex-shrink:0}
.logo-pemex{background-image:var(--logo-pemex);aspect-ratio:408/240}
.logo-cepab{background-image:var(--logo-cepab);aspect-ratio:239/240}
.ic{width:1.05em;height:1.05em;display:inline-block;vertical-align:-.17em;flex-shrink:0}
.ic-lg{width:1.3em;height:1.3em;vertical-align:-.28em}
.ic-g{color:#10b981}.ic-y{color:#f59e0b}.ic-r{color:#ef4444}
/* Encabezado */
.inst-header{position:relative;color:#fff;background:linear-gradient(100deg,#042b20 0%,#0b4d3c 58%,#0d5a45 100%);font-family:Inter,system-ui,sans-serif;text-align:left}
.inst-bar{max-width:80rem;margin:0 auto;display:flex;align-items:center;gap:1.1rem;padding:1rem 1.25rem}
.inst-plate{background:#fff;border-radius:.55rem;padding:.35rem .6rem;display:flex;align-items:center;box-shadow:0 1px 3px rgba(0,0,0,.3);flex-shrink:0}
.inst-sep{width:1px;align-self:stretch;background:rgba(255,255,255,.22)}
.inst-titles{min-width:0;flex:1}
.inst-eyebrow{font-size:.66rem;font-weight:700;letter-spacing:.2em;text-transform:uppercase;color:var(--io3);margin:0 0 .2rem}
.inst-h1{font-family:'Source Serif 4',Georgia,'Times New Roman',serif;font-weight:700;font-size:clamp(1.2rem,2.3vw,1.8rem);line-height:1.15;margin:0;color:#fff;letter-spacing:.005em}
.inst-sub{font-size:.8rem;line-height:1.35;color:#cfe3da;margin:.25rem 0 0}
.inst-cepab{filter:drop-shadow(0 1px 2px rgba(0,0,0,.35))}
.inst-tools{display:flex;flex-direction:column;align-items:flex-end;gap:.55rem;flex-shrink:0}
.inst-tools .tema-pos{position:static;margin:0}
.inst-rule{height:3px;background:linear-gradient(90deg,var(--io5),#e3c48a 50%,var(--io5))}
.inst-nav{background:rgba(0,0,0,.24)}
.inst-nav-in{max-width:80rem;margin:0 auto;display:flex;align-items:center;gap:.2rem;padding:0 1.25rem;overflow-x:auto}
.inst-nav a{display:inline-flex;align-items:center;gap:.45rem;padding:.62rem .85rem;font-size:.78rem;font-weight:600;color:#d6e6df;text-decoration:none;border-bottom:3px solid transparent;white-space:nowrap}
.inst-nav a:hover{color:#fff;background:rgba(255,255,255,.07)}
.inst-nav a[aria-current=page]{color:#fff;border-bottom-color:var(--io5)}
.inst-nav a:focus-visible{outline:2px solid var(--io3);outline-offset:-2px}
.inst-nav .ic{width:15px;height:15px}
.inst-nav-der{margin-left:auto;display:flex;align-items:center;gap:.6rem;padding:.35rem 0;font-size:.7rem;color:#a9c9bb;white-space:nowrap}
@media (max-width:767px){.inst-bar{flex-wrap:wrap;gap:.7rem;padding:.8rem 1rem}.inst-sep{display:none}
 .inst-plate{order:1}.inst-cepab{order:2;margin-left:auto;height:48px!important}.inst-tools{order:3}.inst-titles{order:4;flex-basis:100%}
 .inst-bar>.inst-plate .logo-pemex{height:32px!important}.inst-nav-in{padding:0 .5rem}.inst-nav-der{display:none}}
/* Pie */
.inst-footer{margin-top:auto;background:var(--iv95);color:#cfe3da;border-top:3px solid var(--io5);font:400 .74rem/1.5 Inter,system-ui,sans-serif}
.inst-footer-in{max-width:80rem;margin:0 auto;padding:1.1rem 1.25rem;display:flex;flex-wrap:wrap;gap:.8rem 2rem;align-items:center;justify-content:space-between}
.inst-footer b{color:#fff;font-weight:600}
.inst-footer-id{display:flex;align-items:center;gap:.7rem}
.inst-footer .inst-plate{padding:.25rem .45rem}
.inst-footer-meta{color:#9fc1b3;text-align:right}
/* Encabezado de cada fase */
.inst-num{width:1.95rem;height:1.95rem;border-radius:.45rem;background:var(--iv9);color:#fff;font-weight:800;font-size:.8rem;display:flex;align-items:center;justify-content:center;box-shadow:inset 0 -3px 0 var(--io5);flex-shrink:0}
.inst-h2{font-family:'Source Serif 4',Georgia,'Times New Roman',serif!important;font-weight:700!important;font-size:1.22rem!important;letter-spacing:.005em!important;text-transform:none!important;line-height:1.25}
.inst-fase-cab{border-bottom-color:rgba(184,134,58,.5)!important}
#fases section[style*="--rg"]{--rg:#12a768!important}
@media screen{html[data-tema="noche"] .inst-num{background:#00713f}}
/* Expediente impreso: logotipos en la portada y en el encabezado de cada hoja */
#printRoot .pgHead-brand .sep{margin:0 1px}
.portada-logos{display:flex;align-items:center;gap:5mm;margin-bottom:9mm}
.portada-logos .inst-plate{padding:2.2mm 3.2mm;border-radius:2mm;box-shadow:none}
</style>
<style id="temaCSS">
/* Selector día/noche (estilos propios: funciona aunque Tailwind no cargue) */
.tema-pos{display:flex;justify-content:flex-end;margin:0 0 .75rem}
@media (min-width:768px){.tema-pos{position:absolute;top:.9rem;right:.9rem;margin:0;z-index:20}}
.tema-switch{display:inline-flex;gap:2px;padding:3px;border-radius:999px;background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.2)}
.tema-switch button{font:600 11px/1 Inter,system-ui,sans-serif;color:#cbd5e1;padding:6px 11px;border-radius:999px;border:0;background:transparent;cursor:pointer;white-space:nowrap;transition:background .15s,color .15s}
.tema-switch button:hover{color:#fff;background:rgba(255,255,255,.1)}
.tema-switch button[aria-pressed="true"]{background:#f8fafc;color:#0f172a;box-shadow:0 1px 3px rgba(0,0,0,.35)}
.tema-switch button:focus-visible{outline:2px solid #34d399;outline-offset:2px}
.tema-switch svg{width:13px;height:13px;display:inline-block;vertical-align:-2px;margin-right:5px}
/* Modo noche: solo en pantalla (la impresión conserva los colores originales) */
@media screen{
html[data-tema="noche"]{--b-slate-50:2 6 23;--b-slate-100:30 41 59;--b-slate-200:51 65 85;--b-slate-300:71 85 105;--b-red-50:69 10 10;--b-red-100:127 29 29;--b-red-200:153 27 27;--b-red-300:185 28 28;--b-orange-50:67 20 7;--b-orange-100:124 45 18;--b-orange-200:154 52 18;--b-orange-300:194 65 12;--b-amber-50:69 26 3;--b-amber-100:120 53 15;--b-amber-200:146 64 14;--b-amber-300:180 83 9;--b-emerald-50:4 43 32;--b-emerald-100:11 77 60;--b-emerald-200:6 92 62;--b-emerald-300:0 113 63;--b-teal-50:4 43 32;--b-teal-100:11 77 60;--b-teal-200:6 92 62;--b-teal-300:0 113 63;--b-cyan-50:4 43 32;--b-cyan-100:11 77 60;--b-cyan-200:6 92 62;--b-cyan-300:0 113 63;--b-blue-50:23 37 84;--b-blue-100:30 58 138;--b-blue-200:30 64 175;--b-blue-300:29 78 216;--t-slate-950:248 250 252;--t-slate-900:241 245 249;--t-slate-800:226 232 240;--t-slate-700:203 213 225;--t-slate-600:148 163 184;--t-slate-500:148 163 184;--t-red-950:254 226 226;--t-red-900:254 202 202;--t-red-800:254 202 202;--t-red-700:252 165 165;--t-red-600:248 113 113;--t-red-500:248 113 113;--t-orange-950:255 237 213;--t-orange-900:254 215 170;--t-orange-800:254 215 170;--t-orange-700:253 186 116;--t-orange-600:251 146 60;--t-orange-500:251 146 60;--t-amber-950:254 243 199;--t-amber-900:253 230 138;--t-amber-800:253 230 138;--t-amber-700:252 211 77;--t-amber-600:251 191 36;--t-amber-500:251 191 36;--t-emerald-950:209 250 227;--t-emerald-900:167 240 201;--t-emerald-800:167 240 201;--t-emerald-700:110 224 168;--t-emerald-600:52 199 132;--t-emerald-500:52 199 132;--t-teal-950:209 250 227;--t-teal-900:167 240 201;--t-teal-800:167 240 201;--t-teal-700:110 224 168;--t-teal-600:52 199 132;--t-teal-500:52 199 132;--t-cyan-950:209 250 227;--t-cyan-900:167 240 201;--t-cyan-800:167 240 201;--t-cyan-700:110 224 168;--t-cyan-600:52 199 132;--t-cyan-500:52 199 132;--t-blue-950:219 234 254;--t-blue-900:191 219 254;--t-blue-800:191 219 254;--t-blue-700:147 197 253;--t-blue-600:96 165 250;--t-blue-500:96 165 250;--o-slate-50:30 41 59;--o-slate-100:30 41 59;--o-slate-200:51 65 85;--o-slate-300:71 85 105;--o-red-50:127 29 29;--o-red-100:127 29 29;--o-red-200:153 27 27;--o-red-300:185 28 28;--o-orange-50:124 45 18;--o-orange-100:124 45 18;--o-orange-200:154 52 18;--o-orange-300:194 65 12;--o-amber-50:120 53 15;--o-amber-100:120 53 15;--o-amber-200:146 64 14;--o-amber-300:180 83 9;--o-emerald-50:11 77 60;--o-emerald-100:11 77 60;--o-emerald-200:6 92 62;--o-emerald-300:0 113 63;--o-teal-50:11 77 60;--o-teal-100:11 77 60;--o-teal-200:6 92 62;--o-teal-300:0 113 63;--o-cyan-50:11 77 60;--o-cyan-100:11 77 60;--o-cyan-200:6 92 62;--o-cyan-300:0 113 63;--o-blue-50:30 58 138;--o-blue-100:30 58 138;--o-blue-200:30 64 175;--o-blue-300:29 78 216;--r-slate-50:30 41 59;--r-slate-100:30 41 59;--r-slate-200:51 65 85;--r-slate-300:71 85 105;--r-red-50:127 29 29;--r-red-100:127 29 29;--r-red-200:153 27 27;--r-red-300:185 28 28;--r-orange-50:124 45 18;--r-orange-100:124 45 18;--r-orange-200:154 52 18;--r-orange-300:194 65 12;--r-amber-50:120 53 15;--r-amber-100:120 53 15;--r-amber-200:146 64 14;--r-amber-300:180 83 9;--r-emerald-50:11 77 60;--r-emerald-100:11 77 60;--r-emerald-200:6 92 62;--r-emerald-300:0 113 63;--r-teal-50:11 77 60;--r-teal-100:11 77 60;--r-teal-200:6 92 62;--r-teal-300:0 113 63;--r-cyan-50:11 77 60;--r-cyan-100:11 77 60;--r-cyan-200:6 92 62;--r-cyan-300:0 113 63;--r-blue-50:30 58 138;--r-blue-100:30 58 138;--r-blue-200:30 64 175;--r-blue-300:29 78 216;--p-slate-400:100 116 139;--p-slate-300:71 85 105;--b-white:15 23 42}
html[data-tema="noche"] .tema-fijo{--b-slate-50:248 250 252;--b-slate-100:241 245 249;--b-slate-200:226 232 240;--b-slate-300:203 213 225;--b-red-50:254 242 242;--b-red-100:254 226 226;--b-red-200:254 202 202;--b-red-300:252 165 165;--b-orange-50:255 247 237;--b-orange-100:255 237 213;--b-orange-200:254 215 170;--b-orange-300:253 186 116;--b-amber-50:255 251 235;--b-amber-100:254 243 199;--b-amber-200:253 230 138;--b-amber-300:252 211 77;--b-emerald-50:236 253 243;--b-emerald-100:209 250 227;--b-emerald-200:167 240 201;--b-emerald-300:110 224 168;--b-teal-50:236 253 243;--b-teal-100:209 250 227;--b-teal-200:167 240 201;--b-teal-300:110 224 168;--b-cyan-50:236 253 243;--b-cyan-100:209 250 227;--b-cyan-200:167 240 201;--b-cyan-300:110 224 168;--b-blue-50:239 246 255;--b-blue-100:219 234 254;--b-blue-200:191 219 254;--b-blue-300:147 197 253;--t-slate-950:2 6 23;--t-slate-900:15 23 42;--t-slate-800:30 41 59;--t-slate-700:51 65 85;--t-slate-600:71 85 105;--t-slate-500:100 116 139;--t-red-950:69 10 10;--t-red-900:127 29 29;--t-red-800:153 27 27;--t-red-700:185 28 28;--t-red-600:220 38 38;--t-red-500:239 68 68;--t-orange-950:67 20 7;--t-orange-900:124 45 18;--t-orange-800:154 52 18;--t-orange-700:194 65 12;--t-orange-600:234 88 12;--t-orange-500:249 115 22;--t-amber-950:69 26 3;--t-amber-900:120 53 15;--t-amber-800:146 64 14;--t-amber-700:180 83 9;--t-amber-600:217 119 6;--t-amber-500:245 158 11;--t-emerald-950:4 43 32;--t-emerald-900:11 77 60;--t-emerald-800:6 92 62;--t-emerald-700:0 113 63;--t-emerald-600:0 136 80;--t-emerald-500:18 167 104;--t-teal-950:4 43 32;--t-teal-900:11 77 60;--t-teal-800:6 92 62;--t-teal-700:0 113 63;--t-teal-600:0 136 80;--t-teal-500:18 167 104;--t-cyan-950:4 43 32;--t-cyan-900:11 77 60;--t-cyan-800:6 92 62;--t-cyan-700:0 113 63;--t-cyan-600:0 136 80;--t-cyan-500:18 167 104;--t-blue-950:23 37 84;--t-blue-900:30 58 138;--t-blue-800:30 64 175;--t-blue-700:29 78 216;--t-blue-600:37 99 235;--t-blue-500:59 130 246;--o-slate-50:248 250 252;--o-slate-100:241 245 249;--o-slate-200:226 232 240;--o-slate-300:203 213 225;--o-red-50:254 242 242;--o-red-100:254 226 226;--o-red-200:254 202 202;--o-red-300:252 165 165;--o-orange-50:255 247 237;--o-orange-100:255 237 213;--o-orange-200:254 215 170;--o-orange-300:253 186 116;--o-amber-50:255 251 235;--o-amber-100:254 243 199;--o-amber-200:253 230 138;--o-amber-300:252 211 77;--o-emerald-50:236 253 243;--o-emerald-100:209 250 227;--o-emerald-200:167 240 201;--o-emerald-300:110 224 168;--o-teal-50:236 253 243;--o-teal-100:209 250 227;--o-teal-200:167 240 201;--o-teal-300:110 224 168;--o-cyan-50:236 253 243;--o-cyan-100:209 250 227;--o-cyan-200:167 240 201;--o-cyan-300:110 224 168;--o-blue-50:239 246 255;--o-blue-100:219 234 254;--o-blue-200:191 219 254;--o-blue-300:147 197 253;--r-slate-50:248 250 252;--r-slate-100:241 245 249;--r-slate-200:226 232 240;--r-slate-300:203 213 225;--r-red-50:254 242 242;--r-red-100:254 226 226;--r-red-200:254 202 202;--r-red-300:252 165 165;--r-orange-50:255 247 237;--r-orange-100:255 237 213;--r-orange-200:254 215 170;--r-orange-300:253 186 116;--r-amber-50:255 251 235;--r-amber-100:254 243 199;--r-amber-200:253 230 138;--r-amber-300:252 211 77;--r-emerald-50:236 253 243;--r-emerald-100:209 250 227;--r-emerald-200:167 240 201;--r-emerald-300:110 224 168;--r-teal-50:236 253 243;--r-teal-100:209 250 227;--r-teal-200:167 240 201;--r-teal-300:110 224 168;--r-cyan-50:236 253 243;--r-cyan-100:209 250 227;--r-cyan-200:167 240 201;--r-cyan-300:110 224 168;--r-blue-50:239 246 255;--r-blue-100:219 234 254;--r-blue-200:191 219 254;--r-blue-300:147 197 253;--p-slate-400:148 163 184;--p-slate-300:203 213 225;--b-white:255 255 255}
html[data-tema="noche"]{color-scheme:dark}
html[data-tema="noche"] .tema-fijo{color-scheme:light}
html[data-tema="noche"] .custom-shadow{box-shadow:0 10px 30px -10px rgba(0,0,0,.6)}
html[data-tema="noche"] .campo-error{box-shadow:0 0 0 3px rgba(239,68,68,.35)!important}
html[data-tema="noche"] #resultadoCEPAB{background-color:#020617}
}
</style>
<style id="verCSS">
/* ===== Control de versión CEPAB: pantalla de caducidad y avisos ===== */
.ver-ic{width:1.1em;height:1.1em;flex-shrink:0;vertical-align:-.18em}
body.ver-caducada{overflow:hidden!important}
#verBloqueo{position:fixed;inset:0;z-index:2147483000;display:flex;align-items:flex-start;justify-content:center;padding:4vh 1rem 1.5rem;overflow:auto;background:rgba(3,30,22,.84);-webkit-backdrop-filter:blur(5px);backdrop-filter:blur(5px);font-family:Inter,system-ui,-apple-system,'Segoe UI',sans-serif;text-align:left}
#verBloqueo .ver-card{width:100%;max-width:37rem;background:#fff;color:#1c2a24;border-radius:.9rem;box-shadow:0 24px 60px rgba(0,0,0,.45);overflow:hidden;margin:auto}
#verBloqueo .ver-cab{display:flex;align-items:center;gap:.8rem;padding:.85rem 1.2rem;background:linear-gradient(100deg,#042b20 0%,#0b4d3c 60%,#0d5a45 100%);color:#fff}
#verBloqueo .ver-cab p{margin:0 0 0 auto;font-size:.6rem;font-weight:700;letter-spacing:.16em;text-transform:uppercase;color:#dcbc7c;text-align:right;line-height:1.4;max-width:21rem}
#verBloqueo .ver-regla{height:3px;background:linear-gradient(90deg,#b8863a,#e3c48a 50%,#b8863a)}
#verBloqueo .ver-cuerpo{padding:1.35rem 1.5rem 1.2rem}
#verBloqueo .ver-alerta{display:inline-flex;align-items:center;gap:.4rem;font-size:.68rem;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:#b42318;background:#fdecea;border:1px solid #f5c2bd;border-radius:999px;padding:.22rem .65rem}
#verBloqueo h2{font-family:'Source Serif 4',Georgia,'Times New Roman',serif;font-size:1.65rem;font-weight:700;line-height:1.2;margin:.7rem 0 .45rem;color:#0b4d3c}
#verBloqueo p{margin:.5rem 0;font-size:.92rem;line-height:1.55}
#verBloqueo b{font-weight:700}
#verBloqueo .ver-motivo{background:#f7f2e6;border-left:3px solid #b8863a;padding:.55rem .8rem;border-radius:.35rem;font-size:.86rem}
#verBloqueo .ver-contacto{margin:1rem 0 .9rem;border:1px solid #d3e4db;border-radius:.65rem;padding:.8rem 1rem;display:grid;gap:.5rem;background:#f5faf7}
#verBloqueo .ver-contacto div{display:flex;gap:.55rem;align-items:center;flex-wrap:wrap;font-size:.9rem}
#verBloqueo .ver-contacto b{min-width:5.2rem;color:#0b4d3c}
#verBloqueo .ver-contacto .ver-ic{color:#008850}
#verBloqueo .ver-correo{font-family:ui-monospace,SFMono-Regular,Menlo,Consolas,monospace;font-size:.82rem;word-break:break-all;-webkit-user-select:all;user-select:all}
#verBloqueo .ver-acc{display:flex;flex-wrap:wrap;gap:.5rem}
#verBloqueo .ver-btn{display:inline-flex;align-items:center;gap:.45rem;border-radius:.55rem;padding:.62rem .95rem;font:600 .85rem/1.1 Inter,system-ui,sans-serif;text-decoration:none;cursor:pointer;border:1px solid transparent}
#verBloqueo .ver-btn:focus-visible{outline:3px solid #dcbc7c;outline-offset:2px}
#verBloqueo .ver-btn-p{background:#008850;color:#fff}
#verBloqueo .ver-btn-p:hover{background:#00713f}
#verBloqueo .ver-btn-s{background:#fff;color:#0b4d3c;border-color:#b7d3c6}
#verBloqueo .ver-btn-s:hover{background:#eef6f2}
#verBloqueo .ver-nota{font-size:.8rem;color:#7a4b00;background:#fff6e5;border:1px solid #f0d49c;border-radius:.45rem;padding:.45rem .7rem}
#verBloqueo .ver-pie{margin-top:1rem;padding-top:.7rem;border-top:1px solid #e3ece7;font-size:.74rem;color:#5f6f68}
#verAviso{font:500 .8rem/1.45 Inter,system-ui,sans-serif;border-bottom:1px solid;text-align:left}
#verAviso .ver-in{max-width:80rem;margin:0 auto;padding:.55rem 1.25rem;display:flex;gap:.6rem;align-items:flex-start}
#verAviso p{margin:0;flex:1}
#verAviso a{color:inherit;font-weight:700;text-decoration:underline;text-underline-offset:2px}
#verAviso .ver-x{background:none;border:0;color:inherit;cursor:pointer;padding:.1rem;border-radius:.3rem;opacity:.75}
#verAviso .ver-x:hover{opacity:1}
#verAviso.ver-nueva{background:#e6f4ee;color:#0b4d3c;border-color:#b7dcc9}
#verAviso.ver-por{background:#fff3dc;color:#6b4200;border-color:#efc97c}
#verAviso.ver-sin{background:#f1f3f5;color:#374151;border-color:#d1d5db}
@media screen{
 html[data-tema="noche"] #verBloqueo{background:rgba(1,12,9,.86)}
 html[data-tema="noche"] #verBloqueo .ver-card{background:#0f1e19;color:#dce9e2;box-shadow:0 24px 60px rgba(0,0,0,.7)}
 html[data-tema="noche"] #verBloqueo h2{color:#8fd4b3}
 html[data-tema="noche"] #verBloqueo .ver-alerta{color:#fda29b;background:#3b1210;border-color:#7a2721}
 html[data-tema="noche"] #verBloqueo .ver-motivo{background:#2a2414;border-left-color:#dcbc7c}
 html[data-tema="noche"] #verBloqueo .ver-contacto{background:#132822;border-color:#244a3d}
 html[data-tema="noche"] #verBloqueo .ver-contacto b{color:#8fd4b3}
 html[data-tema="noche"] #verBloqueo .ver-contacto .ver-ic{color:#34c38a}
 html[data-tema="noche"] #verBloqueo .ver-btn-s{background:#132822;color:#cde9dc;border-color:#2c5a4a}
 html[data-tema="noche"] #verBloqueo .ver-btn-s:hover{background:#1a3830}
 html[data-tema="noche"] #verBloqueo .ver-nota{background:#2e230c;color:#f5d58e;border-color:#6b5217}
 html[data-tema="noche"] #verBloqueo .ver-pie{color:#94aca1;border-top-color:#22392f}
 html[data-tema="noche"] #verAviso.ver-nueva{background:#082a20;color:#bfe6d3;border-color:#145a44}
 html[data-tema="noche"] #verAviso.ver-por{background:#2d2008;color:#f7d58f;border-color:#6b4d12}
 html[data-tema="noche"] #verAviso.ver-sin{background:#1c2127;color:#cbd2da;border-color:#343c46}
}
@media (max-width:640px){#verBloqueo{padding:1rem .75rem}#verBloqueo .ver-cuerpo{padding:1.1rem 1.05rem}#verBloqueo h2{font-size:1.4rem}#verBloqueo .ver-cab p{display:none}#verBloqueo .ver-btn{flex:1 1 100%;justify-content:center}}
@media print{
 #verAviso{display:none!important}
 html body.ver-caducada>*:not(#verBloqueo){display:none!important}
 html body.ver-caducada>#verBloqueo{display:block!important;position:static;background:none;-webkit-backdrop-filter:none;backdrop-filter:none;padding:12mm}
 #verBloqueo .ver-card{box-shadow:none;border:1px solid #999}
 #verBloqueo .ver-acc,#verBloqueo .ver-nota{display:none}
}
</style>
<script>/* Versión de esta herramienta (control de versión con la pestaña Ver_CEPAB) */
window.VER_CEPAB={herramienta:'DIRECTORIO',version:'2026.09.27',nombre:'Plataforma de Solicitudes y Directorio CEPAB'};</script>
</head>
<body class="bg-slate-50 text-slate-800 min-h-screen flex flex-col selection:bg-emerald-500 selection:text-white relative font-sans antialiased">

    <!-- Header Institucional -->
    <header class="inst-header tema-fijo">
  <div class="inst-bar">
    <span class="inst-plate"><span class="logo-pemex" role="img" aria-label="PEMEX" style="height:44px"></span></span>
    <span class="inst-sep" aria-hidden="true"></span>
    <div class="inst-titles">
      <p class="inst-eyebrow">Petróleos Mexicanos · Dirección de Exploración y Extracción</p>
      <h1 class="inst-h1">Plataforma de Solicitudes y Gestión Operativa</h1>
      <p class="inst-sub">Altas y bajas de unidades, Autorizaciones Temporales (mercado SPOT), auditoría PAB y declaración de conformidad para la Supervisión de Contratos DEE.</p>
    </div>
    <span class="logo-cepab inst-cepab" role="img" aria-label="CEPAB" style="height:62px"></span>
    <div class="inst-tools"><div class="tema-pos"><div class="tema-switch" role="group" aria-label="Modo de color de la pantalla"><button type="button" data-tema-btn="dia" aria-pressed="false" onclick="temaPoner('dia',true)" title="Modo día (fondo claro)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="4"/><path d="M12 2v2"/><path d="M12 20v2"/><path d="m4.93 4.93 1.41 1.41"/><path d="m17.66 17.66 1.41 1.41"/><path d="M2 12h2"/><path d="M20 12h2"/><path d="m6.34 17.66-1.41 1.41"/><path d="m19.07 4.93-1.41 1.41"/></svg>Día</button><button type="button" data-tema-btn="noche" aria-pressed="false" onclick="temaPoner('noche',true)" title="Modo noche (fondo oscuro)"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 3a6 6 0 0 0 9 9 9 9 0 1 1-9-9Z"/></svg>Noche</button></div></div></div>
  </div>
  <div class="inst-rule"></div>
  <nav class="inst-nav" aria-label="Herramientas CEPAB"><div class="inst-nav-in">
    <a href="CEDULAS_CEPAB_INTEGRADO_v3.html"><svg class="ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"/><polyline points="14 2 14 8 20 8"/><line x1="16" x2="8" y1="13" y2="13"/><line x1="16" x2="8" y1="17" y2="17"/><line x1="10" x2="8" y1="9" y2="9"/></svg>Cédulas CEPAB</a>
    <a href="Directorio_CEPAB_3.html" aria-current="page"><svg class="ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m3 3 3 9-3 9 19-9Z"/><path d="M6 12h16"/></svg>Solicitudes y Directorio</a>
    <div class="inst-nav-der">SMEL-GSLM — Módulo de Atención CEPAB</div>
  </div></nav>
</header>

    <!-- Main Content -->
    <main class="flex-grow max-w-4xl w-full mx-auto px-4 py-8">

        <!-- Formulario Principal -->
        <section class="bg-white rounded-2xl p-6 md:p-8 border border-slate-200 shadow-sm custom-shadow">
            
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3 mb-6 border-b border-slate-100 pb-4">
                <div class="flex items-center gap-3">
                    <div class="p-3 bg-emerald-100 text-emerald-700 rounded-xl shadow-inner">
                        <i data-lucide="file-text" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h2 class="inst-h2 text-xl font-bold text-slate-900">
                            Estructurador de Trámites y Correos Oficiales
                        </h2>
                        <p class="text-sm text-slate-500">
                            Seleccione el módulo operativo, verifique requisitos y genere la documentación institucional.
                        </p>
                    </div>
                </div>
                <!-- Indicador de conexión -->
                <div id="catStatus" class="flex items-center gap-1.5 px-3 py-1 bg-slate-100 text-slate-600 rounded-full text-xs font-medium border border-slate-200 self-start sm:self-auto">
                    <span class="w-2 h-2 rounded-full bg-amber-500 animate-pulse" id="statusDot"></span>
                    <span id="statusText">Conectando a Catálogo...</span>
                </div>
            </div>

            <div class="grid md:grid-cols-2 gap-5">
                
                <!-- 1. Selección de Módulo Operativo -->
                <div class="md:col-span-2">
                    <label for="moduloOperativo" class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">
                        1. Módulo operativo CEPAB <span class="text-red-500">*</span>
                    </label>
                    <div class="relative">
                        <select id="moduloOperativo" class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm font-medium text-slate-800 focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 outline-none transition-all appearance-none cursor-pointer">
                            <option value="">-- Seleccione el Módulo Operativo --</option>
                            <option value="ALTAS">1. Altas y Autorizaciones Temporales (Embarcación, Artefacto Naval, Campamento, Instalación Fija)</option>
                            <option value="BAJAS">2. Bajas (Embarcación, Artefacto Naval y fin de Autorización Temporal)</option>
                            <option value="CONTRATOS">3. Contratos DEE (alta en el catálogo y ampliación de vigencia)</option>
                            <option value="PAB">4. Monitoreo diario y auditoría PAB (OK-CEPAB)</option>
                            <option value="DECLARACION">5. Declaración de Conformidad (Supervisión de Contrato DEE)</option>
                        </select>
                        <i data-lucide="chevron-down" class="absolute right-3 top-3.5 w-4 h-4 text-slate-400 pointer-events-none"></i>
                    </div>
                </div>

                <!-- 2. Sub-trámite / Motivo Específico -->
                <div class="md:col-span-2">
                    <label for="subTramite" class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">
                        2. Sub-trámite / Motivo Específico <span class="text-red-500">*</span>
                    </label>
                    <div class="relative">
                        <select id="subTramite" disabled class="w-full bg-slate-100 border border-slate-200 rounded-xl p-3 text-sm text-slate-400 focus:ring-2 focus:ring-emerald-500 outline-none transition-all appearance-none cursor-not-allowed">
                            <option value="">-- Seleccione primero un Módulo Operativo --</option>
                        </select>
                        <i data-lucide="chevron-down" class="absolute right-3 top-3.5 w-4 h-4 text-slate-400 pointer-events-none"></i>
                    </div>
                </div>

                <!-- Área solicitante: SMEL-GSLM (misma gerencia) u otra gerencia -->
                <div id="wrapGerencia" class="hidden md:col-span-2">
                    <label for="gerenciaSolicitante" class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">
                        Área solicitante (gerencia del Supervisor de Contrato) <span id="reqGerencia" class="hidden text-red-500">*</span>
                    </label>
                    <div class="grid md:grid-cols-[minmax(0,1fr)_16rem] gap-3">
                        <select id="gerenciaSolicitante" class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm text-slate-800 focus:ring-2 focus:ring-emerald-500 outline-none transition-all cursor-pointer">
                            <option value="">-- Seleccione el área solicitante --</option>
                            <option value="GSLM">SMEL-GSLM — Gerencia de Servicios de Logística Marina (misma gerencia)</option>
                            <option value="OTRA">Otra gerencia de la DEE</option>
                        </select>
                        <input id="gerenciaOtra" list="dl-gerencias" type="text" placeholder="Siglas de la gerencia (ej. SMEL-GMEICM)" class="hidden w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm uppercase focus:ring-2 focus:ring-emerald-500 outline-none transition-all">
                        <datalist id="dl-gerencias"></datalist>
                    </div>
                    <p id="gerenciaHint" class="text-[11px] text-slate-500 mt-1.5">Se detecta al capturar el contrato; también puede elegirla.</p>
                </div>

                <!-- ÁREA DINÁMICA DE REQUISITOS Y CHECKLIST NORMADO -->
                <div id="areaInstrucciones" class="hidden md:col-span-2 bg-emerald-50/70 border border-emerald-200 rounded-2xl p-4 md:p-5 transition-all duration-300">
                    <div class="flex items-center justify-between gap-2 mb-3">
                        <div class="flex items-center gap-2 text-emerald-900 font-bold text-sm">
                            <i data-lucide="shield-check" class="w-5 h-5 text-emerald-600"></i>
                            <span id="tituloInstrucciones">Requisitos y Filtros de Gobernanza Obligatorios</span>
                        </div>
                        <span id="badgeProgreso" class="text-[11px] font-bold px-2.5 py-0.5 rounded-full bg-amber-100 text-amber-800 border border-amber-300">
                            0/0 Validados
                        </span>
                    </div>

                    <!-- Lista de Requisitos -->
                    <div id="listaChecklist" class="space-y-2.5 mb-4"></div>

                    <!-- Cuadro de Instrucciones Normativas -->
                    <div id="boxInstruccionTextual" class="hidden bg-white border border-emerald-200 rounded-xl p-3 text-xs text-slate-700 leading-relaxed items-start gap-2.5 shadow-sm">
                        <i data-lucide="info" class="w-4 h-4 text-emerald-600 shrink-0 mt-0.5"></i>
                        <div id="textoInstruccion" class="flex-grow"></div>
                    </div>
                </div>

                <!-- Modalidad de Contratación -->
                <div id="wrapModalidad">
                    <label for="modalidadContratacion" class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2">
                        Modalidad Operativa / Contrato <span class="text-red-500">*</span>
                    </label>
                    <div class="relative">
                        <select id="modalidadContratacion" class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm text-slate-700 focus:ring-2 focus:ring-emerald-500 outline-none transition-all appearance-none cursor-pointer">
                            <option value="CONTRATO DEE">Contrato DEE</option>
                            <option value="AUTORIZACION TEMPORAL">Autorización Temporal (mercado SPOT)</option>
                            <option value="SERVICIO GSLM">Servicio SMEL-GSLM (Logística Marina)</option>
                        </select>
                        <i data-lucide="chevron-down" class="absolute right-3 top-3.5 w-4 h-4 text-slate-400 pointer-events-none"></i>
                    </div>
                </div>

                <!-- Embarcación Principal (Col A) -->
                <div id="wrapEmbarcacion">
                    <label for="embarcacion" id="lblEmbarcacion" class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2">Embarcación o Artefacto Naval <span class="text-red-500">*</span></label>
                    <input id="embarcacion" list="lista-embarcaciones" type="text" placeholder="Escriba o busque embarcación..." class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm focus:ring-2 focus:ring-emerald-500 outline-none transition-all">
                    <datalist id="lista-embarcaciones"></datalist>
                    <div id="hintEmb" class="hidden mt-2 text-[11px] bg-amber-50 border border-amber-200 text-amber-900 rounded-lg p-2.5"></div>
                </div>

                <!-- Ficha de Datos Técnicos Detectados de la Embarcación (Col A-F) -->
                <div id="badgeDatosTecnicos" class="hidden md:col-span-2 bg-slate-100 border border-slate-200 rounded-xl p-3 text-xs text-slate-600 flex flex-wrap gap-4 items-center">
                    <span class="font-bold text-slate-800 flex items-center gap-1">
                        <i data-lucide="ship" class="w-3.5 h-3.5 text-emerald-600"></i> Datos Catálogo:
                    </span>
                    <span><strong>Servicio:</strong> <span id="infoServicio">-</span></span>
                    <span><strong>MMSI:</strong> <span id="infoMMSI" class="font-mono text-emerald-700 font-bold">-</span></span>
                    <span><strong>IMO:</strong> <span id="infoIMO" class="font-mono">-</span></span>
                    <span><strong>Callsign:</strong> <span id="infoCallsign" class="font-mono">-</span></span>
                    <span><strong>Bandera:</strong> <span id="infoBandera">-</span></span>
                </div>

                <!-- Solo SPOT: cantidad de contratos -->
                <div id="wrapNumContratosSpot" class="hidden">
                    <label for="numContratosSpot" class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">
                        ¿En cuántos contratos estará trabajando? <span class="text-red-500">*</span>
                    </label>
                    <input id="numContratosSpot" type="number" min="1" max="20" inputmode="numeric" placeholder="Ej. 3" class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm focus:ring-2 focus:ring-blue-500 outline-none transition-all">
                </div>

                <!-- Número de Contrato (Col G - Independiente) -->
                <div id="wrapContrato">
                    <label for="contrato" class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2">
                        Número de Contrato <span class="text-red-500">*</span>
                    </label>
                    <input id="contrato" list="lista-contratos" type="text" placeholder="Escriba o busque contrato..." class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm focus:ring-2 focus:ring-emerald-500 outline-none transition-all">
                    <datalist id="lista-contratos"></datalist>
                </div>

                <!-- Compañía / Empresa (Col H - Independiente) -->
                <div id="wrapEmpresa">
                    <label for="empresa" class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2">
                        Compañía / Contratista <span class="text-red-500">*</span>
                    </label>
                    <input id="empresa" list="lista-empresas" type="text" placeholder="Escriba o busque compañía..." class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm focus:ring-2 focus:ring-emerald-500 outline-none transition-all">
                    <datalist id="lista-empresas"></datalist>
                </div>

                <!-- Solo artefacto naval: embarcación(es) que lo remolcarán -->
                <div id="wrapRemolque" class="hidden">
                    <label for="remolcador" class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2">Embarcación(es) que lo remolcarán</label>
                    <input id="remolcador" list="lista-embarcaciones" type="text" placeholder="Nombre del remolcador (separe con coma si son varios)" class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm focus:ring-2 focus:ring-emerald-500 outline-none transition-all">
                </div>

                <!-- Solo alta en otro contrato: tipo de contrato en el Atlas GL -->
                <div id="wrapTipoAtlas" class="hidden">
                    <label for="tipoContratoAtlas" class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">Tipo de contrato en el nuevo contrato (Atlas GL) <span class="text-red-500">*</span></label>
                    <select id="tipoContratoAtlas" class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm text-slate-800 focus:ring-2 focus:ring-emerald-500 outline-none transition-all cursor-pointer">
                        <option value="">-- Seleccione --</option>
                        <option value="PERMANENTE">Permanente (activo principal del contrato)</option>
                        <option value="ADICIONAL">Adicional (apoyo secundario; también permanente)</option>
                    </select>
                </div>

                <!-- BLOQUE DINÁMICO: SUSTITUCIÓN DE UNIDADES -->
                <div id="bloqueSustitucion" class="hidden md:col-span-2 bg-amber-50/80 border border-amber-200 rounded-2xl p-4 space-y-3">
                    <p class="text-xs font-bold text-amber-900 uppercase tracking-wider flex items-center gap-1.5">
                        <i data-lucide="arrow-left-right" class="w-4 h-4 text-amber-600"></i> <span id="tituloSust">Datos obligatorios de sustitución</span>
                    </p>
                    <div class="grid md:grid-cols-3 gap-3">
                        <div>
                            <label for="sustNombre" id="lblSustNombre" class="block text-[11px] font-bold text-slate-600 mb-1">Embarcación o Artefacto Naval <span class="text-red-500">*</span></label>
                            <input id="sustNombre" list="lista-embarcaciones" type="text" placeholder="Escriba o busque embarcación..." class="w-full bg-white border border-amber-300 rounded-lg p-2.5 text-xs outline-none focus:ring-2 focus:ring-amber-500">
                        </div>
                        <div>
                            <label for="sustIMO" class="block text-[11px] font-bold text-slate-600 mb-1">IMO</label>
                            <input id="sustIMO" type="text" placeholder="Número IMO..." class="w-full bg-white border border-amber-300 rounded-lg p-2.5 text-xs outline-none focus:ring-2 focus:ring-amber-500">
                        </div>
                        <div>
                            <label for="sustMMSI" class="block text-[11px] font-bold text-slate-600 mb-1">MMSI</label>
                            <input id="sustMMSI" type="text" placeholder="Número MMSI..." class="w-full bg-white border border-amber-300 rounded-lg p-2.5 text-xs outline-none focus:ring-2 focus:ring-amber-500">
                        </div>
                    </div>
                </div>

                <!-- BLOQUE DINÁMICO: ALTA DE INSTALACIONES FIJAS -->
                <div id="bloqueFijas" class="hidden md:col-span-2 bg-teal-50/80 border border-teal-200 rounded-2xl p-4 space-y-3">
                    <p class="text-xs font-bold text-teal-900 uppercase tracking-wider flex items-center gap-1.5">
                        <i data-lucide="building-2" class="w-4 h-4 text-teal-600"></i> <span id="tituloFijas">Alta de Instalaciones Fijas</span>
                    </p>
                    <div class="max-w-sm">
                        <label for="numFijas" id="lblNumFijas" class="block text-xs font-bold text-slate-700 mb-1">¿Cuántas instalaciones fijas se darán de alta? <span class="text-red-500">*</span></label>
                        <input id="numFijas" type="number" min="1" max="20" inputmode="numeric" placeholder="Ej. 2" class="w-full bg-white border border-teal-300 rounded-lg p-2.5 text-sm outline-none focus:ring-2 focus:ring-teal-500">
                    </div>
                    <datalist id="dl-region"><option value="Subdirección de Mantenimiento Estático y Logística"></option></datalist>
                    <datalist id="dl-activo"><option value="Gerencia de Mantenimiento Estático e Infraestructura Complementaria Marina"></option><option value="Gerencia de Servicios de Logística Marina"></option></datalist>
                    <datalist id="dl-complejo"><option value="Subgerencia de Mantenimiento y Confiabilidad de Instalaciones RMSO y RN"></option></datalist>
                    <div id="filasFijas" class="space-y-3"></div>
                </div>

                <!-- BLOQUE DINÁMICO: DETALLES DE MERCADO SPOT -->
                <div id="bloqueSPOT" class="hidden md:col-span-2 bg-blue-50/80 border border-blue-200 rounded-2xl p-4 space-y-3">
                    <p class="text-xs font-bold text-blue-900 uppercase tracking-wider flex items-center gap-1.5">
                        <i data-lucide="calendar-clock" class="w-4 h-4 text-blue-600"></i> Autorización Temporal (mercado SPOT)
                    </p>
                    <div class="max-w-md">
                        <label for="dependenciaSpot" class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">Dependencia / Modalidad Temporal (tipo de folio) <span class="text-red-500">*</span></label>
                        <select id="dependenciaSpot" class="w-full bg-white border border-blue-300 rounded-lg p-2.5 text-sm outline-none focus:ring-2 focus:ring-blue-500">
                            <option value="PMX">PMX — servicio a contratos DEE / mercado SPOT</option>
                            <option value="CNE">CNE — Comisión Nacional de Energía (antes CNH)</option>
                            <option value="FIDENA">FIDENA — Fideicomiso de Formación y Capacitación de la Marina Mercante</option>
                        </select>
                        <p class="text-[11px] text-blue-800 mt-1">El folio lo asigna el Área de Enlace de Integración y Evaluación.</p>
                    </div>
                    <div id="filasContratosSpot" class="space-y-3"></div>
                </div>

                <!-- Datos del Supervisor de Contrato DEE / Solicitante -->
                <div>
                    <label for="supervisorNombre" class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">
                        Supervisor de Contrato DEE / Solicitante <span class="text-red-500">*</span>
                    </label>
                    <input id="supervisorNombre" type="text" placeholder="Nombre completo del Supervisor de Contrato DEE..." class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm focus:ring-2 focus:ring-emerald-500 outline-none transition-all">
                </div>

                <div>
                    <label for="supervisorFicha" class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">
                        Ficha PEMEX / Cargo del Supervisor
                    </label>
                    <input id="supervisorFicha" type="text" placeholder="Ej. 458921 — Supervisor de Contrato DEE" class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm focus:ring-2 focus:ring-emerald-500 outline-none transition-all">
                </div>

                <!-- Correo en Copia (CC) -->
                <div class="md:col-span-2">
                    <label for="ccEmail" class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2">
                        Enviar con Copia (CC)
                    </label>
                    <input id="ccEmail" type="email" placeholder="Ej. integracion.servicios@pemex.com, regulacion.naval@pemex.com" class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm focus:ring-2 focus:ring-emerald-500 outline-none transition-all">
                </div>

                <!-- Observaciones y Detalle Complementario -->
                <div class="md:col-span-2">
                    <label for="observaciones" class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2">
                        Ubicación, Coordenadas u Observaciones Operativas
                    </label>
                    <textarea id="observaciones" rows="3" placeholder="Latitud/Longitud, Sector, Región, Justificación técnica u observaciones específicas..." class="w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm focus:ring-2 focus:ring-emerald-500 outline-none transition-all resize-none"></textarea>
                </div>

            </div>

            <!-- Botones de Acción -->
            <div class="flex flex-wrap items-center gap-3 mt-8 pt-6 border-t border-slate-100">
                <button id="btnGenerar" type="button" class="bg-emerald-600 hover:bg-emerald-700 text-white px-6 py-3 rounded-xl text-sm font-bold flex items-center gap-2 transition-all active:scale-95 shadow-lg shadow-emerald-600/30">
                    <i data-lucide="send-horizontal" class="w-5 h-5"></i> Generar Documento / Correo
                </button>

                <button id="btnLimpiar" type="button" class="bg-slate-100 hover:bg-slate-200 text-slate-700 px-4 py-3 rounded-xl text-sm font-semibold flex items-center gap-2 transition-all active:scale-95">
                    <i data-lucide="rotate-ccw" class="w-4 h-4"></i> Limpiar
                </button>
            </div>

            <!-- Panel de Envío Directo y Vista Previa del Correo -->
            <div id="resultadoCEPAB" class="hidden mt-8 bg-slate-900 rounded-2xl p-6 shadow-xl relative overflow-hidden transition-all duration-300 border border-slate-800">
                <div class="absolute top-0 right-0 w-48 h-48 bg-emerald-500/10 rounded-full blur-3xl -z-10"></div>
                
                <div class="flex items-center justify-between border-b border-slate-800 pb-4 mb-5">
                    <h3 class="text-emerald-400 text-sm font-bold uppercase tracking-wider flex items-center gap-2">
                        <i data-lucide="mail-check" class="w-5 h-5 text-emerald-400"></i> Vista Previa y Canales de Envío
                    </h3>
                    <span id="displayFolio" class="text-xs bg-emerald-500/20 text-emerald-300 border border-emerald-500/30 px-3 py-1 rounded-full font-mono font-medium"></span>
                </div>

                <div id="avisoPendientes" class="hidden bg-amber-500/10 border border-amber-400/40 text-amber-200 rounded-xl p-3 mb-4 text-xs">
                    <p class="font-bold mb-1 flex items-center gap-1.5"><i data-lucide="alert-triangle" class="w-4 h-4"></i> Revise antes de enviar:</p>
                    <ul id="listaAvisos" class="list-disc pl-5 space-y-0.5"></ul>
                </div>

                <!-- PANEL DE BOTONES DE ENVÍO DIRECTO -->
                <div class="bg-slate-800/80 border border-slate-700 rounded-xl p-4 mb-6">
                    <p class="text-xs font-bold text-slate-300 uppercase tracking-wider mb-3 flex items-center gap-1.5">
                        <i data-lucide="zap" class="w-4 h-4 text-amber-400"></i> Seleccione la plataforma para enviar:
                    </p>
                    <div class="grid sm:grid-cols-3 gap-3">
                        
                        <button id="btnMailto" type="button" class="bg-emerald-600 hover:bg-emerald-500 text-white p-3 rounded-xl text-xs font-bold flex items-center justify-center gap-2 transition-all shadow-md active:scale-95 group">
                            <i data-lucide="mail" class="w-4 h-4 transition-transform group-hover:scale-110"></i>
                            <span>Abrir Outlook / App</span>
                        </button>

                        <button id="btnGmail" type="button" class="bg-red-600 hover:bg-red-500 text-white p-3 rounded-xl text-xs font-bold flex items-center justify-center gap-2 transition-all shadow-md active:scale-95 group">
                            <i data-lucide="globe" class="w-4 h-4 transition-transform group-hover:scale-110"></i>
                            <span>Abrir Gmail Web</span>
                        </button>

                        <button id="btnOutlook" type="button" class="bg-blue-600 hover:bg-blue-500 text-white p-3 rounded-xl text-xs font-bold flex items-center justify-center gap-2 transition-all shadow-md active:scale-95 group">
                            <i data-lucide="building-2" class="w-4 h-4 transition-transform group-hover:scale-110"></i>
                            <span>Outlook Web (M365)</span>
                        </button>

                    </div>
                </div>

                <div class="space-y-3 text-sm">
                    
                    <!-- Fila Para -->
                    <div class="flex items-center justify-between border-b border-slate-800 pb-2.5">
                        <div class="flex items-center gap-2 overflow-hidden mr-2">
                            <span class="w-20 text-slate-400 font-medium shrink-0">Para:</span>
                            <span id="displayPara" class="text-slate-200 font-mono text-xs truncate">controldeembarcacionesypersonalabordo@pemex.com</span>
                        </div>
                        <button id="btnCopiarPara" type="button" class="bg-slate-800 hover:bg-emerald-600 text-slate-300 hover:text-white p-1.5 rounded-lg transition-all shrink-0" title="Copiar Destinatario">
                            <i data-lucide="copy" class="w-4 h-4"></i>
                        </button>
                    </div>

                    <!-- Fila CC -->
                    <div id="filaCC" class="hidden flex items-center justify-between border-b border-slate-800 pb-2.5">
                        <div class="flex items-center gap-2 overflow-hidden mr-2">
                            <span class="w-20 text-slate-400 font-medium shrink-0">CC:</span>
                            <span id="displayCC" class="text-amber-300 font-mono text-xs truncate"></span>
                        </div>
                        <button id="btnCopiarCC" type="button" class="bg-slate-800 hover:bg-emerald-600 text-slate-300 hover:text-white p-1.5 rounded-lg transition-all shrink-0" title="Copiar CC">
                            <i data-lucide="copy" class="w-4 h-4"></i>
                        </button>
                    </div>

                    <!-- Fila Asunto -->
                    <div class="flex items-center justify-between border-b border-slate-800 pb-2.5">
                        <div class="flex items-center gap-2 overflow-hidden mr-2">
                            <span class="w-20 text-slate-400 font-medium shrink-0">Asunto:</span>
                            <span id="displayAsunto" class="text-slate-200 font-bold truncate"></span>
                        </div>
                        <button id="btnCopiarAsunto" type="button" class="bg-slate-800 hover:bg-emerald-600 text-slate-300 hover:text-white p-1.5 rounded-lg transition-all shrink-0" title="Copiar Asunto">
                            <i data-lucide="copy" class="w-4 h-4"></i>
                        </button>
                    </div>

                    <!-- Bloque Cuerpo -->
                    <div class="mt-4 bg-slate-950 p-4 rounded-xl border border-slate-800 relative group">
                        <div class="flex items-center justify-between mb-3 border-b border-slate-800/80 pb-2">
                            <span class="text-xs text-slate-400 font-medium">Cuerpo del Mensaje Estructurado:</span>
                            <div class="flex items-center gap-2">
                                <button id="btnCopiarCuerpo" type="button" class="bg-slate-800 hover:bg-emerald-600 text-slate-300 hover:text-white px-3 py-1 rounded-lg text-xs font-semibold flex items-center gap-1.5 transition-all">
                                    <i data-lucide="copy" class="w-3.5 h-3.5"></i> Copiar Texto
                                </button>
                                <button id="btnCopiarTodo" type="button" class="bg-emerald-700 hover:bg-emerald-600 text-white px-3 py-1 rounded-lg text-xs font-semibold flex items-center gap-1.5 transition-all">
                                    <i data-lucide="files" class="w-3.5 h-3.5"></i> Copiar Todo
                                </button>
                            </div>
                        </div>
                        <pre id="displayCuerpo" class="whitespace-pre-wrap text-slate-300 font-mono text-[12.5px] leading-relaxed max-h-96 overflow-y-auto"></pre>
                    </div>

                </div>
            </div>

        </section>
    </main>

    <!-- Footer Institucional -->
    <footer class="inst-footer">
  <div class="inst-footer-in">
    <div class="inst-footer-id"><span class="inst-plate"><span class="logo-pemex" role="img" aria-label="PEMEX" style="height:24px"></span></span><span class="logo-cepab" role="img" aria-label="CEPAB" style="height:36px"></span>
      <div><b>Centro de Control de Tráfico Marítimo — Jefatura CCTM</b><br>Control de Embarcaciones y Personal a Bordo (CEPAB) · Petróleos Mexicanos — Dirección de Exploración y Extracción</div></div>
    <div class="inst-footer-meta">Uso interno<br>Herramientas CEPAB · Versión <b>2026.09.27</b><span id="verPie"></span></div>
  </div>
</footer>

    <!-- Toast Notification -->
    <div id="toast" role="status" aria-live="polite" class="fixed bottom-6 right-6 translate-y-24 opacity-0 bg-slate-900 text-white px-4 py-3 rounded-xl shadow-2xl flex items-center gap-3 transition-all duration-300 pointer-events-none z-50 border border-slate-700">
        <div class="bg-emerald-500/20 text-emerald-400 p-1.5 rounded-lg" id="toastIcon">
            <i data-lucide="check-circle-2" class="w-5 h-5"></i>
        </div>
        <div>
            <p id="toastTitle" class="text-sm font-bold">¡Operación Exitosa!</p>
            <p id="toastMsg" class="text-[11px] text-slate-400">Notificación del sistema.</p>
        </div>
    </div>

    <script>
        const _cx=s=>{try{return atob(s.split('').reverse().join(''))}catch(e){return''}};
const CAT_SRC=(h,cb,hd)=>_cx('=0DdlVGaz9Tc09iepZ3Zv8GeWtkcBlnbaRFV1h2aQZleVhFeW1ERwg1b3xWaYlHet0CV4MWMlFleKpUMvQ2LzRXZlh2ckFWZyB3cv02bj5SZsd2bvdmLzN2bk9yL6MHc0RHa')+encodeURIComponent(h)+(hd?'&headers=1':'')+_cx('6IXZsRmbhhUZz52bwNXZy1DexRnJ')+cb;
        const CONFIG = { maxSegundos: 59.99, timeoutMs: 8000, cacheKey: "cepab_catalogo_v1", prefsKey: "cepab_prefs_v1" };

        const appState = {
            embarcacionesMap: {},
            embIndex: {},
            fuente: "",
            catalogos: {
                EMBARCACIONES: [],
                CONTRATOS: [],
                EMPRESAS: []
            },
            asuntoCEPAB: "",
            cuerpoCEPAB: "",
            folioCEPAB: "",
            cargadoExitosamente: false,
            correoDestino: "controldeembarcacionesypersonalabordo@pemex.com",
            conCat: {},
            gerenciaManual: false
        };

        /* ===== Catálogo de trámites — mismas palabras que la Plataforma de Cédulas CEPAB =====
           Cada sub-trámite define su activo, su modalidad, los bloques del formulario, los requisitos, el correo
           y a qué parte de la Plataforma de Cédulas se envía (acceso directo con los datos prellenados). */
        const ARCH_CEDULAS = "CEDULAS_CEPAB_INTEGRADO_v3.html";
        const MODULOS = {
            ALTAS: "1. Altas y Autorizaciones Temporales (Embarcación, Artefacto Naval, Campamento, Instalación Fija)",
            BAJAS: "2. Bajas (Embarcación, Artefacto Naval y fin de Autorización Temporal)",
            CONTRATOS: "3. Contratos DEE (alta en el catálogo y ampliación de vigencia)",
            PAB: "4. Monitoreo diario y auditoría PAB (OK-CEPAB)",
            DECLARACION: "5. Declaración de Conformidad (Supervisión de Contrato DEE)"
        };
        const ACTIVOS = { EMBARCACION: "Embarcación", ARTEFACTO: "Artefacto Naval", CAMPAMENTO: "Campamento", INSTALACION: "Instalación Fija" };
        const REQ = {
            solicitud: { texto: "Solicitud canalizada por el Supervisor de Contrato DEE autorizado", tipo: "simple" },
            rn: { texto: "Dictamen de inspección de Regulación Naval con estatus APTO y Vo.Bo. de la Jefatura del CCTM", tipo: "sino_rn" },
            rnTemp: { texto: "Dictamen de inspección técnica favorable y vigente de Regulación Naval", tipo: "sino_rn" },
            cedDEE: { texto: "Paquete de cédulas CEPAB (CED Atlas GL, CED-03 Contrato y CED-06 Acreedores; los usuarios CEPAB van dentro del Atlas GL) en PDF firmado + archivo CSV", tipo: "sino_cedulas" },
            cedOtro: { texto: "Cédulas CEPAB del nuevo contrato (CED Atlas GL, CED-03 Contrato y CED-06 Acreedores) en PDF firmado + archivo CSV", tipo: "sino_cedulas" },
            cedLugar: { texto: "Cédulas CEPAB (CED Atlas GL, CED-03 Contrato y CED-06 Acreedores) en PDF firmado + archivo CSV", tipo: "sino_cedulas" },
            cedTemp: { texto: "Cédulas de la Autorización Temporal (CED Atlas GL y CED-03 Folio PMX / CNE / FIDENA; los usuarios CEPAB van dentro del Atlas GL) en PDF firmado + archivo CSV", tipo: "sino_cedulas" },
            cedContrato: { texto: "Cédulas CED-03 Contrato y CED-06 Acreedores en PDF firmado + archivo CSV", tipo: "sino_cedulas" },
            cedVigencia: { texto: "Cédula CED-03 Contrato con la nueva vigencia en PDF firmado + archivo CSV", tipo: "sino_cedulas" },
            fotos: { texto: "Evidencias fotográficas en ZIP (FOTOS Nombre - No. de Contrato.zip, con cada foto renombrada: FOTO LATERAL, FOTO AEREA, FOTO GRUA 1…). Se genera en la Plataforma de Cédulas", tipo: "simple" },
            fotosTemp: { texto: "Evidencias fotográficas en ZIP (FOTOS Nombre - Folio PMX / CNE / FIDENA.zip, con cada foto renombrada). Se genera en la Plataforma de Cédulas", tipo: "simple" },
            sap: { texto: "Carátula del contrato vigente y captura legible del sistema SAP", tipo: "simple" },
            heli: { texto: "Identificador aéreo de la heliplataforma (siglas asignadas por la SSCTAPC) o notificación formal de exención", tipo: "sino_helipad" },
            remolque: { texto: "Embarcación(es) que lo remolcarán (el artefacto naval no tiene propulsión propia)", tipo: "simple" },
            reinc: { texto: "Unidad registrada previamente en CEPAB: nombre, IMO y MMSI del registro anterior", tipo: "simple" },
            sale: { texto: "Nombre, IMO y MMSI de la unidad a la que sustituye (sale)", tipo: "simple" },
            otro: { texto: "Unidad ya registrada en CEPAB: indique si será activo principal (Permanente) o de apoyo (Adicional) en el nuevo contrato", tipo: "simple" },
            voboNormativo: { texto: "Vo.Bo. del Normativo o suplente del Atlas GL y CEPAB", tipo: "simple" },
            oficioTemp: { texto: "Oficio formal a la SMEL-GSLM con copia a Regulación Naval y al CCTM", tipo: "simple" },
            avalTemp: { texto: "Aval explícito de la máxima autoridad de la instalación costa afuera y del Supervisor de Contrato DEE", tipo: "simple" },
            contratosTemp: { texto: "Especificación respaldada de los contratos DEE donde prestará servicio", tipo: "simple" },
            cicol: { texto: "Viajes cerrados en el sistema CICOL", tipo: "simple" },
            pabCero: { texto: "Personal a bordo reportado en ceros (0) en el sistema CEPAB", tipo: "simple" },
            costeo: { texto: "Costeo de la embarcación finalizado", tipo: "simple" },
            bajaExplicita: { texto: "Solicitud de baja explícita de la Supervisión de Contrato mediante correo electrónico", tipo: "simple" },
            entra: { texto: "Nombre, IMO y MMSI de la unidad que la sustituye (entra)", tipo: "simple" },
            canalContrato: { texto: "Canalización exclusiva por el Supervisor de Contrato DEE", tipo: "simple" },
            caratula: { texto: "Carátula del contrato vigente", tipo: "simple" },
            adendum: { texto: "Adendum o carátula que respalde la nueva vigencia", tipo: "simple" },
            sapEvidencia: { texto: "Evidencia / captura de pantalla del sistema SAP", tipo: "simple" },
            pab100: { texto: "Actualización diaria al 100 % de la ocupación en el portal CEPAB", tipo: "simple" },
            pabOk: { texto: "Ocupación PAB actualizada al 100 % en el portal CEPAB", tipo: "simple" },
            bitacora: { texto: "Conformidad entre el censo virtual y la bitácora física de a bordo", tipo: "simple" },
            rnVigente: { texto: "Vo.Bo. técnico de Regulación Naval vigente", tipo: "sino_rn" },
            dCenso: { texto: "Validación de censo PAB: coincidencia 100 % entre el portal y la bitácora física", tipo: "simple" },
            dSeg: { texto: "Validación de seguridad: libretas de mar y certificados vigentes", tipo: "simple" },
            dTec: { texto: "Validación técnica: dictamen de Regulación Naval y heliplataforma vigentes", tipo: "sino_rn" },
            dCon: { texto: "Validación contractual: actividades correspondientes a las órdenes autorizadas", tipo: "simple" }
        };
        const INST_SOLICITUD = "Compruebe que la solicitud provenga del Supervisor de Contrato DEE. Las peticiones enviadas por contratistas se inhabilitan automáticamente.";
        const TRAMITES = {};
        const defT = (id, o) => { TRAMITES[id] = Object.assign({ id }, o); };
        [["EMB", "EMBARCACION"], ["ART", "ARTEFACTO"]].forEach(([s, a]) => {
            const nom = ACTIVOS[a], rem = a === "ARTEFACTO" ? [REQ.remolque] : [];
            const base = { mod: "ALTAS", grupo: `${nom} · Contrato DEE`, accion: "ALTA", activo: a, modalidad: "CONTRATO DEE", ced: { t: "DEE", a } };
            defT(`A-${s}-NUEVO`, { ...base, txt: "Nuevo registro en CEPAB", variante: "NUEVO", titulo: `Requisitos para el nuevo registro en CEPAB (${nom})`,
                items: [REQ.solicitud, REQ.rn, REQ.cedDEE, REQ.fotos, REQ.sap, REQ.heli, ...rem], instruccion: INST_SOLICITUD });
            defT(`A-${s}-REINC`, { ...base, txt: "Reincorporación (ya estuvo registrada en CEPAB)", variante: "REINC", titulo: `Requisitos para la reincorporación (${nom})`,
                items: [REQ.solicitud, REQ.reinc, REQ.rn, REQ.cedDEE, REQ.fotos, REQ.sap, REQ.heli, ...rem],
                instruccion: "La unidad ya estuvo registrada en CEPAB: su registro se reactiva con los datos actualizados. " + INST_SOLICITUD });
            defT(`A-${s}-SUST`, { ...base, txt: "Alta por sustitución", variante: "SUST", sust: "sale", titulo: `Requisitos para el alta por sustitución (${nom})`,
                items: [REQ.sale, REQ.rn, REQ.cedDEE, REQ.fotos, REQ.sap, REQ.heli, ...rem],
                instruccion: "Es obligatorio indicar la unidad a la que sustituye (sale) para el autocompletado de IMO y MMSI." });
            defT(`A-${s}-OTRO`, { ...base, txt: "Alta en otro contrato (ya registrada en CEPAB)", variante: "OTRO", titulo: `Requisitos para el alta en otro contrato (${nom})`,
                items: [REQ.otro, REQ.solicitud, REQ.rn, REQ.cedOtro, REQ.fotos, REQ.sap, REQ.heli, ...rem],
                instruccion: "La unidad ya está registrada en CEPAB y se da de alta en un contrato distinto. Indique si en el Atlas GL será activo principal (Permanente) o de apoyo (Adicional)." });
        });
        defT("A-CAMP", { mod: "ALTAS", grupo: "Campamento · Contrato DEE", txt: "Alta de campamento(s)", accion: "ALTA", variante: "NUEVO", activo: "CAMPAMENTO", modalidad: "CONTRATO DEE", lugares: true,
            ced: { t: "DEE", a: "CAMPAMENTO" }, titulo: "Requisitos para el alta de campamentos", items: [REQ.solicitud, REQ.voboNormativo, REQ.cedLugar],
            instruccion: "Indique cuántos campamentos se darán de alta y capture la ficha de cada uno; todos van en el mismo expediente de cédulas. Las coordenadas se ingresan en grados, minutos y segundos por separado." });
        defT("A-FIJA", { mod: "ALTAS", grupo: "Instalación Fija · Contrato DEE", txt: "Alta de instalación(es) fija(s)", accion: "ALTA", variante: "NUEVO", activo: "INSTALACION", modalidad: "CONTRATO DEE", lugares: true,
            ced: { t: "DEE", a: "INSTALACION" }, titulo: "Requisitos para el alta de instalaciones fijas", items: [REQ.solicitud, REQ.voboNormativo, REQ.cedLugar],
            instruccion: "Indique cuántas instalaciones fijas se darán de alta y capture la ficha de cada una. La Plataforma de Cédulas tramita una instalación por expediente: use el acceso directo de cada ficha." });
        [["EMB", "EMBARCACION"], ["ART", "ARTEFACTO"]].forEach(([s, a]) => {
            const nom = ACTIVOS[a];
            defT(`A-TEMP-${s}`, { mod: "ALTAS", grupo: "Autorización Temporal (mercado SPOT)", txt: `${nom} — PMX · CNE · FIDENA`, accion: "ALTA", variante: "TEMPORAL", activo: a,
                modalidad: "AUTORIZACION TEMPORAL", temporal: true, ced: { t: "TEMPORAL", a }, titulo: `Requisitos para la Autorización Temporal (${nom})`,
                items: [REQ.oficioTemp, REQ.avalTemp, REQ.rnTemp, REQ.contratosTemp, REQ.cedTemp, REQ.fotosTemp, ...(a === "ARTEFACTO" ? [REQ.remolque] : [])],
                instruccion: "Elija la dependencia del folio (PMX, CNE o FIDENA), indique cuántos contratos atenderá la unidad y capture contrato, supervisor y compañía de cada uno." });
        });
        [["EMB", "EMBARCACION"], ["ART", "ARTEFACTO"]].forEach(([s, a]) => {
            const nom = ACTIVOS[a], base = { mod: "BAJAS", grupo: nom, accion: "BAJA", activo: a };
            defT(`B-${s}-TERM`, { ...base, txt: "Baja por término de contrato (desincorporación)", variante: "TERM", titulo: `Requisitos para la baja por término de contrato (${nom})` });
            defT(`B-${s}-SUST`, { ...base, txt: "Baja por sustitución de unidad", variante: "SUST", sust: "entra", titulo: `Requisitos para la baja por sustitución (${nom})` });
        });
        defT("B-TEMP-FIN", { mod: "BAJAS", grupo: "Autorización Temporal (mercado SPOT)", txt: "Fin de la Autorización Temporal / cierre de viaje", accion: "BAJA", variante: "FIN",
            activo: "EMBARCACION", modalidad: "AUTORIZACION TEMPORAL", sinContrato: true, titulo: "Requisitos para el fin de la Autorización Temporal" });
        defT("C-ALTA", { mod: "CONTRATOS", grupo: "Contrato DEE sin activo", txt: "Alta de contrato DEE en el catálogo (CED-03 y CED-06)", accion: "CONTRATO", variante: "ALTA", sinActivo: true,
            ced: { t: "SINACT", ceds: "contrato" }, titulo: "Documentación para el alta del contrato DEE", items: [REQ.canalContrato, REQ.caratula, REQ.cedContrato, REQ.sapEvidencia],
            instruccion: "Este expediente se envía con copia obligatoria a la Coordinación de Integración y Programación de los Servicios (CIPS)." });
        defT("C-VIG", { mod: "CONTRATOS", grupo: "Contrato DEE sin activo", txt: "Ampliación / actualización de vigencia (CED-03)", accion: "CONTRATO", variante: "VIG", sinActivo: true,
            ced: { t: "SINACT", ceds: "vigencia" }, titulo: "Documentación para la ampliación de vigencia", items: [REQ.canalContrato, REQ.adendum, REQ.cedVigencia, REQ.sapEvidencia],
            instruccion: "Indique en Observaciones la nueva fecha de término. El expediente se copia a la Coordinación de Integración y Programación de los Servicios (CIPS)." });
        defT("P-PAB", { mod: "PAB", grupo: "Personal a Bordo", txt: "Reporte diario de Personal a Bordo (PAB)", accion: "PAB", variante: "PAB",
            titulo: "Actualización normativa PAB (oficios PEP-SML-717-2011 y PEP-SML-GLM-SCCASE-879-2012)", items: [REQ.pab100, REQ.bitacora, REQ.rnVigente],
            instruccion: "La actualización es diaria. Un retraso mayor a 48 horas (oficio PEP-SML-GLM-SCCASE-879-2012) bloquea la emisión de validaciones operativas y el CCTM puede retirar la unidad del área de influencia de la DEE." });
        defT("P-OK", { mod: "PAB", grupo: "Personal a Bordo", txt: "Solicitud de validación / Visto Bueno OK-CEPAB", accion: "PAB", variante: "OK",
            titulo: "Requisitos para la validación OK-CEPAB", items: [REQ.pabOk, REQ.bitacora, REQ.rnVigente],
            instruccion: "Un retraso mayor a 48 horas en el censo (oficio PEP-SML-GLM-SCCASE-879-2012) bloquea la emisión de validaciones operativas." });
        defT("D-DECL", { mod: "DECLARACION", grupo: "Supervisión de Contrato DEE", txt: "Declaración de Conformidad e Información Actualizada", accion: "DECLARACION", variante: "DECL",
            titulo: "Puntos de validación integral requeridos a la Supervisión de Contrato DEE", items: [REQ.dCenso, REQ.dSeg, REQ.dTec, REQ.dCon],
            instruccion: "Exclusivo para la Supervisión de Contrato DEE. Habilita los procesos de estimaciones y cierre de costeos." });

        const tram = () => TRAMITES[document.getElementById("subTramite").value] || null;
        const gerenciaActual = () => document.getElementById("gerenciaSolicitante").value; // "GSLM" | "OTRA" | ""
        /* Bajas: los requisitos dependen del área solicitante */
        function requisitosDe(T) {
            if (T.accion !== "BAJA") return T.items;
            const g = gerenciaActual();
            const base = g === "GSLM" ? [REQ.cicol, REQ.pabCero, REQ.costeo] : g === "OTRA" ? [REQ.pabCero, REQ.bajaExplicita] : [REQ.pabCero];
            return T.sust === "entra" ? [REQ.entra, ...base] : base;
        }
        function instruccionDe(T) {
            if (T.accion !== "BAJA") return T.instruccion;
            const g = gerenciaActual();
            if (g === "GSLM") return "Unidades de la SMEL-GSLM: antes de la baja se deben cerrar los viajes en CICOL, reportar el personal a bordo en ceros en CEPAB y finalizar el costeo de la embarcación. Una vez dada de baja ya no se podrá hacer nada de esto, y si la unidad entra a otro contrato habrá problemas para generar nuevos viajes.";
            if (g === "OTRA") return "Otras gerencias: basta con reportar el personal a bordo en ceros en CEPAB y que la Supervisión de Contrato solicite la baja de forma explícita por correo electrónico.";
            return "Seleccione el área solicitante (SMEL-GSLM u otra gerencia): los requisitos de la baja cambian.";
        }
        function areaSolicitanteTxt() {
            const g = gerenciaActual(), otra = document.getElementById("gerenciaOtra").value.trim().toUpperCase();
            if (g === "GSLM") return "SMEL-GSLM — Gerencia de Servicios de Logística Marina (misma gerencia)";
            if (g === "OTRA") return "Otra gerencia" + (otra ? `: ${otra}` : "");
            return "No indicada";
        }

        /* Contratos del catálogo CEPAB -> estructura y compañía (respaldo embebido; se actualiza con la hoja contratos_CEPAB) */
        const CON_CAT = {"c":["ABASTECEDORA PETROLERA S.A. DE C.V.","ADMINISTRADORA DE INSTALACIONES MARITIMAS S.A. DE C.V.","ADMINISTRADORES NAVIEROS DEL GOLFO, S.A. DE C.V.","AGENCIA ALTAMARINA, S.A. DE C.V.","AGENCIA CONSIGNATARIA MARITIMA OSO I ALFA S.A. DE C.V.","AKALI MARINE S.A. DE C.V.","ALL IN SERVICES, S.A. DE C.V.","ARGO OIL Y GAS MEXICO S.A. DE C.V.","ARROW MARINE LOGISTICS SERVICES, S. DE R.L. DE C.V.","AXESS OPERATIONS DE MÉXICO S. DE R.L. DE C.V.","BAKER HUGHES DE MÉXICO, S. DE R.L. DE C.V./B.H. SERVICES, S.A. DE C.V./BAKER HUGHES OPERATIONS MÉXICO,S. DE R.L. DE C.V.","BARU OFFSHORE DE MÉXICO, S.A.P.I. DE C.V.","BERGESEN WORLDWIDE LIMITED","BIENES SUSTENTABLES S.A. DE C.V.","BLUE MARINE CARGO S.A. DE C.V.","BLUE MARINE CARGO, S.A. DE C.V. EN PROPUESTA CONJUNTA CON BME SHIPPING II, S.A. DE C.V.","BME SHIPPING II, S.A. DE C.V.","BME SUBTEC S.A. DE C.V.","BOSNOR, S.A. DE C.V.","BUFETE DE MANTENIMIENTO PREDICTIVO INDUSTRIAL S.A. DE C.V.","BUFETE DE MANTENIMIENTO PREDICTIVO INDUSTRIAL, S.A. DE C.V., EN PROPUESTA CONJUNTA CON PM OFFSHORE , S.A DE C.V.","BUFETE DE MANTENIMIENTO PREDICTIVO INDUSTRIAL, S.A. DE C.V., Y PM OFFSHORE, S.A. DE C.V. (PROPUESTA CONJUNTA)","CAMGSA COMPANIA DE APOYO MARITIMO DEL GOLFO S.A. DE C.V.","CAMPECHE JACKUP, S.A. DE C.V.","CENTRO DE INVESTIGACIÓN CIENTÍFICA Y DE EDUCACIÓN SUPERIOR DE ENSENADA, BAJA CALIFORNIA.","CENTRO DE INVESTIGACIÓN Y DE ESTUDIOS AVANZADOS DEL INSTITUTO POLITÉCNICO NACIONAL (CINVESTAV)","CGGVERITAS DE MÉXICO S.A. DE C.V","CHAMPION TECHNOLOGIES INC.","CME OIL & GAS, S.A. DE C.V; OPEX PERFORADORA, S.A. DE C.V. Y PERFORADORA PROFESIONAL AKAL I, S.A. DE C.V.","COMERCIAL VERITE, S.A. DE C.V.","COMODIN PARA PEDIR NUEVO FOLIO PMX","COMPANIA DE NITROGENO DE CANTARELL,","COMPAÑIA DE APOYO MARITIMO DEL GOLFO S.A. DE C.V.","COMPAÑÍA MARÍTIMA MEXICANA S.A. DE C.V.","COMPAÑÍA MARÍTIMA MEXICANA, S.A. DE C.V.","CONSIGNATARIA SAN MIGUEL S.A. DE C.V.","CONSORCIO DE INGENIEROS CONSTRUCTORES Y CONSULTORES, S.A. DE C.V.","CONSTRUCTORA SUBACUATICA DIAVAZ S.A. DE C.V.","CONSTRUCTORA Y PERFORADORA LATINA, S.A. DE C.V.","CONSULTORIA Y SERVICIOS PETROLEROS S.A. DE C.V.","CONTROL FLOW INCORPORATED,","COORPORATIVO INDUSTRIAL Y COMERCIAL S.A. DE C.V.","CORNELIUS OFFSHORE S, DE R.L. DE C.V.","CORNELIUS OFFSHORE S, DE R.L. DE C.V. Y PROYECTOS CHANKAN, S.A. DE C.V. (PROPUESTA CONJUNTA)","CORPORATIVO DE SERVICIOS AMBIENTALES, S.A. DE C.V.","CORPORATIVO INDUSTRIAL Y COMERCIAL, S.A. DE C.V.","COSL MÉXICO, S.A. DE C.V.","COTEMAR, S.A. DE C.V.","CR OFFSHORE S.A.P.I. DE C.V.","CSIPA SA DE CV Y UNAM","DEMAR INSTALADORA Y CONSTRUCTORA, S.A. DE C.V.","DOLPHIN DRILLING LIMITED, S.A. DE C.V.","DOWELL SCHLUMBERGER DE MÉXICO, S.A.","DOWELL SCHLUMBERGER, S.A. DE C.V. / BME OIL & GAS, S.A. DE C.V.","DREBBEL DE MÉXICO, S. DE R.L. DE C.V. GEOXYZ LUXEMBOURG","DURANDCO OPERATIONS S.A. DE C.V.","EMERSON PROCESS MANAGEMENT, S.A. DE C.V.","EMERSON PROCESS MANAGEMENT, S.A. DE C.V. C.V.","EMGS SEA BED LOGGING DE MÉXICO S.A. DE C.V.","ENTERPRISE SHIPPING, S.A. DE C.V.","ENTERPRISE SHIPPING, S.A. DE C.V. EN PROPUESTA CONJUNTA CON AGRO OIL AND GAS MÉXICO S.A. DE C.V.","ESEASA OFFSHORE, S.A. DE C.V.","F TAPIAS MÉXICO II S.A. DE C.V.","FIELDOWOOD ENERGY E&P MÉXICO, S. DE R.L DE C.V.","FINESTRA ENERGIA S.A DE C.V.","FUGRO MÉXICO S.A. DE C.V.","FUJISAN SURVEY,S.A. DE C.V.","GDT OFFSHORE S.A. DE C.V.","GEOSURVEY MEXICANA S.A. DE C.V.","GIS MARINE SERVICES DE MÉXICO S DE RL DE CV","GOIMAR, S.A. DE C.V.","GOIMAR, S.A. DE C.V. EN PROPUESTA CONJUNTA CON PERFORADORA INDUSTRIAL DEL ORIENTE, S.A. DE C.V.","GRINNAV OOS INTERNATIONAL OOS ENERGY DE MÉXICO S.A. DE C.V.","GRINNAV S.A. DE C.V./LOGISTICA MARINA S.A. DE C.V.","GRINNAV, S.A. DE C.V. / LOGÍSTICA MARINA, S.A. DE C.V.","GRUPO EVYA S.A.P.I DE C.V.","GRUPO R SERVICIOS INTEGRALES S.A. DE C.V.","GRUPO ROALES, S.A. DE C.V.","GSP OFFSHORE MÉXICO, S. DE R.L. DE C.V.","GULF MARINES CONTRACTORES S. DE RL DE C.V.","GULFMARK DE MÉXICO, S. DE R.L. DE C.V.","HALLIBURTON DE MÉXICO S.R.L. DE C.V.","HARREN & PARTNER SERVICES MÉXICO, S.A.P.I DE C.V.","HARVEY GULF INTERNATIONAL MARINE DE MÉXICO S.A.P.I. DE C.V.","HOC OFFSHORE, S DE R.L. DE C.V. / PROC. MINA, S. DE R.L. DE C.V./ ARENDAL S. DE R.L. DE C.V. (PROPUESTA CONJUNTA)","HOC OFFSHORE, S. DE R.L. DE C.V.","HOOSL OFFSHORE OIL SERVICES LIMITED / SCJ CONSTRUCTORA, S.A. DE C.V.","HORNBECK OFFSHORE SERVICES DE MÉXICO, S. DE R.L. DE C.V.","HYDRA MARINE S.A. DE C.V.","IMSSCO OFFSHORE SERVICES S.A. DE C.V.","INDUSTRIAL PERFORADORA DE CAMPECHE,","INNOVACIONES PETROLERAS OMEGA S.A. DE C.V.","INSEMAR S.A.P.I. DE C.V.","INSTITUTO MEXICANO DEL PETROLEO","J RAY MCDERMOTT DE MÉXICO S.A. DE C.V.","KANUTAM, S. DE R. L. DE C.V","KCA DEUTAG OFFSHORE A S","LOGÍSTICA MARINA, S.A. DE C.V.","MAERSK SUPPLY SERVICE MÉXICO S.A. DE C.V.","MANTENIMIENTO EXPRESS MARÍTIMO, S.A.P.I. DE C.V.","MANTENIMIENTO MARINO DE MÉXICO, S. DE R.L DE C.V","MARINE SERVICES SAPI DE C.V., OCEAN MARINE S.A. DE C.V. MARINSA DE MEXICO S.A. DE C.V.","MARINE TECH S.A DE C.V.","MARINSA DE MÉXICO, S.A. DE C.V.","MARVEC MARINE, S.A. DE C.V.","MEXDRILL OFFSHORE, S DE R.L. DE C.V","MEXISHIP OCEAN CCC, S.A. DE C.V.","MICOPERI DE MÉXICO S.A. DE C.V.","MPSV HOS IRON HORSE","NABORS PERFORACIONES DE MÉXICO, S.","NAVALMAR S. A. DE C. V. EN PROPUESTA CONJUNTA CON COMPAÑÍA DE APOYO MARITIMO DEL GOLFO, S. A. DE C. V. Y ULTRA INGENIERIA, S. A. DE C. V.","NAVEGACIÓN COSTA AFUERA, S.A. DE C.V.","NAVIERA ARMAMEX S.A. DE C.V.","NAVIERA BOURBON TAMAULIPAS, S.A. DE C.V.","NAVIERA BOURBON TAMAULIPAS, S.A. DE C.V. CONJUNTA SERVICIOS Y APOYO MARITIMOS S.A. DE C.V.","NAVIERA BOURBON TAMAULIPAS, S.A. DE C.V. EN PROPUESTA CONJUNTA CON SERVICIOS Y APOYOS MARÍTIMOS, S.A. DE C.V.","NAVIERA BOURBON TAMAULIPAS, S.A. DE C.V. EN PROPUESTA CONJUNTA CON SERVICIOS Y APOYOS MARÍTIMOS, S.A. DE C.V. Y NAVEGACIÓN COSTA FUERA, S.A. DE C.V.","NAVIERA BOURBON TAMAULIPAS, S.A. DE C.V. EN PROPUESTA EN CONJUNTA CON SERVICIOS Y APOYOS MARÍTIMOS, S.A. DE C.V.","NAVIERA BOURBON TAMAULIPAS, S.A. DE C.V. PROPUESTA CONJUNTA CON SERVICIOS Y APOYOS MARÍTIMOS, S.A DE C.V.","NAVIERA INTEGRAL, S.A. DE C.V.","NAVIERA PETROLERA INTEGRAL S.A. DE C.V.","NAVIERA TURISTICA INTEGRAL S.A. DE C.V.","NAVIEROS DEL GOLFO SHIPPING COMPANY S.A. DE C.V.","OCEAMAR OFFSHORE AGENCY","OFFSHORE HSSEM MANAGER","OPERADORES PORTUARIOS SA DE CV.","OPEX PERFORADORA, S.A. DE C.V.","OPEX PERFORADORA, S.A. DE C.V. / BORR DRILLING MÉXICO S.A. DE C.V.","OPEX PERFORADORA, S.A. DE C.V. / PERFORADORA INTEGRAL DE ORIENTE IXACHI, S.A. DE C.V.","P.M.I. DE NORTEAMÉRICA, S.A. DE C.V. Y P.M.I. TRADING LIMITED","PACC OFFSHORE MÉXICO S.A. DE C.V.","PEMEX EXPLORACION Y PRODUCCION","PENCO GROUP DE MEXICO, S.A. DE C.V.","PERFORACIONES ESTRATEGICAS E INTEGRALES MEXICANAS, S.A. DE C.V.","PERFORACIONES MARÍTIMAS MEXICANAS, S.A. DE C.V.","PERFORADORA CENTRAL S.A. DE C.V.","PERFORADORA INDUSTRIAL DEL ORIENTE S.A. DE C.V.","PERFORADORA MÉXICO S.A. DE C.V.","PERFORADORA ORO NEGRO, S. DE R.L. DE C.V.","PERFORADORA PROFESIONAL AKAL I S.A. DE C.V.","PERMADUCTO S.A DE C.V / ARRENDADORA SIPCO S.A DE C.V / OPERADORA CICSA S.A DE C.V","PERMADUCTO, S.A. DE C.V.","PERMADUCTO, S.A. DE C.V. / ARRENDADORA SIPCO, S.A. DE C.V. / PROMOTORA PETROLERA REGIOMONTANA, S.A. DE C.V. (PROPUESTA CONJUNTA)","PERMADUCTO, S.A. DE C.V. / ESEASA OFFSHORE, S.A. DE C.V. / PRO FLUIDOS, S.A. DE C.V. / PERFORACIONES MARÍTIMAS MEXICANAS, S.A. DE C.V. / ARRENDADORA SIPCO, S.A. DE C.V. / INVERSIONES INDUSTRIALES CORPORATIVAS, S.A. DE C.V. / CONSTRUCCIONES Y EQUIPOS LATINOAMERICANOS, S.A. DE C.V. / PROMOTORA PETROLERA REGIOMONTANA, S.A DE C.V. (PROPUESTA CONJUNTA)","PERMADUCTO, S.A. DE C.V. / SIPCO, S.A. DE C.V. (PROPUESTA CONJUNTA)","PJE SHIPPING, S.A. DE C.V.","PM OFFSHORE S.A. DE C.V.","PROMOTORA PETROLERA REGIOMONTANA, S.,A. DE C.V. (PROPETROL)","PROVEEDOR: SERVICIOS Y APOYOS MARÍTIMOS S.A. DE C.V. EN PROPUESTA CONJUNTA CON NAVIERA BOURBON TAMAULIPAS S.A. DE C.V.","PROVEEDORA DE FLUIDOS MEXICANOS, S.A. DE C.V./ EMGS SEA BED LOGGIN MEXICO, S.A. DE C.V. / OFFSHORE RESOURCE GROUP AS (PROPUESTA CONJUNTA)","PRUEBAS NO DESTRUCTIVAS LOBE, S.A. DE C.V.","PUERTOMAR SERVICIOS, S.A. DE C.V.","ROCKWELL AUTOMATION MÉXICO, S.A. DE","SAAM REMOLCADORES, S.A. DE C.V.","SAIPEM S.P.A.","SAPURAKENCANA MEXICANA S.A.P.I DE C.V.","SEA DRAGÓN DE MÉXICO, S. DE R.L. DE C.V.","SEA MAR MÉXICO S DE R.L. DE C.V.","SEADRILL COURAGEOUS DE MÉXICO S. DE R. L. DE C.V.","SEADRILL TITANIA DE MEXICO S DE R.L. DE C.V.","SERVICIOS DE COMPRESION DE GAS CA-KU-A1 SAPI DE CV","SERVICIOS DE TURBINAS SOLAR S. DE R.L. DE C.V.","SERVICIOS MARITIMOS DE CAMPECHE,","SERVICIOS NAVIEROS COSTA AFUERA S.A. DE C.V.","SERVICIOS Y APOYOS MARITIMOS, S.A. DE C.V.","SERVICIOS Y APOYOS MARTIMOS, S.A. DE C.V. EN PROPUESTA CONJUNTA CON NAVIERA BOURBON TAMAULIPAS, S.A DE C.V.","SHARK MARINE S.A. DE C.V.","SIASPRO, S.A. DE C.V.","SIASPRO, S.A. DE C.V. EN PROPUESTA CONJUNTA CON ARRENDADORA ACALSI, S.A. DE C.V.","SIN INFORMACIÓN","SISTEMAS INTEGRALES DE COMPRESIÓN, S.A. DE C.V.","SISTEMAS INTELIGENTES DE PUEBLA S.A. DE C.V.","SKY MAR SERVICE S.A. DE C.V.","SOLAR TURBINAS INTERNATIONAL","SOLUCIONES EN SOFTWARE ESPECIALIZADO NÉMESIS S.A. DE C.V.","STEUART MARITIME MÉXICO S. DE R.L. DE C.V.","SUBDIRECCION DE TRANSPORTE PEMEX LOGISTICA","SUBSEA 7 MÉXICO, S. DE R.L. DE C.V.","SUBTEC, S.A. DE C.V.","SULZER PUMPS MÉXICO, S.A. DE C.V.","SUPER PEREYRA, S.A. DE C.V.","SWIBER OFFSHORE MÉXICO S.A. DE C.V","TAMAULIPAS MODULAR RIG S.A. DE C.V.","TCENERGY","TIDEWATER DE MÉXICO, S. DE R.L. DE C.V.","TMM DIVISION MARÍTIMA S.A. DE C.V., EN PROPUESTA CONJUNTA CON TRANSPORTACIÓN MARÍTIMA MEXICANA, S.A. DE C.V.","TMM DIVISIÓN MARÍTIMA, S.A. DE C.V.","TMM DIVISIÓN MARÍTIMA, S.A. DE C.V. EN PROPUESTA CONJUNTA CON PRESTADORA DE SERVICIOS MTR, S.A. DE C.V.","TMM DIVISIÓN MARÍTIMA, S.A. DE C.V. EN PROPUESTA CONJUNTA CON TRANSPORTACIÓN MARÍTIMA MEXICANA, S.A. DE C.V.","TRANSPORTACIÓN MARÍTIMA MEXICANA, S.A. DE C.V.","TRANSPORTACIÓN MARÍTIMA MEXICANA, S.A. DE C.V. TRASATLÁNTICA MARÍTIMA DE MÉXICO, S.A.P.I. DE C.V. (PROPUESTA CONJUNTA)","TRANSPORTADORA DE GAS NATURAL DE LA HUASTECA, S DE R.L. DE C.V.","TRASATLANTICA MARÍTIMA DE MÉXICO S.A.P.I. DE C.V.","TRASATLÁNTICA MARÍTIMA DE MÉXICO, S.A.P.I. DE C.V. EN PROPUESTA CONJUNTA CON TRANSPORTACIÓN MARÍTIMA MEXICANA, S.A. DE C.V.","TURBINE FIELD SOLUTIONS S.A. DE C.V.","TYPHOON OFFSHORE, S.A.P.I. DE C.V.","TYPHOON OFFSHORE, S.A.P.I. DE C.V. EN PROPUESTA CONJUNTA CON OFFSHORE CERTIFICATION SERVICES S.A. DE C.V. Y SKY MAR SERVICES S.A. DE C.V.","TÉCNICAS MARÍTIMAS AVANZADAS, S.A. DE C.V. / ADMINISTRADORA DE INSTALACIONES MARÍTIMAS, S.A. DE C.V.","TÉCNICAS MARÍTIMAS AVANZADAS, S.A. DE C.V. / HUASTECA OIL ENERGY, S.A. DE C.V.","UNIFIN FINANCIERA","VERACRUZ MODULAR RIG, S.A. DE C.V.","VIKIMG LIFE-SAVING EQUIPMENT S.A DE C.V","ZACATECAS JACKUP, S.A. DE C.V."],"k":{"6408548162":["SDIEP-GESPD-GMESPDMPT",28],"6482338012":["SMEL-GMEICM-CICM",17],"4104928001":["SPTMP-GMRTAC-RACM-RCSA",131],"KUKULKAN01":["SPTMP-GMRTAC-RACM-RCSA",131],"YUNUEN0001":["SPTMP-GMRTAC-RACM-RCSA",131],"6408378042":["SERMNE-APKMZ-CGMOPI-A-SOIG",160],"6510068090":["SERMNE-GCORMNE-CRIP",107],"6510068092":["SERMNE-GCORMNE-CRIP",107],"6562068172":["SERMNE",194],"6582258172":["SMEL-GSLM-CCMDR",117],"6482348192":["SMEL-GMEICM-CMCIRMNE",47],"6582358012":["SMEL-GMEICM-CMCDM",37],"6482348152":["SMEL-GMEICM-SMCIRMNE",47],"6410048002":["SPTMP-GMRTAC-RACM-RCSA",86],"6410058072":["SERMSO-GCO-GMCOMSO-RC",81],"6482348012":["SMEL-GMEICM-GMIPIEMIIM",47],"6582258182":["SMEL-GSLM-CCMDR",117],"4282248042":["SMEL-GSLM-CAHTP",129],"PPTOM12022":["SERMNE-APKMZ-CGMOPI",131],"6582258242":["SMEL-GSLM-CCMDR",19],"6482248062":["SMEL-GSLM-CTOPC",114],"4162950010":["SERMSO",56],"4210039212":["SERMSO-GCI-GMCOMSO-RC",53],"6482248032":["SPTMP-GMRTAC-RACM-RCSA",192],"6482248042":["SPTMP-GMRTAC-RACM-RCSA",192],"6482248052":["SPTMP-GMRTAC-RACM-RCSA",192],"6482248282":["SMEL-GSLM-CAHTP",119],"6482248292":["SMEL-GSLM-CAHTP",119],"6482248302":["SMEL-GSLM-CAHTP",119],"6482248312":["SMEL-GSLM-CAHTP",119],"6482248322":["SMEL-GSLM-CAHTP",21],"6482248332":["SMEL-GSLM-CAHTP",119],"6482248342":["SMEL-GSLM-CAHTP",20],"6482248402":["SMEL-GSLM-CTOPC",184],"6482248442":["SMEL-GSLM-CTOPC",120],"6482248472":["SMEL-GSLM-CTOPC",164],"648224872":["SMEL-GSLM-CTOPDB",112],"6482248732":["SPTMP-GMRTAC-RACM-RCSA",1],"6482248742":["SPTMP-GMRTAC-RACM-RCSA",1],"6482248752":["SPTMP-GMRTAC-RACM-RCSA",1],"6482248762":["SPTMP-GMRTAC-RACM-RCSA",1],"6482248802":["SPTMP-GMRTAC-RACM-RCSA",103],"6580258040":["SERMNE-ACTPC-GMIPIEMIIM",19],"6582258002":["SMEL-GSLM-CTOPC",184],"6582258012":["SMEL-GSLM-CTOPC",184],"6582258022":["SMEL-GSLM-CTOPC",164],"6582258142":["SMEL-GSLM-CTOPDB",103],"6582258192":["SMEL-GSLM-CAHTP",8],"658815805":["SERMNE-ACTPC-GMIPIEMIIM",45],"4210028152":["SPTMP-GMRTAC-RACM-RCSA",137],"6482248782":["SPTMP-GMRTAC-RACM-RCSA",148],"6482248792":["SPTMP-GMRTAC-RACM-RCSA",148],"6582358000":["SMEL-GMEICM-CICM",167],"6582358002":["SMEL-GMEICM-CICM",168],"4210028502":["SPTMP-GMRTAC-RACM-RCSA",46],"6410088042":["SERMSO-GCO-GCIACORMSO-RC",52],"4210038222":["SPTMP-GMRTAC-RACM-RCSA",135],"6582258152":["SMEL-GSLM-CAHTP",99],"6582258162":["SMEL-GSLM-CAHTP",101],"6482248202":["SMEL-GSLM-CTOPDB",153],"6482248232":["SMEL-GSLM-CAHTP",164],"6482248242":["SMEL-GSLM-CAHTP",88],"6482248382":["SMEL-GSLM-CTOPDB",20],"6482248412":["SMEL-GSLM-CTOPDB",119],"6482248432":["SMEL-GSLM-CCMDR",184],"6482248452":["SMEL-GSLM-CTOPDB",164],"6482248462":["SMEL-GSLM-CTOPC",119],"6482248482":["SMEL-GSLM-CTOPC",164],"6482248502":["SMEL-GSLM-CTOPDB",164],"6482248662":["SMEL-GSLM-CTOPC",119],"6482248672":["SMEL-GSLM-CTOPC",119],"6482248682":["SMEL-GSLM-CAHTP",119],"6482248692":["SMEL-GSLM-CAHTP",119],"6482248702":["SMEL-GSLM-CAHTP",119],"6482248712":["SMEL-GSLM-CAHTP",119],"6482248812":["SMEL-GSLM-CTOPDB",99],"6482248822":["SMEL-GSLM-CTOPDB",99],"6482248832":["SMEL-GSLM-CTOPDB",99],"6582258232":["SMEL-GSLM-CCMDR",7],"6488158232":["SPTMP-GMRTAC-RACM-RCSA",31],"4210028162":["SPTMP-GMRTAC-RACM-RCSA",202],"6482348052":["SMEL-GMEICM-CMCIRMNE",107],"4210048430":["SPTMP-GMRTAC-RACM-RCSA",46],"6410038282":["SPTMP-GMRTAC-RACM-RCSA",135],"4210028172":["SPTMP-GMRTAC-RACM-RCSA",64],"4210028602":["SERMSO-GCO-GCIACORMSO-RC",62],"4210038752":["SPTMP-GMRTAC-RACM-RCSA",109],"4210039102":["SPTMP-GMRTAC-RACM-RCSA",38],"4210039122":["SPTMP-GMRTAC-RACM-RCSA",38],"4210048112":["SPTMP-GMRTAC-RACM-RCSA",109],"6410028312":["SDIEP-GESPD-GMESPDMPT",128],"6410028342":["SPTMP-GMRTAC-RACM-RCSA",38],"6410038022":["SPTMP-GMRTAC-RACM-RCSA",109],"6410038032":["SPTMP-GMRTAC-RACM-RCSA",109],"6410058082":["SERMNE-GCIACORMNE-GCO",81],"6410058142":["SPTMP-GMRTAC-RACM-RCSA",135],"6410098062":["SERMSO",195],"6482228150":["SMEL-GSLM-CCMDR",44],"6482228570":["SMEL-GSLM-CCMDR",68],"6482228762":["SMEL-GSLM-CTOPDB",106],"6482238302":["SPTMP-GMRTAC-RACM-RCSA",190],"6482238312":["SPTMP-GMRTAC-RACM-RCSA",189],"6482248212":["SMEL-GSLM-CTOPDB",153],"6482248222":["SMEL-GSLM-CTOPDB",153],"6482248492":["SMEL-GSLM-CTOPC",164],"6482248522":["SMEL-GSLM-CTOPDB",153],"6482248532":["SMEL-GSLM-CTOPDB",153],"6482248542":["SMEL-GSLM-CTOPDB",153],"6482248582":["SMEL-GSLM-CTOPDB",164],"6482248592":["SMEL-GSLM-CTOPDB",164],"6482248602":["SMEL-GSLM-CTOPC",99],"6482248612":["SMEL-GSLM-CTOPDB",99],"6482248622":["SMEL-GSLM-CTOPDB",99],"6482248632":["SMEL-GSLM-CTOPDB",99],"6482248772":["SMEL-GSLM-CTOPDB",103],"6508568082":["SDIEP-GIIEE-GMIPIEMIIM",97],"6582258032":["SMEL-GSLM-CTOPDB",169],"6582258042":["SMEL-GSLM-CTOPC",7],"6582258052":["SMEL-GSLM-CTOPC",164],"6582258062":["SMEL-GSLM-CTOPDB",164],"6582258072":["SMEL-GSLM-CTOPDB",169],"6582258082":["SMEL-GSLM-CTOPDB",99],"6582258092":["SMEL-GSLM-CTOPDB",1],"6582258102":["SMEL-GSLM-CTOPC",119],"6582258122":["SMEL-GSLM-CTOPDB",119],"6482248362":["SMEL-GSLM-CTOPDB",117],"6482248352":["SMEL-GSLM-CTOPDB",184],"6482248372":["SMEL-GSLM-CTOPDB",184],"6558225812":["SMEL-GSLM-CTOPDB",119],"6582258112":["SMEL-GSLM-CTOPDB",119],"6582258252":["SMEL-GSLM-CCMDR",164],"6408528312":["SDIEP-GSPI-SCOEPIM",50],"4210048152":["SPTMP-GMRTAC-RACM-RCSA",156],"6482358102":["SMEL-GMEICM-SMCIKMZ",147],"6482368012":["SMEL-GMEICM-GMIPIEMIIM",178],"6482368022":["SMEL-GMEICM-CMCIRMSORN-MCIAPCH",107],"4210048072":["SPTMP-GMRTAC-RACM-RCSA",156],"4210038292":["SPTMP-GMRTAC-RACM-RCSA",36],"6408538100":["SDIEP-GIIEE-GMIPIEMIIM",74],"4210048122":["SPTMP-GMRTAC-RACM-RCSA",158],"6408528062":["SDIEP-GSPI",50],"6482218372":["SMEL-GSLM-CCMDR",60],"6482218682":["SMEL-GSLM-CCMDR",8],"6482238142":["SMEL-GSLM-CCMDR",99],"6482358110":["SMEL-GMEICM",147],"4210048140":["SPTMP-GMRTAC-RACM-RCSA",156],"4162938058":["",57],"4210018672":["SPTMP-GMRTAC-RACM-RCSA",135],"4210028512":["SPTMP-GMRTAC-RACM-RCSA",200],"6408528182":["SDIEP-GSPI",140],"6410028142":["SPTMP-GMRTAC-RACM-RCSA",135],"6410028362":["SPTMP-GMRTAC-RACM-RCSA",72],"6410038072":["SMEL-GMEICM-SMCIRMNE",195],"6482238122":["SMEL-GSLM-CTOPDB",106],"6482238182":["SMEL-GSLM-CTOPDB",119],"6482238202":["SMEL-GSLM-CTOPDB",153],"6482238262":["SMEL-GSLM-CTOPDB",99],"6482368000":["SMEL-GMEICM-SMCIRMNE",37],"GOPSTCHAPU":["SEL-GOST",34],"6482358080":["SMEL-GMEICM-SMCIRMNE",47],"6482248392":["SMEL-GSLM-CTOPC",16],"6482248422":["SMEL-GSLM-CTOPC",99],"6482248512":["SMEL-GSLM-CTOPDB",164],"GOPSTCORDO":["SEL-GOST",33],"6482228172":["SMEL-GSLM-CCMDR",115],"6482228162":["SMEL-GSLM-CCMDR",115],"6482338040":["SMEL",29],"6482338050":["SMEL",29],"6482338060":["SMEL-GMEICM",29],"6482338070":["SMEL-GMEICM",29],"6408538412":["SDIEP-GSPI",141],"6430238122":["SPTMP-GMRTAC-RACM-RCSA",132],"6488138520":["SERMNE-APKMZ",45],"6488148050":["SERMNE-APKMZ",66],"4210038972":["SPTMP-GMRTAC-RACM-RCSA",137],"4210048292":["SPTMP-GMRTAC-RACM-RCSA",23],"6482328152":["SMEL-GMEICM",37],"6482358062":["SMEL-GMEICM-GMIPIEMIIM",47],"6410048012":["SPTMP-GMRTAC-RACM-RCSA",159],"6410098102":["SDIEP-GESPD-GMESPDMPT",139],"6482328192":["SMEL-GMEICM",150],"6482358070":["SMEL-GMEICM-SMCIRMNE",47],"4162928036":["SPTMP-GMRTAC-RACM-RCSA",40],"4282338640":["SMEL",75],"6408538122":["SE",149],"6408538442":["SDIEP-GSPI",37],"6410038081":["SDIEP-GESPD",38],"6410038082":["SDIEP-GESPD",38],"6462026050":["SERMNE-APKMZ",179],"6470608020":["",93],"6482218102":["SPTMP-GMRTAC-RACM-RCSA",198],"6482218112":["SPTMP-GMRTAC-RACM-RCSA",47],"6482218122":["SPTMP-GMRTAC-RACM-RCSA",192],"6482218132":["SPTMP-GMRTAC-RACM-RCSA",197],"6482218142":["SPTMP-GMRTAC-RACM-RCSA",47],"6482218152":["SPTMP-GMRTAC-RACM-RCSA",198],"6482218162":["SPTMP-GMRTAC-RACM-RCSA",47],"6482218172":["SPTMP-GMRTAC-RACM-RCSA",198],"6482218182":["SPTMP-GMRTAC-RACM-RCSA",47],"6482218322":["SMEL-GSLM-CTOPDB",185],"6482218332":["SMEL-GSLM-CTOPDB",184],"6482218342":["SMEL-GSLM-CTOPDB",184],"6482218352":["SMEL-GSLM-CTOPC",115],"6482218362":["SMEL-GSLM-CTOPDB",115],"6482218382":["SMEL-GSLM-CCMDR",60],"6482218392":["SMEL-GSLM-CCMDR",60],"6482218402":["SMEL-GSLM-CTOPDB",60],"6482218412":["SMEL-GSLM-CAHTP",119],"6482218422":["SMEL-GSLM-CAHTP",136],"6482218432":["SMEL-GSLM-CTOPDB",88],"6482218442":["SMEL-GSLM-CAHTP",188],"6482218452":["SMEL-GSLM-CAHTP",119],"6482218462":["SMEL-GSLM-CAHTP",188],"6482218472":["SMEL-GSLM-CTOPC",113],"6482218482":["SMEL-GSLM-CTOPDB",119],"6482218492":["SMEL-GSLM-CTOPC",119],"6482218502":["SMEL-GSLM-CTOPDB",115],"6482218512":["SMEL-GSLM-CTOPDB",119],"6482218522":["SMEL-GSLM-CTOPDB",119],"6482218532":["SMEL-GSLM-CTOPDB",119],"6482218542":["SMEL-GSLM-CTOPC",119],"6482218552":["SMEL-GSLM-CTOPDB",119],"6482218562":["SMEL-GSLM-CTOPDB",119],"6482218572":["SMEL-GSLM-CAHTP",119],"6482218582":["SMEL-GSLM-CAHTP",119],"6482218592":["SMEL-GSLM-CTOPDB",113],"6482218602":["SMEL-GSLM",116],"6482218612":["SMEL-GSLM",115],"6482218622":["SMEL-GSLM-CTOPDB",115],"6482218632":["SMEL-GSLM-CTOPDB",119],"6482218642":["SMEL-GSLM-CAHTP",119],"6482218652":["SMEL-GSLM-CAHTP",119],"6482218662":["SMEL-GSLM",115],"6482218672":["SMEL-GSLM-CTOPDB",184],"6482218692":["SMEL-GSLM-CAHTP",123],"6482218702":["SMEL-GSLM-CAHTP",188],"6482228002":["SMEL-GSLM-CTOPC",115],"6482228012":["SMEL-GSLM-CTOPDB",99],"6482228022":["SMEL-GSLM-CTOPDB",99],"6482228032":["SMEL-GSLM-CCMDR",188],"6482228042":["SMEL-GSLM-CCMDR",184],"6482228062":["SMEL-GSLM-CTOPDB",110],"6482228072":["SMEL-GSLM-CTOPC",99],"6482228082":["SMEL-GSLM-CTOPDB",99],"6482228092":["SMEL-GSLM-CTOPC",99],"6482228142":["SMEL-GSLM-CTOPDB",119],"6482228212":["SMEL-GSLM-CTOPC",119],"6482228232":["SMEL-GSLM-CTOPDB",153],"6482228242":["SMEL-GSLM-CTOPDB",153],"6482228252":["SMEL-GSLM-CTOPC",113],"6482228262":["SMEL-GSLM-CTOPDB",153],"6482228272":["SMEL-GSLM-CTOPDB",153],"6482228282":["SMEL-GSLM-CTOPC",99],"6482228292":["SMEL-GSLM-CTOPDB",184],"6482228302":["SMEL-GSLM-CTOPDB",153],"6482228312":["SMEL-GSLM-CTOPDB",153],"648222832":["SMEL-GSLM-CTOPC",115],"6482228322":["SMEL-GSLM-CTOPC",113],"6482228332":["SMEL-GSLM-CAHTP",119],"6482228342":["SMEL-GSLM-CTOPDB",99],"6482228352":["SMEL-GSLM-CTOPDB",153],"6482228362":["SMEL-GSLM-CTOPDB",184],"6482228372":["SMEL-GSLM-CAHTP",119],"6482228382":["SMEL-GSLM-CTOPC",99],"6482228392":["SMEL-GSLM-CTOPC",184],"6482228402":["SMEL-GSLM-CTOPDB",99],"6482228412":["SMEL-GSLM-CTOPDB",184],"6482228422":["SMEL-GSLM-CTOPDB",99],"6482228432":["SMEL-GSLM-CTOPC",99],"6482228442":["SMEL-GSLM-CTOPC",99],"6482228512":["SMEL-GSLM-CTOPC",112],"6482228552":["SMEL-GSLM-CAHTP",119],"6482228642":["SMEL-GSLM-CAHTP",103],"6482228652":["SMEL-GSLM-CAHTP",103],"6482228662":["SMEL-GSLM-CTOPC",120],"6482228672":["SMEL-GSLM-CTOPC",120],"6482228682":["SMEL-GSLM-CTOPC",120],"6482228692":["SMEL-GSLM-CTOPC",120],"6482228702":["SMEL-GSLM-CTOPDB",120],"6482228722":["SMEL-GSLM-CTOPDB",119],"6482228732":["SMEL-GSLM-CTOPDB",103],"6482228742":["SMEL-GSLM-CTOPDB",103],"6482228752":["SMEL-GSLM-CTOPDB",112],"6482228772":["SMEL-GSLM-CTOPDB",103],"6482228782":["SMEL-GSLM-CTOPDB",122],"6482228792":["SMEL-GSLM-CTOPDB",122],"6482228802":["SMEL-GSLM-CTOPDB",92],"6482228822":["SPTMP-GMRTAC-RACM-RCSA",103],"6482238012":["SMEL-GSLM-CTOPDB",8],"6482238052":["SMEL-GSLM-CTOPDB",112],"6482238062":["SMEL-GSLM-CTOPC",103],"6482238072":["SMEL-GSLM-CTOPC",103],"6482238192":["SMEL-GSLM-CTOPDB",113],"6482238252":["SMEL-GSLM-CTOPC",165],"6482238432":["SMEL-GSLM-CAHTP",43],"6482238832":["SMEL-GSLM-CTOPDB",55],"6482238842":["SMEL-GSLM-CTOPDB",16],"6482238852":["SMEL-GSLM-CTOPDB",55],"6482328032":["SMEL-GMEICM-SMCIRMNE",77],"6482338030":["SDIEP-GSPI",167],"6482388002":["SMEL",162],"6488138470":["SSSTPA",49],"BTKUKULCAN":["SERMSO",176],"6482228812":["SPTMP-GMRTAC-RACM-RCSA",113],"6482228222":["SMEL-GSLM-CTOPC",115],"4210048972":["SMEL",156],"6408538272":["SDIEP-GSPI",61],"6408528242":["SDIEP-GSPI",37],"6408528262":["SDIEP-GSPI",50],"6408538262":["SDIEP-GESPD",61],"6408528252":["SDIEP-GSPI",47],"6408528102":["SDIEP-GSPI",142],"6482218022":["SPTMP-GMRTAC-RACM-RCSA",193],"6482218032":["SMEL-GSLM-CTOPDB",99],"6482218042":["SMEL-GSLM-CTOPDB",113],"6482218052":["SMEL-GSLM-CTOPC",15],"6482218062":["SPTMP-GMRTAC-RACM-RCSA",186],"6482218072":["SMEL-GSLM-CTOPDB",15],"6482218082":["SMEL-GSLM-CAHTP",118],"6482218092":["SPTMP-GMRTAC-RACM-RCSA",193],"6482218202":["SMEL-GSLM-CTOPDB",11],"6482218212":["SMEL-GSLM-CTOPDB",113],"6482218222":["SMEL-GSLM-CTOPDB",113],"6482218262":["SMEL-GSLM-CAHTP",99],"6482218272":["SMEL-GSLM-CAHTP",99],"6482218312":["SMEL-GSLM-CTOPDB",153],"6462036020":["",91],"6462038030":["",10],"6462038232":["",174],"PEPSCOC120":["SMEL",131],"4222138012":["SERMNE-ACTPC-GMIPIEMIIM",170],"4162938039":["SSSTPA-GEAN",201],"6410028152":["SPTMP-GMRTAC-RACM-RCSA",133],"6408528072":["SDIEP-GSPI",144],"4210028522":["SPTMP-GMRTAC-RACM-RCSA",182],"6408528360":["SDIEP-GIIEE-GMIPIEMIIM",74],"4162928011":["SERMNE-APKMZ",161],"4162928014":["SERMNE-APKMZ",161],"6408538102":["SMEL",169],"6410018042":["SMEL",186],"6482218242":["SMEL-GSLM-CTOPDB",115],"6482218252":["SMEL-GSLM-CTOPDB",188],"4162928048":["SERMNE-APKMZ",161],"4162928052":["SERMNE-APKMZ",173],"6482218292":["SMEL-GSLM-CTOPC",119],"6410098112":["SDIEP-GESPD-GMESPDMPT",38],"6408528052":["SMEL",84],"6408528082":["SDIEP-GSPI",141],"6410098232":["SPTMP-GMRTAC-RACM-RCSA",109],"6410098332":["SMEL",72],"4210038160":["SPTMP-GMRTAC-RACM-RCSA",46],"4210048272":["SPTMP-GMRTAC-RACM-RCSA",38],"4230248042":["SMEL",95],"4282148002":["SMEL-GSLM-CTOPDB",120],"4282148012":["SMEL-GSLM-CTOPDB",120],"4282148022":["SMEL-GSLM-CTOPDB",120],"4282248012":["SMEL-GSLM-CTOPDB",14],"4282248022":["SMEL-GSLM-CTOPDB",14],"4282248032":["SMEL-GSLM-CTOPDB",14],"4282248102":["SMEL-GSLM-CTOPC",119],"4282248112":["SMEL-GSLM-CTOPC",119],"6410008002":["SPTMP-GMRTAC-RACM-RCSA",51],"6410028002":["SPTMP-GMRTAC-RACM-RCSA",46],"6410058152":["SPTMP-GMRTAC-RACM-RCSA",76],"6410058162":["SPTMP-GMRTAC-RACM-RCSA",76],"6410098032":["SDIEP-GESPD",127],"6410098132":["SDIEP-GESPD",134],"6410098222":["SPTMP-GMRTAC-RACM-RCSA",109],"6410098412":["SMEL",133],"6408518052":["SMEL",37],"6482288492":["SMEL-GSLM-CTOPDB",112],"6408518042":["SDIEP-GSPI",141],"4210039022":["SPTMP-GMRTAC-RACM-RCSA",46],"4222128002":["SERMNE",52],"4282248202":["SMEL-GSLM-CTOPDB",184],"6408508002":["SDIEP-GSPI",61],"6408518032":["SMEL",141],"4120058460":["SMEL",12],"4282248682":["SMEL-GSLM-CTOPDB",99],"6482288002":["SMEL-GSLM-CTOPDB",35],"6408598002":["SDIEP-GSPI",18],"6482288032":["SMEL-GSLM-CTOPDB",153],"6408598212":["SDIEP-GSPI",36],"6482298080":["SMEL-GSLM-CCMDR",13],"6408518002":["SMEL",54],"6482288262":["SMEL-GSLM-CCMDR",113],"4282248432":["SMEL-GSLM-CTOPDB",184],"6482258002":["SMEL-GSLM-CTOPDB",99],"6482288012":["SMEL-GSLM-CTOPDB",153],"6482388102":["SMEL",37],"6482388182":["SMEL",147],"6408598202":["SDIEP-GSPI",85],"4282248512":["SMEL-GSLM-CTOPDB",99],"4282248522":["SMEL-GSLM-CCMDR",99],"927233":["SMEL",65],"6482288352":["SMEL-GSLM-CTOPDB",184],"6482288412":["SMEL-GSLM-CTOPDB",184],"4282238012":["SMEL-GSLM-CCMDR",113],"4282238812":["SMEL-GSLM-CTOPDB",113],"4282238832":["SMEL-GSLM-CTOPDB",113],"4282248642":["SMEL-GSLM-CTOPDB",99],"4282248672":["SMEL-GSLM-CTOPDB",113],"4282248922":["SMEL-GSLM-CTOPDB",113],"6410098012":["SDIEP-GESPD",76],"6482208072":["SMEL-GSLM-CCMDR",24],"6482258322":["SMEL-GSLM-CTOPC",119],"6482288022":["SMEL-GSLM-CTOPDB",153],"6482288152":["SMEL-GSLM-CAHTP",119],"6482288162":["SMEL-GSLM-CTOPC",119],"6482288192":["SMEL-GSLM-CTOPDB",11],"6482288212":["SMEL-GSLM-CAHTP",189],"6482288242":["SMEL-GSLM-CAHTP",189],"6482288282":["SMEL-GSLM-CTOPDB",119],"6482288292":["SMEL-GSLM-CTOPDB",119],"6482288312":["SMEL-GSLM-CTOPC",113],"6482288332":["SMEL-GSLM-CAHTP",119],"6482288422":["SMEL-GSLM-CTOPDB",186],"6482288552":["SMEL-GSLM-CAHTP",186],"6482288562":["SMEL-GSLM-CAHTP",187],"6482288602":["SMEL-GSLM-CCMDR",59],"6482288612":["SMEL-GSLM-CCMDR",103],"6482288622":["SMEL-GSLM-CCMDR",59],"6482288632":["SMEL-GSLM-CCMDR",119],"6482288662":["SMEL-GSLM-CTOPDB",186],"6482288712":["SMEL-GSLM-CTOPDB",186],"6482298002":["SMEL-GSLM-CCMDR",184],"6482298112":["SMEL-GSLM-CTOPC",119],"6482298122":["SMEL-GSLM-CAHTP",71],"6482298132":["SMEL-GSLM-CTOPDB",119],"6482298152":["SMEL-GSLM-CAHTP",185],"6482298162":["SMEL-GSLM-CAHTP",120],"6482298192":["SMEL-GSLM-CTOPDB",119],"6482298242":["SMEL-GSLM-CTOPC",113],"6482298262":["SMEL-GSLM-CTOPC",119],"6482298312":["SMEL-GSLM-CCMDR",113],"6482298322":["SMEL-GSLM-CTOPC",120],"6488198080":["SSSTPA",25],"6482268012":["SMEL-GSLM-CTOPC",119],"6482298212":["SMEL-GSLM-CTOPDB",184],"6482288132":["SMEL-GSLM-CTOPDB",119],"6482288142":["SMEL-GSLM-CTOPDB",119],"6482288362":["SMEL-GSLM-CTOPDB",184],"6482288592":["SMEL-GSLM-CTOPC",59],"6482288672":["SMEL-GSLM-CTOPDB",113],"6482288682":["SMEL-GSLM-CTOPDB",88],"6482298102":["SMEL-GSLM-CAHTP",71],"6482298202":["SMEL-GSLM-CTOPDB",119],"6482298302":["SMEL-GSLM-CTOPDB",186],"4900031724":["SERMSO",56],"4900032928":["SERMSO",152],"6482298182":["SMEL-GSLM-CTOPDB",59],"6410078020":["SMEL",103],"4282248652":["SMEL-GSLM",113],"6482288302":["SMEL-GSLM-CTOPDB",119],"6482298222":["SMEL-GSLM-CTOPDB",184],"6482298232":["SMEL-GSLM-CTOPDB",113],"6482288372":["SMEL-GSLM-CTOPDB",111],"6482298142":["SMEL-GSLM-CAHTP",121],"4282248662":["SMEL-GSLM-CTOPDB",186],"6482288382":["SMEL-GSLM-CTOPC",2],"4210038112":["SMEL",70],"6482288572":["SMEL-GSLM",113],"6482288182":["SMEL-GSLM-CTOPDB",11],"6482288272":["SMEL-GSLM-CTOPC",119],"6482288392":["SMEL-GSLM-CTOPC",99],"6482288642":["SMEL-GSLM-CTOPC",99],"6482288652":["SMEL-GSLM-CTOPDB",99],"6482288752":["SMEL-GSLM-CTOPC",103],"6482298252":["SMEL-GSLM-CTOPDB",113],"6482208022":["SMEL-GSLM-CTOPDB",113],"4210038502":["SMEL-GSLM",47],"4210038672":["SMEL-GSLM",47],"4210048302":["SPTMP-GMRTAC-RACM-RCSA",47],"4210048312":["SPTMP-GMRTAC-RACM-RCSA",47],"4210048352":["SMEL-GSLM-CTOPC",186],"4210048392":["SMEL-GSLM-CTOPC",198],"4210048682":["SPTMP-GMRTAC-RACM-RCSA",198],"6410058112":["SMEL-GSLM",198],"6410058122":["SMEL-GSLM",198],"6482258272":["SMEL-GSLM-CTOPDB",120],"6402198042":["SE",58],"6482288582":["SMEL-GSLM-CTOPC",103],"6482288732":["SMEL-GSLM-CCMDR",99],"6482288742":["SMEL-GSLM-CCMDR",99],"6408588032":["SDIEP-GSPI",37],"6408588192":["SMEL",50],"4210039182":["SPTMP-GMRTAC-RACM-RCSA",46],"6482258482":["SMEL-GSLM-CTOPC",119],"4282248822":["SMEL-GSLM-CTOPC",103],"4210028332":["SMEL",76],"6408598012":["SDIEP-GSPI",141],"6410098002":["SMEL",103],"4210038682":["SMEL",103],"4210038692":["SPTMP-GMRTAC-RACM-RCSA",103],"4210048322":["SMEL-GSLM",103],"4210048332":["SMEL-GSLM-CTOPC",103],"4210048342":["SPTMP-GMRTAC-RACM-RCSA",103],"4210048582":["SMEL-GSLM",130],"4210048592":["SPTMP-GMRTAC-RACM-RCSA",103],"4210048612":["SPTMP-GMRTAC-RACM-RCSA",103],"4210048852":["SPTMP-GMRTAC-RACM-RCSA",103],"6408508012":["SMEL",178],"6482258532":["SMEL-GSLM-CTOPDB",99],"6482288172":["SMEL-GSLM-CTOPDB",103],"6482288202":["SMEL-GSLM-CTOPDB",103],"6482288222":["SMEL-GSLM-CTOPC",111],"6482288232":["SMEL-GSLM-CAHTP",103],"6482288322":["SMEL-GSLM-CTOPC",103],"6482288402":["SMEL-GSLM-CTOPDB",103],"6482288460":["SMEL-GSLM-CAHTP",180],"6482288692":["SMEL-GSLM-CTOPDB",103],"648229826":["SMEL-GSLM-CAHTP",120],"6482358092":["SMEL-GMEICM-GMIPIEMIIM",47],"6482368002":["SMEL-GMEICM-SMCIRMNE",37],"PEPAS01118":["SMEL",131],"6482298272":["SMEL-GSLM-CTOPC",120],"6482298282":["SMEL-GSLM-CTOPDB",14],"6408588172":["SMEL",50],"6408588182":["SMEL-GMEICM-SMCIRMNE",107],"6482298292":["SMEL-GSLM-CTOPC",14],"6408588012":["SDIEP-GSPI",50],"6408598150":["SMEL",50],"4282248562":["SMEL-GSLM-CTOPDB",119],"4282248612":["SMEL-GSLM-CTOPC",119],"4282248752":["SMEL-GSLM-CTOPC",119],"6408588092":["SMEL",103],"6488598012":["SDIEP-GSPI",143],"4282248882":["SMEL-GSLM-CTOPDB",184],"4282248912":["SMEL-GSLM-CTOPDB",184],"640858812":["SDIEP-GSPI",94],"6408588122":["SMEL",94],"6408598122":["SMEL",141],"4282248852":["SMEL-GSLM-CAHTP",119],"6408368020":["SDIEP-GSPI",94],"4282248872":["SMEL-GSLM-CTOPC",119],"6408388002":["SDIEP-GSPI",18],"6408588132":["SMEL",94],"6408588042":["SMEL",85],"6408588062":["SDIEP-GSPI",85],"648228833":["SMEL-GSLM-CAHTP",121],"6408588082":["SMEL",155],"6482258282":["SMEL-GSLM-CTOPDB",186],"4282248772":["SMEL-GSLM-CAHTP",70],"4282248792":["SMEL-GSLM-CAHTP",119],"6402188002":["SMEL-GSLM-CTOPDB",178],"6410088022":["SMEL",195],"6482258182":["SMEL-GSLM-CTOPDB",119],"6482288042":["SMEL-GSLM-CTOPDB",11],"4282248832":["SMEL-GSLM-CTOPDB",184],"4210039032":["SPTMP-GMRTAC-RACM-RCSA",46],"6408588142":["SMEL",141],"4282219392":["SMEL-GSLM-CTOPDB",153],"PEPAS01117":["SMEL",131],"4282248862":["SMEL-GSLM-CTOPDB",186],"4282248762":["SMEL-GSLM-CAHTP",70],"4180978003":["",173],"4282248842":["SMEL-GSLM-CTOPDB",120],"6408588072":["SMEL",37],"4282248392":["SMEL-GSLM-CTOPDB",112],"6408588002":["SDIEP-GSPI",141],"4282248812":["SMEL-GSLM-CTOPDB",99],"6482258452":["SMEL-GSLM-CTOPDB",184],"4282328292":["SMEL-GMEICM-GMIPIEMIIM",100],"4210048800":["SMEL",154],"6402168092":["",26],"6482258252":["SMEL-GSLM-CTOPDB",99],"4210048552":["SMEL",105],"4210048912":["",195],"4000000011":["",195],"4282219402":["",153],"4282248182":["SMEL-GSLM-CTOPDB",153],"4282248192":["SMEL-GSLM-CTOPDB",153],"4282238842":["SMEL-GSLM-CTOPC",113],"4210078152":["SMEL",90],"4210048662":["SMEL",52],"4282219412":["",153],"4210018402":["SMEL",138],"4282238452":["SMEL-GSLM-CTOPDB",39],"4210039012":["SPTMP-GMRTAC-RACM-RCSA",78],"4282238802":["SMEL-GSLM-CTOPDB",186],"4282248502":["SMEL-GSLM-CAHTP",113],"4210018682":["SMEL",135],"4282238382":["SMEL-GSLM-CTOPDB",87],"4282238352":["SMEL-GSLM-CTOPDB",87],"4180958002":["SMEL",27],"6482258382":["SMEL-GSLM-CTOPC",113],"4282218142":["SMEL-GSLM-CTOPDB",99],"6488158170":["SPTMP-GMRTAC-RACM-RCSA",25],"4210018472":["SMEL",135],"4210048402":["SMEL",96],"6408358032":["SMEL",155],"4208338352":["SMEL-GSLM-CTOPC",141],"6482242222":["SMEL-GSLM-CTOPDB",169],"PMX0000264":["",202],"PMX000262":["",202],"PMX000263":["",202],"PMX0000260":["",128],"PMX0000261":["",3],"PMX0000259":["",63],"PMX0000258":["",169],"PMX000257":["",33],"PMX0000256":["",169],"PMX0000255":["",19],"CNH-R01-L02-A4/2015":["",63],"PMX0000253":["",34],"PMX0000254":["",34],"PMX0000251":["",86],"PMX0000249":["",135],"PMX0000250":["",22],"PMX0000252":["",169],"PMX0000248":["",195],"PMX0000246":["",139],"PMX0000247":["",139],"PMX0000244":["",41],"PMX0000245":["",196],"PMX0000219":["",125],"PMX0000023":["",37],"PMX0000243":["",8],"PMX0000240":["",183],"PMX0000239":["",19],"PMX0000238":["",83],"PMX0000236":["",99],"PMX0000237":["",83],"PMX0000241":["",124],"PMX0000233":["",191],"PMX0000234":["",145],"PMX0000226":["",126],"PMX0000225":["",119],"PMX0000222":["",99],"PMX0000235":["",172],"PMX0000218":["",120],"PMX0000215":["",99],"PMX0000214":["",120],"PMX0000213":["",8],"PMX0000211":["",42],"PMX0000207":["",103],"PMX0000206":["",32],"PMX0000204":["",166],"PMX0000205":["",82],"PMX0000203":["",99],"PMX0000202":["",99],"PMX0000200":["",89],"PMX0000216":["",9],"PMX0000199":["",79],"PMX0000208":["",73],"PMX0000209":["",35],"PMX0000210":["",35],"PMX0000198":["",119],"PMX0000034":["",184],"PMX0000054":["",119],"PMX0000197":["",83],"PMX0000196":["",89],"PMX0000195":["",119],"PMX0000201":["",153],"PMX0000191":["",102],"PMX0000189":["",99],"PMX0000126":["",186],"PMX0000032":["",47],"PMX0000186":["",32],"PMX0000187":["",99],"PMX0000106":["",146],"PMX0000192":["",65],"PMX0000185":["",119],"PMX0000184":["",47],"PMX0000183":["",99],"PMX0000180":["",33],"PMX0000190":["",186],"CNDH0000001":["",82],"PMX0000035":["",103],"PMX0000179":["",89],"PMX0000178":["",32],"PMX":["",30],"PMX0000045":["",103],"PMX0000177":["",103],"PMX0000059":["",103],"PMX0000175":["",151],"PMX0000181":["",99],"PMX0000182":["",99],"PMX0000172":["",177],"PMX0000173":["",2],"PMX0000056":["",104],"PMX0000170":["",98],"PMX0000167":["",103],"PMX0000163":["",8],"PMX0000166":["",87],"PMX0000040":["",135],"PMX0000165":["",184],"PMX0000061":["",166],"PMX0000161":["",82],"PMX0000162":["",186],"PMX0000025":["",39],"PMX0000075":["",2],"PMX0000085":["",47],"PMX0000153":["",175],"PMX0000002":["",103],"PMX0000164":["",119],"PMX0000033":["",103],"PMX0000006":["",14],"PMX0000029":["",39],"PMX0000099":["",163],"PMX0000174":["",103],"PMX0000012":["",88],"PMX0000073":["",103],"PMX0000150":["",11],"PMX0000217":["",88],"PMX0000193":["",99],"PMX0000160":["",119],"PMX0000159":["",146],"PMX0000158":["",99],"PMX0000157":["",47],"PMX0000018":["",8],"PMX0000024":["",32],"PMX0000011":["",32],"PMX0000140":["",88],"PMX0000068":["",103],"PMX0000092":["",119],"PMX0000089":["",32],"PMX0000147":["",6],"PMX0000154":["",32],"PMX0000015":["",157],"PMX0000046":["",103],"PMX0000095":["",32],"PMX0000067":["",146],"PMX0000122":["",70],"PMX0000108":["",186],"PMX0000083":["",103],"PMX0000151":["",83],"PMX0000088":["",146],"PMX0000103":["",88],"PMX0000112":["",32],"PMX0000155":["",88],"PMX0000176":["",103],"PMX0000072":["",103],"PMX0000146":["",0],"PMX0000005":["",32],"PMX0000145":["",171],"PMX0000078":["",48],"PMX0000148":["",119],"PMX0000094":["",14],"PMX0000156":["",99],"PMX0000124":["",32],"PMX0000138":["",69],"PMX0000152":["",83],"PMX0000086":["",184],"PMX0000142":["",103],"PMX0000137":["",87],"PMX0000169":["",98],"PMX0000136":["",87],"PMX0000149":["",186],"PMX0000130":["",82],"PMX0000062":["",47],"PMX0000188":["",47],"PMX0000129":["",99],"PMX0000127":["",32],"PMX0000128":["",108],"PMX0000133":["",119],"PMX0000144":["",87],"PMX0000043":["",181],"PMX0000242":["",5],"PMX0000125":["",103],"PMX0000069":["",103],"PMX0000119":["",153],"PMX0000139":["",199],"PMX0000115":["",99],"PMX0000120":["",99],"PMX0000132":["",99],"PMX0000134":["",87],"PMX0000123":["",99],"PMX0000121":["",184],"PMX0000135":["",87],"PMX0000131":["",106],"PMX0000048":["",2],"PMX0000113":["",103],"PMX0000111":["",70],"PMX0000039":["",186],"PMX0000171":["",186],"PMX0000091":["",32],"PMX0000109":["",186],"PMX0000114":["",32],"PMX0000118":["",153],"PMX0000116":["",32],"PMX0000117":["",32],"PMX0000087":["",68],"PMX0000014":["",146],"PMX0000055":["",146],"PMX0000096":["",47],"PMX0000074":["",103],"PMX0000047":["",70],"PMX0000097":["",103],"PMX0000009":["",8],"PMX0000079":["",119],"PMX0000194":["",119],"PMX0000058":["",32],"PMX0000110":["",48],"PMX0000004":["",32],"PMX0000070":["",32],"PMX0000042":["",103],"PMX0000041":["",135],"PMX0000107":["",103],"PMX0000104":["",70],"PMX0000093":["",6],"PMX0000105":["",119],"PMX0000100":["",186],"PMX0000020":["",119],"PMX0000101":["",119],"PMX0000102":["",119],"PMX0000016":["",157],"PMX0000080":["",146],"PMX0000060":["",2],"PMX0000098":["",119],"PMX0000063":["",103],"PMX0000064":["",22],"PMX0000082":["",80],"PMX0000057":["",146],"PMX0000044":["",181],"PMX0000038":["",102],"PMX0000066":["",4],"PMX0000141":["",87],"PMX0000212":["",166],"PMX0000221":["",42],"PMX0000223":["",67],"PMX0000224":["",125],"PMX0000227":["",126],"PMX0000228":["",82],"PMX0000229":["",42],"PMX0000230":["",146],"PMX0000231":["",82],"PMX0000232":["",145]}};
        function datosContrato(num) {
            num = String(num || "").trim().toUpperCase();
            if (!num) return null;
            const en = appState.conCat || {};
            if (en[num]) return en[num];
            const k = CON_CAT.k[num];
            if (k) return { clave: k[0], cia: k[1] >= 0 ? CON_CAT.c[k[1]] : "" };
            if (num.length >= 8) { // número capturado sin el último dígito
                const cand = Object.keys(CON_CAT.k).filter(x => x.startsWith(num));
                if (cand.length === 1) { const c = CON_CAT.k[cand[0]]; return { clave: c[0], cia: c[1] >= 0 ? CON_CAT.c[c[1]] : "", num: cand[0] }; }
            }
            return null;
        }

        const CATALOGO_LOCAL_A_F = [
            { nombre: "A4", servicio: "ABASTECEDOR", mmsi: "345070316", imo: "8661252", callsign: "XCVN5", bandera: "MEXICANA" },
            { nombre: "ACALLI-E", servicio: "ABASTECEDOR", mmsi: "270135252", imo: "N/A", callsign: "_0000", bandera: "MEXICANA" },
            { nombre: "ADMARINE VIII", servicio: "N/A", mmsi: "N/A", imo: "N/A", callsign: "N/A", bandera: "N/A" },
            { nombre: "ADMIRAL", servicio: "REMOLCADOR", mmsi: "345050010", imo: "9421582", callsign: "XCAN5", bandera: "MEXICANA" },
            { nombre: "ADRIAN CONTRERAS", servicio: "ABASTECEDOR", mmsi: "345010017", imo: "8848367", callsign: "XCAR", bandera: "MEXICANA" },
            { nombre: "AGOSTO 12. (P.A.E.)", servicio: "ORMA AUTO ELI", mmsi: "563552000", imo: "9746968", callsign: "9V3402", bandera: "SINGAPUR" }
        ];

        const CATALOGO_LOCAL_G = ["927233", "640858812", "648222832", "648224872", "648228833", "648229826"];
        const CATALOGO_LOCAL_H = [
            "ABASTECEDORA PETROLERA S.A. DE C.V.",
            "ADMINISTRADORA DE INSTALACIONES MARITIMAS S.A. DE C.V.",
            "ADMINISTRADORES NAVIEROS DEL GOLFO, S.A. DE C.V.",
            "AGENCIA ALTAMARINA, S.A. DE C.V.",
            "AGENCIA CONSIGNATARIA MARITIMA OSO I ALFA S.A. DE C.V.",
            "AKALI MARINE S.A. DE C.V."
        ];

        // ===== Utilidades añadidas =====
        function buscarEmb(nombre) {
            if (!nombre) return null;
            return appState.embarcacionesMap[nombre] || appState.embIndex[nombre.trim().toUpperCase()] || null;
        }

        function fmtFecha(v) {
            if (!v) return v;
            const [y, m, d] = v.split("-");
            return (y && m && d) ? `${d}/${m}/${y}` : v;
        }

        function generarFolio() {
            const h = new Date();
            const dia = h.getFullYear() + String(h.getMonth() + 1).padStart(2, "0") + String(h.getDate()).padStart(2, "0");
            let n;
            try {
                const g = JSON.parse(localStorage.getItem("cepab_folio") || "{}");
                n = (g.dia === dia ? g.n : 0) + 1;
                localStorage.setItem("cepab_folio", JSON.stringify({ dia, n }));
            } catch (e) { n = Math.floor(Math.random() * 900) + 100; }
            return `CEPAB-DEE-${dia}-${String(n).padStart(3, "0")}`;
        }

        function guardarCache(embMap, embList, conList, empList) {
            try { localStorage.setItem(CONFIG.cacheKey, JSON.stringify({ ts: Date.now(), embMap, embList, conList, empList })); } catch (e) {}
        }

        function cargarCache() {
            try {
                const c = JSON.parse(localStorage.getItem(CONFIG.cacheKey) || "null");
                if (!c || !c.embList || !c.embList.length) return false;
                appState.embarcacionesMap = c.embMap;
                appState.catalogos.EMBARCACIONES = c.embList;
                appState.catalogos.CONTRATOS = c.conList || [];
                appState.catalogos.EMPRESAS = c.empList || [];
                poblarDatalists();
                document.getElementById("statusDot").className = "w-2 h-2 rounded-full bg-blue-500";
                document.getElementById("statusText").innerText = `Catálogo en caché (${new Date(c.ts).toLocaleDateString("es-MX")})`;
                return true;
            } catch (e) { return false; }
        }

        function guardarPrefs() {
            try {
                localStorage.setItem(CONFIG.prefsKey, JSON.stringify({
                    n: document.getElementById("supervisorNombre").value.trim(),
                    f: document.getElementById("supervisorFicha").value.trim(),
                    c: document.getElementById("ccEmail").value.trim()
                }));
            } catch (e) {}
        }

        function cargarPrefs() {
            try {
                const p = JSON.parse(localStorage.getItem(CONFIG.prefsKey) || "null");
                if (!p) return;
                document.getElementById("supervisorNombre").value = p.n || "";
                document.getElementById("supervisorFicha").value = p.f || "";
                document.getElementById("ccEmail").value = p.c || "";
            } catch (e) {}
        }

        function validarFormulario() {
            document.querySelectorAll(".campo-error").forEach(el => el.classList.remove("campo-error"));
            const val = id => document.getElementById(id).value.trim();
            const T = tram();
            const faltan = [];
            if (!val("moduloOperativo")) faltan.push(["moduloOperativo", "módulo"]);
            if (!T) faltan.push(["subTramite", "sub-trámite"]);
            if (T) {
                const lugares = !!T.lugares, temporal = !!T.temporal;
                if (!lugares && !T.sinActivo && !val("embarcacion")) faltan.push(["embarcacion", T.accion === "ALTA" && T.activo === "ARTEFACTO" ? "nombre del artefacto naval" : "embarcación"]);
                if (!lugares && !temporal && !T.sinContrato && !val("contrato")) faltan.push(["contrato", "número de contrato"]);
                if (!lugares && !temporal && !T.sinContrato && !val("empresa")) faltan.push(["empresa", "compañía"]);
                if (temporal) {
                    const n = parseInt(val("numContratosSpot"), 10);
                    if (!n || n < 1) faltan.push(["numContratosSpot", "cantidad de contratos"]);
                    document.querySelectorAll("#filasContratosSpot [data-row]").forEach((r, i) => {
                        if (!r.querySelector(".sp-con").value.trim()) faltan.push([r.querySelector(".sp-con").id, `contrato ${i + 1}`]);
                        if (!r.querySelector(".sp-emp").value.trim()) faltan.push([r.querySelector(".sp-emp").id, `compañía ${i + 1}`]);
                    });
                }
                if (lugares) validarFijas(faltan);
                if (T.variante !== "FIN" && !val("supervisorNombre")) faltan.push(["supervisorNombre", "supervisor de contrato"]);
                if (T.sust && !val("sustNombre")) faltan.push(["sustNombre", T.sust === "sale" ? "unidad a la que sustituye" : "unidad que la sustituye"]);
                if (T.variante === "OTRO" && !val("tipoContratoAtlas")) faltan.push(["tipoContratoAtlas", "tipo de contrato (Permanente o Adicional)"]);
                if (T.accion === "BAJA" && !gerenciaActual()) faltan.push(["gerenciaSolicitante", "área solicitante (SMEL-GSLM u otra gerencia)"]);
            }
            const rHeli = document.querySelector('#listaChecklist input[name^="opt_heli_"]:checked');
            if (rHeli && rHeli.value === "SI") {
                const inpHeli = document.getElementById(`valSSCTAPC_Codigo_${rHeli.getAttribute("data-index")}`);
                if (inpHeli && !inpHeli.value.trim()) faltan.push([inpHeli.id, "siglas de la heliplataforma (solicítelas a la SSCTAPC)"]);
            }

            if (faltan.length) {
                faltan.forEach(([id]) => document.getElementById(id).classList.add("campo-error"));
                document.getElementById(faltan[0][0]).focus();
                mostrarToast("Faltan datos", "Revise: " + faltan.slice(0, 4).map(f => f[1]).join(", ") + (faltan.length > 4 ? ` y ${faltan.length - 4} más` : "") + ".");
                return false;
            }
            return true;
        }

        function renderFilasSpot() {
            const cont = document.getElementById("filasContratosSpot");
            const campo = document.getElementById("numContratosSpot");
            let n = parseInt(campo.value, 10);
            if (!n || n < 1) n = 0;
            if (n > 20) { n = 20; campo.value = 20; mostrarToast("Máximo 20 contratos", "Se ajustó la cantidad al límite permitido."); }

            const previos = [...cont.querySelectorAll("[data-row]")].map(r => ({
                c: r.querySelector(".sp-con").value, s: r.querySelector(".sp-sup").value, e: r.querySelector(".sp-emp").value
            }));
            const inputCls = "w-full bg-white border border-blue-300 rounded-lg p-2.5 text-xs outline-none focus:ring-2 focus:ring-blue-500";
            const lblCls = "block text-[11px] font-bold text-slate-600 mb-1 uppercase";

            let html = "";
            for (let i = 0; i < n; i++) {
                const pv = previos[i] || { c: "", s: "", e: "" };
                html += `
                <div data-row class="bg-white border border-blue-200 rounded-xl p-3">
                    <p class="text-[11px] font-bold text-blue-800 mb-2">Contrato ${i + 1} de ${n}</p>
                    <div class="grid md:grid-cols-3 gap-3">
                        <div>
                            <label for="spotCon_${i}" class="${lblCls}">Número de Contrato <span class="text-red-500">*</span></label>
                            <input id="spotCon_${i}" list="lista-contratos" type="text" value="${escapeHtml(pv.c)}" placeholder="Escriba o busque contrato..." class="sp-con ${inputCls}">
                        </div>
                        <div>
                            <label for="spotSup_${i}" class="${lblCls}">Supervisor de Contrato DEE</label>
                            <input id="spotSup_${i}" type="text" value="${escapeHtml(pv.s)}" placeholder="Nombre del supervisor..." class="sp-sup ${inputCls}">
                        </div>
                        <div>
                            <label for="spotEmp_${i}" class="${lblCls}">Compañía / Contratista <span class="text-red-500">*</span></label>
                            <input id="spotEmp_${i}" list="lista-empresas" type="text" value="${escapeHtml(pv.e)}" placeholder="Escriba o busque compañía..." class="sp-emp ${inputCls}">
                        </div>
                    </div>
                </div>`;
            }
            cont.innerHTML = html || '<p class="text-[11px] text-blue-800">Indique arriba cuántos contratos atenderá la unidad para capturar sus datos.</p>';
            cont.querySelectorAll("input").forEach(el => el.addEventListener("input", () => el.classList.remove("campo-error")));
        }

        const DEF_FIJAS = {
            region: "Subdirección de Mantenimiento Estático y Logística",
            activo: "Gerencia de Mantenimiento Estático e Infraestructura Complementaria Marina",
            complejo: "Subgerencia de Mantenimiento y Confiabilidad de Instalaciones RMSO y RN",
            lat_h: "N",
            lon_h: "O"
        };
        const HEMIS = ["N", "S", "E", "O"];
        const SYNC_FIJAS = ["region", "activo", "complejo"];
        const NO_COPIAR_FIJAS = ["ubicacion", "heli", "lat_g", "lat_m", "lat_s", "lon_g", "lon_m", "lon_s"];

        function gvFija(i, k) {
            const el = document.getElementById(`fj_${i}_${k}`);
            if (!el) return "";
            return el.type === "checkbox" ? el.checked : el.value.trim();
        }

        function renderFilasFijas() {
            const cont = document.getElementById("filasFijas");
            const campo = document.getElementById("numFijas");
            let n = parseInt(campo.value, 10);
            if (!n || n < 1) n = 0;
            if (n > 20) { n = 20; campo.value = 20; mostrarToast((tram() || {}).activo === "CAMPAMENTO" ? "Máximo 20 campamentos" : "Máximo 20 instalaciones", "Se ajustó la cantidad al límite permitido."); }

            const previos = [...cont.querySelectorAll("[data-fj]")].map(r => {
                const o = {};
                r.querySelectorAll("[data-k]").forEach(el => { o[el.dataset.k] = el.type === "checkbox" ? el.checked : el.value; });
                return o;
            });

            const esCamp = (tram() || {}).activo === "CAMPAMENTO";
            const inp = "w-full bg-white border border-teal-300 rounded-lg p-2.5 text-xs outline-none focus:ring-2 focus:ring-teal-500";
            const lbl = "block text-[11px] font-bold text-slate-600 mb-1";
            const req = ' <span class="text-red-500">*</span>';
            const txt = (i, k, l, o = {}) => `<div class="${o.full ? "md:col-span-2" : ""}"><label for="fj_${i}_${k}" class="${lbl}">${l}${o.req ? req : ""}</label><input id="fj_${i}_${k}" data-k="${k}" type="${o.type || "text"}" ${o.ph ? `placeholder="${o.ph}"` : ""} ${o.list ? `list="${o.list}"` : ""} class="${inp}${o.up ? " uppercase" : ""}"></div>`;
            const num = (i, k, l, ph, step) => `<div><label for="fj_${i}_${k}" class="${lbl}">${l}</label><input id="fj_${i}_${k}" data-k="${k}" type="number" min="0" step="${step}" inputmode="decimal" placeholder="${ph}" class="${inp}"></div>`;
            const sel = (i, k, l, ops) => `<div><label for="fj_${i}_${k}" class="${lbl}">${l}</label><select id="fj_${i}_${k}" data-k="${k}" class="${inp}">${ops.map(o => `<option value="${o}">${o}</option>`).join("")}</select></div>`;
            const coord = (i, p, titulo, hems) => `<fieldset class="md:col-span-1"><legend class="${lbl}">${titulo}${req}</legend><div class="grid grid-cols-2 sm:grid-cols-4 gap-2">${num(i, p + "_g", "Grados °", "19", 1)}${num(i, p + "_m", "Minutos ´", "17", 1)}${num(i, p + "_s", "Segundos ”", "74", "any")}${sel(i, p + "_h", "Hemisferio", hems)}</div></fieldset>`;
            const chk = (i, k, l) => `<label class="flex items-center gap-1.5 text-xs font-medium text-slate-700 cursor-pointer"><input id="fj_${i}_${k}" data-k="${k}" type="checkbox" class="rounded border-slate-300 text-teal-600 focus:ring-teal-500 w-4 h-4"> ${l}</label>`;

            let html = "";
            for (let i = 0; i < n; i++) {
                html += `
                <div data-fj class="bg-white border border-teal-200 rounded-xl p-3 space-y-3">
                    <div class="flex flex-wrap items-center justify-between gap-2">
                        <p class="text-xs font-bold text-teal-800">${esCamp ? "Campamento" : "Instalación"} ${i + 1} de ${n}</p>
                        <div class="flex flex-wrap items-center gap-2">
                            ${!esCamp ? `<button type="button" onclick="abrirCedulas(${i})" class="text-[11px] font-semibold text-emerald-800 bg-emerald-50 hover:bg-emerald-100 border border-emerald-200 px-2.5 py-1 rounded-lg inline-flex items-center gap-1.5"><i data-lucide="file-text" class="w-3.5 h-3.5"></i> Cédulas de esta instalación</button>` : ""}
                            ${i > 0 ? `<button type="button" data-copiar="${i}" class="text-[11px] font-semibold text-teal-700 bg-teal-50 hover:bg-teal-100 border border-teal-200 px-2.5 py-1 rounded-lg flex items-center gap-1.5"><i data-lucide="copy" class="w-3.5 h-3.5"></i> Copiar datos de la anterior</button>` : ""}
                        </div>
                    </div>
                    <div class="grid md:grid-cols-2 gap-3">
                        ${txt(i, "region", "Región", { full: 1, req: 1, list: "dl-region", ph: "Escriba o elija la sugerencia..." })}
                        ${txt(i, "activo", "Activo", { full: 1, req: 1, list: "dl-activo", ph: "Escriba o elija la sugerencia..." })}
                        ${txt(i, "complejo", "Complejo", { full: 1, req: 1, list: "dl-complejo", ph: "Escriba o elija la sugerencia..." })}
                        ${txt(i, "ubicacion", "D.1. Ubicación actual", { req: 1, ph: "Campamento 00 / ABKATUN-A" })}
                        ${txt(i, "heli", "Siglas y/o identificador de la heliplataforma", { ph: "Si aplica", up: 1 })}
                        ${txt(i, "servicio", "Clasificado por servicio", { req: 1, ph: "Campamento" })}
                        ${txt(i, "proceso", "Clasificado por proceso", { req: 1, ph: "Mantenimiento e Inspección" })}
                        ${txt(i, "estructura", "Tipo de estructura", { req: 1, ph: "Superficie" })}
                        ${txt(i, "sector", "Sector", { req: 1, ph: "ABKATUN POL CHUC" })}
                        ${txt(i, "mision", "Misión", { req: 1, ph: "PL" })}
                        ${sel(i, "fijamovil", "Fija / Móvil", ["FIJA", "MÓVIL"])}
                        ${coord(i, "lat", "Latitud", HEMIS)}
                        ${coord(i, "lon", "Longitud", HEMIS)}
                        <div class="md:col-span-2">
                            <p class="${lbl}">Detalles (servicios a solicitar)</p>
                            <div class="flex flex-wrap items-center gap-4">
                                ${chk(i, "det_AH", "AH")}
                                ${chk(i, "det_CEPAB", "CEPAB")}
                                <input id="fj_${i}_det_otros" data-k="det_otros" type="text" placeholder="Otros servicios..." class="${inp} sm:w-64">
                            </div>
                        </div>
                        ${txt(i, "compania", "Compañía", { req: 1, list: "lista-empresas", ph: "Escriba o busque compañía..." })}
                        ${txt(i, "contrato", "Contrato", { req: 1, list: "lista-contratos", ph: "Escriba o busque contrato..." })}
                        ${txt(i, "inicio", "Inicio", { req: 1, type: "date" })}
                    </div>
                </div>`;
            }
            cont.innerHTML = html || `<p class="text-[11px] text-teal-800">Indique arriba ${esCamp ? "cuántos campamentos" : "cuántas instalaciones"} se darán de alta para capturar su ficha.</p>`;

            cont.querySelectorAll("[data-fj]").forEach((r, i) => {
                const pv = previos[i] || {};
                r.querySelectorAll("[data-k]").forEach(el => {
                    const k = el.dataset.k;
                    const v = (k in pv) ? pv[k] : ((SYNC_FIJAS.includes(k) && previos[0] && k in previos[0]) ? previos[0][k] : DEF_FIJAS[k]);
                    if (v !== undefined) { if (el.type === "checkbox") el.checked = !!v; else el.value = v; }
                    el.addEventListener("input", () => el.classList.remove("campo-error"));
                    if (SYNC_FIJAS.includes(k)) {
                        el.addEventListener("focus", () => el.select());
                        el.addEventListener("input", () => document.querySelectorAll(`#filasFijas [data-k="${k}"]`).forEach(o => { if (o !== el) o.value = el.value; }));
                    }
                    if (k === "lat_h" || k === "lon_h") el.addEventListener("change", () => actualizarHemisferios(i));
                });
                actualizarHemisferios(i);
            });
            cont.querySelectorAll("[data-copiar]").forEach(b => b.addEventListener("click", () => {
                const i = parseInt(b.dataset.copiar, 10);
                document.querySelectorAll(`#filasFijas [data-fj]:nth-child(${i + 1}) [data-k]`).forEach(dst => {
                    const k = dst.dataset.k;
                    if (NO_COPIAR_FIJAS.includes(k) || k === "lat_h" || k === "lon_h") return;
                    const src = document.getElementById(`fj_${i - 1}_${k}`);
                    if (!src) return;
                    if (dst.type === "checkbox") dst.checked = src.checked; else dst.value = src.value;
                });
                actualizarHemisferios(i, gvFija(i - 1, "lat_h"), gvFija(i - 1, "lon_h"));
                mostrarToast("Datos copiados", `${(tram() || {}).activo === "CAMPAMENTO" ? "Campamento" : "Instalación"} ${i + 1}: se copió todo excepto ubicación, heliplataforma y coordenadas.`);
            }));
            reInitLucide();
        }

        function validarFijas(faltan) {
            const total = parseInt(document.getElementById("numFijas").value, 10);
            if (!total || total < 1) { faltan.push(["numFijas", (tram() || {}).activo === "CAMPAMENTO" ? "cantidad de campamentos" : "cantidad de instalaciones"]); return; }
            const n = document.querySelectorAll("#filasFijas [data-fj]").length;
            const oblig = [["region", "región"], ["activo", "activo"], ["complejo", "complejo"], ["ubicacion", "ubicación"], ["servicio", "servicio"],
                ["proceso", "proceso"], ["estructura", "estructura"], ["sector", "sector"], ["mision", "misión"],
                ["compania", "compañía"], ["contrato", "contrato"], ["inicio", "fecha de inicio"]];
            for (let i = 0; i < n; i++) {
                oblig.forEach(([k, txt]) => { if (!gvFija(i, k)) faltan.push([`fj_${i}_${k}`, `${txt} ${i + 1}`]); });
                if (!["N", "S"].includes(gvFija(i, "lat_h"))) faltan.push([`fj_${i}_lat_h`, `latitud ${i + 1} (hemisferio debe ser N o S)`]);
                if (!["E", "O"].includes(gvFija(i, "lon_h"))) faltan.push([`fj_${i}_lon_h`, `longitud ${i + 1} (hemisferio debe ser E u O)`]);
                [["lat", 90, "latitud"], ["lon", 180, "longitud"]].forEach(([pf, maxG, nombre]) => {
                    [["g", maxG, `grados 0-${maxG}`], ["m", 59, "minutos 0-59"], ["s", CONFIG.maxSegundos, `segundos 0-${CONFIG.maxSegundos}`]].forEach(([sfx, max, rango]) => {
                        const v = gvFija(i, `${pf}_${sfx}`);
                        if (v === "" || isNaN(v) || +v < 0 || +v > max) faltan.push([`fj_${i}_${pf}_${sfx}`, `${nombre} ${i + 1} (${rango})`]);
                    });
                });
            }
        }

        function actualizarHemisferios(i, va, vb) {
            const a = document.getElementById(`fj_${i}_lat_h`), b = document.getElementById(`fj_${i}_lon_h`);
            if (!a || !b) return;
            va = va || a.value; vb = vb || b.value;
            const llenar = (sel, excluir, actual) => {
                sel.innerHTML = HEMIS.filter(h => h !== excluir).map(h => `<option value="${h}">${h}</option>`).join("");
                sel.value = actual;
            };
            llenar(a, vb, va);
            llenar(b, va, vb);
        }

        function coordTxt(g, m, s, h) { return `${g}° ${String(m).padStart(2, "0")}´${s}” ${h}`; }

        function obtenerFijas() {
            const n = document.querySelectorAll("#filasFijas [data-fj]").length;
            const out = [];
            for (let i = 0; i < n; i++) {
                const g = k => gvFija(i, k);
                const det = [g("det_AH") && "AH", g("det_CEPAB") && "CEPAB", g("det_otros")].filter(Boolean).join(", ") || "[Sin especificar]";
                const [y, mo, d] = (g("inicio") || "").split("-");
                out.push({
                    region: g("region"), activo: g("activo"), complejo: g("complejo"), ubicacion: g("ubicacion"),
                    heli: g("heli").toUpperCase(), servicio: g("servicio"), proceso: g("proceso"), estructura: g("estructura"),
                    sector: g("sector"), mision: g("mision"), fijamovil: g("fijamovil"), detalles: det,
                    lat: coordTxt(g("lat_g"), g("lat_m"), g("lat_s"), g("lat_h")),
                    lon: coordTxt(g("lon_g"), g("lon_m"), g("lon_s"), g("lon_h")),
                    compania: g("compania"), contrato: g("contrato"), inicio: y ? `${d}/${mo}/${y.slice(2)}` : ""
                });
            }
            return out;
        }

        function escapeHtml(str) {
            if (!str) return '';
            return String(str)
                .replace(/&/g, "&amp;")
                .replace(/</g, "&lt;")
                .replace(/>/g, "&gt;")
                .replace(/"/g, "&quot;")
                .replace(/'/g, "&#039;");
        }

        const ICONOS = {
            "anchor": `<circle cx="12" cy="5" r="3"/><line x1="12" x2="12" y1="22" y2="8"/><path d="M5 12H2a10 10 0 0 0 20 0h-3"/>`,
            "file-text": `<path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"/><polyline points="14 2 14 8 20 8"/><line x1="16" x2="8" y1="13" y2="13"/><line x1="16" x2="8" y1="17" y2="17"/><line x1="10" x2="8" y1="9" y2="9"/>`,
            "chevron-down": `<path d="m6 9 6 6 6-6"/>`,
            "shield-check": `<path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/><path d="m9 12 2 2 4-4"/>`,
            "info": `<circle cx="12" cy="12" r="10"/><path d="M12 16v-4"/><path d="M12 8h.01"/>`,
            "calendar-clock": `<circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/>`,
            "arrow-left-right": `<path d="M8 3 4 7l4 4"/><path d="M4 7h16"/><path d="m16 21 4-4-4-4"/><path d="M20 17H4"/>`,
            "ship": `<path d="M2 21c.6.5 1.2 1 2.5 1 2.5 0 2.5-2 5-2 1.3 0 1.9.5 2.5 1 .6.5 1.2 1 2.5 1 2.5 0 2.5-2 5-2 1.3 0 1.9.5 2.5 1"/><path d="M19.38 20A11.6 11.6 0 0 0 21 14l-9-4-9 4c0 2.9.94 5.34 2.81 7.76"/><path d="M19 13V7a2 2 0 0 0-2-2H7a2 2 0 0 0-2 2v6"/><path d="M12 10v4"/><path d="M12 2v3"/>`,
            "send-horizontal": `<path d="m3 3 3 9-3 9 19-9Z"/><path d="M6 12h16"/>`,
            "rotate-ccw": `<path d="M3 12a9 9 0 1 0 9-9 9.75 9.75 0 0 0-6.74 2.74L3 8"/><path d="M3 3v5h5"/>`,
            "mail-check": `<path d="M22 13V6a2 2 0 0 0-2-2H4a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h8"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/><path d="m16 19 2 2 4-4"/>`,
            "zap": `<polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"/>`,
            "mail": `<rect width="20" height="16" x="2" y="4" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/>`,
            "globe": `<circle cx="12" cy="12" r="10"/><path d="M12 2a14.5 14.5 0 0 0 0 20 14.5 14.5 0 0 0 0-20"/><path d="M2 12h20"/>`,
            "building-2": `<path d="M6 22V4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v18Z"/><path d="M6 12H4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h2"/><path d="M18 9h2a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-2"/><path d="M10 6h4"/><path d="M10 10h4"/><path d="M10 14h4"/><path d="M10 18h4"/>`,
            "copy": `<rect width="14" height="14" x="8" y="8" rx="2" ry="2"/><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"/>`,
            "files": `<path d="M20 7h-3a2 2 0 0 1-2-2V2"/><path d="M9 18a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h7l4 4v10a2 2 0 0 1-2 2Z"/><path d="M3 7.6v12.8A1.6 1.6 0 0 0 4.6 22h9.8"/>`,
            "check-circle-2": `<circle cx="12" cy="12" r="10"/><path d="m9 12 2 2 4-4"/>`,
            "check-circle": `<path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/><path d="m9 11 3 3L22 4"/>`,
            "alert-circle": `<circle cx="12" cy="12" r="10"/><line x1="12" x2="12" y1="8" y2="12"/><line x1="12" x2="12.01" y1="16" y2="16"/>`,
            "alert-triangle": `<path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3"/><path d="M12 9v4"/><path d="M12 17h.01"/>`
        };

        function reInitLucide() {
            document.querySelectorAll("i[data-lucide]").forEach(el => {
                const nombre = el.getAttribute("data-lucide");
                const interior = ICONOS[nombre];
                if (!interior) return;
                el.outerHTML = `<svg xmlns="http://www.w3.org/2000/svg" data-icon="${nombre}" class="${el.className}" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">${interior}</svg>`;
            });
        }

        document.addEventListener("DOMContentLoaded", () => {
            reInitLucide();
            inicializarSistema();
            configurarEventListeners();
        });

        function configurarEventListeners() {
            document.getElementById("moduloOperativo").addEventListener("change", actualizarSubtramites);
            document.getElementById("subTramite").addEventListener("change", manejarSeleccionSubtramite);
            document.getElementById("embarcacion").addEventListener("input", detectarDatosEmbarcacion);
            document.getElementById("sustNombre").addEventListener("input", detectarDatosSustitucion);
            
            document.getElementById("btnGenerar").addEventListener("click", generarSolicitudCEPAB);
            document.getElementById("btnLimpiar").addEventListener("click", limpiarFormulario);

            document.getElementById("btnMailto").addEventListener("click", enviarPorMailto);
            document.getElementById("btnGmail").addEventListener("click", enviarPorGmail);
            document.getElementById("btnOutlook").addEventListener("click", enviarPorOutlookWeb);

            document.getElementById("btnCopiarPara").addEventListener("click", () => copiarTexto(appState.correoDestino, 'Correo Destino'));
            document.getElementById("btnCopiarCC").addEventListener("click", () => copiarTexto(document.getElementById('ccEmail').value.trim(), 'Copia CC'));
            document.getElementById("btnCopiarAsunto").addEventListener("click", () => copiarTexto(appState.asuntoCEPAB, 'Asunto'));
            document.getElementById("btnCopiarCuerpo").addEventListener("click", () => copiarTexto(appState.cuerpoCEPAB, 'Cuerpo del Correo'));
            document.getElementById("btnCopiarTodo").addEventListener("click", copiarTodo);
            document.querySelectorAll("input, select, textarea").forEach(el => el.addEventListener("input", () => el.classList.remove("campo-error")));
            document.getElementById("numContratosSpot").addEventListener("input", renderFilasSpot);
            document.getElementById("numFijas").addEventListener("input", renderFilasFijas);
            document.getElementById("contrato").addEventListener("change", autocompletarContrato);
            document.getElementById("contrato").addEventListener("input", detectarGerencia);
            document.getElementById("embarcacion").addEventListener("input", sugerirVariante);
            document.getElementById("gerenciaSolicitante").addEventListener("change", () => gerenciaCambio(true));
            document.getElementById("filasContratosSpot").addEventListener("input", e => { if (e.target.classList.contains("sp-con")) detectarGerencia(); });
            document.getElementById("filasFijas").addEventListener("input", e => { if (e.target.id === "fj_0_contrato") detectarGerencia(); });
            cargarPrefs();
        }

        function inicializarSistema() {
            const script = document.createElement("script");
            script.src = CAT_SRC('CATALOGOS','recibirDatosCEPAB',0);
            
            script.onerror = function() {
                console.warn("No se pudo conectar al catálogo CEPAB. Cargando catálogo de respaldo.");
                cargarModoRespaldo();
            };

            document.head.appendChild(script);

            const hojaCon = document.createElement("script");
            hojaCon.src = CAT_SRC('contratos_CEPAB', 'recibirContratosCEPAB', 1);
            hojaCon.onerror = () => {};
            document.head.appendChild(hojaCon);

            setTimeout(() => {
                if (!appState.cargadoExitosamente) {
                    console.warn("Timeout de respuesta. Activando respaldo local.");
                    cargarModoRespaldo();
                }
            }, CONFIG.timeoutMs);
        }

        /* Hoja contratos_CEPAB: número de contrato -> estructura (área solicitante) y compañía */
        window.recibirContratosCEPAB = function(json) {
            try {
                const cols = (json.table.cols || []).map(c => String(c.label || c.id || "").toLowerCase());
                const ix = (n, def) => { const i = cols.findIndex(c => c.includes(n)); return i >= 0 ? i : def; };
                const iN = ix("numero", 0), iC = ix("compan", 1), iK = ix("clave", 3);
                const m = {};
                (json.table.rows || []).forEach(r => {
                    const c = r.c || [], g = i => (c[i] && c[i].v != null ? String(c[i].v).trim() : "");
                    const num = g(iN).toUpperCase();
                    if (num && num !== "NUMERO_CONTRATO") m[num] = { clave: g(iK), cia: g(iC) };
                });
                if (Object.keys(m).length) { appState.conCat = m; poblarDatalists(); detectarGerencia(); }
            } catch (e) { console.warn("contratos_CEPAB:", e); }
        };

        window.recibirDatosCEPAB = function(json) {
            if (appState.fuente === "linea") return;

            try {
                if (!json || !json.table || !json.table.rows) {
                    throw new Error("Estructura JSON inválida.");
                }

                const embMap = {};
                const embList = [];
                const conList = [];
                const empList = [];

                json.table.rows.forEach(row => {
                    if (!row.c) return;

                    const emb = row.c[0] && row.c[0].v !== null ? String(row.c[0].v).trim() : "";
                    const srv = row.c[1] && row.c[1].v !== null ? String(row.c[1].v).trim() : "N/A";
                    const mmsi = row.c[2] && row.c[2].v !== null ? String(row.c[2].v).trim() : "N/A";
                    const imo = row.c[3] && row.c[3].v !== null ? String(row.c[3].v).trim() : "N/A";
                    const callsign = row.c[4] && row.c[4].v !== null ? String(row.c[4].v).trim() : "N/A";
                    const bandera = row.c[5] && row.c[5].v !== null ? String(row.c[5].v).trim() : "N/A";

                    if (emb !== "" && emb.toUpperCase() !== "AUTORIZADAS") {
                        if (!embList.includes(emb)) embList.push(emb);
                        embMap[emb] = { servicio: srv, mmsi: mmsi, imo: imo, callsign: callsign, bandera: bandera };
                    }

                    const con = row.c[6] && row.c[6].v !== null ? String(row.c[6].v).trim() : "";
                    if (con !== "" && con.toUpperCase() !== "CONTRATOS" && !conList.includes(con)) {
                        conList.push(con);
                    }

                    const emp = row.c[7] && row.c[7].v !== null ? String(row.c[7].v).trim() : "";
                    if (emp !== "" && emp.toUpperCase() !== "EMPRESAS" && !empList.includes(emp)) {
                        empList.push(emp);
                    }
                });

                if (embList.length > 0) {
                    appState.cargadoExitosamente = true;
                    appState.embarcacionesMap = embMap;
                    appState.catalogos.EMBARCACIONES = embList;
                    appState.catalogos.CONTRATOS = conList;
                    appState.catalogos.EMPRESAS = empList;
                    appState.fuente = "linea";
                    guardarCache(embMap, embList, conList, empList);

                    poblarDatalists();

                    const statusDot = document.getElementById("statusDot");
                    const statusText = document.getElementById("statusText");
                    if (statusDot && statusText) {
                        statusDot.className = "w-2 h-2 rounded-full bg-emerald-500";
                        statusText.innerText = `${embList.length} Unidades Conectadas`;
                    }
                } else {
                    cargarModoRespaldo();
                }

            } catch (e) {
                console.error("Error al procesar datos:", e);
                cargarModoRespaldo();
            }
        };

        function cargarModoRespaldo() {
            if (appState.cargadoExitosamente) return;
            appState.cargadoExitosamente = true;
            if (cargarCache()) return;

            const embMap = {};
            const embList = [];
            CATALOGO_LOCAL_A_F.forEach(item => {
                embList.push(item.nombre);
                embMap[item.nombre] = item;
            });

            appState.embarcacionesMap = embMap;
            appState.catalogos.EMBARCACIONES = embList;
            appState.catalogos.CONTRATOS = CATALOGO_LOCAL_G;
            appState.catalogos.EMPRESAS = CATALOGO_LOCAL_H;

            poblarDatalists();

            const statusDot = document.getElementById("statusDot");
            const statusText = document.getElementById("statusText");
            if (statusDot && statusText) {
                statusDot.className = "w-2 h-2 rounded-full bg-blue-500";
                statusText.innerText = "Modo Respaldo Local";
            }
        }

        function poblarDatalists() {
            appState.embIndex = {};
            Object.keys(appState.embarcacionesMap).forEach(k => { appState.embIndex[k.toUpperCase()] = appState.embarcacionesMap[k]; });
            const listEmb = document.getElementById("lista-embarcaciones");
            const listCon = document.getElementById("lista-contratos");
            const listEmp = document.getElementById("lista-empresas");

            const renderOptions = (arr) => arr.map(i => `<option value="${escapeHtml(i)}"></option>`).join('');

            listEmb.innerHTML = renderOptions(appState.catalogos.EMBARCACIONES);
            const contratos = [...new Set([...appState.catalogos.CONTRATOS, ...Object.keys(appState.conCat || {}), ...Object.keys(CON_CAT.k)])];
            listCon.innerHTML = renderOptions(contratos);
            const ger = [...new Set(Object.values(CON_CAT.k).map(x => x[0].split("-").slice(0, 2).join("-")).filter(s => s && !/^SMEL-GSLM$/.test(s)))].sort();
            document.getElementById("dl-gerencias").innerHTML = renderOptions(ger);
            listEmp.innerHTML = renderOptions(appState.catalogos.EMPRESAS);
        }

        function detectarDatosEmbarcacion() {
            const nombre = document.getElementById("embarcacion").value.trim();
            const badge = document.getElementById("badgeDatosTecnicos");
            const data = buscarEmb(nombre);

            if (data) {
                document.getElementById("infoServicio").innerText = data.servicio || "N/A";
                document.getElementById("infoMMSI").innerText = data.mmsi || "N/A";
                document.getElementById("infoIMO").innerText = data.imo || "N/A";
                document.getElementById("infoCallsign").innerText = data.callsign || "N/A";
                document.getElementById("infoBandera").innerText = data.bandera || "N/A";
                badge.classList.remove("hidden");
                badge.classList.add("flex");
            } else {
                badge.classList.add("hidden");
                badge.classList.remove("flex");
            }
        }

        function detectarDatosSustitucion() {
            const nombre = document.getElementById("sustNombre").value.trim();
            const data = buscarEmb(nombre);

            if (data) {
                document.getElementById("sustIMO").value = (data.imo && data.imo !== "N/A") ? data.imo : "";
                document.getElementById("sustMMSI").value = (data.mmsi && data.mmsi !== "N/A") ? data.mmsi : "";
            }
        }

        function actualizarSubtramites() {
            const mod = document.getElementById("moduloOperativo").value;
            const selectSub = document.getElementById("subTramite");

            selectSub.innerHTML = "";
            manejarSeleccionSubtramite();

            if (!mod || !MODULOS[mod]) {
                selectSub.disabled = true;
                selectSub.className = "w-full bg-slate-100 border border-slate-200 rounded-xl p-3 text-sm text-slate-400 outline-none cursor-not-allowed";
                selectSub.innerHTML = '<option value="">-- Seleccione primero un Módulo Operativo --</option>';
                return;
            }

            selectSub.disabled = false;
            selectSub.className = "w-full bg-slate-50 border border-slate-200 rounded-xl p-3 text-sm font-medium text-slate-800 focus:ring-2 focus:ring-emerald-500 outline-none transition-all cursor-pointer";
            const grupos = {};
            Object.values(TRAMITES).filter(t => t.mod === mod).forEach(t => { (grupos[t.grupo] = grupos[t.grupo] || []).push(t); });
            selectSub.innerHTML = '<option value="">-- Seleccione el Sub-trámite / Motivo --</option>' + Object.entries(grupos).map(([g, ts]) =>
                `<optgroup label="${escapeHtml(g)}">${ts.map(t => `<option value="${t.id}">${escapeHtml(t.txt)}</option>`).join("")}</optgroup>`).join("");
        }

        function manejarSeleccionSubtramite() {
            appState.folioCEPAB = "";
            document.getElementById("resultadoCEPAB").classList.add("hidden"); // no dejar a la vista el correo de otro trámite
            const T = tram();
            const el = id => document.getElementById(id);
            const ver = (id, si) => el(id).classList.toggle("hidden", !si);
            const lugares = !!(T && T.lugares), temporal = !!(T && T.temporal), sinActivo = !!(T && T.sinActivo);

            ver("wrapGerencia", !!T);
            el("reqGerencia").classList.toggle("hidden", !(T && T.accion === "BAJA"));
            ver("bloqueSustitucion", !!(T && T.sust));
            if (T && T.sust) {
                el("tituloSust").textContent = T.sust === "sale" ? "Unidad a la que sustituye (sale)" : "Unidad que la sustituye (entra)";
                el("lblSustNombre").innerHTML = (T.sust === "sale" ? "Unidad que sale" : "Unidad que entra") + ' <span class="text-red-500">*</span>';
            }
            ver("bloqueSPOT", temporal);
            ver("wrapNumContratosSpot", temporal);
            ver("bloqueFijas", lugares);
            ver("wrapContrato", !!T && !temporal && !lugares);
            ver("wrapEmpresa", !!T && !temporal && !lugares);
            ver("wrapEmbarcacion", !!T && !lugares && !sinActivo);
            ver("wrapModalidad", !!T && !lugares && !sinActivo);
            ver("wrapRemolque", !!(T && T.activo === "ARTEFACTO" && T.accion === "ALTA"));
            ver("wrapTipoAtlas", !!(T && T.variante === "OTRO"));

            // La modalidad la define el sub-trámite en las altas; en las bajas se puede elegir
            const selMod = el("modalidadContratacion");
            if (T && T.modalidad) selMod.value = T.modalidad;
            else if (!T || T.accion !== "BAJA") selMod.value = "CONTRATO DEE";
            selMod.disabled = !!(T && T.accion === "ALTA");

            // Etiquetas con las mismas palabras de la Plataforma de Cédulas
            const nomEtq = T && T.accion === "ALTA" && T.activo === "ARTEFACTO" ? "Nombre del Artefacto Naval"
                : T && T.accion === "ALTA" && T.activo === "EMBARCACION" ? "Nombre de Embarcación" : "Embarcación o Artefacto Naval";
            el("lblEmbarcacion").innerHTML = `${nomEtq} <span class="text-red-500">*</span>`;
            el("embarcacion").placeholder = T && T.activo === "ARTEFACTO" && T.accion === "ALTA" ? "Escriba o busque el artefacto naval..." : "Escriba o busque embarcación...";
            if (lugares) {
                const camp = T.activo === "CAMPAMENTO";
                el("tituloFijas").textContent = camp ? "Alta de Campamentos" : "Alta de Instalaciones Fijas";
                el("lblNumFijas").innerHTML = (camp ? "¿Cuántos campamentos se darán de alta?" : "¿Cuántas instalaciones fijas se darán de alta?") + ' <span class="text-red-500">*</span>';
                const b = el("badgeDatosTecnicos");
                b.classList.add("hidden"); b.classList.remove("flex");
                renderFilasFijas();
            } else detectarDatosEmbarcacion();
            if (temporal) renderFilasSpot();

            mostrarInstruccionesSubtramite(T ? T.id : "");
            detectarGerencia();
            sugerirVariante();
        }

        /* ===== Área solicitante: se detecta con el contrato (estructura del catálogo) y se puede corregir ===== */
        function contratoReferencia() {
            const T = tram();
            if (T && T.temporal) { const c = document.querySelector("#filasContratosSpot .sp-con"); return c ? c.value.trim() : ""; }
            if (T && T.lugares) { const c = document.getElementById("fj_0_contrato"); return c ? c.value.trim() : ""; }
            return document.getElementById("contrato").value.trim();
        }
        function detectarGerencia() {
            const sel = document.getElementById("gerenciaSolicitante"), hint = document.getElementById("gerenciaHint");
            const num = contratoReferencia(), dc = datosContrato(num), clave = dc ? dc.clave : "";
            if (clave) {
                const gslm = /^SMEL-GSLM(-|$)/.test(clave);
                if (!appState.gerenciaManual) {
                    const antes = sel.value;
                    sel.value = gslm ? "GSLM" : "OTRA";
                    if (!gslm) document.getElementById("gerenciaOtra").value = clave.split("-").slice(0, 2).join("-");
                    if (sel.value !== antes) gerenciaCambio(false);
                }
                hint.textContent = `Detectado por el contrato ${dc.num || num}: ${clave}${gslm ? " (misma gerencia)" : ""}. Puede corregirlo.`;
            } else {
                hint.textContent = num ? "El contrato no tiene área asignada en el catálogo CEPAB: seleccione el área solicitante." : "Se detecta al capturar el contrato; también puede elegirla.";
            }
            document.getElementById("gerenciaOtra").classList.toggle("hidden", sel.value !== "OTRA");
        }
        function gerenciaCambio(manual) {
            if (manual) appState.gerenciaManual = true;
            document.getElementById("gerenciaOtra").classList.toggle("hidden", gerenciaActual() !== "OTRA");
            const T = tram();
            if (!T || T.accion !== "BAJA") return;
            // Las bajas cambian de requisitos: se conserva lo ya marcado
            const antes = {};
            document.querySelectorAll(".chk-requisito").forEach(c => { const l = c.closest("div").querySelector("label"); if (l) antes[l.innerText.trim()] = c.checked; });
            mostrarInstruccionesSubtramite(T.id);
            document.querySelectorAll(".chk-requisito").forEach(c => { const l = c.closest("div").querySelector("label"); if (l && antes[l.innerText.trim()]) c.checked = true; });
            actualizarProgresoChecklist();
        }
        function autocompletarContrato() {
            const num = document.getElementById("contrato").value.trim(), dc = datosContrato(num), emp = document.getElementById("empresa");
            if (dc && dc.cia && !emp.value.trim()) { emp.value = dc.cia; emp.classList.remove("campo-error"); }
            detectarGerencia();
        }

        /* ===== Sugerencia inteligente: ¿nuevo registro, reincorporación u otro contrato? (según el catálogo CEPAB) ===== */
        function sugerirVariante() {
            const T = tram(), hint = document.getElementById("hintEmb"), emb = document.getElementById("embarcacion").value.trim();
            const aplica = T && T.accion === "ALTA" && ["NUEVO", "REINC", "OTRO"].includes(T.variante) && ["EMBARCACION", "ARTEFACTO"].includes(T.activo) && !T.lugares;
            if (!aplica || !emb) { hint.classList.add("hidden"); return; }
            const enCat = !!buscarEmb(emb), b = (v, t) => `<button type="button" onclick="cambiarVariante('${v}')" class="ml-1 font-bold underline hover:text-amber-700">${t}</button>`;
            if (enCat && T.variante === "NUEVO") hint.innerHTML = `Esta unidad ya aparece en el catálogo CEPAB. ¿Es una ${b("REINC", "reincorporación")} o un ${b("OTRO", "alta en otro contrato")}?`;
            else if (!enCat && T.variante !== "NUEVO") hint.innerHTML = `Esta unidad no aparece en el catálogo CEPAB. Si nunca se ha registrado, es un ${b("NUEVO", "nuevo registro")}.`;
            else { hint.classList.add("hidden"); return; }
            hint.classList.remove("hidden");
        }
        function cambiarVariante(v) {
            const T = tram(); if (!T) return;
            const id = T.id.replace(/-[A-Z]+$/, "-" + v);
            if (!TRAMITES[id]) return;
            document.getElementById("subTramite").value = id;
            manejarSeleccionSubtramite();
            mostrarToast("Sub-trámite actualizado", TRAMITES[id].txt);
        }

        /* ===== Acceso directo a la Plataforma de Cédulas con los datos de esta solicitud ===== */
        function lugaresParaCedulas(indice) {
            const n = document.querySelectorAll("#filasFijas [data-fj]").length, out = [];
            const T = tram(), todos = T && T.activo === "CAMPAMENTO";
            for (let i = 0; i < n; i++) {
                if (!todos && indice !== undefined && i !== indice) continue;
                if (!todos && indice === undefined && i > 0) break;
                const g = k => gvFija(i, k);
                out.push({ nombre: g("ubicacion"), complejo: g("complejo"), sector: g("sector"), estructura: g("estructura"), proceso: g("proceso"), servicio: g("servicio"),
                    lat: [g("lat_g"), g("lat_m"), g("lat_s"), g("lat_h")], lon: [g("lon_g"), g("lon_m"), g("lon_s"), g("lon_h")],
                    ah: !!g("det_AH"), cepab: !!g("det_CEPAB"), heli: String(g("heli") || "").toUpperCase(), contrato: g("contrato"), compania: g("compania") });
            }
            return out;
        }
        function payloadCedulas(indice) {
            const T = tram(); if (!T || !T.ced) return null;
            const v = id => (document.getElementById(id) ? document.getElementById(id).value.trim() : "");
            const P = { v: 1, tram: T.id, tramTxt: `${T.grupo} — ${T.txt}`, t: T.ced.t, a: T.ced.a || "", ceds: T.ced.ceds || "paquete", datos: {} };
            const d = P.datos, ficha = (v("supervisorFicha").match(/\b\d{5,8}\b/) || [""])[0];
            if (T.temporal) {
                P.d = v("dependenciaSpot") || "PMX";
                d.c_equipo = v("embarcacion");
                d.t_sol_nombre = v("supervisorNombre");
                P.ct = [...document.querySelectorAll("#filasContratosSpot [data-row]")].map(r => ({ num: r.querySelector(".sp-con").value.trim(), sup: r.querySelector(".sp-sup").value.trim(), cia: r.querySelector(".sp-emp").value.trim() }))
                    .filter(x => x.num || x.sup || x.cia);
            } else if (T.lugares) {
                P.lugares = lugaresParaCedulas(indice);
                const l0 = P.lugares[0] || {};
                d.c_num = l0.contrato || v("contrato");
                d.c_cia = l0.compania || v("empresa");
                d.mando_sp_nombre = v("supervisorNombre");
                d.mando_sp_ficha = ficha;
                if (l0.heli && !/^(N\/?A|NO)$/.test(l0.heli)) { P.heli = "SI"; d.h_siglas = l0.heli; }
            } else {
                if (!T.sinActivo) d.c_equipo = v("embarcacion");
                d.c_num = v("contrato");
                d.c_cia = v("empresa");
                d.mando_sp_nombre = v("supervisorNombre");
                d.mando_sp_ficha = ficha;
                if (T.variante === "OTRO") d.g_tipo = v("tipoContratoAtlas");
                if (T.variante === "REINC") d.c_obs = "Reincorporación: la unidad estuvo registrada previamente en CEPAB.";
                if (T.sust === "sale" && v("sustNombre")) {
                    const ids = [v("sustIMO") && `IMO ${v("sustIMO")}`, v("sustMMSI") && `MMSI ${v("sustMMSI")}`].filter(Boolean).join(", ");
                    d.c_obs = `Alta por sustitución: sustituye a ${v("sustNombre")}${ids ? ` (${ids})` : ""}.`;
                }
            }
            if (T.activo === "ARTEFACTO" && v("remolcador")) P.rm = v("remolcador").split(/[,;\/]+/).map(s => s.trim()).filter(Boolean);
            const rh = document.querySelector('#listaChecklist input[name^="opt_heli_"]:checked');
            if (rh) {
                P.heli = rh.value;
                const s = document.getElementById(`valSSCTAPC_Codigo_${rh.getAttribute("data-index")}`);
                if (rh.value === "SI" && s && s.value.trim()) d.h_siglas = s.value.trim().toUpperCase();
            }
            Object.keys(d).forEach(k => { if (!d[k]) delete d[k]; });
            return P;
        }
        function abrirCedulas(indice) {
            const P = payloadCedulas(indice);
            if (!P) { mostrarToast("Sin cédulas", "Este sub-trámite no se tramita en la Plataforma de Cédulas."); return; }
            const w = window.open(`${ARCH_CEDULAS}#dir=${encodeURIComponent(JSON.stringify(P))}`, "_blank");
            if (!w) mostrarToast("Ventana bloqueada", "Permita las ventanas emergentes para este archivo y vuelva a intentarlo.");
            else mostrarToast("Plataforma de Cédulas", "Se abrió en otra pestaña con el trámite elegido y los datos prellenados.");
        }

        function mostrarInstruccionesSubtramite(subtramite) {
            const area = document.getElementById("areaInstrucciones");
            const titulo = document.getElementById("tituloInstrucciones");
            const lista = document.getElementById("listaChecklist");
            const boxTextual = document.getElementById("boxInstruccionTextual");
            const textoTextual = document.getElementById("textoInstruccion");

            if (!subtramite) {
                ocultarInstrucciones();
                return;
            }

            const T = TRAMITES[subtramite];
            const config = T ? { titulo: T.titulo, items: requisitosDe(T), instruccion: instruccionDe(T) } : {
                titulo: `Requisitos de Validación: ${subtramite}`,
                items: [{ texto: "Verifique las cédulas en PDF firmado y el archivo CSV.", tipo: "simple" }],
                instruccion: "Asegúrese de contar con los avales y visto bueno correspondientes."
            };

            titulo.innerText = config.titulo;
            lista.innerHTML = "";

            if (config.items && config.items.length > 0) {
                config.items.forEach((itemObj, idx) => {
                    const textoReq = itemObj.texto;
                    const tipoReq = itemObj.tipo;

                    const divWrapper = document.createElement("div");
                    divWrapper.className = "bg-white p-3.5 rounded-xl border border-emerald-100 shadow-sm transition-all";

                    let htmlItem = `
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                            <div class="flex items-center gap-2.5 flex-grow">
                                <input type="checkbox" id="chk_${idx}" class="chk-requisito rounded border-slate-300 text-emerald-600 focus:ring-emerald-500 w-4 h-4 shrink-0 transition-colors ${tipoReq === 'simple' ? 'cursor-pointer' : 'pointer-events-none'}" ${tipoReq === 'simple' ? '' : 'disabled'}>
                                <label for="chk_${idx}" class="text-xs font-semibold text-slate-700 ${tipoReq === 'simple' ? 'cursor-pointer hover:text-emerald-700 transition-colors' : 'select-none'}">
                                    ${escapeHtml(textoReq)}
                                </label>
                            </div>
                    `;

                    if (tipoReq === "sino_rn") {
                        htmlItem += `
                            <div class="flex items-center gap-4 text-xs font-bold text-slate-700 shrink-0 bg-slate-50 px-3 py-1.5 rounded-lg border border-slate-200">
                                <span class="text-[11px] text-slate-500">¿Tienes el Resultado?</span>
                                <label class="flex items-center gap-1 cursor-pointer">
                                    <input type="radio" name="opt_rn_${idx}" value="SI" class="sino-radio text-emerald-600 focus:ring-emerald-500" data-index="${idx}"> SI
                                </label>
                                <label class="flex items-center gap-1 cursor-pointer">
                                    <input type="radio" name="opt_rn_${idx}" value="NO" class="sino-radio text-amber-600 focus:ring-amber-500" data-index="${idx}"> NO
                                </label>
                            </div>
                        `;
                    } else if (tipoReq === "sino_cedulas") {
                        htmlItem += `
                            <div class="flex items-center gap-4 text-xs font-bold text-slate-700 shrink-0 bg-slate-50 px-3 py-1.5 rounded-lg border border-slate-200">
                                <span class="text-[11px] text-slate-500">¿Tienes las Cédulas?</span>
                                <label class="flex items-center gap-1 cursor-pointer">
                                    <input type="radio" name="opt_ced_${idx}" value="SI" class="sino-radio text-emerald-600 focus:ring-emerald-500" data-index="${idx}"> SI
                                </label>
                                <label class="flex items-center gap-1 cursor-pointer">
                                    <input type="radio" name="opt_ced_${idx}" value="NO" class="sino-radio text-amber-600 focus:ring-amber-500" data-index="${idx}"> NO
                                </label>
                            </div>
                        `;
                    } else if (tipoReq === "sino_helipad") {
                        htmlItem += `
                            <div class="flex items-center gap-4 text-xs font-bold text-slate-700 shrink-0 bg-slate-50 px-3 py-1.5 rounded-lg border border-slate-200">
                                <span class="text-[11px] text-slate-500">¿Tienes heliplataforma?</span>
                                <label class="flex items-center gap-1 cursor-pointer">
                                    <input type="radio" name="opt_heli_${idx}" value="SI" class="sino-radio text-emerald-600 focus:ring-emerald-500" data-index="${idx}"> SI
                                </label>
                                <label class="flex items-center gap-1 cursor-pointer">
                                    <input type="radio" name="opt_heli_${idx}" value="NO" class="sino-radio text-amber-600 focus:ring-amber-500" data-index="${idx}"> NO
                                </label>
                            </div>
                        `;
                    }

                    htmlItem += `</div>`;

                    // SUBPANEL CONDICIONAL PARA SI/NO RN
                    if (tipoReq === "sino_rn") {
                        htmlItem += `
                            <div id="subpanel_rn_${idx}" class="hidden mt-3 pt-3 border-t border-slate-100 text-xs text-amber-900 bg-amber-50/80 p-3 rounded-lg border-amber-200 space-y-1">
                                <p class="font-bold flex items-center gap-1 text-amber-800">
                                    <i data-lucide="alert-circle" class="w-4 h-4 text-amber-600"></i> Si la respuesta es NO, Instrucciones para solicitar Visto Bueno y/o Inspección para Contrato Directo PEMEX:
                                </p>
                                <p class="text-[11px] text-slate-700">
                                    • Gestionar la solicitud de <strong>Visto Bueno y/o Inspección</strong> dirigido a la <strong>Jefatura de Regulación Naval</strong>.
                                </p>
                            </div>
                        `;
                    }

                    // SUBPANEL CONDICIONAL PARA SI/NO CÉDULAS: acceso directo a la Plataforma de Cédulas con prellenado
                    if (tipoReq === "sino_cedulas") {
                        htmlItem += `
                            <div id="subpanel_ced_${idx}" class="hidden mt-3 pt-3 border-t border-slate-100 text-xs text-amber-900 bg-amber-50/80 p-3 rounded-lg border-amber-200 space-y-2">
                                <p class="font-bold flex items-center gap-1 text-amber-800">
                                    <i data-lucide="alert-circle" class="w-4 h-4 text-amber-600"></i> Genérelas ahora en la Plataforma de Cédulas CEPAB: se abre con el trámite, el activo y la modalidad ya elegidos y con los datos de esta solicitud prellenados.
                                </p>
                                <button type="button" onclick="abrirCedulas()" class="bg-emerald-600 hover:bg-emerald-500 text-white text-xs font-bold px-3 py-2 rounded-lg inline-flex items-center gap-1.5"><i data-lucide="file-text" class="w-4 h-4"></i> Llenar las cédulas ahora</button>
                                <p class="text-[11px] text-slate-600">Entregue el PDF firmado y el archivo CSV (y, si aplica, el ZIP de evidencias fotográficas). Después regrese aquí y marque «SI».</p>
                            </div>
                            <div id="subpanel_ced_si_${idx}" class="hidden mt-2 text-[11px] text-slate-600">¿Necesita revisarlas o corregirlas? <button type="button" onclick="abrirCedulas()" class="font-semibold text-emerald-700 hover:text-emerald-800 underline">Abrir la Plataforma de Cédulas</button></div>
                        `;
                    }

                    // SUBPANEL CONDICIONAL PARA HELIPLATAFORMA (SI / NO)
                    if (tipoReq === "sino_helipad") {
                        htmlItem += `
                            <div id="subpanel_helipad_${idx}" class="hidden mt-3 pt-3 border-t border-slate-100 space-y-3 bg-slate-50/80 p-3 rounded-lg border border-slate-200">

                                <!-- SUB-BLOQUE A: YA LO TIENE -->
                                <div id="boxSSCTAPC_Tiene_${idx}" class="space-y-1">
                                    <label class="block text-[11px] font-bold text-slate-600">Siglas del Identificador Aéreo asignadas por la SSCTAPC <span class="text-red-500">*</span></label>
                                    <input type="text" id="valSSCTAPC_Codigo_${idx}" placeholder="EJ. ABCD" class="w-full bg-white border border-emerald-300 rounded-lg p-2 text-xs font-mono uppercase focus:ring-2 focus:ring-emerald-500 outline-none" maxlength="6">
                                </div>

                                <!-- SUB-BLOQUE B: NO LO TIENE (INFORMACIÓN PARA SOLICITAR - DIRECTORIO) -->
                                <div id="boxSSCTAPC_NoTiene_${idx}" class="bg-red-50 border border-red-300 rounded-xl p-3.5 text-xs text-slate-700 space-y-2 shadow-sm">
                                    <p class="font-bold text-red-700 flex items-center gap-1.5"><i data-lucide="alert-triangle" class="w-4 h-4 text-red-600"></i> Falta el identificador aéreo (siglas) de la heliplataforma. No se podrá generar el correo hasta capturarlo.</p>
                                    <p class="text-[11px] text-slate-600 leading-relaxed">
                                        Por instrucciones del <strong>Líder de Control Marino y Sistemas de Radar</strong>, se informa que toda embarcación, instalación o artefacto naval que cuente con <strong>HELIPLATAFORMA</strong> y requiera servicios de transporte aéreo de personal, debe realizar la gestión formal ante la <strong>Supervisión de Servicios y Contratos de Transporte Aéreo de Personal Carmen (SSCTAPC)</strong> para la asignación del identificador aéreo correspondiente.
                                    </p>
                                    <div class="bg-amber-50 border border-amber-200 rounded-lg p-2.5 text-[11px] space-y-1">
                                        <p class="font-bold text-amber-900">ACCIÓN MANDATORIA PARA EL ALTA EN SISTEMA:</p>
                                        <p class="text-slate-600">Es indispensable coordinar con el titular de la SSCTAPC la validación de las siglas de heliplataforma previo al registro en el sistema. En caso de no requerir este servicio, es necesario notificarlo formalmente a la autoridad para proceder con el <strong>ALTA inmediata</strong> en el sistema, asegurando la integridad de los datos en las cédulas de registro.</p>
                                    </div>
                                    <div class="pt-2 border-t border-slate-100 text-[11px] space-y-1 font-mono text-slate-600">
                                        <p class="font-bold text-slate-800">Directorio de contacto - SSCTAPC:</p>
                                        <p>• <strong>Carlos Torres López:</strong> <a href="mailto:carlos.torres@pemex.com" class="text-blue-600 underline">carlos.torres@pemex.com</a> | Ext. (801) 2-71-04</p>
                                        <p>• <strong>Juana Ortega Bonola:</strong> <a href="mailto:juana.ortega@pemex.com" class="text-blue-600 underline">juana.ortega@pemex.com</a> | Ext. (801) 2-71-10</p>
                                        <p>• <strong>Raúl Rodríguez Estrada:</strong> <a href="mailto:raul.rodrigueze@pemex.com" class="text-blue-600 underline">raul.rodrigueze@pemex.com</a> | Ext. (801) 2-71-02</p>
                                    </div>
                                    <button type="button" onclick="solicitarSiglasDir(${idx})" class="bg-red-600 hover:bg-red-500 text-white font-bold text-xs px-3 py-2 rounded-lg flex items-center gap-1.5"><i data-lucide="mail" class="w-4 h-4"></i> Solicitar siglas a la SSCTAPC (generar correo)</button>
                                    <div id="correoSiglasDir_${idx}" class="hidden"></div>
                                </div>
                            </div>
                        `;
                    }

                    divWrapper.innerHTML = htmlItem;
                    lista.appendChild(divWrapper);
                });

                lista.classList.remove("hidden");

                // Eventos para los checkboxes tipo 'simple' (interacción manual)
                lista.querySelectorAll(".chk-requisito").forEach(chk => {
                    if (!chk.disabled) {
                        chk.addEventListener("change", actualizarProgresoChecklist);
                    }
                });

                // Eventos para los radios de SI / NO en cada requisito
                lista.querySelectorAll(".sino-radio").forEach(radio => {
                    radio.addEventListener("change", (e) => {
                        const idx = e.target.getAttribute("data-index");
                        const val = e.target.value;
                        const chk = document.getElementById(`chk_${idx}`);
                        
                        // Controlar el Checkbox principal según SI o NO
                        // En heliplataforma basta con responder (SI o NO) para validar
                        const esHeli = e.target.name.startsWith("opt_heli_");
                        chk.checked = (val === "SI") || esHeli;

                        // Mostrar u ocultar subpaneles específicos
                        const subRn = document.getElementById(`subpanel_rn_${idx}`);
                        if (subRn) {
                            if (val === "NO") subRn.classList.remove("hidden");
                            else subRn.classList.add("hidden");
                        }

                        const subCed = document.getElementById(`subpanel_ced_${idx}`);
                        if (subCed) {
                            if (val === "NO") subCed.classList.remove("hidden");
                            else subCed.classList.add("hidden");
                        }
                        const subCedSi = document.getElementById(`subpanel_ced_si_${idx}`);
                        if (subCedSi) subCedSi.classList.toggle("hidden", val !== "SI");

                        const subHelipad = document.getElementById(`subpanel_helipad_${idx}`);
                        if (subHelipad) {
                            if (val === "SI") subHelipad.classList.remove("hidden");
                            else subHelipad.classList.add("hidden");
                        }

                        actualizarProgresoChecklist();
                    });
                });

// Heliplataforma: si faltan las siglas, campo en rojo y directorio de la SSCTAPC visible
lista.querySelectorAll("[id^='valSSCTAPC_Codigo_']").forEach(inp => {
    const idxReal = inp.id.split("_").pop();
    const actualizar = () => {
        const falta = !inp.value.trim();
        inp.classList.toggle("campo-error", falta);
        const box = document.getElementById(`boxSSCTAPC_NoTiene_${idxReal}`);
        if (box) box.classList.toggle("hidden", !falta);
    };
    inp.addEventListener("input", actualizar);
    actualizar();
});

            } else {
                lista.classList.add("hidden");
            }

            if (config.instruccion) {
                textoTextual.innerText = config.instruccion;
                boxTextual.classList.remove("hidden");
                boxTextual.classList.add("flex");
            } else {
                boxTextual.classList.add("hidden");
                boxTextual.classList.remove("flex");
            }

            area.classList.remove("hidden");
            actualizarProgresoChecklist();
            reInitLucide();
        }

        function ocultarInstrucciones() {
            const area = document.getElementById("areaInstrucciones");
            if (area) area.classList.add("hidden");
        }

        function actualizarProgresoChecklist() {
            const checkboxes = document.querySelectorAll(".chk-requisito");
            const badge = document.getElementById("badgeProgreso");

            if (checkboxes.length === 0) {
                badge.classList.add("hidden");
                return;
            }

            badge.classList.remove("hidden");
            const total = checkboxes.length;
            let marcados = 0;

            checkboxes.forEach(chk => { if (chk.checked) marcados++; });

            if (marcados === total) {
                badge.className = "text-[11px] font-bold px-2.5 py-0.5 rounded-full bg-emerald-600 text-white shadow-sm flex items-center gap-1";
                badge.innerHTML = `<i data-lucide="check-circle" class="w-3 h-3"></i> ${marcados}/${total} Validado(s)`;
            } else {
                badge.className = "text-[11px] font-bold px-2.5 py-0.5 rounded-full bg-amber-100 text-amber-800 border border-amber-300";
                badge.innerHTML = `${marcados}/${total} Validado(s)`;
            }
            reInitLucide();
        }

        function obtenerResumenChecklist() {
            let resumen = [];
            document.querySelectorAll(".chk-requisito").forEach((chk, idx) => {
                const label = chk.closest('div').querySelector('label').innerText.trim();
                let linea = `  - [${chk.checked ? '✓ CUMPLE (SI)' : '✗ NO CUMPLE (NO) / PENDIENTE'}] ${label}`;

                const _rh = document.querySelector(`input[name="opt_heli_${idx}"]:checked`);
                if (_rh) linea = `  - [✓ RESPONDIDO: ${_rh.value === "SI" ? "SI CUENTA CON HELIPLATAFORMA" : "NO CUENTA CON HELIPLATAFORMA"}] ${label}`;
                const inputHeliCode = document.getElementById(`valSSCTAPC_Codigo_${idx}`);
                const _subHeli = document.getElementById(`subpanel_helipad_${idx}`);
                const _visible = _subHeli && !_subHeli.classList.contains('hidden');
                if (inputHeliCode && _visible) linea += ` (SIGLAS IDENTIFICADOR AÉREO: ${inputHeliCode.value.trim().toUpperCase()})`;

                resumen.push(linea);
            });

            if (resumen.length === 0) return "";
            return `\n\nCHECKLIST DE GOBERNANZA Y REQUISITOS:\n` + resumen.join("\n");
        }

        function generarSolicitudCEPAB(opts = {}) {
            const T = tram();
            const val = id => document.getElementById(id).value.trim();
            if (!validarFormulario()) return false;
            const modalidadTxt = { "CONTRATO DEE": "Contrato DEE", "AUTORIZACION TEMPORAL": "Autorización Temporal (mercado SPOT)", "SERVICIO GSLM": "Servicio SMEL-GSLM (Logística Marina)" }[val("modalidadContratacion")] || val("modalidadContratacion");
            const emb = val("embarcacion");
            const contrato = val("contrato") || "[Número de Contrato]";
            const empresa = val("empresa") || "[Compañía / Contratista]";
            const supNombre = val("supervisorNombre") || "[Nombre del Supervisor / Solicitante]";
            const supFicha = val("supervisorFicha") || "[Ficha PEMEX / Cargo]";
            const obs = val("observaciones");
            const dataTec = buscarEmb(emb) || {};
            const mmsiVal = dataTec.mmsi || "[MMSI]";
            const nomAct = ACTIVOS[T.activo] || "Embarcación / Artefacto Naval";

            if (!appState.folioCEPAB) appState.folioCEPAB = generarFolio();
            const checklistTxt = obtenerResumenChecklist();
            const de = `De: ${supNombre} (${supFicha})\nÁrea solicitante: ${areaSolicitanteTxt()}`;
            const firma = `\n\nAtentamente,\n${supNombre}\n${supFicha}`;
            const sust = { n: val("sustNombre") || "[Nombre]", i: val("sustIMO") || "[IMO]", m: val("sustMMSI") || "[MMSI]" };
            const unidad = `* ${nomAct}: ${emb}\n* MMSI: ${mmsiVal} | IMO: ${dataTec.imo || "[IMO]"} | Call Sign: ${dataTec.callsign || "[Call Sign]"}`;
            const remTxt = T.activo === "ARTEFACTO" ? `* Embarcación(es) que lo remolcarán: ${val("remolcador") || "[Por definir]"}\n` : "";
            let asunto = "", cuerpo = "";

            if (T.accion === "ALTA" && T.lugares) {
                const camp = T.activo === "CAMPAMENTO", fj = obtenerFijas(), et = camp ? "CAMPAMENTO" : "INSTALACIÓN";
                const bloques = fj.map((f, i) => `${et} ${i + 1} DE ${fj.length}\n* Región: ${f.region}\n* Activo: ${f.activo}\n* Complejo: ${f.complejo}\n* D.1. Ubicación actual: ${f.ubicacion}\n* Siglas / identificador de heliplataforma: ${f.heli || "N/A"}\n* Clasificado por servicio: ${f.servicio}\n* Clasificado por proceso: ${f.proceso}\n* Tipo de estructura: ${f.estructura}\n* Sector: ${f.sector}\n* Misión: ${f.mision}\n* Latitud: ${f.lat}\n* Longitud: ${f.lon}\n* Detalles (servicios a solicitar): ${f.detalles}\n* Fija / Móvil: ${f.fijamovil}\n* Compañía: ${f.compania}\n* Contrato: ${f.contrato}\n* Inicio: ${f.inicio}`).join("\n\n");
                asunto = `SOLICITUD DE ALTA DE ${camp ? "CAMPAMENTO" : "INSTALACIÓN FIJA"} — ${fj.map(f => f.ubicacion).join(" / ")}`;
                cuerpo = `A: Control de Embarcaciones y Personal a Bordo (CEPAB) / Normativo del Atlas GL\n${de}\n\nPor medio del presente, en mi calidad de Supervisor de Contrato DEE, solicito formalmente el ALTA de ${fj.length} ${camp ? "campamento(s)" : "instalación(es) fija(s)"} en el catálogo Atlas GL / CEPAB, con la siguiente información:\n\n${bloques}\n\nObservaciones: ${obs || "Sin observaciones adicionales"}${checklistTxt}\n\nSe adjuntan las cédulas CEPAB (CED Atlas GL, CED-03 Contrato y CED-06 Acreedores) en PDF firmado junto con el archivo CSV.${firma}`;

            } else if (T.accion === "ALTA" && T.temporal) {
                const filasSpot = [...document.querySelectorAll("#filasContratosSpot [data-row]")].map((r, i) =>
                    `  ${i + 1}. Contrato DEE: ${r.querySelector(".sp-con").value.trim()} | Supervisor: ${r.querySelector(".sp-sup").value.trim() || "[Supervisor]"} | Compañía: ${r.querySelector(".sp-emp").value.trim()}`);
                const resumen = [...document.querySelectorAll("#filasContratosSpot .sp-con")].map(e => e.value.trim()).join(", ");
                const dep = val("dependenciaSpot");
                asunto = `AUTORIZACIÓN TEMPORAL (${dep}) — ${nomAct.toUpperCase()} ${emb} — CONTRATOS: ${resumen}`;
                cuerpo = `A: Control de Embarcaciones y Personal a Bordo (CEPAB)\n${de}\n\nSolicito la AUTORIZACIÓN TEMPORAL (mercado SPOT) para ${nomAct.toLowerCase() === "embarcación" ? "la embarcación" : "el artefacto naval"} ${emb} (sin contrato permanente), para prestar servicios operativos temporales.\n\n${unidad}\n* Dependencia / tipo de folio: ${dep} (folio por asignar por el Área de Enlace de Integración y Evaluación)\n${remTxt}* Cantidad de contratos en los que operará: ${filasSpot.length}\n${filasSpot.join("\n")}\n* Observaciones: ${obs || "Sin observaciones adicionales"}${checklistTxt}\n\nSe adjunta oficio formal remitido a la SMEL-GSLM, dictamen técnico vigente de Regulación Naval y las cédulas (CED Atlas GL y CED-03 Folio ${dep}; los usuarios CEPAB van dentro del Atlas GL) en PDF firmado junto con el archivo CSV y el ZIP de evidencias fotográficas (FOTOS ${emb} - Folio ${dep}.zip), para la asignación del folio ${dep}.${firma}`;

            } else if (T.accion === "ALTA") {
                const tipoAtlas = { PERMANENTE: "Permanente (activo principal del contrato)", ADICIONAL: "Adicional (apoyo secundario; también permanente)" }[val("tipoContratoAtlas")] || "[Tipo de contrato]";
                const V = {
                    NUEVO: ["SOLICITUD DE ALTA — NUEVO REGISTRO EN CEPAB", "el NUEVO REGISTRO en CEPAB y el alta en el catálogo Atlas GL", ""],
                    REINC: ["SOLICITUD DE REINCORPORACIÓN EN CEPAB", "la REINCORPORACIÓN en CEPAB (unidad registrada previamente)", "* Reincorporación: unidad registrada previamente en CEPAB\n"],
                    SUST: ["SOLICITUD DE ALTA POR SUSTITUCIÓN", "el ALTA POR SUSTITUCIÓN", `* Sustituye a (sale): ${sust.n} (IMO: ${sust.i}, MMSI: ${sust.m})\n`],
                    OTRO: ["SOLICITUD DE ALTA EN OTRO CONTRATO", "el ALTA EN OTRO CONTRATO de la unidad, ya registrada en CEPAB", `* Tipo de contrato en el Atlas GL: ${tipoAtlas}\n`]
                }[T.variante];
                asunto = `${V[0]} — ${nomAct.toUpperCase()} ${emb} — CONTRATO ${contrato} — MMSI: ${mmsiVal}${T.variante === "SUST" ? ` — SUSTITUYE A ${sust.n}` : ""}`;
                cuerpo = `A: Centro de Control de Tráfico Marítimo / Control de Embarcaciones y Personal a Bordo (CEPAB)\n${de}\n\nPor medio del presente, en mi calidad de Supervisor del Contrato DEE N.º ${contrato}, solicito formalmente ${V[1]}:\n\n${unidad}\n* Modalidad: Contrato DEE\n* Número de Contrato: ${contrato}\n* Compañía / Contratista: ${empresa}\n${V[2]}${remTxt}* Ubicación / Coordenadas / Observaciones: ${obs || "Conforme a programa operativo"}${checklistTxt}\n\nAdjunto al presente las cédulas CEPAB (CED Atlas GL, CED-03 Contrato y CED-06 Acreedores; los usuarios CEPAB van dentro del Atlas GL) en PDF firmado junto con el archivo CSV, el ZIP de evidencias fotográficas (FOTOS ${emb} - ${contrato}.zip, fotos renombradas con el nombre de la unidad), carátula de contrato, captura de SAP, dictamen de aptitud de Regulación Naval y el soporte de heliplataforma / exención.${firma}`;

            } else if (T.accion === "BAJA") {
                const g = gerenciaActual();
                const motivo = { TERM: "BAJA POR TÉRMINO DE CONTRATO (DESINCORPORACIÓN)", SUST: "BAJA POR SUSTITUCIÓN DE UNIDAD", FIN: "FIN DE LA AUTORIZACIÓN TEMPORAL / CIERRE DE VIAJE" }[T.variante];
                const conf = g === "GSLM"
                    ? "1. Los viajes de la unidad están cerrados en el sistema CICOL.\n2. El personal a bordo está reportado en ceros (0) en el sistema CEPAB.\n3. El costeo de la embarcación está finalizado."
                    : "1. El personal a bordo está reportado en ceros (0) en el sistema CEPAB.\n2. La Supervisión de Contrato solicita la baja de forma explícita mediante este correo electrónico.";
                asunto = T.variante === "FIN" ? `FIN DE AUTORIZACIÓN TEMPORAL / CIERRE DE VIAJE — ${emb}` : `SOLICITUD DE ${motivo} — ${nomAct.toUpperCase()} ${emb} — [${modalidadTxt}]`;
                cuerpo = `A: Control de Embarcaciones y Personal a Bordo (CEPAB)\n${de}\n\nSolicito formalmente procesar la ${motivo} de la siguiente unidad en el catálogo Atlas GL:\n\n${unidad}\n* Modalidad: ${modalidadTxt}\n* Contrato: ${val("contrato") || "N/A"}\n${T.sust === "entra" ? `* Unidad que la sustituye (entra): ${sust.n} (IMO: ${sust.i}, MMSI: ${sust.m})\n` : ""}\nCONFIRMACIÓN DE CRITERIOS DE CIERRE (${g === "GSLM" ? "SMEL-GSLM" : "otra gerencia"}):\n${conf}${checklistTxt}${firma}`;

            } else if (T.accion === "CONTRATO") {
                const vig = T.variante === "VIG";
                asunto = `SOLICITUD DE ${vig ? "AMPLIACIÓN DE VIGENCIA" : "ALTA"} — CONTRATO DEE N.º ${contrato}`;
                cuerpo = `A: Coordinación de Integración y Programación de los Servicios (Atn. Ing. Manuel Reynaldo Alegría / Ing. Mónica Rubio)\nCon copia a: Jefatura del CCTM / Control de Embarcaciones y Personal a Bordo (CEPAB)\n${de}\n\nPor medio del presente solicito ${vig ? "la ampliación / actualización de vigencia" : "el alta"} del contrato DEE en el catálogo institucional conforme a la siguiente información:\n\n* Número de Contrato: ${contrato}\n* Compañía / Contratista: ${empresa}\n* Observaciones / Vigencia: ${obs || "Conforme a adendum / carátula adjunta"}${checklistTxt}\n\nSe adjunta carátula de contrato vigente, ${vig ? "la cédula CED-03 Contrato" : "las cédulas CED-03 Contrato y CED-06 Acreedores"} en PDF firmado junto con el archivo CSV, y la captura del sistema SAP.${firma}`;

            } else if (T.accion === "PAB") {
                asunto = `${T.variante === "OK" ? "SOLICITUD DE VALIDACIÓN OK-CEPAB" : "ACTUALIZACIÓN Y REPORTE DIARIO PAB"} — ${emb} — ${new Date().toLocaleDateString("es-MX")}`;
                cuerpo = `A: Control de Embarcaciones y Personal a Bordo (CEPAB)\nDe: ${supNombre} (Capitán / Administrador de la Unidad ${emb})\nÁrea solicitante: ${areaSolicitanteTxt()}\n\nSe notifica la actualización del reporte de Personal a Bordo (PAB) en la plataforma CEPAB correspondiente al día de hoy:\n\n* Embarcación: ${emb} (MMSI: ${mmsiVal})\n* Contrato / Compañía: ${contrato} - ${empresa}\n* Estatus en el portal: actualizado al 100 % conforme al oficio PEP-SML-717-2011.\n* Detalle / Bitácora: ${obs || "Censo al día sin novedades"}${checklistTxt}\n\nSe solicita la emisión del estatus de validación OK-CEPAB.${firma}`;

            } else if (T.accion === "DECLARACION") {
                asunto = `DECLARACIÓN DE CONFORMIDAD E INFORMACIÓN ACTUALIZADA — CONTRATO DEE ${contrato}`;
                cuerpo = `A: Control de Embarcaciones y Personal a Bordo (CEPAB) / CCTM\n${de}\n\nPor medio del presente correo, en mi carácter de Supervisor del Contrato DEE N.º ${contrato}, emito la DECLARACIÓN DE INFORMACIÓN ACTUALIZADA Y CONFORME para la unidad asignada a este contrato:\n\n* Unidad involucrada: ${emb} (MMSI: ${mmsiVal})\n* Compañía: ${empresa}\n\nVALIDACIONES RATIFICADAS BAJO PROTESTA DE DECIR VERDAD:\n1. Censo PAB: el conteo en el portal CEPAB concuerda fielmente con las bitácoras físicas de embarque y desembarque.\n2. Seguridad y documentación: la tripulación y el personal cumplen con la certificación técnica y libretas de mar vigentes.\n3. Estatus técnico: los dictámenes de Regulación Naval y los permisos de heliplataforma se encuentran vigentes.\n4. Operación contractual: las actividades ejecutadas corresponden a los frentes de trabajo autorizados.\n\nOtorgo el Vo.Bo. formal para la consolidación de la información operativa en CEPAB y la trazabilidad de estimaciones.${checklistTxt}${firma}`;
            }
            appState.asuntoCEPAB = asunto;
            appState.cuerpoCEPAB = cuerpo;

            const pend = document.querySelectorAll(".chk-requisito:not(:checked)").length;
            if (pend > 0) {
                appState.cuerpoCEPAB = appState.cuerpoCEPAB.replace("\n\nAtentamente,", `\n\nNOTA: ${pend} requisito(s) figuran como PENDIENTE y serán regularizados a la brevedad.\n\nAtentamente,`);
            }
            appState.cuerpoCEPAB = `Folio de referencia: ${appState.folioCEPAB} (Plataforma de Solicitudes y Directorio CEPAB, versión ${(window.VER_CEPAB || {}).version || ""})\n\n` + appState.cuerpoCEPAB;

            const avisos = [];
            if (pend > 0) avisos.push(`${pend} requisito(s) del checklist sin validar; el correo los marca como PENDIENTE.`);
            if (!T.lugares && !T.sinActivo && !buscarEmb(emb)) avisos.push("La unidad no está en el catálogo CEPAB: MMSI, IMO y Call Sign quedaron como marcadores.");
            document.getElementById("listaAvisos").innerHTML = avisos.map(a => `<li>${escapeHtml(a)}</li>`).join("");
            document.getElementById("avisoPendientes").classList.toggle("hidden", avisos.length === 0);

            document.getElementById("displayFolio").innerText = "FOLIO: " + appState.folioCEPAB;
            document.getElementById("displayAsunto").innerText = appState.asuntoCEPAB;
            document.getElementById("displayCuerpo").innerText = appState.cuerpoCEPAB;

            const ccEmail = val("ccEmail");
            const filaCC = document.getElementById("filaCC");
            const displayCC = document.getElementById("displayCC");
            if (ccEmail) {
                displayCC.innerText = ccEmail;
                filaCC.classList.remove("hidden");
            } else {
                filaCC.classList.add("hidden");
            }

            const contenedor = document.getElementById("resultadoCEPAB");
            contenedor.classList.remove("hidden");
            if (!opts.silencioso) contenedor.scrollIntoView({ behavior: 'smooth', block: 'nearest' });

            guardarPrefs();
            if (!opts.silencioso) mostrarToast("Documento Generado", "Revise el cuerpo e inicie el envío.");
            reInitLucide();
            return true;
        }

        function enviarPorMailto() {
            if (!generarSolicitudCEPAB({ silencioso: true })) return;
            const cc = document.getElementById("ccEmail").value.trim();
            let url = `mailto:${encodeURIComponent(appState.correoDestino)}?subject=${encodeURIComponent(appState.asuntoCEPAB)}&body=${encodeURIComponent(appState.cuerpoCEPAB)}`;
            if (cc) url += `&cc=${encodeURIComponent(cc)}`;
            if (url.length > 1900) { copiarTexto(appState.cuerpoCEPAB, "Cuerpo del Correo"); }
            window.location.href = url;
            mostrarToast("Iniciando Correo...", "Abriendo aplicación de correo predeterminada.");
        }

        function enviarPorGmail() {
            if (!generarSolicitudCEPAB({ silencioso: true })) return;
            const cc = document.getElementById("ccEmail").value.trim();
            let url = `https://mail.google.com/mail/?view=cm&fs=1&tf=1&to=${encodeURIComponent(appState.correoDestino)}&su=${encodeURIComponent(appState.asuntoCEPAB)}&body=${encodeURIComponent(appState.cuerpoCEPAB)}`;
            if (cc) url += `&cc=${encodeURIComponent(cc)}`;
            window.open(url, '_blank');
            mostrarToast("Gmail Web", "Abriendo ventana de redacción.");
        }

        function enviarPorOutlookWeb() {
            if (!generarSolicitudCEPAB({ silencioso: true })) return;
            const cc = document.getElementById("ccEmail").value.trim();
            let url = `https://outlook.office.com/mail/deeplink/compose?to=${encodeURIComponent(appState.correoDestino)}&subject=${encodeURIComponent(appState.asuntoCEPAB)}&body=${encodeURIComponent(appState.cuerpoCEPAB)}`;
            if (cc) url += `&cc=${encodeURIComponent(cc)}`;
            window.open(url, '_blank');
            mostrarToast("Outlook Web", "Abriendo ventana de M365.");
        }

        async function copiarTexto(texto, etiqueta) {
            if (!texto) return;
            try {
                if (navigator.clipboard && navigator.clipboard.writeText) {
                    await navigator.clipboard.writeText(texto);
                } else {
                    throw new Error("API Clipboard no disponible, ejecutando fallback.");
                }
                mostrarToast(`¡${etiqueta} copiado!`, "Guardado en portapapeles.");
            } catch (err) {
                const area = document.createElement("textarea");
                area.value = texto;
                area.style.position = "fixed";
                area.style.opacity = "0";
                document.body.appendChild(area);
                area.select();
                document.execCommand("copy");
                document.body.removeChild(area);
                mostrarToast(`¡${etiqueta} copiado!`, "Guardado en portapapeles.");
            }
        }

        function copiarTodo() {
            const cc = document.getElementById("ccEmail").value.trim();
            const completo = `PARA: ${appState.correoDestino}\n${cc ? 'CC: ' + cc + '\n' : ''}FOLIO: ${appState.folioCEPAB}\nASUNTO: ${appState.asuntoCEPAB}\n\n========================================\nCUERPO DEL MENSAJE:\n========================================\n${appState.cuerpoCEPAB}`;
            copiarTexto(completo, "Expediente Completo");
        }

        function limpiarFormulario() {
            document.getElementById("moduloOperativo").value = "";
            ["embarcacion", "contrato", "empresa", "supervisorNombre", "supervisorFicha", "ccEmail", "observaciones", "sustNombre", "sustIMO", "sustMMSI",
             "numContratosSpot", "numFijas", "remolcador", "tipoContratoAtlas", "gerenciaSolicitante", "gerenciaOtra"].forEach(id => { document.getElementById(id).value = ""; });
            document.getElementById("dependenciaSpot").value = "PMX";
            document.getElementById("filasFijas").innerHTML = "";
            document.getElementById("filasContratosSpot").innerHTML = "";
            appState.gerenciaManual = false;
            actualizarSubtramites();
            document.getElementById("badgeDatosTecnicos").classList.add("hidden");
            document.getElementById("hintEmb").classList.add("hidden");
            document.getElementById("resultadoCEPAB").classList.add("hidden");
            Object.assign(appState, { asuntoCEPAB: "", cuerpoCEPAB: "", folioCEPAB: "" });
            document.querySelectorAll(".campo-error").forEach(el => el.classList.remove("campo-error"));
            ocultarInstrucciones();

            mostrarToast("Formulario Reiniciado", "Todos los campos fueron restablecidos.");
        }


        /* ===== Correo de "vuelos": solicitud de siglas de heliplataforma a la SSCTAPC (con copia a CEPAB) ===== */
        const SSCTAPC_DIR = [["Carlos Torres López", "carlos.torres@pemex.com"], ["Juana Ortega Bonola", "juana.ortega@pemex.com"], ["Raúl Rodríguez Estrada", "raul.rodrigueze@pemex.com"]];
        const correosDir = {};
        function urlCorreoDir(via, m) {
            const e = encodeURIComponent, to = m.to.join(","), cc = m.cc.join(",");
            if (via === "gmail") return `https://mail.google.com/mail/?view=cm&fs=1&tf=1&to=${e(to)}&cc=${e(cc)}&su=${e(m.asunto)}&body=${e(m.cuerpo)}`;
            if (via === "o365") return `https://outlook.office.com/mail/deeplink/compose?to=${e(to)}&cc=${e(cc)}&subject=${e(m.asunto)}&body=${e(m.cuerpo)}`;
            return `mailto:${to}?cc=${e(cc)}&subject=${e(m.asunto)}&body=${e(m.cuerpo)}`;
        }
        function abrirCorreoDir(key, via) {
            const m = correosDir[key]; if (!m) return;
            let url = urlCorreoDir(via, m);
            if (via === "mailto" && url.length > 1900) { copiarTexto(m.cuerpo, "Cuerpo del correo"); url = urlCorreoDir(via, { ...m, cuerpo: "(El texto completo se copió al portapapeles: péguelo aquí con Ctrl+V.)" }); }
            if (via === "mailto") window.location.href = url; else window.open(url, "_blank");
        }
        function solicitarSiglasDir(idx) {
            const val = id => document.getElementById(id).value.trim();
            // Obligatorios (*): embarcación, contrato, compañía y supervisor; lo demás se incluye si ya se capturó
            const req = [["embarcacion", "Embarcación / Artefacto Naval"], ["contrato", "Número de Contrato"], ["empresa", "Compañía / Contratista"], ["supervisorNombre", "Supervisor de Contrato DEE / Solicitante"]];
            const falt = req.filter(([id]) => !val(id));
            if (falt.length) {
                falt.forEach(([id]) => document.getElementById(id).classList.add("campo-error"));
                document.getElementById(falt[0][0]).focus();
                mostrarToast("Faltan datos para el correo", falt.map(f => f[1]).join(", ") + ".");
                return;
            }
            const emb = val("embarcacion"), cat = buscarEmb(emb) || {};
            const L = [], add = (l, v) => { if (v && String(v).trim() && v !== "N/A") L.push(`• ${l}: ${v}`); };
            add("Embarcación / Artefacto Naval", emb); add("Servicio", cat.servicio); add("MMSI", cat.mmsi); add("IMO", cat.imo); add("Call Sign", cat.callsign); add("Bandera", cat.bandera);
            add("Número de Contrato DEE", val("contrato")); add("Compañía / Contratista", val("empresa"));
            add("Supervisor de Contrato DEE / Solicitante", val("supervisorNombre")); add("Ficha PEMEX / Cargo del Supervisor", val("supervisorFicha"));
            const m = {
                to: SSCTAPC_DIR.map(x => x[1]), cc: [appState.correoDestino],
                asunto: `SOLICITUD DE IDENTIFICADOR AÉREO (SIGLAS) DE HELIPLATAFORMA — ${emb}`,
                cuerpo: `Buen día.\n\nPor instrucciones del Líder de Control Marino y Sistemas de Radar, solicito la asignación del identificador aéreo (siglas) de la heliplataforma de la siguiente unidad, necesario para su alta en el Atlas GL y en el Módulo CEPAB:\n\n${L.join("\n")}\n\nQuedo atento a su respuesta para registrar las siglas en la cédula del Atlas GL.\n\nAtentamente,\n${val("supervisorNombre")}${val("supervisorFicha") ? "\n" + val("supervisorFicha") : ""}`
            };
            const key = "siglas" + idx; correosDir[key] = m;
            const cont = document.getElementById(`correoSiglasDir_${idx}`);
            const fila = (l, v, c) => `<p class="text-[11px]"><span class="font-bold text-slate-500 inline-block w-14">${l}</span><span class="font-mono ${c}">${escapeHtml(v)}</span></p>`;
            cont.innerHTML = `<div class="mt-2 bg-slate-900 text-slate-200 rounded-xl p-3 space-y-2 border border-slate-700">
                <p class="text-emerald-400 text-xs font-bold uppercase tracking-wider">Correo a la SSCTAPC (identificador aéreo)</p>
                ${fila("Para:", m.to.join(", "), "text-slate-200")}${fila("CC:", m.cc.join(", "), "text-amber-300")}${fila("Asunto:", m.asunto, "text-white font-bold")}
                <pre class="whitespace-pre-wrap bg-slate-950 border border-slate-800 rounded-lg p-2.5 text-[11.5px] text-slate-300 max-h-64 overflow-y-auto">${escapeHtml(m.cuerpo)}</pre>
                <div class="flex flex-wrap gap-2">
                    <button type="button" onclick="abrirCorreoDir('${key}','mailto')" class="bg-emerald-600 hover:bg-emerald-500 text-white text-xs font-bold px-3 py-2 rounded-lg">Abrir Outlook / App</button>
                    <button type="button" onclick="abrirCorreoDir('${key}','o365')" class="bg-blue-600 hover:bg-blue-500 text-white text-xs font-bold px-3 py-2 rounded-lg">Outlook Web (M365)</button>
                    <button type="button" onclick="abrirCorreoDir('${key}','gmail')" class="bg-red-600 hover:bg-red-500 text-white text-xs font-bold px-3 py-2 rounded-lg">Gmail Web</button>
                    <button type="button" onclick="copiarTexto(correosDir['${key}'] && ('PARA: ' + correosDir['${key}'].to.join(', ') + '\\nCC: ' + correosDir['${key}'].cc.join(', ') + '\\nASUNTO: ' + correosDir['${key}'].asunto + '\\n\\n' + correosDir['${key}'].cuerpo), 'Correo completo')" class="bg-slate-700 hover:bg-slate-600 text-white text-xs font-bold px-3 py-2 rounded-lg">Copiar todo</button>
                </div></div>`;
            cont.classList.remove("hidden");
        }

        function mostrarToast(titulo, mensaje) {
            const toast = document.getElementById("toast");
            document.getElementById("toastTitle").innerText = titulo;
            document.getElementById("toastMsg").innerText = mensaje;

            toast.classList.remove("translate-y-24", "opacity-0");
            toast.classList.add("translate-y-0", "opacity-100");

            setTimeout(() => {
                toast.classList.remove("translate-y-0", "opacity-100");
                toast.classList.add("translate-y-24", "opacity-0");
            }, 3500);
        }
    </script>
<script id="verCEPAB">
/* ===== Control de versión CEPAB =====
   Cada herramienta lleva su versión (VER_CEPAB.version, AAAA.MM.DD). Al abrir, cada hora y al volver a la pestaña
   (tras 30 min) se lee la pestaña Ver_CEPAB del archivo de catálogos:
     herramienta · version_vigente · version_minima · caduca_el · mensaje · enlace   (una fila por herramienta)
   - versión < version_minima, sin caduca_el o con la fecha ya cumplida → pantalla «Esta versión caducó» (bloquea).
   - versión < version_minima con caduca_el futura → franja con la fecha y los días que faltan (no bloquea).
   - versión < version_vigente → aviso de versión más reciente (no bloquea).
   Sin internet se usa el último resultado guardado en este navegador (si ya había caducado, sigue bloqueada) y,
   tras 15 días sin poder verificar, se muestra un aviso. Si la pestaña no existe, le faltan los encabezados o no
   tiene la fila de esta herramienta, no se bloquea. El contenido de la hoja se muestra como texto (nunca se ejecuta). */
(function(){'use strict';
 const V=window.VER_CEPAB||{};if(!V.version||!V.herramienta)return;
 const CORREO='controldeembarcacionesypersonalabordo@pemex.com',EXT='2-82-31',HOJA='Ver_CEPAB';
 const DIAS_AVISO=15,CADA=36e5,VOLVER=18e5,ESPERA=12e3,K='cepab_ver_'+V.herramienta,KP=K+'_primera_'+V.version;
 const $=id=>document.getElementById(id);
 const esc=s=>String(s==null?'':s).replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
 const pad=n=>String(n).padStart(2,'0');
 const norm=s=>String(s==null?'':s).normalize('NFD').replace(/[\u0300-\u036f]/g,'').trim();
 const clave=s=>norm(s).toLowerCase().replace(/[^a-z0-9]+/g,'_').replace(/^_+|_+$/g,'');
 const fechaTxt=d=>`${pad(d.getDate())}/${pad(d.getMonth()+1)}/${d.getFullYear()}`;
 const fechaHora=ms=>{const d=new Date(ms);return `${fechaTxt(d)}, ${pad(d.getHours())}:${pad(d.getMinutes())} h`};
 const SVG=p=>`<svg class="ver-ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">${p}</svg>`;
 const I={alerta:SVG('<path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3"/><path d="M12 9v4"/><path d="M12 17h.01"/>'),
  info:SVG('<circle cx="12" cy="12" r="10"/><path d="M12 16v-4"/><path d="M12 8h.01"/>'),
  correo:SVG('<rect width="20" height="16" x="2" y="4" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/>'),
  tel:SVG('<path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>'),
  bajar:SVG('<path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" x2="12" y1="15" y2="3"/>'),
  guardar:SVG('<path d="M15.2 3a2 2 0 0 1 1.4.6l3.8 3.8a2 2 0 0 1 .6 1.4V19a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2z"/><path d="M17 21v-7a1 1 0 0 0-1-1H8a1 1 0 0 0-1 1v7"/><path d="M7 3v4a1 1 0 0 0 1 1h7"/>'),
  copiar:SVG('<rect width="14" height="14" x="8" y="8" rx="2" ry="2"/><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"/>'),
  x:SVG('<path d="M18 6 6 18"/><path d="m6 6 12 12"/>')};

 /* Versión AAAA.MM.DD con sufijo opcional (a, b…). Acepta la celda que Google convierte en fecha, AAAA-MM-DD, DD/MM/AAAA o AAAAMMDD. */
 function ver(x){if(x==null||x==='')return null;const s=String(x).trim();let m,y,mo,d,suf='';
  if((m=s.match(/^Date\((\d+),(\d+),(\d+)/)))[y,mo,d]=[+m[1],+m[2]+1,+m[3]];
  else if((m=s.match(/^(\d{4})[.\-\/](\d{1,2})[.\-\/](\d{1,2})\s*([a-z]?)$/i)))[y,mo,d,suf]=[+m[1],+m[2],+m[3],m[4]||''];
  else if((m=s.match(/^(\d{1,2})[.\-\/](\d{1,2})[.\-\/](\d{4})$/)))[y,mo,d]=[+m[3],+m[2],+m[1]];
  else if((m=s.match(/^(\d{4})(\d{2})(\d{2})$/)))[y,mo,d]=[+m[1],+m[2],+m[3]];
  else return null;
  if(y<2000||mo<1||mo>12||d<1||d>31)return null;
  suf=suf.toLowerCase();return{n:y*1e4+mo*100+d,suf,txt:`${y}.${pad(mo)}.${pad(d)}${suf}`}}
 const cmp=(a,b)=>a.n-b.n||(a.suf<b.suf?-1:a.suf>b.suf?1:0);
 /* Fecha de caducidad: celda fecha de Google, AAAA-MM-DD o DD/MM/AAAA (inicia a las 00:00 de ese día) */
 function fecha(x){if(x==null||x==='')return null;const s=String(x).trim();let m;
  if((m=s.match(/^Date\((\d+),(\d+),(\d+)/)))return new Date(+m[1],+m[2],+m[3]);
  if((m=s.match(/^(\d{4})[.\-\/](\d{1,2})[.\-\/](\d{1,2})/)))return new Date(+m[1],+m[2]-1,+m[3]);
  if((m=s.match(/^(\d{1,2})[.\-\/](\d{1,2})[.\-\/](\d{4})$/)))return new Date(+m[3],+m[2]-1,+m[1]);
  return null}
 const MIA=ver(V.version);

 /* Respuesta de Google: se exigen los encabezados «herramienta» y «version_minima» y la fila de esta herramienta
    (si la pestaña no existe, Google puede devolver otra pestaña: se descarta). */
 function leer(json){
  if(!json||json.status==='error'||!json.table||!Array.isArray(json.table.cols))return null;
  const val=(r,j)=>{if(j<0||!r||!r.c||!r.c[j])return'';const c=r.c[j];return c.v!=null&&c.v!==''?c.v:(c.f||'')};
  let cols=json.table.cols.map(c=>clave(c.label||'')),filas=json.table.rows||[];
  if(cols.indexOf('herramienta')<0&&filas.length){const alt=(filas[0].c||[]).map((c,j)=>clave(val(filas[0],j)));if(alt.indexOf('herramienta')>=0){cols=alt;filas=filas.slice(1)}}
  const ix=n=>cols.indexOf(n),iH=ix('herramienta'),iMin=ix('version_minima');if(iH<0||iMin<0)return null;
  const f=filas.find(r=>norm(val(r,iH)).toUpperCase()===V.herramienta);if(!f)return null;
  const enl=String(val(f,ix('enlace'))||'').trim();
  return{vig:ver(val(f,ix('version_vigente'))),min:ver(val(f,iMin)),cad:fecha(val(f,ix('caduca_el'))),
   msg:String(val(f,ix('mensaje'))||'').replace(/\s+/g,' ').trim().slice(0,600),enl:/^https?:\/\/\S+$/i.test(enl)?enl:''}}
 function decidir(d){if(!d||!MIA)return'sin_control';
  if(d.min&&cmp(MIA,d.min)<0)return d.cad&&Date.now()<d.cad.getTime()?'por_caducar':'caducada';
  if(d.vig&&cmp(MIA,d.vig)<0)return'nueva';
  return'vigente'}

 /* Último resultado en este navegador (por herramienta y versión) */
 function guardar(d){try{localStorage.setItem(K,JSON.stringify({version:V.version,ts:Date.now(),d:d?{vig:d.vig&&d.vig.txt,min:d.min&&d.min.txt,cad:d.cad?d.cad.getTime():null,msg:d.msg,enl:d.enl}:null}))}catch(e){}}
 function guardado(){try{const g=JSON.parse(localStorage.getItem(K)||'null');if(!g||g.version!==V.version)return null;
  return{ts:+g.ts||0,d:g.d?{vig:ver(g.d.vig),min:ver(g.d.min),cad:g.d.cad?new Date(g.d.cad):null,msg:String(g.d.msg||''),enl:/^https?:\/\//i.test(g.d.enl||'')?g.d.enl:''}:null}}catch(e){return null}}
 function primera(){try{let t=+localStorage.getItem(KP);if(!t){t=Date.now();localStorage.setItem(KP,String(t))}return t}catch(e){return Date.now()}}

 const mailto=(asunto,cuerpo)=>`mailto:${CORREO}?subject=${encodeURIComponent(asunto)}&body=${encodeURIComponent(cuerpo)}`;
 const mailVigente=d=>{const v=d&&(d.min||d.vig);return mailto(`Solicitud de la versión vigente — ${V.nombre}`,
  `Buen día.\n\nSolicito la versión vigente de la ${V.nombre}. La versión que tengo es la ${V.version}${v?` y la vigente es la ${v.txt}`:''}.\n\nNombre:\nÁrea / Gerencia:\nExtensión:\n\nGracias.`)};
 function hayCaptura(){try{return[...document.querySelectorAll('#fases [data-k]')].some(el=>!['checkbox','radio','file','hidden'].includes(el.type)&&el.tagName!=='SELECT'&&!el.readOnly&&String(el.value||'').trim())}catch(e){return false}}

 /* ---------- Pantalla de caducidad (bloquea toda la herramienta) ---------- */
 function tarjeta(d,ts,sinRed){
  const v=d&&(d.min||d.vig),csv=V.herramienta==='CEDULAS'&&typeof exportar==='function'&&hayCaptura();
  return `<div class="ver-card">
  <div class="ver-cab"><span class="inst-plate"><span class="logo-pemex" role="img" aria-label="PEMEX" style="height:30px"></span></span><span class="logo-cepab" role="img" aria-label="CEPAB" style="height:42px"></span><p>Petróleos Mexicanos · Dirección de Exploración y Extracción</p></div>
  <div class="ver-regla"></div>
  <div class="ver-cuerpo">
   <span class="ver-alerta">${I.alerta} Actualización obligatoria</span>
   <h2 id="verTit">Esta versión caducó</h2>
   <p id="verDesc">La ${esc(V.nombre)} que está usando (versión <b>${esc(V.version)}</b>) ya no puede utilizarse${v?`; la versión vigente es la <b>${esc(v.txt)}</b>`:''}.</p>
   ${d&&d.msg?`<p class="ver-motivo"><b>Motivo:</b> ${esc(d.msg)}</p>`:''}
   <p>Póngase en comunicación con el <b>Personal de Control de Embarcaciones y Personal a Bordo (CEPAB)</b> para recibir la versión vigente.</p>
   <div class="ver-contacto">
    <div>${I.correo}<b>Correo</b><span class="ver-correo">${CORREO}</span></div>
    <div>${I.tel}<b>Extensión</b><span>${EXT}</span></div>
   </div>
   <div class="ver-acc">
    <a class="ver-btn ver-btn-p" href="${esc(mailVigente(d))}">${I.correo} Escribir a CEPAB</a>
    ${d&&d.enl?`<a class="ver-btn ver-btn-s" href="${esc(d.enl)}" target="_blank" rel="noopener noreferrer">${I.bajar} Descargar la versión vigente</a>`:''}
    ${csv?`<button type="button" class="ver-btn ver-btn-s" data-ver="csv">${I.guardar} Guardar lo capturado (CSV)</button>`:''}
    <button type="button" class="ver-btn ver-btn-s" data-ver="copiar">${I.copiar} Copiar correo</button>
   </div>
   ${csv?'<p class="ver-nota">Guarde lo capturado antes de cerrar: el CSV se importa en la versión vigente y no tendrá que volver a capturar.</p>':''}
   <p class="ver-pie">${sinRed?'Sin conexión: se usa la última verificación':'Verificado'} el ${esc(fechaHora(ts||Date.now()))}. Cuando tenga la versión vigente, cierre esta ventana y abra el archivo nuevo.</p>
  </div></div>`}
 function copiar(txt,b){const ok=()=>{const t=b.innerHTML;b.innerHTML=`${I.copiar} Correo copiado`;setTimeout(()=>{b.innerHTML=t},1800)};
  const viejo=()=>{const a=document.createElement('textarea');a.value=txt;a.setAttribute('readonly','');a.style.position='fixed';a.style.opacity='0';b.parentNode.appendChild(a);a.select();try{document.execCommand('copy');ok()}catch(e){}a.remove()};
  try{navigator.clipboard.writeText(txt).then(ok,viejo)}catch(e){viejo()}}
 function bloquear(d,ts,sinRed){
  let o=$('verBloqueo');
  if(!o){o=document.createElement('div');o.id='verBloqueo';o.setAttribute('role','alertdialog');o.setAttribute('aria-modal','true');o.setAttribute('aria-labelledby','verTit');o.setAttribute('aria-describedby','verDesc');document.body.appendChild(o)}
  o.innerHTML=tarjeta(d,ts,sinRed);
  document.body.classList.add('ver-caducada');
  [...document.body.children].forEach(el=>{if(el!==o&&!el.hasAttribute('inert')){el.setAttribute('inert','');el.setAttribute('data-ver-inert','')}});
  o.querySelectorAll('[data-ver]').forEach(b=>b.addEventListener('click',()=>{
   if(b.dataset.ver==='copiar')copiar(CORREO,b);
   if(b.dataset.ver==='csv'){try{exportar(false)}catch(e){b.textContent='No se pudo generar el CSV';console.warn('Ver_CEPAB:',e)}}}));
  if(!o.contains(document.activeElement)){const p=o.querySelector('.ver-btn-p');if(p)try{p.focus({preventScroll:true})}catch(e){}}}
 function desbloquear(){const o=$('verBloqueo');if(!o)return;o.remove();document.body.classList.remove('ver-caducada');
  document.querySelectorAll('[data-ver-inert]').forEach(el=>{el.removeAttribute('inert');el.removeAttribute('data-ver-inert')})}

 /* ---------- Franja de aviso (no bloquea). Prioridad: por caducar > sin verificar > versión nueva ---------- */
 const PRIO={nueva:1,sin:2,por:3},cerrados=new Set();let avisoTipo='';
 function aviso(tipo,d,desde){
  if(cerrados.has(tipo)||(avisoTipo&&PRIO[avisoTipo]>PRIO[tipo]))return;
  let el=$('verAviso');
  if(!el){el=document.createElement('div');el.id='verAviso';el.setAttribute('role','status');const hd=document.querySelector('header.inst-header');if(hd)hd.insertAdjacentElement('afterend',el);else document.body.insertAdjacentElement('afterbegin',el)}
  avisoTipo=tipo;el.className='ver-'+tipo;
  const contacto=`<a href="${esc(mailVigente(d))}">${CORREO}</a> · Ext. ${EXT}`;let txt='';
  if(tipo==='nueva')txt=`Hay una versión más reciente de la ${esc(V.nombre)} (<b>${esc(d.vig.txt)}</b>); usted tiene la ${esc(V.version)}. Solicítela al Personal de CEPAB: ${contacto}.`;
  if(tipo==='por'){const n=Math.max(1,Math.ceil((d.cad.getTime()-Date.now())/864e5));
   txt=`<b>Esta versión (${esc(V.version)}) caduca el ${fechaTxt(d.cad)}</b> — falta${n===1?'':'n'} ${n} día${n===1?'':'s'}. Solicite la versión vigente${d.min?` (${esc(d.min.txt)})`:''} al Personal de CEPAB: ${contacto}.`}
  if(tipo==='sin'){const n=Math.floor((Date.now()-desde)/864e5);txt=`No se ha podido verificar la vigencia de esta versión (${esc(V.version)}) desde hace ${n} días. Conéctese a internet y vuelva a abrir la herramienta.`}
  if(d&&d.msg&&tipo!=='sin')txt+=` <span>${esc(d.msg)}</span>`;
  el.innerHTML=`<div class="ver-in">${tipo==='nueva'?I.info:I.alerta}<p>${txt}</p><button type="button" class="ver-x" aria-label="Cerrar aviso">${I.x}</button></div>`;
  el.querySelector('.ver-x').addEventListener('click',()=>{cerrados.add(tipo);quitarAviso()})}
 function quitarAviso(){const el=$('verAviso');if(el)el.remove();avisoTipo=''}

 /* Pie de página: versión y estado */
 function pie(est,d,sinRed){const el=$('verPie');if(!el)return;
  el.textContent={vigente:' · vigente',nueva:' · hay una versión más reciente',por_caducar:d&&d.cad?` · caduca el ${fechaTxt(d.cad)}`:'',caducada:' · caducada',sin_control:''}[est]||'';
  if(sinRed&&est!=='caducada')el.textContent+=' (sin verificar)'}

 let estado='',intento=0,seq=0;
 function aplicar(est,d,ts,sinRed){
  estado=est;window.VER_ESTADO={estado:est,version:V.version,vigente:d&&d.vig?d.vig.txt:'',minima:d&&d.min?d.min.txt:'',caduca:d&&d.cad?fechaTxt(d.cad):'',sinRed:!!sinRed,ts};
  pie(est,d,sinRed);
  if(est==='caducada'){quitarAviso();bloquear(d,ts,sinRed);return}
  desbloquear();
  if(est==='por_caducar')aviso('por',d);else if(est==='nueva')aviso('nueva',d);else if(avisoTipo!=='sin')quitarAviso()}
 function procesar(d){guardar(d);aplicar(decidir(d),d,Date.now(),false)}
 function sinConexion(){
  const g=guardado();
  if(g&&g.d){const est=decidir(g.d);aplicar(est,g.d,g.ts,true);if(est==='caducada')return}
  else pie('sin_control',null,true);
  const base=(g&&g.ts)||primera();
  if(Date.now()-base>DIAS_AVISO*864e5)aviso('sin',null,base)}
 function verificar(){
  if(typeof CAT_SRC!=='function')return sinConexion();
  intento=Date.now();const cb='recibirVersionCEPAB'+(++seq);let fin=false,t=0;
  const s=document.createElement('script');
  const cerrar=()=>{if(fin)return false;fin=true;clearTimeout(t);window[cb]=function(){};s.remove();return true};
  window[cb]=json=>{if(cerrar())procesar(leer(json))};
  s.onerror=()=>{if(cerrar())sinConexion()};
  t=setTimeout(()=>{if(cerrar())sinConexion()},ESPERA);
  s.src=CAT_SRC(HOJA,cb,1)+'&_='+Date.now();
  document.head.appendChild(s)}

 /* Arranque: si en este navegador ya se supo que caducó, se bloquea de inmediato (aun sin internet) */
 const g=guardado();if(g&&g.d&&decidir(g.d)==='caducada')aplicar('caducada',g.d,g.ts,true);
 primera();verificar();
 setInterval(verificar,CADA);
 document.addEventListener('visibilitychange',()=>{if(document.visibilityState==='visible'&&Date.now()-intento>VOLVER)verificar()});
 window.verCEPAB={verificar,estado:()=>estado};
})();
</script>
</body>
</html>
