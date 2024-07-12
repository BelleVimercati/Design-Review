# Design Review 001: Página Home

Link do site: [Página Home](https://www.consultoriafocus.com/)\
Link do Figma: [Design do site](https://www.figma.com/design/SehjtDfPtPl2RalCmmxqUp/site-da-focus?node-id=728-564&t=yZ4q9iILItusUrXW-1)

## Resumo da Estratégia

O objetivo deste documento é identificar e registrar todas as discrepâncias entre o design e o front-end, visando levantar e corrigir as diferenças. É fundamental buscar e documentar o máximo de informações de forma clara e objetiva.

## Legenda

- Cenário ainda não alterado: ➖
- Cenário corrigido: ✅
- Cenário apresentando erro ao corrigir: ❌

## Cenários macros

1. Tipografia
2. Peso Tipográfico
3. Espaçamento
4. Texto
5. Proporção
6. Cores
7. Posicionamento
8. Icons/Decoração
9. Menu

### ⚠️ Ponto de Atenção

A página home como um todo está tendendo a não respirar os espaços em branco estabelecidos pelo design, visualmente isso cria a impressão de que o conteúdo está espremido na página. Recomendo a revisão olhando o site como um todo, sem destrinchar as partes.

## Review das partes

| código | seção           | cenário        | descrição                                                            | Dispositivo |                                        evidência                                        | status |
| :----: | --------------- | -------------- | -------------------------------------------------------------------- | ----------- | :-------------------------------------------------------------------------------------: | :----: |
|        | Header          | Espaçamento    | O espaçamento entre os botões do menu está errado                    | Desktop     | [IS01](https://github.com/BelleVimercati/Design-Review/blob/main/Home/issues/header.md) |   ➖   |
|        | Header          | Icons          | O hover no botão "fale com especialista" some com o icon de WhatsApp | Desktop     | [IS02](https://github.com/BelleVimercati/Design-Review/blob/main/Home/issues/header.md) |   ➖   |
|        | Header          | Icons          | Logo da Focus descentralizada                                        | Mobile      | [IS03](https://github.com/BelleVimercati/Design-Review/blob/main/Home/issues/header.md) |   ➖   |
|        | Header          | Menu           | Menu hambúrguer implementado de forma diferente                      | Mobile      | [IS04](https://github.com/BelleVimercati/Design-Review/blob/main/Home/issues/header.md) |   ➖   |
|        | Banner          | Tipografia     | Título com tipografia errada                                         |             |                                                                                         |   ➖   |
|        | Banner          | Texto          | Texto do botão de contato errado                                     |             |                                                                                         |   ➖   |
|        | Banner          | Texto          | Texto do botão de contato errado                                     |             |                                                                                         |   ➖   |
|        | Banner          | Decoração      | Barra vertical decorativa não implementada                           |             |                                                                                         |   ➖   |
|        | Conheça a Focus | Texto          | Título com texto incompleto                                          |             |                                                                                         |   ➖   |
|        | Conheça a Focus | Tipografia     | Título com tipografia errada                                         |             |                                                                                         |   ➖   |
|        | Conheça a Focus | Proporção      | Imagem colocada com proporção diferente do design                    |             |                                                                                         |   ➖   |
|        | Nossos Clientes | Tipografia     | Título com tipografia errada                                         |             |                                                                                         |   ➖   |
|        | Nossos Clientes | Texto          | Título com texto alterado                                            |             |                                                                                         |   ➖   |
|        | Nossos Clientes | Posicionamento | Fade implementado apenas do lado esquerdo                            |             |                                                                                         |   ➖   |
|        | Formulário      | Tipografia     | Título com tipografia errada                                         |             |                                                                                         |   ➖   |
|        | Formulário      | Cores          | Card com cores erradas                                               |             |                                                                                         |   ➖   |
|        | Formulário      | Cores          | Inputs com cores erradas                                             |             |                                                                                         |   ➖   |
|        | Formulário      | Proporção      | Input de mensagem dimensionada errada                                |             |                                                                                         |   ➖   |
|        | Soluções        | Texto          | Subtítulo não sendo implementado e juntando com parágrafo            |             |                                                                                         |   ➖   |
|        | Soluções        | Espaçamento    | Espaço entre texto e links faltando                                  |             |                                                                                         |   ➖   |
|        | Soluções        | Espaçamento    | Espaço entre texto e links faltando                                  |             |                                                                                         |   ➖   |
|        | Depoimentos     | Tipografia     | Título com tipografia errada                                         |             |                                                                                         |   ➖   |
|        | Depoimentos     | Posicionamento | Título de seção não centralizado                                     |             |                                                                                         |   ➖   |
|        | Depoimentos     | Posicionamento | Título de seção não centralizado                                     |             |                                                                                         |   ➖   |
|        | Depoimentos     | Tipografia     | Tipografia do card errada                                            |             |                                                                                         |   ➖   |
|        | Depoimentos     | Tipografia     | Tipografia do card (nome da pessoa) errada                           |             |                                                                                         |   ➖   |
|        | Depoimentos     | Tipografia     | Tipografia do card com tamanho errado                                |             |                                                                                         |   ➖   |
|        | Depoimentos     | Cores          | Tipografia do card com cor errada                                    |             |                                                                                         |   ➖   |
|        | Depoimentos     | Texto          | Texto de cargo do depoente errado                                    |             |                                                                                         |   ➖   |
