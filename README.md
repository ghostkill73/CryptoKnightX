<div>
<img src="banner.png" alt=”banner”>
<!---banner by _surowo (discord)--->
</div>


<!---CKX--->


<br>
<h1 align="center">CryptoKnightX</h1>

<div align="center">
<a href="https://www.gnu.org/software/bash/" target="_blank"><img src="https://badgen.net/badge/Made with/Bash/green?icon"></a>
<img src="https://badgen.net/badge/Version/0.0.4/red?icon">
<a href="https://www.gnu.org/licenses/gpl-3.0.html" target="_blank"><img src="https://badgen.net/badge/Free Software/GPLv3.0+/black?icon"></a>
</div>

<p align="center"><br>CryptoKnightX é um subshell encriptador de arquivos feito em bash script, o
objetivo deste software é manter sua privacidade e integridade de seus arquivos.</p>
<p align="center">Este repositório é uma fork do projeto originado por Slackjeff.
<a href="https://notabug.org/slackjeff/knight" target="_blank">acesse aqui!</a></p>


<!---DEPENDENCIAS--->


<br>
<h2 align="center">Dependências</h2>
<p>Dependências necessárias para utilizar o software:</p>
<ul>
   <li><b><a href="https://www.gnu.org/software/tar/" target="_blank">GNU Tar</a> 1.30+</b></li>
   <li><b><a href="https://www.gnu.org/software/bash/" target="_blank">GNU Bash</a> 3+</b></li>
   <li><b><a href="https://gnupg.org/" target="_blank">gnupg</a> 2.2+</b></li>
</ul>

<b>OBS: as versões exigidas podem não corresponder com a realidade, o software está em fase de testes.
provavelmente dependências mais antigas irão funcionar corretamente.</b>


<!---COMO INSTALAR--->


<br>
<h2 align="center">Como instalar?</h2>
<p>Acesse a última release ou faça o download usando <code>wget</code>:</p>
<pre>
wget https://github.com/ghostkill73/CryptoKnightX/releases/download/0.0.4/ckx-0.0.4.tar.gz && tar -xvf ckx-0.0.4.tar.gz
</pre>

<br><br>
<p>caso queira instalar a versão mais recente, utilize uma das linhas de comando abaixo:</p>

<p><code>git</code>:</p>
<pre>git clone https://github.com/ghostkill73/CryptoKnightX
cd CryptoKnightX
chmod +x ckx</pre>
<br>
<p><code>wget</code>:</p>
<pre><code>wget https://raw.githubusercontent.com/ghostkill73/CryptoKnightX/main/ckx && chmod +x ckx</code></pre>
<br>
<p><code>curl</code>:</p>
<pre><code>curl -L https://raw.githubusercontent.com/ghostkill73/CryptoKnightX/main/ckx >> ckx && chmod +x ckx</code></pre>
<br>


<!---COMO UTILIZAR--->


<br>
<h2 align="center">Como utilizar?</h2>

<p>Para iniciar o software:</p>
<pre><code>sudo ./ckx --start</code></pre>

<br>
<p>crie alguns arquivos e depois utilize o comando <code>exit</code> ou <code>quit</code>
para criptografar os arquivos e sair, será exigido uma senha para a respectiva encriptação,
não perca a senha de jeito algum!
   
Para acessar novamente será preciso digitar a senha que foi
digitada antes.</p>

<h4>Comandos:</h4>
<pre>
-h, --help                 exibe a mensagem de ajuda.
-v, --version              exibe a versão do software.
-l, --license              exibe a licença do software.
-s, --start                inicia o software.
-gpgconf, --enc-config     opção para configurar a criptografia no
                           modo questionário.   
</pre>

<h4>configurando o gpg:</h4>

<pre><code>sudo ./ckx -gpgconf</code></pre>

<p>Esse comando vai facilitar o processo de configuração da criptografia
simétrica do gpg.</p>


<h2 align="center">to-do</h2>

* [ ] Documentação
* [x] Múltiplos diretórios
* [ ] Opção para configurações gerais
* [ ] Interface mais intuitiva e informativa


<!---DONATE--->


<br>
<h2 align="center">Donate</h2>
<p align="center">bitcoin: bc1qq77c3w5l97da0pjn6d4dx9zueys29p799q7heq</p>
