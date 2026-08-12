Implementação do Bloco de Confiança e Segurança

## Objetivo
Desenvolver a o section com fundo totalmente branco, estruturada em uma grade de 4 colunas para exibir os selos de confiabilidade, segurança SSL, liderança em cruzeiros temáticos, facilidade de parcelamento e suporte via WhatsApp[cite: 1].

## Instruções Detalhadas para Execução

1. **Estrutura HTML**:
   * Crie a seção `<section class="trust-section">` contendo quatro artigos (`.trust-item`)[cite: 1]:
     1. **Item 01**: Ícone (globo/escudo), Título: "Site 100% Seguro", Descrição: "SSL Criptografado"[cite: 1].
     2. **Item 02**: Ícone (âncora), Título: "Empresa líder em cruzeiros temáticos", Descrição: "+ de 100 Edições"[cite: 1].
     3. **Item 03**: Ícone (cartão), Título: "Parcele com seu cartão", Descrição: "em até 12x"[cite: 1].
     4. **Item 04**: Ícone (WhatsApp), Título: "Atendimento humano", Descrição: "via WhatsApp"[cite: 1].

2. **Estilização CSS**:
   * Configure `.trust-section` com fundo branco, preenchimento de `70px 20px` e grade CSS (`grid-template-columns: repeat(4, 1fr)`) com gap de `45px`[cite: 1].
   * Estilize os ícones (`.trust-icon`) com dimensões de `64x64px`, centralizados e coloridos em amarelo (`--yellow`)[cite: 1].
   * Defina a tipografia dos títulos e subtítulos com a fonte `HDColton` e cor `--blue-dark`[cite: 1].
   * **Responsividade Mobile**: No breakpoint `@media (max-width: 767px)`, altere a grade para `grid-template-columns: 1fr` com espaçamento vertical ampliado[cite: 1].

## Critério de Conclusão
Os quatro blocos de confiança aparecem organizados de forma limpa sobre fundo branco, com ícones amarelos em destaque e textos institucionais perfeitamente legíveis[cite: 1].