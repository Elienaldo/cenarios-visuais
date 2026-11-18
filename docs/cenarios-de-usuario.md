# Skill para desenhar cenários de usuário

## Propósito

Ajudar o Engenheiro de Produto no início da descoberta (Research) a representar, com texto e ilustrações, como uma pessoa vive um problema e como poderia alcançar seu objetivo. O usuário final deve conseguir se reconhecer na história, percorrer o fluxo e dizer se a experiência proposta atende à sua necessidade antes de a equipe escrever código.

O exercício também deve ampliar a visão sobre o potencial do produto a longo prazo, revelando necessidades recorrentes e oportunidades para outros contextos e perfis.

## Objetivos

- Mostrar em um documento fácil de entender quem participa, o que acontece e em que momento a experiência trava.
- Usar IA para ilustrar as personas e os acontecimentos e ajudar o usuário a formar uma visão mental do cenário inteiro.
- Registrar a **História do antes** quando houver uma funcionalidade ou um fluxo em uso que cause atrito. Mostrar o que a pessoa faz hoje, onde encontra a lacuna e como sofre suas consequências.
- Quando uma proposta tentar corrigir um fluxo existente, confrontar visualmente o atual e o proposto e levar a comparação ao usuário para validação.
- Usar a descoberta para identificar furos na lógica e necessidades ainda não atendidas antes de qualquer implementação.

## Como conduzir a descoberta

Manter a conversa na linguagem do usuário, sem discussão técnica nem perguntas sobre sistemas ou arquitetura. Priorizar perguntas sobre situações concretas: o que motivou a pessoa, o que ela tentou, onde parou, como contornou o problema e como soube se tinha resolvido a tarefa.

Definir padrões obrigatórios de usabilidade para o cenário e aplicá-los durante a simulação. As exigências da experiência devem orientar as decisões posteriores de arquitetura. As perguntas e o documento de descoberta ficam concentrados na experiência da pessoa.

## Estrutura de cada cenário

### 1. Personagem

O personagem reúne uma **persona** e uma **motivação**.

- **Persona:** contexto, habilidades, conhecimentos prévios e limitações relevantes para a situação.
- **Motivação:** o que a pessoa deseja ou precisa no momento exato do uso, por que isso importa e em que situação o objetivo aparece.

Quando houver personas com objetivos ou motivações diferentes, comparar seus contextos e escrever histórias distintas quando essas diferenças mudarem o percurso.

### 2. Simulação

A simulação conta a história da pessoa desde a motivação até o resultado. Cada ação deve ser justificada e decorrer da situação anterior. Percorrer o fluxo integralmente, inclusive trechos difíceis, decisões, transições, tentativas frustradas e momentos de recuperação.

Ao revisar a simulação, checar se a pessoa sabe o que fazer, tem o que precisa para avançar e consegue reconhecer quando atingiu o objetivo. Questionar passos omitidos e testar situações extremas. A história precisa dar à equipe elementos para avaliar o desenho antes de discutir sua viabilidade de implementação.

## Não-Persona

Identificar quem teria razões fortes para rejeitar o produto e o que explica a rejeição. Descrever o contexto e o motivo. Investigar se a pessoa está fora do público pretendido ou se encontra uma barreira que o produto pode remover.

## Pesquisa de skills existentes

A busca encontrou referências que cobrem partes da proposta. Entre as skills consultadas, nenhuma reuniu a entrevista, a simulação completa, a ilustração do antes e do proposto e a validação com o usuário no mesmo fluxo de descoberta.

| Skill | O que aproveitar | Adaptação para esta proposta |
| --- | --- | --- |
| [conducting-user-interviews](https://www.skills.sh/refoundai/lenny-skills/conducting-user-interviews) · 1,8 mil instalações | Partir do relato da última vez que a pessoa viveu o problema. | Usar o relato para reconstruir acontecimentos e descobrir contornos, interrupções e consequências. |
| [journey-map](https://www.skills.sh/owl-listener/designer-skills/journey-map) · 2,5 mil instalações | Mapear objetivo, ações, pontos de contato e atritos por etapa, incluindo o estado atual. | Alinhar o antes e o proposto pelo mesmo objetivo e pelos mesmos momentos da história. |
| [storyboard](https://www.skills.sh/deanpeters/product-manager-skills/storyboard) · 2,7 mil instalações | Contar a história com quadros simples e fáceis de comentar. | Usar quantos quadros a história exigir e manter uma simulação detalhada numerada para preservar transições e exceções. Mostrar a proposta como hipótese, inclusive quando seu desfecho pode falhar. |
| [design-scenario](https://www.skills.sh/bateau84/skills/design-scenario) · 1 instalação | Explicitar o resultado visível para a pessoa, um caso de falha ou recuperação e as suposições relevantes. | Usar como referência metodológica complementar. A adoção registrada é pequena. |
| [scenario-storyboards](https://www.skills.sh/scenario-labs/skills/scenario-storyboards) · 980 instalações | Roteirizar primeiro, manter as mesmas referências de personagem entre os quadros e adicionar as legendas na montagem. | Usar o método para produzir ilustrações coerentes e legíveis com a ferramenta de imagem disponível. |

Contagens exibidas pelo catálogo na consulta. Para a prática de usar quadros com legendas curtas e testar o entendimento com tarefas sem induzir respostas, consulte [Storyboards Help Visualize UX Ideas](https://www.nngroup.com/articles/storyboards-visualize-ideas/) e [From Research Goals to Usability-Testing Scenarios](https://www.nngroup.com/articles/ux-research-goals-to-scenarios/), da Nielsen Norman Group.

## Primeira versão proposta

**Nome sugerido:** `cenarios-de-usuario`.

**Entrada:** um relato de uso, notas de pesquisa ou uma descrição inicial da dor. Reaproveitar o que já foi informado e perguntar somente o que muda a história.

1. **Reconstituir um episódio.** Perguntar, por exemplo: “Conte a última vez em que isso aconteceu”, “O que você esperava conseguir?”, “O que você fez quando travou?” e “Como soube se deu certo?”. Procurar também etapas fora do produto, como pedir ajuda ou recorrer a outro canal.
2. **Definir personagem e sucesso.** Registrar motivação, contexto e restrições que alteram decisões. Distinguir o que foi observado, o que foi relatado e o que é hipótese. Identificar motivos de rejeição e avaliar se são barreiras removíveis.
3. **Simular do começo ao fim.** Para cada passo, registrar o que a pessoa sabe naquele momento, o que faz e por quê, o que percebe em seguida e o que permite avançar. Incluir falha, abandono ou recuperação quando forem plausíveis. Criar outra trajetória quando a mudança de persona alterar o objetivo ou a sequência.
4. **Definir e aplicar padrões obrigatórios de usabilidade.** Escrevê-los como comportamentos verificáveis. Por exemplo: “Se a tarefa for interrompida, a pessoa consegue dizer o que já foi concluído e como retomar”. Vincular cada padrão aos passos pertinentes e marcar se a simulação o atende ou revela uma lacuna. Levar esses padrões adiante como condições para as decisões de produto e arquitetura.
5. **Ilustrar depois de revisar a história.** Entregar um documento visual com cenas numeradas, ilustrações geradas por IA, legendas em linguagem comum e uma descrição em texto para cada cena. Quando houver um fluxo atual comparável, usar os mesmos marcos, personagem e objetivo para revelar o que muda lado a lado. Se o produto for novo, registrar como a pessoa resolve a necessidade hoje, quando houver evidência.
6. **Validar sem conduzir a resposta.** Mostrar a história atual primeiro e deixar a pessoa corrigi-la. Em seguida, pedir que ela percorra a proposta e diga o que faria em cada ponto crítico, onde ainda travaria e como saberia que terminou. Registrar correções e decisões abertas. Se a conversa com usuários ainda não ocorreu, marcar a proposta como pendente de validação.
7. **Registrar oportunidades futuras.** Anotar necessidades que reaparecem em outros contextos como hipóteses de longo prazo e indicar qual observação justificaria investigá-las.

### Piloto sugerido

Aplicar a primeira versão a **um fluxo existente com atrito relatado**, com uma persona principal, um objetivo e uma interrupção realista. Isso exercita tanto a história do antes quanto a comparação.

Exemplo fictício: uma pessoa tenta remarcar uma consulta e precisa fechar a página no meio. No fluxo atual, ela volta sem conseguir saber se o horário mudou. Na proposta, ela reencontra a tarefa e entende o que está pendente e qual horário está confirmado. Durante a conversa, pedir que a pessoa aponte onde retomaria a tarefa e diga em qual horário compareceria. O roteiro deve incluir também o que ela faria se o novo horário não estivesse mais disponível.

O piloto funciona se a pessoa consegue recontar a história com suas palavras, reconhecer ou corrigir o atrito e indicar a próxima ação e o sinal de conclusão na proposta. Registrar o que falhou e revisar o cenário antes de repetir o teste.

