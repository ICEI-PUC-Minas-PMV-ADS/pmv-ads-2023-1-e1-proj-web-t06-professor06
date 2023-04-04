# Especificações do Projeto

As personas foram criadas a partir de entrevistas com pessoas que viajam com frequência, sejam essas viagens de lazer ou a negócios. Foram entrevistadas 5 pessoas com perfis diferentes, para que se pudesse explorar um pouco mais seus hábitos.

## Personas

### Ana Paula Brandão
![Ana Paula Brandão](./img/persona1.jpg){: .image-left }
- Idade: 30 anos
- Profissão: Advogada
- Estado Civil: Casada, sem filhos
- Interesses: Viagens internacionais, fotografia, gastronomia

Ana Paula adora viajar e já visitou diversos países da América Latina, Europa e Ásia. Ela gosta de experimentar novas comidas, conhecer diferentes culturas e tirar fotos dos lugares que visita. No entanto, ela costuma ter dificuldades em fazer a mala, principalmente quando vai viajar para lugares com climas diferentes do Brasil. Ana Paula é um pouco vaidosa e gosta de estar sempre bem vestida, especialmente para as fotos. No entanto, como tem uma agenda de trabalho agitada e está focada no desenvolvimento da sua carreira, nem sempre tem tempo para pesquisar sobre o clima e as particularidades do destino para onde está indo. Por isso, planeja mal suas mala e já teve problemas de excesso de bagagem, além de também de não levar as roupas adequadas para o clima. Isso acabou prejudicando sua experiência em algumas viagens.

**Motivação:** Ana Paula espera poder aproveitar cada minuto das suas viagens, tendo tudo aquilo que precisar na hora que precisar, mas sem ter que ficar carregando malas pesadas ou pagando excesso de bagagem. 

**Frustração**: Ana Paula não tem muita habilidade em montar looks e coordenar roupas, o que acaba dificultando ainda mais o processo de planejamento da mala.

### Marcelo Souza
![Marcelo Souza](./img/persona2.jpg){: .image-left }
- Idade: 25 anos
- Profissão: Estudante de Engenharia
- Estado Civil: Solteiro
- Interesses: Viagens de aventura, trilhas, acampamentos, esportes radicais

Marcelo adora viajar para lugares que ofereçam aventura e desafio. Ele gosta de fazer trilhas, acampar e praticar esportes radicais, como escalada e rapel. Já viajou para diversos lugares do Brasil e da América Latina, mas também já fez algumas viagens para a Europa e a Ásia. Ele costuma levar uma mochila grande em suas viagens e tem habilidade em arrumar seus equipamentos e utensílios de forma compacta e organizada. Marcelo é um cara bastante pragmático. Sabe que algumas roupas e utensílios podem ser usados várias vezes e não vê problemas em ter que lavar suas roupas durante a viagem. Seu lema é curtir a viagem sem estresse.

**Motivação**: Marcelo curte planejar a sua viagem. No entanto, seus registros de viagem não são muito organizados e ele acaba não aproveitando a experiência da viagem anterior no planejamento da nova viagem. Ele busca alguma forma de aproveitar essas experiências anteriores de alguma forma.

**Frustração**: Marcelo encara qualquer aventura que aparece na sua viagem. Ele não gosta, porém, de perder alguma dessas aventuras por estar despreparado, isto é, por ter esquecido algo que seria importante nesses momentos.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
