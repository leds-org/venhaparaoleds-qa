# Desafio QA - LEDS
*Bem-vindo!* 👋

Neste desafio, você terá a oportunidade de demonstrar que possui as habilidades necessárias para atuar no time de QA do laboratório.

# Contextualização

A aplicação **coLAB** tem como objetivo o gerenciamento de projetos e dados relacionados. Para este desafio, você deverá focar nas funcionalidades principais descritas no backlog do projeto, cobrindo o cadastro, visualização, edição e deleção de **Projetos**, **Pessoas**, **Bolsas** e **Financiadores**.

Você deve utilizar a aplicação disponível nos repositórios:
- [coLAB - Módulo Backend (.NET)](https://github.com/sofialctv/coLAB)
- [coLAB - Módulo Frontend (Vue.js)](https://github.com/sofialctv/coLAB-frontend)

## Funcionalidades a serem testadas

Com base no backlog da aplicação **coLAB**, você deverá desenvolver testes automatizados para garantir o correto funcionamento das seguintes features:

| #  | Feature               |
|----|--------------------|
| 1  | Cadastrar Projeto  |
| 2  | Visualizar Projeto |
| 3  | Editar Projeto     |
| 4  | Deletar Projeto    |
| 5  | Cadastrar Pessoa   |
| 6  | Visualizar Pessoa  |
| 7  | Editar Pessoa      |
| 8  | Deletar Pessoa     |
| 9  | Cadastrar Bolsa    |
| 10 | Visualizar Bolsa   |
| 11 | Editar Bolsa       |
| 12 | Deletar Bolsa      |
| 13 | Cadastrar Financiador |
| 14 | Editar Financiador    |
| 15 | Deletar Financiador   |

# O que deve ser entregue?

1. **Automação de Testes (obrigatoriamente utilizando Cypress)**: Desenvolva testes automatizados cobrindo as funcionalidades listadas acima. 

    Certifique-se de:

   - Implementar testes end-to-end para as principais rotas da aplicação.
   - Seguir a abordagem **AAA (Arrange, Act, Assert)** para estruturar seus testes.
   - Testar as interações com a API para **cadastrar**, **visualizar**, **editar** e **deletar** dados.

2. **Manipulação de APIs**: Certifique-se de que os testes realizam as requisições apropriadas e verificam as respostas corretamente (códigos de status, conteúdo retornado, etc.).

3. **Relatórios de Bugs utilizando GitHub Issues**: 
   - Garanta que seus testes estejam organizados e fáceis de entender.
   - Caso encontre algum comportamento inesperado ou melhoria a ser implementada, crie um **relatório de bug** detalhado, incluindo:
     - Passos para reproduzir o problema ou descrição da melhoria a ser implementada.
     - Comportamento esperado vs. comportamento observado.
     - Evidências como screenshots, GIFs ou logs.

4. **Teste de Dependências**: Garanta que os testes tenham tratamento adequado para dados dependentes (ex.: não deletar um projeto que está associado a uma pessoa).

## Diferenciais (pontos bônus)

- **Testes Unitários no Backend**: Se possível, adicione testes unitários no backend da aplicação coLAB.
- **SonarQube**: Integre sua solução com o **SonarQube** para garantir a qualidade do código.
- **Pipeline no GitHub**: Configure um pipeline de CI/CD no GitHub para executar os testes e análise de código automaticamente.
- **Gestão das tarefas com GitHub Projects**: Gerencie as etapas do desafio e quais tarefas você precisa desenvolver até a entrega utilizando as funcionalidades do GitHub Projects. 
- **Análise de melhorias de código na aplicação coLAB**: Como QA, identifique possíveis melhorias que poderiam ser implementadas nas aplicações do coLAB.
- **Implementar usando Docker**: Configure sua aplicação de testes com Docker. 

# Como entregar
1. Faça um **fork** do repositório `venhaparaoleds-qa`. Nesse fork esperamos encontrar uma documentação completa indicando os testes automatizados e o relatório de bugs.
2. Abra um **pull request (PR)** do seu fork para o nome repositório com o seu nome como título. Assim conseguimos te localizar melhor e ver que você já finalizou o desafio!

🚨 **Atenção**: você deve enviar apenas o código fonte. Não serão aceitos códigos compilados.

>  *Observação: Para utilizar a aplicação coLAB, também faça **forks** dos repositórios. Não abra PRs para eles.*

## Avaliação

Sua solução será avaliada levando em conta os seguintes critérios:

| Critério                                             | Valor  |
|------------------------------------------------------|--------|
| Cobertura dos testes automatizados                   | 20     |
| Tratamento de dependências entre testes              | 20     |
| Legibilidade e aplicação de boas práticas dos testes | 15     |
| Relatório de Bugs                                    | 15     |
| Documentação geral da resolução do desafio           | 10     |
| **Total**                                            | **80** |


## Bônus
Você pode **aumentar sua pontuação** implementando os seguintes diferenciais:

| Critério                                                                                     | Valor  |
|----------------------------------------------------------------------------------------------|--------|
| Testes Unitários no Backend                                                                  | 20     |
| Criar um pipeline completo com execução de testes e análise de qualidade (SonarQube + CI/CD) | 20     |
| Implementar análise de qualidade de Código com SonarQube                                     | 10     |
| Implementar pipeline de CI/CD no GitHub                                                      | 10     |
| Dockerização da solução                                                                      | 10     |
| Gestão das tarefas com GitHub Projects                                                       | 5      |
| Análise de melhorias de código na aplicação coLAB                                            | 5      |
| **Total**                                                                                    | **80** |


A pontuação final será calculada somando os critérios obrigatórios e os diferenciais implementados corretamente.

# Penalizações

Você será desclassificado se:

1. Enviar uma solução que não funcione.
2. Não cumprir os critérios da seção **Avaliação**.
3. For identificado plágio.
   
***Que a força esteja com você. Boa sorte!***

<div align="left">
</div>

###

<br clear="both">

<div align="center">
  <a href="https://www.linkedin.com/school/ledsifes" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="40" alt="linkedin logo"  />
  </a>
  <a href="https://www.instagram.com/ledsifes/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="40" alt="instagram logo"  />
  </a>
  <a href="https://www.youtube.com/@ledsifes/?sub_confirmation=1" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="40" alt="youtube logo"  />
  </a>
</div>

###
