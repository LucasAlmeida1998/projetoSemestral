# projetoSemestral
<!DOCTYPE html>
<html>
	<head>
		<title> Item 15 Projeto </title>
	</head>
	<body>
		<form action="sevidor" method="get">
			<fieldset>
			
			<legend>Dados de login</legend>
			
			<table cellspacing='10'>
			<tr>
				<td>
					<label for="Nome"> Nome Completo </label>
				</td>
				<td align="left">
					<input type="text" name="Nome">
				</td>
			</tr>
			<tr>
				<td>
					<label> Celular: </label>
				</td>
				<td align="left">
					<input type="text" name="ddd" size="2" maxlength="2"> 
					<input type="text" name="num" size="9" maxlength="9"> 
				</td>
			</tr>
			<tr>
				<td>
					<label for="email"> E-mail </label>
				</td>
				<td align="left">
					<input type="text" name="email">
				</td>
			</tr>
			<tr>
				<td>
					<label for="imagem"> Imagem de perfil </label>
				</td>
				<td>
					<input type="file" name="imagem">
				</td>
			</tr>
			<tr>
				<td>
					<label for="login"> Login de usuario </label>
				</td>
				<td align="left">
					<input type="text" name="login">
				</td>
			</tr>
			<tr>
				<td>
					<label for="pass"> Senha: </label>
				</td>
				<td align="left">
					<input type="password" name="pass">
				</td>
			</tr>
			<tr>
				<td>
					<label for="passconfirm"> Confirme a senha </label>
				</td>
				<td align="left">
					<input type="password" name="passconfirm">
				</td>
			</tr>	
			</table>
			
			<input type="submit">
			<input type="reset" value="Limpar">
			
			</fieldset>
			
		</form>
	</body>	
</html>
