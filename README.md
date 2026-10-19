<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>VERDEVA · Pitch</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;0,700;1,500&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#f6f2e8;--bg2:#ece6d6;--ink:#17261e;--mut:#556459;--g:#2f6b4c;--g2:#7fa88a;--gold:#a97a2c;--line:rgba(23,38,30,.14);--card:rgba(255,255,255,.65);
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0a1510;--bg2:#101e17;--ink:#f3efe3;--mut:#a9b9ae;--g:#7fc79a;--g2:#2f6b4c;--gold:#d9ad62;--line:rgba(255,255,255,.12);--card:rgba(255,255,255,.05)}}
:root[data-theme="dark"]{--bg:#0a1510;--bg2:#101e17;--ink:#f3efe3;--mut:#a9b9ae;--g:#7fc79a;--g2:#2f6b4c;--gold:#d9ad62;--line:rgba(255,255,255,.12);--card:rgba(255,255,255,.05)}
*{box-sizing:border-box}html{height:100%;scroll-snap-type:y proximity;scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--ink);font:17px/1.6 Inter,system-ui,sans-serif;overflow-x:hidden}
h1,h2,h3{font-family:'Cormorant Garamond',Georgia,serif;font-weight:600;margin:0;line-height:1.02}
h2{font-size:clamp(2.4rem,6.4vw,4.6rem);letter-spacing:-.01em}h3{font-size:1.7rem}
p{margin:0 0 12px;color:var(--mut)}em{color:var(--gold);font-style:italic}
.s{min-height:100svh;scroll-snap-align:start;display:flex;flex-direction:column;justify-content:center;padding:96px 7vw 80px;position:relative;background:radial-gradient(900px 500px at 85% 0%,color-mix(in srgb,var(--g) 14%,transparent),transparent),var(--bg)}
.s:nth-child(even){background:radial-gradient(800px 500px at 0% 100%,color-mix(in srgb,var(--gold) 12%,transparent),transparent),var(--bg2)}
.w{max-width:1120px;width:100%;margin:auto}
.dk{--ink:#f3efe3;--mut:#b6c4ba;--g:#7fc79a;--gold:#d9ad62;--line:rgba(255,255,255,.16);--card:rgba(255,255,255,.07);color:var(--ink);background:radial-gradient(900px 600px at 80% 10%,rgba(127,199,154,.22),transparent),radial-gradient(700px 500px at 0% 100%,rgba(217,173,98,.16),transparent),linear-gradient(160deg,#08130f,#123325 70%,#1b4a35)!important}
.k{font-size:.74rem;letter-spacing:.28em;text-transform:uppercase;color:var(--gold);font-weight:600;display:block;margin-bottom:18px}
.k:before{content:"";display:inline-block;width:34px;height:1px;background:var(--gold);vertical-align:middle;margin-right:12px}
.big{font:600 clamp(3.4rem,10vw,7.4rem)/.95 'Cormorant Garamond',serif;color:var(--g)}
.lead{font-size:1.2rem;max-width:620px}
.grid{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));margin-top:38px}
.c{background:var(--card);border:1px solid var(--line);border-radius:22px;padding:26px;backdrop-filter:blur(6px)}
.c h3{margin-bottom:8px}.c p{margin:0}
.n{font:600 2.6rem 'Cormorant Garamond',serif;color:var(--gold);line-height:1;margin-bottom:10px;display:block}
nav{position:fixed;top:0;left:0;right:0;z-index:20;display:flex;justify-content:space-between;align-items:center;padding:calc(14px + env(safe-area-inset-top,0px)) 5vw 14px;pointer-events:none}
nav b{font:700 1.35rem 'Cormorant Garamond',serif;letter-spacing:.3em;color:var(--gold)}nav span{font-size:.78rem;color:var(--mut);letter-spacing:.14em}
.bar{position:fixed;top:0;left:0;height:3px;width:0;background:linear-gradient(90deg,var(--g),var(--gold));z-index:30}
.dots{position:fixed;right:18px;top:50%;transform:translateY(-50%);z-index:20;display:flex;flex-direction:column;gap:11px}
.dots a{width:8px;height:8px;border-radius:50%;background:var(--line);border:1px solid var(--mut);transition:.3s}.dots a.on{background:var(--gold);border-color:var(--gold);transform:scale(1.5)}
.arr{position:fixed;right:5vw;bottom:calc(22px + env(safe-area-inset-bottom,0px));z-index:20;display:flex;gap:10px}
.arr button{width:46px;height:46px;border-radius:50%;border:1px solid var(--line);background:var(--card);color:var(--ink);font-size:1.1rem;cursor:pointer;backdrop-filter:blur(8px)}.arr button:hover{background:var(--gold);color:#111}
.rv{opacity:0;transform:translateY(26px);transition:opacity .9s ease,transform .9s ease}.v .rv{opacity:1;transform:none}.v .rv:nth-child(2){transition-delay:.12s}.v .rv:nth-child(3){transition-delay:.24s}.v .rv:nth-child(4){transition-delay:.36s}
.cover h1{font-size:clamp(4.4rem,17vw,12rem);letter-spacing:.12em;margin:14px 0 10px;background:linear-gradient(180deg,#fff,#cfe6d6 60%,#d9ad62);-webkit-background-clip:text;background-clip:text;color:transparent}
.tag{font:italic 500 clamp(1.4rem,3.4vw,2.2rem) 'Cormorant Garamond',serif;color:#dfe9e0}
.names{display:flex;flex-wrap:wrap;gap:10px 28px;margin-top:40px;font-size:.92rem;color:#c9d6cd}.names b{color:#fff;font-weight:500}
.btn{display:inline-block;padding:15px 34px;border-radius:99px;background:linear-gradient(135deg,#e8c27a,#b88a3e);color:#1a1409;font-weight:600;text-decoration:none;margin:10px 10px 0 0;transition:.3s}.btn:hover{transform:translateY(-2px);box-shadow:0 14px 30px -12px #d9ad62}
.btn.o{background:transparent;color:var(--ink);border:1px solid var(--mut)}
.steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:14px;margin-top:40px;counter-reset:s}
.steps div{counter-increment:s;background:var(--card);border:1px solid var(--line);border-radius:20px;padding:22px 16px;text-align:center;font-weight:500}
.steps div:before{content:"0" counter(s);display:block;font:600 2.4rem 'Cormorant Garamond',serif;color:var(--gold)}
.row{margin:13px 0}.row span{display:flex;justify-content:space-between;font-size:.92rem;margin-bottom:6px}.row div{height:10px;background:var(--line);border-radius:10px;overflow:hidden}
.row i{display:block;height:100%;width:0;border-radius:10px;background:linear-gradient(90deg,var(--g2),var(--g));transition:width 1.4s cubic-bezier(.2,.8,.2,1)}
.two{display:grid;gap:44px;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));align-items:center}
.split{display:flex;height:74px;border-radius:18px;overflow:hidden;font:600 1.15rem Inter;color:#fff;margin-top:26px}.split div{display:grid;place-items:center}
.donut{width:min(300px,70vw);aspect-ratio:1;border-radius:50%;margin:auto;display:grid;place-items:center;background:conic-gradient(#7fc79a 0 40%,#d9ad62 40% 64%,#2f6b4c 64% 84%,#e8d3a4 84% 94%,#9fb7a7 94% 100%)}
.donut div{width:64%;aspect-ratio:1;border-radius:50%;background:#0d1f18;display:grid;place-items:center;text-align:center;font:600 2.6rem/1 'Cormorant Garamond',serif;color:#d9ad62}.donut small{display:block;font:400 .72rem Inter;color:#b6c4ba;letter-spacing:.1em;margin-top:6px}
.leg{list-style:none;padding:0;margin:0}.leg li{display:flex;justify-content:space-between;gap:14px;padding:13px 0;border-bottom:1px solid var(--line);font-size:.98rem}.leg li:last-child{border:0}.leg b{color:var(--gold);white-space:nowrap}.leg em{font-style:normal;color:var(--mut);display:block;font-size:.82rem}
.sw{width:11px;height:11px;border-radius:3px;display:inline-block;margin-right:10px}
.team .c{text-align:center}.av{width:84px;height:84px;border-radius:50%;margin:0 auto 16px;display:grid;place-items:center;font:600 1.9rem 'Cormorant Garamond',serif;background:linear-gradient(135deg,#e8c27a,#b88a3e);color:#1a1409}
.role{color:var(--gold);font-size:.8rem;letter-spacing:.14em;text-transform:uppercase;font-weight:600}
@media(max-width:700px){.dots{display:none}.s{padding:90px 6vw 90px}}
</style>
</head>
<body>
<div class="bar" id="bar"></div>
<nav><b>VERDEVA</b><span id="ct">01 / 11</span></nav>
<div class="dots" id="dots"></div>
<div class="arr"><button id="pv" aria-label="Anterior">←</button><button id="nx" aria-label="Siguiente">→</button></div>

<section class="s dk cover" id="s1"><div class="w">
<span class="k rv">Frescura natural · Pitch · Octubre 2026</span>
<h1 class="rv">VERDEVA</h1>
<div class="tag rv">Crea tu desodorante natural, hecho a tu manera.</div>
<div class="rv"><a class="btn" href="#s9">Nuestra propuesta</a><a class="btn o" style="color:#f3efe3" href="https://neofiddev.github.io/verdeva/">Probar el personalizador</a></div>
<div class="names rv"><span><b>José Arturo Cervantes Andrade Castilla Villarreal</b></span><span><b>Fidel Nicolás Pablo León</b></span><span><b>Leonardo García Villalpando</b></span></div>
</div></section>

<section class="s" id="s2"><div class="w">
<span class="k rv">El problema</span>
<h2 class="rv">Todos usan desodorante.<br><em>Casi nadie lo elige.</em></h2>
<p class="lead rv" style="margin-top:22px">Productos iguales para todos, con ingredientes que no siempre entendemos y empaques de plástico. Le preguntamos a 40 personas qué quieren de verdad:</p>
<div class="grid">
<div class="c rv"><span class="n"><b class="cu" data-to="95" data-suf="%">0</b></span><p>quiere, o tal vez quiere, elegir la <b>forma</b> de su desodorante.</p></div>
<div class="c rv"><span class="n"><b class="cu" data-to="90" data-suf="%">0</b></span><p>está abierto a un desodorante <b>natural sin fragancia</b>.</p></div>
<div class="c rv"><span class="n"><b class="cu" data-to="20" data-suf="%">0</b></span><p>crearía su propio <b>aroma</b>: 1 de cada 5.</p></div>
</div></div></section>

<section class="s" id="s3"><div class="w">
<span class="k rv">La solución</span>
<h2 class="rv">Un desodorante <em>diseñado por ti</em></h2>
<p class="lead rv" style="margin-top:20px">Verdeva es cosmética natural donde cada persona crea el suyo. Tú eliges cómo se siente, cómo huele y cuánto necesitas.</p>
<div class="grid">
<div class="c rv"><span class="n">01</span><h3>Tú lo diseñas</h3><p>Personalizador paso a paso con vista previa y precio en vivo.</p></div>
<div class="c rv"><span class="n">02</span><h3>Natural de verdad</h3><p>Sin aluminio ni parabenos. Pocos ingredientes, cada uno con un trabajo claro.</p></div>
<div class="c rv"><span class="n">03</span><h3>A tu medida</h3><p>3 formas, 3 tamaños y más de 9 aromas, o tu propia mezcla.</p></div>
<div class="c rv"><span class="n">04</span><h3>Menos impacto</h3><p>Tubo de cartón reciclado o certificado y producción solo bajo pedido.</p></div>
</div></div></section>

<section class="s" id="s4"><div class="w">
<span class="k rv">Cómo funciona</span>
<h2 class="rv">Cinco pasos, <em>una sola página</em></h2>
<div class="steps rv"><div>Elige tu forma</div><div>Elige tu tamaño</div><div>Elige tu aroma</div><div>Personaliza tu diseño</div><div>Recibe tu Verdeva</div></div>
<p class="rv" style="margin-top:26px">Barra de progreso, carrito con total en vivo y un botón <b>Sorpréndeme</b> que arma una combinación por ti.</p>
<a class="btn rv" href="https://neofiddev.github.io/verdeva/">Abrir el personalizador en vivo →</a>
</div></section>

<section class="s" id="s5"><div class="w two">
<div><span class="k rv">El producto</span><h2 class="rv">Pocos ingredientes.<br><em>Cada uno con función.</em></h2>
<p class="rv" style="margin-top:20px">Ceras y aceites de origen vegetal y biodegradables, preparados por pedido para evitar excedentes y desperdicio.</p></div>
<div class="c rv"><ul class="leg">
<li><span>Aceite de coco</span><b>Suaviza</b></li><li><span>Karité</span><b>Nutre</b></li><li><span>Bicarbonato</span><b>Neutraliza olores</b></li><li><span>Almidón</span><b>Absorbe</b></li><li><span>Aceites esenciales</span><b>Aroma natural</b></li>
</ul><p style="margin-top:14px;font-size:.88rem">Sin aluminio · Sin parabenos · Sin plástico en el cuerpo del producto</p></div>
</div></section>

<section class="s" id="s6"><div class="w">
<span class="k rv">Nuestro mercado</span>
<h2 class="rv">Arrancamos en México, <em>en línea</em></h2>
<div class="grid">
<div class="c rv"><span class="n">18–35</span><h3>Jóvenes conscientes</h3><p>Leen etiquetas, prefieren lo natural y quieren marcas con identidad.</p></div>
<div class="c rv"><h3>Pieles sensibles</h3><p>Fórmulas simples, con o sin aroma, sin ingredientes agresivos.</p></div>
<div class="c rv"><h3>Regalos con nombre</h3><p>Producto con nombre y frase propios: original, útil y accesible.</p></div>
</div>
<p class="rv" style="margin-top:28px">Cómo llegamos: tienda en línea, redes sociales, recomendación entre amigos y ediciones para regalo.</p>
</div></section>

<section class="s" id="s7"><div class="w two">
<div><span class="k rv">Validación · encuesta a 40 personas</span><h2 class="rv">Lo que <em>dice</em> nuestro público</h2>
<p class="rv" style="margin-top:20px">La barra es el formato más usado (60%) y el 72.5% quiere personalizar la forma. En aromas gana la lavanda.</p>
<p style="font-size:.8rem">Menta, amaderado y sin aroma: valores estimados por diferencia sobre las 40 respuestas.</p></div>
<div class="c rv" id="bars">
<b style="font-family:Inter;font-size:.78rem;letter-spacing:.16em;text-transform:uppercase;color:var(--gold)">Aroma preferido</b>
</div></div></section>

<section class="s" id="s8"><div class="w">
<span class="k rv">Modelo de negocio</span>
<h2 class="rv">Casi la mitad de cada venta <em>es margen</em></h2>
<div class="split rv"><div style="flex:28;background:#2f6b4c">Costo $28</div><div style="flex:27;background:#b88a3e">Margen $27</div></div>
<p style="margin-top:12px">Por cada unidad vendida a $55 MXN. Precio de introducción: $55–60.</p>
<div class="grid">
<div class="c rv"><span class="n"><b class="cu" data-to="49" data-pre="≈" data-suf="%">0</b></span><p>de margen sobre el precio de $55.</p></div>
<div class="c rv"><span class="n">$2,700</span><p>de margen por cada 100 unidades vendidas.</p></div>
<div class="c rv"><span class="n">$22,000–27,500</span><p>de ingresos con las primeras 400 a 500 unidades.</p></div>
<div class="c rv"><span class="n">$10,800–13,500</span><p>de margen con ese primer lote.</p></div>
</div></div></section>

<section class="s dk" id="s9"><div class="w">
<span class="k rv">La propuesta</span>
<div class="big rv" style="color:#d9ad62">$30,000 MXN</div>
<h2 class="rv" style="margin-top:6px">por el <em>10%</em> de Verdeva</h2>
<p class="lead rv" style="margin-top:22px">De los $50,000 que necesita el arranque. Valoración implícita: <b style="color:#fff">$300,000 MXN</b>. Para producir las primeras 400 a 500 unidades y lanzar la marca.</p>
<div class="grid">
<div class="c rv"><span class="n">$50,000</span><p>Inversión inicial total</p></div>
<div class="c rv"><span class="n">$30,000</span><p>Lo que solicitamos hoy</p></div>
<div class="c rv"><span class="n">10%</span><p>Participación ofrecida</p></div>
</div></div></section>

<section class="s" id="s10"><div class="w two">
<div class="rv"><div class="donut"><div>$50k<small>USO DEL CAPITAL</small></div></div></div>
<div><span class="k rv">En qué lo usamos</span><ul class="leg rv">
<li><span><i class="sw" style="background:#7fc79a"></i>Insumos y materia prima<em>Coco, karité, aceites esenciales y envases de cartón</em></span><b>40% · $20,000</b></li>
<li><span><i class="sw" style="background:#d9ad62"></i>Marketing local<em>TikTok/Instagram Ads y empaques de envío</em></span><b>24% · $12,000</b></li>
<li><span><i class="sw" style="background:#2f6b4c"></i>Moldes y herramientas<em>Silicona ergonómica para las 3 formas</em></span><b>20% · $10,000</b></li>
<li><span><i class="sw" style="background:#e8d3a4"></i>Fondo de reserva<em>Imprevistos de producción</em></span><b>10% · $5,000</b></li>
<li><span><i class="sw" style="background:#9fb7a7"></i>Dominio y pagos<em>Dominio .mx, Stripe / Mercado Pago</em></span><b>6% · $3,000</b></li>
</ul></div></div></section>

<section class="s dk team" id="s11"><div class="w">
<span class="k rv">Equipo y cierre</span>
<h2 class="rv">Tres fundadores. <em>Una marca.</em></h2>
<div class="grid">
<div class="c rv"><div class="av">JA</div><h3>José Arturo Cervantes Andrade Castilla Villarreal</h3><p class="role">Finanzas</p></div>
<div class="c rv"><div class="av">FN</div><h3>Fidel Nicolás Pablo León</h3><p class="role">Producto e investigación</p></div>
<div class="c rv"><div class="av">LG</div><h3>Leonardo García Villalpando</h3><p class="role">Marca y presentación</p></div>
</div>
<div class="rv" style="text-align:center;margin-top:46px"><div class="tag">Diseña tu propio desodorante natural.</div>
<a class="btn" href="https://wa.me/525624477194">WhatsApp 56 2447 7194</a><a class="btn o" style="color:#f3efe3" href="mailto:contacto@verdeva.mx">contacto@verdeva.mx</a><a class="btn o" style="color:#f3efe3" href="https://neofiddev.github.io/verdeva/">Crea tu Verdeva</a></div>
</div></section>

<script>
var S=[].slice.call(document.querySelectorAll('.s')),i=0,D=document.getElementById('dots'),CT=document.getElementById('ct');
S.forEach(function(s,k){var a=document.createElement('a');a.href='#'+s.id;D.appendChild(a)});
var A=[["Lavanda",35],["Cítricos",20],["Personalizado",20],["Floral",15],["Menta",5],["Amaderado",2.5],["Sin aroma",2.5]];
document.getElementById('bars').insertAdjacentHTML('beforeend',A.map(function(r){return '<div class="row"><span>'+r[0]+'<b>'+r[1]+'%</b></span><div><i data-w="'+r[1]*2+'"></i></div></div>'}).join(''));
function cu(e){var t=+e.dataset.to,p=e.dataset.pre||'',f=e.dataset.suf||'',n=0,st=t/50;var h=setInterval(function(){n+=st;if(n>=t){n=t;clearInterval(h)}e.textContent=p+Math.round(n)+f},24)}
var io=new IntersectionObserver(function(es){es.forEach(function(e){if(e.isIntersecting){var s=e.target;if(!s.classList.contains('v')){s.classList.add('v');s.querySelectorAll('.cu').forEach(cu);s.querySelectorAll('.row i').forEach(function(b){setTimeout(function(){b.style.width=b.dataset.w+'%'},300)})}
i=S.indexOf(s);CT.textContent=('0'+(i+1)).slice(-2)+' / '+S.length;[].forEach.call(D.children,function(d,k){d.className=k==i?'on':''})}})},{threshold:.55});
S.forEach(function(s){io.observe(s)});
function go(k){k=Math.max(0,Math.min(S.length-1,k));S[k].scrollIntoView({behavior:'smooth'})}
document.getElementById('nx').onclick=function(){go(i+1)};document.getElementById('pv').onclick=function(){go(i-1)};
document.addEventListener('keydown',function(e){if(['ArrowRight','ArrowDown','PageDown',' '].indexOf(e.key)>-1){e.preventDefault();go(i+1)}if(['ArrowLeft','ArrowUp','PageUp'].indexOf(e.key)>-1){e.preventDefault();go(i-1)}});
addEventListener('scroll',function(){var h=document.documentElement;document.getElementById('bar').style.width=(h.scrollTop/(h.scrollHeight-h.clientHeight)*100)+'%'},{passive:true});
</script>
</body>
</html>
