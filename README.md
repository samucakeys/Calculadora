<!doctype html>
<html lang="pt-Br">

<head>
	<title>Calculadora</title>
	<!-- Required meta tags -->
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

	<link href="./css/style.css" type="text/css" rel="stylesheet" />
	<!-- Bootstrap CSS -->
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
		integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
</head>

<body>

	<nav class="navbar navbar-expand navbar-dark bg-dark">
		<div class="nav navbar-nav">
			<a class="nav-item nav-link active" href="#">Calculadora JavaScript <span
					class="sr-only">(current)</span></a>
		</div>
	</nav>
	<div class="container" style="margin-top: 40px;">
		<div class="row">
			<div class="col-md-12">

				<div id="calculadora">

					<table>
						<tr>
							<td colspan="4">
								<input type="text" id="tela" maxlength="30" readonly="readonly" />
							</td>
						</tr>
						<tr>
							<td><input type="button" id="apagarAnterior" value="<-" /></td>
							<td><input type="button" id="limparTela" value="C" /></td>
						</tr>
						<tr>
							<td><input type="button" id="num7" value="7" /></td>
							<td><input type="button" id="num8" value="8" /></td>
							<td><input type="button" id="num9" value="9" /></td>
							<td><input type="button" id="divisao" value="/" /></td>
						</tr>
						<tr>
							<td><input type="button" id="num4" value="4" /></td>
							<td><input type="button" id="num5" value="5" /></td>
							<td><input type="button" id="num6" value="6" /></td>
							<td><input type="button" id="multiplicacao" value="*" /></td>
						</tr>
						<tr>
							<td><input type="button" id="num1" value="1" /></td>
							<td><input type="button" id="num2" value="2" /></td>
							<td><input type="button" id="num3" value="3" /></td>
							<td><input type="button" id="subtracao" value="-" /></td>
						</tr>
						<tr>
							<td><input type="button" id="num0" value="0" /></td>
							<td><input type="button" id="ponto" value="." /></td>
							<td><input type="button" id="resultado" value="=" /></td>
							<td><input type="button" id="soma" value="+" /></td>
						</tr>
					</table>
				</div>
			</div>
		</div>
	</div>

	<footer class="footer mt-auto py-3 navbar-dark bg-default">
		<div class="container">
			<span>Produzido por Francisco Chaves.</span>
		</div>
	</footer>

	<script type="text/javascript" src="./js/script.js"></script>
	<!-- Optional JavaScript -->
	<!-- jQuery first, then Popper.js, then Bootstrap JS -->
	<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
		integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
		crossorigin="anonymous"></script>
</body>

</html>
