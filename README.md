# Introducao a Git e GitHub

## Índice

- [Git](#git)
  - [O que é o Git](#o-que-é-o-git)
  - [Como baixar o Git](#como-baixar-o-git)
  - [Como iniciar um repositório Git](#como-iniciar-um-repositório-git)
- [GitHub](#github)
  - [O que é o GitHub](#o-que-é-o-github)
  - [Como usar o GitHub](#como-usar-o-github)

---

## Git

### O que é o Git

- O Git é uma ferramenta de versionamento de projetos.
- Ele serve para manter o controle de versões, garantindo que, em caso de erro, seja possível retornar para uma versão anterior de forma segura.

### Como baixar o Git

- O Git normalmente já vem instalado em sistemas Linux e Mac.
- No Windows, é necessário baixá-lo diretamente pelo site oficial: [Link git](https://git-scm.com/)

### Como iniciar um repositório Git

1. Abra o terminal (Git Bash, CMD ou PowerShell).
2. Navegue até a pasta do seu projeto.
3. Inicie o versionamento com:
   ```bash
   git init
   ```
4. Verifique o status do repositório:
   ```bash
   git status
   ```
5. Adicione arquivos para o controle de versão:
   ```bash
   git add <arquivo>
   ```
   Ou para adicionar todos os arquivos:
   ```bash
   git add .
   ```
6. Crie um commit:
   ```bash
   git commit -m "mensagem"
   ```
7. Conecte o repositório local a um repositório remoto:
   ```bash
   git remote add origin <link-do-repositório>
   ```
8. Crie ou renomeie a branch principal:
   ```bash
   git branch -M <nome-da-branch>
   ```
9. Envie os commits para o repositório remoto:
   ```bash
   git push -u origin <nome-da-branch>
   ```

---

## GitHub

### O que é o GitHub

- O GitHub é uma plataforma de hospedagem de repositórios Git na nuvem.
- Ele facilita o armazenamento de projetos, colaboração entre desenvolvedores, controle de versão e revisão de códigos.

### Como usar o GitHub

1. **Criar uma conta:**  
   Acesse [https://github.com/](https://github.com/) e registre-se gratuitamente.

2. **Criar um novo repositório:**

   - Clique em "New Repository".
   - Defina um nome, descrição (opcional) e escolha se será público ou privado.

3. **Clonar um repositório existente:**

   ```bash
   git clone <link-do-repositório>
   ```

4. **Enviar alterações para o GitHub:**  
   Após fazer mudanças no seu projeto:

   ```bash
   git add .
   git commit -m "Descrição das alterações"
   git push
   ```

5. **Colaborar em projetos:**  
   Utilize branches e Pull Requests para trabalhar em equipe sem impactar diretamente a branch principal do projeto.

---

> **Dica:** Sempre escreva mensagens de commit claras e objetivas! Elas ajudam você e sua equipe a entenderem rapidamente o que foi alterado.

## <!-- Guia pa tirar duvidas futuras -->

# atividade do modulo

## realização

feito a implementação dos arquivos da atividade anterior para comparação no pull
