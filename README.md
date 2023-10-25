# DevLinks

## Descrição
Este é o código-fonte de uma página web chamada "DevLinks". A página é projetada para apresentar links e informações de perfil de um desenvolvedor chamado Mayk Brito. A página inclui um sistema de alternância de modo claro/escuro e links para suas redes sociais, bem como links para se inscrever em um evento chamado NLW, baixar um e-book e conhecer o Explorer da Rocketseat.

## Estrutura do Código
O código-fonte é escrito em HTML e CSS, com um toque de JavaScript para a funcionalidade de alternância de modo claro/escuro.

### HTML
O HTML define a estrutura da página e inclui os seguintes elementos:

- Tags `<head>` que contêm links para fontes e configurações de metadados.
- Um `<title>` que define o título da página como "DevLinks".
- Uma referência a um arquivo CSS chamado "style.css".
- Um corpo `<body>` que contém o conteúdo da página, incluindo informações de perfil, links e rodapé.
- O corpo inclui uma série de elementos, como imagens, links para redes sociais e um botão para alternar o modo claro/escuro.
- Inclui também uma referência a dois arquivos JavaScript para lidar com a funcionalidade de alternância de modo.

### CSS
O CSS define a aparência da página e utiliza variáveis CSS personalizadas para definir as cores e estilos do modo claro e escuro. Alguns pontos-chave incluem:

- Definição de variáveis CSS para controlar cores, imagens de fundo e outros estilos.
- Estilos para o corpo da página, incluindo a imagem de fundo e as cores do texto.
- Estilos para elementos como o perfil, botão de alternância e links.
- Animações CSS para o botão de alternância.

### JavaScript
O JavaScript fornece a funcionalidade de alternância de modo claro/escuro. A função `toggleMode()` é chamada quando o botão de alternância é clicado e atualiza as classes CSS no elemento HTML para alternar entre os estilos claro e escuro, bem como trocar a imagem do perfil.

## Modo Claro/Modo Escuro
A página permite que os usuários alternem entre o modo claro e escuro, o que afeta a aparência e as cores. O botão de alternância na parte superior direita da página ativa a função `toggleMode()` em JavaScript, que faz as seguintes alterações:

- Altera a classe do elemento raiz HTML para alternar entre as configurações de estilo claro e escuro.
- Troca a imagem do perfil entre uma versão clara e escura.

## Autor
Este código foi criado por [Rikhardie](https://github.com/Rikhardie) insipirado por [Mayk Brito](https://github.com/maykbrito).

## Recursos
- [Inter Font](https://fonts.google.com/specimen/Inter)
- [Ionicons](https://ionicons.com/)
- Imagens utilizadas no projeto (localmente) encontram-se em `/assets`.

## Agradecimentos
Esta página foi criada com carinho pela equipe da [Rocketseat](https://rocketseat.com.br/). 

Divirta-se explorando os links e aproveite o conteúdo!