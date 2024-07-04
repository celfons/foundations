# Plano de Estudos para Certificação GitHub Foundations

Este plano de estudos é projetado para preparar você para a certificação GitHub Foundations em 30 dias, com exemplos práticos para cada tópico sugerido.

## Semana 1: Introdução ao Git e GitHub

**Objetivo:** Compreender os conceitos básicos de controle de versão, Git e GitHub.

### Dia 1-2:
- **Estudo:** Conceitos de controle de versão e controle de versão distribuído.
  - **Exemplo:** Leia sobre controle de versão no [Microsoft Learn](https://learn.microsoft.com/en-us/training/paths/github-fundamentals/).
  - **Prática:** Crie um documento simples e salve diferentes versões dele manualmente para entender o conceito de versionamento.

### Dia 3-4:
- **Estudo:** Comandos básicos do Git: commits, branches, merges.
  - **Exemplo:** Assista a tutoriais no [LinkedIn Learning](https://www.linkedin.com/learning/paths/prepare-for-the-github-foundations-certification).
  - **Prática:** No terminal, execute:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    git branch new-feature
    git checkout new-feature
    git merge new-feature
    ```

### Dia 5-7:
- **Estudo:** Conceitos de repositórios, commits, branches no GitHub.
  - **Exemplo:** Crie um repositório no GitHub e explore as abas de "Code", "Issues", "Pull requests".
  - **Prática:** Crie um repositório no GitHub, faça um commit e crie uma branch:
    ```bash
    git remote add origin <URL do repositório>
    git push -u origin master
    git checkout -b feature-branch
    git push origin feature-branch
    ```

## Semana 2: Trabalhando com Repositórios GitHub e Recursos de Colaboração

**Objetivo:** Aprender a trabalhar com repositórios GitHub e utilizar recursos de colaboração.

### Dia 8-9:
- **Estudo:** Clonar, forkar e criar pull requests.
  - **Exemplo:** Leia sobre pull requests na [documentação do GitHub](https://docs.github.com/en/pull-requests).
  - **Prática:** Clone um repositório, faça uma alteração e crie um pull request:
    ```bash
    git clone <URL do repositório>
    cd <nome do repositório>
    git checkout -b new-feature
    # Faça alterações no código
    git add .
    git commit -m "Add new feature"
    git push origin new-feature
    # Crie um pull request no GitHub
    ```

### Dia 10-11:
- **Estudo:** Issues, labels e milestones.
  - **Exemplo:** Crie uma issue no seu repositório e adicione labels e milestones.
  - **Prática:** No GitHub, vá até a aba "Issues" e crie uma nova issue. Adicione uma label e um milestone.

### Dia 12-14:
- **Estudo:** GitHub Actions e GitHub Pages.
  - **Exemplo:** Configure uma ação simples no GitHub Actions para rodar testes automatizados.
  - **Prática:** Crie um arquivo `.github/workflows/main.yml`:
    ```yaml
    name: CI
    on: [push]
    jobs:
      build:
        runs-on: ubuntu-latest
        steps:
          - uses: actions/checkout@v2
          - name: Run a one-line script
            run: echo Hello, world!
    ```
  - Publique uma página no GitHub Pages:
    - Vá até as configurações do repositório, habilite o GitHub Pages e selecione a branch `main`.

## Semana 3: Desenvolvimento Moderno e Gerenciamento de Projetos

**Objetivo:** Entender o desenvolvimento moderno e como gerenciar projetos no GitHub.

### Dia 15-16:
- **Estudo:** GitHub Projects.
  - **Exemplo:** Crie um projeto no GitHub e organize tarefas.
  - **Prática:** Vá até a aba "Projects" no seu repositório e crie um novo projeto. Adicione colunas e cartões para organizar tarefas.

### Dia 17-18:
- **Estudo:** Templates de repositório e respostas salvas.
  - **Exemplo:** Crie um template de repositório.
  - **Prática:** Vá até as configurações do repositório e marque a opção "Template repository". Crie um novo repositório a partir deste template.

### Dia 19-21:
- **Estudo:** Insights de projetos e fluxos de trabalho.
  - **Exemplo:** Analise insights de um projeto.
  - **Prática:** Vá até a aba "Insights" no seu repositório e explore as métricas disponíveis. Configure um fluxo de trabalho no GitHub Actions para automatizar tarefas.

## Semana 4: Privacidade, Segurança, Administração e Comunidade GitHub

**Objetivo:** Garantir a segurança da conta, entender a administração do GitHub e os benefícios da comunidade.

### Dia 22-23:
- **Estudo:** Autenticação e segurança, incluindo 2FA e permissões de acesso.
  - **Exemplo:** Configure 2FA na sua conta GitHub.
  - **Prática:** Vá até as configurações da sua conta GitHub e habilite a autenticação de dois fatores (2FA).

### Dia 24-25:
- **Estudo:** Administração de repositórios e configurações de privacidade.
  - **Exemplo:** Habilite/desabilite recursos e configure proteções de branch.
  - **Prática:** Vá até as configurações do repositório e configure proteções de branch para a branch `main`.

### Dia 26-27:
- **Estudo:** Benefícios da comunidade GitHub, GitHub Sponsors e InnerSource.
  - **Exemplo:** Participe de um projeto open source.
  - **Prática:** Encontre um projeto open source no GitHub, faça um fork, contribua com uma alteração e crie um pull request.

### Dia 28-30:
- **Revisão:** Revise todos os tópicos estudados.
  - **Prática:** Faça simulados e exercícios práticos para reforçar o conhecimento. Utilize recursos como [GitHub Docs](https://docs.github.com/) e [Microsoft Learn](https://learn.microsoft.com/en-us/training/paths/github-fundamentals/).

## Recursos Adicionais
- **Microsoft Learn:** [GitHub Foundations Learning Path](https://learn.microsoft.com/en-us/training/paths/github-fundamentals/)
- **LinkedIn Learning:** [Prepare for the GitHub Foundations Certification](https://www.linkedin.com/learning/paths/prepare-for-the-github-foundations-certification)
- **Documentação GitHub:** [GitHub Docs](https://docs.github.com/)

## Dicas Finais
- **Prática Regular:** Pratique regularmente no GitHub para reforçar o aprendizado.
- **Participação em Comunidades:** Participe de comunidades e fóruns para tirar dúvidas e compartilhar conhecimento.
- **Revisão Constante:** Revise os conceitos regularmente para garantir que estão bem compreendidos.

Seguindo este plano de estudos com exemplos práticos, você estará bem preparado para a certificação GitHub Foundations em 30 dias. Boa sorte!
