---
version: alpha
name: ActionPay-design-system-blue
description: Interface escura e energética para a ActionPay, plataforma de afiliados e performance. Esta variação preserva o sistema original e substitui a cor de destaque original por azul (#0059a8), mantendo a tipografia, os componentes, os espaçamentos e os estados semânticos.

colors:
  primary: "#0059a8"
  primary-active: "#00427d"
  primary-disabled: "#27455f"
  primary-glow: "#398ad1"
  ember: "#003f78"
  ember-deep: "#002442"
  ink: "#ffffff"
  body: "#d9d9d9"
  body-strong: "#f2f2f2"
  muted: "#8a8a8a"
  muted-soft: "#5f5f5f"
  hairline: "#2a2a2a"
  hairline-soft: "#202020"
  canvas: "#0d0d0d"
  surface-soft: "#141414"
  surface-card: "#1a1a1a"
  surface-card-elevated: "#222222"
  surface-light: "#ffffff"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  on-dark-soft: "#a8a8a8"
  success: "#4caf50"
  warning: "#e8a02a"
  error: "#e5484d"

typography:
  display-xl:
    fontFamily: "Sora, Outfit, Manrope, sans-serif"
    fontSize: 64px
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: -1.5px
  display-lg:
    fontFamily: "Sora, Outfit, Manrope, sans-serif"
    fontSize: 48px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -1px
  display-md:
    fontFamily: "Sora, Outfit, Manrope, sans-serif"
    fontSize: 36px
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: -0.5px
  display-sm:
    fontFamily: "Sora, Outfit, Manrope, sans-serif"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.3px
  stat-xl:
    fontFamily: "Sora, Outfit, Manrope, sans-serif"
    fontSize: 40px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.5px
  stat-md:
    fontFamily: "Sora, Outfit, Manrope, sans-serif"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: -0.3px
  title-lg:
    fontFamily: "Manrope, Inter, sans-serif"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: 0
  title-md:
    fontFamily: "Manrope, Inter, sans-serif"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 0
  title-sm:
    fontFamily: "Manrope, Inter, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 0
  body-md:
    fontFamily: "Manrope, Inter, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-sm:
    fontFamily: "Manrope, Inter, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  caption:
    fontFamily: "Manrope, Inter, sans-serif"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  caption-uppercase:
    fontFamily: "Manrope, Inter, sans-serif"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 1.5px
  button:
    fontFamily: "Manrope, Inter, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: 0
  nav-link:
    fontFamily: "Manrope, Inter, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0

rounded:
  xs: 4px
  sm: 6px
  md: 10px
  lg: 14px
  xl: 20px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 96px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 12px 22px
    height: 44px
  button-primary-active:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
  button-primary-disabled:
    backgroundColor: "{colors.primary-disabled}"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 12px 22px
    height: 44px
  button-text-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
  button-icon-circular:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    size: 48px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 72px
  hero-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-xl}"
    padding: 96px
  hero-title-accent:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.display-xl}"
  hero-product-card:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
  feature-item:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    padding: 12px 0
  feature-icon-ring:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    size: 56px
  feature-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  stat-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.stat-md}"
    rounded: "{rounded.lg}"
    padding: 20px
  stat-card-featured:
    backgroundColor: "{colors.surface-card-elevated}"
    textColor: "{colors.ink}"
    typography: "{typography.stat-xl}"
    rounded: "{rounded.lg}"
    padding: 24px
  chart-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
    rounded: "{rounded.lg}"
    padding: 24px
  pricing-tier-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-lg}"
    rounded: "{rounded.lg}"
    padding: 32px
  pricing-tier-card-featured:
    backgroundColor: "{colors.surface-card-elevated}"
    textColor: "{colors.ink}"
    typography: "{typography.title-lg}"
    rounded: "{rounded.lg}"
    padding: 32px
  callout-card-blue:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  text-input:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: 10px 14px
    height: 44px
  text-input-focused:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
  category-tab:
    backgroundColor: transparent
    textColor: "{colors.muted}"
    typography: "{typography.nav-link}"
    padding: 8px 14px
    rounded: "{rounded.md}"
  category-tab-active:
    backgroundColor: "{colors.surface-card-elevated}"
    textColor: "{colors.primary}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.md}"
  badge-pill:
    backgroundColor: "{colors.surface-card-elevated}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  badge-blue:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.caption-uppercase}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  badge-trend-up:
    backgroundColor: transparent
    textColor: "{colors.success}"
    typography: "{typography.caption}"
  cta-band-blue:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.display-sm}"
    rounded: "{rounded.lg}"
    padding: 64px
  cta-band-glow:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-sm}"
    rounded: "{rounded.lg}"
    padding: 64px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark-soft}"
    typography: "{typography.body-sm}"
    padding: 64px
---

## Overview

A ActionPay é uma interface de **tecnologia que gera dinheiro**: escura, direta e energética. A base é um **preto quente** (`{colors.canvas}` — #0d0d0d), nunca um preto puro, com um **brilho azul radial** nos cantos e na base que parece luz saindo da tela. Os títulos usam uma **sans geométrica arredondada** (Sora / Outfit / Manrope) em peso semibold com espaçamento negativo, e a ênfase vem da **alternância entre branco e azul** dentro do mesmo título.

A tensão da marca vem do **par preto + azul**. O azul (`{colors.primary}` — #0059a8) é o único destaque: aparece no "pay" do logo, na segunda linha de cada título, nos ícones, nos separadores, nos botões e na seta ascendente. Branco cuida da leitura, cinza dá apoio e verde existe apenas para sinalizar números que subiram.

O sistema tem três modos de superfície que se alternam:
1. **Canvas preto quente** (`{colors.canvas}`) — fundo padrão, com brilho azul opcional
2. **Cards grafite** (`{colors.surface-card}`) — painéis de dados, gráficos e recursos
3. **Faixa azul** (`{colors.primary}`) — chamadas de ação em largura total

**Características principais:**
- Preto quente com brilho azul em gradiente radial e textura de pontos no canto superior. Profundidade sem poluição.
- Um único azul vibrante. Os tons de brasa (`{colors.ember}`, `{colors.ember-deep}`) só aparecem como degradês do azul se apagando no preto.
- Títulos em duas cores: ideia em branco peso regular, resultado em azul peso semibold.
- Cards grafite com borda quase invisível, que separam camadas sem sombra.
- Números grandes e legíveis (`{typography.stat-xl}`) como protagonistas, com indicador verde de variação.
- Ícones de linha fina em azul dentro de anéis com contorno.
- Seta ascendente grande em azul como símbolo de crescimento.
- Raios hierárquicos: `{rounded.md}` (10px) para botões e inputs, `{rounded.lg}` (14px) para cards, `{rounded.xl}` (20px) para o mockup do hero, `{rounded.pill}` para badges.

## Colors

### Marca e destaque
- **Azul / Primary** (`{colors.primary}` — #0059a8): cor de marca. Botões primários, palavras de destaque, ícones, linhas divisórias, seta e gráficos.
- **Azul ativo** (`{colors.primary-active}` — #00427d): estado de pressão e sombra da seta.
- **Azul brilho** (`{colors.primary-glow}` — #398ad1): ponto mais claro de gradientes e marcadores de gráfico.
- **Azul desabilitado** (`{colors.primary-disabled}` — #27455f): botão inativo, azul apagado sobre o escuro.
- **Brasa** (`{colors.ember}` — #003f78) e **Brasa profunda** (`{colors.ember-deep}` — #002442): a cor "azul-escura" que nasce quando o azul se mistura ao preto. Usadas em degradês de gráficos de área e no brilho de fundo. Nunca como cor sólida de componente.

### Superfícies
- **Canvas** (`{colors.canvas}` — #0d0d0d): piso padrão da página.
- **Surface Soft** (`{colors.surface-soft}` — #141414): faixas e áreas levemente elevadas.
- **Surface Card** (`{colors.surface-card}` — #1a1a1a): cards de dados, recursos e preços.
- **Surface Card Elevated** (`{colors.surface-card-elevated}` — #222222): cards em destaque, aba ativa, badges.
- **Hairline** (`{colors.hairline}` — #2a2a2a): borda de 1px nos cards. Sutil, quase imperceptível.
- **Hairline Soft** (`{colors.hairline-soft}` — #202020): divisor dentro da mesma faixa.
- **Surface Light** (`{colors.surface-light}` — #ffffff): uso raro, apenas para botão invertido sobre faixa azul.

### Texto
- **Ink** (`{colors.ink}` — #ffffff): títulos e texto principal.
- **Body Strong** (`{colors.body-strong}` — #f2f2f2): parágrafos de destaque.
- **Body** (`{colors.body}` — #d9d9d9): texto corrido.
- **Muted** (`{colors.muted}` — #8a8a8a): legendas e rótulos secundários, como "Ganhos do período".
- **Muted Soft** (`{colors.muted-soft}` — #5f5f5f): fine print e linhas de gráfico em segundo plano.
- **On Primary** (`{colors.on-primary}` — #0d0d0d): texto sobre azul. Branco, para garantir contraste sobre a cor de destaque.
- **On Dark Soft** (`{colors.on-dark-soft}` — #a8a8a8): texto do rodapé.

### Semânticas
- **Success** (`{colors.success}` — #4caf50): variações positivas (↑ 32,5%). Cor funcional, nunca de marca.
- **Warning** (`{colors.warning}` — #e8a02a): alertas raros.
- **Error** (`{colors.error}` — #e5484d): erros de validação e variações negativas.

## Typography

### Famílias
**Sora** (ou **Outfit** / **Manrope** como substitutas) é a sans geométrica arredondada para títulos e números. **Manrope** (ou **Inter**) cuida de corpo, navegação e rótulos. Fallback: `Sora, Outfit, Manrope, -apple-system, "Segoe UI", sans-serif`.

### Hierarquia

| Token | Tamanho | Peso | Altura de linha | Espaçamento | Uso |
|---|---|---|---|---|---|
| `{typography.display-xl}` | 64px | 600 | 1.05 | -1.5px | H1 do hero ("Mais oportunidades. Mais resultados.") |
| `{typography.display-lg}` | 48px | 600 | 1.1 | -1px | Títulos de seção |
| `{typography.display-md}` | 36px | 600 | 1.15 | -0.5px | Subtítulos |
| `{typography.display-sm}` | 28px | 600 | 1.2 | -0.3px | Chamadas de faixa, nomes de plano |
| `{typography.stat-xl}` | 40px | 600 | 1.1 | -0.5px | Número principal ("R$ 28.540,00") |
| `{typography.stat-md}` | 28px | 600 | 1.15 | -0.3px | Números de cards secundários (cliques, conversões) |
| `{typography.title-lg}` | 22px | 600 | 1.3 | 0 | Nome do plano |
| `{typography.title-md}` | 18px | 600 | 1.4 | 0 | Itens de lista de recursos |
| `{typography.title-sm}` | 16px | 600 | 1.4 | 0 | Títulos de card de gráfico |
| `{typography.body-md}` | 16px | 400 | 1.55 | 0 | Texto corrido |
| `{typography.body-sm}` | 14px | 400 | 1.55 | 0 | Rodapé e fine print |
| `{typography.caption}` | 13px | 500 | 1.4 | 0 | Legendas, indicadores de variação |
| `{typography.caption-uppercase}` | 12px | 600 | 1.4 | 1.5px | Tags "NOVO" |
| `{typography.button}` | 14px | 600 | 1.0 | 0 | Botões |
| `{typography.nav-link}` | 14px | 500 | 1.4 | 0 | Menu |

### Princípios
**Título em duas cores, dois pesos.** A primeira linha vai em branco, peso 400 a 500. A segunda vai em azul, peso 600. O olho lê a ideia e pousa no resultado. O mesmo vale para o logotipo: `action` em branco, `pay` em azul, sempre em minúsculas.

Espaçamento negativo nos títulos é obrigatório. Números de dashboard usam peso 600 e tamanho grande: são os heróis visuais. Nunca use serifa nem fonte condensada.

## Layout

### Espaçamento
- **Unidade base:** 4px.
- **Tokens:** `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.section}` 96px.
- **Padding de seção:** 96px.
- **Padding interno:** 32px em cards de recurso e preço; 20px a 24px em cards de dados.

### Grid e container
- **Largura máxima:** ~1200px centralizada.
- **Hero:** divisão 5/7. Texto e lista de recursos à esquerda, mockup do produto à direita, levemente inclinado e sangrando para fora da borda.
- **Lista de recursos:** coluna única, ícone em anel + texto, separados por 16px.
- **Cards de dados:** 3 colunas no desktop, 1 no mobile.

### Filosofia de espaço
Muito preto ao redor, pouco conteúdo por vez. O vazio escuro faz o azul e o branco parecerem luz. Os respiros entre faixas são uniformes (96px).

## Elevation & Depth

| Nível | Tratamento | Uso |
|---|---|---|
| Plano | Sem sombra, sem borda | Seções, nav, hero |
| Hairline | Borda 1px `{colors.hairline}` | Cards, inputs |
| Card grafite | Fundo `{colors.surface-card}` | Painéis de dados |
| Card elevado | Fundo `{colors.surface-card-elevated}` | Número principal, plano em destaque |
| Brilho azul | Gradiente radial `{colors.primary}` → `{colors.ember-deep}` → transparente | Cantos e base do hero, atrás do mockup |

A profundidade vem do **brilho** e da diferença de tons de cinza, não de sombras. Sombras ficam reservadas à seta e ao mockup, em preto de baixa opacidade.

### Profundidade decorativa
- **Brilho radial azul** no canto inferior ou lateral, como luz vazando.
- **Textura de pontos** no canto superior direito, em `{colors.primary}` com 15% a 30% de opacidade, esmaecendo em direção ao centro.
- **Gráfico de área** com linha em `{colors.primary}`, marcadores em `{colors.primary-glow}` e preenchimento em degradê de `{colors.ember}` para transparente.
- **Seta ascendente** grande, em degradê de `{colors.primary-glow}` para `{colors.primary-active}`, cruzando a borda do mockup.

## Shapes

| Token | Valor | Uso |
|---|---|---|
| `{rounded.xs}` | 4px | Detalhes pequenos |
| `{rounded.sm}` | 6px | Itens de dropdown |
| `{rounded.md}` | 10px | Botões, inputs, abas |
| `{rounded.lg}` | 14px | Cards |
| `{rounded.xl}` | 20px | Mockup do hero |
| `{rounded.pill}` | 9999px | Badges |
| `{rounded.full}` | 9999px / 50% | Anéis de ícone, botões circulares |

### Ícones e ilustração
- Ícones de **linha fina** (stroke 1.5px a 2px), em `{colors.primary}`, dentro de **anéis circulares** de 56px com contorno de 1.5px na mesma cor.
- Metáforas simples: megafone (anunciantes), gráfico de barras com seta (comissões), foguete (escala).
- Nada de fotografia realista. O produto aparece como **mockup de dashboard** em notebook, com dados plausíveis.
- Uma **linha azul curta** (~64px × 2px) separa título e lista.

## Components

### Navegação superior
**`top-nav`**: barra de 72px sobre `{colors.canvas}`. Logotipo `actionpay` à esquerda (`action` em `{colors.ink}`, `pay` em `{colors.primary}`), menu central em `{typography.nav-link}`, à direita "Entrar" como texto e "Começar agora" em `{component.button-primary}`.

### Botões
**`button-primary`**: fundo `{colors.primary}`, texto `{colors.on-primary}`, 44px de altura, raio `{rounded.md}`. Ativo escurece para `{colors.primary-active}`.

**`button-secondary`**: transparente, texto `{colors.ink}`, borda de 1px em `{colors.hairline}`. Mesmas medidas do primário.

**`button-icon-circular`**: 48px, contorno azul de 1.5px, ícone azul.

**`text-link`**: links inline em `{colors.primary}`.

### Hero
**`hero-band`**: fundo `{colors.canvas}` com brilho azul. À esquerda: logotipo, título em duas linhas (primeira `{colors.ink}`, segunda `{component.hero-title-accent}`), linha azul curta e lista de três recursos. À direita: `{component.hero-product-card}` com o notebook e a seta ascendente.

**`feature-item`** + **`feature-icon-ring`**: ícone em anel azul de 56px e texto em `{typography.title-md}` com `{colors.ink}`, em até duas linhas.

### Cards de dados
**`stat-card`**: fundo `{colors.surface-card}`, raio `{rounded.lg}`, padding 20px. Contém rótulo em `{typography.caption}` `{colors.muted}`, número em `{typography.stat-md}` e variação em `{component.badge-trend-up}` (seta ↑ + percentual em verde).

**`stat-card-featured`**: igual, com fundo `{colors.surface-card-elevated}` e número em `{typography.stat-xl}`. É o "Resumo de ganhos".

**`chart-card`**: contém gráfico de área ou donut. Linha e marcadores em azul, grade em `{colors.hairline}`, rótulos em `{colors.muted}`.

### Planos
**`pricing-tier-card`**: fundo `{colors.surface-card}`, borda hairline, nome em `{typography.title-lg}`, preço em `{typography.stat-xl}`, recursos em `{typography.body-md}` e `{component.button-primary}` no fim.

**`pricing-tier-card-featured`**: fundo `{colors.surface-card-elevated}` com borda de 1px em `{colors.primary}` e badge azul "MAIS POPULAR".

### Chamadas
**`callout-card-blue`**: cartão azul com texto `{colors.on-primary}`. O botão dentro inverte para fundo `{colors.canvas}` e texto `{colors.ink}`.

**`cta-band-blue`**: faixa azul pré-rodapé, padding 64px, título em `{typography.display-sm}`.

**`cta-band-glow`**: alternativa escura, com brilho azul radial atrás do título e botão primário.

### Formulários
**`text-input`**: fundo `{colors.surface-card}`, borda `{colors.hairline}`, raio `{rounded.md}`, altura 44px.

**`text-input-focused`**: borda em `{colors.primary}` e anel externo de 3px em azul a 20% de opacidade.

### Tags e abas
**`badge-pill`**: fundo `{colors.surface-card-elevated}`, texto `{colors.ink}`, `{typography.caption}`.

**`badge-blue`**: fundo `{colors.primary}`, texto `{colors.on-primary}`, `{typography.caption-uppercase}`.

**`category-tab`** / **`category-tab-active`**: inativa em `{colors.muted}`; ativa com fundo `{colors.surface-card-elevated}` e texto `{colors.primary}`.

### Rodapé
**`footer`**: fundo `{colors.canvas}`, texto `{colors.on-dark-soft}`, quatro colunas (Produto, Empresa, Recursos, Legal) e logotipo no topo.

## Do's and Don'ts

### Do
- Ancore toda página no preto quente. O contraste com o azul é a identidade.
- Use um único azul (`{colors.primary}`) para destaque. Brasa só em degradês.
- Faça títulos em duas cores: ideia em branco, resultado em azul.
- Mostre o produto real (dashboard com números) em vez de ilustrações abstratas.
- Deixe números grandes e legíveis, com variação em verde.
- Use brilho radial azul nos cantos e textura de pontos no topo.
- Mantenha ícones de linha fina em anéis azul.
- Aplique `{spacing.section}` (96px) entre faixas.
- Use texto com contraste adequado (`{colors.on-primary}`) sobre fundos azul.

### Don't
- Não use preto puro (#000) nem cinza frio como piso.
- Não use branco como fundo de página. Fica fora da identidade.
- Não introduza azul, roxo ou outro acento. Preto, azul e branco são a tríade.
- Não use verde fora de indicadores positivos.
- Não pinte tudo de azul. Azul é destaque, não fundo de página inteira (exceto faixas de CTA).
- Não use fonte serifada, condensada ou pesada demais (700+) nos títulos.
- Não use brasa (`{colors.ember}`) como cor sólida de botão ou texto.
- Não use sombras fortes. A profundidade vem de brilho e tons de grafite.
- Não repita a mesma superfície em duas faixas seguidas: alterne canvas → card grafite → brilho azul → faixa azul → rodapé.

## Responsive Behavior

| Nome | Largura | Mudanças |
|---|---|---|
| Mobile | < 768px | Menu hambúrguer; H1 64→34px; mockup vai para baixo do texto; cards 1 coluna |
| Tablet | 768–1024px | Menu horizontal compacto; cards 2 colunas |
| Desktop | 1024–1440px | Menu completo; hero 5/7; cards 3 colunas |
| Wide | > 1440px | Igual ao desktop, com mais respiro lateral; conteúdo limitado a 1200px |

### Alvos de toque
- Botões com altura mínima de 44px.
- Botão circular de 48px.
- Inputs com 44px.

### Estratégia de colapso
- O hero passa para coluna única: título, lista e botões primeiro, mockup depois.
- A seta ascendente reduz de tamanho e fica contida no card, sem sangrar a borda.
- Gráficos mantêm legibilidade com rolagem horizontal interna, sem espremer rótulos.
- Brilho radial e textura de pontos reduzem de intensidade no mobile.

## Iteration Guide

1. Trabalhe um componente por vez, referenciando a chave YAML (`{component.stat-card}`).
2. Variantes (`-active`, `-disabled`, `-focused`, `-featured`) são entradas separadas em `components:`.
3. Use `{token.refs}` sempre. Nunca escreva hex direto no componente.
4. Documente apenas estados padrão e ativo/pressionado.
5. Títulos: Sora semibold com espaçamento negativo, duas cores. Corpo: Manrope/Inter 400.
6. Preto + azul + branco é a tríade. Não adicione uma quarta cor de marca.
7. Na dúvida sobre ênfase: troque a cor da palavra para azul antes de aumentar o peso.

## Known Gaps

- Os valores de cor foram estimados visualmente a partir de uma imagem. Confirme com o manual oficial da marca antes de uso em produção.
- A fonte original não foi identificada. Sora, Outfit e Manrope são as aproximações mais próximas.
- O logotipo `actionpay` é um ativo de marca, não formalizado aqui como token.
- Animações, transições e estados de erro de formulário não foram definidos.
- Não há versão clara (tema branco) do sistema.
- Dados exibidos nos mockups (R$ 28.540,00, 23.149 cliques etc.) são ilustrativos.
