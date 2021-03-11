# DiferHtml
![](https://raw.githubusercontent.com/geniodev/DiferHtml/main/magichtmlsearch.png?raw=true)</br>
&nbsp;
*Pega HTML e traz parametros para buscas unicos usando as tags e parametros*</br>

*O DiferHtml, serve para quando você precisa usar chaves unicas para pesquisar informações no html que você baixou e fez webscrap.*</br>
*Ele vai transformar o html em uma tabela, e retirar todo atributo que tem mais de 1 vez, assim voce pode pegar uma tag e baixar a informação certa usando aquela configuração no Beatfulsoup 4 nos metodos de buscar tags com parametros para baixar dados.*</br>

&nbsp;
&nbsp;

*Índices*
&nbsp;
- <a href="https://github.com/geniodev/VozTexto#voztexto" target="_self">Inicio</a>
- <a href='https://github.com/geniodev/VozTexto#bibliotecas-instalar' target='_self'>Bibliotecas Install</a>
- <a href='https://github.com/geniodev/VozTexto#documenta%C3%A7%C3%A3o---f%C3%B3rmulas' target='_self'>Documentação</a>
  - <a href='https://github.com/geniodev/VozTexto#remove-acentos-das-strings-inseridas-no-txt' target='_self'>Remove acentos das strings inseridas no 'txt'</a>
    - <a href='https://github.com/geniodev/VozTexto#remove-acentos-das-strings-inseridas-no-txt' target='_self'>remover_acentos(txt)</a>
  - <a href='https://github.com/geniodev/VozTexto#ouvi-a-fala-de-voz-e-retorna-o-texto-sem-acentos' target='_self'>Ouvi a fala de voz e retorna o texto sem acentos</a>
    - <a href='https://github.com/geniodev/VozTexto#ouvi-a-fala-de-voz-e-retorna-o-texto-sem-acentos' target='_self'>ListenWorkd()</a>
  - <a href='https://github.com/geniodev/VozTexto#fala-a-hora-atual-e-minutos' target='_self'>Fala a hora Atual e minutos</a>
    - <a href='https://github.com/geniodev/VozTexto#fala-a-hora-atual-e-minutos' target='_self'>Falarhora()</a>
  - <a href='https://github.com/geniodev/VozTexto#voz-para-texto' target='_self'>Voz para Texto</a>
    - <a href='https://github.com/geniodev/VozTexto#voz-para-texto' target='_self'>OuvirFala()</a>
  - <a href='https://github.com/geniodev/VozTexto#texto-para-voz' target='_self'>Texto para Voz</a>
    - <a href='https://github.com/geniodev/VozTexto#texto-para-voz' target='_self'>falag(falaragora)</a>





&nbsp;
&nbsp;
<h1 id="install">Bibliotecas Instalar</h1></br>

```bash
pip install beautifulsoup4
pip install pandas
pip install numpy
```

&nbsp;
# Documentação - Fórmulas:</br>

#### Arquivo: Uso passe o nome do arquivo salvo em html
#### HtmlTxt: Passe o html completo em forma de string contendo tudo(tags, atributos...)
Principal(Arquivo, HtmlTxt)
> `Principal(Arquivo=None, HtmlTxt=None)`


&nbsp;
<h6 align="center">Desenvolvedor: RA (Ricardo Andrade)</h6>
<h6 align="center">Versão: 2.0.0</h6>
