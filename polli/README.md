#README.md
Objetivo: Fazer atividade criando um Fork do Repositório da Aula 01 (29/06/2024)

Passo 1:
   - Acessar no GitHub: https://github.com/reprograma/on34-python-s01-conceitos-iniciais
   - Clicar no botão "fork" (canto superior direito destacado em vermelho, na figura abaixo);
   ![image](https://github.com/Polliferraz/on34-python-s01-conceitos-iniciais/assets/171433469/bc775f0b-e1b6-41c8-8040-b950afae3b28)
   - Abrirá a página "criar um fork novo":
      • Contendo o proprietário e o nome do repositório;
      • Uma descrição opcional;
      • Clique em "Criar Fork".
     
Passo 2: 
   - Clonar o Repositório Fork para o Seu Computador: copie a URL (conforme destaques em vermelho, na figura a abaixo);
     ![image](https://github.com/Polliferraz/on34-python-s01-conceitos-iniciais/assets/171433469/f76206bf-2557-40af-a1e4-39eba0f3999f)
   - Abra o Terminal ou Prompt de Comando: Clique com botão direito do mouse na pasta de sua preferência, e clique em "Open Git Bash here";
   - Execute o comando: git clone <cole aqui URL copiada anteriormente>

Passo 3:
    - Criar uma Pasta com Seu Nome no Diretório do Repositório Clonado:
    - Execute o comando: cd on34-python-s01-conceitos-iniciais (Objetivo do comando "cd": retornar ao diretório indicado)
    - No terminal, execute o comando: mkdir <seu-nome> (Objetivo do comando "mkdir": criar pasta)
   
Passo 4: 
    - Criar um Arquivo README.md
    - Navegar até a Pasta Criada, por meio da execução do comando "cd"
    - Execute o comando: echo "# README.md" > README.md (Objetivo desse formato de comando "echo": criar aquivo com conteúdo)
  
Passo 5:
   - Editar o Arquivo README.md:
   - Abra o arquivo README.md em um editor de texto (como VSCode ou Notepad).
   - Adicione conteúdo.
   - Salvar o Arquivo após editar.

Passo 6: 
   - Criar uma cópia com todas as Mudanças e edições do projeto para o GitHub (commit)
   - Adicionar a Pasta e o README.md ao Staging Area: Execute o comando: git add <seu-nome>/README.md (Objetivo do comando "git
   add .": adicionar os arquivos na área de apresentação)
   - Fazer o Commit das Mudanças: Execute o comando: git commit -m "Adicionei README.md com informações divertidas na pasta <seu-nome>"

Passo 7:
   - Enviar as Mudanças para o GitHub (Push)
   - Execute o comando: git push origin main

Passo 8:
   - Criar um Pull Request: Atualiza o repositório local com as mudanças do repositório remoto.
   - Acessar o Repositório Forkado no GitHub
   - Criar um Pull Request:
       • Clique no botão "Pull request".
       • Clique no botão "New pull request".
       • Compare suas mudanças com o repositório original.
       • Adicione uma descrição ao pull request explicando o que você fez.
       • Clique em "Create pull request".

Passo 9:
   - Entrega da Atividade: Copie o link do seu pull request e cole na entrega de atividade da S01 no Classroom.

     


---
