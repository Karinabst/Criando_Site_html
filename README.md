Primeiro site html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1 id="inicio">Informações sobre HTML</h1>
    <hr/>
    <h2>Índice</h2>
    <ul>
        <li><a href="#História">História da web</a></li>
        <li><a href="#client">Conceito de client</a></li>
        <li><a href="#server">Conceito de server</a></li>
        <li><a href="#Estrutura">Estrutura básica do html<a></li>
        <li><a href="#Textos">O que são Textos</a></li>
        <li><a href="#parágrafos">O que são parágrafos</a></li>
        <li><a href="#listas">O que são Listas</a></li>
        <li><a href="#tags">O que são Tags</a></li>
        <li><a href="#links">O que são Links</a></li>
        <li><a href="#referências">Referências</a></li>
    </ul>
    <h2 id="História"> História da web</h2>
    <small><a href="#inicio">(Voltar)</a></small>
    <p>A internet surgiu a partir de um projeto de pesquisa financiado pelo Departamento de Defesa dos Estados Unidos, na década de 1960, conhecido como ARPANET (Advanced Research Projects Agency Network). O objetivo era desenvolver uma rede de computadores descentralizada que permitisse a troca de informações entre instituições acadêmicas e militares.</p>
    <p>A internet começou a se popularizar na década de 1990, quando os computadores pessoais se tornaram mais acessíveis e surgiram provedores de serviços de internet comerciais. A World Wide Web (WWW), desenvolvida por <b>Tim Berners-Lee em 1989,</b> foi um elemento crucial para a disseminação da internet. A WWW é um sistema de distribuição de informações baseado em hipertexto, permitindo que documentos e recursos fossem interligados e acessados através de navegadores.</p>
    <p>Desde então, a internet continuou a se expandir e evoluir rapidamente, conectando pessoas ao redor do mundo, transformando a comunicação, o comércio, a educação e diversos outros aspectos da sociedade. Hoje, a internet é uma rede global que conecta bilhões de dispositivos e oferece uma ampla gama de serviços e recursos online.</p>
    <h2 id="client">Conceito de client</h2>
    <small><a href="#inicio">(Voltar)</a></small>
    <p>O termo "cliente" (ou "client", em inglês) é amplamente utilizado na área de computação e redes para se referir a um dispositivo, programa ou aplicativo que solicita e recebe serviços ou recursos de um servidor.</p>
    <p>O cliente é a entidade que faz uma requisição ao servidor, buscando obter informações, acessar recursos ou realizar alguma operação específica. O cliente pode ser um computador, um dispositivo móvel, um software, um navegador da web ou qualquer outro sistema capaz de se comunicar com um servidor.</p>
    <h2 id="server">Conceito de server</h2>
    <small><a href="#inicio">(Voltar)</a></small>
    <p>O termo "servidor" (ou "server", em inglês) é amplamente utilizado na área de computação e redes para se referir a um dispositivo, programa ou aplicativo que fornece serviços, recursos ou informações para clientes.</p>
    <p>Em uma arquitetura cliente-servidor, o servidor desempenha um papel fundamental. Ele recebe as solicitações dos clientes e fornece as respostas apropriadas com base nessas solicitações. Existem diferentes tipos de servidores, alguns exemplos comuns incluem:
    <ul>
    <li>Arquivos</li>
    <li>Segurança (Firewall)</li>
    <li>E-mail</li>
    <li>Streaming</li>
    <li>Web</li>
   </ul>
   <h2 id="Estrutura">Estrutura básica do html</h2>
   <small><a href="#inicio">(Voltar)</a></small>
   <p>A estrutura básica de um documento HTML (Hypertext Markup Language). É uma linguagem de marcação padrão para criar páginas da Web. Inclui os seguintes elementos: </p>
   <img src=" https://www.juliobattisti.com.br/tutoriais/davidoliveira/frontpagebasico002_clip_image010.jpg">
   <p>
   <P> <b>Html:</b> Define o cabeçalho mais importante e todo o conteúdo da página html.</P>
   <p> <b>Head:</b> Cabeçalho, são as informações que vão ser carregadas antes de ser mostradas para o usuário.
   <p><b>Title:</b> Define o título da página, que é exibido na aba ou janela do navegador.</p>
   <p><b>Body:</b> Contém todo o conteúdo visível da página, como textos, imagens, links, tabelas, formulários e outros elementos HTML.</p>
   <h2 id="Textos"> O que são textos</h2>
   <small><a href="#inicio">(Voltar)</a></small>
   <p> Os tiutulos s são definidos com as <b>tags 'h1 até o h6'.</b></p>
   <p> Eles servem para definir títulos em uma página Web, facilitando a leitura do usuário. </p>
   <h2 id="parágrafos"> O que são parágrafos</h2> 
   <small><a href="#inicio">(Voltar)</a></small>
   <p>O parágrafo no HTML é usado para publicar texto nas páginas web.</p>
   <p>os parágrafos são definidos com a <b>tag 'p'</b> é uma tag muito básica e normalmente é a primeira tag que aprendemos na construção de páginas em HTML </p>
   <h2 id="listas">O que são listas</h2>
   <small><a href="#inicio">(Voltar)</a></small>
   <p>Listas são importantes para trazer o conteúdo mais organizado para o seu usuários, e também facilita a varredura de informações. Existem dois tipos de Listas:
   <P><b>Ordenadas tag 'ol':</b> São usadas para indicar alguma sequência ou numeração. Você também pode criar uma lista ordenada por letras, basta adicionar o atributo </P> 
   <P><b>Não Ordenadas tag 'ul':</b> As listas não numeradas são usadas para listar itens, sem se preocupar com sua sequência. Chamamos de lista de marcadores apenas.</P>
   <h2 id="tags">O que são tags</h2>
   <small><a href="#inicio">(Voltar)</a></small>
   <p> As tags são formadas por uma estrutura própria, iniciam com o sinal “menor que”, em seguida vem o nome daquele elemento e por fim, o sinal “maior que”. Podem ser dispostas em tags que precisam de fechamento e tags que fecham sozinhas (self-closing). O fechamento de uma tag será definido com uma barra (/), sendo que no caso das tags de auto fechamento, não há necessidade da presença desse caractere.</p>
   <p> As tags podem ser categorizadas inicialmente em dois tipos, em “nível de bloco” e “em linha”. Um elemento em nível de bloco ocupa toda a largura de seu elemento pai, que também chamamos de elemento container, criando assim um “bloco”. Já os elementos linha, geralmente usamos para demarcação de conteúdos de texto.</p>
   <h2 id="links">O que são links</h2>
   <small><a href="#inicio">(Voltar)</a></small>
   <p>Links são encontrados em quase todas as páginas da web. Os links permitem que os usuários cliquem de uma página para outra. Links HTML são hiperlinks, você pode clicar em um link e pular para outro documento.</p>
   <p> Um link não precisa ser texto. Um link pode ser uma imagem ou qualquer outro elemento HTML!</p>
   <p>A tag HTML <b>'a'</b> define um hiperlink.</p>
   <h2>Referências</h2>
   <p>Você pode aprender mais acessando os links:</p>
   <a href="https://www.w3schools.com/">W3Schools.com</a>
   <br> 
   <a href="https://www.youtube.com/watch?v=SV7TL0hxmIQ">youtube.com</a>
</body>
</html>
