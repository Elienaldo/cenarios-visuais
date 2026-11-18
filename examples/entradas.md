# Exemplos de entrada

Os exemplos abaixo são fictícios e ilustram como iniciar uma conversa. As perguntas são possibilidades para testar o comportamento da skill.

## Acompanhar um pedido sem confirmação

```text
$cenarios-visuais Quero entender por que algumas pessoas abrem o chat logo depois de comprar.
```

A entrada indica um comportamento, mas ainda falta saber o que aconteceu em um caso concreto. Uma pergunta útil seria: “Na última vez que alguém abriu o chat depois de comprar, o que essa pessoa queria confirmar?”.

## Retomar o envio de um comprovante

```text
$cenarios-visuais Uma prestadora precisa enviar um comprovante antes do fim do dia para receber um reembolso. No celular, ela escolhe o arquivo, perde a conexão e volta à lista de despesas. Como a tela só mostra a palavra “pendente”, ela não sabe se o comprovante chegou nem se deve enviar de novo. Para evitar duplicidade, espera até o dia seguinte e pede ajuda. Quero mostrar a situação atual e avaliar uma forma de retomar o envio.
```

Já dá para esboçar o percurso. Em seguida, vale testar a diferença entre perder a conexão antes do envio e perder a conexão depois dele, quando o comprovante pode já ter sido recebido. Se essa distinção não estiver clara na pesquisa, registre-a como hipótese para validar.
