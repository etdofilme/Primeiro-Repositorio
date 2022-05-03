# Primeiro-Repositorio
Meu primeiro repositório com arquivos HTML e CSS, tudo referente a criação de um site que fiz junto a plataformas de curso online conhecido como Alura.
#Código do site:
''
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Home - Barbearia Alura</title>
		<link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style-home.css">
    <link rel="stylesheet" href="produtos.css">
  </head>
  <body>
    <header>
      <div class="caixa">
        <h1><img src="logo.png"></h1>

        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="produtos.html">Produtos</a></li>
            <li><a href="contato.html">Contato</a></li>
          </ul>
        </nav>
      </div>
    </header>
			<img id="banner" src="banner.jpg">
			<div class="principal">
				<h2 class="titulo-centralizado">Sobre a Barbearia Alura</h2>

				<p>Localizada no coração da cidade a <strong>Barbearia Alura</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>

				<p id="missao"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

				<p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
			</div>

			<div class="beneficios">
				<h3 class="titulo-centralizado">Benefícios</h3>

				<ul>
					<li class="itens">Atendimento aos Clientes</li>
					<li class="itens">Espaço diferenciado</li>
					<li class="itens">Localização</li>
					<li class="itens">Profissionais Qualificados</li>
				</ul>

				<img src="beneficios.jpg" class="imagembeneficios">
			</div>

			<footer>
	      <img src="logo-branco.png">
	      <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
	    </footer>

		</body>
	</html>
''
