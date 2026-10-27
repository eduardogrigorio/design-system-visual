<div align="center">

# Design System Visual

### Um design system visual para criar sistemas consistentes em qualquer área

<p>
  <a href="./design-orange-system.md"><img src="https://img.shields.io/badge/Design%20System-Orange-f47b20?style=for-the-badge&labelColor=0d0d0d" alt="Design System"></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-0d0d0d?style=for-the-badge&logo=python&logoColor=f47b20" alt="Python"></a>
  <a href="https://www.riverbankcomputing.com/software/pyqt/"><img src="https://img.shields.io/badge/PyQt6-Preferred-4caf50?style=for-the-badge&labelColor=0d0d0d" alt="PyQt6"></a>
  <a href="./design-orange-system.md"><img src="https://img.shields.io/badge/AI%20Ready-222222?style=for-the-badge&logo=openai&logoColor=ff9a3d" alt="AI Ready"></a>
</p>

<p>
  <strong>Uma base visual comum para aplicações desktop, web, mobile, dashboards e ferramentas internas.</strong>
</p>

</div>

---

## O que é este repositório?

O `design-system-visual` é um **design system visual e técnico** para orientar a criação de diferentes tipos de sistemas, modelos de negócio e funções.

Ele existe para que cada novo projeto não precise começar do zero. A interface pode mudar de finalidade e de tecnologia, mas deve manter uma linguagem visual profissional, organizada e coerente.

> **Ideia central:** uma mesma identidade visual pode ser adaptada para diferentes produtos sem perder consistência.

## Onde utilizar

<table>
  <tr>
    <td><strong>Sistemas administrativos</strong><br>Operação, gestão e backoffice.</td>
    <td><strong>Dashboards</strong><br>Indicadores, métricas e relatórios.</td>
    <td><strong>Ferramentas internas</strong><br>Fluxos técnicos e operacionais.</td>
  </tr>
  <tr>
    <td><strong>Sistemas comerciais</strong><br>Vendas, clientes e processos.</td>
    <td><strong>Aplicações desktop</strong><br>Python e PyQt6.</td>
    <td><strong>Aplicações web e mobile</strong><br>Adaptação dos mesmos tokens visuais.</td>
  </tr>
</table>

## A fonte visual oficial

Toda a identidade do template está documentada em [`design-orange-system.md`](./design-orange-system.md).

O guia define:

- paleta escura com preto quente, grafite, branco e laranja;
- cores semânticas para sucesso, alerta e erro;
- tipografia e hierarquia visual;
- espaçamento baseado em múltiplos de 4 pixels;
- raios de borda e níveis de elevação;
- cards, botões, campos, menus e navegação;
- brilho, contraste, profundidade e uso de ícones;
- adaptação para diferentes fluxos, modelos e funções.

Antes de criar uma nova tela, consulte o guia visual.

## Linguagem visual

```text
CANVAS       #0d0d0d   preto quente de fundo
SURFACE      #141414   superfícies discretas
CARD         #1a1a1a   cards principais
CARD ELEVATED#222222   cards em destaque
PRIMARY      #f47b20   laranja de ação
PRIMARY GLOW #ff9a3d   brilho e destaque
INK          #ffffff   títulos e textos principais
BODY         #d9d9d9   texto corrido
SUCCESS      #4caf50   estados positivos
WARNING      #e8a02a   alertas
ERROR        #e5484d   erros
```

A profundidade deve vir principalmente da diferença entre superfícies, do contraste e do brilho laranja. Evite adicionar cores ou padrões que criem uma identidade paralela sem justificativa.

## Exemplos de aplicação

As imagens abaixo mostram três aplicações diferentes utilizando a mesma linguagem visual: uma landing page institucional, um sistema desktop de monitoramento e um dashboard de auditoria no Google Sheets.

### Landing page institucional

<p align="center">
  <img src="./Landing%20Page.JPG" alt="Exemplo de landing page com o design system laranja" width="900">
</p>

A landing page utiliza fundo escuro, títulos em branco e laranja, cards grafite, indicadores em verde, navegação superior e chamadas para ação com destaque laranja.

### Sistema desktop de monitoramento

<p align="center">
  <img src="./assets_monitor.JPG" alt="Exemplo de sistema desktop de monitoramento com o design system laranja" width="900">
</p>

O sistema de monitoramento adapta os mesmos princípios para uma aplicação operacional: cards de métricas, campos de entrada, botões, status, tabela e alertas.

### Dashboard de auditoria no Google Sheets

<p align="center">
  <img src="./Google%20Sheets.JPG" alt="Exemplo de dashboard de auditoria de PIX no Google Sheets com o design system laranja" width="700">
</p>

O dashboard de auditoria de PIX aplica a mesma linguagem visual a planilhas e relatórios: fundo escuro, indicadores em cards, estados semânticos, tabelas e gráficos com destaque laranja.

Esses exemplos demonstram que o template não é limitado a um único produto ou plataforma. A mesma base visual pode atender diferentes modelos e funções sem perder identidade.

## Padrão técnico

Para aplicações desktop desenvolvidas em Python, a tecnologia preferencial é:

```text
Python + PyQt6 + Qt Style Sheets (QSS)
```

O PyQt6 deve ser priorizado para sistemas desktop em Python. Em aplicações web, mobile ou projetos desenvolvidos com outra tecnologia, os mesmos tokens, componentes, cores, tipografia e espaçamentos devem ser adaptados à plataforma escolhida.

| Plataforma | Aplicação do template |
|---|---|
| Python desktop | PyQt6, widgets, layouts e QSS |
| Web | Componentes, CSS e tokens equivalentes |
| Mobile | Componentes nativos ou framework escolhido, mantendo a linguagem visual |
| Dashboard | Cards, métricas, tabelas, gráficos e estados semânticos |
| Ferramenta interna | Fluxos operacionais, formulários e painéis reutilizáveis |

## Guia universal: como aplicar em qualquer projeto

Este design system é **agnóstico de plataforma, linguagem e ferramenta**. Ele pode orientar um sistema web, desktop, mobile, dashboard, planilha, protótipo, aplicação no-code ou uma interface criada com ajuda de qualquer IA. O que deve ser preservado é a linguagem visual e a lógica dos componentes; a sintaxe e a tecnologia podem mudar.

### Passo 1 — Defina o projeto antes de criar a tela

Preencha estas informações em poucas linhas:

```text
Nome do projeto:
Tipo de sistema: site, painel, cadastro, vendas, financeiro, suporte etc.
Usuários principais:
Plataforma: web, desktop, mobile, planilha ou outra.
Linguagem e framework: se já estiverem definidos.
Principais ações: consultar, cadastrar, editar, aprovar, exportar etc.
Telas necessárias:
Restrições: responsividade, acessibilidade, integração, prazo ou dispositivo.
```

Se a plataforma ou a linguagem ainda não estiver definida, primeiro descreva o objetivo do sistema. A tecnologia pode ser escolhida depois, sem alterar os princípios visuais.

### Passo 2 — Abra o guia e os exemplos

Consulte nesta ordem:

1. [`design-orange-system.md`](./design-orange-system.md), para conhecer cores, tipografia, espaçamentos, raios, componentes e estados;
2. as imagens de exemplo do README, para observar a aplicação visual em diferentes contextos;
3. este passo a passo, para transformar as decisões visuais em código, configuração ou componentes da ferramenta escolhida.

Não copie uma tela inteira sem entender sua finalidade. Reaproveite os princípios e adapte o conteúdo, o fluxo e o layout ao problema real.

### Passo 3 — Converta os tokens para a tecnologia escolhida

Crie uma única fonte de verdade para as decisões visuais. Os mesmos tokens podem ser escritos de formas diferentes:

| Contexto | Onde colocar os tokens |
|---|---|
| HTML, CSS, Vue ou web em geral | variáveis CSS, tema ou arquivo de estilos |
| React, Angular ou TypeScript | objeto de tema, constantes ou design tokens |
| Python, PyQt, Tkinter ou desktop | módulo de constantes, tema e arquivo de estilos |
| Flutter, React Native ou mobile nativo | tema, arquivo de constantes ou componentes compartilhados |
| Java, .NET, Qt ou outra aplicação desktop | classe de tema, recursos e estilos da plataforma |
| Figma, no-code ou planilha | variáveis, estilos, cores e regras documentadas |

Exemplo de tokens em CSS. Em outra linguagem, mantenha os mesmos nomes e valores, adaptando apenas a sintaxe:

```css
:root {
  --canvas: #0d0d0d;
  --surface-card: #1a1a1a;
  --surface-elevated: #222222;
  --primary: #f47b20;
  --primary-glow: #ff9a3d;
  --text: #ffffff;
  --body: #d9d9d9;
  --muted: #8a8a8a;
  --success: #4caf50;
  --warning: #e8a02a;
  --error: #e5484d;
  --radius-md: 10px;
  --radius-lg: 14px;
  --space-md: 16px;
  --space-lg: 24px;
}
```

Regra simples: **não espalhe valores hexadecimais, tamanhos ou raios diretamente pelas telas**. Consulte os tokens e altere a fonte central quando uma decisão global for necessária.

### Passo 4 — Crie os componentes antes das telas

Comece pelos componentes compartilhados e só depois monte as páginas ou janelas:

1. estrutura de página, container, cabeçalho, navegação e rodapé;
2. tipografia, botões, links e ícones;
3. campos, seleção, filtros e formulários;
4. cards, tabelas, métricas, gráficos e badges;
5. mensagens, alertas, diálogos, carregamento, vazio e erro.

Todo componente deve ter apenas os estados que fazem sentido para seu uso: normal, hover ou ativo, foco, desabilitado, carregando, sucesso, aviso e erro. Em uma planilha ou ferramenta no-code, esses componentes podem ser representados por abas, células formatadas, validações, cartões ou estilos salvos.

### Passo 5 — Monte cada tela em uma sequência curta

Para cada tela, siga esta ordem:

1. defina a ação principal e a informação mais importante;
2. escolha a estrutura de layout adequada à plataforma;
3. aplique fundo, superfícies, espaçamento e hierarquia tipográfica;
4. reutilize os componentes já criados;
5. adicione dados reais ou dados de exemplo plausíveis;
6. trate estados de carregamento, vazio, sucesso, aviso e erro;
7. adapte o comportamento a diferentes tamanhos de tela ou janelas, quando aplicável.

O conteúdo e o fluxo podem mudar completamente entre um sistema financeiro, um CRM ou um painel de infraestrutura. A identidade visual, os tokens e os estados dos componentes devem continuar coerentes.

### Passo 6 — Valide antes de considerar pronto

Use este checklist em qualquer tecnologia:

- [ ] o fundo usa o preto quente e as superfícies corretas;
- [ ] o laranja é usado como destaque, não em excesso;
- [ ] textos, títulos e números têm hierarquia clara;
- [ ] espaçamentos e raios seguem os tokens;
- [ ] botões, campos, tabelas e cards possuem estados compreensíveis;
- [ ] sucesso, aviso e erro usam as cores semânticas corretas;
- [ ] há contraste e legibilidade suficientes;
- [ ] a interface funciona no tamanho de tela ou janela esperado;
- [ ] teclado, toque e foco são considerados quando aplicável;
- [ ] não existem estilos isolados que criem uma identidade paralela;
- [ ] exceções foram registradas e justificadas.

### Fluxo fácil usando qualquer IA

Este processo funciona em ChatGPT, Claude, Gemini, Copilot ou outra IA capaz de analisar instruções e gerar código:

1. envie o link deste repositório ou os arquivos `README.md` e `design-orange-system.md`;
2. informe o objetivo do sistema usando a ficha do Passo 1;
3. peça primeiro um plano de telas, componentes e tokens — não o projeto inteiro de uma vez;
4. peça a implementação de uma tela ou componente por vez;
5. execute o resultado, observe uma imagem ou erro e envie esse retorno à IA;
6. peça a correção sem permitir que a IA crie uma nova paleta sem justificativa;
7. depois de validar a primeira tela, peça a reutilização dos mesmos componentes nas demais;
8. ao final, peça uma revisão usando o checklist acima.

O melhor resultado vem de ciclos curtos: **planejar → implementar → visualizar → corrigir → reutilizar**.

## Uso por Inteligências Artificiais

O repositório foi estruturado para ser usado como contexto por IAs que geram código, interfaces e sistemas completos.

Uma IA deve usar este template para:

1. identificar a identidade visual antes de escrever a interface;
2. escolher as cores e os estados semânticos corretos;
3. manter a hierarquia tipográfica e o espaçamento;
4. criar componentes reutilizáveis;
5. converter tokens para QSS, CSS ou o mecanismo da plataforma;
6. adaptar o sistema para sua área e função;
7. evitar estilos isolados que quebrem o padrão;
8. documentar qualquer alteração global no design system.

### Como uma IA deve usar este repositório

O repositório deve ser tratado como uma **fonte de referência de design**, e não como um conjunto de telas para copiar sem análise. A IA deve seguir este fluxo:

#### 1. Entender o projeto

Antes de escrever código, a IA deve identificar:

- qual é o tipo do sistema;
- quem utilizará a aplicação;
- qual é a plataforma de execução;
- quais são as funções principais;
- quais telas, fluxos e estados são necessários.

#### 2. Ler o guia visual

A IA deve abrir o [`design-orange-system.md`](./design-orange-system.md) e extrair os tokens relevantes:

- cores de fundo, superfície, texto e estados;
- tipografia e hierarquia de títulos;
- espaçamentos e tamanhos;
- raios de borda e níveis de elevação;
- regras de botões, campos, cards, tabelas e navegação.

#### 3. Consultar os exemplos

As imagens `Landing Page.JPG`, `assets_monitor.JPG` e `Google Sheets.JPG` mostram como a mesma identidade visual pode ser aplicada em produtos e plataformas diferentes. A IA deve observar a linguagem visual dos exemplos, mas adaptar a estrutura à finalidade do novo sistema.

O objetivo não é copiar a landing page ou o monitor de ações. O objetivo é reutilizar os princípios: fundo escuro, contraste, destaque laranja, cards organizados, estados semânticos e hierarquia clara.

#### 4. Escolher a implementação

Depois de entender a plataforma, a IA deve escolher a implementação adequada:

- **Python desktop:** PyQt6, layouts, widgets e QSS;
- **Web:** componentes, CSS e tokens equivalentes;
- **Mobile:** componentes nativos ou o framework escolhido;
- **Dashboard:** cards, métricas, gráficos, tabelas e filtros;
- **Ferramenta operacional:** formulários, ações, status e painéis.

#### 5. Criar tokens antes das telas

A IA deve transformar o guia em variáveis reutilizáveis antes de estilizar os componentes. Por exemplo:

```python
COLORS = {
    "canvas": "#0d0d0d",
    "surface_card": "#1a1a1a",
    "surface_elevated": "#222222",
    "primary": "#f47b20",
    "primary_glow": "#ff9a3d",
    "text": "#ffffff",
    "body": "#d9d9d9",
    "success": "#4caf50",
    "warning": "#e8a02a",
    "error": "#e5484d",
}
```

Os mesmos valores podem ser convertidos para QSS, CSS, tema mobile ou outro sistema de estilos. A regra é manter uma única fonte de verdade para a identidade visual.

#### 6. Montar componentes reutilizáveis

A IA deve criar componentes antes de duplicar estilos em cada tela. Exemplos:

```text
AppButton
AppInput
AppCard
AppTable
AppBadge
AppSidebar
AppHeader
AppDialog
```

Cada componente deve possuir estados normal, hover ou ativo, foco, desabilitado, erro e sucesso quando fizer sentido.

#### 7. Implementar a tela sem perder o padrão

Com os tokens e componentes definidos, a IA deve montar a tela do sistema. Ela pode alterar o conteúdo, a quantidade de campos, os indicadores e o fluxo, mas não deve inventar uma nova paleta ou misturar estilos incompatíveis sem justificar a decisão.

#### 8. Validar visualmente

Antes de considerar o trabalho pronto, a IA deve verificar:

- contraste e legibilidade;
- alinhamento e espaçamento;
- comportamento em diferentes tamanhos de janela;
- estados dos componentes;
- consistência entre telas;
- uso correto das cores semânticas;
- ausência de cores, sombras ou componentes fora do padrão.

#### 9. Documentar exceções

Se o sistema exigir uma cor, componente ou fluxo que não exista no guia, a IA deve explicar a necessidade, registrar a decisão e evitar alterar o padrão global sem avaliar o impacto nos demais projetos.

### Prompt universal recomendado

```text
Use este repositório como referência visual e técnica do novo projeto.
Leia README.md e design-orange-system.md antes de propor ou escrever código.

Projeto: [descreva o sistema]
Usuários: [descreva os usuários]
Plataforma: [web, desktop, mobile, dashboard, planilha ou outra]
Linguagem/framework: [informe ou escolha a opção mais adequada]
Telas e ações principais: [liste as telas e ações]

Antes de implementar:
1. identifique a finalidade, os usuários, a plataforma e os fluxos;
2. proponha a estrutura de telas e os componentes reutilizáveis;
3. mapeie os tokens do design system para a linguagem escolhida;
4. aponte qualquer suposição ou informação que esteja faltando.

Depois implemente uma etapa por vez, começando pela base visual e por uma tela.
Preserve cores, tipografia, espaçamentos, raios, estados, contraste e hierarquia
definidos no guia. Separe interface, lógica e dados quando a tecnologia permitir.
Use os equivalentes nativos da plataforma, sem inventar uma nova paleta.
Se uma exceção for necessária, justifique-a e registre-a.

Entregue sempre: arquivos alterados, instruções para executar, estados tratados
e uma lista curta do que deve ser validado visualmente.
```

## Diretrizes de implementação

Todo projeto baseado neste template deve, sempre que possível:

- separar apresentação, lógica e acesso a dados;
- centralizar cores, medidas e tokens;
- reutilizar componentes antes de criar variações isoladas;
- validar estados normal, ativo, desabilitado, foco, erro e sucesso;
- manter a interface responsiva ao redimensionamento;
- preservar contraste, legibilidade e acessibilidade;
- evitar estilos espalhados diretamente pelos componentes;
- documentar mudanças que afetem vários projetos.

## Estrutura recomendada para Python e PyQt6

```text
meu_sistema/
├── app.py
├── requirements.txt
├── README.md
├── src/
│   ├── main_window.py
│   ├── widgets/
│   ├── views/
│   ├── services/
│   └── resources/
├── styles/
│   ├── tokens.py
│   └── app.qss
└── tests/
```

## Como utilizar

Clone o template:

```bash
git clone https://github.com/eduardogrigorio/design-system-visual.git
```

Leia primeiro o guia visual:

```text
design-orange-system.md
```

Para um projeto desktop Python com PyQt6:

```bash
pip install PyQt6
```

Depois, converta as decisões do guia em componentes, layouts e estilos adequados ao sistema. Em PyQt6, utilize widgets, layouts e QSS; em outras plataformas, utilize os equivalentes tecnológicos.

## Estrutura do repositório

```text
Template System/
├── README.md
├── design-orange-system.md
├── Perfil GitHub.html
├── Google Sheets.JPG
├── Landing Page.JPG
└── assets_monitor.JPG
```

- `README.md`: apresentação e instruções de uso do template.
- `design-orange-system.md`: fonte oficial das decisões visuais.
- `Perfil GitHub.html`: material complementar do projeto.
- `Google Sheets.JPG`: exemplo de dashboard de auditoria de PIX em uma planilha.
- `Landing Page.JPG`: exemplo visual de uma landing page institucional.
- `assets_monitor.JPG`: exemplo visual de um sistema desktop de monitoramento.

## Evolução

Este é um design system vivo. Novos componentes, padrões e exemplos podem ser adicionados conforme surgirem novos sistemas e necessidades.

Antes de alterar cores, tipografia, espaçamento ou componentes globais, avalie o impacto sobre os projetos que utilizam este template e documente a mudança.

## Uso e direitos

Este repositório é uma referência visual e técnica para projetos do autor, desenvolvedores e ferramentas de IA. Verifique a licença e os direitos de qualquer recurso externo antes de incorporá-lo a um produto distribuído.

<div align="center">

**Uma identidade visual. Vários sistemas. Diferentes funções.**

</div>
