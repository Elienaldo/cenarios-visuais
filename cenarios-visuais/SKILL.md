---
name: cenarios-visuais
description: Ajuda o Engenheiro de Produto a transformar uma necessidade real em um cenário ilustrado na descoberta, antes da implementação. Use ao investigar onde uma experiência trava, mostrar como alguém usaria uma funcionalidade ou comparar o fluxo atual com uma proposta para conversar com usuários.
disable-model-invocation: true
---

# Cenários Visuais

Ilustre o fluxo, encontre lacunas e valide a experiência antes do código.

## Comece com o que a pessoa trouxe

Aceite entradas abertas em linguagem comum, de uma frase a um relato longo, incluindo notas de pesquisa e descrições de fluxos. Leia todo o material antes de perguntar e aproveite o que já está respondido. Exemplo: “Quero entender por que é tão difícil remarcar uma consulta pelo celular”. Se a pessoa só chamar a skill, pergunte: “O que alguém está tentando fazer e o que torna isso difícil hoje?”. Avalie se já consegue identificar quem vive a situação, o que precisa resolver naquele momento, o que acontece hoje ou levou à ideia, e qual resultado teria valor para a pessoa. Se faltar algo que mude a história, faça uma pergunta curta por vez e reavalie após cada resposta. Dê preferência a “Como foi a última vez?” e siga o episódio até a consequência e o desfecho. Assim que houver material para uma primeira versão compreensível, pare de perguntar e monte o cenário. Se um detalhe relevante for desconhecido e quem pediu não puder esclarecê-lo, registre a lacuna e avance com as partes sustentadas. Evite formulários, jargão e perguntas sobre sistemas, arquitetura ou implementação.

### Dê continuidade até a primeira entrega

Quando precisar de uma resposta, use um recurso de pergunta que mantenha o trabalho em andamento, se disponível. Faça uma pergunta por vez e diga em uma frase o que ela ajuda a esclarecer. Se tiver de aguardar em outra mensagem, indique que o cenário está em andamento e que será retomado assim que a pessoa responder.

Ao receber a resposta, retome a necessidade, o relato e as decisões já registradas. Uma resposta curta pode ser a continuação da descoberta mesmo sem a pessoa chamar a skill de novo. Faça outra pergunta somente se faltar um detalhe que altere o percurso ou a conclusão. Se já houver base suficiente, avance no mesmo turno para a primeira versão visual e para as perguntas de validação. Uma pergunta de descoberta, por si só, não é a entrega. Quando puder avançar, marque as lacunas restantes e mostre o cenário ao usuário.

## Conduza a descoberta

1. **Encontre a necessidade imediata.** Identifique quem estava tentando fazer o quê, por que naquele momento, o que tentou, onde travou e o que isso custou ou impediu. Registre de onde veio a informação como observada, relatada ou hipótese. Se só houver uma ideia de solução, investigue a situação que motivou a ideia. Evidência ausente vira hipótese ou pergunta de pesquisa. Preserve o anonimato no material apresentado.
2. **Escreva o personagem e a simulação.** Personagem é a persona (contexto, habilidades, conhecimentos e limitações relevantes) com uma motivação concreta. Defina um resultado que a própria pessoa reconheceria. Na simulação, acompanhe o percurso do gatilho até conclusão, abandono ou retomada. Inclua ações fora do produto quando elas mudarem o fluxo. Se outra persona tiver objetivo ou percurso diferente, escreva outro cenário. Quando houver indício de rejeição, registre quem evitaria o produto e por quê como Não-Persona. Distinga falta de necessidade de barreiras removíveis, inclusive de acessibilidade.
3. **Procure lacunas antes de desenhar.** Em cada passagem, verifique o que a pessoa sabe, por que tomaria a próxima ação, o que precisa ter em mãos, o que vê em seguida e se isso basta para avançar. Procure passos pulados, informações faltantes, mudanças de canal, hesitações, interrupções, erros e situações extremas plausíveis. Simule pelo menos uma quebra relevante e siga seu efeito até a recuperação, a saída ou uma lacuna sem resposta. Se a mesma lacuna surgir na proposta, mostre-a. Converta lacunas e suposições decisivas em perguntas de pesquisa.
4. **Defina padrões obrigatórios de usabilidade.** Expresse cada um como uma condição verificável da experiência e vincule aos passos e às lacunas. Exemplo: “Ao voltar depois de uma interrupção, a pessoa sabe o que ficou pendente e como retomar”. Marque cada condição como atendida na simulação, com lacuna ou pendente de evidência. Leve essas condições para as próximas decisões de design e arquitetura sem prescrever soluções técnicas.
5. **Ilustre para o usuário final.** Crie uma sequência visual com persona em ação, situação reconhecível, legendas curtas e equivalentes em texto. Se houver fluxo existente com atrito, conte a História do antes. Coloque atual e proposto nos mesmos marcos quando existir uma proposta comparável. Quando ainda não houver proposta, ilustre o que a pessoa vive hoje e deixe as perguntas em aberto. Para produto novo, mostre alternativas atuais quando conhecidas. Mantenha a sequência detalhada como apoio para que os quadros possam ser simples sem omitir transições da simulação. Quando uma escolha muda a experiência e o ambiente permitir, ofereça um percurso com escolhas e consequências visíveis. Siga o [guia de entrega visual](guia-visual.md).
6. **Valide com a pessoa.** Mostre a história atual primeiro, peça que ela a corrija e depois apresente a proposta. Em cada ponto decisivo, pergunte o que faria e esperaria em seguida, onde ainda travaria e como saberia que resolveu. Evite perguntas que sugiram a saída ou peçam apenas aprovação. Registre o retorno real, o que mudou e o que ainda é incerto. Sem participação de usuários, marque “Pendente de validação”. Respostas simuladas são material para preparar a pesquisa.
7. **Olhe além deste fluxo.** Quando a dor revelar uma oportunidade de longo prazo, registre a hipótese, o outro contexto ou perfil que poderia se beneficiar e a evidência que justificaria investigá-la.

## Antes de entregar

- A história começa na necessidade da pessoa e mostra uma consequência concreta do atrito.
- É possível acompanhar cada ação e o que acontece em seguida. O documento inclui uma falha plausível e o desfecho ou a lacuna.
- O visual mostra quem está agindo, e a legenda permite entender a cena sem depender da imagem.
- Atual, proposta, evidência, hipóteses e situação da validação estão claros. Os padrões de usabilidade foram aplicados nos pontos correspondentes.
- O resultado é consultável pelo usuário final em linguagem comum. Entregue o visual e as perguntas de validação. Mantenha evidências, lacunas e oportunidades no material de apoio.
