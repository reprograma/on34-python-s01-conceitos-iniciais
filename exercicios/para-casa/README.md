# Exercício de Casa 🏠 

### Atividades de GitHub: Fork, Pasta e README

#### Fazer Fork do Repositório da Aula

1. **Acessar o Repositório da Aula**:
   - Vá para o repositório da aula no GitHub https://github.com/reprograma/on34-python-s01-conceitos-iniciais

2. **Fazer Fork do Repositório**:
   - No canto superior direito da página do repositório, clique no botão `Fork`.

#### Clonar o Repositório Forkado para o Seu Computador

1. **Abrir o Terminal ou Prompt de Comando**.

2. **Clonar o Repositório Forkado**:

   - Navegue até o diretório onde você deseja clonar o repositório.

   - Execute o comando:

     ```sh
     git clone https://github.com/seu-usuario/reprograma/on34-python-s01-conceitos-iniciais
     ```

     

####  Criar uma Pasta com Seu Nome

1. **Navegar até o Diretório do Repositório Clonado**:

   ```sh
   cd on34-python-s01-conceitos-iniciais
   ```

2. **Criar uma Pasta com Seu Nome**:

   - No terminal:

     ```sh
     mkdir <seu-nome>
     ```

     Substitua `<seu-nome>` pelo seu próprio nome (sem espaços).

#### Adicionar um README.md na Pasta Criada

1. **Navegar até a Pasta Criada**:

   ```sh
   cd <seu-nome>
   ```

2. **Criar um Arquivo README.md**:

   - No terminal:

     ```sh
     echo README.md
     ```

   - Ou, se estiver usando um editor de texto, crie um arquivo chamado `README.md` dentro da pasta.

3. **Editar o Arquivo README.md**:

   - Abra o arquivo `README.md` em um editor de texto (como VSCode ou Notepad).
   - Adicione conteúdo divertido e motivador sobre você. Aqui está um exemplo:

```markdown
# Olá, Mundo! 🌍

Bem-vindo ao meu perfil GitHub! Meu nome é Jenifer e aqui está um pouco sobre mim de uma forma divertida e motivadora:

## Sobre Mim 🧑‍💻

- 🎓 **Formação**: Sou formado(a) em Tecnologia da Informação e Análises e Desenvolvimento de Software.
- 🛠 **Habilidades**: Adoro programar em Python, Java, JavaScript e explorar novas tecnologias.
- 🎨 **Hobbies**: Nas horas vagas, gosto de ler e jogar com meus filhos.
- 🌟 **Objetivos**: Meu objetivo é ficar rica, bricadeira rs, tenho vários mas quero muito ir a Disney.

## Curiosidades Divertidas 🎉

- 🐶 Tenho um cachorro chamado Ferdinando que adora correr no parque.
- 🍕 Meu prato favorito é pizza, especialmente de toscana.
- 🌍 Sonho em viajar pelo mundo e conhecer diferentes culturas e principalmente ir a Disney.

## Objetivos ao terminar o curso

- Criar uma startup para análise de dados 

Espero que tenha gostado de saber um pouco mais sobre mim! Vamos nos conectar e construir algo incrível juntos!

[LinkedIn](#) | [Twitter](#) | [Instagram](#)

---
*Feito com ❤️ por Jenifer Plácido*
```

4. **Salvar o Arquivo** após editar.

####  Comitar e Enviar as Mudanças para o GitHub

1. **Adicionar a Pasta e o README.md ao Staging Area**:

   ```sh
   git add <seu-nome>/README.md
   ```

2. **Fazer o Commit das Mudanças**:

   ```sh
   git commit -m "Adicionei README.md com informações divertidas na pasta <seu-nome>"
   ```

3. **Enviar (Push) as Mudanças para o GitHub**:

   ```sh
   git push origin main
   ```

####  Criar um Pull Request

1. **Acessar o Repositório Forkado no GitHub**.
2. **Criar um Pull Request**:
   - Clique no botão "Pull request".
   - Clique no botão "New pull request".
   - Compare suas mudanças com o repositório original.
   - Adicione uma descrição ao pull request explicando o que você fez.
   - Clique em "Create pull request".


#### Entrega da atividade

Copie o link do seu pull request e cole na entrega de atividade da S01 no classroom

### Resumo das Atividades

1. **Fazer fork** do repositório da aula no GitHub.
2. **Clonar o repositório forkado** para o seu computador.
3. **Criar uma pasta** com seu nome dentro do repositório.
4. **Adicionar um README.md** com informações divertidas sobre você dentro da pasta.
5. **Adicionar, comitar e enviar** as mudanças para o GitHub.
6. **Criar um pull request** para o repositório original da aula.



Terminou o exercício? Dá uma olhada nessa checklist e confere se tá tudo certinho, combinado?!

- [ ] Fiz o fork do repositório.
- [ ] Clonei o fork na minha máquina (`git clone url-do-meu-fork`).
- [ ] Resolvi o exercício.
- [ ] Adicionei as mudanças. (`git add .` para adicionar todos os arquivos, ou `git add nome_do_arquivo` para adicionar um arquivo específico)
- [ ] Commitei a cada mudança significativa ou na finalização do exercício (`git commit -m "Mensagem do commit"`)
- [ ] Pushei os commits na minha branch (`git push origin nome-da-branch`)
- [ ] Criei um Pull Request seguindo as orientaçoes que estao nesse [documento](https://github.com/mflilian/repo-example/blob/main/exercicios/para-casa/instrucoes-pull-request.md).
