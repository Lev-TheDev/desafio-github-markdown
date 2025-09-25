# Desafio de Projeto: Git, GitHub e Markdown 👽

Olá! Este é o repositório oficial do **Desafio de Projeto GitHub Markdown** focado em praticar os fundamentos de Git, GitHub e a linguagem de formatação Markdown.

O principal objetivo aqui é simular um ambiente de colaboração real, passando por todas as etapas essenciais do fluxo de trabalho com Git: desde a clonagem de um repositório até a abertura de _Issues_ e _Pull Requests_.

---

## 🚀 Sobre o Desafio

Este projeto foi criado para aplicar de forma prática os conhecimentos adquiridos sobre:
* **Git:** Comandos essenciais como `clone`, `branch`, `commit`, `add`, e `push`.
* **GitHub:** Colaboração através de _Issues_, _Pull Requests_ (PRs) e gerenciamento de repositórios.
* **Markdown:** Formatação de texto para criar documentações claras e bem estruturadas como esta.

---

## 🛠️ Instruções para Colaboradores

Se você foi adicionado como colaborador, siga os passos abaixo para fazer sua primeira contribuição. Este guia irá orientá-lo em todo o processo.

### Passo 1: Clonar o Repositório

Primeiro, você precisa criar uma cópia deste repositório na sua máquina local. Para isso, utilize o comando `git clone`.

Abra seu terminal ou Git Bash e execute o comando abaixo, substituindo `<URL_DO_REPOSITORIO>` pela URL SSH ou HTTPS do projeto.

```
# Clone usando HTTPS
git clone [https://github.com/SEU-USUARIO/desafio-github-markdown.git](https://github.com/SEU-USUARIO/desafio-github-markdown.git)

# Ou clone usando SSH
git clone git@github.com:SEU-USUARIO/desafio-github-markdown.git

# Após clonar, navegue para a pasta do projeto
cd desafio-github-markdown
```

### Passo 2: Criar uma Nova Branch
Nunca trabalhe diretamente na branch main ou master. Crie sempre uma branch específica para suas alterações. Isso mantém o projeto organizado e evita conflitos.

Use o comando `git checkout -b NovaBRanch` para criar e já mudar para a nova branch.

# Crie uma branch com um nome descritivo (ex: adicionar-seu-nome)
git checkout -b feature/adicionar-meu-nome
Dica: Usar prefixos como feature/, fix/ ou docs/ ajuda a identificar o propósito da branch.

### Passo 3: Realizar Alterações e Commits
Agora é a sua vez de contribuir! Faça alguma alteração no projeto. Por exemplo, adicione seu nome em uma seção de "Participantes" neste README.md.

Após fazer as alterações, use os comandos `git add` para preparar os arquivos e `git commit` para salvá-los no histórico da sua branch.

# Adicione todos os arquivos modificados para a área de "stage"
`git add .`

# Grave as alterações com uma mensagem de commit clara e objetiva
`git commit -m "Docs: Adiciona Fulano de Tal à lista de participantes"`

### Passo 4: Enviar as Alterações para o GitHub
Com suas alterações "commitadas", envie sua branch para o repositório remoto no GitHub com o comando `git push`.

# O '-u origin' define o rastreamento da sua branch local com a remota
`git push -u origin feature/adicionar-meu-nome`

### Passo 5: Abrir um Pull Request (PR)
Ótimo, seu código já está no GitHub! O último passo é solicitar que suas alterações sejam incorporadas à branch main. Isso é feito através de um Pull Request.

1. Acesse a página do repositório no GitHub.
2. O GitHub irá detectar que você enviou uma nova branch e mostrará um aviso com um botão "Compare & pull request". Clique nele.
3. Adicione um título claro e uma descrição detalhada para o seu PR, explicando o que você fez.
4. Clique em "Create pull request".

Pronto! Agora o dono do repositório poderá revisar suas alterações, fazer comentários e, finalmente, aprová-las (fazer o merge).

-----

💡 Como Abrir uma Issue
Se você encontrou um problema, tem uma dúvida ou uma sugestão de melhoria, o lugar certo para discutir isso é em uma Issue.

1. Na página do repositório, clique na aba "Issues".
2. Clique no botão verde "New issue".
3. Escreva um título informativo e um comentário detalhado descrevendo a issue.
4. Clique em "Submit new issue".

As issues são fundamentais para rastrear tarefas e organizar a comunicação do projeto.

------

Feito por [Jhonathan/Lev-TheDev] 💞
