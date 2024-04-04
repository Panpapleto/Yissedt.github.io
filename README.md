<!DOCTYPE html>
<html lang="en">
<head>
	<!-- Agrega la biblioteca de iconos -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6/css/all.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="redes.css">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Leidy Yissedt Lara Díaz</title>
	<style>
	 img {
        border-radius: 100px 100px 100px 100px;
		position: fixed;
		top: 10px;
		left: 10px;
      }
		body {
		
font-family: Arial, sans-serif;
			background-color: #f2f2f2;
			margin: 0;
		}
		header {
              color: #fff;
              background-image:linear-gradient(to bottom,
               #ae00d1b2, #ff1ac6ec, #fa2f2fb9, #f84f1be0, #f8e218);
			                padding: 20px;
}
		nav {
			display: flex;
			justify-content: space-between;
			align-items: center;
		}
		nav ul {
			list-style: none;
			margin: 0;
			padding: 0;
			display: flex;
		}
		nav ul li {
			margin: 0 10px;
		}
		nav ul li a {
			color: #fff;
			text-decoration: none;
			padding: 10px;
			border-radius: 5px;
		}
		nav ul li a:hover {
			background-color: #666;
		}
			main {
			margin: 20px;
			display: flex;
			flex-direction: column;
			align-items: center;
		}
		h1 {
                        font-size: 36px;
			margin-bottom: 20px;
			margin-left: 160px;
					}
		section {
                        background-color: #fff;
                        padding: 20px;
			border-radius: 5px;
			box-shadow: 0px 0px 10px rgba(0,0,0,0.2);
			margin-bottom: 20px;
			width: 100%;
			max-width: 800px;
		}
		section h2 {
			font-size: 24px;
			margin-bottom: 10px;
		}
		section p {
			font-size: 16px;
			line-height: 1.5;
			margin-bottom: 10px;
		}
		form label {
			display: block;
			margin-bottom: 10px;
		}
		form input, form textarea {
			padding: 10px;
			border-radius: 5px;
			border: none;
			margin-bottom: 10px;
			width: 100%;
			max-width: 400px;
		}
		form input[type="submit"] {
			background-color: #333;
			color: #fff;
			cursor: pointer;
		}
		form input[type="submit"]:hover {
			background-color: #666;
		}
	</style>
	
</head>
<body>
    <header>
		<nav>
			<img class="Yissedt" src="Yiss.jpg" alt="Imagen" width="150" height="150">
				<h1>Leidy Yissedt Lara Díaz</h1>
			<ul>
				<li><a href="#inicio">Inicio</a></li>
				<li><a href="#currículum">Currículum</a></li>
				<li><a href="#publicaciones">Publicaciones</a></li>
				<li><a href="#contacto">Contacto</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="inicio">
			<h2>Inicio</h2>
			<p>Bienvenid@s.</p>
		</section>
		<section id="currículum">
			<h2>Currículum</h2>
			<embed src="CV_Lara-Diaz.pdf" type="application/pdf" width="100%" height="800px">
			<p>Aquí puedes encontrar mi currículum y mi experiencia laboral.</p>

</section>
<section id="publicaciones">
<h2>Publicaciones</h2>
<p>Aquí puedes encontrar los enlaces de mis publicaciones más recientes:</p>
<ul>
<li><a href="https://noticias.udec.cl/aplican-matematica-para-resolver-problemas-del-area-forestal/">Noticias UdeC: Aplican matemática para resolver problemas del área forestal</a></li>
<li><a href="https://paginav.cl/2021/04/05/investigacion-udec-analiza-efectividad-de-medidas-de-control-covid-decretadas-por-el-gobierno/">Paginav: Investigación UdeC analiza efectividad de medidas de control COVID decretadas por el gobierno</a></li>
<li><a href="https://revistaidi.udec.cl/pronosticar-covid-19-usando-matematica/">Revista UdeC: Pronosticar COVID-19 usando matemática</a> </li>
<li><a href="https://www.ci2ma.udec.cl/publicaciones/tesisposgrado/graduado.php?id=84">CI2MA: Tesis dortoral </a></li>
<li><a href="https://www.cmm.uchile.cl/?p=43657">CMM: UdeC titula a dos nuevas Doctoras en Ingeniería Matemática con apoyo CMM</a></li>
</ul>
</section>
<section id="contacto">
<h2>Contacto</h2>
<!-- Agrega los enlaces a tus redes sociales -->
<a href="https://www.facebook.com/yissedt.lara" class="fa fa-facebook"></a>
<a href="https://twitter.com/Yisslara" class="fa fa-twitter"></a>
<a href="https://www.linkedin.com/in/leidy-yissedt-lara/" class="fa fa-linkedin"></a>
<a href="https://www.instagram.com/yisslara/" class="fa fa-instagram"></a>
<a href="https://wa.me/56937571538" class="fa fa-whatsapp"></a>
<a href="mailto:leyla.math@gmail.com" class="fa fa-envelope"></a>
<a href=""><i class="fab fa-researchgate"></i></a>
<form>
<label for="nombre">Nombre:</label>
<input type="text" id="nombre" name="nombre" required>
<label for="correo">Correo electrónico:</label>
<input type="email" id="correo" name="correo" required>
<label for="comentario">Comentario:</label>
<textarea id="comentario" name="comentario" rows="4" required></textarea>
<input type="submit" value="Enviar">
</form>
<form action=""method="post">
	<input type="file" name="file" id="file">
	<div id="preview" class="styleImage"></div>
</form>
</section>
</main>
<script src="js/main.js"></script>
  </body>
</html>
