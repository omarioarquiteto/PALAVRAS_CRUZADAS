# Palavras Cruzadas

Jogo de palavras cruzadas em português, inspirado no visual clássico dos passatempos impressos.

## Como jogar

1. Abra o arquivo `index.html` em um navegador moderno.
2. Escolha a dificuldade: **Fácil**, **Médio** ou **Difícil**.
3. Clique em uma pista horizontal ou vertical e digite as letras nos quadrinhos.
4. Use **Conferir respostas**, **Revelar palavra**, **Limpar** e **Novo diagrama** quando precisar.

## Recursos

- Interface responsiva para computador e celular, com grade dimensionada para toque em telas pequenas.
- Botão **Tela cheia** para aproveitar melhor a tela; em navegadores compatíveis usa o modo de tela cheia do sistema, com alternativa visual quando essa API não está disponível.
- Layout adaptado para orientação retrato e paisagem.
- Diagramas gerados aleatoriamente a cada nova partida.
- Três níveis de dificuldade, com quantidade e comprimento de palavras diferentes.
- Destaque visual da palavra selecionada e foco automático na primeira célula ao escolher uma pista.
- Navegação por setas do teclado e alternância entre horizontal/vertical com Enter nos cruzamentos.
- Conferência com destaque visual de letras corretas e incorretas; revelação da palavra selecionada e limpeza da partida.
- Banco local com mais de **1.700 entradas** de vocabulário e plurais comuns gerados automaticamente, com respostas normalizadas sem acentos.
- Não exige instalação, conta, servidor ou bibliotecas externas.

## Executar

É um site estático: basta abrir `index.html`. Para publicar com GitHub Pages, entre em **Settings → Pages** e selecione a branch `main` e a pasta `/(root)` como origem. O GitHub Pages publica arquivos HTML estáticos do repositório; a publicação pode levar alguns minutos.

## Observação sobre as pistas

As palavras principais possuem pistas descritivas, e os plurais gerados recebem pistas do tipo “Plural de …”. Parte do vocabulário adicional ainda usa uma pista genérica; revisar e enriquecer essas pistas editorialmente continua sendo uma melhoria importante.
