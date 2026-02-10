<!DOCTYPE html>
<style>
body { margin:0; font-family: Arial, Helvetica, sans-serif; background:#111; color:#fff; }
header { background:#000; padding:20px; text-align:center; }
header h1 { margin:0; color:#f5c542; letter-spacing:2px; }
header p { margin:5px 0 0; font-style:italic; }
nav { background:#1a1a1a; padding:10px; text-align:center; }
nav a { color:#fff; margin:0 15px; text-decoration:none; font-weight:bold; }
nav a:hover { color:#f5c542; }
.banner { padding:60px 20px; text-align:center; background:linear-gradient(135deg,#000,#222); }
.banner h2 { font-size:36px; margin-bottom:10px; }
.banner span { color:#f5c542; }
.produtos { padding:40px 20px; max-width:1100px; margin:auto; }
.produtos h2 { text-align:center; margin-bottom:30px; }
.grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px; }
.card { background:#1a1a1a; border-radius:10px; padding:20px; text-align:center; }
.card img { width:100%; border-radius:8px; }
.card h3 { margin:15px 0 5px; }
.card p { font-size:14px; color:#ccc; }
.card button { margin-top:10px; padding:10px 20px; border:none; background:#f5c542; color:#000; font-weight:bold; cursor:pointer; border-radius:5px; }
.card button:hover { background:#ffd966; }
.sobre { background:#000; padding:40px 20px; text-align:center; }
.sobre span { color:#f5c542; }
footer { background:#000; padding:20px; text-align:center; font-size:14px; color:#aaa; }
</style>
</head>
<body>


<header>
<h1>LEO ARTIGOS</h1>
<p>Estilo que fala por você</p>
</header>


<nav>
<a href="#">Início</a>
<a href="#produtos">Produtos</a>
<a href="#sobre">Sobre</a>
<a href="#contato">Contato</a>
</nav>


<section class="banner">
<h2>Moda Masculina com <span>Atitude</span></h2>
<p>Roupas de marca • Conforto • Estilo</p>
<h3><span>Novidades chegando!</span></h3>
</section>


<section class="produtos" id="produtos">
<h2>Destaques</h2>
<div class="grid">
<div class="card">
<img src="https://via.placeholder.com/300x300" alt="Camiseta Nike" />
<h3>Camiseta Nike</h3>
<p>Conforto e estilo para o dia a dia</p>
<button>Comprar</button>
</div>
<div class="card">
<img src="https://via.placeholder.com/300x300" alt="Camisa de Time" />
<h3>Camisa de Time</h3>
<p>Paixão pelo futebol com estilo</p>
<button>Comprar</button>
</div>
<div class="card">
<img src="https://via.placeholder.com/300x300" alt="Moletom Lacoste" />
<h3>Moletom Lacoste</h3>
<p>Elegância e conforto premium</p>
<button>Comprar</button>
</div>
</div>
</section>


<section class="sobre" id="sobre">
<h2>Sobre a <span>Leo Artigos</span></h2>
<p>Somos uma loja focada em moda masculina, trazendo roupas modernas, de qualidade e com identidade. Aqui você se veste para se destacar.</p>
</section>


<footer id="contato">
<p>Leo Artigos © 2026 - Moda Masculina</p>
<p>Vendas online • Atendimento via WhatsApp e Instagram</p>
</footer>


</body>
</html>
