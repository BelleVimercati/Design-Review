# 🐛 Issues encontrados no Header

[Issue 01](#is01---espaçamento-entre-botões)\
[Issue 02](#is02---icon-com-problema-no-hover)\
[Issue 03](#is03---logo-da-focus-decentralizada-mobile)\
[Issue 04](#is04---menu-hambúrguer-sendo-implementado-de-maneira-errada-mobile)\

Link do site: [Página Home](https://www.consultoriafocus.com/)\
Link do Figma: [Design do site](https://www.figma.com/design/SehjtDfPtPl2RalCmmxqUp/site-da-focus?node-id=728-564&t=yZ4q9iILItusUrXW-1)

## Tipos de Issues

1. Espaçamento
2. Icons

## Evidências

## [IS01] - Espaçamento entre botões

**Descrição:** \
O espaçamento entre os botões de link do header está alterado. O design proposto prevê um ``gap`` maior do que está sendo implementado.

**Evidência de Implementação:**
![Evidências de Gap alterado: Implementação](/Home/issues/assets/header/headergap1.png)

**Evidência de Design:**
![Evidências de Gap alterado: Design](/Home/issues/assets/header/headergap2.png)

**Alteração Sugerida:**\
Alterar o valor de gap entre os itens do header de ``20px`` para ``70px``.

----

### [IS02] - Icon com problema no Hover

**Descrição:** \
Quando colocamos o mouse sobre o botão, temos um problema quando o hover é disparado, isso se dá pelo ícone de WhatsApp ser branco e não ser trocado no hover.

**Evidência de Implementação:**
![Evidência de Hover: não selecionado](/Home/issues/assets/header/headerhover1.png)
![Evidência de Hover: selecionado](/Home/issues/assets/header/headerhover2.png)

**Evidência de Design:**\
Atualmente o design não prevê a implementação de um hover no botão de "fale com um especialista".

**Alteração Sugerida:**\
Conversa com o P.O. do projeto e definir se há a necessidade de um hover neste botão, ou apenas um ``cursor: pointer`` já atenderia os requisitos esperados para a situação.

----

### [IS03] - Logo da Focus decentralizada (mobile)

**Descrição:** \
Quando estamos na versão mobile do site da Focus, a logo do header fica descentralizado

**Evidência de Implementação:**

![Evidência de centralização: Logo da Focus (implementado)](/Home/issues/assets/header/logo1.png)

**Evidência de Design:**\
![Evidência de centralização: Logo da Focus (design)](/Home/issues/assets/header/logo2.png)

**Alteração Sugerida:**\
Ajustes no header para que o espaçamento lateral possa ser resolvido e a logo seja centralizada.

----

### [IS04] - Menu hambúrguer sendo implementado de maneira errada (mobile)

**Descrição:**\
Se considerando o design proposto, o menu hambúrguer que hoje está sendo implementado na versão mobile não segue o estabelecido.

**Evidência de Implementação:**

![Evidência do menu: implementação](/Home/issues/assets/header/menu1.png)

**Evidencia do Design:**

![Evidência do menu: design](/Home/issues/assets/header/menu2.png)

**Alteração Sugerida:**\
Sem muita certeza se há como reaproveitar a estrutura atual do menu, acredito que a melhor forma de resolver o problema seja refazendo a implementação dele.
