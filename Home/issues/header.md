# 🐛 Issues encontrados no Header

Link do site: [Página Home](https://www.consultoriafocus.com/)\
Link do Figma: [Design do site](https://www.figma.com/design/SehjtDfPtPl2RalCmmxqUp/site-da-focus?node-id=728-564&t=yZ4q9iILItusUrXW-1)

## Tipos de Issues

1. Espaçamento
2. Icons

## Evidências

### [IS01] - Espaçamento entre botões

**Descrição:** \
O espaçamento entre os botões de link do header está alterado. O design proposto prevê um ``gap`` maior do que está sendo implementado.

**Evidência de Implementação:**
![Evidências de Gap alterado: Implementação](/Home/issues/assets/headergap1.png)

**Evidência de Design:**
![Evidências de Gap alterado: Design](/Home/issues/assets/headergap2.png)

**Alteração Sugerida:**\
Alterar o valor de gap entre os itens do header de ``20px`` para ``70px``.

### [IS02] - Icon com problema no Hover

**Descrição:** \
Quando colocamos o mouse sobre o botão, temos um problema quando o hover é disparado, isso se dá pelo ícone de WhatsApp ser branco e não ser trocado no hover.

**Evidência de Implementação:**
![Evidência de Hover: não selecionado](/Home/issues/assets/headerhover1.png)
![Evidência de Hover: selecionado](/Home/issues/assets/headerhover2.png)

**Evidência de Design:**\
Atualmente o design não prevê a implementação de um hover no botão de "fale com um especialista".

**Alteração Sugerida:**\
Conversa com o P.O. do projeto e definir se há a necessidade de um hover neste botão, ou apenas um ``cursor: pointer`` já atenderia os requisitos esperados para a situação.
