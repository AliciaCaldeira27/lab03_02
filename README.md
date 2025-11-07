# Lab03 02 - Containers e Integração Contínua com Docker e GitHub Actions

Este repositório apresenta a implementação da **Atividade II do Laboratório 03** da disciplina **Web Academy CI/CD**, com o foco em consolidar o uso de **containers Docker** e **pipelines automatizados** de integração contínua (CI) utilizando o **GitHub Actions** e o **Docker Hub**.

---

## Objetivo da Atividade

O principal objetivo desta etapa foi aprofundar o uso de pipelines de CI, configurando um fluxo completo de **build, teste e deploy automatizado em container**.  
A proposta envolveu o uso do **Docker** para empacotar a aplicação e o **GitHub Actions** para automatizar a criação e publicação da imagem no **Docker Hub**.

---

## Implementação Realizada

Durante o desenvolvimento da atividade, foram realizadas as seguintes ações:

- Preparação e configuração do projeto Node.js para ser executado dentro de um **container Docker**.
- Criação do arquivo **Dockerfile**, definindo todas as etapas de build e execução da aplicação.
- Testes locais da imagem Docker, garantindo que a aplicação rodasse corretamente na porta `3000`.
- Criação de um arquivo **.gitignore** para evitar o versionamento de diretórios como `node_modules` e `dist`.
- Configuração de um workflow **docker_build.yml** dentro do diretório `.github/workflows`, automatizando o processo de build e push da imagem para o **Docker Hub**.
- Criação de segredos no repositório GitHub (`DOCKERHUB_USERNAME` e `DOCKERHUB_TOKEN`), possibilitando o login automático do pipeline.
- Envio do projeto para o GitHub e execução do **GitHub Actions**, validando o pipeline com sucesso.
- Verificação da imagem publicada no **Docker Hub**, confirmando o funcionamento de ponta a ponta.

---

## Resultados Obtidos

Ao final da atividade, foi possível:

- Executar a aplicação localmente e dentro de um container Docker.
- Automatizar o processo de build e deploy da imagem via GitHub Actions.
- Publicar a imagem com sucesso no **Docker Hub**, validando o fluxo de CI/CD com containers.

---

## Conclusão

Durante a realização desta segunda parte do laboratório, consegui compreender na prática como o uso do **Docker** e do **GitHub Actions** se complementa no processo de integração contínua. Após corrigir pequenas falhas iniciais e testar localmente cada etapa, o pipeline funcionou corretamente e a imagem foi enviada ao **Docker Hub** com sucesso. Essa experiência me permitiu consolidar o aprendizado sobre automação de builds, versionamento de imagens e publicação contínua, tornando o processo de deploy muito mais ágil, confiável e reprodutível.

Foi muito satisfatório perceber, em uma reunião da BEMOL DIGITAL, o quanto o conteúdo de CI/CD que estou aprendendo na Web Academy tem relação direta com a prática profissional. Durante a conversa, uma funcionária da área de Infraestrutura comentou que já havia tido aula com o senhor, o que reforçou ainda mais a importância e o impacto dos aprendizados que estou adquirindo. Esse momento me fez ver como teoria e prática realmente se conectam.

---

### Discente: Alicia Caldeira  
### Curso: Web Academy - UFAM
