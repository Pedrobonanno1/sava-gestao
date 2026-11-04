# Programa de Indicação SAVA

Planejamento decidido em 04/11/2026. Prêmio único por cliente fechado, pago com o
dinheiro que o próprio cliente indicado já pagou.

## 1. Objetivo

Transformar clientes e parceiros da SAVA em canal de aquisição, pagando um prêmio por
cliente novo que fechar. O custo de aquisição fica travado em **uma mensalidade** e só
sai do caixa depois que o cliente indicado já pagou três.

## 2. Quem pode indicar

| Perfil | Quem é | Como recebe |
|---|---|---|
| **Cliente** | Qualquer cliente ativo e adimplente da SAVA | Dinheiro ou crédito na mensalidade |
| **Parceiro** | Pessoa ou empresa cadastrada no programa (consultor, contador, escritório, fornecedor, amigo da casa) | Dinheiro (PF ou PJ) |

Parceiro precisa de um cadastro simples antes da primeira indicação: nome, CPF/CNPJ,
contato e dados de pagamento (Pix). Cliente já está cadastrado; basta indicar.

## 3. O prêmio

Um prêmio por cliente fechado, definido pelo regime tributário do cliente indicado:

| Regime do indicado | Em dinheiro | Em crédito na mensalidade |
|---|---|---|
| Simples Nacional | R$ 300 | R$ 400 |
| Lucro Presumido | R$ 500 | R$ 650 |

- **Crédito** é a opção para quem é cliente: desconto aplicado nas próximas mensalidades
  do indicador até consumir o valor. Não mexe no caixa e vale mais. Deve ser a opção
  padrão apresentada ao cliente.
- **Dinheiro** é a opção para parceiro externo e para cliente que preferir.
- O indicador escolhe a forma no momento em que o prêmio é liberado, não na indicação.
- Sem teto de indicações. Dez clientes fechados são dez prêmios.
- Crédito não é resgatável em dinheiro nem transferível, e se perde se o indicador
  cancelar a SAVA antes de consumir.

> Decisão pendente: o valor do crédito para Lucro Presumido. O combinado foi "crédito de
> 400"; aqui está extrapolado na mesma proporção (cerca de 30% acima do dinheiro). Se a
> ideia for crédito fixo de 400 em qualquer regime, basta ajustar a tabela.

## 4. Quando o prêmio é liberado

**Na quitação da 3ª mensalidade do cliente indicado.**

Isso dá na prática uns 90 dias após o fechamento, mas a regra é contada em pagamentos,
não em dias. Razões:

- **Caixa:** o prêmio sai do que o indicado já pagou. A SAVA nunca desembolsa antes de
  receber.
- **Churn:** cliente que entra e sai no primeiro ou segundo mês não gera prêmio.
- **Comunicação:** "pagamos quando o cliente completa três mensalidades" é regra de
  retenção, não sinal de aperto de caixa.

Depois de liberado, dinheiro é pago via Pix em **até 10 dias** e crédito entra na
**próxima fatura** do indicador.

## 5. Regras do programa

1. **O que é "fechar":** contrato assinado **e** primeira mensalidade paga. Proposta
   aceita não conta.
2. **Registro antes do contato:** a indicação precisa estar registrada (formulário ou
   link) antes de o cliente procurar a SAVA. Cliente que já está no funil não pode ser
   "indicado" depois.
3. **Conflito de indicação:** se duas pessoas indicam o mesmo cliente, vale o primeiro
   registro.
4. **Sem autoindicação:** não vale indicar a própria empresa nem empresa do mesmo sócio
   ou grupo.
5. **Base de cálculo:** o regime do indicado no momento do fechamento. Se ele mudar de
   regime depois, o prêmio não muda.
6. **Cliente com desconto:** o prêmio é o da tabela, independente de desconto promocional
   que o indicado tenha recebido.
7. **Indicador inadimplente:** prêmio fica retido até o indicador regularizar.
8. **Validade da indicação:** 6 meses. Se o indicado não fechar nesse prazo, a
   indicação expira e pode ser registrada de novo por qualquer pessoa.
9. **Direito de mudar:** a SAVA pode alterar valores e regras com aviso de 30 dias.
   Indicações já registradas seguem a regra vigente no registro.

## 6. Fluxo operacional

```
Indicador                SAVA                              Cliente indicado
   |                       |                                      |
   |- registra indicação ->| confirma por WhatsApp/e-mail         |
   |                       |- cria lead no funil (origem =        |
   |                       |  Indicação, campo "indicado por")    |
   |                       |- faz o comercial normal ------------>|
   |                       |<------------ contrato + 1ª mensalidade|
   |<- avisa: "fechou" ----|                                      |
   |                       |<------------ 2ª mensalidade ---------|
   |                       |<------------ 3ª mensalidade ---------|
   |<- prêmio liberado ----| pergunta: dinheiro ou crédito?       |
   |- escolhe ------------>|                                      |
   |<- Pix em 10 dias -----|  ou crédito na próxima fatura        |
```

**Registro da indicação.** Formulário simples (nome da empresa, contato, quem indicou).
Cada cliente e parceiro recebe um link com código próprio, para o registro não depender
de ninguém digitar nada certo. Para começar, um formulário basta.

**Toque com o indicador.** Três mensagens automáticas, no mínimo: recebemos a indicação,
fechou, prêmio liberado. Parceiro que não sabe o que aconteceu com a indicação não
indica de novo.

## 7. Pagamento e lado fiscal

| Forma | Tratamento |
|---|---|
| Crédito na mensalidade | Desconto na fatura do indicador. Sem tributo adicional, sem documento. É a forma mais barata para a SAVA em todos os sentidos. |
| Dinheiro para PJ | Parceiro emite nota fiscal de serviço (intermediação / agenciamento) contra a SAVA. |
| Dinheiro para PF | RPA com retenção de INSS (11%) e IR pela tabela progressiva, e INSS patronal de 20% por conta da SAVA. Na prática um prêmio de 300 custa uns 360. |

Por causa da última linha, a comunicação deve empurrar cliente para o crédito e, para
parceiro frequente pessoa física, vale sugerir que ele receba por um CNPJ (MEI serve
para agenciamento).

## 8. Impacto no caixa

Premissa: mensalidade igual ao prêmio em dinheiro (300 Simples, 500 Presumido).

| Mês | Indicado paga (acumulado) | SAVA paga ao indicador | Saldo do cliente |
|---|---|---|---|
| 1 | 300 | 0 | +300 |
| 2 | 600 | 0 | +600 |
| 3 | 900 | 300 (ou 400 em crédito) | +600 |
| 12 | 3.600 | 300 | +3.300 |

O prêmio consome uma mensalidade em doze, e nunca precisa de capital de giro. Se 10
clientes fecharem por indicação num mês, o custo é zero nesse mês e no seguinte, e no
terceiro são 3.000 a 5.000 reais pagos com os 9.000 a 15.000 que esses clientes já
pagaram. Vale medir o churn dos indicados separado: cliente indicado costuma ficar mais,
o que faz esse CAC ser ainda melhor do que a tabela mostra.

## 9. O que mudar na plataforma de gestão

A plataforma (`orca/lina-gestao`) já tem funil, clientes, cobrança por competência e
comissão por responsável. O programa encaixa em cima disso, em três fatias:

1. **Origem "Indicação" no lead** com campo `indicado_por` apontando para um cliente ou
   parceiro. Cadastro de parceiros é uma tabela nova e pequena (nome, documento, Pix,
   contato). Isso já permite registrar e acompanhar manualmente.
2. **Tela "Indicações":** lista cada indicação com estágio (registrada, fechou, 1ª, 2ª,
   3ª paga, prêmio liberado, prêmio pago), forma escolhida e data. O estágio é derivado
   das cobranças baixadas do indicado, sem ninguém contar na mão.
3. **Lançamento automático do prêmio:** ao liberar, dinheiro vira uma despesa a pagar
   (categoria "Indicações") e crédito vira desconto na próxima cobrança do indicador.
   Assim o custo do programa aparece no DRE sem lançamento manual.

A fatia 1 é suficiente para lançar. As outras duas entram quando houver volume para
justificar.

## 10. Comunicação e material

- **Uma página no site** explicando o programa em cinco linhas: quem pode, quanto ganha,
  quando recebe, como indicar, regras resumidas. Com o formulário de registro.
- **Termo de adesão** de uma página para parceiro, incorporando as regras da seção 5.
  Para cliente, o aceite é pelo próprio formulário.
- **Mensagem pronta** para o cliente mandar ao indicado, e uma arte para WhatsApp.
- **Lembrete no onboarding e na fatura** do cliente: "indique e ganhe 400 de crédito".

## 11. Métricas

Acompanhar mensalmente:

- Indicações registradas e de quem vieram (cliente vs. parceiro).
- Taxa de conversão de indicação para cliente fechado, comparada com os outros canais.
- Prêmios liberados, pagos em dinheiro e em crédito.
- Custo total do programa / clientes fechados por indicação (CAC do canal).
- Churn dos indicados nos primeiros 6 meses contra o churn geral.

Se a conversão de indicação for muito superior aos outros canais, há espaço para subir
o prêmio. Se o crédito dominar, há espaço para oferecer crédito ainda maior.

## 12. Cronograma de lançamento

| Semana | Entrega |
|---|---|
| 1 | Fechar regras e valores (este documento), termo de adesão, texto da página. |
| 2 | Formulário de registro com link por indicador; campo "indicado por" no funil. |
| 3 | Lançar para a base de clientes atuais (e-mail + WhatsApp + lembrete na fatura). |
| 5 a 8 | Convidar parceiros externos, começando pelos que já mandaram cliente sem programa. |
| Mês 3 | Primeiros prêmios liberados. Revisar métricas e decidir sobre a tela "Indicações". |

## 13. Decisões em aberto

- [ ] Valor do crédito para Lucro Presumido (650 proporcional, ou 400 fixo).
- [ ] Se parceiro externo pode receber crédito em outro serviço da SAVA, ou só dinheiro.
- [ ] Quem responde pelo programa internamente (registro, mensagens, pagamento).
- [ ] Nome público do programa.
