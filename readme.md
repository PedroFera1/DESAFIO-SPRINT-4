*README.MD

Projeto Site da Ford - Desafio Front-End (FORD e SENAI CIMATEC)

Este projeto consiste em um website simples para a Ford, apresentando informações sobre um novo veículo (a Ford Ranger), com páginas para a página inicial, lançamentos e contato.
Páginas.

Index.html (Home):

-   Apresenta o logotipo da Ford e uma navegação para as páginas "Home", "Lancamento" e "Contato".-   Exibe uma imagem da Ford Ranger com um link para mais informações no website oficial da Ford Brasil.
 Lancamento.html (Lançamento)
-   Incorpora um vídeo (atualmente um placeholder do YouTube).-   Apresenta uma seção para comparar diferentes modelos da Ford Ranger:    -   XL Cabine Simples 2.2 Diesel 4x4 MT (R$ 146.200,00) com opção de seleção.    -   XLS 2.2 Diesel 4x4 AT (R$ 185.400,00) com opção de seleção.    -   Storm 3.2 Diesel 4x4 AT (R$ 220.500,00) com opção de seleção.-   Inclui um botão "Comparar modelos".

Contato.html (Contato)

-   Apresenta uma imagem da Ford Ranger XL Cabine.-   Contém um formulário de contato com os seguintes campos:    -   Nome (obrigatório)    -   E-mail (obrigatório)    -   CPF (obrigatório)    -   Sobrenome (obrigatório)    -   Telefone    -   Motivo do Contato (select com opções: Elogio, Reclamação, Solicitação - "MOTIVO DO CONTATO" como padrão desabilitado)    -   Mensagem (obrigatório, textarea)-   Um botão "Enviar" para submeter o formulário.

Elementos Comuns:

Header

-   Exibe o logotipo da Ford no canto esquerdo.-   Possui uma barra de navegação com links para "Home", "Lancamento" e "Contato".


Footer

-   Apresenta uma seção de "Redes Sociais" com links (atualmente placeholders) para Facebook, YouTube e Instagram.-   Contém uma mensagem de direitos autorais ("© 2025 Ford Motor Company. Todos os direitos reservados.").-   Exibe o logotipo da Ford.

Estilos (`/css/style.css`):

A folha de estilos `style.css` fornece a formatação visual para todas as páginas, incluindo:
-   Estilos gerais para a `body` e `html`.-   Estilização do `header` (background, padding, alinhamento, imagem, navegação).-   Estilização da `nav` (lista, links).-   Estilização do `main` (padding, flex layout para centralização).-   Estilos específicos para elementos em cada página (`#img-index`, `#video-container`, `.lancamento-destaque`, `.imagens-veiculo`, `.tabela-modelos`, `.formulario-contato`).-   Estilização do `footer` (background, cor do texto, padding, alinhamento, redes sociais).-   Media queries para responsividade em diferentes tamanhos de tela.-   Estilos adicionais para a página de contato (`.galeria`, `#Posicionamento`).-   Estilos para a seção de comparação de modelos na página de lançamento (`.comparacao`, `.modelo`, botão "Comparar").
Imagens (`/img/`)

O projeto utiliza as seguintes imagens:

-   `logo-ford-256.png`: Logotipo da Ford.-   `imagem_1.jpg`: Imagem da Ford Ranger para a página inicial.-   `ranger_2.jpg`, `ranger_3.jpg`, `ranger_1.jpg`: Imagens dos diferentes modelos da Ford Ranger para a página de lançamento.-   `facebook-50.png`, `youtube-squared-50.png`, `instagram-logo-50.png`: Ícones de redes sociais.-   `ford-96.png`: Outra versão do logotipo da Ford utilizada no rodapé.


Conhecimentos agregados


HTML e CSS Puros: Desenvolver o site exclusivamente com HTML e CSS reforçou a necessidade de uma lógica bem detalhada e organizada com  profundidade dos conhecimentos básicos.

Layout Responsivo: A tarefa de garantir que o rodapé ficasse sempre fixado na base, independentemente da quantidade de conteúdo, impulsionou a prática com técnicas avançadas de layout e posicionamento. Conectar todas as partes do site  de modo harmônico e responsivo proporcionou uma visão completa da estrutura de um site profissional, preparando o terreno para desafios futuros, como a migração para uma versão mobile com React Native.

Como Usar

Para visualizar o website, basta abrir os arquivos HTML (`index.html`, `lancamento.html`, `contato.html`) em um navegador web. Certifique-se de que a pasta `css` e a pasta `img` estejam no mesmo diretório que os arquivos HTML para que os estilos e as imagens sejam carregados corretamente.

Clone o repositório:

CONTATO:

Git http://github.com/PedroFera1/DESAFIO-SPRINT-4.git