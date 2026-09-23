\# Design System — Shelf Hub



\## 1. Visão Geral



O Design System do \*\*Shelf Hub\*\* define as diretrizes visuais e de interação que serão utilizadas na construção da interface da plataforma.



O objetivo é garantir uma experiência consistente, simples e agradável para organizar, acompanhar e avaliar diferentes tipos de conteúdos culturais.



A identidade visual segue uma abordagem \*\*minimalista + moderna/tech\*\*, mantendo a interface limpa para que as capas das obras sejam um dos principais elementos visuais.



Os detalhes visuais poderão ser refinados durante a implementação do front-end, conforme os componentes forem testados na prática.



\---



\# 2. Direção Visual



\## 2.1 Estilo



O Shelf Hub utilizará uma combinação de:



\* Minimalismo;

\* Design moderno;

\* Elementos sutis de tecnologia;

\* Espaçamento generoso;

\* Hierarquia visual clara;

\* Tipografia legível;

\* Uso controlado de cores;

\* Interface limpa e organizada.



A interface deve evitar excesso de elementos visuais para que as informações das obras e suas capas sejam os principais pontos de atenção.



\---



\# 3. Paleta de Cores



\## 3.1 Cores principais



\### Primária



\*\*Indigo — `#4F46E5`\*\*



Utilizada principalmente em:



\* Botões principais;

\* Links;

\* Elementos selecionados;

\* Estados de foco;

\* Ações importantes.



\### Primária escura



\*\*Indigo escuro — `#3730A3`\*\*



Utilizada para:



\* Estados de hover;

\* Destaques;

\* Elementos que precisam de maior contraste.



\### Cor de destaque



\*\*Âmbar — `#F59E0B`\*\*



Utilizada principalmente para:



\* Favoritos;

\* Avaliações;

\* Destaques;

\* Elementos que precisam chamar atenção sem representar erro.



\---



\## 3.2 Cores neutras



| Função            | Cor               | Hex       |

| ----------------- | ----------------- | --------- |

| Fundo geral       | Cinza muito claro | `#F8FAFC` |

| Cards/superfícies | Branco            | `#FFFFFF` |

| Bordas/divisores  | Cinza claro       | `#E2E8F0` |

| Texto secundário  | Cinza             | `#64748B` |

| Texto principal   | Cinza escuro      | `#0F172A` |



Os tons neutros devem ocupar a maior parte da interface, mantendo o visual leve e permitindo que as cores de ação tenham maior destaque.



\---



\# 4. Cores de Status



Os status das obras possuem cores próprias para facilitar sua identificação.



| Status       | Cor      | Hex       |

| ------------ | -------- | --------- |

| Planejado    | Azul     | `#2563EB` |

| Em andamento | Amarelo  | `#F59E0B` |

| Consumido    | Verde    | `#16A34A` |

| Abandonado   | Vermelho | `#DC2626` |



\### Significado



\* \*\*Planejado:\*\* conteúdo que o usuário pretende consumir.

\* \*\*Em andamento:\*\* conteúdo que está sendo consumido atualmente.

\* \*\*Consumido:\*\* conteúdo que foi concluído.

\* \*\*Abandonado:\*\* conteúdo que o usuário decidiu interromper.



A cor não deve ser utilizada como único indicador do status. O nome do status deve sempre estar presente para garantir melhor acessibilidade.



\---



\# 5. Tipografia



\## 5.1 Fonte principal



A fonte principal escolhida para o Shelf Hub é a \*\*Inter\*\*.



Ela será utilizada tanto em títulos quanto em textos da interface, garantindo consistência visual e boa legibilidade.



\### Aplicações



\*\*Títulos\*\*



\* Inter;

\* Peso maior;

\* Destaque visual.



\*\*Textos\*\*



\* Inter;

\* Peso regular;

\* Alta legibilidade.



\*\*Metadados\*\*



\* Inter;

\* Tamanho menor;

\* Cor secundária.



\## 5.2 Código e informações técnicas



Quando houver necessidade de apresentar código ou informações técnicas, poderá ser utilizada uma fonte monoespaçada como \*\*Fira Code\*\*.



\---



\# 6. Componentes



\## 6.1 Botões



O sistema terá quatro tipos principais de botão.



\### Primário



Utilizado para ações principais.



Exemplos:



\* Adicionar obra;

\* Salvar;

\* Cadastrar.



Características:



\* Fundo `#4F46E5`;

\* Texto branco;

\* Maior destaque visual.



\### Secundário



Utilizado para ações alternativas.



Exemplos:



\* Cancelar;

\* Voltar;

\* Outras ações de menor prioridade.



Características:



\* Fundo claro ou transparente;

\* Borda em tom neutro ou primário;

\* Menor destaque que o botão primário.



\### Destrutivo



Utilizado para ações que removem informações.



Exemplos:



\* Excluir obra;

\* Remover comentário;

\* Remover link.



Características:



\* Vermelho `#DC2626`;

\* Deve ser utilizado com confirmação quando a ação for permanente.



\### Ícone



Utilizado para ações compactas.



Exemplos:



\* Favoritar;

\* Editar;

\* Excluir;

\* Abrir detalhes.



Ações representadas apenas por ícones devem possuir identificação acessível, como tooltip ou descrição adequada.



\### Estados dos botões



Todos os botões devem considerar:



\* Default;

\* Hover;

\* Active;

\* Disabled;

\* Focus.



\---



\# 7. Campo de Busca



A pesquisa é uma funcionalidade central do Shelf Hub e terá um campo de busca de destaque na biblioteca.



\### Estrutura



\* Ícone de pesquisa;

\* Campo de texto;

\* Placeholder: \*\*"Pesquisar obras..."\*\*;

\* Opção de limpar a pesquisa quando houver conteúdo.



\### Comportamento



A pesquisa deve:



\* Permitir pesquisar pelo nome completo;

\* Permitir pesquisar por parte do nome;

\* Apresentar resultados correspondentes;

\* Informar quando nenhum resultado for encontrado;

\* Poder ser utilizada em conjunto com os filtros.



\### Estados



\* Default;

\* Focus;

\* Preenchido;

\* Sem resultados;

\* Disabled.



A barra de pesquisa deverá ficar em posição de destaque na biblioteca, antes dos filtros.



\---



\# 8. Card de Obra



O card de obra será um dos principais componentes visuais do Shelf Hub.



As capas devem ter destaque, mantendo a interface limpa.



\### Informações



O card poderá apresentar:



\* Capa;

\* Nome;

\* Tipo;

\* Gênero;

\* Status;

\* Nota, quando existir;

\* Indicador de favorito.



\### Informações que ficam fora do card



Para evitar excesso de informação, dados como:



\* Comentário;

\* Data;

\* Onde foi consumida;

\* Links externos;



serão apresentados na visualização detalhada da obra.



\### Interação



Ao selecionar um card, o usuário deve ser direcionado para os detalhes da obra.



No desktop, o hover poderá apresentar uma pequena elevação e alteração de sombra.



As microinterações devem ser sutis e não prejudicar a navegação.



\---



\# 9. Filtros



Os filtros permitem restringir os conteúdos apresentados na biblioteca.



\### Filtros disponíveis



\* Tipo;

\* Gênero;

\* Status;

\* Nota;

\* Favoritos.



O usuário poderá combinar diferentes filtros.



\### Exemplo



> Tipo: Filme

> Gênero: Terror

> Status: Consumido



O resultado deverá apresentar somente as obras que atendam aos critérios selecionados.



\### Responsividade



No desktop, os filtros poderão ser apresentados em uma área lateral ou painel expansível.



No mobile, os filtros poderão ser apresentados em um painel ou modal.



\### Sem resultados



Quando nenhum conteúdo corresponder aos filtros, o sistema deverá informar:



> \*\*Nenhuma obra encontrada.\*\*



Também deve orientar o usuário a alterar ou remover alguns filtros.



\---



\# 10. Ordenação



A biblioteca deverá permitir organizar as obras por diferentes critérios.



\### Opções



\* Mais recentes;

\* Mais antigas;

\* Maior nota;

\* Menor nota;

\* A-Z;

\* Z-A.



A ordenação deverá funcionar em conjunto com os filtros.



\### Exemplo



> Filtro: Filmes

> Ordenação: Maior nota



Nesse caso, somente os filmes serão apresentados e organizados da maior para a menor nota.



\---



\# 11. Status e Badges



Os status serão apresentados visualmente por meio de badges.



\### Exemplos



\* 🔵 \*\*Planejado\*\*

\* 🟡 \*\*Em andamento\*\*

\* 🟢 \*\*Consumido\*\*

\* 🔴 \*\*Abandonado\*\*



\### Características



Os badges deverão:



\* Possuir formato compacto;

\* Ter cantos arredondados;

\* Utilizar uma versão visual suave da cor do status;

\* Manter texto legível;

\* Apresentar sempre o nome do status.



\### Utilização



Os badges poderão aparecer em:



\* Cards;

\* Biblioteca;

\* Detalhes da obra;

\* Filtros.



A cor não será utilizada isoladamente para representar o status.



\---



\# 12. Avaliação por Estrelas



O Shelf Hub utilizará um sistema de avaliação por estrelas.



\### Cores



\*\*Estrela selecionada\*\*



`#F59E0B`



\*\*Estrela não selecionada\*\*



`#CBD5E1`



\### Regras



\* A avaliação só estará disponível após a obra ser consumida;

\* O usuário poderá alterar sua avaliação;

\* Obras sem avaliação não receberão uma nota automaticamente;

\* A nota poderá ser utilizada nos filtros e na ordenação;

\* A nota também será utilizada nas estatísticas do usuário.



\---



\# 13. Favoritos



O recurso de favoritos permitirá destacar obras importantes para o usuário.



\### Representação



O favorito poderá ser representado por um ícone de estrela.



\### Regras



\* O usuário poderá favoritar uma obra;

\* O usuário poderá remover uma obra dos favoritos;

\* Cada usuário poderá possuir no máximo \*\*20 favoritos\*\*;

\* O estado de favorito deve ser identificado no card e nos detalhes;

\* Favoritos poderão ser utilizados como filtro.



A cor de destaque dos favoritos será o \*\*Âmbar `#F59E0B`\*\*.



\---



\# 14. Navegação



A navegação deverá ser simples e consistente.



A interface poderá utilizar:



\* Abas;

\* Sidebar;

\* Navegação responsiva.



A estrutura definitiva poderá ser refinada durante a criação do protótipo no Figma e posteriormente durante a implementação.



O objetivo é facilitar o acesso principalmente às áreas de:



\* Biblioteca;

\* Pesquisa;

\* Estatísticas;

\* Cadastro de obra.



\---



\# 15. Responsividade



O Shelf Hub seguirá uma abordagem \*\*mobile-first\*\*.



A interface deverá se adaptar a:



\* Smartphones;

\* Tablets;

\* Desktops.



Os componentes devem manter suas funções e hierarquia visual independentemente do tamanho da tela.



Elementos como filtros, navegação e cards poderão alterar sua disposição conforme o espaço disponível.



\---



\# 16. Acessibilidade



A acessibilidade será considerada desde o desenvolvimento inicial.



\### Diretrizes



\* Contraste mínimo recomendado de \*\*4.5:1\*\* para textos;

\* Cores não devem ser o único meio de transmitir informação;

\* Botões e elementos interativos devem possuir estados de foco;

\* Ícones utilizados em ações devem possuir identificação adequada;

\* Textos devem manter boa legibilidade;

\* Componentes devem ser utilizáveis em diferentes tamanhos de tela.



\---



\# 17. Princípios de UX



O Shelf Hub seguirá os seguintes princípios:



\### Hierarquia visual



As informações mais importantes devem receber maior destaque.



As capas das obras devem ser um dos principais elementos visuais.



\### Consistência



Componentes e padrões de interação devem funcionar de maneira semelhante em diferentes áreas do sistema.



\### Simplicidade



A interface deve evitar informações ou elementos desnecessários.



\### Feedback



Ações como cadastrar, editar, excluir, favoritar e alterar status devem fornecer uma indicação clara de que foram realizadas.



\### Microinterações



Animações e transições devem ser sutis e utilizadas apenas quando ajudarem a comunicar uma ação ou mudança de estado.



\### Responsividade



A experiência deve permanecer funcional e organizada em diferentes tamanhos de tela.



\### Acessibilidade



A interface deve considerar diferentes necessidades de interação e leitura.



\---



\# 18. Aplicação no MVP



Os componentes e padrões definidos neste documento deverão atender principalmente às funcionalidades do MVP:



\* Cadastro de obras;

\* Edição;

\* Exclusão;

\* Alteração de status;

\* Biblioteca;

\* Pesquisa;

\* Filtros;

\* Ordenação;

\* Visualização de detalhes;

\* Favoritos;

\* Avaliação;

\* Comentários;

\* Links externos;

\* Estatísticas.



\---



\# 19. Evolução do Design System



Este documento representa a primeira versão do Design System do Shelf Hub.



Durante a criação do protótipo no Figma e posteriormente durante o desenvolvimento do front-end, os componentes poderão ser refinados com base em testes práticos.



Poderão ser definidos posteriormente:



\* Tamanhos exatos dos componentes;

\* Espaçamentos;

\* Grid;

\* Bordas e raios;

\* Sombras;

\* Escalas tipográficas;

\* Versões detalhadas dos estados;

\* Componentes adicionais;

\* Tokens de design;

\* Variações para diferentes dispositivos.



Esses ajustes não alteram a direção visual definida neste documento.



\---



\# 20. Resumo da identidade



\*\*Estilo:\*\* Minimalista + Moderno/Tech



\*\*Fonte principal:\*\* Inter



\*\*Cor primária:\*\* Indigo `#4F46E5`



\*\*Cor de destaque:\*\* Âmbar `#F59E0B`



\*\*Status:\*\*



\* Planejado — `#2563EB`

\* Em andamento — `#F59E0B`

\* Consumido — `#16A34A`

\* Abandonado — `#DC2626`



\*\*Princípios:\*\* simplicidade, consistência, hierarquia visual, feedback, responsividade e acessibilidade.



O Design System será utilizado como referência para a criação do protótipo no Figma e para a futura implementação do front-end.



