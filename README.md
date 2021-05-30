# Formulario-001

<div id="app">
  <div ui-view></div>
</div>
<img class="img-responsive" src="https://dfprojetos.com.br/loja/image/cache/Produto/cadastro%20de%20clientes-800x800.jpg">
html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<title>CADASTRO DE CLIENTES COM BANCO DE DADOS E PHP</title>
<style type="text/css">
.style1 {
color: #FF0000;
font-size: x-small;
}
.style3 {color: #0000FF; font-size: x-small; }
</style>
<script type="text/javascript">
function validaCampo()
{
if(document.cadastro.nome.value=="")
{
alert("O Campo nome é obrigatório!");
return false;
}
else
if(document.cadastro.email.value=="")
{
alert("O Campo email é obrigatório!");
return false;
}
else
if(document.cadastro.endereco.value=="")
{
alert("O Campo endereço é obrigatório!");
return false;
}
else
if(document.cadastro.cidade.value=="")
{
alert("O Campo Cidade é obrigatório!");
return false;
}
else
if(document.cadastro.estado.value=="")
{
alert("O Campo Estado é obrigatório!");
return false;
}
else
if(document.cadastro.bairro.value=="")
{
alert("O Campo Bairro é obrigatório!");
return false;
}
else
if(document.cadastro.pais.value=="")
{
alert("O Campo país é obrigatório!");
return false;
}
else
if(document.cadastro.login.value=="")
{
alert("O Campo Login é obrigatório!");
return false;
}
else
if(document.cadastro.senha.value=="")
{
alert("Digite uma senha!");
return false;
}
else
return true;
}
<!-- Fim do JavaScript que validará os campos obrigatórios! -->
</script>
</head>
<body>
<form id="cadastro" name="cadastro" method="post" action="cadastro.php"
onsubmit="return validaCampo(); return false;">
<table width="625" border="0">
<tr>
  <img class="img-responsive" src="data:image/jpeg;base64,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">
<td width="69">Nome:</td>
<td width="546"><input name="nome" type="text" id="nome" size="70" maxlength="60"/>
<span class="style1">*</span></td>
</tr>
<tr>
<td>Email:</td>
<td><input name="email" type="text" id="email" size="70" maxlength="60" />
<span class="style1">*</span></td>
</tr>
<tr>
<td>Sexo:</td>
<td><input name="sexo" type="radio" value="Masculino" checked="checked" />
Masculino
<input name="sexo" type="radio" value="Feminino" />
Feminino <span class="style1">*</span> </td>
</tr>
<tr>
<td>DDD:</td>
<td><input name="ddd" type="text" id="ddd" size="4" maxlength="2" />
Telefone:
<input name="telefone" type="text" id="telefone" />
<span class="style3">Apenas números</span> </td>
</tr>
<tr>
<td>Endereço:</td>
<td><input name="endereco" type="text" id="endereco" size="70" maxlength="70" />
<span class="style1">*</span></td>
</tr>
<tr>
<td>Cidade:</td>
<td><input name="cidade" type="text" id="cidade" maxlength="20" />
<span class="style1">*</span></td>
</tr>
<tr>
<td>Estado:</td>
<td><select name="estado" id="estado">
<option>Selecione...</option>
<option value="AC">AC</option>
<option value="AL">AL</option>
<option value="AP">AP</option>
<option value="AM">AM</option>
<option value="BA">BA</option>
<option value="CE">CE</option>
<option value="ES">ES</option>
<option value="DF">DF</option>
<option value="MA">MA</option>
<option value="MT">MT</option>
<option value="MS">MS</option>
<option value="MG">MG</option>
<option value="PA">PA</option>
<option value="PB">PB</option>
<option value="PR">PR</option>
<option value="PE">PE</option>
<option value="PI">PI</option>
<option value="RJ">RJ</option>
<option value="RN">RN</option>
<option value="RS">RS</option>
<option value="RO">RO</option>
<option value="RR">RR</option>
<option value="SC">SC</option>
<option value="SP">SP</option>
<option value="SE">SE</option>
<option value="TO">TO</option>
</select>
<span class="style1">* </span></td>
</tr>
<tr>
<td>Bairro:</td>
<td><input name="bairro" type="text" id="bairro" maxlength="20" />
<span class="style1">*</span></td>
</tr>
<tr>
<td>País:</td>
<td><input name="pais" type="text" id="pais" maxlength="20" />
<span class="style1">*</span></td>
</tr>
<tr>
<td>Login:</td>
<td><input name="login" type="text" id="login" maxlength="12" />
<span class="style1">*</span></td>
</tr>
<tr>
<td>Senha:</td>
<td><input name="senha" type="password" id="senha" maxlength="12" />
<span class="style1">*</span></td>
</tr>
<tr>
<td colspan="2"><input name="news" type="checkbox" id="news" value="ATIVO"
checked="checked" />
Desejo receber novidades e informações sobre o conteúdo deste site. </td>
</tr>
<tr>
<td colspan="2"><p>
<input name="cadastrar" type="submit" id="cadastrar" value="Concluir meu
Cadastro!" />
<input name="limpar" type="reset" id="limpar" value="Limpar Campos
preenchidos!" />
<span class="style1">* Campos com * são obrigatórios! </span></p>
<p> </p></td>
</tr>
</table>
</form>
</body>
</html>
----------------- Upload da foto em PHP
<html>
<head>
<title>Envia Produto</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1">
<style type="text/css">
<!--
.style5 {font-family: Verdana, Arial, Helvetica, sans-serif; font-weight: bold; color: #345885; font-size: 11px; }
-->
</style>
<link href="css.css" rel="stylesheet" type="text/css">
<style type="text/css">
<!--
.style6 {
    font-family: Verdana, Arial, Helvetica, sans-serif;
    font-weight: bold;
    font-size: 20px;
    color: #345885;
}
.style7 {
    font-size: 14px;
    font-family: Verdana, Arial, Helvetica, sans-serif;
    font-weight: bold;
    color: #FF3300;
}
.style8 {
    color: #333333;
    font-size: 12px;
}
-->
</style>
</head>

<body>
<p><span class="style6">Produtos |</span> <span class="style7">Telefones <br>
    <span class="style8">*Somente envie fotos no formato JPG, e no tamanho preferencial de 130x142 px</span> </span></p>
<hr align="left" width="80%" class="regua">
<form method="POST" action="../postar.php" enctype="multipart/form-data"><div align="left">
  <table width="95%"  border="0" cellspacing="0" cellpadding="0">
    <tr>
      <td width="22%" bgcolor="#F5F5F5"><span class="style5">&nbsp;&nbsp;&nbsp; Nome:</span></td>
      <td width="78%"><input name="nome" type="text" class="formula" size="80"></td>
    </tr>
    <tr>
      <td bgcolor="#F5F5F5"><span class="style5">&nbsp;&nbsp; &nbsp;Foto</span></td>
      <td><input name="form_imagem" type="file" class="formula" id="form_imagem2" size="45"></td>
    </tr>
    <tr>
      <td bgcolor="#F5F5F5"><span class="style5">&nbsp;&nbsp;&nbsp;Descri&ccedil;&atilde;o</span></td>
      <td><textarea name=msg cols="80" rows="6" class=formula id="textarea2" tabindex=3></textarea></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
      <td><input name="acao" type="hidden" id="acao2" value="enviar">
        <input name="form_url" type="hidden" id="form_url2" value="<? echo $url; ?>">
        <br>
        <input name="Submit" type="submit" class="bt" value="Enviar"></td>
    </tr>
  </table>
  </div>
</form>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
	<title>Cadastro de Cliente</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="css/custom.css">
</head>
<body>
	<div class='container'>
		<fieldset>
			<legend><h1>Formulário - Cadastro da Empresa</h1></legend>
			
			<form action="action_cliente.php" method="post" id='form-contato' enctype='multipart/form-data'>
				<div class="row">
					<label for="nome">Selecionar Foto</label>
			      	<div class="col-md-2">
					    <a href="#" class="thumbnail">
					      <img src="https://eckart.com.br/site/wp-content/uploads/2020/09/marca-sua-empresa.png" height="190" width="150" id="foto-cliente">
					    </a>
				  	</div>
				  	<input type="file" name="foto" id="foto" value="foto" >
			  	</div>

			    <div class="form-group">
			      <label for="nome empresa ">Nome Empresa</label>
			      <input type="text" class="form-control" id="nome empresa" name="nome empresa" placeholder="Infome o Nome Empresa">
			      <span class='msg-erro msg-nome'></span>
			    </div>

			    <div class="form-group">
			      <label for="email">E-mail</label>
			      <input type="email" class="form-control" id="email" name="email" placeholder="Informe o E-mail">
			      <span class='msg-erro msg-email'></span>
			    </div>

			    <div class="form-group">
			      <label for="cnpf">CNPJ</label>
			      <input type="cnpj" class="form-control" id="cnpj" maxlength="14" name="cnpj" placeholder="Informe o CNPJ">
			      <span class='msg-erro msg-cpf'></span>
			    </div>
			    <div class="form-group">
			      <label for="data_entrada">Data de Entrada</label>
			      <input type="data_entrada" class="form-control" id="data_entrada" maxlength="10" name="data_entrada">
			      <span class='msg-erro msg-data_entrada'></span>
			    </div>
			    <div class="form-group">
			      <label for="data_saida">Data Saida</label>
			      <input type="data_saida" class="form-control" id="data_saida" maxlength="12" name="data_saida" placeholder="Informe a data_saida">
			      <span class='msg-erro msg-data_saida'></span>
			    </div>
			    <div class="form-group">
			      <label for="celular">Celular</label>
			      <input type="celular" class="form-control" id="celular" maxlength="13" name="celular" placeholder="Informe o Celular">
			      <span class='msg-erro msg-celular'></span>
			    </div>
			    <div class="form-group">
			      <label for="status">Status</label>
			      <select class="form-control" name="status" id="status">
				    <option value="">Selecione o Status</option>
				    <option value="Ativo">Ativo</option>
				    <option value="Inativo">Inativo</option>
				  </select>
				  <span class='msg-erro msg-status'></span>
			    </div>

			    <input type="hidden" name="acao" value="incluir">
			    <button type="submit" class="btn btn-primary" id='botao'> 
			      Gravar
			    </button>
			</form>
		</fieldset>
	</div>
	<script type="text/javascript" src="js/custom.js"></script>
</body>
</html>

