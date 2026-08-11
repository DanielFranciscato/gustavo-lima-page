# Prompt 3: Implementação da Seção Hero e Faixa de CTA "COMPRE SUA CABINE"

## Objetivo
Desenvolver a Seção 01 (Hero) com a grande imagem promocional do evento e o CTA correspondente, seguida imediatamente pela faixa azul de destaque "COMPRE SUA CABINE", mantendo a identidade visual náutica de alto impacto[cite: 1].

## Instruções Detalhadas para Execução

1. **Estrutura HTML da Seção Hero**:
   * Crie a seção dentro do `<main>` utilizando `<section class="hero">`[cite: 1].
   * Insira a estrutura de mídia com a imagem principal do evento (`assets/hero/hero.jpg`) e um container para elementos textuais adicionais caso não estejam fundidos na arte[cite: 1].

2. **Estilização CSS da Seção Hero**:
   * Configure `.hero` com `position: relative` e `overflow: hidden`[cite: 1].
   * Garanta que a imagem hero ocupe `width: 100%` com altura automática (`height: auto`), evitando cortes indesejados (`object-fit: cover` desnecessário se comprometer a arte)[cite: 1].
   * Estilize o botão de CTA interno (`.hero-cta`) com display `inline-flex`, altura mínima de `48px`, preenchimento de `10px 34px`, fundo `--aqua`, texto cor `--blue-dark`, fonte `HDColton` pesada (weight 700), caixa alta, bordas arredondadas de `28px` e borda sutil de `2px solid rgba(255,255,255,.25)`[cite: 1].

3. **Estrutura HTML e CSS da Faixa de CTA (`.purchase-strip`)**:
   * Crie logo abaixo da hero a faixa promocional: `<section class="purchase-strip">COMPRE SUA CABINE</section>`[cite: 1].
   * Estilize com altura mínima de `54px`, centralização flexível, fundo `--blue-primary`, cor de texto `--yellow`, fonte `HDColton` pesada (weight 800), tamanho responsivo utilizando `clamp(20px, 3vw, 32px)` e texto em caixa alta[cite: 1].

## Critério de Conclusão
A seção hero exibe corretamente a arte principal com seu botão de chamada integrado, acompanhada pela faixa azul de alta visibilidade com os dizeres "COMPRE SUA CABINE" em amarelo forte[cite: 1].