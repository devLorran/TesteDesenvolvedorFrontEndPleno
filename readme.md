<!doctype html>
<html lang="pt-br">
<head>
	<meta charset="utf-8">
	<title>NodeProp</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta name="description" content="Agência especialista em Marketing digital e, Criação de aplicativos Mobile.">
	<meta name="keywords" content="Agência digital, Marketing Sites">
	<meta name="robots" content="index follow">
	<meta name="author" content=" Lorran Rodrigues">
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.1.1/css/all.css" integrity="sha384-O8whS3fhG2OnA5Kas0Y9l3cfpmYjapjI0E4theH4iuMD+pLhbf6JI0jIMfYcK3yZ" crossorigin="anonymous">
	<link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet">
   <script src="http://code.jquery.com/jquery-1.12.0.min.js"></script>
</head>
<body class="fadeIn">
	<input class="checkbox" type="checkbox" name="" id="chec">
	<label id="lbl" for="chec">
		<img src="img/Hamburger_icon.svg.png" alt="" srcset="" id="hamburger">
	</label>
	<nav class="nav-hamburger">
		<ul>
			<li><a href="#">Home</a></li>
			<li><a href="#">Notícias</a></li>
			<li><a href="#">Entreterimento</a></li>
			<li><a href="#">Esportes</a></li>
			<li><a href="#">Copa do Mundo 2022</a></li>
			<li><a href="#">Carros</a></li>
			<li><a href="#">TV e Famosos</a></li>
			<li><a href="#">Planeta</a></li>
			<li><a href="#">Economia</a></li>
			<li><a href="#">Saúde</a></li>
		</ul>
	</nav>

	<div class="banner container">
			<!-- IMAGENS -->
			
		<main class="servicos container bg-white">
			<article class="servico">
				<a href="#"><img id="img" src="img/criacoes.jpg" alt="Campanhas publicitárias">
				<div class="inner">
					<a href="#"> Campanhas publicitárias </a>
					<h4> Impressos VTs e Jingles </h4>
					<p> Se você está precisando de criação de algum material em específico conte com a nossa equipe de profissionais. Eles farão toda companha publicitária.VT,outdor,folder,anúnucio e muito mais pela sua empresa no mais alto padrão de qualidade.
				</div>
			</article>
			<article class="servico container">
				<a href="#"><img id="img" src="img/md.jpg" alt="Marketing Digital">
				<div class="inner">
					<a href="#"> Marketing Digital </a>
					<h4> Administração de Redes sociais </h4>
					<p> Como agência de publicidade aplicamos estratégias nos meios digitais para que a seu negócio seja visto por milhões de usuários. O Brasil é o 5º país mais conectado do mundo. Por este motivo, o seu negócio não pode ficar fora do mercado digital.</p>
				</div>
			</article>
			<!--Menu Criação de internet -->
			<article class="servico">
				<a href="#"><img id="img" src="img/cs.jpg" alt="Criação de sites">
				<div class="inner">
					<a href="#"> Criação de sites </a>
					<h4> Sites administráveis </h4>
					<p> Agora você pode administrar seu site quando e como quiser. E melhor ainda pois você pode pagar por este serviço, pois desenvolvemos de forma. Seu site atualizado, com seus últimos produtos, integração com redes sociais, agora é possível </p>
				</div>
			</article>
		</main>
		<section class="newsletter container">
		<h2> Inscreva-se agora! </h2>
		<h3> Receba novidades, dicas e muito mais </h3>
		<form name="dados">
			<input type="email" id="email" name="email" placeholder="Digite seu e-mail">
			<button id="botao1" onclick="MyFunction()"> Cadastrar </button>
		</form><br>
		<!-- FOOTER -->
		<footer class="rodape container">
			<div class="social-icons">
				<a href="#"><i class="fab fa-facebook"></i></a>
				<a href="#"><i class="fab fa-twitter"></i></a>
				<a href="#"><i class="fab fa-google"></i></a>
				<a href="#"><i class="fab fa-instagram"></i></a>
				<a href="#"><i class="fa fa-envelope"></i></a>
			</div>
			<p class="copyright">
			&copy; 2019 Feito por Lorran </p>
		</footer>
		<!-- Jquery -->
	<script>
		$(".btn-menu").click(function(){
			$(".menu").show();
		})
		$(".btn-close").click(function(){
			$(".menu").hide();
		})
	</script>
</body>
</html>