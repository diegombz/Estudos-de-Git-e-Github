# Comandos Básicos :keyboard:

- ```
  git init
  ```

Esse comando **inicia um novo repositório Git** em um diretório, para criar um novo repositório enquanto *especifica o nome do projeto*, use o seguinte comando:

- ```
  git init [nome do projeto]
  ```

---

- ```
  git add nome_do_arquivo
  ```

Esse comando é usado para **preparar alterações em arquivos**, preparando-os para o próximo commit:

---

- ```
  git commit -m "Adicionar novo recurso"
  ```

Use esse comando para **criar uma mensagem de commit para as alterações**, tornando-as parte do histórico do seu projeto:

---

- ```
  git status
  ```

Esse comando **exibe informações importantes sobre as modificações e o status** de preparação de seus arquivos.

---

- ```
  git log
  ```

Em sua forma básica, o **git log** permite visualizar uma lista cronológica do histórico de commits:

---

- ```
  git rm arquivo1.txt
  ```

Esse comando **remove arquivos do seu diretório de trabalho** e prepara a remoção para o próximo commit.

---

- ```
  git mv arquivo1.txt arquivo2.txt
  ```

Use esse comando para **renomear e mover arquivos em seu diretório de trabalho**, para **mover** um arquivo para um diretório diferente, digite:

- ```
  git mv arquivo1.txt nova_pasta/
  ```

---

## **Comandos de repositório remoto Git** :keyboard:

- ```
  git clone https://github.com/username/meu-projeto.git
  ```

Esse comando cria uma **cópia de um repositório remoto em seu computador local**. Um exemplo de uso básico do **git clone** é clonar um repositório do [**GitHub**](https://www.hostinger.com.br/tutoriais/o-que-github):

---

- ```
  git push origin main
  ```

Esse comando **envia os commits do branch local do Git para um repositório remoto**, atualizando-o com suas alterações mais recentes.

---

