<html>
<h1 align="center">CryptoKnightX</h1>

<div align="center">
<img width=”200" height=”200" src="ckx-img.png" alt=”Banner”>
</div>

<div align="center">
<a href="https://www.gnu.org/software/bash/" target="_blank"><img src="https://badgen.net/badge/SHELL/BASH/green?icon=terminal"></a>
<a href="https://www.gnu.org/software/bash/" target="_blank"><img src="https://badgen.net/badge/Versão/0.0.1b/red"></a>
</div>

<p align="center"><br>CryptoKnight é um gerenciador de arquivos feito puramente em bash script, o
objetivo deste programa é manter sua privacidade e integridade de seus documentos.</p>
<p align="center">Este repositório é uma fork do projeto original de Slackjeff.
<a href="https://notabug.org/slackjeff/knight" target="_blank">acesse aqui!</a></p>

<h1 align="center">Configurando</h1>

<p>Abra o executável <code>ckx</code> com um editor de texto e procure pelas variáveis com configurações fundamentais para
o acesso dos arquivos ocultos. exemplo:</p>

<pre>
<code>usuario="root" # <- LOGIN 
senha="root" # <- SENHA 
codinome="debian" # <-- HOSTNAME --> uname -n</code>
</pre>

<p>Edite as variáveis com um login, senha e hostname da sua máquina (utilize o comando <code>uname -n</code> para exibir).</p>
<p>Após isso, salve a edição e execute o <code>install.ckx</code>, o script fará algumas verificações nos repositórios
da máquina para copiar o <code>ckx</code> para <code>/usr/bin/</code> e conceder permissão 700 para somente o root alterar
o arquivo.</p>

<h1 align="center">Comandos</h1>

<h3>Comandos de linha:</h3>
<p><code>ckx [--destruction | -d]</code> - sobrescreve e apaga todos os arquivos contidos na pasta oculta do CKX.</code></p>
<br>

<h3>Comandos no sub-shell:</h3>

<pre>
<code>help - exibe os comandos disponíveis no software</code>
</pre>

<pre>
<code>ckx [v]
   -v > exibe a versão atual.</code>
</pre>

<pre>
<code>view [--image|--text]
   --image | -i > abre uma imagem.
   --text | -t > abre o texto de um arquivo.</code>
  necessita dos utilitários 'mc editor' e 'geeqie'.
</pre>

<hr>
<p align="center">donate<br>bitcoin: bc1qq77c3w5l97da0pjn6d4dx9zueys29p799q7heq</p>
</html>
