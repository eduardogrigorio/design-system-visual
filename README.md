# Template System

Template visual e técnico para criação de sistemas Python modernos, consistentes e reutilizáveis.

Este repositório funciona como uma base comum para novos projetos desenvolvidos com **Python** e **PyQt6**. Seu objetivo é evitar que cada sistema comece do zero e garantir que as telas mantenham uma identidade visual profissional, organizada e coerente.

## Para que serve

O `template_system` pode ser usado por desenvolvedores, equipes de produto e ferramentas de Inteligência Artificial que precisam criar interfaces desktop com um modelo de design já definido.

Ele serve como referência para:

- criação de novos sistemas Python;
- geração de interfaces PyQt6 por IAs;
- padronização de cores, tipografia e espaçamentos;
- definição de botões, cards, campos, menus e painéis;
- criação de dashboards e telas administrativas;
- manutenção de uma identidade visual comum entre projetos;
- evolução de componentes reutilizáveis ao longo do tempo.

## Padrão técnico

A tecnologia padrão para as interfaces deste template é:

```text
Python + PyQt6 + Qt Style Sheets (QSS)
```

O PyQt6 deve ser priorizado na criação de novas telas e componentes. Quando um projeto precisar de uma tecnologia diferente, a decisão deve ser documentada para preservar a consistência do ecossistema.

## Guia visual oficial

O arquivo [`design-orange-system.md`](./design-orange-system.md) é a fonte principal das decisões visuais do template.

Ele define, entre outros elementos:

- paleta escura com preto quente, grafite, branco e laranja;
- cores semânticas para sucesso, alerta e erro;
- tipografia e hierarquia de títulos;
- espaçamento baseado em múltiplos de 4 pixels;
- raios de borda e níveis de elevação;
- regras para cards, botões, campos e navegação;
- princípios de profundidade, brilho e contraste;
- orientação para ícones e ilustrações;
- estrutura visual de dashboards e sistemas administrativos.

Ao iniciar um novo projeto, o arquivo `design-orange-system.md` deve ser consultado antes da criação da interface.

## Uso por Inteligências Artificiais

Este repositório foi criado para ser compreendido e utilizado por IAs que geram código, interfaces e sistemas completos.

Uma IA pode usar este template como contexto de design para:

1. identificar a identidade visual do projeto;
2. escolher as cores corretas;
3. manter a hierarquia tipográfica;
4. criar componentes PyQt6 consistentes;
5. transformar tokens visuais em estilos QSS;
6. produzir telas novas sem quebrar o padrão existente;
7. reutilizar a mesma linguagem visual em diferentes sistemas.

### Prompt recomendado para uma IA

```text
Use este repositório como template visual e técnico para o novo sistema.

Tecnologia obrigatória: Python com PyQt6.

Leia o arquivo design-orange-system.md antes de criar qualquer tela.
Respeite a paleta, a tipografia, os espaçamentos, os raios, os componentes
 e os princípios de layout definidos no guia. Crie componentes reutilizáveis,
separe a lógica da interface e mantenha a identidade visual consistente.
Não invente uma nova paleta ou um novo padrão visual sem justificar a mudança.
```

## Estrutura atual

```text
Template System/
├── README.md
├── design-orange-system.md
└── Perfil GitHub.html
```

### Arquivos

- `README.md`: apresentação, objetivo e instruções de uso do template.
- `design-orange-system.md`: guia visual oficial e fonte de referência para as interfaces.
- `Perfil GitHub.html`: material complementar relacionado ao perfil do projeto.

## Diretrizes para novos projetos

Todo novo sistema baseado neste repositório deve, sempre que possível:

- usar PyQt6 para a interface;
- separar a apresentação, a lógica e o acesso a dados;
- transformar as cores e medidas do guia em constantes ou tokens reutilizáveis;
- centralizar os estilos QSS;
- evitar estilos espalhados diretamente pelos widgets;
- reutilizar componentes antes de criar variações isoladas;
- manter a interface responsiva ao redimensionamento da janela;
- validar estados normal, ativo, desabilitado, foco, erro e sucesso;
- preservar acessibilidade, contraste e legibilidade;
- documentar qualquer alteração significativa no design system.

## Exemplo de organização recomendada

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

Clone o repositório ou utilize o conteúdo do guia como referência no novo projeto:

```bash
git clone https://github.com/eduardogrigorio/template_system.git
```

Depois, leia o guia de design:

```text
design-orange-system.md
```

Em um projeto PyQt6, instale a dependência principal:

```bash
pip install PyQt6
```

A implementação final deve converter as decisões do guia em widgets, layouts e estilos QSS adequados ao sistema criado.

## Evolução do template

Este repositório é uma base viva. Novos componentes, padrões e exemplos podem ser adicionados conforme surgirem novos sistemas e necessidades de interface.

Antes de incluir uma mudança global, avalie o impacto sobre os projetos que utilizam este template. Alterações de cores, tipografia, espaçamento ou componentes devem ser documentadas para que as IAs e os desenvolvedores consigam aplicar a nova versão corretamente.

## Licença e uso

Este repositório funciona como um template de referência para os projetos do autor e para ferramentas de IA que precisem de um modelo visual e técnico. Verifique a licença e os direitos de qualquer recurso externo antes de incorporá-lo a um projeto distribuído.
