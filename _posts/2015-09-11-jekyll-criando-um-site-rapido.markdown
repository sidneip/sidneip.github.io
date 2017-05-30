---
title: O Primeiro <s>pedaço do bolo</s> <b>POST</b> vai para o Jekyll
date:   2015-09-11 17:00:00
description: Jekyll um gerador de paginas estaticas utilizando Markdown. Utilizei para criar este blog pela sua praticidade. Dedico a ele o primeiro <s>pedaço do bolo</s> <b>POST!</b>
---

Iniciei este projeto, e estava pensando como construir o meu blog logo vem diversas tecnologias,
frameworks e estava pensando em fazer em HTML puro logo penso em repetições no codigo, então vem
frameworks como Wordpress, Drupal... Que irão adicionar novos fatores como themes, servidor,
segurança e configuração. Então adotei o Jekyll com Github.


### Criando repositorio no Github para hospedar nosso site
![Criando repositorio](/assets/images/github_new_repo.png)
> Seu site já vai esta disponivel em http://sidneip.github.io,
> Envie uma pagina index.html para o seu repositorio.


### Instalando o Jekyll
{% highlight ruby %}
# Instalando o Jekyll
gem install jekyll
# Gerandor site estatico
jekyll new .
# Subindo servidor e compilando a cada alteração
jekyll serve --watch
{% endhighlight %}

### Temas
Após instalarmos o Jekyll, vamos procurar um tema legal para iniciarmos nosso blog/site. Site com alguns temas gratis<br>
[Alguns temas para Jekill](http://jekyllthemes.org/)
Após baixar o tema escolhido e instalarmos, substituindo os arquivos que baixamos. Vamos configurar, __lembrando que após subsitituir os arquivos do tema é precisa reiniciar o servidor__.

### Configurando
A configuração é simples, um arquivo yaml _config.yml com variaveis que devem ser preenchidas para serem utilizadas pela engine e template. As pastas do projeto são bem intuitivas sem dificuldade para alterações.
<br>
Após personalizar seu projeto basta você commitar e subir para o repositorio. E o seu site esta publicado.

# Resumindo
Neste <b>POST</b> não tinha como objetivo falar como subir um site em __Jekyll__, e sim a facilidade em adotar esse framework para minha solução, chegando ao minimo que desejava de forma simples e retirando diversos passos que teria para caso adotasse o Wordpress como Personalizar/Configurar novo tema, Hospedagem, mySQL, Plugins, permalinks, SEO. Porem para blogs com 500 posts como seria a compilação a cada alteração.

_Iniciando o blog esta otimo_

{%highlight s%}
Regenerating: 1 file(s) changed at 2015-08-12 23:52:46 ...done in 0.07258 seconds.
{%endhighlight%}

