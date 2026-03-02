<!DOCTYPE html><html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Voltix Eletrônicos</title><!-- Google Font --><link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet"><style>
:root{
  --azul:#0d6efd;
  --verde:#25d366;
  --escuro:#0f172a;
  --cinza:#f1f5f9;
}

*{box-sizing:border-box}

body{
  margin:0;
  font-family:'Poppins',sans-serif;
  background:var(--cinza);
  color:#111;
}

/* HEADER */
header{
  background:linear-gradient(135deg,var(--azul),#003c9e);
  color:white;
  padding:40px 20px;
  text-align:center;
}

header h1{
  margin:0;
  font-size:32px;
}

header p{
  margin-top:8px;
  opacity:.9;
}

/* CONTAINER */
.container{
  max-width:1200px;
  margin:auto;
  padding:30px 20px;
}

.section-title{
  font-size:24px;
  font-weight:700;
  margin-bottom:20px;
}

/* GRID */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
  gap:24px;
}

/* CARD */
.card{
  background:white;
  border-radius:18px;
  padding:18px;
  box-shadow:0 10px 25px rgba(0,0,0,.08);
  transition:.25s;
}

.card:hover{
  transform:translateY(-6px);
  box-shadow:0 18px 35px rgba(0,0,0,.12);
}

.card img{
  width:100%;
  height:170px;
  object-fit:contain;
}

.card h3{
  font-size:18px;
  margin:12px 0 6px;
}

.preco{
  color:var(--azul);
  font-size:22px;
  font-weight:700;
}

.botao{
  display:block;
  margin-top:12px;
  background:var(--verde);
  color:white;
  text-decoration:none;
  padding:12px;
  border-radius:10px;
  font-weight:600;
  transition:.2s;
}

.botao:hover{
  filter:brightness(.95);
}

/* WHATS FLOAT */
.whats-float{
  position:fixed;
  right:18px;
  bottom:18px;
  background:var(--verde);
  color:white;
  padding:14px 18px;
  border-radius:50px;
  text-decoration:none;
  font-weight:700;
  box-shadow:0 10px 25px rgba(0,0,0,.25);
  z-index:999;
}

/* FOOTER */
footer{
  background:var(--escuro);
  color:white;
  text-align:center;
  padding:28px 20px;
  margin-top:40px;
}

@media(max-width:480px){
  header h1{font-size:26px}
}
</style></head><body><header>
  <h1>⚡ Voltix Eletrônicos</h1>
  <p>Tecnologia com preço justo e entrega rápida</p>
</header><div class="container">
  <div class="section-title">🔥 Produtos em destaque</div>  <div class="grid"><div class="card">
  <img src="https://via.placeholder.com/400x300" alt="Smartphone" />
  <h3>Smartphone Premium</h3>
  <div class="preco">R$ 1.299,00</div>
  <a class="botao" href="https://wa.me/qr/NWDN7NW3DFXPK1" target="_blank">Comprar no WhatsApp</a>
</div>

<div class="card">
  <img src="https://via.placeholder.com/400x300" alt="Fone Bluetooth" />
  <h3>Fone Bluetooth</h3>
  <div class="preco">R$ 149,90</div>
  <a class="botao" href="https://wa.me/qr/NWDN7NW3DFXPK1" target="_blank">Comprar no WhatsApp</a>
</div>

<div class="card">
  <img src="https://via.placeholder.com/400x300" alt="Smartwatch" />
  <h3>Smartwatch Pro</h3>
  <div class="preco">R$ 299,90</div>
  <a class="botao" href="https://wa.me/qr/NWDN7NW3DFXPK1" target="_blank">Comprar no WhatsApp</a>
</div>

<div class="card">
  <img src="https://via.placeholder.com/400x300" alt="Caixa de Som" />
  <h3>Caixa de Som Bluetooth</h3>
  <div class="preco">R$ 219,90</div>
  <a class="botao" href="https://wa.me/qr/NWDN7NW3DFXPK1" target="_blank">Comprar no WhatsApp</a>
</div>

  </div>
</div><!-- BOTÃO FLUTUANTE --><a class="whats-float" href="https://wa.me/qr/NWDN7NW3DFXPK1" target="_blank">
  💬 Falar no WhatsApp
</a><footer>
  © 2026 Voltix Eletrônicos — Todos os direitos reservados
</footer></body>
</html>
