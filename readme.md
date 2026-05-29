githttps://matheusbobsin.github.io/Ap2-Boostrap-Front-End/

**Por que escolhi esse tema?**
Eu decidi fazer um site de receitas porque acho um assunto bem visual e legal de estruturar. O nome do portal ficou "Sabores do Mundo" e o foco dele é mostrar um catálogo limpo e bonito de pratos usando fotos reais.

**Como organizei as páginas do site:**
Para cumprir a regra de ter pelo menos três páginas interligadas, criei três arquivos HTML e conectei um ao outro pelos links do menu:

`index.html`:  É a página inicial do site. Coloquei um banner bem grande com a foto de uma pizza e um texto de boas-vindas chamando a pessoa para explorar o catálogo.

`galeria.html`: É onde o catálogo de receitas acontece de verdade. Ali dentro ficam os cartões com as fotos e descrições dos pratos (coloquei Pizza, Panqueca e Lasanha).

`contato.html`: Criei uma página limpa com um formulário focado para o usuário sugerir novas receitas para o portal.

Também tomei o cuidado de não usar tags genéricas (como ficar espalhando <div> para todo lado). Usei as tags semânticas do HTML5 para deixar o código bem organizado: <header> no topo do menu, <nav> para a navegação, <main> para o miolo da página, <section> para separar os blocos, <footer> no rodapé e <small> para os direitos autorais. Cada receita da galeria foi envelopada em uma tag <article> para o navegador entender que cada prato é um conteúdo único.

**Componentes que usei no layout:**
**Offcanvas** (O menu lateral): Configurei o menu lateral usando apenas regras de CSS puro por trás (com o alvo :target). O visual ficou ótimo, abrindo e fechando na hora do clique e deixando o topo limpo.

**Cards**: Usei para fazer os quadradinhos brancos com sombra da galeria de receitas e também para emoldurar o formulário de contato.

**Badges**: São os crachás pequenos em cima do tempo de preparo para mostrar se a receita é "Fácil" ou "Médio".

**Formulários***: Usei as classes de formulário para deixar as caixas de texto de Nome, E-mail e Mensagem alinhadas, com cantos arredondados e fáceis de preencher.

**List Group**: Usei para criar e empilhar a lista de links que fica dentro do menu lateral.

**Como resolvi o design, o Flexbox e a Responsividade:**
Para o visual, escolhi cores que lembram culinária: usei um tom de vinho escuro (`#8b263e`) no topo e no rodapé, e os botões e detalhes importantes ganharam um tom dourado (`#ffca3a`) para chamar a atenção. O fundo do site ficou bem clarinho para a leitura ser confortável.

O site é 100% responsivo. Se você abrir no celular, o banner e o formulário ocupam a tela inteira de um jeito confortável para o dedo. Se abrir no computador, eles encolhem para o meio para não ficarem esticados. Para fazer o catálogo de receitas funcionar desse jeito, usei o Display Flex do Bootstrap (**.d-flex**, **.flex-wrap** e **.justify-content-center**). Desse jeito, os cards de receitas ficam um do lado do outro no monitor do computador e quebram para a linha de baixo sozinhos se você abrir o site em uma tela menor, mantendo tudo centralizado e organizado.
