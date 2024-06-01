```markdown
## 🤔 O Que é um Fork?

Um **fork** é uma cópia de um repositório de código que você cria na sua própria conta GitHub. Ele permite que você faça mudanças no código de forma independente, sem afetar o repositório original. Forks são frequentemente usados para contribuir com projetos de código aberto: você faz um fork do repositório, faz suas mudanças e, então, propõe essas mudanças ao projeto original através de um pull request.

## 🚀 O Que é um Pull Request?

Um **pull request (PR)** é uma maneira de propor mudanças no código de um repositório. Quando você cria um PR, está solicitando que os mantenedores do repositório original revisem e aceitem suas mudanças. É uma ferramenta fundamental para a colaboração em projetos de software, especialmente em projetos de código aberto.

## 📋 Passo a Passo para Fazer um Fork e Criar um Pull Request

### 1. Faça um Fork do Repositório 🍴

1. Vá para a página principal do repositório.
2. Clique no botão **Fork** no canto superior direito da página.
3. Isso criará uma cópia do repositório na sua conta GitHub.

### 2. Clone o Repositório Forkado 💻

Para trabalhar no código, você precisa clonar o repositório forkado para o seu computador. No terminal, execute:

```sh
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 3. Configure o Upstream 🔄

Para manter seu fork sincronizado com o repositório original, configure um repositório remoto chamado `upstream`:

```sh
git remote add upstream https://github.com/reprograma/on34-python-s01-conceitos-iniciais
git fetch upstream
```

### 4. Crie uma Nova Branch 🌿

Crie uma nova branch para trabalhar nas suas mudanças. Isso mantém o código principal limpo e organizado:

```sh
git checkout -b seu-nome
```

### 5. Faça Suas Alterações 🛠️

Faça as mudanças necessárias no código. Certifique-se de testar suas alterações antes de prosseguir.

### 6. Commit suas Alterações ✅

Adicione e commit suas alterações com uma mensagem descritiva:

```sh
git add .
git commit -m "Descrição das mudanças feitas"
```

### 7. Sincronize seu Fork (Opcional, mas Recomendado) 🔄

Antes de enviar suas mudanças, é uma boa prática sincronizar seu fork com o repositório original para evitar conflitos:

```sh
git fetch upstream
git checkout main
git merge upstream/main
```

### 8. Envie as Alterações para o Seu Repositório Forkado 🚀

Envie suas mudanças para o seu repositório forkado no GitHub:

```sh
git push origin minha-nova-funcionalidade
```

### 9. Abra um Pull Request ✨

1. Vá para o seu repositório forkado no GitHub.
2. Clique no botão **Compare & pull request**.
3. Descreva suas alterações na descrição do Pull Request.
4. Clique em **Create pull request**.

### 10. Acompanhe o Pull Request 🔍

Depois de criar o Pull Request, a professora vai revisá-lo. Ela pode solicitar alterações ou fazer perguntas sobre o seu código. Acompanhe o Pull Request e responda a quaisquer comentários ou solicitações.

## 📝 Resumo dos Comandos

```sh
# Clone o repositório forkado
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

# Configure o upstream
git remote add upstream https://github.com/reprograma/on34-python-s01-conceitos-iniciais
git fetch upstream

# Crie uma nova branch
git checkout -b SEU-NOME

# Faça suas alterações, depois adicione e commit
git add .
git commit -m "Descrição das mudanças feitas"

# Sincronize com o repositório original
git fetch upstream
git checkout main
git merge upstream/main

# Envie suas alterações
git push origin SEU-NOME
```

