Implementação da Seção de Cabines

## Objetivo
Desenvolver a Seção 05 ("Cabines para Todos os Gostos"), apresentando a introdução textual explicativa e a lista vertical com os três principais tipos de acomodação em cards estilizados na cor coral[cite: 1].

## Instruções Detalhadas para Execução

1. **Estrutura HTML**:
   * Crie a seção com `<section class="cabins-section">`[cite: 1].
   * Insira o bloco de introdução (`.cabins-intro`) com o título principal e o parágrafo descritivo sobre a variedade de cabines do MSC Divina[cite: 1].
   * Crie a lista de cabines (`.cabins-list`) contendo três artigos (`.cabin-card`):
     1. **Cabine Interna**: "PARA QUEM QUER CURTIR CADA MINUTO DA FESTA E SÓ VAI PRA CABINE DORMIR.. UM POUQUINHO."[cite: 1]
     2. **Externa Experience**: "PRA QUEM QUER CONFORTO PREMIUM E UMA EXPERIÊNCIA ALL INCLUSIVE."[cite: 1]
     3. **Yacht Club**: "DESCUBRA UM IATE DENTRO DE UM NAVIO..."[cite: 1]
   * Cada card deve possuir um botão interno `.cabin-button` com o texto "COMPRAR CABINE" e uma seta indicativa (`➜`)[cite: 1].

2. **Estilização CSS**:
   * Configure os cards `.cabin-card` utilizando o fundo coral (`--blue-primary` nos títulos internos e texto descritivo em branco em caixa alta)[cite: 1].
   * Estilize os títulos dos cards com a fonte `HDColton`, peso 500, tamanho responsivo `clamp(28px, 4vw, 44px)` e caixa alta[cite: 1].
   * Estilize o botão `.cabin-button` com fundo transparente, sem bordas, cor `--blue-primary`, peso 800, sem preenchimento excessivo, parecendo integrado ao design tipográfico do card[cite: 1].

## Critério de Conclusão
Os três cards de cabines aparecem empilhados verticalmente com o fundo coral característico, tipografia pesada em caixa alta e botões de compra integrados sem sombras excessivas[cite: 1].