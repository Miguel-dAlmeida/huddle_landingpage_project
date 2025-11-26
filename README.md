# Quest HTML + CSS Avançado | Desafio do Frontend Mentor
<div>
  <img src="https://raw.githubusercontent.com/Miguel-dAlmeida/huddle_landingpage_project/main/src/images/gif_final_page.gif" alt="Gif do resultado final da página" >
</div>

### [Veja a página clicando aqui!](https://miguel-dalmeida.github.io/huddle_landingpage_project/) 

## __Sumário__

- [Apresentação](#apresentação)
- [Explicação do Projeto](#explicação-do-projeto)
- [Ferramentas e Tecnologias Utilizadas](#ferramentas-e-tecnologias-utilizadas)
- [Principais Recursos e Abordagens](#principais-recursos-e-abordagens)
- [Aprendizado Adquirido](#aprendizado-adquirido)
- [Desenvolvimento Contínuo](#desenvolvimento-contínuo)
- [Agradecimentos e Conclusão](#agradecimentos-e-conclusão)

## __Apresentação__  

Olá, meu nome é Mário Miguel, e sou um aspirante a Desenvolvedor Web. Este projeto faz parte da minha jornada de aprendizado no curso de Formação de Desenvolvedor Web Fullstack _DevQuest - Dev em Dobro_.  

O desafio, intitulado **_"Huddle Landing Page With Single Introductory Section"_**, faz parte do site **Frontend Mentor** e foi proposto no módulo **"Quest HTML + CSS Avançado"**. Após concluir os módulos de HTML e CSS avançado, fui desafiado a recriar esse layout individualmente, aplicando na prática todo o conhecimento adquirido anteriormente.  

## __Explicação do Projeto__  

Este projeto consiste em uma Landing Page para promover o __*Huddle*__, uma aplicação web de bate-papo e criação de comunidades. A página apresenta uma chamada para ação, introduzindo brevemente o propósito do Huddle e incentivando o usuário a se registrar por meio de um botão. Além disso, inclui ícones das redes sociais que direcionam os usuários para os perfis oficiais da aplicação.  

O design da landing page utiliza predominantemente as cores roxo, branco e rosa, adotando uma estética moderna. O layout foi cuidadosamente desenvolvido para garantir uma boa experiência em diferentes dispositivos, como smartphones, tablets, notebooks e desktops. Além disso, atenção especial foi dada à adaptação do layout para redimensionamentos de tela, como ao usar atalhos de janela no Windows ou a navegação em modo paisagem, especialmente em tablets, assegurando a coesão visual em qualquer contexto de uso.

## __Ferramentas e Tecnologias Utilizadas__
<div style="display: inline_block"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Markdown" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/markdown/markdown-original.svg" />
</div>

## __Principais Recursos e Abordagens__

- **Tags semânticas**: Utilização de tags semânticas como `<header>`, `<footer>`, `<main>`, entre outras, para garantir uma melhor estruturação do conteúdo e facilitar a acessibilidade e a indexação por mecanismos de busca (SEO).
- **Div's estilizatórias**: Uso de `<div>` como contêineres para organizar e estruturar o layout da página, proporcionando maior facilidade na aplicação de estilos com CSS (principalmente no que diz respeito ao posicionamento dos elementos).
- **Desktop First**: A abordagem inicial foi a criação do layout com foco em dispositivos desktop, seguido de ajustes para telas menores utilizando media queries.
- **Unidade de medida relativa (rem)**: Garantia de escabilidade dentro do projeto (com essa abordagem, um ponto de alteração reflete em toda a página)
- **CSS Flexbox**: Aplicação do _Flexbox_ para a disposição e alinhamento de elementos.
- **Propriedades `transition`**: Uso de transições CSS para elevar a estética da aplicação.
- **Media Queries**: Aplicação de media queries para garantir que o layout se adapte adequadamente a diferentes tamanhos de tela.
- **Responsividade Condicional**: Implementação de media queries com condicionais, como `(orientation: portrait)`, para aplicar estilos específicos conforme a orientação da tela e outras características do dispositivo.
- **Pseudo-classes**: Utilização de pseudo-classes como `:hover` e `:nth-child`. 
- **Prefixos `-webkit-`, `-ms-` e `-o-`**: Inclusão de prefixos em propriedades CSS para garantir compatibilidade com versões antigas de navegadores.  
*__Nota:__ Utilizei o site <a href="https://autoprefixer.github.io/">Autoprefixer CSS online</a> para incluir os prefixos automaticamente.*
- **Ícones do FontAwesome**: Importação de ícones do FontAwesome.
- **Fontes do Google Fonts**: Inclusão da fonte *Open Sans*.
- **Resets CSS**: O uso de um arquivo de _Reset CSS_ para normalizar a aparência dos elementos e resetar algumas definições indesejadas.

## **Desafios Enfrentados**  

Na construção da estrutura HTML do projeto, não encontrei dificuldades. Da mesma forma, a codificação dos estilos e do reset CSS, embora mais trabalhosa do que a marcação, fluiu sem grandes desafios.  

As verdadeiras complicações surgiram na implementação da responsividade. Embora eu não tenha precisado "quebrar a cabeça" para torná-la funcional, meu código acabou ficando excessivamente verboso, tornando o processo cansativo. A falta de um planejamento inicial voltado para escalabilidade me levou a ajustar manualmente os valores de diversas propriedades, o que aumentou consideravelmente o tempo de desenvolvimento.  

Apesar de ter conseguido replicar o layout fielmente, não fiquei satisfeito com o resultado. Após finalizar o projeto, enviei-o para correção. __No período de espera pelo feedback do professor, dediquei-me ao estudo aprofundado de responsividade, com foco especial na escalabilidade por meio de unidades relativas, como `%` e `rem`. Com esse aprendizado, refatorei meu código, reduzindo drasticamente o tamanho do arquivo `responsive.css` e eliminando redundâncias.__

Paralelamente, recebi um documento do professor contendo uma análise detalhada dos pontos positivos e negativos do meu código. Ele não alterou diretamente o projeto, mas apontou erros e sugeriu melhorias, o que me levou a refiná-lo por conta própria. Dentre as mudanças implementadas, destaque-se a inclusão da tag `<ul>` para agrupar os ícones das redes sociais, melhorando a semântica e a organização, além da aplicação de `box-shadow` no botão para criar um efeito de borda no estado `hover`.


## **Aprendizado Adquirido**  

Durante o desenvolvimento deste projeto, aprofundei meus conhecimentos em diversos aspectos do HTML e CSS.  

Um dos primeiros desafios solucionados foi a adição de bordas arredondadas ao redor dos ícones das redes sociais. Inicialmente, utilizei `padding`, o que resultava em tamanhos ligeiramente desiguais entre os ícones, causando desalinhamento visual nas bordas. Após pesquisas, descobri que a solução ideal seria envolver os ícones em um contêiner fixo e circular. Esse ajuste só foi possível quando compreendi que os ícones do Font Awesome funcionam como elementos `:before` dentro da tag `<i>`.    
Além disso, aprendi sobre a media query `orientation`, que aceita os valores `portrait` e `landscape`, o que me permitiu adicionar pontos de quebra condicionais, conferindo maior especificidade às minhas declarações e evitando sobrescrições indesejadas. 

No entanto, o aprendizado mais significativo veio fora da codificação do projeto. Como mencionei no campo "Desafios Enfrentados", fiquei insatisfeito com a verbosidade do meu arquivo `responsive.css` e, enquanto aguardava o feedback do professor, busquei aprimoramento adicional. Durante esse período, assisti à masterclass *Responsividade na Prática | Masterclass #08* do canal *Rocketseat* no YouTube. Com 1h30min de duração, a aula proporcionou um estudo aprofundado sobre responsividade na prática, onde pude codificar junto ao instrutor um layout responsivo completo.  

### Assista também à masterclass de responsividade clicando no link abaixo:  
[![Responsividade na Prática | Masterclass #08](https://img.youtube.com/vi/H91DhKPjhPk/maxresdefault.jpg)](https://www.youtube.com/watch?v=H91DhKPjhPk)

__Dentre os aprendizados mais valiosos extraídos desse aulão da Rocketseat, destaco:__

- **Escalabilidade com `rem` e `%`**  
  Bom, eu já sabia que essas unidades combinadas serviam para escalar os valores numéricos de uma aplicação. Porém, por esse conhecimento ser majoritariamente teórico, não consegui aplicá-lo corretamente.  
  Durante o aulão da Rocketseat, foi-me mostrado na prática como usar esse conceito. Com essa nova bagagem de conhecimento prático, pude aplicá-lo em meu projeto __*Huddle*__, reduzindo drasticamente o tamanho do arquivo `responsive.css`.   

- **Alinhamento automático com `margin-left: auto` e `margin-right: auto`**  
  Esse método simplifica o posicionamento de elementos nas extremidades laterais dos contêineres.  

- **Ajuste dinâmico do Grid com `auto-fit`**  
  O valor `auto-fit` no CSS Grid já havia sido abordado no módulo *"CSS Avançado - Parte 3 (Grid)"* do curso *__DevQuest__*, mas a masterclass reforçou minha compreensão, demonstrando sua aplicação na prática para automatizar a quebra e a expansão dos itens de grade.

- **Criação de Menu Hambúrguer com HTML, CSS e JavaScript**  
  Em larguras inferiores a 540px, o layout fictício da Rocketseat apresentava problemas no `<header>`, exigindo a implementação de um menu hambúrguer. No curso *DevQuest*, já havia aprendido a construir esse tipo de menu utilizando apenas HTML e CSS. Porém, na masterclass da *Rocketseat*, foi adicionada a implementação em JavaScript para manipular a exibição da lista de navegação. Embora eu ainda não tenha iniciado meus estudos em JavaScript, consegui compreender sua função na criação desse recurso.  

- **Media Queries avançadas**  
  Aprofundei meus conhecimentos sobre valores como `screen` e `print` em media queries, além de técnicas como agrupamento de media queries e uso de `all`, `and` e `or`. 

- **Imagens responsivas e formatos otimizados**  
  Descobri diferentes variações de imagens, como `hqdefault` (High Quality Default), `mqdefault` (Medium Quality Default) e `maxresdefault` (Maximum Resolution Default), aprendendo em quais contextos cada uma deve ser utilizada. Além disso, revisei o uso das tags `<picture>` e `<source>` para exibir imagens distintas dependendo do tamanho da tela do usuário.  

- **HTML Media Attributes**  
  Entendi melhor a aplicação do atributo `media` no HTML. 

## __Desenvolvimento Contínuo__  

Ao terminar o módulo __*"Quest HTML + CSS Avançado"*__, o percurso padrão seria começar o módulo de __JavaScript Básico__ do _DevQuest_. Mas, em vez de seguir direto para o JS, decidi fazer um pequeno desvio.  

Quero reforçar ainda mais meus conhecimentos em HTML e CSS antes de avançar. Para isso, vou praticar com alguns desafios do **Frontend Mentor**, que exigem apenas essas duas tecnologias. Sei que JavaScript é essencial, mas prefiro ter uma base bem consolidada primeiro. Assim, quando for a hora de aprender JS, acredito que tudo fará mais sentido.

## __Agradecimentos e Conclusão__

Se você chegou até aqui, meu sincero obrigado por dedicar seu tempo a explorar este projeto e acompanhar minha jornada. Completar esse desafio foi uma grande conquista, e cada passo reforça minha certeza de que estou no caminho certo para conquistar minha primeira vaga como desenvolvedor web júnior.  

A cada projeto finalizado, percebo o quanto minha características de ser autodidata têm sido um diferencial no meu aprendizado. Sempre que encontro um obstáculo, recorro a documentações, vídeos, blogs e até IA para encontrar soluções. Acredito que essa mentalidade investigativa será essencial para minha evolução na área.  

Um grande abraço e até o próximo projeto. __Bora codar!__

 <div style="margin-bottom: 20px;">
    <a style="padding-right: 3px;" href="https://www.linkedin.com/in/mariomigueldealmeida/" target="_blank"><img
        src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"
        target="_blank"></a>
    <a href="mailto:mariomigueldealmeida@gmail.com"><img
        src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"
        target="_blank"></a>
  </div>

<div align="center">
  <img src="https://raw.githubusercontent.com/Miguel-dAlmeida/huddle_landingpage_project/main/src/images/closingImage.gif" alt="Imagem representando união e parceria" width="80%">
</div>


