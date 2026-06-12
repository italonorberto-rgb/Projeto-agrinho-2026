<header>
  <h1>Agrinho 2026</h1>
  <h2>Integração entre Campo e Cidade</h2>
</header>

<section class="banner">
  <img src="https://images.unsplash.com/photo-1500937386664-56d1dfef3854?w=1200" alt="Campo">
</section>

<section class="conteudo">
  <h2>Por que a integração é importante?</h2>
  <p>
    O campo produz alimentos, matérias-primas e recursos essenciais para a vida.
    A cidade oferece tecnologia, serviços e oportunidades. Juntos, campo e cidade
    formam uma parceria que fortalece a cidadania e o desenvolvimento sustentável.
  </p>

  <button onclick="mostrarMensagem()">Clique para saber mais</button>

  <p id="mensagem"></p>
</section>

<footer>
  <p>Projeto Agrinho 2026 - Integração, Campo e Cidade</p>
</footer>
<div class="quiz">
  <h2>Quiz: Campo e Cidade</h2>

  <p>1. Quem produz a maior parte dos alimentos consumidos nas cidades?</p>
  <button onclick="resposta('certa1')">O campo</button>
  <button onclick="resposta('errada')">A indústria</button>

  <p>2. O que a cidade oferece ao campo?</p>
  <button onclick="resposta('certa2')">Tecnologia e serviços</button>
  <button onclick="resposta('errada')">Somente transporte</button>

  <p>3. A integração entre campo e cidade ajuda a:</p>
  <button onclick="resposta('certa3')">Promover o desenvolvimento sustentável</button>
  <button onclick="resposta('errada')">Separar as comunidades</button>

  <h3 id="resultado"></h3>
</div>
<section class="mapa">
  <h2>Rebouças e suas Comunidades Rurais</h2>

  <iframe
    width="100%"
    height="450"
    frameborder="0"
    scrolling="no"
    src="https://drive.google.com/file/d/1FEDijBrhhXUx8b68zKn-wHHTusz8ilqn/view?usp=sharing"> 
  </iframe>

  <p>
    O município de Rebouças possui diversas comunidades rurais que contribuem
    para a produção agrícola, fortalecendo a integração entre campo e cidade.
  </p>
</section>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f4f4f4;
}

header {
  background: linear-gradient(90deg, #2e7d32, #81c784);
  color: white;
  text-align: center;
  padding: 20px;
}

.banner img {
  width: 100%;
  height: 350px;
  object-fit: cover;
}

.conteudo {
  max-width: 900px;
  margin: auto;
  padding: 20px;
  text-align: center;
}

.conteudo h2 {
  color: #2e7d32;
}

button {
  background: #2e7d32;
  color: white;
  border: none;
  padding: 12px 20px;
  border-radius: 8px;
  cursor: pointer;
  font-size: 16px;
}

button:hover {
  background: #1b5e20;
}

#mensagem {
  margin-top: 20px;
  font-weight: bold;
  color: #1b5e20;
}

footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
}
.quiz {
  background: white;
  padding: 20px;
  margin-top: 30px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.quiz button {
  margin: 5px;
}
.mapa {
  max-width: 1000px;
  margin: 30px auto;
  padding: 20px;
  text-align: center;
}

.mapa iframe {
  border-radius: 10px;
  border: 2px solid #2e7d32;
}function mostrarMensagem,(){
document.get
}
