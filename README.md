[![made Language {generic badge}](https://img.shields.io/badge/Made%20with-FIGMA%20-8A2BE2)](https://github.com/Team-Git-AI/bagaceira-games-store-ui/)
[![create date](https://badges.pufler.dev/created/Team-Git-AI/bagaceira-games-store-ui?color=8A2BE2)](https://github.com/Team-Git-AI/bagaceira-games-store-ui/)
[![last update date](https://badges.pufler.dev/Updated/Team-Git-AI/bagaceira-games-store-ui?color=8A2BE2)](https://github.com/Team-Git-AI/bagaceira-games-store-ui/)

[![contributors](https://img.shields.io/github/contributors/alanmugiwara/login-system-c?color=8A2BE2)](https://github.com/Team-Git-AI/bagaceira-games-store-ui/)
[![issues counter](https://img.shields.io/github/issues/alanmugiwara/login-system-c?color=8A2BE2)](https://github.com/Team-Git-AI/bagaceira-games-store-ui/)
[![repo size](https://img.shields.io/github/repo-size/alanmugiwara/login-system-c?color=8A2BE2)](https://github.com/Team-Git-AI/bagaceira-games-store-ui/)
[![directory size](https://img.shields.io/github/directory-file-count/alanmugiwara/login-system-c?color=8A2BE2)](https://github.com/Team-Git-AI/bagaceira-games-store-ui/)

# Bagaceira Games - Projeto de Interface e Usabilidade
Este repositório documenta o desenvolvimento do projeto "Bagaceira Games", um e-commerce focado no público gamer, como parte da disciplina de Interface e Usabilidade.

## 1. Objetos de pesquisa:
- Entregar um site de e-commerce funcional e atraente para o público gamer.
- Público alvo: Gamers de diversas plataformas, interessados em adquirir jogos digitais, DLCs e itens relacionados.
- Identificar as necessidades: Facilidade de navegação, descoberta de novos jogos (com seções como "Recomendados", "Mais Jogados"), promoções claras (descontos visíveis nos cards), processo de compra simplificado, informações detalhadas dos produtos (requisitos de sistema, mídias, avaliações), integração com plataformas de jogos (login social com Steam, PSN, Xbox, etc., como visto na tela de login), e uma interface visualmente imersiva e alinhada à cultura gamer.

## 2. Definição de Requisitos:
- **Requisitos Funcionais:**
    - Cadastro e Login de usuários (tradicional e via redes sociais/plataformas como Google, Facebook, Steam, PSN, Xbox, conforme tela de login).
    - Catálogo de jogos com filtros (categoria, preço, popularidade) e busca.
    - Página de detalhes do produto (descrição, imagens/vídeos em carrossel, requisitos de sistema, avaliações, como visto na página do Red Dead Redemption 2).
    - Carrinho de compras.
    - Processo de checkout.
    - Lista de desejos (botão "Favoritos" na página de produto).
    - Visualização de ofertas e jogos gratuitos (seção "Jogos grátis" na home).
    - Seção de perfil do usuário (histórico de compras, dados pessoais).
    - Seleção de diferentes edições do jogo (como visto na página do jogo Red Dead Redemption 2 com  versões "Standard Edition", "Ultimate Edition").
    - 
- **Requisitos Não Funcionais:**
    - Interface intuitiva e responsiva.
    - Design visualmente atraente e alinhado à estética gamer (tema predominantemente escuro, cores vibrantes como roxo e rosa, fontes com apelo pixelado/moderno, como visto nos mockups).
    - Desempenho otimizado para carregamento rápido das páginas.
    - Acessibilidade (como meta inicial).
- **Alinhar requisitos com objetivos de negócio:** Aumentar o engajamento do usuário, facilitar a conversão (compra) e construir uma marca reconhecida no nicho gamer.

## 3. Arquitetura de Informação:
- **Mapa do Site (Principais Seções):**
    - Home (com destaques, ofertas, jogos grátis, recomendados)
    - Login / Cadastro
    - Catálogo de Jogos (com filtros e busca)
        - Página de Produto (Detalhes do Jogo)
    - Carrinho
    - Checkout
    - Perfil do Usuário
        - Meus Pedidos
        - Lista de Desejos
        - Configurações da Conta
    - Ofertas (seção dedicada ou integrada na home/catálogo)
    - Jogos Grátis (seção dedicada ou integrada na home)
    - Sobre Nós
    - Suporte / FAQ

## 4. User Flow:
- **Fluxos Principais Mapeados:**
    - **Cadastro/Login:** Usuário acessa a tela de login (com logo "Bagaceira Games") -> Opta por login social (Google, Facebook, Steam, PSN, Xbox) ou preenche formulário de email/usuário e senha -> Clica em "LOGAR" -> Acessa a plataforma.
        - *Ponto de decisão:* Login social | email/senha.
    - **Navegação e Compra:** Usuário navega pela Home (com banners e seções de cards de jogos) -> Seleciona um jogo -> Visualiza detalhes do produto (tela do Red Dead Redemption 2 como exemplo) -> Adiciona ao carrinho (botão vermelho destacado) -> Procede para o carrinho -> Inicia Checkout -> Preenche dados de pagamento -> Confirma compra.
        - *Ponto de decisão:* Continuar comprando vs. ir para o carrinho; escolher edição do jogo.
    - **Adicionar à Lista de Desejos:** Usuário na página de produto -> Clica em "Favoritar" (botão com ícone de adição).

## 5. Wireframes:
- Wireframes de alta fidelidade foram criados no Figma para as telas principais, evoluindo para os mockups de alta fidelidade apresentados.
    - **Home Page:** Estrutura com banner principal ("Bagaceira Games"), seções de destaque (cards de jogos em fileiras de 4 itens, como "Os estourados do momento com desconto no talo!", "Recomendados para você", "Jogos grátis") e navegação principal (implícita no header). Sidebar direita com "Best of 2025".
    - **Página de Produto (Red Dead Redemption 2):** Layout com galeria de mídia à esquerda (com navegação por setas), informações do jogo à direita (título, preço original/promocional, botões de ação "Adicionar ao carrinho" e "Favoritos"), seguido por seções como "Versões" (com cards para Standard e Ultimate Edition), "Siga-nos", "Avaliação" (com barras de progresso), "Requisitos".
    - **Página de Login:** Layout centralizado com logo "Bagaceira Games Pixelado", título "Boas Vindas" representando linguagem inclusiva, subtítulo "Efetue seu Login", botões de login social (Google, Facebook, Steam, PlayStation, Xbox) em uma linha, campos de formulário para "Email ou Usuário" e "Senha" com ícones, checkbox "Mantenha-me conectado", botão "LOGAR" e links para "Esqueci a senha", "Termos de Serviço", "Política de Privacidade", "Política de Reembolso da Loja".
- Elementos de interface incluídos: botões (primários, secundários, sociais), campos de formulário com ícones, cards de produto com tags de desconto, navegação (principal, secundária, breadcrumbs implícitos), modais (implícito para checkout), carrossel de mídia, checkboxes, barras de progresso para avaliações.
- Princípios de hierarquia visual aplicados para guiar o usuário (tamanhos de fonte, cores de destaque, posicionamento).
- Consistência mantida entre as telas.
  
## Página do projeto no FIGMA Community:
[![Figma badge](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/community/file/1509320259054211679)

## Página do projeto no FIGMA Community:
[![Figma badge](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/community/file/1509320259054211679)

## Wireframes

Home Page:
[![home page](https://github.com/Team-Git-AI/bagaceira-games-store-ui/blob/main/src/img/01_home_page.png?raw=true)](https://github.com/Team-Git-AI/bagaceira-games-store-ui)

LoginPage:
[![cart page](https://github.com/Team-Git-AI/bagaceira-games-store-ui/blob/main/src/img/03_login_page.png?raw=true)](https://github.com/Team-Git-AI/bagaceira-games-store-ui)


Cart Page:
[![login page](https://github.com/Team-Git-AI/bagaceira-games-store-ui/blob/main/src/img/02_cart_page.png?raw=true)](https://github.com/Team-Git-AI/bagaceira-games-store-ui)


## 6. Design System:
- **Elementos Fundamentais Definidos (com base nos mockups de alta fidelidade):**
    - **Tipografia:**
        - **Principal (Títulos e Logo):** Fonte pixelada/estilizada (visível no logo "BAGACEIRA GAMES" e em alguns títulos de seção maiores).
        - **Secundária (Corpo de Texto, UI):** Fonte Sans-Serif limpa e legível (usada em botões como "Saber mais", "LOGAR", descrições, preços e menus).
    - **Cores:**
        - **Primária (Fundo Principal):** Roxo escuro (predominante nos fundos.
        - **Secundária (Destaques, CTAs):** Roxo vibrante (usado em botões de ação como "LOGAR", banners e elementos de destaque).
        - **Acento 1:** Rosa/Magenta (usado em destaques, tags de desconto, e elementos gráficos).
        - **Acento 2:** Ciano/Azul claro (usado em detalhes, promoções e elementos gráficos).
        - **Acento 3 (CTA Principal):** Vermelho/Laranja (usado no botão "Adicionar ao carrinho" na página de produto).
        - **Neutras:** Branco e tons de cinza claro para texto e ícones sobre fundos escuros). Cinza escuro para bordas e elementos secundários.
        - **Cores de Feedback:** Verde para sucesso/descontos (implícito), vermelho para erro/preço original riscado.
    - **Grid:**
        - Sistema de grid flexível, em destaque como um sistema de 12 colunas para o layout geral da página, permitindo:
            - **Home:** Listagens de jogos em 4 colunas (cards ocupando parte do container principal). Sidebar ocupando outra proporção.
            - **Página de Produto:** Layout principal em 2 colunas.
            - **Login:** Layout centralizado de coluna única para o formulário, com botões sociais dispostos horizontalmente.
        - **Espaçamentos (Gutters/Padding):** Consistentes, com margens e paddings visivelmente. definidos
    - **Iconografia:**
        - **Social/Plataformas:** Ícones originais das marcas (Google, Facebook, Steam, PSN, Xbox, Windows).
        - **UI:** Estilo limpo e moderno com contorno fino.
    - **Componentes:**
        - Botões (Primário: roxo vibrante/vermelho com texto claro; Secundário: contorno ou cor de acento; Social: com logos das plataformas).
        - Cards de Produto (com imagem de capa, título, preço original/promocional, tags de desconto).
        - Campos de Formulário (com placeholders, ícones de prefixo e bordas sutis).
        - Navegação (Tabs/Pills para edições de jogos, como "Standard Edition", "Ultimate Edition").
        - Carrossel de Mídia (com setas de navegação para imagens/vídeos).

## 7. UI Design:
- Estilo visual aplicado aos wireframes, resultando nos mockups de alta fidelidade.
- **Mockups em Alta Fidelidade (Figma):**
    - **Home Page:** Aplicação do tema escuro com destaques em roxo, rosa e ciano. Cards de jogos exibem capa, título, plataforma (implícito), preço e desconto. Banners promocionais com forte apelo visual.
        - *Imagem Referência:* [Print da Home Page já fornecido]
    - **Página de Produto (Red Dead Redemption 2):** Galeria de mídia proeminente, informações claras sobre preço e edições. Botões de CTA ("Adicionar ao carrinho", "Favoritos") bem destacados. Seções de requisitos e avaliações de fácil leitura.
        - *Imagem Referência:* [Print da Página de Produto já fornecido]
    - **Página de Login:** Logo pixelado "Bagaceira Games" em destaque. Opções de login social visualmente claras e botões grandes. Formulário tradicional limpo e direto.
        - *Imagem Referência:* [Print da Página de Login já fornecido]
    - [Link para o arquivo Figma completo ou para a apresentação dos mockups]
- **Acessibilidade Visual:** Atenção ao contraste entre texto claro (branco/cinza claro) e fundos escuros (roxo). Botões de CTA (roxo vibrante, rosa, vermelho) com texto branco parecem ter bom contraste. Tamanhos de fonte hierarquizados para legibilidade (títulos maiores, texto de corpo legível).

## 8. Especificações:
- Documentação detalhada de componentes (estados: hover, active, focus, disabled; interações) e estilos será mantida no Figma e/ou em um guia de estilo complementar.
- 
- **Guia de estilo detalhado inclui:**
    - **Tipografia:**
        - **Fonte Principal para Títulos de Alto Impacto (Login):**
            - 'Black Ops One', Regular
                - Uso: "Boas Vindas" (Login) - Tamanho: 150px
                - Uso: "Efetue seu Login" (Login) - Tamanho: 50px
        - **Fonte Principal para Títulos de Cards (Home):**
            - 'ADLaM Display', Regular
                - Uso: Títulos dos jogos nos cards da Home - Tamanho: 16px
        - **Fonte Secundária para Texto Geral e UI:**
            - 'Abel', Regular
                - Uso: Links de navegação/informação (Home - "encontrar na loja", "descobrir", "navegar", "mapa do site") - Tamanho: 12px
                - Uso: Chamadas para ação secundárias (Home - "faça sua compra agora") - Tamanho: 16px
                - Uso: Links de rodapé (Login - "Termos de Serviço", etc.) - Tamanho: 30px
        - **Fonte Secundária para Preços e Descrições:**
            - 'ABeeZee', Regular
                - Uso: Preços dos jogos nos cards da Home - Tamanho: 16px
                - Uso: Descrição principal na página de produto (RDR2 - "Vencedor de mais de 175 prêmios...") - Tamanho: 22px
                - Uso: Restante do corpo de texto na página de produto (RDR2) - Tamanho: 16px
        - **Outros Elementos Textuais (a definir com base nas fontes acima ou fontes complementares):**
            - Títulos de Seção (H2, H3)
            - Corpo de texto padrão
            - Legendas e textos menores
            - Botões e elementos de formulário
        - **Pesos:** Predominantemente 'Regular' conforme especificado. Outros pesos (Bold, Light) podem ser utilizados para hierarquia onde necessário e se disponíveis nas famílias de fontes escolhidas.
        - **Alturas de Linha (Line Height):** A ser definida para cada uso, visando ótima legibilidade. *Valores exatos devem ser verificados no Figma.*

    - **Paleta de Cores Completa (consolidada das páginas Home, Login e Produto RDR2):**
        - **Primária (Fundo Principal - visualmente inferido dos mockups):** Roxo escuro.
        - **Secundária (Destaques, CTAs principais como "LOGAR"):** Roxo.
        - **Acento 1 (Destaques secundários, tags na Home):** Rosa/Magenta.
        - **Acento 2 (Detalhes, promoções, banner Home):** Azul.
        - **Acento 3 (CTA de Compra Principal "Adicionar ao carrinho"): Vermelho .
        - **Neutras (para texto, ícones, fundos secundários, bordas):**
            - Branco:
                - `#FFFFFF` (100% opacidade - *Home, Login, RDR2*)
                - `#FFFFFF` (60% opacidade - *Home, Login, RDR2*)
                - `#FFFFFF` (10% opacidade - *Home, Login, RDR2*)
                - `#FFFFFF` (1% opacidade - *RDR2 - uso para efeitos muito sutis*)
            - Cinzas Claros:
                - `#F5F5F5` (100% opacidade - *Home, Login, RDR2 - Usado para "Icon/Neutral/On Neutral"*)
                - `#F5F5F5` (60% opacidade, 50% opacidade - *Home Page*)
                - `#E7E7E7` (100% opacidade - *Home, Login, RDR2*)
            - Cinza Médio:
                - `#CCCCCC` (100% opacidade - *Home, Login, RDR2*)
            - Fundos Escuros Alternativos / Elementos Muito Escuros:
                - `#262626` (100% opacidade - *Página Produto RDR2*)
                - `#202020` (100% opacidade - *Home Page*)
                - `#000000` (100% opacidade - *Login Page*)
        - **Feedback / Cores Específicas:**
            - Sucesso / Checkbox Ativado: Verde claro.
            - Erro/Aviso (Geral): Vermelho (pode ser um tom específico - *a definir/confirmar no Figma*).
            - Alerta (Geral): Amarelo/Laranja.
        - **Cores de Marca para Botões Sociais (Login Page):**
            - Facebook: Azul escuro.
            - Google, Steam, PlayStation, Xbox:
        *Nota: O Figma é a fonte definitiva para todos os valores hexadecimais e suas aplicações exatas em todo o sistema de design.*

    - **Espaçamentos:**
        - Sistema de espaçamento baseado em múltiplos de 4px ou 8px. A imagem da página RDR2 mostra "Spacing: 87", indicando espaçamentos específicos que podem não seguir estritamente essa regra em todos os contextos, mas o sistema base é uma boa prática.
        - **Margens e Paddings:** Aplicados consistentemente para ritmo visual e separação clara.
        - **Gutters (Grid):** Espaçamento entre colunas do grid.
        *Valores exatos para componentes reutilizáveis e layouts devem ser verificados e documentados a partir do Figma.*

    - **Bordas e Sombras:**
        - **Cards de Produto/Jogo:** `border-radius` sutil. Podem ter uma borda fina ou depender de sombra para separação.
        - **Botões:** `border-radius` sutil. Os prints mostram "Corner radius: 0" ou "Mixed" para seleções amplas, indicando que o `border-radius` é aplicado a componentes específicos e não globalmente.
        - **Campos de Formulário:** `border-radius`, borda fina em estado padrão.
        - **Sombras:** Sutis, usadas para dar profundidade a cards e elementos flutuantes.
        *Especificações exatas de `border-radius`, espessura de borda e valores de sombra para cada componente devem ser retiradas do Figma.*

    - **Uso de Iconografia:**
        - **Biblioteca de Ícones:** Preferencialmente SVGs para escalabilidade e personalização de cor.
        - **Estilos:**
            - Ícones Sociais: Logos originais das marcas.
            - Ícones de UI: Estilo consistente (sólido, contorno fino). A cor "Icon/Neutral/On Neutral" é consistentemente `#F5F5F5` nas seleções, indicando uma cor base para ícones sobre fundos neutros/escuros.
        - **Tamanhos e Cores:** Definir tamanhos padrão. Cores devem seguir a paleta.

- **Comportamentos de Componentes:**
    - **Botões:**
        - *Hover:* Leve aumento de brilho, sutil mudança de cor, ou leve sombra/elevação.
        - *Active (mousedown/touch):* Mudança de cor mais pronunciada, sutil encolhimento ou sombra interna.
        - *Focus (navegação por teclado):* Borda de foco claramente visível.
        - *Disabled:* Aparência esmaecida (opacidade reduzida, cor dessaturada), cursor `not-allowed`.
    - **Campos de Formulário (Input, Textarea):**
        - *Focus:* Borda destacada com cor de acento).
        - *Error:* Borda vermelha, possível ícone de erro e mensagem de validação próxima.
        - *Disabled:* Fundo e borda esmaecidos, texto interno cinza claro.
    - **Cards (de produto/jogo):**
        - *Hover:* Leve sombra intensificada, sutil zoom/elevação, ou borda destacada com cor de acento.
    - **Links:**
        - *Hover:* Mudança de cor, possível sublinhado.
        - *Active:* Similar ao hover, ou cor mais intensa.
        - *Focus:* Outline visível.
    - **Carrossel de Mídia:**
        - *Setas de Navegação (Hover):* Aumento de opacidade/visibilidade, mudança de cor de fundo.
    - **Checkboxes/Radio Buttons:**
        - *Hover:* Borda ou fundo do controle levemente destacado.
        - *Focus:* Outline visível ao redor do controle.
        - *Checked:* Mudança visual clara.
