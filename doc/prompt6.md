Implementação da Seção MSC Divina (Navio e Galeria)

## Objetivo
Construir a Seção 04 dedicada ao navio "MSC Divina", exibindo o título principal em amarelo, o subtítulo "PELA PRIMEIRA VEZ NO BRASIL" em branco, uma galeria fotográfica em grade de 6 imagens e o CTA final "CONHEÇA ESSA OBRA-PRIMA"[cite: 1].

## Instruções Detalhadas para Execução

1. **Estrutura HTML**:
   * Crie a seção `<section class="ship-section">` com fundo azul principal (`--blue-primary`)[cite: 1].
   * Adicione o cabeçalho com o título e subtítulo[cite: 1]:
     ```html
     <header class="ship-heading">
         <h2>MSC DIVINA</h2>
         <h3>PELA PRIMEIRA VEZ NO BRASIL</h3>
     </header>
     ```
   * Crie a galeria `.ship-gallery` contendo 6 imagens em `assets/navio/` (de `01.jpg` a `06.jpg`)[cite: 1].
   * Adicione os indicadores visuais estáticos da galeria (`.gallery-indicators`) e o botão de CTA: `<div class="ship-cta">CONHEÇA ESSA OBRA-PRIMA</div>`[cite: 1].

2. **Estilização CSS**:
   * Estilize o título em amarelo e o subtítulo em branco, ambos em caixa alta e com alta escala tipográfica[cite: 1].
   * Configure `.ship-gallery` utilizando CSS Grid com `grid-template-columns: repeat(3, 1fr)` e gap de `7px`[cite: 1].
   * Defina a proporção das imagens da galeria com `aspect-ratio: 16 / 9` e `object-fit: cover`[cite: 1].

## Critério de Conclusão
A seção apresenta o navio com títulos imponentes, uma galeria organizada em formato de grade 3x2 com proporção de tela panorâmica e o botão de chamada final[cite: 1].